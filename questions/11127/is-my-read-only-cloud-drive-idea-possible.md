## Is my "read-only cloud drive" idea possible?

- posted by: [frankie](https://stackexchange.com/users/1480988/frankie) on 2016-09-13
- tagged: `content`, `cloud`, `media`
- score: 0

<p>I run a successful video content company for 10 years. I've built up the catalog now to over 50GB of content that users can subscribe to. Usually, the users are emailed links to everything in the catalog to download and keep forever.</p>

<p>My idea now is to use Amazon S3 as a virtual repository of content that users can subscribe to. Once subscribed, our master repository would get mirrored on the users end.</p>

<p>My questions are:</p>

<ul>
<li>Is there a service/api that does something like this already?</li>
<li>Is it possible to have content/virtual hard drive locally mounted that is write/copy protected?</li>
<li>Any other ideas? </li>
</ul>



## Answer 11709

- posted by: [Stefan D](https://stackexchange.com/users/1533420/stefan-d) on 2016-12-15
- score: 1

<p>Look into <a href="http://www.webdav.org/" rel="nofollow noreferrer">WebDav</a>. It's a standard protocol for cloud drives and will save you development effort.</p>



## Answer 11129

- posted by: [László Kovács](https://stackexchange.com/users/9064103/l-szl-kov-cs) on 2016-09-14
- score: 0

<p>I do not know of a software or service that specifically provides read-only drive mirroring. However, I think you should consider that read-only is the default nature of the Web. What you are describing is basically just a website or web app, probably similar to what you have already. </p>

<p>I believe a good option would be to develop a small desktop application that creates the local folder and syncs the master repository in the background. This would be similar to, e.g. the Google Drive desktop agent when you sync one of your Drive folders to your computer.</p>

<p>S3 or another cloud hosting service could certainly be used to host the master repository.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
