## Best methods for hosting a customer's data

- posted by: [Alec O'Connor](https://stackexchange.com/users/5170592/alec-o-connor) on 2017-02-06
- tagged: `website`, `web-development`
- score: 2

I am experience with running my own server for my personal developer usages, but that is not up 100% of the time. At this point I am setting up accounts with hosting providers for my clients and giving them the keys. There has to be a better way.

Any suggestions for this? Theoretically I would like to have a virtual apache server that I can access via ssh. I'd also like the ability to host multiple website platforms within. It would be nice if there was a way to separate my customers' databases.


## Answer 12100

- posted by: [Raj Sharma](https://stackexchange.com/users/3713933/raj-sharma) on 2017-02-13
- score: 3

There are two ways to look at it

**1. If you want your system to be highly configurable and scalable**
Use VPN (Digital Ocean or AWS(preferable)). I would prefer AWS because it is highly scalable. But that being said it needs you to know what are the different AWS services and how and when to use them. AWS you will need ec2 for ssh, setting up a server that would solve most of your needs to start with but later you can switch to different services. 
Eg. I was using php to process my images files and upload them in my amazon ec2 in a folder. But when the traffic increased I easily moved to lambda(processing) and s3(storage)

**2. I Just want to start cheap.**
Use something like godaddy. Not developer friendly. Best suited for simple websites. Not web applications. Not much control over server config. Difficult to scale and maintain. 


## Answer 12054

- posted by: [Daniel](https://stackexchange.com/users/7592784/daniel) on 2017-02-06
- score: 2

Get yourself a Virtual Private Server (VPS) with your favorite flavor of Linux. Generally Linux VPS hosting comes with cPanel server management software, allowing you to easily remotely operate the server through a web-based GUI or SSH.  Ultimately, you have complete control over your own server to install whatever modules you want.  Much less restrictive than shared hosting.

cPanel is designed to manage services on a customer-driven model, keeping each customer and their data separate.  You can even grant your customer limited access to their cPanel account so they can manage their own email addresses and such, if you so desire.

Not all VPS hosting providers are created equal.  You should be able to get fast, reliable Linux VPS hosting for $20 a month.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
