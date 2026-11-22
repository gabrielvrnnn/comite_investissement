# 08 — Vérification : LVMH (MC.PA), séance du 2026-11-22 (passe 1)

Référence : `01-fiche.md` (y compris « Ajouts du Risk manager » [R01]-[R09]) et `profil-investisseur.md`.
Textes contrôlés : 02 à 07. Tous les calculs ont été refaits.

## 1. Bilan par fichier

| Fichier | Agent | Chiffres contrôlés (≈) | KO |
|---|---|---|---|
| 02-bull.md | Bull | ≈ 120 | 3 |
| 03-bear.md | Bear | ≈ 105 | 4 |
| 04-replique-bull.md | Bull | ≈ 80 | 3 |
| 05-replique-bear.md | Bear | ≈ 85 | 4 |
| 06-risques.md | Risk manager | ≈ 40 | 2 |
| 07-dca.md | Conseiller DCA | ≈ 80 | 2 |
| **Total** | | ≈ 510 | **18** |

Aucun identifiant inconnu. Aucun chiffre inventé. Toutes les valeurs citées avec un `[Fxx]`, `[Rxx]` ou `[P]` correspondent à la fiche ou au profil. Les KO portent sur des attributions (Sephora / Distribution sélective, identifiant [F75]), deux calculs mal construits et quelques affirmations que la fiche contredit ou ne contient pas.

## 2. KO

