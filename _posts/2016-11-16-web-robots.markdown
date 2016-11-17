---
layout: post
title:  "Web Robots"
date:   2016-11-16 10:34:50 +0000
categories: posts
---
Web Robots are programs that explores and crosses the web, and are especially used frequently by search engines. Most 
search engines uses them to index the web content or to get certain information. 

The web page authors have the possibility of giving the robots instructions on what content that should be indexed. 
By creating a robots.txt-file in your root-directory, you have the option to block the robots you don't want snooking around, or 
you can control what content the robots shouldn't index. It looks something like this:

{% highlight ruby %}
User-agent: *
Disallow: /whatever.html
Disallow: /whatever2.html
Disallow: /assets/
{% endhighlight %}

The User-agent implies what robots are allowed, and the * means that this section applies to all robots. The "Disallow" tells 
the robot what pages or files that shouldn't be indexed.

For this site, I have created a text-document called robots.txt. In the robots.txt, i've applied user agent to all robots, and 
disallowed access to the assets and posts, like this:

{% highlight ruby %}
User-agent: *
Disallow: /posts/
Disallow: /assets/
{% endhighlight %}