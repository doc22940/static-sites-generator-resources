# Jekyll Help
> Useful links and tips which helped me learn about building static sites with Liquid and Jekyll

**Table of Contents**

- [Docs](#Docs)
    - [Shopify's Liquid docs](#Shopifys-Liquid-docs)
    - [Official Jekyll docs](#Official-Jekyll-docs)
- [Repos](#Repos)
- [Resources](#Resources)


## Docs

- [Jekyll cheatsheet](https://learn.cloudcannon.com/jekyll-cheat-sheet/).
- [Bundle install](https://bundler.io/man/bundle-install.1.html)


### Shopify's Liquid docs

- shopify.github.io
    - [Filters](https://shopify.github.io/liquid/filters/abs/)
    - [Basic introduction](https://shopify.github.io/liquid/basics/introduction/)
- shopify.dev
    - [Data types](https://shopify.dev/docs/liquid/reference/basics/types)
    - [Tags](https://shopify.dev/docs/liquid/reference/tags)
    - [Filters](https://shopify.dev/docs/liquid/reference/filters)


### Official Jekyll docs

- [Home](https://jekyllrb.com)
- [Plugins](https://jekyllrb.com/docs/plugins/)
- [Configuration options](https://jekyllrb.com/docs/configuration/options/)
- [Command-line usage](https://jekyllrb.com/docs/usage/)

- [Data files](https://jekyllrb.com/docs/datafiles/)
- [Navigation](https://jekyllrb.com/tutorials/navigation/)
- [Includes](https://jekyllrb.com/docs/includes/)
- [Layouts](https://jekyllrb.com/docs/layouts/)

- [Convert an HTML site to Jekyll](https://jekyllrb.com/tutorials/convert-site-to-jekyll/)
- [Liquid Filters](https://jekyllrb.com/docs/liquid/filters/)
- [Link tag](https://jekyllrb.com/docs/liquid/tags/#links)

See also the content on the Jekyll site's sidebar around pages, posts, front matter and more.


## Repos

- [Github Pages Ruby Gem](https://github.com/github/pages-gem) - A simple Ruby Gem to bootstrap dependencies for setting up and maintaining a local Jekyll environment in sync with GitHub Pages.
- [Minima theme](https://github.com/jekyll/minima)

To see your installed files of a theme such as `mimima`, run the following:

```bash
$ # View path
$ bundle show minima
<PATH_TO_REPO>/vendor/bundle/ruby/2.3.0/gems/minima-2.5.0

$ # Open on Mac.
$ open $(bundle show minima)

$ # Open on Linux.
$ open-xdg $(bundle show minima)
```

## Resources

- [Alligator.io - Jekyll posts](https://alligator.io/jekyll/)
