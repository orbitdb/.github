OrbitDB is a serverless, distributed, peer-to-peer database. OrbitDB uses [IPFS](https://ipfs.tech/) as its data storage and [Libp2p Pubsub](https://docs.libp2p.io/concepts/pubsub/overview/) to automatically sync databases with peers. It's an eventually consistent database that uses [Merkle-CRDTs](https://arxiv.org/abs/2004.00107) for conflict-free database writes and merges making OrbitDB an excellent choice for p2p and decentralized apps, blockchain applications and [local-first](https://www.inkandswitch.com/local-first/) web applications.

[![](https://img.shields.io/badge/project-orbit-red.svg?style=flat-square)](https://github.com/orbitdb/orbitdb)
[![Matrix](https://img.shields.io/matrix/orbit-db:matrix.org?label=chat%20on%20matrix)](https://app.element.io/#/room/#orbit-db:matrix.org)

## Funding

OrbitDB is currently funded by our community. If you would like to contribute, you can do so via [OpenCollective](https://opencollective.com/orbitdb) or via our cryptocurrency wallets. Please visit [our funding page](https://github.com/orbitdb/funding) to find out more.

## Installation

The quickest way to get started with OrbitDB is to install the core module:

```js
npm i @orbitdb/core
```

## Repositories and Architecture

The [@orbitdb](https://github.com/orbitdb) organization on GitHub contains many different repositories. For the most part, these are either code which relates to OrbitDB, or are various non-code repositories for documentation and the like.

### Code-free repositories

**[Awesome OrbitDB](https://github.com/orbitdb/awesome-orbitdb)**, which is an attempt to list everything that is using OrbitDB, or could help people. Basically, what has been built?

### OrbitDB

**[OrbitDB Core](https://github.com/orbitdb/orbitdb)** - The main repo for OrbitDB.

There are also 3rd party modules which are officially developed by OrbitDB. It should be noted that **all** of these are JavaScript modules on npm.

**[Ethereum Identity Provider](https://github.com/orbitdb/orbitdb-identity-provider-ethereum)** - An Ethereum-based identity provider for OrbitDB.

**[DID Identity Provider](https://github.com/orbitdb/orbitdb-identity-provider-did)** - A Decentralized IDentitifer identity provider for OrbitDB.

### Implementations

A Go implementation is developed and maintained by [the Berty project](https://github.com/berty) at [berty/go-orbit-db](https://github.com/berty/go-orbit-db).

The best place to find out what is available is likely by asking in the [Matrix](https://app.element.io/#/room/#orbit-db:matrix.org). If you know of any other repos that ought to be included in this section, point them out to us!

### Press

Materials for press (logos, formats, guidelines, etc) are available **[here](https://github.com/orbitdb/logo)**. For interviews etc, [reach out to us in an email](mailto:info@orbitdb.org).

### Other repositories?

There are other repositories that aren't in the organization around the web which are important - for instance, of course, [ipfs](https://github.com/ipfs/ipfs). For now, these are the main ones in the @orbitdb organization.

If there is something missing from this list, please let us know! Either open a PR or an issue, and we'll add it. Thank you.

## Registries

We maintain OrbitDB accounts on these registries:
- [npm @orbitdb](https://www.npmjs.com/org/orbitdb)
- [DockerHub @orbitdb](https://hub.docker.com/u/orbitdb)

## Contribute

Please contribute! [Dive into the issues](https://github.com/orbitdb/orbitdb/issues)!

Check out our [contributing document](/CONTRIBUTING.md) for more information on how we work, and about contributing in general. Please be aware that all interactions related to OrbitDB are subject to the OrbitDB [Code of Conduct](CODE_OF_CONDUCT.md).

Small note: If editing the README, please conform to the [standard-readme](https://github.com/RichardLitt/standard-readme) specification.

If you've got any questions, feel free to join us on [Matrix](https://app.element.io/#/room/#orbit-db:matrix.org) or [email us](mailto:info@orbitdb.org). If you experience bugs or wish to contribute an improvement or a new feature, you can open an issue or a pull request.

## License

This repository is only for documents. All of these are licensed under the [CC-BY-SA 3.0](LICENSE) license © 2016-2024 Protocol Labs Inc., Haja Networks Oy. Any code is under a [MIT](LICENSE) © 2016-2024 Protocol Labs Inc., Haja Networks Oy.
