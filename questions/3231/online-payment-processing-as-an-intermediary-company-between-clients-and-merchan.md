## Online payment processing as an intermediary company between clients and merchants

- posted by: [gpierris](https://stackexchange.com/users/1248492/gpierris) on 2015-01-28
- tagged: `mobile-apps`, `payment`
- score: 2

<p>We are developing a service where our users will be able to deposit a minimal amount, e.g., 10 euros to our startup's accounts, which will later be used as a form of credit to a number of shops/merchants. Hence,</p>

<p>a) We need to pay transaction fees to receive the payments from the users (e.g., 30p+3%).</p>

<p>b) We need to pay transaction fees again when paying the shops back (another 30p+3%).</p>

<p>Question:
Do you see a better approach on minimizing the costs of the transactions, i.e., merging somehow steps a) and b) ? </p>

<p>Tip: <em>I am not referring to optimization techniques like finding the least transaction fees for each step by using a different payment processing, but structurally avoiding the need to pay two times the transaction fees.</em></p>



## Answer 3258

- posted by: [Henry Taylor](https://stackexchange.com/users/1734959/henry-taylor) on 2015-01-30
- score: 1

<p>You are building a payment triangle involving a customer, a merchant and your service, and you are using credit card transactions to move money between all three players.  Why?</p>

<p>If your company has a contractual agreement with the merchants, there is a lot cheaper ways to move money between business partners.  Why not just write them a check?  Or if the merchants are in a hurry, do bank transfers.</p>

<p>As for getting money from your customers, consider providing incentives to get your customers to deposit larger amounts at a time.  That way you can pay the fixed portion of your transaction fee less frequently.</p>

<p>Hope that helps with your transaction fee issues, but I'm still curious about how you are handling the risk of charge backs.  The credit card companies give their customers an ability to reverse any transaction which they don't claim was valid.  A customer could therefore purchase a large credit in your system using a credit card, spend that credit with your merchants and then claim their credit card traffic was fraudulent.  Say bye bye to your credit card revenues, and you still owe your merchants for the products that customer purchased.  I don't need you to answer here in the forums, but before you open for business, you really need to figure out how you're going to cover yourself for that risk.</p>



## Answer 3240

- posted by: [theonlydanever](https://stackexchange.com/users/4692060/theonlydanever) on 2015-01-29
- score: 0

<p>You could merge both your options and take 30p + 6% and saving yourself 30p down the line, but ultimately covering your merchant fees.</p>

<p>Alternatively, you could pass all the fees onto the end user so a £10 transaction would be £10 + 6% + 30p = £10.90.</p>

<p>Can I ask which payment gateway you're using? Even <a href="https://www.paypal.com/gb/webapps/mpp/merchant" rel="nofollow">Paypal</a> don't charge 30p per transaction and I thought they were one of the most expensive out there.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
