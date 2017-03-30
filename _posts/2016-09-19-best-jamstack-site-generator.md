---
title: "Hugo: The Best JAMstack Site Generator"
date: 2016-09-19T10:36:32-05:00
modified: 2017-03-30
author: Josh Habdas
excerpt: In a sea of choice, which static site generator will you choose?
categories:
  - opinion
tags:
  - hugo
  - static websites
  - static site generators
  - jamstack
  - jekyll
  - hexo
header:
    overlay_image: photo-1457203112846-f9f76625f7c4_1280.jpg
    overlay_filter: 0.5
    teaser: photo-1457203112846-f9f76625f7c4_512.jpg
redirect_from:
  - /choose-hugo-over-jekyll/
---

Many are familiar with the idea of static site generators like Jekyll and [why they should use them](http://jekyll.tips/jekyll-casts/why-use-a-static-site-generator/). But those aren't the only <abbr title="Static Site Generator">SSG</abbr>s out there. In fact, there are literally <a href="https://staticsitegenerators.net/" rel="nofollow">hundreds of SSGs</a> guaranteed to give you analysis paralysis. With so many to choose from it can be difficult to decide which to use.

After trying a number of static site generators myself over the years to build my JAMstack sites, **the one I've zeroed in on is none other than [Hugo](https://gohugo.io)**. Here's just a few of the reasons why Hugo rocks the socks off the competition:

- **It has zero dependencies.** Once you get a hold of the Hugo binary you're ready to roll. Many other static site generators require a complex environment and dependencies to run. For Jekyll, that means Ruby and RubyGems. For Hexo, you'll need Node and NPM. For Hugo, all you need is Hugo.
- **It's easy to set-up.** If you're a OS X user, simply `brew install hugo` and you can start a new website with the `hugo new site` command. Hugo pre-built binaries are available for FreeBSD, Windows and Linux as well.
- **It's extremely fast.** Unlike Jekyll or Hexo, which [can](https://mademistakes.com/articles/using-jekyll-2016/#posts-for-all-the-things) [take](https://github.com/hexojs/hexo/pull/550) hours to compile a large site, Hugo can generate up to [5,000 webpages in under 10 seconds](https://youtu.be/CdiDYZ51a2o).

  **Update 10 Feb 2017:** As of Hugo v0.17, when multilingual sites were introduced, Hugo site generation speed has---wait for it---doubled!
  {: .notice--info}

- **It's ultra flexible.** Unlike Jekyll, which was blog-focused until [Collections](https://jekyllrb.com/docs/collections/) were bolted on, Hugo was built from the ground up with freedom of content structure in mind.
- **It's fun!** To prove this last point I decided to create a theme for Hugo called [After Dark](https://comfusion.github.io/after-dark/) (pictured below). The initial theme creation process took about two days, and making it reminded me of the joys of coding for the Web circa 1995---back when flying toasters were all the rage.

![After Dark theme for Hugo screenshots](https://raw.githubusercontent.com/comfusion/after-dark/master/images/minimal-mac.png "After Dark running on a MacBook and iPhone")

There are **some downsides** to Hugo, don't get me wrong. For starters, Hugo hasn't been around as long and, as a result, doesn't not have as large of a community as more well established SSGs like Jekyll. Additionally, you may find a few holes in Hugo's documentation--which is otherwise pretty great.

**Update 30 Mar 2017:** Hugo is currently under way of rollout out an entirely new documentation site. The last one was good. The next one will be even better.
{: .notice--info}

So what are you waiting for? **[Give Hugo a try](/zero-to-http-2-aws-hugo/)**. And, while you're at it, check out the [After Dark theme](https://comfusion.github.io/after-dark/) and for a [culture jamming](https://en.wikipedia.org/wiki/Vaporwave) take on content publishing in the new millennium.