---
layout: post
title:  "Blogging with Github and Jekyll!"
date:   2016-07-16 18:00:00 +0800
categories: Jekyll blog theme Github
---

As discussed mentioned earlier, I will go through my environment and how to start your first blog using Jekyll and hosting it as a repository in Github.

Side note: about my environment, I'm using OS X El Capitan 10.11.5.

How to set up the blog:

1. Create a repository on Github account as `YOUR_BLOG_NAME.Github.io`
2. Use Git client tool, I use command line (SourceTree if you want a graphical tool or the command line for more control on git repos)
3. Install the following
* [Ruby](https://gorails.com/setup/osx/10.11-el-capitan), I used Ruby 2.3.1.
* [RubyGems](https://rubygems.org/pages/download)
* [NodeJS](https://nodejs.org/en/)
* [Python](https://www.python.org/downloads/)

4. Create a branch in this folder now to track your changes and you can name it anything like initBlog or something else.
5. Install [Jekyll](https://jekyllrb.com/docs/installation/) but make sure that you initialize Jekyll in the right folder. For simplicity, I use $Username/Developer/NameOfWebSiteOrRepo 
6. Test it by run the command: `jekyll serve --watch --incremental`. Note that watch option to take care of updating the website according to your changes and incremental option as well.
7. Open the browser on `http://127.0.0.1:4000` and watch your local deployment of your website.
8. Make the required changes in the `_config.yaml` for the base url and the website name.
9. Push these changes into Github and open your blog from `http://YOUR_BLOG_NAME.Github.io`.

You can add any theme you want as I'm using [UNO](https://github.com/joshgerdes/jekyll-uno).