UrlRule
=================
An enhanced UrlRule for Yii2 UrlManager component.


Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist ptheofan/yii2-urlrule "*"
```

or add

```
"ptheofan/yii2-urlrule": "*"
```

to the require section of your `composer.json` file.


Usage
-----

TODO: write usage examples.
In short, extend the /ptheofan/urlrule/UrlRule and override the getParamValue and the setParamValue. The rest
works exactly the same as the default UrlRule. With this approach you can write rules that still use all
of the default nice stuff like regexs, etc. and make them super flexible and also support named arguments
that work with Database, etc. Also by extending your own routes you can easily create partial url rules,
very helpful to remove code duplication and make maintenance easier.
