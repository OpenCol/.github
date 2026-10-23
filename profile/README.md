<p align="center">
  <a href="https://github.com/OpenCol/win-port"><img src="screenshots/map-revealed.png" width="32%" alt="The map of a late game, revealed: the southern continent, roads and colonies"></a>
  <a href="https://github.com/OpenCol/win-port"><img src="screenshots/map-colonies.png" width="32%" alt="English colonies joined by roads, with plowed fields around them"></a>
  <a href="https://github.com/OpenCol/win-port"><img src="screenshots/colony.png" width="32%" alt="A colony screen: buildings, fields, docks and warehouse"></a>
</p>
<p align="center"><sub>The 1995 Windows game, running in <a href="https://github.com/OpenCol/win-port">win-port</a>.</sub></p>

# OpenCol

A fan project around Sid Meier's Colonization (1994). We rebuild the original games from their own code, write down how they work, and make tools for maps and saved games. The Windows version already runs natively on modern systems. The DOS version is next, as OpenCol.

## Play

### Right now: win-port

[win-port](https://github.com/OpenCol/win-port) is the 1995 Windows version, rebuilt from its own code into a native program - no emulator, no DOSBox. It runs on Windows 7 to 11, and on macOS and Linux through Wine. The rules, graphics, music and saved games are the 1995 game's.

[Download win-port](https://github.com/OpenCol/win-port/releases)

### You need your own copy of the game

| Store | Game |
| --- | --- |
| Steam | [Sid Meier's Colonization (Classic)](https://store.steampowered.com/app/327400/) |
| GOG | [Sid Meier's Colonization](https://www.gog.com/en/game/sid_meiers_colonization) |

Both sell the DOS version, but the CD image that comes with it also has the Windows version on it, and win-port picks it up from there. A copy installed from the 1995 Windows CD-ROM works too. Don't buy *Civilization IV: Colonization* by mistake - that's the 2008 remake.

### Next: OpenCol

OpenCol is the DOS game rebuilt as a modern program. It isn't public yet. The first goal is that it plays exactly like the original. After that we start on bug fixes and new features, and each one will be an option you can turn on or off. Until then, play win-port. The same Steam or GOG copy will work with OpenCol. We post progress on [Discord](https://discord.gg/4XP4S9yfJ8).

### Extras for the original Windows game

- [win31-runtime](https://github.com/OpenCol/win31-runtime) runs the original, unmodified 16-bit program on a modern computer.
- [win-patches](https://github.com/OpenCol/win-patches) patches that program: animated water, a few bug fixes and some hidden features ([download](https://github.com/OpenCol/win-patches/releases/latest)).

## Maps

- The original DOS [map editor](https://github.com/OpenCol/mapedit) now runs natively on macOS and Windows, without DOSBox. It has the same screens and keys, and the `.MP` files it saves are byte-for-byte what the original writes. [Download](https://github.com/OpenCol/mapedit/releases/latest)
- The [map archive](https://opencol.github.io/maps/) collects community maps and scenarios, including some rescued from sites that no longer exist. [Submit yours](https://github.com/OpenCol/maps/issues/new?template=map_submission.yml).
- [fsm-to-mp](https://github.com/OpenCol/fsm-to-mp) converts FreeCol `.fsm` maps into classic `.MP` maps.

## Docs and saved games

- [The documentation](https://opencol.github.io/docs/) is what we've learned from reading the code. It covers map generation, combat, taxes, Founding Fathers, difficulty, the `.SAV` and `.MP` formats, every DOS and Windows file format, and how the versions differ.
- The [savegame editor](https://opencol.github.io/sav-editor/) opens and edits `.SAV` files in your browser.

## Under the hood

The source reconstructions aren't public yet:

- win-decomp - the Windows 3.1 game, rebuilt byte-for-byte from the original program.
- dos-decomp - the DOS game, rebuilt from the original program.
- mapedit-decomp - the DOS map editor. It compiles with Microsoft C 6.00A to the same machine code as the shipped program, using the developers' own function names.

These tools are public:

- [dos-tools](https://github.com/OpenCol/dos-tools) - extract, edit and rebuild the DOS game's graphics, palettes and text, and preview maps and saves.
- [win-tools](https://github.com/OpenCol/win-tools) - extract, convert and rebuild the Windows version's assets.
- [web-ui](https://github.com/OpenCol/web-ui) - the shared CSS behind our websites.

## Get involved

You don't need to write code to help.

- Chat with us on [Discord](https://discord.gg/4XP4S9yfJ8).
- Found a bug? Open an issue on the project it's in, for example [win-port](https://github.com/OpenCol/win-port/issues) or [mapedit](https://github.com/OpenCol/mapedit/issues).
- Have an old map lying around? [Send it in](https://github.com/OpenCol/maps/issues/new?template=map_submission.yml).
- The [docs](https://github.com/OpenCol/docs) are plain Markdown, and corrections are welcome.
- [r/ColonizationGame](https://www.reddit.com/r/ColonizationGame/) is where the wider community hangs out.

![OpenCol banner](banner.jpg)

---

*OpenCol is a fan project, not affiliated with or endorsed by the original creators or rights holders. We don't distribute any game files, so you need your own copy.*
