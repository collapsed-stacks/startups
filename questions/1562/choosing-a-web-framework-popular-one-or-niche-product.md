## Choosing a web framework: popular one or niche product?

- posted by: [Thomas Weller](https://stackexchange.com/users/222412/thomas-weller) on 2014-12-05
- tagged: `website`, `web-development`, `low-capital`
- score: 3

**TL;DR**

Since the question "How to decide for a web framework?" is probably too broad for a SE network site, the question which I can't get my head around is:

- The top ten well-known frameworks are probably robust, performant and well tested
- A niche product could much better suit my needs, I could get direct contact to developers and benefit from their enthusiasm

What pros and cons can be seen in these two types of framework so that a startup can make a better decision? At the moment, they are equally weighted.

**Details**

I am a programmer, but haven't done much web-programming. However, my idea would need a specific web-site. At the moment, this is a single-person company. Since a few weeks already, I'm 

- trying to figure out which frameworks would match 
- how fast I can understand the concepts
- how active the community reacts on questions and bugs

Of course I have already limited the number of frameworks by requirements such as

- has REST support
- provides database mapping
- is free (open source)
- ...

Luckily but also unfortunately, there are so many web frameworks available, it's not just a matter of deciding between a small number of frameworks. Since I'm employed in parallel (full time), I evaluate frameworks in my free time only, which takes long.

I also doubt that I explain my situation to a consultant and let him decide. The consultant will also have limited knowledge and potentially recommend a framework that he's most familiar with ("golden hammer" advice).

I already tried to add more requirements, but it starts becoming artificial and maybe I exclude a good framework that way.




## Answer 1565

- posted by: [joslinm](https://stackexchange.com/users/91414/joslinm) on 2014-12-06
- score: 3

Always the popular one. Think about it in terms of input and output. What input goes into learning a new web framework? Learning and coding. Choose the one that is most popular because it'll make both of those tasks way easier, which in turn will fuel your output.

In my opinion, you should choose Ruby on Rails or Node.js. These frameworks have large communities, so if you hit a programming problem, or need guidance, or a dependent library, you'll have the most success with either of these. 

EDIT:   

I'm amazed I see an answer that states "it ultimately doesn't matter most likely":

That's just wrong. Of course it matters. Let's go over some real world problem solving:

* When it comes time to deploy, how easy is to deploy your language? With Ruby, node.js, php, or java, deployment is easy over Heroku. Deciding to go with cool, niche language? Have fun deploying it yourself. 
* When it comes time to hunt down a bug, how many other people have probably gotten the same one? With the popular language, you can probably google your error code or whatever question you're having and find many resources. With cool, niche language, you're going to have to hunt that down yourself
* When it comes time to create a new feature, how many other people have created something like it and have written blog posts, guides, or even wrote completely dedicated libraries to the very feature you're looking for? With popular language, probably a lot of people.
* When it comes time to expand, how many people will be familiar with cool, niche language vs popular language? How will this impact hiring?
* When it comes time to ask the community about something you just can't understand, how wide will your listening audience be? 

And so on and so on... At the end of the day, if you're intent on building a product and shipping it, you go with the safe, popular choice because you're trying to avoid unnecessary risk. Choosing a niche framework is just that -- an unnecessary risk. 


## Answer 1587

- posted by: [Shauna](https://stackexchange.com/users/276547/shauna) on 2014-12-09
- score: 3

Frankly? Just like languages, it ultimately doesn't matter most likely. Pick one and go with it. Usually, you'll pick based off of familiarity or ease of learning, anyway.

I don't entirely agree with the "always go with the popular one." Popular does not always equate to good (or good for your needs).

The big, popular tools are also prone to feature bloat. They become popular, so they appeal to a wider audience, the wider audience has more input, the maintainers try to keep including things to keep their popularity. The little upstarts tend to be leaner, having only added the things the team has identified as necessary. Either of these could be a pro or a con, depending on your needs. If the little tool doesn't have what you need, then it's not useful to you, but the big tool may or may not be overkill.

The niche tools are more prone falling off the face of the earth, since they are usually only maintained primarily by one person working on it in their spare time. However, they might have cleaner code that you can maintain yourself if necessary. The popular framework may not go anywhere, but there may also be more chaff to weed through to get the high quality things (examples, plugins, etc).

As I said, the same goes for language. Ruby is a great language, but shared hosts don't usually support it, so you'd need to know how to stand up your own Ruby-capable web server. So, if you don't want to manage your server, you are likely to need to go with a language (and therefore, the language's frameworks) that is supported by the host you're using. 

My recommendation is to sit down and think about the features you need and want, both technical and personal, and write them down (and sort them by deal-breakers vs nice-to-haves). Then, go and find one that best fits those needs.


## Answer 1591

- posted by: [Esqarrouth](https://stackexchange.com/users/3055586/esqarrouth) on 2014-12-10
- score: 0

A niche product will probably suit your needs better, but it will be more buggy, slower, hard to learn, has lack of documentation, has lack of content, updated slower. 

Especially if you haven't done much web-programming I would stick to one of the most popular frameworks. Typing that "stupid bug you have no hope of solving" into google and seeing the fix in the first result is priceless. Whatever pros they have, this outweighs them all.



## Answer 1605

- posted by: [Bugra Balci](https://stackexchange.com/users/3843228/bugra-balci) on 2014-12-12
- score: -1

Did you try any of them? I feel you might find useful those since you are a single company for now.
  
Google Web Starter Kit  
Zurb Foundation v5+  
Semantic UI  
Ulkit  
Bootstrap v3.2  
Ink Interface Kit  
Maxmertkit  
Concise  
Metro UI CSS 2.0  
Skeleton  
Kube  
Responsive Grid System  
Pure by Yahoo!  


***Best of luck!***



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
