## Image service CDN

- posted by: [Frank Goortani](https://stackexchange.com/users/1156045/frank-goortani) on 2015-06-25
- tagged: `lean-startup`
- score: 1

as a part of our startup, users can upload a lot of images. we have chosen not to store the images on our servers. We need a content delivery network (CDN) that is fast enough, cheap and easy to code. We initially chose Amazon S3 and CloudFront for multiple reasons however, now we realize its taking too long to code as we need this feature done for our MVP first release. Considering the security required for each user, what are the best alternatives for my problem?


## Answer 5604

- posted by: [Nero](https://stackexchange.com/users/1705837/nero) on 2015-06-27
- score: 2

<blockquote>
  <p>We need a content delivery network (CDN) that is fast enough, cheap and easy to code. We initially chose Amazon S3 and CloudFront for multiple reasons however, now we realize its taking too long to code as we need this feature done for our MVP first release.</p>
</blockquote>

<p>Given that you are a startup and this will be your first release, it sounds that you do not have customers/users yet.</p>

<p>Under this premise, for your first users you do not need a content delivery network with servers around the world. When you click on a small website, you can not even tell on which continent the server is located. And you probably will not have a hundred clicks per minute on day one.</p>

<p>Paul Graham wrote in his article <a href="http://www.paulgraham.com/ds.html" rel="nofollow">Do Things that Don't Scale</a></p>

<blockquote>
  <p>When you only have a small number of users, you can sometimes get away with doing by hand things that you plan to automate later. This lets you launch faster, and when you do finally automate yourself out of the loop, you'll know exactly what to build because you'll have muscle memory from doing it yourself.</p>
</blockquote>

<p>So, if Amazon S3 is too costly/time-consuming at the beginning, you have the possibility to host everything on your own servers. And this is <em>because</em> you are still small. Move your data/service to some CDN later, when you have too much traffic to handle it on your own server.</p>

<p>Don't forget that - at the beginning - you're small.</p>




---

All content is licensed under the [CC BY-SA 3.0 license](https://creativecommons.org/licenses/by-sa/3.0/).
