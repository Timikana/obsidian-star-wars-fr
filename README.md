# 🌌 Star Wars Obsidian Vault (FR)

Un vault Obsidian complet documentant l'univers Star Wars en français — **648 fiches** couvrant ~6900 ans d'histoire galactique, du **Old Republic** (Ajunta Pall, ~6900 BBY) à **Exegol** (35 ABY).

## 📊 Contenu

| Catégorie | Total |
|---|---|
| ⚔️ Personnages | **462** |
| ⚔️ Événements & Batailles | **35** |
| 🪐 Planètes | **44** |
| 🚀 Vaisseaux | **34** |
| 🐉 Créatures | **19** |
| 🏛️ Organisations | **17** |
| 🧬 Espèces | **15** |
| 🗡️ Artefacts | **15** |
| 🌌 Concepts (Force, Règle des Deux…) | **7** |
| **TOTAL** | **648 fiches** |

## ✨ Fonctionnalités

- 🎨 **Système de couleurs** : chaque nœud du graphe est coloré selon sa couleur de sabre laser, sa faction ou sa région galactique
- 🔗 **~6000 wikilinks** interconnectent personnages, planètes, vaisseaux et événements
- 📚 **MOCs (Maps of Content)** pour chaque catégorie + lignées Skywalker/Sith/Darksaber
- 🎭 **Canon Disney+ complet** : films, séries live (Mando, Andor, Acolyte, Ahsoka, Skeleton Crew…), animés (Clone Wars, Rebels, Bad Batch…)
- 📖 **Légendes essentiels** : KOTOR, SWTOR, NJO, Force Unleashed, Tales of the Jedi, Doctor Aphra, Trilogie Thrawn
- 🌟 **Haute République** Phases I, II, III complètes

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

Autres points d'entrée :
- [`Index/Personnages.md`](Index/Personnages.md) — MOC complet par faction
- [`Index/Relations.md`](Index/Relations.md) — lignées Skywalker / Sith / Darksaber
- [`Index/Sabres.md`](Index/Sabres.md) — index par couleur de sabre
- [`Index/Evenements.md`](Index/Evenements.md) — chronologie galactique

## 🎨 Système de couleurs (graph)

Les nœuds sont colorés automatiquement via `graph.json` (35 groupes de couleurs) :

**Personnages — par sabre laser ou faction**
- 🟦 Bleu (Jedi gardien) · 🟩 Vert (consulaire) · 🟥 Rouge (Sith) · 🟪 Violet (Mace, Vernestra) · 🟨 Jaune · ⬜ Blanc (Ahsoka) · ⬛ Noir (Darksaber) · 🟧 Orange (Baylan)
- 🔶 Rébellion · ⬛ Empire · 🟥 Premier Ordre · 🟡 République · 🔵 Mandalorien · 🟫 Pègre / Hutts · 🟢 Jedi (sans sabre) · 🟣 Sith

**Planètes — par région galactique**
- 🟦 Core Worlds · 🟪 Inner/Mid Rim · 🟧 Outer Rim · 🟫 Wild Space · ⚫ Unknown Regions

## 📂 Structure

```
/
├── Personnages/    # 462 fiches
├── Planetes/       # 44 fiches
├── Vaisseaux/      # 34 fiches
├── Evenements/     # 35 fiches
├── Creatures/      # 19 fiches
├── Organisations/  # 17 fiches
├── Especes/        # 15 fiches
├── Artefacts/      # 15 fiches
├── Concepts/       # 7 fiches
├── Index/          # MOCs + HOME
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
couleur: <classe>
couleur_hex: "#XXXXXX"
cssclasses:
  - perso-<couleur>
tags: [...]
---
```

## 📜 Sources

Canon Wookieepedia + StarWars.com Databank.

## 🤖 Génération

Ce vault a été généré et organisé via [Claude Code](https://claude.ai/code) en utilisant des agents en parallèle pour couvrir toutes les ères Star Wars.

## 📄 Licence

Contenu fan-made non-officiel. Star Wars © Lucasfilm Ltd.

Ce vault est un travail de fan, sous licence [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) pour la structure et l'organisation.

---

May the Force be with you. ⚔️
