## Storing Credit Card information for ad-hoc payments

- posted by: [Paul G](https://stackexchange.com/users/5601094/paul-g) on 2015-01-09
- tagged: `payment`, `billing`
- score: 3

<p>I am starting a new project that will provide general support services to entrepreneurs. </p>

<p>The service will be provide on an ad-hoc basis. For example we may have requests from a customer several times in the space of a couple of weeks but then we may not hear from them for a couple of months.</p>

<p>I want to charge the customer per support request, but for convenience of the customer, I want the ability to store the customers card details so that they do not have to keep giving us their details.</p>

<p>So far I have phoned PayPal (I already use PayPal for card processing) &amp; Zoho asking for a solution but to no avail.</p>

<p>With thanks to anyone with any suggestions.</p>



## Answer 2933

- posted by: [Jason Mcmunn](https://stackexchange.com/users/5429346/jason-mcmunn) on 2015-01-09
- score: 3

<p>Storing people's credit card numbers is a huge risk.  If you don't have a PCI grade secure enclave to store the information in and you ever lose it to compromise you're in serious jeopardy.  I would do one of two things.  Pick a better partner that offers that service for you (probably white label).  Depending on what your technology stack is you can select the best partner best on that.</p>

<p>Another alternative would be to sell credits.  Think of them like facebook credits.  The entrepreneurs can purchase bundles of credits from you and they only have to restock periodically. </p>

<p>Another alternative would be monthly billing.  You might not be at a point in your business where you can afford to extend people credit, but if you are, that adds a lot of credibility to your business from a customer point of view.</p>



## Answer 2935

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-01-09
- score: 2

<p>Don't store credit card data. The risk in doing so is big, and you're not allowed to store some pieces of information (the security code at the back of the card.)</p>

<p>Charge in advance instead. Depending on what you type of client you have, also consider being a tiny bit lenient when it comes to enforcing things with repeat clients: "All right! So we're all good now. Btw, I can see your pre-paid support balance is [all used up|running very low], so please take a time to refill it at your convenience." or "OK let's get this done. Btw, I see your pre-paid support balance is nearly-used up, so you might need to refill it after we're done -- at your convenience."</p>

<p>Clients don't mind getting prompted to pay when you just saved the day. They'll happily pull out their credit card when you do. (They do mind, however, being told to <em>pay up or else</em>, as they feel they're getting gouged when you approach them so, and that is why I'm suggesting to be a tiny bit lenient -- just enough to make the pill easier to swallow, by putting delivering results before worrying about upfront payments when the balance is running low.)</p>



## Answer 3182

- posted by: [SilentSteel](https://stackexchange.com/users/1092182/silentsteel) on 2015-01-26
- score: 2

<p>You should integrate into a billing platform and use their API.</p>

<p>There is a <em>lot</em> of coding involved in billing and you don't want to do this yourself.</p>

<p>For example, FreshBooks handles:</p>

<ol>
<li>Secure credit card storage</li>
<li>Invoice generation</li>
<li>PDF exports</li>
<li>Automatic invoice emails</li>
<li><em>Snail mailing</em> invoices with a client- great for late payers to send a clear message.</li>
<li>Late fees</li>
<li>Late invoice email reminders</li>
<li>Tax reporting</li>
<li>Logging of invoices views (so you know if a customer saw the invoice and didn't pay)</li>
</ol>

<p>And a heck of a lot more!
So, yeah, programming with their API will definitely take time but it's worth it!</p>

<p>Here are the top choices for billing platforms. Not sure if all store credit card info:</p>

<ul>
<li>FreshBooks: Very easy to use. API is okay not the best.</li>
<li>Recurly: Heard very good things. Like Freshbooks.</li>
<li>WHMCS: Lets you run it all on your own server. Not sure how CC storage is handled but I think they provide the sophisticated encryption packages needed.</li>
<li>BillingOrchard: Haven't tried.</li>
<li>WaveAccounting: Very "complete" solution which ties into accounting deeply. Haven't tried the API tho.</li>
<li>Xero: Not sure if an API exists, but this is a very powerful accounting system that may also do this.</li>
</ul>

<p>For my last business, I integrated into FreshBooks and it was great. This can take a <strong>long time</strong> depending on how your product works. But it's worth it.</p>



## Answer 3147

- posted by: [Justin Clark](https://stackexchange.com/users/5675946/justin-clark) on 2015-01-24
- score: 0

<p>What you are looking for is a provider with the ability to tokenize or "vault" your card data. They provide you with a token in place of the card data and you store the token.</p>

<p>Later, to run a transaction on the same card, you initiate a transaction and pass in the token instead of a card number.</p>

<p>There are numerous services out there that provide this but are generally fairly expensive.</p>

<p>A couple that come to mind:</p>

<ul>
<li>Trustcommerce - Traditional merchant account w/vaulting</li>
<li>Merchant e-Solutions - Same TC</li>
<li>Spindle - Their developer integrations support vaulting. Payment Service Provider - No monthly fee model.</li>
</ul>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
