_This is a fork of the official repository, which supports Symfony 7._\
_This means it is compatible with Drupal 11._

_The repository attempts to mirror the most recent upstream releases, with changes for Drupal 7 support._\
_(This modified README is part of the master branch, which you can completely ignore.)_

_To use this repository, put this in your project's composer.json:_

```json
{
    "require": {
        "simplesamlphp/simplesamlphp": "^2.4"
    },
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/donquixote/xml-common"
        },
        {
            "type": "vcs",
            "url": "https://github.com/donquixote/simplesamlphp"
        }
    ]
}
```

# SimpleSAMLphp

![Build Status](https://github.com/simplesamlphp/simplesamlphp/actions/workflows/php.yml/badge.svg)
[![Coverage Status](https://codecov.io/gh/simplesamlphp/simplesamlphp/branch/master/graph/badge.svg)](https://codecov.io/gh/simplesamlphp/simplesamlphp)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/simplesamlphp/simplesamlphp/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/simplesamlphp/simplesamlphp/?branch=master)
[![Type coverage](https://shepherd.dev/github/simplesamlphp/simplesamlphp/coverage.svg)](https://shepherd.dev/github/simplesamlphp/simplesamlphp)
[![BrowserStack Status](https://automate.browserstack.com/badge.svg?badge_key=LzlCL29sZEVDRXJpdGtxZUdITFA3YjYyUFBBYkVVZDVDcG1YZXRaN2pvTT0tLVhCNzkwVUNGVFVjVFVicUg0R1BNR0E9PQ==--f9efb6f330bd98dd6e3c7b816ac2f0982275a872)](https://automate.browserstack.com/public-build/LzlCL29sZEVDRXJpdGtxZUdITFA3YjYyUFBBYkVVZDVDcG1YZXRaN2pvTT0tLVhCNzkwVUNGVFVjVFVicUg0R1BNR0E9PQ==--f9efb6f330bd98dd6e3c7b816ac2f0982275a872)

This is the official repository of the SimpleSAMLphp software.

* [SimpleSAMLphp homepage](https://simplesamlphp.org)
* [SimpleSAMLphp Downloads](https://simplesamlphp.org/download)

Please, [contribute](CONTRIBUTING.md)!
