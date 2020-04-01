---
title: How to Contribute
layout: default
permalink: /contributing/
---

<section class="intro">
	<p>
		When contributing to this CarpentryConnect Website repository, please first discuss the change you wish to make with this repository's maintainers via <a href="/issues">this repository's issue tracker</a> or <a href ="mailto:community@carpentries.org">email</a> before dedicating time to make big, time-consuming changes.
	</p>
</section>

## About the Code Base

 This resource is a [Jekyll](https://jekyllrb.com) website. 

Here's how content is organised on the website:

### Markdown files

Files for pages available in the menu bar at the top of the website are available in the root folder i.e.

- index.markdown
- in-person.markdown
- online.markdown
- case-studies.markdown
- CONTRIBUTING.md


### Stylesheet

All associated styling that makes pages in this resource readable and aesthetically pleasing can be found in the [css](https://github.com/CarpentryConnect/carpentryconnect.org/tree/master/css) folder.


### YAML files

YAML files are a human-readable way to feed data into our website.

- [_config.yml](https://github.com/CarpentryConnect/carpentryconnect.org/blob/master/_config.yml) holds information about navigation settings.


Be careful about spacing when working with YAML files. When in doubt / experiencing errors, use a linter service like [YAMLlint](http://www.yamllint.com) to validate your additions. 

### Image Files

All image files are in the [img](https://github.com/CarpentryConnect/carpentryconnect.org/tree/master/img) folder.

## Setting Up a Local Instance

Should you wish to make changes locally, and review them before submitting a Pull Request, here's how to go about it:

1. Open your local terminal and clone this repository

1. Install Bundler. If you like, you can [learn more](https://bundler.io) about bundler.

`gem install bundler`

3. Navigate to your root folder and run the command

`bundle install`

This looks at your GEMFILE and installs all ruby gems listed in it.

4. Run Jekyll

`bundle exec jekyll serve`


## Where to Find Help

### Submit an Issue

We welcome any questions you may have about setting up or contributing to this website repository in the [issues](https://github.com/CarpentryConnect/carpentryconnect.org/issues) section of this repository.

### Email us

Where email is preferred, you can reach out to us on [community@carpentries.org](mailto:community@carpentries.org).


