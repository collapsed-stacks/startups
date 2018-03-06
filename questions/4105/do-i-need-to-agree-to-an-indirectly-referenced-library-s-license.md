## Do I need to agree to an indirectly referenced library's license?

- posted by: [jt000](https://stackexchange.com/users/4550640/jt000) on 2015-04-24
- tagged: `licensing`, `open-source`
- score: 3

*Not sure if this is the right group, but couldn't find a "legal" group on SE.*

When a package *(project\app\library or whatever you want to call it)* takes a reference to an open-source package through [NPM](https://www.npmjs.com/) they install both the package they took a reference to, plus any packages that package references.

For example:

    myproj@0.0.0 C:\git\myproj
    ├─┬ foo@1.5.2
    │ ├── bar@1.0.0
    │ ├── huh@0.4.4
    │ ├── goto@0.4.4
    │ ├── things@0.2.0
    │ ├── stuff@0.6.6
    │ ├── items@1.3.0
    │ └─┬ doodads@1.3.2
    │   └── doodads-types@1.0.2
    └── something@0.3.0
    // In this example, myproj directly references "foo" and 
    // "something". "foo" directly references 
    // "bar", "huh", etc. myproj does not directly take a 
    // reference on "bar".


Is "myproj" liable for agreeing to all licenses of every package in the tree or just the packages that "myproj" is directly referencing? 

For example, say "bar@1.0.0" has no commercial license, but "foo@1.5.2" does. Does this mean that the owners of "myproj" is liable for mis-use of "bar" or are the owners of "foo" taking the liability of using an unlicensed package? (maybe the owners of "foo" have an undisclosed agreement with the owners of "bar"?)

**Update:** Replacing real package names with fake ones to clarify that I'm not looking for specific licensing requirements of body-parser and bytes


## Answer 4110

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2015-04-25
- score: 5

[Body Parser](https://www.npmjs.com/package/body-parser) and [Bytes](https://www.npmjs.com/package/bytes) are both MIT licensed.

In short and for the sake of the argument though, if you ***replace*** Dependency with something else then (obviously) only Library's license applies to you. If, on the other hand, you stick with actually *using* Dependency then (just as obviously) its license applies to you in full.

It's really that clearcut. You do not get to avoid the GPL or CC-NC by writing a layer of code around a dependency and slapping MIT on the resulting library. The dependency underneath it is still GPL or CC-NC and its license terms apply in full force.

For the sake of correctness to its end-users, the library should highlight the GPL or CC-NC nature of its dependencies if it opts for a different license, and ideally provide an adapter interface so you can replace it with alternative dependencies.


## Answer 4115

- posted by: [blunders](https://stackexchange.com/users/216182/blunders) on 2015-04-25
- score: 2

You are responsible for what your code does, which includes any code you manually added, or it automatically adds after you enabled it to do so.  Meaning you are agreeing to all licenses of every package your software uses directly or indirectly.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
