## Is it better to tailor my website to users based on their country or region?

- posted by: [Jeff Caros](https://stackexchange.com/users/5742094/jeff-caros) on 2015-11-21
- tagged: `website`, `international`
- score: 1

I have an entertainment website that is based on pop culture. I want users from across the world to be able to register, but I have to provide them a list of options to choose from to encapsulate their culture, so that the website is relevant to them personally.

Should it be a list of countries, or a list of regions that they choose from?

Most websites I've seen make users choose a country, but I think there are probably countries that share a very similar culture. Not to mention that some countries might have multiple cultures.


## Answer 7903

- posted by: [Luke Gedeon](https://stackexchange.com/users/1119600/luke-gedeon) on 2015-11-21
- score: 1

I don't know if this is possible with the framework you are working within, but I would go for a statistical model where you show "possibly" related links. At first they can be totally random or seeded based on linguistic analysis or you could have content creators (or a bunch of friends) start tagging things as related. Over time, track which links get the most clicks from each other source and start considering those related. You will then get bubbles of groupings that are a lot more meaningful than geography.

But let's say you really need it to be based on location. Then use country and group countries into regions behind the scenes. It is easier for people to tell you what country they are in than to figure out region you think they belong in, and they are less likely to argue with you about how you split the regions. As for splitting counties into different cultures, I can't think of a country that has a clean geographic split between cultures anymore except in cases where one or both of the cultures are pre-web.

Get people online and they start forgetting where they live.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
