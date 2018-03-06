## How can I know if my developer is doing a good job?

- posted by: [John G.](https://stackexchange.com/users/4594105/john-g) on 2015-01-22
- tagged: `website`, `web-development`, `freelancing`, `work-for-hire`
- score: 62

I don't know anything about code except some basic HTML.

Recently, I hired a freelance developer to do some front-end updates on my e-commerce website. Because of the nature of e-commerce websites, I care a lot about showing up in search results and having fast page loads.

I'm pretty happy with the result so far, but I have no idea whether my developer has coded well, or if they have any talent or skill at it. On top of that, he charged me for twelve hours of work, and I really can't judge if that's a reasonable amount of time for my update and if he's being honest about working time.

How can I, without a technical background, judge the technical skill and honesty of a freelance developer like this? I would be open to hiring a code review service, if there is such a thing.


## Answer 3114

- posted by: [blunders](https://stackexchange.com/users/216182/blunders) on 2015-01-22
- score: 63

If you own a car, and get it repaired, how do you know the repair was needed and that the related time and materials were billed at fair rates?

Fact is that the way coders solve problems and the problems they solve vary so much that for a small company issues like code quality and costs are just a fact of life.

There is no silver bullet, and in my opinion it is foolish to believe there is. 

The best way to know if a coder is good is to have them do work and have a meaningful way to measure the outcome of that work that best aligns to the goals of the company. 

In the end it comes down to you being able to trust the coder, and for some trust is harder than for others no matter how trustworthy someone might be.


## Answer 3117

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-01-22
- score: 25

## Get a cofounder or a technical advisor

First off, **if you're creating a business that is deeply technical, you want a technical co-founder**. If it's only moderately technical, you still want a good programmer around if only to oversee cheaper code grunts -- someone who you trust will steer things in the right directions and who is able to give educated insights on the quality of their work.

## But if you really must evaluate yourself...

Good programmers tend to live by the [mantra](https://stackoverflow.com/questions/876089/who-wrote-this-programing-saying-always-code-as-if-the-guy-who-ends-up-maintai): "Always code as if the guy who ends up maintaining your code will be a violent psychopath who knows where you live."

In practice, it means they write **code that is reasonably understandable by a non-programmer**, either because it's self-explanatory, or because comments lying around allow you to get the gist of what's going on.

Another characteristic is a consistent coding style. But as rightfully noted by some commenters, noticing this kind of stuff takes some programming expertise, and you don't necessarily want to spend time acquiring it. In a nutshell though, a random mix of `CamelCase` and `snake_case`, unindented code, inconsistent use of tabs and spaces for indents, kilometer-long functions, or seemingly identical code blocks repeated all over the place, are some red flags to have in mind.

**Good programmers additionally use source control** to document small, incremental change sets. Doing so allows to go back in time when a bug is identified, in order to know precisely when the bug first appeared and how it was introduced. If your programmer left dead code commented out all over the place or wrapped in `if (false)` blocks, that usually is a sign that they're not using source control.

There are more aspects to it, of course, but for a non-programmer who needs to evaluate code quality produced by a cheap coder hired on eLance, the above are reasonably good proxies. They're not magic bullets however; only proxies. So again, get a good programmer as a co-founder -- or at least as a part-time technical advisor.

## Your current recruit is likely dishonest... but against himself

With respect to honesty: if he says it took him 12h, it probably means he spent more time than that if you additionally account for the time he took interacting with you. (And that, btw, is why very good freelances invariably switch to billing by the day or week rather than by the hour.)

## Hire another programmer for code reviews: it's another pair of eyes

As for code reviews, consider sourcing that particular task to a second programmer on e.g. eLance, until you locate a good programmer to join your team on a full or part-time basis.


## Answer 3116

- posted by: [demiculus](https://stackexchange.com/users/5264485/demiculus) on 2015-01-22
- score: 24

<p>If you are running an IT business you should be familiar with codes (and everything else related to your business) so the first way to solve this problem is</p>

<ul>
<li><p>Learn principles of coding</p></li>
<li><p>Another way to solve this problem is to find a technical partner or a technical advisor (if you are in IT business at least one of the founders should be technical)</p></li>
<li><p>Like you said there are code review services which you can hire such as <a href="https://www.airpair.com/" rel="nofollow noreferrer">airpair</a> or <a href="http://ocscodereview.com/" rel="nofollow noreferrer">OCS</a></p></li>
<li><p>Use the Goal/Measure system, set a goal for him to do and then measure it. </p></li>
</ul>

<p>For example if you are ranked around 30 in google and you want to get in top 5 measure it by going to google through various proxies.
Or if your site loads in 0.8secs and you want to bring it down to 0.4 measure it by using an online tool such as <a href="https://www.otreva.com/calculator/" rel="nofollow noreferrer">web speed test</a>. 
Though to measure and estimate every task like this you must search the internet and learn how it works for every single goal.</p>

<ul>
<li><p>You can also use online calculators which are really usefull to estimate freelance costs. <a href="https://www.otreva.com/calculator/" rel="nofollow noreferrer">Otreva</a> and <a href="http://www.kinvey.com/app-cost-estimator" rel="nofollow noreferrer">kinvey</a> are good for mobile, <a href="http://www.webpagefx.com/How-much-should-web-site-cost.html" rel="nofollow noreferrer">webpagefx</a> and <a href="http://www.comentum.com/ecommerce-cms/" rel="nofollow noreferrer">comentum</a> are good for web development. By using these you can easily figure out if the freelancer is charging you too much or too little for a given feature.</p></li>
<li><p>Lastly like <a href="https://startups.stackexchange.com/a/3115/1345">this answer has mentioned</a>, you can hire freelancers from platforms such as <a href="https://www.elance.com/" rel="nofollow noreferrer">elance</a>, <a href="http://www.guru.com/" rel="nofollow noreferrer">guru</a> or <a href="https://www.odesk.com/" rel="nofollow noreferrer">odesk</a> for the best freelance experience. </p></li>
</ul>



## Answer 3128

- posted by: [Mikaveli](https://stackexchange.com/users/280211/mikaveli) on 2015-01-23
- score: 13

<p><strong>Quis custodiet ipsos custodes?</strong><br>
("Who will guard the guards?")</p>

<p>If you hire someone to check-up on the work of your freelance developer, how do you know <em>they</em> know what they're talking about (unless they're <a href="https://stackoverflow.com/users/22656/jon-skeet">Jon Skeet</a>, of course)?</p>

<p>The bottom line is, you need to be able to trust someone - how someone gains your trust in an area (development) you're unfamiliar with is not straightforward. Having a "technical co-founder" is great, but how are you accessing their credentials - I've met many a CTO whose technical knowledge just wasn't there (beyond a light surface understanding and vocabulary of trendy buzzwords...).</p>

<p>Suggestions from other answerers telling <em>you</em> to use code quality tools is not a good one. Just as an experiment, I just ran a well written part of the <a href="http://jquery.com/" rel="nofollow noreferrer">jQuery</a> library through JSLint and it comes back showing 53 "errors". Most automated code quality tools have (at least some) rules that are either highly contentious or very academic / superficial. A "good developer" will know which "errors" need to be acted upon, which ones should be addressed (given the time / budget) and which ones can be ignored completely (and still have a "quality" code base). If you don't know enough to correctly interpret the reports you get back (whether from a tool or reviewer you hire), you'll be causing yourself more problems than you solve.</p>

<p>As with any form of engineering, there's a way to get things done quickly, an "ideal / preferred" approach and there are lazy / unskilled "cowboy" ways to fulfil a brief. Where do you draw the line?</p>

<p>If your freelance developer ran your whole code base through <a href="http://jslint.com/" rel="nofollow noreferrer">JSLint</a>, fixed every error and delivered an academically perfect solution, but billed for you 1000 hours, would you be happy?</p>

<p>You need to communicate your expectations up front - what is "quality code", what's the maximum time you'd like them to spend on an issue / feature (what's your budget)? What browsers / platforms are you supporting? How much time should be spent refactoring or fixing issues in existing code?</p>

<p>For all of your expectations, you need a way of measuring success against them. If you can't measure it, why ask for it? If you've asked for a feature to be added, testing its (end-user) functionality should be part of a showcase on delivery. If you've asked for well tested software, get them to show you their (documented) test cases and any unit tests added. Some things can't be practically measured - time spent gaining knowledge of a system, time spent understanding a requirement and drafting potential solutions, time spent testing (which is no guarantee of coverage), so there's no avoiding at least an element of trust.</p>

<p>You're primary mitigation is to try and ensure you have a robust way of hiring, which may include looking at (in no particular order):</p>

<ul>
<li>Their work experience. </li>
<li>Qualifications (academic or industry certification). </li>
<li>A portfolio (websites of previous clients etc.).</li>
<li>Community participation (like <a href="https://stackoverflow.com/">Stack Overflow</a>).</li>
<li>Skills assessments (using candidate testing and selection services).</li>
<li>Recommendations (from colleagues or other businesses you trust).</li>
</ul>

<p>Even then there are no guarantees. Trust is the key - after all, they could be writing great code, while stealing your customer data...</p>

<p><strong>TL;DR</strong></p>

<p>Use all the information you do have to assess them using your best guess, then trust them until they give you a reason not to.</p>



## Answer 3126

- posted by: [Peter](https://stackexchange.com/users/1767139/peter) on 2015-01-23
- score: 9

The question is entirely equivalent to the more generic question "**How do I know if someone working outside my field of expertise is doing a good job?"** How do you know if your sales guy is good at selling your product, or if they are just good at making you set low targets?

The short answer is, **you don't**. But you can always hire someone (i.e. an audit) to get their opinion on the quality of the work - but how do you know they are doing a good job?

---------------------------------------

One important thing to keep in mind is that the immediately relevant question is not if the person is doing a good job. The immediately relevant question is if the job the person is performing is actually worth doing at the quality+speed+salary/compensation of that person.

You may then have other questions, such as: "Can another developer take over if the original developer gets hit by a bus?" - This question can easily be addressed by letting the original developer know of that concern and then hire another developer for the next change request, just to make sure another developer can work with the code.


## Answer 3133

- posted by: [Nathan Long](https://stackexchange.com/users/3082/nathan-long) on 2015-01-23
- score: 7

# This is a human problem

I'm a developer. I'd say this is more of a human problem than a technical one.

How do you know your accountant, lawyer, surgeon, or mechanic is good? You probably use reputation and "how do they answer my questions?" as proxies.

If you want to verify the **quality** of their work, you might get a second opinion from another expert in the same field. In this case, the other developer could look at the code before and after the changes to see whether what was done seems logical.

Verifying the **speed** of their work is harder. Estimating software tasks is notoriously hard, so "was that done reasonably quickly?" is a hard question to answer. It's probably better to ask, "if this feature cost me $X, was it worth that to my business?" If you consistently say "no", there may be a problem with this developer. Then again, maybe your code is particularly tricky to modify, and another developer will have the same problems.

In any case, it will always be hard for a non-expert to judge an expert's work. Preferably you'd have a team of developers you trust and would let them evaluate one another.


## Answer 3136

- posted by: [l0b0](https://stackexchange.com/users/34241/l0b0) on 2015-01-23
- score: 6

**Even developers can't agree what makes a good developer.** And in my experience most of them will be able to present a sensible argument for their own position, whatever it is. Whether that makes sense for *you* is another matter:

- *Introvert or extrovert?* The "ideal" programmer would be able to work productively and independently for long stretches of time, while being able and willing to work with and explain things in great detail to others. I suspect such people are rather rare.
- *Fast or thorough?* Even a mediocre developer should be able to shift between the two depending on whether she's doing a spike, working on a prototype, writing a maintenance script or developing high-risk production code. A great developer should be able to go even further in either extreme, racing through to proving a concept and then developing a very stable, flexible, readable, secure, etc, etc, solution.
- *Fast learner or experienced?* Great developers are both, but they are only going to be willing to work on something which is very technically challenging.

Personally, if I were a manager with little technical expertise, I would base a hiring decision on whether the person has any kind of **track record** with other companies or open source projects (preferably in relevant technologies) and human factors like **cooperation, trust, and whether they admit to errors at least once in a while.**


## Answer 3143

- posted by: [Christian Bongiorno](https://stackexchange.com/users/673865/christian-bongiorno) on 2015-01-23
- score: 4

Let me suggest **Audit** as others have but gives you a specific methodology for getting there.

I am a software development veteran of 15 years and I can definitely sympathize. 

Here is how you approach this:

 1. Decide how often you will need this service. No one vetts the guy who puts the tires on his car or changes his oil but a good babysitter is hard to find.
 2. Decide how important it is to you in $ terms. Assuming you found a contractor you really like, how much would you be willing to pay to acquire and keep him?
 3. Now Audit him with outside contractors. It's validation through corroboration 

I found a website where you can pay to have this done. Basically, grant them license to your whole repository, including history, so they can review it. This sort of thing is generally reserved for interviews. Have it done, say, 3 times for everytime you have him do work. If the results from the audit consistently come back positive, then treat the guy right to keep him around. 

If this has real similarities to hiring and employee, performance reviews and HR hassles from a corportate world it's for a reason: It is the same! You're just contracting out the whole process.

Ultimately, if you're happy with the result (Time to deliver, cost, features, bug free) then it's good software. 


## Answer 3125

- posted by: [rlms](https://stackexchange.com/users/2773218/rlms) on 2015-01-22
- score: 3

I would strongly advise you against dabbling in programming, and then asking questions about code - "Which design patterns are you using?" etc (although learning a bit of programming is never bad). However, you could educate yourself about other aspects of development, and inquire about those.

As mentioned by Denis, good developers should use distributed source control (some standard tools being Git and Mercurial). That's one thing you could ask about. You could also try running source code analysis programs, such as [jslint](http://www.jslint.com/) for programs written in JavaScript. These analyse how nicely written code is. They won't tell you if code works or not, but if source code fails them, the programmer may have some bad habits. In some cases, you could also ask if they have automated the build process, but that probably doesn't apply as much to front-end development.


## Answer 3127

- posted by: [aportr](https://stackexchange.com/users/457646/aportr) on 2015-01-23
- score: 3

How can you know if any of these answers are good answers?

You should be able to clearly state what you want the developer to do before you engage them, and if they deliver you something that meets your requirements, they have probably coded well enough.

As for price, ask around for quotes like you would for anything else.

Personally, I would focus on the site as a whole and how it interacts with your business requirements rather than worrying about how cost effective your SEO is.

e.g.

 - Is it secure?
 - Is it resilient, or will your site go down the next time a server crashes?
 - Can you scale performance easily if it takes off in popularity?
 - Is it compliant with all your local obligations (PCI, SOX404, etc)?
 - Can you get enough information out of it to guide your other business decisions?


## Answer 3187

- posted by: [HSquirrel](https://stackexchange.com/users/3682254/hsquirrel) on 2015-01-26
- score: 2

Check nr1: Test the changes. Do they work as you expected? If yes, that is the most basic check and the most important one.

Check nr2: Let several other coders/companies audit the code. I think that's excessive here (and would cost significantly more than the code itself).

After that, you should be looking first at your bottom line. Will the return on investment offset the costs of the developer? If yes, then you did what's right for the business. You might have been able to make a bit more had you found a cheaper/faster, but equally skilled developer. Ideally, you should estimate the ROI before and you could then talk with your developer up front about the changes you want, how much time he thinks he'll charge for the work and see if your expectations line up.

More long term, you want to take various things into account.
How much time it takes to make changes to the system, how often bugs are introduced, how well estimates work out, ...
All of those require you to have a longer working relationship with your developer. I would advise you to build up that kind of relationship. It is time-consuming to learn a new project and its business, you get to skip that cost if you keep the same developer. You also skip the cost of multiple craftsmen each working in their own way, which tends to clutter the system for later developers.

How to pick a developer that you want to build a longer relationship with? Most important factor here is probably whether you guys get along. Judging skill is a hard problem. You could try to go by reputation, but that's sketchy at best as a lot of developers tend to be introverted. Other things are important too: if there is a critical bug in the middle of the night, can you call your developer? At what price?




## Answer 4020

- posted by: [Dmitri Zaitsev](https://stackexchange.com/users/1769946/dmitri-zaitsev) on 2015-04-16
- score: 2

<p>Taking the analogy with the car, when it gets repaired, there are <strong>visible</strong> and <strong>invisible</strong> results. It is obvious what the visible are, but the invisible ones can <strong>become visible</strong> in course of the time but not necessarily immediately. Say your car runs perfectly for several months and then suddenly breaks down and your new repairman tells you the one who fixed it was an idiot :)</p>

<p>It is not much different in software. You can try your site now and see what works immediately, but there are lots of other things called <a href="http://en.wikipedia.org/wiki/Technical_debt" rel="nofollow noreferrer"><strong>technical debt</strong></a> that you can't easily see. Like bad inefficient code violating best practices, outdated and unsupported 3rd party technologies, mobile support, performance issues etc.</p>

<p>You might get a quick'n'dirty work that makes your site look like it is running, then you notice few things here'n'there and <strong>specifically those things</strong> will be fixed, then your developer will call it a day. Now your site is running and that is where things start getting interesting. What worked before, suddenly stops working, 3rd party libraries you use get old and abandoned, your site makes customers' browsers crash and so on. Now you invite a new developer who tells you, your code is no good and everything has to be rewritten from scratch...</p>

<hr>

<h2>So how can you protect yourself from those troubles?</h2>

<ul>
<li>To begin with, many things you can even do yourself without paying anyone a cent. Look for <em>online web site performance and quality tests</em>, <a href="https://developers.google.com/speed/pagespeed/insights/" rel="nofollow noreferrer">Google</a> and <a href="http://yslow.org/" rel="nofollow noreferrer">Yahoo</a> have great tools among many others. Further, you don't have <strong>learn programming</strong> yourself but there are lots of resources to help you get an idea what kind of <strong>programming work</strong> is involved. <a href="https://medium.com/@dmitri145/getting-out-your-minimal-viable-app-6b163f9ef1c8" rel="nofollow noreferrer">Here is a blog post I wrote</a> to give you some "meat" :)</li>
</ul>

<p>Then there are basic questions you can ask your developer. Such as:</p>

<ul>
<li><p>Are you running automated tests for my site? If you are not sure what they are and why you want to have them, google them, read in Wikipedia, on Quora and Stackoverflow. <a href="https://stackoverflow.com/questions/17070522/can-protractor-and-karma-be-used-together/29619467#29619467">Here is a detailed overview</a> I wrote specifically for the popular <em>front end Framework <a href="https://angularjs.org/" rel="nofollow noreferrer">AngularJS</a></em> and its two main test runners - <em>Karma and Protractor</em>. It is written for technical minded folks but you can still try to make sense out of it. And many testing principles there are not specific to Angular. </p></li>
<li><p>Speaking of Frameworks, your developer should be able to give you a run-down on what sort of Frameworks and 3rd party libraries he likes, has experience with and so on.</p></li>
<li><p>If your developer is active on Stackoverflow or Quora (I hope he is),  it might be worth your time reading his posts to better connect with him, understand what his strengths and weaknesses are, what he likes and what he doesn't and many other insights.</p></li>
<li><p>Other things - contributions to open source projects on <a href="http://github.com" rel="nofollow noreferrer">Github</a> - own repositories, pull requests, issues etc. Again if you feel lost on Github, just write them a help request clicking their "contact human" button - they are very good at responding to those.</p></li>
</ul>

<p>Next if you in the <strong>interview mode</strong>, ask these and see what he says:</p>

<ul>
<li><p>What are the best practices you are going to follow?</p></li>
<li><p>What do you think of "SOLID principles", can you explain them?</p></li>
<li><p>Do you split your modules into Model-View-Controller or other flavours (e.g. Model-View-ViewModel is great for front end projects) ?</p></li>
<li><p>Do you follow any coding style guide?</p></li>
<li><p>What makes your code modular and reusable?</p></li>
<li><p>Whether he read <a href="http://www.joelonsoftware.com/" rel="nofollow noreferrer">Joel Spolsky's blog</a> and what in particular he liked there. Even if he didn't know about it (believe me or not - many programmers don't!), he'll love you for telling him about it! :)</p></li>
</ul>

<hr>

<p>Finally, no top skill will replace good trustworthy relationship. <a href="https://freelancing.stackexchange.com/a/2195/4546">Here is an answer I wrote explaining my view</a>.</p>



## Answer 7678

- posted by: [Paparazzi](https://stackexchange.com/users/300272/paparazzi) on 2015-10-31
- score: 2

You mentioned updates, speed, and search results. There is a lot between those objectives and code.  

In large business you have role CIO that sits between IT and the business to make effective use of IT and hold them accountable.  You need to take on the CIO role.  You also need to take on a roles of product manager and project manager.

You may not be a programmer but you do control the requirements. Have very clear written requirements and acceptance testing. Even if they are by the hour ask them how long they think it will take. Have a maximum on the number of hours they can bill without a status. 

I am developer and I will get loose verbal requirements and then when it is done they will change this and that. Then when they get the bill they act like they are the victim when they are the cause. Think thru what you want and clearly articulate in writing.

Many non-technical (and some technical) have problems with requirement versus a design.  A requirement does not have an implementation.  I will often get these elaborate designs that are going to be expensive and when I extract what they are trying to achieve I can suggest a less expensive implementation.  If they don't want my suggestion then I am happy with billing for a more expensive functional design.  These interviews are time and money.  Take the time to document the requirement in writing up front.  A design can start to take a life of its own and you forget what you were trying to achieve.  It is called scope creep and it is expensive.

If you need 5 things done then it will be more cost effective to have the programmer do all 5 rather than 1 at a time.  

Speed is lot about the site architecture as a whole.  I need this button to return in 0.1 second may be costly.  Be open to a cost versus performance discussion.   Some times that next increment in speed means changing out a lot of code.  And some times poor performance is just plain sloppy code.  

SEO is a lot in  your control.  Some words hit better.  There is a lot of free information out there.  All the search engines have information on how to make your site more searchable.   Educate yourself on SEO.  The non-technical site is as important as the technical side.

So in the end it is code and you have some good answers on code review. 

What I suggest is even if you are not technical there is a lot in the process that is in your control.     

Control the keys to web site.  Don't let the programmer register themselves as any of the domain registration roles as they can hold you hostage.  Give them password / physical / certificate access to the site and be able to take that away.  Make a copy of the site before you give them access.  You can get a bad / unethical programmer that may take down your site.  Yes that should not happen but you still should protect yourself with a simple copy.


## Answer 7358

- posted by: [Rachel Collier](https://stackexchange.com/users/6961464/rachel-collier) on 2015-09-16
- score: 1

You can simply check if your developer is good by checking out the website worked for you. In checking, take a look and validate the code, if you see two or three errors in the page, assume that they didn't do a good work. Next is check the technical details. Lastly is to double check if the website displays correctly in the major browsers. If the website performs well in all those areas, you can say that your developer did a good and proper job. Actually there's much more. But these three steps are the basics of a good website. Therefore they are a good indicator if the developer is good and basically knew what they were doing.


## Answer 9352

- posted by: [Simon](https://stackexchange.com/users/8535473/simon) on 2016-05-29
- score: 1

<p>As you say, you want to show up on the search engine. 
The best way to do that is to focus on the SEO part of your website. </p>

<p>There are several faktors for SEO some of them are:
On-page SEO, linkbuilding, technical SEO and speed optimization. </p>

<p>You need to learn something about all of them. 
I can show you this <a href="http://generel-viden.over-blog.com/2016/05/how-you-write-seo-friendly-content.html" rel="nofollow">guide</a> about how you can get SEO friendly content. </p>

<p>But alot of people like you probably have no time at all. If this is the case for you as well, then I will suggest that you get in touch with a <a href="http://www.skaftekster.nu/seo" rel="nofollow">SEO agency</a>. 
It can be a bit expensive but I think the money are well given.  </p>



## Answer 3942

- posted by: [Roman](https://stackexchange.com/users/88863/roman) on 2015-04-05
- score: -3

In my opinion the question is irrelevant and wrong. It does not meter how much time the developer invested in the creation of what you need (it does not meter if it was really 12 hours or just 30 minutes). The main question is if you get what you need and how much money you are ready to pay for the implemented feature. In other words, the main question is: "How important (valuable) the implemented feature for you?" and not: "How hard was it for him/her to implement it?"



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
