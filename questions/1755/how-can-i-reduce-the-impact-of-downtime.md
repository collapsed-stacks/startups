## How can I reduce the impact of downtime?

- posted by: [Matthew Haugen](https://stackexchange.com/users/1325646/matthew-haugen) on 2014-12-26
- tagged: `tech-company`, `customer-service`, `saas`
- score: 6

<p>As I sit here waiting on downtime to be resolved on one of my most-used services, I started wondering: what kinds of things can a business do to ease the customer service hit of unplanned downtime on a SaaS product?</p>

<p>I'm not too worried about the legal aspects of it, since presumably an SLA is upheld. I'm focusing more on the customer service, and keeping people as happy as possible during the period.</p>

<p><em>Bonus points for addressing planned downtime, but that's not really what I'm going for with this.</em></p>



## Answer 1756

- posted by: [Matthew Haugen](https://stackexchange.com/users/1325646/matthew-haugen) on 2014-12-26
- score: 4

<p>I've thought of a couple ideas, but I'm not sure if I love them or not.</p>

<h1>Updated Service Status Page</h1>

<p>The classic solution is to just have a page at <code>/status</code> on which you list out any service interruptions and any updates that come up.</p>

<h3>Pros</h3>

<ul>
<li>It's easy for anyone to pop on and see how it's going.</li>
<li>You can be pretty transparent with what's going on and how long it'll be until it's done.</li>
</ul>

<h3>Cons</h3>

<ul>
<li>You have to maintain the status page, and conceivably even host it on its own server (you don't want your status page going down during a service outage).</li>
<li>You have to spend some time writing updates, and you have to decide how often to do that.</li>
<li>Users have to manually check for status information.</li>
<li>If something is down at a very low level (DNS, that sort of thing), users might not know how to find that status page, even if it <em>is</em> up.</li>
</ul>

<h1>Twitter Status Updates</h1>

<p>This is a more modern twist on the previous solution, and happens to be what <a href="https://twitter.com/stackstatus" rel="nofollow">Stack Exchange does</a>. Essentially, this would entail just tweeting out the same updates as you'd post to your status page, and perhaps link back to that page.</p>

<h3>Pros</h3>

<ul>
<li>It doesn't depend on your servers. This means you can depend on Twitter's infrastructure to not go down.</li>
<li>It's pushed directly to users who are watching Twitter.</li>
</ul>

<h3>Cons</h3>

<ul>
<li>If users don't have or use Twitter, they have to actively check in, just like with a status page.</li>
</ul>

<h1>Email on down and up</h1>

<p>A lot of B2B providers (particularly PaaS) email users when service gets interrupted, then again when it comes back up. This is again typically used in conjunction with a status page of some kind.</p>

<h3>Pros</h3>

<ul>
<li>Unlike with a status page, updates are pushed directly to users.</li>
<li>Users will feel like you're being proactive; they don't have to look for information.</li>
</ul>

<h3>Cons</h3>

<ul>
<li>Depending on your approach to customer service, you might not always want an irreversible record of downtime. In other words, if someone doesn't notice for themselves, it may or may not be ideal for them to read their email post-facto and have a reminder waiting for them that your service can be unreliable.</li>
<li>You have to decide when to push out emails--too early and the outage might be restored very quickly, too late and it's useless. The same applies for saying something is back up.</li>
<li>It only works if people check their email, otherwise, it's the same as a status page.</li>
</ul>

<h1>Phone Reminders</h1>

<p>This is something that I was surprised to learn during the downtime that prompted me to post this, that Microsoft does for Xbox Live. They use a status page, but on it, they allow people to enter their phone numbers to be alerted via a call or SMS when service is restored.</p>

<h3>Pros</h3>

<ul>
<li>Pretty well everyone has a phone (particularly everyone who wants to use my service), and they're probably more likely to hear that feedback than simply getting an email.</li>
<li>Users don't have to check in all the time, and the only important update (it's back!) is pushed in pretty-well real time.</li>
<li>You get some good data on how many users are actively waiting on you.</li>
</ul>

<h3>Cons</h3>

<ul>
<li>There's a fair bit of infrastructure involved in automating phone calls (compared to email, anyway).</li>
<li>I'm assuming most companies will work 24/7 to restore service, so what happens if it comes back at 3:00 am? Do I get a call while I'm asleep? On the other hand, what if I <em>need</em> the service, so I do want a call at 3:00 am? This almost makes it sound like a setting is in order for when not to call, but that complicates things a lot for the user.</li>
<li>A sudden surge in returning users could lead to downtime, but you could scale that by throttling calls out.</li>
<li>You have to be very sure that calls <em>work</em> and phone numbers are actually collected in the first place, since people probably won't keep checking if they're waiting on a call.</li>
<li>People can spoof phone numbers and use your service to annoy other people by putting false numbers in.</li>
</ul>



## Answer 1757

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2014-12-26
- score: 4

<h2>Know that you're down before your users do</h2>

<p>In my experience, the single-most important part of keeping end-users happy is <strong>actually knowing you're down before your end-users do.</strong></p>

<p>It may sound silly and ludicrous. But it's in fact <em>extremely</em> common, not to mention infuriating, for a service provider to become aware that its site or service is down <em>because an end-user told them it was.</em></p>

<h2>Communicate that you know you're down</h2>

<p>Once proper monitoring is in place, how you communicate that you know is basically cosmetic. It can be a status page somewhere (on a different server, of course), it can be updates on twitter, it can be notifications by email or SMS, etc. Matthew has posted a list already. Which medium and the specifics aren't so important.</p>

<p>What really really does matter is communicating to end-users that you already <em>know</em> you're down. You don't want them to inundate you with soul-draining support requests and angry emails and what have you, and you don't want to waste time and resources answering them instead of fixing things.</p>

<h2>Bonus: notify users when you're back up</h2>

<p>In my mind this is mostly a bonus. It can be by email, by SMS, whatever. Make it opt-in (e.g. "Notify me by email when you're back up!") or if doing this on Twitter doesn't seem like it's enough.</p>

<h2>Bonus: explain why you were down</h2>

<p>This is also a bonus in my mind. Users care less about why the service was down than about how fast it was back up. If your audience does care about the former, it will usually be satisfied with high level explanations (e.g. "An excavator slit the telco links while digging a trench.")</p>

<p>If you do this, prefer doing it in a private, clients-only area for the same reason as you wouldn't want prospects to visit a support forum: it can give the wrong impression to potential clients.</p>

<p>Unless, of course, it was a planned downtime...</p>

<h2>Announce your planned downtimes</h2>

<p>For planned downtimes, it's not a bonus. You want to:</p>

<ol>
<li>Explain that you need to be down in advance in a reasonably public place (e.g. the company's blog and Twitter)</li>
<li><strong>Send a reminder to end-users an hour before the downtime if appropriate</strong> (i.e. allow end-users to save their work)</li>
<li>Highlight when the downtime is over in the same reasonably public place.</li>
</ol>



## Answer 1760

- posted by: [Luke Adams](https://stackexchange.com/users/3153675/luke-adams) on 2014-12-26
- score: 2

<p>Hmm, personally I would:</p>

<ol>
<li><p><strong>Get a status page.</strong> Your Startup is probably young, and you NEED to be transparent about outages to keep your users trusting of you. Check out <a href="https://www.statuspage.io" rel="nofollow">statuspage.io</a> (building your own might not be the best idea -- what if everything crashes?). </p>

<p>a. One answer mentioned placing the status page under "/status" of your domain. This is OK, but convention is to place it on a subdomain. (status.github.com , status.trello.com , and many more). IMHO status.yourdomain.com is preferable to yourdomain.com/status simply because the implementation is SO MUCH SIMPLER. The former is simply a DNS record pointing to the server for your status page, while the latter routes to the server that is probably down (you could get around it by using load balancers etc, but that's not fun).</p></li>
<li><p><strong>Find affected users.</strong> If it's a few isolated cases, don't go writing a blog post about your down time. Always post to the status page, and make it clear to users that the status page exists (maybe a "Status" link in the page footer?).</p>

<p>a. Write a notification to those affected. Email is probably the best, but maybe a message on the next successful login would work, too. Depending on what your service is, provide some consolation if you feel it necessary. (For example, if you provide a service that people NEED to get work done, give them a free month of your service).</p>

<p>b. If you DO explain the outage, make sure that it is accurate and honest. Trying to fabricate a story "lol, a cat ate one of our HDDs in the secure datacenter and etc..." makes your company sound like it has no idea what it's doing, while a response like "One of our 10G peering links failed due to a PDU fault causing power to be lost to the router" would go WHOOSH over the user's head, most likely. Find a balance between accuracy and jest, while still taking full blame for it. <strong>Make your users know that you REALLY DO care about them.</strong></p></li>
<li><p><strong>Find out WHY.</strong> Outages = very bad (same with downtime) As a SaaS provider, you <em>really</em> need to have your backend together. Personally I don't use products if I don't think the company can handle my data. </p>

<p>a. Make customers trust you by making downtime nonexistent. I containerize my apps with Docker atop CoreOS which makes rolling updates really simple (nobody ever loses service, but everybody is upgraded). When was the last time you saw Facebook, Twitter or Youtube go down for "planned maintenance"? </p>

<p>b. In addition to having rolling updates, you should have redundancy. You <em>should</em> have multiple geographically diverse (read: not located in the same building) servers, so if one blows up (or a whole rack spontaneously combusts), your users won't notice a thing. Efficient use of Anycast DNS will let you serve requests from multiple DCs. If one goes down, the user gets routed to the next available one (data replication across them can be expensive though).</p></li>
</ol>

<p>Good luck (and great question!)</p>



## Answer 1779

- posted by: [Esqarrouth](https://stackexchange.com/users/3055586/esqarrouth) on 2014-12-28
- score: 0

<h1>Funny/Cute Status Page</h1>

<p>A standard "hey we are down" page with a funny or cute element added on top.<br>
Here are some examples I liked:<br>
<a href="http://www.smashingmagazine.com/2009/06/12/effective-maintenance-pages-examples-and-best-practices/" rel="nofollow">http://www.smashingmagazine.com/2009/06/12/effective-maintenance-pages-examples-and-best-practices/</a><br>
<a href="http://waldowsocial.com/best-unsubscribe-ever/" rel="nofollow">http://waldowsocial.com/best-unsubscribe-ever/</a>  </p>

<h3>Pros</h3>

<ul>
<li>Having a funny or cute status page lowers the disappointment of the users. </li>
<li>Seeing something unexpectedly interesting can get you referrals you haven't been tapping on normal uptime. </li>
</ul>

<h3>Cons</h3>

<ul>
<li>Might have a real negative impact on a serious industry.</li>
</ul>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
