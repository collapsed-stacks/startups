## Reasonable rate of online user-account validation?

- posted by: [thequeue](https://stackexchange.com/users/209929/thequeue) on 2014-09-30
- tagged: `service`, `cloud`
- score: 5

Launched some cloud-based software available to the general public. Accounts are required for software use. We have a typical account-creation process: enter name, email, password -> verification link is emailed to user -> account is activated on click of link.

About 20% of people that create an account don't click that link (account stays inactive). Reasons include spam folders, bad address, user-incompetence, loss of interest, etc.

Is this rate of 20% acceptable? It seems pretty high to me but I have no basis of comparison.

As far as numbers of emails, there are about 10,000 activated accounts and 2,000 lingering un-activated accounts. ~400 of the 2k were returned as "mailbox not found" types of error. Aside from this, we can only guess the reason why someone wouldn't activate. Just looking to see if there's a general acceptable rate of account activation?


## Answer 850

- posted by: [JR Warren](https://stackexchange.com/users/1866317/jr-warren) on 2014-09-30
- score: 3

Percentages are going to vary based on the niche, particularly how familiar people in that niche are with this standard account verification process, and how dedicated the sign-ups are to wanting to try your service.

If they're only mildly interested, it's not uncommon for someone to think, "Oh, I have to sign into Yahoo, find that email and click the link. I won't waste my time." or "Oh, I'll do it later."  The "do it later" ones are almost as bad because they rarely do (out of sight out of mind).

That said, in my experience 20% isn't a horrible number. 

In the email marketing world, I've heard numbers quoted between 10-40% of users not confirming their email addresses when they subscribe to a mailing list. Obviously signing up for an email list is slightly different than signing up for a software service, but I would still expect some correlation in the numbers.

With my direct experience for my company, I crowd-funded before my website was live. Then I directed people to sign up on the website after the funding campaign was over. I don't have hard numbers off hand for the amount of confirmed/unconfirmed emails for those that signed up on the site, but I wouldn't be surprised if it was 15-20% - and this is from people who have already given me their money. So I know their committed to actually signing up. I've gotten feedback from a lot of them later on saying they mean to do it later and just never did.

On a different train of thought, you may also be seeing SPAMmers signing up with automated software hoping to find somewhere to post a message or a link. This is especially likely if you have any kind of forum or blog that requires a signup to comment on the SPAMmers have software the sniffs out footprints of blogs, forums, wikis, etc and automatically signs up and posts a message. If they don't have it set up right, it might not be confirming the email (though the software is certainly capable of it).

That last bit may or may not apply depending on how your site is set up.


Other things you might consider to help lower the number:

 - You could try putting a little message next to the email box on the
   signup page that says, "Make sure this is valid. We'll send you an
   email once you sign up to confirm your identity." Or something like
   that. That sets the expectation before they even sign up that they are going to need to check that email account.
 - Put a message after the signup is complete saying, "Hey thanks for signing up. We just sent you an email with a link in it. Go click that link to activate your account and access this incredibly fantastic software that you're itching to get your hands on!"
 - Make sure the email subject and body are both clear (as well as the "from" name/address being recognizable as you). Make sure the content of the email guides the user to click the link (not distracting by talking too much about other stuff - this email has one key purpose).
 - Make sure the email works and looks good in text only email clients (really that should be a rule for any email correspondence).
 - Make sure whatever email server/service you're sending from is not on a bad domain/IP address. A bad reputation will land you in spam folder consistently.

Obviously I don't know which of those things you may already be doing and they'll need to be customized to your specific situation. But the key is to set the expectation, remind them, and help keep them focused all along the way until you actually get them to click that link.

**EDIT:**

Based on the information you added that 1/5 of the unconfirmed email addresses were bounced as invalid, I would wonder if you're either getting spam signups hoping to get in without the hassle of using a real email address. In which case something like a captcha or other turing test may help. Or it could be real people signing up again, hoping not to use their real email address, in which case setting the expectation during signup that you will be sending a confirmation email may be helpful.


## Answer 851

- posted by: [blunders](https://stackexchange.com/users/216182/blunders) on 2014-09-30
- score: 2

<p>Any requirement to validate users will result in meaningful losses at every point in your conversion funnel. </p>

<p>Beyond that, industry stats are meaningless in my opinion, since I beat them all the time and stopped trying to figure out why a long time ago. The very idea of something being acceptable should be based on your performance, not others. Meaning optimize this aspect of your funnel until your efforts are better spent somewhere else.  </p>

<p>That said, there nothing wrong with learning from others and seeing if it applies to you. For example, <a href="http://baymard.com/blog/simplifying-sign-up" rel="nofollow"><strong>19 Ways to Simplify 'Sign Up'</strong></a> or <a href="http://www.marketingsherpa.com/article/case-study/triggered-emails-that-target-conversion" rel="nofollow"><strong>Email Marketing: Triggered emails that target the conversion funnel boost revenue</strong></a>:</p>

<blockquote>
  <p>GamersFirst was able to get an additional 3.75 paying customers for
  every 1,000 validation reminder emails it sent, or a 0.38% conversion
  rate. At an average customer lifetime value of about $125, that's $469
  for every email sent.</p>
</blockquote>

<p><strong>To answer your question though, 20% appears to below the norm, which is 25% based on my understanding.</strong> Your hard-bounce rate seems a bit high, if you don't have inline email validation baked into the form, that would be the first step in attempting to address this issue; I would not add a CAPTCHA, since in my experience this will just result in losing real users.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
