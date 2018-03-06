## Handling price objections, deep discount requests?

- posted by: [Top Gear](https://stackexchange.com/users/4690596/top-gear) on 2015-01-09
- tagged: `customer-development`, `pricing`
- score: 6

So I am running into a lot of similar situations where:

Prospect loves my SaaS and the tool, sees a ton of value but says they won't pay more than low double digits per month for it.

Common reasons include their supervisor is stingy, they are able to use teams in India etc.

My software has already saved thousands of man hours for customers who are paying the full price, and for these folks they don't seem to object to the price, rather they understand that the software saves them time. 

How do I respond to these price objectors who demand a whopping 86% in discount, yet interestingly enough they are the MOST demanding when it comes to support and feature requests.

"Oh but I can get someone in India doing it for $2/hr to do it for me"

Are these people simply not a right fit? Should I drop them? IF so, how would I tell them that they might not be a good fit in a polite way?

OR is does this signal a poor market-fit of the product and the price needs to drop? 

I just don't understand why the current customers paying the full price are so happy while the new prospects seem very stingy and selective, even after claiming they see the value and the time it will save them.

If saving 100s of hours is worth very little to someone, doesn't it mean that their time is probably worth very little? Where as someone who's time is worth a lot (executives, managers) saving 100 of hours would pay off greatly? 



## Answer 2929

- posted by: [Jeremy Parsons](https://stackexchange.com/users/497810/jeremy-parsons) on 2015-01-09
- score: 4

This may be a great opportunity to provide a new value proposition to address a customer group and grow your top and bottom line. Or it may just be a *false objection*.

**False objections are just the things people say instead of buying.** They often have logic, but that doesn't make them true. And until you probe further, you don't know if this is a sales issue (the prospect is bailing out, but this was a sale you could have made) or whether it's really a 'no'.

Your diagnostic question is something like this. **"If I could offer you the service with some limitations with fixed fees below $$, would you go ahead?"** If the wriggling just changes, stop wasting your time. But a "yes" tells you that perhaps there's a second market for you.

My pricing mantra is, **the *right* price is the *highest effective* price**. From what you've said, there's a significant market for you at the full price, and there are some negatives beyond pure revenue at lower price points, so you probably shouldn't be lowering your general pricing.

That leaves the possibility that you can construct an offering carrying different pricing, that will co-exist with your general pricing. We need to look at two cases.

The first case, which is excellent where it works out, is where you can **offer a single product at multiple pricings**. Often the best way to deliver this is to vary not just the headline price, but the price structure. The optimal outcome right-prices the service for each distinct group while minimising negative effects such as encouraging customers to "downgrade."

Beware taking prospect talk at face value, but for the purpose of illustration, here's a possible route.

You could offer a fixed cost at the "under the supervisor's radar" level, but with measured usage - number of uses, or hours of use, or data processes, or whatever you can sensibly track. Taking your support point (not unique to you - it's widely observed that customer who pay less ask for more!), you may also want to premium price support to these customers, or offer a significantly lower SLA. 

If I'm experimenting with pricing like this, as a safety barrier I will generally look for a few ways to become mildly "annoying" without actually damaging the function. For instance, I might feature "Economy Edition" prominently in the UI and in output screens, files and logs; I might find some places where I can slow down the journey through the utility; I might expire sessions more aggressively. These tactics are about reinforcing two different ways different customer groups can be smart - by using a great tool that delivers real value and saves money; or by getting a huge (perceived) saving in exchange for some ongoing hassle.

Sometimes, though, you have to carry that a step further, and **offer distinct value propositions with distinct pricing**. Doing this effectively means dissecting the use cases and the value drivers. I'll illustrate, but I'll have to make a assumptions where you should be using best data.

So you are indicating that your primary value driver is time saved. And you're also saying that the low-price prospects are, essentially, valuing their time differently. Let's say that core customers value time saved at $100/hour, economy customers at $10/hour. So on principle, if you offered a version of your SaaS that took more user-hours to drive, and took more elapsed time to deliver results, you could price at a fraction of the core product, while delivering best value to each group.

This is logical and attractive, but in my experience it's often unsustainable, for a variety of reasons. So I would normally try and work down through secondary value drivers. (This is hard work, but it does pay off.) You are looking for drivers that have relevance to each group, that are at least partly orthogonal, and that are as straightforward as possible to deliver differential service or/and pricing. 

For mass-market services, this can get pretty subtle. But where what we're really doing is simply putting more distance between a high-priced and low-priced product, you can be crude. My rule of thumb is:

* If the secondary driver is <15% as important as the main driver, work on delivering the minimal acceptable service and no more for the secondary value prop, with zero optionality

* If it's 15%-75%, it's a strong candidate to introduce as a second price lever - with (relative to base pricing) high additional fees for better service

* If it's >75%, consider making it the lead element of the value prop as communicated online

These techniques can be extremely powerful. But if you're at an early stage, I'll usually advise startups, especially if they're bootstrapping, to keep a tight focus on customers who are a better fit while the product is developing and you have a small team and a viable funnel. That said, I've seen a lot of startups fail to maximise their potential because they keep things simple too long!


## Answer 2944

- posted by: [rob](https://stackexchange.com/users/19190/rob) on 2015-01-09
- score: 2

<p>This is a common tactic. Don't cave in, but offer some alternatives.</p>

<p>If this is an important customer, you can offer a less feature-rich version of the product at the lower price. Ideally you would have a bunch of options or features that you can flip on or off to satisfy the customer's budget.</p>

<p><strong>It may not be that your price is too high, but that it's too low</strong></p>

<p>As nonsensical as it may seeem, sometimes it's not the price that's important, it's that the customer is receiving a discount.</p>

<p>Several years ago we had a large customer whose purchasing agent refused to buy our product unless we offered a major discount, even though the company's own ROI study showed that our product was a home run and would save more than half a million dollars in a very short time--in other words, during one of this customer's production cycles, our product would pay for itself many times over. I discovered that this purchasing agent was actually contracted from a separate purchasing company to negotiate the purchase on behalf of our customer. She was operating under very strict terms and had to show on paper that she negotiated a discount. At the time we were already planning to increase the price, so we ended up raising the price and offering the old price, which effectively showed a significant discount. The so-called price objection was now addressed.</p>

<p><strong>You can't win them all</strong></p>

<p>Unfortunately in the end I actually had to refuse the sale because the company's initial purchasing agreement included a number of ridiculously draconian terms and the customer's legal department was on vacation until past the end of the purchasing window.</p>

<p>More recently, a customer wanted an enterprise-wide deployment but this time demanded an outrageous 90% discount. It is common practice in the industry for contracts to include a <a href="http://itlaw.wikia.com/wiki/Most_favored_nation_clause" rel="nofollow">most favored nation clause</a> and offering a 90% discount to this customer would have potentially required us to give massive refunds to other large customers. We offered some very generous alternatives, such as a generous discount (but far smaller than 90%), or letting them purchase the number of seats that fit into their budget, and giving free licenses to the rest of their users for a year or more. This way, they could spread their purchase across multiple years while getting all the benefit up front. Unfortunately negotiations came to an abrupt halt because the customer wouldn't even consider any of the options we offered.</p>

<p>In the end, a lost sale is better than a bad sale which could potentially ruin you.</p>



## Answer 2930

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-01-09
- score: 1

> How do I respond to these price objectors who demand a whopping 86% in discount, yet interestingly enough they are the MOST demanding when it comes to support and feature requests.

Phrased that way, you stand firm. They're not qualified leads for you; full stop. Politely tell them that your prices aren't negotiable (or that they're only negotiable upwards, with your largest clients.)

You do *not* want to bend over for clients who require tons of support and send tons of feature requests without reaching deep into their pocket. If they think they can do the same for cheaper using Indian labor, politely suggest that they should -- it's their problem if they do, not yours.

Before you do, however, double-check that their reaction has nothing to do with your marketing. Sales objections typically break down to one of two things: either the lead isn't qualified (e.g. they can't afford you) or it didn't get enough of the right information (i.e. they don't register the value you're delivering, or doesn't trust that you're able to deliver.)



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
