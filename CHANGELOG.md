## 0.8.1
### Added
- Minilib.Text.Unicode: Added `from_array`, `to_array`, `from_code_unit`.

## 0.8.0
### Changed
- fixproj.toml: Bumped `fix_version` to 1.3.0. Depends on minilib-common@0.12.0.

## 0.7.2
### Added
- Minilib.Text.Unicode: Added `find`, `push_back`, `pop_back`, `set`.
- Minilib.Text.WideChar: Added `get_width`.
### Changed
- Minilib.Text.Locale: Changed `init_locale` implementation.
### Fixed
- Minilib.Text.SimpleParser: Fixed a bug where the first line number of `Stream` was 0.
- Minilib.Text.Unicode: Fixed that `LessThan`, `LessThanOrEq` did not work.

## 0.7.1
### Added
- Minilib.Text.Locale: Added `with_locale`, `lc_*`, `locale_*`.

## 0.7.0
### Added
- Added Minilib.Text.Locale.
- Added Minilib.Text.WideChar.

## 0.6.0
### Added
- Minilib.Text.Unicode: Added `UTF8String`, `UTF16String`, `UTF32String`.
