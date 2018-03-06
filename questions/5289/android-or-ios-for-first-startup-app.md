## Android or iOS for first startup app?

- posted by: [Subhransu Mishra](https://stackexchange.com/users/117429/subhransu-mishra) on 2015-05-15
- tagged: `mobile-apps`, `android-development`
- score: 4

This question is not generic it's specific to my situation. After developing my app for like  50% I realized that many startups start with iOS first then go for Android. Will it be a good strategy to stop the android development and jump into iOS (dev app from scratch) or continue building the android app (rest 50%) complete and launch. The reasons for iOS first are mentioned in other stackexchange questions. I am looking for advice specific to my situation.

**Edit**
The app I am developing is a community based(Like quora/twitter) app. It's not a paid app. But I am planning to have yearly 1$ fee(first year free). 


## Answer 5290

- posted by: [blunders](https://stackexchange.com/users/216182/blunders) on 2015-05-15
- score: 3

Much of writing code in my experience is about thinking about the flow of code, data structures, etc. and the interface, so if you switch which platform you deploy to first, you've still already done some work that would likely help. 

That said, what you would lose is some of the familiarity you have with the code you're currently working on.

If it were me, unless there was some reasoning I'm missing, I'd finish what you've started.


## Answer 5295

- posted by: [jdero](https://stackexchange.com/users/1972448/jdero) on 2015-05-16
- score: 2

I am highly confused - if you've really done 50% of the work, you should know with quite some specificity exactly what it's going to take to write the iOS app.

I'd say the hardest part about building an app, regardless of the platform, is bringing the UX into alignment with your business plan. Writing code isn't hard. Giving the precise definition to build exactly as it needs to be done is the tricky part.


## Answer 5294

- posted by: [John Looker](https://stackexchange.com/users/5196682/john-looker) on 2015-05-16
- score: 1

Leaving the question of which platform is best to target marketing wise, technology wise Android and iOS are different enough that significant duplication of code will occur if you go native. 

You will also usually need to make at least some small design changes between platforms, like the location of buttons.

IF you decide to re-write your App for iOS i'd recommend you look at investing in cross-platform development tools that can support both iOS and Android simultaneously (or with minimum additional effort) and doing the job right. That way the investment and additional delay would be worth it.

Your iOS version may turn out to be different than your 50% Android version anyway, which may require you re-writing your Android version again.

Think clearly about the end-in-mind and plan accordingly.
Look at the trade-offs between writing twice for two platforms vs cross-platform.
Cross platform vs native etc.

Perhaps do some porting of your current code base to a cross-platform tool to see if the performance and features match your requirements.

If this all seems too complicated right now then just finish your Android app and go from there.



## Answer 9274

- posted by: [davidtaubmann](https://stackexchange.com/users/2167306/davidtaubmann) on 2016-05-20
- score: 1

<p>I've edited my answer for the sake of standards... As this question is a duplicate of <a href="https://startups.stackexchange.com/a/9275/9136">this one asked some years ago</a>, I've decided to move my answer there and will leave the link here very clear, so you can anyways mark this as a good answer for you (if it is so):</p>

<p><a href="https://startups.stackexchange.com/a/9275/9136">https://startups.stackexchange.com/a/9275/9136</a></p>

<p>Basically I'm pointing to an alternative that's becoming very strong this last months: Progressive Web Apps.</p>

<p>This covers ALL devices, and MOST needs of apps, and in the near future it's focusing to cover ALL needs, for me the Internet (as I now call it web 3.0) should be the real path and recover the place that Apps have taken, as it has been built upon world standards in which experts have agreed over decades already (W3 + Companies + Developers). </p>

<p>Hopefully the Internet works as the biggest example of all, and more things become done this way in humanity (Democratically with Meritocracy and Active Participation).</p>

<p>Finally, I would add an extra <strong>option</strong>... If you have spent a considerable amount of time already developing your app, maybe you should better finish it, moreover if it is on Android (which is indeed a good path as it is the most used mobile OS), and once finished with crashes and bugs repairings, you should consider re-developing it over Firebase or some similar Backend solution, and this way much of it can be easily built to support the 3 environments (web, iOS &amp; Android).</p>

<p>Somebody told me on wednesday... "[Nowadays,] <strong>There's no wrong answer</strong> [when choosing the first path for a mobile development]."</p>



## Answer 9279

- posted by: [Jim](https://stackexchange.com/users/351236/jim) on 2016-05-21
- score: 1

Startups are not about the technology, they are about business first. Think about clothing - an apparel company should seriously consider fabric and stitching, but those are rarely the core concerns of the business. Pizza companies promote "better ingredients" but that is promotional, but there's a lot more to the business than that. 

For apps there is so much more to the business than the platform, and here are some business considerations:

1. If your app concept will draw in more people from Google Play, go with Android. If the Apple app store is better, go with iOS. 

2. If you are looking for investors, then if your investors are accustom to investing in Android apps, stick with Android. However, most investors use iPhones. So if you don't know, then probably play the odds and go with iOS. 

3. Consider your demographics. There are differences in the Android vs. iOS demographics. Check that out to see what makes the most sense. 

4. iOS users tend to spend more money on apps than Android users. But there are more Android users than iOS. 

Also look at apps that are similar to yours - do they have more iOS or Android users? Can you find out which platform produces more money for them. Users that already use apps similar to yours will probably be attracted to it. (This is like restaurants that are built next to each other - to some it seems like it would hurt business to have your "competition" close by, but it's a good business model.)

Hope this helps. And good luck!


## Answer 9273

- posted by: [Ess Kay](https://stackexchange.com/users/2619138/ess-kay) on 2016-05-20
- score: 0

<p>You can use Visual Studio with Xamarin Mobile Development add on both included in free community version, or Unity (Though its more game development oriented)
This way you can deploy to iOS and Android without having to rewrite any code.</p>

<p><a href="https://i.stack.imgur.com/LhQpZ.jpg" rel="nofollow noreferrer"><img src="https://i.stack.imgur.com/LhQpZ.jpg" alt="enter image description here"></a></p>

<p>Source: <a href="https://www.xamarin.com/" rel="nofollow noreferrer">https://www.xamarin.com/</a></p>

<p><a href="https://i.stack.imgur.com/MvQ9z.jpg" rel="nofollow noreferrer"><img src="https://i.stack.imgur.com/MvQ9z.jpg" alt="enter image description here"></a></p>

<p>Source: <a href="https://unity3d.com/unity/multiplatform" rel="nofollow noreferrer">https://unity3d.com/unity/multiplatform</a></p>

<p>Visual Studio:</p>

<p><a href="https://www.visualstudio.com/en-us/products/compare-visual-studio-2015-products-vs.aspx" rel="nofollow noreferrer">https://www.visualstudio.com/en-us/products/compare-visual-studio-2015-products-vs.aspx</a></p>

<p>The reason why many companies like iOS first is because there is only a handful of Apple Mobile Operating Systems ratio to Phone types available, while Android can be installed on a multitude of phones with very varying processors and other hardware specifications which may be incompatible with one another.</p>

<p>So building an app on iOS reduces the amount of testing you will need to have it work on every customer's phone.</p>

<p>Android however has a much larger customer base thus you will have a larger audience.
eg: <a href="http://sahrzad.net/blog/android-vs-ios-on-smartphones-worldwide-statistics/" rel="nofollow noreferrer">http://sahrzad.net/blog/android-vs-ios-on-smartphones-worldwide-statistics/</a></p>

<p>To answer your question, You may want to rewrite the code with VS or Unity so when you need to make changes in the future, you don't have to do it twice.
You may want to publish to android first with the price difference and larger user-base, but ultimately it is your own preference.</p>



## Answer 9302

- posted by: [Hobby Dev](https://stackexchange.com/users/4995745/hobby-dev) on 2016-05-24
- score: 0

<p>I would advice to consider cross platform development. E.g. <a href="https://www.xamarin.com/" rel="nofollow">Xamarin</a> or <a href="http://phonegap.com/" rel="nofollow">Phonegap</a>. This way you have to maintain single code base. Though I would like to warn you that cross platform is still not come of age when you want to use advance platform capabilities. But in many cases like yours it can be used. It requires knowledge of the specific languages related to the platform you are using. Phonegap require html, css and javascript whereas Xamarin require C#. It is always helpful to have some understanding of native development to target them from cross platform and shared code base.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
