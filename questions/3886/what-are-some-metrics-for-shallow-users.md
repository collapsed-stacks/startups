## What are some metrics for shallow users?

- posted by: [ShallowHallow](https://stackexchange.com/users/6025104/shallowhallow) on 2015-03-30
- tagged: `software`, `metrics`
- score: 4

<p>I just put up a software prototype online, and people have been checking it out all day. </p>

<p>Now some people just log on, play around for a few minutes, and leave.  </p>

<p>Other people log on and have been using the software all day.</p>

<p>What metrics are there for measuring "shallow users" vs. "deep users"?  What baseline percentage of people -- roughly -- should I expect to just try out software for 30 seconds and then never use it again?</p>



## Answer 3893

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-03-31
- score: 2

<p>The gold standard to <a href="http://www.kaushik.net/avinash/advanced-analytics-visitor-segments-engagement-social-media-search-long-tail/" rel="nofollow">segment non-flirts</a> is to filter users with page depth >= 3 in GA or something to that effect.</p>

<p>In your case, it may make sense to toss in an additional filter, namely number of sessions >= 2 (or 3, whichever makes sense in your data). This is assuming that your shallow users only have one or two sessions.</p>

<p>In the event you've active users that are deep and others that are shallow, GA also offers the possibility to users segment by session duration.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
