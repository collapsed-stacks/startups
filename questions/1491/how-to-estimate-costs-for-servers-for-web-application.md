## How to estimate costs for servers for web application?

- posted by: [hellectronic](https://stackexchange.com/users/58516/hellectronic) on 2014-11-25
- tagged: `business-plan`, `startup-costs`
- score: 6

Maybe I can find some answers here. How would you estimate costs for a  
business plan in context of a web application that is running on a cloud?

Problem is I do not know how the application will technically perform, we have  
no prototype yet. At one point we will need to scale...


## Answer 1493

- posted by: [DP_](https://stackexchange.com/users/171799/dp) on 2014-11-25
- score: 5

<p><strong>Approach #1</strong></p>

<p>I can give you an example, how to estimate the costs for a fictious application, which runs in the cloud (Amazon AWS).</p>

<p>Let's say, there is a device, which regularly sends requests to the server. The server runs in the cloud and needs to process those requests.</p>

<p>Let's assume that the requests are sent every 10 minutes or 144 times per day or 4320 requests per month.</p>

<p>Then, we assume that it takes the server 0.005 seconds (5 milliseconds) to process one request. This gives 0.72 hours of machine time per user per day and 21.6 hours per user per month.</p>

<p>Let's assume we have 10000 users. This gives a total machine time per hour of 216000.</p>

<p>Finally, you go to the web site of Amazon AWS and look up the price per machine hour. At the time of creating that example (months ago) it was equal to 22.2 roubles.</p>

<p>Multiply machine hour price (22.2) by the number of machine hours per month (216000) and you get the total costs of the cloud server infrastructure (4 795 200 roubles).</p>

<p>You can download a spreadsheet with these calculations <a href="https://dl.dropboxusercontent.com/u/11776689/altruix/additionalMaterials/2014_08_30_profitability_estimate.ods" rel="nofollow noreferrer">here</a>.</p>

<p>The diagram below shows how assumptions (yellow ellipses) affect expenses and revenue in that spreadsheet.</p>

<p><img src="https://i.stack.imgur.com/IzASG.png" alt="Assumptions, expenses and revenue"></p>

<p>It goes without saying that you should insert different value into your assumptions to see how the final value changes.</p>

<p><strong>Approach #2</strong></p>

<p>Apart from Amazon AWS, there is DigitalOcean. Here, you pay 5 dollars per virtual machine.</p>

<p>If you can estimate the number of virtual machines (their specs are available on the site of DigitalOcean), you can take the number of required machines and multiply by 5.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
