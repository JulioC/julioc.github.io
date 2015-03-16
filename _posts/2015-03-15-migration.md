---
layout: post
title: Migrating to GitHub Pages and Jekyll
---

After years using Wordpress to host an abandoned it was time to make a refresh on my page. Because the plan was to build just a simple about me page, I went with plain static pages.

At first, it looked like an good idea. With the basic layout done, I started building [my resume]({{ site.url }}/resume) with [JSON Resume](http://jsonresume.org/) and a custom template, along with the [localized version]({{ site.url }}/resume/br) and the [projects page]({{ site.url }}/projects). Soon I realized it was going to be a nightmare to keep everything up to date.

#### Jekyll and GitHub Pages

My alternative plan was to go with a static site generator, like [Pelican](http://getpelican.com/), built on Python, or [Jekyll](http://jekyllrb.com/), built on Ruby. After some research, Jekyll was the winner for the single fact that it powers [GitHub Pages](https://pages.github.com/).

Jekyll has lot of features, including [Markdown](http://daringfireball.net/projects/markdown/) (including [GFM](https://help.github.com/articles/github-flavored-markdown/) using the [kramdown engine](http://kramdown.gettalong.org/)), [Liquid](https://github.com/Shopify/liquid/) templating language and [Sass](http://sass-lang.com/). As a bonus for hosting on GitHub Pages you get a nice hosting for free and lots of easy ways to edit the content.

Starting out the project was easy, following [Jekyll documentation](http://jekyllrb.com/docs/) and studying the structure of projects like [Jekyll Now](https://github.com/barryclark/jekyll-now) and [Poole](https://github.com/poole/poole). Jekyll is a bit tricky to install on Windows, but there is a nice [tutorial for that](http://jekyll-windows.juthilo.com/).

As a goal for this project I wanted to be able to generate my resume from the same JSON file I used on JSON Resume. Jekyll is able to read JSON [data files](http://jekyllrb.com/docs/datafiles/), so I just needed to rewrite my resume template to use Liquid (with some help from their [syntax guide](https://github.com/Shopify/liquid/wiki/Liquid-for-Designers)).

#### Final result

In a week, working on my free time, I feel the result is good enough (if you disagree, please leave your suggestion). I expect to post here more frequently, logging my progress on game development and other random topics.

If you are curious about the source code, explore the [repository on GitHub](https://github.com/JulioC/julioc.github.io/). You are free to copy it (under [MIT license](https://github.com/JulioC/julioc.github.io/blob/master/LICENSE)), just be original with the appearance.