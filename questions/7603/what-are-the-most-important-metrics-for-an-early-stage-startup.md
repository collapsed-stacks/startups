## What are the most important metrics for an early-stage startup?

- posted by: [Dawny33](https://stackexchange.com/users/6444670/dawny33) on 2015-10-19
- tagged: `marketing`, `growth`, `metrics`
- score: 3

What are the most important metrics for a startup(in the initial user acquisition phase) which can translate it's growth?


## Answer 7606

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-10-19
- score: 6

In my view the main two are:

1. Customer acquisition cost.
2. Customer retention rate.

The first allows to know where it's better to put your marketing money. The second yields the Customer lifetime value.

Break both down per channel. Doing so and combining the two allows to compute an ROI per channel - you'll then know precisely if you're going sideways or making progress.

That said, the above assumes you're aiming for growth while staying profitable. If your intent is to grow first and monetize later, the metrics you'll want might be quite different.


## Answer 11441

- posted by: [Ryan Law](https://stackexchange.com/users/9520414/ryan-law) on 2016-10-27
- score: 2

<p>These are 5 high-level metrics that almost all early-stage startups should track:</p>

<h2>1) Product/Market Fit</h2>

<p>When you're an early-stage startup, this is the single most important metric to understand, answering two pivotal questions:</p>

<ol>
<li><em>Does my product solve a valuable problem?</em></li>
<li><em>Will the market for my product support a profitable business?</em></li>
</ol>

<p>With those questions answered, you can usually warrant further investment into scaling your business.</p>

<p>The simplest way to gauge this is with the <a href="https://www.cobloom.com/blog/how-to-create-a-product-market-fit-survey-with-free-template" rel="nofollow noreferrer">Sean Ellis PMF test</a>, a one-question survey sent to 40-50 active, representative customers (if you lack these customers to survey, it's very likely you don't have PMF):</p>

<p><em>How would you feel if you could no longer use [product]?</em></p>

<ul>
<li><em>Very disappointed</em></li>
<li><em>Somewhat disappointed</em></li>
<li><em>Not disappointed (it really isn’t that useful)</em></li>
<li><em>N/A - I no longer use [product]</em></li>
</ul>

<p>If over 40% of users respond to the survey saying they'd be "Very disappointed", it's likely your product has found Product/Market Fit. Why?</p>

<p>After comparing nearly 100 startups, Sean found that those that struggled to reach traction always scored under 40% on this particular test, whereas those that gained strong traction always scored over 40%.</p>

<h2>2) Monthly Recurring Revenue (MRR)</h2>

<p>MRR is essential for understanding the growth of your business, and with a good handle on customer acquisition and churn rates, it can also be used to extrapolate future revenue:</p>

<p><img src="https://chart.apis.google.com/chart?chf=bg,s,fffff0&amp;cht=tx&amp;chl=%5Ctext%7BMRR%7D_t%3D%5Csum%5Ctext%7BRecurring%20Revenue%7D_t" alt="Monthly Recurring Revenue MRR Formula"></p>

<p>For example, if we have 2 customers in January, each paying subscription of $2,000 pcm, and in February, we gain an additional customer, MRR increases as a result:</p>

<p><img src="https://chart.apis.google.com/chart?chf=bg,s,fffff0&amp;cht=tx&amp;chl=%5Ctext%7BFebruary%3A%20%7D%242%2C000%2B%242%2C000%2B%242%2C000%3D%246%2C000%20%5Ctext%7B%20MRR%7D" alt="MRR worked example"></p>

<h2>3) MRR Growth Rate</h2>

<p>The <a href="https://www.cobloom.com/blog/saas-metrics" rel="nofollow noreferrer">MRR Growth Rate</a> measure improvements to your revenue generation over time, and functions as a good stand in for "growth" as a whole:</p>

