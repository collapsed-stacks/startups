## How to find the correct price and discount, based on customer's purchase

- posted by: [Saeed Neamati](https://stackexchange.com/users/429080/saeed-neamati) on 2015-07-15
- tagged: `product`, `pricing`
- score: 5

<p>A little while ago I asked this question on SuperUser:</p>

<p><a href="https://superuser.com/questions/940355/how-to-create-a-data-series-for-exponential-decrease-diagram">https://superuser.com/questions/940355/how-to-create-a-data-series-for-exponential-decrease-diagram</a></p>

<p>I wanted to find a formula for pricing my products, so that I could price them fairly such that purchasing more would result in more discount.</p>

<p>The pricing goal was to achieve this:</p>

<pre><code>If you purchase 50 pieces, you should pay 2500 (units) per piece.
.
.
.
.
If you purchase 10000 pieces, you should pay 300 (units) per piece.
</code></pre>

<p>The minimum salable count is 50, and there is no more discount for purchases over 10,000 pieces. I wanted to find the discount in between. But I didn't want it to be <strong>linear</strong>. To get linear filling, I could use Excel's linear extrapolation techniques.</p>

<p>However, what I wanted was to have a logarithmic (exponential) discount curve, <strong>to highly encourage customers, to purchase more</strong>. That is, by doubling the order, they would receive a huge discount in lower quantities.</p>

<p>However, based on the answers, I found out that the resulting chart would be something like this:</p>

<p><img src="https://i.stack.imgur.com/bOdtv.png" alt="enter image description here"></p>

<p>Which is absolutely wrong. Because it financially means that "if you buy 4000 units you should pay more than when you buy 8000 units". Of course it doesn't make sense. Now I'm trying to find the data series that can create an increasing amount of payment. But I can't figure it out, and my mathematical knowledge is not helpful here.</p>

<p>So, if you have <strong>minimum_salable_pieces_count</strong> sold at price <strong>x</strong>, and <strong>discount_limit_pieces_count</strong> sold at price <strong>y</strong>, and you want to have an <strong>exponential discount model</strong>, how would you find the intermediate prices for each amount of purchase? </p>



## Answer 5735

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-07-15
- score: 3

<p>Your premise is probably incorrect: you shouldn't be deciding what your volume discount price is from the onset. Nobody buys 10k units of something on an e-commerce store. You'll get an email and/or a phone call when someone wants to buy that many.</p>

<p>Start with your costs. As you do, don't underestimate the logistics and the administrative sides of things because they add up. Then compute your total cost to <em>ship</em> -- including the time you spend on closing the deal, invoicing, etc. Add two healthy margins on top. One is a margin of error plus a minimum sales margin. It yields a price under which you do not want to go under. The other is your desired sales margin. The total is your price.</p>

<p>Also, keep in mind that costs do not decrease linearly. Because labor and equipment don't scale. You can only do so much with a unit of human labor or output so much with a piece of equipment. Once you hit those limits, you need to hire and/or invest in new equipment. Upon making that hire or investment you you'll also need the volume to occupy that productive capacity down the road.</p>

<p>Come time for negotiations, keep each of your total costs, your minimum margin, and your productive capacity in mind. They yield a price and shipping delays underneath which you're simply not interested in selling -- no matter how hard the opposite party is haggling. And make it clear that this is <em>for this order only</em> -- if the client comes back later and asks for half the number of units, your price should be higher.</p>

<p>Lastly, recognize that an order can sometimes be too big for your business. It's rarely good when a client represents a third of your orders or more -- if that client goes off, you're screwed.</p>

<p>If you insist on some kind of formula, your final price is going to look like:</p>

<pre><code>min_total_price = total_cost + safety_margin
total_price = min_total_price + sales_margin

min_unit_price = min_total_price / units
unit_price = total_price / units
</code></pre>

<p>There's no exponential curve or what have you because that won't match your cost structure.</p>



## Answer 5772

- posted by: [Steve](https://stackexchange.com/users/6570044/steve) on 2015-07-20
- score: 2

<p>An out of box question might require an out of box solution
with zero (or very limited) mathematical skills myself this is my approach.
with zero consideration to the business implementations (as I believe you know what you are looking for) </p>

<ol>
<li>grab yourself photoshop / gimp or other reasonable imaging program</li>
<li>create a 1 by 1 pixel ratio template 2500pixels high by 10000 pixels wide. (min 300dpi)</li>
<li>set location bottom left corner as plot 0,0 (x,y) using a ruler tool</li>
<li>use a vertical guideline at x axis 50 (this is your min 50 count)</li>
<li>use a vertical guideline at y axis 300 (this is your min sale price per unit)</li>
</ol>

<p>now using an arc or eclipse tool draw a curve you like.
play around a bit until you get the effect you are looking for. </p>

<p>once you have the curve you like - you now need the formula for that specific curve. </p>

<p>export or save your graph at full 300dpi 1x1 pixel ratio. 
and head over to a maths forum post your graph image and ask if somebody could produce the formula for the specific curve. </p>

<p><img src="https://i.stack.imgur.com/hVIXH.png" alt="sample curve - not recommended to use this"></p>

<p>on a business level you could then play around with the incremental discount volume amounts eg, this curve doesn't produce a significant discount between the sale volumes of 9500 and 10000 but might between 7500 and 10000 so you might consider min bulk sales,   </p>

<p>there may be flaws in this method of price modelling as some are mentioned above , even "scalable" digital duplication has its costs proportional to volume -  however I'm assuming the OP is asking advice on a math solution, an not so much a business price modelling solution </p>



## Answer 6166

- posted by: [JCA](https://stackexchange.com/users/6822638/jca) on 2015-08-26
- score: 1

<p>Every year we review our costing and submit - if needed - a request for cost increase to our customer (largest retailer in the US). During this review process we also take a look at retails (the price you as a consumer pay for the product we sell to largest retailer in the US) and how margins are affected by our cost increase. If margins decrease and are not within the reasonable standard for the retailer then we adjust retails. This adjustment in retails and its impact is important to understand.</p>

<p><strong>Price Elasticity</strong></p>

<p>In very simple terms, it is the assumption that as X price goes up for a product, Y unit sales must go down, this is the same for the inverse which assumes that when X price for a product goes down, Y unit sales must go up. These are assumptions, and by conducting a price elasticity analysis you'll be able to determine if they are correct for <strong>your product</strong> or if they are not.</p>

<p>Some products experience no effect when X is either increase or decreased, others vary greatly.</p>

<p>Below is a very good read provided by HBR (Harvard Business Review) which should simplify the calculation and explanation:</p>

<ul>
<li><a href="https://hbr.org/2015/08/a-refresher-on-price-elasticity" rel="nofollow">A Refresher on Price Elasticity</a></li>
</ul>



## Answer 6171

- posted by: [Paparazzi](https://stackexchange.com/users/300272/paparazzi) on 2015-08-26
- score: 0

<p>The math would be better on <a href="https://math.stackexchange.com/">https://math.stackexchange.com/</a>   </p>

<p>I did the math and even with a log based price for faster discount early if you apply that price to ALL then there will always be a quantity at which the total starts to decrease.  The price to ALL part takes over.</p>

<p>You need to use incremental pricing<br>
the first 1000 are X<br>
the second 1000 are Y<br>
so 1500 = 1000X + 500Y</p>

<p>Q is quantity<br>
b is base quantity<br>
s is slope (in this case s is negative)<br>
i price at base<br>
total = Q ((log(Q) - log(b))s  + i)<br>
if you take the derivative of total there will be a Q at which the derivative is zero (the total stops going up) if s is negative  </p>

<p>But take this to math SE for validation as it as been a while since did derivatives</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
