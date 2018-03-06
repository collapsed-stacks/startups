## Pricing code reviews

- posted by: [Luke Gedeon](https://stackexchange.com/users/1119600/luke-gedeon) on 2015-12-02
- tagged: `pricing`
- score: 3

I would like to price code-reviews based on number of statements (roughly lines of code). I don't want to count comments or white space because they help the reviewer rather than slow him down.

I want to adjust for multiple statements packed on the same line. For example, minified css and js will put thousands of statements on the same line. So really, I want to count number of statements.

To that end I would count:

 - CSS: number of semicolons, commas, and closing braces not preceded by semicolon.
 - JS: number of semicolons, periods, and closing braces not preceded by semicolon.
 - PHP: number of semicolons and closing ?> not preceded by semicolon.
 - HTML: number of tags.

Are there any concerns with this way of pricing? Am I missing anything? Is there enough of a difference for code review purposes between declarative and logical statements that I should factor that into pricing?

As a side note, I am familiar with CLOC and SLOCCount which would need additional code to do this type of count, but if you know of a better tool, a comment would be appreciated, but answers should focus on pointing out problems with this pricing structure.


## Answer 8784

- posted by: [Marcus D](https://stackexchange.com/users/258531/marcus-d) on 2016-03-21
- score: 1

<p>I think the things you have picked up are reasonable.</p>

<p>I suspect you have thought of these aspects already, but you need to make it a repeatable and as automated process as possible, so I would suggest one or more "standard" code formatters. You obviously don't want an <a href="http://beta.phpformatter.com/" rel="nofollow">online</a> one, but an installed offline version that caters for your languages. </p>

<p>I realise that these code formatters will often split lines of code over multiple lines. I would accept this as reasonable and build this into your costing-business model. The code you get will be more maintainable and the other advantage is that your clients can have a easier way to determine what they are paying for.</p>

<p>Then following that, you could write a PHP/Perl/Python script that will count lines of code as per the formatted lines, ignoring comments, white space etc.</p>

<p>I realise that I haven't focused on your exact question. but potential problem that you could have with your pricing model are:-</p>

<ul>
<li>complex multiline PHP syntax, depending if you decide that piping (or whatever is the equivalent term) results from one function to another is one or many 'lines'</li>
<li>HTML pages where there is a lot of formatting, but perhaps then the CSS would take care of that</li>
<li>JS code that is simple but repetitive due to language constraints. Not sure I have an exact example, but in SQL performing some types of pivots are very code intensive, even though the logic is simple.</li>
</ul>

<p>Overall, I think its a decent enough method, especially if you are paying for the code to be written using the same metric, then charging a margin on the code that is sold. You can potentially use fairly low level coders, depending on the complexity and scope of what you want.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
