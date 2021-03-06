Template for making new [bl.ocks](https://bl.ocks.org/). `d3_.js` contains a custom of build of d3 with [jetpack](https://github.com/gka/d3-jetpack) and [underscore](http://underscorejs.org/).

Make a new directory and copy this code with [degit](https://github.com/Rich-Harris/degit): 

```
mkdir my-example-name && cd $_
degit 1wheel/d3-init
```

# workflow
[Let's Make a Block](https://bost.ocks.org/mike/block/) is a great introduction. I use a couple of additional tools: 

```
# install CLI helpers
npm install -g degit hot-server gistsnap gistup git-go gistclone

# pick a project name and make a directory
mkdir my-example-name && cd my-example-name

# grab starter files
degit 1wheel/d3-init

# start a local server
hot-server

# write some code...

# take a screen shot
gistsnap

# publish
gistup -m my-example-name

# update
git-go this is a commit message

# download
gistclone https://bl.ocks.org/1wheel/4b9d34d74bd64a63d34028f160a71d7b
```

- https://github.com/Rich-Harris/degit
- https://github.com/1wheel/hot-server
- https://github.com/mbostock/gistup
- https://github.com/gka/git-go
- https://github.com/1wheel/gistclone

Make sure you've upgraded node >= 8 - `npm install -g n && n latest` will do it for you.  
