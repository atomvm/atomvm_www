# Prerequisites

To build this website, you will need:

* [Ruby 2.7](https://www.ruby-lang.org/en/)
* [Bundler](https://bundler.io)

# Instructions

Change your working directory to the directory containing this README:

    cd <path-to-this-directory>

[Optional] We recommend installing all the needed Ruby gems locally (by convention, under `vendor/bundle`):

    bundle config set --local path 'vendor/bundle'

Install all the needed gems.  This may take some time to complete.  Be patient.

    bundle install

Serve up your site!

    bundle exec jekyll serve [--host <host>] [--port <port>]

or build the website:

    bundle exec jekyll build [-d <path-to-output>] [--watch]

# Add a News Post

To post a new article add a file to the _posts directory in the format:

`YYYY-MM-DD-{title}.md`

with a title section like:

```
---
layout: post
title: {Your Headline}
excerpt_separator: <!--more-->
---
```

followed by the news post in markdown format.
If you are posting a long article you can tell where to cut off the introduction that is displayed in the news section, leaving the full article available by following the article link, by placing a line containing:

`<!--more-->`

All content following the above line will only be included in the full article, content before will be displayed as a description on the `atomvm.org/news` page.
