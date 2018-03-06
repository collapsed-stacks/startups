## Should we sell our air pollution sensors to individual customers?

- posted by: [Defozo](https://stackexchange.com/users/1302735/defozo) on 2017-01-12
- tagged: `tech-company`, `sales`, `market-research`, `customer-service`, `sell`
- score: 5

I'm a co-founder of a company that provides:

- air pollution sensors
- interactive air pollution map (website and Android app) where the air quality is presented

[![enter image description here][1]][1]
The map is available for everyone.

Background - what do we do now, how the problem started
-------------------------------------------------------

As for now, we have a business model for leasing our sensors to cities (the government in general). They are paying initial payment (for the sensor, mounting, configuring etc.) + monthly fee (for maintaining and periodically calibrating the sensor and maintaining our website). This business goes fine.

However, there are many e-mails from individual customers that are fascinated with our idea of distributed dense network of air pollution sensors and they want to buy our sensors for their location as well.

----------

**There are few questions that I'd like to have answer for:**

- Should we sell sensors to individuals or just sell them to cities, towns etc. as we do now?
- If we should sell sensors to individuals, then on what terms? Should we resign from the idea of monthly fee?
- Should we show the sensors that would be bought by that customers on our map?
- Do you have any pros/cons to add?

We are just a startup. This is complex problem and any advice would be appreciated.

----------

Selling sensors to individuals (in general)
------------------------------
**Pros:**

- More money.
- More active points on our map (if we decide to show them).

**Cons:**

- Need to provide customer service.

----------

**We can divide these customers into two cases:**

People that want to buy sensor within area of existing sensor network
------------------------------------------------------------------------

**Pros:**

- They are near our headquarters, so possible warranty is handled easily - if something happens to the sensor, we can deliver a new one in the same day.
- We can mount our sensors by ourselves, so we can make sure that the sensor is mounted correctly and in the right place.
- We have better control over reliability of data presented on our website - with the dense network of measuring sensors we can detect an outliner easily and we can physically check if sensor is OK by going to the place where the sensor is.

People that want to buy our sensor and are far away from our dense network of sensors
------------------------------------------------------------------------
**Pros:**

- Showing measurements from remote location where no sensors were previously may raise awareness of badly polluted air in people's minds and therefore attract city to buy more sensors.

**Cons:**

- Handling potential warranties would require extra time and resources.
- We won't be able to mount the sensor by ourselves or that would cost us extra money, so we have no control over how the sensor is mounted.
- We have less control over validating if the measurements are correct. However, it's still possible but in limited way.
- It may happen that the cities won't be interested in our offer anymore because the citizens would buy many of our sensors in particular city.

**Additional information:**

- We've installed above 100 sensors and from that number about 1 sensor started to work improperly in about 2 months time.
- One of our concerns are the users who can take sensor away from the location where it was mounted. For example, take it indoor. We have temperature sensor and we can scan WiFi networks, so it can be detected but in limited way.
- We really want to care about quality of the data. We want to be reliable.
- We are not sure yet how often the calibration of the sensors will be needed. We approximate it for about 2 years now.

  [1]: https://i.stack.imgur.com/zGIX2.jpg


## Answer 11895

- posted by: [mustaccio](https://stackexchange.com/users/1270839/mustaccio) on 2017-01-12
- score: 2

<p>I think you would do well by riding the <a href="https://en.wikipedia.org/wiki/Citizen_science" rel="nofollow noreferrer">"citizen science"</a>  wave, targeting hobbyists and "makers" who are interested in tinkering with electronics, IoT and sensors. One good example is <a href="https://www.wunderground.com/" rel="nofollow noreferrer">The Weather Underground</a>, although they don't manufacture sensors themselves. </p>

<p>Targeting early adopters will partially address your installation and warranty service concerns. These customers will be inherently interested in obtaining accurate measurements and therefore are more likely to install your sensor themselves and do it thoroughly, given appropriate instructions. They will also be likely more flexible than government customers or mass consumers when it comes to the warranty replacement turnaround times (you would still need to handle RMA and replacement, obviously). </p>

<p>You can address your data quality concerns by separating "hobby" data and possibly more accurate "real customer" data onto separate maps, with appropriate disclaimers. As your sensor adoption rate goes up you would be able to assess "hobby" data accuracy and potentially integrate the two maps, at least in some locations. </p>

<p>As The Weather Channel story tells us (they were recently acquired by IBM for a nice sum with nine zeroes at the end), the collected data can be more valuable than the sensor network itself: you can only sell a sensor once, but the data it collects keep flowing, and you can sell data analytics many times without additional cost. </p>

<p>At some point you might be able to improve reliability and accuracy of your equipment to an extent allowing you to offer a version for a mass consumer, at which point you can essentially outsource sensor installation and maintanance to random people around the globe and still benefit from data they collect by selling ready analytics to municipalities and businesses.</p>

<p>P.S. I'd buy one of your sensors myself.</p>

<p>P.P.S. Do you offer equity, by chance? :)</p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
