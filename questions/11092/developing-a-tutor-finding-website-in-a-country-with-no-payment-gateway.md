## Developing a tutor finding website in a country with no payment gateway

- posted by: [Fahad Uddin](https://stackexchange.com/users/160083/fahad-uddin) on 2016-09-07
- tagged: `business-model`
- score: 1

I am working on creating an online tutor finding website. The students and parents would be able to see reviews and details of the tutor and contact them through the website or through the given number. I need to work on a win-win situation where the website becomes profitable.

There is no online payment gateway (there are a few attempts made but the services don't have many users).

Now after careful thought, I figured out the following business model,

Students find tutors through the website. After a month student gives review about the tutor and pays the first month fee to the site using the bank or we collect the cash from house. We then send 50% of the first months fee to the teacher (This is my business model).

Please advise me if I should implement this idea and test it.

Thanks 


## Answer 11096

- posted by: [paulzag](https://stackexchange.com/users/5451744/paulzag) on 2016-09-07
- score: 1

I think an entrepreneur should implement an idea and test it. The reality is that no one knows anything about the state of your market. Also you haven't mentioned your country (I assume Pakistan).

However I can make some observations around business models generally and your proposed business model in particular.

I don't understand how your current model can scale. After 1 month the students will pay you for the tutor using a bank or you collect the cash? It seems difficult. What if they don't pay?

## You must work out how to get the money.
You don't have to develop a payment gateway, but *getting paid* is how you *get paid*. If people paying money into your bank account by visiting a bank is the only way to get paid, then work out how to make that work for you. It may mean there is no ecommerce _instant payment, next day delivery_. But people will pay for something they want. When I started selling online we did not have credit card facilities. Customers had to visit a bank and deposit into our account (or use early EFT methods) but our offering made it worth it to them.

Are you sure there aren't payment gateways available that you haven't discovered? 2Checkout (supports Paypal), Skrill, UBL gateway, MCB, Easypay by EasyPaisa, plus banks gateways.

## Transactions leak from your market
There is a financial incentive for tutors and students to take the transaction out of your marketplace as soon as possible. Getting a tutor cheaper and the tutor getting more than you pay makes it attractive for them to cut you out of the deal.

You can address this via becoming the escrow service but *that* becomes your business model. The student pays for 1 month of tutoring on joining. You hold the funds as a satisfaction guarantee. But 1 month of tutoring seems like a long time to keep the tutor's money. Plus who knows what other problems holding students money will create. Also asking for money up front will limit student adoption of the service.

Will tutors start offering a heavily discounted "introductory" lesson just to meet potential students?

## Classified style ad revenue

This is the eBay/Kijiji style business model. You create a free-to-list service for students and tutors. Revenue is created via "listing upgrades" like top-of-the-page, borders, photos and sample uploads. That way some advertisers (the tutors) may want to pay to stand out from the crowd. You also sell ads on your site that matches your demographics.

## List Tutors for Free but charge to reply/send quotes.
This is the dating site model. The students access the site for free and can see all the tutors for their local area. Tutors get a free listing too. Students may message Tutors for free. Your software must obfuscate phone numbers and email addresses (or you manually approve messages). But Tutors making contact with a potential student costs money (or _points_). Tutors subscribe (for example) for 5 quotes a month. Once they have sent out 5 quotes they must renew their 5 quotes. You can limit the number of quotes a student receives to say 3 quotes if you want. 

This model allows you to buy student traffic. If each quote costs $1 to the potential tutor and there is a maximum of 3 quotes per student, each student requesting a quote is worth $3 in revenue. If you can acquire students placing ads for less than $3 per request-for-quote it is self funding. Adjust these dollar amounts to suit your country.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
