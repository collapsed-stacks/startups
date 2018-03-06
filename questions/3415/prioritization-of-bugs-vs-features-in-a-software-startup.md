## Prioritization of bugs vs features in a software startup

- posted by: [Esqarrouth](https://stackexchange.com/users/3055586/esqarrouth) on 2015-02-13
- tagged: `tech-company`, `lean-startup`, `agile`
- score: 2

Adding new features before the bugs of an old feature is somewhat fixed is basically regarded as bad practice in software development. Every bug you leave unfixed will cause problems in new features, will take longer to solve later cause you forgot what it was, put you in a lot of technical debt. 

On the other side startups should focus on learning what features the customers need and ship as fast as possible, iterating as much as possible.

The key here would be saving time, learning early what the feature should be will save time but fixing bugs early before introducing new layers of programming will also save time. 

So how should we prioritize between bugs and features in software startups and find a balance that works? 


## Answer 3416

- posted by: [Matthew Haugen](https://stackexchange.com/users/1325646/matthew-haugen) on 2015-02-13
- score: 4

Interesting question. I think there are a few main issues to take into consideration when you're establishing this stuff. Some of these are a tad coupled, but keep with me.

**TL;DR:** Contemplate the headings, and you'll get the gist of what I'm trying to say.

I've taken lately to putting my conclusion at the top of posts, so here's that:

I'd like, per usual, to give you a numerical answer, and perhaps there's research out there that can give one, but I think once you contemplate each of these questions, you'll be able to get a pretty good feel for whether a bug is worth fixing or not.

One approach that I've always liked is the simple one: work on bugs you know about that are actually hurting someone, and for new features, just stick a "beta" tag on them. That works really well on websites, particularly. If you can launch with a base product, then add modular features with "beta" written parenthetically next to the name, you'll attract just the right type of people to them. I think most people who use the apps we care about these days know what a beta is, and know what it means (subject to change, subject to bugs, etc.), so if someone is afraid of that, they'll just shy away.

Of course, if a bug actually *does* have an impact on other features that you plan to develop, it's probably right to fix it then and there. Most of what I'm talking about are minor bugs that people hit once in a blue moon, and aren't super critical to the workflow of average, or at least important, users.

Admittedly, on a more personal note, I haven't had a ton of experience with the "technical debt" that people often talk about with this stuff. I definitely take a liberal approach with features versus bugs, but generally I don't come across coupled behaviors enough that make bugs pile up on themselves. As long as relatively critical things are fixed in a timely fashion, things tend to work out for me pretty comfortably. I know I'm probably just lucky in that, but you should know it, going into this post.

##What is your service platform?

Pretty straight-forward: are you launching a website? Mobile app? Desktop application? IoT firmware?

Think about what it takes to update something. Think about whether people *get* updates. If you have a website and you get a bug report, it's relatively simple to push a new version up. If you have firmware on someone's smart watch, that might be a bit more difficult. If your product, in production, is difficult to push updates to, you should make sure to remove as many bugs as you can before pushing up, and definitely keep that balance tipped towards keeping things stable, rather than necessarily innovative. If you can freely experiment (or even only push updates to a small percentage of users at a time), that gives you some more leniency.

##What stage is your product in?

This one's boring, but it needs saying--if you're in beta, bugs are more tolerable than if you're in full-blown production. I'm assuming that you're referring to full-blown production.

If people are expecting bugs, don't kill off all of your innovation in order to mitigate them all. Obviously, with all this, if something stops someone from being able to use the software under "reasonable circumstances," it's probably worth fixing. Or if it's just a typo on one line, it's probably worth fixing. But if something is very hard to fix, or if you haven't found it yet (I'm thinking of "the balance between bugs and features" as including "the balance between testing and feature development"), early stages can be conducive to innovation. Just make sure you don't innovate throughout your entire beta period, then have a whole new feature-set that doesn't get fully tested.

##Who uses the product?

On one hand, you have the users who would rather see new features and actually be the first ones to report bugs to you. They're the early adopters, and they're a pretty crucial part of most (particularly tech) startups.

On the other hand, you have *most people.* Most people don't want bugs at all, and will, in fact, be actively turned away from your software (perhaps permanently) if they see bugs from the get-go.

The first step to determining your release cycle and the specifics of your development process is determining your audience between those two groups. Obviously, like anything, there are people who will be in between. But that's the center from which you'll want to find the "balance" that you've asked for.

It's not necessarily bound to work, and unfortunately it will carry an innate bias towards the "early adopter" crowd, but one approach to establishing that about your audience is just asking them. Post a user survey (this is fine for websites, a bit more awkward for apps but still doable) that asks in plain English: "would you rather see new features, or a finely polished app?" Modern users will (mostly) understand what you're asking, and if you're feeling daring, I don't see any reason why you couldn't include a brief paragraph explaining this exact predicament and asking them how they'd like to see you side.

Beyond that, and less abstractly, you just have to think about who your target audience is, and where on this spectrum they may fall. If you're developing for Stack Overflow, for example, with a ton of developers, it's probably reasonable to focus on features. Bug reports will be happily served. Obviously you never want to ship bad software, and when users report a bug, you should probably fix it. But testing doesn't necessarily have to be your number one top priority, as it may have to be, for, say, Microsoft Word.

##What's their investment?

Think about your investment (are you serving up ads?), but also think about your users investments. If your users are hedging their business on your service, or if they're paying you regularly for it, bugs are a big no-no. You'll scare people away, if nothing else. Many B2B clients, in particular, would rather see a stable product that never ever changes, rather than a constantly evolving one. That's (part of, in addition to budgeting) why so many big organizations are still using Windows XP.

If your customers are paying or relying heavily on you, it's best not to let them down. If your customers are using you mostly for non-critical activities, or if they're willing to crowd-source testing, you can be a little more liberal.

##How's your support?

If you're taking bug reports, be ready to *take bug reports.* Logging them all up in SQL (or NoSQL, as the kids are using these days) is great, but you'd better be on top of those. And if something serious breaks, you'd better be ready to work all hours to fix it. That's the absolute biggest risk, I'd say, with putting features ahead of stability--when stability crumbles, even just a little, you have to [make sure you're on top of it](https://startups.stackexchange.com/q/1755/59), whatever it takes.

On top of this, make sure users know how to submit bug reports. To use Stack Exchange as an example yet again, most users are aware of the [Meta system](/help/whats-meta) we have here, and once you know what Meta is for and how to ask a question (which most people submitting bugs should know), it's very straight-forward. Some other software, particularly desktop software, not so much. This is really a general point, since you should expect bugs even if you are building for stability and not features, but it's particularly important if you put features first.

##Will the features be consistent?

I talk about this one a lot with clients (and even friends, because yeah, I'm that much fun to hang out with) in real life. Innovation is awesome, but it's also dangerous.

There are a few ways to explain it, but I'll just be straight-forward with a bulleted list. The way I see it, there are four fundamental ways a feature can go when a version (let's call it V2) is released.

* **It stays the same**: Hooray!
* **Added in V2**: Hooray!
* **Removed in V2**: If it was a feature people liked, they're mad at you. And little secret: someone likes every feature. Someone will be mad.
* **Changed in V2**: If it's a significant change, you'll just wind up with confused, mad users.

The common theme here is that it's best to get features right the first time. So if you aren't sold on how a feature (or small aspect of a feature, even) will be implemented, I prefer to hold off. Considering how users tend to be excited about new features being implemented anyway, I think focusing on a good piece of software is the right side to go for when you're on the fence.


## Answer 12603

- posted by: [user13588](https://stackexchange.com/users/10828248/user13588) on 2017-05-04
- score: 3

<p>An easy way to get tripped up when thinking about bug fixes versus building new features is not fully understanding just <em>how important</em> a given bug is. </p>

<p>Sometimes it's very obvious like a high paying customer has complained, or you've pushed a bug to your signup page, in which case fixing the bug is even more pressing than working on building new features. </p>

<p>But what about the edge cases when it's not so clear? It's important to have visibility into this because the truth is not all bugs are worth fixing, and there are ways you can effectively prioritize bugs and feel more confident when allocating time towards them. </p>

<p>Things to consider: </p>

<ul>
<li>Is this error happening frequently?</li>
<li>Is this error impacting an important section of my code?</li>
<li>Is this an error regression (something I’ve already tried to fix before)?</li>
<li>Is this error impacting a high number of users or a very important user?</li>
<li>Maybe not yet, but will this error be worth fixing in the future?</li>
</ul>

<p>Things that can help make this easier: </p>

<ul>
<li>proactively monitoring for bugs (error monitoring tool)</li>
<li>grouping like bugs together so you can understand how often a bug is happening</li>
<li>mapping bugs to users to you can see how many users are affected</li>
<li>intelligent alerting to make sure you only receive notifications about errors that might be worth prioritizing</li>
<li>the ability to silence or snooze errors that aren’t important</li>
</ul>

<p>The idea is to remove the guesswork associated with figuring out just how important a bug is. Further reading in <a href="https://blog.bugsnag.com/bug-prioritization/" rel="nofollow noreferrer">A guide to prioritizing bug fixes</a> </p>



## Answer 3429

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-02-14
- score: 1

Cosmetic bugs can usually wait. Feature-related bugs often cannot.

The two key questions to ask yourself are:

1. **Is the bug getting reported often**, i.e. it mostly works but it's "in your face" buggy to the point where you periodically get feedback that mentions it?

2. **Is the bug causing user churn**, i.e. it's not a rare edge case, and it's severe enough that users stop using your app -- or use it a lot less -- when they run into it?

If yes to either question, fix the bug first: it's making you look unprofessional, or getting in the way of your growth -- or both.


## Answer 3428

- posted by: [Tommy Otzen](https://stackexchange.com/users/4026382/tommy-otzen) on 2015-02-14
- score: 0

If the question is "Prioritize new features or fix known bugs?", then you only have to answers "yes or no". I think the answer is a third one. You should give your users the most valuable feature at any given time, regardless if it is fixing an old bug or adding a new feature.
Let me explain: lets say you have a known bug, users dont get a conformation after adding certain details to a formula, the system just return a blank page. The system works, but isn't easy to understand and your users have learned to live with the bug.
At the same time users are requesting the option to change the formula after finishing it the first time. This feature is very importent to the users.
Should you then change the old bug or add the new feature? You should off course change both, but prioritize the most valuable to your users first, not the first you knew of. You could even make the rules in this way:
1. The most critical to make the system work.
2. The most valuable to your users.





---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
