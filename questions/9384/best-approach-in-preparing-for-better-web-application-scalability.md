## Best approach in preparing for better web application scalability

- posted by: [picolo](https://stackexchange.com/users/5330039/picolo) on 2016-06-01
- tagged: `prototyping`
- score: 6

<p>In order to have the least amount of issue with scaling a startup in response to a projected growth of user base, is it better to :</p>

<p>1- create a simple prototype of the idea which can serve only 10s of users, with the hopes that its development is done faster and it will be easier to present to investors/new employees</p>

<p>or </p>

<p>2- Develop something more solid and stable which can serve 1000s of users, but will take more time. Yet once completed it allows for better presentation to the investors/new employees. </p>

<p>What are the factors in making a choice from the two options when there is zero or very limited amount of funds. </p>



## Answer 9390

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2016-06-02
- score: 5

<p>In my view the answer is in the question:</p>

<blockquote>
  <p>but will take more time [...]</p>
  
  <p>there is zero or very limited amount of funds</p>
</blockquote>

<p>Further, I think you're over-thinking this for at least two reasons:</p>

<ol>
<li>Unless what you're up to is extremely resource intensive, only the most inept devs could ever deliver anything that "can serve only 10s of users". That was already true in the mid-90s, and the super-computers of the time were less powerful than a modern-day smartphone.</li>
<li>If you use a proper framework instead of re-inventing the wheel, you'll be building on top of scalable solutions <em>anyway</em>. If you're using PHP, use Symfony or some other battle-tested framework; if you're using Ruby, use Rails; etc.</li>
</ol>

<p>Twitter was prototyped as a Rails app. Groupon was prototyped using WordPress... Yes, both had scaling issues down the road but let's get real: neither broke at 10s of users.</p>

<p>As such, go with as simple a proof of concept as you can get away with, without over-engineering anything. If you ever catch yourself thinking "this will take 2 days but will be better for the future" you're likely over-thinking the problem and should move forward with the 2 minute solution.</p>



## Answer 9389

- posted by: [D J Sims](https://stackexchange.com/users/7242000/d-j-sims) on 2016-06-02
- score: 1

<p>Always prepare for large scale from the start, using various ops frameworks, docker, spark, etc.</p>

<p>If you don't do that you will have these problems:</p>

<ol>
<li><p>Your system will require a bunch of undocumented manual steps dependent on key people being available. If you have some sort of auto deploy for large scale use then this won't be a problem.</p></li>
<li><p>You will probably underestimate the capacity that you need during peak periods.</p></li>
<li><p>You can make huge changes to your system and demand lots of money from VCs in the future for things that you already know are easy decoupled configuration settings.</p></li>
<li><p>It will be easier to explain your system to other people because it will be a series of decoupled scalable modules rather than obscure hacks. </p></li>
<li><p>It will save time in the long run because the work that goes into scaling saves you from many bugs that you would hit in production.</p></li>
</ol>

<p>So #2 definitely. </p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
