# Pokémon TCG - Jappawakka fork - English Mods branch

This is a fork of the disassembly of Pokémon TCG.

It uses the following ROM as a base:

* Pokémon Trading Card Game (U) [C][!].gbc  `md5: 219b2cc64e5a052003015d4bd4c622cd`

To build, first download and install Cygwin (https://cygwin.com/install.html), then download RGBDS (https://github.com/bentley/rgbds/releases) and extract it to [CygwinInstallationDirectory]/usr/local/bin.
Copy the above ROM to [CygwinInstallationDirectory]/home/[YourUserName]/poketcg/ and rename it to "baserom.gbc".
Open the Cygwin terminal, and type `cd poketcg` to change to the directory and then `make` to build the project.

This will output a file named `tcg.gbc`.

Enter the `make` command everytime you make changes. Don't worry about an error from a function called `compare` when making modifications. It's there to show if the built tcg.gbc file differs from the baserom.gbc file and is mainly used when disassembling.

The `master` branch of this repo is for contributions to the official pret/poketcg repo.
The `english-mods` branch is for changes to the game (graphics, code, whatever).
The `dutch-translations` branch contains the same changes as the english-mods branch but also contains my translations of the game into Dutch.

# See Also

* Disassembly of [**Pokémon Red/Blue**][pokered]
* Disassembly of [**Pokémon Yellow**][pokeyellow]
* Disassembly of [**Pokémon Gold**][pokegold]
* Disassembly of [**Pokémon Crystal**][pokecrystal]
* Disassembly of [**Pokémon Pinball**][pokepinball]
* Disassembly of [**Pokémon Ruby**][pokeruby]
* Disassembly of [**Pokémon Fire Red**][pokefirered]
* Disassembly of [**Pokémon Emerald**][pokeemerald]
* Disassembly of [**Pokémon Trading Card Game**][poketcg]
* Discord: [**pret**][Discord]
* irc: **irc.freenode.net** [**#pret**][irc]

[pokered]: https://github.com/pret/pokered
[pokeyellow]: https://github.com/pret/pokeyellow
[pokegold]: https://github.com/pret/pokegold
[pokecrystal]: https://github.com/pret/pokecrystal
[pokepinball]: https://github.com/pret/pokepinball
[pokeruby]: https://github.com/pret/pokeruby
[pokefirered]: https://github.com/pret/pokefirered
[pokeemerald]: https://github.com/pret/pokeemerald
[poketcg]: https://github.com/pret/poketcg
[Discord]: https://discord.gg/d5dubZ3
[irc]: https://kiwiirc.com/client/irc.freenode.net/?#pret
