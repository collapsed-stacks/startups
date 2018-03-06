## Versioning convention

- posted by: [Mowzer](https://stackexchange.com/users/1803081/mowzer) on 2015-07-27
- tagged: `software`
- score: -2

By convention, would a software version 0.9.101 come before or after version 0.9.90? And why?



## Answer 5848

- posted by: [Nero](https://stackexchange.com/users/1705837/nero) on 2015-07-27
- score: 5

Short answer:

Version 0.9.101 is usually released after 0.9.90. But it depends on you what kind of version numbering scheme you use.

<hr />

Long answer:

From my experience, a common version numbering scheme is something along the lines of 
> major.minor[.bugfix]

where each of these numbers can be increased as far as needed. Also, when sorting the version numbers each part is interpreted as a number, so, as 101 is bigger than 90, version 0.9.101 is considered newer than version 0.9.90. 

If you, for example, add a minor new feature to version 0.9.101, you can release it as version 0.10[.0], and because 10 is bigger than 9, version 0.10 will be perceived as newer than version 0.9.101.

As a real world example, have a look at the past releases of Mac OS X. In 2013, Apple released OS X Mavericks (version number 10.9) and in 2014 OS X Yosemite (version number 10.10). Other releases now were numbered e.g. as 10.10.4. Although for these numbers, the major part is actually the second part. The first *10* comes from the *X* in *Mac OS X* (a roman 10). So currently Apple uses something like *10.major[.minor]* for the OS X releases.



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
