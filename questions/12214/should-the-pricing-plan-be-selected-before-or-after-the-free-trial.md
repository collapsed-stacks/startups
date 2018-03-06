## Should the pricing plan be selected before or after the free trial?

- posted by: [porton](https://stackexchange.com/users/457033/porton) on 2017-02-28
- tagged: `service`, `internet`, `online-store`
- score: 0

We are going to sell a service with several pricing plans. A pricing plan limits the max number of users.

We are going to give one month trial period.

What is the widespread practice in this situation: to select the pricing plan on signup and start of a trial period or on end of the trial period?

What are advantages and disadvantages these two variants?

One advantage of selecting a pricing plan is that the max number of users is known in advance, what eliminates the need for the special case of trial period to allow unlimited number of users, what would require a special case of our code checking the number of users.


## Answer 12226

- posted by: [DonQuiKong](https://stackexchange.com/users/9739821/donquikong) on 2017-03-01
- score: 2

My suggestion would be to let the customer have unlimited users, but if they switch from one to another pricing plan (during the trial) tell them that they would now be in a higher pricing plan. 

Have that plan as default for when the user wants to select a pricing plan. 

Pros:

- Bootstrapping users into higher pricing plans by letting them have those features and later miss them is easier than getting them to pay for more if they could live with less before.

- How would you procede if someone selects the highest pricing plan for the trial period and then wants a lower one? Letting users elect upfront is abusable.

- Users can actually try all features, if you let them try only one pricing plan, the ones that would pay for more might not like it.

Cons:

Maybe higher internal costs for providing more content/downstream etc. 


## Answer 12230

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2017-03-02
- score: 2

The best practice is to give the _full_ product, in its entirety, during the trial period. This way, a prospect gets to see what they will _lose_ by sticking to the lower plan they intended to get - irrespective of what they initially thought they'd need.

The reason essentially is the same as why you want to list the priciest options first in a pricing table: you want users to be cognizant about what they'll miss out on because the fear of losing something you acknowledge as useful (which you have by the time you thought "oh this is/sounds cool!") is a much stronger motivator than the prospect of gaining something extra that you don't necessarily understand how it's useful ("meh, I can live without").

Ergo, throw in the plan picker _after_ the trial. If you can - it's not always possible / sensible to do so.

That said, mind clients who just want to buy it: in your order form, allow to directly pick a plan, and offer the full trial features to everyone. Else you'll lose on the first month because everyone will get it for free. You'll likely find users who actually upgrade after their first month of payment, too.


## Answer 12232

- posted by: [Jithin U. Ahmed](https://stackexchange.com/users/3244972/jithin-u-ahmed) on 2017-03-02
- score: 0

In this scenario, what I think the best is.

Give the client **full product for trial**.

Let him use all the features in the product and finally let him list down the **requered modules/features**.

On that selected modules/features, you may **fix a price** or **select the best** matching price from the price list comparable to the **selected feature**.

So, you can tell your client that, **pricing will be based on your requirements only**. By this method, you will be **safe to deliver at the right price** and this will also make the client happy for **just need to pay for the right requirements only**.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
