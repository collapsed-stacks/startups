## iOS vs Android first: What makes iOS first a valid strategy for mobile app companies?

- posted by: [connor](https://stackexchange.com/users/392995/connor) on 2014-09-28
- tagged: `tech-company`, `mobile-apps`
- score: 11

The pattern for most mobile app startups appears to be to release an app on iOS first then release an Android version. Later, they may release on other platforms like windows and blackberry. Some examples I can think of right now are Simple, Mailbox and Robinhood. 

Since Android has a much larger market share than iOS, it seems like it would make more sense to launch there first. [(84.7% vs 11.7%)][1] What then is the technical or business reason for companies to use this iOS first strategy?

  [1]: http://www.idc.com/prodserv/smartphone-os-market-share.jsp


## Answer 1352

- posted by: [Damian Yerrick](https://stackexchange.com/users/3095780/damian-yerrick) on 2014-11-12
- score: 13

Even if Android has seven times the installed base of iOS, you can still make more revenue from the App Store than from Google Play if the average user of iOS contributes nine times the revenue of the average user of Android, as a [_Business Insider_ article from mid-2016](http://www.businessinsider.com/apple-app-store-revenue-per-user-versus-android-2016-7) suggests, or if Android is far more expensive to support.

**iOS users are more willing to buy IAPs.** An article by Ewan Spence in _Forbes_, "[For Mobile Monetization, Choose Android for Ads and Apple For In-App Purchases](http://www.forbes.com/sites/ewanspence/2014/05/21/for-mobile-monetization-choose-android-for-ads-and-apple-for-in-app-purchases/), cites a report by mobile marketing company Swrve that highlights differences between iOS and Android in how their users contribute to revenue. Users of iOS spend more than users of Android, especially on in-app purchases. A mid-2015 [survey by VisionMobile](http://www.itworld.com/article/2957215/development/how-to-make-money-as-an-independent-developer.html) backs up this rule of thumb that iOS users tend to be richer. Users of Android, on the other hand, reopen their applications more often, giving more eyeball time for an advertising-supported app.

**Android users have wanted free.** At one time, there was a huge difference in app prices between iOS and Android. When Android first came out in 2008, Google had payment processing in place in only a handful of countries. When a carrier launched an Android phone in any country without Google Checkout, Android Market would show only free apps to users in that country. So at the time, developers had to make their apps free in order to reach users in those countries. This built up a psychological expectation among Android's user base of being able to download free apps. Apple, on the other hand, would always launch iTunes Store on Mac and Windows in a particular territory before launching iOS devices there. I'm not sure how to what extent this difference continues into the 2010s though, especially with geographic expansion of Google Wallet and price wars among app developers. But in any case, iOS users are [more likely to have already added a payment method](https://support.apple.com/en-us/HT204034), removing another barrier to purchase.

**iOS is familiar to Mac developers.** If a company already maintains an app for OS X, its developers may have an easier time learning the iOS tools (such as Xcode and Cocoa Touch).

**iOS has consistent hardware.** Because Apple controls the entire supply chain, every iPhone of the same generation and every iPad of the same generation will be identical, save screen size in the iPhone 6 and later and iPad mini. Android phones, on the other hand, have far larger differences in CPU, memory, graphics, defects in manufacturer and carrier customizations of the software stack, etc. Some Android devices don't even have ARM CPUs; they have MIPS or x86 CPUs instead, and NDK applications (those using native code as opposed to 100% pure Java) usually need to be recompiled. Sometimes these media refers to these differences as "fragmentation", and it can lead to support headaches when your app inadvertently depends on implementation-defined, unspecified, or undefined behaviors of the Android platform.


## Answer 836

- posted by: [blunders](https://stackexchange.com/users/216182/blunders) on 2014-09-28
- score: 11

<p><strong>TLDR:</strong> Answer is there is no clear answer. In my opinion, the best solution would be to pick a platform that enables deploying to both unless you've got to write platform dependent code, run-time issues based on your specs result in failures in converting and retaining users, etc.</p>

<hr>

<p>As you point out, <a href="http://www.idc.com/prodserv/smartphone-os-market-share.jsp" rel="nofollow noreferrer">Android continues to dominate the global smartphone market</a>, with over 255 million units shipped and nearly 85% of the market share in the second quarter of 2014. Given Apple introduced two new iPhone 6 models this month, it's possible that Apple will gain more market share, though that's yet to be seen.  Market share in this case refers to installs, and the issue is that the count of devices running a given system turns out to be a bit deceptive in the context of selecting a platform to build apps for. </p>

<p>Main issue is that Apple's devices on average have better hardware, and as a result, have a larger market share when it comes to devices that are able to run higher end apps. It turns out that two thirds of the devices that make up Android’s 81 percent market share are cheap “<a href="http://www.forbes.com/sites/tonybradley/2013/11/15/android-dominates-market-share-but-apple-makes-all-the-money/" rel="nofollow noreferrer">junk phones</a>”.</p>

<p>The next issue is that install counts do not take into account the fragmentation that Google has allowed with the Android platform; Apple’s primary rival is really Samsung, not Google. Depending on the requirements for the app, this might not be an issue.</p>

<p>While there are other factors to account for, many which are driven by context, the OS's usage and engagement online is a huge factor:</p>

<p><strong>Percentage of Web Traffic Worldwide</strong></p>

<p><img src="https://i.stack.imgur.com/yvSVp.jpg" alt="OS&#39;s usage and engagement "></p>

<p>The chart above shows the percentage of total web traffic worldwide, across all platforms, that is taken up by Android, iOS, and Linux; source: <a href="http://www.netmarketshare.com/operating-system-market-share.aspx?qprid=9&amp;qpcustom=iOS,Android,Linux&amp;sample=29" rel="nofollow noreferrer">netmarketshare</a>. Clearly, Android is making grounds with online usage, though it's important to recall that online use does not equal high-end hardware. In fact, when it comes to web-traffic, apps really are not the best solution in most cases, mobile websites are.</p>

<p><strong>App Stores for iOS vs. Android</strong> </p>

<p><img src="https://i.stack.imgur.com/psHLP.jpg" alt="enter image description here"></p>

<p>According to Piper Jaffray, the source of the graph above, they claim apps are no longer a "point of differentiation," having become an expected feature for modern smartphones. Chart reflects top 200 apps for both stores as January 2014, 38 paid and 74 free titles were found on both platforms. That said, if you're a top 200 app on one platform, likelihood that you'd do both platforms to leverage your brand's value is pretty high; meaning these stats and the resulting <a href="http://appleinsider.com/articles/14/01/06/apps-no-longer-differentiator-in-ios-vs-android-war-services-next-battleground" rel="nofollow noreferrer">analysis that apps are not a platform selection for consumers</a> is likely flawed.</p>



## Answer 844

- posted by: [Laconic Droid](https://stackexchange.com/users/3920235/laconic-droid) on 2014-09-29
- score: 3

<p>There is a great <a href="http://www.imore.com/iterate-43-pocket-casts-and-going-android-first" rel="nofollow" title="Iterate">Iterate</a> podcast from 2013, where the guys from Shifty Jelly discuss why they went "Android First" with their Pocket Casts app. It covers a lot if interesting ground as to why iOS is often the initial platform for developers, and why they decided to take the opposite approach.</p>



## Answer 839

- posted by: [Matthew Haugen](https://stackexchange.com/users/1325646/matthew-haugen) on 2014-09-29
- score: 2

I like to think I'm wrong on this, but as a general rule, I'd say it's just a mixture of habit and "coolness" factor, more than anything too objective. I have a Windows Phone--try not to laugh too hard--so I'll admit that I look at the battle over these two phones from somewhat of an exterior perspective, but I think you might be reading a bit too much into it. *"This question appears to be off-topic because it asks us to explain the behaviors of others."*

What's about to follow are some pretty wild, baseless judgments that display my guesses about what could be the cause for this, so take this with a grain of salt. I'm also not sure that this necessarily explains it all, but it does account for a few select cases of startups that I've dealt with.

**Habit**

Per model, I suspect iPhone has better coverage than Android. There are a lot of Android devices, but that just means that their attention becomes distributed throughout them, which means it's hard for innovators to objectively look at the world and see the numbers accurately. Say you have a party with five attendees: one has a Galaxy Note, one has an HTC One, two have iPhones, one has an LG G3. If you aren't *technically minded* (whatever that means), you might not draw the correlation that three of those are Android devices and only two are iPhones, you might just see it as three individual and unrelated devices *and two iPhones*. I suspect a similar effect can be seen in people's views of the actual market-share.

Furthermore, by only having one (or two) iPhone models, Apple has managed to keep the mental picture people draw to have a physical form. What do I mean by that? Look even just at the semantics: "iPhone" is hardware, and "Android" is software. I think the fact that Apple can capitalize on people's touch senses and give them a device to imagine the feeling of makes it seem more significant, so even though Android has a better market share, many people's minds will consider an iPhone to be more *real* than an operating system. Unfortunately, then, a lot of excited small business owners still make decisions based off of subjective, non-truths about the marketplace.

The same kind of thing applies consumer-side, too (and remember, SMB owners are consumers). For most people (and obviously a lot of people are different), phones are just phones. The average consumer probably doesn't get excited about the new version of Android, so much as they might get excited about the new phone. But people *do* get excited about the new iPhone. That leads to an overall consensus that iPhones are more popular, even though people who recognize a phone for its firmware might see a different picture.

**Coolness**

I suspect, similarly, a lot of SMB owners and consumers consider the iPhone to just be a cooler device, regardless of market share. Having an app in the store has become a social necessity for a lot of companies, and I think that plays into it. Much of Apple's success can be traced back to people who think their products are just cooler than their nerdy equivalents in Android, or even PCs. Some of that is beginning to shift, but there are still legacy thoughts in play that sway the decision-makers at small businesses.




## Answer 841

- posted by: [Community](https://stackexchange.com/users/-1/community) on 2014-09-29
- score: 0

One word: Xamarin

Its awesome (I do love Microsoft though, so I do have some bias).

Develop once for all platforms. Why limit yourself :)

As Matthew says the coolness factor seems to play into launching on iOS first. Android is where the market share is, even on higher end phones. As mentioned in the stats by blunders, the 1/3 of Android phones that aren't junk phones is still on its own, higher than the entire Apple market.




## Answer 3967

- posted by: [Elder Smash](https://stackexchange.com/users/3962865/elder-smash) on 2015-04-07
- score: 0

Develop for both. Release at the same time unless you see the value in soft launching to a small region on the Play Store.

For cross-platform development don't forget about Anywhere Software and their Basic4android / Basic4iOS. People who are comfortable with classic Visual Basic can jump right into making modern apps once they learn the API. It's the right fit for some people (as funny as that sounds).

Edit:

Meteor is a solid answer for most modern apps. Looking back it was the correct way to go. Nowadays it's very easy to prototype apps quickly in HTML/CSS/JS and deploy them as native mobile apps when you use Meteor. Have a look see: https://www.meteor.com/tutorials/blaze/running-on-mobile


## Answer 9275

- posted by: [davidtaubmann](https://stackexchange.com/users/2167306/davidtaubmann) on 2016-05-20
- score: 0

<h2>ALTERNATIVE</h2>

<p>I would choose... NONE of them... my option for many years has been WEB APPs (at least just as a first phase/stage) and now they are PROGRESSIVE...</p>

<p><strong>Why?</strong> If you build a PWA (Progressive Web App), you are solving ALL devices, and unless you require access to a special technology that is only accesible through native apps, then your best first step would be PWA (Progressive Web Apps)</p>

<p><strong>What are PWAs</strong>? <strong>Progressive Web Apps</strong> Is a concept being pushed forward strongly by Google and many Web oriented developers who understand that in the end standards are for sake of almost everything in technology (efficiency in time, economics, storage, memory, space, processing, battery, etc). They ara basically the next step of the web (<strong>web 3.0</strong> maybe?). There's lots more info out there, but I'll resume:</p>

<p>On this path... traditional web "sites" are nowadays responsive, since many years can be put on homescreen like native apps and already interact with the server without loading the entire page (possible since AJAX, HTML5 and CSS3 which are the base of web 2.0, together with some other specs from Android and iOS). 
Rather than that... PWA's can now really compare to native apps because of technologies like push notifications, effortless realtime-data interaction, offline availability, amazing lower times of loading from the 2nd visit and forth, easily synchronizable client-side storage, safe (absolute HTTPS is a base requirement), access to hardware (camera, GPS, accelerometer, etc), access to other devices (bluetooth is on tests, usb are under development), and many more things under development thanks to the cross-platform/browser junction over web standars...</p>

<p>As you can see, this <strong>covers ALL devices</strong>, and MOST needs of apps, and in the near future it's focusing to cover ALL needs. For me the Internet (as I now call it web 3.0) should be the real path and recover the place that Apps have taken, as it has been built upon world standards in which experts have agreed over decades already as a world-wide team (W3 + Companies + Developers + +).</p>

<p>Hopefully the Internet works as the biggest example of all, and more things become done this way in humanity (Democratically with Meritocracy and Active Participation).</p>

<p>If you haven't been <strong>up-to-date on tech news</strong>, you should check out the 2016 Google IO which is ongoing right now (last day of three), and it's videos will be available here: <a href="http://events.google.com/io2016/" rel="nofollow">events.google.com/io2016/</a>
They are really promoting a lot the PWA's, Android and iOS apps easy development using their new <a href="http://firebase.google.com" rel="nofollow">Firebase</a> (which really is great because it covers your server-side/backend needs, letting you focus on the real matter).</p>

<p>Finally, I would add an <strong>option</strong>... If you have spent a considerable amount of time already developing your app, maybe you should better finish it, moreover if it is on Android (which is indeed a good path as it is the most used mobile OS), and once finished with crashes and bugs repairings, you should consider re-developing it over Firebase or some similar Backend solution, and this way much of it can be easily built to support the 3 environments (web, iOS &amp; Android).</p>

<p>Somebody told me on wednesday... "[Nowadays,] <strong>There's no wrong answer</strong> [when choosing the first path for a mobile development]."</p>



## Answer 9291

- posted by: [Dr. Rhino](https://stackexchange.com/users/2373456/dr-rhino) on 2016-05-22
- score: 0

<p>As a serial Software Entrepreneur, I would like to add my 5 cents to the non-technology based group of answers - meaning: if you cannot go both ways, which one is supposed to be first.</p>

<p>In Layman's terms: whatever the number of total devices distributed are, what matters most is where the store revenue is the biggest and this seems to be the AppStore so far - at least in the majority of countries.</p>

<p>Apple sometimes discloses numbers but it sort of faded a bit in the last year or so. However, there are still plenty of market research firms or journalists around that can provide more or less accurate (and reliable) numbers about the revenue made from apps in this particular app store. </p>

News

<ul>
<li><a href="http://venturebeat.com/2016/01/20/app-annie-2015-google-play-saw-100-more-downloads-than-the-ios-app-store-but-apple-generated-75-more-revenue/" rel="nofollow">9ti5mac2016</a></li>
<li><a href="http://appleinsider.com/articles/16/01/20/apple-increases-ios-app-store-revenue-lead-now-earns-75-more-than-androids-google-play-" rel="nofollow">AppleInsider2016</a></li>
<li><a href="http://www.forbes.com/sites/dougolenick/2015/05/27/apple-ios-and-google-android-smartphone-market-share-flattening-idc/#a1bfd1c2d4e6" rel="nofollow">Forbes2015</a></li>
</ul>

Research

<ul>
<li><a href="http://www.statista.com/statistics/283753/apple-app-store-global-category-revenue-share-per-business-model/" rel="nofollow">Statista2014</a> (hover over the categories to see the breakdown, i.e. Food&amp;Drinks paid apps (55%), paid apps with inApp purchase (3.7%), free apps with inApp purchase (41.3%) ... the numbers vary a lot by category e.g. Games: 6.1/2/92</li>
<li><a href="http://blogs.forrester.com/thomas_husson/15-01-30-five_myths_about_mobile_apps" rel="nofollow">Forrester2015</a></li>
</ul>

<p>I just referenced some articles freely available for anybody. I believe, that your business plan - as long as the revenue is > $1M planned revenue for the 3rd year from now or so - is supposed to be based on high quality research that you need to purchase from Forrester or alike. Also make sure that you find a research report or study that is not too dated (or subscribe to a membership with Statista or alike) and base your CEO's or CFO's chain of argumentation on this research, especially when you are VC funded.</p>

<p>For me - careful this is a bit opinionated - the difference is more the business model you are on. I think that there is no doubt that Google dominates the online advertisement market. Therefore, apps paid through advertisements are probably very well positioned in the Android/Google Play world. I admit that there are quite a number of advertisement-dependent apps in Apple's app store as well. What I think is crucial is how much people are willing to pay for not being bothered by advertisements along the way of using an app. I think in this way, the readiness to even consider paying directly for software or a service provided through software is the key and should be paramount (if your tech staff tells you that you have to pick one first) for your decision. In the North American and most European Markets the answer is clearly leaning towards Apple's AppStore in that concern. And: mind the specialties of your local market if you are not planning on a global rollout from the get-go.</p>

<p>One last word toward doing both (now more thinking as a Software Engineer): there are quite some development techniques out there nowadays that can enable you to do both in the way that all or part of the investment in code, written for your app can be initially written for one platform and with a little extra effort be re-used in any other. <code>Xamarin</code> was mentioned already and has quite a history by now. Another one is <code>Apache Cordova</code>. Never underestimate the power of having the right team of in-house or contracted software developers that you can bind to your business idea for a long enough period of time that you as a CEO/founder/entrepreneur need to elaborate your businesses' USPs and the customer base. Hear them out first - maybe they are opinionated towards their favorite approach and ready to fight for their technology. A team like this can move mountains - just what you need, right?</p>

<p>Good luck!</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
