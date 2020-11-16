# FFmpeg Stable Autobuilds for Windows

![Build FFmpeg on push](https://github.com/AnimMouse/ffmpeg-stable-autobuild/workflows/Build%20FFmpeg%20on%20push/badge.svg)
![Build FFmpeg on pull request](https://github.com/AnimMouse/ffmpeg-stable-autobuild/workflows/Build%20FFmpeg%20on%20pull%20request/badge.svg)

[FFmpeg](https://ffmpeg.org/) stable nonfree release builds with additional libraries/dependencies.

Version: n4.3.1

[Downloads](https://github.com/AnimMouse/ffmpeg-stable-autobuild/releases)

Schedule of builds: Every time [ffmpeg-windows-build-helpers](https://github.com/rdp/ffmpeg-windows-build-helpers) updates or I updated the repository or when FFmpeg makes a new major release.

ffmpeg, ffprobe, and ffplay are included.

Nonfree builds with Fraunhofer FDK AAC (libfdk_aac) & DeckLink.

All builds are static.

Powered by [ffmpeg-windows-build-helpers](https://github.com/rdp/ffmpeg-windows-build-helpers) script to cross compile for Windows on Linux.

Uses [GitHub Actions](https://github.com/features/actions) to automatically compile FFmpeg.

For stability, use release builds.

For latest git/snapshot/development builds for Windows, goto [ffmpeg-autobuild](https://github.com/AnimMouse/ffmpeg-autobuild)