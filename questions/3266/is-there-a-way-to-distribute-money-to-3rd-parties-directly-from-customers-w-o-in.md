## Is there a way to distribute money to 3rd parties directly from customers w/o incurring 2x fees?

- posted by: [jt000](https://stackexchange.com/users/4550640/jt000) on 2015-01-30
- tagged: `finance`, `merchant-services`
- score: 0

<p>Say for example, a non-profit corporation of 4 members needs to pay their electric bill ($10), rent ($10), and water bill ($10) for the month. They need to send out a bill of $7.50 to each member. Each member pays the $7.50 bill with their credit card to the corporation. Then the corporation pays to the utility companies each $10.</p>

<p>If this were done with credit cards, then each transaction would be almost instantaneous but would incur large charges from member->corp, then corp->3rd party (essentially taking 2x merchant fees).  </p>

<p>If this were done with ACH, then each transaction would be cheaper so 2x fees is less important but the transactions take 1-3 days which would mean less time before the 3rd parties get paid.</p>

<p>Assuming all transactions occur online (so cash is non-option) within the same marketplace (so one system manages all transactions), is there a way to have instant transactions &amp; lower merchant fees (ideally 1x fees) when paying out 3rd parties directly from members?</p>



## Answer 3271

- posted by: [Davidraz](https://stackexchange.com/users/4447731/davidraz) on 2015-01-30
- score: 1

<p>You might be able do the first part of the transaction for free with - 
<a href="https://venmo.com/" rel="nofollow">https://venmo.com/</a> or <a href="https://square.com/cash" rel="nofollow">https://square.com/cash</a> (You can transfer between bank accounts in the US for free so its good for members->>corporation)
Then you can make the payment to the utility companies as you would do it otherwise. </p>

<p>If its small amounts of money its a valid solution but if its higher numbers you should consult with an accountant regarding the local tax implications.</p>



## Answer 3273

- posted by: [jt000](https://stackexchange.com/users/4550640/jt000) on 2015-01-30
- score: -1

<p><a href="https://stripe.com/docs/tutorials/sending-transfers" rel="nofollow">Stripe Transfer API</a> has the ability to pull directly into my own account using credit card transactions, then push out to 3rd party bank accounts or debit cards. This does take 2-days to settle the initial transfer but prevents the corporation from needing to pay 2x merchant fees (instead its 2.9%+$.30 for initial cc charge, then $.25 for each transfer).</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).