# lambdale.org

The website for LambdAle, a functional programming conference in a pub.

This is a Jekyll site that uses the [Scribble](https://github.com/muan/scribble) theme.

## Running locally

First make sure you have Jekyll and Bundler installed:

```
$ gem install jekyll bundler
```

Then:

1. Clone the repo: `git clone git@github.com:LambdAle/lambdale.github.io.git`

2. Run `bundle install`

3. Run Jekyll: `bundle exec jekyll serve -w`

4. Go to http://localhost:4000

## Deploying a change

1. Make a PR against `master`

2. Somebody merges the PR

3. GitHub automatically deploys it. It should show up at http://lambdale.org within minutes.
