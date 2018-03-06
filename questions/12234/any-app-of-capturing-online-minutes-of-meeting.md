## Any app of capturing online minutes of meeting

- posted by: [Omaruko2016](https://stackexchange.com/users/10365581/omaruko2016) on 2017-03-02
- tagged: `web-apps`
- score: 1

In case we hold online meetings, I assume we utilize several apps such as  Voice & video chat・・・Skype 
Documentation・・・Google documentation 
Capturing on line minutes of meeting・・・I am now looking for any app.

Are there any rules to make a minute of a conference when attendants make it by themselves.
Without rules,it is difficult to make a minute every attendants accepts.
That's because one may say he didn't say that,and one may say what he said is not in the minute.

Please advise me any suggestion about the said matter from you.
Thank you in advance.


## Answer 12235

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2017-03-02
- score: 3

Coming from marketing and sales (management), I've a similar type of problem. Namely, recording market research-related interviews and client calls, both for QA and feedback purposes, and then ideally transcribing them when necessary.

Bluntly, there's no magic bullet at the moment insofar as I'm aware. Your current best option is to record the (audio or video) conversation in full, and then use speech recognition APIs (e.g. Google, Microsoft) to get a transcript.

It's somewhat trickier in practice than it seems at first glance because, as a meeting participant, you typically want to capture both the microphone and the headset output, rather than merely the microphone like most recording software do. Options include 3rd party services that do it for you (e.g. Uberconf, GotoMeeting) or webinar/podcast recording tools (e.g. Screenflow).

Most of the time the audio is enough. Sometimes, you'll want a full transcript because text is faster to read. To get that, grab the audio track and throw it at a speech recognition API to get a transcript. Note that you unfortunately won't get participant recognition (or at least that part wasn't available last I tried doing this).

That being said, here's a tip to prevent the problem from occurring to begin with: **At the end of any meeting, recap key points that were agreed upon and key next steps** - as well as owners and timelines for the latter. This holds true for work meetings, sales calls, you name it. This builds group buy-in, ensures everyone knows what they're expected to do and by when, and it'll spare you many confusions and misunderstandings down the road.


## Answer 12241

- posted by: [Omaruko2016](https://stackexchange.com/users/10365581/omaruko2016) on 2017-03-03
- score: 0

Thank you for your useful and detailed post. Refering to your post,I came up with the following idea.

That is
Minutes of meeting shall be made the template.
We must consider the contents of the template and prepare.
After one agenda is completed, we fill the template of minutes of meeting.
If minutes is completed, we can move the following agenda

Considering the contents of 5W1H, we must consider the template.
As the case may be, already has at somewhere.
If anyone of you know where I can have, let me know.

Here are free online minutes of meeting from Quora.
https://www.quora.com/What-is-a-good-online-service-to-capture-meeting-minutes
Rainbow Agenda
ATTENTIV
Vie meeting 

I think it is not necessary as long as I can do the said matter.
Because our member is not so many for now.
Skype and Google documentation are enough for us.

For your reference, I happen to find the interesting app
This one is app which can make minutes of meeting automatically.
clake.ai
https://clarke.ai/

I would like to have your comments and advice.
 



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
