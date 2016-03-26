---
title: Advantages
layout: about
---

### Advantages

- full Markdown support
- liquid templating
- full html, css, javascript
- git/Github for versioning and hosting
- Github provided CDN
- seo optimised static content
- support for custom dns using cname redirects
- supports categories, and list filtering
- Github supports multiple sites per github account with project pages and cnames
- no hosting, opaque db backend, webserver, ssl termination, firewall, backup needed
- no cron copy job

#### Refs

- <http://webapps.stackexchange.com/questions/42455/publishing-more-than-one-site-on-github-pages>

- <http://jekyllrb.com/docs/github-pages/#project-page-url-structure>

- <http://jekyllrb.com/docs/templates>

- <https://help.github.com/articles/configuring-jekyll/>

- <http://joshualande.com/jekyll-github-pages-poole/>

- Adding Google comments will improve seo
  <http://steelx.github.io/best-internet-tips/2014/11/23/Add-google-plus-comments-box-to-jekyll-website.html>

- dns apex on route53 is a bit limited
  <http://stackoverflow.com/questions/16022324/how-to-setup-dns-for-an-apex-domain-no-www-pointing-to-a-heroku-app>

- <https://forums.aws.amazon.com/thread.jspa?threadID=151954>

- Also seems as though cannot do double cname to github, but could probably use this, redirector
  or else set up an instance to do 301 http redirect
  <http://wwwizer.com/naked-domain-redirect>

- Downloads
  <http://stackoverflow.com/questions/32673993/how-do-i-provide-files-for-download>

- Datafiles - json, yaml etc.
  - <https://jekyllrb.com/docs/datafiles/>
  - this provides a good mechanism, to control content creation - eg. could create index pages.
  - only thing missing is really zip files,  