| # | Fichier | Agent | Citation exacte | Type de KO | Ce que dit la fiche | Correction demandée |
|---|---|---|---|---|---|---|
| 1 | 02-bull.md (§2) | Bull | « 26,5 % au pic de 2023 [F22] » | KO-fait | 2023 n'est pas le pic : 26,7 % en 2021 (calcul [F20]) et 26,6 % en 2022 (calcul [F21]), 26,5 % en 2023 [F22] | « 26,5 % à 26,7 % sur 2021-2023 [F20]-[F22] » ou « 26,5 % en 2023 [F22] » sans le mot « pic » |
| 2 | 02-bull.md (§3.2) | Bull | « Sephora suit : +6 % organique sur 9 mois et ROC 2025 en hausse de 28 % [F34] » | KO-fait (attribution) | [F34] = groupe d'activités **Distribution sélective** (Sephora **et** DFS), pas Sephora seul | « La Distribution sélective (Sephora, DFS) suit : +6 % organique sur 9 mois et ROC 2025 +28 % [F34] » |
| 3 | 02-bull.md (§5) | Bull | « Le contrôle familial est stabilisé par le projet Agache [F85] » | KO-fait | [F85] : *projet annoncé*, dont l'objectif affiché est d'« assurer la stabilité » ; AGE attendues en décembre 2026, dérogations AMF en attente ; source [W9] non vérifiée en primaire | « Le projet Agache vise à stabiliser le contrôle familial (objectif annoncé, non réalisé, non vérifié en primaire [F85]) » (le Bull l'a déjà concédé en 04 ; la thèse 02 doit être corrigée) |
| 4 | 03-bear.md (thèse en une phrase) | Bear | « Un PER de 17 » | KO-sans-source | PER 17,41 (12 mois glissants) [F73] | « Un PER d'environ 17 [F73] » |
| 5 | 03-bear.md (§1) | Bear | « vient de Sephora et de la joaillerie, et Sephora ne dégage qu'une marge de 9,7 % [F34] » | KO-fait (attribution) | 9,7 % = marge du groupe Distribution sélective (Sephora + DFS) [F34]. Sur 9 mois 2026, Vins et Spiritueux sont aussi à +5 % organique [F37] | « vient de la Distribution sélective (Sephora, DFS), de Montres et Joaillerie et des Vins et Spiritueux ; la Distribution sélective ne dégage qu'une marge de 9,7 % [F34] » |
| 6 | 03-bear.md (§7) | Bear | « La dette financière nette LVMH s'élève à 8 245 M€, mais la dette totale S&P atteint 37 151 M€ [F50]. L'écart de ≈ 28,9 Md€ (calcul) correspond probablement aux loyers » | KO-calcul (comparaison net / brut) | L'écart 37 151 − 8 245 compare une dette **brute** (S&P) à une dette **nette** (LVMH) : il inclut la trésorerie de 12 214 M€ [F50]. Comparaison homogène : dette nette S&P 24 937 M€ contre dette financière nette LVMH 8 245 M€ [F50], écart ≈ 16 692 M€ (calcul), proche des dettes locatives ≈ 16 627 M€ [R01] | « La dette nette S&P (24 937 M€) dépasse de ≈ 16,7 Md€ la dette financière nette LVMH (8 245 M€) [F50] (calcul) ; cet écart correspond aux dettes locatives (≈ 16 627 M€ [R01]) » |
| 7 | 03-bear.md (§5) | Bear | « le PDG renvoie à « 7-8 ans » [W8], soit pile notre horizon » | KO-fait (mineur) | Citation « 7-8 ans » [W8] ; l'horizon du profil est de 10 ans et plus [P] : 7-8 ans tombe *dans* l'horizon, pas « pile » dessus | « soit à l'intérieur de notre horizon de 10 ans [P] » |
| 8 | 04-replique-bull.md (Point 1) | Bull | « Sephora ne vaut que 9,7 % de marge, mais son ROC 2025 progresse de 28 % [F34] » | KO-fait (attribution) | Idem n° 2 : Distribution sélective (Sephora + DFS) [F34] | « La Distribution sélective (Sephora, DFS) ne vaut que 9,7 % de marge, mais son ROC 2025 progresse de 28 % [F34] » |
| 9 | 04-replique-bull.md (Point 3) | Bull | « l'absence de guidance trimestrielle ne m'empêche pas de juger » | KO-fait (mineur) | Aucune guidance chiffrée, ni annuelle ni trimestrielle [F--] (section 10 : « perspectives qualitatives seulement ») | « l'absence de guidance chiffrée [F--] ne m'empêche pas de juger » |
| 10 | 04-replique-bull.md (Point 9) | Bull | « Le rendement FCF de 7,6 % selon S&P, ou 6,0 % selon la définition LVMH [F75] » | KO-valeur (identifiant) | [F75] ne contient que la valeur S&P (P/FCF 13,10 → ≈ 7,6 %). Le 6,0 % est un calcul de la fiche à partir de [F31] et [F72] (11 333 / 188 339), note sous la section 8 | « 7,6 % selon S&P [F75], ou ≈ 6,0 % selon la définition LVMH (calcul de la fiche à partir de [F31] et [F72]) » |
| 11 | 05-replique-bear.md (Argument 1) | Bear | « le résultat net 2025 (10 878 M€ [F10]) est inférieur de 9,6 % à celui de 2021 (12 036 M€ [F06]) (calcul) : quatre ans de recul » | KO-fait | Le calcul −9,6 % est juste, mais il n'y a pas « quatre ans de recul » : RN 14 084 M€ en 2022 [F07] et 15 174 M€ en 2023 [F08], au-dessus de 2021. Le recul porte sur 2024 et 2025 seulement ([F09], [F10]) | « … inférieur de 9,6 % à celui de 2021 (calcul) : après le pic de 2023 [F08], deux années de recul (2024-2025, [F09][F10]) » |
| 12 | 05-replique-bear.md (Argument 4 et 3) | Bear | « ROC de Sephora +28 % [F34] » ; « Sephora, à 9,7 % de marge [F34] » | KO-fait (attribution) | Idem n° 2 : Distribution sélective (Sephora + DFS) [F34] | Remplacer « Sephora » par « la Distribution sélective (Sephora, DFS) » |
| 13 | 05-replique-bear.md (Argument 4) | Bear | « la joaillerie pèse 8,5 % du ROC (calcul : 1 514 / 17 755). Revenir à 2023 n'ajouterait que ≈ 3,6 % au ROC du groupe (calcul : 648 / 17 755) » | KO-calcul (entrées non citées) | Résultats justes (8,53 % ; 3,65 %), mais 17 755 = [F24] n'est cité nulle part dans 05 et 648 n'est pas dans la fiche (calcul du Bull : 2 162 [F106] − 1 514 [F35]) | « (calcul : 1 514 / 17 755, [F35][F24]) » ; « (calcul : (2 162 − 1 514) / 17 755, [F106][F35][F24]) » |
| 14 | 05-replique-bear.md (Arguments 2 et 12) | Bear | « Le ROIC a perdu 7,5 points en trois ans (19,94 % → 12,43 %, [F53][F57]) » ; « Au rythme actuel du ROIC (−2,5 points par an, calcul [F53][F57]), le seuil de 10 % sera franchi dans un an environ » | KO-calcul (période) | [F53] = exercice 2022 ; [F57] = 12 mois glissants au 30.06.2026 : 3,5 ans d'écart, pas 3. 7,51 / 3,5 ≈ −2,1 points par an (calcul) ; 12,43 − 10 = 2,43 points → ≈ 1,1 an à ce rythme | « 7,5 points en trois ans et demi » ; « (≈ −2,1 points par an, calcul [F53][F57]) … franchi dans un peu plus d'un an » |
| 15 | 06-risques.md (risque n° 1) | Risk manager | « Les conditions de sa révocation par les actionnaires commanditaires dépendront des statuts, qui ne sont pas publiés » | KO-fait | La fiche ne dit pas que les statuts ne sont pas publiés : [R04] indique seulement que le communiqué original n'a pas été ouvert et que les sites AMF / info-financiere n'ont pas été atteints | « … des statuts de la SCA, non consultés (absents du dossier) » |
| 16 | 06-risques.md (tableau, ligne Fiscalité) | Risk manager | « surtaxe d'IS de +4 points du taux d'impôt en 2025 … [W1][L1] » | KO-fait (attribution primaire) | Les +4 points viennent de la presse seule [W1], « non vérifié dans le communiqué » (section 10). [L1] ne contient que les 5,5 Md€ d'IS (vérifié : le chiffre des 4 points n'apparaît pas dans [L1]) | Source : « [W1] (presse, non vérifié dans le communiqué) » ; retirer [L1] ou le limiter aux 5,5 Md€ |
| 17 | 07-dca.md (§6) | Conseiller DCA | « rendement FCF ≈ 6,0 % selon LVMH [F75] » | KO-valeur (identifiant) | Idem n° 10 : [F75] = 7,6 % (S&P) ; 6,0 % = calcul de la fiche à partir de [F31] et [F72] | « rendement FCF ≈ 6,0 % selon LVMH (calcul de la fiche à partir de [F31] et [F72]) ; 7,6 % selon S&P [F75] » |
| 18 | 07-dca.md (§5) | Conseiller DCA | « l'ETF Stoxx Europe 600 [P] compte LVMH parmi ses composantes » | KO-fait | Ni la fiche ni le profil ne disent que LVMH fait partie du Stoxx Europe 600 (la fiche ne traite pas des indices). [P] ne couvre que la détention de l'ETF | Retirer l'affirmation ou la marquer « appartenance à l'indice : à faire sourcer par l'Analyste [F--] ». (Si l'Analyste veut l'ajouter : la lettre aux actionnaires [L15] cite les indices de LVMH, sans mention du Stoxx Europe 600.) |

