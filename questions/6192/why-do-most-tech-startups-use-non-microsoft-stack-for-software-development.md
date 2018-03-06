## Why do most tech startups use non-Microsoft stack for software development?

- posted by: [Steve](https://stackexchange.com/users/6168451/steve) on 2015-08-27
- tagged: `startup-costs`
- score: 9

My understanding is that most startups choose non-MS stack for software development. Why? I think they choose to do this to keep costs low. But is it really any cheaper?

Lot of opensource projects start out as free so as to gain lot of users and so that creators can get lot of visibility within and outside their company, but when the projects start getting used a lot, many creators start their own companies which now charge money to fix all the problems caused by their opensource projects.

The other thing with a non-MS platform in today's world is that there are just too many choices to choose from esp. on the backend and in big-data processing. You pick anything and there will be some 20+ open source projects/technologies/databases to evaluate. It becomes overwhelming.


## Answer 6193

- posted by: [Alain](https://stackexchange.com/users/21866/alain) on 2015-08-27
- score: 12

You should choose the stack that your technical team is familiar with. The early days of a startup are not the time to discover new technologies. So if your team comes from a Windows background, stick with it.

StackOverflow is a great example of Windows-based startup. But yes, a lot of startups choose Linux and open source instead, and no, they don't have to pay after a while (unlike with Microsoft BizSpark program).


## Answer 6197

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-08-27
- score: 6

Seconding Alain's voice as well. Just answering to add that:

> I think they choose to do this to keep costs low. But is it really any cheaper?

Actually, that's not why they choose non-MS. But if you really must know, it is cheaper.

The reason they choose it is because open source developers tend to be *nix savvy. If you're developing in a non-MS language, well... sure you could do that on Windows, but the truth is your server is *nix in a way or another and it's going to be running Apache or Nginx if you're building web apps. So you might as well do the same on your work device. (Never mind virtualization.)

As to OS X/Darwin, which you bring up later in your question, it's what OSS devs tend to use in order to avoid the grueling task of configuring a Linux or Windows laptop - or indeed desktop - to make it functional enough to get work done. Not all of course. But Macs give those that use them the benefits of a BSD-like Unix platform with the "it just works" comfort of OS X.

As to cost, it actually is A LOT cheaper. Every developer hour not wasted on fighting with their computer must be factored into your calculation of cost vs benefit. And [they *quickly* add up](http://www.loopinsight.com/2015/08/06/why-am-i-a-mac-user/). If your developers want Macs, don't hesitate and give them some. Because they mostly just work.


## Answer 6222

- posted by: [Mischa](https://stackexchange.com/users/4832404/mischa) on 2015-08-30
- score: 3

<p>(This is just an addition to the accepted answer :)</p>

<p>While knowledge of the development stack is important to make progress fast - it is also important for a startup to foresee the costs in the future, when it has to scale the product/service.</p>

<p>While it is possible to foresee the increase in costs for OS servers/dbs, it is hard to do so with the MS ecosystem.</p>

<p>So heres the anecdote:</p>

<p>Few years ago - at university - i had to write a business plan for a <em>tech startup</em> with a long term finance plan (this is scrying, i know.) But i had to consider real costs (like renting offices, paying employees ...) for an exponentialy growing product for three years.</p>

<p>So I tried to figure out how much a MS Server 2012 + MS SQL 2012 would cost if you need multiple instances - and you know what, its like impossible because they have really <a href="http://www.microsoft.com/en-us/server-cloud/products/sql-server/purchasing.aspx" rel="nofollow">curious pricing plans</a> (like pay per Server, per Instance, per Core etc.)</p>

<p>So on the one hand (i.e. with linux + mariadb) you have costs for the machines and the staff - and on the other hand you have costs for the machines and the staff and the licenses, which for some setups can become more than for the actual machines and staff.</p>



## Answer 6205

- posted by: [David Mulder](https://stackexchange.com/users/507061/david-mulder) on 2015-08-28
- score: 2

First of all, in regards to the other answers: Yes, speaking with your tech team makes sense, except I hope/assume that this choice is being made before hiring an entire team, so it's quite a reasonable question.

Now, to get to your actual question(s): You should consider Microsofts offering just one of many. You are arbitrarily drawing a line between the 'peaceful hypermarket' that is Microsoft and the 'crowded marketplace'. In reality they are all located on the same super crowded market and you simply have to choose the best tool for the job. Where you seem to consider it a luxury that you don't have to evaluate choices when using Microsoft, the huge downside of that is of course that there are no choices in the first place.

Now, regarding your idea of open source projects being lures to get you to pay up: that's simply incorrect. The majority of open source projects starts simply because people are passionate about an idea. Next the project grows to the size where companies want high quality support and somebody decides to fill up that hole in the market (which is often the developer, but just as often somebody else entirely). In my experience for small and mid-sized companies the support delivered by 'the open source community' actually outperforms the entry-level standard support provided by commercial companies. Is that a strict rule? Definitely not, but it's been quite a consistent trend.

And lastly you ask about buying consumer machines: Well, first of all this is *really* something best decided by your employees. I mean, ignoring special businesses requirements and technically capable employees people tend to be far more efficient using the software (IDE, OS, etc.) they are used to. Beyond that $1500+ laptops are *far* more than you need in virtually any job (barring special requirement, but in most of those special requirements desktop systems make a lot more sense and those are *far* cheaper). I mean, as a developer I could probably do *most* of my work even on my $300 dollar laptop (though I of course prefer my overpowered $1000 desktop system).


## Answer 6194

- posted by: [Jeff O'Neill](https://stackexchange.com/users/46273/jeff-o-neill) on 2015-08-27
- score: 1

I second Alain's point about talking with your technical team.

Development machines are a great example.  I know a ton of software developers having recently been at one of the largest tech companies (not Microsoft or Apple).  For laptops, mac books are far and away the most preferred.  For desktops, linux boxes are the most common.  Few developers to want to use Windows for coding (unless you are building Windows software).  I can't imagine any developers wanting a touch screen for writing code so I wouldn't consider that as a factor.

Also compare hardware prices to employee salaries and productivity.  A cheap developer gets paid about $2000/week.  Give them the computer they want, I bet they will easily be 10% more productive.  You'll cover the extra cost of a mac book in two weeks.



## Answer 7509

- posted by: [Bogdan](https://stackexchange.com/users/7093266/bogdan) on 2015-10-09
- score: 1

Because of its propensity for self-serving standards, closed-loop development components, and enormous scale, Microsoft has in the past seemed to have created an ecosystem which it hoped developers would never leave.

This has caused two very critical issues:

Your "average" Microsoft developer is often crippled by this ecosystem when dealing with any non-Microsoft technology.  I've found fantastic .NET developers who were incapable of integrating Javascript frameworks and other technologies -- insisting, instead, on using .NET "components" to accomplish tasks.  While I'm absolutely convinced there are proficient, expert developers who use Microsoft technologies as well, I've found anecdotally these are very difficult to find (and I've never met one).  Thus your development cost can be much higher than you expected and your flexibility to adapt constrained more than desired.
Many folks have been burned by the "standards" implemented by Microsoft -- with everything integrating so nicely, it's very easy to fall into the trap of believing you're working along a standard.  When you suddenly need to integrate with something else, you can get slapped pretty hard.  Configuration, integration, compilation, and execution are great when you stay within the ecosystem, but once you stray even a little, you face all kinds of challenges. Some are death by a thousand mosquito bites, while others are huge glaring walls of stone.


## Answer 13306

- posted by: [Francois Lanthier Nadeau](https://stackexchange.com/users/9879243/francois-lanthier-nadeau) on 2017-09-07
- score: 1

<p>Microsoft or not isn't really the question to ask here. At least not the first one. In reality, when launching a startup, your time-to-production as a developer will play a huge role in your potential success. You need to iterate quickly on MVPs and different features to scale as fast as possible to product/market fit. In that sense, the question becomes: what's the technology stack that'll allow you to do just that? <strong>The one you're most familiar with is the answer</strong>. A simple filter, huh?</p>

<p>Once you're successful (read: traction, steady growth, revenue, etc.), you can start looking into progressive refactoring using trendier techs. But business imperatives will always trump technical preferences. We've got a post on <a href="https://snipcart.com/blog/startup-tech-stack" rel="nofollow noreferrer">choosing, keeping &amp; refactoring your tech stack</a> if you want to dig deeper.</p>

<p>As for the Microsoft part, I believe there's a widespread but fading belief that MS is a closed, cluttered ecosystem forcing you to work on Windows. Truth is MS has released Visual Studio Code, a lean, lighter code editor liked by many. It has made VS available on Mac, too. .NET Core also solves many of bloating issues often cited. The MS open source ecosystem is getting stronger and stronger, and .NET is a solid, reliable framework to build web apps. Microsoft even offers a startup program called Bizspark to facilitate launching a SaaS using their tools. At Snipcart, our lead dev and co-founder was initially familiar with .NET, so we ended up working and scaling with it (<a href="https://snipcart.com/blog/why-dot-net-technologies" rel="nofollow noreferrer">more details here</a>).</p>

<p>If you look through [StackShare.io][3]'s entries, I'm sure you'll find more "boring" and MS techs than you'd have thought. :)</p>

<p>Hope this helps!</p>



## Answer 6203

- posted by: [breb](https://stackexchange.com/users/6860829/breb) on 2015-08-27
- score: 0

Forget the MacBook Pro, real developers want a huge screen like the iMac with Retina 5K display, it's in the same price range. Usually we're not hackers on the run from authorities. :P

And don't forget the time you save not cleaning your touch screen!

MS-products used to be a lot more expensive, but prices are falling there too. Just let people pick what they prefer, makes no sense to use better tools or cheaper ones if they can't work with it.

Btw, Windows runs native on Mac-hardware too if needed, but rarely in the other direction. Non-Mac-Software like Android Studio or Eclipse runs a little clumsy on Mac, there I would use a Windows OS. For iOS development you need a Mac, and so on.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
