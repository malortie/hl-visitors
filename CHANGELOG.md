# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [visitors/1.0.2] - 2021-10-23

### Added

- Missing wall particles effects

### Changed

- Tweaked sniper primary and secondary attack delays

### Removed

- Entity ammo_egonclip
- Entity ammo_sniper
- Entity item_longjump
- Entity item_suit
- Entity weapon_egon
- Entity weapon_gauss

### Fixed

- Missing sniper reload sound
- Sniper using wrong weapon slot
- Wrong sniper max clip value
- HUD not displayed on some maps
- Use GetNextAttackDelay for next primary and secondary attack in CSniper
- Use UTIL_WeaponTimeBase for next idle time in CSniper
- Pipe not casting hit decal

## [visitors/1.0.1] - 2021-04-10

### Added

- Visual Studio 2019 project files

### Removed

- Hardcoded Python reload sound

### Fixed

- Missing zoom variable in sniper save/restore array

## [visitors/1.0.0] - 2015-12-03

### Added

- HL: Visitors reimplementation source code
