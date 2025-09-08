[![Deployment](https://github.com/VivaainNg/VivaainNg.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/VivaainNg/VivaainNg.github.io/actions/workflows/pages/pages-build-deployment)


# vivaainng.github.io
My personal blog

Pre-requisite:
- Git (Source control to manage the repo)
- [Jekyll](https://jekyllrb.com/docs/installation/) - to generate our static sites.
- [Ruby](https://www.ruby-lang.org/en/downloads/) - why? Because Jekyll is written in Ruby.
- [Bundler](https://bundler.io/#getting-started) - to manage dependencies for Ruby projects.


Steps to locally run:
1. Fork this repo and git clone it.
2. Then proceed to install the tools needed in pre-requisites above.
3. Once you've installed all them:
```
# To install gems (in my case, with alembic theme) on local
$ bundle install 

# To build and serve the static site on local
$ bundle exec jekyll serve 
```
4. The site should be up and running locally on http://127.0.0.1:4000/


## Outline of repo ##
