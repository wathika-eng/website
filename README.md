# Gin website

[![Run Deploy](https://github.com/gin-gonic/website/actions/workflows/node.yml/badge.svg)](https://github.com/gin-gonic/website/actions/workflows/node.yml)

Welcome! This repository houses all the assets required to build the Gin website and documentation. We're pleased that you want to contribute! The website is hosted at https://gin-gonic.com.

We use [Hugo](https://gohugo.io/) to format and generate our website, the [Docsy](https://github.com/google/docsy) theme for styling and site structure. Thanks!.

**Note:** We only support hugo [v0.75.1 version](https://github.com/gohugoio/hugo/releases/tag/v0.75.1).
See how to install Hugo v0.75.1 [here](static/hugo_install.md).

## Contribution

- Fork the repository

You can click the Fork button in the upper-right area of the screen to create a copy of this repository in your GitHub account. This copy is called as fork.

> You need to use the below command to clone code for docsy theme.

```sh
git clone --recurse-submodules --depth 1 https://github.com/google/docsy.git themes/docsy
```

- Create one pull request

Make any changes you want in your fork, and when you are ready to send those changes to us, go to your fork and create a new pull request to let us know about it.

- Merge the pull request

Once your pull request is created, a Gin reviewer will take responsibility for providing clear, actionable feedback, re-improve and merge.

## Running

See the [official Hugo documentation](https://gohugo.io/getting-started/installing/) for Hugo installation instructions.

To run the site locally when you have Hugo installed:

```sh
# If you use the `hugo` command, first run `npm install` to install dependencies
$ npm install
$ hugo
# Alternatively, you can use `hugo server`, which doesn't require `npm install`
$ hugo server
```

This will start the local Hugo server on port 1313. Open up your browser to http://localhost:1313 to view the site. As you make changes to the source files, Hugo updates the site and forces a browser refresh.

## Thanks

Gin thrives on community participation, and we really appreciate your contributions to our site and our documentation!
