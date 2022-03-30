# Steam Play - Sonic CD 2011 Decompilation 

Sonic CD but you can run it on steam on linux. A fork of this project https://git.froggi.es/eukara/reGTA-SteamPlay

# Dependencies
None, it expects your /bin/sh to handle arrays and things though.

# Installation
If you use a Steam Deck, just go into desktop mode.

In order to install it, you just clone
the repository into your $HOME/.steam/steam/compatibilitytools.d/SonicCD-steamplay directory.
If those those folders don't exist, just create the folders and dump the repository there.

After doing that, go to Sonic CD's properties on steam and force a Steam Play compatitbility tool and then pick SonicCD-Decomp

One thing to note, it comes with a custom settings.ini file that's has a ScreenWidth set to 384. That was to accommodate the Deck's 16:10 screen. If you want to change it to 16:9, just set it to the original 424 value.

# License

Copyright (c) 2021 Marco "eukara" Hladik

Permission to use, copy, modify, and distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF MIND, USE, DATA OR PROFITS, WHETHER
IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING
OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE. 
