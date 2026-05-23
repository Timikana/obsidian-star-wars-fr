# 🌌 Star Wars Obsidian Vault (FR)

Le vault Obsidian Star Wars le plus exhaustif en français — **1368 fiches** couvrant ~25 000 ans d'histoire galactique, du **Dawn of the Jedi** à **Legacy** (~130 ABY), canon Disney+ ET Légendes.

## 📊 Contenu

| Catégorie | Total |
|---|---|
| ⚔️ Personnages | **982** |
| 🪐 Planètes | **78** |
| 🚀 Vaisseaux | **73** |
| 🐉 Créatures | **60** |
| ⚔️ Événements & Batailles | **53** |
| 🏛️ Organisations | **35** |
| 🌌 Concepts (Force, kyber, Mortis…) | **32** |
| 🧬 Espèces | **30** |
| 🗡️ Artefacts | **25** |
| 📍 Index & MOCs | **21** |
| **TOTAL** | **1368 fiches** |

## ✨ Fonctionnalités

- 🎨 **Système de couleurs strict** : chaque fiche colorée par sabre laser, faction ou région — cohérence 4 points (slug / hex / cssclass / span body)
- 🔗 **~14 000 wikilinks** interconnectant l'univers entier
- 📚 **MOCs (Maps of Content)** par catégorie + **9 fiches-pivots par époque** (`Index/Epoque-*.md`) pour clustering
- 🕰️ **Toutes les époques** couvertes :
  - **Ancienne République** (KOTOR, KOTOR II, SWTOR — Revan, Bane, Vitiate, Bastila…)
  - **Haute République** Phases I/II/III + *The Acolyte* (Avar Kriss, Marchion Ro, Nihil…)
  - **Prélogie** & **Guerre des Clones** (Conseil Jedi complet, clones nommés, Séparatistes)
  - **Dark Times / Empire** (Inquisiteurs, Rebels, Andor, Rogue One)
  - **Trilogie Originale** + Holiday Special + Ewok films/cartoons + Droids cartoon
  - **Nouvelle République** (Mandalorian, Boba Fett, Ahsoka, Bad Batch, Skeleton Crew)
  - **Postlogie / Premier Ordre** + *Resistance*
  - **Légendes EU** : NJO, Legacy, Dark Empire, Tales of the Jedi, Crimson Empire, Thrawn Trilogy, X-wing, Republic Commando
- 🎮 **Jeux** : Jedi Knight series, Force Unleashed, Republic Commando, Empire at War + Forces of Corruption (Consortium Zann), Battlefront II, Bounty Hunter, Pod Racer, Fallen Order, Jedi: Survivor, Outlaws, Squadrons, Hunters, Young Jedi Adventures
- 📰 **Comics** : Marvel canon (Aphra, Vader, Bounty Hunters, HR), Dark Horse Légendes (Tales of the Jedi, KOTOR, Legacy, Crimson Empire, Dark Empire, Lost Tribe of the Sith), Marvel 1977-1986
- 📚 **Romans** : Aftermath, Bloodline, Thrawn canon + Ascendancy, Master & Apprentice, Phasma, Lost Stars, Plagueis, Coruscant Nights, Galaxy of Fear, Young Jedi Knights

## 🚀 Installation

1. Cloner ce repo :
   ```bash
   git clone https://github.com/Timikana/obsidian-star-wars-fr.git
   ```
