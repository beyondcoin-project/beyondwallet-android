[![Beyondwallet](/images/header-android.png)](https://play.google.com/store/apps/details?id=com.beyondwallet&hl=en_US)
======================
[![Release](https://img.shields.io/github/v/release/beyondcoin-project/beyondwallet-android?style=plastic)](https://img.shields.io/github/v/release/beyondcoin-project/beyondwallet-android) 
[![MIT License](https://img.shields.io/github/license/beyondcoin-project/beyondwallet-android?style=plastic)](https://img.shields.io/github/license/beyondcoin-project/beyondwallet-android?style=plastic)

## Easy and secure
Beyondwallet is the best way to get started with Beyondcoin. Our simple, streamlined design is easy for beginners, yet powerful enough for experienced users. This is a free app produced by the Beyondcoin Project and Beyondcoin's creator Beyondtoshi.
 
<!--## Donations-->
<!--The Litewallet Team is a group of global volunteers & part of the Litecoin Foundation that work hard to promote the use of Litecoin. Litewallet takes alot of time and resources to improve and test features but we need your help.  Please consider donating to one of our addresses:
|                                   Hardware Campaign                                   	|                              General Beyondcoin P                              	|
|:-------------------------------------------------------------------------------------:	|:-------------------------------------------------------------------------------------:	|
| [QR Code](https://blockchair.com/litecoin/address/MJ4W7NZya4SzE7R6xpEVdamGCimaQYPiWu) 	| [QR Code](https://blockchair.com/litecoin/address/MVZj7gBRwcVpa9AAWdJm8A3HqTst112eJe) 	|
-->
## Completely decentralized

Unlike other iOS Beyondcoin wallets, **Beyondwallet** is a standalone Beyondcoin client. It connects directly to the Beyondcoin network using [SPV](https://en.bitcoin.it/wiki/Thin_Client_Security#Header-Only_Clients) mode, and doesn't rely on servers that can be hacked or disabled. Even if Beyondwallet is removed from the App Store, the app will continue to function, allowing users to access their valuable Beyondcoin at any time.

## Cutting-edge security

**Beyondwallet** utilizes AES hardware encryption, app sandboxing, and the latest iOS security features to protect users from malware, browser security holes, and even physical theft. Private keys are stored only in the secure enclave of the user's phone, inaccessible to anyone other than the user.

## Designed with new users in mind

Simplicity and ease-of-use is **Beyondwallet**'s core design principle. A simple recovery phrase (which we call a paper key) is all that is needed to restore the user's wallet if they ever lose or replace their device. **Beyondwallet** is [deterministic](https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki), which means the user's balance and transaction history can be recovered just from the paper key.

## Features:

- ["simplified payment verification"](https://github.com/bitcoin/bips/blob/master/bip-0037.mediawiki) for fast mobile performance
- no server to get hacked or go down
- single backup phrase that works forever
- private keys never leave your device
- import [password protected](https://github.com/bitcoin/bips/blob/master/bip-0038.mediawiki) paper wallets
- ["payment protocol"](https://github.com/bitcoin/bips/blob/master/bip-0070.mediawiki) payee identity certification


## Localization

**Beyondwallet** is available in the following languages:

- Chinese (Simplified and traditional)
- Danish
- Dutch
- English
- French
- German
- Indonesian
- Italian
- Japanese
- Korean
- Portuguese
- Russian
- Spanish
- Swedish

---
## Beyondwallet Development:
[![GitHub issues](https://img.shields.io/github/issues/beyondcoin-project/beyondwallet-android?style=plastic)](https://github.com/beyondcoin-project/beyondwallet-android/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/beyondcoin-project/beyondwallet-android?color=00ff00&style=plastic)](https://github.com/beyondcoin-project/beyondwallet-android/pulls)

### Building & Developing Beyondwallet for Android: 

1. Download and install Java 7 or up
2. Download and install the latest Android studio
3. Download NDK r15c from the [NDK Archives](https://developer.android.com/ndk/downloads/older_releases.html)
4. Clone this repo & init submodules
```bash
$ git clone https://github.com/beyondcoin-project/beyondwallet-android
$ git submodule init
$ git submodule update
```
5. Open the project with Android Studio, navigate to `File > Project Structure > SDK Location`
6. Change `Android NDK Location` with the path to NDK r15c that you downloaded earlier
7. Go to SDK Manager and download all the SDK Platforms and SDK Tools
9. Build -> Rebuild Project

### Beyondwallet Team:
* [Development Code of Conduct](https://github.com/beyondcoin-project/beyondwallet/blob/master/DEVELOPMENT.md)
---
**Beyondcoin** source code is available at https://github.com/beyondcoin-project/beyondcoin

