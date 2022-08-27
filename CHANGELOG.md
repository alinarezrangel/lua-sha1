# Changelog

## 0.8.0 (2022-08-27)

## Added

* New `sha1.sha1_chunked` function which allows you to hash messages with known
  length but dynamically generated contents.

## 0.7.0 (2022-08-27)

### Changed

* `init.lua` now uses the Lua 5.3 bit operators on Lua 5.4.

## 0.6.1 (2022-05-21)

### Changed

* Changed rockspec file so that Lua 5.4 is supported.

## 0.6.0 (2018-10-06)

### Added

* New `sha1.version` field contains `sha1` version.

### Changed

* `sha1` now uses bitwise operation modules or Lua 5.3 bitwise operators when
  available. This improves performance considerably. Pure Lua fallback
  used on Lua 5.1 is now much faster, too.

## 0.5.0 (2014-01-22)

Initial LuaRocks release.
