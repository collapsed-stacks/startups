## How can I give sales commissions through an API (programmatically)?

- posted by: [pixelearth](https://stackexchange.com/users/129602/pixelearth) on 2017-02-14
- tagged: `payment`, `commissions`
- score: 2

I have a service that gives sales commissions on digital products sold. We currently pay out commissions monthly to our artists manually via paypal, but this is getting time-consuming as the number of artists grow. 

We would like to transition to a different system, ideally one that can be automated. We're not opposed to changing banks if need be.

I think paypal might have an API service for this, but if possible, we'd like to move away from paypal for a number of reasons.

Thanks in advance, and as always, sorry if this is the wrong place or wrong content for this question. 


## Answer 12116

- posted by: [Jonathan Pellerin](https://stackexchange.com/users/1748443/jonathan-pellerin) on 2017-02-14
- score: 3

Paypal does provide that API. I have a business that works like Uber (from a business model perspective) and we use Paypal for payouts. You can automate those from your servers. 

I agree with you on trying to move away from Paypal, but for now they are still trusted by customers, and they provide the service.

Edit: you can find more info on the API here: https://developer.paypal.com/docs/integration/direct/payouts/



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
