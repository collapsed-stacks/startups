## Outsourcing software development

- posted by: [DonkeyKong](https://stackexchange.com/users/1459632/donkeykong) on 2015-07-30
- tagged: `tech-company`, `website`, `software`, `web-development`, `outsourcing`
- score: 5

We are about to have a woocommerce site developed through Elance. We would like to have the minimum viable product be developed offshore, and then look for a US-based developer, if we can get some traction with it. 

I am server/network admin, not a programmer. But I have been asked to manage this project. What should I do to make the process go smoothly?

Should I ask for the full repository on delivery? I am guessing having everything commented in English is a good idea. What should I look out for?


## Answer 5907

- posted by: [Matiss](https://stackexchange.com/users/1819512/matiss) on 2015-07-31
- score: 6

A rule of thumb for this to succeed is to have a internal oversight over the outsourced development, e.g. someone, who actually is a developer himself and will oversee what the outsourced developer/team does, and checks for the quality of deliverables. 

In your case it sounds like that might not be possible, as it seems like your project might be just a one man job - correct me if I am wrong. 

In this case, you should actually weight what will you actually gain with this and is the gain sufficient to justify the use of a outsourced developer.

One con I can warn you about is that outsourcing this could actually turn out more expensive than you imagine, and the reason is duplicate learning curve. Your outsourced developer will make you a MVP of his technical design, and when your local developer will be assigned to this, he will need to make himself familiar with the doings of the outsourced developer - this will take time and time equals money.

Outsourcing usually makes sense for one-timers and very large projects where outsourcing is used to augment the existing resources or when shifting to outsourced solutions completely. For projects you actually want to maintain locally afterwards, I would recommend against outsourcing, especially if you don't have any way to oversee what the outsourced party actually delivers.

If, however, this decision is final and you must proceed with outsourcing, you must ask for all the source code (in a form of GIT repository with full commit history would be nice), the technical documentation that might be relevant - architecture details and requirements, major decision point documentation (why chose this solution instead of that), installation instructions, maintenance instructions, hardware and software requirements, etc. etc. 

Code, of course should be written and commented in English, and I can not emphasize this enough - there must be automated tests for the parts of the code that the outsourced developer makes - unit tests, behavior tests, anything that assures things work and things does not break when the local developer starts to make changes. There is no way you can actually verify the quality of the automated tests without actually inspecting them, but asking for them in the first place might plant the idea that you actually are aware of stuff you are asking for in the mind of the outsourced developer, which could play in your favor a lot.

Last, but not least, you must ask for continuous delivery, e.g. you shall ask for near-real-time access to the work the developer is doing and results of it, e.g. some sort of live system where you can check on progress. Changes there should be published as often as possible, and no longer than with a week long intervals. This will help you to oversee the actual progress of the project, not the one being reported. 


## Answer 8223

- posted by: [Miles Rose](https://stackexchange.com/users/7489029/miles-rose) on 2015-12-29
- score: 3

If you haven't managed outsourced development be prepared for some surprises. Some are your fault and some are the developers. The people you speak with aren't necessarily do the work. Outsourced developers leave all the time. Its a huge problem. When working with a new vendor I work on a small project on a flat fee. Don't do anything before you have a spec. Set rules in terms of documentation both in the code and document work product. Two sentences, worked on database, for two weeks work really doesn't cut it for me. Make sure you have access to all code. See if you can get some sort of guarantee that those starting will also finish the project. In reality most off shore programming takes more time and costs more money. You have to write a spec and they have to build to the spec. You can find a lot of other information about requirements in terms of software and version used, etc. If you haven't done this before find someone who can help you. Always set you spec in stone and try and get a flat rate for each part of the project. Joel on software has some excellent, not excellent, the best in terms of how to write a spec and related matters. 


## Answer 8252

- posted by: [Bluebay](https://stackexchange.com/users/7562754/bluebay) on 2016-01-03
- score: 0

You could ask a local programmer that you wish to work with, if they are happy to work with offshore programmer code, on either an ongoing basis, where they 

A. might both contribute to the repository, or 

B. whether they will take over properly commented code, provided it meets the specification you have laid out for the software, and you provide good specs for the local programmers for the work you wish them to do.

Look for hesitation on the answers you get, or if the local programmers are receptive to the idea of working on off- shore produced code.  

It may be worthwhile for you to research local programmers, and get attitudes bedded down to what you wish to achieve and why, rather than rushing in to outsourcing first, then forcing that work onto others. 
If you try locally first, you may find programmers might be receptive to the idea, and may say "go right ahead, but make sure you have the right plan in place eg, offshore uses Mercurial, local does not.  

Also, make sure you are 100% focussed on the each section of the whole project,  so that may entail using your own story board, (You can use , for example, storiesonboard.com),  and compare your story cards one by one to the written spec, so that you know it in detail. 

Then when you know it backwards,  you can deal more effectively with both the offshore company, and the onshore ones.

Use a senior programmer as an overseer to steer you with the code reviews and whether milestones are matching expectations from your boss. Convince your boss that you need someone to help in the programming reviews, at least once a week.

Make sure everyone knows (ideally on a daily basis, but weekly works) what the status of the project is. And by status I mean what has been done, what is left to do, open questions, problems, etc. Anything that can impact the completion of the project should be reported.

You should go over the big picture every day for an hour. Ask yourself the questions. What's been completed? What's left to do? What are the open questions? What's the goal? You should be able to give someone a detailed status of the project whenever they ask.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
