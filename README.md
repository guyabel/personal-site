# personal-site
personal site with hugo and blogdown

* added publishdir: ../personal-site-public to config.yaml following https://womendotcode.be/blog/how-to-make-blog-with-r-blogdown-and-github-pages/#step-4.-customize-%E2%80%98config.yaml%E2%80%99
* run in git and check this is in .gitattributes added after
```{}
git lfs install
git lfs track ".gif"
git lfs track ".mp4"
git lfs track ".png"
git lfs track ".jpg"
```
* make sure you have a .nojekyll file in the root of your repo to avoid jekyll processing the files
```{}
file.create('.nojekyll')
```