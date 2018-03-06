## Do we need to verify user's email address if we verified his mobile phone?

- posted by: [Hamed Afshar](https://stackexchange.com/users/1545654/hamed-afshar) on 2017-04-26
- tagged: `business-structure`
- score: -1

In the signup form of my website, I ask the user for email address as well as phone number. Verifying both in the signup process will be a pain for the user.
So, my thought is to only verify his phone number.
I'm wondering how often users will enter a fake email address, but a correct mobile?
What disaster may hit me if I only verify phone number?


## Answer 12560

- posted by: [user1091558](https://stackexchange.com/users/1098507/user1091558) on 2017-04-26
- score: 2

You are doing it wrong.

For a internet business email verification require more than mobile verification.

People may change their mobile number often, but rarely change the email address. 

Some users may type their email address incorrectly. By verifying email address you are making sure that the user is using the correct address.

You also don't want to send spam to incorrect email addresses. 

So ask your users to verify both. 



## Answer 12561

- posted by: [theonlydanever](https://stackexchange.com/users/4692060/theonlydanever) on 2017-04-26
- score: 0

Does it not depend on the industry or sector you're in?

A blog would suffice with an email address, whereas a financial firm would require an email **and** a phone number, for example. (Phone number to send a code via SMS, an email to send confirmation and financial statements).

Sometimes, there are legal/compliance reasons why companies need an email address... but it'd also mean that you're able to send marketing emails or updates (if the client allows it). 

> **I'd ask for an email address if it's going to add value.** Otherwise,
> verifying users through mobile number is probably enough.

Sidenote: Don't forget that security is everything when it comes to the Internet. If you're storing customer details you need to make sure it's safe. If your database is hacked and you lose customer details, you can pretty much say goodbye to your business.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
