# ESA ESA Stack website
The document website is hosted at https://www.esastack.io.

We use [Hugo](https://gohugo.io/) with the [google/docsy](https://github.com/google/docsy)
theme for styling and site structure, and [Github Actions](https://docs.github.com/en/actions) to manage the deployment of the site.

## Local development

This section will show you how to develop the website locally, by running a local Hugo server.

### Install Hugo

To install Hugo, follow the [instructions for your system type](https://gohugo.io/getting-started/installing/).

### Install Node Packages

Follow the [Docsy getting started](https://www.docsy.dev/docs/getting-started/#as-an-npm-module) and [Docsy InstallPostCss](https://www.docsy.dev/docs/getting-started/#install-postcss) to install node packages. You may need to install NodeJs if there's no NodeJs in you local environment.

### Run Hogo Server

1. Switch to the site root

```text
cd site
```

2. Get local copies of the project submodules so you can build and run your site locally:

```text
git submodule update --init --recursive
```
3. Build your site:

```text
hugo server
```
Preview your site in your browser at: http://localhost:1313/. You can use `Ctrl + c` to stop the Hugo server whenever you like.