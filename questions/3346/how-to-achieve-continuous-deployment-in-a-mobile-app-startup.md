## How to achieve continuous deployment in a mobile app startup?

- posted by: [Esqarrouth](https://stackexchange.com/users/3055586/esqarrouth) on 2015-02-05
- tagged: `mobile-apps`, `lean-startup`
- score: 3

> Continuous deployment is a process whereby all code that is written
> for an application is immediately deployed into production. The result
> is a dramatic lowering of cycle time and freeing up of individual
> initiative. It has enabled companies I’ve worked with to deploy new
> code to production as often as fifty times every day. [Eric Ries][1]

Android apps take about an hour, while iOS apps take about a week to deploy. What are tips and tricks to achieve the benefits of continuous deployment when it is technically really hard to achieve?

  [1]: http://radar.oreilly.com/2009/03/continuous-deployment-5-eas.html


## Answer 3413

- posted by: [Yevgeniy Brikman](https://stackexchange.com/users/223985/yevgeniy-brikman) on 2015-02-13
- score: 2

<p>The release cycle of mobile is one of its downsides compared to the web, but there are a few things you can do to make it better:</p>

<ol>
<li>If you're building an app that you use yourself ("dogfooding"), then you can do continuous delivery within the company by regularly delivering new builds to all co-workers (internal builds don't have to go through an app store). </li>
<li>Even with a native mobile app, some of the content can be determined dynamically by your servers, which you can update any time. See <a href="http://engineering.linkedin.com/mobile/mobile-ab-testing-linkedin-how-members-shape-our-apps" rel="nofollow">Mobile A/B testing at LinkedIn: how members shape our apps</a> for more info.</li>
<li>You can take idea #2 even further by using a WebView (i.e., a web browser) within the mobile app for rapidly changing parts of the UI. This has downsides, such as slower performance and a look &amp; feel and interactions that won't quite feel native, but if you need to iterate quickly, it can be worth it. </li>
</ol>



## Answer 3348

- posted by: [Okyasoft](https://stackexchange.com/users/294248/okyasoft) on 2015-02-05
- score: 0

Since, for native apps on app stores there is a review process for getting approved I am not sure if a true continuous integration will be feasible.
However, one potential way to achieve that is using a mobile site instead of an app. Where the app just is a way to access the site. This way, whenever you make any changes to the website you can deploy it to everyone.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
