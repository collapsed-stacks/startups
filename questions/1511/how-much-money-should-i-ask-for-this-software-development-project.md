## How much money should I ask for this software development project?

- posted by: [Dživo Jelić](https://stackexchange.com/users/1825074/d-ivo-jeli) on 2014-11-27
- tagged: `tech-company`, `mobile-apps`, `pricing`, `quotations`
- score: 5

<p>We are having a meeting tomorrow and I have to come up with a price for this project.
What they want is:</p>

<ul>
<li>Database with around 20 tables</li>
<li>Web management system and Web API</li>
<li>iOS app</li>
<li>Android app</li>
<li>Windows Phone app</li>
</ul>

<p>I have no clue how much should I ask. </p>



## Answer 1513

- posted by: [DP_](https://stackexchange.com/users/171799/dp) on 2014-11-27
- score: 14

<p>A rough estimate can be created in the following way:</p>

<ol>
<li>For each piece of sofware, write down use cases or user stories.</li>
<li>For each user story, sketch the user interface using Evolus Pencil or comparable tool.</li>
<li>After doing the first 2 steps, create a spreadsheet with following fields: Task number, Task type (e. g. "Create database table", "Create UI X", "Create algorihm Y"), Complexity (easy, medium, hard).</li>
<li>Go through every database table and every use case, and fill in the tasks associated with it into the spreadsheet.</li>
<li>You'll end up with a huge list of tasks categorized by complexity.</li>
<li>Guesstimate the average number of days per easy, medium and hard task (3-9 guesstimates, 9, if you provide ranges - minimum, average, maximum - for every complexity type).</li>
<li>Multiply your guesstimates by the number of tasks of that type.</li>
<li>Add 30 % to the sum for unexpected efforts.</li>
</ol>

<p>In the end you will have 3 numbers - minimum, average and maximum amount of time for implementing that system. It's not precise, but provides a starting point for a discussion (e. g. what features are more important to customer).</p>



## Answer 1514

- posted by: [Henry Taylor](https://stackexchange.com/users/1734959/henry-taylor) on 2014-11-27
- score: 4

<p>At tomorrow's meeting, show Dmitri's excellent answer to your potential employer and discuss the process by which you will come up with his estimate.  If you have all the technical skills needed for this project, then congratulations on your technical diversity; competence across four platforms is rare. If you don't already have experience writing web/webapi, iOs, Android and WP apps, then admit that you may need to hire out parts of this project; factor in your having to pay full retail for other programmers time.  If your depending on using phone-gap or xamarin to handle the cross platform stuff, then change the question a little bit... have you already successfully used the intended tool to write apps like in all three phone platforms, or are you just relying on their advertised ease of use and power.  New tools are ALWAYS more time consuming (and therefore more expensive) to use than tools that you are familiar with.
So you have a lot of work to perform, just to figure out a dollar value for the main project; more work, in my estimation, than you can do by tomorrow.  So instead of going to tomorrow's meeting with a firm dollar amount to which you are willing to be chained, why not go with a question...</p>

<p>Who is paying for the time it takes to calculate this estimate?</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