<p><img src="https://chart.apis.google.com/chart?chf=bg,s,fffff0&amp;cht=tx&amp;chl=%5Ctext%7BMRR%20Growth%20Rate%7D%3D%5Cfrac%7B%5Ctext%7BMRR%7D_t-%5Ctext%7BMRR%20%7D_%7Bt-1%7D%7D%7B%5Ctext%7BMRR%20%7D_%7Bt-1%7D%7D%5Ctimes100" alt="MRR Growth Rate Formula"></p>

<p>If we generated $1,500 MRR last month, and increased that to $2,000 this month, we'd have an MRR Growth Rate of approximately 33%:</p>

<p><img src="https://chart.apis.google.com/chart?chf=bg,s,fffff0&amp;cht=tx&amp;chl=%5Ctext%7BMRR%20Growth%20Rate%7D%3D%5Cfrac%7B%242%2C000-%241%2C500%7D%7B%241%2C500%7D%5Ctimes100%5Capprox33%5C%25" alt="MRR Growth Rate Worked Example"></p>

<h2>4) Customer Churn Rate</h2>

<p>Growth depends on both new customer acquisition and minimising the loss of existing customers. <a href="https://www.cobloom.com/blog/saas-metrics" rel="nofollow noreferrer">Customer Churn</a> measures the rate at which your existing customers stop paying for your product:</p>

<p><img src="https://chart.apis.google.com/chart?chf=bg,s,fffff0&amp;cht=tx&amp;chl=%5Ctext%7B%25%20Customer%20Churn%20Rate%7D%3D%5Cfrac%7B%5Ctext%7BCustomers%20that%20churned%20in%20period%20t%7D%7D%7B%5Ctext%7BTotal%20customers%20at%20the%20start%20of%20period%20t%7D%7D" alt="Customer Churn Formula"></p>

<p>If we start a given month with 20 paying customers, but finish with only 19, that month's customer churn rate was 5%:</p>

<p><img src="https://chart.apis.google.com/chart?chf=bg,s,fffff0&amp;cht=tx&amp;chl=%5Ctext%7B%25%20Customer%20Churn%20Rate%7D%3D%5Cfrac%7B20-19%7D%7B20%7D%3D5%5C%25" alt="customer churn rate worked example"></p>

<h2>5) Customer Acquisition Cost (CAC)</h2>

<p>If MRR measures revenue, <a href="https://www.cobloom.com/blog/saas-metrics" rel="nofollow noreferrer">Customer Acquisition Cost</a> measures the investment required to generate that revenue. Your CAC determine show much you can afford to spend on revenue generation, and determines the types of sales and marketing strategies you can profitably deploy:</p>

<p><img src="https://chart.apis.google.com/chart?chf=bg,s,fffff0&amp;cht=tx&amp;chl=%5Ctext%7BCAC%7D_t%3D%5Cfrac%7B%5Ctext%7BSales%20%26%20Marketing%20Cost%7D_t%7D%7B%5Ctext%7BNew%20Customers%7D_t%7D" alt="CAC Formula"></p>

<p>For example, if you spent $5,000 on sales and marketing in a given month, and closed 10 new customers over the same period, that month's CAC would be $1,000:</p>

<p><img src="https://chart.apis.google.com/chart?chf=bg,s,fffff0&amp;cht=tx&amp;chl=%5Cfrac%7B%245%2C000%2B%245%2C000%7D%7B10%7D%3D%241%2C000" alt="CAC worked example"></p>



## Answer 11442

- posted by: [Neil](https://stackexchange.com/users/2711480/neil) on 2016-10-27
- score: 0

Simple one that I am surprised is not on here - cash flow. 

In a startup you have lots of demands and variable (but usually quite limited) cash. Therefore, watch your cash flow to determine income and expenditure to identify if you have any short-falls in the future. You can also set a "safety net" level of cash that you need to retain. 

This will help you identify how much cash you can put into growth activities (e.g. R&D/ Sales team etc.). It will also help prevent bankruptcy...



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
