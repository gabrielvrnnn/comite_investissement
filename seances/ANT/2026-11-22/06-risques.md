# Risques — Anthropic, PBC (ANT) — 2026-11-22

> Conflit d'intérêts : rédigé par un modèle Claude, développé par Anthropic. Exigence renforcée. Faits nouveaux : [R01]-[R13] dans `01-fiche.md`, **tous issus de résumés de presse** (prospectus non lu), sauf [R12] (partiellement primaire).

## Grille

| Risque | Bull/Bear | Probabilité 10 ans | Impact | Source |
|---|---|---|---|---|
| Litiges droits d'auteur (livres, musique, Reddit) : 1,5 Md$ déjà concédés [R01], > 3 Md$ réclamés dans un seul dossier musical [R03], quatre autres en cours [R03][R04] | rien | forte (nouveaux règlements) | modéré, grave si le « fair use » tombe | [R01]-[R04] |
| Conflit avec l'État fédéral : désignation « supply chain risk » confirmée en appel 2-1 [R05] ; préjudice réputationnel reconnu par le S-1 [R06] | rien | forte (déjà réalisé) | grave si extension au-delà de la défense | [R05][R06] |
| Contrôle à l'export : modèles phares coupés pour tous les clients pendant ≈ 3 semaines, réimposable [R07] | rien | moyenne | grave (CA à l'arrêt sur les modèles visés) | [R07] |
| Concentration clients : deux clients ≈ 12 % chacun du CA 2025 ; top 5 ≈ 25 % sur 9 mois 2026, sans contrats longs [R08] | partiel (Bear : « [F--] ») | moyenne | grave | [R08] |
| Taïwan / TSMC / HBM : capacité alternative « at early stages » [R09] | rien | faible à moyenne | perte définitive possible (895,4 Md$ d'engagements [F27] sans puces livrées) | [R09][F27] |
| Fournisseurs de calcul = actionnaires = concurrents [F28][F50] | traité | forte | grave | [F28] |
| Régulation (EU AI Act, SB 53, RAISE Act) ; licéité des données d'entraînement non garantie par le S-1 [R13] | rien | forte | modéré | [R13] |
| Sécurité : fuite de ≈ 512 000 lignes de code de Claude Code + attaque de dépendance le même jour [R10] | rien | forte (récurrence) | modéré | [R10] |
| Gouvernance : classe F à 50,1 % [F54], Trust [F56], mission pouvant primer sur l'intérêt financier [R12] | traité | certaine | grave (aucun recours) | [F54][R12] |
| Rotation des talents : départs non-fondateurs [R11] | rien | moyenne | modéré | [R11] |
| Dilution, lock-up, SBC [F48][F59][F22] | traité | forte | grave | [F48] |
| Dette de 130,5 Md$ de nature inconnue [F25], rang avant l'action | partiel | introuvable | perte définitive possible en restructuration | [F25] |

## Ce que le débat a raté

1. **Le risque juridique est déjà matérialisé, pas hypothétique.** Le règlement Bartz (1,5 Md$ [R01], dont 1,2 Md$ encore en passif courant au 30/06/2026 [R02]) représente ≈ 4,3 % du CA 12 mois (1,5 / 35,3, à partir de [R01][F08]). Il a été concédé alors que le juge validait l'entraînement en « fair use » [R01] : le coût vient de la *provenance* des données. *Concord II* reprend exactement cet angle (torrenting dissimulé, > 20 000 œuvres, > 3 Md$ [R03]) et vise personnellement le CEO [R03]. Sony/Warner : jusqu'à 150 000 $ par œuvre [R03]. Aucun jugement au fond : plafond de perte introuvable [F--].

2. **L'État américain est une contrepartie hostile et active.** Deux actions en 2026 : blacklistage défense, confirmé en appel [R05], et coupure à l'export des modèles phares pour tous les clients [R07]. Le poids direct est faible (< 1 % du CA [R06]), mais l'arme est puissante : le Commerce garde le droit de réimposer une licence [R07]. Un modèle qui ne peut plus être servi hors États-Unis frappe 31 % du CA du T3 (calcul : 5 249 / 16 956, à partir de [F07]).

3. **Concentration clients.** Deux clients ≈ 24 % du CA 2025 (2 × 12 % [R08]), soit ≈ 1,1 Md$ (calcul à partir de [R08][F03]), sans contrat long [R08] ; les coûts, eux, sont fixes (69,8 Md$ dus sous 12 mois [F27]).

## Les 3 risques que le comité doit garder en tête

1. **Engagements de calcul non résiliables (895,4 Md$ [F27]) × dépendance Taïwan / TSMC [R09] × concentration clients [R08]** : la structure de coûts est fixe ; l'offre (puces) et la demande (5 clients ≈ 25 % [R08]) sont fragiles.
2. **Risque souverain américain** : désignation de défense confirmée [R05], contrôle à l'export réimposable [R07]. Le S-1 reconnaît lui-même l'effet réputationnel [R06].
3. **Litiges sur les données d'entraînement** : 1,5 Md$ payés [R01], > 3 Md$ réclamés dans un seul dossier [R03], au moins cinq procédures musicales ou de données ouvertes [R03][R04], et un S-1 qui ne garantit pas la licéité de sa collecte [R13].

## Risque de perte définitive du capital : **moyen**

- **Contre** une perte totale : trésor ≈ 249 Md$ après IPO (calcul de `02-bull.md`, [F25][F37][F38]), flux opérationnel positif [F19], liquidité à court terme solide.
- **Pour** : (a) 895,4 Md$ d'engagements [F27] et 134 986 M$ de dette [F25] **passent avant l'action** ; si la croissance cale, la sortie est une restructuration ou des augmentations de capital massives, où l'actionnaire de classe A, sans contrôle [F54], est dilué jusqu'à l'effacement ; (b) sanction fédérale élargie [R05][R07] ou crise taïwanaise [R09] : événements binaires non assurables ; (c) l'actionnaire ne peut ni changer la direction ni s'opposer à une décision prise au nom de la mission [R12].
- Un recul de plus de **−50 %**, seuil de tolérance de Gabriel [P], est plausible : le Bear chiffre −35 % sans accident (`03-bear.md`). **À signaler explicitement.** Rien n'est vérifié dans le 424B4.
