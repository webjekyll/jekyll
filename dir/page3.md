---
title: Page 3
description: This is just another page
layout: default
categories: AAA BBB
---

### [back](../)
#### [dir](./)

# _config.yml

## Eg1.

```
markdown: kramdown
theme: minima
rms46@rmsbase:~/tmp/dumdum$ vi _config.yml 
rms46@rmsbase:~/tmp/dumdum$ cat _config.yml 
title: TITLE
description: >- # ignore until "baseurl:"
   Dadada...
baseurl: "" # the subpath of your site, e.g. /blog
url: "" 
twitter_username: dummy
github_username:  dummy
email: e@ma.il

markdown: kramdown
theme: jekyll-theme-hacker
plugins:
  - jekyll-feed

# exclude:
#   - Gemfile
#   - Gemfile.lock
#   - node_modules
#   - vendor/bundle/
#   - vendor/cache/
#   - vendor/gems/
#   - vendor/ruby/

```

## Eg2.

```
defaults:
   -
      scope:
       path: ""
       type: "posts"
      values:
         layout: "post"
         title:  "My Title"
  -
    scope:
      path: ""
      type: "pages"
    values:
      layout: "my-site"
  -
    scope:
      path: "projects"
      type: "pages" 
    values:
      layout: "project"
      author: "Mr. Hyde"
      category: "project"
  -
    scope:
      path: ""
      type: "my_collection" 
    values:
      layout: "default"


```

### [back](../)

# Front Mater

## Eg1.

```
---
layout: post
title:  "Welcome to Jekyll!"
date:   2019-06-28 18:06:07 +0700
categories: jekyll update
author: CbK
permalink: /about/
permalink: /:categories/:day/:year/:month/:title.html
---

```

### [back](../)

# Bundle

## Eg1.

```
bundle exec jekyll serve --draft
```

### [back](../)


