## How to securely share women's data online?

- posted by: [Fahad Uddin](https://stackexchange.com/users/160083/fahad-uddin) on 2015-10-23
- tagged: `pivoting`
- score: 5

I am working on [a startup in Pakistan][1] that allows you to search for a teacher online. The search results show contact number of the person so they can be contacted for hiring.

One issue that I am facing is if women provide contact numbers in my country, they might be harassed using phone. How can I avoid it? Shall I remove the contact number to be compulsory for women? Thanks.


  [1]: http://www.inspuratesystems.com/tuitionteacher/search.php


## Answer 7630

- posted by: [Gordon Amable](https://stackexchange.com/users/7114347/gordon-amable) on 2015-10-23
- score: 2

Why don't you implement a system where the pupil must send a request to the teacher.

The teacher can access to the full profile of the pupil, if he/she accepts the request, then the contact may be etablished, else if, profile's information stays invisible

An other option is to don't specify genre of the teacher. Just describe her as "Math professor at university, speaks english, [blablabla...]"
And show the genre or photo after the request was accepted.


## Answer 7649

- posted by: [BrettFromLA](https://stackexchange.com/users/2813127/brettfromla) on 2015-10-27
- score: 2

One option is to offer some other, safer form of communication that the teachers can use without giving out their phone number. After the teacher feels safe with a particular person, he/she could give his/her phone number.

Your site could offer that safe communication via instant message, audio chat, or video chat. That could be combined with a rating system; students with low ratings (because they're new) would be limited to the type of communication and the number of different people they could contact each day.


## Answer 7686

- posted by: [jdero](https://stackexchange.com/users/1972448/jdero) on 2015-11-02
- score: 1

I wasn't a fan of either of the two answers here so I'll submit my two cents.

Let it be known -- In America, basically every teacher in the country has work contact info publicly available (unemployed or employed - some have work phones even when they aren't currently in an administrative position). 

When I'm faced with issues like these, I like to think of hacks that mitigate damages and increase the disincentives of any potential threat.

Is there any way you can mix the contact details for male and female teachers? Perhaps this means removing any flags for gender, essentially removing the search capacity to target females.

You don't have to be a genius to know it's easy to aggregate female contact numbers online - it's just your job not to aggregate it for them.

Cultural disclaimer: When I visited India, I was blown away by the sexism in the country, and imagine Pakistan isn't much different (I was lucky enough to visit the Wagah Border!) -- my point is that unless you're making a hiring directory to find female teachers (which is by definition, sexist), you should take into consideration the points I have listed below. Note: this is by and large a cultural problem, not one pertaining to startups, but I'll answer all of the professional concerns I have with actually building the software:

1. Make it very easy to remove your contact info if you are a teacher

2. Make adding a contact phone optional. Email should always suffice for positions like this, and it's far less aggressive / open to spam.

3. When you enter a marketing stage, be sure to target specifically towards school districts and places where the teachers know their data is being presented. 

Bonus points if you decide to:

 - Require verified authentication to view contact information of a teacher
 - Allow teachers to maintain their own profile and privacy settings







---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
