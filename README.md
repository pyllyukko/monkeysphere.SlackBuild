monkeysphere.SlackBuild
=======================

A SlackBuild script for [Monkeysphere](http://web.monkeysphere.info/).

Original can be found here: https://slack.sarava.org/slackbuilds/net/misc/monkeysphere/

Dependencies
------------

* [Crypt::OpenSSL::RSA](http://slackbuilds.org/repository/14.1/perl/perl-Crypt-OpenSSL-RSA/)
* [Crypt::OpenSSL::Bignum](http://slackbuilds.org/repository/14.1/perl/perl-Crypt-OpenSSL-Bignum/)

Notes
-----

* The Monkeysphere package can be verified with the Monkeysphere Archive Signing Key (0x18E667F1EB8AF314). As we use *gpgv*, it needs to be on the *trustedkeys.gpg* keyring so the script can use it.
* You need to have *monkeysphere* user and group on the system and the script does not currently create these
