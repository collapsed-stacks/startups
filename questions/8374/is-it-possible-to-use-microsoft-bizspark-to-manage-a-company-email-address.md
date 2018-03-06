## Is it possible to use Microsoft BizSpark to manage a company email address

- posted by: [SeanJ](https://stackexchange.com/users/3029947/seanj) on 2016-01-22
- tagged: `bizspark`, `email-marketing`
- score: 4

I signed up for BizSpark and there's a bunch of us in the company.

We want to get company email addresses for our domain.  It's easy to do with either microsoft or google:

products.office.com/en-us/exchange/exchange-online - $4 per month

apps.google.com/intx/en_my/pricing.html - $5 per month

Seeing as we have €170 azure credits per month, does anyone know if it can be done using azure? Every penny counts at this point!

**edit**  This doesn't seem possible, I'm considering using authenticated SMTP on register 365 and the import/export feature on gmail.

In case anyone is interested, I'll be documenting the benefits of BizSpark, that I discover [here][1].


  [1]: https://thecodeisbroken.wordpress.com/2016/01/19/maximizing-bizspark/


## Answer 8424

- posted by: [Ess Kay](https://stackexchange.com/users/2619138/ess-kay) on 2016-01-29
- score: 3

According to Microsoft it is not mentioned in the description and can be assumed that is not included:
**Source: https://www.dreamspark.com/what-is-BizSpark.aspx**

> When you’re ready to start your own business, Microsoft has a
> three-year program that gives you access to all the right resources
> you need to help you become the next big thing. 
>
> what is BizSpark?
> Microsoft BizSpark is a global program that helps startups succeed by
> giving free access to Microsoft cloud services, software and support.
>
> Since 2008, over 100,000 startups have joined BizSpark….and counting
> 
>BizSpark includes: 
>
> Up to $750 per month of FREE Azure cloud services
> for 3 years; that’s $150 per month each for up to 5 developers. 
> 
>A full
> suite of development and test software and tools such as Visual
> Studio, Windows and Office. 
>
>Access to hundreds of FREE training
> classes, technical content plus 4 break-fix phone support incidents.



Based on my knowledge, the Office 365 subscription for BizSpark is the Developer subscription. Microsoft Office 365 Developer subscription provides tools and an environment to build and test apps for the Office and SharePoint stores.

If you want to use Office 365 for Email purpose, you should own Exchange Online license.


**The Following was a derived answer from a Microsoft Support Employee**:

> I'm sorry that the answer is no. Office 365 for business is not free
> for Bizspark members.
> 
> You received access to a developer version of MSDN subscription. It is
> not free in the other formats.
> 
> "BizSpark is a Microsoft program that provides free Microsoft
> products, software design, and development tools to business startups
> for 3 years. Included in these benefits is MSDN Ultimate.
> 
> Included in your MSDN Ultimate subscriptions are all Microsoft desktop
> operating systems from Windows XP through Windows 8 Pro. You also get
> every version of Microsoft Office, including a subscription to Office
> 365. You also get all Microsoft server operating systems and server applications, like SharePoint, SQL Server, and everything else.
> 
> Your MSDN subscription also includes Windows and Windows Phone
> developer accounts, priority support in MSDN forums, Microsoft
> e-learning courses, MSDN Magazine, and a whopping $150/month credits
> in Windows Azure – our cloud service for storage, compute, and
> hosting."
**Source: https://community.office365.com/en-us/f/155/t/257360**

Hope that helps.
Ess






---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
