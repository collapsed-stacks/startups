## Workflow for queuing client work

- posted by: [Janpan](https://stackexchange.com/users/1647720/janpan) on 2016-08-18
- tagged: `web-development`, `project-management`, `process`
- score: 1

So I started a startup company with a friend of mine and currently we are doing websites and web related services however our goal is bigger projects. 

We are using trello for team projects and work.
We are using slack for communications.
We are using freshdesk for support.

However, we are facing a bit of a problem with queing work from clients.

Basically, we are only 3 people and growing to 4 soon. When we receive a new job, e.g. a new website for a client, we have a workflow and development processes, however we find it difficult to manage in the queue of current webwites we are working on. For example, we are busy with 3 websites, then a new website arrives and needs to be worked on, then a client emails us about content that needs to be added, then more work comes in later during the day and before you know it, you have so many jobs to do and you cant remember which on came in first or which on iw more important etc.


Basically we need a way to queue work from most important to least important or basically following a fifo queue process. And we need to be able to move items in the queue for example if you are waiting for a client and can continue with another job. 

I guess you can use trello for this but it will only make sense to a certain extent.

Please share any ideas you have. Thanks for the help !


## Answer 10957

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2016-08-18
- score: 3

A Trello list _is_ a TODO list organized like a FIFO queue unless you mess around with the card order or have cards all over the place: older items are at the top, new items are at the bottom. You can reorder the cards if needed. Take the top card assigned to you, move it to Doing, and eventually to Done. (And then archive the card at some point to keep things tidy.)

Your problem might stem from using multiple boards. Namely one per client or something to that effect, in order to give them insights on what you're up to. If so, keep those boards high level, and move the day to day operational stuff to a single board that you treat as a big todo list. You can use checklists to keep the client updated. Checklist items, btw, can be Trello URLs leading to other boards - but note that only your team will be able to see the details if you do that.

As a tip, this set of lists works pretty well for an operational board: Triage [for new ideas], Planned, Doing, Done [Kanban board], Planned Next [for the next sprint], Theme/Project A, Theme/Project B, Theme/Project C [categorized backlog with itemized tasks], Done W32, Done W31 [older sprints, which get archived after a month]. Then use labels to help surface interesting tasks in the backlog: Urgent/Blocker, High Priority, High Impact, Low Priority, Low Impact, Maybe Later.

Alternatively try Asana. A task in Asana can belong to multiple projects and have subtasks. In particular to a special list of tasks that you plan to do today. It's a bureaucrat's delight if you like things _really_ organized with everything having a place and everything in it's place. But someonwhat soul draining if you prefer things to be visual and a bit ad'hoc. Matter of taste.


## Answer 10966

- posted by: [DeveloperUK](https://stackexchange.com/users/7015503/developeruk) on 2016-08-19
- score: 1

Another area to consider is that with a team of 4 you can probably have someone taking the role of managing the relationships with your customers.  Doing that right can save you a lot of time, as you need a holistic view to be able to prioritise effectively.  Working on the right things, and not being forced to context switch can have a big impact on productivity.

It depends on the skills you have in your company.  You mention looking for bigger projects, and this is something you'll probably need to build up for that.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
