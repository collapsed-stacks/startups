## How find a startup friendly native mobile analytics platform?

- posted by: [Esqarrouth](https://stackexchange.com/users/3055586/esqarrouth) on 2015-01-21
- tagged: `mobile-apps`, `analytics`
- score: 1

A lot of the current analytics for mobile are either focused on web, get data updated really late, are filled with bunch of data which aren't very important for startups, expensive.

How do you find a startup friendly native mobile analytics platform - and what's the best way to determine its fitness for commonly used [startup metrics][1] such as: acquisition, activation, retention, referral, revenue, cohort analysis, etc.


  [1]: http://500hats.typepad.com/500blogs/2007/09/startup-metrics.html


## Answer 3107

- posted by: [Jason Mcmunn](https://stackexchange.com/users/5429346/jason-mcmunn) on 2015-01-21
- score: 1

<p>I would look at the Amazon AWS suite.  One of their key offerings is the Mobile Analytics component.  You can get more information <a href="http://aws.amazon.com/mobileanalytics/" rel="nofollow">http://aws.amazon.com/mobileanalytics/</a>.  What I like most about the service is that it is evolving fast and is also priced based on your volume.  If you're just getting started you can probably even qualify for the free tier for a year.  Even if you can't get the free tier, it's very cost effective.
The reasons I feel it's good:</p>

<ol>
<li>Cost effective - If you look at the pricing example you can do 20 million sessions with 12 events per session for $140/month.</li>
<li>Has support for online and offline event capture</li>
<li>Is exportable to other amazon tools or third parties.</li>
</ol>

<p>You don't have to use amazon's other services to use this service.  You can use this stand alone, but it does integrate nicely with their other services such as RedShift(data warehouse) or Hadoop style data manipulation tools.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
