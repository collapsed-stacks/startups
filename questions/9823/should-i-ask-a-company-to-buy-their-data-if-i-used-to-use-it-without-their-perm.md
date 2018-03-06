## Should I ask a company to buy their data, if I used to use it without their permission?

- posted by: [Ooker](https://stackexchange.com/users/3908836/ooker) on 2016-07-31
- tagged: `legal`, `intellectual-property`, `copyright`, `data`, `negotiation`
- score: 1

A year ago I made a project for free, using the data from a company without permission. The data is published to the internet widely, but since all of the page using them is not commercial, so I guess it's not worth for them to follow the cases. At that time, I wasn't really aware of copyright or the company's services, and I would consider that I used the data with fair use.

I consider that my first project is successful, and I want to make a paid one based on it. I think I should buy their data. However, I'm afraid that if I contact them, they will sue me for using their data without permission before. And more importantly, both of my project essentially compete their services.

Should I contact them?


## Answer 9824

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2016-07-31
- score: 2

TL;DR: no, don't reach out to your data source before a pre-flight check with an attorney. If you're this nervous about them chewing your bottom should you merely reach out to them, there's a good chance it's for valid reasons in a ["I know it when I see it"](https://en.wikipedia.org/wiki/I_know_it_when_I_see_it) kind of way.

---

First off a disclaimer: I work for Scrapinghub, which helps businesses scrape web content. We periodically get questions from clients that revolve around topics similar to what is worrying you.

The short answer is: it depends on how you use the data and on the laws from where you're based. IANAL so really you'll be better off asking a lawyer who is familiar with this topic to make sure.

At a high level, you don't technically own the data, so you need to stay within the boundaries of fair use. The legal environment is very dynamic and the limits of fair use itself are constantly being [battled in court](http://www.reuters.com/article/us-google-media-germany-idUSKCN0SL2TI20151027).

Using scraped data is legit and useful for a wide range of activities. Google, for one, would not be able to let you search the internet without scraping it. But that's only the surface. Among the plethora of other use cases we encounter, there are price comparison apps of course, but also competitor or reseller monitoring apps, marketing or consumer analytics apps, data augmentation apps, businesses scraping small amounts of data behind a login on a daily basis to automate a data entry assistant's job (e.g. new court rulings), [watchdog groups that scrape government data](https://blog.scrapinghub.com/2016/07/13/improving-access-to-peruvian-congress-bills-with-scrapy/) to surface corruption, national statistics agencies scraping prices on e-commerce sites to automate calculating consumer price indexes, and even law enforcement agencies [monitoring the dark web](http://www.darpa.mil/program/memex) for criminal activities. Pretty much everyone is doing it.

Legit scraping use cases tend to have this much in common though: they slice and dice, augment, filter, and otherwise process the data, rather than serve it raw, as is. In this sense app authors can all put forward that they're providing a service, which is collecting the data, and then providing some analysis and conclusions based on it or otherwise adding value by augmenting it. (In some sense you can think of it as an attorney giving you legal advice. The attorney doesn't technically own the factual advice and it doesn't matter that they don't. What they do is package it up, provide you access to it, and add value by helping you make decisions.)

In your case, I'd gather your data source will have a thing or two to say in court - to put it mildly - if you're competing against them using data that is a) collected from their own site and b) served essentially as is on yours. If that doesn't more or less describe what you're up to, then the right thing to do is to double-check with a lawyer for proper legal advice. And _then_ reach out to your data source if appropriate and applicable.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
