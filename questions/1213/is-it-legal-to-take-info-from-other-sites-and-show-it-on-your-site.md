## Is it legal to take info from other sites and show it on your site?

- posted by: [Cliff](https://stackexchange.com/users/5255187/cliff) on 2014-10-30
- tagged: `legal`, `intellectual-property`, `web-development`
- score: 5

I want to start a property search website.

But the problem is I don't have  information to show on the website. So I was thinking of getting this info via scanning other sites and showing it on my site. But I will show  the guest where this information has come from and when they want to inquire I will redirect to  the source site.

I seen other sites like hotelscombined.com do this. But is this legal?






## Answer 1219

- posted by: [Jared Wadsworth](https://stackexchange.com/users/5056044/jared-wadsworth) on 2014-10-30
- score: 4

<p>That is an excellent question and one that has been debated in recent years. Surprising enough, wikipedia has a great article on the legality of web scraping <a href="http://en.wikipedia.org/wiki/Web_scraping#Legal_issues" rel="nofollow">here</a>. It's quite enlightening, and I would definitely recommend you read it before you go on. </p>

<p>There have been quite a few cases recently over web scraping incidents. None of them, however have been able to set a precedence, and the results have been varied. There is a case that as of today is still undecided, which is that of Craigslist vs 3Taps. Basically 3Taps was scrapping info from Craigslist to place on their site. Craigslist sent them a cease and desist letter, and later blocked their IP. This didn't deter 3Taps, and they went around the block. Craigslist sued, and 3Taps made an argument for dismissal based on the fact that it was publicly accessible data. The court however ruled against the dismissal stating that the letter and block were sufficient notice to 3Taps that they (specifically) were not authorized.</p>

<p>Now thats just a lot of legal mumbo jumbo. Based on what I've seen here, and in other places (I've had this same question for a long time as I have a crawler and wanted to make sure I was protected), theres a few things you need to watch out for when scraping.</p>

<ol>
<li><p><strong>Robots.txt</strong></p>

<p>There is often a robots.txt file on servers stating what crawlers / scrapers can and cannot do. Be sure to have your scraper parse this file, and check what is ok to do on that particular site. Remember also that the file is subject to change at any time, and you are responsible to follow the changes. Be sure to parse it again every so often</p></li>
<li><p><strong>Terms of use</strong></p>

<p>Another thing to keep in mind is the terms of use on sites. If you're going to be scraping major sites, you may have to do some manual labor and read their terms of use which may specify what you are allowed to use on your scraper.</p></li>
<li><p><strong>Consider damage to the site</strong></p>

<p>Most sites only care that you're scrapping because it harms their site. Make sure you are not drawing business away from sites, otherwise you could upset them, and cause them to come after you. Even if you win, it could put you out of business, and cost lots of money.</p></li>
</ol>

<p>That being said, you are very much in a legal grey area. As stated on wikipedia</p>

<blockquote>
  <p>The degree of protection for such content is not settled</p>
</blockquote>

<p>Just don't do anything stupid and you should be fine, and if they ask you to stop, do it.</p>



## Answer 1249

- posted by: [Jeremy Parsons](https://stackexchange.com/users/497810/jeremy-parsons) on 2014-11-03
- score: 1

You're worrying about the wrong question.

If you're successful, then you probably *either* expect that you're all about acquiring content without those sites, *or* that you're going to be aggregating content forever and adding value in some useful way.

In the first case, a lot of growth hackers would suggest that you do whatever it takes to get initial content so you can press on to validation. The measure is going to be about content you acquire directly, and if you don't see a path emerge then you'll need to pivot.

Some startups do this under a private beta or in complete stealth mode, only exposing their service under NDAs. That can work well if you have a team that looks highly investable, or if you're pitching your service to realtors say, so that you're using the scraped content for demo purposes. But if it's consumers you need to validate with, the longer you delay engaging with a big market, the lower your chances.

In the second case, you will more likely want to keep as much as possible of what you're doing inside the Ts & Cs (making use of APIs and affiliate schemes wherever you can), because it's the value you're adding on top that you need to validate.

So think about the long term, look at what you need to validate, and then worry about how the tactics of getting started could play out when you start to be successful enough to annoy someone.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
