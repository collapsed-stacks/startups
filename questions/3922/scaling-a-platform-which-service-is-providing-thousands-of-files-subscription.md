## Scaling a platform which service is providing thousands of files + subscription

- posted by: [user18375](https://stackexchange.com/users/3746660/user18375) on 2015-04-02
- tagged: `tech-company`, `growth`, `web-development`, `saas`, `service`
- score: 1

I am creating a platform that showcases behind the scenes material from movies. The unique value proposition is in its quality but also the quantity of never before seen content.

How to start out agile with so much content. These are the minimum requirements of the service:

1. Users can preview 10% of the content for each movie, no subscription required
2. Users can subscribe for 10$ a month to access all the material
3. The site also has a shop w. thousands of files, no subscription required

How can I go by building this ? What types of SaaS can encompass all of this or which go together well ?<br />
I have been thinking about Subbly + BigCommerce.

Budget is relatively large, but I would like to start agile. I got front-end programming experience and would like to customise the design fully - but not deal with back end.

What path should I choose to help scale this business while maintaining the minimum requirements ?


## Answer 3924

- posted by: [chelder](https://stackexchange.com/users/1234525/chelder) on 2015-04-02
- score: 1

To start agile I'll think about how to do it without spending time in building a platform. 

For instance, cut the videos with any video editing software. Then provide a link to buy the full video (or even ask to send you an email if they want to buy the full video). Youtube could be the platform to store the preview video. If it works and people buy it, then build the platform (or build the platform at the same time). 

Is it an answer for you or you are asking about technologies?


## Answer 5237

- posted by: [Sam](https://stackexchange.com/users/2541867/sam) on 2015-05-08
- score: 0

<p>I would look for a business partner with backend service delivery experience or work on a PaaS (Platform as a Service) I highly recommend Bluemix ( I work for IBM so I would be bound to say that ).</p>

<p>Bluemix offers tools to rapidly develop and scale applications. There are examples, high level tool kits and lots of support on the website.</p>

<p><a href="https://console.ng.bluemix.net/" rel="nofollow">https://console.ng.bluemix.net/</a></p>

<p>For instance the Bluemix catalog includes built in push functionality to mobile devices, which would allow you to create mobile apps that update the user in real time as new behind the scenes video becomes available. (<a href="https://console.ng.bluemix.net/?ace_base=true/#/store/cloudOEPaneId=store&amp;serviceOfferingGuid=aa206aa9-1c49-499b-86ad-add09f73fabd&amp;fromCatalog=true" rel="nofollow">Bluemix iOS 8 push</a>)</p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
