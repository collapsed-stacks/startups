## When to register a company, payments and SSL

- posted by: [raphadko](https://stackexchange.com/users/3229369/raphadko) on 2015-09-29
- tagged: `startup-costs`, `lean-startup`
- score: 1

<p>So, i've been working on my project for aboua an year and now I'm ready to launch it. I wanted to test the public response before going through all the paperwork of registering a company.</p>

<p>Is it ok to launch (and receive payments) for a couple months without having a company registered? Are there any drawbacks to that?</p>

<p>I'm using stripe to receive my payments.. would they pay me if I don't have a registered company yet?</p>

<p>Also, when registering for a SSL certificate, they will ask me for company details for generating the CSR, is it ok to put my future company's details on those fields?</p>



## Answer 7443

- posted by: [Jeff O'Neill](https://stackexchange.com/users/46273/jeff-o-neill) on 2015-09-30
- score: 2

<blockquote>
  <p>Is it ok to launch (and receive payments) for a couple months without
  having a company registered? Are there any drawbacks to that?</p>
</blockquote>

<p>The question to ask is what risks are you facing.  If you are selling a game for $5, then people might ask for their money back.  Not a big risk.  If you are writing software for self driving cars then there is a big risk since someone could die and sue you.  Most companies do not have significant risks so it is fine to start selling without creating any kind of company.</p>

<blockquote>
  <p>I'm using stripe to receive my payments.. would they pay me if I don't
  have a registered company yet?</p>
</blockquote>

<p>Yes, they will.  Lots of people use Stripe as individuals without having a company.</p>

<blockquote>
  <p>Also, when registering for a SSL certificate, they will ask me for
  company details for generating the CSR, is it ok to put my future
  company's details on those fields?</p>
</blockquote>

<p>Absolutely not.  You need to tell the truth as it is now.  Misrepresenting yourself creates liability, and if it is just you (not a company) then you are personally liable and you don't want that.</p>



## Answer 7441

- posted by: [Abhi](https://stackexchange.com/users/200253/abhi) on 2015-09-29
- score: 1

<blockquote>
  <p>I wanted to test the public response before going through all the paperwork of registering a company.</p>
</blockquote>

<p>That is a great idea - as long as part of the paperwork you are not collecting any user information - I think you should be OK. If you do collect I would recommend you at least have an LLC setup (assuming you are in US). check with an attorney for details.</p>

<blockquote>
  <p>Is it ok to launch (and receive payments) for a couple months without having a company registered? </p>
</blockquote>

<p>setup an LLC (more so because fin transactions are involved)</p>

<blockquote>
  <p>Are there any drawbacks to that?</p>
</blockquote>

<p>If your financial partner or someone in the pipeline messes up with your Client's information including financial information - it will hurt you. I strongly suggest an LLC.</p>

<blockquote>
  <p>I'm using stripe to receive my payments.. would they pay me if I don't have a registered company yet?</p>
</blockquote>

<p>I don't know</p>

<blockquote>
  <p>Also, when registering for a SSL certificate, they will ask me for company details for generating the CSR, is it ok to put my future company's details on those fields?</p>
</blockquote>

<p>Basically SSL Certificates bind together: the domain name, server name or hostname and the organizational identity (i.e. company name) and location. So it might be better to have real information here. My recommendation is using LLC.</p>

<p>I have a startup I am moving into field Trial (with greatly reduced monthly payment) - I have the startup incorporated.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
