[![tests][tests]][tests-url]
[![chat][chat]][chat-url]

<div align="center">
  <img width="200" height="200"
    src="https://cdn.worldvectorlogo.com/logos/circleci.svg">
  <a href="https://github.com/easymetrics">
    <img width="200" height="200" vspace="" hspace="25"
      src="https://cdn.worldvectorlogo.com/logos/webpack-icon.svg">
  </a>
  <h1>CircleCI 2.0 base build container</h1>
  <p>Docker Repository for the WebpackContrib Debian Jessie based CircleCI build & deployment Image.<p>
</div>


<h2 align="center">Usage</h2>

```bash
# config.yml
    docker:
      - image: webpackcontrib/circleci-node-base
```

<h2 align="center">Container Includes</h2>

- CircleCI specific dependencies & runtime user configuration.
- Docker tooling ( Engine, Compose, Dockerize ).
- Node Version Manager ( Version defaults to node:latest )

> This container does not have a headless browser configuration

[tests]: http://img.shields.io/travis/webpack-contrib/istanbul-instrumenter-loader.svg
[tests-url]: https://travis-ci.org/webpack-contrib/istanbul-instrumenter-loader

[chat]: https://badges.gitter.im/webpack/webpack.svg
[chat-url]: https://gitter.im/webpack/webpack