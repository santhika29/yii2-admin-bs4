RBAC Manager for Yii 2
======================
GUI manager for RABC (Role Base Access Control) Yii2. Easy to manage authorization of user :smile:.

[![Latest Unstable Version](https://poser.pugx.org/santhika29/yii2-admin/v/unstable)](https://packagist.org/packages/santhika29/yii2-admin)
[![Total Downloads](https://poser.pugx.org/santhika29/yii2-admin/downloads.png)](https://packagist.org/packages/santhika29/yii2-admin)
[![Daily Downloads](https://poser.pugx.org/santhika29/yii2-admin/d/daily)](https://packagist.org/packages/santhika29/yii2-admin)
[![License](https://poser.pugx.org/santhika29/yii2-admin/license)](https://packagist.org/packages/santhika29/yii2-admin)
[![Reference Status](https://www.versioneye.com/php/santhika29:yii2-admin/reference_badge.svg)](https://www.versioneye.com/php/santhika29:yii2-admin/references)
[![Build Status](https://img.shields.io/travis/santhika29/yii2-admin.svg)](http://travis-ci.org/santhika29/yii2-admin)
[![Dependency Status](https://www.versioneye.com/php/santhika29:yii2-admin/dev-master/badge.png)](https://www.versioneye.com/php/santhika29:yii2-admin/dev-master)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/santhika29/yii2-admin/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/santhika29/yii2-admin/?branch=master)
[![Code Climate](https://img.shields.io/codeclimate/github/santhika29/yii2-admin.svg)](https://codeclimate.com/github/santhika29/yii2-admin)

Documentation
-------------
> **Important: If you install version 3.x, please see [this readme](https://github.com/santhika29/yii2-admin/blob/3.master/README.md#upgrade-from-2x).**


- [Change Log](CHANGELOG.md).
- [Authorization Guide](http://www.yiiframework.com/doc-2.0/guide-security-authorization.html). Important, read this first before you continue.
- [Basic Configuration](docs/guide/configuration.md)
- [Basic Usage](docs/guide/basic-usage.md).
- [User Management](docs/guide/user-management.md).
- [Using Menu](docs/guide/using-menu.md).
- [Api](https://santhika29.github.io/yii2-admin/index.html).

Installation
------------

### Install With Composer

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).



to the require section of your `composer.json` file and execute `php composer.phar update`.

### Install From the Archive

Download the latest release from here [releases](https://github.com/santhika29/yii2-admin/releases), then extract it to your project.
In your application config, add the path alias for this extension.

```php
return [
    ...
    'aliases' => [
        '@sant/admin' => 'path/to/your/extracted',
        // for example: '@sant/admin' => '@app/extensions/sant/yii2-admin-2.0.0',
        ...
    ]
];
```

[**More...**](docs/guide/configuration.md)

[screenshots](https://goo.gl/r8RizT)
