## How is the content of my startup protected from hosting company?

- posted by: [Klaatu Verata Necto](https://stackexchange.com/users/102880/klaatu-verata-necto) on 2016-10-05
- tagged: `legal`, `website`, `data`
- score: 1

I'm working on a project which involves collaboration of various lawyers, who create the content of a portal. For a start I plan to get standard hosting, or in other words not too expensive.

**How am I protected from the misuse of that data by the hosting company?** Are there any laws that protect us or it is simply down to terms and conditions of the hosting company?


## Answer 11291

- posted by: [Jeff O'Neill](https://stackexchange.com/users/46273/jeff-o-neill) on 2016-10-05
- score: 4

Regardless of whether laws protect you (and you didn't specify a country), laws do sometimes get broken by people at the company or hackers may steal the data.

The way to truly protect your data is to have control over the encryption.  I am mostly familiar with Google Cloud services so I'll use that as an example, but I suspect the situation is similar with other cloud services.

The two main ways you store data are (1) as files and (2) in a database.  Google encrypts all stored data for you.  This helps protect you against hackers but doesn't necessarily protect you against a nefarious Google employee.

To be even more sure, you can control the encryption.  

For Google Cloud Storage (files) you can provide an encryption key for Google to use and then Google can't decrypt the data because it doesn't have the decryption key.

For Google Cloud Datastore (database), you can encrypt the data as well, but it is a more manual process as you will need to explicitly encrypt and decrypt data yourself.

You need to be very careful, of course, about where and how you store your decryption key.


## Answer 11336

- posted by: [Jeremy Parsons](https://stackexchange.com/users/497810/jeremy-parsons) on 2016-10-13
- score: 3

The quick answer is, **it's all in the Terms and Conditions**. And commodity hosting is almost certainly offering you a degree of protection (by maintaining systems that are designed not to leak data, if their customer is competent), but very close to zero liability.

But as I understand it, the people with means, motive and opportunity to pass on your valuable data at this stage are your customers. So thinking about ***your* Terms and Conditions** and working out how to **deliver value without creating incentives and easy means for your customers to sell or give that value away** is an area you should be exploring and reviewing alternative approaches in different industries.

So for instance, take online sheet music publishing. I've seen at least three strategies in play:

 1. **Make it easy to steal your property**, in the hope that if it's distributed unchanged that will sometimes generate a sale (if an orchestra plays something, there's someone who's going to check that royalties are paid and only purchased sheet music makes it into the performance space)

 2. **Make it hard to steal your property** (always tough, but there are people out there with software that works hard to drive only a verified dumb printer and only at a quality level that's sufficiently close to the border of acceptability that most scans or photocopies will dip below it)

 3. **Make it clear to your customers and everyone else what they have and haven't acquired** (e.g. including nice and clearly, "This music was purchased as a single printed copy by Ms Irma Strummer on 14 May, 2016 and may not legally be duplicated, scanned or otherwise re-used in any other than its original printed form without express written permission from the copyright administrators, MusicCo on behalf of the author, Mimi Starving" plus "May not be copied" running in light text diagonally behind the musical notes), so that the person who is about to copy it knows they're doing something wrong that hurts another human being.


## Answer 11293

- posted by: [Community](https://stackexchange.com/users/-1/community) on 2016-10-05
- score: 2

Encryption is the way to go if you're storing something sensitive online.

A Generic, Secure Online Collaboration Model
--------------------------------------------

To expand a little, I will give a high-level example of how a generic, secure online collaborative system might work. To keep things simple, we'll assume your client applications are web browsers running a local browser-based HTML+JavaScript application (I'll call this the "browser app") and that the team is running a remote server-based application remotely (I'll call this the "server app").

On one end, a user would create content in his browser. Upon saving the content, the browser app would intercept the content, would encrypt it locally using an encryption algorithm only available to your team members, and then would send the encrypted content to the server. The server would store the content it receives, which has already been encrypted. When a second user uses the browser app to open content, her browser app would download the encrypted content, automatically decrypt the content, and would display the content unencrypyted in the web browser. The second user might make some modifications to the content. When she wants to save it to the server, the browser would similarly encrypt the content locally on her machine and then send the encrypted (now-updated) version to the server. Again the server only stores the encrypted version.

Here's a crude diagram of how this might work:

    [User A's Computer: Viewable Content -> Encyption -> Encrypted Content]    
    
    --- transfer over the Internet --->

    [Server] 

    --- transfer over the Internet --->
    
    [User B's Computer: Encrypted Content -> Decryption -> Vieable Content -> Encryption -> Encrypted Content]
    
    --- transfer over the Internet --->
    
    [Server] 

    --- transfer over the Internet --->
    
    [User A's Computer: Encrypted Content -> Decryption -> Viewable Content]


Costs
-----

You mention that you are using cheap hosting to save money. Hosting costs aren't really the issue in implementing a secure model. The difficulty is having the technology to implement a secure model in an optimized way. You could easily send encrypted content back-and-forth over email in a worst-case-scenario. However, having an online interface with real-time collaboration and a suite of features can enhance the productivity of your team.

Regardless, such a system would not cost any more to host than an encrypted system. The technology that runs the system is the taxing part.

Pick a Trustworthy Host
-----------------------

Perhaps what's most important here is to pick a host you can trust. Unless you are storing content encrypted on the host itself, the host will always have the potential to peak at your work. Finding a host you can trust to be respectful of your content is the easiest solution if you're not dealing with extremely sensitive information. Having such a host would allow you to use a cheap, off-the-shelf collaborative system and all you'd have to do is encrypt the transfers (which is easy relatively speaking).

Alternatively, you can pick a host you trust with an end-to-end solution (like the one Kekito mentioned) to service your collaboration needs.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
