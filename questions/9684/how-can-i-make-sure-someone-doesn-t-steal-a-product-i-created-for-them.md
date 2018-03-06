## How can I make sure someone doesn't steal a product I created for them

- posted by: [Jacques Marais](https://stackexchange.com/users/3848651/jacques-marais) on 2016-07-12
- tagged: `tech-company`, `website`, `web-development`
- score: 2

I am a startup web designer/developer and have just recently started my company. I have created one website so far, but that was for a family member. I was wondering how I could make sure that if I create a website for a person, that they pay me before I hand it over to them.

Is there any good and safe way to do this? Also, if I create a website and show it to them via the web, what is a safe way to make sure they don't copy the source of my pages and files?


## Answer 9686

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2016-07-12
- score: 2

Unless you're selling hand-coded HTML websites (which you should not) a way to proceed is to not give your client any admin access to the server until you have been paid.

Then, try to work out a schedule (you have a contract, _right_?) that goes something like 50% upfront (this should cover your costs) and then either 50% upon receiving the deliverable. Or for that matter, 100% upfront for smaller projects once you've enough experience and references that you can command higher rates. That way you reduce your risk - you cover your costs even in the odd cases where you don't get paid.

There's also something to say about avoiding crappy clients. Don't even try to do business with anyone who has "I'm going to be a source of problems" written all over their face. You'll learn to recognize them soon enough. More often than not they'll approach you like you're a code monkey with pre-conceived ideas that won't budge, and make you compete against cheaper remote code monkeys. Let the cheaper remote workers deal with them.

Lastly, don't fuss too much about it in practice. Most people are genuine and honest. Trust your gut and rule out working with people who you feel are not.


## Answer 9698

- posted by: [neutro](https://stackexchange.com/users/8808557/neutro) on 2016-07-13
- score: 0

Just an additional idea is as follows (one I've tried when I did web development):

In the event that a customer really tried to play games with me, I created a hidden page (whose URL only I knew about).  This hidden page on the site had an unlabeled text entry field with an unlabeled button.  If a particular code was entered into the text field, a php script was executed that deleted all of the other pages on the site (or at least rendered them non-displayable until I went in and made the appropriate reset).  Essentially, it was a self-destruct button that only I knew about.

I never had to use it or even threaten to use it.  I never informed the client of its existence.  Nevertheless, it gave me a lot of peace-of-mind when it came to addressing the non-payment issue.  It works well if your clients don't know much about web development themselves, and couldn't read the php script to realize what the mystery field did.

Overall, I'd say that if it got to the point of having to use the self-destruct, your relationship with your client is pretty much gone anyway, and your chances of getting the rest of the payment are slim.  But as mentioned before, the peace of mind was priceless.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
