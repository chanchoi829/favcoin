Favcoin Core
=============

Setup
---------------------
Favcoin Core is the original Favcoin client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Favcoin transactions (which is currently more than 7 GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Favcoin Core, visit [favcoin.org](https://favcoin.org).

Running
---------------------
The following are some helpful notes on how to run Favcoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/favcoin-qt` (GUI) or
- `bin/favcoind` (headless)

### Windows

Unpack the files into a directory, and then run favcoin-qt.exe.

### OS X

Drag Favcoin-Core to your applications folder, and then run Favcoin-Core.

### Need Help?

* See the documentation at the [Favcoin Wiki](https://favcoin.info/)
for help and more information.
* Ask for help on [#favcoin](http://webchat.freenode.net?channels=favcoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=favcoin).
* Ask for help on the [FavcoinTalk](https://favcointalk.io/) forums.

Building
---------------------
The following are developer notes on how to build Favcoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Favcoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/favcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [FavcoinTalk](https://favcointalk.io/) forums.
* Discuss general Favcoin development on #favcoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=favcoin-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
