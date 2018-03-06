## User for Great Neural Network Library?

- posted by: [Carlos Reyes](https://stackexchange.com/users/5778949/carlos-reyes) on 2015-08-20
- tagged: `software`, `business-model`, `product`, `partnership`, `financing`
- score: 3

I have invented a really powerful neural network training algorithm. The network can be trained in real time, requiring only about one millisecond per observation. Using the resulting neural network for prediction is extremely fast. This is with stock server hardware. The results are robust even if the data is noisy or it experiences concept drift. There is only one tunable parameter and its exact value is not critical. Even relatively non-technical users can get good results with the algorithm.

The original version of the code is in Haskell. I have been working on JavaScript and C++ versions. I believe it is patentable technology, though that is not a personal goal of mine. It should go without saying that it is the result of many years of experience with neural networks.

I do not have the financial means to launch a company to take advantage of this algorithm. I would love to see it put to good use. Even better, I would love to get paid to work on it. As a last resort, I plan on releasing the code as open source projects (GNU Affero GPL license). But I also need to put food on the table. I would love for somebody to step forward and help me turn it into a commercial product or to turn it into a new feature on an existing software product.

Any takers? Any ideas?

UPDATE 1: I was trying to be factual in the description of the code without getting too technical and without giving away too many details. What I was trying to say may have been open to misinterpretation as a result. I'm a practitioner (coder) with many years of experience. Writing research papers is just not something that I do. (i.e., no interest and no time).

The design goal of the code was to provide good results quickly via a very user friendly API. The robustness and concept drift features were added to make the code easier to use, if that makes sense. Researchers tend to care about 0.0001% better accuracy at the cost of days of runtime on a GPU. I did not set out to compete with them in any way.

I do not work in a lab. I work in the real world. I wrote the code for a specific commercial application. But I can see uses in many other settings. I have not come across any open source libraries that are even close to what I wrote. They tend to be toolkits for machine learning experts.

Several have suggested testing the code against MNIST. Looking into it. I already know the results would be good but not great. I know I cannot compete with an expert using an existing toolkit. But I'll bet my code could easily beat a non-expert using another toolkit. Hope that clears things up.


## Answer 6128

- posted by: [vallismortis](https://stackexchange.com/users/2369743/vallismortis) on 2015-08-23
- score: 2

<p>If you think the method in the software is patentable, then publishing the code as Open Source under any license would likely invalidate any claims you make on it; the code would essentially become Prior Art.</p>

<p>If you plan to commercialize while providing all or part of the code as Open Source, then the Apache License would potentially be more compatible with your commercial goals. The newer GPL licenses have not yet had a good legal test. As a reference for Open Source/commercial compatibility, refer to the <a href="https://www.mongodb.org/about/licensing/" rel="nofollow">MongoDB licensing page</a>.</p>

<p>Finally, if you are in any way affiliated with a university or if there is a technology incubator in your area, you might find some helpful resources for commercializing your method.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
