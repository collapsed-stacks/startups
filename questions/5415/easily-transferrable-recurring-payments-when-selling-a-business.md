## Easily transferrable recurring payments when selling a business

- posted by: [Bemmu](https://stackexchange.com/users/5090/bemmu) on 2015-05-31
- tagged: `payment`, `e-commerce`
- score: 3

In my [current subscription box business][1] I've used recurring payments through PayPal recurring payment buttons.

Now that the service has grown nicely, I've occasionally entertained thoughts of selling it. However I have a large number of subscribers still subscribing through my personal PayPal account. I think this means that I would need to transfer my entire personal PayPal account to the new owner in order for them to be able to receive the payments without interruption. 

Transferring the whole account would be quite awkward, as the account is receiving other recurring payments as well. Ideally it should be possible to transfer only the recurring payments associated with a single app/site.

For my future apps/sites, what would be a better way to structure recurring payments to make transition easier when transferring ownership? 

  [1]: http://www.candyjapan.com


## Answer 5417

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-05-31
- score: 1

You can create a separate, autonomous PP account for each app:

- pp@app1domain.com
- pp@app2domain.com
- etc.

As a bonus, you can still access some of your money if your PP account is locked for any reason. ([It happens](http://www.paypalsucks.com/).)

For existing users that still pay on your personal account, an option might be to create a special subscription link, and prompt them to click it by email. Remind them each week or two until they click it -- e.g. first payment free, then the usual price they're paying. Inturrupt the process -- and all remaining subscriptions -- after a last call email sent a few months down the road. When they click the link, use the PP IPN to cancel the subcription to your account. As their subscription payment nears, their incentive to grab the free month will increase.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
