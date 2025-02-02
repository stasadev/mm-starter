---
title: ddev/ddev-phpmyadmin
description: phpMyAdmin Add-on For DDEV
stars: 9
categories:
  - official
---

[![tests](https://github.com/ddev/ddev-phpmyadmin/actions/workflows/tests.yml/badge.svg)](https://github.com/ddev/ddev-phpmyadmin/actions/workflows/tests.yml) ![project is maintained](https://img.shields.io/maintenance/yes/2024.svg)

# ddev-phpmyadmin <!-- omit in toc -->

* [What is ddev-phpmyadmin?](#what-is-ddev-phpmyadmin)

## What is ddev-phpmyadmin?

This add-on provides a phpMyAdmin service for [DDEV](https://github.com/ddev/ddev/).

In DDEV v1.22+ phpMyAdmin is not provided by default, but it can be added with this add-on.

For DDEV v1.23.5 or above run

```sh
ddev add-on get ddev/ddev-phpmyadmin
```

For earlier versions of DDEV run

```sh
ddev get ddev/ddev-phpmyadmin
```

Then restart your project

```sh
ddev restart
```

You can run phpMyAdmin easily with the command after installing this add-on:

```sh
ddev phpmyadmin
```

**Contributed and maintained by [@rfay](https://github.com/rfay)**
