## What sort of legal steps do I need to create a peer-to-peer payment service?

- posted by: [Jordan](https://stackexchange.com/users/6836433/jordan) on 2015-08-30
- tagged: `tech-company`, `legal`, `business-plan`, `taxes`, `united-kingdom`
- score: 3

<p>So I'd like to create a simple peer to peer payment service whereby users of the service can simply add "tokens" (1 token = £0.01 GBP) to their account, send them to another account via the client area or via a merchant payment gateway and then then convert them into GBP again and then send them back into their bank account.</p>

<p>I'm ready to begin designing this as long as I'm legally able to</p>

<p>So... is there anything legal that I need to check/do first?</p>

<p>Thank you in advance, <br />
Jordan</p>



## Answer 6234

- posted by: [eggyal](https://stackexchange.com/users/310184/eggyal) on 2015-09-01
- score: 2

<p>Since <a href="https://startups.stackexchange.com/questions/6228/what-sort-of-legal-steps-do-i-need-to-create-a-peer-to-peer-payment-service#comment6242_6228">you mention</a> that you intend to use Stripe, I'll start with <a href="https://stripe.com/gb/terms#prohibited-businesses" rel="nofollow noreferrer">their Terms of Service</a>:</p>

<blockquote>
  <h2>Section B: Registering for Stripe</h2>
  
  <ol start="5">
  <li><h3>Prohibited Businesses</h3>
  
  <p>By registering for Stripe, you are confirming that you will not use the Service to accept payments in connection with the following businesses, business activities or business practices:</p>
  
  <p>... (16) cheque cashing, wire transfers or money orders, ... (34) money transmitters or money service businesses, ... (39) quasi-cash or stored value, ... (50) virtual currency that can be monetised, re-sold or converted to physical or digital goods or services or otherwise exit the virtual world, ...</p>
  
  <p>By accepting this Agreement you confirm that you satisfy these requirements and will continue to do so in connection with your use of the Service.</p></li>
  </ol>
</blockquote>

<p>So, your proposed business violates Stripe's Terms of Service—and thus you would either need to negotiate with them some non-standard terms (unlikely to be possible) or else find an alternative payment processor.  However, since Stripe prohibit businesses of this sort because they deem the underwriting risk to be too great, you will likely find similar prohibitions from most other providers.</p>

<p>Once (if) you find a merchant account provider who's willing to underwrite the card processing element of your business, you will then need to register as a <a href="https://small-firms.fca.org.uk/apply-become-payment-institution-pi/apply-become-small-payment-institution-pi" rel="nofollow noreferrer">Payment Institution with the FCA</a> and a <a href="https://www.gov.uk/guidance/money-laundering-regulations-register-with-hmrc" rel="nofollow noreferrer">Money Service Business with HMRC</a> (because you "transmit a representation of money").</p>

<p>Amongst other things, these permissions require that you pass HMRC's "<a href="https://www.gov.uk/guidance/money-laundering-regulations-apply-for-the-fit-and-proper-test" rel="nofollow noreferrer">fit and proper test</a>":</p>

<blockquote>
  <p>You’ll fail the test if you cannot satisfy HMRC that you’re a fit and proper person with regard to the risk of money laundering or terrorist financing. HMRC will want to see evidence of your honesty and integrity and whether you’re able to understand and fulfil your obligations under the regulations.</p>
</blockquote>

<p>I <em>suspect</em> that HMRC won't consider you to have demonstrated that "you're able to understand and fulfil your obligations" unless you have (a senior director with) some relevant anti money-laundering qualification.</p>

<p>The FCA impose a similar requirement: "directors and managers must be of good repute with appropriate skills to provide payment services".  Again, I suspect that they won't consider this to have been met unless you have (a senior director with) some relevant banking qualification.</p>

<p>Having registered, you should be sure to read <a href="https://www.gov.uk/government/publications/anti-money-laundering-guidance-for-money-service-businesses" rel="nofollow noreferrer">Anti-money laundering guidance for money service businesses</a> in order to understand your ongoing compliance obligations&mdash;but in brief:</p>

<ul>
<li><p>you must put in place (and apply) appropriate, risk-sensitive policies aimed at preventing money laundering;</p></li>
<li><p>you must nominate an anti-money laundering officer to whom all suspicions of money laundering must be reported, and who will consider whether those reports should be forwarded to the National Crime Agency; and</p></li>
<li><p>you must record certain customer details and, where sums over €1000 are involved (or you suspect money laundering), those details must be verified from a reliable independent source.</p></li>
</ul>

<p>Other obligations include:</p>

<ul>
<li><p>you must take precautions to prevent terrorist financing and/or breach of international sanctions;</p></li>
<li><p>you must keep customer funds secure and safe; and</p></li>
<li><p>you must report transaction volumes periodically to the FCA.</p></li>
</ul>

<p>Beware that getting this wrong could land you not only with civil penalties, but potentially criminal ones too.  I'd strongly advise you get advice from a lawyer before proceeding any further with this business.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
