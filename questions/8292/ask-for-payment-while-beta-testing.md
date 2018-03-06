## Ask for payment, while beta-testing?

- posted by: [Mruf](https://stackexchange.com/users/3246202/mruf) on 2016-01-08
- tagged: `payment`, `testing`
- score: 3

We are developing a software, which requires a lot of user input. 

The process is more or less:

 - ask customer to enter some variables
 - create tasks for the customer, which are required
 - do a lot of back end things
 - execute valuable service and provide contents for users of our customer

We went from last to first. So we already developed an engine, which is able to do the backend calculations and provide the service. (So the last two points are complete, the first two aren't)

We want to test this service, but it takes a lot of time to set things up for each test case with real customers. We are already short on time. So, should we at least ask for payment?

On the one side, we invested a lot of work and time into this project. Also without our software, there would be custom development needed to offer equal functionality. So, there is a value, even while alpha- and beta-testing.

On the other hand, the product is not done. Paying for an unfinished software feels somehow... bad? But it is not the whole product. It's not finished. Still we are able to set options, (by setting flags in our database), solve the task by our self and deliver that valuable service.

So my questions are:

 - is it ok to ask for payment while alpha or beta testing?
 - how to communicate that?
 - any funny ideas on how to handle our time problem another way?


## Answer 8298

- posted by: [Matthew Haugen](https://stackexchange.com/users/1325646/matthew-haugen) on 2016-01-09
- score: 3

It's a matter of trade-offs.

By requesting payment now, you'll risk keeping your existing beta testers. That's bad for later on, when you want to charge for a fully-functional product, and it's bad for right now, when you lose people to help you build the fully-functional product.

By delaying payment, it sounds like you're risking your business directly.

The super simple answer (more easily said than done) if you're comfortable with the process and expense to get it going, is to look for investors. But I didn't figure that was the answer you were looking for.

----

On Windows Azure, Microsoft charges "preview rates," which I think are generally around 50% of the general availability equivalents. The percentage isn't all that important, but as long as you make clear to customers that they're getting a discount in exchange for helping test the software, I think that's a good model.

The trouble there comes up if you don't have a lot of new customers coming on board. If you depend on just a few loyal customers, it's difficult to start charging them for something they've been getting for free.

If you do have a lot of new customers, however, I'd be tempted to introduce that pricing model.

What I would do, in either case, is work toward some milestone (we're receiving positive feedback on more than *x%* of jobs). Once you're there, optionally change your version name (e.g. "alpha" becomes "beta," or whatever), then announce a new, discounted pricing model. They can't expect it to be free forever, and if they do, they probably aren't valuable customers to you anyway. I don't think you have to worry about how you announce it, beyond how you should always phrase public announcements well.

Ideally, just from a keep-people-happy perspective, announce it to take place in a month or two, so people have time to prepare. If the possible surge of people getting in free jobs while they can will hurt you, of course, you might get away with doing it immediately, depending on what your contract says.


## Answer 8299

- posted by: [Matthew Haugen](https://stackexchange.com/users/1325646/matthew-haugen) on 2016-01-09
- score: 2

I do think it's [okay to ask for payment during beta testing](https://startups.stackexchange.com/a/8298/59), but I don't think that's the only option.

---

You said paying for "unfinished software" feels bad. I'd argue that it doesn't have to be inherently bad, but paying for *buggy* software does.

One could claim that software is never finished. And I don't mean to spring a linguistic trap on you here (I know this might be what you meant), but do remember that.

Just because you aren't feature-complete, as long as what people expect to work does, most of the time, it's fair to start charging for it.

If you can start selling your fully-functional and mostly bug-free people-as-a-service implementation that it sounds like you've got somewhat in place now, that might not be a bad idea.

It's a bit different a business model than automating everything, but they work together nicely, and having that flexibility (if you can make it work financially) may let you scale into other sectors more quickly than you would.

Be it that or something else, I would definitely sit down and think about what you already have that's already working well enough to launch. If you have something you're comfortable with (and comfortable supporting as a paid product), don't worry if it's not exactly how you eventually want to do things. Definitely put thought into it, and don't launch just because a stranger on the internet told you do, but do try and take a step back. Sometimes our dream products are twice what customers really want, and however cool they are, it can be nice to launch with something that fills the need, then worry about making it really cool.


## Answer 8303

- posted by: [Austin Sanderson](https://stackexchange.com/users/6109645/austin-sanderson) on 2016-01-10
- score: 2

Asking for money when providing a valuable service is not a bad thing. However, what matters most is how you do it. One option is to include an investor page where you might ask for contributions towards the future of the business. Another option is to include and icon where people might donate a small amount for the service(always ask after the service has been rendered - not before). 

In either case, you want to frame it where the provider knows that they are helping the business grow and that their contribution is appreciated. In addition to that, you should sell the contribution as a development cost (not a profit) and be sure to explain to interested parties what the money will be used for first. Ask if a certain new feature would be beneficial enough to warrant an investment from them. Tell them that this would put them in the hat as potential investors/partners should the business succeed greatly. Be humble. Make sure you are actually adding value.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
