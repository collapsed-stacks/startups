## How can I make my product economically feasible?

- posted by: [Top Gear](https://stackexchange.com/users/4690596/top-gear) on 2014-09-19
- tagged: `customer-development`, `business-model`
- score: 2

Background: My product extracts data from pdf files. Free users get 8 free jobs. Paying users get 40 jobs. Each job is a data extraction from a pdf file.

Problem: User engagement terminates after they run into a bad extraction. On some pdf files it just doesn't work, it returns empty data. Most times it extracts data but not exactly to what the user had in mind (duplicate, mismatching column, unwanted data). Right after this happens, the user will either try a few more times with other pdf files or just give up and never return again. To fix the cases where it returns empty data, it takes me at least 10 hours. 

Concern: I can't support myself to work on such fixes and I can't see the number of bad data extraction that needs to be fix decreasing for each user. It's very tough problem to extract data from pdf files, it's never perfect but I was hoping it was good enough for some users. Even a paying user with their number of fix requests, I would have a hard time getting to them all. The bigger problem is that I priced is cheap so I would get more users, turns out this would lead to a far greater number of problems being encountered with the data extraction process.

Search for solution: My immediate thought is to ditch the free plan, increase the product price and somehow deal with the number of fixes being requested and barely breakeven. 

I don't know if anyone's been in this situation, it almost seems like the end user cares about the result of the data extraction unlike say a bookkeeping web application that has a much narrow scope of problems expected. Like if a pdf doesn't extract correctly, it's of no value to the user so they will want this to be fixed right? And as they keep encountering more and more fixes I won't be able to keep up....


## Answer 2947

- posted by: [rob](https://stackexchange.com/users/19190/rob) on 2015-01-09
- score: 1

You need to start by writing a business plan. Although you may have to make up a lot of numbers in the first draft, just going through the process is incredibly valuable because it forces you to think about aspects of your business which you may not have ever considered.

Part of a business plan includes a break-even analysis to see how many paying users you need in order to cover your expenses under various scenarios. Perhaps your expenses also include subsidizing the free users. Determine how long you can go before you need to break even, then look at how many users you have now and try to work backwards to see how much growth you will need to see each year. If your goals still seem realistic, set some measurable success metrics along the way and review your progress at each point.

Prepare an exit plan and decide up front what you consider failure at each benchmark point.  If at any point you are failing, then either adjust your plans accordingly or exit.



## Answer 754

- posted by: [Matthew Haugen](https://stackexchange.com/users/1325646/matthew-haugen) on 2014-09-19
- score: 0

My initial reaction is to wonder how *worth it* this business actually is for you. That's a hard thing to hear and an even harder thing to question yourself, but if you're encountering more bugs than you have time or resources to fix, it might be time to hang this project up for a while.

Before jumping to any conclusions in any direction, ask yourself a few, basic questions

 - Do you have something to fall back on? Is this project actually taking up time that *would* be better spent, more than time that simply *could* be?
 - What commitments do you have with regards to this? Do you have legal or ethical responsibilities to your current clients? Do you have employees?
 - Is there any conceivable end to the bugs? It seems like there should be, since file types tend to go through a finite number of iterations, so once you handle each bug, you should be a step closer to being done with them all. Ten hours is *a long time* to spend on a single bug that only occurs once, for one user.
 - What sorts of success-rates are you getting? Although this one is less important if you're already spending all your time fixing the errors, even a 95% success rate is probably only going to be as good as your 5% fix rate.
 - What is this used for? Is it something that the client *needs*? In other words, alongside with success rate, could you market it as, say, 95% successful, and the other 5% they do manually? Or is it definitely necessary to have 100%, or else it's entirely useless?

In all honesty, I don't have a ton of confidence that you'll be able to drop your free level and bump up your prices, particularly if the paid customers are often running into bugs too. I don't know a lot about the industry, but I've used Spire.PDF before for reading PDF files, and it seems like they have pretty good support and effectiveness, not to mention a free version.

If I were you, and if I had a better way to spend my time, I would probably just open-source it. You might even be able to drive clients to whatever your next venture is if you have something solid in the open-source community, and that should take a fair bit of weight off your shoulders as far as fixing things is concerned. If you think you might want to sell it again one day, you could just keep it aside and work on it here or there. But I wouldn't focus on it any more, pending those above questions.

Regardless of what you do, I definitely think you should stop acquiring new clients. It will be harmful to your reputation and potentially even open you up to some liabilities if you continue to release a faulty product, especially when you're aware of how badly it's going.


## Answer 2978

- posted by: [22SAVY](https://stackexchange.com/users/5612597/22savy) on 2015-01-12
- score: 0

You should definitely open source your software, if I were in this position I would increase my price drastically. I would make my software more user specific(software built for a certain kind of client that benefits most from pdf file data extraction) then I would charge 100-250/month. You have a proven concept, double down on the kind of clients you think have the biggest budget and pivot your software/business for those guys. Also if your software extracts data from pdf files, what other files can it extract content from? online content ,summaries,essays. I think theres a multitude of things you can do with the software. Ideally with this kind of software you should go with the ten true clients model, each client should be worth 1000$ So pivot your software/service to provide a 1000$ worth of value to your clients. 



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
