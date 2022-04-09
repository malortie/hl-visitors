# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.2] - 2022-04-09

### Fixed

- Thirdperson player pipe animation
- Thirdperson player sniper animation

## [1.0.1] - 2021-11-07

### Added

- CMake support
- Missing wall particles effects

### Changed

- Tweaked sniper primary and secondary attack delays

### Removed

- Hardcoded Python reload sound
- Entity ammo_egonclip
- Entity ammo_sniper
- Entity item_longjump
- Entity item_suit
- Entity weapon_egon
- Entity weapon_gauss

### Fixed

- Missing zoom variable in sniper save/restore array
- Missing sniper reload sound
- Sniper using wrong weapon slot
- Wrong sniper max clip value
- HUD not displayed on some maps
- Use GetNextAttackDelay for next primary and secondary attack in CSniper
- Use UTIL_WeaponTimeBase for next idle time in CSniper
- Pipe not casting hit decal

## [1.0.0] - 2015-12-03

### Added

- HL: Visitors reimplementation source code
