## How to transfer payments to my clients?

- posted by: [Sergei Basharov](https://stackexchange.com/users/46016/sergei-basharov) on 2016-10-14
- tagged: `payment`
- score: 3

<p>I am working on an app which receives payments for products Z owned by clients B from clients C</p>

<ol>
<li>Client A publishes a product Z for selling => </li>
<li>Client B buys it =></li>
<li>My App receives the money via Stripe =></li>
<li>Client A needs to receive the money minus my fee and commissions.</li>
</ol>

<p>I am wondering what's the easiest automated way to perform the step 4?</p>

<p>Do I need to integrate another service into my app to send payments to clients? Or can I do this inside current Stripe setup?</p>

<p>Please recommend.</p>



## Answer 11345

- posted by: [Jeremy Parsons](https://stackexchange.com/users/497810/jeremy-parsons) on 2016-10-14
- score: 1

<p>Take a look at <strong>chained payments</strong>, supported by both Stripe and PayPal. </p>

<p>You need to think about who the customer is buying from (and will see on the transaction detail) and be very clear about the payment logic. That's doubly important if you have to deal with refunds.</p>



## Answer 11487

- posted by: [Gianluca Ghettini](https://stackexchange.com/users/928106/gianluca-ghettini) on 2016-11-04
- score: 0

<p>Chained payment by PayPal is the way to go. <a href="https://developer.paypal.com/docs/classic/adaptive-payments/ht_ap-basicChainedPayment-curl-etc/" rel="nofollow noreferrer">Check it out!</a></p>

<p>It's an advanced payment flow for which you'll have to submit a request to get an AppId, pass a very simple screening process (few questions by the PayPal team, over email, not a big deal)</p>

<p>Tip: the PayPal APIs are a little bit messy, documentation is usually poor but you have good libraries out there which abstract the intricacies of the PayPal protocol</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
