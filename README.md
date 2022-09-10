# Twemoji replacer

This module changes Google Noto Emoji to Twitter Emoji.

## Description

Uses the [Fedora](https://fedoraproject.org/)'s twitter-twemoji-fonts package because it's already in [CBDT/CBLC](https://docs.microsoft.com/en-us/windows/win32/directwrite/color-fonts#what-kinds-of-color-fonts-does-windows-support) format (the one used in Android and Chrome).

I took inspiration from [ttf-twemoji](https://aur.archlinux.org/packages/ttf-twemoji/) over from the Arch Linux User Repository to get the compatible font.

I do not own the graphics, nor the font files, I'm just sharing them in a way that is easy for everyone to enjoy.

It changes <code>/system/fonts/NotoColorEmoji.ttf</code> and <code>/system/fonts/NotoColorEmojiFlags.ttf</code>. The flags variant is smaller and only has flags, and has lower priority than the regular font file, but I include it regardless, as there is a slight chance some app wants it.

The module is confirmed to work in LineageOS 18.1 and 19.1 (Android 11 and 12L) with Magisk 20+.

Any issue of emoji not changing can be fixed by cleaning the app's cache and rebooting so the stock ones are replaced.

## Attribution

[Twitter Emoji for everyone!](https://github.com/twitter/twemoji)

Copyright 2019 Twitter, Inc and other contributors

Graphics licensed under CC-BY 4.0: https://creativecommons.org/licenses/by/4.0/

