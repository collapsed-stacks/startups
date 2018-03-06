## Estimating need for data storage capacity for profiles on social network startup

- posted by: [Tommy Otzen](https://stackexchange.com/users/4026382/tommy-otzen) on 2014-08-21
- tagged: `tech-company`, `startup-costs`, `cloud`
- score: 2

I'm new here, so if I need to redefine my question, please guide me.

I'm building a social/professional network. This network will contain user-profiles a bit like Linked-in. In order to do the best calculation for our budget, I need to somehow make an estimation on MB per profile, so I could see how much data is needed for 10, 100, 1000, 10.000 users and so on.

Average on MB per Linked-in profile would be a good estimate for me. 

I've looked and searched all over the net, but didn't find a satisfying answer.



## Answer 442

- posted by: [Laxiton6893](https://stackexchange.com/users/2181902/laxiton6893) on 2014-08-21
- score: 1

<p>It really depends on the need case. If the user action is just uploading a new profile picture and doing text based posts, then not much at all. If the user action is uploading lots of pictures, media e.g. then it is a whole new story. </p>

<p>In your case I would say not to worry about storage per user, because it will become irrelevant as you grow. If storage does become an issue you can always charge users to buy more storage. </p>

<p>What you may want to think about scalability and efficiency. Making sure that your media assets (static, dynamic) are using proper compression so as to give you the best quality while using the least amount of resources.</p>

<p>For start up solutions I recommend looking into <a href="https://www.digitalocean.com/" rel="nofollow">Digital Ocean</a>, really good pricing for basic needs. As you expand then AWS and Rackspace will give you the more granular control.  </p>

<p>From personal experience from dong something similar with basic text posts and user profile image uploading as the only media asset, at 300 users the site is only 40mb with the DB of 23mb. It runs on Drupal which makes up a good 30mb with only 10mb of our own code that makes the site function. </p>

<p>So long story short, web apps built right never really take up that much space. </p>

<p>Hope that helps. </p>



## Answer 471

- posted by: [SerkanSerttop](https://stackexchange.com/users/4509857/serkanserttop) on 2014-08-23
- score: 1

It also depends upon your choice of database/s and how you decide to write to database/s. My project requires 3 different persistent databases for example, to handle different use cases.

To give an example, I collected tweet streams and wrote them straight into MongoDB.
I had about 1.6 million tweets.
MongoDB was ~ 8.6 GB with long field keys, ~ 5.3 GB with shortened field keys, while Postgres was ~ 780 MB.

You have to collect some data, or create it the way you want and then run a loop to populate your choice of database and test your results. That's the only way you can tell.

Update 2014-08-24:
I have not touched upon storing pics or videos as that's a very different type of storage than data. You may want to use SSD for database storage while pics can be on cheaper HDDs and much easier and cheaper to scale. Videos can come from youtube via API, and you seem to have  specified "data storage" which I take it to mean database storage. You may want to clarify this point.


## Answer 475

- posted by: [George](https://stackexchange.com/users/3516499/george) on 2014-08-23
- score: 0

You cannot look at user count alone.  A major consideration are the blogs/community posts.  If you allow these to have pics, or even video, the the size of a sub forum could be larger than all of your user profiles.

You need to better explain the type of data that will be saved, and expected total users in the first month.  Space is cheap, but whatever space you think you will need, it will double every 6 months.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
