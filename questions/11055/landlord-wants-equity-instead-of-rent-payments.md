## Landlord Wants Equity Instead of Rent Payments

- posted by: [user899893](https://stackexchange.com/users/484305/user899893) on 2016-09-02
- tagged: `valuation`
- score: 2

<p>I am trying to start a store and the property owner wants equity in the store instead of rent payments. He doesn't want to invest anything else.</p>

<p>How should I quantify his share?</p>

<p>I am expecting to invest $200,000 up front and I will operate at a loss for 3 years. The rent for this property is around $2,000. The <a href="http://www.investopedia.com/terms/i/irr.asp" rel="nofollow">internal rate of return</a> for this project is 22% over a period of 10 years. The rent is expected to increase by 15% every 3 years. </p>

<p>Can someone suggest an ideal way to calculate the owner's equity?</p>



## Answer 11084

- posted by: [Community](https://stackexchange.com/users/-1/community) on 2016-09-06
- score: 5

<p><strong>What a crazy idea.</strong></p>

<p>I don't know what country you're in, but in the United States it costs money to own property. You have to pay property taxes and possibly any number of other taxes like trash collection, water, and sewer. On top of that, you need to pay electricity and gas. If the owner takes your equity, he'd have to pay these fees every month on behalf of your business (because otherwise, rent would "buy-out" these obligations).</p>

<p>The owner is essentially making an investment of rent in your business every month or year (whenever rent is due). Since your internal rate of return is 22%, that's a reasonable amount he might expect to get make annualized, on average, over the 10 year period.</p>

<p><strong>Assuming the Rent is Paid Yearly</strong></p>

<p>Rent is $2,000 for the first three years, $2,300 for the next three years, $2,645 for the three years after that, and $3,041.75 for the final year. That would represent the 15% increase every three years. Discounting the rental payment for each year we'd get the following present values:</p>

<p><code>
Start of Lease: $2,000 today is           $2000.00
After 1 year:   $2,000 discounted 22% is   1639.34
After 2 years:  $2,000 discounted 22% is   1343.72
After 3 years:  $2,300 discounted 22% is   1266.63
After 4 years:  $2,300 discounted 22% is   1038.22
After 5 years:  $2,300 discounted 22% is    851.00
After 6 years:  $2,645 discounted 22% is    802.17
After 7 years:  $2,645 discounted 22% is    657.52
After 8 years:  $2,645 discounted 22% is    538.95
After 9 years:  $3,041.75 discounted 22% is 508.02
                                         ---------
                                        $10,645.57
</code></p>

<p>So in this scenario, the value value of the landlord's equity is $10,645.57.</p>

<p><strong>Assuming the Rent is Paid Monthly</strong></p>

<p>If you want to do this monthly, you'll want to calculate the start-of-period value of all the payments in each yearly period and then discount that to today. Since we have 4 possible rents, we can calculate a time-zero value for each:</p>

<p><code>
One year of monthly $2,000 payments is worth $21,368.80
One year of monthly $2,300 payments is worth $24,574.13
One year of monthly $2,645 payments is worth $28,260.24
One year of monthly $3,041.75 payments is worth $32.499.28
</code></p>

<p>Knowing this, we can discount each year's value to the present value:</p>

<p><code>
Start of Lease: $21,368.80 today is          $21,368.80
After 1 year:   $21,368.80 discounted 22% is  17,515.41
After 2 years:  $21,368.80 discounted 22% is  14,356.89
After 3 years:  $24,574.13 discounted 22% is  13,533.14
After 4 years:  $24,574.13 discounted 22% is  11,092.74
After 5 years:  $24,574.13 discounted 22% is   9,092.41
After 6 years:  $28,260.20 discounted 22% is   8,570.70
After 7 years:  $28,260.20 discounted 22% is   7,025.16
After 8 years:  $28,260.20 discounted 22% is   5,758.33
After 9 years:  $32,499.28 discounted 22% is   5,427.94
                                            -----------
                                            $113,741.52
</code></p>

<p>And so the value of the landlord's investment is $113,741.52.</p>

<p><strong>How Much Equity Should the Landlord Get?</strong></p>

<p>Now that we've gotten the finance out of the the way, let's talk about how much the landlord should actually get. There won't be a <em>right answer</em> to this question. But finance isn't always designed to find you a <em>right answer</em>, it's more designed to make sure you don't overpay. Your objective should be to give as little as possible to the landlord. It is you, after all, who is bringing him a 22% yearly return and that has tremendous value.</p>

<p><em>Method 1: Comparing Present Values</em></p>

<p>Once way to determine how much the landlord should get is to compare the present values of your investments. You are putting in $200,000 while he is putting in $113,741.52. Based on these investments alone, he'd get 56.87% of the equity. Of course that may not be reasonable to you, but at least you have a benchmark.</p>

<p><em>Method 2: Comparing Theoretical Present Values</em></p>

<p>If we take the value of your $200,000 after 10 years of 22% returns, we can calculate the company is worth $1,460,926.28 in future dollars. Discounting this at a 2% inflation rate we have a present value of $1,198,468.39. Comparing the landlord's investment to this theoretical present value of your company, you'd get get a fair equity for your landlord of 9.49% ($113,741.52/$1,198,468.39). This again is another benchmark you can use. Combining <em>Method 1</em> and <em>Method 2</em>, you have a range.</p>

<p><em>What I Would Do</em></p>

<p>If this were my business, <strong>I don't think I'd let a passive landlord leach on my 22% IRR</strong>. It's simply not fair. What I would do is determine the typical rate of return a landlord might expect in the area and recalculate the present values of his investments based on that (lower) interest rate. Then I would use that to determine the current value of his investment and use it to determine a maximum amount of equity I would allow him to have in negotiations.</p>

<p><em>Other Methods</em></p>

<p>You can literally find infinite ways to value the equity of your landlord's offer taking into account infinite variables. You might consider his offer more valuable during the first three years when you are operating at a loss, and less valuable after year 3 when you have income funding working capital. You can rework my calculations above using different rates of return or copy them up using multiple rates of return <strong><em>The thing about financial analysis is, once we get past the basics (the first part of this answer), you need to start plugging in variables with your best guesses.</em></strong></p>

<p><strong>Other Considerations</strong></p>

<p>You'll want to get a 10 year lease that explicitly details your arrangement. 10 years is a long time and either you or your landlord might be tempted to break the agreement unless it is firmly defined.</p>

<p>This is all pro-forma. Nothing is certain and things will change. Sometimes they change for the better, sometimes they change for the worse. Giving your landlord too much equity might hamper your ability to raise/retain capital if your business slows. On the other hand, this arrangement can also provide your business a lot of security and a form of financing to start you might otherwise have to raise elsewhere.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
