# Pinned: Critical bugs only!
Since we are working on the next-gen version of the wallet, we won't be reviewing pull requests with new features and bugs (only critical bugs will be reviewed and merged). Our intention is deploying the first beta of the v2 desktop wallet in a few weeks time so we need to be focused on it exclusively.

Please do not submit Pull-Requests (PRs) unless they solve an urgent problem.

## Pinned: Help us with translations
Collaborate with other translators on our OneSky project and help us get wallet translated in other languages  http://osjc1wl.oneskyapp.com/collaboration/project?id=95031

Please do not submit Pull-Requests (PRs) for translations, but use the link above!

## Installing via Package Managers

#### AUR
For distros derived from Arch Linux the package is available in AUR, just run:

```
yaourt -Sy CMT-desktop
```

#### Homebrew
For Mac users the package is available in [Homebrew](https://brew.sh/):

```
brew update
brew cask install CMTclient
```

## Features
* Available on ***Windows***, ***Linux*** (Ubuntu/Debian) and ***MacOSX*** (signed).
* No need to download CMT blockchain, just sync to the network: launch and use within seconds.
* View any account from its address (transactions, delegate status and votes).
* Label any account and add your own contacts.
* Hardware wallet support : Ledger Nano S.
* Real-time currency value (updated every 5 min) in USD, EUR, BTC, HKD, JPY, CNY, AUD, GBP, Rubble, ...
* Autoconnect to a healthy CMT network peer. If the peer is not good anymore, it will automatically find a new one.
* Send CMT from / to any account.
* Easily switch to a different network, or private chains.
* Customized backgrounds and themes for better user experience.
* Choose between dCMT or light mode.
* Isolated processes on Windows and MacOSX to prevent from data sniffing or injection.
* Translations (thanks to the CMT community) - help out http://osjc1wl.oneskyapp.com/collaboration/project?id=95031
* Organise your accounts with virtual folders (for instance savings, personnal etc...) so you don't pay any transfer fee (stored locally).
* Change your delegate vote.
* When new version is available, message is shown in the right upper part.
* Easy to update - download latest version, start installation program and it will automatically remove previous version and install new one.
* Second signature supported.
* (soon) Deposit or withdraw CMT using altcoins or USD (via exchange) - no registration needed.
* (soon) Multisignature accounts.
* **SAVE YOUR PASSPHRASE(S) - if you lose it, you lose access to that particular CMT address(es). There is no forgot my password option with blockchains and no one can help you retrieve it!**

## Build

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. Optionally switch to node 8.11.2, because this is currently developed with this version:
```
nvm install 8.11.2
nvm use
```

Install from source:
```bash
# Clone this repository
git clone https://github.com/CMTEcosystem/CMT-desktop
# Go into the repository
cd CMT-desktop
# Install dependencies
npm install
```

* In some cases, [node-hid](https://github.com/node-hid/node-hid) doesn't provide pre-built binaries, so is necessary to install the [node-hid dependencies](https://github.com/node-hid/node-hid#compiling-from-source) to build them from source before running `npm install`.

Then start:
```bash
npm start
```

### Requirements to build from OS X

```
brew tap Homebrew/bundle
brew bundle
```

## Authors
- Lorenzo Caruso <lorenzo.caruso@outlook.com>

## License

CMT Desktop is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
