---
layout: post
title:  "Tumblr to Jekyll Importer"
date:   2013-09-14 21:58:10
categories: jekyll markdown
---

So this is how its done. How do you go from Tumblr to Middleman?  Go thru another middleman, hahaha.  Use a Jekyll importer to get your tumblr posts into middleman.

Try this code (actually this was my code, not yours)

`ruby -rubygems -e 'require "jekyll/jekyll-import/tumblr"; JekyllImport::Tumblr.process("http://agsdot.tumblr.com", "md", true, false, false)'
`

Some stuff is probably superfluous. I don't think I got the images imported (that's why there was one more "true" boolean statement).  The front matter stuff in jekyll is a little different than middleman, but heck, I got the tumblr stuff into markdown.  Thats the important part.

Jekyll post one.  Likely the last one too.  For Ruby static sites, I'm a middleman type of man.


JL