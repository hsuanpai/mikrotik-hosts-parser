# MikroTik hosts parser

[![Version][badge_version]][link_packagist]
[![Build Status][badge_build_status]][link_build_status]
[![StyleCI][badge_styleci]][link_styleci]
[![Coverage][badge_coverage]][link_coverage]
[![Code Quality][badge_quality]][link_coverage]
[![GitHub issues][badge_issues]][link_issues]
[![License][badge_license]][link_license]
[![Downloads count][badge_downloads_count]][link_packagist]

Приложение, которое генерирует скрипт для роутера на базе `RouterOS`, который блокирует "рекламные" хосты.

Более подробно о нем можно прочитать по [этой ссылке (хабр)][habr].

Крайне рекомендую использовать `php` версии 7 и выше по соображениям производительности.

### Установка

Для развертывания приложения достаточно выполнить в терминале:

```bash
$ composer create-project tarampampam/mikrotik-hosts-parser
```

Все интересные настройки вынесены в файлы конфигурации, что лежат в директории `./config`:

### Демо

Не гарантирую что приложение будет жить вечно, что пользоваться им можешь [тут][demo].

### Лицензия

[MIT license](./LICENSE) *(да делай ты что хочешь, просто не удаляй имя автора)*.

[badge_version]:http://img.shields.io/packagist/v/tarampampam/mikrotik-hosts-parser.svg?style=flat&maxAge=30
[badge_downloads_count]:https://img.shields.io/packagist/dt/tarampampam/mikrotik-hosts-parser.svg?style=flat&maxAge=30
[badge_license]:https://img.shields.io/packagist/l/tarampampam/mikrotik-hosts-parser.svg
[badge_build_status]:https://scrutinizer-ci.com/g/tarampampam/mikrotik-hosts-parser/badges/build.png?b=master
[badge_styleci]:https://styleci.io/repos/39877790/shield?style=flat&maxAge=30
[badge_coverage]:https://scrutinizer-ci.com/g/tarampampam/mikrotik-hosts-parser/badges/coverage.png?b=master
[badge_quality]:https://scrutinizer-ci.com/g/tarampampam/mikrotik-hosts-parser/badges/quality-score.png?b=master
[badge_issues]:https://img.shields.io/github/issues/tarampampam/mikrotik-hosts-parser.svg?style=flat&maxAge=30
[link_packagist]:https://packagist.org/packages/tarampampam/mikrotik-hosts-parser
[link_styleci]:https://styleci.io/repos/39877790/
[link_license]:https://github.com/tarampampam/mikrotik-hosts-parser/blob/master/LICENSE
[link_build_status]:https://scrutinizer-ci.com/g/tarampampam/mikrotik-hosts-parser/build-status/master
[link_coverage]:https://scrutinizer-ci.com/g/tarampampam/mikrotik-hosts-parser/?branch=master
[link_issues]:https://github.com/tarampampam/mikrotik-hosts-parser/issues
[faker_repository_link]:https://github.com/fzaninotto/Faker
[getcomposer]:https://getcomposer.org/download/
[demo]: https://stopad.kplus.pro/
[habr]: https://habrahabr.ru/post/264001/