## Downround equity calculation

- posted by: [franck](https://stackexchange.com/users/2321339/franck) on 2015-12-16
- tagged: `equity`, `funding`, `investment`, `financing`
- score: 2

<p>Suppose you own 10% of a company valued at 1M and then there's a down round valuing the company at 250k, the round is 200k big. </p>

<p>How to calculate how much money do you have to put in this round if you want your equity to remain 10%?</p>

<p>How diluted are you, if you don't put any money in?</p>



## Answer 8135

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-12-16
- score: 4

<p>Imagine for a moment that you've 10% of a company valued a $1M w/ 1M shares. It means you've 100k shares.</p>

<p>Come a round that adds $200k with the company valued at $250k. It means you're going to increase the number of shares by 1M * 200k/250k = 800k. Total shares is thus 1.8M.</p>

<p>If you don't put money in there, you still have your 100k shares, which is to say 5.56% of the company's 1.8M shares.</p>

<p>To keep your 10% stake, you'd need to own 180k of the new 1.8M share pool. That means buying 80k of 800k new shares valued at $200k, i.e. your cost will be $20k.</p>

<p>If we assume the round is larger in that the new investors are buying $200k worth of stock regardless of what you do, you'll need to match their contribution at that rate while keeping 10%. That means owning <code>x</code> extra shares such that <code>100k + x = (1.8M + x)/10</code>. In other words 88.9k shares which valued as above means $22.2k give or take a rounding error.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
