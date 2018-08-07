# Virgil Keyknox JavaScript SDK

[![Build Status](https://travis-ci.com/VirgilSecurity/keyknox-javascript.svg?branch=master)](https://travis-ci.com/VirgilSecurity/keyknox-javascript)
[![GitHub license](https://img.shields.io/badge/license-BSD%203--Clause-blue.svg)](https://github.com/VirgilSecurity/virgil/blob/master/LICENSE)

[Introduction](#introduction) | [SDK Features](#sdk-features) | [Installation](#installation) | [Docs](#docs) | [Support](#support)

## Introduction
<a href="https://developer.virgilsecurity.com/docs"><img width="230px" src="https://cdn.virgilsecurity.com/assets/images/github/logos/virgil-logo-red.png" align="left" hspace="10" vspace="6"></a>[Virgil Security](https://virgilsecurity.com) provides an SDK which allows you to communicate with Virgil Keyknox Service.
Virgil Keyknox Service allows users to store their sensitive data (such as Private Key) encrypted (with end-to-end encryption) for using and sharing it between different devices.

## SDK Features
- use [Virgil Crypto library][_virgil_crypto]
- use [Virgil SDK][_virgil_sdk]
- upload encrypted sensitive data to Virgil Keyknox Service
- download the data from Virgil Keyknox Service
- update and synchronize the data

## Installation
You can install this module from npm. Another option is to add it via `script` tag in browser.

### npm
You will need to install `keyknox-sdk`.
```sh
npm install keyknox-sdk
```

You will also need to install `virgil-crypto` and `virgil-sdk` from npm, unless you've already used them.
```sh
npm install virgil-crypto@3.0.0 virgil-sdk@next
```

### In browser via `script` tag
You will need to add `keyknox-sdk` script.
```html
<script src="https://unpkg.com/keyknox-sdk@0.1.0/dist/keyknox-sdk.browser.umd.js"></script>
```

You will also need to add `virgil-crypto` and `virgil-sdk` scripts, unless you've already used them.
```html
<script src="https://unpkg.com/virgil-crypto@3.0.0/dist/virgil-crypto.browser.umd.min.js"></script>
<script src="https://unpkg.com/virgil-sdk@next/dist/virgil-sdk.browser.umd.min.js"></script>
```

Now you can use global variables `Keyknox`, `Virgil` and `VirgilCrypto` as namespace objects, containing all of `keyknox-sdk`, `virgil-sdk` and `virgil-crypto` exports as properties.

## Docs
Virgil Security has a powerful set of APIs, and the documentation below can get you started today.

* [Virgil Security Documentation][_documentation]

## License
This library is released under the [3-clause BSD License](LICENSE).

## Support
Our developer support team is here to help you. Find out more information on our [Help Center](https://help.virgilsecurity.com).

You can find us on [Twitter](https://twitter.com/VirgilSecurity) or send us email support@VirgilSecurity.com.

Also, get extra help from our support team on [Slack](https://virgilsecurity.slack.com/join/shared_invite/enQtMjg4MDE4ODM3ODA4LTc2OWQwOTQ3YjNhNTQ0ZjJiZDc2NjkzYjYxNTI0YzhmNTY2ZDliMGJjYWQ5YmZiOGU5ZWEzNmJiMWZhYWVmYTM).

[_virgil_crypto]: https://github.com/VirgilSecurity/virgil-crypto-javascript
[_virgil_sdk]: https://github.com/VirgilSecurity/virgil-sdk-javascript
[_documentation]: https://developer.virgilsecurity.com
