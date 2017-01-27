# trumpocalypse-ui
_Showing our slide_

trumpocalypse-ui is a way of displaying data collected in a [trumpocalypse](https://github.com/Sagelt/trumpocalypse) data set.

This repo provides Jekyll template to display a collection of links. On its own it's just a data renderer, but if you have a [Jekyll](https://jekyllrb.com/) site you can use this data along with [a data store](https://github.com/Sagelt/trumpocalypse) to keep your own log.

## Using trumpocalypse on Jekyll with this repo

These steps assume you have an existing Jekyll site. If you don't, [GitHub pages](https://pages.github.com/) is a great way to set one up.

1. Add trumpocalypse as a submodule within your \_data directory
```
git submodule add https://github.com/Sagelt/trumpocalypse.git trumpocalypse
```
2. Add trumpocalypse renderer as a submodule wherever you'd like the page to live. For example, if you add the submodule under /pages, you'd run this command there.
```
git submodule add https://github.com/Sagelt/trumpocalypse-ui.git trumpocalypse
```
3. Update as often as you'd like
```
git submodule update --remote
```

## Using trumpocalypse on Jekyll with your own repo

As above, but replace the repo links being added with your own repos.

## Pull Requests

Please send your pull requests! There's plenty of improvements to be made in the UI.

## FAQ

### WHY?

Some friends and I have a group chat where we share news stories. [garykac](https://github.com/garykac) had the great idea of hosting a page to collect all these things. It resonated with me because I'd heard advice to keep a log of changes to avoid the slow redefinition of 'normal' under Trump. I wanted to make something that could be merged easily so people can share what they find, so I expanded on garykac's idea.

### Did you just reinvent CMS on git with static HTML and YAML?

Yep. 

### Why Jekyll/Git/YAML/Bootstrap instead of X/Y/Z?

I used stuff I like. I was more interested in creating a tool anyone could fork and host themselves than fancy CMS features.
