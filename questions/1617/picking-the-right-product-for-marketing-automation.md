## Picking the right product for marketing automation

- posted by: [chubbsondubs](https://stackexchange.com/users/51881/chubbsondubs) on 2014-12-12
- tagged: `marketing`
- score: 6

<p>I'm a developer.  I need to setup some marketing automation in my product such that when new users come into my app I want to put them on a program that I will market to them as a new user.  So for example, someone signs up a free trial.  I send them the welcome email with some instructions on what to do next.  Based on what they do in the app, like if they  complete some tasks in my app I want to send them another email telling them what to do next.  If they don't complete these tasks I want to send them a reminder, etc.</p>

<p>Now I could certainly program all of the behavior myself which would make this a stupid question. But, I'm trying to evaluate products I could use that might help with this task.  My main objective is to allow marketing to modify the look and content of the email, but I'm wondering how much of the logic could I push to them.  If I can let them handle some of the logic then that makes the solution more flexible as the campaigns change.  If I simply handled all logic and let them only handle the email being sent it's a clear division of labor, but that means when they want to tweak the rules I have to go change code.</p>

<p>Currently marketing is using Mailchimp already and I've looked through their API, but it's mostly focused on maintaining email lists which I'm not sure that's the best idea.  I think with Mandrill I can quite simply have a series of templates that I maybe able to choose from and I would direct which template to invoke (simple division of labor case).  After staring at their docs it's not clear if this is the best choice.</p>

<p>So I started to look at others Hubspot, etc.  But I got so tired of reading their marketing speak about a marketing product I wanted to shoot myself.  I just need the straight dope from a technical person about what is the best way to approach this without all of the marketing BS.  I want someone to talk to my situation.  Can anyone give me some guidance on what they did to accomplish this?  What products did you use and how did you use them (ie what is your division of labor in logic vs look)?  How did you use their API to integrate with their product?</p>



## Answer 1620

- posted by: [okoboko](https://stackexchange.com/users/4542446/okoboko) on 2014-12-13
- score: 4

<p>You want to look at Intercom.io (<a href="http://intercom.io" rel="nofollow">http://intercom.io</a>) or Customer.io (<a href="http://customer.io" rel="nofollow">http://customer.io</a>).</p>

<p>A number of SaaS products use these tools for onboarding, behavior based messaging, and in-app notifications/announcements.</p>

<p>I saw this last at Pingometer (<a href="http://pingometer.com" rel="nofollow">http://pingometer.com</a>) which is the uptime monitor for all of my servers/websites. When I first signed up, I got an email welcoming me. I didn't log in for a few days and got another email saying they missed me. Then, I logged back in and setup my first monitor to keep an eye on a server. A couple days after that, I got a personalized message introducing me to features I hadn't explored yet. Pretty cool...</p>

<p>To implement both products, you basically push a bunch of tags/events via their API.</p>

<p>Example:</p>

<ol>
<li>Login (Push "Login" Tag)</li>
<li>Click Dashboard (Push "Dashboard" Tag)</li>
<li>Click Pricing (Push "Pricing" Tag)</li>
<li>Use Feature #1 (Push "Feature #1" Tag)</li>
</ol>

<p>You can create rules to trigger automated emails (e.g. all users who completed #1 and then completed #4 within X days get an email about other features to try).</p>

<p>The trick with implementation is to push tags for almost all possible actions in your application.</p>

<p>This way, you don't need to define the rules right away but the data is there if you need/want it later.</p>

<p>You manage everything (rules) from Intercom.io or Customer.io and don't have to mess with the code on your side later on.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
