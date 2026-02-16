## 0.8.3
### Added
- Minilib.Text.Unicode: Added `from_iter`, `to_iter`.
### Changed
- Utilized minilib-common@0.12.3.
### Fixed
- Minilib.Text.Unicode: `find`: Fixed a bug where `"ababa".find("aba", 3)` caused a crash.

## 0.8.2
### Fixed
- Minilib.Text.Locale::get_locale: Changed `_unsafe_from_c_str_ptr` -> `unsafe_from_c_str_ptr_io`.

## 0.8.1
### Added
- Added Minilib.Text.WParser.
- Minilib.Text.SimpleParser: Added `eval_parser`, `eval_parser_str`.
- Minilib.Text.Unicode: Added `from_array`, `to_array`, `from_code_unit`.
### Changed
- Minilib.Text.SimpleParser: `ParseResult` is now deprecated. Changed document comments.

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
