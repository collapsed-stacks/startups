## Should the pricing plan be selected before or after the free trial?

- posted by: [porton](https://stackexchange.com/users/457033/porton) on 2017-02-28
- tagged: `service`, `internet`, `online-store`
- score: 0

<p>We are going to sell a service with several pricing plans. A pricing plan limits the max number of users.</p>

<p>We are going to give one month trial period.</p>

<p>What is the widespread practice in this situation: to select the pricing plan on signup and start of a trial period or on end of the trial period?</p>

<p>What are advantages and disadvantages these two variants?</p>

<p>One advantage of selecting a pricing plan is that the max number of users is known in advance, what eliminates the need for the special case of trial period to allow unlimited number of users, what would require a special case of our code checking the number of users.</p>



## Answer 12226

- posted by: [DonQuiKong](https://stackexchange.com/users/9739821/donquikong) on 2017-03-01
- score: 2

<p>My suggestion would be to let the customer have unlimited users, but if they switch from one to another pricing plan (during the trial) tell them that they would now be in a higher pricing plan. </p>

<p>Have that plan as default for when the user wants to select a pricing plan. </p>

<p>Pros:</p>

<ul>
<li><p>Bootstrapping users into higher pricing plans by letting them have those features and later miss them is easier than getting them to pay for more if they could live with less before.</p></li>
<li><p>How would you procede if someone selects the highest pricing plan for the trial period and then wants a lower one? Letting users elect upfront is abusable.</p></li>
<li><p>Users can actually try all features, if you let them try only one pricing plan, the ones that would pay for more might not like it.</p></li>
</ul>

<p>Cons:</p>

<p>Maybe higher internal costs for providing more content/downstream etc. </p>



## Answer 12230

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2017-03-02
- score: 2

<p>The best practice is to give the <em>full</em> product, in its entirety, during the trial period. This way, a prospect gets to see what they will <em>lose</em> by sticking to the lower plan they intended to get - irrespective of what they initially thought they'd need.</p>

<p>The reason essentially is the same as why you want to list the priciest options first in a pricing table: you want users to be cognizant about what they'll miss out on because the fear of losing something you acknowledge as useful (which you have by the time you thought "oh this is/sounds cool!") is a much stronger motivator than the prospect of gaining something extra that you don't necessarily understand how it's useful ("meh, I can live without").</p>

<p>Ergo, throw in the plan picker <em>after</em> the trial. If you can - it's not always possible / sensible to do so.</p>

<p>That said, mind clients who just want to buy it: in your order form, allow to directly pick a plan, and offer the full trial features to everyone. Else you'll lose on the first month because everyone will get it for free. You'll likely find users who actually upgrade after their first month of payment, too.</p>



## Answer 12232

- posted by: [Jithin U. Ahmed](https://stackexchange.com/users/3244972/jithin-u-ahmed) on 2017-03-02
- score: 0

<p>In this scenario, what I think the best is.</p>

<p>Give the client <strong>full product for trial</strong>.</p>

<p>Let him use all the features in the product and finally let him list down the <strong>requered modules/features</strong>.</p>

<p>On that selected modules/features, you may <strong>fix a price</strong> or <strong>select the best</strong> matching price from the price list comparable to the <strong>selected feature</strong>.</p>

<p>So, you can tell your client that, <strong>pricing will be based on your requirements only</strong>. By this method, you will be <strong>safe to deliver at the right price</strong> and this will also make the client happy for <strong>just need to pay for the right requirements only</strong>.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
