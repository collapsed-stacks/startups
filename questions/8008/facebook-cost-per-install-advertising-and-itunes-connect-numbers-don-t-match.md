## Facebook cost per install advertising and itunes connect numbers don't match

- posted by: [vondip](https://stackexchange.com/users/43161/vondip) on 2015-12-05
- tagged: `mobile-apps`
- score: 5

I've got an iOS app on the App Store which costs $5.

Lately I've started advertising it on a cost per install basis on Facebook.

While Facebook reports many downloads and charges me for them, iTunes connect doesn't recognise these downloads and subsequently I don't get paid for them.

What could be causing this? Has anybody else encountered this issue?

Please note, I'm viewing results from a few days back, so most likely it has nothing to do with data not yet being digested by apple.



## Answer 9043

- posted by: [Marcus D](https://stackexchange.com/users/258531/marcus-d) on 2016-04-25
- score: 1

This isnt an answer, but might help you towards the answer. @Denis de Bernardy's article is interesting. I would suggest that there is an underlying problem here that itunes is ignoring because it is just oncharging you.

The direction I would go, is to download all the data you have into Excel and attempt to join your FB data and your itunes data together so you can try and tell more about the problem and identify something similar about the rogue transactions. This is sort of a datascience.SE question, but you may be able to analyse the data and find that FB downloads from specific countries are highly likely to be fraudulent, or transactions done at a specific time of day relative to local time, or IP address. To be honest I'm not sure what information you receive from either source.

It's tricky to analyse, but the key is understanding the data. It is possible that if you can prove to itunes that specific transactions are exact duplicates or have a fraudulent "signature" they you can build up a case. 



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
