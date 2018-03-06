## Choose back end stack to quickly start up Saas/Social web app

- posted by: [tnsaturday](https://stackexchange.com/users/10702171/tnsaturday) on 2017-09-13
- tagged: `website`
- score: 1

I'm a self occupied front end developer as of now. That basically means that i'm pretty confident about HTML, CSS and JS (e.g. vanilla JS, jQuery/UI, and some Angular). Now i've decided to start my first very own project, which means i need to choose relevant stack of technologies and learn it quite well.

I've been googling around for this and that, and narrowed down to choose between RoR or Python + Django. This goes along with my list of requirements:

 1. I'm not feeling that well about classic static typed compiled
    languages like Java or C++ and go respectively.   
 2. I now close to
    nothing about back end, workflow of back end development and deploy.
    I know basic concepts such as http protocol, MVC model and SQL
    databases, but it's all kinda couch expertise, cause i've never had
    a chance to get my hands dirty about that. 
 3. I prefer to learn technology that is competetive on job market so that i 
    could later become more of Full Stack Developer, or even switch to back end
    entirely. 
 4. I need technology so that i can hit the market with my MVP
    as soon as in couple of month. Taking into account that i'll be
    working alone on whole back end thing maybe with a couple of people
    helping me with UI/UX and overall look of the app/site we'll be
    building.

Given that, i had to discard dated technologies with low job market profile like (PHP) or overall too difficult technologies like Java or Go (cause thay require much more expertise just to get started).

What would you suggest?


## Answer 13336

- posted by: [Neil Slater](https://stackexchange.com/users/2274369/neil-slater) on 2017-09-14
- score: 2

I think you've already done some good rational narrowing down on the assumption that you will write the first MVP. Both RoR and Python/Django are popular enough in general that you would find other developers to grow your product if successful. And also both reasonable fallbacks for you to work for someone else. If you cannot see a preference from a quick look at the languages and frameworks themselves, you may as well toss a coin . . .

There are a couple of other things worth looking at, provided investigating them does not take too long and cause decision paralysis:

 * If your SaaS product is joining an existing marketplace, what do other people in the market use? Not necessarily direct competitors, just related systems where you might have a pool of employees or employers.

 * Similarly, look at the job market in areas where you want to live/work. How do the technologies stack up locally, or perhaps for remote-only jobs?

 * Check the languages and frameworks in a bit more depth, see what existing libraries and plugins are available that might make your life easier, or that are areas that would be interesting for your company. Python's recent popularity is in part driven by the many useful machine-learning and scientific packages for example - if these are relevant to you or your work, then that might help you decide (because Ruby does not have as much in this area). Time limit this investigation though, otherwise you risk never starting. 




## Answer 13345

- posted by: [Neil Cresswell](https://stackexchange.com/users/3828551/neil-cresswell) on 2017-09-15
- score: 2

You mention familiarity with JS, possibly strong familiarity since Angular etc is also in your arsenal. So, why not stick with JS for your back-end too and leverage that with a node.js solution?


## Answer 13339

- posted by: [Stephan Lechner](https://stackexchange.com/users/3107532/stephan-lechner) on 2017-09-14
- score: 0

<p>If you are confident with HTML/CSS/JS but do not want to deal with backend technologies to much (or even at all), you might try a headless (API-based) cms approach combined with a cloud service. Thereby, you get an interface for editing the data underlying your app for free, while you can focus on rendering the data as you like using common frontend technologies.</p>

<p>Such a system is, for example, <a href="https://www.storyblok.com" rel="nofollow noreferrer">Storyblok</a>. Hope it helps.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
