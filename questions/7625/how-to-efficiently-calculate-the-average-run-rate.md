## How to efficiently calculate the Average Run Rate?

- posted by: [Dawny33](https://stackexchange.com/users/6444670/dawny33) on 2015-10-22
- tagged: `marketing`, `sales`, `growth`, `revenue`, `churn`
- score: 1

<p>Annual <a href="http://www.investopedia.com/terms/r/runrate.asp" rel="nofollow noreferrer">Run Rate</a> is a metric which would help the company to set its targets, by extrapolating current trends and results.</p>

<p>And it's calculation is also very tricky(even more if your business has seasonal effects). So, are there any standard ways/techniques which can help startups calculate ARR efficiently, keeping their trends and patterns of sales in mind?</p>

<p>And why should we calculate Annual run Rate of Recurring Revenue vs Time Period (segmented with respect to churn)?  What can be learned from this analysis?  (<a href="http://www.forentrepreneurs.com/saas-metrics-2/" rel="nofollow noreferrer">Source</a>)</p>

<p><a href="https://i.stack.imgur.com/PUsKv.png" rel="nofollow noreferrer"><img src="https://i.stack.imgur.com/PUsKv.png" alt="enter image description here"></a></p>



## Answer 7636

- posted by: [Mruf](https://stackexchange.com/users/3246202/mruf) on 2015-10-23
- score: 2

<p>As i wrote in a comment, this topic is quite complex. I only scratched the surface, but I tried to name as many things as possible, without getting to far away from the answer.</p>

<p>The first thing is, if it is even necessary to do this calculations as a startup. So first question should be "When should I do advanced calculations?". The answer is as short as simple: Do it, when you want/need to sell your company. If not, try to find some key figures for measurement. (That still could be over management, but in terms of growth it could be very interesting)</p>

<p>Let's assume, we want to create a model for StartUps. (This will not be complete, but it should be way more accurate). </p>

<p>First thing is: Run Rate has high error acceptance. That's why it is accepted to  to have a linear growth, without limits and all those quite overestimating predictions. <a href="http://seanonstartups.co/2014/07/10/the-run-rate-trap/" rel="nofollow noreferrer">Take a look here</a>.</p>

<p>Now lets try to develop some figures, so we will be more accurate. First thing to mention is, that those high run rate startups estimate their turn over, the customer amounts etc. Of course most estimations are based on numbers, but there is an uncertainty variable coming with it. (<a href="http://www.startuplessonslearned.com/2010/06/what-is-startup.html" rel="nofollow noreferrer">Take a look here</a>) Only a very small minority will reach half of their predictions. And the amount meeting their predictions... well lets just say, there is a reason to call them unicorns.</p>

<p>Lets get going:</p>

<p>The normal run rate is very simple to calculate. Take your actual revenue or earnings and multiply them by the time period (earnings in January = 10000,; Prediction over 12 month) : RunRate = 10.000€ * 12 = 120.000€</p>

<p>Now lets take the growth rate in account, here lets say we have a percentage growth of 10% per year: </p>

<p><a href="https://i.stack.imgur.com/Q5hrh.png" rel="nofollow noreferrer"><img src="https://i.stack.imgur.com/Q5hrh.png" alt="enter image description here"></a></p>

<p>Remember that this run rate will be even higher, as the run rate w/o growth</p>

<p>For functional notations of the seasonal part, my math is not good enough, but it is simple excel work. I created a sample document. </p>

<p>Here we guess the amount of customers and their changing rates, especially the mostly ignored chrun rate (+ some other variables). You also can set relative changes depending on seasons. <a href="https://docs.google.com/spreadsheets/d/1W8AdCzZj_r2Sl6NPRx04fs5kq4QkV7l3kGYimxYIaBg/edit?usp=sharing" rel="nofollow noreferrer">Take a look here</a></p>

<p>Implications:</p>

<ul>
<li>Season can have an impact, but needs to be quite strong</li>
<li>Run Rate is no tool for estimations or predictions. It's a metric to compare and evaluate</li>
<li>In startups with growth potential, growth should be considered.</li>
<li>To get an more realistic insight, also include the chrun rate</li>
</ul>

<p>What does the graph display? </p>

<ul>
<li>Green Line: Every time period you earn some money. If nothing changes over X time periods you will have earned X times that value. (... and by that ignoring so may things)</li>
<li>Blue Line: Wait... that can't be accurate! Think about it: You spent 1000$ to attract 20 Customers per time period, but if you spent 2000$ you may get 31 (it is NOT doubled). But you will also loose 15% of your customers per time period. That means for the first time period: If you have 100 Customers you will loose 15%, but with your marketing you will get 20 new ones. => Growth of 5 Yay!
For the second time period: you will again get 20 new ones, but you will lose 16. => Growth of 4 Meh!. So your growth is not linear, it decreases over time!</li>
<li>Red Line: It tells you that there is a border, you can't exceed. I theory, you can, but in reality your marketing costs would explode. So the red line, represents a limit!</li>
</ul>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
