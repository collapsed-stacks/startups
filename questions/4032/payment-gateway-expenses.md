## Payment gateway expenses

- posted by: [user4685174](https://stackexchange.com/users/5959610/user4685174) on 2015-04-18
- tagged: `payment`
- score: 3

<p>What would be the average cost per transaction for a payment gateway based in the USA.This should include the bank charges and all other recurring charges.Is there any source from where I could figure out the cost per transaction that a payment gateway based in the USA would incur.</p>



## Answer 4033

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-04-18
- score: 2

<p>It completely depends on the provider, on the industry you're in, and on where you're located. If you operate a shoe store out of NYC, your US-based merchant account related costs will look nothing like those of an online casino operating out of the Caribbean. The former might be getting a small flat rate per transaction and/or a small percent shaved off of the transaction, and sometimes a small setup fee and a small monthly recurring fee; they may end up paying ~3% in total. The latter might face a $5k+ monthly charge on top of higher transaction fees (~5-6%), because most merchant account providers won't want to touch them with a 10-foot pole.</p>

<p>Also note there's more to choosing your merchant account provider than mere costs. Think good APIs, good docs, fraud management tools, and the need for sandboxing for testing.</p>

<p>Stripe is very popular for good reasons. You'll find a whole bunch of other popular options by googling for "stripe vs", "paypal vs", "2checkout vs", or "authorize net vs" and letting Google make suggestions.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
