## How effective are free app promotions?

- posted by: [connor](https://stackexchange.com/users/392995/connor) on 2014-10-17
- tagged: `mobile-apps`
- score: 4

There are several services that offer their users free apps. They work by partnering with app developers who agree to offer their app for free for a short period of time (normally a day or week) and pay a fee in return for their app being advertised. It's an enticing pitch for developers who have just released an app and are looking for traction, but does it actually work?

They promise thousands of free downloads during the promotion, but is there any evidence that this translates into more paid downloads later on?


## Answer 1037

- posted by: [tiguchi](https://stackexchange.com/users/1590158/tiguchi) on 2014-10-17
- score: 4

This answer is from an Android app developer's perspective:

First of all, those "free app of the day" campaign providers offer their promotion for free. At least for their promotion campaigns for paid full versions of your apps. And there is also a big catch here.

I participated in one of those promotion campaigns for an Android game. A technical limitation imposed by Google Play forces an app developer to publish a copy of the full version of the game without DRM. The problem is, once a paid app is switched to "free", you cannot switch back to paid again. So promoting the actual paid game was out of question here. And those promo service providers know that and they tell you to create and publish a free copy.

When the free promo campaign is over you have to "unpublish" the copy of the app, so other people cannot download your paid app for free.

Now there were the following results in my case:

1. I had **over 30,000 downloads** for that DRM-free version of my game that sky-rocketed into several "free game" charts on the net (some of them sent me a notification email on that day). It caused a bit of a buzz online.

2. However, I had to **unpublish** that DRM-free copy so basically that sky-rocketed app disappeared from the surface of the planet and I had **absolutely no benefit** from that gained visibility and app store ranking. The original paid version and the ad-supported free version still had just a handful of downloads and therefore no visibility to speak of.

3. A few more new downloads of my ad-supported version of the game started to trickle in, but quickly diminished and went back to normal; there were basically **no noticeable viral effects** caused by that user base of 30,000 people despite Facebook sharing and "like" functions. However, I bet that my design and the genre of the game are to blame. Most apps are way more pushy in order to force some kind of viral effect.

Then there are unpleasant side-effects:

1. In case of updates and fixes I have to **maintain yet another copy of the same** game, which means more time spent on builds, tests and deployment.

2. The **"unpublished" game is still accessible** for anyone who downloaded the game, while it was officially available. However, they have to know how to get to the app store page (only possible through a direct link).

3. If someone buys a new phone or reinstalls the game, **they cannot find it by searching the app store**. In the eyes of your users, that's of course the developer's fault.

4. It is neither explicitly documented nor for sure if an unpublished app remains accessible in the future. I figured it out through experimentation that is is possible now. Google Play may change that without notice.

**The bottom line is:**

While it was a nice experiment, the benefit did not quite justify the effort I had to put into it. Only a very few blogs and minor European publications picked up that my app was free for a day and wrote something about it. Since I had to unpublish the promoted version of the game, it was an extremely pointless exercise for me. The extra visibility on the Google Play app store is lost.

The Samsung app store is way better for that kind of promotion campaign, since they allow you to discount your app for any period of time. Unfortunately the Samsung app store is not supported by those companies that provide free app promotion campaigns. Most likely also because it's not a widely used app store.


## Answer 1041

- posted by: [Jeremy Parsons](https://stackexchange.com/users/497810/jeremy-parsons) on 2014-10-18
- score: 4

To understand "free for a day," you need to **focus on the principle and away from the mechanism**.

"Free" is a big attention draw, but learning what people might accept for free tells you nothing about what they might pay for. In consumer goods, "free" can be a relatively low-cost way of getting a consumer to try your product and at least recognise it in future. But Mercedes isn't going to launch its latest model by giving it away free for a month.

Apps are more like Mercedes vehicles than they are like chocolate bars. So if you give them away, it needs to be because you need an initial user base, or access to different types of user than you have now, or because your monetization strategy isn't all about the buy price.

If one of those applies to you, the many free for a day / week / month sites and apps out there could be worthwhile, as could coupons for in-app purchases distributed other ways.

Once you've decided it could be right for you, it's time to understand the mechanics in fine detail, because the mechanics of your particular app ecosystem, and of the free app promoter, are going to have an impact. Here are the main tripping hazards I've seen, but get out and scan for blog posts, because things can change fast.

***Free,* or *free upgrade*?**

If you are just looking for volume, low friction is vital. Every step you add to the process increases the drop-out rate. Some app ecosystems have a free trial mechanism; some expressly prohibit your free app becoming paid. So go through what you have to do initially, and what you have to do longer-term, and if there's extra hassle, weigh that in as a cost.

To mitigate complexity, you'll see a lot of people using these services to offer a free (forever) app, with a free (for now) premium upgrade. In the success case, that gives some fine-grained control over what happens to the free cohort over time. But it will be difficult or impossible to know whether you would have got better results if you had avoided that high friction complication.

**Hate bait**

In your head, your app is going to be great for a certain type of user, in a certain use case. Having a paid app makes that outcome more likely: even if your app is a penny, I'll pause for a moment before paying.

Go free, even for a day, and suddenly you have people using your app who you didn't build it for. If they're unhappy, you don't mind... **only that's where your ratings are going to flood in from**. Never mind they got something for nothing, Joe public is going to one star your app for its unfriendly interface, even though it clearly stated it was only for nuclear physicists.

So take nothing on trust. Don't just check the "free app" references they give you. Sign up yourself, take up every offer, and watch the results. You need to know what kind of apps are going to be well-received, and if it's not your kind, steer clear of the haters.

**Free, or worthless?**

I see a lot of people push buggy v0.1 of their app out through this kind of channel. The logic goes - why would I invest time in making my app shine unless lots of people want it? If they come in droves, I'll fix it then.

This sucks. The site or app that gave me the free offer told me a story about how I'd get something valuable on a limited offer freebie, it didn't tell me they were filling a skip with junk, help yourself.

Don't use these services that way. It's actually surprisingly cheap to pay people to try your app and give you feedback. So if you love your idea, invest at least as far as debugged v1.0. Or if it's the idea itself you want to test, pare it back to an MVP that you can build well.

**So what?**

The services you describe are one of a number of channels that can help you leverage the impact of "free." If "free" isn't good for your app, steer clear. If it could be, then you need to understand the options, and choose with care. Beware the stories of success and the tales of woe. It doesn't matter how this worked for them, it only matters how it *might* work for you.


## Answer 1036

- posted by: [blunders](https://stackexchange.com/users/216182/blunders) on 2014-10-17
- score: 1

Offering the app for free as a promo works best if most of the revenue is made via in-app purchases.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
