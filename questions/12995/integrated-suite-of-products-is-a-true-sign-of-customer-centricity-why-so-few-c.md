## Integrated suite of products is a true sign of customer-centricity. Why so few companies do it?

- posted by: [Saeed Neamati](https://stackexchange.com/users/429080/saeed-neamati) on 2017-07-12
- tagged: `venture-capital`, `business-proposal`
- score: 1

As a user of Google's products, we all experience the ease and smoothness of facing its integrated products. You create one account, you login once, when you search, based on your search you see relevant ads on YouTube, and contacts are available in Gmail and ...

It's no doubt that integration of products given by a company is one of the most important aspects of UX. And Microsoft, Apple and even smaller companies like Zoho do it.

But, how it comes that very few companies actually do it?

The reason I'm asking this question, is that I have a startup that has created 3 integrated apps, alongside a proposal, to grab the attention of investors. Yet as they ask for existing samples of such an approach, I fail to give them enough samples.

I can't find companies with integrated suite of IT products beyond what I mentioned here.


## Answer 12997

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2017-07-13
- score: 1

Here are a few more examples: Atlassian, Intercom, Facebook, Twitter, Automattic...

It's common practice, but at least two reasons get in the way of you finding _many_ examples off the top of your head: it's non-trivial and thus costly to implement, and you won't necessarily notice it. Such integrations can stem from in-house development or acquisitions.

When integrating something that wasn't built in-house, you end up needing to do some non-trivial engineering in order to split out and merge the two apps' identity service - the part that manages the users, how they log in, etc. -  and, depending on your scale or the level of integration, other services like user preferences, billing, UI/UX guidelines, caching, etc. This can quickly get complex, and it's costly enough to do that it's not necessarily worth doing.

When developing things in-house, similar type of work occurs in the background in practice, albeit smoothly enough that you may not actually feel it. Look at Intercom for a prime example of this: they've been building a single app all along, but one whose features are built as piecemeal blocks (one would hope for them anyway) that are then bundled together as products - with feature overlaps between the various bundles and a core to manage the likes of identity, billing, etc.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
