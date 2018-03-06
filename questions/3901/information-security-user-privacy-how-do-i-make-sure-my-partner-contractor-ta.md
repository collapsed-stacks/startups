## Information security & user privacy: how do I make sure my partner/contractor takes as much care of it as I do?

- posted by: [icehenge](https://stackexchange.com/users/5076778/icehenge) on 2015-04-01
- tagged: `legal`, `contracts`, `partners`, `contractors`
- score: 7

There was a highly publicized security & user privacy issue last month involving [Lenovo and Superfish](http://www.nytimes.com/2015/03/02/technology/how-superfishs-security-compromising-adware-came-to-inhabit-lenovos-pcs.html), which bears apparent similarities to the [Sony rootkit scandal](http://en.wikipedia.org/wiki/Sony_BMG_copy_protection_rootkit_scandal) many years ago. The difference between the two cases, in my opinion, is that while the later seems to be attributable solely to bad business ethics, the former, at least on the part of Lenovo, seems to be the unfortunate product of asymmetric information and disparate incentives in a complex business dealing. 

This further reminds me of cases similar in nature involving security breaches caused by negligent contractors, like *GAP's stolen job applicants' data* (in a contractor's laptop), and *Stanford Hospital's patient data exposure* (which ended up being given by the contractor unencrypted to a potential hire who then posted it on a public website), and many more -- you can search by the italic text for detailed reports since I can't post more than two links.

Suppose I am running a business that handles large amounts of sensitive user data. Obviously from my perspective, part of the objective of contracting or partnering with others is to save myself the trouble of dealing with the details of something that helps me achieve certain technical or financial objectives but is not part of my core business. As the result, there are a lot of things they know and I don't need to know and can't possibly know. So here comes information asymmetry. It will be unlikely, for example, if I rely on the other party to store and maintain user data, that I can go as far as asking how they are encrypting user's passwords, and further, whether they are salted. Taking Lenovo's perspective as in the case with Superfish, I would need to dig deeply into my partner's software to see the not so nice things under the guise of a state-of-the-art craft with cutting edge image recognition and search suggestion technologies, and such inspections themselves would probably be prohibited under the contract (I would definitely prohibit it if I were Superfish). It would probably be even more difficult for me, taking the perspective of GAP or Stanford Hospital, to look into the internal policies of my contractor/partner to see if they secure their data tightly, change their admin password frequently, train their staff properly, etc. And if I have to worry about all these, why not just do it myself?

It would be nice, however, if my partner/contractor had a sufficient incentive to try as hard as I do to protect the sensitive user data. Unfortunately, this is often not the case. While I would be dealing with damaged reputation, disgruntled customers and potential lawsuits, should a security breach occur, and would be paying huge costs, the other party might simply walk away free and clear  (and might even get the bonus of free advertisement like Superfish).

So my question is: 

**Is there an efficient and reliable mechanism through which I can share the burden of information security and user privacy, and the costs, in case of a breach, equally with my partner/contractor?** Ideally the answer could provide suggestions with respect to the formulation of an agreement or contract, hopefully with specific examples of contractual terms. Other related suggestions of reading, resources, case studies, legal opinions ... would also be greatly appreciated.





## Answer 4086

- posted by: [Ali](https://stackexchange.com/users/2815644/ali) on 2015-04-22
- score: 2

When you appoint a contractor to provide you with a service, you would enter into a service contract with him. The service contract would outline the exact service you expect from the provider, specific specifications, quality of the service, liable areas, and if need be, penalties for failing to provide the quality of service or if a failure occurred due to improper operations by the service provider. 

In your specific case, if you determine that your company has insufficient skills or resources to manage cyber security in-house, do not want to hire an in-house team or would like to have a third part security auditor (a very good idea) or need a full service provider, then you can shop around for a internet security firm and request for proposals. Then evaluate the proposals, discuss service agreement clauses include penalties and liability clauses and select the provider. The providers on their side would negotiate limitation on the liability in order reduce their financial burden in case of a failure.

It would be fair to assume that big companies like GAP, Target etc would use a cyber security provider who probably got canned and sued when the breach occurred. For instance, a NY company called Trustwave Holdings was providing security auditing for Target when it got breached and Trustwave was sued by several banks. The lawsuit was eventually dropped. 

IMHO, majority of the breaches and lapses occur due to improper practices and inadequate control. For instance in the case of Target they had been storing customer card info for 6 days before it was being deleted and the practice had been noted and they had been advised about it before the breach.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
