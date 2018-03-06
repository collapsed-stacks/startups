## What is the meaning of having "selection bias" in email targeting?

- posted by: [Dawny33](https://stackexchange.com/users/6444670/dawny33) on 2016-05-19
- tagged: `marketing`, `advertising`, `email-marketing`, `ab-testing`
- score: 3

I have been reading [this research paper][1], titled: **Do Targeted Discount Offers Serve as Advertising? Evidence from 70 Field Experiments**

In this, there is a piece of text which reads:

> In the context of email marketing, computing incremental sales via a
> simple comparison of outcomes across those receiving and not receiving
> the email with an offer (in order to measure the effect of the email) is rendered
> inappropriate due to the selection inherent in targeting.

> Well-designed experiments can, in theory, overcome this problem. In
> practice, however, these experiments need to be executed with care
> because they can be non-representative, costly, and time-consuming.

So, what does **selection inherent in targeting** mean? And why does it make the computations of incremental sales difficult/inappropriate?

And, why does the authors say these experiments are non-representative? Aren't email targeting campaigns intended to target specific group of customers?



  [1]: http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2530290


## Answer 9278

- posted by: [PV22](https://stackexchange.com/users/8264469/pv22) on 2016-05-21
- score: 1

The selection bias is that the people who receive the email advertisement were targeted for a specific reason. Therefore the group will have skewed statistical results because the targeting would limit you to a small subdivision of the wider general population. 

The results are effected by what ever selection criteria was used to target the emails. The likely finds would be that the data is biased towards an inflated success rate, versus the sales in the general public. This is further exacerbated if you are comparing it the second group, "those who did not receive the email", which also has a selection bias because it cannot include the part of the population that is likely to purchase the product, because that population comprises the group of people who did get the email.

Additionally, the reference to the results being "non-representative" is referring to the results and whether they demonstrate the effectiveness of the email campaign.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
