## Limits on Total Client Acquisition, Myth or Real?

- posted by: [Joseph Astrahan](https://stackexchange.com/users/1759123/joseph-astrahan) on 2017-06-17
- tagged: `startup-costs`, `customer-development`, `difficult-client`
- score: 0

<p>So I was working on a financial projection tool and stumbled upon a bit of an issue.  I was simulating the percentage chance of getting customers and <strong>the chance of losing them.</strong></p>

<p>Lets say I can predict with great accuracy <strong>I can get 10 customers every month.</strong></p>

<p>If I say at any given time <strong>I will lose 3% of the clients per month on average.</strong>  Then the math concludes that at some point I will lose as many clients as I gain and effectively the <strong>company will stop growing.</strong></p>

<p>For example, lets say I've got 450 clients, 3% of 450 is 13.5.  This number is greater than the 10 customers I could gain every month.  Essentially the company would lose clients down to probably 350 to 400 and stabilize around there never growing anymore.</p>

<p><strong>Is this accurate to think this way in terms of losing a client?</strong> Is it safe to say that given these metrics the company can never grow past 350 to 400~ clients?</p>

<p><strong>If yes, then is the only solution to escape that customer lock to get more then 10 customers every month, correct?</strong></p>

<p>The reason I am asking this question is I feel like maybe I'm missing something here in terms of projecting client loss every month and the chance of it occurring.</p>



## Answer 12869

- posted by: [Neil Slater](https://stackexchange.com/users/2274369/neil-slater) on 2017-06-17
- score: 1

<blockquote>
  <p>Lets say I can predict with great accuracy I can get 10 customers every month.</p>
</blockquote>

<p>This value and form of growth is a major assumption in the model. You then build the rest of your analysis comparing a perpetual linear growth versus perpetual exponential decay. </p>

<p>However, your analysis once you have made that decision is mathematically sound - i.e. given your model and the numbers you input, the projected customer numbers would stabilise at around 323. If you start with 450 customers, it would take around 6 years to drop down to 340 customers at those rates.</p>

<blockquote>
  <p>Is this accurate to think this way in terms of losing a client?</p>
</blockquote>

<p>A linear customer acquisition model may not apply on a longer time scale, it depends on the nature of your business.</p>

<p>A percentage churn rate (exponential decay) is a reasonable assumption in terms of statistics. It is based roughly on assuming that there are a bunch of random factors that each customer deals with independently, that would lead them to churn.  </p>

<blockquote>
  <p>The reason I am asking this question is I feel like maybe I'm missing something here in terms of projecting client loss every month and the chance of it occurring.</p>
</blockquote>

<p>You are projecting a simplified monthly growth and churn model several years into the future. Real world situations are often more dynamic than that, and will depend on many different details - some of which you may have control over, and be able to influence in the company's favour. What the model does is clear away all those details, assuming that they are essentially random things that you cannot control.</p>

<p>In reality, there is often a complex story behind each customer acquired and each customer that churns. Gaining insights into the reasons and limitations for each event, and then targeting things that appear regularly, can help you beat those numbers by adjusting the approaches that company takes to acquire and retain customers.</p>

<blockquote>
  <p>If yes, then is the only solution to escape that customer lock to get more then 10 customers every month, correct?</p>
</blockquote>

<p>Yes, although for any fixed customers-per-month value and fixed churn rate you will just get a different steady-state point in the model. You could also try to reduce the 3% churn rate (e.g. reducing it to 2% per month would have a similar model tend towards a steady state of 490 customers). Which is easiest to address depends entirely on details of your business.</p>

<p>One thing to bear in mind is that acquisition rate and churn rate can be linked. For example it is possible to improve your acquisition rate through advertising, but a change to the advertising demographic may attract new customers with an inherently different churn rate.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).