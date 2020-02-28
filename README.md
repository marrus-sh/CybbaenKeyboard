# Cybæ̈n Keyboard for macOS

This repository contains a handwritten macOS Keyboard Bundle for the Cybæ̈n English orthographies (Latin/Runic).
It is a somewhat more niche successor to [Kibæn Keyboard](https://github.com/marrus-sh/KibaenKeyboard).

This keyboard layout differs starkly in some ways from the traditional English one.
It is not convenient for typing traditional English text.
It is recommended that you use the macOS Keyboard Viewer to familiarize yourself with its layout before use.

## Installation

01. Clone this repository, or download it as a ZIP and unzip its contents.

02. In Finder, click `Go > Go to Folder…` and type `~/Library`, then press Return to navigate to your user library folder.

03. Create the `Keyboard Layouts` directory if it doesn't already exist in this folder.

04. Drag `Cybæ̈n.bundle` (from this repository) into the `Keyboard Layouts` folder.

## Usage

Open System Preferences, click on Keyboard, and then Input Sources.
Use the + button to add a new input source.
The Cybæ̈n keyboard will be available under the English category.

## Notes

+ The keyboard is the same as a typical US keyboard layout when the Command or Control key is held down.

+ To output a standalone `˙` or `¨`, type the corresponding dead key and press space.

+ The caps lock key switches the keyboard layout to Runic. Pressing shift while caps lock is activated will provide Latin equivalents to Runic characters.

+ There is no ASCII apostrophe key. ASCII hyphen­‑minus is located at Shift+Option+`7`.

+ Option+Space produces a nonbreaking thin space, for use when padding punctuation (for example, in the French tradition).
Shift+Option+Space produces an ordinary nonbreaking space.
So, be sure to release Option if your intent is to type a breaking interword space.

+ The POUND SIGN `£` is given as the uppercase of LONG S `ſ`.

+ At time of publication, not all characters output by this keyboard are formally in the Unicode Standard.
The spurious characters are:

	+ U+A7D4, which is hoped to be assigned as LATIN CAPITAL LETTER TURNED W in a future Unicode version.

Be cautious when typing these characters prior to their formal addition.
They are included here as mere placeholders.

## Changelog

+ **1.0:**
Initial release.
