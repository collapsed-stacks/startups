## Is it customary and mutually beneficial to offer product sales in foreign currencies?

- posted by: [pixelearth](https://stackexchange.com/users/129602/pixelearth) on 2017-02-20
- tagged: `product`, `payment`
- score: 1

<p>This from one of my site users: </p>

<p>"The subscription plans can´t be paid using Paypal? (We pay a huge tax on currency exchange on credit cards in Brazil...)"</p>

<p>Is it customary to offer products in foreign currencies? How does this work?</p>

<p>Stripe customer support says "you'd need to use a 3rd party service to get the current conversion rate and compute the amount. Keep in mind that the rate used by Stripe to convert the funds back won't be exactly the same (Stripe's rate is "approximately 2% above the daily mid-market rate")"</p>

<p>So this kind of integration seems brittle and imprecise. And yet some of my customers could clearly benefit...</p>



## Answer 12153

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2017-02-20
- score: 3

<blockquote>
  <p>Is it customary to offer products in foreign currencies? How does this work?</p>
</blockquote>

<p>No, it's not. Customers like it, obviously, but from your standpoint it's about risk: by stating a price in this or that currency you're basically announcing that you'll pick up the currency exchange bill and take the currency risk related to transferring it back to your own currency on top.</p>

<p>There are (pricey) insurances for the latter btw - see e.g. Coface. But they're usually used for 5-figure+ export-related transactions rather than day to day couple-of-bucks online transactions.</p>

<p>IMO it breaks down to how big a float you need in the currencies you're dealing with.</p>

<p>If you're constantly dealing with Brazilian Real invoices, then yeah, it's perfectly fine to accept Real payments, because it spares you from needing to buy/sell the currency when you receive/send payments in it.</p>

<p>If not, then your better interest is to stick to your local currency. Note that some countries allow you to file your accounts and taxes based on a non-local currency. Probe into that with your accountant if your local currency isn't USD or EUR.</p>

<p>In practical turns, if you've an account with a balance in that currency it may makes sense to accept it; if not, it's usually better let your clients eat the risk.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
