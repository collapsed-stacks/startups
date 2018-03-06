## How to calculate Churn Rate?

- posted by: [demiculus](https://stackexchange.com/users/5264485/demiculus) on 2014-12-15
- tagged: `tech-company`, `churn`
- score: 5

I am trying to calculate churn rate for a mobile payments project and I am confused. Some people say 2% some say 60%. I read some articles but I think that countries are important in these kinds of things. Here(Turkey) credit card usage is really high but the trust index is not that good. 

So how can I calculate Churn Rate?


## Answer 1655

- posted by: [Dan Dukeson](https://stackexchange.com/users/40875/dan-dukeson) on 2014-12-15
- score: 8

User churn is "Number of users that cancelled this month" divided by "total number of users"

You had 100 users, 2 left last month, your user churn was 2%.

You could also calculate revenue churn similarly, but counting revenue lost in cancellations as a percentage of total revenue.







## Answer 11432

- posted by: [Ryan Law](https://stackexchange.com/users/9520414/ryan-law) on 2016-10-26
- score: 3

<h2>Customer Churn</h2>

<p><a href="https://www.cobloom.com/blog/saas-metrics" rel="nofollow noreferrer">Customer churn</a> (or "Logo Churn") measures the rate at which your existing customers cancel their subscription to your service:</p>

<p><img src="https://chart.apis.google.com/chart?chf=bg,s,fffff0&amp;cht=tx&amp;chl=%5Ctext%7B%25%20Customer%20Churn%20Rate%7D%3D%5Cfrac%7B%5Ctext%7BCustomers%20that%20churned%20in%20period%20t%7D%7D%7B%5Ctext%7BTotal%20customers%20at%20the%20start%20of%20period%20t%7D%7D" alt="customer churn rate formula"></p>

<p>For example, if we start January with 20 paying customers, but finish with only 19, the customer churn rate for January was 5%:</p>

<p><img src="https://chart.apis.google.com/chart?chf=bg,s,fffff0&amp;cht=tx&amp;chl=%5Ctext%7B%25%20Customer%20Churn%20Rate%7D%3D%5Cfrac%7B20-19%7D%7B20%7D%3D5%5C%25" alt="customer churn rate worked example"></p>

<h2>Revenue Churn</h2>

<p><a href="https://www.cobloom.com/blog/saas-metrics" rel="nofollow noreferrer">Revenue churn</a> (or "MRR churn rate") is the rate at which monthly recurring revenue (MRR) is lost, as a result of lost customers and downgraded subscriptions.</p>

<p><img src="https://chart.apis.google.com/chart?chf=bg,s,fffff0&amp;cht=tx&amp;chl=%5Ctext%7B%25%20Revenue%20Churn%20Rate%7D%3D%5Cfrac%7B%5Ctext%7BMRR%7D_%7Bt-1%7D-%5Ctext%7BMRR%7D_t%7D%7B%5Ctext%7BMRR%7D_%7Bt-1%7D%7D" alt="revenue churn formula"></p>

<p>For example, if we made $5,000 MRR in January, but as a result of our lost customer, only $4,750 during February, that month's revenue churn is $250, or 5%:</p>

<p><img src="https://chart.apis.google.com/chart?chf=bg,s,fffff0&amp;cht=tx&amp;chl=%5Ctext%7B%25%20Revenue%20Churn%20Rate%7D%3D%5Cfrac%7B5%2C000-4%2C750%7D%7B5%2C000%7D%3D5%5C%25" alt="revenue churn rate worked example"></p>



## Answer 11445

- posted by: [Daniel Anderson](https://stackexchange.com/users/8398759/daniel-anderson) on 2016-10-27
- score: 0

One of the other considerations when looking at overall churn rate is how many *new* customers did you add during the same period?  So, if you have 100 customers at the start of the period and lose 2, your churn rate is 2%.  But if you also *added* 5 new customers, then you still had a net gain for the period of 3% (started with 100 customers, lost 2, added 5).

***Both*** sets of numbers are important metrics to know and understand, but in reality, as long as new customer acquisitions outpace losses, you're still a growing concern.

The biggest problem with churn frequently has to do with cost of customer acquisition versus how long customers stay before leaving.  So let's say, for instance, you calculate your customer acquisition cost at $50.00, and it takes you four months to recoup that cost before you can really say you're earning a profit on the customer.  If they leave prior to reaching the break-even milestone on the acquisition cost then you have problems, because each lost customer is not only lost revenue going forward, but you have an actual loss on the account because they left before you could realize enough revenue to justify the cost of acquiring them in the first place.

This is the reason why, in the United States, mobile phone, security and satellite/cable companies often require you to sign two-year (or longer) service agreements in order to get their best deals -- the acquisition cost of gaining you as a customer requires them to *keep* you as a customer for a fair portion of that initial service agreement just to recoup their costs in acquiring your business.  This figure is often referred to as a "multiple".  When I worked in satellite television, our new customer multiple was 18, meaning the first 18 months of a new customer's monthly payments went toward the costs (equipment, commissions, installation, etc.) of adding them as a new account.  It wasn't until month 19 that we could reasonably expect to count monthly payments as real revenue.

So while a raw "churn" number is important, it is also **VERY** important to understand how that number is arrived at.  If most of your customer churn is coming from customers who do not stay with your service for long then you have some serious issues to resolve.  It may be an indication that they're being promised things you can't deliver, or perhaps there are customer service or quality issues that cause them to leave so quickly.  On the other hand, if most of your churn is long-term customers then you need to understand that as well, because perhaps you are not executing as well as you once did, or your competitors are offering better deals to your older accounts.

I hope this is helpful.

Good luck!



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
