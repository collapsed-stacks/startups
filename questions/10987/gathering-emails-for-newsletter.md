## gathering emails for newsletter

- posted by: [jav974](https://stackexchange.com/users/1769270/jav974) on 2016-08-23
- tagged: `legal`, `email-marketing`
- score: 1

<p>I built an Android app that requires google login in order to authenticate and continue into the app. The credentials are sent to a backend server of mine (auth token and email).</p>

<p>Now I would like to send newsletters to those email addresses but I wonder if that is legal. I never asked the user about that.</p>

<p>I'd like to know if I can start emailing those addresses, or do I need to ask for permission first?</p>



## Answer 10990

- posted by: [Community](https://stackexchange.com/users/-1/community) on 2016-08-23
- score: 2

<p>The law should be the least of your concerns.</p>

<p>At some point (unless you own an Internet backbone and some unrestricted IP space), you probably agreed to service providers' terms that expressly forbid you from using their network to transfer unsolicited bulk mailings. If enough people complain (which includes pressing the "Spam" button in any major email client), and you have not been strictly compliant with the expectations people have about about email (let alone the law), you may be blacklisted by one of the many organizations like <a href="https://www.spamhaus.org" rel="nofollow">Spamhaus</a>, which can cause your service provider(s) to suspend your service, sometimes without asking questions first. You may also be personally added to an industry customer tracking system shared by many service providers to screen potential customers. (I can't tell you about this system, but I assure you it exists.) If you get blacklisted by the industry, it can be very difficult to use anyone's servers in the future.</p>

<p>Service providers have no greater threat to their business than spammers (or more specifically, accused spammers) and they will not think twice about protecting the reputation of their IP assets.</p>

<p>Google's terms related to you using their authentication system almost surely prohibit unsolicited messaging as well, but I'll leave the exercise of looking that up to you.</p>

<p>Going forward you should obviously start offering the option to subscribe to your marketing messages (newsletters or anything else not strictly transactional). You might also take the opportunity to propt for sign-ups when users next use your app. But don't just start sending messages to which people have not agreed. People care more than you think and the consequences can be harsh.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
