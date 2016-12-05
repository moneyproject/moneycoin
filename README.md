![MoneyCash Logo](https://i.imgur.com/ovemJA3.png)

[![Slack](https://slack.moneycoin.pw/badge.svg)](https://slack.moneycoin.pw/)
[![Gitter](https://badges.gitter.im/moneyproject/money.svg)](https://gitter.im/moneyproject/money?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=body_badge) [![Build Status](https://travis-ci.org/moneyproject/money.svg?branch=master)](https://travis-ci.org/moneyproject/money) [![Code Climate](https://codeclimate.com/github/moneyproject/money/badges/gpa.svg)](https://codeclimate.com/github/moneyproject/money) [![Test Coverage](https://codeclimate.com/github/moneyproject/money/badges/coverage.svg)](https://codeclimate.com/github/moneyproject/money/coverage) 

Introduction
===========================

The Money Project  is a decentralized peer-to-peer platform, created under an open source license, featuring a built-in cryptocurrency, end-to-end encrypted messaging and decentralized marketplace. The decentralized network aims to provide anonymity and privacy for everyone through a simple user-friendly interface by taking care of all the advanced cryptography in the background. 

* [Website](https://moneycoin.pw/)
* [Blog](https://blog.moneycoin.pw/)
* [Documentation](https://doc.moneycoin.pw/)
* [Forum](https://talk.moneycoin.pw/)

"They who can give up essential liberty to obtain a little temporary safety deserve neither liberty nor safety." 

Releases
===========================
[Click on this link to go to the latest release - 1.5.0.3](https://github.com/moneyproject/money/releases/latest)

Supported Operating Systems:
* Linux (64 bit)
* ~~Linux (32 bit)~~
* Windows (32 bit)
* Windows (64 bit)
* OSX 


Linux releases will not work out of the box on the Raspberry Pi, you'll have to compile from source.

Development process
===========================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
stable release versions of MoneyCash.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'.

Building Money
===========================

See [doc/readme-qt.rst](https://github.com/moneyproject/money/blob/master/doc/readme-qt.rst) for instructions on building **MoneyCoin QT** | *the intended-for-end-users, nice-graphical-interface, reference implementation of MoneyCash.*

See [doc/build-msw.txt](https://github.com/moneyproject/money/blob/master/doc/build-msw.txt) for instructions on building **moneycoind (Windows)** | *the intended-for-services, no-graphical-interface, reference implementation of MoneyCash.*

See [doc/build-osx.txt](https://github.com/moneyproject/money/blob/master/doc/build-osx.txt) for instructions on building **moneycoind (Mac)**

See [doc/build-unix.txt](https://github.com/moneyproject/money/blob/master/doc/build-unix.txt) for instructions on building **moneycoind (UNIX)**


> For guides and technical documentation please refer to [doc.moneycoin.pw (en)](https://moneycoin.pw/en/documentation)
