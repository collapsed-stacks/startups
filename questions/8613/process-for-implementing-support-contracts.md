## Process for implementing Support Contracts?

- posted by: [Wasted_Coder](https://stackexchange.com/users/978739/wasted-coder) on 2016-02-26
- tagged: `software`, `contracts`, `strategy`
- score: 2

<p>So we have developed a software product for payrol. The system captures timesheets and calculate salaries based on that.</p>

<p>We currently only sell the software with a yearly licence attached. The product works fine, but we have fallen into a hole where our clients keep on calling us at the end of the month with problems with their time entries, not related to software fault, but related to new employees, or funny time entries thus operational reasons.</p>

<p>This is keeping us so busy during the day, that our employees cannot do much more than just answer queries. We have decided that the best way forward would be to start charging for this support, or sell support contracts. </p>

<p>We need advice on how to "convert" old clients to accepting that they need to pay. We cannot just off the bat start denying support. So we need a process to gradually introduce the support cost that the client will need to pay. The clients currently "expect" us to give them help for our software. </p>

<p>It is not always hours of support per client, it may take us 5 ot 10 minutes to solve some problems. We have thought of starting to charge ad-hoc for support queries, but because the time per case can be so short, we cannot charge the client only a few bucks for each call, that is a lot of billing admin for not much extra.</p>

<p>Please advise on how we could approach this conundrum? Also we rather "want" clients to pay monthly for a support contract, but we realise that we cannot force that upon them, so how can we convince them to rather take a contract than ad-hoc services?</p>

<p>Example Ideas:
Should we load the ad-hoc pricing? </p>

<p>Should we make the process of getting ad-hoc support very cumbersome? How? (For instance in large companies, they normally have policy against accepting invoices without first requesting a purchase order from finance, so just having to do that, makes a company decide to rather take a contract than having to go through the process every time they need help working).</p>

<p>Thank you in advance!</p>

<p><strong>EDIT/UPDATE:</strong> </p>

<p>From the answers below and some more discussions we reviewed our first attempt at an SLA agreement, and realised it was more just a "Service Agreement". We did not have any information for response and turnaround time. We only mentioned additional services (like weekly verification of data accuracy) and that the client will pay ad-hoc when rendered by us.</p>

<p><em>License Agreement:</em>
We have realised that we should rewrite our <strong>licence agreement</strong>. Thus the "benefits" included when clients pay the <strong>yearly licence fee</strong>. It should clearly stipulate what is included (like free updates and basic support which we will express in a basic SLA agreement with for instance 24 hours response time). Also the reasoning behind why we charge yearly license fees, is that the client pay a fee to have right to use our software.</p>

<p><em>Support Agreement:</em>
Then we will convince the client to commit to a "<strong>Support Contract</strong>" which will consist of an SLA with faster response and turnaround times. Reasoning behind why they would pay for a <strong>Support Contract</strong> is because this binds us to provide support to them. Our software comes with a large hardware investment, and they wouldn't want us to just decide to close shop leaving them in the dark. They pay monthly so that we can acquire the necessary resources. Also the SLA provides a guaranteed service level which they can expect to receive, and should give them re-assurance. As our product are heavily used during month end payroll.</p>

<p>We will also look at "tiered" fees for the "<strong>Support Contracts</strong>". The cost will be fixed per month, calculated using @Baronz's answer below as guide. </p>

<p>For our smaller clients the <strong>Support Contract</strong> will include a fixed amount of support time the client can use under the contract terms and cost. Any out of contract support will be charged ad-hoc at a higher fee per hour than the included time in the contract. We also decided we will allow 1 month roll-over, so that a client can use more support time in the next month if he did not use all in the current month.</p>

<p>For our larger clients, we will provide a "unlimited" time support contract, calculated based on the total amount of employees in the company. This "Support Contract" would be a bit more expensive (we will consider how much support time a client can use of such size), but we may also provide a SLA with "priority support". </p>

<p>With our product we will include a small compulsory support contract for the first 6 months, then the contract will be month-to-month, and he can cancel with 30 days notice. The client can also upgrade his support contract if he continually need and pay for out of contract support.</p>

<p>We will also continue to have "Service Contracts/Agreements" for any recurring monthly activities that the client may ask for, like backup service.</p>



## Answer 8615

- posted by: [fiprojects](https://stackexchange.com/users/5370155/fiprojects) on 2016-02-26
- score: 3

<ol>
<li><strong>What you need to write is a SLA (Service Level Agreement)</strong> If you creatively surf you might find a few on the web that you can alter - I have seen them written from two to twenty pages. You need set expectations. Best write a default document, and refer the default document to a schedule. The schedule will contain variables (hours/days when the service is offered, the cost of out of hours cover, what is covered, what is not covered, how a call is costed/charged, the number/email address for them to call, escalation points when the process you describe fail, and how failure in your service is compensated to the customer).</li>
<li><strong>Costing</strong> I suggest arranging your time in units of 30minutes - so if a call takes 15mins, they are charged for 30mins (one unit). If the call takes 40minutes, you charge for 1 hour (two units). Award your old customers two or four units a month for three months to get them familiar with the process. After that they can buy credits in - to encourage them to buy in advance, let's say a unit costs $50 - if they buy ten units in advance, it will cost $400. If they call without any credits, charge $60 per unit. (EDIT: Give units a life span of 30-60 days).</li>
<li><strong>Reporting</strong> Record who you talked to, when, and the purpose of the call. If the same information is delivered more than once then the customer needs to educate their team unless they are happy spending units being told the same thing more than once. Also see note 6 below.</li>
<li><strong>Compensation</strong> You need to put stage gates - that calls will be answered between 0900/1700hrs for example, Monday to Friday, except not when it is a local holiday. You need explain that you will respond to a request for help within certain time frames (15mins/30mins/60mins) and that you will provide an answer within a certain time frame. You need also explain how you will compensate them if you fail to answer a valid question. Best award them credits to avoid breaking your bank.</li>
<li><strong>Encouragement</strong> To encourage your customers to adopt the new service, ask them to buy credits in advance. If they don't then your response will be best effort basis via email only.</li>
<li><strong>Enhancements</strong> Look at the reports (note 3 above) you create that record the most common problems/failures and enhance your product to reduce support calls. This should hopefully allow you to profit listening more to your customers needs, and potentially grow your client base.</li>
<li><strong>Get Liability Insurance</strong> If someone is using your product and you have licensed it to them, any loss to their business as a result of them using your product could result in your company being held liable. If you are a sole trader (meaning not incorporated company) then that holds you personally liable (your home, your credit rating). If incorporated, the company will be held liable (if the fault is deemed to be accidental) and the insurance will help. It's not expensive - I costed insurance last year at under $500 which covers me for service that excludes physical labour (thus I cannot lift a computer server etc - service of a mental capacity only). It covers me worldwide, $5million per incident.</li>
</ol>

<p>Best of luck!</p>



## Answer 8617

- posted by: [Baronz](https://stackexchange.com/users/7281676/baronz) on 2016-02-26
- score: 1

<p>So, another answer on here gave you a lot of details on a variety of things you should consider and build into that "support contact".</p>

<p>I wanted to help by adding a seperate answer to talk about how much other companies charge, and what they offer for that price.</p>

<p>I understand that in our modern software era, where phone apps are free or cost $0.99 and get free updates forever some of what I'm describing here will seem insane, but it's the reality of many current enterprise software offerings.</p>

<p>Across most of the tools in the industry I'm in (Engineering Software) the Software Vendors all charge some form of monthly maintenance contracts with the following basic model:</p>

<p><br></p>

<h2><strong>The cost of monthly maintenance:</strong></h2>

<p>In my industry, 0.8% to 1.0% per month, per user is pretty standard.</p>

<p>So if the software costs $5000, and you have 10 users, the client should expect to also pay this value in perpituity:</p>

<pre><code>$5000 x 10 x .01 = $500 usd / month
</code></pre>

<p><br></p>

<h2><strong>Monthly Maintenance Remediation:</strong></h2>

<p>If the customer stops paying maintanance for over a year, some vendors allow the customer to pay 12 months of back-maintenance to bring their contract back into compliance.  Other vendors demand all back-maintenance regardless of time-lapse to return to compliance.</p>

<p><br></p>

<h2><strong>Value provided for that monthly maintenance:</strong></h2>

<ol>
<li><p><strong>Floating License -</strong> Most of the Vendors allow you to install the software on a large number of computers (75,000) and then use the license file to ensure you don't exceeed the number of concurrent users (25,000).</p></li>
<li><p><strong>Software Updates -</strong> Allow you to update use any supported version of the software (Usually the current version and previous two releases)</p></li>
<li><p><strong>New License Files -</strong> When new versions come out, the software vendor provides a new license file to replace the old license file as part of the monthly maintenance cost.  <em>NOTE: If the customer needs a new license file because they change license servers, the vendor normally charges a fee for that unplanned license generateion.</em></p></li>
<li><p><strong>Access to Online FAQs\Knowledgebase -</strong> Most vendors have a private system that includes additional knowledge, like sample API programs, that are not generally available to customers not paying maintenance.</p></li>
<li><p><strong>Limited Web Training -</strong> The Vendors all have expensive training classes where people fly in from all over to attend specilized training.  As a value add for maintenace, the vendors offer some more introductory training on the web for their customers with current maintenance.</p></li>
<li><p><strong>Access To Technical Support -</strong> The customers have access to a system to log tickets.  The tickets are responded to in a timely manner, usually at least opening a dialog with the customer within 3 days.  Depending on the SLA, this may include the helpdesk working with the developers directly to resolve issues.</p></li>
<li><p><strong>Mission Critical Support -</strong> In the unlikely event that a server-based software fails, many maintnance contracts include in the server license for 24-7 phone support.</p></li>
<li><p><strong>Strategic Maintenance -</strong> Many of the vendors allow the customer to use their maintenance dollars to influence the direction or priority of development.  If the vendor was plannining a feature for calendar year 2026, but the customer wants it earlier, they can spend their influence to make that request for the feature to be delivered in 2023.  The more seats you own, the more you can spend that influence.</p></li>
</ol>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
