## What tools and software are used to create a new social network?

- posted by: [WebBeing](https://stackexchange.com/users/7120461/webbeing) on 2015-10-14
- tagged: `software`, `website`, `web-development`, `social-networking`, `programmers`
- score: 0

<p>I have an idea. It is a pretty simple idea, it something I need and I cannot find on internet, and I believe that  people around the world need it. 
That said, I can find on internet very similar web sites to the one I have in mind, but they provide different services from the one I want. </p>

<p>The social network has two different users: those who give the service (retailers) and those who use the service (customers).  Structurally, it is very similar to airbnb or uber or many many websites. It does not need (for the moment) of a mobile app or heavy data analysis, but just social networking. So, I think there are tons of software already ready to create this website. I can develop software, so I'd like to create an alpha of the website before looking for partners. <strong>What software and which kind of hosting service do I need to build such a website?</strong>
This is a preliminary list of thinks that (I guess) have to be done:</p>

<ul>
<li>Find the right hosting service (<em>Do I need of AWS-like services or a standard hosting service with php+mysql could be enough?</em>) </li>
<li>A possible way to manage suggestions can be through neo4j.</li>
<li>Manage multiple languages  (<em>is there a specific software for this?</em>). in particular I would start with my local language and English and eventually cover the most frequent languages.</li>
<li>I thought to use PayPal as the simplest way to allow customers to pay for the service, and then the website to pay the retailers.</li>
<li>what language should I use to develop the server-side website? (<em>php, node.js, ruby on rails, python?)</em> I have no idea. </li>
<li>Buy a domain</li>
</ul>

<p>I believe the smarter way to start is finding a something already developed for this kind of websites. </p>

<p><strong>Does exist a software that, like WordPress for blogs, allows to create a social-network quickly and efficiently?</strong> </p>

<p><strong>Can you suggest a more effective list of TODOs?</strong></p>



## Answer 7553

- posted by: [Sebhastien](https://stackexchange.com/users/6116817/sebhastien) on 2015-10-14
- score: 1

<p>Although I think it is possible to create such a network on Wordpress, I think customization would be very limited. You can use plugins like bbpress.</p>

<p>However, I think your best solution is to find some one who knows some basic Ruby on Rails.</p>

<p>An alpha version of a site like this can be built in less than 24 hours Using Ruby on Rails. My To Do list would go something like: </p>

<ol>
<li>Find someone that knows/or learn Ruby on Rails</li>
<li>Create a quick user flow chart to plan how users will use the site</li>
<li>From the user flow chart, create a basic Wireframe of the site to create a structure</li>
<li>Create a basic design using Bootstrap. (Just cause it is an alpha doesn't mean it has to be ugly.)</li>
<li>Create the site in Rails. Using some basic gems:

<ul>
<li>Devise Gem for User Authentication (Create user accounts)</li>
<li>CanCanCan gem for User Authorization (Create abilities for Retailers vs Customers)</li>
<li>Bootstrap &amp; Font Awesome gems (Add quick styling)</li>
<li>Stripe gem (Accepting payments)</li>
</ul></li>
<li>Host your alpha for free on Heroku.com. That way you can hold off on buying a domain name and paying for hosting until you have your first beta vesion done.</li>
</ol>

<p>I hope this helps.</p>



## Answer 7567

- posted by: [Luke Gedeon](https://stackexchange.com/users/1119600/luke-gedeon) on 2015-10-15
- score: 1

<p>Probably worth mentioning that BuddyPress will turn WordPress into a social network, with a ton of customization options. <a href="https://buddypress.org/" rel="nofollow">https://buddypress.org/</a></p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
