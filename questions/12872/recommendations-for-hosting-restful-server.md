## Recommendations for hosting RESTful server

- posted by: [Sharon](https://stackexchange.com/users/284897/sharon) on 2017-06-19
- tagged: `mobile-apps`, `servers`
- score: 0

I'm building my first app in Android Studio, and I need to connect to a central database, so I'm creating a REST interface. I'm getting ready to laumch, but not sure how best to go about hosting my REST interface. I don't have my own web space or anything I can use, and I also don't have much of a budget at this stage.

I'd like something where I can put it for free or very cheaply to start off with, while I finish building it, just to test and so on, and in the early days if there aren't many users (so either something with a free trial, or one which only charges by the amount of traffic or something like that). On the offchance that it gets really popular, I also need the hosting to scale up (or for it to be easy to transfer elsewhere) - obviously I'm happy to pay for that if it happens.

Just don't want to fork out a lot of money now, especially as I'm still some way off being able to earn money from the app, and can't really afford to pay for hosting I don't need.

I have very little knowledge of the technical aspects of hosting, so something that's either easy to use or has very detailed documentation would be good too.

All the recommendations I've found have been from several years ago, so I'm assuming things might have changed since then.

Any recommendations are much appreciated.


## Answer 12873

- posted by: [Mahesh Attarde](https://stackexchange.com/users/4638292/mahesh-attarde) on 2017-06-19
- score: 1

<p>Easiest way to start with RESTful server on android is  to  use  <strong><a href="https://cloud.google.com/endpoints/docs/frameworks/legacy/v1/java/" rel="nofollow noreferrer">google  cloud endpoints</a></strong>.
You can also  easily start with <a href="http://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-create-api-step-by-step.html" rel="nofollow noreferrer">AWS endpoints</a></p>

<p>Do check restrictions for datatypes and processing limitations for this. ( i had few issues with image processing while back) </p>

<p>Personally i used laravel+ GraphQL stack on docker with  AWS deployment. (bit of advanced 
but worth if you need freedom from cloud limitation.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
