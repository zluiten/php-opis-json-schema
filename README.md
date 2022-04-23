# php-opis-json-schema

php-opis-json-schema is a Composer metapackage that provides a single package for
installing event-engine/php-json-schema along with opis/json-schema.

- [event-engine/php-json-schema](https://www.github.com/event-engine/php-json-schema)
- [opis/json-schema](https://www.github.com/opis/json-schema)

With your project relying on this package instead of manually adding `opis/json-schema`
to your project, your dependency update bot of your choice no longer bothers you with
an impossible upgrade to `opis/json-schema` v2.

Install using:

```console
$ composer require netiul/php-opis-json-schema
```
