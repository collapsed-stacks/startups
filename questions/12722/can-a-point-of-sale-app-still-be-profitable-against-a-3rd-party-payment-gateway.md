## Can a point of sale app still be profitable against a 3rd party payment gateway?

- posted by: [cfly24](https://stackexchange.com/users/5925052/cfly24) on 2017-05-26
- tagged: `mobile-apps`, `payment`, `applications`
- score: 0

Is it possible to make any money and be competitive writing your own point of sale app (tablet/mobile) against someone else's payment gateway?

All the Payment APIs I could find leave no room for profit. For example, Stripe charges 2.9% + 30¢ for every transaction, but a Square POS Register charges fees of 2.75% per swipe transaction. Is there any payment platform that you can use to onboard merchants, authorize credit cards, and still have room for any type of profit?

Or is the space simply too competitive without investing the hundreds of thousands for your own payment gateway?

Thanks!


## Answer 12729

- posted by: [Gypsy Spellweaver](https://stackexchange.com/users/9933161/gypsy-spellweaver) on 2017-05-28
- score: 0

I suspect that the only "point of profit" for a new POS app would be in value-added service. Even Square, which I use, is constantly marketing their value-added features. The "profits" from transaction fees are probably minimal anyway, since there's going to me major expenses involved in building. maintaining and running the gateway. Square Register, itself (sans added features) seems to be well thought-out and works easily (even on my Gen. 4 iPod running iOS 6.1). Where their standard package falls flat on its face is the web store front they offer.

I'd suggest targeting either a subscription-based service, or value-added features. Using your app as a front end to an established gateway. Leave the gateway to handle the transaction fees, making it plain in your app that _you_ don't handle the payment - Square (or whomever you choose) does. Maybe even allow your front end app to select from multiple gateways, where the user establishes their own account there and your app only connects to the API of the selected gateway.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
