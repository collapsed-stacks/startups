## Why do startups move off Backend-as-a-service (BaaS)?

- posted by: [Ali Al-Ebrahim](https://stackexchange.com/users/5182176/ali-al-ebrahim) on 2014-10-15
- tagged: `mobile-apps`, `web-development`
- score: 17

Many startups initially build on a BaaS platform such as Parse, Kinvey, or Kii, but some move off.

Why do businesses move off these services? For instance, was it cost, inflexibility, something else?

**Context:** I'm cofounder of a startup that is adding a new spin on BaaS, and we want to make sure our new spin adds enough value to encourage startups to start with us and stay with us.


## Answer 1028

- posted by: [Jeremy Parsons](https://stackexchange.com/users/497810/jeremy-parsons) on 2014-10-17
- score: 24

BaaS typically solves three problems and introduces two. The way these problems play out over time and scale creates an "exit arc" for developers.

**Solved Problem One: Pace**

Just about every startup project I've been involved with kicks off with a session where you go through your target feature set and ask, "what can we grab that does that for us?" Along comes BaaS offering to tick lots of boxes, and I'm in!

*But* that's an early days problem, at least for apps that achieve success. You only have the problem of "how do we get to v1 fast, cheap and with minimum risk" once.

**Solved Problem Two: Alignment**

If you want to deploy into multiple ecosystems, it's hard to stay aligned. There are lots of offerings out there promising some level of "make once, run everywhere," but the compromises these involve are sometimes unacceptable. Your favourite apps are almost certainly being developed native.

BaaS moves the multi-platform focus from front-end user experience to the vital, invisible back-end. If our iOS and Android apps are consistent under the hood, it's easier to stay in sync and it's less likely that we'll get bogged down with platform-specific issues.

How does this problem play out over time? Every time we're updating, we'll hit that problem, so a great BaaS offering ought to help on these occasions.

Thinking about a startup, if you're in a high-impact, highly competitive consumer space then this problem is going to come back again and again. If your objective is to hit more of a steady state where the initial effort to build an app and build an audience is followed by minimum cost and effort to maximise return, then alignment isn't a recurrent issue.

**Solved Problem Three: Reach**

Most startups will do better if they can deliver on these three measures for their users:

1. My app makes things happen that I want to share

1. My app works better and better the more my friends use it too

1. My app goes everywhere I want it

If your startup was designed around an idea with strong inherent virality, BaaS will help you build fast and uniformly, but we've already covered those above, so there's no clear additional benefit.  However, most startups - mine included - start with a local problem, or a cool possibility, or a pragmatic goal, or any one of a whole range of possibilities that probably aren't inherently viral - even if they hit one or two of those three measures.

Because BaaS majors on bringing virality enablers such as identity management, social integration and cloud storage into easy reach, it's way easier to start experimenting from the get-go, and good BaaS offerings tend to lead you into good practices.

How does that problem play out over time and scale? Well, if the pace problem is mainly about v1, the reach problem starts at v2 and goes on until you get it right. BaaS delivers some additional benefit after that point - the real, if mundane, problem of keeping lots of interfaces current. 

*So much for problems solved.* Now, what problems get added when you use BaaS?

**Added Problem One: Blunting**

BaaS makes your life easier by letting you stand back from the fine detail, so you focus on what you want to achieve, not so much on how to achieve it. Who wouldn't want that?

As a startup, you're constantly looking for opportunities to stand out, so you get attention, to break through a competitive field, to make bold claims that are an impossible stretch for others.

Current BaaS platforms have different strategies for trying to keep out of your way when you need something they don't give, but the first time you find yourself developing a workaround, the shine has gone.

If your BaaS has true lock-in, then guess what? Next time, you're not going to use it. And if it doesn't, then while changing is a hassle, it's a clearly-defined, manageable project.

What's the timeline here? Most startups will never hit that moment at all. But they'd like to...

**Added Problem Two: Taxation without Representation**

If you're looking at a commercial BaaS, then as soon as you get modestly successful, fees kick in. That's not a problem if the cost ties up neatly with both the value to you, and revenue from your users, advertisers and others. But it *probably* doesn't.

Your BaaS is going to have to charge you for something it can measure, and it can't directly measure either the value it's giving you or your revenue. The App Store can do that in part at least, but your BaaS provider can't. So the fees you pay won't line up perfectly with your business model, and the management tools to help you control the fees will typically degrade user experience when your capping measures kick in.

In a competitive market, this ought apparently to even out in the long term: don't choose a BaaS provider whose revenue model cuts across yours. But in the startup world, monetization is often the biggest exercise in guesswork, so how do you pick?

Unsurprisingly, commercial BaaS continually gravitates towards the corporate customer, and towards companies focused on B2B. That's nothing to do with the *benefits* BaaS delivers, but it's *everything* to do with cash flows.

**BaaS: The Best of Businesses, the Worst of Businesses**

There are surely few tech businesses where there's as great an opportunity to delight your users as BaaS. Your customers drop their problems on a table, and you sweep lots of them up.

Your startup customers love you, but they won't be loyal to you. Entrepreneurs are creative, determined opportunists. So the day you're no longer solving important problems, you'll appear on some Trello board. And the day you start to get in the way, the writing is on the wall. So you can get high market penetration with unsuccessful startups, and high churn with successful ones. Like BizSpark before you, you'll find it's hard work but achievable to give away freebies to startups, but oh so dangerous to forecast future revenues.

And that's not the only squeeze you face. If you are creating back-end capability, then you're competing with some very deep pocketed providers. If you are only helping hook apps in to other services, you have to race hard to keep up with changes or your proposition is dead in the water.

For those reasons and others, open source BaaS componentry and (reasonably) complete systems are coming through pretty fast, which further constrains the opportunity for you.

So how would you delight and retain me in future projects? Here's my wish list for a startup-friendly BaaS partner.

**1. Dig deeper and deeper into getting me *fast* to an *awesome* v1**

No, I won't reward you by sticking with you forever if that's all you do. But I'll sit very happily in the top of your funnel, which is good for you.

**2. Don't stop at half the job: I want a growth and monetization back end**

Every startup wants to grow. Every startup wants to make money. But nobody has a formula for guaranteed success. As a BaaS, though, you can get an objective aerial view of what's working now. Don't get too obtrusive, but do gather data, learn from it, and pass the learning to me. Tools I can use are great: thank you. But learning I can apply fast is golden.

**3. Collect a share of my profit, not a return on my cost**

Yes, I get that you want to collect a subscription revenue. And yes, I get that when I use a lot of your services, you want to get paid. But seriously? Those are your problems, not mine.

So when you teach me that a push notification costs me money, what do you expect me to do? First, I'll be cautious about using push notifications. Second, when I see an indirect return, I'm not more motivated to stick with you, I'm even more motivated to go elsewhere and pay less, or preferably nothing.

If I've sold that push notification, then the picture changes completely. If you can manage that for me so that you keep some of the money I make, I'm happy. Yes, I'm still going to be open to better deals, but if you've eliminated the risk that you get paid when I don't (or long before I do), I'm thrilled.

Mostly things aren't quite that simple. There's probably nobody waiting to pay me to send out a push notification, but for most of us startups, there are only so many ways we get paid - app sales, subscriptions, in-app advertising, in-app purchases, out-of-app advertising covers most of it.

If you cover 90% of what I need, and expect to make your money *when* I get paid and out of *what* I get paid, we're on the same side.

You'll have to protect yourself - I get that. So I don't expect that you'll give me truly unlimited service on a no earn, no pay basis. It's just that I respond better to the carrot than the stick. 

So if you solve my pace problems, help me not just to v1 but to scale and monetization, and avoid creating misaligned financial penalties, Startups who think like me will choose you, and stick.


## Answer 3866

- posted by: [chelder](https://stackexchange.com/users/1234525/chelder) on 2015-03-26
- score: 1

<p>I don't think Startups move off BaaS if BaaS are open source. I recommend to use a BaaS if it has a big community behind. However open source BaaS are not so well established as the commercial ones yet. That's why I believe most developers doubt to use them nowadays.</p>

<p>I have done a little research about some open source BaaS. For example, I have searched on Google <code>Dreamfactory BaaS</code> or <code>usergrid BaaS</code>. Thought it is not a very scientific research, I hope is a quite valid way to know which is the most mature one:</p>

<ul>
<li><a href="http://www.dreamfactory.com/" rel="nofollow">Dreamfactory</a>: 86,000 results. PHP server.</li>
<li><a href="http://usergrid.incubator.apache.org/" rel="nofollow">Apache Usergrid_</a>: 6,640 results  </li>
<li><a href="http://deployd.com/" rel="nofollow">deployd</a>: 3,460 results </li>
<li><a href="http://www.baasbox.com/" rel="nofollow">BaasBox</a>: 4,390 results</li>
<li><a href="http://sockethub.org/" rel="nofollow">sockethub</a>: 1,460 results</li>
<li><a href="http://hood.ie/" rel="nofollow">Hoodie</a>: 45,400 results</li>
<li><a href="http://helios.io/" rel="nofollow">Helios</a>: only iOS</li>
</ul>

<p>Not a BaaS but with the idea of minimizing the time of doing the backend in its core:</p>

<ul>
<li><a href="https://www.meteor.com/" rel="nofollow">Meteor</a>: 34,900,000 results. <a href="http://davidwalsh.name/meteor-frontend-engineers" rel="nofollow">It is not a BaaS. Unlike other Js frameworks, it runs both on the server and the client, meaning you can manage your whole app with a single code base</a>.</li>
</ul>

<p>Notice I'm beginning to research about those technologies, so you better don't take this research too much seriously!</p>



## Answer 3876

- posted by: [Brad Rhoads](https://stackexchange.com/users/42121/brad-rhoads) on 2015-03-27
- score: 1

<p>Two more related issues: </p>

<ol>
<li><p>What if you suddenly go out of business or have a significant
failure? I've been a victim of that in past.</p></li>
<li><p>What if my data isn't accessible the way I need it to be?</p></li>
</ol>

<p>The best way to mitigate both of those concerns is to make a backup of my data available to me on a daily basis.</p>

<p>For example, checkout <a href="https://www.teamwork.com/" rel="nofollow">Teamwork</a>. I'm able to go in and request a complete backup of my data and download it to my local machine. Then I load it right up into my own MySQL system to do some reporting that Teamwork doesn't provide.</p>

<p>What they could do better is allow me to have the backup scheduled to happen automatically and put the output into a directory that I can ssh into. Then I could completely automate the process. (Seems like a feature that could be in a pro version.)</p>



## Answer 8774

- posted by: [George Batschinski](https://stackexchange.com/users/7970616/george-batschinski) on 2016-03-19
- score: 0

There are several factors startups move off from BaaS – Backend As A Service solution. The more common are: 

**Source Code Access -** Most of the BaaS companies do not provide access to the application source code and developers are locked forever on the platform. Parse ( Parse.com ) shut down clearly represents how developers rely on the BaaS providers and are dependent on them. Because of Facebook decision to shut down Parse platform thousands of developers have a huge hassle to migrate the apps to a new provider. Unless customers have complete access to the database and source code the more the startup grows the more dependent they will be on a BaaS provider. This factor only can be seen as a risk for the startups founders and investors. It is extremely important for the startup technical team to have continuous access to the source code generated by the BaaS provider and flexibility to host the service wherever it is more adequate. New BaaS players, such as, Back4app ( www.back4app.com ) have a new approach and allow developers complete access to the source code and integration with Git repositories. 


**Costs –** The more a Startup grows higher will be the BaaS charge for the service provided. The most important metrics for charging a startup are API requests and total storage. Some BaaS websites are quite confusing and it is real challenge to understand how much will be the total charge on the end of the month.  Some startups do not take in consideration the recurrent and growing costs of the BaaS provider. I do strongly recommend to clearly understand how the service is charged before using any BaaS provider and also simulate at least a one-year simulation to project how the cost structure will look like. 


**Reliability –** As soon as the Startup start to grow more complex the application will become. Considering the BaaS is a relatively new market not all BaaS providers are prepared for these level of complexity and large quantity of users. So, the BaaS hosting service becomes unstable or slow jeopardizing the Startup business. This risk can be mitigated by an initial research of which providers are more reliable and adequate for Startup long run plans. 



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
