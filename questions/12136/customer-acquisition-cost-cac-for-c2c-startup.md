## Customer Acquisition Cost (CAC) for C2C startup

- posted by: [Joao de Araujo](https://stackexchange.com/users/67481/joao-de-araujo) on 2017-02-17
- tagged: `business-model`, `user-acquisition`
- score: 5

When a startup has one main audience it seems fairly simple to understand the aspects to take into account for calculating CAC (Customer Acquisition Cost). However, when the business model is Consumer to Consumer (C2C), the scenario is a bit more complex.

 - In a C2C business model, how is the CAC defined and calculated?
 - Should it be determined against both audiences? If yes, how?

Thanks.

 


## Answer 12161

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2017-02-21
- score: 5

Your CAC (Customer Acquisition Cost) is first and foremost a tool to prioritize your marketing efforts. Don't merely stick to calculating an overall CAC. You want to break it down per channel, and per product when applicable, and then put it in the context of that channel's CLV (Customer Lifetime Value).

Failing to do so, you may end up with e.g. a `[[$10, 25%], [$20, 25%], [$30, 25%], [$40, 25%]]` CAC tuple and erroneously conclude that your CAC is e.g. $25. The CLV for context is also crucial, because it may turn out that the latter CAC tuple yields an `[$25, $25, $25, $50]` CLV tuple - and now you know that the $10 and $40 channels get the most bang for the buck.

Without more details it's anyone's guess how to best break it down in your specific case. Intuitively though, breaking down consumers by source/origin/campaign/whatever and matching each one might get you in the right direction. Mind correlations as you work out the gory details: working on source A-B also contributes to e.g. A-C, A-D, B-C and B-D if you've four key sources.

Pro tip: decide on an attribution model, [extract the data from GA](https://developers.google.com/analytics/devguides/collection/analyticsjs/field-reference#trafficsources) when they first sign up, and throw it into ChartMogul for pretty visualizations and segmentation.

---

In light of the comment you added with more details... your actual customers are those users who are sellers. What you're looking for in the end is to identify:

- The (one-time) channel- and business type-based costs associated with acquiring your sellers; and
- The (recurring) channel-based costs associated with acquiring these specific sellers' buyers

... such that the total costs involved over a given seller's lifetime are less than your sellers' total lifetime value.

It's a thorny network-related problem in that it's full of correlations and convoluted feedback loops because:

- Acquiring sellers might bring bonus buyers as a side effect and vice versa
- Acquiring one type of seller in a specific channel might also contribute to acquiring another type of seller in the same channel, and similarly for buyers
- Different seller types will likely have buyer types in common

Adding insult to injury, there's an extra layer of non-linearity in that your customer lifetime value depends on your sellers' ability to sell enough to make it worth their time to use your platform, and the latter is directly related to whether you've a large enough number of buyers for them to stay around. Put another way, you've a threshold to work out for each seller segment, and even then the threshold is actually per seller because a small fry might be happy with some clients but a larger/more lucrative seller might need a lot more buyers to justify using your platform.

Anyway, you certainly don't want to waste any time trying to model this perfectly and find the optimal solution. Look for local optimums through trial and error instead - aka things that work.

Start with the seller acquisition costs. How much does it cost you to acquire a new seller, per channel, and probably segmented by business type for good measure. Then do the same type of work for their respective buyers, also per channel.

If a buyer channel caters to more than one seller buckets, distribute its costs. (How is rather arbitrary: you could e.g. pro-rate based on revenue %.)

Then compute seller CAC + buyer acquisition costs as suggested in the first part of my answer to get a feel of what's worth doing or not.

In practical terms, I'd gather you already have a feel of a handful of seller types that will likely be profitable. Start with the most promising one, and try to optimize it. Then throw in another, etc.



## Answer 12179

- posted by: [Dave Feyereisen](https://stackexchange.com/users/527283/dave-feyereisen) on 2017-02-23
- score: 1

I would start by focusing on 'your definition of a customer'.  That isn't always as simple as it seems.  Once you define exactly what a customer is, figure out what it will cost to get enough of them.  




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
