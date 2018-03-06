## YouTube preroll ad attribution without utm tags

- posted by: [Bemmu](https://stackexchange.com/users/5090/bemmu) on 2016-10-17
- tagged: `marketing`, `advertising`
- score: 2

If someone looks at my ad on Facebook but doesn't click on it, but then later on navigates to my site in another way, it seems that Facebook can still attribute that sale, because they know who the person viewing the ad is AND know that the conversion is from that same person, as I have a Facebook pixel on my site.

However with YouTube preroll ads, it seems that this is not happening. I am showing my ads to thousands of people and have some customers who claim to have found my site through them. Yet AdWords is showing zero conversions for the campaign.

Is there a way to get attribution to work on YouTube as well? 


## Answer 11365

- posted by: [Bemmu](https://stackexchange.com/users/5090/bemmu) on 2016-10-17
- score: 1

<p>I'm not sure if these steps are required or if they are all that is required, but after doing these I was able to examine view-through conversions in AdWords. I was still not able to figure out how to see them in Google Analytics though.</p>

<p>1) Enable extra data collection in Google Analytics</p>

<p><a href="https://i.stack.imgur.com/LOcNw.png" rel="nofollow noreferrer"><img src="https://i.stack.imgur.com/LOcNw.png" alt="enter image description here"></a></p>

<p>2) In AdWords you usually look at the "conversions" value, but now you want to add a new column to see the "view-through conversions". These are conversions where the customer first saw the ad, then purchased later, without necessarily clicking on the ad at all.</p>

<p><a href="https://i.stack.imgur.com/DE0DM.png" rel="nofollow noreferrer"><img src="https://i.stack.imgur.com/DE0DM.png" alt="enter image description here"></a></p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
