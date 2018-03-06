## Should we open the API of our smart object?

- posted by: [Thomas](https://stackexchange.com/users/2545829/thomas) on 2015-05-23
- tagged: `tech-company`
- score: 8

Our startup is making a smart object. You connect to it via Android or iOS, and use the smartphone to control it (e.g adjust the temperature of it via the app)

We were wondering if it would be a good idea to go "open" with our smart object API and allow any developer to write an app that connect to it.

On the upside : looks cool on marketing, and we could focus more on the product and less on the apps if someone made better apps that us

On the downside : I feel that there has to be one (competitors could use their app to control our product etc) but can't think of anything harmful

What's your experience on that ? Do you know any company that opened their api with success or failure ?

NB : Im talking about communication between our bluetooth product and a smartphone, nothing related to servers

Thanks !


## Answer 5349

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-05-23
- score: 5

The answer lies in the question for the most part: the main side-effect is other devs using your smart object in unforeseen ways.

You can hardly go wrong with that. Until you do. Like IBM did when it decided to let Microsoft run the show. So, keep the truly strategic stuff in-house. Let others play with the rest.

Two other famous examples are Facebook and Twitter.

Both attracted a strong following of developers thanks to their open API.

Of possible interest: both also fiddled with how the developers could use it. Only one of the two did so before turning into a de facto utility. Cripplingly so in my opinion -- the rate limitation erased all developer goodwill overnight. I do not think Twitter will recover from that mistake.


## Answer 5428

- posted by: [NotMe](https://stackexchange.com/users/1771/notme) on 2015-06-01
- score: 2

When selling a device you need to look at who your market is.  Are they people who just want to plug it in and essentially forget about it?  Are they people who want to tinker with it?  Are they people who want to take your thing and use it as a component to build something else?

If they just want to plug it in and forget about it then you need to focus on making a slick UI that makes this incredibly easy.  Kind of like Roku with their remote.  

If they want to tinker, then you need both - an easy / basic UI but also an API that has a few extra tricks for those that want to explore it.  The UI is still the primary focus but you have the API for those tech heads that like to play around.

If they want to use your product in a larger product, then you need to focus heavily on the API making it as robust as possible as this will be the primary means your device is communicated with.  The UI should be considered throw away, although it should still have an Easy and Advanced mode - likely only implementing a small subset of what the device can do.


## Answer 5430

- posted by: [Malekai](https://stackexchange.com/users/5820495/malekai) on 2015-06-01
- score: 1

I would suggest that it depends on what exactly your product is capable of. If your own app will cover all of the functionalities of your product then there would be no need to develop anything else.

For example: If your product is something that controls the lights, temperature etc of your home, then surely your own app will cover all capabilities of the product. Whereas if your product is more like a micro controller (generic) then it may be worth opening up your API to developers.

The main issue I would say is that "Is there any point?" and "What do WE get from this?". As another answerer has said, opening the API does have some risks, therefore it absolutely is not worth taking if you stand to gain nothing from it.

Without the details this is just a best guess, but my gut says you shouldn't expose your product, any weakness in your API could cause potential security risks for people using Third Party Apps to control your product. Control the way your product can be safely used by keeping control of your API.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
