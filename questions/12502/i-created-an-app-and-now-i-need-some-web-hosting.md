## I created an app and now I need some web hosting

- posted by: [Erik Hellberg](https://stackexchange.com/users/9173756/erik-hellberg) on 2017-04-15
- tagged: `website`
- score: -2

<p>Short story, Single person startup from Sweden - I created an app and now I need some web hosting to get a domain name and website for my users. Where should I start?</p>

<p>App:<br>
- Android </p>

<p>Backend:<br>
- Firebase databas</p>

<p>Requirement:<br>
- web site for my users to read info about app and of course my EULA </p>

<p>Future:<br>
- Running service code from the web host to maintenance Firebase</p>

<p>What do you think a good start web host is considering I never done this before?</p>



## Answer 12506

- posted by: [Kev Price](https://stackexchange.com/users/1109274/kev-price) on 2017-04-15
- score: 1

<p>Amazon AWS has a free tier and makes it relatively easy to manage your budget as you scale.</p>

<p>Using their elastic beanstalk service, setup and deployment is pretty user friendly for new users (you'd still have to be technical or at least understand some terms enough to look up help). Only really gets complicated if you have to edit config files like nginx.conf as then you have to write YAML to edit the file with each deployment (stackoverflow is  far easier to get help from than their own docs)</p>

<p>And it has teething problems like the free tier runs out of memory resources when deploying cos it can't handle its own full health check (on by default)...</p>

<p>(I've only done this myself with nodejs and postgres)</p>

<p>But i use it myself, have always been able to solve problems myself with a bit of googling and am still managing to control my costs to a couple of dollars per month (have not yet gone full production)</p>

<p>If you have a budget but are not technical then rackspace will offer their famous support for AWS too.</p>



## Answer 12505

- posted by: [Tristan Schlarman](https://stackexchange.com/users/6545796/tristan-schlarman) on 2017-04-15
- score: 0

<p>Any services exist that can provide this for you. First things first don't use anything that is a website builder. You are selling and app that you made and if you have a weekly site people will look poorly on you like you can't program.</p>

<p>So either learn html and css on your own or pay someone to make a site for you.</p>

<p>As far as web hosting if you Wanna have freedom digitalocean and vultr offer pretty nice $5 a month VPS and if not do a shared hosting plan with GoDaddy or Bluehost, for a domain I use name cheap, the UI is awesome and huge selection of domain names for a fair price.</p>

<p>Lookup tutorials they will show you how to do all of this</p>



## Answer 12510

- posted by: [Chukk Chukk](https://stackexchange.com/users/4950206/chukk-chukk) on 2017-04-18
- score: 0

<p>You are using Firebase, so why wouldn't you host it on Google?</p>

<p><a href="https://firebase.google.com/docs/hosting/" rel="nofollow noreferrer">Google Firebase Hosting</a></p>

<p>It's native to Google and Google has one, if not the fastest CDN's in the world. The first "Spark" for Firebase hosting is free. Not to mention, they give you $300 to start the Google Cloud Platform (GCP). GCP is the most reasonably priced cloud in the world, you pay only for what you use. Having done much research about hosting as of late, these are the facts that have come to surface. </p>

<p>If you are already familiar with Firebase, why switch to something new? </p>

<p>Google Domains, for your domain. G Suites for everything else for $5 a month. With Google Sites you can make and host a website. Get a domain with G Suites, and have everything ready to go with Gmail or Inbox, Docs, Sheets, Slides, and Drive. </p>

<p>Having accounts on Digital Ocean, Vultr, Bitnami, GCP, Gandi, and even Github for hosting. For simplicity, security, and compatibility, in your situation using Firebase, Google would be the clear answer for myself anyway.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