2. Ouvrir le dossier comme vault dans [Obsidian](https://obsidian.md)
3. **Settings → Apparence → Snippets CSS** → activer `star-wars-colors`
4. `Ctrl+R` pour recharger
5. `Ctrl+G` pour ouvrir le graphe coloré

## 🎯 Démarrage rapide

Ouvre [`Index/HOME.md`](Index/HOME.md) comme hub principal.

Points d'entrée par époque :
- [`Index/Epoque-Ancienne-Republique.md`](Index/Epoque-Ancienne-Republique.md)
- [`Index/Epoque-Haute-Republique.md`](Index/Epoque-Haute-Republique.md)
- [`Index/Epoque-Prelogie.md`](Index/Epoque-Prelogie.md)
- [`Index/Epoque-Clone-Wars.md`](Index/Epoque-Clone-Wars.md)
- [`Index/Epoque-Empire-Dark-Times.md`](Index/Epoque-Empire-Dark-Times.md)
- [`Index/Epoque-Trilogie-Originale.md`](Index/Epoque-Trilogie-Originale.md)
- [`Index/Epoque-Nouvelle-Republique-Mandalorian.md`](Index/Epoque-Nouvelle-Republique-Mandalorian.md)
- [`Index/Epoque-Postlogie-Sequels.md`](Index/Epoque-Postlogie-Sequels.md)
- [`Index/Epoque-Legendes-EU.md`](Index/Epoque-Legendes-EU.md)

Autres MOCs :
- [`Index/Personnages.md`](Index/Personnages.md) — par faction
- [`Index/Relations.md`](Index/Relations.md) — lignées Skywalker / Sith / Darksaber
- [`Index/Sabres.md`](Index/Sabres.md) — par couleur de sabre
- [`Index/Evenements.md`](Index/Evenements.md) — chronologie galactique

## 🎨 Système de couleurs

44 groupes de couleurs dans `graph.json` + 9 groupes par époque :

**Personnages — par sabre laser ou faction**
- 🟦 Bleu (Jedi) · 🟩 Vert (consulaire) · 🟥 Rouge (Sith) · 🟪 Violet (Mace, Vernestra, Mara) · 🟨 Jaune (gardes) · ⬜ Blanc (Ahsoka) · ⬛ Noir (Darksaber) · 🟧 Orange (Baylan) · 🟫 Bronze (Sskeer)
- 🔶 Rébellion · ⬛ Empire · 🟥 Premier Ordre · 🟡 République · 🔵 CIS · 🔷 Mandalorien · 🟫 Hutts · 🟧 Contrebandiers · ⬜ Droïdes

**Planètes — par région galactique**
- 🟡 Core Worlds · 🟦 Inner Rim · 🟪 Mid Rim · 🟧 Outer Rim · 🟫 Wild Space · ⚫ Unknown Regions

**Vaisseaux · Créatures · Organisations · Artefacts** : palettes dédiées par faction/comportement.

## 📂 Structure

```
/
├── Personnages/    # 982 fiches
├── Planetes/       # 78 fiches
├── Vaisseaux/      # 73 fiches
├── Creatures/      # 60 fiches
├── Evenements/     # 53 fiches
├── Organisations/  # 35 fiches
├── Concepts/       # 32 fiches
├── Especes/        # 30 fiches
├── Artefacts/      # 25 fiches
├── Index/          # 21 fiches (MOCs + 9 pivots Époque)
└── .obsidian/
    ├── snippets/star-wars-colors.css
    └── graph.json
```

## 📝 Format des fiches

Chaque fiche utilise un frontmatter YAML standardisé :

```yaml
---
alias: [...]
espece: ...
affiliation: [...]
periode: [...]
statut: ...
canon: Canon | Légendes
premiere_apparition: ...
sabre_couleur: ...
sabre_hex: "#XXXXXX"
couleur: <slug>
couleur_hex: "#XXXXXX"
cssclasses:
  - perso-<slug>
tags: [...]
---
```

**Convention VF** : tous les Sith en `Dark X` (Dark Sidious, Dark Vador, Dark Maul, Dark Krayt…), jamais `Darth`.

## 📜 Sources

Wookieepedia (canon + Legends) · StarWars.com Databank · Visual Dictionaries officiels.

## 📄 Licence

Contenu fan-made non-officiel. Star Wars © Lucasfilm Ltd.

Vault sous licence [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) pour la structure et l'organisation.

---

May the Force be with you. ⚔️
