## Putting banking details on website: bad idea?

- posted by: [nic](https://stackexchange.com/users/80211/nic) on 2016-07-21
- tagged: `website`, `payment`
- score: 2

Many customers buy our product via bank transfer, usually via this workflow:

> Customer: I want to buy X zorglubs.  
> Us: OK, please transfer Z yen to our bank account: (bank account details)

Because emails can easily be faked, I would like to replace with this workflow:

> Customer: I want to buy X zorglubs.  
> Us: OK, please transfer Z yen to our bank account, see: http://z.com/bank-account-details

**QUESTION**: Is it safe to do that in Japan? Would this expose us to various scams/etc?


## Answer 9746

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2016-07-21
- score: 3

A bank account number is not so useful by itself, but it's still a relevant piece of information. Think of it like a credit card number without the extra details. It's more than nothing.

That's not the real issue here though. What you describe is relatively poor form either way. You should be putting an invoice behind a login on an https server instead. (Or use Freshbooks or some equivalent to issue the invoice that will take care of that for you.)

If that's not an option, send it by email like you're doing now, and use a [text expander](http://lifehacker.com/a-comprehensive-guide-to-textexpander-1616374942) to avoid needing to re-type it each time.


## Answer 9748

- posted by: [Pulkit Agrawal](https://stackexchange.com/users/6564375/pulkit-agrawal) on 2016-07-21
- score: 1

Bad idea is relative but why take the risk if it's unnecessary? Try using Paypal or Stripe or something similar to have to avoid this.


## Answer 9765

- posted by: [Edward Craig](https://stackexchange.com/users/8882535/edward-craig) on 2016-07-24
- score: 0

Never put your banking information on your web site for any reason, since it can open up your company to theft.

I'm not familiar with Japan's methods for wire transfers, but here in the States, all that is needed is the bank's routing number and account number.  Thieves can get the information, make checks using blank check stock and magnetic ink that's easily obtainable on the internet, and drain an account.

Here's a Dateline/NBCNews story about this type of scam.  Read the middle section about Debbie Perry. (http://www.nbcnews.com/id/29903354/ns/dateline_nbc-the_hansen_files_with_chris_hansen/t/promises-promises-work-from-home-scams/)

Wire transfers are common for international purchases as well as larger transactions, such as $100,000USD or more, and the $30USD fee is insignificant at that level.  There are a couple things you can do to protect yourself.

First, get a separate bank account for these transfers, and move the money into your regular account as soon as it arrives.  If you get hit by fake checks, they won't take all of the company's money.  In the States, you'll get the money back after filing a police report, but it can take a few days.

Second, you need to use an invoicing strategy.  Some banks allow you to issue an invoice through their website.  When the customer pays by wire, it's done directly through the bank's website so the customer doesn't need your account information.

Also, all communication can be faked, not just email.  Your solution provides little additional protection from just emailing the account information.


## Answer 9767

- posted by: [Ace OfAllMedia](https://stackexchange.com/users/8881266/ace-ofallmedia) on 2016-07-24
- score: 0

Does Google Wallet work in Japan? Honestly - if you can't for whatever reason get an actual merchant account  or TPP (and i can completely understand if you're purposely avoiding PayPal btw, any large sum of money in their hands is an enormous risk in itself) - then you can invoice people through Google Wallet....that would enable them to use a credit card or checking account to transfer funds from their account to your Wallet account (you can set it up in 5 minutes within your Google Account console) and from there, you can withdraw from your Google Wallet to your Checking account, and it keeps you protected...

By the way, A checking account number online is EXTREMELY risky... What you need to provide for a customer to wire you the funds directly would be the PAH Name, account number and the Swift/Routing number and (in the US) the zip/postal code....which is precisely the same as what you need to initiate an ACH Debit FROM your account - food for thought



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
