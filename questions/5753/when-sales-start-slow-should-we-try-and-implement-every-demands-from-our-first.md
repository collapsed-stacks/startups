## When sales start slow, should we try and implement every demands from our first/potential clients?

- posted by: [Andy123](https://stackexchange.com/users/1546073/andy123) on 2015-07-16
- tagged: `tech-company`, `sales`, `e-commerce`
- score: 8

For the past 2 years, I have been working on a web application for my company, which provides a standardized e-commerce site aimed for a very specific market with specific regulations. The sales model would be based on a subscription fee, so clients would be paying for a continuous service. (**Saas**)

At the beginning of the project, a strong emphasis was put on **industrialization**: we needed a website that could be slightly customizable (mostly design: colors, fonts, pictures...), so it could be redistributed as-is to all clients, and benefit from updates from the codebase automatically: we'd just have to push updates to all clients, ignoring the custom stylesheet.

We launched the product, sales did not start flowing in... so our sales department started pandering to every demand of potential buyers: this meant that I had to add very specific and opinionized features (features that definitely a minor subsets of clients would want) to the codebase, **all while ensuring that these features could be opted-in/opted-out by future clients**, and in a very short delay since negotiations were running fast at the time.

This was harsh, but acceptable at the time since we did not have any running instance yet ; but nowadays I am feeling a twinge of regret. Because now we have one client with an instance running, and the company keeps dealing with these kinds of demands and asking me to implement them.

I feel like this is going against the fundamental idea behind our product: if we are going to tailor each and every site like it is the client's own, maybe we should start charging them for *an actual standalone website*, and not a subscription fee. Because all of these custom changes add up, and create a monstrous codebase for handling future updates and bug fixes, and making sure that one client's demand does not overlap another client's.

With all these things considered, I cannot help but sympathize with my company for wanting to get clients at any cost to get the project running. I am just worried that **there is currently no line being drawn**, and I do not seem to be able to communicate that feeling to them. I keep telling them "this goes against our model, you wouldn't call the Wordpress team and ask them to add *a field for adding silly pop-up ads on the top-left corner of iPad screens only*" (intentional exaggeration). But we are a launching company, so I guess this is a different situation.

What is your take on this, and do you have any advice to give, whether technical and/or communication-related? Is it a bold move to say *"no"* to customers [like Henry Ford did](http://diginomica.com/2013/12/03/true-saas-box-long-black/), when the company is struggling to get clients?


## Answer 5754

- posted by: [Community](https://stackexchange.com/users/-1/community) on 2015-07-16
- score: 6

You are in very complicated situation. I have been there myself but it was not that grave.

Let me share what would be my line of thinking if I find myself in it again today.

In first place you have to take into account you are not the authoritative person doing product vision or decisions (there are some sort of "business" guys, right?) so any fight you might pick with the subject matter experts would be very disruptive and nonconstructive. Going against the wisdom of the sales/product teams and vetoing or worse — refuting their roadmap is justified only if you are prepared to go into "take no prisoners" offense.

What you could do is provide feedback (ideally cost, in $) for what these decisions mean short and long term. This is uphill battle as well, but at least you are authority on what you are discussing and you are not the challenging party. If you manage to translate it into hopes and fears (excuse me, "opportunities" and "liabilities") important to the business/sales people — excellent. 

Once you have done the job above, all you can do is hope that your partners will be open to revise their view of the situation and consider your feedback constructively (even if they do don't expect miracles). If this is not the case (and it seems you guys have entered an "escalation of commitment" loop already) you have in general two options:

- dial it up — scream louder that doom is approaching, threaten to quit, so on... hoping that somebody influential will panic, grab the steering wheel and avoid the iceberg
- vote with your feet. Quit if you see they won't listen to you xor stay with the clear understanding that you are executing strategy you disagree with. If you choose the second option do your best not to act as a victim.

In case this line of thinking is relevant for you I can work further on elaborating tactics for providing the feedback. 

Overall you appear to have kept you head cool and this is the most important precondition for getting out of such situation.




## Answer 5755

- posted by: [Paparazzi](https://stackexchange.com/users/300272/paparazzi) on 2015-07-16
- score: 2

I have been with a couple starts ups and this is very real.   

Need to have a plan and enough capital to stick with the plan. Most startups don't have enough capital as the model is money starts as soon as the product is done.   

Sales should not have a direct line to development.  Need to have a product manager in between.  Strategic planning is foreign to sales - they just want that commission now.
  
I was sales support and for a while and prospects are always going ask can I have this feature or that. A weak sales person will just cave and say let me check. A strong sales person will ask what is the business need and show them how it is achieved with the current product. They need to get focused on closing the deal with what they have.  A revenue model with a dev cycle may pay the light bill next month but that is not how you grow a company.

I play a game with sales where they pretend to be customers and ask for whacked out stuff.  I break it down and show them how to with current product.  But I have knowledge of the business domain and did sales support for 3 years.

Like you said specific features hand cuff the product from strategic growth.

My favorite is need to be able to search across databases.  I said why?  And two databases won't have the same configuration.  They said this one does.  So I said why and sales said because they they loaded into two separate by accident. I said just take the load file and load into one.  Sales said they the started processing.  I said then export and import.  Sales said but they don't want to do that.  I said you have got to be kidding you want a major feature because they don't want to spend all of 2 hours to export and import data.

As a development manager all you can do is draw a line in the sand but they are going to step over it until a strategic product manager takes charge. And the real problem there is the code has likely been trashed out by then anyway. 

I have been dev manager for over 5 years and never had a feature list longer than 3 from sales and even then it is a trashy functional specification rather than a functional requirement.  They complain test cost is high and I tell them because you are taking one feature at a time to market.  The other problem you have is multiple versions in production as you don't want to risk banging everyone to the current rev until it is field tested.  So now bug fix has to be applied to multiple versions.  I have even had sales people tell me have to have this for a new customer but cannot apply it to existing customers as they like the way the current product works.  The problem you have is if the product is successful in three years you have mess that is expensive to support.

I don't have an answer other than do the best you can.  Try and at least have a stable data model.   Take it a feature at a time and just do the best you can. Try and take a specific requirement and build a generalized feature that does it.  Tell sales it take x months - don't tell them you could hack it in a few weeks.


## Answer 5756

- posted by: [JeffO](https://stackexchange.com/users/24180/jeffo) on 2015-07-16
- score: 1

There is a huge market for clients who want free software. If you take them on, expect them to keep asking for more. As you've stated, there is a risk that you will no longer be able to continue to deliver and maintain all these customizations with your current staffing.

The sales and marketing people have failed to negotiate deals that are beneficial to the company, but probably benefit the salesperson the most. They have not learned how to find good clients nor identify features that will bring the most sales in the long-run. Telling them to stop offering these extra benefits without enough fees to pay for the necessary staffing, is going to set them back. 

Explain the risks of your current software development and what staffing it will take to fix it. The alternative is to change the way you've been doing business which isn't going to be easy. 


## Answer 5888

- posted by: [stevenrcfox](https://stackexchange.com/users/42876/stevenrcfox) on 2015-07-29
- score: 1

There is a much better approach for both you and the sales people.

Build an API (on a change by change basis is ok) into your application and charge clients a development fee if they need enhancements. (does not need to be the full price of the change, as other customers will likely want a similar in the future.

Over time, the additional modules and the API will be valuable sales tools in their own right, and you'll have homogenous core system and a module ecosystem rather than a spaghetti mess!

Most business folk don't grasp the concept of technical debt. Its vital that this concept is understood, and ideally quantified as one of the company KPI's



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
