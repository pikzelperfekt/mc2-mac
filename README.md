# MC²

A free, native Minecraft: Java Edition launcher for macOS and Windows. Full
control over every pack, plus what other launchers leave out: free server
hosting on your own computer, friends and pack sync, and capes and pets seen in
game.

**Website: [getmc2.com](https://getmc2.com)** ·
[Every feature](https://getmc2.com/features) ·
[Compared with Prism, Modrinth App and CurseForge](https://getmc2.com/compare) ·
[Server hosting](https://getmc2.com/hosting)

**This repository carries releases only.** The source is private; what you will
find here are tagged builds, their signatures, and the update feeds the app
checks.

## What it does

**Packs and versions**
- Unlimited packs, several running at once, and the same pack in a second window
- Every Minecraft release, snapshots and old alpha/beta versions
- Fabric, Quilt, Forge, NeoForge and Legacy Fabric
- The right Java for each version, downloaded for you
- Per-pack memory, JVM and game arguments, and a searchable list of every launch flag
- Every mod, resource pack and shader stored once and shared by every pack that uses it
- Imports from Prism Launcher, MultiMC, CurseForge, ATLauncher, Modrinth App, GDLauncher and the Minecraft Launcher

**Mods**
- Modrinth and CurseForge in one browser, dependencies included
- Update all with one-click rollback, a config editor, and a Culprit Finder for crashes

**Servers, on your own Mac, free**
- Paper, Purpur, Spigot, Folia, Sponge, Mohist, Arclight, Vanilla, Fabric, Quilt, Forge, NeoForge and Bedrock
- Several at once, kept running in the menu bar, started automatically with Always on
- Port forwarding done for you (UPnP, NAT-PMP, PCP), Java and Bedrock crossplay through Geyser
- Console, player list, server.properties editor, whitelist and bans, world backups, scheduled restarts, and a phone console

**Friends**
- Friends list, chat, send a pack, packs that stay in sync

**Everything else**
- Built-in recording, one keybind profile for every pack, launcher plugins, and cosmetics earned by playing

## Download

**Mac:** grab the latest `MC2.dmg` from [Releases](../../releases/latest) and
drag **MC².app** to Applications. macOS 14 or later, Universal for Apple silicon
and Intel. Signed with Developer ID and notarized by Apple.

**Windows (beta):** `MC2-Setup.msi` from the same release. Windows 11 x64.

## Updates

The app updates itself. Every build is signed with an EdDSA key whose public
half is compiled into the app, so an update it cannot verify is an update it
will not install.

## Issues

Bug reports and feature requests are welcome in [Issues](../../issues). Please
say which OS and MC² version you are on, and attach the launcher log if the
game failed to start. There is also a [Discord](https://discord.gg/t9b6FReNmE).
