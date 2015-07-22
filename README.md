# jekyll-post-via-web
A simple HTML+JS page that allows you to post new articles to your GitHub-hosted Jekyll blog, using a browser.

## What is this?
If you host your Jekyll blog on GitHub, you can use jekyll-web-post to post new articles from a browser.
You can find more details here: [Post to your GitHub-hosted blog using a simple bookmarklet.](https://blog.vrypan.net/2015/05/29/post-to-github-jekyll-using-a-bookmarklet/)

## Installation
Just copy cms.html to the root of your Jekyll blog source, and deploy. Then visit the page using your web browser, 
usually at `<url>/<base_url>/cms.html`.

Make sure you have `github.repo` and `github.branch` set in `_config.yml`. This is the repository and branch holding your
blog's source. For example:
```
github:
  repo: vrypan/vrypan.github.io
  branch: master
```

## Support this project
If you'd like this project, consider [donating a fraction of bitcoin](https://blog.vrypan.net/support.html). Thank you in advance!

## Copyright
Panayotis Vryonis, [vrypan.net](https://www.vrypan.net)
