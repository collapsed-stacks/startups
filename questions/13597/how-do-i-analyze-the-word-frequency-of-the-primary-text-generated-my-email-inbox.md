## How do I analyze the word frequency of the primary text generated my email inbox?

- posted by: [Carnell Tate](https://stackexchange.com/users/5843368/carnell-tate) on 2017-11-09
- tagged: `software`, `web-development`, `data`, `email-marketing`, `analytics`
- score: 0

I'm reading the book, "Agile Data Science", and I want to get into data science for my own personal use. However; the book is not for beginners, and I'm having trouble implementing the theory. 

In one of the chapters they explain, "We might analyze the body of the email by counting its word frequency. Once we remove
noncoding common stopwords (like of and it), this looks like Figure 2-10.
[![enter image description here][1]][1]
Figure 2-10. Email body word frequency


  [1]: https://i.stack.imgur.com/2L3ey.png

However, how do I take the primary text from email, and make a code to extract this information? 
What software do I use? I've tried apache, and avro but it's setting in my download folder on my desktop and every time I try to open it, the program opens then disappears! 

Please help! Thank you


## Answer 13598

- posted by: [HCK](https://stackexchange.com/users/9584327/hck) on 2017-11-09
- score: 0

Haven't read that book but in my programming experience you could do something like this:
Tokenize the body of emails using an string-explode function, this to create an array containing words of all the sentences. After this, exclude all the words that has a length of 2 or less. Now then can storage the words on the array to analize.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
