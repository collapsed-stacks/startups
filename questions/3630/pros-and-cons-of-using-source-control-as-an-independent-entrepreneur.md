## Pros and Cons of using source control as an independent entrepreneur

- posted by: [JPM](https://stackexchange.com/users/5523828/jpm) on 2015-03-06
- tagged: `entrepreneurship`, `time-management`, `programmers`
- score: 7

**Take the following scenario;**

*You are a solo entrepreneur with two years of programming experience in C# but with no knowledge of using Source Control.
You have an idea to develop a product for small businesses and currently only have a small budget.*

> **Would it beneficial to use source control software such as Git in this
> situation or are the advantages of using a service like this only fully
> optimized when dealing with a team of developers?**

Source control, like all new things, takes time and a potentially steep learning curves to master. There are a number of open source software's that can be used which can minimize cost but as the old saying goes, "Time is money". 

Although new to the entrepreneurial scene, one areas that I have seen that is given a lot of emphasis is the time at which you take your product to market.

> **Could taking on the task of adding source control potentially mean you
> spend less time on developing and fine tuning your product and
> therefore miss your best opportunity to go to market?**
> 
> 
> **What are the Pros and Cons of using source control in this situation?**

Any personal experience or suggestions would be much appreciated. 




## Answer 3631

- posted by: [afaf12](https://stackexchange.com/users/399142/afaf12) on 2015-03-06
- score: 8

Advantages of using version control are fully utilized when many people work on the same project, that is right. However, From my experience, it is definitely worth it even when working alone. The time spent on learning the basics of Git is regained fast, and you end up with saved time, and some additional benefits.

**Pros:**

 - Easy to set up, I estimate 1-3 hours for you to learn the basics and start using version control in your own project.
 - Source control disciplines you.
 - Finding out why some functionality "broke" is much easier, you can track it down to a
   specific revision of your software.
 - Backups. I do, however, also suggest using GitHub (or even DropBox or Google Drive) to have remote backups, in case your local PC breaks.

Following Pros apply when GitHub is used:

 - supports issue tracking.
 - an easy way to have a remote backup server
 - Cheap, plan costing 7$/month gives you 5 private repositories
 - You can work from different computers. Work on computer A, commit your changes, then work from a different location on computer B.

**Cons:**

 - Takes some time to learn.


## Answer 3649

- posted by: [adrianh](https://stackexchange.com/users/7553/adrianh) on 2015-03-07
- score: 7

I'm going to try and pull out some business reasons for adopting source control, rather than focus on the technical goodness:

* **It reduces time to market.** As others have pointed out it makes moving back out of mistakes much easier. As others have pointed out it makes finding bugs simpler. For much the same reasons it makes making trying experiments with the code much easier too. You can try something and trivially change your mind with zero risk of you missing something and fouling up your codebase. All this together means you can move faster and deliver earlier.

* **Basic business safety.** Having everything in hosted source control helps solve your backup / business safety issues. The lack can actually affect business insurance payout stuff (via the same sort of basic precaution clauses that mean you don't get payouts for theft if you forget to switch the alarm on and leave the doors unlocked). 

* **Helps with legal claims.** Having everything in source control, tracked, backed up, etc. is a safety net in the unlikely event of claims of IP theft, etc. It's an auditable record of what you did and when.

* **It makes it easier to scale your team.** At some point you're going to need to pull in other developers. At that point source control is vital for folk to work together effectively. So you're going to want to be proficient before you hit that point.

* **It will help developer recruitment.** Not having source control is going to make you appear unprofessional when recruiting. For many people (myself included) source control is at the "washing hands before food prep" level of basic practices. Back in the day when I did contract dev work one of the first questions would have been about looking at your repository. The absence of one generally have me disengaging from the client because if they're not doing the basics right…



## Answer 3635

- posted by: [BarzinM](https://stackexchange.com/users/5742222/barzinm) on 2015-03-06
- score: 5

<p>Probably, sooner or later you are going to use it. Also, learning it does not take too long, just like <a href="https://startups.stackexchange.com/users/3829/afaf12">afaf12</a> said you can learn the basics in 1-3 hours and start using it. You can find many tutorials that teach you the basics of source control. Here are some resources that I usually suggest to my friends when they want to start working with git:</p>

<ul>
<li><a href="http://rogerdudler.github.io/git-guide/" rel="nofollow noreferrer">http://rogerdudler.github.io/git-guide/</a>   (A compact tutorial which also use some illustrations)</li>
<li><a href="https://try.github.io/levels/1/challenges/1" rel="nofollow noreferrer">https://try.github.io/levels/1/challenges/1</a> (A git simulator so that you can play with commands before installing git)</li>
</ul>

<p>If you are worried about your GitHub repositories being public and you don't want to pay, you can start with bitbucket.org or sync your repositories using DropBox or Google Drive.</p>

<p>Even for individual projects, you can gain a lot from using version control. It does not take time away from development effort at all. You can simply commit your changes in less than a minute. On the other hand, when you need to do debugging, it can save you a lot of time.</p>

<p>In conclusion, I highly suggest using any version control system (Git or SVN), even for small projects.</p>



## Answer 3632

- posted by: [Nero](https://stackexchange.com/users/1705837/nero) on 2015-03-06
- score: 3

In my opinion, you should always use a version control system when developing serious projects. Of course, the total power of version control systems is only used when working with two or more people, but it is still worth using one as a sole developer.

Yes, of course it adds a little bit of overhead to commit the changes to the system, but even for beginners it is not hard to learn how to do that and does not cost much time. And it becomes super easy when using some tool with a GUI to commit the changes.

And this little time is spent well when considering the following: You started implementing the new super-awesome feature X, but after say two and a half days you notice that you made a fundamental mistake or that the feature can not be built entirely or something broke, or whatever. Now you want to go back in time. Ctrl/Cmd-z is nice for a few lines but now, without a version control system you have to manually revert everything. Doing this once costs much more time than using version control and is more prone to mistakes.

I once developed an important small to medium size project without a version control system because none was available without asking the administrator to install one and filling out paper stuff and so on. I ended up with a ton of backup-save-files of the whole project and it really was a mess, especially after trying to go back in time. I wish I had asked for a Git.

So: Use some version control system and (especially as beginner) get some help from a program providing a nice GUI to the system. Personally, I use SourceTree and Git on my Mac for a long time now and I'm very happy with this combination.


## Answer 3645

- posted by: [mikeatlarge](https://stackexchange.com/users/5898883/mikeatlarge) on 2015-03-07
- score: 1

It's also useful for archival purposes. When a project is current and fresh in your mind you might inherently know what you did when and why you did it. But if you have to go back and revisit an old project years later--either for support or other reasons--a version control system can make it a lot easier to get back up to speed.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
