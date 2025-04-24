# Terminal shortcuts

* `Ctrl+a/e`: move to start/end of line
* `Ctrl+u/k`: delete to start/end of line
* `Alt+b/Alt+f`: move to start/end/of word
* `Ctrl+w/Alt+d`: delete to start/end of word
* `Ctrl+y`: paste deleted content

# Commands

## Terminal
* `Clear`

## Exploration
* `ls`
* `tree`

## Navigation
* `cd`
* `cd -`
* `pwd`
* `dirs -v`
* `pushd .`

```bash
# Select a dir and cd to it
select ITEM in $(dirs -l); do
    cd $ITEM
    break
done
```
