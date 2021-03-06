# Class **Phalcon\\Config\\Factory**

*extends* abstract class [Phalcon\Factory](/en/3.2/api/Phalcon_Factory)

*implements* [Phalcon\FactoryInterface](/en/3.2/api/Phalcon_FactoryInterface)

<a href="https://github.com/phalcon/cphalcon/blob/master/phalcon/config/factory.zep" class="btn btn-default btn-sm">Source on GitHub</a>

Loads Config Adapter class using 'adapter' option, if no extension is provided it will be added to filePath

```php
<?php

use Phalcon\Config\Factory;

$options = [
    "filePath" => "path/config",
    "adapter"  => "php",
];
$config = Factory::load($options);

```


## Methods
public static  **load** ([Phalcon\Config](/en/3.2/api/Phalcon_Config) | *array* $config)





protected static  **loadClass** (*mixed* $namespace, *mixed* $config)

...


