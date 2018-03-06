## What SaaS solution tracks all major Ecommerce KPI's?

- posted by: [Arturino](https://stackexchange.com/users/231983/arturino) on 2016-10-02
- tagged: `e-commerce`, `data`, `analytics`
- score: 1

I'm looking for a 1-stop solution that will do:

Multiple Cohort Reporting ( Retention,etc)
Generate & Track CLV, CAC, etc..
Referral Tracking

If not at least working out-of-the box on all of this.. it has the ability for me to customize this data.

thanks!





## Answer 11261

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2016-10-02
- score: 1

Short answer: there is none.

That being said, look into Segment, Heap Analytics, and Periscope Data for a close approximation:

https://segment.com/docs/integrations/heap/

https://segment.com/docs/integrations/periscope.io/

Segment is a pipeline service that allows you to track once and integrate with all sorts of SaaS tools that let you dissect and massage data as you want. It also lets you can replay your past data so you can evaluate tools with your actual data.

Heap is neat, in that it basically tracks _everything_ and lets you run queries to gain insights ex-post.

Periscope allows you to mine your data and produce just about every report you'll ever want.

The truth, though, is that the only sensible way to get good data is to stream it to your own warehouse and customize the queries you're after - i.e. throw it into Postgres or Redshift and start mining it with Periscope or similar. Chief among the reasons for doing so is that you want to strip out noise data - ad fraud-related traffic, completely unqualified users who opened your page indeed but closed their browser tab then and there, etc. None of the SaaS offers out there will clean your data for you. Another good reason is that every company has its own definition of CAC, active user, retention rate, or even CLV.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
