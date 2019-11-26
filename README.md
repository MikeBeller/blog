# How to Rebuild

Clone the repo using --recurse-submodules

    git clone --recurse-submodules git@github.com:MikeBeller/blog.git

Edit posts in content/posts/...  (See hugo documentation).

```
    # in blog directory
    hugo
    cd public
    git add .
    git commit...
    git push origin master
    cd ..
    git add .   # in order to update the public submodule link
    git commit...
    git push origin master
```