### Observations (non bloquantes, pas de KO)
- 02 §7 : « Une succession désordonnée au sommet [F85] » : [F85] traite du projet Agache, pas de la succession (citation « 7-8 ans » [W8], section 10 ; [R06]). Mieux citer [W8].
- 03 scénario noir : « C'est au-delà de la tolérance de −50 % » : vrai pour ≈ −58,5 % (plus haut 2023 → plus bas, en séance [F80]) ; −49,8 % (clôtures) est *à* la limite. Préciser à quel chiffre on se réfère.
- 05 Argument 6 : les +8 % de cash-flow [F31] portent sur 2024 → 2025, mais l'explication utilise 2023 → 2025 (capex −39 %). Sur 2024 → 2025, capex −17 % (5 531 → 4 567 M€) et flux opérationnel stable (18 924 → 18 874 M€) [F30][F31] (calcul) : la conclusion tient, la base de comparaison est à aligner.
- 06 (dette locative) : le « seuil Bull de 25 % » est défini sur la dette nette publiée ; l'ajout des loyers change de définition. À présenter comme une relecture du seuil, pas comme un franchissement.
- 07 §6 : la publication du 25.01.2027 [S1] est une date **estimée** selon la fiche.
- 07 §3 : « sans impôt immédiat » dans le PEA : règle fiscale générale, absente du profil (non chiffrée ; à garder prudent).

