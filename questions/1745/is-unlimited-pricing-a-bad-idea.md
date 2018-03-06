## Is unlimited pricing a bad idea?

- posted by: [Top Gear](https://stackexchange.com/users/4690596/top-gear) on 2014-12-25
- tagged: `pricing`, `saas`
- score: 10

I have a SaaS that lets people extract data from movies. It is resource intensive and the more amount of work they bring the more it will cost me in terms of time, working with them, and etc.

I offer an unlimited video processing plan for my small, medium, large plans. Is this a horrible idea? There is no reason for someone to move off the small plan into a medium plan. 

Should I limit each plan by features instead and keep the unlimited processing?

Or should all plans have the full set of features but different quota of the number of videos they can process every month?

I've had some user say they will stop using my service if I remove the unlimited processing. This was their big reasons why they are using my service according to them. But some customers demand is just extreme for what they are paying (very little). Should I just tell them to go away?

In some ways I ended up getting customers directly from my competitors because of the unlimited processing. Is it too early to say this is working or this isn't working?

Cheers.


## Answer 1746

- posted by: [Matthew Haugen](https://stackexchange.com/users/1325646/matthew-haugen) on 2014-12-25
- score: 9

This is somewhat difficult to answer without more intimate knowledge of your product, but when I'm pricing things nowadays, I tend to look at a pay-for-what-you-use model, over anything unlimited.

I'm not a particular fan, as a business owner, of unlimited services. They're just unfair for everyone, as I'll get into in a bit.

In your scenario, I would probably try to charge $*x* per movie.

That definitely has some pros and cons, which I'll get to in a second, but whether you go with that or not, calculating out an approximation for *x* is pretty important. It sounds like you already have a good user base, and with it, a good usage history. So if you look at how much on average you seem to get per user per time period and how many movies they process in that time, that'll probably make it pretty clear whether this is reasonable or not.

You have to assume that you pay for resources. Whether those resources are on-premise or in the cloud (it sounds like the load here is on the server?), your price will scale more or less linearly with the resource usage.

# User backlash

I know you mentioned that some users would be upset if you moved to a limited model, but that just gives you a good opportunity to "grandfather them in," or in other words, give them unlimited for as long as they choose to remain with you. If they continue to pay you, they'll continue to get unlimited usage. Worst case, they leave and you stop losing money on them. Best case, you lure them into wanting to stay on, even if they become less certain of their need for some small amount of time.

As for other users, the argument I like to make is that by charging per movie, you both get the best deal. Otherwise, one of you is losing money, and since you're setting prices, it'll probably be them. Chances are extremely slim that you'd price it perfectly to what they were going to use, which means they're either paying way more than they want or way less. If you can phrase it right, you can make it sound like (since you actually are) you're doing them a favor.

#Pros and cons

Ultimately, the major pro then is that price scales with use, and that applies equally to you and to your customers. 

That said, it's not a perfect system. Per-movie pricing isn't particularly "sticky"--if someone isn't roped into paying per-month, they might not come back. Beyond that, some users will feel like you're nickel-and-diming them out of money, which isn't a good feeling.

# Implementations

Fortunately, there are some other models that work off of the same central philosophy, but shift around the disadvantages. I haven't mentioned your feature differences yet, so here's that too.

* The most basic implementation is pretty well what I've said. You give everyone all of the features, and they pay a constant rate per movie.
* A tad more complex, and something I do for one service a business I'm in offers, you can have bulk pricing. "$10 per movie for just one, $8 per movie if you buy 10 credits now, $5 if you buy 20," etc.. You'd still give everyone the same features, but this way you attract them to stay on a bit longer. Of course, in your particular field, I'm not sure how often people want to deal with bulk movie processing.
* A little more complex, you could do the same thing as either of the two previous approaches, but have different pricing for different features. I don't know what features you offer, so this may or may not be relevant, but I imagine "feature A for $5 per movie," "features A and B for $7 per," etc.
* If you're worried about stickiness, you can do a hybrid of what you're saying and this. Have your feature levels laid out, then for each one, say $*x* per month with *y* credits, then $*z* for each additional credit after that, where *x* and *y* scale proportionally together, and *z* scales inversely (they pay a lot, so they get a lot of credits and a lower rate after they run out). It probably sounds complex with my phrasing here, but really it's not different from what you're saying, but with limited allowances. For example, you might charge "$10 per month for 2 movies with feature A, then $5 additional after that, or $20 per month for 8 movies with features A and B, then $4 additional after that."
* If some users do need unlimited, you can add on another level that charges a lot more. I'd avoid that if you can, but sometimes you just need to offer it.
* On top of any of these, you can also decide whether to make the credits expire or roll-over. I'd be tempted to have them not expire in cases of bulk purchasing, and expire for month-to-month stuff. But either way has merits that you can decide upon.

# Conclusion

Ultimately, I'm just a fan as a consumer and SaaS provider of the pay-per-use model. I think it's clean, easy to understand, and it gives everyone the best price. But if you're worried about losing current or future customers and you aren't actively losing too much money right now, it might not be a bad idea to hold off and see whether after a few months it all evens out.


## Answer 1747

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2014-12-25
- score: 7

It's a bit hard to answer without more specifics on what you're doing exactly, and who it caters to.

First off, two of your side questions merit a short and immediate answer:

> I offer an unlimited video processing plan for my small, medium, large plans. Is this a horrible idea?

Yes, it's horrible. Starting with the plan names, in fact. **Plan names count.** It's not unheard of for an enterprise client to shift to a more expensive plan because a line that reads "Hobbyist" or "Small Business" looks absolutely awkward in a budget while "Corporate" or "Enterprise" does not.


> I've had some user say they will stop using my service if I remove the unlimited processing. (...) Should I just tell them to go away?

In short, yes -- give them the boot. (But read on.)

---

With respect to your pricing strategy, Matthew has already expanded on the case for *per movie* pricing, so I won't elaborate on it any further than saying that if your variable prices are high enough, you should very seriously consider it.

What I'd like to focus on is your marketing, because you're giving the impression that your prices are too low: you absolutely *need* to segment and understand your users. Note that what follows might invite you to refocus your efforts and cater to an entirely different set of users. 

## Segment your users

### Which of your users are valuable?

Identify good client segments: those who actually need your service and are more than willing to pay for it. Identify bad client segments: those who are wasting your time and resources, or inundate you with support issues, while providing little material benefit on your end.

(Don't discard word of mouth as an upside. Hobbyists that bring near-zero profit might be talking about you every day in forums. In fact, you might even want a *free* tier for that reason alone.)

### Bad client segments

The bad client segments will often have this in common: they perceive your full service as something they're entitled to while paying little or nothing. It is easy enough to handle on paper: erect enough of a price or feature barrier that they won't come.

Consider whether any or all of them can be salvaged before executing this. How big a price increase or feature decrease will make it so that they become worth your time?

### Good client segments

The good client segments will often have this in common: they perceive your full service as valuable and well worth their money. If told to jump as a group, your best clients are those who will want to know: "How high?" What you need to determine from there is: how high *can* they jump?

## Define and price your tiers

### B2B SaaS products are often underpriced

Keep in mind here that scores of B2B SaaS products are woefully underpriced. More often than not, they charge **pocket change in comparison to the salary of the employees** in charge of making use of it.

The reason is, they're typically run by engineers who forget to hire a marketer very early on. The engineers end up setting the price *they* would pay, which is to say roughly zero -- it's "just time." (If you need an example of how ludicrously wrong they can be, recollect how techies laughed at Dropbox on grounds that the same can be set up for yourself using OSS and some duct tape.)

(If anything, a better pricing strategy for many a SaaS startup would be more along the lines of: What's the highest figure we can think of without laughing out loud saying it? The price elasticity is quite flat.)

### Identify the upside you deliver

Now, ignore your SaaS competitors' prices for a moment.

Can your good clients even do what you're offering without your service? If so, think in terms of cost savings: how much would they save by extracting the same data using alternative DIY solutions. If not, think in terms of added value: what financial benefit do they get from using it?

Is their financial upside $1 per movie? $5? $10? $50? $100? More? Ask them.

Price your higher tiers accordingly. And no, by all means, don't offer unlimited plans if your variable costs are anything material.

### Segment tiers by requirement

Your tiers should additionally reflect who they're catering to. What does a typical hobbyist need? A small business? A medium business? An enterprise?

Slice the tiers, with seats, features, number of movies, value-added services, and so on accordingly.

The cheapest plans should only be acceptable for a hobbyist or a client that rarely needs your service. The largest plans should give no second thoughts to clients that constantly need your service and derive well understood value from it. Again, make sure you *do* understand this value.

A hobbyist or a small business here or there needs more than what's in the plan? Cool: they'll get a larger plan. Or go elsewhere -- and cost your competition money.

### Avoid the wholesale price trap

Lastly, be wary of the wholesale unit pricing trap as you price higher-end tiers. With appropriate enough added-value with each tier, decreasing the per unit price can make very little sense. Yet again, be aware of *what* that upside is from the client's standpoint.

## Compare with your competition

Only then should you consider what you're up against in terms of SaaS competition. Compare the offers *from the viewpoint of clients that you actually wish to close.* Do NOT do feature to feature or price vs price comparison. Think of yourself as your target low-, mid-, or high-end SaaS buyer, and wonder if you'll get the *value* that you're looking for with yours vs theirs.

Tweak your tiers if applicable, keeping in mind what you offer that they don't and vice-versa, the quality of your respective services and onboarding experiences, and -- most importantly -- how compelling your respective marketing copy and sales arguments are (e.g. [excellent](http://close.io/#pricing) vs [terrible](http://www.salesforce.com/crm/editions-pricing.jsp).)


## Answer 1754

- posted by: [Paccc](https://stackexchange.com/users/441027/paccc) on 2014-12-26
- score: 3

I think the other answers here (by @Matthew and @Denis) both have very good analysis of your situation, but I wanted to add one more suggestion to that. 

One option would be to set the price of the unlimited plan higher than it currently is, but offer credits back to the user based on low monthly usage of the service. For example, if they only use 5 hours of video processing time this month (assuming the average is 100 hours), then give them 1 free hour of processing time on your faster 8-core server for the next month.

I don't know how your service is priced, so maybe that example doesn't make sense for your situation. One advantage of this option is that by giving them credits to use the premium features of your service, it gives them a reason to come back and use your service again, with the goal of having them develop a habit of using your service.

You have to find the right balance of what kind and how much of the credits to give back to the user. You don't want to incentivise the customers NOT to use your service! :)



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
