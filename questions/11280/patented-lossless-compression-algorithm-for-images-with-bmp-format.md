## Patented lossless compression algorithm for images with .bmp format

- posted by: [Hosseinz501](https://stackexchange.com/users/9322918/hosseinz501) on 2016-10-04
- tagged: `business-plan`
- score: -1

I've developed a lossless compression algorithm for images with .bmp format, this algorithm for ".bmp" images is better than others algorithms like PAQ algorithms, Zopfli algorithm, brotli algorithm, png format, zip format, etc. This algorithm compresses .bmp files "20% to 40%" more than other lossless compression algorithms. The speed of compression with this algorithm is high and it uses little Ram for compression in the first few options (this algorithm has a few options).

Do you think I can sell the algorithm to some software company? What companies could I sell to? In what ways can be associated with these companies? How can I make these companies from the performance of this algorithm? If I can't sell this algorithm, in your opinion, what else can I use this algorithm for?


## Answer 11333

- posted by: [Jeremy Parsons](https://stackexchange.com/users/497810/jeremy-parsons) on 2016-10-13
- score: 1

<p>Making money from a single algorithm is possible, but it's seriously non-trivial. So you need to focus on finding the shortest path to demonstrating value sufficiently well to persuade an investor to join you.</p>

<p>I'd try two routes.</p>

<p><strong>ROUTE 1 - NETWORKING</strong></p>

<p>First, I would ask, <em>where do a few bits cost an insane amount</em>? Then I'd find a place where people are working on startups in that context, and go there with my story.</p>

<p><strong><em>Guess #1 - Satellite imagery.</em></strong> </p>

<p>I'm in the UK, so I would head to the <a href="http://sa.catapult.org.uk" rel="nofollow">Satellite Applications Catapult</a> armed with a prototype. The prototype is just a script that chugs through any number of BMP files, spitting out text something like this:</p>

<pre><code>File 267: Saving 437 kbytes.
Cumulative saving 98.4 Mbytes 
Cumulative improvement: 23.7%
Verified lossless: 100%.
</code></pre>

<p>I'm not going there to find out about patenting. I'm going there to find out who wants to use my software and why. And I'm going there to find out who has a track record of helping people like me make money from inventions in software.</p>

<p><strong><em>Guess #2 - Financial services</em></strong></p>

<p>Similar story, only I'd start at a FinTech event or accelerator. This time, my script would be all about the microseconds saved in compressing, transmitting and decompressing the files.</p>

<p><strong>ROUTE 2 - DIRECT VALIDATION</strong></p>

<p>I'd start with a bad idea (all ideas start out bad) to translate my code into cash in a way that didn't expose the algorithm at all.</p>

<p>A bad idea might be, cloud storage for BMP files on Amazon, charging less than Amazon. It's potentially a viable idea because fewer bits means less money to store files and less money to transfer files in and out of storage.</p>

<p>Then I'd execute the usual experiment / engage / enhance cycle until I had creditworthy customers wanting to pay money.</p>

<p>Then I have two assets: a potential niche business ready to be bootstrapped with cofounders or executed with investors, and the technology that business will have to license, ready to seek further exploitation, or to seek investment to protect.</p>



## Answer 11286

- posted by: [BrettFromLA](https://stackexchange.com/users/2813127/brettfromla) on 2016-10-04
- score: 0

Websites that display pictures will like this algorithm. It will make their web pages load faster. But that would only work on a web browser that understood your algorithm. Therefore, you need to give this for free to web browsers (Chrome, Firefox, Internet Explorer, Safari, etc.). Then, you need to sell this to big websites that show a lot of pictures (Instagram, Pinterest, Facebook, Amazon, etc.).

But this sounds very difficult. I don't know how you could contact web browsers and ask them to include your algorithm.


## Answer 11294

- posted by: [Alari Truuts](https://stackexchange.com/users/5357302/alari-truuts) on 2016-10-06
- score: 0

This is very difficult, as code can not be patented, and patenting the algorithm as a beneficial model is a financial suicide, and still remains unlikely to protect from similar solutions with slight modifications.

If it works, it'll get stolen, unless you get someone with deep pockets to back you.

Your best bet in my mind is to take your algorithm, create an uncompression js and try sell your compression as a service/solution to websites with high traffic. Ofcourse you'll have to provide proof your algorithm actually saves the client money on whatever measurable (electricity, traffic, cpu resources) and has to actually be unnoticeable to endusers, noone wants to slow down the process of loading a site.

Get media publicity and companies might even turn to you to legally acquire your code. And you'll always have a fixed point in time and Internet to always say it was yours and you were first.


## Answer 11297

- posted by: [Paparazzi](https://stackexchange.com/users/300272/paparazzi) on 2016-10-06
- score: 0

<p><a href="https://en.wikipedia.org/wiki/PKZIP" rel="nofollow">PKZIP</a>  used a model forming a company   </p>

<blockquote>
  <p>PKZIP was originally written by Phil Katz and marketed by his company
  PKWARE</p>
</blockquote>

<p>A buddy of mine that is a math professor said he knows a guy that wrote an optimization algorithm used by airlines and he made a lot of money off it.  </p>

<p>It certainly has value but making money off it is another thing.  </p>

<p>Did you also file patent in the US?  Companies monitor patents and if it had value companies would be finding you.</p>

<p>Try and get published by a scientific journal that verifies the speed.</p>

<p>On web sites you would need to show it is faster.  With compress and decompress it might not be faster. Routers also compress and compress files don't further compress well.</p>

<p>The value is people or companies that want to archive a lot of bmp files.  </p>

<p>If you are not going to try and sell it then just release an open source program that has free use of your algorithm.</p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