## 3. Contrôle des sources

Identifiants contrôlés : tous les [Rxx], plus les [Fxx] les plus cités dans 02-07 : [F33] (22 citations), [F24] (17), [F68] (13), [F73] (12), [F10] (11), [F85] (9), [F50] (9), [F31] (9), [F22] (8), puis, à égalité pour la 10e place (7), [F80], [F49] et [F14].

| Identifiant | Source rouverte | Statut | Détail |
|---|---|---|---|
| [F33] | [L1], [L2], [L3] (lvmh.com, HTML) | **Confirmée** | 37 770 M€ (−8 % / −5 % org.), ROC 13 209 M€ (−13 %), marge 35 % [L1] ; S1 2026 18 146 M€, −1 % org., T2 +1 %, ROC 6 195 M€ (−7 %) [L2] ; 9 mois 26 391 M€, −2 % org., T3 −5 % [L3] |
| [F24] | [L1], [L4], [S2] | **Confirmée** | Marge brute 53 528 M€ / 66 %, ROC 17 755 M€ / 22,0 % [L4] ; S&P 66,24 % / 21,86 % / 17 668 M€ / 13,46 % [S2] |
| [F68] | [L1], [S5], [S3] | **Confirmée** | 13 € (acompte 5,50 € le 4 décembre, solde 7,50 € le 30 avril 2026) [L1] ; taux de distribution 59,43 % [S5] ; rachats 1 640 M€ [S3] |
| [F73] | [S5] (+ [S2]) | **Confirmée** | PER 17,41, prévisionnel 16,27, VE/EBITDA 9,24, VE/EBIT 12,31, P/B 2,77, P/CA 2,36 ; PER et VE/EBITDA 2021-2025 retrouvés ; moyennes recalculées 26,69 et 16,95 |
| [F10] | [L1], [L4], [S2] | **Confirmée** | CA 80 807 M€ (−5 % publié, −1 % org., change −3 %), RN 10 878 M€ (−13 %), RN total 11 222 M€ ; BPA 21,85 € [S2] |
| [F85] | [W9] (fashionunited.com, business-standard.com, nssmag) | **Source non lue** | Hôtes non résolus par le réseau de la session (business-standard.com testé : ENOTFOUND) ; seuls des extraits de recherche existent |
| [F50] | [L2], [S4], [S5] | **Confirmée** | Dette financière nette 8 245 M€ vs 10 176 M€ (−19 %) [L2] ; trésorerie 12 214 M€ (équivalents 6 803), dette totale 37 151 M€, dette nette S&P 24 937 M€ [S4] ; dette nette / EBITDA 1,24x [S5] |
| [F31] | [L1], [S3] | **Confirmée** | Cash-flow disponible d'exploitation 11 333 M€ (+8 %) [L1] ; flux opérationnel 18 874, capex −4 567, FCF 14 307 M€, 28,73 €/action [S3] |
| [F22] | [L4], [L12], [S2] | **Confirmée** | Marge brute 59 277 M€ / 69 %, ROC 22 802 M€ / 26,5 % [L4][L12] ; S&P 68,80 % / 26,44 % / 17,61 % [S2] |
| [F80] | [E1], [L15], [S2] | **Confirmée** (partie cours et BPA) | Clôture 754,80 € le 27.01.2025 (plus haut de clôture), 378,55 € le 02.10.2026 (plus bas de clôture), plus bas en séance 375,65 € le 13.10.2026, 376,00 € le 02.10.2026, 645,00 € au 31.12.2025, 463,10 € au 31.03.2026 [E1] ; 904,60 € plus haut 2023 [L15] ; calculs −49,8 %, −58,5 %, −28,2 % justes. Éléments de presse [W11][W12] non relus (non cités dans 02-07) |
| [F49] | [L1], [L15], [S4], [S5] | **Confirmée** | Dette financière nette 6 857 M€ (−26 %), capitaux propres 68 949 M€ [L1] ; ratio 9,9 % [L15] ; 13 520 / 36 779 / 23 259 M€ [S4] ; 1,13x [S5] |
| [F14] | [S2] (vue TTM) | **Confirmée** | CA 79 641 M€, RN 10 877 M€, BPA 21,94 € |
| [R01] | [S4] (stockanalysis, bilan) | **Confirmée** (+ correction de lecture) | 3 003 / 13 384 M€ au 31.12.2025 ; 3 118 / 13 509 M€, dette LT 13 049 M€, dette CT 6 003 M€ au 30.06.2026. **Mais** les « ≈ 1 472 M€ non expliqués » figurent sur la même page : « Current Portion of Long-Term Debt » 1 472 M€. 13 049 + 1 472 + 6 003 + 3 118 + 13 509 = 37 151 M€ (calcul) : la réconciliation est complète |
| [R02] | [S4] | **Confirmée** | Écarts d'acquisition 18 561 M€, autres incorporels 23 331 M€ (30.06.2026) ; 18 315 / 23 129 M€ (31.12.2025) |
| [R03] | live.euronext.com, Reuters, 03.08.2026 (page ouverte) | **Confirmée** (une réserve) | Participation de 34 %, option de vente « according to LVMH filings », participation valant « about €4.3 billion in 2025 », arbitrage de 2020 sur 181 M€ de dividendes 2019 : retrouvés. « Deux entités » : absent de l'article. La page ouverte décrit une condition de l'option : le Risk manager peut relire et compléter [R03], puis retirer la mention « extraits de recherche uniquement » |
| [R04] | boursedirect.fr, business-standard.com | **Source non lue** | Hôtes inaccessibles (curl : pas de connexion ; WebFetch : ENOTFOUND). www.amf-france.org joignable, mais recherche dynamique sans document exploitable ; www.info-financiere.fr : pas de réponse |
| [R05] | echanges.dila.gouv.fr | **Source non lue** | Hôte bloqué |
| [R06] | rte.ie, fortune.com | **Source non lue** | Hôtes inaccessibles (rte.ie : ENOTFOUND) |
| [R07] | fashionunited.fr, thefashionlaw.com | **Source non lue** | Hôtes inaccessibles (fashionunited.fr : ENOTFOUND) |
| [R08] | moodiedavittreport.com, lejournaldesentreprises.com | **Source non lue** | Hôtes inaccessibles (moodiedavittreport.com : ENOTFOUND) |
| [R09] | commission.europa.eu, vie-publique.fr, euronews.com | **Source non lue** | Hôtes inaccessibles (commission.europa.eu : ENOTFOUND) |

