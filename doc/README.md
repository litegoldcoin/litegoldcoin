LiteGoldCoin 1.8.1
====================

* Copyright (c) 2009-2014 Bitcoin Developers
* Copyright (c) 2011-2013 Litecoin Developers
* Copyright (c) 2013-2014 LiteGoldCoin Developers


Setup
---------------------
[LiteGoldCoin Core](http://litegoldcoin.com/en/download) is the original LiteGoldCoin client and it builds the backbone of the network. However, it downloads and stores the entire history of LiteGoldCoin transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once. If you would like the process to go faster you can [download the blockchain directly](bootstrap.md)

Running
---------------------
The following are some helpful notes on how to run LiteGoldCoin on your native platform. 

### Unix

You need the Qt4 run-time libraries to run LiteGoldCoin-Qt. On Debian or Ubuntu:

	sudo apt-get install libqtgui4

Unpack the files into a directory and run:

- bin/32/litegoldcoin-qt (GUI, 32-bit) or bin/32/litegoldcoind (headless, 32-bit)
- bin/64/litegoldcoin-qt (GUI, 64-bit) or bin/64/litegoldcoind (headless, 64-bit)



### Windows

Unpack the files into a directory, and then run litegoldcoin-qt.exe.

### OSX

Drag LiteGoldCoin-Qt to your applications folder, and then run LiteGoldCoin-Qt.

### Need Help?

* See the documentation at the [LiteGoldCoin Wiki](http://dogeco.in/)
for help and more information.
* Ask for help on [#litegoldcoin](http://webchat.freenode.net?channels=litegoldcoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=litegoldcoin).
* Ask for help on the [/r/dogeducation subreddit](http://reddit.com/r/dogeducation).

Building
---------------------
The following are developer notes on how to build LiteGoldCoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OSX Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-msw.md)

Development
---------------------
The LiteGoldCoin repo's [root README](https://github.com/litegoldcoin/litegoldcoin/blob/master/README.md) contains relevant information on the development process and automated testing.

- [Coding Guidelines](coding.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/bitcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)

### Resources
* Discuss on the [/r/litegoldcoindev](http://www.reddit.com/r/litegoldcoindev) subreddit.
* Discuss on [#litegoldcoin-dev](http://webchat.freenode.net/?channels=litegoldcoin-dev) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=litegoldcoin-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)

License
---------------------
Distributed under the [MIT/X11 software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](http://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
