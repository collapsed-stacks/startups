## When should code our own web site, instead of buy one?

- posted by: [john mangual](https://stackexchange.com/users/382049/john-mangual) on 2016-01-02
- tagged: `website`, `e-commerce`, `programmers`
- score: 4

<p>From what I've learned about startups, we don't want to use any more technology then we have to (since it can be costly).  Let's look at a websites.  My options are:</p>

<ul>
<li>build my own website</li>
<li>hire someone to do it</li>
<li>use online service</li>
</ul>

<p>Since I know some HTML and front-end and back-end, I don't like option 2.  So really it's between options #1 and #3.</p>

<p>There are many service which automatically build beautiful websites at low cost, e.g. </p>

<ul>
<li><p><a href="http://www.squarespace.com/pricing" rel="nofollow">SquareSpace</a> (at least $8/month)</p></li>
<li><p><a href="https://ghost.org/pricing/" rel="nofollow">Ghost</a> (at least $8/month)</p></li>
<li><p>Facebook, Wordpress and more...</p></li>
</ul>

<p>And to think about it if I host my own website, server costs are already $5/month and these services offer to do it for you.</p>

<hr>

<p>This is more of a rhetorical point since I know and am comfortable with coding.  But what if I am making recommendations to a client.  There are many business owners who know very little coding - basically <strong>none</strong> and would be willing to spend $100/yr or more to have a website done for them.</p>

<p>How do I explain to clients/business owners the advantages of a coding background instead of hiring a WISIWYG editor?  </p>

<p>It may very well depend on the individual needs of the business, and so this question may not be specific enough...</p>

<hr>

<p>Version of this question exist even if we move further down the chain.  Even web developers now have choices for tools that will do much of the coding for <em>them</em> as well.. but I may ask that separately.</p>



## Answer 8250

- posted by: [Matthew Haugen](https://stackexchange.com/users/1325646/matthew-haugen) on 2016-01-02
- score: 7

<p>I typically just base it off of what's needed out of the site.</p>

<p>I <em>am</em> a web developer, so I might view things a little differently than someone with less experience in the space, but I put site requirements into three buckets:</p>

<ul>
<li><p><strong>Very basic:</strong> we need a website that announces our presence, maybe hosts some static content, but basically just holds the domain name while we wait.</p>

<p>For these cases, I'd typically just write it myself. Simply creating a template website from online can handle much more than this, and you can realistically probably have it done in an hour or two. This lends a ton of freedom down the road to add features that you wouldn't have even thought of.</p>

<p>On the other hand, if someone in a non-technical business came to me on an ad-hoc basis and asked me whether they should pay me to do a basic website or just hire a service, I'd probably suggest the latter. If they ever wanted to change anything, it would make more sense to use a service they could log into, since I wouldn't be around to do it.</p></li>
<li><p><strong>Middle-ground:</strong> we need a website that has everything from "very basic," but we also need some more advanced functionality; a Contact Us page that accepts input, a blog onto which we can post dynamic content (especially this one), and so on.</p>

<p>For these, I typically look at third-party solutions. To address the blogging point, I typically set up the very basic site on my own, then set up a Tumblr blog at <code>blog.example.com</code> and link to it, then theme it similarly (but not so similarly that it's confusing if we change one and not the other). I like that hybrid approach. But in general, there's no use going through the hassle of setting up something that's already out there a thousand times, just to save $3 a month.</p></li>
<li><p><strong>Very complex:</strong> as a web developer, this is more where I live. We need to get into authentication and providing functionality through our own services beyond basic SMTP or blogging.</p>

<p>In this case, I'd be tempted to jump back to the first bucket and write it myself. If a website is a big part of your presence, the difference between writing it yourself and having it done for you is likely not going to be all that substantial compared to your actual product, and if you use something automated, you're likely to have to write your own before you launch too seriously later on, anyway.</p></li>
</ul>

<p>Ultimately, it's just a matter of what you need it to do (something automated will do very little, but will do it well), how much that time is really worth, and what the chances are that you'll have to redo it all in the near future anyway.</p>

<p>On top of that, never neglect the actual finances of the thing. Especially for that middle-ground area. Say it takes you or your developer 2 hours to create a template, set up an SMTP host (or SQL Server) for the contact us page, and do all the administrative overhead on that, and say you're paying $60 an hour for that, you're looking at $120. If you can host it for $5 a month, but a service charges $8 a month, that $120 represents 40 months. What are the chances you won't have to make any technical changes to it within 40 months?</p>

<p>Not to mention, it probably won't require engineering resources to fill in content through a service, although it might to do it yourself.</p>

<p>On the other hand, if you, like me, are comfortable taking an hour or two out of your Saturday to throw together the website without billing the company hourly, that might make more sense.</p>

<p>Just think about how you're going to use the website, how you might end up using the website in the future, what role it will play, and how abundant development hours are on your team.</p>



## Answer 8257

- posted by: [Rakesh S](https://stackexchange.com/users/7563360/rakesh-s) on 2016-01-03
- score: 2

<p>I was in same state of mind when I was working on idea for my website. I did had some technology experience(Java, Php, JS etc). I tried to start with Wordpress or similar template based platform but they did not exactly solved my need. I was short on budget , so didn't hired any full time or freelancers. Finally I hired designer for doing design and HTML/CSS related work and rest I did it myself. So in nutshell, here is my conclusion.</p>

<p>In case you are going to build only information sharing website, then it is better to go with template based solutions like Wordpress or likewise sites. If you are building some thing that is more dynamic, and intend to grow features while you scale , then do make your own portal. Use your technical skills (HTML and other technologies) and hire someone who can compliment your skills to create full blown product.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
