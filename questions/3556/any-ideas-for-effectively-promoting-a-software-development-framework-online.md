## Any ideas for effectively promoting a software development framework online?

- posted by: [Evan de la Cruz](https://stackexchange.com/users/262161/evan-de-la-cruz) on 2015-02-28
- tagged: `marketing`, `software`, `web-development`
- score: 2

<p>The basic jist of the question is: How do I get the word out? </p>

<p>I'm not super concerned with monetization.</p>

<p>Promoting a framework is tricky, I think, because everyone and their mom has developed some cheesy home-grown framework and people tend to want to stick with stuff that is well-known / supported.  Also, anything that is overtly an advertisement, would be unappealing to most developers (I think).</p>

<p>Even if people are critical of the framework I'd at least like to get some eyeballs on it.  </p>

<p>My question is meant to be generic, but if it matters:</p>

<ul>
<li>The framework is for web development with PHP/Javascript/CSS</li>
<li>there are some unique things about this framework that I believe would be interesting to developers, if only I knew how to make them aware of it.</li>
</ul>

<p>I realize that you can't give me a full marketing plan.  Obviously there is stuff like SEO, pay-per-click, and traditional advertising such as print.</p>

<p>I'm more interested in finding out about any outlets that are specific to this sort of thing.  User groups, blogs, websites, contests, or anyone that would be willing to check out the framework.</p>



## Answer 3559

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-02-28
- score: 3

<p>You say in a comment:</p>

<blockquote>
  <p>I assume you're assuming that this project is open-source, which it can be. But I've never managed an open source project so I'm ignorant.</p>
</blockquote>

<p>I don't mean to give you too much of a sobering cold shower, but you really need to get real here. Your chances of successfully promoting a new PHP framework that is NOT open source are simply zero.</p>

<p>As in Nil. Zilch. Nada. Forget it.</p>

<p>Once you've resolved that by posting the source code on Github where it belongs, your next step will be create a website that doesn't make readers want to scratch their eyes out.</p>

<p>The site needs to show what's possible when using the framework. And as things stand if we're talking about ActiveWAFL, the layout, the colors, the typography, the navigation submenu bugs that overlap each other, etc. all contribute to give a terrible first impression.</p>

<p>Compare with the website of any of these popular PHP frameworks, and you'll get a feel of what I mean:</p>

<ul>
<li><a href="http://symfony.com" rel="nofollow">http://symfony.com</a></li>
<li><a href="http://framework.zend.com" rel="nofollow">http://framework.zend.com</a></li>
<li><a href="http://laravel.com" rel="nofollow">http://laravel.com</a></li>
<li><a href="http://phalconphp.com" rel="nofollow">http://phalconphp.com</a></li>
<li><a href="http://auraphp.com" rel="nofollow">http://auraphp.com</a></li>
<li><a href="http://www.yiiframework.com" rel="nofollow">http://www.yiiframework.com</a></li>
</ul>

<p>(As an aside, note that several (all?) of these sites offer actual books for users who are willing to learn them. Packt will publish just about anything though, so that's relatively straightforward to fix. Some also full-on training.)</p>

<p>You'll then need to come up with a very good explanation as to why a PHP developer should be using your framework instead of any of the gazillions of other battle tested, open-source frameworks out there. In particular, why yours instead of the popular ones highlighted above, knowing that several of them boast large, mature followings, and even some level of component compatibility -- e.g. Laravel is built on top of Symfony and Zend.</p>

<p>Perhaps even more importantly, you'll need to come up with extremely compelling explanations as to why one should be parting from just about every commonly used library out there. In particular: why not use Composer? Doctrine? Swift? PSR? That's a <em>huge</em> barrier to entry right there. Nobody wants to learn a new ORM or a new template engine.</p>

<p>Lastly, you'll want some community-related infrastructure: something for the community to contribute docs (a wiki or a versioned doc manager), something for community members to help each other out (Slack or IRC, forums, mailing lists), something to discuss what the next phases in the project will be (Slack or IRC, a project blog or wiki, a ticketing system), and so forth.</p>

<p>Once you get all of <em>that</em> in order, the time will be ripe to consider how to actively promote the framework.</p>

<p>Honestly, though, you need to take a cold hard look of your chances of success. Even reputable PHP developers such as those behind the Lithium PHP framework (aspect-oriented programming) or those behind the Habari CMS (clean code and admin area) didn't manage to gather more than a tiny following.</p>

<p>If the Ghost CMS is anything to go by, your first step towards promoting it will likely be a successful Kickstarter -- one that goes through all of the good explanations you came up with for your website.</p>



## Answer 3557

- posted by: [blunders](https://stackexchange.com/users/216182/blunders) on 2015-02-28
- score: 1

<p>Why not just pull a list of developers that already contribute to other frameworks using those languages? Then offer a bounty for finding a bug, adding a feature, deploying it to a site with the highest user count, etc.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
