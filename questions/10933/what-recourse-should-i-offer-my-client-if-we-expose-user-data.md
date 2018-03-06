## What recourse should I offer my client if we expose user data?

- posted by: [ChristopherJ](https://stackexchange.com/users/1466151/christopherj) on 2016-08-14
- tagged: `data`, `privacy`
- score: 13

I've developed an app to analyse user data for a client. They've asked me what recourse they will have if the data is exposed (is made accessible to others). I'm not too sure how to answer this question. We've taken the usual best practices with the data: we don't actually store any sensitive information except for their API key which could be used to retrieve sensitive information from their system, the API key is stored encrypted, w/ key rotation, etc.

But it's the internet, even with all the best practices there's always a chance something could get compromised.

I don't really want to go back to them and say they have no recourse, but we're a (very) small operation.

I've looked through some other posts, and references and looked up privacy policies and it seems that as a general rule people don't have any recourse if best practice has been used and the vendor notifies them if they become aware of a breech.

How should we respond? Is there any other kind of recourse that I've overlooked that they would reasonably expect?

We're working with an Australian client but the system is on US servers.


## Answer 10935

- posted by: [Community](https://stackexchange.com/users/-1/community) on 2016-08-14
- score: 16

<p>Data breaches have become extremely common over the last few years with <a href="https://en.wikipedia.org/wiki/List_of_data_breaches">a massive corporation losing millions of records</a> every couple weeks, on average. While best practices to ensure data security are critical, the expectation that a data breach will happen is now so common that the US Department of Justice took it upon itself to issue <a href="https://www.justice.gov/sites/default/files/opa/speeches/attachments/2015/04/29/criminal_division_guidance_on_best_practices_for_victim_response_and_reporting_cyber_incidents2.pdf">data breach response best practices</a>.</p>

<p>Any system connected to the Internet will have security holes that can be breached no matter how much effort was made to secure it. (Historically, this is much less true for <a href="http://www.openbsd.org/">OpenBSD</a>, but I digress.) The most sensitive systems should be the least connected, or entirely offline if that's feasible. There can be no absolute security expectations of any connected system.</p>

<p>So it's best to <s>hope</s> work for the best and prepare for the worst.</p>

<p>Data breach risk, like any other common business risk, can be insured. The risk is now so common, data breach insurance policies have become common. If you search the Internet for "data breach insurance," you'll find many insurance companies interested in offering you quotes based on your business activities. One broker recently told a news publication that policies <a href="http://www.usatoday.com/story/tech/2014/12/09/security-data-breach-insurance-target/20011477/">average $2,500 per year but can go up to $10,000 per month</a>. Of course, an insurance company would have to evaluate your particular risks to give you a correct premium that may or may not be in this range.</p>

<p>You should explain to your client the precautions you take to secure their data. You should also explain that there is no security in existence that you or anyone else can implement to fully guarantee the safety of their data. You might explain that you are in the data analysis business and not in the cyber-security risk management business, but that you are willing to work with the client and a third party insurance company to insure any potential financial risks that are of particular concern. You can then evaluate the risks of a data breach carefully with the client and determine if these risks are worth insuring away. Any premium and deductible costs would have to be passed on to your client(s). </p>

<p>Regardless of whether or not you purchase an insurance policy, you should make a plan up-front on how you'll deal with the breach. Know the risks posed by the data being stolen and be prepared to deal with the situation right away.</p>



## Answer 10934

- posted by: [Daniel Anderson](https://stackexchange.com/users/8398759/daniel-anderson) on 2016-08-14
- score: 7

As a professional developer working in the field for more than 30 years, there's no more horrifying thought that the prospect of losing a customer's data.  And the short answer is, there may not ***be*** an answer you can give this particular client that will satisfy them.  As Anonymous pointed out, they sound like they're a litigious lot, which is potentially disastrous for a small firm without the resources to absorb the hit of things go awry.

Now, that being said, I have had clients who were *reasonably* satisfied that I was willing to carry insurance against data loss or some type of breach resulting from my work, and I also provided information about a company I'd developed a relationship with that specialized in data recovery.

***HOWEVER***, what you *must* do in this case is get the client away from thinking about the negative "what ifs" of dealing with your company.  The question they've asked has put you on the defensive, and no war has ever been won on defense.

What's key here is to be proactive and positive in explaining the measures you take to safeguard their data and look out for their best interests without making it sound like something bad is inevitable, if that makes sense.  Talking about it in the "when it happens" mode is a bad place to be, because all they'll do is continue to come up with more questions you can't really answer.

You need to talk to them about data loss and breaches as if they're minor annoyances and about as likely as you winning the lottery.  In other words, you have to downplay the possibility of a breach or loss ever occurring in the first place and discuss it from the standpoint of why what you do assures their data is safe and secure.

This is less of a technical issue for you and more of a public relations matter.  The customer has called you out and wants you to explain why they should trust you.  Tell them.  Be honest.

*Above all*, ***DON'T BE AFRAID TO WALK AWAY FROM THE DEAL.***  There's nothing worse than a needy, whiny, impossible-to-satisfy customer.  As a small shop, you're probably scared to death that if you walk away from them then you may not get another customer.  What you *should* be afraid of is a customer like this who is already making you think you need to have an attorney available just in case they get an itch to sue.  There are always more clients, trust me.

I hope this helps.

Good luck!


## Answer 10940

- posted by: [Marcus D](https://stackexchange.com/users/258531/marcus-d) on 2016-08-15
- score: 3

<p><strong>The Client's Question</strong></p>

<p>Your client is really asking 'Can we trust you?' and 'How much effort and thought have you put into the security of our data?'</p>

<p>We (a cloud-based data analytics company) have faced similar questions. We have an internal 'data security' document, which we share with our clients, then that gives us a good place to start the conversation to minimise their fears.</p>

<p>If they are still worried, then as other posters have said, get a '<a href="http://www.computerweekly.com/news/2240202703/An-introduction-to-cyber-liability-insurance-cover" rel="nofollow">data breach insurance</a>' policy.</p>

<p><strong>Different Causes of Data Loss</strong></p>

<p>To drill into things a bit, to enable you to talk around the broader issues with your client, I guess there are two fronts to data loss. Your question perhaps relates to the second.</p>

<ol>
<li>Data Loss to system failure. This can be mitigated by a good disaster recovery / <a href="https://en.wikipedia.org/wiki/Business_continuity" rel="nofollow">business continuity</a> procedure. These should be written down and tested.</li>
<li>Data loss through the data 'escaping' outside the control of your system. This is the potentially more tricky one to mitigate. This can be done by a party external to your company (hacker) or internal to your company.  </li>
</ol>

<p>There are some startling figures with regard to current and previous employees stealing or being <a href="http://www.esecurityplanet.com/network-security/survey-20-percent-of-employees-have-stolen-corporate-data.html" rel="nofollow">poor with regard to data security</a>. A couple of concerning quotes ... </p>

<blockquote>
  <p>1 in 4 employees said they would take corporate data with them when
  they left their job</p>
  
  <p>66 percent of employees said they still had access to corporate data
  via cloud apps such as Dropbox or Google Docs after they left their jobs</p>
</blockquote>

<p>There is a suggestion that the <a href="http://www.hackmageddon.com/category/security/cyber-attacks-statistics/" rel="nofollow">main motivation for hacking is financial</a>. There is a <a href="https://digitalguardian.com/blog/insider-outsider-data-security-threats" rel="nofollow">very good article</a> collecting a number security professionals' thoughts together. There seems to be no clear picture of internal vs. external threats, so both need to be protected against.</p>

<p><strong>Protection Against Data Loss</strong></p>

<p>There are some things you can do to mitigate (I'll include the ones you have listed already for completeness)</p>

<p>Staff</p>

<ul>
<li>Managing employees leaving well. Identifying risky employees and give them gardening leave.</li>
<li>Using a cloud files provider (like dropbox/google drive/etc.) that allows remote wipe when employees leave</li>
<li>Have data level encryption on all company movable devices (laptops/USB/external drives)</li>
<li>Have a robust backup routine, suitable for your particular client</li>
</ul>

<p>IT Staff</p>

<ul>
<li>Separation of production/UAT/dev systems. </li>
<li>Have a good set of dev/test data created that does not use real client data.</li>
</ul>

<p>Server</p>

<ul>
<li>Strong passwords that have an enforced password policy</li>
<li>Keep your private encryption keys private. Restrict access</li>
<li>VPN</li>
<li>Use protection against malware/anti virus/etc. on your servers.</li>
</ul>

<p>Database</p>

<ul>
<li>Implement database level encryption, or field level encryption on sensitive fields</li>
<li>Separate sensitive data from non-sensitive data by foreign keys. </li>
<li>Keep your servers (app/db/web, etc) patched with the most recent patches.</li>
<li>Ensure database permissions are as restricted as possible, only allow what a process needs to run and no more.</li>
<li>Ensure full audit trails are on the database / server</li>
</ul>

<p>This is a slightly formatted brain dump. I'll add to it as I think of extra bits.</p>

<p>I would also ask your client, what steps they take with regard to these things? </p>



## Answer 10939

- posted by: [Neil](https://stackexchange.com/users/2711480/neil) on 2016-08-15
- score: 0

I would include a general clause about disputes going through an independent arbitration service e.g. http://www.cedr.com/solve/arbitration/. There are loads of these, just make sure that you find one that is reputable and serves your region(s). Then you can point your prospective client at this part of the contract. It is worth also thinking about why they want this. Have they recently been hacked and now they are sensitive? Perhaps it is worth showing them how you have made your app protection and seek their advice on how it could be improved (minute the meeting in case...)

If they push for specific clauses and penalty amounts then I would suggest considering advice from other answers (running a mile...).




## Answer 10941

- posted by: [fiprojects](https://stackexchange.com/users/5370155/fiprojects) on 2016-08-15
- score: 0

I suggest you seek Liability cover (it costs me under 500euro a year to cover 5million USD per incident - I cannot lift/shift physical hardware, but I can program it). 

Be polite to your client - tell them that you have done your professional best but you understand their concern - remind them that even with the entire resources of a country, attempts on a President or Prime Minister are sometimes made, and sometimes the attempts are successful. 

Agree a schedule with your client that you have frequent (quarterly/half yearly) meetings to discuss potential new threats. This should help reduce the risk and/or impact to their business. 

Beyond this, if there is a specific area of concern they have they should share it so you can address it.

But... being honest... if the worst was to happen your client would have to follow a path no different than they would with any of their other service suppliers. An arbitration or court would decide if you folks were negligent in your service. Think of September 11th and ask yourself could those who built the building have done anything to have reduced the impact? Short answer is no because nobody ever expected the situation that occurred. You have considered every conceivable situation and covered your bases - if there is something you have missed, you'll apply your best efforts to resolve.

I suspect your client is not out to trick you but they just want comforting that you have given their best interests serious thought. They are perfectly professional to ask, and they would not have selected you to deliver a service had they not thought you competent. But they have legal obligations to ensure the data they carry is properly respected. (This question should have been raised when you folks first bid for the project though).

Best of luck!


## Answer 10943

- posted by: [JS.](https://stackexchange.com/users/118990/js) on 2016-08-15
- score: 0

I know nothing about your system, but just though I might offer a suggestion.

Is it possible for you to run all or part of your app on their systems?  If your app can do all it needs to with private data while on their system and avoid leaking private data to the outside. you could, in theory, shift much of the onus of data protection back to them.

Alternately, it might be possible to structure your software so that only a part need run on their system.

It's unlikely that this is feasible, but just food for thought.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
