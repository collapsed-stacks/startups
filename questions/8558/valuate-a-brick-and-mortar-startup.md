## Valuate a brick and mortar startup

- posted by: [Cleber Goncalves](https://stackexchange.com/users/50800/cleber-goncalves) on 2016-02-18
- tagged: `equity`, `investors`, `valuation`
- score: 3

<p>I founded a brick and mortar company funded with my own cash and bank loans guaranteed with personal possessions.</p>

<p>The total invested in equipment, raw materials, location and work capital for a year will be around 200,000.</p>

<p>I would like to bring in investors and offer equity as incentive for key employees to join.</p>

<p>What is the fair way to valuate the company? Taking just the 200K as the 'company value' ignores the risk I'm taking and the time and effort I put on getting the company started.</p>

<p>Valuating it on future revenue expectations is the standard for software startups, however it appears to be a big guess since there is no way to accurately predict how much of the market my company will capture. </p>

<p>To illustrate, the company currently has 10,000 shares available, valuating it based solely on the cash invested so far would make those worth 20 each.</p>

<p>If however we forecast the company to have 2 million in revenue after 5 years those shares could theoretically be valuated at 200 each.</p>

<p>Is this how those valuations are done? </p>



## Answer 8592

- posted by: [Escher](https://stackexchange.com/users/4623443/escher) on 2016-02-23
- score: 3

<p><strong>Your shares for $2M revenue in 5 years are not worth $200 each now.</strong> Here's an explanation why - I'm simplifying some concepts - it's not <em>exactly</em> like they teach in business school. </p>

<p><strong><em>The general principle of valuation is that an asset is worth the discounted free cash flow it generates.</em></strong> Let's consider this phrase:</p>

<p><em>"Free cash flow"</em> - this is simple enough. If a widget is going to generate a single $100 bill for you today, once only, and has no salvage value, then it's worth $100.
<em>"Discounted"</em> - this means you take into account the time value and the risk of the cash flow. How do we do that?</p>

<ul>
<li><em>Time:</em> Let's say the widget isn't going to generate that $100 bill today, but rather in one year's time, and let's also assume that your
bank pays 10% annual interest. Well, to have $100 in your account in
a year, you should deposit $100/110% = $90.91 today. So that's what the widget is worth today if it will only generate the cash in a year.</li>
<li><em>Risk:</em> What if your widget isn't 100% reliable? If it only has a 9-in-10 chance of producing the $100 bill in a year, then in expectation it is only worth 90% as much, right? So that's 90.91*90% = $81.82. But wait, ask yourself now as a buyer, is a 90% chance of $90.91 equivalent to a sure $81.82 for you? Rationally, yes, but most people are risk averse when it comes to large sums (because of the sorrow of loss). You might argue that you're only willing to pay $75 for a 90% chance of $100 in a year to compensate you for the uncertainty in the cash flow your counterparty is proposing.</li>
</ul>

<p>So, for this example, your discount rate is  100/75 - 100% = 33%, representing the time delay between when the buyer pays for the widget and when it produces the cash, and also the risk premium associated with the uncertainty of the cash flow.</p>

<p>What if the widget will keep producing $100 bills once a year indefinitely, with 90% probability each time? Then your widget would be worth: <em>(note to nitpickers, I'm keeping the dicount rate constant, even though the probability calculation is not strictly correct since each $100 bill is IID)</em></p>

<pre><code>$100/1.33 + $100/1.33^2 + $100/1.33^3 + ...
</code></pre>

<p>Guessing the revenues is can be hard, as is agreeing on an appropriate discount rate if the business isn't very comparable. In these cases, as a proxy for this calculation, sometimes both parties just agree on a multiple of earnings as the valuation (a P/E ratio) based on other businesses of similar size or similar activity.</p>

<p>In your particular case, you have the value of loans (your liabilities) to deduct from your assets' value before arriving at your equity value. You also talk about $2M revenue in 5 years - remember that revenue != profit, and that being brick-and-mortar you have real costs to account for!</p>

<h2>Your business:</h2>

<p>You haven't provided revenue projections, yet it is a brick-and-mortar business. Brick-and-mortar is relatively predictable - your costs should be predictable based on how much revenue you're going to be making. Given that it's brick and mortar, your market size is going to be fixed for the next year or two, unless you are going to borrow more money and open more shops or build more factories. And you've been in business a year, right? So you should have a decent idea of how much profit you'll make for the next 24 months - which will already give you a large indication of the value of your business if you use the DCF method above.</p>

<p>Finally, to consider what I think is the real purpose of your question, remember that your objective in offering equity to employees is not necessarily to realise the value of the equity like in a sale, but rather to provide an incentive. An incentive has a purpose - be clear about what it is (More products per hour? More customers acquired? Less churn?) and decide if offering equity is the best way of achieving that purpose (especially if the equity will be completely illiquid for employees and they won't be able to make a good estimate of future value if they don't know the business well). You have a lot of control over your business' destiny - an employee with 0.4% share and a mid-level job has virtually none. For this reason, your valuations of that equity will differ, and you may find that cash bonuses, or a higher base salary, or autonomy, snacks, and perks would all be more effective motivators. </p>



## Answer 8590

- posted by: [Baronz](https://stackexchange.com/users/7281676/baronz) on 2016-02-23
- score: 0

<p><strong>There is no "silver bullet" for valuation.</strong></p>

<p>It's all in the negotation between the value the seller of the shares perceives, and the value the buyer applies to the shares.</p>

<p>The Business Brokerage Press has some general guidelines broken down by industry, that professionals can use to help them get a good feel for what the business might be worth:</p>

<p><a href="http://www.bizstats.com/reports/valuation-rule-thumb.php" rel="nofollow">http://www.bizstats.com/reports/valuation-rule-thumb.php</a></p>

<p>Here's a database of values for 12,000 companies that you can use as a baseline to compare to your company value:</p>

<p><a href="http://www.bvmarketdata.com/defaulttextonly.asp?f=BIZCOMPS%20-%20Main%20Street%20Business%20Private%20Transactions" rel="nofollow">http://www.bvmarketdata.com/defaulttextonly.asp?f=BIZCOMPS%20-%20Main%20Street%20Business%20Private%20Transactions</a></p>

<p>Here's a presentation about valuation with a lot of tips and resources:</p>

<p><a href="https://www.blackbaud.com/files/resources/recordings/PrivateCompanyValuation_HigherEd.pdf" rel="nofollow">https://www.blackbaud.com/files/resources/recordings/PrivateCompanyValuation_HigherEd.pdf</a></p>



## Answer 8596

- posted by: [fiprojects](https://stackexchange.com/users/5370155/fiprojects) on 2016-02-23
- score: 0

<p>Perception is everything - Take off your "sellers hat" and put on a "buyers hat" and ask yourself if the offer seems attractive, reasonable or imaginative.</p>

<p>What the business is worth to you, and what it is worth to an investor are two different things. </p>

<p>Are growth expectations are considered realistic or pie in the sky is another. </p>

<p>Why do you seek an investor? Because you want to grow the business or because you think you deserve an expensive holiday or you want to pay off your mortgage? An investor will want their money to work and grow, not just to buy a slice of what you had in the past.</p>

<p>Are there many investors who would be interested in investing in your type of business? If true, then expect the valuation be better in your favour - if the number of investors that might be interested are few and far between, it will be to your loss. Think of it like selling a house - many buyers can encourage competition, but few buyers and many sellers mean beggars cannot be choosers.</p>

<p>I would get an accountant to value the business. Expect an investor to do their own homework and their own valuation, but the one provided by your accountant will help give both of you a guide. </p>

<p>Timing is everything and it might surprise you that it works in your favour at the moment. Anyone who has cash is struggling to make it grow. Cash in a bank is worth nothing at the moment - in some countries, where they have negative interest rates, it is costing them money to keep cash in the bank. Anyone who has something reasonable should be able to raise an offer - however only you can determine if the offer is attractive enough or not.</p>

<p>When seeking investment, consider an advertisement in business magazines like the back pages of the Economist. Don't pay investors anything - you are bound to attract time wasters or scam artists or even competitors sniffing around. Make sure you get professional advice as you risk an investor laundering money (there are investors who do such and claim on innocent businesses leaving you to pay to cleanup). Do a little background on potential investors before you share your plans or your books.</p>

<p>Do not underestimate professional advice - You are going to make a change in your livelyhood - once you put pen to paper on an agreement, misunderstandings later will be at your cost!</p>

<p>Best of luck!</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).