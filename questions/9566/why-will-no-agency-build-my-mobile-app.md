## Why will no agency build my mobile app?

- posted by: [RisingSupernova](https://stackexchange.com/users/8707573/risingsupernova) on 2016-06-26
- tagged: `product`
- score: 4

<p>I've been trying to find a development studio/agency to build an iOS app I've been working on for almost a year now with no luck. The app is a basic front end (this has already designed &amp; I have produced a clickable prototype in InVision), with most of the heavy lifting done server side. I have a 30+ page spec with all user journeys mapped out, specified how the backend should work, what SDKs I need integrated, what access levels each user type should have etc. etc. But can’t find an agency to build it.</p>

<p>The product is currently undergoing patent review so I cannot be too specific, however here is the gist of its functionality:</p>

<ol>
<li>User scans government ID and populates our register form via an open OCR SDK and their iPhone's camera</li>
<li>User fills in any missing details (email, mobile number)</li>
<li>User scans credit card using card.io open SDK</li>
<li>Our server runs background check API against a third party DB to confirm eligibility 

<ol start="5">
<li>User can now be automatically registered to any of our partner sites as a pre-vetted lead with a single tap</li>
</ol></li>
<li>User can access deals offered by the partners he has signed up for via an in-app inbox</li>
<li>User can be logged into the partner sites by the app, or via any other device</li>
</ol>

<p>The challenge is point 5 as none of our partners have an API we can use, therefore our server needs to fill in the partner's registration firm with the users details. We are considering using a Selenium webdriver running server-side, with a script that populates a user's details into a test script and runs on the partners registration form, however I am open to suggestions from the agency that would undertake the project; so far though I have no takers.</p>

<p>Is it just that there is enough business in building pretty brochure apps that there is no need to undertake a challenging project or should I be looking at a totally different type of dev agency rather than an app agency? </p>



## Answer 9567

- posted by: [Daniel Anderson](https://stackexchange.com/users/8398759/daniel-anderson) on 2016-06-27
- score: 3

<p>As a professional developer, what I can tell you is that you're getting a common response from people who don't have the expertise to build what you're looking for, so they're trying for the "low-hanging fruit" of designing the front end.  </p>

<p>Might I suggest that you try posting a listing on either UpWorks.com, Guru.com, or FreeLancer.com?  These are sites which allow companies to find, vet, hire, and pay programmers who will take on all kinds of projects, especially programming stuff.  I guarantee you'll get quite a few bids from programmers around the world who would like to do this job for you.</p>

<p>I hope this helps.</p>

<p>Good luck!</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
