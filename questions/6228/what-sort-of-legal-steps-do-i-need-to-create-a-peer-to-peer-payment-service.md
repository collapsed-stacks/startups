## What sort of legal steps do I need to create a peer-to-peer payment service?

- posted by: [Jordan](https://stackexchange.com/users/6836433/jordan) on 2015-08-30
- tagged: `tech-company`, `legal`, `business-plan`, `taxes`, `united-kingdom`
- score: 3

So I'd like to create a simple peer to peer payment service whereby users of the service can simply add "tokens" (1 token = £0.01 GBP) to their account, send them to another account via the client area or via a merchant payment gateway and then then convert them into GBP again and then send them back into their bank account.

I'm ready to begin designing this as long as I'm legally able to

So... is there anything legal that I need to check/do first?

Thank you in advance, <br />
Jordan


## Answer 6234

- posted by: [eggyal](https://stackexchange.com/users/310184/eggyal) on 2015-09-01
- score: 2

Since [you mention](https://startups.stackexchange.com/questions/6228/what-sort-of-legal-steps-do-i-need-to-create-a-peer-to-peer-payment-service#comment6242_6228) that you intend to use Stripe, I'll start with [their Terms of Service](https://stripe.com/gb/terms#prohibited-businesses):

> ## Section B: Registering for Stripe ##
> 
> 5. ### Prohibited Businesses ###
> 
>     By registering for Stripe, you are confirming that you will not use the Service to accept payments in connection with the following businesses, business activities or business practices:
> 
>     ... (16) cheque cashing, wire transfers or money orders, ... (34) money transmitters or money service businesses, ... (39) quasi-cash or stored value, ... (50) virtual currency that can be monetised, re-sold or converted to physical or digital goods or services or otherwise exit the virtual world, ...
> 
>   By accepting this Agreement you confirm that you satisfy these requirements and will continue to do so in connection with your use of the Service.

So, your proposed business violates Stripe's Terms of Service—and thus you would either need to negotiate with them some non-standard terms (unlikely to be possible) or else find an alternative payment processor.  However, since Stripe prohibit businesses of this sort because they deem the underwriting risk to be too great, you will likely find similar prohibitions from most other providers.

Once (if) you find a merchant account provider who's willing to underwrite the card processing element of your business, you will then need to register as a [Payment Institution with the FCA](https://small-firms.fca.org.uk/apply-become-payment-institution-pi/apply-become-small-payment-institution-pi) and a [Money Service Business with HMRC](https://www.gov.uk/guidance/money-laundering-regulations-register-with-hmrc) (because you "transmit a representation of money").

Amongst other things, these permissions require that you pass HMRC's "[fit and proper test](https://www.gov.uk/guidance/money-laundering-regulations-apply-for-the-fit-and-proper-test)":

> You’ll fail the test if you cannot satisfy HMRC that you’re a fit and proper person with regard to the risk of money laundering or terrorist financing. HMRC will want to see evidence of your honesty and integrity and whether you’re able to understand and fulfil your obligations under the regulations.

I *suspect* that HMRC won't consider you to have demonstrated that "you're able to understand and fulfil your obligations" unless you have (a senior director with) some relevant anti money-laundering qualification.

The FCA impose a similar requirement: "directors and managers must be of good repute with appropriate skills to provide payment services".  Again, I suspect that they won't consider this to have been met unless you have (a senior director with) some relevant banking qualification.

Having registered, you should be sure to read [Anti-money laundering guidance for money service businesses](https://www.gov.uk/government/publications/anti-money-laundering-guidance-for-money-service-businesses) in order to understand your ongoing compliance obligations&mdash;but in brief:

* you must put in place (and apply) appropriate, risk-sensitive policies aimed at preventing money laundering;

* you must nominate an anti-money laundering officer to whom all suspicions of money laundering must be reported, and who will consider whether those reports should be forwarded to the National Crime Agency; and

* you must record certain customer details and, where sums over €1000 are involved (or you suspect money laundering), those details must be verified from a reliable independent source.

Other obligations include:

* you must take precautions to prevent terrorist financing and/or breach of international sanctions;

* you must keep customer funds secure and safe; and

* you must report transaction volumes periodically to the FCA.

Beware that getting this wrong could land you not only with civil penalties, but potentially criminal ones too.  I'd strongly advise you get advice from a lawyer before proceeding any further with this business.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
