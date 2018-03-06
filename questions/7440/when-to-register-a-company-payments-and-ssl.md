## When to register a company, payments and SSL

- posted by: [raphadko](https://stackexchange.com/users/3229369/raphadko) on 2015-09-29
- tagged: `startup-costs`, `lean-startup`
- score: 1

So, i've been working on my project for aboua an year and now I'm ready to launch it. I wanted to test the public response before going through all the paperwork of registering a company.

Is it ok to launch (and receive payments) for a couple months without having a company registered? Are there any drawbacks to that?

I'm using stripe to receive my payments.. would they pay me if I don't have a registered company yet?

Also, when registering for a SSL certificate, they will ask me for company details for generating the CSR, is it ok to put my future company's details on those fields?


## Answer 7443

- posted by: [Jeff O'Neill](https://stackexchange.com/users/46273/jeff-o-neill) on 2015-09-30
- score: 2

> Is it ok to launch (and receive payments) for a couple months without
> having a company registered? Are there any drawbacks to that?

The question to ask is what risks are you facing.  If you are selling a game for $5, then people might ask for their money back.  Not a big risk.  If you are writing software for self driving cars then there is a big risk since someone could die and sue you.  Most companies do not have significant risks so it is fine to start selling without creating any kind of company.

> I'm using stripe to receive my payments.. would they pay me if I don't
> have a registered company yet?

Yes, they will.  Lots of people use Stripe as individuals without having a company.

> Also, when registering for a SSL certificate, they will ask me for
> company details for generating the CSR, is it ok to put my future
> company's details on those fields?

Absolutely not.  You need to tell the truth as it is now.  Misrepresenting yourself creates liability, and if it is just you (not a company) then you are personally liable and you don't want that.



## Answer 7441

- posted by: [Abhi](https://stackexchange.com/users/200253/abhi) on 2015-09-29
- score: 1

> I wanted to test the public response before going through all the paperwork of registering a company.

That is a great idea - as long as part of the paperwork you are not collecting any user information - I think you should be OK. If you do collect I would recommend you at least have an LLC setup (assuming you are in US). check with an attorney for details.

> Is it ok to launch (and receive payments) for a couple months without having a company registered? 

setup an LLC (more so because fin transactions are involved)

> Are there any drawbacks to that?

If your financial partner or someone in the pipeline messes up with your Client's information including financial information - it will hurt you. I strongly suggest an LLC.

> I'm using stripe to receive my payments.. would they pay me if I don't have a registered company yet?

I don't know

> Also, when registering for a SSL certificate, they will ask me for company details for generating the CSR, is it ok to put my future company's details on those fields?

Basically SSL Certificates bind together: the domain name, server name or hostname and the organizational identity (i.e. company name) and location. So it might be better to have real information here. My recommendation is using LLC.

I have a startup I am moving into field Trial (with greatly reduced monthly payment) - I have the startup incorporated.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
