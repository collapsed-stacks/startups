## What could be putting limits on user engagement?

- posted by: [Top Gear](https://stackexchange.com/users/4690596/top-gear) on 2014-09-20
- tagged: `customer-development`, `business-model`
- score: 3

My SaaS product extracts data from pdf files. Free trial gets users 10 free extractions. Paying users get 100 jobs. User logs into dashboard, uploads pdf, and downloads the extracted data. That is one job.

While observing 50 users so far I notice that the user engagement seems to terminate after they run the job for the first time. Even if it is successful. Some users run it a few more times but the result is the same, they leave and never come back or they come back run a job and leave again. Another observation is that 30 out of 50 users never created any jobs (they must label the pdf using the web app before extraction can happen, I explain how to do it in the demo video).

Even reaching out to all 50 users asking if I could help them, I got one reply. Here's what one of my user said 

> "Give that your subscription packages allow customers to run a certain
> number of jobs, it’d be important to me as a customer to know that I
> don’t waste jobs trying to figure out what data are captured every
> time and refining the same job until I get it right. "

Is limiting the free trial to 10 jobs per user be the cause of engagement terminating after running a few jobs? I reached out to the user to see how they would respond to having no limits.

Are people having trouble with just figuring out how to use the tool evidence by a over 60% inactivity? Whats more frustrating is that they do not respond to my email queries where I ask them if they need help.

I would like to study more about user engagements and creating a business model that will get users to engage with the product in order to reach a key activation metric to find value in the product.


## Answer 771

- posted by: [Matthew Haugen](https://stackexchange.com/users/1325646/matthew-haugen) on 2014-09-22
- score: 1

I don't know a ton about your actual software, but from what I've gathered over this question and your [previous one](https://startups.stackexchange.com/questions/753/how-can-i-make-my-product-economically-feasible), I'm starting to wonder whether you might want to adjust your pricing model.

More and more these days, modern applications--notably SaaS and PaaS--tend to work off of a pay-for-what-you-use model. Given your concerns about economically supporting the product with relatively high failure rates *and* the fact that the quoted user here seems worried about wasting uses, maybe you'd be better to charge on a per-use, satisfaction guaranteed model.

Alternatively (and arguably more ideally), you could charge a bit more and offer unlimited, extractions. By nature of software, I'm assuming it doesn't take much work or money from you to do a single extraction, so if you charged people $100/month for unlimited rather than $60/month for ten extractions, you'd likely have happier and more comfortable users, at little cost to you. Particularly if you don't expect most users to even do ten a month.

The choice between these two models isn't an easy one, and it would take some decisions by you. Both have marketing advantages over your current pricing (namely, you could either say "unlimited for just $100/month" or "pay only for what you use"), so the rest is mostly dependent just on how much it actually costs you (in your support time and presumably-server-based resources) to do a single job.

In general, though, I think switching to one of those is your best bet. Unless it's for storage, charging a set amount every night for a set amount of the product is turning into a legacy model, and users don't like it.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
