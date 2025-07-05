# Twemoji replacer

This module changes Google Noto Emoji to Twemoji.

## Description

~~Uses the [Fedora](https://fedoraproject.org/)'s twitter-twemoji-fonts package because it's already in [CBDT/CBLC](https://docs.microsoft.com/en-us/windows/win32/directwrite/color-fonts#what-kinds-of-color-fonts-does-windows-support) format (the one used in Android and Chrome).~~

Now uses [WhyNotHugo's SourceHut](https://git.sr.ht/~whynothugo/twemoji.ttf) font file because it provides a compatible one directly from the new jdecked's Twemoji.

I took inspiration from [ttf-twemoji](https://aur.archlinux.org/packages/ttf-twemoji/)<sup>AUR</sup> over from the Arch Linux User Repository to get the compatible font.

I do not own the graphics, nor the font files, I'm just sharing them in a way that is easy for everyone to enjoy.

It changes <code>/system/fonts/NotoColorEmoji.ttf</code>.

The module is confirmed to work in LineageOS 18.1, 19.1, 22.2 (Android 11, 12L, and 15) with Magisk 20+.

Any issue of emoji not changing can be fixed by cleaning the app's cache and rebooting so the stock ones are replaced.

## Attribution

[Twitter Emoji for everyone!](https://github.com/twitter/twemoji)

[Justine De Caires's Twemoji fork](https://github.com/jdecked/twemoji)

Copyright 2019 Twitter, Inc and other contributors

Graphics licensed under CC-BY 4.0: https://creativecommons.org/licenses/by/4.0/

