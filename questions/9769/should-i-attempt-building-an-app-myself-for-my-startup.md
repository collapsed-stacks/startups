## Should I attempt building an app myself for my startup?

- posted by: [Strife](https://stackexchange.com/users/5943228/strife) on 2016-07-25
- tagged: `mobile-apps`, `startup-costs`
- score: 4

I think my startup would benefit from having an app. There are many apps out there that are similar to the one I want to build, but none of them are really that good and there's definitely a demand-- I already validated the idea with my target audience. I cannot afford to hire a developer to build the app. So, I'm thinking about building it myself. 

I have some front-end programming experience, but my back-end knowledge is very limited. I know enough to build a simple & good looking website, but I've never built an app before. I'm thinking of *trying* to build the app myself and learning along the way. But, I'm not sure if that's a good idea, because it would be my very first app and I'll likely run into a lot of issues building it.

Should I attempt to build it myself? Or should I wait until I practice and learn more about the app creation process before I take on a fairly big project such as this? I'm a student, so paying a developer $40/hour is out of the question.


## Answer 9770

- posted by: [Community](https://stackexchange.com/users/-1/community) on 2016-07-25
- score: 4

_This answer is based on the fact that you are a student. I'm assuming you are young and lack any real serious professional skill either in technology or in another field critical to your business. If you are an expert at something critical to your business, ignore my answer and just go find a partner who can code. The following is advice for the young, financially-challenged, but driven student entrepreneur._

As an entrepreneur, to get just about anything done, you'll need to provide either time or money. Since you have no money, your only option is giving your own time. Assuming you have time to spare away from your studies, **yes**, you should build it yourself.

When you say "front-end programming," you could either mean JavaScript in a browser or you could mean designing with HTML/CSS. If you mean JavaScript, and if you're pretty good at it, you should be able to learn to build apps pretty fast. The fundamentals of JavaScript are very similar to just about any other [C-family language](https://en.wikipedia.org/wiki/List_of_C-family_programming_languages) (including Swift for iOS and Java of Android). Apps are really just front-ends, after all, just like websites. On the other hand, if your skills are limited to designing HTML/CSS, then unfortunately, you have a ways to go before you can consider yourself even a beginner programmer. Start with a learning-to-program book.

As for the back-end, there are really two distinct topics to learn: programming your apps and server administration. If you already know JavaScript, a natural progression might be to learn [Node](https://nodejs.org), which is just JavaScript on the server. It's basically the same language you are using now with some extra features to do things you can't do in a browser (like saving files, etc).  You can use a framework like [Express](https://expressjs.com/) to make things easier with Node. You could also go beyond JavaScript with languages like [Ruby](https://www.ruby-lang.org) (try the [Sinatra](http://www.sinatrarb.com/) framework) or [Python](https://www.python.org/) (try the [Flask](http://flask.pocoo.org/) framework).

As for administering the server(s), that part is tough to learn and you'd probably be better off abstracting the complexity away to start with a [platform-as-a-service provider](https://en.wikipedia.org/wiki/Platform_as_a_service#Providers) (tip: [Heroku](https://www.heroku.com/) and [Google App Engine](https://cloud.google.com/appengine/) are well-regarded but can be expensive to scale if you get big).

Now, if there's one thing you take away from this answer please make it this: you **must** develop actual software if you want to learn programming. Practicing little bits of unrelated code and learning without applying will get you absolutely no where. So **yes** start with this actual app right from the start (along with other apps you will work on while learning). However, don't treat this app or any other app you will ever code as a "big project." Programming is about taking many small, incremental steps. The first version of your app should be the name of your app and a close button (or some other tiny bit of progress). Keep repeating the tiny steps, adjusting as necessary, and you will become a successful programmer.


  [1]: https://nodejs.org


## Answer 9813

- posted by: [Q.Jones](https://stackexchange.com/users/8201155/q-jones) on 2016-07-29
- score: 0

<blockquote>
  <p><em>Should I attempt to build it myself?</em></p>
</blockquote>

<p><strong>Yes.</strong></p>

<p>If you're time rich and money poor, you don't really have a choice! But don't just jump straight into the programming...</p>

<p>Even if you had the money to pay a developer, I would at least wire-frame or mock up the app yourself to begin with. 
With a mock-up, you have a clear vision for what you want the app to look like, the functions of the app, how the interactions would work and so on. <a href="https://balsamiq.com" rel="nofollow">Balsamiq</a> is a great mock-up tool, or Google plenty of others.</p>

<p>Once the mock-up is complete (or complete enough to start development), then you can choose to develop it yourself or if its too complex for your programming comfort, you can farm it out to a developer, and at least they have an idea of how you would like the app to work. </p>

<p>The main benefit for programming yourself is that you save money whilst learning a valuable skill. An additional benefit is that you gain a greater understanding of the platform you're developing for, and any limitations or constraints imposed by the platform. </p>



## Answer 9822

- posted by: [HLC](https://stackexchange.com/users/6237396/hlc) on 2016-07-31
- score: 0

Would it benefit you to use an App builder? A HTML5 version will be a mobile friendly version of your site, (Although your site should be responsive nowadays) but this can defeat the object of producing an App, as you generally want a simpler version of your site.

Or a Native version, built to be accessed via various devices. 




## Answer 9825

- posted by: [Ram Segev](https://stackexchange.com/users/8806737/ram-segev) on 2016-07-31
- score: 0

If you already validated you idea you should start building an MVP yourself (I recommend you read "The lean startup",a must for every startup), when you'll start thinking of the MVP you will find yourself removing a lot of unneeded features and saving a lot of time and money doing so. I think that if you have some programming knowledge start doing it yourself and don't worry about the info-structure and building it right, cause you will change it so many times anyhow (just how it goes with startups:-) ) and if you struggle with a piece of code you always have SO, focus about bringing value to users at this stage (you don't need to build an info-structure that support 1M users before you have 1).
Go for it and good luck. 




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
