# github-pages-template
Template project for using Jekyll on Github Pages with custom Jekyll plugins.
This allows the use of the `jekyll-assets` [gem](http://jekyll-assets.github.io/jekyll-assets/), which provides a nice assets
pipeline like in Rails.

## Installation
Just run

```bash
bundle install
```
and you're set.

## Workflow
Instead of using `master`, make all your commits in the `source` branch. Then,
when you're ready to publish to Github Pages, run the `sites:publish` Rake task.
This will take your built `_sites` directory in `source` and place it at the
root of `master` on Github, so that Pages can serve it properly with any custom
Jekyll plugins you decide to use.

## Troubleshooting
Honestly I made this in like an hour so you should check here for more help:

https://help.github.com/articles/using-jekyll-with-pages/

http://jekyllrb.com/

http://jekyll-assets.github.io/jekyll-assets/
