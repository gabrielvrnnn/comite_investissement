# Comité d'investissement

Mini-société d'agents IA qui évalue si une action cotée est un bon investissement **pour Gabriel**, en DCA, à horizon 10 ans et plus.
Outil d'aide à la réflexion, pas un conseil financier.

## Lancer une séance
Dans ce dossier (le coffre `deuxieme-cerveau` doit être dans le dossier voisin) :

```bash
claude "/comite LVMH"
```

Relancer la même société dans quelques mois : même commande. Le Président retrouve la séance précédente et ajoute « Ce qui a changé ».

## Les agents
| Ordre | Agent | Fichier | Lit | Écrit |
|---|---|---|---|---|
| 0 | Président (orchestrateur) | `.claude/commands/comite.md` | tout | `decision.md`, coffre, historique |
| 1 | Analyste | `.claude/agents/analyste.md` | web | `01-fiche.md` |
| 2 | Bull ‖ Bear | `bull.md`, `bear.md` | fiche seule | `02`, `03` |
| 3 | Réplique | `bull.md`, `bear.md` | fiche + thèse adverse | `04`, `05` |
| 4 | Risk manager | `risk-manager.md` | `01`-`05` + web | `06` + ajouts `[Rxx]` dans la fiche |
| 5 | Conseiller DCA | `conseiller-dca.md` | profil + `01`-`06` | `07` |
| 6 | Vérificateur | `verificateur.md` | fiche + textes | `08` → renvoi aux agents (2 allers-retours max) |

## Traçabilité des chiffres
Chaque chiffre de la fiche a un identifiant `[F12]` et une source. Les autres agents citent l'identifiant ; le Vérificateur contrôle. Donnée introuvable = `[F--]`, jamais d'estimation.

## Fichiers
- `profil-investisseur.md` : profil lu par tous les agents (à tenir à jour).
- `modeles/` : fiche standard et note de décision.
- `seances/<TICKER>/<date>/` : tout le travail d'une séance ; `seances/<TICKER>/historique.md` : une ligne par séance.
- Coffre : `deuxieme-cerveau/01 Projets/Comité d'investissement/` (note projet + `Décisions/`).
