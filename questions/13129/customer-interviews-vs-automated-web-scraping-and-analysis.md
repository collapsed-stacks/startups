## customer interviews vs automated web-scraping and analysis

- posted by: [alpha_989](https://stackexchange.com/users/6090175/alpha-989) on 2017-08-05
- tagged: `lean-startup`, `customer-development`
- score: 4

<p>Customer interviews are expensive to conduct in terms of time and money. Say you want to know what is the most popular method for web-scraping or data-retreival in artificial intelligence. You could ask an expert in this        matter, but getting to that expert would be a lot of work. There are currently a lot of well-developed tools for web-scraping and automated textual analysis such as Scrapy, BeautifulSoup, NLTK etc.</p>

<p>If you are a programmer and can relatively easily build automated scripts to build programs which can give you a quantitative answer to such questions, (which cant always be found by Googling), why not build such automated scripts instead of doing customer interviews?</p>

<p>How do you guys decide when to do customer interviews to answer questions that may arise when you are building products vs doing some automated data mining on the web?</p>



## Answer 13130

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2017-08-06
- score: 3

<blockquote>
  <p>If you are a programmer and can relatively easily build automated scripts to build programs which can give you a quantitative answer to such questions, (which cant always be found by Googling), why not build such automated scripts instead of doing customer interviews?</p>
</blockquote>

<p>I'd put three reasons forward (by no means an exhaustive list):</p>

<ul>
<li><p>Automated data collection sometimes is much more complex or expensive than it looks at first glance. Particularly web scraping, owing to the scores of bot countermeasures in the wild.</p></li>
<li><p>Sticking to quantitative data only can lead you to <a href="https://www.ted.com/talks/tricia_wang_the_human_insights_missing_from_big_data" rel="nofollow noreferrer">miss the forest behind the tree</a>.</p></li>
<li><p>If you measure a large number of things, you're almost guaranteed to get a "statistically significant" finding regardless of reality, as illustrated by the <a href="https://io9.gizmodo.com/i-fooled-millions-into-thinking-chocolate-helps-weight-1707251800" rel="nofollow noreferrer">chocolate weight loss hoax</a>.</p></li>
</ul>

<p>Product management offers an example of the dangers of using quantitative findings without doing qualitative interviews. If you stick to using stats and analytics on how users use your product, you may end up concluding that you're meeting what you thought your users' requirements were, when in reality your users are all bitching about the convoluted workflow you're imposing them - and the missing functionality that you're not aware of - when they're solving their actual problem. For instance, regular usage of log viewers that are scattered all over the place might be hiding the fact that your product is doing a pathetic job at helping your users troubleshoot whatever your product allows them to do.</p>

<blockquote>
  <p>How do you guys decide when to do customer interviews to answer questions that may arise when you are building products vs doing some automated data mining on the web?</p>
</blockquote>

<p>You'll get different opinions depending on who you ask. Personally, I view quantitative data as mostly worthless without qualitative context:</p>

<ul>
<li>You're usually better off starting with qualitative data, and then using quantitative data to get a sense of how you're progressing towards the goals you've come up with.</li>
<li>In cases where quantitative data allow you to infer a few hypothesis, it's best practice to then go out in the field and validate if those hypothesis make sense (and then returning back to quantitative data to track progress).</li>
</ul>

<p>As an aside, qualitative studies need not be large scale. Key findings will usually surface after a half dozen well conducted interviews - they'll be the ones most or all of your interviewees will have complained about. Focus on those, solve them, then rinse and repeat with a new batch of users.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