Aucun **KO-source** : chaque chiffre retrouvé dans un document ouvert est identique à la fiche.

Remarque à l'Analyste (non bloquante) : la page [S3] contient une ligne « Free Cash Flow After Leases » égale, de 2021 à 2025, au cash-flow disponible d'exploitation LVMH (13 531 / 10 113 / 8 104 / 10 478 / 11 333 M€). L'hypothèse « écart dû aux loyers IFRS 16, non vérifié » de la section 4 peut passer en « vérifié sur [S3] ».

### Identifiants classés « Source non lue »
- Contrôlés dans cette passe : **[F85]** ([W9]), **[R04]**, **[R05]**, **[R06]**, **[R07]**, **[R08]**, **[R09]**.
- Cités dans 02-07 mais déjà marqués non vérifiés par la fiche, non rouverts (hors top 10) : [F81]-[F84] ([W8]), [F58] et [F77] ([W10]), BPA 2019 de [F04] et BPA de [F78] ([W5]), citation « 7-8 ans » et « rumeurs de divisions » ([W8], [W2]), surtaxe d'IS ([W1]).
- Hôtes à faire autoriser pour lever ces réserves : business-standard.com, boursedirect.fr, fashionunited.com / .fr, thefashionlaw.com, rte.ie, fortune.com, moodiedavittreport.com, lejournaldesentreprises.com, commission.europa.eu, vie-publique.fr, euronews.com, echanges.dila.gouv.fr ; www.info-financiere.fr n'a pas répondu.

## 4. Conclusion

**Corrections à renvoyer à : Bull (02, 04), Bear (03, 05), Risk manager (06, et lecture de [R01] / [R03]), Conseiller DCA (07).**
Pas de correction de fiche demandée à l'Analyste (aucun KO-source) ; remarque facultative sur [S3] ci-dessus et, s'il le souhaite, identifiant à créer pour l'appartenance de LVMH au Stoxx Europe 600 (KO n° 18).
