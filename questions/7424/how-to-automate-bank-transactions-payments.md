## How to automate bank transactions / payments?

- posted by: [Xeros](https://stackexchange.com/users/6984932/xeros) on 2015-09-26
- tagged: `payment`
- score: 3

<p>I need to send money to many different accounts, usually only small amounts and often across borders. I don't want to do all the transactions manually, so I'm wondering what other options are available? Ideally I would be able to provide a data file (CSV file) or access an API.</p>

<p>I already know Paypal offers mass payments, but I would appreciate any input on alternatives.</p>



## Answer 7425

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-09-26
- score: 2

<p>Banks all provide some kind of solution to do this. Albeit pricey more often than not, they're able to help you out. So do check there.</p>

<p>Also look into Stripe. Quoting Cristina Cordova's answer to <a href="https://www.quora.com/What-is-the-best-way-to-send-out-mass-payments?share=1" rel="nofollow">this Quora question</a>, where several other solutions are outlined:</p>

<blockquote>
  <p><a href="https://stripe.com/blog/send-payouts-with-stripe" rel="nofollow">Stripe now has an API</a> that
  allows you to collect funds processed via credit card into one Stripe
  account, and then programmatically send ACH bank deposits to anyone
  with a US bank account. It's intended for Stripe users who are
  providing some service or product for their customers, but need to be
  able to pay out third parties like sellers, vendors, or service
  providers.</p>
  
  <p>You <a href="https://stripe.com/docs/tutorials/charges" rel="nofollow">create charges as usual</a>, but
  instead of those payments being automatically transferred to your bank
  account, the funds will instead accumulate in your Stripe account. You
  can then collect bank account details from your users, and transfer
  funds to them with a single API call.</p>
</blockquote>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).