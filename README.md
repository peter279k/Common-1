[![PHP >= 5.4.0](https://img.shields.io/badge/PHP-%3E%3D%205.4.0-8892bf.svg)](https://maikuolan.github.io/Compatibility-Charts/)
[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)

## Common Classes Package.

The common classes package is intended to provide some of the classes that I originally wrote for common use by CIDRAM, phpMussel, etc as a separate, redistributable package, available to be readily integrated and used with other projects and packages via Composer.

All classes in the common classes package use the namespace `Maikuolan\Common`.

The common classes package currently contains the following classes:
- **L10N**: Used by CIDRAM and phpMussel to handle L10N data, the L10N class reads in an array of L10N strings and provides some safe and simple methods for manipulating and returning those strings when needed, and for handling cardinal plurals, where integers and fractions are concerned alike, based upon the pluralisation rules specified by the L10N from a range of various pluralisation rules available, to be able to suit the needs of most known languages.
- **YAML**: Used by CIDRAM and phpMussel to handle YAML data, the YAML class is a simple YAML handler intended to adequately serve the needs of the packages and projects where it is implemented. Note however, that isn't a complete YAML solution, instead supporting the YAML specification only to the bare minimum required by those packages and projects known to implement it, and I therefore can't guarantee that it'll necessarily be an ideal solution for other packages and projects, whose exact requirements I mightn't be familiar with.

---


### How to install:

The recommended way to install it is by using Composer:

`composer require maikuolan/common`

You can, however, download the classes you need from this repository manually, if you want to do so.

After you've downloaded the package, or any needed classes, [PSR-4](https://www.php-fig.org/psr/psr-4/) autoloading is preferred way to access the classes (particularly if you're using a large number of different, unrelated classes). If you're installing the package via Composer, all you have to do is `require_once 'vendor/autoload.php';` and everything will be taken care of. Alternatively, if you're installing the package or its classes manually (or without Composer), or if you don't want to use a PSR-4 autoloader, you can simply require or include any needed classes into your projects by using an include or require statement in your code, to point to the needed classes in any PHP code that needs them.

---


### How to use:

- to do -

---


### Other information:

#### Licensing:
Provided using the [GNU General Public License version 2.0](https://github.com/CIDRAM/Aggregator/blob/master/LICENSE.txt) (GPLv2).

#### For support:
Please use the issues page of this repository.

---


Last Updated: 28 February 2019 (2019.02.28).
