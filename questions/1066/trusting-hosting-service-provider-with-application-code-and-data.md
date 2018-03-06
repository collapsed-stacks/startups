## Trusting Hosting Service Provider with application code and data

- posted by: [Jasper](https://stackexchange.com/users/947165/jasper) on 2014-10-20
- tagged: `tech-company`, `legal`, `intellectual-property`, `copyright`, `servers`
- score: 3

Consider this scenario: A small company which wants to host a web application.

It has following choices:<br> 

 1. It can host it on Virtual Servers at a Hosting Service Provider<br> 
 2. It can buy/rent some servers at a data center (co-location?)

In Option 1. especially - how can the small startup company trust the Hosting Provider with our code and data?

The idea is to protect both code (intellectual property perhaps) and data. What would start-ups do?<br />
Any ideas?


## Answer 1071

- posted by: [blunders](https://stackexchange.com/users/216182/blunders) on 2014-10-21
- score: 1

Most startups don't worry about this, and if they do, my experience is they don't survive to have the problem of some stealing their code.


## Answer 1130

- posted by: [Jeremy Parsons](https://stackexchange.com/users/497810/jeremy-parsons) on 2014-10-24
- score: 0

Your web app wants to be hosted where and how it will work best for your customers. You've listed two answers, but there's a much wider range of choices.

Any public-facing server presents a bunch of security issues. You should of course check what your proposed host's terms and conditions set out, but while credible hosts will be clear that your code and data are your property, you're likely to find that most of the issue of security is pushed firmly to your side of the table.

For most of us, code theft would be annoying, but probably not a big issue. If there's some fancy algorithm you need to hide, hide it. If you can afford the overhead, put the magic behind an API, and lock down the API and the system that's serving it. Or invest in the modest cost of a code obfuscator, deterring all but the determined reverse engineer. But is that a real issue? I doubt it.

Data, both yours and your customers', is a whole other story. Your MVP was probably pretty casual, and none the worse for it. But as you get traction, you need at the very least to work out what's your horror story, and how to mitigate. Here isn't the place for a treatise on data security, and I'm not the one to write it in any case. But again, if you look at the evidence, you're likely to decide that hackers and your team come out as far bigger risks than your host or your unintended neighbour on the rack!



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
