## Should I try cheaper/ foreign developers first if the app has simple features?

- posted by: [Issa Gem](https://stackexchange.com/users/11751966/issa-gem) on 2017-09-13
- tagged: `mobile-apps`, `outsourcing`
- score: -1

<p>I believe the app will be simple. Is email sync considered advanced? What about the movable sticky notes? Thank you</p>



## Answer 13330

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2017-09-13
- score: 2

<blockquote>
  <p>Is email sync considered advanced?</p>
</blockquote>

<p>Email may look simple, but it's more like mind bogglingly complex once you get into the details. <a href="https://www.ietf.org/rfc/rfc5322.txt" rel="nofollow noreferrer">Here's an RFC</a> to give you a taste of how hairy the topic can be.</p>

<p>IMO avoid hiring a cheap rookie in some offshore location to build an app around email. Even trivial looking things like validating an email will catch a beginner off guards and blow up in their face.</p>

<p>More generally, and in my experience, you're usually better off building a prototype with a local, or at the very least someone who is on more or less the same cultural wavelength as you are. Doing so will spare you all sorts of problems along the lines of "hold on, didn't you say the other day that you understood what the specs were?"</p>

<p>Software developers are like most professions: competent, available, cheap; pick two.</p>



## Answer 13430

- posted by: [h22](https://stackexchange.com/users/167824/h22) on 2017-10-02
- score: 0

<p>I really would not advice to go with any outsourcing if you do not have a proper technical specification (derived from the proper business requirements document). Hiring freelancers of unknown expertise all over the world without knowing what do you actually want is even more risky.</p>

<p>Without specification, it is not uncommon for such a remote teams not to do any development for weeks just because they do not understand the task. When they finally write something, it is almost never that is needed. Remote freelancers are not automatically bad developers but it is your part to prepare the proper design documents for them.</p>

<p>You need at least one really technically competent team member that could do the design and lead the development. He could also do all prototyping where simplified proof of concept code is really fast and easy to write. Find one, and offer CTO for him, rather than thinking that random freelancers and cheap money can do the same for you.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
