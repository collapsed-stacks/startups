## How can I pick which technologies to use for my IT business?

- posted by: [TapanHP](https://stackexchange.com/users/7167579/tapanhp) on 2016-07-09
- tagged: `tech-company`, `business-plan`, `business-model`
- score: 3

As a startup IT company, how should we select technologies to work with, in the interest of improving customer interaction? Is it better to work on trending technologies or should we trust running strong technologies? Newer technologies are coming out every day, so it's difficult to decide what customer will demand for, and switching on technologies is pretty difficult.


## Answer 9663

- posted by: [Ebrahim Pasbani](https://stackexchange.com/users/460651/ebrahim-pasbani) on 2016-07-09
- score: 4

You can't choose like this. All IT technologies are just tools to help you do your business. 

It depends on your business. You need to study your area market and choose some fields to start your business there. Several parameters are there to make decision about which field is good for.

For last step you can choose your IT technologies. 

For example if you want to create a social network, maybe your technologies are : node.js, mongodb, redis, ember.js, react.js.

Or if you want to create a core banking solution, maybe your technologies are : javaEE, oracle/postgresql, spring, ...

You see, choosing technologies depends on your business. 


## Answer 9692

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2016-07-12
- score: 3

> As a it company startup how should be selection of technologies to work on that it will provide high customer interaction?

**The biggest disservice you can do to your startup is picking a stack you're unfamiliar with.** It means you'll be fighting two battles: the usual one where you need to become familiar with your market; and a bonus (?) one where you need to learn your stack. Don't do that.

Pick one from the ones you're competent with. It's really the only thing that counts. All else being equal, look for things like "how mature/scalable/what have you" but also look for "how cheap is it to find someone competent in this stack" and "how smart are the typical people who actually use and know this stack".

Mind your market, too. As already highlighted, some sectors are voracious for techs they're familiar with and know how to maintain (e.g. Java/Oracle in fintech). In the case of banks it's in part because of Java's merits compared to techs at the time, in part because they all switched from Cobol at around the same time, and in part because there's no shortage of candidates with the requisite skill set in the job marketplace. Whatever the reason though, it matters. (And yes, there are always exceptions. But keep it in mind, because it can be an extra blocker for sales.)

> Also I want to know if it's better to work on trending technologies or should trust on running strong technologies?

Mature oftentimes (not always, but oftentimes) beats new in my experience.

Taking my introduction to Node.js as an example (admittedly a non-representative one), when Node.js came out in ~2010 or so, I recollect trying it, and getting vividly excited like a lot of other geeks on the web. But upon scratching beneath the surface I was like, seriously?!? The problems related to the architecture were gross (non-blocking io is cool and all but if it's a single-process thing it's not a silver bullet either), the libraries were either non-existant or half-baked and very buggy, there were no frameworks to speak of, the community seemed to all be filled with a handful of competent devs and _a lot_ of much less competent devs or semi-devs, I knew a thing or two about callback hell already... The list of gotchas went on and on, and I thankfully knew better by then to wait and see before giving it a more serious second look. (I've yet to do so.)

If you allow for a slight tangent, [always code as if the guy who ends up maintaining your code will be a violent psychopath who knows where you live](https://stackoverflow.com/q/876089/417194). Much the same goes for your stack choices. So when in doubt, stay clear of new tech - even more so if you're unfamiliar with it. (Also, yes: learn a new language per year. But don't make it a point to actually use it in production.)

What actually counts in practice is competent and mature library developers who own what they're doing and are happy owning it. Insist on the latter because, to borrow the words of Yossi Kreinin of C++ FQA fame, if a module's owner doesn't like it, [expect some pretty lousy bug gardening job](http://yosefk.com/blog/redundancy-vs-dependencies-which-is-worse.html). (Competent in my experience typically rhymes with 10+ years of experience - there are unicorns out there but they're far in between.)


## Answer 9702

- posted by: [Shashi Penumarthy](https://stackexchange.com/users/152747/shashi-penumarthy) on 2016-07-13
- score: 2

There are a couple of assumptions you've made that I believe you need to step away from:

 1. That the technology choice will make or break your startup. 
 2. That switching technologies is pretty difficult.

If you are just starting out, you actually have the least amount of information as to what your business is really about. Even if you feel you are quite clear about what you want to do, experience, market trends, an evolving customer base, customer response and of course funding sources and so many other factors will end up influencing the direction of your startup in ways you may not have foreseen. You will probably want to be open to those changes instead of letting the technology determine your business.

At this stage, you are best going with a technology stack that is easy to prototype with, easy to make changes to, easy to deploy and easy to demo. You're going to need to this to convince your investors/potential customers that you can execute and operationalize your idea.

Many big companies today such as Twitter or Gilt started off as monolithic Ruby on Rails applications, as customizations to an existing system like Django or were written in Perl (Amazon). I myself once led the creation of such an early stage product using the Plone CMS (Python & Zope) over a few months. It was great for iterating, prototyping, testing out ideas. The CEO of the startup and myself had something new to show investors and potential customers every week and adapt and evolve based on their feedback.

That system, just like Twitter or Gilt was completely re-written (more than once) as the needs changed. If your product is successful, you will have problems of scale like you wouldn't believe and you will need to re-write it in a different way. Many companies that started with Ruby on Rails ended up using, for example, Java & Scala with Microservices, Containers and Stream Processing APIs like Apache Kafka all running on the cloud. That's not what you want to worry about at this point. There are amazing software development teams all over the world that can help you get there when you are ready. 

Even your front-end UX needs and the way you deliver that experience can shift significantly. You may even add or change platforms (desktop, web, various mobile devices) or add a component that involves real-world interactions like sending people packages (think Amazon or the Netflix DVD business).

Of course, all this assumes you are not going to pick a dead technology like Microsoft Access, unsupported platforms like Adobe Flex or technologies that are not preferred by developers such as VB.Net.

The best way to learn about technologies is to meet developers and people with experience in person. Find people in tech at meetups or user groups, describe to them your product or idea and ask them how they'd build it. You'll see a pattern emerge and you'll be able to make an informed decision. You might even find a developer or two that is passionate about the same things you are and gain a valuable resource that way.


## Answer 9664

- posted by: [D J Sims](https://stackexchange.com/users/7242000/d-j-sims) on 2016-07-10
- score: -2

For scaling databases:

- Cassandra
- Thats about it...

For scaling the front end:

- Node.js
- HTML with Javascript and bootstrap

For scaling the backend:

- Spark
- Storm
- Zeromq 
- Kafka

For alerting and traceability:

- ELK stack
- Elastalert
- MR/MapReduce

For programming languages:

- C++
- Scala
- Anything Java based

You shouldn't have any scaling problems if you use these.

Definetly don't use new technologies that haven't been around for at least five years.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
