## Finding a decent development team for my new startup

- posted by: [Onur Çevik](https://stackexchange.com/users/5600158/onur-evik) on 2015-01-09
- tagged: `software`, `team`, `hiring`, `android-development`, `cto`
- score: 17

My friend and I are working on a social networking app idea, but we both don't know enough coding to develop such a complex app.

We decided to hire a development team of approximately 5-10 developers which has developers for both, frontend and backend development, and also designers for UI design. While I tried to find such a team on oDesk and Elance, I can't trust those people but don't know why. I have a limited budget which is enough for a prototype app and I plan to try to get some investment or loan later on.

Do you know a decent development team that fulfills my qualifications? Or can you give me some advice on what I should do?


## Answer 2945

- posted by: [Jivan](https://stackexchange.com/users/2391382/jivan) on 2015-01-09
- score: 20

<p>You say you have enough budget to hire 5 to 10 developers immediately. Congrats, that's great news for you and you're asking how to find them. Instead of answering your question directly, I'll go for some observations that I made throughout my (still short but I've been through lots of promising but failed projects and I know exactly why they failed) carrier as a startup developer, then startup CTO.</p>

<p>My short answer will be to give up the idea of 10 people and concentrate every money you wanted to use building such a huge team into building a small commando of 3 to 4 really good people: 2 to 3 developers and one UX designer. <em>Edit: and a QA guy (how could I forget this one).</em></p>

<p>I'll explain why in the steps below.</p>

<p><strong>1. You can't handle 10 developers coming at once</strong></p>

<p>The most important point is <strong>don't hire 5 to 10 developers at once</strong>. You won't be able to manage them and your team will break apart before it has produced any result. Even companies 50 people big go through a lot of pain absorbing 10 developers at once. It's huge. We're talking about strongly opinionated people here (developers) and people who you can't afford to let go during the first few months without putting your whole project in jeopardy. The more people you'll have, the greater the chance that one of them leaves will be.</p>

<p>Building a team takes time and the technical side is just one (almost minor) aspect of the question.</p>

<p><strong>2. But you do need a single point of interaction with your team</strong></p>

<p>Another thing to take into account is, because both you and your cofounder have no solid technical background, you need to have one (and only one) person that you can trust to do the interface between you and the rest of the team. <strong>Otherwise you will get lost</strong> between one person telling you this, one person telling you that, and you won't be able to understand the connections between them.</p>

<blockquote>
  <p>Take this simple but concrete example: how does the client side code
  articulates with the server side code in the case when the front-end
  developer needs to make an Ajax request? The back-end guy will want to
  do it one way and the front-end guy another way, and there is no way
  you can arbitrate between the two of them. And if nobody does arbitrate this,
  your code will soon end up being a total mess that nobody understands.</p>
</blockquote>

<p>In consequence, among the developers you're going to hire, pick one (not the ninja guy, but rather the calm and reasonable guy) and make him your only interlocutor. He will report to you and will held technical responsibility for the team's results.</p>

<p><strong>3. You don't need that many people - in fact it's counterproductive</strong></p>

<p>In a project's early stages, there is not a lot of time available for design and architecture studies. And every developer has their own personal views and beliefs (sometimes almost religious) about what constitutes, in their minds, a <em>good</em> architecture. To avoid disagreements and building an app which will be completely heterogeneous, you have to limit the number of developers that contribute to the early project's foundations.</p>

<p>A modern social web application can be perfectly build with a team of, I'd say, <strong>two to three developers max</strong>. A server side guy (doing Python or PHP or Ruby or which language <strong>he</strong>'ll decide to go with), a client side guy (doing mostly Javascript) and (optionally) a "browser guy" (doing html &amp; css stuff).</p>

<p><strong>4. Don't forget the UX guy</strong></p>

<p>Finally, you're only talking about developers but don't forget that an app stands out in front of the competition not because it is well programmed and has a neat code inside, but by <strong>the quality and consistency of the experience it provides to its users</strong>. You definitely need a UX guy.</p>

<p>Plus, you can view this guy as the man who will give your coders the comforting and reassuring feeling that they have a strong and well-defined path to follow along. If you don't have any kind of experimented UX person in your team, your developers (especially the front-end and the html guys) will always work with the impression that they're making blurry stuff.</p>

<p><strong>5. Edit: don't forget the QA guy as well</strong></p>

<p>You need someone to do the testing. I'll point you to <a href="http://www.joelonsoftware.com/articles/fog0000000067.html">this article from Joel Spolsky</a> (the creator of this vast galaxy of Stack Exchange sites where you asked this question) to understand why.</p>



## Answer 2937

- posted by: [jdero](https://stackexchange.com/users/1972448/jdero) on 2015-01-09
- score: 9

I could share with you a myriad of secrets, but I'll stick to the topic here and just name a few which are incredibly valuable.

If you follow these steps, I truly believe you (and your product) are in good hands:

1. Start the project yourself. This builds credibility by showing you have the capacity to manage effectively, and not just make absurd deadlines. If you can't begin to comprehend the efforts and struggles of your dev team, you are going to have a hard time meeting deadlines (and making them realistically in the first place)

2. Use eLance, but remember to interview. It's important to practice building a personal relationship with the people (notice I didn't say objects) who will form your team. I've been working largely with just one person from India for almost 6 months now. He is going to finally visit our office sometime this year!

3. In building your system, isolate components of your application to build a self-securing gateway. Think of your software as a huge government building with different access cards pertaining to different doorways with restricted access requirements. Trust is hard to gain and easily broken. Always start off by trusting people, or you'll never get far. The moment you have reason to distrust them, don't "fear" your feelings - they're probably right. Just start at the lowest clearance and slowly move up and monitor their progressive responses.

Believe in yourself, and believe in the team you put yourself into.

P.S. Building an app can be long and stressful. Just remember what you're trying to do and don't just give up if things aren't working out. Never stop the car - just adjust the direction it's moving.


## Answer 7361

- posted by: [Rachel Collier](https://stackexchange.com/users/6961464/rachel-collier) on 2015-09-16
- score: 1

Outsource it. There are many outsourcing companies available in country's India and Philippines. They're good at it. You can entrust those works to external vendors. You will have some benefits when you outsource. That would include the cost advantages, increased efficiency, your focus on core areas, you can save on infrastructure and technology, accessed to skilled resources, timezone advantages and lastly better and faster advantages. I know that it would be a hard decision for you. It may take you to some risks but at least you've taken the challenge and surpassed it by next take. 


## Answer 2952

- posted by: [János](https://stackexchange.com/users/85903/j-nos) on 2015-01-10
- score: 0

I think software development changes year by year rapidly. The trends are that backend programmer does not need anymore. mBaas platforms, RESTful and subscription based backend makes impementation much faster. I made only by myself an MVP of an iOS community / dating site in 1 week, somewhat like Tinder. If you work with less enthusiastic guys, programming can take months, years, and the quality can be even worse. I have seen many times. But I can talk only about iOS.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
