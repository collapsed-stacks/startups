## Any ideas for effectively promoting a software development framework online?

- posted by: [Evan de la Cruz](https://stackexchange.com/users/262161/evan-de-la-cruz) on 2015-02-28
- tagged: `marketing`, `software`, `web-development`
- score: 2

The basic jist of the question is: How do I get the word out? 

I'm not super concerned with monetization.

Promoting a framework is tricky, I think, because everyone and their mom has developed some cheesy home-grown framework and people tend to want to stick with stuff that is well-known / supported.  Also, anything that is overtly an advertisement, would be unappealing to most developers (I think).

Even if people are critical of the framework I'd at least like to get some eyeballs on it.  

My question is meant to be generic, but if it matters:

- The framework is for web development with PHP/Javascript/CSS
- there are some unique things about this framework that I believe would be interesting to developers, if only I knew how to make them aware of it.


I realize that you can't give me a full marketing plan.  Obviously there is stuff like SEO, pay-per-click, and traditional advertising such as print.

I'm more interested in finding out about any outlets that are specific to this sort of thing.  User groups, blogs, websites, contests, or anyone that would be willing to check out the framework.


## Answer 3559

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-02-28
- score: 3

You say in a comment:

> I assume you're assuming that this project is open-source, which it can be. But I've never managed an open source project so I'm ignorant.

I don't mean to give you too much of a sobering cold shower, but you really need to get real here. Your chances of successfully promoting a new PHP framework that is NOT open source are simply zero.

As in Nil. Zilch. Nada. Forget it.

Once you've resolved that by posting the source code on Github where it belongs, your next step will be create a website that doesn't make readers want to scratch their eyes out.

The site needs to show what's possible when using the framework. And as things stand if we're talking about ActiveWAFL, the layout, the colors, the typography, the navigation submenu bugs that overlap each other, etc. all contribute to give a terrible first impression.

Compare with the website of any of these popular PHP frameworks, and you'll get a feel of what I mean:

- http://symfony.com
- http://framework.zend.com
- http://laravel.com
- http://phalconphp.com
- http://auraphp.com
- http://www.yiiframework.com

(As an aside, note that several (all?) of these sites offer actual books for users who are willing to learn them. Packt will publish just about anything though, so that's relatively straightforward to fix. Some also full-on training.)

You'll then need to come up with a very good explanation as to why a PHP developer should be using your framework instead of any of the gazillions of other battle tested, open-source frameworks out there. In particular, why yours instead of the popular ones highlighted above, knowing that several of them boast large, mature followings, and even some level of component compatibility -- e.g. Laravel is built on top of Symfony and Zend.

Perhaps even more importantly, you'll need to come up with extremely compelling explanations as to why one should be parting from just about every commonly used library out there. In particular: why not use Composer? Doctrine? Swift? PSR? That's a *huge* barrier to entry right there. Nobody wants to learn a new ORM or a new template engine.

Lastly, you'll want some community-related infrastructure: something for the community to contribute docs (a wiki or a versioned doc manager), something for community members to help each other out (Slack or IRC, forums, mailing lists), something to discuss what the next phases in the project will be (Slack or IRC, a project blog or wiki, a ticketing system), and so forth.

Once you get all of *that* in order, the time will be ripe to consider how to actively promote the framework.

Honestly, though, you need to take a cold hard look of your chances of success. Even reputable PHP developers such as those behind the Lithium PHP framework (aspect-oriented programming) or those behind the Habari CMS (clean code and admin area) didn't manage to gather more than a tiny following.

If the Ghost CMS is anything to go by, your first step towards promoting it will likely be a successful Kickstarter -- one that goes through all of the good explanations you came up with for your website.


## Answer 3557

- posted by: [blunders](https://stackexchange.com/users/216182/blunders) on 2015-02-28
- score: 1

Why not just pull a list of developers that already contribute to other frameworks using those languages? Then offer a bounty for finding a bug, adding a feature, deploying it to a site with the highest user count, etc.




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
