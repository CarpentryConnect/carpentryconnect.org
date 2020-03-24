

When contributing to this CarpentryConnect Website repository, please first discuss the change you wish to make with this repository's maintainers via [this repository's issue tracker](/issues) or [email](community@carpentries.org) before making a change.

# About the Code Base

The underlying code for CarpentryConnect website is a fork of [Project Zepellin](https://github.com/gdg-x/zeppelin). It is a [Jekyll](https://jekyllrb.com) website. 

Here's how content is organised on the website:

## HTML files

1. Files for pages available in the menu bar at the top of the website are available in the root folder i.e.

- index.html
- in-person.html
- online.html
- case-studies.html
- contributing.html


2. Any associated files that make up specific sections of these pages i.e.

- about.html
- footer.html

and more are available under the [_includes](/_includes) folder.

## Markdown files

The Case Studies feed on the website is made possible by Markdown files published under the [_posts](/_posts) folder.


## YAML files

YAML files are a human-readable way to feed data into our website.

1. [_config.yml](/_config.yml) holds information about 

- site settings
- the case studies page and more

2. YAML files in the [_data](/_data) folder hold specific information about

- community members involved in of planning for various CarpentryConnects
- resource curation personnel information ( The Carpentries Core Team in this case)
- partner and sponsor information for past CarpentryConnect events

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

## Project Zeppelin repository

The Project Zeppelin team has extensive documentation available [here](https://github.com/gdg-x/zeppelin/wiki).