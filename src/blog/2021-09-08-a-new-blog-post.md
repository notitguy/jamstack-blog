---
title: A new blog post
description: some description is here.
author: Michael Scott
date: 2021-09-08T18:45:06.778Z
tags:
  - post
  - featured
image: https://static.remove.bg/remove-bg-web/97e23b9bea3ef10227bf2e0bed160d3a30f93253/assets/start-0e837dcc57769db2306d8d659f53555feb500b3c5d456879b9c843d1872e7baa.jpg
imageAlt: A girl holding her had
---
## Authentication

Now that you have your Netlify CMS files in place and configured, all that's left is to enable authentication. We're using the [Netlify](https://www.netlify.com/) platform here because it's one of the quickest ways to get started, but you can learn about other authentication options in the [Backends](https://www.netlifycms.org/docs/backends-overview) doc.

### [](https://www.netlifycms.org/docs/add-to-your-site/#setup-on-netlify)Setup on Netlify

Netlify offers a built-in authentication service called Identity. In order to use it, connect your site repo with Netlify. Netlify has published a general [Step-by-Step Guide](https://www.netlify.com/blog/2016/10/27/a-step-by-step-guide-deploying-a-static-site-or-single-page-app/) for this, along with detailed guides for many popular static site generators, including [Jekyll](https://www.netlify.com/blog/2015/10/28/a-step-by-step-guide-jekyll-3.0-on-netlify/), [Hugo](https://www.netlify.com/blog/2016/09/21/a-step-by-step-guide-victor-hugo-on-netlify/), [Hexo](https://www.netlify.com/blog/2015/10/26/a-step-by-step-guide-hexo-on-netlify/), [Middleman](https://www.netlify.com/blog/2015/10/01/a-step-by-step-guide-middleman-on-netlify/), [Gatsby](https://www.netlify.com/blog/2016/02/24/a-step-by-step-guide-gatsby-on-netlify/), and more.

### [](https://www.netlifycms.org/docs/add-to-your-site/#enable-identity-and-git-gateway)Enable Identity and Git Gateway

Netlify's Identity and Git Gateway services allow you to manage CMS admin users for your site without requiring them to have an account with your Git host or commit access on your repo. From your site dashboard on Netlify: