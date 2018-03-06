## How to charge for very small amounts of money? Like Adwords/AWS

- posted by: [James Scott](https://stackexchange.com/users/10167557/james-scott) on 2017-02-03
- tagged: `business-model`, `billing`
- score: 4

For businesses like Google adwords or Amazon AWS, they charge users by the hour, or by the amount of views an ad receives. Sometimes this results in extremely fractional and small totals. (e.g. $0.00001) or something.

How do these businesses process these? 

 1. Do they just let them sit there until they pass a certain threshold (thereby losing out on potentially a lot of money when these small amounts are aggregated over large number of accounts)

 2. Do they just round them up to some sort of minimum?

 3. Do they just process them as is and eat the cost of processing a $0.00001 bill?


## Answer 12040

- posted by: [Keith Wolf](https://stackexchange.com/users/147215/keith-wolf) on 2017-02-03
- score: 5

Most companies in this pricing model will do one of two things: 

 - Charge up-front for a certain amount, say $10.  The customer's usage would eat into that amount until it's almost used up and then charge another $10 to the account automatically.
 - Take the card info but don't charge until the usage has hit a certain threshold, like $10, then charge for the total current usage at that time. It may exceed that threshold amount (e.g. $12.34 by the time the billing occurs).  

I believe Amazon does the 2nd one.  

Charging for tiny amounts isn't worth it since even the most favorable card charging fees typically are at least 10 cents per charge, regardless of the amount (30 cents is by far the most common).



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
