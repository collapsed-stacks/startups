## How to send an email to thousands of potential customers and customize its contents?

- posted by: [mstoldt](https://stackexchange.com/users/3543049/mstoldt) on 2015-09-09
- tagged: `marketing`, `email-marketing`
- score: 1

<p>Good morning everyone,</p>

<p>I am starting my SaaS platform soon and created a database with ca. <strong>5.000 potential Customers</strong>. The name of their company, the name of the person who I would contact and his E-Mail.</p>

<p>I have a <strong>template</strong> for an email. The subject is like "use MyAwesomeTool at YourCompanyName". The E-Mail starts with Dear PersonResponsible, and as an attachment I've got a PDF-File, also personally adressing the person in charge. </p>

<p>Is their a way to <strong>automative send everyone</strong> of these 5.000 potential customers an email, changing Mail-Adress, Company-Name and the person in an PDF-File and the E-Mail?</p>

<p>I have absolutely no clue. </p>

<p>Thank you!</p>



## Answer 7315

- posted by: [hyperN](https://stackexchange.com/users/1342945/hypern) on 2015-09-10
- score: 3

<p>We are sending around 300.000 emails weekly to people who are subscribed to our newsletter, and we are doing it using Mandrill (it is much cheaper than Mailchimp - same company is behind both products), and as you can send 12.000 emails per month for free, it would cost you nothing ! And of course, you can completely customize content of the emails</p>

<p>Only catch is that you have to know a bit of programming, but there are a lot of Mandrill libraries for various languages, so it is pretty easy thing to do. If you know C# I could send you our code, it's basic stuff.</p>

<p>And about changing PDF-s, we are doing this, but also programmatically, so again, I can only help you if you know C# </p>



## Answer 7313

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-09-10
- score: 1

<p>It's possible but there are much better ways to do it. The term you're looking for is cold email, and there's more to it than just crafting a template and blasting your list.</p>

<p>First off, get proper software as it helps a lot with automations. You need a direct mail tool or an auto-responder that lets you easily strip out or segment users who reply. A text expander also helps. For instance <a href="http://directmailmac.com" rel="nofollow">Direct Mail</a> and <a href="http://www.trankynam.com/atext/" rel="nofollow">aText</a> if you're using a Mac. <a href="https://close.io" rel="nofollow">Close.io</a> is a good tool for follow-ups once they do reply.</p>

<p>Next, prepare not one but 6-8 templates as a series. Because you'll want to follow up multiple times to get your prospects' attention. Sometimes your emails won't get read the first few times. Keep trying over the course of a month or two and you'll eventually become a familiar name in their inbox. They'll ultimately look at what you have to say. And ask you to stop if they really have no interest - comply. Some good reading on the topic:</p>

<p><a href="http://growtheverywhere.com/sales/cold-email-response-rates/" rel="nofollow">http://growtheverywhere.com/sales/cold-email-response-rates/</a></p>

<p><a href="http://salesfolk.com/blog/how-to-write-cold-emails-human/" rel="nofollow">http://salesfolk.com/blog/how-to-write-cold-emails-human/</a></p>

<p><a href="http://blog.close.io/how-to-improve-your-cold-email-response-rates" rel="nofollow">http://blog.close.io/how-to-improve-your-cold-email-response-rates</a></p>

<p>It goes without saying that you should not be writing uninteresting gibberish or salesly fluff. You're going to be emailing people who have little time on their hands. Respect them. Get to the point. Keep things focused. And don't forget to put the next step forward - aka a phone call.</p>

<p>Last, you actually <em>don't</em> want to blast it all in one go. You ideally want to get their attention before emailing. Ideally you want a proper referral who tells them you'll be in touch - network your way in. When you can't, there are plenty of options. You can retweet them or comment on their blog with <em>useful</em> insights a few times or something to that effect. A PR push or three helps too. Another one that works very well is to send a direct sales letter using snail mail. Use a normal stamp rather than automated billing and toss in some kind of small goodie inside the envelope (e.g. a poker chip) to prompt them to open your letter. Point is: make them aware of you; <em>then</em> email.</p>



## Answer 7309

- posted by: [mustaccio](https://stackexchange.com/users/1270839/mustaccio) on 2015-09-10
- score: -1

<p>Is there a way to do this? Certainly yes. Google "mail merge" for more information.</p>

<p>Should you do this? Certainly no. In addition to being ethically questionable, your proposed action:</p>

<ul>
<li>can result in your email address being blacklisted by the recipients or your internet service provider, or both;</li>
<li>may be deemed illegal in some jurisdictions. For example, in Canada you could be fined <em>for each incidence</em> of unsolicited email (which yours definitely would be).</li>
</ul>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).