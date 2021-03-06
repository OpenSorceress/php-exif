# [PHPExif v0.2.1](http://github.com/Miljar/php-exif) [![Build Status](https://travis-ci.org/Miljar/php-exif.png?branch=master)](https://travis-ci.org/Miljar/php-exif) [![Coverage Status](https://coveralls.io/repos/Miljar/php-exif/badge.svg?branch=v0.2.2)](https://coveralls.io/r/Miljar/php-exif?branch=v0.2.2)

PHPExif is a library which gives you easy access to the EXIF meta-data of an image.

PHPExif serves as a wrapper around some native or CLI tools which access this EXIF meta-data from an image. As such, it provides a standard API for retrieving and accessing that information.

## Supported tools

* Native PHP functionality (exif_read_data, iptcparse)
* [Exiftool](http://www.sno.phy.queensu.ca/~phil/exiftool‎) adapter (wrapper for the exiftool binary)

## Installation (composer)

```json
"miljar/php-exif": "~0.2"
```


## Usage

[Before v0.2.2](Resources/doc/usage_0.2.1.md)

[v0.2.2+](Resources/doc/usage.md)

## Contributing

Please submit all pull requests against the correct branch. The release branch for the next version is a branch with the same name as the next version. Bugfixes should go in the master branch, unless they are for code in a new release branch.

PHPExif is written according the [PSR-0/1/2 standards](http://www.php-fig.org/‎). When submitting code, please make sure it is conform these standards.

All contributions are welcomed and greatly appreciated.

## Feedback

Have a bug or a feature request? [Please open a new issue](https://github.com/Miljar/php-exif/issues). Before opening any issue, please search for existing issues.

## License

[MIT License](http://github.com/Miljar/php-exif/blob/master/LICENSE)
