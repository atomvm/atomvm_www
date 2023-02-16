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
