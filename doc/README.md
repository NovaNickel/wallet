NovaNickel
=============

Setup
---------------------
NovaNickel is a NovaNickel client and it builds the backbone of the network. However, it downloads and stores the entire history of NovaNickel transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download NovaNickel, visit [novanickelmore.org](https://novanickel.net).

Running
---------------------
The following are some helpful notes on how to run NovaNickel on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/novanickel-qt` (GUI) or
- `bin/novanickeld` (headless)

### Windows

Unpack the files into a directory, and then run novanickel-qt.exe.

### OS X

Drag NovaNickel-More.app to your applications folder, and then run NovaNickel-More.

### Need Help?

* See the documentation at the [Bitcoin Wiki](https://en.bitcoin.it/wiki/Main_Page)
for help and more information.
* Ask for help on [#novanickel](http://webchat.freenode.net?channels=novanickel) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=novanickel).
* Ask for help in [NovaNickel room](https://gitter.im/NovaNickel_Hub) on Gitter.
* Ask for help in [/r/novanickel/](https://nm.reddit.com/r/novanickel/) on Reddit.
* Ask for help on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [NovaNickel topic](https://bitcointalk.org/index.php?topic=3017838.new#new).

Building
---------------------
The following are developer notes on how to build NovaNickel on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The NovaNickel repo's [root README](/README.md) contains relevant information on the development process and automated testing.

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
* Discuss on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [NovaNickel topic](https://bitcointalk.org/index.php?topic=3017838.new#new).
* Discuss NovaNickel development in [NovaNickel room](https://gitter.im/NovaNickel_Hub) on Gitter.
* Discuss NovaNickel development in [NovaNickel team](https://keybase.io/team/novanickel) on Keybase.

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
