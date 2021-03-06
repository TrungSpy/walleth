[![on Google Play](https://ligi.de/img/play_badge.png)](https://play.google.com/store/apps/details?id=org.walleth)
[![on FDroid](https://ligi.de/img/fdroid_badge.png)](https://f-droid.org/repository/browse/?fdid=org.walleth)
![](https://github.com/ligi/walleth/blob/master/assets/1024x500.png)

WALLΞTH
=======

Native Android Ethereum wallet.

Features
========

 - Networks main(1), ropsten(3), rinkeby(4)
 - Tokens(ERC-20)
 - ERC-67 URLS
 - ERC-55 Checksums 
 - TREZOR Support
 - watch only accounts 
 - contains go-ethereum light client

find more information on https://walleth.org

References
==========

* [ERC67](https://github.com/ethereum/EIPs/issues/67)
* [ERC20](https://github.com/ethereum/EIPs/issues/20)
* [Import Geth - a Devcon2 talk](https://ethereum.karalabe.com/talks/2016-devcon.html#1)
* [go Mobile:-Account-management](https://github.com/ethereum/go-ethereum/wiki/Mobile:-Account-management)
* [Ethereum visual reference](https://www.ethereum.org/images/logos/Ethereum_Visual_Identity_1.0.0.pdf)

License
=======

GPL

Build Walleth
=============
The app has three flavor dimensions: geth, store, firebase 
The simplest way to build for development is 
```
./gradlew assembleWithGethNoFirebaseForFDroidDebug
```
If you are using Android Studio do not upgrade to Android plugin 3.+ but keep using the following dependency for 2.3.3 due to issues for android tests mentionend in [#88](https://github.com/walleth/walleth/pull/88)
```
classpath 'com.android.tools.build:gradle:2.3.3'
```
