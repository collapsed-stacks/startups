## A startup that violates Google terms of service

- posted by: [Clarendon](https://stackexchange.com/users/8465544/clarendon) on 2016-05-18
- tagged: `legal`, `business-model`
- score: 3

I am developing a software that uses Google search but accesses it in a way that violates its terms of service. I have done an extensive research and test to confirm its user value. I believe in it with all my heart and have invested years of my life into it.

My plan is to launch it regardless and prove its value. When it gets big enough to be noticed by Google, they will raise issues but will see the value at the same time. Then we can talk business and they may be able to change their terms or buy the startup and make it part of their own operation. 

Is this a viable business model ? <br />
Will any incubator accept me if they know about the violation ?  <br />
Does anyone know a similar case that has been successful ?  <br />


## Answer 9254

- posted by: [Jim](https://stackexchange.com/users/351236/jim) on 2016-05-19
- score: 2

> Is this a viable business model ?

A startup like this carries risks much higher than most startups, and most startups fail. That makes your model less attractive.

> Will any incubator accept me if they know about the violation ?

Incubator all have different rules. You don't want to violate their TOS or other agreements, so you should ask if they monitor or care about known TOS violations for large companies. If they do, you probably want to end the conversation there.

> Does anyone know a similar case that has been successful ?

I'm not familiar with any successes (only failures - and some that tried ideas that sound similar to yours). Google makes it a habit of buying companies that innovate. Google also changes policies on a regular basis. Generally, Google makes their policies more restrictive, not less restrictive. You might get lucky, and "win the fight" but if you are really convinced of user value of your approach, it's possible Google will listen. They do have a venture capital group (http://www.gv.com/) - maybe you can just go straight to them with your pitch. Otherwise, simply put, the odds are very much stacked against you.




## Answer 9250

- posted by: [Community](https://stackexchange.com/users/-1/community) on 2016-05-19
- score: 0

As LokiAstari stated in the question comments and as I can verify from personal experience, Google may hit your users with [captcha](https://www.google.com/recaptcha/intro/index.html)s if they figure out what you're doing and don't like it. If you're automatically scraping results, the user of your software will get no results back. You might try to integrate the captcha into your software (which is easier said than done) and let the user complete it.

If you want to see how Google does captchas, try to launch a virtual machine at a popular VPS provider and use it as a proxy to search Google.

Keep in mind also, captcha technology is quite sophisticated now -- not the simple "retype these letters from this image" stuff from ten years ago.

I don't advise going to war with Google in any way. Even if you outsmart their engineers, their lawyers can destroy you with just the threat of legal action (unless your prepared to risk millions in litigation costs).

And of course, Google is big and probably not particularly approachable as far as I know. (They probably get so many requests that they have to be cautious.) But that does not mean you can't try to find someone who might be willing to hear you out. You can use tools like [NDA](https://en.wikipedia.org/wiki/Non-disclosure_agreement)s to protect yourself if this approach works out.

All that being said, you're not the first one to use Google's search results without asking. [Bing has done it](https://googleblog.blogspot.com/2011/02/microsofts-bing-uses-google-search.html). Others have done it as well (which is probably why any public VPS service I use as a proxy requires a captcha on each search). I think the key is to look as natural as possible to Google with non-data-center IP addresses and queries that look like they are coming from a popular web browser on a popular operating system at a limited pace. Caching results could slow searches down as well. Of course, I don't know much about the nature of your software or how much of this is applicable.

If you feel (as you stated in the comments) that your software is revolutionary enough to be successfully patented and you are worried about losing your idea, the patent route may be a good way to go before approaching Google. A patent is public information so anyone an see it (but not use it). Having a patent might give you something of value with which to approach Google or might even spark their interests in working with you.

**The nature of what we're discussing here is by definition a [long-shot](http://www.dictionary.com/browse/long-shot), so proceed at your own risk.**



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
