## Is it risky to use cloud services like Google Docs to host business plans?

- posted by: [Awal Garg](https://stackexchange.com/users/3333488/awal-garg) on 2014-08-01
- tagged: `business-plan`, `security`, `resources`
- score: 38

I am trying to find a safe place to put all the "secret" info of my startup online. I know I can write it on a diary, but, I find it more convenient to write it digitally.

I would also need remote access to them, and thus, I need an internet service.

So, which (if any) is the best, and most secure way to host business plans online, and also share them, if possible.

I'll discuss some ideas I have in my own answer below.


## Answer 155

- posted by: [Matthew Haugen](https://stackexchange.com/users/1325646/matthew-haugen) on 2014-08-01
- score: 33

**Do. Not. Use. Google.**

----

*Preface:* I wrote this whole post about the specific implications for a startup storing sensitive information on their Google services, because this is a Startup-centric site.

There have been concerns about security, and I'm not the best-suited to address those. I believe some other answers here begin to, and if that's your primarily concern, you might have more luck over on [Security Stack Exchange](//security.stackexchange.com) (double-check their scope and for duplicates, of course).

But from a high-level review, I think it's a fairly good bet that Google will keep your content secure, within their terms of service. Of all the companies out there that we hand secure documents, I think Google is likely among the better-prepared to handle breaches.

If that's your only concern, that's alright. But I heavily stress that it maybe shouldn't be, and that's what this answer was meant to highlight.

----

This is a quote from Google's [Terms of Service](http://www.google.com/intl/en/policies/terms/):

>When you upload, submit, store, send or receive content to or through our Services, you give Google (and those we work with) a worldwide license to use, host, store, reproduce, modify, create derivative works (such as those resulting from translations, adaptations or other changes we make so that your content works better with our Services), communicate, publish, publicly perform, publicly display and distribute such content.

*...to **or** through*. That means anything that passes through Chrome, GMail, Google Search, Google Docs, YouTube, or whatever else you can think of there is subject to this.

As we all know, most people don't read these things. And that's all well and good in most cases. But this isn't most cases. I have heard from several attorneys that posting ideas about an invention could limit your patentability. Even though Google would never, practically speaking, disclose your emails or documents, the fact that you're granting them permission to do so would likely be sufficient to make a case against any the validity of patents you apply for. You can't get a patent in many countries if you publicly disclose your invention--in the United States, we're nice enough to give you a year's grace period. That means by posting details about it on Google Docs, you are immediately blocking yourself from getting any protection on that front in most countries, and you're limiting yourself to doing it within a year in the States, which isn't long when we're talking about the process of starting a real-world business.

To be blunt, I've only ever heard of one person actually being aware of Google and defending it for their terms of service. That person was a law school student, and he was extremely embarrassed afterward to hear that all the lawyers in the discussion felt it was frivolous even to consider Google for pertinent documents.

So yeah, don't do that. Other services a bit kinder in their TOS's, but I'd still be cautious, as you say, posting more than you *need* on them.

You'd be best to set up your own server. Particularly through Microsoft's BizSpark program, for many startups you can get Small Business Server for free, and it'll have file sharing and email built in. That way, you can be sure to keep your information *yours* which, particularly these days, is a pertinent competitive advantage in many arenas.

But if we're just talking about which is most secure, I'm sure most you've heard of will be fine. Google won't get hacked, neither will Office 365 or DropBox. It's mostly a matter of personal preference. I tend to like Office 365 because Exchange and SharePoint work with everything, but the gap is narrowing these days anyway. You'll likely also get better TOS's from Microsoft. But again, it's mostly just a matter of personal preference.

**Edit:**

After a relatively lengthy talk with user @jdero, I think it's important to note this: if you aren't worried about your IP or if it's already protected, this all becomes a much less serious matter. I'd be cautious to ever call yourself "protected" since new innovations are always coming up, but if you're sold on what you've got and don't intend to file any more, I'd say it's safe to trust that Google, say, won't email out your business plan to your competitors. So in that respect, it's totally fine. As I said, it probably won't get hacked, and it sure is nice to have around. I just think it's very important that people are aware of the possible implications of posting potential intellectual property to Google. It could be the difference between twenty years of no competition and people immediately reverse-engineering your processes. It's a risk/reward balance, and it should be decided upon for every individual business.

**Yet another Edit:**

User @eggyal brought up another really great point that I think is worth bringing up here from comments:

>You've rather conveniently omitted the preceding paragraph from Google's TOS: "You retain ownership of any intellectual property rights that you hold in that content. In short, what belongs to you stays yours." The licence that you are granting to them is in order for them to be able to deliver their services to you: how can Google Docs enable you to edit a Word document in a web-app unless they have the right to do all of the things in the paragraph to which you object? Moreover, since you very explicitly retain the IP to your work, what on Earth do you perceive to be the threat?

That's a good catch, but not quite to the point. The difference here is what "retaining ownership" means. What Google is saying is that they won't read your invention specs, get excited, then file for their own patents on that invention. And that's very polite of them. However, that does not qualify as sufficient to limit your disclosure. My point is that hosting your data on Google Docs could be argued as a disclosure, not a transfer of your intellectual property.

And while we're on the topic of "retaining ownership," it's an inherent conflict for Google to say, "you can keep all the rights to your IP and give us rights to do whatever you want with it." A significant part of IP *is* having the right to stop people from doing things with your secrets.

**I guess a very important distinction to be made here is that you'll probably get your patent if you post stuff on Google Docs, but the concern is that if someone challenges it down the road, they might be able to invalidate it.** And it's a pretty significant risk for someone to get a patent that might be invalidated as soon as it's challenged. Everything will *probably* be fine, but I still consider this warning well worth putting out there. And yet again, to those of you downvoting this and calling it invalid: these are lawyers' words as well we mine. I'm not a lawyer and none of this is meant to constitute legal advice, but I am paraphrasing what a number of lawyers have said, including a unanimous response on popular forums like the Washington State Bar Association one.

**Edits Galore:**

This is in re to an edit by user @Conner, who quoted the Dropbox terms of service as saying:

>We need your permission to do things like hosting Your Stuff, backing it up, and sharing it when you ask us to. Our Services also provide you with features like photo thumbnails, document previews, email organization, easy sorting, editing, sharing and searching. These and other features may require our systems to access, store and scan Your Stuff. You give us permission to do those things, and this permission extends to trusted third parties we work with.

There's a slight difference here. Before anyone indulges me in that, I'd like to remind us all that this is the *law* we're speaking about: I don't know if any of you have ever gotten a speeding ticket thrown out for not being signed, or if you've watched a murderer go free because the jury just wasn't feeling it. The law is subjective. It's an awesome system we have here in the United States, but, well, it still could use some work.

So yes, to be honest, Dropbox scares me as well. If it were me, I would probably avoid that. As I said way back before this turned into such a controversial matter, I would be inclined to just buy (or get for free through BizSpark if you could) a Windows SBS machine, then use that. It's cheap, reliable, and none of this is even remotely relevant.

But why does Dropbox not scare me *as much* as Google? Framing. Read the language of Dropbox's TOS next to Google's. In Dropbox, they're being very careful to limit the scope to being about you: they need to do these things in order to provide you with service. In the eyes of a patent judge, this would likely deem it a necessary evil. There is no way a business could work in that arena calling any fewer rights than their terms dictate, and they phrase their terms in such a way that supports that philosophy.

Google, on the other hand, is a bit more "selfish" on the matter. Sure, they say "the rights you grant in this license are for the limited purpose of operating, promoting, and improving our Services, and to develop new ones," but if you read the whole thing (or at least this whole section) carefully, you'll find that they're claiming all the rights they need to be able to do whatever they want, and they're leaving it just as open-ended. For instance, do they *really* need the right to "publicly perform" your content? They're grabbing every right they can. And even though it might not have practical negative implications, the law is based on theory.

So unfortunately, that's really the best answer I can serve up at the moment. I hate it, because it's overwhelmingly subjective and it's hard to really read those as regular people and truly see the difference, but that's it: Dropbox limits their rights to what they need to serve you, Google limits their rights to what they need to serve Google. And again, since we're speaking in the arena of a "public disclosure," that line needs to be drawn somewhere.

I suppose a layman's way of viewing the distinction might be like this--and I'm making this up as an example, it probably isn't *actually* how it would go. Dropbox phrases their terms in such a way that they could be considered a business partner; you need to tell your business partner things about your IP so that he or she, or it in this case, can help you grow your business. Google phrases it as a separate entity that benefits from you; I don't mean to make that sound quite that evil, but that's what it is. So by giving your inventions to Dropbox, you're passing them off to an automated partner who can store and share those inventions. By giving them to Google, you're passing them off to a company who reads your documents to build ads and promote themselves to you.

Again, that's just an analogy. Obviously I don't mean to suggest that Dropbox is actually meaning to join your business in the legal sense. But you can see how the terms of service for each suggest a different tone in how they want to use your data, and how that could affect your date of disclosure. And yet again, this is all law, so it's inherently very blurry and subjective, so there's a great chance that you'll never have a problem with any of it. My concern is that the benefits simply don't outweigh the risks.


## Answer 2911

- posted by: [SilentSteel](https://stackexchange.com/users/1092182/silentsteel) on 2015-01-08
- score: 8

Unless these are military secrets or customer credit card numbers, I'd say, just use Google Docs (or any online provider with a good reputation).

 - Venture capitalists and angel investors do not sign NDAs in most cases. 
 - Nor do incubators (see angel.co to apply to them).

Investors are far more capable of stealing your idea, but entrepreneurs trust them every day. Business ideas die more often because of a paranoid entrepreneur than because of someone stealing it.

I've always used cloud providers for business ideas and many of the startup cofounders I know, who have raised tons of money use them as well.

If your mentality is to keep your idea closed, I'd recommend finding startup groups on Meetup.com or visiting a nearby incubator to learn about modern business approaches. You'll find that business success relies on openness, feedback and hard work. It's tons of work-- years of work-- to build up a business, and so it's rare that someone will steal your idea.. They have their own idea and dream.


## Answer 156

- posted by: [DataSmarter](https://stackexchange.com/users/3128474/datasmarter) on 2014-08-01
- score: 6

In short:
**Why not to use your domain + webhosting?**

 - It is **very cheap** (you can have some unlimited webhosting for +/-
   $50/year) - as it is for "private use", you don't need any costly solution for $500/year that supports thousands of users
 - with FTP access, **you can manipulate the files very easily** (e.g. with Filezilla)
 - to have an "internet interface", **you can install a simple Wordpress or Joomla website**. Some webhostings provide the "quick install" where all is done for you - **no technical skills required**
 - e.g. Wordpress has a specific "**private site" plugin** so when someone arrives on the website (like www.example.com) the only thing he will see is the login box
 - the website interface is the simplest for the compatibility between devices

 
Some years ago, it was technically difficult and quite expensive to have your own "internet space". Now, it's the contrary. **It doesn't cost almost anything and it doesn't require (almost) any technical skills.** 

So why to put your sensitive information to someone else? You can have it on your own place. **Nowadays, you can trust only yourself.**


## Answer 252

- posted by: [Math](https://stackexchange.com/users/2225566/math) on 2014-08-05
- score: 3

<p>The chances of an unauthorized access to the document you want to preserve may happen when transmitting as well when storing. That means that the document can be captured when you're sending it via an unsafe connection, because to get to the final destination the document can go across multiple different servers, and if you really care about the confidentiality of the documents you just can't trust that the document will reach the destination untouched. The other possibility is that the document is stored in a host that can be unsafe as well.</p>

<p>In other words, it's almost impossible to guarantee that your files will be transfered around completely safe from human interaction. </p>

<p>Assuming the fact that you can't avoid people to having access to the document, it leaves you the option to make the content unreadable to other people, in other words: Encrypt it!</p>

<p>I, as a software developer, use a control version software called Git, and I put the Git repository contents in a web host as a matter of backup and accessibility. If I were as concerned as you are, I could have used a ready solution that transparently encrypts my git repository with a single command line (after some configuration), and decrypts as simple as the encrypt command.</p>

<p>One of the many possible solution is the <a href="https://gist.github.com/shadowhand/873637" rel="nofollow">Transparent Git Encryption</a> (which I'm completely not involved as developer and don't even know who they are).</p>

<p>Their security concerns are similar to yours:</p>

<blockquote>
  <p>I use git and Dropbox as a reliable, highly available, cost saving and distributed version control solution, and have really found it convenient and effective. One thing that is not addressed in this solution is data privacy/confidentiality. As Dropbox is a third-party data storage service with Amazon S3 as its backend data store, a paranoid user like myself would always be concerned about the Dropbox hosted data being disclosed to others, accidentally or deliberately. After all, putting unconditional trust on a third-party provider never seems to be a perfect rescue.</p>
</blockquote>

<p>If you're not a developer you can make a manual encryption to your files. To do so just zip password-protected a file, several files, or folders. </p>

<p>Zip password-protected files are only breakable through brute-force, so if you choose a strong password you're making the chances of unauthorized access to the content of the document really low. Prefer big passwords, mixing special characters, numbers, upper and lower cases. The strength of your password exponentially increases the difficulty to brute force it, as per the <a href="http://en.wikipedia.org/wiki/Combination" rel="nofollow">combination formula</a>.</p>

<p>The drawbacks are that zipping and unzipping is a boring repetitive process, moreover, big files may make the process long and even more boring yet, therefore, you are subject to eventually leave the encryption aside opening breaches for evil acts. One possible solution is to use a ready-made third-party software that automated encrypts and decrypts your documents, but you may fall again in the uncertainty of the origin of the development of the software. I don't know any, but I believe you can find a reliable tool to do the encrypt/decrypt process. Software are reverse-engineer passive, so if you find a tool that millions say are safe it's likely that at least one decompiled it to verify the integrity of it.</p>

<p>As an easy and ready solution I would say: manually zip password-protected small and really confidential files.</p>



## Answer 153

- posted by: [Awal Garg](https://stackexchange.com/users/3333488/awal-garg) on 2014-08-01
- score: -3

Some ideas I have:

 - Don't use a dedicated service. Just email them to yourselves, and make sure you are using a trusted email provider like Gmail, Yahoo, Hotmail, etc.
 - Use Dropbox, and turn sync between the trusted devices you have.
 - If using Gmail, use Google Drive to store docs and sync instead of Dropbox.
 - If using Hotmail, use Skydrive to store docs and sync instead of Dropbox/Google Drive.
 - Try to keep the information online as limited as possible.
 - Always password protect the docs. (Yes this is possible in Google Drive and Skydrive etc.)
 - Ensure that you are on a secure HTTP<b>S</b> connection. (S = secure). This will prevent any MITM etc.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
