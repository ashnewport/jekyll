# Base Jekyll site for prototypes with Foundation 6

A starting point with Jekyll and Zurb Foundation 6 for quick prototyping.

## Getting started

Make sure [Jekyll] is installed to use this repo.

Clone the repo and run the following command:
`jekyll serve -I -w --baseurl ''`

Bash will tell you the local server address to preview, e.g. `http://127.0.0.1:4000`

## Viewing on GitHub Pages

Included is a `gh-pages` branch which needs to be updated with changes from development to be viewed on a `github.io` URL.

Note that the GitHub Pages URL will be the username of the account, followed by `github.io`, then `/project-name`. Likely you will be changing the project name from this repo so be sure to update the `baseurl` value in `_config.yml` to match the new project name. Be sure to include the leading `/` in the config file.

If updating with changes from master then do the following:

```
git checkout gh-pages
git rebase master
git push -u origin gh-pages
```

You can now preview on GitHub Pages, e.g. `ashnewport.github.io/jekyll`

## Technology stack

For prototyping the following technology is used to build and host:

* HTML
* CSS
* JavaScript
* [Jekyll]
* [YAML]
* [Liquid Template][liquid]
* [GitHub Pages][gh-pages]

### To do

* Clean up some of the starting files to remove junk
* Add normalize.scss
* Add font awesome
* Update config.yml
* Create a more relevant default page and post
* Keep tech stack updated for ICT


[jekyll]: <http://jekyllrb.com/docs/installation/>
[yaml]: <http://www.yaml.org/>
[liquid]: <http://liquidmarkup.org/>
[gh-pages]: <https://pages.github.com/>