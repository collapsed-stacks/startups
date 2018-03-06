## Purchasing SSL cert for startup

- posted by: [Jeff O'Neill](https://stackexchange.com/users/46273/jeff-o-neill) on 2015-09-25
- tagged: `website`
- score: 3

I want to have the nice green lock sign to the left of the URL bar for my website so I'm purchasing an SSL certificate.

It seems that you can buy from a reseller (e.g., namecheap) or directly from the provider (e.g., RapidSSL or Comodo).  When you buy from the reseller it is only $10 but when you buy directly it is $50!!!  It seems that you are buying the exact same thing.

This kind of thing always seems scammy to me because it doesn't make any sense.

Is there any reason why you would buy directly and pay more?  Is there any logic to this business model?



## Answer 7419

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-09-26
- score: 2

It's a matter of due diligence. Root and intermediate certificate authorities are in charge of doing their own due when they issue a cert. Some do very little - or indeed, none at all. Some are less greedy than others. Prices vary widely as you've noticed, ranging from free or a few bucks to lots.

The main thing that counts when picking your provider is this: Is the root authority recognized by all major browsers? If yes, cool. If not, run.

If you really want to nitpick, also consider whether you're dealing with a root authority or with an intermediate one. Because every cert between the root cert and yours is one that can be revoked for a reason or another. That's in theory. It's rare enough that you shouldn't care. HeartBleed occurred and should have resulted in blanket cert revocations but very few certs got revoked. And even if they had been, [revoking certs is broken](http://news.netcraft.com/archives/2013/05/13/how-certificate-revocation-doesnt-work-in-practice.html) anyway.


## Answer 7422

- posted by: [Robert Warren Gilmore](https://stackexchange.com/users/335394/robert-warren-gilmore) on 2015-09-26
- score: 1

It looks like you may not need to pay money for it at all soon. I heard of a new service that gives SSL certificates for free. https://letsencrypt.org/



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
