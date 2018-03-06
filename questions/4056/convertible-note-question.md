## Convertible note question

- posted by: [Stan](https://stackexchange.com/users/6173398/stan) on 2015-04-20
- tagged: `investment`
- score: 3

Can anyone please help me understand the following:
I recently raised $20,000 as a convertible note with $2,500,000 cap and 25% discount.

I'm now raising another $100,000 round at $3,000,000 valuation.

What happens with the first convertible note? Does it convert at $100,000 valuation or at $3,000,000 valuation?

Is it the dollar amount raised that goes into formula for calculating conversion or the valuation of the new round?



## Answer 4064

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-04-20
- score: 1

Quoting [FoundersClub](https://fundersclub.com/learn/convertible-notes/#numerical-example-2):

> Numerical Examples: $25k convertible note with $5M cap, 20% discount

> Let’s do numerical example ignoring any accrued interest:

> You invest $25k in a startup’s seed round using a convertible note with a $5M cap, 20% discount

> If, at the Series A, the startup raises money from a venture capital firm that invests at a pre-money valuation of $10M with a per share price of $5.00 IF we apply the discount, the price per share would be $4.00/share ($5.00 times (1 minus 20%)) IF we apply the cap, the price per share would be $2.50/share ($5.00 times ($5M cap divided by $10M pre-money valuation)) THUS the cap would apply and the note would convert at $2.50/share which gives 10,000 shares of Series A Preferred Stock ($25,000 divided by $2.50/share). On paper, your 10,000 shares at $5.00/share are worth $50,000 which is an unrealized return of 100%

> If, at the Series A, the startup raises money from a venture capital firm that invests at a pre-money valuation of $6M with a per share price of $5.00 IF we apply the discount, the price per share would be $4.00/share ($5.00 times (1 minus 20%)) IF we apply the cap, the price per share would be $4.1667/share ($5.00 times ($5M cap divided by $6M pre-money valuation)) THUS the discount would apply and the note would convert at $4.00/share which gives 6,250 shares of Series A Preferred Stock ($25,000 divided by $4.00/share). On paper, your 6,250 shares at $5.00/share are worth $31,250 which is an unrealized return of 25%


## Answer 9562

- posted by: [user3667089](https://stackexchange.com/users/4510966/user3667089) on 2016-06-26
- score: 0

Assuming your $3,000,000 valuation is the standard pre-money valuation and you have X number of outstanding shares before the priced round.

The 3M raise values the share price at 3M/X dollar per share. 100k investment yields 0.1M/(3M/X) = 0.0333 * X shares.

For the convertible note, if it's converted with the 25% discount, it will convert at 3M/X * 0.75 = 2.25/X dollar per share. 

If it's converted with the 2.5M pre-money valuation with the "post series A out standing shares" (this is the worse case scenario, read your contract carefully), it will convert at 2.5/(X+0.0333X) = 2.4194/X dollar per share, which is still higher than 2.25/X.

Therefore, the 25% discount will kick in for your case.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
