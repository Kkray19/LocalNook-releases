# LocalNook releases

Downloads for **LocalNook**, a native macOS app that puts what's playing, your
day and your tools in the notch. This repository holds only the release
downloads and their notes.

Each release has two files:

- `LocalNook-<version>.dmg`: open it and drag LocalNook to Applications.
- `LocalNook-<version>.zip`: the same app, used by LocalNook's built-in
  updater.

## Updates

With "Check for updates automatically" on (Settings ▸ About), LocalNook asks
this repository once a day whether a newer release exists. When one does, it
tells you, and it downloads and installs it only when you press Install. It
installs only a copy signed with the same certificate as the one you are
running.

## Opening it the first time

LocalNook is not yet notarized by Apple, so macOS blocks the first launch.
Open System Settings ▸ Privacy & Security, scroll down, and click
**Open Anyway** next to LocalNook.

## Requirements

macOS 15 or later, on a Mac with Apple silicon.

## License

From version 0.5.0, LocalNook is proprietary software. What you may do with
your copy is in its `LICENSE` file, inside the app (Settings ▸ About ▸
License ▸ Open LICENSE) and on the disk image. Versions 0.2.0 to 0.4.8 were
released under the GNU General Public License v3.0 or later, and stay under
it for everyone who has them.

## Source code of the fan helper

The root fan helper inside LocalNook (`com.localnook.app.fan-helper`) is a
separate program, free software under the GNU General Public License v3.0 or
later. Where to get its complete corresponding source for the version you
have is in `LocalNook-Source-Offer.txt`, inside the app (Settings ▸ About ▸
License ▸ Source code offer) and at the top of the disk image, and in that
version's release notes. Other open-source parts keep their own licences;
their notices are in `THIRD_PARTY_LICENSES.md` inside the app.
