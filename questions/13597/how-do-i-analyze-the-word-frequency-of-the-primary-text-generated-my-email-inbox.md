## How do I analyze the word frequency of the primary text generated my email inbox?

- posted by: [Carnell Tate](https://stackexchange.com/users/5843368/carnell-tate) on 2017-11-09
- tagged: `software`, `web-development`, `data`, `email-marketing`, `analytics`
- score: 0

<p>I'm reading the book, "Agile Data Science", and I want to get into data science for my own personal use. However; the book is not for beginners, and I'm having trouble implementing the theory. </p>

<p>In one of the chapters they explain, "We might analyze the body of the email by counting its word frequency. Once we remove
noncoding common stopwords (like of and it), this looks like Figure 2-10.
<a href="https://i.stack.imgur.com/2L3ey.png" rel="nofollow noreferrer"><img src="https://i.stack.imgur.com/2L3ey.png" alt="enter image description here"></a>
Figure 2-10. Email body word frequency</p>

<p>However, how do I take the primary text from email, and make a code to extract this information? 
What software do I use? I've tried apache, and avro but it's setting in my download folder on my desktop and every time I try to open it, the program opens then disappears! </p>

<p>Please help! Thank you</p>



## Answer 13598

- posted by: [HCK](https://stackexchange.com/users/9584327/hck) on 2017-11-09
- score: 0

<p>Haven't read that book but in my programming experience you could do something like this:
Tokenize the body of emails using an string-explode function, this to create an array containing words of all the sentences. After this, exclude all the words that has a length of 2 or less. Now then can storage the words on the array to analize.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
