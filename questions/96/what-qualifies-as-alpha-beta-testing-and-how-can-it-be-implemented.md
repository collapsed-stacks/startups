## What qualifies as alpha/beta-testing and how can it be implemented?

- posted by: [Awal Garg](https://stackexchange.com/users/3333488/awal-garg) on 2014-07-31
- tagged: `internet`, `testing`, `beta-testing`
- score: 3

<p>The code for my next startup is gonna be ready in a while. I want to have rigorous testing for it, to ensure that the end user-experience is perfect.</p>

<p>So, what qualifies as alpha/beta testing and how can I go about carrying it out?</p>

<p>Some details about the startup:</p>

<ul>
<li>Completely internet based. No product delivery or anything.</li>
<li>Security and User Experience matter the most for it.</li>
<li>Target audience is people talented in technology.</li>
</ul>



## Answer 111

- posted by: [Peter Maidens](https://stackexchange.com/users/4637522/peter-maidens) on 2014-07-31
- score: 5

<p>Alpha and beta testing are simply a release of the product before it is fully functional. The creators of the software get to determine what qualifies as an alpha or beta. Alphas and betas typically have some or most of the core functionality, but may be lacking some extra bells and whistles or may not be completely stable.</p>

<p>You shouldn't use alphas and betas as your only means of testing. You should be writing unit tests while developing your software. Alphas and betas should be relatively bug free and be more of a place where you are trying to get feedback about your product. This is especially true if your application is security centric and your audience is technical.</p>



## Answer 113

- posted by: [Noah](https://stackexchange.com/users/4382547/noah) on 2014-07-31
- score: 4

<p>As Peter pointed out, you should be focusing on using other forms of tests that aren't "end-user tests". The <a href="https://softwareengineering.stackexchange.com/">Programmers StackExchange</a> is a good resource for learning about test-driven development (includes more than just Unit Tests).</p>

<p>To directly answer the question, there are no definite guidelines to use for "alpha" and "beta". It's an arbitrary label that developers/publishers use to identify that a product:</p>

<ol>
<li>is not complete (not to be confused with "commercial release"),</li>
<li>may contain some major bugs,</li>
<li>is not persistent (items and progress can and will be wiped at any time), and</li>
<li>should not be sold (in-app purchases or the sale of the software package.</li>
</ol>

<p>And while alpha and beta are only two test phases, many people choose to have multiple versions of each, such as a "pre-alpha", "closed beta", "open beta", "beta round 2", etc. (See above where I note that it's completely arbitrary)</p>



## Answer 112

- posted by: [SwankSwashbucklers](https://stackexchange.com/users/3088589/swankswashbucklers) on 2014-07-31
- score: 3

<p>Alpha and Beta testing is just getting your product out to a small group of people before you unleash it on the public. For this testing you might invite your friends and family to have a look at your product, with instructions to tell you of any concerns or bugs they run into. Another good way to get beta testers is through social media. If you invite your core fan base to beta test it makes them feel special and strengthens their connection to your startup, making them more likely to follow your product into its completion and to spread the word.</p>

<p>With an internet based product you might consider using a login as a way to constrict your user base. However, you might even consider launching it in full, just holding off on marketing it, and only telling your beta testers. That way you can easily direct people to it, and if the product is just starting out you wouldn't have to worry too much about other people stumbling upon it. If you do take this approach though be careful to note that it is, in fact, in beta, just in case someone does manage to find it.</p>



## Answer 194

- posted by: [Adam Plocher](https://stackexchange.com/users/378064/adam-plocher) on 2014-08-03
- score: 1

<p>I agree with most of what Peter said but in my opinion, Alpha is usually more of a non-feature complete preview to showcase a subset of the product that is provided to some special people (stake holders or a lucky few).</p>

<p>The beta would be feature complete but maybe missing some unimportant "bells and whistles".</p>

<p>There is often closed and open betas which would be internal only or open to the public for finding issues.</p>

<p>A lot of people these days throws those terms around pretty liberally. Gmail was beta for years even though it was completely solid (imo)</p>

<p>I would suggest creating a list of milestones for both. I would also suggest keeping alpha testing internal for the most part.</p>



## Answer 274

- posted by: [Tiago César Oliveira](https://stackexchange.com/users/1257691/tiago-c-sar-oliveira) on 2014-08-08
- score: 1

<p>I recommend you forget about alpha/beta test and actually do <em>real</em> test with a reduced number of customers.</p>

<p>It's your teams responsibility to deliver a product that is working and well tested. You customers should be involved only on perceiving the absolute and relative value of your new piece of code. That is why Twitter and Facebook release a new layout for a reduced number of users: they want to see how it performs, how it can actually get better. Errors could happen, but the solution is tested to exhaustion before release (even for this reduced universe of users/customers).</p>

<p>Never ever provide a user experience that is less valuable than your actual one. Remember: it's your team's duty to guarantee that everything is on place and works (of course, we can get errors - and consistently <em>will</em> - but our focus is always on providing a finalized product).</p>

<h3>Where this doesn't apply</h3>

<p>We see a lot nowadays initiatives through Steam for early access for games still being developed. Your customer is paying to access something he/she wants very much, months in advance. In this case, he/she is actively opting for a product with a noticeable number of errors and failures.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
