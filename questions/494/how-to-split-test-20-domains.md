## How to split-test 20+ domains?

- posted by: [Richard Watson](https://stackexchange.com/users/29057/richard-watson) on 2014-08-26
- tagged: `testing`
- score: 2

I've accumulated over 20 possible domains for one project. I'd like to use Adwords to push a bunch of traffic at them to see which sticks.

I assume I have to point all of the domains at one solution and I have to tell the solution to accept each of them. I have to write a bunch of copy to test with. I have to set up a bunch of ad groups, each of which will push at one domain. I assume I should tell Google not to crawl each of the sites, so there's no dupe hit.

Is there a service that makes this easy? Should I just hire a VA to do it? Roll my own site or use one of unbounce/launchrock etc? (Who seems to specialise in on-page optimization, not necessarily domain testing). Is there a way to stop Google penalising me for duplicate content?


## Answer 498

- posted by: [DataSmarter](https://stackexchange.com/users/3128474/datasmarter) on 2014-08-26
- score: 6

Do you want to test the same content (also the same logo, same graphics,...) on different domains or do you need to change the content as well (e.g. logo and metadata that "stick" to the domain name?

**If it is exactly the same content, to make a redirection of you domains is not so difficult.** E.g.: your advertising points to "www.test1.com", user clicks on it, arrives on "www.test1.com" an is immediately (he even doesn't see it) redirected to "www.test-general-solution.com". The same for "www.test2.com",... In that case, there is no "duplicate content" (the content is only on "www.test-general-solution.com") and thus you don't need to worry about google.

This is often used when companies have several domains that point to the main one. The reason can be a) avoiding mistyped domain names, b) several products or company parts pointing to the main site (e.g. "www.ABC-group.com" and "www.abc-holding.com" pointing to "www.abc.com") or even c) the national domains pointing to the "global one" (e.g. www.mycompany.fr pointing to www.mycompany.com/fr)

**If you need to adapt the content based on the domain name**, it will be more work (then indeed, a VA can be useful) and you will have to pay attention to Google. You can do that in the "Google Webmaster Tools" tool and/or via the "robot.txt" (just google this expressions to see how it works).

But still, at your place, **I would first do some "human" testing** - ask the opinion of your family, your friends, your colleagues,...** And try to decrease the number of the potential domain names that you will test to 3-5.** Otherwise, it will be quite hard to manage it in a proper way. And pay AdSense for 5 websites will be much cheaper than for 20...



Concerning Google, add each of your domains to the "Webmaster Tools" tool where you can easily manage the rules of the access of the Google's spider to each of y


## Answer 501

- posted by: [JezC](https://stackexchange.com/users/87431/jezc) on 2014-08-26
- score: 4

<p>There is no duplicate penalty. There is a reduction of rank between the websites as Google shares the value between them, if you are seen as playing games. It's not so much a penalty as a self inflicted wound. You can fix it. You use the Canonical Link Reference to tell Google which is your preferred domain, and on all the other domains, you tell the web spiders that you want "NOINDEX,NOFOLLOW" - so you're not seen as trying to influence ranking signals by creating a "Small World".</p>

<p>There may be an issue with Google AdWords - different websites promoted by the same organisation should have different offers. You might well run into AdWords problems with making the same offer on different websites. Part of the <a href="https://support.google.com/adwordspolicy/answer/2600168?hl=en-GB" rel="nofollow">Double Serving Policy</a>. Make certain that you use one AdWords account - Double Serving is a way to get a fast permanent suspension. </p>

<p>Personally... I wouldn't do this. It's a lot of effort. The domain does have an impact, especially if branding is involved. If branding is not involved, then advert contents will outweigh the domain (domains are only 35 characters, you have another 95 characters, not in green, one of which has 25 characters in a bolder enlarged font) to make an impact in AdWords. Chances are, you can use the Folder/directory path of the Display URL to carry the weight you're currently placing entirely on the domain. Unless... you can't find a domain that keeps you under the 35 character limit. :)</p>

<p>The main reason that I wouldn't do it, is that you're probably trying to build a business. If you split test across 20 websites, you take approximately 20 times as long to gather enough data to decide that one domain name is better than another. But the likely difference in click through rate and conversion rate is... what? 10%? Chances are you'll have far more impact tuning the adverts and the landing page, than the domain. That's a lot of testing time and exposing searchers to suboptimal adverts for a small improvement. LP improvement might yield a several hundred percent improvement in less time.</p>

<p>Back when Skype was young, I was helping them with landing page optimisation for a business offer. The first iteration, we increased the "second click rate" - taking users further into the website - by 800%. The second iteration was another 600% improvement on the previous rate. You probably won't get that with domain names. Landing pages dominate conversion rates and bounce rates, usually. And Click Through Rates dominate Quality Score. The optimum point is usually a high CTR advert and a high converting LP. And the domain is 35 characters at most of a 130 controllable character advert, with the possibility of using the path in the Display URL, and it is de-emphasised in search results over the Title and Description. Unless you have some real evidence that it is important (for example, how you're embedding a brand name), then... focus on something else and worry about this later, when you're trying to find single digit improvements. By then, you'll know what key words people use and what titles and ad copy they respond to. Better place to start domain name testing. :)</p>

<p>Focus on the user, all else will follow. (<a href="https://www.google.co.uk/about/company/philosophy/" rel="nofollow">Google's Ten Things, Number 1 rule</a>).</p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
