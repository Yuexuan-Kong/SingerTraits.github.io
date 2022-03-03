---
layout: post
title:  "A Short Introduction to AI in Music World"
date:   2022-02-12 14:34:25
categories: mediator feature
tags: regular
image: /assets/article_images/introduction/bg.JPG
---

# What is singer traits detection and why are we studying this ?  


## About this blog ... 
>Here, we will write about how to identify singer traits (gender/age/race/etc.) through singing voice of the popular songs based on acoustic features. This is one of the mains problems in Music Information Retrieval (MIR).

## What is MIR ... 
>Music Information Retrieval (MIR) is an interdisciplinary science between audio signal processing and music information analysis, ex- tracting information from music including audio or meta-data. MIR is as paralinguistic speech processing in speech world. 

Common tasks in MIR includes cover song identification, music melody extraction, song chord recognition, music recommendation, etc. 


## How about singer traits recognition ?
>Singer trait classiﬁcation, that is, automatically recognizing meta data such as age and gender of the performingvocalist(s) in recorded music, is still an unexploited area. Few research have been conducted on identifying singer traits given that no prestored database is provided. 


However, from the audio of a piece of music, localizing the portions that contain singing voice is a strong information that can be useful for a variety of applications including vocal melody extraction, singing voice separation, or singer identification. Music exhibits some similarity of structural regularity like natural language, inspired by speech recognition, a good model of musical language can also help the music transcription and classification problem. Male and female have different singing pitch range as well as timbre, recognizing singer traits can help improve vocal quality over phone, as well as help collecting user information. Exploiting genderinformation is known to be very useful for building modelsfor other music information retrieval tasks such as automaticlyrics transcription.


Current research in speech processing suggests that the automatic determination of age in full realism is challenging even in clean, spoken language. On the other hand, it is well known that age as well as body shape (height and weight) have acoustic correlates that can be exploited for automatic classification; additionally, it has been shown that demographic traits including ethnicity can be derived from spoken language. In comparison to speech, recognition of singer traits is expected to be an even more challenging task due to pitch variability, influence of voice training, and presence of multiple vocalists as well as instrumental accompaniment. 


This is why in this blog, we focus on singer traits detection and try to take a more clear and closer look at it.





<!-- the most common way is to run `jekyll serve --watch`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help]. -->

<!-- {% highlight js %} -->

<!-- <footer class="site-footer">
 <a class="subscribe" href="{{ "/feed.xml" | prepend: site.baseurl }}"> <span class="tooltip"> <i class="fa fa-rss"></i> Subscribe!</span></a>
  <div class="inner">a
   <section class="copyright">All content copyright <a href="mailto:{{ site.email}}">{{ site.name }}</a> &copy; {{ site.time | date: '%Y' }} &bull; All rights reserved.</section>
   <section class="poweredby">Made with <a href="http://jekyllrb.com"> Jekyll</a></section>
  </div>
</footer>
{% endhighlight %} -->


<!-- [jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
 -->