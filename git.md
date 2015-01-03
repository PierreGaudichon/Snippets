### Undo the file deletion

The `$file` is the path, need to be changed.

``` bash 
  git checkout $(git rev-list -n 1 HEAD -- "$file")^ -- "$file"
```
