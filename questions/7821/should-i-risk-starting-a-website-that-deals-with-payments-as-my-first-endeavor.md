## Should I risk starting a website that deals with payments as my first endeavor?

- posted by: [DarthVoid](https://stackexchange.com/users/5555544/darthvoid) on 2015-11-12
- tagged: `startup-costs`, `payment`
- score: 0

<p>I've been working on a website for a while. It will require users to pay in order to use it. However, this is my first business endeavor (no experience with building a company or a website) and I'm a young guy, so people are less likely to take me seriously. But I think this idea could have value to many people and I want to try. </p>

<p><strong>My idea in a nutshell</strong>:</p>

<p>It's basically a site to find professionals to answer your question and you pay them for it. The users pay via iFrames (Braintree) and if they are satisfied by the professional's expertise, they click a button and that professional gets paid. I am currently attempting to integrate Braintree's iFrames into my Wordpress site.</p>

<p>I've heard advice that I shouldn't start a website that involves payments as my first try at a business/website in general because of a few key reasons:</p>

<ol>
<li>I won't be able to keep it secure, nor have the means to pay an I.T. company to secure it</li>
<li>I won't have the ability to deal with lawsuits should they occur</li>
<li>Lack of web dev experience will lead to a mediocre website</li>
</ol>

<p>But keeping my idols in mind, I don't think I should be phased by this. There are a lot of people who start websites that involve payment info and yes a lot fail, but why is that any reason to not try?</p>

<p>What do people think about this? Am I an idiot for trying to start a website that involves payments by myself? What are the risks and what could be the worst outcomes of all this? </p>



## Answer 7828

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-11-12
- score: 3

<p>The parts you absolutely do NOT want to be handling are the payment itself, the billing system, and the accounting system.</p>

<p>Doing so is a boulevard of thorny problems, even when you're familiar enough with double-entry bookkeeping to implement it underneath. Among the problems you'll may end up getting: failed transactions, refunds, chargebacks, reversed chargebacks, abandoned users and transactions that lead to duplicate users, the list goes on and on and on. It's a mess. :-)</p>

<p>Braintree handles this mess for you. Go with that.</p>



## Answer 7830

- posted by: [Brandon Parrie](https://stackexchange.com/users/7273564/brandon-parrie) on 2015-11-12
- score: 0

<p>Try looking at Tim Ferriss' "Four Hour Workweek" it walks you through a system on how to test an idea for an online business in order to see if its worth diving into. It'll save you some time and give you a good idea on how to go about building at least a decent site.
<a href="http://fourhourworkweek.com/" rel="nofollow">http://fourhourworkweek.com/</a>  here's a link to the official book website.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
