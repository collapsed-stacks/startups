## For software licensing based on installation count, how should I define 'server'?

- posted by: [mjn](https://stackexchange.com/users/29836/mjn) on 2015-12-12
- tagged: `marketing`, `software`, `licensing`
- score: 1



My research showed that some server-based licensing schemes - for example for SQL servers - use a highly complex pricing model, while others keep it simple and say for example 'A server is a physical 4 core box'.

If I want to sell licenses of my software based on the installation count, and prefer a simple definition of a server instance (which however also takes into account hardware virtualization), and is clear enough both for the technicians and the managers who have to approve the purchase, should I stick with the simple definition above (1 server = 4 physical cores)?



## Answer 8080

- posted by: [Jimnotgym](https://stackexchange.com/users/7461839/jimnotgym) on 2015-12-12
- score: 3

I hate complex pricing models, and I believe you are right to make things straightforward for a purchaser. It is highly embarrassing to have to go back to your Finance Director and tell him you got the licensing costs wrong and need more money, and I believe certainty in the final cost may get your product specced more often.

The licensing model however depends on the product. Is it the kind of thing I could set up on 20 VM's on a high spec server and beat your model?

Perhaps 1 server is 1 physical server with up to 4 physical cores and up to two virtual machines? Is anyone likely to scale your software onto multiple machines on one server and resell it?



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
