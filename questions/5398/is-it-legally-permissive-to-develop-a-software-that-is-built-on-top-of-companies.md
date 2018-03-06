## Is it legally permissive to develop a software that is built on top of companies' services without getting permission?

- posted by: [Blaszard](https://stackexchange.com/users/2738792/blaszard) on 2015-05-29
- tagged: `legal`, `software`, `trademark`
- score: 3

Is it legally permissive to develop a software that is built on top of other companies' services? For example, [this OS X app named Chat for Tinder](https://itunes.apple.com/us/app/chat-for-tinder/id933848120?mt=12) mentions the following in the description page:

> Disclaimer: Tools for Chat and Tools for Tinder are not affiliated, associated, authorized, endorsed by, or in any way officially connected with Tinder, Co.

For your information, Tinder have not made its API in public and the aforementioned developer did it at their own discretion. As far as I know this is not the case in Twitter or Facebook, since they provide its API in public (of course developers can use their service only when they observe their regulation.)

So, my question is the following:

1. Is it legally permissive to develop and sell the service that is built on top of other companies' service (as long as developers prescribe it)?

2. If it is subject to the violation in one country but if the company or developer that develops it is based in another country, which country's law should be applied? 

3. If you develop an app that uses API released not by officials but by a third-party developer, is it you or the third-party developer who should be sued? (e.g. [Tinder API documentation on Github](https://gist.github.com/rtt/10403467))




## Answer 5399

- posted by: [Jeff O'Neill](https://stackexchange.com/users/46273/jeff-o-neill) on 2015-05-29
- score: 4

<p>Anyone providing online services has published its <a href="http://en.wikipedia.org/wiki/Terms_of_service" rel="nofollow">Terms and Conditions</a>.  If a company does not want you to use their services in any particular way, then it should be stated there.</p>

<p>If you violate a company's terms and conditions, then you are probably not violating a law (at least in the United States), but you could potentially be sued for breach of contract.  The more likely scenario, however, is that they will simply block your IP address and/or send you a nasty letter from an attorney.  If you persist (e.g., change your IP address) then you are asking to be sued.</p>



## Answer 5400

- posted by: [Ali](https://stackexchange.com/users/2815644/ali) on 2015-05-29
- score: 2

The problem with doing something the API owners do not approve of is that they can lock you out of the system very easily. They can block your key, change the API, or even blacklist your IP etc. When it happens, you would not be able to offer the service to your clients. If your customers have paid ahead, you'd have to refund them and your whole business model collapses. 

Take a look at http://tweetadder.com for an example of what happens when you get banned by the API owner. 

If you persist in it, they can legally sue you especially if they can prove to the court that your service is damaging their brand, affecting their system performance or causing them loss of revenue. 

If you want to build a business on somebody else's service, the first rule is you have to make sure that the service is reliable enough so that you can provide the desired quality and experience for your customers. This applies to all businesses including brick and mortar ones. For example, if you were offering a opening a retail store, and the power company that provides power to your store is unreliable and there is a black out every few hours, you are not going to be able to provide a good experience for your customers. 

If  you want to rely on somebody's API, the best thing to do would be to make sure you are on reliable footing. If you cannot discern this from their documentation, verify it by writing to them. Find out about limitations, throttling etc that may affect the service you give to your customers. 





---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
