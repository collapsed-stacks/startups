## What is a sensible way to measure customer retention rate?

- posted by: [alexw](https://stackexchange.com/users/3556746/alexw) on 2014-10-29
- tagged: `customer-development`, `customer-service`, `metrics`, `retention`
- score: 6

<p>I run a <a href="http://bloomingtontutors.com" rel="nofollow">local tutoring business in Indiana</a>, and we employ/contract about 12 tutors to work one-on-one with college students.</p>

<p>Our focus is on repeat business - i.e., we want customers to be satisfied with their tutor, enough to schedule additional sessions with that same tutor.  My goal is to gauge this satisfaction based on whether or not the student schedules a followup session.  If they do, I'd consider this a success, and that the tutor is working out for the student.</p>

<p>What I'd like to do is measure this on the fly, rather than waiting until the end of the semester when the "votes are in".  What I've been doing so far is:</p>

<p>At a given time <em>t</em>, count the number of students with whom the tutor has completed a session between the beginning of the semester, and <em>t - (2 weeks)</em>.  Let's call that <em>total_students</em>.  I consider 2 weeks to be a "reasonable" amount of time for a followup session to occur.  </p>

<p>Then, count how many of those students have completed <strong>at least one</strong> additional session with the tutor between the beginning of the semester, and now.  Let's call that <em>followup_students</em>.  </p>

<p>I am thus defining the <em>2-week student retention rate</em> for a tutor as <em>followup_students</em> / <em>total_students</em>.  Thus a tutor who never gets a second session with a student will have a retention rate of 0, and a tutor who keeps them coming back will have a retention rate of 1.</p>

<p>However, there are some caveats.  Attrition can happen for a number of reasons, not just poor customer satisfaction:</p>

<ul>
<li>The student could drop the course.  This will hit harder on our tutors who tend to work with students who are struggling more.</li>
<li>The student could be a "exam-only" type of student.  Meaning, that they tend not to want to meet with a tutor until right before an exam, and then suddenly it's cram time.  This would make their tutors look bad between the first and second round of exams.</li>
</ul>

<p>Furthermore:</p>

<ul>
<li>Tutors with fewer students are going to bounce around more, since one followup session will make a huge difference.</li>
<li>2 weeks is an arbitrary period of time that I just decided was "long enough."</li>
<li>Should I factor in the <em>number</em> of followup sessions (instead of a simple binary model)?</li>
</ul>

<p>In general, does this make sense as a way to evaluate customer retention rate, for my tutors or even for the business as a whole?</p>

<p>Disclaimer: I was advised to post my question via <a href="https://meta.stackexchange.com/questions/242406/where-should-i-ask-a-question-about-metrics/">a meta-question</a>.</p>



## Answer 1192

- posted by: [JR Warren](https://stackexchange.com/users/1866317/jr-warren) on 2014-10-29
- score: 4

<p>I'm certainly not an expert in this area, but I'll take a shot at it:</p>

<p>I think you've got a good start on it and with some tweaking you'll be getting some more actionable data.</p>

<blockquote>
  <p>Attrition can happen for a number of reasons, not just poor customer
  satisfaction:</p>
</blockquote>

<p>I've worked with a number of companies and generally from what I've seen they all have an "acceptable rate of attrition". This includes turn over from an "acceptable" number of unhappy customers as well as those odd cases where they know a certain number of people are going to move to a different location outside your service area (for example) and there's nothing you could have done to stop it.</p>

<p>You'll need to determine what is acceptable. I would suggest a good place to start is by taking measurements of each of your tutors and see if there are any noticeable trends in those initial numbers.  (Obviously with the goal always being to become more efficient in pushing even the "acceptable"/expected attrition rate down)</p>

<blockquote>
  <p>The student could drop the course. This will hit harder on our tutors
  who tend to work with students who are struggling more.</p>
</blockquote>

<p>If you have particular tutors that tend to work with these "high-risk clients" (assuming here you <em>know</em> they are struggling when they sign up), you may just need to classify them differently as their numbers are going to come up different than everyone else's.  This may be as simple as finding a different number for their expected rate of attrition.</p>

<p>I used to do DSL tech support in a call center and they measured us all on a dozen different metrics. One of them was whether or not the customer called back after we were done. Once I'd been there a while, they set up a special phone queue so they could send customers that had already called in 3+ times in the past week to a veteran agent.  I was one of the people receiving those calls, and at first they expected us to live up to the same metrics as everyone else. Problem is if someone has already called in 3 times, yeah there's a chance they got newbies the last couple times and I'll be able to fix their problem... but it's more likely they've already got a ticket in with the main office or are waiting on a tech to come out and all I'm going to be able to do is give them an update, try to keep them calm, and if the ticket isn't resolved by the next day they're going to call in again no matter what I said to them. </p>

<p>Giving a different set of metrics/goals to the people handling those situations solves that problem.</p>

<p>There may also be a way to classify the client differently rather than the tutor. Then the high-risk client would simply be weighted differently in your algorithm than a regular client.  If a high-risk client is twice as likely to skip out on the follow-up then it only carries half the weight against the tutor's score OR it counts twice as much for their score when they come in for a follow-up. (Adjust that for whatever % difference there actually is in likelihood of attrition)</p>

<blockquote>
  <p>The student could be a "exam-only" type of student. Meaning, that they tend not to want to meet with a tutor until right before an exam,
  and then suddenly it's cram time. This would make their tutors look
  bad between the first and second round of exams.</p>
</blockquote>

<p>If you know when exam-time is, you can account for this as well. Anyone that has no history of seeking tutoring, and then signs up a week before exams is automatically classified as high risk and weighted differently.</p>

<blockquote>
  <p>Tutors with fewer students are going to bounce around more, since one
  followup session will make a huge difference.</p>
</blockquote>

<p>That is probably to be expected, and I'm not sure off hand how to counter-act it. </p>

<blockquote>
  <p>2 weeks is an arbitrary period of time that I just decided was "long
  enough."</p>
  
  <p>Should I factor in the number of followup sessions (instead of a
  simple binary model)?</p>
</blockquote>

<p>Doubt anyone here is going to be able to give a better estimate of how long is long enough for a follow-up than you.</p>

<p>I would imagine having the number of follow-up sessions as a part of your data could be very valuable. However, I think I would keep them separate.</p>

<p>So you want to know the proportion of people coming back AND you want to know the average number of times they're coming back. Those data points are <em>related</em> but they are very <em>different</em>.</p>

<p>Another thought: You haven't mentioned it but if you have a period of high sign-ups/drop-offs at the beginning of the semester (sign-up at the beginning and then decide they don't need it or don't have time for the extra commitment), that would need to be accounted for too.  I would think it could be accounted for in a similar way.</p>

<p>Hope that all made sense! It's about 2 am here and I need to go to bed...</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
