## Dividing Code Responsibility

- posted by: [Charles](https://stackexchange.com/users/6444220/charles) on 2015-07-22
- tagged: `software`, `project-management`
- score: 2

<p>I'm the lead of a 4 person development team for a pre-funded startup.  Most of us have paying jobs and work on the project part-time at very different hours and locations.  Our software stack has several layers, requiring familiarity with a few different programming languages/concepts.  My question is what is the best way to assign responsibilities given that some tasks involve touching more than one layer.  The options I see are</p>

<ol>
<li>Assign each task to one individual, expecting him to acquire over time the skills to work in all layers.</li>
<li>Give each developer an area of responsibility, leading to assigning complex projects to multiple people.</li>
</ol>

<p>Option 2 seems more realistic for the stage when we're all working full-time, but what would be the most efficient usage of resources until then?  With the cost being defined as time to task completion, does the additional learning time cost more than the coordination cost?  If so, is it worth it long-term because of the skills each will develop?</p>



## Answer 5809

- posted by: [forsberg](https://stackexchange.com/users/1781896/forsberg) on 2015-07-22
- score: 1

<p>Economically speaking, focus on a single task / responsibility is always a better approach.</p>

<p>From my own dev practice: when a dev is responsible for, say, one layer, then his or her creativity is focused on it to improve it, and some rivarly factor comes in as well, as no one wants to be perceived as less effective or something.</p>



## Answer 5955

- posted by: [Vladimir Moushkov](https://stackexchange.com/users/6664959/vladimir-moushkov) on 2015-08-05
- score: 1

<p>Best would be to attempt doing the both.</p>

<p>Give everyone to be responsible for two projects for on of each developer must be the leader. 
This introduces competition and redundancy in case someone is not available. Still the fact someone still leader behind the project will aim what forsberg is talking about as truly developer works best if he is focused on something.</p>



## Answer 5810

- posted by: [Matiss](https://stackexchange.com/users/1819512/matiss) on 2015-07-22
- score: 0

<p>Option two. Your problem is not exactly related to task allocation, but that your tasks seems to be too broadly defined and too large in general - this is usually the case when this exact problem is observed. Multiple people can surely work on a single task across different scopes provided it is split in to multiple small units that can be implemented independently or almost independently.</p>

<p>For example, a task to develop a API frontend and backend can be divided in many smaller subtasks, like, create DB structure, define API, implement backend, implement transport, implement frontend etc. </p>

<p>Managing this will involve some negotiation and planning, however, having smaller, more manageable task units will allow you to assign specific small units to people who could handle them the best.</p>

<p>About widening the scope of the skills, its nice to have, but - deliver first, play later.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
