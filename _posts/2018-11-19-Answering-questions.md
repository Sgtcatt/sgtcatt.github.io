---
layout: post
title: "Answering questions"
categories: jekyll update
---
Pre-compiling CSS

CSS Preprocessors are a lot better to learn how to use than just continuing to use normal CSS. the usage of these compilers makes it so that it's much easier to update your code and there are a lot less code that you must write in the end. 

In the code I have for the website, I have mostly been using SCSS to change the colors of a lot of things and made sure that everything was working/ looking the way I wanted. I could for example change the color of $text-color to orange, and all the code that uses the variable would change.

variables in CSS are a lot clunkier to write. this is an example of variables written in CSS vs SCSS:

{% highlight ruby %}
:root{
  color:red; 
}

h2{
    color: var(--color);
}
#=> css 
{% endhighlight %}
{% highlight ruby %}

$color: red

.h2{
    color: $color;
}
#=> scss 
{% endhighlight %}

So preprocessors in the end are a lot better to use.



Static site generators

Static site generators are nice to use if you are going to create a large website with a lot of pages.
With the generators you can quickly create a layout that all pages are going to use and update new pages with new content instead of having to add in all the other code from the layout before you start creating new code.
this page I’m writing this in does not have a single piece of code inserted in it (if you don’t count my examples above) and it still looks beautiful.
so for large websites, having a site generator is super helpful.

Robots.txt

Robots.txt is a text file that search engines first look for. So, in the txt file you can put what the engines can’t show and if you don’t want for example: images to not show in search results, that’s where you want to write it in.
in my robots.txt file I don’t really have anything because right now, my webpage doesn’t have much information or pictures etc. but in the future i may add more.
it is recommended to always have a robots.txt file for all webpages you create.

Humans.txt

Humans.txt is not a required file to add to the webpage but it is recommended. think of humans.txt as the credits of a webpage. that’s where you write all the developers and software or whatever you want.
in my humans.txt I have written what software I have been using and listed myself as the main developer of my site.

Comments
The comments provider I use is just comments becouse I found a nice tutorial on the net (and disqs was clunkier). I implemented the comment code in my _layous and post.html code that is used as a layout for all my blogg pages (and it works like a charm ;)).
