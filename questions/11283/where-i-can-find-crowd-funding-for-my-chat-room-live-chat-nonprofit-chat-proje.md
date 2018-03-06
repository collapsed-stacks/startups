## Where I can find Crowd-Funding for my chat room/Live chat "nonprofit" chat project?

- posted by: [narzan](https://stackexchange.com/users/4938632/narzan) on 2016-10-04
- tagged: `crowd-funding`, `non-profit`
- score: 1

I finished coding chat room/ live chat.

**This chat can work only on two ways:**

 - Hosting it on my own servers and make it easy to people to just past
   a small code on their website without any coding knowledge.
 - Giving the code to people as an open source and make people donate
   for me, but the code require a developer to make it work on their
   website.

I really want to work on the first option, but I am a student and that require money for hosting..

I want to give a push up for bloggers, students and small businesses.
and make them pay a tiny fees just to keep my server running..
To make that I need funding to start up!
Most funding companies want to make profit from it!

Where I can find that kind of Crowd-Funding for nonprofit project!
Note: I am not in the US.  




## Answer 11285

- posted by: [BrettFromLA](https://stackexchange.com/users/2813127/brettfromla) on 2016-10-04
- score: 2

You asked about crowd funding, but this answer is a third option. You could sell / license your software to people for a very monthly small fee, like the price of a cup of coffee or tea.  Then, you could give them the small code to paste into their website without any coding knowledge.

To prevent theft or copying of your small code, make the small bit of code also pass the current URL to your servers. Your server can validate whether the owner of that URL has been paying their monthly fee. For example, if your small code appears on MyWebsite.com, then your server would query the database to see if MyWebsite.com has paid for this month. If they did pay for this month, then your server would provide your software. If they did not pay, then your server would provide an error message (or nothing).

NOTE: I realize you said "non-profit" in the title, so this may not be a good solution for you.


## Answer 11287

- posted by: [Chiragh Dewan](https://stackexchange.com/users/9254789/chiragh-dewan) on 2016-10-04
- score: 1

To begin with, the project that you're working would be more appropriately fall under the open source community rather than a Non-Profit. 

 - The best way to go about it would be to post the source code on a platform like GitHub and maybe make a webpage for the same and add a donation button. 

 - Another way to go about it would be to try to start with a free hosting website. Now I know that the config provided by those companies are really low and not sure whether your code will work on those servers or not, but it's an option to look into. 

 - Another option you can go with is providing it as a service. People who really want to use this product can contact you can you charge them a minimal fee and help them integrate your code with their existing website. This will also allow you to help others and after you do this for a couple of people, you'll have enough money to have your own servers and deploy on it (Digital Ocean provides hosting for as low as $5/month).  

 



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
