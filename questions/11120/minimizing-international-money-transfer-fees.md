## Minimizing international money transfer fees

- posted by: [Bemmu](https://stackexchange.com/users/5090/bemmu) on 2016-09-13
- tagged: `payment`
- score: 1

<p>I have an online store in Japan, but all my payments are arriving via Stripe in USD. </p>

<p>I think my Stripe account is somehow European, as it only allows me to withdraw to EU. This means now I need to first withdraw USD to a bank account in Europe in EUR. Then I send that to Japan, where it gets again converted to JPY.</p>

<p>Am I losing a lot of money doing this? If yes, any better way while being able to charge in USD? Transfer fees are hard to understand, as I assume some of them are built into conversion rates, which change moment to moment.</p>



## Answer 11122

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2016-09-13
- score: 2

<p>That sounds really expensive - you're probably losing to the order of 10% of anything you sell online owing to CC fees, Forex fees, and wire transfer fees.</p>

<p>Start by double-checking with Stripe that having a JP-based account is not feasible. If you can do that, it'll likely be your cheapest option.</p>

<p>If you can't, check if your EU bank offers USD accounts. They usually do, and for all you know Stripe may allow you to put USD onto a USD account, thereby sparing you from a costly back and forth to EUR.</p>

<p>Also look into opening an account for your business in the US. This can be complex if you've no SSN. You might need to incorporate locally, and you might need to go there in person because of money laundering-related laws. But it might very well be worth doing in the end. (If you do this, be sure to keep things pristine from a tax standpoint and to retrieve all revenue to JP, else you'll get slaughtered by your taxman). Upon doing that, get a US-based Stripe account.</p>

<p>A last option, of course, is to change CC processor.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
