## How to protect my idea and code before pitching it

- posted by: [warship](https://stackexchange.com/users/4801837/warship) on 2016-03-21
- tagged: `intellectual-property`
- score: 20

<p>Are there any safety mechanisms set in place to protect your ideas/code when pitching your startup to prospective funding agencies (e.g., Y Combinator, Techstars, etc) or angel investors?  </p>

<p>I recently heard a horror story of an angel investor promising to invest in a startup company, then after receiving all the juicy details (both strategy and implementation) from the CEO, taking these intellectual property contents to another similar company with a better team and proposing them as his own.  Now I understand that had these ideas/codes been already at least under provisional patent, such a situation would have been less likely to occur (albeit not impossible).  </p>

<p>So my question comes down to: what can I do, as a software developer with a code base and business plan, to proactively defend myself during the pitching process?  Do I have any other weapons at my disposal (besides for provisional patenting of my code implementations and their projected applications in my field of expertise).  I am fully aware that a provisional patent would only secure my claim to the idea/code for 1 year, so I would need to act fast in securing seed funding and rolling out a patent shortly thereafter.   </p>

<p>Related posts: <a href="https://startups.stackexchange.com/questions/1067/how-to-protect-my-idea-when-seeking-a-business-partner">How to protect my idea when seeking a business partner</a>, <a href="https://startups.stackexchange.com/questions/5966/how-do-i-protect-my-startup-idea-in-an-academic-setting">How do I protect my startup idea in an academic setting?</a> </p>



## Answer 8781

- posted by: [Mowzer](https://stackexchange.com/users/1803081/mowzer) on 2016-03-21
- score: 25

<p>TL; DR: There is no perfect solution. Self-funding is mine.</p>

<p>This question comes up all the time. I have been doing this for a while and this is the most difficult part of being a tech entrepreneur. I have yet to find a single, go-to, comprehensive solution for this problem. Every option seems to come with its own unique set of negative unintended consequences. So it comes down to choosing which set of negative unintended consequences you want to live with.</p>

<p>However, since you are a developer, you have one key option that is not available to non-developers. This is the option I have opted for several times myself (as I am a developer too). It is this:</p>

<blockquote>
  <p><em>Go it alone. Develop your product without any outside help and self-fund its development.</em></p>
</blockquote>

<p><strong>The problem with VCs and NDAs</strong>.
The scenario you describe in your OP is definitely a possibility. Many  VCs won't sign an NDA. At least not until they agree to a deal. And by "many," I mean most if not all. If you look around the internet you will find much written about how approaching VCs with NDAs before pitching them makes the entrepreneur seem naive, amateurish, un-savvy, etc. And, AFAIK, VCs have many more pitches than they can read or hear. So they can just move on to the next pitch if you insist on an NDA.</p>

<p><strong>The problem with patents</strong>. The patent field is so technical and complex you really need a lawyer to do it. And lawyers are expensive. And if you are like me, as a developer, you probably have more product ideas than you have time to build them all yourself. So, obtaining a patent on each idea when you get it is... expensive. Probably prohibitively so. Also, I heard somewhere they are no longer issuing "process patents" which applies to most software and apps. Although that might be a false rumor. Don't go by what I say here; do your own research. Also, you might already know, the moment you write your code, you receive copyright protection. Your remedy for all IP protection is to sue. Again, expensive.</p>

<p><strong>The problem with partners</strong> <em>this includes co-founders as well as money parters like VCs, seed funders, angels etc.</em> is the potential for disputes about who owns what. Especially if you already have your own code base. I've had a prospective co-founder demand the rights to all the code I have ever written. Obviously preposterous. But in my experience, non-technical co-founders have a tendency to vastly overvalue their contribution and vastly undervalue yours. I think this is because only a developer can know (because you've done it) how difficult it is to develop something, write the code and make it work. Non-developers tend to estimate about 1% of the actual time, effort and knowledge it takes. There's no way you will make up that gap when you start negotiating ownership with a (newbie) non-tech co-founder. Also, if you are smart, you will want to reuse a lot of your code base on your next project. And many more after that. The potential for disputes about this is increased dramatically if you add partners. Even one. Also, at many key points you might have to pivot on your concept or some important element of your strategy or implementation. Again, as soon as you add that second person, you have to get people to agree. That takes time, effort and there is a real cost in potential for sub-optimization or outright company-ending disagreements. Aside: Did you know the number one reason for startups failure is disputes among the management team?</p>

<p>Startups only do two things: product development and sales. Before the product is developed there is nothing to sell. So if your prospective partners aren't writing code, what value do they really have anyway?</p>

<p><strong>The problem with self-funding</strong>. It takes a looooooong time. To build anything substantial. It's hard work and long hours with no immediate compensation. However, I have found it to be worth it. Once you are revenue positive, it will be a lot easier to bring people on board with terms that are more realistic.</p>

<p>The most useful ideas I've found for achieving positive revenue are:</p>

<ol>
<li><p>You need to be full-stack. This includes front-end. I started writing my first app with the back-end first but eventually came to grips with the fact that the user is going to eventually have to interact with the product. Fortunately, last year I stumbled across Polymer (a Google open source project). And an excellent solution for taking advantage of the web-components spec and allowing for front end development to reuse these "web components" and focus on only writing what's new for each app. Less than one year in production. Otherwise, a good front-end solution would be even more challenging.</p></li>
<li><p>Slow and steady wins the race. Accomplish (at least) one thing per day. When you develop solo and self-fund you enter a marathon not a sprint. Each day of that marathon you need to stay motivated and on track. A technique that has been effective for me is to set a daily goal of accomplishing one major, complex task (or set of tasks) each day with a clear product or deliverable. And I try not to sleep until I succeed. Sleep has become my de facto self-reward mechanism.</p></li>
<li><p>You need to work backwards in your design. Hopefully, you have started with a solid core of <strong><em>domain knowledge</em></strong> about the environment your product will be used. How things are currently done in the industry. And what your customers, clients or users will really need. So my trick has been to focus on the user. Understanding them and their needs. Then incorporating all that into the product design and strategy.</p></li>
<li><p>Build it first. Customer feedback is invaluable. But they need to see something. Build a prototype. Then start reaching out to customers. If you point them to a nice looking, working app (without all the bells and whistles) you gain instant credibility. They will give you useful feedback that you then recycle back into the product design. Repeat that process until you have something people are willing to pay for.</p></li>
<li><p>Trim out all the fat. Meaning you probably won't need all the features you currently imagine in your product. Identify the essential few. There is a concept called <strong><em>minimum viable product</em></strong>. Look it up. Understand what that means. Focus on your MVP then release something. Add the bells and whistles later in future releases. Product upgrades. Or premium pay services.</p></li>
</ol>



## Answer 8794

- posted by: [Dendi Suhubdy](https://stackexchange.com/users/4264924/dendi-suhubdy) on 2016-03-23
- score: 1

<p>By simply (and smartly) not putting confidential information inside a pitch. That may sound simple but it really is the way around for meeting with VCs that do not require them to sign NDAs each time you talk to them.</p>

<p>For example, if you are in the robotics domain, do know show your abstraction of classes/concept of programming to them. Show them the end product through a video. At least these days and idea is just worthless without you building the product itself.</p>

<p>You may already know that talking to an investor means a lot of trust on both parties. If an investor like that f**ks up the situation by shopping your idea to another team, that is frontrunning and that is unethical.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
