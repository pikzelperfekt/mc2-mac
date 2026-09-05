# MC² for macOS

A native Minecraft launcher for the Mac. Written in Swift and SwiftUI, not a web
app in a window and not a port.

**This repository carries releases only.** The source is private; what you will
find here are tagged builds, their signatures, and the Sparkle appcast the app
checks for updates.

## Download

Grab the latest `MC2.zip` from [Releases](../../releases/latest), unzip it, and
drag **MC².app** to your Applications folder.

Requires macOS 14 or later. Universal, for Apple silicon and Intel.

### Opening it the first time

This build is signed but not yet notarized by Apple, so Gatekeeper refuses it on
a double click and says the app cannot be opened. That is expected, and there is
nothing wrong with the download.

**Right-click MC².app, choose Open, then confirm.** You only need to do it once;
every launch after that is a normal double click.

If macOS still refuses, it is because the file was quarantined on download. Clear
the flag and open it again:

```sh
xattr -dr com.apple.quarantine "/Applications/MC².app"
```

## Updates

The app updates itself. It reads
[`appcast.xml`](../../releases/latest/download/appcast.xml) from this repository
once a day, and every build is signed with an EdDSA key whose public half is
compiled into the app, so an update it cannot verify is an update it will not
install.

## Issues

Bug reports and feature requests are welcome in [Issues](../../issues). Please
say which macOS and MC² version you are on, and attach the launcher log if the
game failed to start.
