## Could I monetize the creation of a data schema?

- posted by: [davidge](https://stackexchange.com/users/5417773/davidge) on 2014-12-02
- tagged: `intellectual-property`
- score: 2

I've worked with a widely used, unimaginably complex, dataset for years. Putting it into 2nd normal form seems impossible, but I sometimes think "just maybe I could do it...", but then I realize that there are too many exceptional cases and so I stop thinking about it". I am certain that there is value in doing this, but I'm not _exactly_ sure to whom. At the least, academics would, but they don't have deep pockets.

So, how would it work?

 1. create the keys, tables, columns, etc. that create 2nd normal form.

then what?   
Do I create wrapper classes, hide the data model somehow, then sell the wrapper classes as the only means to access the data model?  
Or, could I patent, (or copyright?), the data model, and sell a license to use it?  
Or, I don't know...

Schemas are not much different from APIs and the Java API was not deemed to be the intellectual property of Oracle, right? So, there really is no hope of a pay-off for creating a 2nd normal data model, right?

I love "open source", but there is no chance I will invest the time to try and do something that is probably impossible anyway without some hope of a financial pay-off. I've got so much other work, maybe I should stop thinking about this.


## Answer 1538

- posted by: [Henry Taylor](https://stackexchange.com/users/1734959/henry-taylor) on 2014-12-02
- score: 3

You may be addressing this opportunity from the wrong side.  Your looking at it as a technology creator.  Consider it from the technology consumer point of view.  What will such a consumer be able to accomplish with your normalized database which cannot already be done with the public dataset?  
The value which you can offer a potential customer base may not come from the raw data, reformatted into your new model... the value may come from the pre-digested results and statistics which your model can produce.  Offering a paid subscription to a web-service which constantly reports trends and statistics on a growing dataset is a viable business model; especially if the extreme complexity of that growing dataset makes it difficult for users to calculate those trends and statistics on their own.

**Edited due to new information from Comments...**  

Your targetted audience is therefore Enthusiasts of the Japenese Written Language, which is (in theory) a rather large audience.  If you deliver your product as a normalized database, you are limiting that audience to the subset which knows how to query a database.  Although not an empty set, this is a much more limited audience.  So again, I would recommend marketting the product of your data modelling, not the model itself.

One of the things I like most about StackExchange is that it has gamified the sharing of knowledge.  I think that you could do very well, gamifying the interaction of Japenese Language Enthusiasts.  Contests whose answers are drawn from your database, could be posted openly, allowing visitors to compete for points while you are collecting their contact and demographic information.  Such a site could be supported by advertising, by the sale of customer information to affiliate and email marketters, and game-token purchases.  Perhaps a visiter is only allowed to enter one contest per day for free, but tokens let them enter more.

A subscription model might work around a set of practice tools, flash-cards and other memory aids, aimed at Language Contest competitors.  You might also want to offer question generation services for Language Contest Organizers.

All of this is about leveraging the better-than-average access which your data model would grant you over the public data.  Sell the results, not the method.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
