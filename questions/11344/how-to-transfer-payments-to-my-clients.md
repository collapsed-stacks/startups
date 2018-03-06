## How to transfer payments to my clients?

- posted by: [Sergei Basharov](https://stackexchange.com/users/46016/sergei-basharov) on 2016-10-14
- tagged: `payment`
- score: 3

I am working on an app which receives payments for products Z owned by clients B from clients C


1. Client A publishes a product Z for selling => 
2. Client B buys it =>
3. My App receives the money via Stripe =>
4. Client A needs to receive the money minus my fee and commissions.

I am wondering what's the easiest automated way to perform the step 4?

Do I need to integrate another service into my app to send payments to clients? Or can I do this inside current Stripe setup?

Please recommend.


## Answer 11345

- posted by: [Jeremy Parsons](https://stackexchange.com/users/497810/jeremy-parsons) on 2016-10-14
- score: 1

Take a look at **chained payments**, supported by both Stripe and PayPal. 

You need to think about who the customer is buying from (and will see on the transaction detail) and be very clear about the payment logic. That's doubly important if you have to deal with refunds.


## Answer 11487

- posted by: [Gianluca Ghettini](https://stackexchange.com/users/928106/gianluca-ghettini) on 2016-11-04
- score: 0

<p>Chained payment by PayPal is the way to go. <a href="https://developer.paypal.com/docs/classic/adaptive-payments/ht_ap-basicChainedPayment-curl-etc/" rel="nofollow noreferrer">Check it out!</a></p>

<p>It's an advanced payment flow for which you'll have to submit a request to get an AppId, pass a very simple screening process (few questions by the PayPal team, over email, not a big deal)</p>

<p>Tip: the PayPal APIs are a little bit messy, documentation is usually poor but you have good libraries out there which abstract the intricacies of the PayPal protocol</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
