# Changelog

All notable changes to this project will be documented in this file.

## [1.2.2] - 2026-01-13

### Fixed
- `--limit` flag now correctly limits results for `--trending` and `--new-releases`
- `-t song/track` search filter now only shows songs (previously showed all types)

### Added
- Preview Mode documentation in README with note that `--show-results` doesn't download

## [1.2.1] - 2026-01-13

### Fixed
- Search `--show-results` now respects `-t` type filter (e.g., `-t artist` only shows artists)

## [1.2.0] - 2026-01-13

### Added
- `--show-results` flag now works with `--trending`, `--new-releases`, playlist URLs, and album URLs
- Preview content without downloading using `--show-results`
- `print_playlist_info` panel for playlists (shows title, track count, plays, favorites)
- `print_tracks_list` table for displaying track lists

### Changed
- Author updated to `notdelta_xd`

## [1.1.1] - 2026-01-13

### Added
- Rich version output with banner (`gaana -v`)
- Updated ASCII banner to show "gaanadl"

## [1.1.0] - 2026-01-13

### Added
- `--trending` command to download trending tracks by language
- `--new-releases` command to download new release tracks
- Language support for trending/new-releases (hi, en, pa, etc.)
- `--limit` option works with trending/new-releases

## [1.0.0] - 2026-01-13

### Added
- Initial release
- Download tracks, albums, playlists, and artist top tracks
- Search functionality across all content types
- Synced lyrics from LRCLIB
- 11 output formats: FLAC, ALAC, WAV, AIFF, MP3, AAC, M4A, Opus, OGG, Vorbis, WMA
- Metadata embedding with cover art
- Parallel HLS segment downloads
- Beautiful CLI with colored output and progress bars
- Customizable folder/track naming formats
