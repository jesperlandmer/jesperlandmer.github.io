---
layout: post
title:  "Static Site Generators! What about it?"
date:   2016-11-15 10:34:50 +0000
categories: posts
---
Static site generators(SSG) is commonly used when building web pages. You can describe the SSG as a machine; you put 
different product parts and throw it into the<!--more--> machine, and the machine produces and returns a product. Now, replace the parts 
with templates, text and HTML, and the machine returns a static html site.

When building your web page, a static site generator could be a very useful tool. It makes it much easier to keep track of 
and implement all the different elements that your site may contain(header, nav, footer etc). For this site, I used Jekyll
(read more about it [here][jekyll]) as the SSG. It's much easier to work from a SSG rather than editing each html-file and copy and 
paste every element on every page. That's just too much extra work. 
With a SSG, you just have to create one footer-file, one header-file etc. and then let all other pages on your website use the same framework.

Using a static site generator is useful when creating a simple static website, for example if you want one of those 
one page-endless-scroll web pages. It's also useful in most website-building practices when you just want a simple web page or
blog, where the magic happens mostly in <main\>, and the other elements stays static.

A SSG comes with other benefits as well. Usually a SSG will heighten you websites performance and increase the
ability to handle more traffic to the website. It will also increase security since SSG don't have any databases, and 
tons more.

[jekyll]: https://jekyllrb.com/