---
layout: default
title: Home
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

# Welcome to REDCap Hub!
{: .fs-9 }

REDCap Hub is a site providing support to REDCap users in the form of informational excerpts and examples of work with particular REDCap features and examples of best practices when it comes to data management.
{: .fs-6 .fw-300 }

---

## REDCap

Research Electronic Data Capture (REDCap) is a rapidly evolving web tool developed by researchers for researchers in the translational domain. REDCap features a high degree of customizability for your forms and advanced user right control. It also features free, unlimited survey functionality, a sophisticated export module with support for all the popular statistical programs.

[REDCap Overview](https://redcap.c2e2.ca/surveys/?s=TTFNCANPPN){: .btn .fs-5 .mb-4 .mb-md-0 }

### Getting Started



### Instance available in the area

1. REDCap UBC

### Local installation: Use the gem-based theme

1. Install the Ruby Gem
```bash
$ gem install just-the-docs
```
```yaml
# .. or add it to your your Jekyll site’s Gemfile
gem "just-the-docs"
```
2. Add Just the Docs to your Jekyll site’s `_config.yml`
```yaml
theme: "just-the-docs"
```
3. _Optional:_ Initialize search data (creates `search-data.json`)
```bash
$ bundle exec just-the-docs rake search:init
```
3. Run you local Jekyll server
```bash
$ jekyll serve
```
```bash
# .. or if you're using a Gemfile (bundler)
$ bundle exec jekyll serve
```
4. Point your web browser to [http://localhost:4000](http://localhost:4000)

If you're hosting your site on GitHub Pages, [set up GitHub Pages and Jekyll locally](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll) so that you can more easily work in your development environment.

### Configure Just the Docs

- [See configuration options]({{ site.baseurl }}{% link docs/configuration.md %})

---

## About the project

REDCap Hub is provided and supported by 2020-{{ "now" | date: "%Y" }} by [C2E2](http://www.c2e2.ca/).

### License

Just the Docs is distributed by an [MIT license](https://github.com/pmarsceill/just-the-docs/tree/master/LICENSE.txt).


