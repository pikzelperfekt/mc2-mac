# MC² for macOS

A native Minecraft launcher for the Mac. Written in Swift and SwiftUI — not a
web app in a window, not a port.

**This repository carries releases only.** The source is private; what you will
find here are tagged builds, their signatures, and the Sparkle appcast the app
checks for updates.

## Download

Grab the latest `MC2.zip` from [Releases](../../releases/latest), unzip it, and
drag **MC².app** to your Applications folder.

Requires macOS 14 or later. Universal — Apple silicon and Intel.

## Updates

The app updates itself. It reads
[`appcast.xml`](../../releases/latest/download/appcast.xml) from this repository
once a day, and every build is signed with an EdDSA key whose public half is
compiled into the app, so an update it cannot verify is an update it will not
install.

## Issues

Bug reports and feature requests are welcome in
[Issues](../../issues) — please say which macOS and MC² version you are on, and
attach the launcher log if the game failed to start.
