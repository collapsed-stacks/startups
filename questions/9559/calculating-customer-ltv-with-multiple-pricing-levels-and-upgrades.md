## Calculating customer LTV with multiple pricing levels and upgrades

- posted by: [Robert Byrne](https://stackexchange.com/users/5232876/robert-byrne) on 2016-06-25
- tagged: `software`, `business-model`, `pricing`, `revenue`, `ltv`
- score: 5

The business model for our software goes as follows...

Different levels of customers (standard, pro, enterprise) at different pricing levels with a yearly purchase. This doesn't make calculating LTV (Life Time Value) too difficult.

However, the yearly "upgrade" fee for this software (which will be valuable because the technology it works with changes) will be set at ~50% of the initial purchase price of the software. This means that a customer in year 2 will have a lower value (in revenue) than a new customer.

**Question:**

How can we predictably calculate (estimate) customer LTV with this many variables?

I am a believer in keeping things as simple as possible for both us and customers but this seems to be the way this particular industry prices its products.

**Why ask this?**

We are setting a revenue goal to hit over the next 2 years and a major aspect of monitoring this will include being able to roughly predict a customer LTV.

Thanks for the input folks. I look forward to hearing everyone thoughts. 

Feel free to comment for more clarification if it is needed.


## Answer 11075

- posted by: [vpego](https://stackexchange.com/users/7073322/vpego) on 2016-09-05
- score: 1

Not that difficult... but you'll have to elaborate more on 2 variables:

1. Churn Rate
2. Recurring Revenue (The L of LTV)

**Churn Rate**

Churn rate, when applied to a customer base, refers to the proportion of contractual customers or subscribers who leave a supplier during a given time period. 

**Recurring Revenue (The L of LTV)**

The L on LTV would refer to the Lifetime of the customer, or how long will your customers stay with you? 

Once we're talking about yearly purchase the real question is: How many times (years) will the customer repurchase your product (pay again)? 

This will answer the amount of Recurring Revenue you will get from each customer.

> If you don't have enough data to calculate those both metrics, try to emulate
> with some industry average.

**Let's give some values to see what we got:**

Standard subscription: $ 99,00

Given Churn Rate Percentages:

After 1 year:  25%

After 2 years: 50%

After 3 years: 75%

After 5 years: 90%

**(Simple) LTV of 1 customer on Standard pricing level:**

Year 1: $ 74,25

Year 2: $ 24,75

Year 3: $ 12,37

Year 4: $ 12,37 (nothing changes)

Year 5: $ 4,95
______________
TOTAL:  $ 128,69

So if we consider that you close 100 'Standard Customers' on Year 0, your overall LTV would be: 

**$ 12.869**

> More complex LTV would consider Rate of Discount, Tax and other metrics.

For other pricing levels, just apply the same logic.

I hope that helps.











## Answer 9602

- posted by: [D J Sims](https://stackexchange.com/users/7242000/d-j-sims) on 2016-07-02
- score: 0

I would be conservative and assume that the product has only a single year of value. Once you have experience and a past history of upgrades to look at, you can adjust the LTV accordingly. 

Software customers are very fickle anyway and most of them can't commit to anything beyond a quarter. There's a reason why the perpetual license and yearly license on most software are so similar in price.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
