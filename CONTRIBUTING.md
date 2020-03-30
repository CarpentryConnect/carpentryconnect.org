

When contributing to this CarpentryConnect Website repository, please first discuss the change you wish to make with this repository's maintainers via [this repository's issue tracker](/issues) or [email](community@carpentries.org) before making a change.

# About the Code Base

The underlying code for CarpentryConnect website is a fork of [Project Zepellin](https://github.com/gdg-x/zeppelin). It is a [Jekyll](https://jekyllrb.com) website. 

Here's how content is organised on the website:

## Markdown files

Files for pages available in the menu bar at the top of the website are available in the root folder i.e.

- index.markdown
- in-person.markdown
- online.markdown
- case-studies.markdown
- contributing.markdown


## Stylesheet
All associated styling that makes pages in this resource readable and aesthetically pleasing can be found in the [css](/css) folder.  


## YAML files

YAML files are a human-readable way to feed data into our website.

- [_config.yml](/_config.yml) holds information about navigation settings.


Be careful about spacing when working with YAML files. When in doubt / experiencing errors, use a linter service like [YAMLlint](http://www.yamllint.com) to validate your additions. 

## Image Files

All image files are in the [img](/img) folder.

# Setting Up a Local Instance

Should you wish to make changes locally, and review them before submitting a Pull Request, here's how to go about it:

1. Open your local terminal and clone this repository

1. Install Bundler. If you like, you can [learn more](https://bundler.io) about bundler.

`gem install bundler`

3. Navigate to your root folder and run the command

`bundle install`

This looks at your GEMFILE and installs all ruby gems listed in it.

4. Run Jekyll

`bundle exec jekyll serve`


# Where to Find Help

## Submit an Issue

We welcome any questions you may have about setting up or contributing to this website repository in the [issues](/issues) section of this repository.

