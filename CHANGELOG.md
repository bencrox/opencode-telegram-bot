# Changelog

All notable changes to the OpenCode Telegram Bot fork will be documented in this file.

## [Unreleased]

### Added
- Cantonese (zh-HK) locale support with Traditional Chinese conversions
  - Renamed `src/i18n/zh-HK.ts` to `src/i18n/zh-hk.ts` (lowercase naming convention)
  - Updated `src/i18n/index.ts` locale definition for `zh-hk`
  - Updated `.env` with `BOT_LOCALE=zh-hk`

### Changed
- Fixed locale resolution case mismatch (zh-hk vs zh-HK)
- Improved locale file naming convention consistency

### Fixed
- Locale fallback from English to proper Cantonese/Traditional Chinese
