# PokemonTeamListCreator
Creates an Open Team List/Sheet and Close Team List/Sheet from Pokémon Showdown paste

## Source

This repository is maintained at [simusr2/PokemonTeamListCreator](https://github.com/simusr2/PokemonTeamListCreator).

The original project is [DhSufi/PokemonTeamListCreator](https://github.com/DhSufi/PokemonTeamListCreator) ([live demo](https://dhsufi.github.io/PokemonTeamListCreator/)).

### Changes in this fork

- **May 2025**: Fixed PDF generation when a held item has no translation in the item database (for example custom or unreleased items). The list now shows the item name as entered in the Showdown paste instead of crashing.

Update March 2024
- Added multi language list. Thanks a lot to Aurélien Soula (Axior)

Update December 2023:
- Added Pokémon from The Indigo Disk
- Added the ability to pass URL parameters ([Thanks to Joe Zhu](https://twitter.com/joezhuu)):
  - player=text
  - trainer=text
  - team=text
  - switch=text
  - id=text
  - dob=text (recommended use -)
  - age=Junior, Senior or Master
  - lang=chs, cht, en, es, fre, ger, ita, jpn, jpnkanji or kor

Update July 2023:
- Added Pokémon for Regulation D
- Improved file size (about x50 less disk space)
  
Pending: Special characters not allowed (for example ★)

Libraries used:

https://github.com/itsjavi/koffing


https://github.com/parallax/jsPDF
