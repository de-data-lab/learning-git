# learning-git

A repository for the Git/GitHub learning workshop

## How to run the site locally

(See also the [GitHub Doc](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll))

1. Install [Jekyll](https://jekyllrb.com/docs/installation/)
2. Install [Bundler](https://bundler.io/)
3. Run `bundle install`
4. Run `bundle exec jekyll serve`
5. Go to http://localhost:4000/learning-git/

## Repository-Specific Variables

The domain, the base URL, and the repository name are hard-coded into the `_config.yml`.
If you'd like to reuse the code, you will need to update the following variables:

1. `domain` - Domain name
2. `url` - Domain name with "https://"
3. `baseurl` - Name of the repository
