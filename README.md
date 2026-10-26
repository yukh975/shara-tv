# Shara TV

IPTV + SMB media player for Android TV (like Kodi, without the extras).

**This repository holds only releases.** The source code lives in a private
GitLab repository. Releases are published here for in-app updates on the TV.

- IPTV: add a playlist URL (M3U / Xtream / provider `get.php` links), groups,
  channel numbers, logos, XMLTV EPG.
- SMB: add a server (address + login/password) → browse its shares → play video,
  seek via HTTP Range, resume where you left off, star favourite shares.
- Remote-first UI: OK / arrows / CH± / BACK.

## Install

Download the latest APK from
[Releases](https://github.com/yukh975/shara-tv/releases) and install it on your
Android TV (`adb install -r` or a file manager from USB).

The app checks this repo's releases for updates (Settings → Updates).

## Verification

APKs are signed with the Shara TV production key (certificate SHA-256
`9a9f3b6f769694907728114d87a4c5901cbb0e185d457976e2396ee22119ded5`). The app
verifies the package and signature before installing an update.
