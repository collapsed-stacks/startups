## How to make a groupon like site successful in a country where online wallets are nascent?

- posted by: [Fahad Uddin](https://stackexchange.com/users/160083/fahad-uddin) on 2017-06-24
- tagged: `payment`
- score: 1

<p>I am working on a Groupon like site in Pakistan. In order to make it successful, I need a payment system that people will use to prepay for the deal. The payment systems in the market are very nascent and require more time to get mature. I have two choices,
1. Partner with a payment systems and use their service for the payments.
2. Create my own payment system and integrate it with the app.</p>

<p>Which selection should I go for?</p>



## Answer 12904

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2017-06-24
- score: 3

<p>When it comes to payments, don't roll your own. Ever. It's way too easy to get something wrong in the process and get screwed 10 times over. Use a battle-tested solution. And choose wisely: extensively test the solution before deploying it.</p>

<p>Personal anecdote: at one point I was selling a digital product using a pre-built shopping cart that I adapted as a plugin on WordPress. It turned out it accepted decimal values as units and, sure enough, a user eventually became curious enough to pass "0.1" as quantity.</p>



## Answer 12913

- posted by: [Nikita Kononov](https://stackexchange.com/users/7861393/nikita-kononov) on 2017-06-25
- score: 2

<p>I would suggest you go with ready payment gateway which supports payments from Pakistan. </p>

<p>A full-stack payment gateway will cost you a couple of $100,000s at least to build. Also, you need to contact an acquiring bank and make a lot of paper stuff. </p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
