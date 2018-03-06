## Importing our customers' Mastercard activity to get correct exchange rate for purchases in foreign countries?

- posted by: [Rasmus Severinsen](https://stackexchange.com/users/5103633/rasmus-severinsen) on 2014-10-07
- tagged: `accounting`
- score: 4

We are a startup doing expense reporting for our customers. We have run into some challenges when it comes to recording the correct amount on the books when our customers make purchases abroad. Apparently, the publicly available day-rates reported by Mastercard cannot be used, because the exchange rate applied by Mastercard is that of the day the money is recorded - and NOT the rate of the day the actual purchase was made (there is a varying delay of typically 2-5 days). 

We have therefore found ourselves in a situation where we might need access to our customers' Mastercard transactions where the correct exchange rate is implied by the amount in foreign and local currency. However, we have been unable to find any information about how we can go about this matter in technical terms. We heard rumors that we need to be PCI compliant and Mastercard possibly could send a .CSV file on a regular basis - granted we have consent from our customers. I know that many businesses (such as Mint.com) has this feature where people can import their personal credit card purchases.

The question is therefore: Does anyone know the technicalities behind importing such Mastercard activity from our customers? 


## Answer 5548

- posted by: [Jason Mcmunn](https://stackexchange.com/users/5429346/jason-mcmunn) on 2015-06-18
- score: 1

I can speak a bit to the technology behind companies like mint.  I worked at a bank and the interface they used was very cludgy. They basically capture the user's credentials and replay them over and over.  They log in as the customer a few times a day to the customer's bank (not to Master Card directly).  They pull in the transactions and compare them to their version of register.  They may log into 5 or 10 different accounts to gather the whole portfolio of a user.

There are services that will do this for you. They provide middleware for you to capture that information, but they are expensive.  Yodlee and CashEdge (bought by fiserv) are to companies to investigate.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
