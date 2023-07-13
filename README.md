# AACL SRW 2023 Website

This is a Jekyll site written in Ruby and Markdown files. Most of the contents are written in `.md` file so they can be changed with minimal efforts without affecting the functionality of the website.

## Setup

Here is a helpful [resource](https://www.docslikecode.com/learn/02-jekyll-ruby-gh-pages/) to install the requirements. I listed several important commands to run below. When in doubt, checkout the link above, [Jekyll docs](https://jekyllrb.com/docs/ruby-101/), or Google.

```bash
gem install bundler
```

If you are seeing issues with installing bundler, checkout this [post](https://stackoverflow.com/questions/51126403/you-dont-have-write-permissions-for-the-library-ruby-gems-2-3-0-directory-ma)

If necessary, install `jekyll` manually ([source](https://stackoverflow.com/questions/8146249/jekyll-command-not-found)):

```bash
gem install -n /usr/local/bin jekyll
```

```bash
bundle update
bundle install
```

## How to deploy

```bash
bundle exec jekyll serve
```
