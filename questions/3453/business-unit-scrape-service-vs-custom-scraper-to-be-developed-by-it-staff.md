## Business unit scrape service vs custom scraper to be developed by IT staff

- posted by: [Igor Savinkin](https://stackexchange.com/users/1275029/igor-savinkin) on 2015-02-19
- tagged: `web-development`, `data`
- score: -2

If my startup needs data from the web (~1M records), what would be the pros/cons of different methods to scrape those data: 

 1. Outsource to a specialized scraping services (i.e. Mozenda, kimonolabs and others) 
 2. Set up a custom scraping program by IT department staff 

Have you any experience in this?

Could you suggest how to evaluate money and time costs especially for the second case (doing it by IT department)? Also any special considerations your experience suggests we should factor in.


## Answer 3455

- posted by: [blunders](https://stackexchange.com/users/216182/blunders) on 2015-02-19
- score: 3

<p>Best way to think about scraping data is that you're attempting to build an interface to an very bad API that may in fact vary in its response from one request to another, or require human intervention to bypass its features.</p>

<p>Per Mozenda, <a href="https://www.mozenda.com/managed-service" rel="nofollow">factors that affect the cost of a project include</a>:</p>

<ul>
<li>Overall size and complexity of the job</li>
<li>Amount of data to be downloaded</li>
<li>Complexity of Agent creation</li>
<li>Number of websites supported</li>
<li>Frequency of data delivered</li>
<li>Need for Anonymous services</li>
<li>Custom engineering and other product enhancements</li>
<li>Data validation efforts</li>
</ul>

<p>Writing custom scripts from scratch is a bad idea, since if the extraction is simple enough to write a script for, there's already going to be a free product out there to do it.</p>

<p>Given you haven't really provided much to go on, my suggestion would be to attempt to find three existing free products and attempt to pull a sample of the data, not all the data. Doing so will give you a much better idea of the requirements for your pulling the data.  Say this in part since defining the count of records to be pulled, in this case you say 1-million records, means nothing in my opinion; for example, the records in question might just be million RSS feeds, or they might be on a site that actively blocks attempts to pull its data.</p>



## Answer 8998

- posted by: [PV22](https://stackexchange.com/users/8264469/pv22) on 2016-04-17
- score: 1

My Experience: Hello. I am writing based on my experience involving both the development, implementation, and automation of in-house tools (including web-scraping methods), as well as evaluating third-party tools. In my experience there are a lot of factors you need to take into account, but one major component to consider is determining how your current and long term resources are best invested. Here is a basic PRO and CON list of implementing for both methods. I hope this helps give you some points to consider. 

**IT Development PROs:**

- Customization: collecting, analyzing and delivering data as you need it.
- Lower medium term maintenance costs.
- Lower/adjustable initial investment
- IT can more easily enhance tools.
- Proprietary rights to methodologies and tools

**IT Development CONs:**

- Implementation time can be significant
- Resource focus can be significant
- In-house development capability can be a limiting factor
- Material Capital (server, terminals, etc.)

**Outsourcing PROs:**

- Predesigned tools can often offer faster implementation times
- You may be able to implement with fewer people involved
- Outsourcing maintenance responsibility
- A preset format to help guide and focus your analytics development.

**Outsourcing CONs:**

- Usually a higher initial and long term capital investment.
- Control of project is dependent on the cooperation and reliability of the third party vendor
- Lack of sole proprietary ownership of data
- More rigid and less customizable platform

Please consider that for every PRO and CON there is a counterpoint. For example, you may notice that the more rigid Third-party platform offers both a more focused output, but also limits how much customization or enhancement you can do. 

The decision is very much dependent on your team's strengths and what financial and time investments you are in a position to make. 

In the end, if it is cheap enough to use the third party that is reliable and provides the service you need, it is good to go that route initially. Development can always be done later, but the investing in in-house development can often become quicksand.

**Anecdotes:**

- **Cautionary Tale (applicable for either in-house or third-party projects):** There is a project in my department going on 6 years now with no delivery. This tool, being developed with a third-party developer has had no delivery and does not have one in sight. This project, to replace an in-house RFQ system, has resulted in the termination of the upkeep in the existing tool because no one wants to invest in fixing the current system when the new system is "on its way". So the tool slowly deteriorates, effecting current work. This tool has also consumed so much capital investment, abandoning it is a financial/political nightmare everyone refuses to consider.
- **Positive In-House Experience:** I myself have developed lots of in-house tools for my own use, and am currently managing a project to develop a enterprise pricing tool. The development helps build a more intimate understanding of the data and business processes. Customization allows you to achieve greater benefits from changing layouts and methodology.
- **Positive Third-Party Experience:** I manage several Third-Party web-scrapping arrangements. Those vendors that are dependable, offer good customer service, and reasonably priced are a pleasure to work with. They help by providing specific expertise and prebuilt tools.

**Note:** In your question it was unclear if you have considered using a third-party vendor, rather than a tool. For example, I work with a vendor that has pre-written scrape algorithms for specific sites I require data from. I provide them with the terms used to navigate to the specific data I need, but they provide both the GUI, code and processing resources (i.e. servers to run and store the data). They then provide us the data in a template output file. I am not familiar with Mozenda, but at first gglance it looks like just the tool. You may want to consider what requirements you might need to still invest in (servers, computers, bandwidth access, etc.).




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
