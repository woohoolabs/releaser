# Woohoo Labs. Releaser

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Total Downloads][ico-downloads]][link-downloads]
[![Gitter][ico-gitter]][link-gitter]

**Woohoo Labs. Releaser is a lightweight release tool for Open Source projects.**

## Table of Contents

* [Install](#install)
* [Basic Usage](#basic-usage)
* [Versioning](#versioning)
* [Change Log](#change-log)
* [Contributing](#contributing)
* [Support](#support)
* [Credits](#credits)
* [License](#license)

## Install

The only thing you need is [Composer](https://getcomposer.org) before getting started. Then run the command below to get
the latest version:

```bash
$ composer require woohoolabs/releaser
```

You can also download the source code of the repository.

## Basic Usage

As a prerequisite, `git` has to be installed on your machine, and the current working directory has to be a version
controlled directory. Additionally, you must have GPG set up for `git` as Releaser [signs the tags](https://help.github.com/articles/signing-tags/)
by default.

If you want to release a package, run the following script (if you use Composer to download Releaser):

```bash
$ ./vendor/bin/releaser.sh
```

## Versioning

This library follows [SemVer v2.0.0](https://semver.org/).

## Change Log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Support

Please see [SUPPORT](SUPPORT.md) for details.

## Credits

- [Máté Kocsis][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see the [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/woohoolabs/releaser.svg
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg
[ico-downloads]: https://img.shields.io/packagist/dt/woohoolabs/releaser.svg
[ico-gitter]: https://badges.gitter.im/woohoolabs/releaser.svg

[link-packagist]: https://packagist.org/packages/woohoolabs/releaser
[link-downloads]: https://packagist.org/packages/woohoolabs/releaser
[link-author]: https://github.com/kocsismate
[link-contributors]: ../../contributors
[link-gitter]: https://gitter.im/woohoolabs/releaser?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge
