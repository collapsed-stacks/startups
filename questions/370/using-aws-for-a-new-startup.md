## Using AWS for a new startup

- posted by: [George](https://stackexchange.com/users/3516499/george) on 2014-08-18
- tagged: `tech-company`, `united-states`, `startup-costs`, `servers`
- score: 21

Has anyone had experience using [AWS Start-Up](http://aws.amazon.com/start-ups/) for their own company?  Their pricing is very competitive and the massive breath of features offered along with the system/scalability has me nearly convinced to use them for my hosting and data storage.

Has anyone had problems or know about drawback form their free usage tier.  Their free server is not enough for production, but the level above is cheap especially if traffic will start slow anyway.

Would anyone propose a competative to use for hosting and data storage?  [Rackspace](http://www.rackspace.com/cloud/sites/)?  They charge $150/month and might be bought out by a larger company anyway.

I plan on using a LAPP stack (PostgreSql instead of MySQL since I am using the PostGIS spatial addon).  My app was written using Symfony2 and there is a nice bundle for AWS, plus AWS has a detailed guide for configuring a site using Symfony2 specifically.  I think Google has similar detail and I feel that this upfront support will help.  Last thing I want is to run into an error with the web server and have their tech support tell me they do not support using Symfony2.

PS - Is it possible to have AWS and hosting added as Tags?  Not many tags are available.

**Update**
After a few more months of development, I reviewed hosting and went with AWS, but Rackspace has nice features and probably better support.  I chose AWS because of their configurations and even though it was a steep learning curve, I like the control I have over the server and pricing is the cheapest, but not drastically cheaper than other services.  My database has close to 1 million rows now and I do expect up to 1,000 simultaneous users at peak and I think AWS was easy enough to scale as users connect and scale down after peak time is over.

**Update June 2015**

I launched my company a few months ago and while I have not had a large spike in traffic, all of the AWS services work very well.  There is a steep learning curve.  I use EC2 with a Load Balancer, Elasticbeanstalk, S3, RDS, Route53, SES, and VPC.  There are actually several services I am not using to keep things _simple_.

Even though these are a lot of services, they do work well together and I think in the end you can save a lot of money by paying for the services you need and easily adjust if changes are needed.  There is a large community of users that have posted on aws forums, stackoverflow and other exchange sites.  I have been able to solve all of my problems by using this community and that's a big advantage.  I will keep using AWS for a while and if I have to switch, it will be a major rebuild.


## Answer 384

- posted by: [SilentSteel](https://stackexchange.com/users/1092182/silentsteel) on 2014-08-19
- score: 11

<p>I have used AWS, although it was after the startup phase.</p>

<ul>
<li>AWS is way better than using your own hardware / dedicated server. Hardware takes tons of time, money to maintain.</li>
<li><p>However, I would recommend using <a href="http://parse.com">Parse.com</a> or Google App Engine instead. The reason is, these 2 services offer a lot more out-of-the-box. (I know you want to use PostGIS so not sure if it's relevant.)</p>

<p>Amazon is comparatively very bare-bones compared to, say, Parse.com. With AWS, you still need to manage virtual servers, databases.. There's tons of different services; you're knee deep in EBS volumes, CloudFront, SSH Keys, S3, etc.</p></li>
</ul>

<p>At the beginning, focusing on a killer front-end product experience will take all your time. If there's a service that has a more managed backend, go for it.</p>



## Answer 373

- posted by: [ErstwhileIII](https://stackexchange.com/users/2320529/erstwhileiii) on 2014-08-18
- score: 10

<p>I need to revise my post (originally made in 2014) in the light of new options. While Amazon Web Services (AWS) remains quite useful, you should also check out Google Cloude Services and, in particular, the Firebase 2.0 recently announced at Google I/O 2016.  This offers the option to make and deliver a variety of applications at a free tier that can also grow .. without forcing you to code a backend service to get anywhere. A reference is here (<a href="https://firebase.google.com/" rel="nofollow">https://firebase.google.com/</a>) but you can "google" firebase in case that link ever goes dark).</p>

<p>Here is my original post:
I have worked with several startups that used AWS ... the reasons included the following:</p>

<ul>
<li>Ability to expand beyond free usage tier easily</li>
<li>Ability to drive start-up in one direction, find it was wrong, and redirect without having long term commitments to particular hardware / software</li>
<li>You could also take a look at the hosting / storage offered by the Google Cloud Platform (their March announcements and storage price reductions helped spur reductions by Amazon). See <a href="https://cloud.google.com/" rel="nofollow">Google Cloud Platform</a></li>
</ul>



## Answer 391

- posted by: [JezC](https://stackexchange.com/users/87431/jezc) on 2014-08-19
- score: 5

I've been using Heroku. DB is free for up to 10k rows. Free email (300-600 messages/month). Various other free services, including scheduled DB backups. 750 hours of compute time per month for free (or one webserver, plus about 10 hours of worker server time, enough to do a fair amount of background processing per day - 10 minutes should be enough to do most reasonable things with 10k rows of data). Upgrade to 10M rows for $9/month. Be smarter about when you have the webserver running (shut it down automatically each night) and you can get more compute hours in your free allowance. When it comes time to scale, `heroku scale web=2` and you've doubled your webservers. 

Unless you're deeply into managing the tech, I wouldn't go the AWS route. It is fantastic if you know you want to deal with the details. But if your business is about the service and the service isn't about webservers and computations, and routings and so on... try to find a way to ignore those until you can build enough value to hire a team to take care of it. That'll be quite a sizeable business, I should think. Hosting is cheap. $35/month or so, per webserver. Takes a lot of webservers at $10's/month per server, before adding a staff member will save money.


## Answer 393

- posted by: [Levi Blackstone](https://stackexchange.com/users/420597/levi-blackstone) on 2014-08-19
- score: 2

You asked about alternatives to AWS, so I'll mention Rackspace's [Developer+](https://developer.rackspace.com/signup/) program. It's a 12-month infrastructure credit geared towards developers wanting to test out their software at scale. They also have a [startup program](http://rackspacestartups.com/) that you can apply for that offers some sort of credits for using their infrastructure. 

Just to clarify, Rackspace doesn't use AWS; they have their own infrastructure, but they are geared towards managing your servers for you rather than just providing the infrastructure. As such, the prices are somewhat higher, but it's including a lot more support. It's up to you if the price difference is worth not to have to manage everything yourself. (For a startup not wanting to worry too much about IT,  I'd say yes).

Disclaimer: I work for Rackspace, but this information is not endorsed/paid for by them.


## Answer 4023

- posted by: [Dmitri Zaitsev](https://stackexchange.com/users/1769946/dmitri-zaitsev) on 2015-04-16
- score: 1

<p><a href="http://Parse.com" rel="nofollow">Parse.com</a> mentioned here is much more developer-friendly than AWS, has clean documentation and complete cost control with very generous free tier. Reading their Doc is a joy, whereas I would need to hire an assistant just to <strong>read</strong> their bloated pages and decrypting the (insane) cost structure.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
