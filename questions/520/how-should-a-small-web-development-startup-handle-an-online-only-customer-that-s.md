## How should a small web development startup handle an online only customer that stops communicating once the bill is sent

- posted by: [Nick Wilde](https://stackexchange.com/users/454046/nick-wilde) on 2014-08-28
- tagged: `united-states`, `canada`, `web-development`
- score: 14

Generally for online only clients I provide a maximum of 2 hours work before requiring at least the initial payment. However for some clients that is the total amount of work (or more) in some of those cases I have had clients that stop communicating as soon as the bill is received. I am located in Canada some of my clients are located in the US (but they could be pretty much anywhere).

I don't have a deal with any debt collectors and I suspect that may be not very effective for recovering small amounts (less than $75). I generally do still have access to the hosting/FTP/webadmin for the client. So my question is kinda three questions:

- Should I hire a debt collector?
- Should I put up a notice blocking their site until they pay? (ie I have the ability but are there any legal problems with doing so? (given that I have a papertrail showing an unpaid bill)
- Is there something else I should do or should I just write it off?


## Answer 524

- posted by: [JezC](https://stackexchange.com/users/87431/jezc) on 2014-08-28
- score: 9

IANAL and IANADC (I am not a debt collector). IME, if you pursue a US business for unpaid debts, they will take into account the costs of pursuing the debt. You'll get a fraction of the amount owing, and that's if they have reasonable belief that you will turn up in a US court, as a furriner, to pursue a debt with a solid paper trail. IME, US Courts don't like furriners, so you need a very solid paper trail demonstrating that the client understood that a payment was involved, clearly accepting that the work had been completed satisfactorily, that there was no dispute over the quality of the work, and then refusing to pay. IOW, unless there are serious sums, don't bother with small debt collection (under six figure sums) in the USA. For me, that means I don't work for US businesses from outside the US, any more, unless they prepay.

Given the proximity of the US and Canada, you might be perceived as having a higher likelihood of pursuing a claim. There may also be mutual agreements between the US and Canada, to protect trade. I don't know. Can't usefully comment on that.

For other jurisdictions, also no idea. I haven't had this problem with EU clients (Germans and French both pay on time, IME), and UK law is pretty defensive for UK based small businesses and reluctant established businesses in the UK. 

My recommendation is that international customers should prepay for work. You can say that Canadians get your great offer. Everyone else pre-pays. Unless you find that the fraction of US defectors is small enough to write off as a cost of doing business. If you only lose a few percent per annum to US defaulters, just up your prices to the US by a few percent.

I'll be interested to see what other approaches people have adopted and recommend!


## Answer 528

- posted by: [Haakon Dahl](https://stackexchange.com/users/1782291/haakon-dahl) on 2014-08-28
- score: 6

Regarding your question and not your proposed answer, I would communicate relentlessly but very politely.  After all, your desired end-state is a satisfied paying customer who repeats business and refers others.  If the customer is happy with the service but has been (literally) embarrassed for funds, consider simply forgiving the debt.  It sounds small, and while you are a hungry startup, the fact that you are a startup means you are hungrier for a loyal customer base than for mere cash.  Customers bring cash and not the other way around.

Ask if there is any problem with the service.  Ask if the customer would like to change anything about the agreement.  Ask if the customer needs some additional time to pay.  Finally, offer to forgive the debt if it means keeping a paying customer who needs to not pay one time.  It just happens to be the first time, and from then on, you would have no trouble asking for payment up front.


## Answer 1047

- posted by: [SilentSteel](https://stackexchange.com/users/1092182/silentsteel) on 2014-10-19
- score: 4

I had been in this exact situation in my last Canadian-based business. It was also SaaS.

**NOTE: The advice here applies to B2B businesses since that was my space; not consumers.**

At first I was simply too nice and fearful of losing customers. But this turned me into the last guy who gets paid. I then decided to have super-strict policies and this helped a lot. So long as policies were not firm, **I kept being the last in line to get paid**.
 
**In sum, after well-over 7 years of experience, here are some steps:**

 - The basic math is- if they have 0 employees (or are a consumer), they may be struggling. Try to work out a specific deal with them. (Ex: If they owe $100, then automated payments of $25/month over 4 months.) If they have one full-time employee or more, then they **do** have cash but are choosing **not to prioritize paying you**. This is because a salary is thousands per month. So if they are paying an employee well over $1K/month, they can afford your invoice.
 - Use an automated billing platform- even if you have almost 0 invoices. Followup work is insane. Some options: FreshBooks, Wave Accounting, Billing Orchard, WHMCS, Plesk Billing. Automatic reminders is a must.
 - On your website's "about" or "contact us", have clear instructions on how to make payment. Ensure your legal name and mailing address is up-to-date. Companies will require this to both issue payment and enter you into vendor databases. Often AP staff have no time to call and will just send a cheque to this address.
 - If B2B, charge late fees at the highest legal rate. (I believe this was about 27%/year in 2013?). **Only** if your customers are businesses, not consumers. This can be done automatically using Freshbooks. If you don't charge late fees, you're giving **no incentive** for the AP department to prioritize your invoice.
 - Send a disconnection / late fee notice the date after the invoice is overdue. Again, this can be automated using FreshBooks or a similar system.
 - Disable the account once the invoice is over 45 days. But do not put up a nasty message on their website. Simply disconnect. Maybe a generic message like "Please contact support for assistance in restoring this website." You'd be shocked at how quickly people pay. Sometimes we figured the customer wasn't using it and they chose to just never pay. But then they'd instantly react once being disconnected.
 - Indicate in the 45 day notice that overdue invoices may be sent to a collections service. If you deal with individuals and not businesses, I'd probably skip this step. Since we were 100% B2B, it was fine.
 - You can find small business collection agencies out there. Truth be told, we never needed one once we became strict and got better at collecting. Still, in retrospect, we should have gotten one since there are definitely some cases I can think of where businesses really did screw us out of what they owed, despite having money.
 - Remember for **large** US vendors, they may need a W8 form. (Only provide if asked.) If they ask for a W9, tell them as a Canadian you provide a W8 instead, as a foreign entity.
  
**In the Case of Consulting**

I did this when younger. Some tips:

- I would advocate trying to get partial payment in advance, even if it's $1. Do not wait long before collecting your first big payment.

- You can also do things like collecting first+last month's costs from customers who tend to pay late. Or, from all customers. Not always possible. Depends on what you offer.

- Use RightSigniture to quickly get people to sign any sales contracts. Tho it's easier to collect first+last without a contract than get a signed contract.

- Never overpromise. For new customers with ambiguos work, charge by the hour until you're confident in your customer. Why? Because a job like 'making my website' could actually mean programming an entire startup. It's too ambiguous.

- As a consultant, beware of people who withhold payment until after you improve something. They often plan to never pay, or will then say it was not delivered on time. It's not realistic. Example: You build them a website suitable for their budget, but then they want a shopping cart feature, or only want to pay after adding another 7 hours of work. If this ever happens, sometimes it's better to ask them to pay 50% now and 50% afterwards. Unless the pay is amazing, I'd often then not deal with those people again.

**Background: There are 3 reasons customers pay late:**

 - They are a big business and the accounts payable department is a mess. This is very common. AP staff are often overburdened. They often have outdated payment and mailing info, and they often have only 1 way of doing things. (Ex: They can only pay by Amex, and as a Canadian, that's hard to accept. Was a classic case for us back in the day.)
 
 - They are a small business and they don't intend to pay rapidly, or at all. Depending on your target market, this can be common. Often I find they do pay, but unless you demonstrate strict policies, it happens late.
 
 - They are a large company going bankrupt. Really, really rare. Even so, in this case you'll often get official documents from a bankruptcy lawyer in the end. You may be able to recoup some of the invoices. They may use delay tactics until news is official but never assume this is the case.


## Answer 522

- posted by: [sandman](https://stackexchange.com/users/194597/sandman) on 2014-08-28
- score: 3

For me, legal things are always the last resort. So far I did not have to use any. I usually push reminding messages in a polite manner until they pay. 

But this will not work for the clients you don't have history with. With them I either use 1-week upfront or some percentage upfront. If the work is hourly, register at some freelancing service and do hourly work. All of them have hourly protection which means that they will forcibly charge the client. 

In your case, I would not hire anyone. A couple of hours is too little money. I would try to push the client via his website. I am not sure if there are legal consequences if you block entire site - maybe there are since you did only part of it. Maybe you can revert your work? That way he will not get your work - a small satisfaction in case he does not pay you. 

There are also other things you can probably "disable", but thou they are not illegal, they are not ethical. 

In future, have one policy for new clients, and another for old clients. 


## Answer 525

- posted by: [George](https://stackexchange.com/users/3516499/george) on 2014-08-28
- score: 3

This is an important point for many people here and it highlights the need for a carefully worded contract at the onset.  If you have the ability to withdraw the service if the customer does not pay (i.e. shutting the site down) then that is a great tool to include in your original contract.  This way you will make it clear that they are required to pay and will not be able to get the service for free by avoiding to pay you.  It's always best to disclose as much info as possible in the beginning and to think of all scenarios even though you hope they never occur.

As for your current problem, going though a court system will take 2-3 years and will involve significant costs, and an in person appearance.  You may not have a legal standing to sue the person in the US and it will actually depend on the state that customer is in.  You may be able to sue them in Canada, but there is no way for you to force them to pay you unless they step foot in Canada.

You could try a debt collector to have them call the individual at their home, but you need to be careful of harassment otherwise this customer could sue you.

You could amend the current Terms of Service with all customers and add in something that says you have the right to block service and post a notice on the websites saying this site is suspended until the owner pays for web design fees or something along those lines.  It could offend people and be a turn off though.

The easiest thing here is to write off all of the work and lost revenue as a bad debt for tax purposes.  


## Answer 530

- posted by: [ATrubka](https://stackexchange.com/users/1052629/atrubka) on 2014-08-28
- score: 2

In my opinion, generally, you won't be able to recover any funds. Especially, if the client didn't get any gain out of this relationship. That's your cost of doing business unfortunately.

In order be less vulnerable, I believe you have to adjust your business model and expectations a little bit.

As a service provider, I believe you should be prepared to make certain efforts towards customer's satisfaction without expecting a payment. Doing so you will be able to attract more clients and eventually make more money.

At a certain point you have to start charging your client for your services. I believe it should be at the point when the client is already hooked either by your technology (if you have any) or simply by the amount of time he invested in communication with you.

You still have to expect that you might not get paid for your services. Thus you have to make sure the client doesn't get much from your efforts until he pays. If you're a designer, don't send quality images or vector graphics until paid or unless you have long history with the client. If you're developer, don't upload/checkin the final solution before the money. This would be a motivation for the client to pay.

The section below is best understood when you look at it from the client's standpoint.

You also have to be prepared that the client walks away. At that point he doesn't need your services anymore. If you've ensured what I mentioned in the previous paragraph, then this means he's walking away with nothing. It probably means that he didn't like your service. That's what you would do when let's say you're given a bill that's twice higher than a sales guy promised. Or when you realize that you're just wasting your time with someone.

The most practical step at this point would be to think how to improve your service. Problems may reside in its quality, pricing model, communication, delivery time, etc.

I hope it was somewhat helpful and not too offensive.



## Answer 549

- posted by: [josinalvo](https://stackexchange.com/users/1128108/josinalvo) on 2014-08-29
- score: 2

<p>This is a well known <a href="http://vimeo.com/22053820" rel="nofollow">video by a webdesigner</a> (aka: 'fuck you, pay me'). He knows what he is talking about.
Despite sounding aggressive on the title, he gives very good, very practical, non-aggressive advice in the video</p>

<p>One thing I remember and you might use: until payment, do not transfer IP.
Preferably (this is me now, and I don't know anything. He does though =P) don't even transfer control of the server/app/whatever.</p>

<p>Another thing is to receive payments spaced for the duration of the project (pref. just after deliverables)</p>

<p>But seriously, go watch the whole thing</p>



## Answer 566

- posted by: [rollingBalls](https://stackexchange.com/users/3720453/rollingballs) on 2014-08-30
- score: 1

The main issue is that you provide deliverables before payment. To resolve it, simply change your strategy so that if a deliverable can not be protected (e.g. by hosting it yourself if it 's a backend script), you should get paid first.


## Answer 7985

- posted by: [Euan M](https://stackexchange.com/users/2233586/euan-m) on 2015-12-02
- score: 0

**1)** Pre-empt the issue.

Don't hand the deliverables over with the bill.  Hand them over on successful clearance of payment. 

For blogger pages:  

either send them a representative sample with the bill, rather than the entire item;

or send the whole article as a low-res image file.  That way they can read it, but not post it.

**2)** For the clients that have already bolted before you manage to close the stable door: find out how cheaply you can get a boiler-plate lawyer's letter, that you can fill in the client's name and address.

Simply discovering that they are not hidden and anonymous might jar some of them into paying up.

**3)** Finally, be most rigorous with new clients who have not established a history of timely payments with you.  Once they are known reliable payers, you can afford to be a little more relaxed.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
