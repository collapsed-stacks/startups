## What is the least expensive WHITE LABEL payment gateway to accept debit cards for micropayments?

- posted by: [Jon Tonti](https://stackexchange.com/users/6076215/jon-tonti) on 2015-04-20
- tagged: `business-model`, `sales`, `payment`, `business-structure`
- score: 4

<p>Requirements:</p>

<ul>
<li>just takes a % of the the transaction fee, no 30 cent flat transaction fee (even if you can batch)</li>
<li>user can remain logged in like Stripe</li>
<li>fully white label</li>
</ul>



## Answer 4076

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-04-21
- score: 4

<p>Short answer is: none.</p>

<p>Honestly... Walmart and Costco aren't getting those kinds of terms when issuing branded credit cards, so you've zero chances of getting them yourself for online payments.</p>

<p>Paypal and Amazon both seem to offer micropayment accounts at $.05 + 5% per transaction. Neither is white labeled, and this is apparently limited to same-currency transactions. (Google had an in-app payment API that did 5% at one point, but it got retired.)</p>

<p>Another option is to accept bitcoin or another crypto-currency. But not everyone uses bitcoins, and carrying a bitcoin balance is risky.</p>

<p>The better option, imo, is to consider whether charging once per transaction makes any sense to begin with. Apple aggregates transactions in the App Store, and then charges you each month you spend something. Shouldn't you be doing something similar?</p>

<p>Further reading:</p>

<ul>
<li><a href="https://money.stackexchange.com/questions/6923/what-are-cheap-ways-to-accept-small-amounts-of-money-micropayments-on-my-web-s">https://money.stackexchange.com/questions/6923/what-are-cheap-ways-to-accept-small-amounts-of-money-micropayments-on-my-web-s</a></li>
<li><a href="https://stackoverflow.com/questions/3346070/micropayment-processing-using-paypal-or-other-payment-processing-service">https://stackoverflow.com/questions/3346070/micropayment-processing-using-paypal-or-other-payment-processing-service</a></li>
<li><a href="http://www.quora.com/What-is-the-best-payment-processor-for-accepting-micropayments?share=1" rel="nofollow noreferrer">http://www.quora.com/What-is-the-best-payment-processor-for-accepting-micropayments?share=1</a></li>
</ul>



## Answer 8959

- posted by: [Nat](https://stackexchange.com/users/5802386/nat) on 2016-04-12
- score: 1

<p>For a UK or European based solution then there is <a href="http://www.cardstream.com" rel="nofollow">Cardstream</a></p>

<p>They offer a full white label payment gateway. They do not charge a %, only a low wholesale transaction cost. You will need a merchant account or aggregator account from an acquirer (who will charge you a %). </p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
