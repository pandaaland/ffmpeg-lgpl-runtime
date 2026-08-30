# ffmpeg-lgpl-runtime

Automated standalone static FFmpeg / FFprobe runtime builds for Windows and macOS under **GNU LGPL v2.1** (no GPL or non-free components).

## Overview

This repository builds zero-dependency static binaries of `ffmpeg` and `ffprobe` using official FFmpeg source tarballs with strictly LGPL configuration:

- `--disable-gpl --disable-nonfree --enable-static --disable-shared`
- Built-in native audio decoders, demuxers, and filters
- Includes `LICENSE`, `COPYING.LGPLv2.1`, `SOURCE.txt`, and `THIRD-PARTY-NOTICES` in each release archive

## Platforms

- **Windows x64** (`ffmpeg-<version>-win32-x64.zip`)
- **macOS Apple Silicon** (`ffmpeg-<version>-darwin-arm64.zip`)
- **macOS Intel** (`ffmpeg-<version>-darwin-x64.zip`)

## Releases

Pre-built binaries are available on the [Releases](https://github.com/pandaaland/ffmpeg-lgpl-runtime/releases) page.
