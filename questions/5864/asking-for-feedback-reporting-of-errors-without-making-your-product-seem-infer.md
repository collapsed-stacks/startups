## Asking for feedback (reporting of errors) without making your product seem inferior

- posted by: [Charitoo](https://stackexchange.com/users/5938527/charitoo) on 2015-07-28
- tagged: `product`, `communication`
- score: 1

<p>I have been programming for some time and I have created this software I would like to sell to educational institutions. The problem is how to request for feedback and <strong>errors reporting</strong>(mostly) without making the product seem error-prone.<br>
I don't have a server to send error reports to so I can't do internally in the software. The error reporting will have to be in the form of emails or phone calls. Any ideas.</p>



## Answer 5867

- posted by: [Mowzer](https://stackexchange.com/users/1803081/mowzer) on 2015-07-28
- score: 0

<h3>Use a good tool to collect bug reports efficiently</h3>

<p><a href="https://www.google.com/forms/about/" rel="nofollow">Use Google Forms</a>.</p>

<p>It replaces the need to use your own server. Just create a form to collect the error reports, then put a discreet but visible link to it in your software.</p>

<p>I don't think there is a special way to ask to report errors without making the product look error prone. Those are two separate issues.</p>

<hr>

<h3>How to get users to report errors</h3>

<p>You get the users to report errors by asking them to report errors and giving them a convenient way to do so. Convenient in my opinion is a link to a form. Not an email address or a phone number. Not for you to manage it that way, anyway.</p>

<hr>

<h3>How to make the product not seem error prone</h3>

<p>You fix as many bugs as you can as soon as you can. For this, you have to know about them. Which means the users have to report them. There is no way to mask the bugs. The clients will see them and know about them before you do. Which is why you need them to tell you about them.</p>



## Answer 5884

- posted by: [Ali](https://stackexchange.com/users/2815644/ali) on 2015-07-29
- score: 0

<p>This seems more like a programming question that should be on stackoverflow. But there are many methods of error reporting and they can be configured to do it automatically or manually. </p>

<p>If you do not want to bring attention to the error, the best way would be to do it automatically or with less interactivity. In your case, a good way would be to configure have the exception handler to report using SMTP or similar means. That way, the system can send the error report to you via email without user interactivity. You can use the SMTP server linked to your domain name or you can use something like GMail - <a href="http://lifehacker.com/111166/how-to-use-gmail-as-your-smtp-server" rel="nofollow">http://lifehacker.com/111166/how-to-use-gmail-as-your-smtp-server</a>. There are several exception handling packages like <a href="http://www.madshi.net/" rel="nofollow">http://www.madshi.net/</a> that can do this.</p>



## Answer 6005

- posted by: [zazaalaza](https://stackexchange.com/users/4672194/zazaalaza) on 2015-08-10
- score: 0

<p>Go to <a href="http://freelancer.com" rel="nofollow">Freelancer</a>, post a contest in the testing section and offer a bounty for the most comprehensive error report.
This way you'll get multiple error reports and you'll only have to pay out the bounty to one person.</p>

<p>Similarly you can use <a href="http://betalize.com" rel="nofollow">Betalize</a>, they have testers signed up ready to dissect your product.</p>



## Answer 6009

- posted by: [MSLV](https://stackexchange.com/users/2242446/mslv) on 2015-08-10
- score: 0

<p>Education market is huge. </p>

<p>Potentially, there are thousands of clients waiting in line for your product. Identify a few and give them your product/service free of charge <strong>in exchange for their honest feedback</strong>. </p>

<p>Position/market your offer wisely: few people will be interested in testing <em>someone's buggy prototype</em>, but getting access to an <em>early beta version</em> just sound a whole lot better. </p>

<p>Not only you'll be able to get feedback that <em>you</em> need - you might tap into real clients that will have their own ideas (aka <em>features</em>) on how to improve your product and, this time around, they'll be much more <strong>willing to pay</strong> very real money for it. </p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
