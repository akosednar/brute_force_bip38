brute-force BIP38
=================

A brute-force decoder of BIP38 encoded private keys for the CLI.

## Installation

### Install dependencies

Download and install the latest version from:

* [Node.js LTS](https://nodejs.org/en/download/) (installs 'node' and 'npm')

### Clone repository

Clone the *brute-force BIP38* repository to a nice place on your machine via:

    git clone git@github.com:countzero/brute_force_bip38.git

### Build

Fire up your console at the project location and execute:

    npm install
    npm link

## Configuration

1. Edit the [config.json](./config.json) and paste the `publicAddress` and `encryptedPrivateKey` values of your BIP38 key.
2. Edit the [secrets.js](./secrets.js) so that it will return an array of all secrets you want to test on your BIP38 key.

## Start

Fire up your console at the project location and execute:

    brutebip38

License
-------
*brute-force BIP38* is released under the [MIT license](https://opensource.org/licenses/MIT).
