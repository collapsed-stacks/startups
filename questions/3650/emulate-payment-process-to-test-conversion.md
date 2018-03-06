## Emulate payment process to test conversion

- posted by: [Shcheklein](https://stackexchange.com/users/113167/shcheklein) on 2015-03-07
- tagged: `payment`
- score: 2

Is there some simple way to create a payment page that looks like a real one (credit card number and so on) but doesn't start the actual money transaction? Just something fast and realistic enough to test conversion level, engage with customers that are ready to pay and so on.

Easy means that it should not require company. 




## Answer 3651

- posted by: [blunders](https://stackexchange.com/users/216182/blunders) on 2015-03-07
- score: 2

<p>Assuming that you mean you want to not capture the credit card information, but be pretty sure that the user entered a valid credit card number - which is easy to do using <a href="http://www.regular-expressions.info/creditcard.html" rel="nofollow">regular expressions to learn more, visit this page</a> by <a href="http://www.oreilly.com/pub/au/3608" rel="nofollow">Jan Goyvaerts</a>; Jan is the author of a number of books on RegEx -- and produces a number of popular regular expression products including: RegexBuddy, RegexMagic, and PowerGREP.</p>

<p>If you have a language in mind, just Google "credit card validation using [INSERT-LANGUAGE-HERE]"; for example, <a href="https://www.google.com/search?q=credit%20card%20validation%20using%20javascript" rel="nofollow">JavaScript is very popular</a>.</p>

<hr>

<p><strong>Following is only of use if you're testing internally:</strong></p>

<p>Many merchants and vendors have fake/test numbers that are intended to be used for there system and are treated as a special test transaction that won't give the user an error message.</p>

<p>Googling "(test OR fake) credit card generator" will produce numbers that have a valid numberic pattern, but are not being pulled from a list of active cards; in theory, unless you're using a number supplied from a vendor, merchant, etc. the fake number might be real, though the other data would not match, so it would not matter. Using these numbers allows the user to bypass the not a credit card (CC) error, but get the CC not valid error.</p>

<p>Lastly, though not recommend, if the users are "trusted" - for example, employees - I've seen companies use a company card, then void the transactions; would not recommend this approach for a number of reasons.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
