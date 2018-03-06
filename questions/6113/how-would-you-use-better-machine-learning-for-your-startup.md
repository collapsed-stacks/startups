## How would you use better Machine Learning for your startup?

- posted by: [Michael R. Bernstein](https://stackexchange.com/users/5853415/michael-r-bernstein) on 2015-08-21
- tagged: `target-market`, `data`, `learning`
- score: 5

Assume you are given access to a new approach/architecture for neural networks useful for unsupervised machine learning that produces qualitatively better models than current approaches, with no significant performance loss.

What problems would you want to try applying it to?


## Answer 6115

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-08-22
- score: 1

Lots of things...

For instance, I had a recent client who could have made good use of neural nets to automate enhancing video covers. The cover images were mostly similar (same type of topic) but with vastly different levels of quality and levels. The result they were seeking was to have harmonious color and brightness characteristics, with a pinch of sharpening where needed.

Another type of topic I'd find useful would be analyzing site usage data (e.g. Google Analytics) to highlight interesting trends and traffic patterns. Kind of like what they're doing over at Narrative Science, but with the twist that you'd want to weed out trash in the data before performing the analysis -- as in, ignore very short sessions or spam traffic like ghost referrals.


## Answer 6146

- posted by: [zazaalaza](https://stackexchange.com/users/4672194/zazaalaza) on 2015-08-24
- score: 1

I wouldn't just pick an idea and go with it without doing some serious market research first, but I'd do one of two things:

1. Disrupt an existing market. E.g. a search engine built on a neural network.

2. Create something new. E.g. a tool that tells you what genetic traits your children will inherit based on your and your spouses DNA.


## Answer 7898

- posted by: [Mohammad Abu Musa](https://stackexchange.com/users/1386863/mohammad-abu-musa) on 2015-11-20
- score: 1

I am using machine learning to segment people based on products they used before, I want to help startups validate their products through connecting them with early adopters who used similar products to theirs before.

Please visit this page, you will find a video demo in the bottom 

http://findearlyadopters.com/startups

I would love to get your feedback.


## Answer 7906

- posted by: [Dawny33](https://stackexchange.com/users/6444670/dawny33) on 2015-11-21
- score: 1

<p>Great to see the love for data science and Machine Learning amongst startups.</p>

<p>So, I am the lead data scientist in a startup, and this is how we use ML here:</p>

<p>We model the customer journey into a graph, where the most important features are included in the node, and the derieved properties like the behavior of the customer, likes and dislikes, etc are modeled as hidden variables for the graph.</p>

<p>So, this became a <a href="https://en.wikipedia.org/wiki/Hidden_Markov_model" rel="nofollow noreferrer">Hidden Markov Model</a>.</p>

<p>The graph would look something like this:</p>

<p><a href="https://i.stack.imgur.com/aT6Dq.png" rel="nofollow noreferrer"><img src="https://i.stack.imgur.com/aT6Dq.png" alt="enter image description here"></a></p>

<p>Each z is a different state in which the customer is, in the marketing funnel.</p>

<p>From this model, we predict flags for the growth team about when a customer is dissatisfied or having a high probability of churning.</p>

<p>So, this is one application in which we use ML amongst a lot others.</p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
