# Minilib.Text.Unicode

Defined in minilib-text@0.5.2

Unicode conversions (UTF8 <-> UTF32 <-> UTF16)

## Values

### namespace Minilib.Text.Unicode

#### encode_code_point_to_utf8

Type: `Std::U32 -> Std::Array Std::U8 -> Std::Array Std::U8`

Encode a unicode code point to UTF-8

#### utf16_to_utf32

Type: `Std::Array Std::U16 -> Std::Array Std::U32 -> Std::Array Std::U32`

Convert UTF16 string to UTF32 string.

#### utf32_to_utf16

Type: `Std::Array Std::U32 -> Std::Array Std::U16 -> Std::Array Std::U16`

Convert UTF32 string to UTF16 string.

#### utf32_to_utf8

Type: `Std::Array Std::U32 -> Std::Array Std::U8 -> Std::Array Std::U8`

Convert UTF32 string to UTF8 string. Please specify the output destination buffer.

#### utf8_to_utf32

Type: `Std::Array Std::U8 -> Std::Array Std::U32 -> Std::Array Std::U32`

Convert UTF8 string to UTF32 string. Please specify the output destination buffer.

## Types and aliases

## Traits and aliases

## Trait implementations