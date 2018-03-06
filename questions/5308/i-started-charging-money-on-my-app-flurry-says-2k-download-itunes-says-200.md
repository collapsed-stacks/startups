## I started charging money on my app. Flurry says 2k download, iTunes says 200

- posted by: [vondip](https://stackexchange.com/users/43161/vondip) on 2015-05-18
- tagged: `mobile-apps`
- score: 3

I've developed an iOS application. My application has been receiving a steady download rate of 5K per day. Lately, I've become short on money and decided to start charging money for downloading the app.

From that point onwards AppStore reported a decline to around 200 installs per day, whereas Flurry, Facebook and crashalytics have all been reporting ~2 k new app installs.

How could that be? What am I missing?



## Answer 6053

- posted by: [zazaalaza](https://stackexchange.com/users/4672194/zazaalaza) on 2015-08-15
- score: 1

Flurry and other analytics platforms don't have full access to the App Store's API (meaning that the App Store does not provide referral tracking for downloads) so they have to determine downloads another way, i.e. when the user clicks on the link on your website that redirects to the download page.

This might be the source of all those extra numbers. Maybe they go there and they put the app on their wishlist instead of buying it and this is what registers as a false download in Flurry.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
