## Managing fixed costs of a stagnant mobile app

- posted by: [user3915477](https://stackexchange.com/users/4853890/user3915477) on 2016-10-25
- tagged: `mobile-apps`, `business-model`, `revenue`
- score: 3

I'm developing a mobile application that will generate revenue through the purchase of downloads. No ads, no in-app purchases, just purchases of the app itself. If the number of active users is above a certain quantity, there comes a monthly cost associated with the backend database service (BaaS) that the core feature of the app is built around. The more people using, the higher the monthly costs of utilizing the BaaS. 

My problem is this: If every consumer in the market for this app buys it and uses it avidly, how do I prevent that revenue from bleeding away to zero due to the constant monthly costs of the BaaS. 

It seems to me that the only economical thing to do is to sell as many downloads as possible until the rate of new download revenue falls below those BaaS costs, and then cancel the BaaS service altogether. This will ruin the value of the product to those that bought it, but it will protect the revenue that was generated from being eroded. I can't think of any suitable alternatives to this.


## Answer 11420

- posted by: [Jeremy Parsons](https://stackexchange.com/users/497810/jeremy-parsons) on 2016-10-25
- score: 1

If that's your way of thinking, why do I want to be your customer?

You really have three common options to pick.

First and generally wisest if you're expert at getting purchases, **make new apps to sell to your customers**. New products to existing customers is the low risk route, and the cool thing about apps is that with care, you can market in a low friction, ultra low cost way. The lifetime value (LTV) of each app sale can be 1x your original app, or if you work hard, 5-10x.

Second best (in my opinion) is **don't worry, but keep an eye open**. As you know, very few apps are used more than a few times, or for more than a few months. If you've got nothing more for your customer, the usual decay cycle will solve your hypothetical profit and loss issue.

Then, you can consider the option to **sell while you're ahead**. Suppose you have some of (1) a large user base; (2) an evidenced current profitable customer acquisition process; (3) transferrable IP (code and other digital assets, plus relationships etc). Then that has a value to someone else that's substantially higher than the value to you, because you're only in it for the initial app sale, while they may be interested for all kinds of reasons.

Clearly it's the job of a BaaS platform to be indispensable. But in truth, BaaS saves you time and effort in exchange for recurring cost. Because you're asking the question, I'll guess that if you take the BaaS away, the work that leaves you with isn't worth the effort. So before you launch in future, you need the discipline of trying to **create a good estimate of the average lifetime cost** of the BaaS (factoring in its pricing method, churn rates etc) and making sure you have plenty of headroom in the lifetime value - which right now is your income from selling the app once.


## Answer 11986

- posted by: [DukeZhou](https://stackexchange.com/users/4146639/dukezhou) on 2017-01-25
- score: 1

I think that if the app is useful, and the customer base comes to rely on it, you could gently transition to a subscription model once you reach a critical mass of users.

This would maintain the value of the product for those who find it useful, but defray your back-end costs in a way that is fair. 

If the majority of the customer base rejects the transition, it at least provides the rationale for shutting down the product.  

Conversely, a mass exodus might put the numbers back below the the level where it costs to maintain the app, and give you some breathing room to rebuild the customer base under new monetization model.







---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
