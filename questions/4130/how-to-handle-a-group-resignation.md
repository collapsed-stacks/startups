## How to handle a group resignation

- posted by: [TheAsker](https://stackexchange.com/users/6211538/theasker) on 2015-04-27
- tagged: `team`
- score: 6

My company's main product is a mobile app (on Google Play and Apple's app store).

All of our Technology team (manager, 2 iOS devs, 2 Android devs) group-resigned yesterday.

Regardless of the resignation reason (it seems the resignation is final), We want to get the info we need from the resigning team, and build a new one. Questions are:

1. What info should we get from the resigning team (source codes, usernames and passwords for app stores, etc...)

2. How to handle the situation if the resigning team refused to cooperate in the knowledge transfer process?

3. What is the best mechanism for rapidly building a new team that can pick it up from where the first one stopped?


## Answer 4132

- posted by: [Ali](https://stackexchange.com/users/2815644/ali) on 2015-04-27
- score: 5

1. Documented source code that you can verify by compiling
2. General documentation
3. Current bugs and ongoing issues
4. Passwords and usernames to accounts within the company and offline
5. Locations to source code, documentation
6. Any emails to third parties, key correspondences
7. Passwords to email accounts and names
8. Product manager logs,specifications, project files and documentation
9. Normal exit interview
10. Phone number and contact for contacting
11. Licenses to any tools, code signing keys,  that the company has bought
12. Verify CDs, USB keys and all file locations
13. Keys to office, storage cabinets
14. Mini inventory of equipment, audit petty cash and check for any accounting irregularities

Try to convince 1 person to stay behind until you get someone else. If that is not possible, try to convince at least 1 person from the main dev team to be contactable if the new team requires any clarification when restarting the project. 

If you suspect malicious behavior, change admin passwords, change external account passwords while making sure that it would not have any impact on operations. 

Then start recruiting for your new team. Learn the reason for the departure/gripes from the exit interviews and make improvements/precautions for the next team.


## Answer 4131

- posted by: [marius bardan](https://stackexchange.com/users/1109512/marius-bardan) on 2015-04-27
- score: 3

Regarding your 1st question, as you've already hinted, you should ask for:

- the location of the source code - if there are 2 projects, there should be at least 2 different locations (pointing to different repositories). These can be hosted online, like Github, Bitbucket, etc.
- the admin account for those repositories.
- credentials for AppStore & PlayStore accounts.
- credentials for Apple Developer account that manages the certificates used for signing/publishing the application.
- if there is already a release keystore file for Android application (that is, if the app was already submitted), then you also need it.
- depending on how your apps were distributed internally, you might ask for credentials for that as well (if, for example, using HockeyApp, Crashlytics, etc)
- any other licenses you may have bought for various project libraries.



## Answer 5216

- posted by: [bhupendra](https://stackexchange.com/users/5500798/bhupendra) on 2015-05-07
- score: 1

Regarding your problem some questions came to my mind:

 - why all team members resigned immediately.Also it appears you are not to much technical person. Are they going to develop same product for them self or your competitor.
 - You must keep keys of mobile App. Otherwise you may loose your app itself on apple store or play store.


 



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
