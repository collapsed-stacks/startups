## Recurring vs. one-time payment

- posted by: [NielsH](https://stackexchange.com/users/294373/nielsh) on 2016-07-15
- tagged: `payment`, `pricing`
- score: 5

<p>We are a startup running an online learning platform in the healthcare space and currently have a subscription-based business model offering 3 types of subscription lengths: 1, 6 and 12 months - all offering the same feature set.</p>

<p>Our typical customers are students that prepare for an exam using our product. After they have passed the exam, they rarely use our product.</p>

<p>We are currently internally discussing and evaluating the option to offer one-off instead of recurring payments for the following reasons:</p>

<ul>
<li>for a younger audience a one-off payment is more appealing (higher conversion rates)</li>
<li>nature of the product is a "one-off solution to pass the exam"</li>
<li>simpler payment flow (easier to communicate)</li>
<li>more variety in payment methods we can offer (there is a bunch that doesn't handle recurring payments)</li>
<li>easier to integrate "add-ons"</li>
</ul>

<p>Normally the main downside of a one-off payment is that the customer has to pay more up front. We try to avoid this by splitting up our content in content packages.</p>

<p>My questions are:</p>

<ul>
<li>Are there any case studies / real world examples on subscription vs. one-time payment for a similar audience / product setup?</li>
<li>Are there any tools or methodologies are there to estimate, design tests for and ultimately decide on the right price points? (we're comfortable and willing to run A/B tests, surveys or doing email campaigns with some offers to test hypotheses)</li>
<li>We have purchase data (and analytics) from the last 3 years or so, and can analyze things like lifetime value, retention / churn etc. What metrics should we look at in particular for making a more informed decision about any price changes? (we're a bit lost in all the data)</li>
</ul>

<p>Thanks in advance for all your help. Also happy to provide more details if required.</p>



## Answer 9740

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2016-07-20
- score: 3

<blockquote>
  <p>Are there any case studies / real world examples on subscription vs. one-time payment for a similar audience / product setup?</p>
</blockquote>

<p>No idea if there are any studies for a similar audience / product setup, but here are few thoughts:</p>

<p>One-off likely makes sense for you indeed. You're offering something which I presume is very valuable to the students if you deliver. (More on this below.)</p>

<p>Students, like all consumers, like to try before spending their hard-earned money (or worse: their student loan money), so definitely explore offering either some kind of a free trial for a month or a money back guarantee.</p>

<p>If you offer a money back guarantee, be aware of this counter-intuitive fact: the longer the guarantee is, the better. Because consumers will either have had plenty of time to decide "yeah this really <em>was</em> valuable", and some will have forgotten about the guarantee come its deadline. I've tried 1-month and 3-months over the years, and found 3-months is generally better: the clearcut refunds usually occur in the first weeks anyway, when it's only 1-month it's stressful in that users need to decide quickly, and by the 3rd month the on-the-edge ones will either have been rescued or have forgotten. I've never probed into 12-months (it always made my clients nervous) but I hear it works quite well too.</p>

<p>If you do set up a money back guarantee, the next debate will be whether to send a "Reminder: you've one month left to ask for your money back if you weren't satisfied with our service." type of email. Personally, I prefer to send a "We'd like to hear from your experience in the past quarter" email instead, and remind those who can't realistically be rescued without a lot of effort that you've a money back guarantee. This will ensure even unhappy clients say nice things about you - they did get their money back, after all. Either way be sure to collect the feedback so you're aware of opportunities to improve your service.</p>

<p>With respect to terms, and getting back to the earlier point I intended to expand on, it strikes me as bizarre that you're providing the same thing for three different price points. If the goal is to help them prepare an exam, the closer you are to the exam the more valuable your service and the more desperate your buyers. So it's just wrong.</p>

<p>That being said, there is something to say about students not being able to throw big bucks at a problem. You should, I suspect, be thinking about your subscriptions not in terms of durations but in terms of installments: "Pay $x one off, or pay it in 4/12/[what have you] installments at no (or little) extra charge."</p>

<p>Switching from your current subscription model to one with installments involves some technical tweaking, but is otherwise mostly copy change. Doing so should have an instant effect to your bottomline as a bonus, in that your clients' lifetime value will be roughly constant and, depending on what your retention rate is now, much higher than it currently is.</p>

<p>While you're at it, you can likely give lifetime or multi-year access to the materials you're posting with very little risk. Those who pass the exam won't care much about what's new anyway (or maybe they will and value it, yielding an expanded market), and you'll do a well deserved favor to the occasional students who fail their exams in the process. (Because hey, you failed to live up to your promise if they did.) You'll get the goodwill of the students on top, and the opportunity to up-sell whatever might be useful to ensure they don't fail twice. You may very well end up building a community of users in the process, too. Think forum where old time users chit chat on random insider topics and the "good old times" while providing help to newbies. Plenty of benefits in doing so...</p>

<p>Lastly, you're dealing with students so don't hesitate to probe into alternative business models. I once ran into a fun guided tour operator that offered nearly free tours that couldn't possibly be breaking even on the tours alone. Further probing revealed they were earning money by operating the tourist shop in front of the bus stop and selling the photos their professional photographer would shoot as the tourists visited the premises they took them to. Can you do something like that? If so, consider trying it to undercut your competition.</p>

<blockquote>
  <p>Are there any tools or methodologies are there to estimate, design tests for and ultimately decide on the right price points? (we're comfortable and willing to run A/B tests, surveys or doing email campaigns with some offers to test hypotheses)</p>
</blockquote>

<p>Step one is to ask them of course. I really mean ask, as in face to face or phone or equivalent. Not survey, not email, not what have you. Get them on Skype or in a Google Hangout, and collect the raw info straight from the horse's mouth. Anything in writing will have been filtered (like this answer) two or three times before it is written. Written chat kind of works too if you really need this to be cheaper, but live feedback with voice intonation and body language is always better.</p>

<p>Step two is to take a step back and see what you're charging in the context of what the students have committed to pay already. Assuming this is Germany where education is free, it's a different story from the US where you may end up paying thousands per year for your education. Still, picture what a student typically pays per year, and put your service in perspective. What are your odds of rescuing a failed student? Prove it by showing success/failure rates of non-clients vs clients. Highlight how much an extra year is worth to those who fail. Then slap a sensible number on your service. "Invest $x and save $y by not having %z more chance of succeeding." I'm sure you've a stats person around in your team who will give you the precise figure you should be charging based on that remark.</p>

<p>Apart from that, yeah, the usual suspects of A/B tests and yada yada yada if you really feel like fiddling. But do note my above remark on installments. My best guess is it'll have a higher impact on your business' bottom line than any amount of A/B testing. Plus it'll go faster.</p>

<blockquote>
  <p>We have purchase data (and analytics) from the last 3 years or so, and can analyze things like lifetime value, retention / churn etc. What metrics should we look at in particular for making a more informed decision about any price changes? (we're a bit lost in all the data)</p>
</blockquote>

<p>Aren't we all? :-)</p>

<p>Joke aside, it really depends on your company and its goals. The two that usually count in sane startups are your customer acquisition costs per acquisition channel and your customer lifetime value per acquisition channel. For startups so well funded that they're on a mission to burn as much cash as they can to meet user growth targets, raw sign-up (and retention) rates are often the ones that count.</p>

<p>(The problem either way is, of course, that even with the data most startups are unable to compute either. And there is, to boot, an attribution problem when you factor in cross-device, multi-session users who run into service on their phone, explore it on their tablet, and purchase on their desktop. But that really is another question altogether.)</p>



## Answer 9760

- posted by: [Ted Taylor of Life](https://stackexchange.com/users/4406495/ted-taylor-of-life) on 2016-07-23
- score: 1

<blockquote>
  <p>Are there any case studies / real world examples on subscription vs.
  one-time payment for a similar audience / product setup?</p>
</blockquote>

<ul>
<li>This person from Quora did a great job (Olivier Marschalik)of answering your question

<ul>
<li><a href="https://www.quora.com/What-are-the-pros-and-cons-of-software-subscription-vs-perpetual-license" rel="nofollow">https://www.quora.com/What-are-the-pros-and-cons-of-software-subscription-vs-perpetual-license</a></li>
<li>Here is a <strong>study</strong> that should help you <a href="http://resources.flexerasoftware.com/web/pdf/archive/wp-SoftSummit-2012-KeyTrendsSurvey.pdf" rel="nofollow">http://resources.flexerasoftware.com/web/pdf/archive/wp-SoftSummit-2012-KeyTrendsSurvey.pdf</a></li>
</ul></li>
</ul>

<p>I cannot post anymore links because I do not have the rep.</p>

<blockquote>
  <p>We have purchase data (and analytics) from the last 3 years or so, and
  can analyze things like lifetime value, retention / churn etc. What
  metrics should we look at in particular for making a more informed
  decision about any price changes? (we're a bit lost in all the data)</p>
</blockquote>

<ul>
<li><p>One are you may want to look at  are retention rates, churn and the friction to pay for your product.</p>

<ul>
<li>Don't you wanna see the stickiness of your product?   </li>
<li>As a customer, do I know that I am getting what I really need?</li>
</ul></li>
<li><p>Is there something that is making the customer think twice about pulling the trigger? </p>

<ul>
<li>It could be a lot of things, it could be the design or the site, how easy it is to navigate etc.</li>
</ul></li>
</ul>

<hr>

<p>Best of luck and I hope this helps!</p>

<p>Edit:</p>

<hr>

<blockquote>
  <p>" Over 285,745 medical students and professionals all over the world
  have used <strong>Kenhub</strong> to learn anatomy."
  - You failed to mention that your users are only learning one thing, anatomy.</p>
</blockquote>

<ul>
<li>Now that I know what you are talking about, this is much easier to try and help. 

<ul>
<li>What about seeing how long it takes someone to complete a course or quiz? </li>
<li>Activity, how fast does the average user learn based off their background or age? I could go on and on, but this is pro bono and I have given you plenty of resources to help you make a decision. </li>
</ul></li>
</ul>



## Answer 9800

- posted by: [Neil](https://stackexchange.com/users/2711480/neil) on 2016-07-28
- score: 0

<blockquote>
  <p>We have purchase data (and analytics) from the last 3 years or so, and can analyze things like lifetime value, retention / churn etc. What metrics should we look at in particular for making a more informed decision about any price changes? (we're a bit lost in all the data)</p>
</blockquote>

<p>I am just going to answer this part as I do not know about the other questions.</p>

<p>I would recommend bringing in a statistician/data scientist/ social scientist (with quantitative statistical background) to look at your data and help design your experiment or analyse existing data.</p>

<p>I will help with the working to frame this kind of work. But success will depend alot on the quality of your data. With the above I have worked with statisticians who do not understand business and struggle to communicate, so I would ask for a anonymous report from another client from the outset.</p>

<p><strong>Analysing existing data:</strong></p>

<p><em>Independent variable</em> = Subscription length (1,3,12)
<em>Dependent variables</em> = Subscription duration, Number of service access times, price etc. (add in all your categories)
<em>Analytical method</em> = Structural Equation Modelling (SEM) with Confirmatory Factor Analysis (SEM) output or Analysis of Variance both with multi-colinearity. </p>

<p>This will tell you what factors significantly affect your income.</p>

<p><strong>Designing an experiment</strong></p>

<p>Based upon what you have said I would recommend you try a range of promotions at different times and different medians. Ensure that these all have a unique promotion code (e.g. Promo 671 then Promo A85 etc.). This will test the effectiveness of your marketing and advertising as well as costings.</p>

<ul>
<li>Median (different web-platforms, print adverts etc)</li>
<li>Price (track the sale price)</li>
<li>Timings (Ensure that you track when orders come in to build up trends).</li>
<li>Descriptive information (age, gender, education level)</li>
</ul>

<p>I would recommend that these all are tested against a measure such as total income by customer.</p>

<p>Then you can build up your customer segments and have evidence for the optimal pricing (to do this really well this should be embedded into your website etc). </p>



## Answer 9717

- posted by: [Edmund](https://stackexchange.com/users/1693376/edmund) on 2016-07-15
- score: -1

<p>Since this is a one off, I'd suggest you do a Bronze / Silver / Gold package set up, with different features and pricing for each. Try segmenting your audience based on what they need. Maybe some of them want extra support for certain subjects, and maybe some of them just need a basic outline (not so sure what your product is but you get the idea).</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
