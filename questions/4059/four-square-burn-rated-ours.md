## Four square burn rated ours

- posted by: [user4685174](https://stackexchange.com/users/5959610/user4685174) on 2015-04-20
- tagged: `funding`
- score: 2

<p>Why does four square need so much cash? They have collected over 111 mil in funding over a 4 year period. They don't need those huge data centers like Facebook does, nor does their business model need liquidity like uber. Most of the content is gps based data which is collected from user activity, so why are they burning through so much cash?</p>



## Answer 4061

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-04-20
- score: 2

<p>I'm unfamiliar with the specifics of how Foursquare works or what they're up to, but I wouldn't be as sure as you are about their not needing Facebook-style infrastructure.</p>

<p>Sure it'll be smaller in that they're not storing video or tons of images. Regardless, I'm familiar enough with making DB applications scale to surmise that their data throughput is much higher than what a dumb hard drive can handle. Engineers with the skills needed to make that work don't grow on trees, and the infrastructure needed to make that work doesn't come free.</p>

<p>Adding to this, indexing spatial data is not the same as building an index on more typical data. It's slower for writes, slower for reads, it's potentially lossy on reads to boot (that is, it can produce false positive matches that must be filtered out from the result set), and you're typically running proximity- or shape-related queries that may need to get re-ordered in memory based on separate criteria because the requisite indexes are unsorted (in contrast with B-tree indexes). Point here is, it's indeed less HD intensive that streaming videos and serving images over a CDN, or less memory intensive than caching dumb data in memcached, but it's a lot more CPU and memory intensive at the server level.</p>

<p>Add to end-user data collection and reads the fact that the stuff is <a href="http://pando.com/2014/06/27/foursquare-finally-comes-up-with-a-monetization-strategy-that-makes-sense/" rel="nofollow">mined in exchange for money</a>, and the dots seem to connect pretty well imho.</p>



## Answer 4069

- posted by: [adrianh](https://stackexchange.com/users/7553/adrianh) on 2015-04-21
- score: 2

<p>AFAIK your headline $120 million over four years is incorrect. It's <a href="http://en.wikipedia.org/wiki/Foursquare#Funding" rel="nofollow">$112.35M over the last five years</a> — which they're still working through. I don't know how much runway left from that they have. </p>

<p>You also have to remember that most of that money was burned through as they figured out their business model. You don't raise a new round of funding unless you run out of money, or think you're seriously undervalued. </p>

<p>So let's just look at the series D funding ($41 raised in 2013) and guess (I don't know the terms) that that was meant to get them to profitability in five years. </p>

<p>So simplifying and ignoring the growth over that time $8.2M per year:</p>

<ul>
<li>45M users — 1/30 the size of Facebook is still pretty darn big and very definately needs their own dedicated data centres.</li>
<li>170 employees — they're long past startup time and have to pay real wages.</li>
<li>Offices, personal computers, the usual business infrastructure, etc.</li>
</ul>

<p>… and suddenly those numbers don't look so large.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
