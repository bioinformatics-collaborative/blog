## How to contribute to this blog

1. Download/install [Hugo](https://gohugo.io/getting-started/installing/) on your computer.
2. Fork this repository (you may want to clone it to your computer as well).
3. Go to the `content/post` folder.
4. Create a post using the below format. You can use rmarkdown or html in your post.

```r
+++
banner = ""
categories = ["random"]
date = "2017-05-20T12:00:23+02:00"
description = ""
images = []
menu = ""
tags = []
title = "Random Post"
+++

Leading information about this post.
<!--more-->

XYZ is blah blah
```

5. Regenerate the site with the following command in the top level of the github repository: `hugo -t`
6. Change directories to the public folder: `cd public`
7. Now, add your changes to git and push to Github.
```bash
git add .
git commit -m "Added a new post"
git push origin master
```
8. Open and submit a [pull request](https://github.com/ummc-bjc/blog/compare).
