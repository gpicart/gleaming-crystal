# Gleaming Crystal

A mod for [gen1recomp](https://github.com/bryanthaboi/gen1recomp) that plays Polished Crystal 3.2.3, with Capi's extras.

Based on the Pokemon Gen 1 Recompilation Project by BOIS CLUB GAMES, LLC (https://github.com/bryanthaboi/gen1recomp).

This repository is being prepared for the public release.

## License

Gleaming Crystal is a mod that runs inside gen1recomp and patches its code, so it is a work based on gen1recomp and is licensed the same way: **GPLv3 with gen1recomp's Additional Terms** (Section 7). See [LICENSE.md](LICENSE.md).

What this means for you, in short (the license file is what counts):

- You may use, change and share this mod, and use parts of it in other projects, as long as what you share stays under GPLv3 with the same Additional Terms, with its source.
- Anything based on it must keep the license and the copyright notices, and must credit gen1recomp visibly in its README and in-app credits, with the line: "Based on the Pokemon Gen 1 Recompilation Project by BOIS CLUB GAMES, LLC (https://github.com/bryanthaboi/gen1recomp)".
- The license gives no right to the names or logos of BOIS CLUB GAMES, LLC.

### What the license does not cover

The license covers only this project's own code, tests, tools and documents. It does not cover, and this repository does not include:

- **Pokemon Crystal**: its code, names, text, graphics and music. Pokemon and all related names and content are the property of Nintendo, Creatures Inc. and GAME FREAK inc. The player supplies a ROM they own, and gen1recomp imports it on their computer.
- **Polished Crystal** by Rangi42 and its contributors: its text, graphics, music, maps and data. The player supplies the Polished Crystal 3.2.3 ROM, and the mod reads it on their computer. Polished Crystal is published without a license; this project uses it with Rangi42's permission, and the few short in-game names or lines that appear in this repository's code as fallbacks remain theirs.
- **gen1recomp** itself, which is not in this repository and keeps its own license, including its proprietary Launcher.
- **Other mods** the cart can work beside, such as Gmarc's Gen 2 Voxel Mod: their files are read from the player's own install and are not copied here.

## Credits

- **gen1recomp** is by BOIS CLUB GAMES, LLC: https://github.com/bryanthaboi/gen1recomp. Based on the Pokemon Gen 1 Recompilation Project by BOIS CLUB GAMES, LLC.
- **Polished Crystal** is by Rangi42 and many contributors. Its credits are in [CREDITS.md](https://github.com/Rangi42/polishedcrystal/blob/v3.2.3/CREDITS.md) (version 3.2.3, the one this mod reads). The game's content comes from their work.
- Polished Crystal is built on [pokecrystal](https://github.com/pret/pokecrystal), the pret disassembly of Pokemon Crystal.
- **Gleaming Crystal** and its extras are by Capi, built with AI assistance (see below).

### Use of AI

Capi built Gleaming Crystal with Claude (Anthropic) as a coding assistant. The design, the testing and every decision are Capi's; the commits and pull requests that Claude wrote carry a `Co-Authored-By: Claude` line.

This covers only this project's own work: the mod's code, its tests, its tools and its docs, and Capi's extras. The AI use stops there. The work this project builds on is its authors' own and is not part of it: Polished Crystal by Rangi42 and its contributors, pokecrystal by pret, gen1recomp by BOIS CLUB GAMES, LLC, and the other third-party work it uses. Problems found here are this project's, not theirs.
