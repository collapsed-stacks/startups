## To launch or not to launch - thats the question

- posted by: [Monacco Franze](https://stackexchange.com/users/4766136/monacco-franze) on 2015-03-02
- tagged: `launch`
- score: 11

I am currently building a product and after some weeks it's now running.
Due to my limited coding skills in some languages used, (mainly SQL) it does the job, but the code is - nicely put - a mess. It does work though, and that pretty good. 

The question is :<br />
*Should I launch the product (which is probably going to generate some attention - my friends are pretty much begging for a beta) now or later, with improved code?*

Right now, I don't have multi-threading implemented, and I don't have the skills to do it. It would only affect the performance, if the site generates more than 1000 hits a day.

**Pros:**

* Getting experience with user behaviour
* Having a product to show to skilled programmers
* Generating attention

**Cons:**

* Messed up start if server/service breaks down.
* Idea ist out in the wild, ready to be stolen and coded in a better way










## Answer 3576

- posted by: [A E](https://stackexchange.com/users/5191744/a-e) on 2015-03-02
- score: 7

<p>Launch it, because  that way you'll begin to learn from the users. </p>

<p>You'll start to get an idea of what you need to change.</p>

<p>Then as you make the necessary changes you can improve the maintainability and efficiency of the code-base.</p>

<p>Remember that users don't care what the code looks like, and that (particularly in these modern days of cloud computing) simply upscaling the hardware is often cheaper than the developer time it would take to make the software more efficient. That's doubly true on a very early version of the software which will have extensive changes made to it anyway - there's no point in making it perfect when large chunks of it will be thrown away.</p>

<p>Concerning this point:</p>

<blockquote>
  <p>Idea is out in the wild, ready to be stolen and coded in a better way</p>
</blockquote>

<p>If the only thing that makes the business defensible is keeping it secret - i.e. you're relying solely on <a href="http://en.wikipedia.org/wiki/First-mover_advantage">first mover advantage</a> - then that's a problem in itself. You're going to have to go public at some stage in order to get customers/users. You need some other competitive advantage beyond secrecy of the core idea.</p>



## Answer 3575

- posted by: [blunders](https://stackexchange.com/users/216182/blunders) on 2015-03-02
- score: 5

Yes, you should launch the app, and learn as much as you are able to learn from it.

> **"...but someone might steal the idea and..."**

No one is going to steal your idea, ideas can't be stolen. 


## Answer 3578

- posted by: [guillaume](https://stackexchange.com/users/1961248/guillaume) on 2015-03-02
- score: 3

Launch a private beta with your friends only. Not that you should really be afraid of someone copying you, nobody is going to drop what they're doing to focus on cloning your app unless it's a huge hit and a couple of months won't be enough for you to get prepared anyway. But it's safer to iron out bugs with people who will forgive anything. Nobody likes buggy software. Then go to invite-only or directly to public beta.

1000 hits/day is nothing (1 visitor every minute or so? I hope requests don't take 60s to respond) and the wrong thing to measure. 1000 concurrent users at peak time is, I believe, easy with a beefy server depending on what you're doing.


## Answer 5203

- posted by: [udeme samuel](https://stackexchange.com/users/1959602/udeme-samuel) on 2015-05-06
- score: 0

<p>I love this topic so much because my startup (<a href="https://www.crunchbase.com/organization/jobinpal-enterprises" rel="nofollow">Jobinpal Enterprises</a>) too is facing this issue, we are about to launch a product (<a href="http://popibay.com" rel="nofollow">popibay</a>) but the time is due for the public beta when the private beta has not been done.</p>

<p>The analytics is showing good results of page views from our users but the main features of the app has not been completed, so we decided to scale from a small to large over time.<br />
So right now we are seeking for donations.</p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
