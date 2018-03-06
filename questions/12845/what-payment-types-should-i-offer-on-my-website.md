## What payment types should I offer on my website?

- posted by: [pixelearth](https://stackexchange.com/users/129602/pixelearth) on 2017-06-16
- tagged: `payment`
- score: 1

My website has customers from all over the world. We currently only offer credit card purchases and paypal purchases. I'm wondering if I would see an uptake in sales if I offered more payment types.

Since the app is custom, it isn't necessarily trivial to add a new payment type. Is there research that shows if it's better to offer a variety of payment types, or just a couple?

If I should add more types, which ones should I add? Google wallet? Apple pay? Something else?


## Answer 12847

- posted by: [Jeff O'Neill](https://stackexchange.com/users/46273/jeff-o-neill) on 2017-06-16
- score: 3

I don't have any evidence beyond my own experience, but my view is that there is very little benefit to add payment methods beyond credit cards and PayPal.  I use Stripe for credit card processing and PayPal.

Just about all customers in the U.S. are happy to pay with one of those two options.  If you implemented Google Wallet or Apple Pay, some of your customers might use it, but just about all of them would also pay with a credit card or PayPal so you are not realizing any benefit.

People in non-US countries often don't want to pay with credit cards.  Either because they don't have them or they have unreasonable fees for foreign purchases.  I have found that these people are generally happy with PayPal.  I don't see Google Wallet or Apple Pay providing a benefit here either.


## Answer 12846

- posted by: [Jurijs Kovzels](https://stackexchange.com/users/5570775/jurijs-kovzels) on 2017-06-16
- score: 0

From what I read on the topic everyone agree that the more options you have the (to the degree) better for for you, but no one provides any statistics. It is logical that you should use whatever your users are using instead of forcing payment methods on them.

Besides that, it should not be that difficult to add new methods in 2017. Payment processors as Braintree and BluePay promise easy integration and variety of methods.



## Answer 12853

- posted by: [dan_kaufhold](https://stackexchange.com/users/1552235/dan-kaufhold) on 2017-06-16
- score: 0

From my experience, you have most of the market covered when offering CC and PayPal. However some people might be more comfortable using different means. Also in some countries credit cards aren't as common as for example in the United States, so they would effectively be left with only one method (PayPal) to "choose" from.

If you consider a switch to other payment methods, you might consider using Braintree. They offer:

 - Credit/Debit Cards
 - PayPal
 - PayPal One Touch
 - Venmo
 - Apple Pay
 - Android Pay
 - Visa Checkout
 - Masterpass
 - Amex Express Checkout

So if I take Braintree/PayPal's decision to include these as a signal which are most used in the world, I would say having these is pretty safe. Also they are very easy to integrate and have SDKs for pretty much all popular programming languages.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
