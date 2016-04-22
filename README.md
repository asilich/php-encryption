php-encryption
===============

[![Build Status](https://travis-ci.org/defuse/php-encryption.svg?branch=master)](https://travis-ci.org/defuse/php-encryption)

This is a library for encrypting data with a key or password in PHP. **It
requires PHP 5.4 or newer.** The current version is v2.0.0, which is expected to
remain stable and supported by its authors with security and bugfixes until Jan
01, 2019.

The library is a joint effort between [Taylor Hornby](https://defuse.ca/) and
[Scott Arciszewski](https://paragonie.com/blog/author/scott-arcizewski) as well
as numerous open-source contributotrs.

What separates this library from other PHP encryption libraries is, firstly,
that it is secure. The authors used to encounter insecure PHP encryption code on
a daily basis, so they created this library to bring more security to the
ecosystem. Secondly, this library is "difficult to misuse." Like
[libsodium](https://github.com/jedisct1/libsodium), its API is designed to be
easy to use in a secure way and hard to use in an insecure way.

Dependencies
------------

This library requres no special dependencies except for a version of PHP 5.4 or
newer with the OpenSSL extensions enabled (the default). It comes bundled with
[random\_compat](https://github.com/paragonie/random_compat) so that your users
will not need to follow any special installation steps.

Getting Started
----------------

Start with the [**Tutorial**](docs/Tutorial.md). You can find instructions for
obtaining this library's code securely in the [Installing and
Verifying](docs/InstallingAndVerifying.md) documentation.

After you've read the tutorial and got the code, refer to the formal
documentation for each of the classes this library provides:

- [Crypto](docs/classes/Crypto.md)
- [File](docs/classes/File.md)
- [Key](docs/classes/Key.md)
- [KeyProtectedByPassword](docs/classes/KeyProtectedByPassword.md)

If you encounter difficulties, see the [FAQ](docs/FAQ.md) answers. The fixes to
the most commonly-reported problems are explained there.

If you're a cryptographer and want to understand the nitty-gritty details of how
this library works, look at the [Cryptography Details](docs/CryptoDetails.md)
documentation.

If you're interested in contributing to this library, see the [Internal
Developer Documentation](docs/InternalDeveloperDocs.md).

Examples
---------

If the documentation is not enough for you to understand how to use this
library, then you can look at an example project that uses this library:

- [encutil](https://github.com/defuse/encutil)

Security Audit Status
---------------------

This code has not been subjected to a formal, paid, security audit. However, it
has received lots of review from members of the PHP security community. In all
likelihood, you are safer using this library than almost any other encryption
library for PHP.

If you use this library as a part of your business and would like to help fund
a formal audit, please [contact Taylor Hornby](https://defuse.ca/contact.htm).

Public Keys
------------

TODO: put links (and fingerprints) for the developers' public keys here.
