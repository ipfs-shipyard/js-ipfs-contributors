# js-ipfs-contributors

> Script to generate a list of the contributors to js-IPFS since the last release

![Screenshot](https://raw.githubusercontent.com/ipfs-shipyard/js-ipfs-contributors/master/screenshot.png)

## Install

Install dependences:

* [Node.js](https://nodejs.org/en/)

Then:

```sh
npm install -g js-ipfs-contributors
```

Or, install from source:

```sh
# Clone the repo
git clone https://github.com/ipfs-shipyard/js-ipfs-contributors.git
cd js-ipfs-contributors

# Install project dependencies
npm install
```

## Usage

Simply run the tool by typing the following at the command line:

```sh
js-ipfs-contributors
```

Or, if you've installed from source:

```sh
npm start
```

Then follow the prompts. You will need a [Github personal access token](https://github.com/settings/tokens/) with the following scopes:
* read_org
* user_email

Note: It may take a long time! Please be patient!

## License

The js-ipfs Project is dual-licensed under Apache 2.0 and MIT terms:

- Apache License, Version 2.0, ([LICENSE-APACHE](https://github.com/ipfs/go-ipfs/blob/master/LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
- MIT license ([LICENSE-MIT](https://github.com/ipfs/go-ipfs/blob/master/LICENSE-MIT) or http://opensource.org/licenses/MIT)

## Thanks

Thanks to @alanshaw, author of [filecoin-contributors](https://github.com/filecoin-project/filecoin-contributors) (which itself was inspired by https://gist.github.com/alanshaw/5a2d9465c5a05b201d949551bdb1fcc3, also by @alanshaw) of which this module is a blatant ripoff.  I mean an homage.  A pale imitation, if you will.
