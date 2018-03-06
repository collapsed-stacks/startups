## Building Skyscanner clone

- posted by: [katch](https://stackexchange.com/users/3215440/katch) on 2015-08-27
- tagged: `tech-company`, `business-model`, `strategy`
- score: 2

I am interested in building a service which can be remotely compared to Skyscanner. I would like to understand following things --

a) Considering calling every hotel or car hiring company to join their network is very expensive and non scalable how does Skyscanner manage to build their inventory?

b) How does Skyscanner ensure their inventory data is not stale(some listed hotels may not be in business or might have already booked all rooms) or how does Skyscanner and their partners remain in sync

c) How does Skyscanner make money?


## Answer 6199

- posted by: [Mruf](https://stackexchange.com/users/3246202/mruf) on 2015-08-27
- score: 1

<p>a) I think, there are data providers or APIs, which make i quite easy to gather data and reorganize them for your users. You just "request" information, filter it, so it matches your sponsors or what ever you want to do with that data.</p>

<p>Maybe there is an interesting one in this <a href="http://www.programmableweb.com/news/5-travel-apis-comparison-to-booking/2007/10/29" rel="nofollow">article</a> (If not google for flight API or something similar)</p>

<p>b) Because they "steal" it from an API, but "steal" is the wrong word, since it is offered by thous companies you want to compare. There is no need to steal or to sync it. If you watch closely, they even don't host the data. On a search (and a few clicks) it tells you, which APIs he searches through. (exp: seat24, thomas cook etc.)</p>

<p>c) Basically by commission or affiliate. Depending on the model, skyscanner gets a fixed amount + a percentage of the overall value. So, with thomas cook for example you get 6€ - 85€ per Lead (a person, which visits the site and may registers) and 2,5% - 4% of every buy this person does within a time frame (maybe a month)</p>

<p>Bonus:
d) So why does not everyone start such a business? Because they are very expensive to promote, the market is more or less satisfied and you have very strong competitors... Good Luck!</p>

<p>Bonus: e) Should I still do it? Well if you have a nice idea, to position your self, of course: Do it. But if you just want to clone Skyscanner... I would really think about your idea and/or consider some alternatives</p>



## Answer 11510

- posted by: [Sam](https://stackexchange.com/users/9611717/sam) on 2016-11-09
- score: 1

This is the core team who developed skyscanner. Just check their home page for the story. They used web scrapping to fetch data on a real time basis from different sites.
http://orderofcode.com/portfolios/web-scraping/


## Answer 6200

- posted by: [zazaalaza](https://stackexchange.com/users/4672194/zazaalaza) on 2015-08-27
- score: 0

<p>Skyscanner doesn't need to call any hotels. They just need to aggregate all the possible offers from the internet and they present you with the best possible option which redirects to the source website. Because most of the places they aggregate from are also search engines, they are a metasearch engine.</p>

<p>They probably index only trusted sites to make sure that the listings are always accurate. Those partners probably use tools like <a href="http://totalstaygroup.com/brands-and-solutions/" rel="nofollow">this</a> to check and confirm bookings instantly and to ensure that rooms are available.</p>

<p>Among others they make money through performance based commissions which means that other platforms pay them for the users they bring to their websites. <a href="http://www.fubra.com/about/advertising-lead-solutions/skyscanner-case-study/" rel="nofollow">Source</a>.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
