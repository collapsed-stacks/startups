## What's the best way to build and prioritise a product roadmap?

- posted by: [Alex Schmidt](https://stackexchange.com/users/11766359/alex-schmidt) on 2017-09-14
- tagged: `product`, `product-market-fit`, `minimum-viable-product`
- score: 2

<p>I've recently been promoted to a Product Owner role at a startup, and to be completely honest, I still have a lot to learn.</p>

<p>One of the things I have been struggling with is that I have inherited a Excel sheet backlog that is actually more a giant spreadsheet of ideas.</p>

<p>Within that, I'm expected to be able to prioritise all these ideas against one another. I've done plenty of reading on the topic and I get the concepts, but it in to practice just doesn't seem to be working for me. T-Shirt sizing and Fibonacci estimates that Scrum talks for Effort and Impact are great, but I seem to be missing a link in how I can determine them. Is there any good material that helps with putting scoring in to practice? Is there software that will guide you for this?</p>

<p>Any ideas?</p>



## Answer 13338

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2017-09-14
- score: 3

<p>Ignore the spreadsheet and refrain from trying to apply a systematic scoring rule at once.</p>

<p>TL;DR: let users and those on the front line set the priorities for you based on the amount of kicking a screaming you're able to detect.</p>

<h3>First things first: talk to your clients.</h3>

<p>Send them an (individual) email to invite them to have a chat on Skype or whatever, pop up a chat prompting them to talk to you in whatever web-based chat app you're using, yada yada. As a product manager, if your week hasn't included 2-3 chats with clients at least, file it under utterly wasted time.</p>

<p>Ask them about how they found the product (don't forget to tell marketing), what they use it for (same), where they got pushback when adopting it (same), what they struggle with (a favorite of mine is: is there anything you regularly find yourself wishing our product did or did better?), etc.</p>

<p>Probe into their product usage. I cannot stress the importance of this enough, because marketing departments are unfortunately all too often populated with people who actually have little clue of what marketing is actually about. If your marketing department is not providing you with a very regular stream of client wish lists and market insights, then it's an indication they're not talking to clients and under no circumstances should you rely on them for useful information.</p>

<p>Don't forget to involve a sales or two in product planning meetings if you've an actual sales team - if not always at least do so sometimes. Sales meet with clients every day. It's what they do. They're on the front line when it comes to sorting out client horror stories or dealing with engineer messes. They've skin in the game and will usually kick and scream if you're not sorting out the mess they need to cope with daily.</p>

<p>And basically ignore internal feedback, unless it comes from marketing and sales, actual product users, or are obviously great ideas. You're in this to create a product that users want to buy; not a product that your engineers want to fap at. Everyone in an org will have a pet feature that they'd love to see, but as a product manager you're the one whose job it is to see clients eye to an eye and ask them what they actually want to be doing.</p>

<h3>Then prioritize...</h3>

<p>You will rapidly find patterns as you talk to users. Invariably, there are things users regularly struggle with. They will come up over and over. Probe, and probe deeper. Note that your product doesn't necessarily answer their requirements. Sad but true. For all you know they're using your product for one thing but are genuinely troubled by some other related thing day in day out. Fix that and you've a killer, so be sure to understand what they're up to in practice as they use the product.</p>

<p>Fix the utterly obvious first. It's usually small things that everyone takes issue with. Then focus on larger problems based on how often they come up and how big a problem they are (think in terms of cost to fix vs impact).</p>

<p>If your organization is open for it, also ensure there's a very thin layer of support between level 1 support and the actual product developers. The thinner the better. Get obvious questions out of their way, but see to it that every little niggle that clients ask about over and over lands straight in their inbox. They'll be kicking and screaming about fixing them in no time to get customers out of their inboxes, and that's your best ally to garner internal support for how useful this or that is as opposed to re-engineering something else for the fun of it.</p>

<p>Think of the latter this way: every time support explains or - worse - documents how to work around a broken piece of software, an opportunity is lost on the product manager's end to make the problem go away to being with. Documentation, as an aside, is good in general, but it's also a surefire way to set a broken process in stone - users get used to bad UI if it's well documented enough. Require constant feedback about what clients are asking about and what docs they're looking at from your support department if there is one. And require the same from your devs if you're able to not shield them support requests.</p>

<h3>Don't forget stats, but...</h3>

<p>Monitor <em>everything</em>. And I really mean, everything. If you can afford a package like Heap Analytics (which literally monitors everything, allowing you to build queries ex-post to answer questions you're wondering), do so. If you can't, see to it that you get a budget to that effect ASAP.</p>

<p>Stats are indispensable for your job. It'll make the difference between saying "yeah it worked" and "yeah it worked and here was the precise effect".</p>

<p>Do not, however, let stats substitute client interviews proper. You cannot hide from clients in your position. You <em>must</em> talk to them. I've lost count of the number of times I ran into a startup where the product manager was rarely talking to users and I was giving them insights about what to develop and why within a week or two. They're usually neck deep into stats (or less often, not into stats at all), and making assumptions in an ivory tower without the slightest idea of what their clients are actually up to. Don't do that.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
