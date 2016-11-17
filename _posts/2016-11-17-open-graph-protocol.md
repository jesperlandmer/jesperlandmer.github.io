---
layout: post
title:  "Open Graph Protocol"
date:   2016-11-17 09:34:50 +0000
categories: posts
---

Nowadays, information and marketing thrives on social media. For just a small amount of money, you could reach thousands with
whatever you want to market. <!--more-->Perhaps you want to market your website? But first, make sure you have your open graph ready.

### What is Open Graph?
The Open Graph Protocol is a way of making any web page a much more attractive object in social graphs. For instance, it can
present a link to your website with a small photo and a presentation.

There are many ways for making a more informative object on social media, but the Open Graph Protocol offers a way to
combine many of these methods to a more simpler one.

### How is it implemented?
Open Graph is configured in the head of your page. It's done with META-tags, and can contain lots of different information.
On this web page, the META-tags has been implemented like this(using Jekyll):

{% highlight ruby %}
<meta property="og:title" content="title">
<meta property="og:description" content="Github portfolio 
for Web Development student Jesper L Pedersen">
<meta property="og:type" content="website.portfolio">
<meta property="og:url" content="url">
<meta property="og:image" content="src/assets/me.png">
<meta property="og:image:width" content="300">
<meta property="og:image:height" content="300">
{% endhighlight %}