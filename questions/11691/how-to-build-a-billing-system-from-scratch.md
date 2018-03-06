## How to build a billing system from scratch?

- posted by: [Sergei Basharov](https://stackexchange.com/users/46016/sergei-basharov) on 2016-12-12
- tagged: `payment`, `billing`
- score: 1

Say, I have a project that users will pay for on recurring basis, or any other way with credit cards.

I don't need the billing system to be highly flexible or customizable as it's made just for this project. I suppose I can even have only one bank in the backend to process the payments. Being a programmer I can do some dirty job to connect their system to my project.

I wonder, what's the shortest path from the payment page to my account? Is it possible that I go to bank, tell them that I want to accept payments online via CC and put the money on my account in this bank and then they provide me with some tools to integrate?

I know I can use Stripe, Braintree or any other of the myriad of billing systems but I am interested in how they work on the side of actual processing of the payments. As these services are attractive to developers because of their simplicity, I wonder what amount of crap and boring stuff they have to deal with?

Can I learn more about it somewhere? Are there special conditions I have to conform to before being able to accept payments besides having a company?


## Answer 11694

- posted by: [Jeff O'Neill](https://stackexchange.com/users/46273/jeff-o-neill) on 2016-12-12
- score: 2

<p>Another big reason for using services like Stripe is to reduce your own risk.  When using Stripe, you never actually possess the customer's credit card number and that is a great thing.  Possessing credit card numbers online is a HUGE risk, and if someone hacks you and gets a credit card number then you are in big trouble.</p>

<p>If you want to learn more, then you can read up on <a href="https://en.wikipedia.org/wiki/Payment_Card_Industry_Data_Security_Standard" rel="nofollow noreferrer">PCI compliance</a>.  It is a lot of work to comply with all credit card regulations, so it is not something most startups want to deal with.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
