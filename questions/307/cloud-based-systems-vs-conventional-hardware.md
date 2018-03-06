## Cloud Based Systems vs. Conventional Hardware

- posted by: [oharkins](https://stackexchange.com/users/1422371/oharkins) on 2014-08-11
- tagged: `tech-company`, `cloud`, `servers`
- score: 13

What are the advantages of Hosting in the cloud as opposed to buying conventional systems? Is there a difference in the security? Is there a longterm monetary advantage to buying hardware?


## Answer 308

- posted by: [jdero](https://stackexchange.com/users/1972448/jdero) on 2014-08-11
- score: 12

<p>Great question.</p>

<p>I think it's first most reasonable to ponder the size and intended scale of your application. <em>Even if you have big plans,</em> try to estimate where your size will be in the next year or so.</p>

<p>I read this question and immediately think in terms of <em>specialization</em> and <em>optimization.</em> Specifically, in a well run, modular business, it's important to look at your time and money and determine what your best course is. Taking these into mind, I've given you some pros and cons of running hardware vs. using the cloud for your service.</p>

<h1>Cloud Advantages</h1>

<ul>
<li>Convenience: Cloud systems are easy to set up. They require no physical setup, other than a 1 minute purchase. </li>
<li>Cost: You only pay for <em>what you use.</em></li>
<li>Scalability: Jump between different hardware sizes quickly, <em>adapting</em> at the same rate as your growth. More change equals less waste.</li>
<li>Systems stability - you get what you pay for. Reduced variables in setting up a software environment</li>
<li>Security: Buying into a cloud service gives you a packaged security that reduces the number of things you have to worry about. Then again, this also has a flip side, as seen below.</li>
<li>Adaptability: Access to premade boxes (like <a href="http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html">Amazon's AMIs</a>), and ability to save machine images and move them into different environments easily.</li>
</ul>

<h1>Cloud Disadvantages</h1>

<ul>
<li>Downtime: You are subject to your provider's availability. Pretty self explanatory.</li>
<li>Security: the 'public' nature of the service is often a data-breach hacking incentive, since often an entire infrastructure is targeted. Furthermore, you are trusting your data in the hands of your provider (rarely an issue). Again though, you rarely have to deal with these issues, and you have to remember that you clearly have the security service that you are probably paying for.</li>
<li>Large-Scale Cost: Most companies don't get this big, but if you're in the top 1%, there is actually more room for optimization with your own hardware. But I consider this a rare use-case.</li>
</ul>

<p>I'd recommend the cloud. Less variables.</p>



## Answer 309

- posted by: [Matthew Haugen](https://stackexchange.com/users/1325646/matthew-haugen) on 2014-08-12
- score: 4

Here's to this analogy again, it's kind of like buying or renting a house. There are advantages to each, and there are disadvantages to each. I think @jdero hit on the important parts as far as theoretical implementations are concerned.

With the cloud, you get a solid infrastructure that (probably) won't fail out from under you. You pay only for what you actually use, in theory anyway, you can scale with a couple clicks, you don't have to pay IT people, and you can access your information from absolutely anywhere without having to worry about things like failures, or even petty setup issues like firewalls.

With a private setup consisting of your own hardware, you can do a whole lot more (in theory anyway). You can put in exactly the hardware you want (say you need a whole lot of CPU and memory isn't overly important, you can do that), although that's less and less of an issue. You also get to work out software upgrades on your schedule, which means if you have some heavy-traffic event going on, there's no chance your service provider will schedule an overlapping maintenance event (of course, if you set up your cloud system right, that won't be an issue).

But really, when all is said and done, it's just a matter of finances. Hardware is a one-time expenditure. As I said *way back when,* it's like a house. For the purposes of this analogy, we'll pretend you're paying up-front and mortgages don't exist. You can buy a house once, then it's yours to do with what you please. You can upgrade or change it as you wish, but you have to pay to keep it up. On the other hand, if you rent one, you'll be paying more regularly, but you'll also be all set for (some) disasters.

Ultimately, it's a business decision more than a technical one. Would you rather pay a little, a lot, or a lot, a little?

There's a lot the cloud doesn't do right now. Azure SQL Database, for a random and specific example, doesn't support CLR functions. But every few months I see new features pushed out, so I think those sorts of limitations are going away.


## Answer 312

- posted by: [Levi Blackstone](https://stackexchange.com/users/420597/levi-blackstone) on 2014-08-12
- score: 2

This is another example of a business tradeoff that depends on your priorities.  As I see it, here are some of the major pluses and minuses to consider:

**ADVANTAGES**

 1. Service Level Agreements (SLAs) - 
Cloud providers make you a contract-backed guarantee of server uptime. The advantages of these assurances will become more apparent as your company grows, and unreliable service becomes a huge liability.
 2. Scalability -
It's far easier to scale up as demand grows with cloud infrastructure. Plus, it becomes possible to scale up temporarily for periods of high demand. For example, if you are running an e-commerce website, the holiday shopping season tends to bring a substantial increase in traffic, and you want to make sure that your site doesn't buckle under the stress.
 3. Reliability - 
Cloud providers have a lot of domain-specific experience, and are less likely to make hardware mistakes that could ruin your day (or your business) if something goes wrong. Redundant backups and a team of admins at the datacenters means that you should be able to get back up and running quickly in the event of a hardware failure.
 4. Staffing costs -
Choosing to use cloud infrastructure means that you don't have to hire a team to run your hardware on-site. Some providers also offer support for managing your configurations and software, so you can avoid loading your budget down with your own IT staff. 

**DISADVANTAGES**

 1. Security -
Putting your confidential data in another company's hands is a calculated risk. There is always the possibility that your data could be mishandled or accessed/erased in a security breach. There have been [instances](http://searchaws.techtarget.com/news/2240223024/Code-Spaces-goes-dark-after-AWS-cloud-security-hack) of smaller cloud providers being hacked and having all of their customer data wiped out. If you use cloud services, be careful which provider you trust, and have a contingency plan for catastrophic problems (i.e. off-site backups).
 2. Noisy neighbors - 
A major real-world problem with cloud computing is the so-called "noisy neighbor" problem. In most cases, your server will be running as a virtual machine that shares the underlying hardware with other cloud customers. Depending on what the other VMs are doing, you could have unreliable computing and networking performance. There are ways to mitigate these problems beyond the scope of this question, but it is a very common complaint.

Overall, I think the advantages of cloud systems far outweigh the disadvantages for a startup. As much as possible, you want to maintain focus on the core parts of your business (i.e. the product that differentiates you), and cloud services can save you a lot of time, energy, and (at least in the long run) money.

Disclaimer: I work for Rackspace, but these opinions are my own.


## Answer 541

- posted by: [Chase Ouhrabka](https://stackexchange.com/users/4956076/chase-ouhrabka) on 2014-08-29
- score: 0

I would recommend starting with the cloud and expanding to a separate server one you expand. It's low cost and easier to use. Also you can get some very useful analysis that wouldn't be as accessible with a tower type server unless you pay a lot more. 



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
