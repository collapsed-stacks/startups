## How do Evernote (and others) achieve their pricing model while on multiple platforms?

- posted by: [Robert Byrne](https://stackexchange.com/users/5232876/robert-byrne) on 2015-11-18
- tagged: `mobile-apps`, `business-model`, `lean-startup`
- score: 2

<p>Companies like Evernote, any.do, Slack etc. Achieve a monthly/yearly subscription pricing model when they are apps on many platforms that all (most) take a cut of profits.</p>

<p>iOS and Android both take 30% of app sales, and even if you gave the app away for free I cannot see apple being easy to get along with if you were cutting them out of their usual piece of the pie...</p>

<p>So do they just give up the %30 + %30 of premium subscription sales? or is there something in there that I am missing?</p>

<p>Is this something that is acceptable for apple, or would they fight it? Are they able to charge like this because they have a user base and the have leverage of having a product that apple users want?</p>

<p>Anyway, Thanks for having a look at this question, I look forward to the dialog....</p>

<p>-RB</p>



## Answer 7887

- posted by: [Robert Byrne](https://stackexchange.com/users/5232876/robert-byrne) on 2015-11-19
- score: 1

<p>I have found what I think the be a clear (as mud?) answer to the question that I asked above. After giving this some though on this topic has sparked an idea of how to mitigate this problem.</p>

<p>I gathered 3 things from my research...</p>

<ol>
<li>They will <em>not stop</em> you from letting your users subscribe <em>outside</em> of your mobile app.</li>
</ol>

<p>But...</p>

<ol start="2">
<li>They will <em>not allow</em> your app to lead your users to any external link to subscribe.</li>
</ol>

<p>and...</p>

<ol start="3">
<li>You <strong>MUST</strong> also offer the same subscription through IAP</li>
</ol>

<p>Sources:</p>

<p>I had a look at Apple's App Store Review Guidelines (Section 11: purchasing and currencies</p>

<p><a href="https://developer.apple.com/app-store/review/guidelines/#purchasing-currencies" rel="nofollow">https://developer.apple.com/app-store/review/guidelines/#purchasing-currencies</a></p>

<p>and it reads...</p>

<p>11.12 </p>

<blockquote>
  <p><strong>Apps offering subscriptions must do so using IAP</strong>, Apple will  share the same 70/30 revenue split with developers for these purchases, as set forth in the Program License Agreement</p>
</blockquote>

<p>11.13   </p>

<blockquote>
  <p><strong>Apps that link to external mechanisms for purchases or
  subscriptions</strong> to be used in the App, such as a "buy" button that
  goes to a web site to purchase a digital book, <strong>will be rejected</strong></p>
</blockquote>

<p>11.14  </p>

<blockquote>
  <p><strong>Apps can read or play approved content</strong> (specifically magazines, newspapers, books, audio, music, video and cloud storage) that is <strong>subscribed to or purchased outside of the App</strong>, as long as there is <em>no button or external link in the App</em> to purchase the approved content. Apple will only receive a portion of revenues for content purchased inside the App</p>
</blockquote>

<p>11.15  </p>

<blockquote>
  <p>Apps may only use auto-renewing subscriptions for periodicals (newspapers, magazines), business Apps (enterprise, productivity, professional creative, cloud storage), and media Apps (video, audio, voice), or the App will be rejected</p>
</blockquote>

<p>Thanks for having a look at my question. Feel free to chime in if you have some first hand experience with this type of situation.</p>

<p>-RB</p>



## Answer 7881

- posted by: [Tom](https://stackexchange.com/users/1841165/tom) on 2015-11-18
- score: 0

<p>I believe they distribute only free app on those market places. You can buy premium service from their own website, which will open up new features on your free app as well. This way they don't have to deal with market place comissions.</p>



## Answer 7901

- posted by: [Luke Gedeon](https://stackexchange.com/users/1119600/luke-gedeon) on 2015-11-20
- score: 0

<p>I haven't tested trying to subscribe to a service after getting the app. I always signed up and then downloaded, but most of the services offer a free app and a free account to start out with. Then if you want premium options, it would be simple enough for them to redirect you to the site to view the pricing page and do any transaction.</p>

<p>I wouldn't even advertise premium features from inside the app, honestly. Keep the app simple. Send them to the web for account settings and such. No need to build that interface twice when it doesn't get used as much as the main functionality.</p>

<p>In answer to 11.13 - you are not linking to a purchase option, you are linking to settings and information pages. Even if that info is about pricing. :)</p>

<p>11.14 - does not prohibit this because you are not linking to a purchase of content. Actually content is a key word in several points. If it a service and not content or a physical product you are clear all the way.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
