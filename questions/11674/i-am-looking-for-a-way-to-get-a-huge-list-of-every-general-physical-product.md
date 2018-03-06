## I am looking for a way to get a HUGE list of every general physical product

- posted by: [David Tunnell](https://stackexchange.com/users/9814024/david-tunnell) on 2016-12-09
- tagged: `product`, `e-commerce`
- score: 2


I am looking for a way to get a HUGE list of every general physical product. Examples: coffee mug, video cards, mouse and keyboard, etc but for pretty much every physical product that can be sold.

Idea include, scraping amazon. But is this the only way? Do any databases exist like this?


## Answer 12086

- posted by: [Paulo Scardine](https://stackexchange.com/users/199019/paulo-scardine) on 2017-02-10
- score: 1

There is a HUGE database called EAN (>100 million).

From https://www.ean-search.org/:

> # What is an EAN ?

> EAN, or EAN13, stands for International Article Number (originally European Article Number). It is an extension of the UPC codes and you'll find them as barcodes on most everyday products. Sometimes the barcode is also called GTIN or GTIN13 (Global Trade Identifier).
> # Which information is included in an EAN ?

> The EAN includes the country of origin, the manufacturer and a product number. In addition to that it includes a checksum.
When you only look at the barcode, you can't easily see which product it belongs to. Thus, this website provides a reverse EAN lookup, that tells you the product the EAN code belongs to.

> #Is this database complete ?

> Currently the database includes over 104.171.000 entries, but thats still only a fraction of all the EANs ever issued.



## Answer 11689

- posted by: [Matt](https://stackexchange.com/users/499963/matt) on 2016-12-12
- score: 0

There's a couple thoughts here from around the net: 

- https://www.quora.com/Why-does-Amazon-not-have-a-sitemap
- https://stackoverflow.com/questions/37413989/amazon-sitemap-data-in-xml-gz-form-uncompressable

Amazon is gigantic, but the .xml.gz file in the second link appears to have a listing of various sub-maps, which you could use to get a good list. 

If you don't want to try and go the Amazon route, you might try going through APIs or site maps for other large sales sites like eBay, and looking for cloud maps of post tags, or site maps themselves. 

eBay's site map is a little more detailed, for example: http://pages.ebay.com/sitemap.html

From the eBay example, you could have someone write a script that opens each link, finds the subcategory listing for each, stores it, and then possibly repeats for each step down you want. That's how scraping would go, at least. 

Something to consider there is whether it's legal -- many / most / all of these sites will prohibit some or all of that sort of scraping, especially if you're looking to use the results of it to make a profit. So, I'd review that before you go about hammering one of the sites to scrape out that info. 

Another potential starting point: http://www.wholesalecentral.com/catoverview.htm




## Answer 12244

- posted by: [Nick Duncan](https://stackexchange.com/users/5384292/nick-duncan) on 2017-03-03
- score: 0

Any list you'll get will most likely not be ideal for what you want to use it for. You will probably find out that as soon as you have the list, most of it will be irrelevant to you and your needs. You'll most likely be spending countless hours trying to clean it, categorise it and sort it.

Focus on **quality over quantity**...



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
