## Marketing and implementing waiting room queue tracking system

- posted by: [Thomas Nicholson](https://stackexchange.com/users/6024766/thomas-nicholson) on 2017-10-31
- tagged: `marketing`, `mobile-apps`
- score: -1

I have created a website for tracking waiting room tickets for any specific department that has them implement. I'm sorry, I don't really know what they are called in English. You come to a bank, take a number and wait for that number to appear on a screen signaling you are next in line.

Well, I got the idea that I should find a way for people to track the development of the situation mobily. So I did. I made a web app in which people can enter their ticket number, counter name/ID, and they get a notification when there are ..., 15, 10, 5, 4, 3, 2, ... people in line before them. Initially, I imagined that people would take a ticket, insert it into the app, and update the current positions for each counter themselves, which I have implemented and tested on a test server.

Sadly, that doesn't work because some men just want to watch the whole world burn. So I got the idea that I should offer this app to departments that are using a waiting room system, for a small compensation, and have them update the counters themselves. Problem is, I don't know how these waiting room systems work. They probably have an internal counter and the servicepeople just press a button to increment the last value. Internal, meaning it's not online.

That creates a problem for me, since I can't have that number pop up in my database without some interface. I am thinking of approaching the company that manufactures these devices first, and offer a deal. But then I ask myself if they have programmers that can develop the system on their own and decline my offer. The thought of that is really disconcerning because my dad came up with this idea and I programmed it; it would really suck if someone took it and made it their own.

So how do I approach this problem? Is there a precedent from which I can learn how to monetize my app?

P.S. I should add that these waiting room ticket machines are definitely not some high-tech gadgets. They use 7-segment displays and a scoreboard style for tracking the last 3 updated counters. Maybe I should come up with an upgrade that would make use of LCDs and touchscreens?


## Answer 13565

- posted by: [metara](https://stackexchange.com/users/12153582/metara) on 2017-11-02
- score: 0

Rauno from the mentioned Qminder here. 

We started exactly with the same idea you have ( among countless others)
*"to put the take-a-number ticket in your smartphone so you wouldn't be stuck in the waiting room with little to no info"*  

Long story short is that the places that use a take-a-number system are not yet ready for such innovations or sometimes simply do not care about customer experience (think: DMV's). 
Furthermore: people do not like downloading apps for these "one-off" waits. 

After years of iterations, we have ended up providing the best queue management and service intelligence system: https://www.qminder.com 

 * People type in their name for service. (no one likes to be "just a number") 
 * The iPad gives them a wait-time estimation ( a series of algorithms based historical data of waiting lines) 
 * Our AppleTV based solution gives a nice clear overview of the waiting line on a TV.     
 * All this provides the business Service Intelligence, meaning data and stats to make the service even better. 
 * and we have an open API, so it's possible to integrate the waiting line info into the locations own app or website if they so want to...

Sorry if it sounds a bit "salesy", but that how it is :)

 



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
