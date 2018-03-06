## How to record daily work hours of staff?

- posted by: [Omid1989](https://stackexchange.com/users/2817522/omid1989) on 2016-05-29
- tagged: `payment`, `employees`, `salary`, `hours`
- score: 7

We are nearly 7 people in a startup (mainly engineers and designers; electrical, mechanical, IT, graphical, etc. working on design and production of high-tech devices.), and we want to record the daily work hours of each person. But the problem is that the staffs' conditions are really different:

- Some people are working at home. They come to the office once or twice a week, give reports, get to-do lists, and continue to work at home.
- Some people are working part-time, some work full-time, and some work extra-full-time !!
- Some people come to the office when we ask them. They do their regular work at home or elsewhere, and when we need them to come to the office and do some special works, we call them and they come. Usually 2-3 times a week.
- Some people work at the office, and some work out of the office. Some work both in and out of office.

We've tried the following methods:

1. Staff manually submit the hours when they come to the office or when they exit the office (Enter/Exit Hours). This method had several problems:
- Some staff work at home, or out of office. So they don't come to the office to submit the enter/exit hours.
- When at the office, some staff do their personal works, play games, waste time, etc.! So it cannot be considered worked hours!!
- After some time, some staff ignore to submit the daily work hours, because they think it's difficult and time-consuming!
2. Staff manually submit the daily hours they work for the company. Instead of submitting the enter/exit hours, they submit the real worked hours. This method solves the problem of work-at-home or work-outdoor staff. But still has these problems:
- It is difficult to judge the submitted and claimed hours, i.e. some staff work at home from 9 AM to 5 PM, where only 2 hours would belong to the company and the rest were about personal works or surfing the net or playing games! But the employee submits 8 hours for that day instead of 2 hours!!
- Some staff ignore to submit the daily hours on that day, and prefer to submit it weekly, where it is just a guess, an estimate, and might be more or less than real worked hours.
- Some staff again think it's difficult and time-consuming to submit the daily hours!

As you see, we've had difficulties recording the activities of staff. The final goal is to be able to calculate the salaries fairly; but to do so, we have to find a proper method to record or monitor the activities of staff.

***So, How should we record the activities of staff!?***

----

***Edit 1***

It is not essential to record the *hours*. The main goal is to track the output. But to do so, we probably need a quantitative parameter. What is it? ***And how should we track the output and results?***


## Answer 9347

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2016-05-29
- score: 9

In my opinion you're trying to solve the wrong problem. You want to track output, not how many hours of "suffering" went into producing that output. Ultimately you'll want to get:

1. Consistent (and ideally: regularly increasing) output from existing staff
2. Proper metrics in place to identify under-performers and potential over-performers
3. Methods and processes in place to train and retain all promising hires

With respect to these three points, tracking time:

1. Is a source of distraction that wastes time for both the employee (who needs to worry about tracking it) and their boss (who needs to review it); it also promotes micro-management by their boss; either way it harms performance more often than not
2. Is in no way correlated with under- or over-performing - some employees will just do things more or less quickly (and properly), the only thing that really matters is it taking you less time to manage than to do it yourself (properly)
3. Is a huge turn-off for any self-respecting engineer who you'd want to keep - the employees you want to keep will rarely put up long with such BS

If you were running a burger flipping business or something that relies on repetitive manual labor, then time track all you can and want of course. Just don't go down that route with creative work that is more typical for statups.

Further, on the topic of games, keep in mind that getting an occasional distraction is pretty important when doing creative work - you can't focus for 8h straight (let alone 10 or 12); and on the topic of personal stuff, _having_ a distraction can be a brain drain - it's often better to just get it out of the way so as to clear up your mind and get work done. Just my $.02...


## Answer 9385

- posted by: [Jordan Georgiev](https://stackexchange.com/users/482374/jordan-georgiev) on 2016-06-01
- score: 3

<p>I'd suggest adding an overall process so you can have clear visibility of output. <em>Time-tracking programmers, artists, any creative job doesn't really work.</em></p>

<p>For a good system, I'd suggest for you to go with <strong>Scrum</strong>, but you could as well use <strong>kanban</strong> or any other <strong>Agile</strong> methodology for that matter.</p>

<p>The basic structure you would need:</p>

<ul>
<li>Planning stage ( every 1 to 4 weeks; usually shorter timeframes produce better visibility )</li>
</ul>

<blockquote>
  <p>Planning should include an overview of your company goals and a definitive set of tasks that employees should do in a preset time span. Tasks could be given out at the start or left for grabs by anyone. Tasks could have a difficulty/score value associated with them to help evaluate speed ( See: <a href="https://en.wikipedia.org/wiki/Planning_poker" rel="nofollow">Planning Poker</a> )</p>
</blockquote>

<ul>
<li>Sprint</li>
</ul>

<blockquote>
  <p>Sprints are simply fixed periods of time for work. Every worker aims to complete as many scheduled tasks as possible. Scheduled tasks should be as fixed as possible to allow people to work without distractions and constantly changing goals and objectives. They are short term to avoid working a long time on a stale goal, yet fixed to allow clear focus.</p>
</blockquote>

<ul>
<li>Retrospective</li>
</ul>

<blockquote>
  <p>Retrospectives are meetings at the end of a Sprint. Their sole goal is for everyone to work on improving the process and the work/feedback loop. Basically, get everyone involved on how to make the process better.</p>
</blockquote>

<ul>
<li>Finally, you can count points at the end of every full period and work on gradually improving the score every single Sprint.</li>
</ul>

<p>Obviously, this is just a basic generalized structure. I outlined the most important things you'll need to get a clearer feedback on what's going on, but you will need to work on the process with your employees to make the best of it.</p>

<p>For further reading, I'll recommend the original <a href="http://rads.stackoverflow.com/amzn/click/038534645X" rel="nofollow">Scrum Book</a>.</p>



## Answer 9356

- posted by: [Z Z](https://stackexchange.com/users/7691178/z-z) on 2016-05-30
- score: 2

To start with, I believe you need a combination of things:

 1. **Rough/credible estimates** (in working days or hours) of
    projects/tasks people will be working on. This can be done by those
    who have expertise/experience in the area. This will help in gauging how well the task is going or if the person is struggling. Without this, it is difficult to know how well the project/task is progressing.
 2. **Timetracking** - preferable should be an online time-tracking system that you can set up all the projects and tasks. You should also setup tasks like holidays, idle time, support/maintenance, etc.. It can never be exact, but the aim is to capture time from all categories including real project tasks and time fillers etc. In general, staff do not like entering time. But if they understand it is used to measure actual work against estimates provided, and also tied to performance, then they may be encouraged to enter daily or at the end of the week. Time entered should be actual time spent on tasks, not based on "time in/time out"
 3. **Salaries** - for permanent staff, this should be tied to the market value of the role. Of course you can pay above or below market value depending on other incentives like end-of-year bonus, healthcare, holidays, etc. For non-permanent (contract) staff, salaries will unfortunately have to be tied to daily or hourly rates. But you will need some scrutiny in checking that hours are just being entered without much output. Hence there may be a need for weekly brief status on tasks and if on target in relation to estimates. For contract staff, you could attempt to negotiate payment for fixed pieces of work.
 4. **Performance/Evaluation Culture** - there will need to be ways of rewarding performance as some people will be good at delivering tasks in much less time than the "average" performer. So timetracking should not be the sole means. This is probably a separate question...




## Answer 9393

- posted by: [Neil](https://stackexchange.com/users/2711480/neil) on 2016-06-02
- score: 1

Some very good answers here already. Slightly different angle - I would recommend how you communicate this to your employees is important. 

If you mishandle it, then it can easily erode trust. I have been in a number of environments when timetracking has been implemented and led to this happening.

Also by adding a tracking system you will also be adding a non-value added activity to your employees.

I would therefore proposal a brief daily catch conference call at the start of the day (c.1-3 minutes) and get everyone to identify their daily workload. 

Then at the end of the day wrap it up with another one. This will improve your understanding of what everyone is doing in your networked organisation, help you measure/improve output (and remunerate accordingly), and foster links between employees who may not regularly see each other.




## Answer 9511

- posted by: [Nikunj Aggarwal](https://stackexchange.com/users/3836409/nikunj-aggarwal) on 2016-06-20
- score: 1

We also had the similar situation and to solve it we used a tool called Hubstaff. This is a very excellent tool. You just need to ask you staff to install it on their  machines and start the recording when they are doing something actually productive for your organisation. This tool captures the snapshots at an interval of 10 minutes randomly. and it also records the activity percentage. So if a person is just keeping the system open and not doing anything productive the activity percentage will be less and in that way can actually know that how much a person was active while his/her system was on.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
