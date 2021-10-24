CHANGELOG.md       _config.yml        _posts             files
CONTRIBUTING.md    _data              _publications      images
Gemfile            _drafts            _sass              markdown_generator
Gemfile.lock       _includes          _site              package.json
LICENSE            _layouts           _talks             talkmap
README.md          _pages             _teaching          talkmap.ipynb
_config.dev.yml    _portfolio         assets             talkmap.py

# Welcome to Jekyll!
#
# This config file is meant for settings that affect your entire site, values
# which you are expected to set up once and rarely need to edit after that.
# For technical reasons, this file is *NOT* reloaded automatically when you use
# `jekyll serve`. If you change this file, please restart the server process.

# Site Settings
locale                   : "en-US"
title                    : "Your Name / Site Title"
title_separator          : "-"
name                     : &name "Your Name"
description              : &description "personal description"
url                      : https://academicpages.github.io # the base hostname & protocol for your site e.g. "https://mmistakes.github.io"
baseurl                  : "" # the subpath of your site, e.g. "/blog"
repository               : "academicpages/academicpages.github.io"

404.md                         markdown.md                    tag-archive.html
about.md                       non-menu-page.md               talkmap.html
archive-layout-with-content.md page-archive.html              talks.html
category-archive.html          portfolio.html                 teaching.html
collection-archive.html        publications.md                terms.md
cv.md                          sitemap.md                     year-archive.html

# main links links
main:
  - title: "Publications"
    url: /publications/

  - title: "Talks"
    url: /talks/

  - title: "Teaching"
    url: /teaching/

  - title: "Portfolio"
    url: /portfolio/

  - title: "Blog Posts"
    url: /year-archive/

  - title: "CV"
    url: /cv/

  - title: "Guide"
    url: /markdown/
    
    # main links links
main:
  - title: "Research"
    url: /research/

  - title: "Blog"
    url: /year-archive/

  - title: "CV"
    url: https://github.com/elizabethmcd/cv/blob/master/EAM-CV.pdf
    
    ![](../images/file.png)
    
    git add --all
git commit -m "initializing personalized website"
git push origin master
