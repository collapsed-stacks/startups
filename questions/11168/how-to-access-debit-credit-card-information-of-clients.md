## how to access debit/credit card information of clients

- posted by: [adam](https://stackexchange.com/users/251482/adam) on 2016-09-19
- tagged: `business-model`
- score: 1

<p>I have a business proposal that depends on pulling money from client's debit/credit card accounts based on the purchases they make.
I need to access type of purchases and how much they spent; then depending on the money spent on certain items, I would request some money from the bank account/credit card - of course with their earlier permission to access their account to a limit amount-.
I need to figure out how to get this setup through an online webpage. What are the permissions that I need to apply for, am I dealing with master/visa directly in this case, or individual banks? </p>



## Answer 11173

- posted by: [Denis de Bernardy](https://stackexchange.com/users/182468/denis-de-bernardy) on 2016-09-20
- score: 1

<p>The only way to get this information is form the banks involved in those transactions. Intuitively you could try tapping into intermediaries like Visa, MasterCard, etc. or Swift but you'd then miss out on transactions between accounts from the same banks. So, really, banks are your only option.</p>

<p>Off the bat I'd gather your chances of finding a bank that provides you with access to this data is just about zero. Even if a few do accept, finding a bank equipped with an API to provide you such information is probably close to zero as well, so you'd be on the hook to make that happen.</p>

<p>The only way to know for sure arguably is to reach out to banks and see for yourself.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
