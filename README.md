sv-dvorak
=========

`sv_dvorak` is a (non-standard) Swedish dvorak keyboard layout designed by
[Thomas Lundqvist](http://tlundqvist.org/sv_dvorak/).

This implementation of Thomas' layout was pretty much grafted on to Apple's
standard US Dvorak. This means it has a full range of optional characters and
the Ctrl/Opt keys work as expected even in more exotic environments such as
MacVim.

# Installation instructions

You can install this either as a system-level keyboard for all users of the
computer, or just for your own. I generally recommend installing it for _all_
users, or you won't be able to use it when OS X asks you for an administrator
password.

## Install for all users of a computer

1. Download `Dvorak (Swedish).keylayout`
2. Right-click the downloaded file and select "Get Info" ("Visa info")
3. Under "Name and extension" ("Namn och filändelse"), make sure the file name
   ends with `.keylayout` (not `.keylayout.txt`, for example)
4. Open a Finder window and select "Go to folder..." from the "Go" menu.
   (Swedish: "Gå" -> "Gå till mapp...")
5. Enter `/Library/Keyboard Layouts` and press "Go" ("Gå")
6. Drag the downloaded file into the `Keyboard Layouts` folder.

## Install for only a single user

1. Download `Dvorak (Swedish).keylayout`
2. Right-click the downloaded file and select "Get Info" ("Visa info")
3. Under "Name and extension" ("Namn och filändelse"), make sure the file name
   ends with `.keylayout` (not `.keylayout.txt`, for example)
4. Open a Finder window and select "Go to folder..." from the "Go" menu.
   (Swedish: "Gå" -> "Gå till mapp...")
5. Enter `~/Library/Keyboard Layouts` and press "Go" ("Gå")
6. Drag the downloaded file into the `Keyboard Layouts` folder.

## Enable the keyboard layout

1. Open System Preferences (Systeminställningar)
2. Click "Language and Text" ("Språk och text") and go to "Input Sources"
   ("Inmatning"?)
3. Click the check box next to "Dvorak (Swedish)".
4. You should now also see a small flag in the right-hand side of your menu
   bar. This is where you can change keyboard layouts.
5. Open the flag menu and select "Dvorak (Swedish)".
6. Start typing!

# Maintainer

Maintained by Janko Luin ([GitHub](https://github.com/gufo) |
[email](mailto:janko@luin.se)). Comments and modifications are welcome - just
open a pull request or send me an email.
