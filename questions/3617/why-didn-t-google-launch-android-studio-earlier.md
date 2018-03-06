## Why didn't Google launch Android Studio earlier?

- posted by: [Mohammad](https://stackexchange.com/users/1679161/mohammad) on 2015-03-05
- tagged: `startup-costs`, `brand`, `android-development`
- score: 4

I'm an Android developer. I remember when I started coding for Android, Google was recommending Eclipse to compile, and now, after years of launching first Android versions Google has it's own Android studio.

Isn't it cheap for such a big company to use an Eclipse plug-in instead of its own Android studio?

I don't think Google had lack of resources at first, it could hire a separate professional team to work on Android studio parallel with ones working on Android OS itself.

I think there might be a reason.
Any idea?

What kind of simplifications damage your brand and what not?


## Answer 3619

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-03-05
- score: 1

The colloquial idea is "ship fast and iterate," in contrast with shipping something *perfect*. Eclipse is a good enough IDE (and indeed a very good one), so there was no reason to rush Android Studio.

The rule of thumb is: if ignoring a feature doesn't make your product dysfunctional or useless, then not implementing it immediately should be on your radar. Release that as version one. Then plan for follow-up releases.

(In the case of Android, there *might* also have been something related to the [legal claims from Oracle](http://en.wikipedia.org/wiki/Oracle_America,_Inc._v._Google,_Inc.), or something related to mimicking what Apple does. *Might*.)


## Answer 3621

- posted by: [blunders](https://stackexchange.com/users/216182/blunders) on 2015-03-05
- score: 0

There are a lot of assumptions floating around in this question in my opinion, to the degree I almost feel as if the question in the end doesn't add up.

Yes, there are differences between the two IDEs -- and yes, Google might have gone with IntelliJ instead of Eclipse to start, but sounds unlikely to me. What I do know is that they've been working on this over two years and no longer actively developing for Eclipse; which to me goes against the claim Google has unlimited resources, they don't.

I could try to spin this some how into being some sort of progressive form of developing a product to limit resource expenditure and mitigate risks, but the fact is unless the real reasons behind Google's switch are known, it's just speculation; which is what it is.


## Answer 3623

- posted by: [plunntic](https://stackexchange.com/users/2200821/plunntic) on 2015-03-05
- score: 0

I would rather say, that it's not any "launching", it's just a bad word to me. Years later they just been telling that eclipse is official Android IDE, and now their changed their mind saying, that InteliJ is official Andoird IDE. Android Studio is not their product, it's just a customized for android development version of InteliJ. Probably you have some sugar on top of that, maybe some of it becomes from google, but the crucial part - the IDE - is an open source project.

So, to answer your question, I think it might be that they follow the hype for jetBrains products, and it might be that they really see more potential there (which they didn't years ago). Hard to say.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
