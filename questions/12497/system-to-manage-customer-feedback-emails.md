## System to manage customer feedback emails

- posted by: [Cheok Yan Cheng](https://stackexchange.com/users/27431/cheok-yan-cheng) on 2017-04-14
- tagged: `email-marketing`
- score: 1

Currently, I have an Android app. The Android app has a feedback form, which allows user to send feedback to us. 

The app just send an email to `my_company@gmail.com` with user feedback content, along with customer replied email.

However, as customer grows, we found it is very difficult to manage our relationship with customers.

 1. We don't have a way to know all our customer emails, without opening up mail one-by-one in mail box.
 2. We find it difficult to track back our conversation with customers. For instance, same customer can send us feedback several times, by using the in-app feedback form. Hence, in our email mail box, we will end up with multiple email threads for a single customer.

Is there a software, or online service, which enables us to manage our customer email, so that we can serve our customer in better way?


## Answer 12521

- posted by: [Marcus D](https://stackexchange.com/users/258531/marcus-d) on 2017-04-19
- score: 1

<p>There are two software systems that you are after here</p>

<ul>
<li>Helpdesk - a system to monitor customer (or supplier/partner) interactions mostly concerning software or process defects. They can be used much more broadly than this, but from your point of view, it is to support your Android App. The purpose is to track and resolve problems. They can be cloud hosted or installed. Some charge a monthly fee, some are free, some are a one-off cost. Some suppliers of helpdesk software are <a href="https://www.zendesk.com/" rel="nofollow noreferrer">ZenDesk</a>, <a href="https://www.atlassian.com/software/jira/service-desk" rel="nofollow noreferrer">Jira Service Desk</a>.</li>
<li>CRM system - a system that tracks interactions with customers (and/or suppliers/partners) from the point of view of trying to understand customer behaviour to increase sales, build analytical customer engagement models, track sales leads, etc. These can again be installed or hosted, and are free, one off cost or monthly subscription based. Examples are <a href="https://www.salesforce.com/uk/" rel="nofollow noreferrer">Salesforce</a>, <a href="https://www.microsoft.com/en-gb/dynamics365/home" rel="nofollow noreferrer">MS Dynamics CRM</a> and <a href="https://freshdesk.com/support-software" rel="nofollow noreferrer">Freshdesk</a>.</li>
</ul>

<p>You will need to build some <a href="https://en.wikipedia.org/wiki/Middleware" rel="nofollow noreferrer">middleware</a> that connects your email system to your CRM and helpdesk that enables you to manage the three systems seamlessly. This will be tricky to do but sounds like a key to expanding your business.</p>

<p>Note: I do not work for any of the companies mentioned above, but have used some of the software.</p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
