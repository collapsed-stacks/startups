## What happens to my software libraries which I used in one of my projects that I need to sign a Non Disclosure Agreement for

- posted by: [Sajib Acharya](https://stackexchange.com/users/4474969/sajib-acharya) on 2016-05-10
- tagged: `legal`, `non-disclosure-agreement`, `licensing`
- score: 1

<p>I am a software developer and I have a few libraries and APIs that I use in almost all my projects. They do not have any licensing.</p>

<p>Recently I have become a part of a Startup where I am developing a software for them. Now they want me to sign a NDA for the codebase with a clause that I may not reproduce it anywhere else, among many others.</p>

<p>While I am a part of the startup but I am not comfortable to hand over my APIs to it. </p>

<ul>
<li>What happens to my libraries once I use them in that codebase ? </li>
<li>How
do I protect them from literally handing them over ?</li>
</ul>



## Answer 9125

- posted by: [Ess Kay](https://stackexchange.com/users/2619138/ess-kay) on 2016-05-10
- score: 2

<p>Firstly, this is a very broad question.</p>

<p>Secondly this is off topic as it is not a startup question.</p>

<p>To make it less broad you should include the following details:
How many libraries and what language are you talking about? </p>

<p>Perhaps you would like to take the time to create a second set of files with some obfuscation. Have a look at the articles below for some ideas.</p>

<p><a href="http://www.excelsior-usa.com/articles/java-obfuscators.html" rel="nofollow">http://www.excelsior-usa.com/articles/java-obfuscators.html</a></p>

<p><a href="http://www.ssware.com/articles/protect-and-obfuscate-your-dotnet-code-against-reverse-engineering-using-crypto-obfuscator.htm" rel="nofollow">http://www.ssware.com/articles/protect-and-obfuscate-your-dotnet-code-against-reverse-engineering-using-crypto-obfuscator.htm</a></p>

<p>The meat of the question is how to legally protect your code, but first lets tangent off to another option. If your libraries are hard to understand, then perhaps they will not use them in the first place.</p>

<p>Some examples of obfuscation to protect your code can be easy to implement, and what I would do is as follows:</p>

<ul>
<li>Change all methods and functions in the libraries to obscure names so that they will not be descriptive of their real methods.</li>
<li>Encode the parameters and returns from the above functions so that the other developers will need a type of key to activate the methods and procedures</li>
<li>Encrypt your code</li>
<li>Covert libraries to a language not used/understood in the company </li>
</ul>

<p>Now for the legal aspect:</p>

<p>There are also several other questions regarding this, and since this is not a startup question it would be located in stack exchange.</p>

<p><a href="https://stackoverflow.com/questions/3051651/open-source-licence-header-on-each-source-file-or-a-single-copying-or-both">https://stackoverflow.com/questions/3051651/open-source-licence-header-on-each-source-file-or-a-single-copying-or-both</a></p>

<p>below is a How-To on GNU Copyright, If that is the path you would like to take
<a href="https://www.gnu.org/licenses/gpl-howto.html" rel="nofollow">https://www.gnu.org/licenses/gpl-howto.html</a></p>

<p>Finally, The last approach would be to directly talk with your employer and define the ownership of your code, and have it written down on paper because a signature holds up in court better than a 'he said she said'</p>

<p>Here is an exert of the website below:</p>

<blockquote>
  <p>Who is the author and who is the owner?  Under U.S. copyright law, the
  author of a work generally owns the copyright. However, when it comes
  to software development, the issue of copyright ownership can be a
  complex matter. Under the work-made-for-hire doctrine, if a Software
  Developer is working as the employee of a company, then the employer
  is considered the “author” and owns the copyright. This is true even
  if the Developer(s) strategize, plan, develop, and test the new
  software.</p>
  
  <p>However, if the Software Developer is working as an independent
  contractor, rather than as an employee, then the Developer is
  considered the owner unless there is a written agreement to the
  contrary. The company for which the software is developed may have a
  license to use the software, but it won’t be the owner of the software
  and may not be able to sell or create new versions of the software.</p>
  
  <p>It is important that both Software Developers and Software Companies
  1) understand at the beginning who will own any copyrights that result
  from the work, and 2) create the necessary contracts to ensure that
  ownership ends up where it was intended.</p>
</blockquote>

<ul>
<li>See more at: <a href="http://saperlaw.com/2007/09/27/five-things-every-software-developer-should-know/#sthash.mBamMoCY.dpuf" rel="nofollow">http://saperlaw.com/2007/09/27/five-things-every-software-developer-should-know/#sthash.mBamMoCY.dpuf</a></li>
</ul>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).