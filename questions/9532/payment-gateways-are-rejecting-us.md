## Payment gateways are rejecting us

- posted by: [nerdalert](https://stackexchange.com/users/7006917/nerdalert) on 2016-06-23
- tagged: `payment`
- score: 1

<p>My startup company is currently going through some issues with regards to accepting Credit card payments. We have a Wordpress site, which a client can go into and select one of three subscription packages to purchase (monthly, semi-annually, or annually). </p>

<p>We have the whole mechanism working fine, in that their subscription is activated once a payment goes through, and the recurring charges are handled by the system just fine. This has been tested using sandbox PayPal and Braintree accounts.</p>

<p>But we are having unforeseen issues with payment gateways rejecting our startup because of "higher risk" involved with startups and "subscription based models". In other words, these particular gateways' sponsoring banks are not granting us the required Merchant account and as a result rejecting our application.</p>

<p>Both PayPal and Braintree rejected us because we do not have a supportive turnover. Well us being a startup, this is expected.</p>

<p>My company is based in Europe (Cyprus), so a lot of gateways are not supported (Stripe, and a few others). </p>

<p>Has any other European startup faced this issue and how did you get around this? We are considering contacting every single gateway available in our region and asking if they will be willing to work with us. Does this sound like the best course of action?</p>



## Answer 9533

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2016-06-23
- score: 1

<blockquote>
  <p>We are considering contacting every single gateway available in our region and asking if they will be willing to work with us.</p>
</blockquote>

<p>... is likely the right way to proceed indeed, if incorporating elsewhere or moving away from subscriptions are not an option.</p>

<p>You're not merely based in Europe. You're in Cyprus, which is up there in the list of risky locations alongside Lichtenstein and Malta - or places like the Seychelles, Belize, and a slew of other tax havens. When it comes to credit card processing, they basically have Nigeria written all over them. Monthly charges for merchant accounts in those areas can run into the thousands per month owing to the risk, if only because of the impression that a) money can easily appear and disappear there without leaving much of a trace, thereby opening a floodgate for potential fraud and abuse; and b) it's hard to collect in those places.</p>

<p>It matters little if your business is perfectly legit or if those impressions don't hold so much water in practice. The fact is that the typical online business in your location (<a href="https://startups.stackexchange.com/questions/1592/tax-structuring-how-to-pay-no-corporate-tax/1665#1665">read this if it isn't</a>) is one that caters towards offshore companies, shipping, or gambling; it's not a subscription-based startup. By default, CC providers will assume you fall in one of the latter categories.</p>

<p>A last note on subscriptions: do you <em>really</em> need them? I ask because subscriptions can be forgotten, so they tend to generate some chargebacks after a certain period of time. They can also go unnoticed if you don't pay much attention to your CC bills - until you do and realize someone subscribed you to a random website with a stolen CC number <em>ages</em> ago. If you can get rid of subscriptions altogether in your business model, you'll likely find better deals.</p>



## Answer 11267

- posted by: [JJBee](https://stackexchange.com/users/6998558/jjbee) on 2016-10-03
- score: 0

<p>Incorporate as a US corporation from outside the USA. Google this, and you will find a few examples of startups who have done this for the reason you're citing.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
