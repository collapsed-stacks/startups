## Can anyone provide a good algorithm that details how to plan for cloud server cost estimation?

- posted by: [user2997154](https://stackexchange.com/users/3591112/user2997154) on 2015-11-04
- tagged: `tech-company`, `business-plan`, `startup-costs`, `servers`
- score: 1

<p>Server cost estimation is one of those things that almost any tech startup(that offer <em>some</em> web service) has to deal with. Yet, There really doesn't seem to be any good, <strong>easy to understand</strong> guides out there to plan for server costs. Of course, a "fit all" algorithm to finding the costs is no easy task because of all the possible variables that can affect the estimation(what does you app do, which cloud platform do you chose, etc).</p>

<p>With that said, does anyone has a go to guide?</p>

<p>So far, I could at least think of the following steps(but each steps would require a paragraph in itself):</p>

<ol>
<li>Figure out what does your database store for each user and quantify it in   storage units(Mbs)</li>
<li>Figure out how much data a user download per day in Mbs</li>
<li>Figure out how much data a user upload per day in Mbs</li>
<li>Estimate how many hours per week your server will run a maximum traffic</li>
<li>Estimate your maximum traffic</li>
<li>Chose a cloud platform(probably needs steps to chose one...)</li>
<li>Based on your platform choice, estimate the price per month per quantum of users(I say quantum because I assume the price doesn't vary in a linear fashion with the number of users).</li>
</ol>

<p>Note: This is not a duplicate of this <a href="https://startups.stackexchange.com/questions/1491/how-to-estimate-costs-for-servers-for-web-application">question</a> as I'm asking for specific steps(though the answer might give us some indications).</p>



## Answer 7734

- posted by: [Jaap Jansma](https://stackexchange.com/users/4767822/jaap-jansma) on 2015-11-05
- score: 1

<p>I don't think there is a general algorithm for costs of hosting. It depends on what you want, your SLA with the hosting provider, your requirements. Etc.. </p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
