<p align="center"><img src="https://avatars1.githubusercontent.com/u/30041331?v=4&s=80"></p>

## About InstantUssd

InstantUssd is a USSD development library.

Requirements
------------

Please see the [composer.json](composer.json) file.

Installation
------------

### Via Git (clone)

First, clone the repository to the approriate folder within your project:

```bash
# git clone https://github.com/bitmarshals/InstantUssd.git
$ cd path/to/install
# remove .git directory; you no longer need it
$ rm -Rvf .git
```

At this point, you need to use [Composer](https://getcomposer.org/) to install
dependencies. Assuming you already have Composer:

```bash
$ cd path/to/project/root
# install bitmarshals/instant-ussd composer package via the command
# php composer.phar require bitmarshals/instant-ussd:dev-master
# OR
$ composer require bitmarshals/instant-ussd:dev-master
```

Finally, import instant ussd tables from [database.sql](config/database.sql) file.


## License

InstantUssd is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT). However, it has a dependancy of <code>bitmarshals/instant-ussd</code> composer package which is still proprietary.

