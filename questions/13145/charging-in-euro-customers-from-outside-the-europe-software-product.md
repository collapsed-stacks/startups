## Charging in Euro customers from outside the Europe - Software product

- posted by: [Michał T. Krawczyk](https://stackexchange.com/users/9929142/micha-t-krawczyk) on 2017-08-09
- tagged: `pricing`
- score: 1

Do you have some experience or sources about the possible consequences of changing currency from USD to EUR for customers from outside the Europe? I'm a bit worried about currency trust. Not sure if customers from Asia or South America will be eager to pay in Euro instead of Dollars. Of course, the best solution would be local currencies, but we're not able to do that now. We want to keep Dollars for USA customers.

We want to change the currency because USD exchanges rates are low. Prices in Euro will be approximately lower.


## Answer 13149

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2017-08-09
- score: 2

FWIW I've done this change the other way around at one point in my career: I was charging in EUR and switched to charging in USD outside of Europe.

It made little difference for people living outside of North America. Sales ticked slightly upwards, which I attributed to USD being slightly more familiar. But only so much. Basically, unless people are getting paid or otherwise using a currency on a regular basis, they'll have little notion of its value and will end up needing to figure out what the cost is in their local currency either way.

(I would add, as one who has been living in Hungary for a few years, that I'm still converting HUF to something more familiar whenever I pull out my wallet. And for better or worse, I'm old enough and have lived outside of Europe enough to occasionally recoil in horror at the amount of [FF](https://en.wikipedia.org/wiki/French_franc) I'm about to spend when paying in EUR. Even after dealing with a new currency for years, it can still be hard to get a sense of how much it's worth.)

On the US front in contrast (and to some extent for Canada) the switch from EUR to USD made an enormous difference. The two most common pre-sales questions I was getting until making the switch were, in order, 1) How much is the cost in dollars? and 2) What is a Euro? (I kid you not.) Variations of what developing country I was living in came third. Sales went up and pre-sales questions went down the moment the price was in USD.

Since then I've systematically done the following:

- Charge in EUR when doing business in Europe and Africa.
- Charge in USD everywhere else.

Sometimes it's worth iterating on that and charging in other local currencies. The usual suspects here are GBP and JPY - i.e. large markets. In other lines of business it might be INR, RMB, BRL, or what have you. Methinks only do this when those markets are substantial enough (or if it's easy enough for you) to warrant you going the extra mile to streamline their purchase experience.

Lastly, it's not that hard to actually display or charge in a local currency. A script that periodically taps into a data source is enough to do the former (e.g. add a "Convert to my currency" button), and some CC processors allow you to convert your price in some local currencies on the fly before processing the payment.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
