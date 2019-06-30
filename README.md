# lambdale.org

The website for LambdAle, a functional programming conference in a pub.

This is a Jekyll site that uses the [Scribble](https://github.com/muan/scribble) theme.

## Running

### Locally
First make sure you have Jekyll and Bundler installed:

```
$ gem install jekyll bundler
```

Then:

1. Clone the repo: `git clone git@github.com:LambdAle/lambdale.github.io.git`

2. Run `bundle install`

3. Run Jekyll: `bundle exec jekyll serve -w`

4. Go to http://localhost:4000

### Using docker

```
export JEKYLL_VERSION=3.8
docker run --rm \
  --volume="$PWD:/srv/jekyll" \
  -p 4000:4000 \
  -it jekyll/jekyll:$JEKYLL_VERSION \
  jekyll serve -w
```

## Deploying a change

1. Make a PR against `master`

2. Somebody merges the PR

3. GitHub automatically deploys it. It should show up at http://lambdale.org within minutes.
