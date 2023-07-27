# Pokémon TCG - Jappawakka fork - Dutch Translation branch

This is a fork of the disassembly of Pokémon TCG.

It builds the following ROM:

- Pokémon Trading Card Game (U) [C][!].gbc `sha1: 0f8670a583255cff3e5b7ca71b5d7454d928fc48`

To build, first download and install Cygwin (https://cygwin.com/install.html), then download RGBDS (https://github.com/gbdev/rgbds/releases) and extract it to [CygwinInstallationDirectory]/usr/local/bin.
Copy the above ROM to [CygwinInstallationDirectory]/home/[YourUserName]/poketcg/ and rename it to "baserom.gbc".
Open the Cygwin terminal, and type `cd poketcg` to change to the directory and then `make` to build the project.

This will output a file named `poketcg.gbc`.

Enter the `make` command everytime you make changes. Don't worry about an error from a function called `compare` when making modifications. It's there to show if the built tcg.gbc file differs from the baserom.gbc file and is mainly used when disassembling.

The `master` branch of this repo is for contributions to the official pret/poketcg repo.
The `english-mods` branch is for changes to the game (graphics, code, whatever).
The `dutch-translation` branch contains the same changes as the english-mods branch but also contains my translations of the game into Dutch.

## See also

- [**Symbols**][symbols]
- **Discord:** [pret][discord]
- **IRC:** [freenode#pret][irc]

[pokered]: https://github.com/pret/pokered
[pokeyellow]: https://github.com/pret/pokeyellow
[pokegold]: https://github.com/pret/pokegold
[pokecrystal]: https://github.com/pret/pokecrystal
[pokepinball]: https://github.com/pret/pokepinball
[pokeruby]: https://github.com/pret/pokeruby
[pokefirered]: https://github.com/pret/pokefirered
[pokeemerald]: https://github.com/pret/pokeemerald
[poketcg]: https://github.com/pret/poketcg
[symbols]: https://github.com/pret/poketcg/tree/symbols
[discord]: https://discord.gg/d5dubZ3
[irc]: https://web.libera.chat/?#pret
