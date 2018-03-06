## How to reduce and minify the cost of two-step verification for login security?

- posted by: [Saeed Neamati](https://stackexchange.com/users/429080/saeed-neamati) on 2016-09-06
- tagged: `web-apps`
- score: 0

I have created a service in which customers log in and use stuff.

For the purpose of security, I want to activate 2-step verification for login process.

Yet the more I search, the more I realize it's truly expensive to send transactional SMS messages.

How businesses afford this volume of short messages? How can I minify the cost of this feature for my startup?


## Answer 11086

- posted by: [Community](https://stackexchange.com/users/-1/community) on 2016-09-06
- score: 3

Two-step verification, better know as Two-Factor Authentication or _2FA_, can be done in many ways. Text messages are just one way to do 2FA. The benefit of text messages is they are extremely simple and everyone knows how to use them. The downsides are the costs and the fact that it assumes cell phone number cannot be stolen [which is not always true](https://www.youtube.com/watch?v=LlcAHkjbARs&feature=youtu.be&t=3m57s). Text messages can also be slow.

Using text messages for authentication is better saved for verifying phone numbers upon registration (once per user), rather than as a form of 2FA on each login.

A more common form of 2FA is [TOPA](https://en.wikipedia.org/wiki/Time-based_One-time_Password_Algorithm) values calculated by your site on one end, and by a device the user has (usually a cell phone) on the other end. [Many services use this](https://en.wikipedia.org/wiki/Time-based_One-time_Password_Algorithm#Server_implementations). TOPA requires an authenticator app. There are many such apps including [Google Authenticator](https://support.google.com/accounts/answer/1066447?hl=en), Microsoft Authenticator, and my personal favorite because it has extra features, [Authy](https://www.authy.com/app/mobile/). (BTW, take a look at Authy's offerings for developers.) Using TOPA should cost you very little. It's also very fast because users do not have to wait on a slow cell phone network to deliver them a code via SMS. And the TOPA algorithm is standard so the authenticator apps are interchangeable.

You can do 2FA in other ways like asking security questions, asking someone to type in a number from a card they are holding, or having some sort of physical dongle that users plug into a USB port like a [YubiKey](https://www.yubico.com/products/yubikey-hardware/). These methods may have a one-time up-front cost but then should cost little or nothing over time.


## Answer 11273

- posted by: [JJBee](https://stackexchange.com/users/6998558/jjbee) on 2016-10-03
- score: 0

Maybe you should use device fingerprinting instead and require email code verification if login comes from a new device. 2FA is not something I would worry about for a startup. On top of just cost for 2FA, it can be abused for IRSF--with call verification, but I imagine there is something similar with SMS.


## Answer 11106

- posted by: [itsben](https://stackexchange.com/users/2371687/itsben) on 2016-09-09
- score: -2

 The best way to grow and verify your users

To get Digits, just download Fabric and install the Digits Kit. 

https://get.digits.com 



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
