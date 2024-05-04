# FFmpeg Stable Autobuilds for Windows
[FFmpeg](https://ffmpeg.org) stable nonfree release builds with additional libraries/dependencies.

[Downloads](https://github.com/AnimMouse/ffmpeg-stable-autobuild/releases)

### Schedule
Every time [ffmpeg-windows-build-helpers](https://github.com/rdp/ffmpeg-windows-build-helpers) updates or when FFmpeg makes a new major release.\
The workflow will check if those are updated at 11:07 on Sunday weekly or if someone starred this repository.

#### Release Retention Policy
Release builds are kept for two years.

ffmpeg, ffprobe, and ffplay are included.

Nonfree builds with Fraunhofer FDK AAC (libfdk_aac) & DeckLink.

All builds are static.

Powered by [ffmpeg-windows-build-helpers](https://github.com/rdp/ffmpeg-windows-build-helpers) script to cross compile for Windows on Linux.

Uses [GitHub Actions](https://github.com/features/actions) to automatically compile FFmpeg.

Uses [endoflife.date](https://endoflife.date) to get latest version of FFmpeg.

For stability, use release builds.

For latest git/snapshot/development/master/nightly builds for Windows, go to [ffmpeg-autobuild](https://github.com/AnimMouse/ffmpeg-autobuild)

For other builds of FFmpeg built by others, go to [My list of FFmpeg Binaries](https://www.animmouse.com/p/ffmpeg-binaries/).