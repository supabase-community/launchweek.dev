# launchweek.dev

This repository tracks past and upcoming launch weeks across the dev tools space. 

**What's a launch week?**

It's a week of announcing new features.

**The objective?**

- **For developers**, to save the date and discover awesome developer-first products;
- **For dev-first founders and marketers**, to help plan and promote their launch weeks and find inspiration.

This repo is maintained by [Anna](https://github.com/maban), [Ellen](https://x.com/ellenchisa), [Paul](https://x.com/kiwicopple) and [Flo](https://x.com/fmerian).

```diff
+ 👀 Watch this to get notifications about new launch weeks
```

## About

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

- [Installation](#installation)
- [Local Development](#local-development)
- [Build](#build)
- [Deployment](#deployment)

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you're using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
