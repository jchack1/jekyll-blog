---
layout: post
title:  "Blog stopped working and now works again"
date:   2019-11-23 18:27:00 -0700
categories: jekyll
author: Julia Hack 
tags: jekyll
---
First of all, I would like to give credit to the Jekyll documentation step-by-step tutorial for giving me the code to work with on my blog page.

I am not sure what happened exactly, but for a while my blog page decided to stop working. Upon searching on stack overflow I noticed some people were having issues with the _site folder deleting and regenerating each time you serve the site again. I had this problem as well, because my logo decided it would just disappear when I served the site again.

This is because I placed it directly in the img folder inside of _site. I learned from this that you DON'T TOUCH the _site folder. That is for jekyll to render your site. From this I also learned that you need to use "jekyll build" when you make changes to your site, then re-serve it. Seems to be working so far but I am a bit shaky on my understanding of it.

After messing around in the code a fair bit, and doing severl "jekyll build" & "bundle exec jekyll serve", something changed and my blog now works (again). I suspect it has something to do with the commands I mentioned above.  