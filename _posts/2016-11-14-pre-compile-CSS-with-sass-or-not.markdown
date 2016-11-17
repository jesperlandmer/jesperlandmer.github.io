---
layout: post
title:  "Pre-compile CSS with SASS or not?"
date:   2016-11-14 10:34:50 +0000
categories: posts
source: http://sass-lang.com/guide
---
So what is the main difference between CSS and SASS? 
Well, SASS is an extension of CSS that spits out a more powerful and a more well-structured CSS. 
It's an addition to the standard CSS, and adds helpful features 
that regular CSS lacks(like variables, nested selectors, mixins, operators and more).

Another great feature with using SASS, is the way it's calling the different stylesheets. Splitting CSS-files to 
smaller and more maintainable files, allows you to have more control over the CSS. Usually, you would call all the CSS-files
with @import, and gather it in a main CSS-file. The downside with this method using standard CSS, is that each time you use
@import in CSS, it creates a new HTTP-request which in turn lowers the efficiency. 

The smart thing with SASS is that it combines all the imported CSS into a single file, which is then sent to the browser.
It can even compile the CSS, to make it even more efficient(the browser won't have to go through all the empty-space). 

### How is SASS implemented?
For this web page, I obviously used SASS as a method to forward the CSS. The main reason why I prefer SASS is that it can use different 
variables. The variables makes it so much easier to keep track of margins between elements, and makes it much easier to maintain.
I also love the way SASS allows you to nestle rules. 

It forms a more easier and good-looking structure of the code, which makes
it more comfortable to work with. SASS also allows you to use operators that allows the CSS to perform calculations. This is very 
useful for example when creating margins. It can be used(and is used on this web page), to for example substitute for media querys.

{% highlight ruby %}
$calc-width: calc(850px - (30px * 2))

.wrapper
  max-width: $calc-width
{% endhighlight %}

### Pros and Cons

So there is obviously tons of pros to use SASS instead of standard CSS. The best arguments are following:
* It allows you to use usable features that CSS lacks
* It compresses the CSS-files down to one single file, which in turn heightens the efficiency.
* It makes it easier to structure your CSS

The are some cons tough. SASS is harder to debug, which makes it frightening to some programmers. There are ways to work
around it tough. Another con is that it can be time consuming to translate, if you for example 
have to work with lots of copied CSS from an already half made CSS-structure, or if you have to copy a large piece from the web.

Check out this [Sass Guide][sass-guide] for more information!

[sass-guide]: http://sass-lang.com/guide
