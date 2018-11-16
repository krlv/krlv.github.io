---
layout: post
title: (WIP) Testing PHP Preloading RFC
---

Foreword

<!--more-->

# Introduction to PHP Preloading

Todo: 

1. Explain how PHP opcache works
2. Explain how preloading can help

[PHP RFC: Preloading](https://wiki.php.net/rfc/preload)

> [...] On server startup – before any application code is run – we may load a certain set of PHP files into memory - and make their contents “permanently available” to all subsequent requests that will be served by that server.

Find out more by [visiting the PR on GitHub](https://github.com/php/php-src/pull/3538).

# Building PHP with Preloading enabled

Todo:

1. Explain how to build PHP with preloading feature

# Implementing Preloading routine for an existing PHP application

Todo:

1. Script to preload application's classes and deps, smth like `vendor/preload.php`

# Benchmarking PHP Preloading

Todo:

1. Post benchmark results for the test application with and without preloading feature enabled
