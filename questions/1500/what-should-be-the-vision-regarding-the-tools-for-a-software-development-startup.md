## What should be the vision regarding the tools for a Software Development Startup?

- posted by: [Sahil Babbar](https://stackexchange.com/users/4519390/sahil-babbar) on 2014-11-26
- tagged: `software`, `lean-startup`
- score: 2

I'm looking at choosing the programming frameworks and version control systems that should be used by a startup. So what I'm wanting to know is, should the startup keep a vision of 10 to 15 years or just follow what is best *now* in terms of technological tools. For example, nowadays, Ruby on Rails is one of the most sought after frameworks to build software but its capabilities are less as compared to JVM, if we consider the number of users. So, should the startup take Rails only and if later if necessary shift to JVM? e.g. Twitter did this. 


## Answer 1506

- posted by: [adrianh](https://stackexchange.com/users/7553/adrianh) on 2014-11-27
- score: 4

IMHO the right framework to pick is whatever framework your current team is most familiar with and can make the most progress in quickly. The biggest problems startups face isn't scaling and architecting for N years in the future. It's being able to deliver early prototypes and experiments quickly to validate that they have problem-solution or problem-market fit. 

I've seen many startups flail around for ages picking frameworks. I've also seen many startups waste way, *way* too much time and money prematurely architecting for the problems they assume they'll be getting N years in the future. In several cases so much time and money they die.

The number of startups I've seen fail, or heard about failing, because they picked the wrong implementation framework — zero. 

Because if you face scaling problems then you have a business model that works and you can either get investment or bootstrap. If you can't do either of those then the problem is going to be with the business model, not the software architecture or implementation framework.

The pattern that you see with successful companies is often reimplementation. eBay completely rewrote everything at least three times. Twitter haa fundamentally rebuilt their system at least twice. Basecamp has basically stuck with Rails, but completely rebuilt their product. Google has a rule of thumb for designing systems for a single order of magnitude increase over their current needs.

There's a common fallacy that these re-implementations could have been avoided. That's not true. The early implementations were fundamental learning tools that allowed the company to grow to the point where the latter implementations made sense.

You might find [this piece on Sacrificial Architecture](http://martinfowler.com/bliki/SacrificialArchitecture.html) a useful read.


## Answer 1503

- posted by: [Nick Wilde](https://stackexchange.com/users/454046/nick-wilde) on 2014-11-26
- score: 3

Well you know I think this is an ideal time to share a quote a friend shared with me a couple days ago:
> "Look at it this way: Barring a sharp blow to the head, as you stand
> here today, you are as dumb as you ever will be. We are all learning,
> getting smarter every day.
> 
> This is especially true in software projects: You can be sure that you
> will have a better grasp of the requirements, technology, and design
> of any software system that you work on at the end of the project than
> at the beginning.
> 
> Whenever you put in a feature before you really need it, you are
> guilty of programming while stupid; if you wait until you really need
> the thing, you are likely to have a better understanding of what you
> need to do and how you should go about doing it."
> 
> Russ Olsen, Design Patterns in Ruby

More specifically to your situation: 

- Should you make plans for 10-15 years from now in regards to what technologies you are going to be using? Probably not.
- Should you make plans for 5 years? Probably but you are most likely better to make choices that will be good now than in 5 years - if possible make technology choices that will support both development time and stability now and growth into the future.
- Should you make plans for 2 years? Definitely - and include some growth estimates in there.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
