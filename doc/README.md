Yearcoin Core 0.13.2
=====================

Setup
---------------------
[Yearcoin Core](http://yearcoin.org/en/download) is the original Yearcoin client and it builds the backbone of the network. However, it downloads and stores the entire history of Yearcoin transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

Running
---------------------
The following are some helpful notes on how to run Yearcoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/yearcoin-qt` (GUI) or
- `bin/yearcoind` (headless)

### Windows

Unpack the files into a directory, and then run yearcoin-qt.exe.

### OS X

Drag Yearcoin-Core to your applications folder, and then run Yearcoin-Core.

### Need Help?

* See the documentation at the [Yearcoin Wiki](https://yearcoin.info/)
for help and more information.
* Ask for help on [#yearcoin](http://webchat.freenode.net?channels=yearcoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=yearcoin).
* Ask for help on the [YearcoinTalk](https://yearcointalk.io/) forums.

Building
---------------------
The following are developer notes on how to build Yearcoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Yearcoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/bitcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [YearcoinTalk](https://yearcointalk.io/) forums.
* Discuss project-specific development on #yearcoin on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=yearcoin).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
