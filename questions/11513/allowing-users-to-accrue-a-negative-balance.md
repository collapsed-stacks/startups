## Allowing users to accrue a negative balance

- posted by: [Jonathan](https://stackexchange.com/users/1247179/jonathan) on 2016-11-09
- tagged: `payment`, `accounting`
- score: 4

Some of my users use my web service and pay in small amounts where the credit card processor pretty much takes the entire charge and I receive almost nothing.

I am considering allowing users to accrue negative balances of up to $10. This way when they pay off their balance the credit card processing fee will be small relative to the payment.

Is this something that users will be OK with? Are there other reasons why this may be a bad idea? (I am prepared to absorb the loss if they decide not to pay, since it is relatively small)


## Answer 11515

- posted by: [Jeremy Parsons](https://stackexchange.com/users/497810/jeremy-parsons) on 2016-11-10
- score: 1

You're looking for a way to let your users help you solve your problem. Personally, I'd start the other way round.

There are great reasons why web services like to offer subscriptions or/and purchase of credits. One reason is that your average transaction value (ATV) goes up, reducing the impact of payment processing fees. Another is that you can engage users more ways, and reward your best customers.

What's the biggest risk with your negative balance idea? It's that **you're rewarding dishonesty**. Your users may not suddenly start opening a new account every time they want your service so they never have to pay, but they could, and knowing that drives a wedge between you. 

With credits or subscriptions, you can always offer incentives - a month for free, or the second tier for the price of the first, or double the credits bought with the first purchase. Perhaps more importantly, **when you offer a familiar structure, you lower friction and complexity**. The cases where you should innovate a payment workflow are few, and you've said nothing that warrants an exception.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
