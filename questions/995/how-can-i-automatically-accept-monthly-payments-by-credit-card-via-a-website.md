## How can I automatically accept monthly payments by credit card, via a website?

- posted by: [Matthew Haugen](https://stackexchange.com/users/1325646/matthew-haugen) on 2014-10-15
- tagged: `tech-company`, `merchant-services`, `payment`, `saas`
- score: 1

<p>I'm looking to set up a service that has a flat monthly fee. How can I set up my website to allow users to input a credit card that then automatically gets billed monthly, with minimal human intervention?</p>

<p>As I understand it, QuickBooks does what I want, kind of. But that requires human intervention (practically speaking, at least). It'll be relatively low-volume, so I <em>could</em> theoretically just accept credit card information and manually via a regular <code>TextBox</code>, then feed myself an alert to copy that into QuickBooks (or equivalent) every time someone signs up. But that seems like it could become cumbersome pretty quickly, not to mention nothing would be validated (beyond the unimpressive checksums you can find online) until I had gotten around to typing it up.</p>

<p>I looked around online, but all the solutions I can find are for one-off purchases (like in a web-based store).</p>

<p>Just as examples, and they clearly have to deal with higher loads than I would, an ideal solution would be something like I imagine Netflix, Hulu Plus, SharePoint Online, etc. would use. I suspect <em>they</em> don't have someone sitting and copying over everyone's credit card information.</p>

<p>I suppose I could write a web-job or something, perhaps, to run in the background and bill people monthly, if an ecommerce plug-in had a code-only API available. But that just seems like it would be more trouble than it should be.</p>

<p>How can a SaaS startup automatically accept monthly payments?</p>



## Answer 997

- posted by: [Jeremy Parsons](https://stackexchange.com/users/497810/jeremy-parsons) on 2014-10-15
- score: 2

<p>Recurring payments used to be a hassle. We're in a startup world, so lots of startups jumped in to fill the void, which encouraged the payment platforms to up their game.</p>

<p>There are still plenty of financial institutions who don't offer this facility on their gateways, and there are some jurisdictions where the fees are high unless you take 'raw' service. But that detail probably isn't relevant to you today.</p>

<p>In that case, the usual suspects include <a href="http://paypal.com" rel="nofollow">Paypal</a> and <a href="http://stripe.com" rel="nofollow">Stripe</a>. Stripe tends to be favoured where you don't want the payment processor to show through too much to your users, while Paypal has advantages where their brand name and scope in terms of payment sources are of value.</p>

<p>Recurring payments are a great way of turning your web app into a viable business. But don't rely on the payment provider as your primary source of customer visibility. For instance, if a customer's usage has dropped right off, you might want to consider emailing them to find out what's up, rather than have them be reminded you exist by seeing the payment going out - which can be a major source of churn.</p>



## Answer 7280

- posted by: [irms](https://stackexchange.com/users/49306/irms) on 2015-09-06
- score: 2

<p>I would highly recommend using <a href="http://stripe.com" rel="nofollow">Stripe</a> if you can find someone to integrate that service for you. You'll love it long term and it's free to sign up. It handles recurring payments with no problem and it's perfect for SaaS startups.</p>



## Answer 996

- posted by: [blunders](https://stackexchange.com/users/216182/blunders) on 2014-10-15
- score: 1

<p>Pretty much any major payment gateway should offer this service. Unless you're PCI compliant, you <strong>really</strong> should not be storing credit card payment information. For example, PayPal has <a href="https://www.paypal.c/pdn-recurring" rel="nofollow">subscription and recurring payment services</a>.</p>

<p>Main things to look for in a recurring payment service are automated alerts to that allow you to end service, and enable the payer to fix the issue on their own; meaning put in a new CC, change/approve the payment amount/type, etc.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
