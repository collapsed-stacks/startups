## Asking for feedback (reporting of errors) without making your product seem inferior

- posted by: [Charitoo](https://stackexchange.com/users/5938527/charitoo) on 2015-07-28
- tagged: `product`, `communication`
- score: 1

I have been programming for some time and I have created this software I would like to sell to educational institutions. The problem is how to request for feedback and **errors reporting**(mostly) without making the product seem error-prone.   
I don't have a server to send error reports to so I can't do internally in the software. The error reporting will have to be in the form of emails or phone calls. Any ideas.


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

This seems more like a programming question that should be on stackoverflow. But there are many methods of error reporting and they can be configured to do it automatically or manually. 

If you do not want to bring attention to the error, the best way would be to do it automatically or with less interactivity. In your case, a good way would be to configure have the exception handler to report using SMTP or similar means. That way, the system can send the error report to you via email without user interactivity. You can use the SMTP server linked to your domain name or you can use something like GMail - http://lifehacker.com/111166/how-to-use-gmail-as-your-smtp-server. There are several exception handling packages like http://www.madshi.net/ that can do this.


## Answer 6005

- posted by: [zazaalaza](https://stackexchange.com/users/4672194/zazaalaza) on 2015-08-10
- score: 0

Go to [Freelancer](http://freelancer.com), post a contest in the testing section and offer a bounty for the most comprehensive error report.
This way you'll get multiple error reports and you'll only have to pay out the bounty to one person.

Similarly you can use [Betalize](http://betalize.com), they have testers signed up ready to dissect your product.


## Answer 6009

- posted by: [MSLV](https://stackexchange.com/users/2242446/mslv) on 2015-08-10
- score: 0

Education market is huge. 

Potentially, there are thousands of clients waiting in line for your product. Identify a few and give them your product/service free of charge **in exchange for their honest feedback**. 

Position/market your offer wisely: few people will be interested in testing *someone's buggy prototype*, but getting access to an *early beta version* just sound a whole lot better. 

Not only you'll be able to get feedback that *you* need - you might tap into real clients that will have their own ideas (aka *features*) on how to improve your product and, this time around, they'll be much more **willing to pay** very real money for it. 



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
