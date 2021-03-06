# CHANGELOG

## master (unreleased)
* [#123](https://github.com/rails/web-console/pull/123) Replace deprecated `alias_method_chain` with `alias_method` ([@jonatack])

## 2.1.2

* [#115](https://github.com/rails/web-console/pull/115) Show proper binding when raising an error in a template ([@gsamokovarov])
* [#114](https://github.com/rails/web-console/pull/114) Fix templates non rendering, because of missing template suffix ([@gsamokovarov])

## 2.1.1

* [#112](https://github.com/rails/web-console/pull/112) Always allow application/x-www-form-urlencoded content type ([@gsamokovarov])

## 2.1.0

* [#109](https://github.com/rails/web-console/pull/109) Revamp unavailable session response message ([@gsamokovarov])
* [#107](https://github.com/rails/web-console/pull/107) Fix pasting regression for all browsers ([@parterburn])
* [#105](https://github.com/rails/web-console/pull/105) Lock scroll bottom on console window resize ([@noahpatterson])
* [#104](https://github.com/rails/web-console/pull/104) Always whitelist localhost and inform users why no console is displayed ([@gsamokovarov])
* [#100](https://github.com/rails/web-console/pull/100) Accept text/plain as acceptable content type for Puma ([@gsamokovarov])
* [#98](https://github.com/rails/web-console/pull/98) Add arbitrary big z-index to the console ([@bglbruno])
* [#88](https://github.com/rails/web-console/pull/88) Spelling fixes ([@jeffnv])
* [#86](https://github.com/rails/web-console/pull/86) Disable autofocus when initializing the console ([@ryandao])
* [#84](https://github.com/rails/web-console/pull/84) Allow Rails 5 as dependency in gemspec ([@jonatack])
* [#69](https://github.com/rails/web-console/pull/69) Introduce middleware for request dispatch and console rendering ([@gsamokovarov])

[@jonatack]: https://github.com/jonatack
[@ryandao]: https://github.com/ryandao
[@jeffnv]: https://github.com/jeffnv
[@gsamokovarov]: https://github.com/gsamokovarov
[@bglbruno]: https://github.com/bglbruno
[@noahpatterson]: https://github.com/noahpatterson
[@parterburn]: https://github.com/parterburn
