## Why is Java not so popular in software development startup projects?

- posted by: [AndreaNobili](https://stackexchange.com/users/2056257/andreanobili) on 2016-05-12
- tagged: `tech-company`, `software`, `web-development`
- score: 94

<p>I am a <a href="http://en.wikipedia.org/wiki/Java_Platform,_Enterprise_Edition">Java EE</a> developer (more specifically a <a href="http://en.wikipedia.org/wiki/Spring_Framework">Spring</a> <a href="https://en.wikipedia.org/wiki/Spring_Framework#Model.E2.80.93view.E2.80.93controller_framework">MVC</a> developer), and I have always worked in the typical enterprise environment (mainly big company and public administration).</p>

<p>I am very interested in technological startups, and I am considering the idea of work for a startup to see something different.</p>

<p>I noticed that most of the job offers proposed by startups are not for Java developers. I know that nowadays the best front end technology are related to JavaScript (<a href="http://en.wikipedia.org/wiki/AngularJS">AngularJS</a> and <a href="https://en.wikipedia.org/wiki/React_%28JavaScript_library%29">React</a>). But it is not difficult to integrate a Java back end to an AngularJS front end (for example; it is absolutely good practice to implement a back end using the Spring Framework and then use its MVC component to create robust <a href="http://en.wikipedia.org/wiki/Representational_state_transfer#RESTful_web_services">RESTful</a> web services that serves the AngularJS front end).</p>

<p>The thing that seems me so strange is that, for startups, the most popular position is for <a href="http://en.wikipedia.org/wiki/PHP">PHP</a> developers. What does PHP offer that Java doesn't? I think nothing. Indeed, it tends to be much less robust than Java as it is not natively strongly typed. But I don't want to open a flame war between Java developers and PHP developers.</p>

<p>From my experience, I think that the Spring framework provides a real state-of-the-art software architecture, and I really don't understand why it is considered the main reference in the enterprise development, but is not considered in startup projects.</p>

<p>I also noticed that <a href="http://en.wikipedia.org/wiki/Ruby_on_Rails">Ruby on Rails</a> is becoming very popular in startup projects. Does this language offer something that Java doesn't?</p>

<p>I am asking if these kind of preferences depends more on the some psychological reasoning, or are related to language learning curve or what...</p>

<p>What do you think?</p>



## Answer 9132

- posted by: [Dawny33](https://stackexchange.com/users/6444670/dawny33) on 2016-05-12
- score: 67

<p>This might sound very non-intuitive. But, in most startups, <strong>the language of choice is mostly the one which is the area of expertise of the CTO or of the one who built the startup.</strong></p>

<p><strong>Why?</strong></p>

<p>Because, when they were building the company, the priority was to build an <a href="https://en.wikipedia.org/wiki/Minimum_viable_product">MVP</a> as soon as possible, and definitely not the language. So, they generally choose a language which they are most comfortable in, and which can get the work done.</p>

<p>So, going forward, the architecture gets too big and complex. So, companies tend to stick with it, and try to improve it rather than re-writing it into another language. <strong>Rewriting an entire company's architecture in a startup is a very hectic and a bad idea.</strong></p>

<p>So nowadays, such problems are being handled by breaking those monoliths slowly into <a href="http://microservices.io/">microservices</a>, which can be written in a different language.</p>

<p>The same explanation above works for your question regarding: <em>Why PHP and not Java.</em> too.</p>



## Answer 9137

- posted by: [Carlos Silva](https://stackexchange.com/users/7837401/carlos-silva) on 2016-05-12
- score: 41

<p>In my opinion, these are the two main reasons:</p>

<ol>
<li>Practicality. Languages like Ruby, PHP or Node tend to be faster to develop with than Java, even if at the expense of robustness as you point out. However in a startup speed is everything - you need to very quickly develop a prototype or MVP that gets you paying customers and / or funding. I'm actually going through the pain of transitioning from a Ruby/Rails architecture to Java microservices at the company I work for, because Ruby is not coping with the load and number of users we acquired in the meantime. But, choosing Ruby proved to be the right choice to get the company off the ground, and now we have the staff and revenue required to re-architect.</li>
<li>Anti-corporate thinking. As <a href="https://startups.stackexchange.com/users/5834/dawny33">@Dawny33</a> pointed out, in most cases the language of choice is the one the CTO has experience with or interest in. Many people who decide to create or work in a startup (such as the CTO) have something anti-corporate about them. Either they worked in a large corporation before and want to escape process, bureaucracy, and multiple management layers; or they decided that they want to challenge the status-quo. Java, created by Sun Microsystems (large corporation), owned by Oracle (large corporation), and used mostly by large corporations, is seen as a corporate language. So, some startup founders decide to use other languages to further position themselves away from corporations.</li>
</ol>



## Answer 9146

- posted by: [Jim](https://stackexchange.com/users/351236/jim) on 2016-05-12
- score: 36

<blockquote>
  <p>Why Java is not so popular in software development startup projects?</p>
</blockquote>

<p>First - I love Java. I write a lot of code in java. For startups, I recommend (and have used) PHP... ugh. EDIT: Ruby is also a good choice, Python maybe next IMHO /EDIT</p>

<p>In a startup you want a programming language that offers the following:</p>

<ol>
<li>Fast and easy changes to the visible elements of your product</li>
<li>Cheap labor (or at least, cheaper than your competitor)</li>
<li>The ability to scale "enough" - but not too much</li>
</ol>

<p>You can't sell what you can't see or show to people. So, any startup that focuses on code quality, scalability, extensibility or anything else in an attempt to "plan for the future" is probably wasting their time. You use the term "robust" which is similar to these concepts. Most startups fail. Investors don't want to spend their money on a scalable, maintainable, "robust" codebase that ends up in the garbage. </p>

<p>The same is true if a startup focuses too much on "getting customers before they have a real product" or "saving money for next year" or "spending money that you haven't earned." There are a lot of startup pitfalls - and a big one is <em>not building up tech debt properly</em>. Tech debt is like credit card debt, right? And lots of businesses start off with credit card debt, spending more than they are earning -<em>but weighing that risk against the debt they are accumulating</em>. Tech should not be any different. With a startup you are betting today's loan against tomorrow's earnings.</p>

<p>Putting Java in as a solution early could be like leasing an office that can hold 50 people when you only need 5. Or buying 30 cubicles because it's cheaper per cube, but you only need 10. Or getting an expensive phone system or whatever else might "prevent future problems" - but will you even have a future if that is the choice you make today? That is the core of the issue. However, if you plan to build cars, you need a garage/space at least big enough to build one! So, a company may <em>need</em> Java, but that is different from selecting it as a way of planning ahead.</p>



## Answer 9167

- posted by: [chrylis](https://stackexchange.com/users/1223835/chrylis) on 2016-05-13
- score: 32

<p>As a CTO whose product backend is written in Java/Groovy, I think the answers so far are mostly missing the pragmatic reason: inertia resulting from serious friction that's been close to eliminated in the last three or four years.</p>

<p>Most relevant for Web startups, managing a servlet container has always been a massive headache, from development through staging to production. Configuration was cryptic, deployments never worked quite right, debugging could be tricky, and container quirks always tended to show up at inconvenient times.</p>

<p>On top of that, Java has traditionally been thoroughly XML-happy. Building a Java Web application involved your POM, your servlet descriptors, your Hibernate mappings, your Spring application context files... It was a lot of externalized configuration adding significant overhead and very little value.</p>

<p>All of this meant that in a big company where applications were giant and sysadmins took care of the servers, the advantages of Java (particularly typing and the huge library ecosystem) gave it an edge, but in startups, the overhead was just too much.</p>

<p>Recently, however, new developments such as Servlet 3 and <em>especially</em> Spring Boot, which eliminates essentially <em>all</em> configuration except for the application-specific settings you want to provide, have made JVM projects even easier to work with than the traditional scripting competitors, while at the same time providing smooth refactoring paths for the future and a single-jar replicable deployment that needs nothing but a JVM installed. This is why a number of companies from Stormpath to Netflix have switched to Boot recently.</p>

<p>Changing minds takes time, though, and over on SO I constantly see questions about complicated Spring configuration arrangements from someone who's trying to get started based on a tutorial from two major versions back. To somebody who knows that it's all unnecessary and <a href="https://twitter.com/rob_winch/status/364871658483351552">a working Spring application can fit in a tweet</a>, Java is an obvious choice, but its reputation hasn't caught up to its new ease and flexibility.</p>



## Answer 9138

- posted by: [Peter Masiar](https://stackexchange.com/users/2249598/peter-masiar) on 2016-05-12
- score: 18

<p>This exact question was answered by <a href="https://en.wikipedia.org/wiki/Paul_Graham_%28computer_programmer%29" rel="nofollow noreferrer">Paul Graham</a>, founder of Viaweb and Y-combinator (so I think his opinion is highly relevant here) in his essay <a href="http://www.paulgraham.com/avg.html" rel="nofollow noreferrer">Beating the averages</a> </p>

<blockquote>
  <p>During the years we worked on Viaweb I read a lot of job descriptions. A new competitor seemed to emerge out of the woodwork every month or so. The first thing I would do, after checking to see if they had a live online demo, was look at their job listings. After a couple years of this I could tell which companies to worry about and which not to. The more of an IT flavor the job descriptions had, the less dangerous the company was. The safest kind were the ones that wanted Oracle experience. You never had to worry about those. You were also safe if they said they wanted C++ or Java developers. If they wanted Perl or Python programmers, that would be a bit frightening-- that's starting to sound like a company where the technical side, at least, is run by real hackers. </p>
</blockquote>

<p>Read the linked article, it explains differences in power of the programming languages (from his POV).</p>

<p>Also, if your plan includes being bought by Google, you may consider to use the technology <strong>they</strong> are interested in - and that would be more Python than Java (except Dalvik I guess).</p>

<p>Re @djechlin comments: <a href="https://stackoverflow.com/questions/2560310/heavy-usage-of-python-at-google">Heavy usage of Python at Google</a> by one of top Python gurus, Alex Martelli. read it up, Google uses</p>

<blockquote>
  <p>C++ for the parts of the software stack where very low latency and/or tight control of memory were crucial, and Python, allowing more rapid delivery and maintenance of programs, for other parts. </p>
</blockquote>

<p>BTW Guido works for Google too. </p>



## Answer 9133

- posted by: [Z Z](https://stackexchange.com/users/7691178/z-z) on 2016-05-12
- score: 13

<p>Another reason for this is that start-ups generally need to get the initial release out sooner, with the ability to run on "average" hardware with out breaking the bank. Hence the reason to use languages like PHP etc., that can run on a variety of hosts without the need for heavy duty RAM.</p>

<p>As the company expands, they may well choose the rearchitect the system and use another language. But this will have to be in stages.</p>



## Answer 9140

- posted by: [Monty Harder](https://stackexchange.com/users/3002189/monty-harder) on 2016-05-12
- score: 12

<h1>JVM Vulnerabilities</h1>

<p>I'm not a "developer"; I'm a system administrator.  It is a distressingly-frequent task of mine to replace older Java Virtual Machines in which security vulnerabilities have been found, with newer ones (in which no vulnerabilities have been found ... <em>yet</em>).  Every time I have to do that, there is a non-trivial chance the new JVM will break one or more of the Java apps running on it, which means going back to the developers and getting them to fix the Java code so it will run on the new JVM, deploying the new code to the QA environment and letting the QA team re-test, [lather, rinse, repeat] until we finally have Java code that will run on the new JVM I can push together with the Java code to production.  (Having to replace both at once during the maintenance window overnight is <em>so much more fun</em> than doing one or the other.)</p>

<p>Even if it didn't break anything, there's still my time patching, and the QA team's time to validate that nothing broke.  Java has become such a pain point for me that when we recently built out an upgraded environment for one application for which a previous admin had written some glue code in Java, I rewrote the glue in cmd.exe batch files just so we wouldn't have to put a JVM on the new servers.  If I can do something with built-in OS components, and not need an add-on interpreter, I have reduced the attack surface that needs to be defended.</p>

<p>This endless patch/test/rewrite cycle adds to the "total cost of ownership" of Java apps.  I can't be the only person to have decided that cost was too high to pay.</p>



## Answer 9134

- posted by: [Marcus D](https://stackexchange.com/users/258531/marcus-d) on 2016-05-12
- score: 9

<p>There is a certain startup way of thinking that says "<strong>open source is good</strong>" and "<strong>proprietary is bad</strong>". We have pitched for work in a few startups (I do MS SQL Server) and was told that they only use open source languages.</p>

<p>This isn't meant to be a rant against open source. I love it, and use R, but I think the rationale could be some of the following:</p>

<ul>
<li>Open source generally means "free"</li>
<li>The more popular open source languages have very significant user bases</li>
<li>The fact that the language is controlled by the users, means that any user can write/critique the code</li>
<li>The <strong>open</strong> aspect of open source means that the code is easily accessible to anyone, so has a large body of people testing and critiquing it.</li>
</ul>



## Answer 9182

- posted by: [bmargulies](https://stackexchange.com/users/44736/bmargulies) on 2016-05-14
- score: 7

<ol>
<li>There are many startups. Most of them fail. If you want to look at the relationship between programming language and startups, you would do better to look at the ones that last a little while.</li>
<li>You focus on Java Enterprise. As a CTO, I don't know anyone who knowingly touches J2EE with a very long pole. I know a fair number of people who code computational, parallel, tasks in Java. Look at the entire Hadoop ecosystem.</li>
<li>As others have explained at length, many early-stage startup start by worrying about the user experience, building a minimal back-end. That generally means 'Angular' or something like it as the actual front end, there are a number of ways to bang out an initial back-end.</li>
<li>The jobs advertised as, of course, the jobs that the core founders aren't doing for themselves. (Excepting <a href="http://whartoniteseekscodemonkey.tumblr.com/">the infamous code monkey case</a>). That might skew things in various ways.</li>
<li>If, as others have pointed out, you are racing to get noticed before you burn through your angel money, well, you are looking for a very lean approach. Unless you are working in one of the Java ecosystems (see remark about Hadoop), the mere fact that Java requires compilation should lead you to wonder if it's going to be the fastest path.</li>
</ol>



## Answer 9183

- posted by: [djechlin](https://stackexchange.com/users/1413944/djechlin) on 2016-05-14
- score: 7

<p>Disclaimer, my last startup was half Java and half Node.js, we seemed to survive.</p>

<p>I think this is actually an extremely fascinating question. In my opinion, the answer is almost entirely cultural. <strong>Tech stacks, in particular languages, are an incredibly powerful way for a company to signal to investors and recruits just what the company is all about.</strong></p>

<p>Some loose stereotypes:</p>

<ul>
<li>Java, C++: either a baby language you use in Programming 101, or a, literally corporate language, likely to be in use by 10,000+ employee enterprises.</li>
<li>Python, Ruby: easy languages that are the choice of a modern educated technologist.</li>
<li>Scala, Haskell, Ocaml: "hard" languages that hyper-intelligent, possibly academic people like.</li>
</ul>

<p>I think there is a sociological feedback loop: once these stereotypes have bubbled up - and they certainly have - companies will double down on them to differentiate their offering. <a href="https://stackoverflow.com/research/developer-survey-2016#technology">You might peruse the StackOverflow developer survey results</a> for some evidence backing what languages are "cool."</p>

<p>And I must address the fact that <strong>there is really no reason to give Java primordial prefence.</strong> Some developers don't like Java. Some start startups. Some join startups. Who are you to silence them because you like Java? Whether Java is a "good" language is an awkward question, but there are many other languages people think are very good, would love to spend their day job coding in, and usually can't in a "corporate" setting because Java is a proven language and the upside to migrating off millions of lines of code in a proven language is small. </p>

<p><strong>Startups do not have the legacy factor.</strong> Some developers who either <em>love</em> hacking in new languages with beautiful features in their spare time, or developers who <em>hate</em> Java even for personal or political reasons like despising Oracle, have created thriving open source communities and code bases making it as easy for a startup to get up and running in Ruby or Node.js as easily as a corporation like Facebook or a media company can spin up a new web server on their own Java or PHP stack.</p>

<p>I'm sorry to say that many other answers given in this thread are nonsense.</p>

<ul>
<li><strong>The CTO probably is seasoned in Java or C++ and can probably get a robust web server running very quickly.</strong> They will probably use IntelliJ (or Eclipse but eh) for an IDE that manages Java boilerplate, MINA or Netty for multithreaded IO, Spring or Guice or Dagger for IoC, Maven for build, Jenkins for deploy, JUnit for testing, a beautiful JVM for debugging and performance tuning, the Play framework for web, Guava or now, finally, Java 8 for immutability-oriented code and functional programming, very quickly.</li>
<li><strong>I think of Java as easier to performance tune than the Python or Ruby VM.</strong> I'm not an expert here but this simply is not something startups optimize for. You get an AWS small box and the JVM runs just fine on it. This was never an issue when my startup had as few as 3 developers.</li>
<li><strong>There is no such thing as writing for a target acquirer's tech stack.</strong> One, it's impossible - you think Java at Google looks <em>anything like</em> the Java you write on their own? And Google's build system is its pride and joy, it's certainly not going to integrate your Maven stack and Jenkins deploy. Two, there are many different acquirers with incompatible tech stacks. Three, it's a nonsense business strategy in the first place. You want to prove to your acquirer that you are viable long term without them in a sale, not that you are supplicant to them and are nothing without their generosity.</li>
<li><strong>Java is not a "bad language."</strong> Many huge, profitable companies are clearly getting by just fine on it. Although if you need to fill an awkward silence during an interview and can't legally ask about religion, family, etc., asking the candidate their opinion on that is a great way to fill the time.</li>
<li><strong>Startups that don't prioritizing hiring "good developers" I assume just fail</strong>. Java developers being expensive, <em>if</em> that's true, well, you get what you pay for.</li>
<li><strong>Startups go through multiple rearchitectures and migrations</strong> of small parts of their stack and their whole stack multiple times. Seriously, I don't know why people keep claiming this <em>never</em> happens, that sounds like something you would say if you haven't actually joined your first company yet. If it did never happen then you made a mistake because premature <em>scaling</em> is the root of all evil. You probably move off of Ruby on Rails to something else at some point.</li>
</ul>

<p>TLDR: Java is dead, long live Java!</p>



## Answer 9152

- posted by: [coteyr](https://stackexchange.com/users/2001206/coteyr) on 2016-05-12
- score: 6

<p>To be honest, it's because "Java Sucks".</p>

<p>Now, let me be clear, as a language I actually like Java. I like how it works, and if I have to choose a strongly-typed language I usually would pick Java. That being said, this is what I see happening at startups all the time:</p>

<p>CEO ask around, and asks some developers, some people, some UI guys, "What language would you use?"</p>

<p>All the guys, have their different favorites, and one of them even suggests Java.</p>

<p>All the other guys, go "Well, Java's nice, but this one time..."</p>

<p>The CEO goes back to the "Java supporter" and says "everyone has a horror story", and the supporter is stuck going "well yeah, if you write bad code bad things happen".</p>

<p>The overall attitude of the group gets summed up as "Anything but Java!" or "Java Sucks!", even though individually, each person on the list only has one or two bad experiences with Java code.</p>

<p>What it really comes down to is that Java, as a language, has not received the "good vibes" that other languages have. The companies that "run" it have a "bad" or "no fun" reputation. Every developer out there can think of at least one horror story in Java.</p>

<p>It's simple: Bad public relations.</p>

<p>Play the game in your head:</p>

<p>What's a popular, well-supported, profitable application (that you didn't work on) written in...</p>

<ul>
<li>PHP</li>
<li>Ruby on Rails</li>
<li>Python</li>
<li><a href="http://en.wikipedia.org/wiki/Perl" rel="nofollow">Perl</a></li>
<li>.NET</li>
<li>Java</li>
</ul>

<p>What is a terrible, unprofitable, slow app written in:</p>

<ul>
<li>PHP</li>
<li>Rails</li>
<li>Python</li>
<li>Perl</li>
<li>.NET</li>
<li>Java</li>
</ul>

<p>Which ones can you answer faster, without the use of Google.</p>

<p>Also keep in mind that companies that write Java applications, tend to try to hide the fact that it's a Java application at all. This is true for games, desktop applications, web applications, and all.</p>

<p>Java just has a bad reputation. Plain and simple. I don't think it's a well deserved reputation, but it has it all the same.</p>



## Answer 9178

- posted by: [transistor09](https://stackexchange.com/users/184507/transistor09) on 2016-05-13
- score: 6

<p>What do other languages offer that Java doesn't? With startups in mind there are a few examples.</p>

<h1>Go</h1>

<p>Go has a few design features that make exploratory programming very pleasant. A few examples I can name:</p>

<ul>
<li>interfaces checked <strong>on use</strong> which means they don't have to be explicitly implemented. You can make your current types implement a new interface without changing a single line of old code</li>
<li><p>extending is fun! You don't have to declare a new type, your function definitions are simply attached to types:</p>

<pre><code>func (the_this *the_type) function_name() {
    the_this.variable = "this works!"
}
</code></pre></li>
</ul>

<h1>Python</h1>

<p>Its syntax sugars are very addictive.</p>

<pre><code>["FizzBuzz"[4 if i % 3 else 0:4 if i % 5 else 8] or i for i in range(1,101)]
</code></pre>

<h1>JavaScript</h1>

<p>With Node.js you can use it to drive your server too. This can be extremely helpful because people that like the same languages are more likely to have similar thought process. Front and back developers communicating efficiently can be the key to success.</p>

<p>Also, in case the team composition changes, people can be much more easily swap places and continue with the work.</p>

<h1>But what does it mean?</h1>

<p>Startups are typically small so each person is vital. Morale has to be high, fatigue low to keep everyone focused.</p>

<p><del>Java, with all its keywords, infers a very rigorous design process.</del> Or so I thought, before I was pointed out not factually correct in the comments. That exposed the more fundamental problem: there might be people thinking that Chekhov's gun applies to keyword use and others who don't, so there's potentially more things to disagree about.</p>

<p>Bottom line is that there are far more nimble languages than Java. Even if they are <em>less safe</em> the results can be produced sooner. Everyone likes results.</p>



## Answer 9180

- posted by: [Nick M](https://stackexchange.com/users/921041/nick-m) on 2016-05-13
- score: 6

<p>Later edit: The short answer: because java sucks.</p>

<p>The long answer: I think if you ask a thousand startups this question, you'll probably get a thousand different answers.</p>

<p>I'll tell you why we don't use Java in our company:</p>

<ul>
<li>Developers are either very expensive or not good at all;</li>
<li>Java apps eat up much more resources, that means a higher servers bill;</li>
<li>Almost all Java applications I saw in production were very difficult to scale, this is 2016, one can't just spend a good chunk of the budget on idle servers, nor afford having extensive downtime required by infrastructure scaling operations;</li>
<li>Development takes significantly more time; we can do the same app 10 times faster with Rails;</li>
<li>Java is not a language built with developer happiness in mind. Ruby and Python are.</li>
<li>The development environment for a Java app takes significantly more time to set up, but I guess this is only done once. Although I on occasion had to spend days trying to figure out cryptic error messages caused by some random idiot shutting down the computer that hosted some random repo where a portion of the code was hosted. In highly regulated environments Github is not an option, same as trying to convince some Fortran-punchcard-minded manager about the advantages of a central code repository.</li>
</ul>

<p>We do financial transaction processing, sports and gaming solutions. Our platform is a self-scalable, agile hybrid consisting of about 5M lines of PHP and Ruby code sitting on top of about 50Gb of highly volatile data. We keep this in MySQL clusters and a distributed graph database.</p>

<p>Before Java we tried .NET. It was a nightmare, almost took the company bankrupt. </p>

<p>Probably in the future Node.js will bring even more agility into our platform and also help lower the bills a bit more ;)</p>

<p>Also, some years ago before I started doing what I do now, I worked as a consultant at a bank. They were building their intranet on a Java stack, it was GREAT at laundering money, basically about 50% of what the bank was paying in development, maintenance and hardware went back into some managers' pockets.</p>

<p>Cheers.</p>



## Answer 9143

- posted by: [djheru](https://stackexchange.com/users/1136951/djheru) on 2016-05-12
- score: 5

<p>I don't use Java, but I am a developer (PHP, Python, Javascript) and do have experience with startups. With an early-stage startup, speed is of the essence. When you have no revenue to speak of and you're paying your developers using investor money, you want to have something to show for your efforts as quickly as possible. </p>

<p>It goes back to the fast/good/cheap triad. For most startup software products, they want it fast, and they want it cheap, and they'll wait until there's a proven need for it before they worry about making sure that the architecture is sustainable or can support growth over the long term.</p>

<p>Some languages and frameworks are designed to promote rapid application development and others are designed to promote stable, scalable architectures with large surface area. I would say that languages/frameworks like Ruby on Rails, node.js with something like Express, PHP with something like Laravel tend to fall more on the "rapid development" end of the spectrum and languages/frameworks like Java/Spring, C#/.net fall more on the stable, scalable end.</p>



## Answer 9215

- posted by: [Peter Masiar](https://stackexchange.com/users/2249598/peter-masiar) on 2016-05-16
- score: 5

<p>Another misconception is that Java might be better than Python because Java code executes faster. <strong>The only speed relevant for a startup is speed to the market</strong> - and experienced coder can produce code <strong>much</strong> faster in Python than in Java, because Python compiler works much harder for the programmer (offloading many decisions which Java programmer has to do).</p>

<p>Also, if 90% of your code is spent in calls to database libraries (same for Java and Python), there is no way to improve speed by using Java enough for it to be relevant. IOW: <strong>Optimizing outside of bottleneck is waste of effort.</strong></p>

<p>Citation:</p>

<p><a href="https://stackoverflow.com/questions/2560310/heavy-usage-of-python-at-google">Heavy usage of Python at Google</a> says: </p>

<blockquote>
  <p>C++ for the parts of the software stack where very low latency and/or tight control of memory were crucial, and Python, allowing more rapid delivery and maintenance of programs, for other parts. ... Java came in later, covering an intermediate niche </p>
</blockquote>

<p>(so Java is faster to develop in than C++ but slower than Python)</p>

<p>Also, personal experience. </p>



## Answer 9194

- posted by: [software.wikipedia](https://stackexchange.com/users/1750120/software-wikipedia) on 2016-05-15
- score: 4

<p>My answer is very incomplete but I hope it brings one more aspect for some niche startups.</p>

<ul>
<li>A lot of data analytics related recent startups prefer scala / python due to the platforms they have chosen e.g. spark. </li>
<li>Many startups begin work with help of freelancers - and I guess PHP may be one of the largest freelancer community to find cheap freelance resource. I would hire a cheaper PHP programmer over a cool java developer. Despite knowing java.</li>
<li>CTOs expertise example is very appropriate since facebook used PHP, and twitter Ruby for same reasons. Although they all now try to prove that each of these languages are scalable, maintainable etc. They need to show it to the world they did the right thing. Until they really fail.</li>
<li>All fancy languages may also give a feel of highly technical company. Just like someone said startups using Python may be run by hackers. We all know you can mess a business with best of programming languages. </li>
<li>Most startups fail. Very few survive, choice of language may not even be 1% of failure reasons. <a href="http://blog.codinghorror.com/we-hire-the-best-just-like-everyone-else/" rel="nofollow">http://blog.codinghorror.com/we-hire-the-best-just-like-everyone-else/</a> </li>
</ul>



## Answer 9172

- posted by: [Jordan Georgiev](https://stackexchange.com/users/482374/jordan-georgiev) on 2016-05-13
- score: 3

<p>TLDR: Java is scalable, works great with big projects, but has a lot of overhead code to achieve that. Javascript, Python, and other languages do not suffer from that problem while giving you considerable scaling opportunities ( perfectly acceptable for the first version of your product; and ever further )</p>

<p>I've personally worked on a few startups with various languages. Initially a .Net developer ( so yeah inherent smash to "puny java" ). Here are some of the startups/projects I've worked on:</p>

<ul>
<li>Shards/Adventures of Zip ( mobile games ): a .Net project using the Unity3d engine. Using the engine allowed us to make quick successive iterations and combined with the large amount of code available in its' asset store - it was a great language &amp; engine choice for game development.</li>
<li>Gamers Aspire ( competitive website ): since .Net worked so fine the first time - we started with the very same language - what could go wrong? Mostly the insane overhead for simple stuff. Instead of basing our stuff on for example wordpress - we were wasting huge amounts of time in writing blog software, handling email marketing issues and fixing our homepage.</li>
<li>Productivity Map ( Temporary name ): lesson learned - the app was successfully prototyped and pretty well functional in a week using javascript and Cordova. That was accompanied by a fully functional blog with email marketing and ALL the analytics in the world.</li>
<li>Scheduling app: meteor based; also a super-quick prototype. We got the idea and started pitching the pretty functional demo in less than a week.</li>
<li>Random Development Tool ( had too many features ): few months in python, the code wasn't too bad, but not perfect while automating a serious amount of our everyday processes. Started as a startup idea, but eventually winded down, because of the sheer lack of overall direction; still keeping it up to date because it makes our lives easier.</li>
<li>Never Productive ( productivity blog ): a few hours on a wordpress installation. No actual code whatsoever - we're solely focusing on building a community before rolling out a product. This is on a whole other level of lightweight programming #lifehacks :D</li>
</ul>

<p>Overall - by all means it's good to use something you're something super comfortable with, but it's even better to use something that allows for rapid development.
Writing a whole app in javascript cordova ( without ever using it ) took less time than actually finding out how the Xamarin framework ( the biggest .Net thing for mobile apps at the time of writing ) even worked.</p>



## Answer 9187

- posted by: [copper.hat](https://stackexchange.com/users/1367810/copper-hat) on 2016-05-14
- score: 3

<p>Here is one dated Java experience from a different industry.</p>

<p>In 1998 I co-founded a <a href="http://www.cadence.com/cadence/newsroom/press_releases/Pages/pr.aspx?xml=061614_jasper" rel="nofollow">startup</a> in the electronic design automation (EDA) space. I was 'in love' with Java then, it seemed to capture many nice elements of C++ (which I used from painful Cfront days) and I bought into the WORA mantra. Another plus was Swing, so we could slap together a
GUI fairly quickly in a fairly integrated way. Since TCL is a standard scripting language in this industry, Jacl was yet another point in Java's favour. We used JNI &amp; dynamic libraries to encapsulate C/C++ libraries for underlying
algorithms.</p>

<p>The setup was awesome for small experiments and early product development.</p>

<p>It quickly hit performance issues, and "memory leaks" (not exactly leaks in
the C/C++ sense, mostly mismanaged data, or unexpected accumulations in things like hash maps). We also kept hitting dynamic .so issues on various
platforms which chipped away at the WORA idea. (Since we were using JNI
we were crossing the line ourselves, but the issues we hit were not with our
.sos, but with java needing to have certain libraries at runtime.
Even Solaris was not immune. As a
two man company in a fast-paced industry, the IT folks were often understandably unsympathetic
to our requests for .so updates!)</p>

<p>Not having a solid body of relevant knowledge (such as existed with C/C++)
meant a lot of wasted time trying to find solutions. The folks at Sun
were available and looked into many problems, but the response timeframe
was way outside what we needed as a frantic startup.</p>

<p>Swing was awfully slow in that it didn't scale well with larger data,
drag &amp; drop was often painful. In fact, the first major change to
the underlying product was to move the Swing interface to Qt (thanks Brajesh)
and the difference was enormous. Later the other parts of the product
were migrated away from Java.</p>

<p>In many cases, the convenience of Java allowed us to delay many design decisions. This was both good &amp; bad. Doing something in a quick &amp; sloppy
way is fine if a route to clean &amp; fast is fairly straightforward, but
sometimes it reflects a bad architectural decision which is painful to
change later.</p>



## Answer 11558

- posted by: [juan Isaza](https://stackexchange.com/users/2782694/juan-isaza) on 2016-11-18
- score: 2

<p>In my case it has to do with development speed rather than robustness or performance. Ruby on Rails is slow, but developing a webpage is easy and fast. Speed is everything when doing an MVP and getting funding.</p>



## Answer 9142

- posted by: [VipinS](https://stackexchange.com/users/3685876/vipins) on 2016-05-12
- score: 1

<p>Mostly clients don't prefer Java projects to Startup.Because mostly projects are big and costly. and Other thing is  Java Developers are more costly compare to  Php, Dot Net and other opensource.</p>



## Answer 9144

- posted by: [Aldo Enrique Polanco Valadez](https://stackexchange.com/users/8008887/aldo-enrique-polanco-valadez) on 2016-05-12
- score: 1

<p>I think one of the reasons why some people prefer PHP over Java (I'm a Php backend developer working with MVC, but I learned to code OOP using Java at school and oracle Db) is because some people think that Microsoft and Oracle are evil, and you should not use them for developing (a shitty attitude, but I saw that often). But I think an important one is that PHP servers are cheaper.</p>

<p>But I personally like more strong typed language or python.</p>

<p>At least is what I see in Mexico. </p>



## Answer 9150

- posted by: [l0b0](https://stackexchange.com/users/34241/l0b0) on 2016-05-12
- score: 1

<p>A startup needs to get a working product out as soon as possible. Think <em>"or you will all be out of a job,"</em> not "or the release will be delayed." With a brand new team and not enough time several things may be off the priority list:</p>

<ul>
<li>Learning. You take the skills your hires have and run with it. If everybody knows X that's what you'll use.</li>
<li>Testing. After seeing actual TDD in action, I firmly believe it can significantly accelerate a project. But this requires people who know how to do it properly or have the time to learn (see above).</li>
<li>Architecting. Code explosions are quickly followed by balls of mud everywhere.</li>
</ul>

<p>If you need to show <em>something</em> to the people with the money by Tuesday you'd be prudent to just get something done. But once the concept is proven you'll want to pay down that tech debt to move faster in the long run. And that's the time to review choices like programming language.</p>



## Answer 9176

- posted by: [Chris Sunami](https://stackexchange.com/users/3403291/chris-sunami) on 2016-05-13
- score: 1

<p>It's cultural and political.  Big corporations are conservative, and their decision makers are generally not programmers.   They want a proven product, backed by a big company.  It also can help them in their industry to be aligned with either IBM (Java) or Microsoft (.NET).</p>

<p>Startups tend to be anti-corporate.  They don't want all the mandatory overhead of a big corporate programming language.  They tend to be run by programmers --probably self-taught --so they're more likely to favor open source languages like php, or cutting edge technology like node.</p>



## Answer 9207

- posted by: [Dave Kok](https://stackexchange.com/users/343189/dave-kok) on 2016-05-16
- score: 1

<p>It is the methodology versus 'what works' balance. Methodology is something a programmer needs to write good code. Customers only care about 'what works'. Since Java is a well established language with libraries and frameworks to boot it has a lot of methodology. The only problem is, if you as the programmer do not understand the methodology well enough it becomes like bureaucracy and overall quality as perceived by the customer will suffer. With languages like PHP you can scale up your methodology when it becomes necessary allowing the programmers to focus more on 'what works' giving the customer what they need. However this does often require rewriting the code several times over the life time of a startup. But that is survivable, going bankrupt to loss of customers is not. </p>



## Answer 9209

- posted by: [Mowzer](https://stackexchange.com/users/1803081/mowzer) on 2016-05-16
- score: 1

<p>Java web applications are not supported by static file hosted web servers. (Like Firebase, for example. Which I highly recommend.)</p>

<p>As an entrepreneur with several apps built and released, I looked into doing a project in Java. Then I encountered the above problem and moved on.</p>

<p>From an entrepreneur's POV it is important to be able to release an MVP product quickly, efficiently and with minimum friction and cost. Free hosts mostly only host static files. Which means strictly HTML and JavaScript for front-end development.</p>



## Answer 9309

- posted by: [Rogelio](https://stackexchange.com/users/267060/rogelio) on 2016-05-25
- score: 1

<p>I'll try to explain my view after 25 years programming, I've used ruby, python, php, javascript and mostly java. I'm the CTO in a new startup that pretends to create a fast development environment creating a reusable, complete and universal single page web app on the front and a complete,secure and scalable app and web service on the back. I'll explain our decisions and aims:
1) The front must be developed with html, css and javascript, on a single page web app. Then you can deploy on android, ios, etc. using cordova library. To improve responsiveness and interface we choosed React, libraries for maps, tables, calendars, charts, qr, barcode, photo capture, gps, etc. Then code our front app for reusability and multilanguage.
2) Communications with servers are compressed ajax. Servers are secure linux servers with Apache 2 and SSL.
3) A Cassandra distributed database on our cloud servers so we can scale to as many server as required to hosts all our databases and apps, with a flexible data structure to cover every need.
4) Server side java over tomcat server. Why?
-With well secured servers we don't need to install any new java version.
-The only performance advantage of node.js, queuing of http requests is implemented in our apps via a library.
-Java is strongly typed and more maintainable the any other script language.
-Java have all required libraries for actual and future apps to develop on our platform. We already use Lucene for text indexing, RTrees for geospatial data, finantial functions library, etc.
-Java has all data structures you can thing of, and we think twice when using new ones so we prevent inter threads bottlenecks and hangs or memory allocation problems due to structures misuse. You will not find another language with better documentation and support. In my experience, is not true that java use more memory that other languages, is just you must use the correct data structure and in the correct way.
-tomcat is a fast, reliable and well engineered server, with many years of development and improvement.
-Java virtual machine has a lot of tuning options to adapt to the host server and the app use. Also free tools for profiling and detect problems.
So scalability is assured, not so in any script language.
-Java execution speed tests compare Java to C++, various orders of magnitude over same code execution in php, python, ruby or node.
-Expensive experienced java programmers will not be needed once the platform is finished and ready to host any new development, almost without write new lines of code.</p>

<p>Our main aim in our project, no matter the cost, is to create an universal and reusable app concept, so we can create new apps and deploy on our servers in days, both for our internal projects and for our startup clients. Maybe have been a longer journey this way, but now we are sure we have an scalable and solid framework to implement as many web services as required on it.</p>



## Answer 9357

- posted by: [Dims](https://stackexchange.com/users/94736/dims) on 2016-05-30
- score: 1

<p>In my opinion, the only reason is because Web languages are easier to sell. <code>HTML</code> is sucks, <code>XML</code> is sucks, <code>PHP</code> is sucks and many other web things are actually sucks, but they are winning just because they are wide spread and thin client oriented, easy deployable into any browser.</p>



## Answer 12878

- posted by: [LetMeSOThat4U](https://stackexchange.com/users/2302518/letmesothat4u) on 2017-06-20
- score: 1

<p>There's one major simple reason: it's too costly (and therefore also ~= slow) development-wise.</p>

<p>Now, most of the answers here do not cite empirical data and measurements. This answer is different:</p>

<p><a href="https://i.stack.imgur.com/9M9Er.png" rel="nofollow noreferrer"><img src="https://i.stack.imgur.com/9M9Er.png" alt="Comparison of lines of code by minimum"></a></p>

<blockquote>
  <p>Table 5 shows the results of the pairwise comparison, where p is the p-value, d the effect size, and R the ratio, as described in Section II-F. In the table, ε denotes the smallest positive floating-point value representable in R.</p>
  
  <p>Figure 6 shows the corresponding language relationship graph; remember that arrows point to the more concise languages, thickness denotes larger effects, and horizontal distances are roughly proportional to average differences. Languages are clearly divided into two groups: functional and scripting languages tend to provide the most concise
  code, whereas procedural and object-oriented languages are significantly more verbose. The absolute difference between the two groups is major; for instance, Java programs are on average 2.2–2.9 times longer than programs in functional and scripting languages.</p>
</blockquote>

<p>Source: <a href="https://arxiv.org/pdf/1409.0252.pdf" rel="nofollow noreferrer">https://arxiv.org/pdf/1409.0252.pdf</a></p>

<p>There are other reasons as well:</p>

<ul>
<li>Java is inheritance-trigger-happy and that contributes to deep hierarchies of classes that per whole cannot be really changed significantly, they're just too "brittle".</li>
</ul>

<p>A startup might have to, I don't know, <em>pivot</em> sooner or later? Even when the change is not that ground-shattering, significant rework of the product is highly likely to happen.</p>

<p>If you're writing in typical Java style, you can't really do that. An example: one of the top-requested features on Bitbucket was Github Gist-like snippet "repo". After a big furball on the Bitbucket forum about this, the company dev wrote that they will not implement this because "assumptions [preventing this feature from implementatoin] are baked in too hard into the [bitbucket] system now" (quoting from memory).</p>

<p>Having worked with large Java code bases, I'm inclined to believe that: there's just too much code (verbosity) and typically it relies way too much on inheritance hierarchies instead of favouring composition (per famous rule) for this thing to be humanly possible to rework in short time. That's lethal for startup.</p>

<p>My own startup used Scala. Having worked for several years with Java before, I'm positively sure that had we used Java, we would not get anywhere near as far as we did in terms of dollar/hour spent per working feature.</p>

<ul>
<li>Java is XML-trigger-happy and XML is a poor UI human-wise</li>
<li>Configuration of software written in Java is complex and time-consuming</li>
</ul>

<p>An hour here, an hour there and pretty soon you're talking about serious time waste. </p>

<p>A big corpo might tolerate cost overruns and delays in software development project - generally, the bigger the project, the higher risk of delay and cost overrun anyway (google articles by Capers Jones). A startup is in no position to do that.</p>



## Answer 9239

- posted by: [owlbird](https://stackexchange.com/users/8467629/owlbird) on 2016-05-18
- score: 0

<p>People that say PHP is not scalable or is not good for big data/companies seems to forget that PHP is present in:</p>

<ul>
<li>Facebook</li>
<li>Wordpress</li>
<li>Opencart</li>
<li>Yahoo</li>
<li>Flickr</li>
<li>Tumblr</li>
<li>Wikipedia</li>
</ul>

<p>Just to start. And about Java, why on earth would I want a language which forces me to pay so much for a hosting? Besides, browsers are now disabling Java like they did with flash. It's a nice programming language to teach students and that's all. </p>

<p>To finish, Java fans needs to thank Android otherwise the language would be dead by now.</p>



## Answer 13443

- posted by: [h22](https://stackexchange.com/users/167824/h22) on 2017-10-06
- score: 0

<p>Java is not obsolete, but you in order to stay competitive with alternatives, you need to develop with the new technologies: serialize to and from JSON and XML with Jackson and JAXB, build web serverices with Spring, access database with Hibernate, use Gradle for builds, use Mockito for testing, BouncyCastle for cryptography, use Elastic Search and Cassandra where they fit better than traditional databases, use Protocol Buffers for data, also look into Scala, Play framework, Android and projects the like.</p>

<p>Due long history of the language, there are many legacy approaches that are no longer viable, and some that are even no longer secure. I believe there is also  significant code/configuration bloat around J2EE XML stuff, and also, of course, CORBA if anybody remembers. Alternative technologies claiming they are faster and easier usually assume Java developers still mount these dinosaurs into his chariot. I fully understand the startup founder looking into J2EE web server configuration <a href="https://docs.oracle.com/cd/E18930_01/html/821-2417/beaql.html" rel="nofollow noreferrer">like this</a> and thinking how could we use all this when <em>just one line of code is enough to bootstrap a server in go</em> (also good language). No, masters, a Java wolf will build a server <a href="https://spring.io/guides/gs/spring-boot/" rel="nofollow noreferrer">like this</a> for you, and will be seen if would take any longer than for a node.js guru. But, probably, not everyone is aware of of. If the node.js guru comes first, he can say Java developers only develop around Glassfish and be believed.</p>

<p>A good Java developer knowing today's technologies well still can beat many "much easier" approaches by the factor of two at least, this is just by taking development time into consideration (have been in such competitions). Of course, individual differences between the developer matter, but it is still far from saying that Java is the language you cannot win with.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
