# SEED Lander

### Local Usage

To use this repo locally, start by running.

``` bash
$ bundle install
```

And then start the dev server.

``` bash
$ bundle exec jekyll serve
```

You can now view the page at http://localhost:4000

To run it on a different port run:

``` bash
$ bundle exec jekyll serve --port 4001
```

You can also turn on live reloading and incremental builds while editing.

``` bash
$ bundle exec jekyll serve --incremental --livereload
```

### Deploy

To deploy `git push` to `master` branch.

Deploy status can be viewed on the Netlify dashboard.

https://app.netlify.com/sites/seed

To use `jekyll.environment` in template, set `JEKYLL_ENV` to `production` as environment varialbe in the Netlify dashboard.

### Older Versions

- [Version 1](https://version1--seed.netlify.com/)
- [Version 2](https://version2--seed.netlify.com/)
- [Version 2.1](https://version2-1--seed.netlify.com/)
