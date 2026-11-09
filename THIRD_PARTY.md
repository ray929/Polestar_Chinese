# Third-party material

| Component | Used for | Licence |
|---|---|---|
| [Polestar](https://github.com/polestar) 0.3.5 by the Polestar authors | The addon, its guides, its data packs and the official zhCN/zhTW locale files this repository starts from | GPL-3.0-only |
| World of Warcraft client data tables via [wago.tools](https://wago.tools) | Game names in Chinese (quests, NPCs, objects, items, instances, encounters, factions, flight points) | Game data © Blizzard Entertainment; used as facts for interoperability |
| [OpenCC](https://github.com/BYVoid/OpenCC) | Build-time conversion of the completed Simplified Chinese texts to Traditional Chinese (`tools/gen_zhTW.py` only) | Apache-2.0; not shipped in any addon |
| Questie / QuestieDB (GPL) | Offline reference while checking names; never read during play and never shipped | See `Polestar_zhCN/LICENSE-DATA.txt` of the upstream release |
| pfQuest database by Shagu | Quest, NPC, object and item facts already compiled into the upstream guides and name packs | MIT |

The game's names and texts belong to Blizzard Entertainment. Each `Polestar_<locale>/LICENSE-DATA.txt` from the upstream release lists the exact tables, pages and names taken for that locale; those notices ship with the addons and are not modified by this repository.
