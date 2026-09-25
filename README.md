# player-aid

Illustrated player aids / decision trees to help newer players follow the rules step by step, without having to dig back through the rulebook.

Unofficial, fan-made content. This project is not affiliated with, or endorsed by, any of the publishers below. Warhammer 40,000, Kill Team and Warhammer Age of Sigmar are trademarks of Games Workshop Limited. A Song of Ice and Fire: Tabletop Miniatures Game is a trademark of CMON Global Limited. Star Wars: Shatterpoint is a trademark of Lucasfilm Ltd., published by Atomic Mass Games. Marvel: Crisis Protocol is a trademark of Marvel, published by Atomic Mass Games.

## Contents

### Warhammer 40,000 (11th edition / v11)

`warhammer40k/v11/<language>/<format>/`

- **fr/** — French version
- **en/** — English version

Each language folder contains:
- `png/` — the posters as image files, ready to print or view on screen
- `pdf/` — the same posters bundled into a single PDF

Available aids:
- **Can I Shoot This Target? / Puis-je tirer sur cette cible ?** — visibility, engagement, range, cover, hidden
- **Visibility: Obscuring Terrain & Hidden / Terrain occultant & Caché** — companion illustration
- **Can I Declare a Charge? / Puis-je déclarer une charge ?**
- **Which Move Should I Make? / Quel mouvement choisir ?**
- **Attack Sequence / Séquence d'attaque** — reference sheet for Hit/Wound/Save/Damage

### Kill Team (3rd edition / v3)

`killteam/v3/<language>/<format>/`

- **fr/** — French version
- **en/** — English version

Available aids:
- **Can I Shoot This Target? / Puis-je tirer sur cette cible ?** — visibility, intervening terrain, cover, obscured, target's order
- **Vantage Terrain Rules / Règles de Promontoire** — height bonuses, cover and obscured to/from vantage terrain
- **Actions & AP / Actions & PA** — reference sheet for the Universal Actions, their AP costs, and the movement-action combo rule
- **Gambit & Counteract Timing / Manœuvres & Contre-attaque : Chronologie** — reference sheet for the Strategy phase Gambit step and the Counteract rule

### A Song of Ice and Fire: Tabletop Miniatures Game (v2021)

`asoiaf/v2021/<language>/<format>/`

- **fr/** — French version
- **en/** — English version

Available aids:
- **Séquence d'attaque / Attack Sequence** — reference sheet for Touche/Défense/Blessures/Test de Panique (Hit/Defense/Wounds/Panic), plus Combat Bonuses (Charge/Flank/Rear)
- **Puis-je déclarer une charge ? / Can I Declare a Charge?** — decision tree for charge eligibility, valid targets and success/failure
- **Cartes, Ordres & Priorité / Cards, Orders & Priority** — reference sheet for three independent priority rules: one effect per trigger, who declares first in simultaneous actions, and reroll priority
- **Terrain : Mots-Clés & Exemples / Terrain: Keywords & Examples** — glossary of the 11 Terrain keywords and their effects, plus a lookup table of example Terrain pieces

### Trench Crusade (digital rulebook v1.1)

`trenchcrusade/v1.1/<language>/<format>/`

- **fr/** — French version
- **en/** — English version

Available aids:
- **Puis-je tirer, et sur qui ? / Can I Shoot This Target?** — decision tree for shooting eligibility, line of sight/range, and cumulative modifiers
- **Puis-je déclarer et réussir une Charge ? / Can I Declare and Succeed at a Charge?** — decision tree for charge eligibility, interposing enemies, and the charge move
- **Résolution & Blessure / Success & Injury Rolls** — reference sheet for the core Success/Injury Roll mechanic, plus Down (knocked down) consequences
- **Marqueurs Sang & Bénédiction / Blood & Blessing Markers** — reference sheet for the marker economy and the Bloodbath Roll
- **Ma bande doit-elle tester le Moral ? / Does My Warband Need a Morale Check?** — decision tree for the Morale Check, Shaken Warbands, and fleeing
- **Déplacements spéciaux / Special Movement** — reference sheet for climbing, jumping and falling

### Star Wars: Shatterpoint (core rules / v2023)

`shatterpoint/v2023/<language>/<format>/`

- **fr/** — French version (règles de base, based on the 2023 rulebook)
- **en/** — English version (based on the more recent 2026 rulebook — same rules, no mechanical differences found between the two printings)

Available aids:
- **Résoudre une attaque / Making an Attack** — reference sheet for the full attack sequence: dice pools, modifiers, hit/block comparison, combat tree, damage
- **Les Dés & l'Arbre de Combat / The Dice & the Combat Tree** — companion sheet for the attack/defense die faces, how to walk a unit's combat tree, and directed vs. personal effects
- **États / Conditions** — reference sheet for the four independent conditions (Strained, Disarmed, Exposed, Pinned)
- **Blessé, Estropié & Vaincu / Wounded, Injured & Defeated** — reference sheet for the damage → wounded → injured → defeated progression

### Warhammer Age of Sigmar (core rules / v2026)

`ageofsigmar/v2026/<language>/<format>/`

- **fr/** — French version (based on the September 2026 rules update)
- **en/** — English version

Available aids:
- **Séquence d'Attaque & de Dégâts / Attack & Damage Sequence** — reference sheet for Hit/Wound/Save/Damage, Ward Saves, and allocating damage
- **Quelle unité combat ensuite ? / Which Unit Fights Next?** — decision tree for choosing a unit to fight in the Combat Phase, incl. Strike-first / Strike-last priority
- **Aptitudes : Chronologie & Règles de Un / Abilities: Timing & the Rules of One** — reference sheet for the Declare/Reactions/Effect timing, the Rules of One, and "Once Per" timings

### Marvel: Crisis Protocol (Revised Core Set / v2026)

`crisisprotocol/v2026/<language>/<format>/`

- **fr/** — French version

Available aids:
- **Séquence d'Attaque** — reference sheet for the 14 official attack steps, condensed into 6 stages (dice pools, Criticals, Modify Dice, success, damage)
- **États Spéciaux** — glossary of the 10 special conditions and their effects
- **Terrain & Déplacements Spéciaux** — the 4 special movement types (Throw, Push, Place, Climb), Cover requirements, and the Dodge roll procedure

## How to use

These posters are meant to be followed arrow by arrow: start at the top, answer Yes/No at each question, and follow the colour down to the result.

## Versioning

Each game keeps its own rules-version folder (e.g. `warhammer40k/v11`, `killteam/v3`). When a ruleset changes enough to need an update, a new version folder is added alongside the old one rather than overwriting it. See [CHANGELOG.md](CHANGELOG.md) for the history of what was added and when.

## License

The posters and layouts in this repository are released under the [MIT License](LICENSE). This covers the original content produced here — it does not grant any rights to the underlying game rules or publishers' trademarks (see disclaimer above).

## Feedback

Spotted a mistake, or want to suggest a term correction or a new aid? Please [open an issue](https://github.com/rollponpon/player-aid/issues).
