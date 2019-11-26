# How to Rebuild

Edit posts in content/posts/...

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
