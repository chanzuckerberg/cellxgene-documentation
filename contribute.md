---
description: make sure to chat with arathi on the location of this
---

# Contribute

## Code of conduct

We warmly welcome contributions from the community!

To ensure a welcoming experience for our entire community, this project adheres to the Contributor Covenant [code of conduct](https://github.com/chanzuckerberg/.github/tree/master/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [opensource@chanzuckerberg.com](mailto:opensource@chanzuckerberg.com).

If you have any questions about any of this stuff, just ask! :\)

## Contributing ideas and issues

We'd love to hear from you! Please submit any bug reports and feature requests through [Github issues](https://github.com/chanzuckerberg/cellxgene/issues).

## Direct contributions

### Getting started

If you are interested in working on `cellxgene` development, you'll need to use git to make a copy of the [project repository](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/working-with-forks) and share your changes.

We have several "rules" \(strong suggestions really\) for contributions:

1. If your contribution is complex, adds new features, new UI design or otherwise warrants discussion, we highly recommend that you submit a github issue, and engage other contributors in a discussion about the details of your proposed PR. This will save you time in the long run, as many details and decisions can be hashed out ahead-of-time.
2. Please submit any direct contributions by [forking the repository](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/working-with-forks), creating a feature branch, and [submitting a Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

First, you'll need the following installed on your machine

* python 3.6+
* node and npm \(we recommend using [nvm](https://github.com/creationix/nvm) if this is your first time with node\)

Next you can build the client web assets and install all requirements by following the directions in our [dev docs](https://github.com/chanzuckerberg/cellxgene/blob/main/dev_docs/developer_guidelines.md#server-dev) on github.

You can start the app while developing either by calling `cellxgene` or by calling `python -m server`. We recommend using the `--debug` flag to see more output, which you can include when reporting bugs.

If you have any questions about developing or contributing, come hang out with us by posting an issue in our [github](https://github.com/chanzuckerberg/cellxgene).

### Contributing code

This project has made a few key design choices:

* The front-end is built with [`regl`](https://github.com/regl-project/regl) \(a webgl library\), [`react`](https://reactjs.org/), [`redux`](https://redux.js.org/), [`d3`](https://github.com/d3/d3), and [`blueprint`](https://blueprintjs.com/docs/#core) to handle rendering large numbers of cells with lots of complex interactivity
* The app is designed with a client-server model that can support a range of existing analysis packages for Python-based backend computational tasks \(currently built for [scanpy](https://github.com/theislab/scanpy)\)
* The client uses fast cross-filtering to handle selections and comparisons across subsets of data

Depending on your background and interests, you might want to contribute to the frontend, or backend, or both!

Please submit any direct contributions via a Pull Request. It'd be great for PRs to include test cases and documentation updates where relevant, though we know the core test suite is itself still a work in progress.

### Contributing documentation

This documentation is written using [gitbook](https://www.gitbook.com/). Feel free to [fork our docs repo](https://github.com/maximilianLombardo/cellxgene-docs/tree/master) and submit a pull request if you would like to contribute documentation or suggest edits to our documentation.

