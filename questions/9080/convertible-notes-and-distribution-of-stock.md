## Convertible notes and distribution of stock

- posted by: [Phibert](https://stackexchange.com/users/3664593/phibert) on 2016-05-01
- tagged: `venture-capital`
- score: 4

This is a financial modelling question based on a fictitious startup.

A founder starts a company with $50K and receives 500,000 common shares, and then receives a convertible note of $500K with a 20% discount with 10% interest and no cap. A year later it raises $6M with a pre-money valuation of $24M and a 10% employee stock option pool being established in the pre money. 

I'm having difficulties figuring out how many shares are present post Series, and how are they distributed between the Series A investor, the convertible note holder, and the ESOP. 

Any help would be much appreciated. 







## Answer 9560

- posted by: [user3667089](https://stackexchange.com/users/4510966/user3667089) on 2016-06-26
- score: 1

No matter how much the founder puts in initially, when he starts his 500,000 shares represents 100%.

After receiving the first convertible note nothing changes to the share numbers yet since it is a "short term debt".

Series A is when things gets interesting. First you have to create a 10% option pool, which is 500,000 *(10/9) - 500,000 = 55,556 shares.

The series A investor is valuing 555,556 shares at $24M, which means the share price is valued at 24M/555,556 = 43.2 dollar per share. Since the series A investor uses 6M to buy the shares, he will receive 6M/43.2 = 138889 shares.

For the convertible note, since a year passed so 10% interest has to kick in, so 500k debt now becomes 500k * 1.1 = 550k. The discount is 20% so the share price for the note holder becomes 43.2 * 0.8 = 34.56 dollar per share. The total shares the note holder will get is 550k / 34.56 =  15914 shares.

To sum up, after series A, the total number of outstanding shares is 710359 shares. The founder owns 70.39%, 7.82% in option pool, series A investor owns 19.55%, note holder owns 2.24%.

One thing you will notice is that the note holder ends up with an extremely small percentage of ownership despite all the early risk he/she has taken, that is because under normal circumstances, no investor will be stupid enough to issue a convertible note without a cap.




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
