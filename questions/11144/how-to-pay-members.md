## How to Pay Members

- posted by: [BrettFromLA](https://stackexchange.com/users/2813127/brettfromla) on 2016-09-15
- tagged: `payment`, `revenue`, `profit-sharing`, `online-store`
- score: 1

<p>I'm considering a business model similar to online t-shirt sites:</p>

<ul>
<li>Members upload art to the company's site.</li>
<li>Site visitors pay the site to have the art put on a t-shirt and mailed to them.</li>
<li>The site pays the member a portion of the money.</li>
</ul>

<p>I'm wondering about that third part, paying the money to the original uploader of the art. How is it possible to automate this, assuming electronic payments (with the option of a paper check that is printed &amp; mailed)? What are the tax considerations? Is there anything else to consider?</p>



## Answer 11958

- posted by: [JonnyZoo](https://stackexchange.com/users/4074587/jonnyzoo) on 2017-01-21
- score: 2

<p>I think there are two questions/problems hidden in the original question:</p>

<p>1) technically. Use any of the popular payment services. They are well proven. But keep things save at your side to avoid faulty transfers etc. (+ hackers etc)</p>

<p>2) the more interesting one in my opinion is the process. Depending on what you choose on 1) you have several topics to consider:</p>

<ul>
<li>liquid funds: if you pay the users portion directly after the customers purchase the money is gone. There are problems with transfer refunds, product returns and finally the amount of money on your account which works as a buffer</li>
<li>transfer fees: the payment service will likely charge per transfer. You don't want to transfer micro portions multiple times a day. I assume the user additionally don't want to have to many single transactions on his bank account</li>
<li>official stuff. taxes, invoices, accounting.</li>
</ul>

<p>There are nice ways to profit in this process, help the user and master this. Mainly I would suggest a "payout" option for the user. The user collects all portions on his virtual money/credit account at your platform and can cash out with a single click. This solves some of the previous topics. Additionally you could have a minimum cashout amount to be save regarding high effort for nothing. And some user will never cash out... :-)</p>

<p>Try find the right solution for the process, then rethink the question.</p>



## Answer 11152

- posted by: [László Kovács](https://stackexchange.com/users/9064103/l-szl-kov-cs) on 2016-09-16
- score: 0

<p>You're looking for a service like Stripe Connect: <a href="https://stripe.com/connect" rel="nofollow">https://stripe.com/connect</a></p>

<p>Stripe is a credit card and payment processor. It seems to provide everything you're asking for.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).