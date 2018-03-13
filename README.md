# PHPExcel - with PHP 7.2

## Laravel and PHP 7.2 Fix

The repo includes a small typo at `phpexcel/Classes/PHPExcel/Writer/Excel2007/Worksheet.php:768` that causes this error:
``` php
    count(): Parameter must be an array or an object that implements Countable
```

This fork simply fixes it.
Just add the following in you `composer.json`:

``` json
"repositories": [
        {"type": "vcs", "url": "git@github.com:nickfls/PHPExcel.git"}
    ],
```

Your PHPExcel version would be 1.8.1.1.

# PHPExcel - DEPRECATED

PHPExcel last version, 1.8.1, was released in 2015. The project is no longer maintained and
should not be used anymore.

All **users should migrate** to its direct successor [PhpSpreadsheet](https://github.com/PHPOffice/PhpSpreadsheet), or another alternative.

In a few months, the GitHub project will be marked as archived, so everything will be read-only.

## License

PHPExcel is licensed under [LGPL (GNU LESSER GENERAL PUBLIC LICENSE)](https://github.com/PHPOffice/PHPExcel/blob/master/license.md)
