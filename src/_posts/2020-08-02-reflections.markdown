---
layout: post
title:  "Reflections"
date:   2020-08-02 06:54:21 -0500
categories: jekyll update
---
<h2>Thoughts on pre-compiling CSS</h2>

Since I've had previous experience with writing CSS it has been a little bit of an adjustment to use this new
method of pre-compiling. It was a little bit tricky at first to figure out which things went where, not to
mention trying to find all the files I needed and properly linking them to make sure everything would be
included in the browser. Despite struggling with this new tool, however, I can abslutely see the value in
using this method and look forward to learning more about it, as I'm sure it will be very helpful when
creating websites in the future!

I used Sass for pre-compiling CSS, and to do this I first copied the pre-existing scss files as a base. Here
I immediately ran into an issue, as the folder the files were supposedly in was nowhere to be found. I did
manage to solve this problem by using "Inspect element" in the prowser, clicking the style tab, and simply
downloading the files by clicking "Save" on them and then placing them in my own _sass folder. With these files saved, I went thought them and experimented with changing values to see what happened. I did
struggle a bit with getting things to connect properly, but after a while I got everything to work the way I
wanted it to.

The main obvious pro of using this method is that it's easy to achieve consistency and it's much easier to
maintain than writing one's own CSS code. However it is a bit tricky to learn how Sass relates to CSS and
how to achieve one's goals, but once you're past the learning curve it is ultimately a great tool to use.

<h2>Thoughts on static site generators</h2>

Static site generators can be useful for quickly and easily throwing together a website for simple purposes
like for instance sharing information with an organization, uploading a photo gallery, or run a blog. The
fact that a lot of things are automatic can be very convenient for these purposes.

----MOAR----

<h2>Robots and humans</h2>

text

<h2>How comments were implemented</h2>

This was by far the most difficult part of the assignment and had me on the verge of pulling my hair out. I
used Disqus for implementing comments, and the principle is a very simple one. I just had to register on the
Disqus website and write two lines in my _config file to add the comment section, that was it! However, it
was not working. When attempting to view the comments on a blog post, all I got was a message saying that
Disqus failed to load and to look over the troubleshooting guide. Hours upon hours were spent trying to figure
out what could have gone wrong. I looked at guides, I read through previous Slack conversations from other people having similar issues, I googled ad nauseam... Nothing worked even though everything looked right.

The only thing I could think of was that it wasn't working on my local machine (and I could also not add it to the list of trusted websites on Disqus since it wasn't a published website) so what I ended up doing was prematurely publishing my website on Github and then added github.io to my list of trusted domains. Lo and behold, now comments were showing up just like they should! I still don't know why it seemed to be working for other people and not me, but I'm glad I managed to figure out how to fix it.

<h2>About Open Graph</h2>

text

<div class="trigger"><a class="page-link" href="/blogposts/">Back to blog posts</a></div>
