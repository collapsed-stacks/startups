## Is it worth to support iOS 7 for an application which will be released on the App Store on September 2015?

- posted by: [King-Wizard](https://stackexchange.com/users/1123041/king-wizard) on 2015-04-20
- tagged: `mobile-apps`
- score: 5

I started the development of an iOS application one month ago (so I am at the early stage of development). I am alone on this project and consequently the only developer and I have to manage other tasks (design, concept of the application, fund raising, etc). I use Swift and iOS 8 to develop this application and do not need to use brand new features only available on iOS 8 (like Apple pay, health, etc). **I need to support iOS 7 for certain features and I take roughly 4 to 5 hours each time to adapt my source code to support iOS 7.**

**I did my research on the internet and found these two following links:** [link 1][1], [link 2][2]. To sum up, these two links tell us that currently there are roughly 19%(13% @Late August) of users using iOS 7 and 79%(86% @Late August) using iOS 8. We also know that nearly each year Apple stops supporting one of their devices. Probably the iPhone 4s in September 2015.

**I plan to release my application on the Apple Store on September 2015 and the future release of iOS 9 will occur the same month.** I have checked the most famous applications on the Apple store and on average they only target the current iOS version and the current iOS version minus one (which means iOS 8 and 7 at that time), excepted for exceptions like WhatsApp and YouTube which respectively support iOS 4.3 and 6. 

**If there were only these data to take in consideration, the choice of not supporting iOS 7 would be obvious in my case, but it is more complicated than that because as you probably know the users having the iPhone 4 will not be able to use my application. They will also not be able to upgrade to iOS 8 (Apple decided to stop supporting the iPhone 4 in all iOS versions > iOS 7.1.2), which means they will never be able to use my application if I do not support iOS 7.** 

**The problem is that I have not been able to find global statistics (related to the App Store) where the data is grouped by iPhone devices, which could obviously help me to answer to the question, knowing what exactly represents the 19%.** Knowing that and after having consulted the statistics above, my goal is to target as many users as possible, but the number has to be significant. Moreover I also see that the iOS 8 adoption by users steadily increases month after month.

**Eventually I am wondering myself if in my case it worth to spend my time supporting iOS 7?**

Note: I guess the wisest decision would be to stop supporting iOS 7 from January 2016 (in a perfect world). Nonetheless I am asking this question to you guys in order to know if it is rational and not dangerous for my future application and business to shorten and thus give up (at least for the moment) the support of iOS 7 and use my time for other things.

  [1]: https://developer.apple.com/support/appstore/
  [2]: http://david-smith.org/iosversionstats/


## Answer 4062

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-04-20
- score: 3

I had a similar experience myself a few years ago when I needed to decide whether to support iOS 4 or not instead of sticking to iOS 5 or more. (I then ruled iOS 3 out due to the lack of ARC.)

The stats at the time were something like 80% iOS 5 / 20% iOS 4, give or take a few percent for older versions.

As you can see, the stats a few years back weren't much different from today's 80% iOS 8 / 20% iOS 7, give or take a few percent for older versions.

And in two years from now, it's pretty safe to assume the ratio will likely be 80% iOS 10 / 20% iOS 9, give or take a few percent for older versions.

The chief reason is that scores of users have a two year mobile plan and change their device every two years by virtue of incentives to either renew with the same carrier or change carrier.

The trend to be on the lookout for when making this decision is whether there's are any serious talk about dropping carrier subsidies on cell phones. As long as they're around in your target markets, you're safe to assume that your client base will be using reasonably recent devices.

(I ended up opting for iOS 5.)


## Answer 4060

- posted by: [thedp](https://stackexchange.com/users/57959/thedp) on 2015-04-20
- score: 1

I am also currently in the middle of an iPhone app development, and here are my conclusions on this dilemma: 
<br/><br/>
The 19% with iOS7 are probably due to one of the following:

 1. People that just can't upgrade to iOS8, due to older hardware.
 2. People who don't care about upgrading, because... reasons.

Here is where you need to take into account the type of application you're working on, and what is the target audience.<br/><br/>
For example, if you're developing a social media related app, that aims at the U.S market for ages 16-21:

 1. The target users will probably soon upgrade their hardware, since they will be left out of all the cool new apps.
 2. The users that don't care, are not part of your target audience in the first place. I know iPhone4 users that are still stuck on iOS4, and as long as it can make a phone call, they don't care.

For the example above, if it's simple to adjust to iOS7, do it. If it creates an additional overhead on the development process then drop it. Especially if you're planning to release only at the end of the year.<br/><br/>

I personally do support iOS7, and not just because I have an iPhone4 :)
My app is due to be released next month, and it's a simple adjustment in my app.

Good luck.


## Answer 4066

- posted by: [Jastor](https://stackexchange.com/users/6160898/jastor) on 2015-04-20
- score: 1

To answer your question about **Global Stats** 

It might be wise to consider that the Western countries often have newer devices and upgrade quickly, while other countries tend to have older devices. Depending on your app and what it plans to do, you could be leaving a lot of users out do to the inability to install your app without the iOS 7 support. 

If you're developing games, that's one thing, if it's a utility or branded app.. that's another.

With more and more people coming online in the next few years, this growth will come from the third world countries, likely using older iPhones (and yes Android devices). This may or may not be a consideration for you depending on the complexity of your app.


## Answer 7573

- posted by: [Cesidio](https://stackexchange.com/users/1732434/cesidio) on 2015-10-15
- score: 1

Here are some stats from Apple regarding market share taken form the App Store.

https://developer.apple.com/support/app-store/



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
