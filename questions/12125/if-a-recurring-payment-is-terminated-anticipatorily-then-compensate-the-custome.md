## If a recurring payment is terminated anticipatorily, then compensate the customer?

- posted by: [porton](https://stackexchange.com/users/457033/porton) on 2017-02-15
- tagged: `payment`, `e-commerce`, `service`, `merchant-services`
- score: -1

<p>What is the common business practice in the following situation? If there is more than one common business practice in this situation, please describe all (considered honest) variants of the business practices (desirably with noting which are more common and which are less common).</p>

<p>Suppose somebody orders an online service with yearly recurring payments. (Let it is paid through PayPal to be specific.) After two months of this he logins into his PayPal account and cancels the recurring payment.</p>

<p>After this we have that he paid year ahead, but canceled it after two month.</p>

<p>What we (the business) should (accordingly to the common practice) do in this situation? Should we provide him the remaining 10 months of service free (for example if he subscribes again with another PayPal account)? Is it OK to say to him: Blame yourself, you've canceled your subscription, it is your not our failure.</p>

<p>I also note that for the programmer (that is me) it is a somehow difficult to make PayPal to "wait" exactly the remaining ("compensation for the remainder") period and charge him only when the "compensation" period ends. Does this difficulty justify us to say "blame yourself" to the customer?</p>



## Answer 12127

- posted by: [porton](https://stackexchange.com/users/457033/porton) on 2017-02-15
- score: 0

<p><em>It seems that I invented a workflow to provide a honest deal (please comment):</em></p>

<p>Every service has "last paid date". If the current date becomes after the last paid date, the service is suspended or terminated.</p>

<p>Every service may be in one of the two states:</p>

<ul>
<li><p>recurring mode: when we know that the customer has a recurring subscription;</p></li>
<li><p>manual mode: the customer is emailed a few days before the last paid date, with email asking to pay.</p></li>
</ul>

<p>Recurring mode &rarr; manual mode if the subscription is terminated (for example through the user's PayPal account).</p>

<p>Manual mode &rarr; recurring mode if the user subscribes. To act honestly, we should provide the duration remaining to the set last paid date as "trial period" in this case. Because for PayPal if the trial period is measured in days, it cannot be more than 90 days, we should allow manual mode &rarr; recurring mode switch only in 90 day before the last paid date.</p>

<p>Every payment (both explicit manual mode payments and automatic recurring mode payments) advanced the last paid date to the amount of days determined by the payment amount.</p>



## Answer 12346

- posted by: [Teddy Ho](https://stackexchange.com/users/10216703/teddy-ho) on 2017-03-19
- score: 0

<p>Generally for a SaaS product, the client is billed at the beginning of the pay period, and in exchange, is granted a license to the software for the duration of the period.  In your case, the client has bought an annual license from you so (provided he has not received any refunds,) the client is entitled to your service for the entire period.  You should continue to provide the service for the remaining 10 months, or provide him a refund for the portion covering that period.</p>

<p>When the client's service is up for renewal, you should make it available for him to pay for another year of service.  If he decides not to pay at that time, only then should you discontinue providing your service to them.</p>

<p>You should list this clearly in your terms of service along with your cancellation/termination of service policy.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
