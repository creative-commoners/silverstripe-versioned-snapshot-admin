## SilverStripe Versioned Snapshot Admin

[![Build Status](https://api.travis-ci.org/silverstripe/silverstripe-versioned-snapshot-admin.svg?branch=master)](https://travis-ci.org/silverstripe/silverstripe-versioned-snapshot-admin)
[![SilverStripe supported module](https://img.shields.io/badge/silverstripe-supported-0071C4.svg)](https://www.silverstripe.org/software/addons/silverstripe-commercially-supported-module-list/)
[![Latest Stable Version](https://poser.pugx.org/silverstripe/versioned/version.svg)](http://www.silverstripe.org/stable-download/)
[![Latest Unstable Version](https://poser.pugx.org/silverstripe/versioned-snapshot-admin/v/unstable.svg)](https://packagist.org/packages/silverstripe/versioned-snapshot-admin)
[![Total Downloads](https://poser.pugx.org/silverstripe/versioned-snapshot-admin/downloads.svg)](https://packagist.org/packages/silverstripe/versioned-snapshot-admin)
[![License](https://poser.pugx.org/silverstripe/versioned-snapshot-admin/license.svg)](https://github.com/silverstripe/silverstripe-versioned-snapshot-admin#license)
[![Dependency Status](https://www.versioneye.com/php/silverstripe:versioned-snapshot-admin/badge.svg)](https://www.versioneye.com/php/silverstripe:versioned-snapshot-admin)
[![Reference Status](https://www.versioneye.com/php/silverstripe:admin/reference_badge.svg?style=flat)](https://www.versioneye.com/php/silverstripe:admin/references)
![helpfulrobot](https://helpfulrobot.io/silverstripe/versioned-snapshot-admin/badge)

## Overview

Provides a drop-in replacement UI for [versioned-admin](https://github.com/silverstripe/silverstripe-versioned-admin)
that adds snapshots to the history view.

WARNING: This module is experimental, and not considered stable. 

## Installation

```
$ composer require silverstripe/versioned-snapshot-admin
```

## Versioning

This library follows [Semver](http://semver.org). According to Semver,
you will be able to upgrade to any minor or patch version of this library
without any breaking changes to the public API. Semver also requires that
we clearly define the public API for this library.

All methods, with `public` visibility, are part of the public API. All
other methods are not part of the public API. Where possible, we'll try
to keep `protected` methods backwards-compatible in minor/patch versions,
but if you're overriding methods then please test your work before upgrading.

## Reporting Issues

Please [create an issue](http://github.com/silverstripe/silverstripe-versioned-snapshot-admin/issues)
for any bugs you've found, or features you're missing.

## License

This module is released under the [BSD 3-Clause License](LICENSE)
