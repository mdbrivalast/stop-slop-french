# Stop Slop — Version Française

Une adaptation en français du skill de Hardik Pandya pour éliminer les tics d'écriture IA de la prose.

## Qu'est-ce que c'est

L'écriture IA a des patterns. Des phrases prévisibles, des structures, des rythmes. Ce skill enseigne à Claude (ou à n'importe quel LLM) à les identifier et les éliminer.

## Structure du skill

```
stop-slop-french/
├── SKILL-fr.md              # Instructions principales
├── references/
│   ├── phrases-fr.md        # Phrases à supprimer
│   ├── structures-fr.md     # Patterns structurels à éviter
│   └── examples-fr.md       # Transformations avant/après
├── README-fr.md
└── LICENSE
```

## Démarrage rapide

**Claude Code :** Ajoutez ce dossier comme skill.

**Claude Projects :** Téléchargez `SKILL-fr.md` et les fichiers de référence dans les connaissances du projet.

**Instructions personnalisées :** Copiez les règles essentielles de `SKILL-fr.md`.

**Appels API :** Incluez `SKILL-fr.md` dans votre prompt système. Les fichiers de référence se chargent à la demande.

## Ce qu'il détecte

**Phrases bannies** - Ouvertures qui gagnent du temps, béquilles d'emphase, jargon commercial, tous les adverbes, déclaratives vagues, méta-commentaires. Voir `references/phrases-fr.md`.

**Clichés structurels** - Contrastes binaires, listes négatives, fragmentation dramatique, mises en scène rhétoriques, fausse agentivité, voix de narrateur distant, voix passive. Voir `references/structures-fr.md`.

**Règles au niveau de la phrase** - Pas de débuts interrogatifs, pas de tirets cadratins, pas de fragmentation staccato, pas d'exagérations paresseuses, voix active requise.

## Scoring

Notez de 1 à 10 sur chaque dimension :

| Dimension | Question |
|-----------|----------|
| Clarté | Des affirmations ou des annonces ? |
| Rythme | Varié ou mécanique ? |
| Confiance | Respecte l'intelligence du lecteur ? |
| Authenticité | Sonne humain ? |
| Densité | Quelque chose à couper ? |

Moins de 35/50 : révisez.

## Adaptations par rapport à la version anglaise

- Toutes les phrases bannies ont été traduites et adaptées au français
- Les tics de l'IA anglaise ont été mappés aux équivalents français
- Les exemples sont des transformations authentiques en prose française
- Les règles sur les adverbes en -ment sont spécifiques au français

## Auteur original

[Hardik Pandya](https://hvpandya.com)

## Adaptation française

mdbrivalast

## Licence

MIT. Utilisez librement, partagez largement.
