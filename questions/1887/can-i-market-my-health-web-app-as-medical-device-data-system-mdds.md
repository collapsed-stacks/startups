## Can I market my Health web app as Medical Device Data System (MDDS)?

- posted by: [Victor Lyuboslavsky](https://stackexchange.com/users/1227306/victor-lyuboslavsky) on 2015-01-05
- tagged: `tech-company`, `marketing`, `legal`, `software`
- score: 4

I'm building a health app that aggregates user's health data.

In my marketing material, can I legally state that it is an **FDA Class I Medical Device Data System (MDDS)**?

I took a look at some [FDA publications][1] and they state that:

> FDA is exempting MDDSs from the premarket notification requirements.


  [1]: https://www.federalregister.gov/articles/2011/02/15/2011-3321/medical-devices-medical-device-data-systems#h-26


## Answer 3444

- posted by: [Sarah O'Connor](https://stackexchange.com/users/5561619/sarah-o-connor) on 2015-02-18
- score: 2

Yes, technically you could. Class 1 requires general controls, Class 2 requires special controls, and Class 3 requires pre-market approval. The actual definition of a MDDS from fda.gov is: Medical Device Data Systems (MDDS) are hardware or software products that transfer, store, convert formats, and display medical device data. An MDDS does not modify the data or modify the display of the data, and it does not by itself control the functions or parameters of any other medical device. MDDS are not intended to be used for active patient monitoring.

If you don't change the actual data, just aggregate it, it should be fine. If yuor app actually takes data from a medical device, not just a user saying "Oh, I have a BMI of _______ ", than it is a MDDS. 



---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
