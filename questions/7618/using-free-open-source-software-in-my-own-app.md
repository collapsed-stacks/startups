## Using free/open source software in my own app

- posted by: [Growler](https://stackexchange.com/users/238615/growler) on 2015-10-21
- tagged: `legal`, `software`, `open-source`
- score: 3

I am creating a web app which uses [W3C/Google Speech-To-Text and Text-To-Speech][1] ([Google Demo of their technology here][2]). I shared the progress with some developers who mentioned I should be wary of the acceptable use policy.

I plan on monetizing my app at some point, and am worried that using this W3C/Google technology I will be relinquishing some rights to my own software... or will be forced to make it open source or something.

On the W3C specs page, (https://dvcs.w3.org/hg/speech-api/raw-file/tip/speechapi.html), there is a "Status Of This Document" section, which has links to the Final Specification Agreement (www.w3.org/community/about/agreements/final/), but they state "It is not a W3C Standard nor is it on the W3C Standards Track", so am not sure if those rules apply?

The W3C document also provides no references back to Google, so I am unsure if there are some Google agreements I may be implicitly agreeing to.

**So my question is:** What implicit usage rules are typical in free software, especially software that is collaborated on between 2 or more groups/companies. For example, I wasn't able to find a "Google & W3C Terms and Conditions for Speech Technology" doc.

I just find it hard to believe that so much work went in to creating their speech technology (recording narrations, algorithms for understanding/interpreting speech, etc), that I wouldn't be giving up some rights by using their software. 

I'd just like to fully understand what I am agreeing to by using this.


  [1]: https://dvcs.w3.org/hg/speech-api/raw-file/tip/speechapi.html
  [2]: https://www.google.com/intl/en/chrome/demos/speech.html


## Answer 7640

- posted by: [aroth](https://stackexchange.com/users/301489/aroth) on 2015-10-26
- score: 2

<p>What you've linked to there is a specification document for a feature that may be supported by HTML5 user-agents (and which is <em>currently</em> <a href="http://caniuse.com/#feat=speech-recognition" rel="nofollow">only supported by Chrome and Opera</a>; as of October 2015).  It is not, in itself, free software or an implementation of any software, API, or SDK (free or otherwise).</p>

<p>So it's not clear what "free software" you're referring to.  If your webapp is simply calling into the browser's speech API's, you really don't need to worry about anything.  There are no more caveats associated with referencing the <code>SpeechSynthesisUtterance</code> class than there are with using the <code>canvas</code> API or <code>&lt;video&gt;</code> and <code>&lt;audio&gt;</code> tags, or any other part of the HTML5/ECMAScript spec.    </p>

<p>If, on the other hand, you're pulling in third-party libraries/code to interface with the browser's speech API (or to implement your own speech solution based upon the W3C spec), then you'll have to check the license terms that apply to each third-party library/bit of code that you're using.  </p>

<p>So to answer your specific question:</p>

<p><strong>What implicit usage rules are typical in free software?</strong></p>

<p>There aren't any.  Software developers set <em>explicit</em> usage rules in their licensing/distribution terms.  You need to check the license terms that pertain to the <em>specific</em> bit of free software that you're using, and ensure that they're suitable for your use-case (a lawyer can help with this).  </p>

<p>There are a <a href="https://en.wikipedia.org/wiki/Comparison_of_free_and_open-source_software_licenses" rel="nofollow">wide variety</a> of different free/open-source software licenses out there, and you can't assume anything about whether you can/cannot use a particular piece of "free" software without first checking its license terms.  </p>

<p>As a <em>general</em> rule, any software that is <strong>permissively</strong> licensed is safe to use, including for commercial purposes.  Keep in mind, however, that some permissive licenses still require that you give attribution to the original developer.  </p>

<p>Bottom line; it's always best to check the actual license terms and make sure they work for you.  There are a wide range of "free" software licenses in use today, some of which are fine for commercial purposes, others which definitely are not.</p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
