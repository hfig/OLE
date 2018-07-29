# Overview

This is a fork of the package PEAR::OLE (pear/ole) with a bugfix for [PEAR bug #21243 ](http://pear.php.net/bugs/21243).

Pull Request on upstream: [https://github.com/pear/OLE/pull/10](https://github.com/pear/OLE/pull/10)

# Upstream README

This package is http://pear.php.net/package/OLE and has been migrated from https://svn.php.net/repository/pear/packages/OLE

Please report all new issues via the PEAR bug tracker.

If this package is marked as unmaintained and you have fixes, please submit your pull requests and start discussion on the pear-qa mailing list.

To test, run

    $ composer install
    $ vendor/bin/phpunit

To build, simply

    $ pear package

To install from scratch

    $ pear install package.xml

To upgrade

    $ pear upgrade -f package.xml
