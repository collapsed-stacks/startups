## Best cheap payment gateways

- posted by: [Drewg23](https://stackexchange.com/users/3131900/drewg23) on 2015-04-27
- tagged: `payment`
- score: 4

<p>A small background: We are working on a website that lets users send sms messages to their friends. This services utilizes <em>Twilios</em>. We would like to charge 99 cents to send the messages for a day.</p>

<p>So Paypal and Stripe charge 2.9% + .30 cent transaction fee. And <em>Twilio</em> charges a penny or so per message (sending pics too). Which doesn't sound like much but we plan on sending at least 10 messages per session. Meaning 10 more cents gone.</p>

<p>Basically, does anyone know of a good way I can charge users only a dollar without the crazy transaction fees?<br />
 I know the fees are only for debit/credit card.<br />
 May end up with PayPal, but I just wanted to check if anyone had any better solutions for me, to charge only 1 dollar, before we implement it.</p>



## Answer 4136

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-04-27
- score: 4

<p>Decompose the authorize/capture steps like Apple does in iTunes:</p>

<ol>
<li>Get the authorize token</li>
<li>Aggregate the purchases internally</li>
<li>Capture at the end of each month</li>
</ol>

<p>That way you pay a transaction fee once per month for the monthly total, instead of once per transaction.</p>

<p>Alternatively, split buying and spending credits in two. Sell $10+ credit to use the site, and then charge the credit rather than the credit card based on usage -- with the site ultimately saying "You're out of credit" when you run out and prompting to do a refill. Note that this option also introduces the opportunity to give a few bucks of credit away for free upon registering the site, so as to ensure it's stickier without committing a new user to spend $10 or more immediately.</p>



## Answer 4137

- posted by: [blunders](https://stackexchange.com/users/216182/blunders) on 2015-04-27
- score: 0

<p>Answer to your question depends on if a significant amount of the purchasers make X amount of payments a month. If significant amount of purchasers only make one one purchase a month, then this approach would likely be more costly that just processing the transactions real-time; reason it would cost more at scale is due to the fact that money available at the present is worth more than the same amount in the future due to its potential earning capacity.</p>

<p>If a significant amount of the purchasers make X amount of payments a month, then <a href="https://startups.stackexchange.com/a/4136/551">Denis' answer covering the transaction pooling approach used by a number of companies include Apple would make sense</a>, but guessing that this point you don't know the answer and in my opinion you'd be better off deploying a method to take payments to learn how much demand there really is and what real world use patterns look like.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
