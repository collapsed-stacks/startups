## How do startups like mint.com get banking data?

- posted by: [Fahad Uddin](https://stackexchange.com/users/160083/fahad-uddin) on 2017-01-29
- tagged: `product`
- score: 4

I came to know about [Mint.com][1] which grabs data from the users bank about his financial life. How do these startups penetrate through the login details of the bank and not being a robot confirmation?


  [1]: http://www.mint.com


## Answer 12018

- posted by: [kforsythe76](https://stackexchange.com/users/3749136/kforsythe76) on 2017-01-29
- score: 5

The most common way is through financial data aggregators like Plaid or Finicity.  Aggregators negotiate relationships with banks allowing the aggregators access to customer banking data.  Many terms are negotiated such as query frequency, level of detail, and security patterns.  Banks will provide API's and/or whitelist aggregators for access to the bank's website (for screen scraping).  In turn, the aggregator will extract the data from multiple banks, normalize it, and make available to aggregator customers (like Mint) via API's.  


## Answer 12954

- posted by: [Frédérick Lavoie](https://stackexchange.com/users/11240676/fr-d-rick-lavoie) on 2017-07-02
- score: 3

Great question.

The first answer your received gives a good chunk of the answer, so here are my additions to it:

**1. Providers of financial data**

Indeed, apps connecting directly to bank accounts all use a financial data aggregator (finagg) to do so. A lot of the scraping is done by simply emulating the behaviour of the user, to connect directly in the account and retrieve the data. In North America, it's often the case that banks are unwilling to deal with third party scrapers. That said, it just makes it more difficult to access the data, but a good finagg is able to offer access nevertheless.

**2. Quick tip if you want to build a finance app:** 

All finance apps that interact in a way or another with their users' bank information (account number, transaction history, etc.) must either ask the users to enter manual information, or gets the services of a finagg. If you build an app today, the market standard prescribes you offer your users' instant synch with their bank accounts.

**3. How to choose your provider?**

One thing to know is that a lot of APIs are unstable, as they're dealing with changing bank interfaces, and a lot of use-case that are hard to handle.

The one thing to do when choosing your provider is making sure you get the best one available to your market. You have big international brand names, but for instance in the US Plaid is renown to be the best provider.

In Canada, due to the low service level experienced by companies we previously operated, my partners and I have launched Flinks, the only finagg dedicated to the Canadian market.

If you plan to build a finance app in Canada, check out what we do (https://flinks.io/)

Cheers!


  [1]: https://i.stack.imgur.com/zHW4u.png



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
