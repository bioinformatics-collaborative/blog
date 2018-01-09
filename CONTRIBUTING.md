## How to contribute to this blog

1. Install [Hugo](https://gohugo.io/getting-started/installing/) on your computer and ensure it is in your path with `hugo -h`.
2. Fork this repository (you may want to clone it to your computer as well).
3. Go to the `content/post` [folder](https://github.com/ummc-bjc/blog/tree/master/content/post).
4. Create a post using the below format. You can use rmarkdown or html in your post. The post should be a `.md` file.

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


5. View the site with `hugo `
6. Remove the public folder using `rm -rf public/`.
7. Use `git submodule add -b master https://github.com/ummc-bc/ummc-bc.github.io.git public` to create a git submodule of the public site folder at the `ummc-bc.github.io` repository.
8. Regenerate the site with the following command in the top level of the github repository: `hugo -t hugo-icarus-theme`
9. Change directories to the public folder: `cd public`
10. Now, add your changes to git and push to Github to publish the site.

```bash
git add .
git commit -m "Added a post titled `How to Code`"
git push origin master
```

11. Remove the public folder using `rm -rf public/`.
12. Update the `blog` repository with your changes i.e. new post.

```bash
git add .
git commit -m "Added a new post"
git push origin master
```

13. Open and submit a [pull request](https://github.com/ummc-bjc/blog/compare).
