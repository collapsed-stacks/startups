## IT Infrastructure for small startup

- posted by: [Display Name](https://stackexchange.com/users/5403987/display-name) on 2016-07-13
- tagged: `software`, `hardware`
- score: 4

New startup happening over the next month or so. It's an Engineering company  I am interested in people opinions on the best IT infrastructure for me. Its been a while so i am open to ideas.

5 people,  Quite heavy on data, Video etc. need to be able to show customer video remotely etc. 
we need good access to our data remotely.
Security is a priority too.  
Scaleability,

Is Microsoft server essentials the best solution?
Citrix Xenapp? or VPN?
Software firewall or hardware?
Wireless network or hardwired?

What about using gmail for business?
 


## Answer 9701

- posted by: [Marcus D](https://stackexchange.com/users/258531/marcus-d) on 2016-07-13
- score: 2

<p>IT Infrastructure is quite a broad subject - document management, email, data storage, communications software, security, integration, calendar, code control, permission control, etc ... Some things are packaged together like <a href="https://products.office.com/en-GB/business/get-latest-office-365-for-your-business-with-2016-visit-office?omkt=en-GB&amp;omkt=en-GB&amp;WT.mc_id=PS_Google_O365SMB_office%20365&amp;WT.srch=1" rel="nofollow">Office 365</a> or <a href="https://apps.google.com/intx/en_uk/products/?utm_source=google&amp;utm_medium=cpc&amp;utm_campaign=emea-gb-en-apps-bkws-super-trial-e_c&amp;utm_term=google%20apps&amp;KWID=43700009065769862" rel="nofollow">Google Apps</a>, others you will have to go to market place and choose.</p>

<p>From a data storage point of view, I would go for one of the cloud platforms - probably either <a href="http://aws.amazon.com/" rel="nofollow">Amazon Web Services (AWS)</a> or <a href="https://azure.microsoft.com/en-us/" rel="nofollow">Microsoft Azure</a> - because as a general principle hosted platforms are the way of the future and the diversity of services they offer is astounding.</p>

<p>In general for your IT services, things you need to consider are the following: -</p>

<ul>
<li>Geolocation of data. Does it matter where in the world your data resides? With Azure, you can specify where in the world your data resides, I <strong>think</strong> that AWS you can't.</li>
<li>Data access by the US Government. As long as it doesnt matter to you, law with regard to the Patriot Act. <a href="http://www.computerworld.com/article/2490690/technology-law-regulation/microsoft-ordered-to-turn-over-customer-data-stored-in-the-cloud.html" rel="nofollow">This case</a> is still ongoing.</li>
<li>Security of data. How secure is the environment you are using?</li>
<li>Integration. How integrated do you need the environments to be with your other services?</li>
<li>Lock in. Are you able to transfer to other suppliers easily?</li>
<li>Uptime. 99.9% is the often quoted figure, which sounds great, but in a year that means 8.75 hours downtime. You need to know what this means to your business.</li>
</ul>

<p>Often companies choose services in a piecemeal fashion, but actually if a number of the infrastructure/systems are chosen together there can be benefits of scale and integration.</p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
