## Best way to onboard non-techies to saas software?

- posted by: [Top Gear](https://stackexchange.com/users/4690596/top-gear) on 2015-01-16
- tagged: `customer-development`
- score: 0

I find that 1/10 people are able to figure out how to successfully use the product and these are technical people.

The other 9/10 have some success or none at all. This is because they miss steps or do not do things properly as dictated by the manual.

I reach out to them and help them how to use the tool properly which half of that 90% appreciate.

The other 50% of that 90% just doesn't seem responsive even when I send them a personal email offering to train them and point out what they did wrong. They even leave once they spent very little amount of time. Are these people simply bad fit?

My #1 concern is people making a mistake on their end and thinking that it's the software's fault. Some people do ask if its something they did wrong which it usually is.

My current method is to monitor their usage and reach out if they had too many unsuccessful attempts.

I just want to know if there is a better way to onboard these non-technical people to my saas software which lets you extract data from video files. You need some input from the user in order to make the data what they expect. This is what large number of non technical users are having trouble with.


## Answer 3042

- posted by: [Henry Taylor](https://stackexchange.com/users/1734959/henry-taylor) on 2015-01-17
- score: 2

I used to work for a software company that held itself up to an amazing discipline.  They took the blame for everything that went wrong in their software.  They didn't try to divide their customers into "the smart ones who could operator their system" and "everyone else who couldn't".  Instead, they embraced even the slightest hesitation from the most novice user with humility, abjectly apologizing for their software's failure.  ...and then fixing it.

The company motto was "every support call leads to a change.".  If a customer was so confused by the interface, function or scope of the system, that they actually picked up a phone and called for help, then there was obviously something horrifically wrong with the software.  Something that needed to be changed before another customer suffered from its effects.

And that software was an enterprise level accounting system...   At first, the phones rang a lot.  Very slowly, across years, the phone calls decreased and eventually stopped.  

What did I learn from working for that company?  I learned that beautiful interfaces are inferior to obvious interfaces.  I learned that rarely used options, which confuse those users who don't use them, are a detraction from the quality of the software;  I learned that any function that can't be described in a paragraph, should probably be left out or at least hidden from the default user view.

Before my time with that company, I wrote complicated, comprehensive solutions which took time and intelligence to master.  My ego was supported by the length of the software's feature list, how much longer it was than those of the competition.

Now I take pride in embracing obviousness.  I figure out what is important to my customers and I do that for them in the simplest, most unchallenging way possible.  And I've gotten my customers into the act, thanking them profusely when they show me how to make what I've written clearer for them.

Your software "extracts data from video files" after the user indicates what kind of data they are looking for.  I don't really know what that means or how many options you are offering your users, but those options seem to be causing 90% of them trouble.  As strange as it sounds, requiring the user to know what they want to do, is putting an unfair burden on them.  

So stop asking them to know what they want.  Computer power is cheap!  Waste a little!

Consider running your data extractions exhaustively, creating result sets for every possible user input, prior to asking them what they want.  Once you have an exhaustive set of result sets, filter out the empty and invalid ones. Show the user what you have found and let them choose which result set fits their needs.  

A/B test it, but I'd bet that the users will have an easier time choosing from available results, over picking from available options.




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
