## Negative average spending when calculating LTV

- posted by: [Dopapp](https://stackexchange.com/users/6538459/dopapp) on 2015-12-13
- tagged: `sales`, `metrics`, `ltv`
- score: 2

When calculating the LTV of a customer, does it make any sense if the customer has a *negative* average spending, but the other values are positive? 

I am using the traditional equation found <a href="https://blog.kissmetrics.com/wp-content/uploads/2011/08/calculating-ltv.pdf">here</a> to calculate LTV. 

In what scenario would having a negative LTV make sense in real life? 

Also, could someone please help with tags?


## Answer 8100

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-12-13
- score: 3

The only case where an LTV can be negative is if you're giving money away to your clients.

Hunch: any odds you forgot to divide the percentages by 100 before applying the formula?


## Answer 8103

- posted by: [Jimnotgym](https://stackexchange.com/users/7461839/jimnotgym) on 2015-12-13
- score: -1

If you got the calculation correct then it could be that your assumptions are the problem.

Which costs are specific to that customer? Are you including costs that have already been spent? That sort of thing.

This kind of metric works well for companies that have a flat aquisition strategy that is aimed at a large group of people (like starbucks as per the example). If you are looking at a business with a more bespoke customer base (like an ERP company) and fewer customers, then you may find there are better ways of looking at this. 



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
