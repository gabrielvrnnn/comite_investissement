# Vérification — note de décision LVMH (MC.PA), 2026-11-22

Périmètre : `decision.md`, contrôlé contre `01-fiche.md` (dont « Ajouts du Risk manager »), `profil-investisseur.md`, les répliques 04-05, `06-risques.md`, `07-dca.md` et le tableau « Contrôle des sources » de `08-verification.md`. Sources web non rouvertes (consigne du Président).

## 1. Bilan

| Fichier | Chiffres contrôlés | KO |
|---|---|---|
| decision.md | 54 (hors périmètre exclus : date, conviction 5/10 et 6 → 5, poids 5 %, plafond 25 %, cible 15 %, seuils 30 % et 10 %, horizon 10 ans) | **0** |

Contrôles de forme :
- Ligne « Outil d'aide à la réflexion, pas un conseil financier. » : **présente** (en tête).
- Mention conflit d'intérêts : présente (« pas de conflit », exact : LVMH hors périmètre IA).
- « Points non vérifiés » : liste bien **[R04], [R05], [R06]** (seuls identifiants « Source non lue » cités à l'appui d'un argument dans la note, raison contre n° 3, verdict, signaux) et **[F85]** ([W9]). [R07]-[R09] y figurent avec la mention « ne fondent pas le verdict » (exact : ils ne sont pas cités dans le corps). Aucun autre identifiant « Source non lue » n'est cité dans la note. **Conforme.**

### Calculs refaits
| Citation | Calcul | Résultat |
|---|---|---|
| ≈ 6 % par an dividende compris [F73][F74] | 28,75 × 17,41 = 500,5 ; (500,5 / 381,95)^(1/10) − 1 = 2,74 % ; + 3,40 % | 6,1 % → OK |
| ≈ 22,8 % du PEA | 1 209 / 5 293 | 22,84 % → OK |
| ROC 2025 ≈ +54 % vs 2019 | 17 755 / 11 504 − 1 | 54,3 % → OK |
| ≈ 1,75 fois les dividendes | 11 333 / 6 465 | 1,753 → OK |
| ≈ 68,9 % lignes françaises | (1 209 + 486 + 484 + 401 + 371 + 351 + 345) / 5 293 = 3 647 / 5 293 | 68,90 % → OK |
| ≈ 74 % du ROC | 13 209 / 17 755 | 74,4 % → OK |
| ≈ 439 € | 20 × 21,94 [F14] | 438,8 € → OK |

### Valeurs vérifiées contre la fiche (toutes OK)
[F24] 22,0 %, 66 %, 17 755 M€ · [F17][F18] 21,4 %, 11 504 M€ · [F33] ≈ 35 %, 13 209 M€, ROC −13 %, −2 % org. 9 mois, −5 % T3 · [F71] 381,95 €, MM200 458,10 € · [F100] 414,20 € fin 2019 · [F73] 17,41 ; ≈ 26,7 · [F74] 3,40 % · [F49] 9,9 % · [F31] 11 333 M€ · [F70] 6 465 M€ (2025) · [R01] ≈ 16 627 M€ · [F80] −49,8 % · [P] tolérance −50 %, seule ligne luxe, CTO 100 % américain · [F53] 19,94 % (2022) · [F57] 12,43 % (12 mois glissants) · [F66]-[F68] 13 € depuis l'exercice 2023 · [R04] 65,55 % des droits de vote, B. Arnault gérant et commandité · [R05] précédent de dérogation AMF · [R06] limite d'âge atteinte en 2034, aucun successeur désigné · [F99] 29 % des ventes en dollars · [F39] Asie hors Japon 26 %. Avis du Risk manager « perte définitive : faible » retrouvé dans 06-risques.md.

## 2. Tableau des KO

Aucun KO.

### Remarques non bloquantes (pas de correction exigée)
| # | Citation | Remarque | Correction suggérée |
|---|---|---|---|
| 1 | Tableau « Sources », absence de S6 | [F74] (3,40 %) a pour source [S5] ; [S6] dans la fiche. S6 manque au tableau. | Ajouter : `S6 \| stockanalysis.com, historique des dividendes \| 2022-2026 \| https://stockanalysis.com/quote/epa/MC/dividend/` |
| 2 | Ligne R04 du tableau « Sources » | Le document cite « Boursier.com via Bourse Direct » sans son URL (seule celle de Business Standard est donnée). | Ajouter l'URL Bourse Direct de [R04] (fiche, ligne R04). |
| 3 | Raison pour n° 2 : « on obtient ≈ 6 % par an (répliques 04 et 05) » | Pas d'identifiant à cet endroit ; les entrées [F73][F74] sont citées dans le verdict. Acceptable. | Facultatif : ajouter « [F73][F74] ». |
| 4 | « Je reprends le verdict du Conseiller DCA » | 07-dca.md écrit « Oui, en petite ligne », la note écrit « Oui, mais en petite ligne ». Simple différence de formulation, sans chiffre. | Facultatif. |

## 3. Contrôle des sources

Pas de nouvelle ouverture de sources (consigne). Classement repris de la passe 1 (`08-verification.md`) pour les identifiants cités dans la note :

| Identifiant | Source | Statut (passe 1) |
|---|---|---|
| [F24], [F31], [F33], [F49], [F73], [F80] (partie cours), [F14], [F68] | L1, L3, L4, S2, S3, S4, S5, E1 | Confirmée |
| [R01] | S4 | Confirmée |
| [R04], [R05], [R06] | presse, DILA (bloqué) | Source non lue → bien listés dans « Points non vérifiés » |
| [F85] | W9 | Source non lue → listé (bien que non cité dans le corps) |
| [F17], [F18], [F39], [F53], [F57], [F66], [F67], [F70], [F71], [F74], [F99], [F100] | L4, L7, L8, L12, L13, L15, L16, S3, S5, E1 | Non contrôlés en passe 1 (hors top 10) ; sources primaires LVMH ou S&P, pas « non lues » |

## 4. Conclusion

**Séance validée.** Aucun KO dans `decision.md`. Les remarques 1 et 2 (tableau des sources) peuvent être appliquées par le Président sans renvoi à un agent.
