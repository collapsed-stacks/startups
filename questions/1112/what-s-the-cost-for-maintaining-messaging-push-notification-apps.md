## What's the cost for maintaining messaging/push notification apps?

- posted by: [user1002782](https://stackexchange.com/users/983761/user1002782) on 2014-10-23
- tagged: `mobile-apps`, `startup-costs`, `servers`, `bootstrapping`
- score: 2

<p>What's the cost for maintaining the backend for a messaging app like WhatsApp say with a million users? Also what could be the backend push notification costs for an app like Yo?</p>

<p>I know a few services like Parse give some free limits, but I was thinking will 1 million req/month be enough for an app that has thousands of user?</p>

<p>Does that mean individuals who want to create such apps would have to stay away from apps that interact heavily with backend and create only offline apps?</p>

<p>Could you please suggest any cost-effective (cheap and best) backend solution for such apps?</p>



## Answer 1564

- posted by: [Thellimist](https://stackexchange.com/users/5431417/thellimist) on 2014-12-05
- score: 2

<p>Parse allows 1 million unique recipients per month for free. 1 million unique devices is sufficient for an app which has thousands of users. </p>

<blockquote>
  <p>Your question reads as if you're focused on scaling to millions of users. If you're focused on supporting millions of users, you'll likely never reach that point. Keep it simple, solve a real problem, then scale. </p>
</blockquote>

<p>I agree with with blunders. You should be thinking scaling when you need to not before. That's one of the biggest advantages of being a startup. Use it. Don't try to work like your in a corporate company.</p>

<p>I advice you to read <a href="http://paulgraham.com/ds.html" rel="nofollow">Do Things that Don't Scale</a>.</p>



## Answer 1114

- posted by: [blunders](https://stackexchange.com/users/216182/blunders) on 2014-10-23
- score: 0

<p>Your question reads as if you're focused on scaling to millions of users. If you're focused on supporting millions of users, you'll likely never reach that point. Keep it simple, solve a real problem, then scale. </p>



## Answer 1457

- posted by: [Henry Taylor](https://stackexchange.com/users/1734959/henry-taylor) on 2014-11-23
- score: 0

<p>I don't want this to read like an advertisement for a specific service, but many of the big cloud providers offer startup programs to offset your costs while your climbing up to that million user level.  These programs usually have a time limit, so someday you will need to figure out how to make money with your idea, but for the short run... (in no particular order)</p>

<p><a href="http://www.microsoft.com/bizspark/" rel="nofollow">http://www.microsoft.com/bizspark/</a></p>

<p><a href="http://aws.amazon.com/free/" rel="nofollow">http://aws.amazon.com/free/</a></p>

<p><a href="https://cloud.google.com/developers/startups/" rel="nofollow">https://cloud.google.com/developers/startups/</a></p>

<p>A great idea that cannot eventually pay for itself is just an idea, and maybe not even a good one.</p>



## Answer 1122

- posted by: [GilesDMiddleton](https://stackexchange.com/users/268546/gilesdmiddleton) on 2014-10-23
- score: -1

<p>A tough question to answer, but I recently saw a video of <a href="http://azure.microsoft.com/en-us/pricing/details/notification-hubs/" rel="nofollow">Azure Mobile Services</a> and thought 'wow', does push, identity, full BaaS. </p>

<p>I currently use PushWoosh with our own backend to manage registration etc - Azure takes that pain away (allegedly).</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
