<!-- tyhp-readme:start -->
# tyhpdef/php-debugbar-php-debugbar

Tyhp type definitions for `php-debugbar/php-debugbar` `3.8.0`.

```bash
composer require --dev tyhpdef/php-debugbar-php-debugbar:3.8.0
```

This is a metapackage. Composer also installs `tyhpdef/php-debugbar-php-debugbar-impl` (type files).
Require **this** name, not `tyhpdef/php-debugbar-php-debugbar-impl`.

See https://tyhplang.com.

## Maintain `php-debugbar/php-debugbar`? Ship the types yourself

If you are a Packagist maintainer of `php-debugbar/php-debugbar`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/php-debugbar-php-debugbar-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `php-debugbar/php-debugbar` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/php-debugbar-php-debugbar": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `php-debugbar/php-debugbar` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `php-debugbar/php-debugbar` with a real constraint,
   `"replace": { "tyhpdef/php-debugbar-php-debugbar": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `php-debugbar/php-debugbar` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/php-debugbar-php-debugbar` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
