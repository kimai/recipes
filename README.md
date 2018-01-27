# Kimai 2 Bundles

This repository contains (Symfony flex) recipes for Kimai 2 bundles.

These bundles are also known as extensions or plugins.
 
## Install bundles

This is how easy you can install new bundles:

```bash
composer req invoice
```

This syntax might be different from what you are used to, it uses the composer plugin [Symfony flex](https://symfony.com/doc/current/setup/flex.html).
You will have it available when you installed Kimai 2 before and your current directory is the Kimai root folder. 

## Available bundles

The value of `Alias` is the identifier to be used when installing via `composer req <identifier>`. 

|Name|Alias|Description|
|---|:---:|---|
|[kevinpapst/kimai2-invoice](https://github.com/kevinpapst/kimai2-invoice)|invoice|Additional invoice features: new renderer and calculator|


## Share your bundle

- Create your repository and add all relevant stuff
- Submit your composer package at [https://packagist.org/](packagist.org)
- Create your Flex recipe and send us a [pull request](https://github.com/kimai/recipes/pulls)

## Documentation

- Packagist docu: <https://packagist.org/about>
- Symfony flex recipe docu: <https://github.com/symfony/recipes>
