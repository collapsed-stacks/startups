## Calculating customer LTV with multiple pricing levels and upgrades

- posted by: [Robert Byrne](https://stackexchange.com/users/5232876/robert-byrne) on 2016-06-25
- tagged: `software`, `business-model`, `pricing`, `revenue`, `ltv`
- score: 5

<p>The business model for our software goes as follows...</p>

<p>Different levels of customers (standard, pro, enterprise) at different pricing levels with a yearly purchase. This doesn't make calculating LTV (Life Time Value) too difficult.</p>

<p>However, the yearly "upgrade" fee for this software (which will be valuable because the technology it works with changes) will be set at ~50% of the initial purchase price of the software. This means that a customer in year 2 will have a lower value (in revenue) than a new customer.</p>

<p><strong>Question:</strong></p>

<p>How can we predictably calculate (estimate) customer LTV with this many variables?</p>

<p>I am a believer in keeping things as simple as possible for both us and customers but this seems to be the way this particular industry prices its products.</p>

<p><strong>Why ask this?</strong></p>

<p>We are setting a revenue goal to hit over the next 2 years and a major aspect of monitoring this will include being able to roughly predict a customer LTV.</p>

<p>Thanks for the input folks. I look forward to hearing everyone thoughts. </p>

<p>Feel free to comment for more clarification if it is needed.</p>



## Answer 11075

- posted by: [vpego](https://stackexchange.com/users/7073322/vpego) on 2016-09-05
- score: 1

<p>Not that difficult... but you'll have to elaborate more on 2 variables:</p>

<ol>
<li>Churn Rate</li>
<li>Recurring Revenue (The L of LTV)</li>
</ol>

<p><strong>Churn Rate</strong></p>

<p>Churn rate, when applied to a customer base, refers to the proportion of contractual customers or subscribers who leave a supplier during a given time period. </p>

<p><strong>Recurring Revenue (The L of LTV)</strong></p>

<p>The L on LTV would refer to the Lifetime of the customer, or how long will your customers stay with you? </p>

<p>Once we're talking about yearly purchase the real question is: How many times (years) will the customer repurchase your product (pay again)? </p>

<p>This will answer the amount of Recurring Revenue you will get from each customer.</p>

<blockquote>
  <p>If you don't have enough data to calculate those both metrics, try to emulate
  with some industry average.</p>
</blockquote>

<p><strong>Let's give some values to see what we got:</strong></p>

<p>Standard subscription: $ 99,00</p>

<p>Given Churn Rate Percentages:</p>

<p>After 1 year:  25%</p>

<p>After 2 years: 50%</p>

<p>After 3 years: 75%</p>

<p>After 5 years: 90%</p>

<p><strong>(Simple) LTV of 1 customer on Standard pricing level:</strong></p>

<p>Year 1: $ 74,25</p>

<p>Year 2: $ 24,75</p>

<p>Year 3: $ 12,37</p>

<p>Year 4: $ 12,37 (nothing changes)</p>

<p>Year 5: $ 4,95</p>

<hr>

<p>TOTAL:  $ 128,69</p>

<p>So if we consider that you close 100 'Standard Customers' on Year 0, your overall LTV would be: </p>

<p><strong>$ 12.869</strong></p>

<blockquote>
  <p>More complex LTV would consider Rate of Discount, Tax and other metrics.</p>
</blockquote>

<p>For other pricing levels, just apply the same logic.</p>

<p>I hope that helps.</p>



## Answer 9602

- posted by: [D J Sims](https://stackexchange.com/users/7242000/d-j-sims) on 2016-07-02
- score: 0

<p>I would be conservative and assume that the product has only a single year of value. Once you have experience and a past history of upgrades to look at, you can adjust the LTV accordingly. </p>

<p>Software customers are very fickle anyway and most of them can't commit to anything beyond a quarter. There's a reason why the perpetual license and yearly license on most software are so similar in price.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
