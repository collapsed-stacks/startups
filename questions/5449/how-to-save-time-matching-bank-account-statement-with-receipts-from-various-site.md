## How to save time matching bank account statement with receipts from various sites?

- posted by: [Bemmu](https://stackexchange.com/users/5090/bemmu) on 2015-06-04
- tagged: `accounting`
- score: 4

Every month I waste hours logging in to various online services to find receipts that match the transactions in my bank account statement.

**For example** 

I might have a transaction "July 4th, 13.50 EUR amazon.co.jp", so now I have to go to Amazon and try to look at the order list to find the order that would be 13.50 so I can download the receipt. Next, "July 5th, 19.95 USD basecamp" so I log in to Basecamp to find a receipt for that. When it comes to a transaction from Google, it can take me 30 minutes to match the bank transactions with receipts as their services are so vast (app engine, adwords, apps etc.).

Is there a better way? 

I'm already using 1Password to at least make logging in easier, but I still have to navigate each site to find and download/screenshot the receipt.




## Answer 5457

- posted by: [IT Bear](https://stackexchange.com/users/2852545/it-bear) on 2015-06-04
- score: 3

<p>The best way to optimize accounting functions, I've found, is to batch them together so alike tasks can all be burned through all at once.</p>

<p>When it comes to getting the data into your accounting software, this can be split into two basic parts, Collecting the Information, and Entering the Data:</p>

<ol>
<li><p><strong>Collecting information.</strong> This sounds like the part you're having the most trouble with, and to be honest it has never really been a problem for me so it would help to elaborate a bit.</p>

<p>Personally, I've been trained by my workplace and my entrepreneurial father to collect receipts <em>religiously</em> at the time of purchase, even if I don't think I'll need them. This is the most time-efficient way to gather data for one-off purchases.</p>

<p>But it sounds like you're having most trouble with getting the data for recurring monthly payments that hit your bank account automatically? There's not many details to go off of, so I'll just call this what it sounds like: bills. Bills are much easier to predict than one-off payments. They always come from the same company (unless you get an email they've been bought out or are going under), they always come once a month at the same of the month (unless you're doing bi-weekly payments such as payroll), you already know what service it is and thus know how to categorize it (unless you're combining services like internet and phone which I would consider even easier as it's less bills), and payments will be very close to the same dollar amount each month. (unless you're using some scalable hosting option like AWS or Azure, where payments may vary wildly month-to-month)</p>

<p>Now for most bills you should already be receiving the traditional paper envelope each month automatically. If not, call and complain. If for some reason this is not the case, such as with a web service, you should still be able to receive email notifications each month when a payment hits. If not, call and complain. Then simply set up the reoccurring payment in your accounting software so you can track what your bank balance should be <em>before</em> the payment hits, and go back to enter the true details for that month once you have them. Either way, you should have all the details you need already in your mailbox or in your inbox, and only have to sign-in to the site itself in very rare circumstances.</p>

<p>That should solve your "collecting the data" problem. If for some reason it doesn't, we all sure could use some more information as to why.</p></li>
<li><p><strong>Entering data.</strong> For me personally this is the part that takes up most of my time. By this point I'll have a stack of receipts or stack of emails in front of me, so I fire up the accounting software, grab the recycle bin, refill my coffee and run through them one at a time.</p>

<p>I don't know how to optimize this process much more than that. The only thing I can think of is if you wrote some sort of script that would analyze the receipt and put all the data into your accounting database in the proper columns for you, but in my experience attempting to write these "time saving" scripts ends up eating more time than if you had just entered it by hand in the first place.</p>

<p>See these XKCD comics I've always found to be hilariously accurate:</p>

<p><a href="https://xkcd.com/1319/" rel="nofollow noreferrer">https://xkcd.com/1319/</a></p>

<p><img src="https://i.stack.imgur.com/UJRUd.png" alt="XKCD Comic 1319: Automation"></p>

<p><a href="https://xkcd.com/1205/" rel="nofollow noreferrer">https://xkcd.com/1205/</a></p>

<p><img src="https://i.stack.imgur.com/WeRPS.png" alt="XKCD Comic 1205: Is it worth the time?"></p>

<p>In the end this begs the question (as this is something I had problems with starting out) is what degree of detail of this information are you trying to store in your accounting software? Are you getting paper bills or emailed bills, but don't like the degree of information they provide, so choose to sign-in online to see <em>everything</em>?</p>

<p>If this is the case, you may seriously want to reconsider why. Do you really need that much detail? If so, it may be more efficient to use a document attachment column in your database to save the whole .PDF of the receipt. If you don't know, look through the past history of what you've entered already. Looking years back is what helped me realize I was overdoing it and give myself permission to simplify.</p></li>
</ol>

<p>Of course, all of this assumes one thing: that you are using an accounting software. (such as QuickBooks, for my personals I use YNAB. e.g. not Excel) You may not be able to automate the data entry and information collection parts, but a good accounting software <em>does</em> automate all the rest. It will save you more time than any of these techniques I've mentioned.</p>

<p>In the end, take a moment to realize that nobody is coming to take your money without you specifically asking them to. (besides the Taxman) Even if you get NET 30, you know a payment is coming in 30 days. Nothing should be a surprise. So any time you sign up for a service or make a purchase, get the evidence.</p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
