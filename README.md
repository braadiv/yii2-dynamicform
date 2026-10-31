# braadiv/yii2-dynamicform

> **⚠️ This is a PHP 8.4 compatibility fork — NOT an original work.**

## Credits & Attribution

This package is a **modernized fork** of the original [`wbraganca/yii2-dynamicform`](https://github.com/wbraganca/yii2-dynamicform.git), created and maintained by **Wanderson Bragança**.

**All original code, design, and intellectual property belong to the original author(s).**

The only modifications made in this fork are:
- Updating dependencies to use PHP 8.4 compatible components (`braadiv/dom-crawler` and `braadiv/css-selector`)
- Updating `composer.json` to support PHP 8.1–8.4 LTS
- Adding `"replace": {"wbraganca/yii2-dynamicform": "self.version"}` as a drop-in replacement
- Retaining 100% backward compatibility as a drop-in replacement

---

## Why this fork?

The original package has been **unmaintained since May 2020** and strictly pins its Symfony dependencies to `~2.8|~3.0`, which trigger deprecation warnings under PHP 8.4 LTS. This fork provides a **safe, drop-in replacement** that works seamlessly under PHP 8.4 LTS.

---

## Installation

```bash
composer require braadiv/yii2-dynamicform
```

## Original Package Information

| | |
|:--|:--|
| **Original Package** | [`wbraganca/yii2-dynamicform`](https://github.com/wbraganca/yii2-dynamicform) |
| **Original Version** | `v2.0.3` |
| **Original Author** | Wanderson Bragança |
| **Original License** | `BSD-3-Clause` |
| **Fork Maintainer** | `braadiv` ([github.com/braadiv](https://github.com/braadiv)) |
| **PHP Compatibility** | `>=8.1 || ^8.2 || ^8.3 || ^8.4` |

---

## Changes from Original

See [CHANGELOG.md](../CHANGELOG.md) for a detailed list of all modifications.

---

## License

This fork retains the **same license** as the original package (`BSD-3-Clause`).
All rights and credits belong to the original author.
