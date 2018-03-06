## Strategy for multiple email addresses?

- posted by: [dwjohnston](https://stackexchange.com/users/1068606/dwjohnston) on 2017-01-25
- tagged: `brand`
- score: 1

Apologies if this is off topic, this is really a question about branding. 

I work full time in IT, but more recently some of my side projects have been gaining more traction. 

I have: 

- A ['Humans of' Facebook page.][1] 
- A [political/relationships blog][2]. 
- An [interactive geometric art webapp][3]. 

I'm wanting to generally consolidate these projects under a full stack web and media development umbrella. ie. selling my services as a someone who can implmement a full social web strategy, with particular emphasis on the web development. 

The question I have is about email addresses. 

For example with my blog, for research purposes I might want to be emailing various people for information, and in that scenario it would be good to have a @eyesofablacksheep.com email address. 

I don't have a domain name for my Humans of Newtown page, and at this point I don't particularly want one - but I do need a Humans of Newtown email to add to my business card. Currently I'm just using a gmail address - but is that unprofessional. 

The question is - is there a way to set up multiple email addresses without having to pay separately for each one? - Given that I'm not currently earning money from these side projects, these costs quickly add up. 

  [1]: https://www.facebook.com/humansofnewtownwgtn/
  [2]: https://eyesofablacksheep.com/
  [3]: http://blacksheepcode.com/


## Answer 11994

- posted by: [Jeff O'Neill](https://stackexchange.com/users/46273/jeff-o-neill) on 2017-01-26
- score: 2

It is straightforward to get a custom email address for very low costs.

You need to purchase the domain name, which is about $10/year.  I recommend doing this at Google domains.  I'll use mydomain.com as an example.

Google domains allows you to set up forwarding addresses so you can forward emails from john@mydomain.com to another email account, such as your personal gmail account.

You can also set up your gmail account to send emails as if they are coming from john@mydomain.com.  When you send an email with gmail, the from address will be a drop down menu so you can select the address to be used to send the email.



## Answer 12013

- posted by: [AlyssaFox](https://stackexchange.com/users/10062862/alyssafox) on 2017-01-29
- score: 0

I'm also in tech. If I was in this situation I would use AWS as my DNS server. Then create the e-mail addresses I want to use. This can be done by configuring an email address that looks the way you want but points to an address you already own. This process is called creating an Alias. For example, say you want jack@blackgoat.com and you own the domain but don't want to pay for another server to house emails for a new address. Simply use your AWS instance that manages your domain and configure an email with that vanity which points to your existing gmail account. Low cost no fuss. 

Hope this is helpful! 


## Answer 12051

- posted by: [Daniel](https://stackexchange.com/users/7592784/daniel) on 2017-02-06
- score: 0

Obviously, you cannot get around buying the domain names for each entity you wish to have an email address for: @eyesofablacksheep.com, @humansofnewtown.com etc.  

But one would think you will also need at least one website for the umbrella entity.  And you might want more than one email address per domain name, sales@, info@, support@ etc.

In order to have the over-all lowest cost, perhaps you should look at a cheap web hosting plan and get the benefits of many things for one cost.  For example, at this moment GoDaddy is offering basic hosting for $3.99 per month. For $47.88 you can get one year of web site and email hosting, and you'll get one domain name for free.

Now you can add the Humans of Newtown (or the umbrella name) domain for free, you can host a website, and you can set up many different email address for whatever domains you have. 

I'm sure there are also lower cost alternatives than GoDaddy.  I have clients that use that platform, so I end up spending a lot of time there. 



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
