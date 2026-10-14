# Oriel releases

Downloads for **Oriel**, a free native macOS app that puts what's playing, your day and your tools in the
notch. Oriel was formerly called LocalNook; some of its files and requests still use that name.

This repository holds only the release downloads and their notes. Oriel's source code is not published here.

## Download

Each release has two files:

- `LocalNook-<version>.dmg`: open it and drag Oriel to Applications.
- `LocalNook-<version>.zip`: the same app, used by Oriel's built-in updater.

The file names keep the old name because the updater looks for them.

## Free, under the Oriel License Agreement

Oriel is free: there is no price, subscription or paid tier. You use it under the Oriel License Agreement,
which you accept, together with the Privacy Policy, the first time you open Oriel. Both documents are also in
the disk image, beside the app.

## Updates

If the update check is on (Settings ▸ About), Oriel asks this repository once a day whether a newer release
exists. It tells you when one does, and downloads one only when you press Install and Relaunch. It installs
only a copy signed with the same certificate as the one you are running.

## Privacy

This version of Oriel collects no usage data. The Privacy Policy, which is also in the disk image, says what
each online feature sends and when.

## Opening it the first time

Oriel is not yet notarized by Apple, so macOS blocks the first launch. Open System Settings ▸ Privacy &
Security, scroll down, and click **Open Anyway** next to Oriel.

## Requirements

macOS 15 or later, on a Mac with Apple silicon.

## Questions and privacy requests

Email oriel.nook@gmail.com about the License Agreement, the Privacy Policy or your personal information. Please
don't send passwords, keys or other sign-ins.

## Source code

This repository does not contain Oriel's source code. Parts of Oriel are open-source software under their own
licences. The fan helper (`com.localnook.app.fan-helper`) is under the GNU General Public License v3.0 or
later, and its complete source is at https://github.com/Kkray19/LocalNook-fan-helper-source.
`LocalNook-Source-Offer.txt`, in the app and in the disk image, says where to get the source of each
open-source part and what each licence requires. LocalNook versions 0.2.0 to 0.4.8 were under the GNU General
Public License, and stay under it for everyone who has them.
