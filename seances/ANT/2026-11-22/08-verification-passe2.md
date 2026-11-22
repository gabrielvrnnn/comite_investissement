# Vérification — Anthropic, PBC (ANT) — 2026-11-22 (2e passage)

Référence : `01-fiche.md` ([F01]-[F59], Ajouts du Risk manager [R01]-[R15]) et `profil-investisseur.md` ([P]). Textes contrôlés : 02, 03, 05, 06, 07 (versions corrigées). Tous les calculs refaits (python).

## 0. Nouveaux ajouts de la fiche
| ID | Source | Statut |
|---|---|---|
| [R14] | [S41] : S-1, S-1/A n° 1 et n° 2, prospectus (URL sec.gov, Fidelity, ipo.anthropic.com), 2026 — extraits via résumé WebSearch, documents non lus | **Sourcé** (secondaire, signalé comme tel) |
| [R15] | [S42] : TechCrunch 27/10/2026, fourweekmba, tech-insider, cryptobriefing, FWP SEC (URL), 2026 — résumés WebSearch, sites non lus | **Sourcé** (secondaire, divergences de nombre d'actions signalées) |

Remarque à l'Analyste (non KO) : la §11 de la fiche liste toujours « [F--] Nature […] de la dette (convertibles ?) » et « [F--] Concentration clients », désormais en partie couverts par [R14] et [R08].

## 1. Statut des 17 KO de la passe 1

| # | Fichier | Statut | Contrôle |
|---|---|---|---|
| 1 | 02 l. 6 | Résolu | ×11,9 (4 585/386) ; ×13,3 (33 242/2 500) ; ×9,4 (386/41) : justes, identifiants cités |
| 2 | 02 l. 15 | Résolu | [F05] |
| 3 | 03 l. 6 | Résolu | « généralement non résiliables » (fiche §10) ; 114,5 + 44,9 = 159,4 Md$ [F28] |
| 4 | 03 l. 14 | Résolu | trois conditions de [F57] rétablies |
| 5 | 03 l. 18 | Résolu | « peut entrer en conflit » [R12] |
| 6 | 03 l. 22 | Résolu | [R08] cité, valeurs exactes |
| 7 | 05 l. 5 | Résolu | [R08] cité, valeurs exactes |
| 8 | 05 l. 9 | Résolu | sept souscripteurs sans Amazon [F38] ; 26,0 / 269,4 = 9,65 % ; part Google + Microsoft [F--] |
| 9 | 05 l. 17 | Résolu | « hors bilan » supprimé ; 69,8 / 0,945 = 74 |
| 10 | 05 l. 30 | Résolu | 249 / 69,8 = 3,57 ans, hypothèse explicite |
| 11 | 06 l. 9 | Résolu | « cinq autres » |
| 12 | 06 l. 20, l. 38-40 | Résolu sur le fond (rang de la dette retiré, [R14][R15] cités) — **mais nouveau KO N2** | voir tableau §3 |
| 13 | 06 l. 28 | Résolu | « parmi des grands clients souvent sans contrat long [R08] » ; 2 × 12 % × 4 585 = 1,1 Md$ |
| 14 | 06 l. 24, l. 34 | Résolu | [R01] + [R02] |
| 15 | 07 l. 9 | Résolu pour la passe 1 (conditionnel) — **mais obsolète depuis [R14] : nouveau KO N1** | voir tableau §3 |
| 16 | 07 l. 23 | Résolu | NVIDIA = souscripteur [F38] ; lien fournisseur [F--] |
| 17 | 07 l. 24 | Résolu | « hors fiche » |

## 2. Bilan par fichier (2e passage)

| Fichier | Agent | Chiffres contrôlés | KO nouveaux | dont graves |
|---|---|---|---|---|
| 02-bull.md | Bull | 70 | 0 | 0 |
| 03-bear.md | Bear | 78 | 1 | 0 |
| 05-replique-bear.md | Bear | 68 | 1 | 0 |
| 06-risques.md | Risk manager | 47 | 1 | 0 |
| 07-dca.md | Conseiller DCA | 48 | 1 | 0 |
| **Total** | | **311** | **4** | **0** |

Calculs nouveaux ou modifiés, tous justes : 47,5 / 5,011 = 9,5× ; 114,5 + 44,9 = 159,4 Md$ ; 26,0 / 269,4 = 9,7 % ; 69,8 / 35,282 = 2,0× ; 249 / 69,8 = 3,6 ans ; 1,5 / 35,3 = 4,3 % ; 2 × 12 % × 4 585 ≈ 1,1 Md$ ; 895,4 / 249,4 = 3,6× ; 3 103 / 7 123 = 44 % ; 985 / 12 416 = 8 % ; 0,03 × 12 416 = 372 € (« ≈ 370 € ») ; seuil Bull ≈ 93 $ (25 × 67 824 / 18,27 Md = 92,8 $, `04-replique-bull.md` l. 24). Calculs inchangés de la passe 1 refaits : justes.

## 3. Tableau des KO restants

| # | Fichier | Agent | Citation exacte | Type de KO | Ce que dit la fiche | Correction demandée | Gravité |
|---|---|---|---|---|---|---|---|
| N1 | 07-dca.md (l. 9, passage corrigé) | Conseiller DCA | « la dette de 134 986 M$ [F25] passerait avant l'action si elle n'est pas convertie à l'IPO — à vérifier dans le 424B4 : nature et traitement introuvables [F--], vraisemblablement des convertibles (fiche §5) », présenté comme fondement du « moyen » du Risk manager | KO-valeur (obsolète) | [R14] : 130 502 M$ = obligations convertibles, converties en classe N juste avant la clôture de l'IPO ; [R15] : reliquat Amazon converti par trimestres, rang et montant résiduel introuvables. `06-risques.md` corrigé : « l'argument dette tombe », « moyen » fondé sur [F27], [R05][R07][R09], [R12] | « Dette : obligations convertibles converties en classe N à l'IPO [R14] ; reliquat converti par trimestres, rang et montant résiduel introuvables [R15]. Le Risk manager fonde le "moyen" sur les engagements [F27], les risques binaires et la gouvernance » | moyen |
| N2 | 06-risques.md (l. 38, passage corrigé) | Risk manager | « la « dette » de 134 986 M$ [F25] […] ce sont, selon les extraits du S-1/A, des obligations convertibles […] [R14] » | KO-valeur | [R14] identifie 130 502 M$ (la dette long terme de [F25]) comme convertibles ; 134 986 − 130 502 = 4 484 M$ de nature non indiquée | « 130 502 M$ sur 134 986 M$ [F25] sont des obligations convertibles [R14] ; ≈ 4,5 Md$ restants (calcul) : nature introuvable [F--] » ; nuancer « pas par un rang avant l'action » en conséquence | mineur |
| N3 | 03-bear.md (l. 22, passage corrigé) | Bear | « dette de 130,5 Md$ de nature inconnue [F25] » | KO-valeur (obsolète) | [R14] : obligations convertibles converties en classe N à l'IPO ; inconnus : montant restant après IPO [R14], rang, taux, échéance du reliquat [R15] | « dette de 130,5 Md$ : convertibles [R14], montant résiduel et rang introuvables [R15] » | mineur |
| N4 | 05-replique-bear.md (l. 21) | Bear | « 134 986 M$ de dette [F25] de nature inconnue [F--] » | KO-valeur (obsolète) | idem N2-N3 | « dont 130 502 M$ de convertibles converties en classe N à l'IPO [R14] ; reliquat [R15] et ≈ 4,5 Md$ : nature introuvable » | mineur |

## Remarques (non KO)
- 06 l. 17 : « mission pouvant primer sur l'intérêt financier [R12] » : [R12] dit « may conflict ». Aligner sur la formule corrigée du Bear (03 l. 18).
- 06 l. 32 : « Engagements de calcul non résiliables » : la fiche dit « généralement non résiliables » ; l. 39, la citation « généralement non résiliables » vient de la fiche §10 / [F28], pas de [F27].
- 06 l. 39 (c) : « l'actionnaire ne peut ni changer la direction… » : citer aussi [F54] (classe F à 50,1 %) ; [R12] prévoit une modification des statuts par supermajorité d'actionnaires.
- 06 l. 12 : colonne « partiel (Bear : « [F--] ») » : le Bear cite désormais [R08].
- 06 l. 20 : « 1 563 617 444 actions N émissibles » attribuées au reliquat Amazon : [R15] parle des « billets restants » dans le paragraphe Amazon. Acceptable.
- Remarques de la passe 1 maintenues : 03 l. 25 (valeur à 6× CA comparée à la VE puis divisée par le nombre d'actions), 03 l. 31 et 05 l. 27 (+23 % vs série H, comparaison post-money / capitalisation à nuancer).

## 4. Conclusion
**Corrections à renvoyer à : Conseiller DCA (07, N1), Risk manager (06, N2), Bear (03 N3, 05 N4).**
Les 17 KO de la passe 1 sont résolus. Restent 4 KO, aucun grave, tous liés à la nature de la dette depuis [R14]/[R15]. Priorité : N1 (le DCA attribue au Risk manager un argument que celui-ci a retiré).
