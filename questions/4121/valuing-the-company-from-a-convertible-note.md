## Valuing the company from a convertible note

- posted by: [Xodarap](https://stackexchange.com/users/140666/xodarap) on 2015-04-26
- tagged: `investment`, `fundraising`, `valuation`
- score: 3

I'm trying to figure out how convertible notes work. Specifically, I want to figure out my implied valuation from a convertible note. (Yes, I know the point of convertible notes is that you don't have an explicit valuation, but there is an implicit one.) Consider the following example:

> Note terms:
>
> * 5% simple, non-compounded interest
> * 20% discount rate
> * $10m cap
> * 12 months of runway (estimate)
> * $1m investment
> 
> A year from now, raise at a $10M valuation, with a share price of one
> dollar per share. Your investors have 1.0 5M total, thanks to accrued
> interest, and they get to purchase at $.80 a share due to the
> discount. This gives them an ownership stake of 1.0 5M/.8 =1,312,500
> shares; 13% of the total. 
> 
> So investors will be purchasing a 13% stake a year from now for $1M,
> which gives a nondiscounted valuation of $7.7 M. (Note that this
> valuation is post-money relative to the first raise, but pre-money
> relative to the second. Confused yet?) Investors will often tell you
> that they believe they will average a 20% IRR; this is complete crap
> but whatever. Using that discount rate (the time discount rate, not
> the discount rate of the note) we get a net present post-money
> valuation of $7.7M/1.2= $6.4M. Subtracting the initial investment
> gives us a pre-money of $5.4 M.

Is that a correct computation of the net present value of the company implied by the investment?



## Answer 4148

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-04-29
- score: 1

You cannot compute a pre-money valuation at the time of closing a new round, and treat it as a valuation at the time your initial investor gave you a convertible note. Not even as a proxy. It's two different valuations at two different points of time.

What your initial investor actually did was place a bet. One that you'll be worth a lot more in 12 months than now (namely $10M+), and pre-paying a chunk of that at a discount, with the understanding that their money will let you get there faster.


## Answer 4178

- posted by: [Xodarap](https://stackexchange.com/users/140666/xodarap) on 2015-05-02
- score: 1

The solution posted in the question is slightly wrong.

As usual, assume [rational pricing](http://en.wikipedia.org/wiki/Rational_pricing). We can view the convertible note as a forward contract. (This is ignoring the possibility of the note converting for less than its cap, but it's pretty close.)

Under the rational pricing assumption, forwards are deterministically priced, so to determine the present valuation you need to do two things:

1. Figure out the effective share price. This was done correctly in the question.
1. Based on that forward price, use the [forward pricing equation](http://en.wikipedia.org/wiki/Forward_contract#Rational_pricing) to determine the current spot price. This was done incorrectly in the question: it's irrelevant what ROI an investor wants to get, only the risk-free interest rate matters.

Of course, you might not think that early-stage companies are rationally priced, but I ran this by a few VCs and they all said that this was how they model convertible notes.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
