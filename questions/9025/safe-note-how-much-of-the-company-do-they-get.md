## Safe Note, How much of the company do they get?

- posted by: [Reid](https://stackexchange.com/users/473379/reid) on 2016-04-22
- tagged: `legal`, `equity`, `venture-capital`, `valuation`, `term-sheet`
- score: 4

I am in a startup incubator that has given me the following safe note, and from reading it, it seems like the amount of shares that the investor gets, goes up, the higher our valuation goes. However I was told point blank by the people who run the incubator that the investor will get a flat 7%. What is correct? How much will the investor get if our company is valued at 1,000,000? 10,000,000? $500,000? The safe note says the following. <strike>Sorry I cant post the whole thing.</strike> The draft version attached below.

The following clauses are part of the safe note
> $20,000 (the “Purchase Amount”)

and

> The “Dilution Cap” is $285,000.

and

>(a) Equity Financing. If there is an Equity Financing before the
> expiration or termination of this instrument,
> the Company will automatically issue to the Investor either: (1) a
> number of shares of Standard Preferred Stock equal to 
> the Purchase Amount divided by the price per share of the Standard
> Preferred Stock, if the pre-money valuation is less 
> than or equal to the Dilution Cap; or (2) a number of shares of Safe
> Preferred Stock equal to the Purchase Amount divided 
> by the Safe Price, if the pre-money valuation is greater than the
> Dilution Cap.

Definitions:

> “Safe Price” means the price per share equal to the Dilution Cap divided by the Company Capitalization.
> 
> “Company Capitalization” means the sum, as of immediately prior to the
> Equity Financing, of: (1) all shares of Capital Stock (on an
> as-converted basis) issued and outstanding, assuming exercise or
> conversion of all outstanding vested and unvested options, warrants
> and other convertible securities, but excluding (A) this instrument,
> (B) all other Safes, and (C) convertible promissory notes; and (2) all
> shares of Common Stock reserved and available for future grant under
> any equity incentive or similar plan of the Company, and/or any equity
> incentive or similar plan to be created or increased in connection
> with the Equity Financing.

Attached is the "draft version" that is almost exactly the same language, with the exception of the dilution cap being $700 more.

[Draft version of document][1]


  [1]: https://drive.google.com/file/d/0B76aLKz21sLKandfckY3RTNOczg/view?usp=sharing


## Answer 12365

- posted by: [Kev Price](https://stackexchange.com/users/1109274/kev-price) on 2017-03-23
- score: 2

The dilution cap is there to ensure that the investor gets their 7% when you raise another round.

The only way that this percentage will increase is if your valuation in the next round is **lower** than the dilution cap.

So, if for example your valuation in the next round was $100,000 this is below the dilution cap and so would invoke the clause:

"a number of shares of Standard Preferred Stock equal to the Purchase Amount divided by the price per share of the Standard Preferred Stock, if the pre-money valuation is less than or equal to the Dilution Cap"

Giving them (rough sum) : 20K (purchase amount) / 100k (valuation) *100 (percent) = 20%

If you managed to get a $1 million valuation in the next round, instead of them getting:

20K / 1M * 100 = 2%

It would invoke clause 2:

" a number of shares of Safe Preferred Stock equal to the Purchase Amount divided by the Safe Price, if the pre-money valuation is greater than the Dilution Cap."

replacing the valuation with the dilution cap of 285K, ensuring the worst deal for them is:

20K / 285K * 100 = 7%

So as long as your valuation in the next round is above the dilution price they will get 7%


## Answer 9564

- posted by: [user3667089](https://stackexchange.com/users/4510966/user3667089) on 2016-06-26
- score: 0

Suppose you have X number of outstanding shares prior to the priced round.

With your example the pre-money valuation which is 500k, 1M, 10M are all above the dilution cap of the note, so it will be converted with the (2) option with the share price of 285k/X dollar per share. Note that the denominator is still X because the "Company Capitalization" section said it's the total sum prior to the priced round (which is great for the founders). 

The total amount of shares that the note holder will receive is 20k/(285k/X)= 0.0702X as long as you can get your pre-money valuation above the 285k dilution cap for the priced round. 

Technically the note holder does not own any percentage of the company before a priced round, they are lending you money.

If the new investor ends up with Y amount of shares after the priced round with whatever your pre-money valuation is, the note holder will end up with 100 * 0.0702X/(X+0.0702X+Y) percent.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
