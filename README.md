# Getting Started 

<div align="center">
<a href="https://metacall.io" target="_blank"><img src="assets/logo.svg" alt="METACALL" style="max-width:100%; margin: 0 auto;" width="80" height="80"></a>
</div>
<div id="badges" align="center">
  <a href="https://t.me/joinchat/BMSVbBatp0Vi4s5l4VgUgg" alt="Discord">
    <img src="https://img.shields.io/static/v1?label=metacall&message=join&color=blue&logo=telegram&style=flat" /></a>

  <a href="https://discord.gg/upwP4mwJWa" alt="Discord">
    <img src="https://img.shields.io/discord/781987805974757426?label=discord&style=flat" /></a>

  <a href="https://matrix.to/#/#metacall:matrix.org" alt="Matrix">
    <img src="https://img.shields.io/matrix/metacall:matrix.org?label=matrix&style=flat" /></a>

  <a href="https://twitter.com/metacallio" alt="Twitter">
    <img src="https://img.shields.io/twitter/follow/metacallio?label=MetaCall" /></a>
</div>

MetaCall's Getting Started serves as the technical guide with the intent of helping folks get up and running with contributing to MetaCall Open-Source as a Community Handbook. For the benefits of the open-source community, this guide serves as the central repository for how we would like to onboard new contributors looking to contribute to our projects. We value openness and transparency. This guide is open to the world and we welcome feedback. While not going too much into depth about the various projects at MetaCall, it covers the following topics:

- Introduction
- Getting Started
- Git & GitHub Workflow
- Contributing to MetaCall

If you are interested in helping with this guide, please use Issues to submit new ideas for improvements. Please make pull requests to fix typos or other issues with the guide.

## Contributing

Contributions are always welcome!

To get started with contributing we would require you to locally install this project on your machine. We are using [Docsify](https://docsify.js.org/) to serve the needs of publishing this guide over the Web. Docsify makes it easy to load and parse Markdown files along with an easy deployment over our [GitHub Pages](https://metacall.github.io/get-started).

To get started we would require you to install [NodeJS](https://nodejs.org/) and [NPM](https://www.npmjs.com/) if you have not already done so. If you have installed NodeJS and NPM, run the following command on the terminal to get started: 

```sh
$ npm i docsify-cli -g
```

It will install the `docsify-cli` on your local machine. Next, clone the repository on your 
local machine: 

```sh
$ git clone https://github.com/metacall/get-started.git
``` 

Once the cloning is complete, you can `cd` into the repository and launch the local
preview by passing the following command: 

```sh
$ docsify serve docs 
``` 

You can now view the local preview on Port 3000 of your preferred browser. To submit patches, which can include typo fixes or refactor, please create a new branch and edit the markdown files, present in the `docs/` directly. 

If you would like to add new guides and documentation, create a new issue. Once assigned, create a new bullet point on the `_sidebar.md` and add a new file where you can document the feature you would like to have. If you are not already familiar with Markdown documentation, please use the [GitHub Guide](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax) for easy reference. 

Follow our standard [Git & GitHub Workflow](https://metacall.github.io/get-started/#/Git-GitHub-Workflow) to make  Issues and send Pull Requests.

  