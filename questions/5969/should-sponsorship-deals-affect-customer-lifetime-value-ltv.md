## Should sponsorship deals affect customer lifetime value (LTV)?

- posted by: [Philip Seyfi](https://stackexchange.com/users/204408/philip-seyfi) on 2015-08-08
- tagged: `metrics`
- score: 2

Let's say that we have a free app with additional content sold via in-app purchases.

`LTV = (Average Order Value) x (Number of Repeat Sales) x (Average Retention Time)`

So far so good. Now let's add two additional revenues sources:

* Sponsored content - 3rd party subsidizing the price of each download
* Sponsored content - 3rd party paying a flat fee to make a content pack free

Should this revenue be included in the LTV formula, despite having no direct connection to individual customers?

_A good real-life example of the above is the LINE messaging app. You can download free sticker packs, purchase premium sticker packs, or download sponsored sticker packs paid for by Coca Cola, Häagen-Dazs, etc. Would LINE's LTV include revenue from sponsorship deals, or only from direct purchases by customers?_


## Answer 6032

- posted by: [zazaalaza](https://stackexchange.com/users/4672194/zazaalaza) on 2015-08-12
- score: 1

Yes. By customer lifetime value basically what you mean is the number of $ a customer generates and in both cases they need to make an action to generate this revenue.

A 3rd party subsidizing the price of each download would increase the customers lifetime value by the value of the subsidy (since every customer needs to download your app).

A 3rd party paying a flat fee to make a content pack free would increase the customers lifetime value by the average download rate (since they need to download the free pack).

So your formula would look something like this:

> LTV = (Subsidy) + (Average Order Value) * (Number of Repeat Sales) * (Average Retention Time) + (Flat Fee) * (Average Download Rate of the Free Pack)

Your free users would also have an LTV this way.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
