## Why do apps move to BaaS?

- posted by: [Alexa](https://stackexchange.com/users/8775623/alexa) on 2016-10-18
- tagged: `mobile-apps`, `applications`
- score: -1

<p>After looking through questions on Stack Exchange, I found one about why startups move off BaaS. However, I know businesses actually tend to move to BaaS offerings, especially if the services are free and reliable. What are the reasons for moving to platforms such as Parse, Backendless, and others?</p>



## Answer 11373

- posted by: [Community](https://stackexchange.com/users/-1/community) on 2016-10-18
- score: 0

<p>The decision of whether or not to use a <a href="https://en.wikipedia.org/wiki/Mobile_backend_as_a_service" rel="nofollow">BaaS</a> (or any other <a href="https://en.wikipedia.org/wiki/As_a_service" rel="nofollow">*aaS</a>) service is about finding the right balance between paying more up-front to develop the service in-house versus paying a third-party more per-request for using their service. In other words, developing your own backend services and running them in-house will require more resources up-front (you have to develop all the code from scratch), but will cost less to per-request since you're not paying a mark-up on the computing resources required to run the service. On the other hand, plugging an app into a third-party API will generally be cheap and painless up-front (no major code to develop, just need to learn an API), but you are going to pay relatively more per-request because the third party service provider needs to pay their costs and earn a profit.</p>

<p>In my experience, companies that use BaaS services start using them because of convenience. Using a service helps to launch faster and lets developers focus on core business logic. Over time, as popularity of an app grows, the per-request costs grow and the company building the app might figure it would be cheaper to build their own backend services to reduce the per-request costs.</p>

<p>Many *aaS providers have free or very cheap plans for low-usage. This is an attempt to <a href="https://en.wikipedia.org/wiki/Vendor_lock-in" rel="nofollow">lock in a customer</a> to a service early in hopes that customer will continue to use the service, and to pay higher rates as his needs grow. Of course, <a href="https://en.wikipedia.org/wiki/There_ain%27t_no_such_thing_as_a_free_lunch" rel="nofollow">there ain't no such thing as a free lunch</a>.</p>

<p>Good *aaS providers will be smart enough to develop a price structure that maintains value to the customer at larger scales. However, given the nature of <a href="https://en.wikipedia.org/wiki/Economies_of_scale" rel="nofollow">economies of scale</a>, the greater the need for a large amount of services, the harder it is to justify *aaS services at any price.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
