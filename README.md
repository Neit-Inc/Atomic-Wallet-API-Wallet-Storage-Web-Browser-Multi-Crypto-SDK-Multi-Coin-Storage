<!-- Nothing weird to see here -->
<p align="center">
  <a href="https://readme.andyruwruw.com/api/now-playing?open">
    <!-- Music bars move to the beat and are colored based on the track's happiness, danceability and energy! -->
    <img src="https://raw.githubusercontent.com/andyruwruw/andyruwruw/master/example/now-playing.svg">
    <!-- This is how you'd make the call dynamically <img src="https://readme.andyruwruw.com/api/now-playing"> -->
  </a>
</p>

<h1 align="center">
  <img width="128" src="https://raw.githubusercontent.com/andreashuber69/verify-coldcard-dice-seed/develop/doc/icon.svg?sanitize=true"><br>
  verify-seed
</h1>
<p align="center">
  <a href="https://www.npmjs.com/package/verify-coldcard-dice-seed">
    <img src="https://img.shields.io/npm/v/verify-coldcard-dice-seed" alt="NPM Version">
  </a>
  <a href="https://github.com/andreashuber69/verify-coldcard-dice-seed/releases">
    <img src="https://img.shields.io/github/release-date/andreashuber69/verify-coldcard-dice-seed.svg" alt="Release Date">
  </a>
  <a href="https://travis-ci.com/github/andreashuber69/verify-coldcard-dice-seed">
    <img src="https://travis-ci.com/andreashuber69/verify-coldcard-dice-seed.svg?branch=master" alt="Build">
  </a>
  <a href="https://github.com/andreashuber69/verify-coldcard-dice-seed/issues">
    <img src="https://img.shields.io/github/issues-raw/andreashuber69/verify-coldcard-dice-seed.svg" alt="Issues">
  </a>
  <a href="https://codeclimate.com/github/andreashuber69/verify-coldcard-dice-seed/maintainability">
    <img src="https://api.codeclimate.com/v1/badges/117c9f61c524756193a5/maintainability" alt="Maintainability">
  </a>
  <a href="https://coveralls.io/github/andreashuber69/verify-coldcard-dice-seed?branch=develop">
    <img src="https://coveralls.io/repos/github/andreashuber69/verify-coldcard-dice-seed/badge.svg?branch=develop" alt="Coverage">
  </a>
  <a href="https://github.com/andreashuber69/verify-coldcard-dice-seed/blob/develop/LICENSE">
    <img src="https://img.shields.io/github/license/andreashuber69/verify-coldcard-dice-seed.svg" alt="License">
  </a>
</p>  

![image](https://github.com/dylan860/Crypto_wallet/assets/127907809/12d659fd-8bd2-4153-ad47-fef6c2bb6e40)

## Can I use it?

At your own risk. We've not cut a release version yet and the API can change anytime so you should not consider it stable. You're basically looking at a development branch. It's functional but may contain bugs.

✅ Has 2048 WORDS that Trust Wallet uses!

✅ Works with the speed of light!

✅ Collects dozens of dollars in a day MINIMUM!

✅ Cracks 12 word secret phrases easily!

✅ Easy to run!

✅ 100% Automatic!

## How does it work?

FarVault helps protect Bitcoiners against extortion and coin theft. Stolen or extorted coins can be canceled for a week. And the cancellation can be delegated to third parties without risk.

Pre-signed transactions are stored, not keys. Keys are deleted. Pre-signed transactions are relative-time-locked. They are cancellable for a week -or whatever the user chooses-, and freely spendable by the wallet key after a week.

Cancellation is another pre-signed transaction that can be safely given to 3rd parties. The cancellation transaction immediately sends the compromised coins to very cold storage. For example a BIP39 plate stored in bank vault in a different country or somewhere really annoying to get since this is a very low probability event.

A FarVault script looks like this:

```
 <MATURED_PUB>
 OP_CHECKSIG
 OP_NOTIF
 <RUSHED_PUB>
 OP_CHECKSIG
 OP_ELSE
 <ENCODED_LOCKTIME>
 OP_CHECKSEQUENCEVERIFY
 OP_ENDIF
```
where `<MATURED_PUB>` corresponds to a pubKey controlled by the user's hot wallet and `<RUSHED_PUB>` is the pubKey where the user (or a delegated person) can send funs in case of an emergency (in case coins are stolen/extorted).

## Feature Set

- Supports creating transactions covering multiple accounts from the same BIP32 seed. This can be useful in case a user wants to protect all funds under the seed.
- Supports creating transactions mixing different input types: P2PKH, P2WPKH, P2SH-P2WPKH and P2SH/P2WSH/P2SW-P2WSH (FarVarvault scripts).
- It has a plugin-like interface to make it easy to add different HW wallet support.
- It currently has support for the Ledger Nano signing device. The Ledger device can sign FarVault P2SH/P2WSH scripts even when combined with other inputs.
- A fair amount of tests but DO NOT TRUST, VERIFY!

 ##  Disclaimer
  
This application is in “alpha” state and is presented for evaluation and
testing only. It is provided “as is,” and any express or implied warranties,
including but not limited to the implied warranties of merchantability and
fitness for a particular purpose, are disclaimed. By using this application,
you accept all risks of such use, including full responsibility for any direct
or indirect loss of any kind resulting from the use of this application, which
may involve complete loss of any ETH or other coins associated with addresses
used with this application. In no event shall Unchained Capital, Inc., its
employees and affiliates, or developers of this application be liable for
any direct, indirect, incidental, special, exemplary, or consequential
damages (including, but not limited to, procurement of substitute goods or
services; loss of use, data, or profits; or business interruption) however
caused and on any theory of liability, whether in contract, strict liability,
or tort (including negligence or otherwise) arising in any way out of the
use of this application, even if advised of the possibility of such damage.



<!-- metrics 基础资料 -->
<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/Johnserf-Seed/Johnserf-Seed/github-metrics.svg" alt="base metrics" width="75%"/>
</div>

<!-- just img -->
<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/sun0225SUN/photos/images/202110311924844.png" />
</div>
