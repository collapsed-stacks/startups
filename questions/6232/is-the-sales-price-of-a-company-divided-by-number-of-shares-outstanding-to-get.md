## Is the sales price of a company divided by "number of shares" outstanding to get the price per share?

- posted by: [Dave](https://stackexchange.com/users/107885/dave) on 2015-08-31
- tagged: `equity`, `stock-options`, `valuation`
- score: 1

<p>This is a follow up to my question:</p>

<p><a href="https://startups.stackexchange.com/questions/5989/how-do-i-figure-out-the-value-of-options-offered-any-relation-to-preferred-shar">How do I figure out the value of options offered? Any relation to preferred shares?</a></p>

<p>which adwiv was generous enough to answer.  I've done the research on my company, and there are 100,000,000 shares outstanding (number changed to protect the innocent :).  I got this information from:
 delecorp.delaware.gov/tin/GINameSearch.jsp  as suggested in the above post.</p>

<p>What does 100,000,000 shares outstanding really mean?  Are these shares spoken for (given to employees, sold to investors etc.)?   If the company was sold for 1 billion dollars, would each share be worth $10.00 (assuming no loans to be paid off), or are some of the shares "not allocated"?</p>

<p>Also, if some of the shares were preferred shares, how would this change the calculation of what each share is worth.  Is there a way to figure out how many of the shares are preferred shares?  </p>

<p>By bottom line here is to figure out what my 50,000 options are worth.  I believe (I may be totally wrong!) that I can come up with an educated guess on how much someone might purchase the company for, but without knowledge as to what percent of the company each share is, it's hard to assign a value per share.</p>

<p>Thanks!
Dave</p>

<p>Update:  I got some extra information by going to the online chat at  delecorp.delaware.gov/tin/GINameSearch.jsp.  The common shares are 60,000,000 and the preferred shares are 40,000,000.</p>

<p>They were listed by the operator as:</p>

<p>COMMON 60,000,000   .001
PFD    40,000,000   .001</p>

<p>Does this give me any extra info?  How do preferred shares usually work?  My option price is about $0.50.  What is the preferred option/share price? Is there some standard formula (10X?)?   I guess I need to know how much is promised to each preferred share to be able to evaluate how much each common share is worth.  Correct?</p>



## Answer 6236

- posted by: [eggyal](https://stackexchange.com/users/310184/eggyal) on 2015-09-01
- score: 2

<blockquote>
  <p>What does 100,000,000 shares outstanding really mean? Are these shares spoken for (given to employees, sold to investors etc.)?</p>
</blockquote>

<p>Yes.</p>

<blockquote>
  <p>If the company was sold for 1 billion dollars, would each share be worth $10.00 (assuming no loans to be paid off),</p>
</blockquote>

<p>Yes.</p>

<blockquote>
  <p>or are some of the shares "not allocated"? </p>
</blockquote>

<p>No.</p>

<blockquote>
  <p>Also, if some of the shares were preferred shares, how would this change the calculation of what each share is worth.</p>
</blockquote>

<p>One can use the <a href="https://en.wikipedia.org/wiki/Dividend_discount_model" rel="nofollow">Dividend Discount Model</a> to value the preference shares, and deduct that from total equity to obtain a value for the ordinaries.</p>

<blockquote>
  <p>Is there a way to figure out how many of the shares are preferred shares?</p>
</blockquote>

<p>Ask the company/check its filing records.</p>

<blockquote>
  <p>My bottom line here is to figure out what my 50,000 options are worth </p>
</blockquote>

<p>This question is very broad, and it's extremely difficult to provide a succinct answer without knowing the specific detail of your case.  Indeed, many substantial volumes have been written on the subject of pricing options; and there are entire university degrees devoted to the subject.</p>

<p>First of all, before you can value a derivative (such as an option), you must be able to value the underlying asset (the share).</p>

<p>There are a number of ways that one can value shares.  If they're traded on a quoted market, then the market price should be enough; however, it sounds as though they're not traded in your case—in which case you can:</p>

<ul>
<li><p>calculate the present value of the dividends that holders of those shares are expected to receive in the future (ad infinitum); or</p></li>
<li><p>apportion the business's total equity value across its share classes, and divide the relevant portion by the number of shares in your class.</p></li>
</ul>

<p>You're asking how to do the latter.  But to do that first requires that you obtain a value for the overall business: this could be obtained by DCF modelling, or by multiplying fundamental metrics by factors implied by transactions involving similar businesses (often one does both).  Having thereby arrived at an "enterprise value", you can subtract net debt to obtain a value for the total equity: if a preferential class of shares is debt-like (it really varies from business to business), you'd typically account for it here.</p>

<p>You're then asking how to apportion the resulting equity value between the remaining classes of share (there might only be one remaining class, but in any event it's is usually a simple case of dividing pro rata to each class's share of the profits—although you may wish to make adjustments for quirks such as voting control, liquidity restrictions, etc).</p>

<p>Having arrived at a total value for your class of share, you can indeed divide by the number of "outstanding" shares to arrive at a(n undiluted) value for each individual share.  You can then feed this into Black–Scholes to get a value for the option.</p>

<p>Clear as mud?</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
