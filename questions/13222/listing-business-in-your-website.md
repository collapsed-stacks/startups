## Listing business in your website

- posted by: [jay](https://stackexchange.com/users/2117126/jay) on 2017-08-23
- tagged: `legal`, `tech-company`, `australia`
- score: 1

<p>I would like to create a website in Australia. Not sure about the legality of it. Basically I would like to create something like Gmap or open street map. I would like to create a filter and list of business on the map. Do I need a permission from each business owner for me to list their business on the map? How about open street? They have businesses listed on their map, do they get permission from each owner? Is it legal for them to do so?</p>

<p>I also just found out that one of my relatives got his business listed in zomato and tripadvisor. he mentioned that he never put his business on those website. So anyone has any feedback on it? Thanks</p>



## Answer 13223

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2017-08-24
- score: 1

<p>Short answer: it's... somewhat murky, or can be... but probably safe to just go ahead.</p>

<p>Longer answer:</p>

<p>A lot of this information is publicly available, for instance on Yellow Pages sites, Google Maps, and a slew of others. Having worked in web scraping, I'd put forward that these public sources are mostly scraped or purchased data, and there are a handful of data brokers working behind the scenes with mind boggling amounts of (scraped or purchased) company data, and a few others working on scraped company websites (rather than scraped or purchased listings) as primary sources. Point is, assume it's scraped unless you're demonstrated otherwise, and don't take "we bought it from X so we're fine" at face value because it was likely scraped a few layers underneath.</p>

<p>With this in mind, part of the actual answer would depend on how you obtain your data and how your local laws view scraped data in case scraping or purchasing data is on your radar. If so ask a local lawyer for a whirlwind tour of the situation in your country. (Hint: scraping is in a gray zone in all countries, and there was a very recent and <a href="http://www.chicagotribune.com/bluesky/technology/ct-linkedin-profiles-court-20170815-story.html" rel="nofollow noreferrer">very interesting US ruling</a> against LinkedIn - that will get appealed if it hasn't been already - whereby LinkedIn must basically disable counter-measures on their site so other companies can scrape publicly available information on it.) This hopefully gives enough pointers on whether you're even allowed to own the data and making it public, in the event you're not crowdsourcing the dataset yourself.</p>

<p>The other issue is usage of the data itself, with two associated problems: privacy and a vortex of other issues that revolves around libel and extortion. Some countries, like Germany, have stricter privacy rules; others may enforce stricter rules in the future. For this you'll likely get a straight answer from a local lawyer, and they'll let you in on whether you need to ask for permission as a bonus. (Hint: it's very unlikely). The other problem is murkier, and best made cognizant with what Yelp does. Its business model is extortion for all practical intents. You're listed whether you like it or not, you can't get de-listed, and you've the possibility to pay to promote yourself - prompting some businesses to <a href="http://www.adweek.com/creativity/restaurant-wants-be-worst-rated-yelp-and-reviews-are-indeed-hilarious-160299/" rel="nofollow noreferrer">ask their clients to give 1-star reviews</a> in retaliation. The related US lawsuits are, insofar as I'm aware, still ongoing. In the EU there's a shortcut: the right to be forgotten.</p>

<p>Bottomline: Scraped data will probably be your main data source, and it's probably safe to use it - everyone does including Google, the world's biggest web scraping business - but stay up to date on legal development as it may potentially change overnight. Be wary of privacy laws in your country and how they evolve. If you throw in any kind of reviews, consider allowing businesses to opt out to avoid getting lawsuits for extortion. And absolutely get a competent lawyer.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
