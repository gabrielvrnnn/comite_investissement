# Vérification — Anthropic, PBC (ANT) — 2026-11-22 (1er passage)

Référence : `01-fiche.md` ([F01]-[F59], note §2, Ajouts du Risk manager [R01]-[R13]) et `profil-investisseur.md` ([P]). Tous les calculs ont été refaits (python).

## 1. Bilan par fichier

| Fichier | Agent | Chiffres contrôlés | KO | dont graves |
|---|---|---|---|---|
| 02-bull.md | Bull | 72 | 2 | 0 |
| 03-bear.md | Bear | 76 | 4 | 1 |
| 04-replique-bull.md | Bull | 55 | 0 | 0 |
| 05-replique-bear.md | Bear | 66 | 4 | 1 |
| 06-risques.md | Risk manager | 38 | 4 | 1 |
| 07-dca.md | Conseiller DCA | 48 | 3 | 2 |
| **Total** | | **355** | **17** | **5** |

Tous les calculs explicites sont justes (aucun KO-calcul arithmétique) : 3 796 / 4 585 = 82,8 % ; 131,8 + 91,6 + 26,0 = 249,4 Md$ ; 1 188 428 / 25 = 47,5 Md$ ; 16 956 × 4 = 67 824 M$ ; 895,4 / 35,282 = 25,4 ; 5 011 − 3 829 = 1 182 M$ (0,10 %) ; 18,27 / 13,37 = +36,6 % ; 176 410 × 6 / 18,27 Md ≈ 57,9 $ (−35 %) ; 88,91 × 18,27 / 6 = 270,7 Md$ (×7,7 ; 22,6 %/an) ; 25 × 67 824 / 18,27 Md ≈ 92,8 $ ; 1 188 428 / (67 824 × 0,3174) ≈ 55 ; 3 103 / 7 123 = 44 % ; 0,03 × 12 416 ≈ 372 €, etc.

Hypothèses correctement signalées (hors périmètre) : 25× FCF (Bull, réplique Bear), 20× FCF et CA ×5 / 6× CA (Bear), 25× CA T3 annualisé (réplique Bull), proportionnalité du seuil 44,5 $ (réplique Bear), poids 0 % / 5 % / 3 % / 12 % (DCA).

## 2. Tableau des KO

| # | Fichier | Agent | Citation exacte | Type de KO | Ce que dit la fiche | Correction demandée | Gravité |
|---|---|---|---|---|---|---|---|
| 1 | 02-bull.md (l. 6) | Bull | « passée en trois ans […] dont le CA croît de plus de 10× par an » | KO-calcul | 2023→2024 : 41 → 386 M$ = ×9,4 [F01][F02] ; ×11,9 en 2025 [F03] ; ×13,3 sur 9 mois 2026 [F04][F09] | « plus de 10× par an depuis 2025 », avec identifiants | mineur |
| 2 | 02-bull.md (l. 15) | Bull | « +1 127 % sur un an [S22] » | KO-identifiant (code source au lieu de Fxx) | Valeur présente dans la ligne [F05] (« presse : +1 127 % ») | Citer [F05] | mineur |
| 3 | 03-bear.md (l. 45) | Bear | « 895 Md$ d'engagements de calcul non résiliables [F27] auprès de ses propres concurrents » | KO-fait | [F27] : engagements d'achat et de location, sans ventilation complète ; principaux engagements nommés : Google ≈ 114,5, AWS ≈ 110,0, Microsoft ≈ 44,9 Md$ [F28] ; seuls Google et Microsoft sont cités comme concurrents (≈ 159 Md$) ; « généralement non résiliables » (§10, [S23]) | « 895 Md$ d'engagements, généralement non résiliables, dont ≈ 159 Md$ identifiés auprès de concurrents (Google, Microsoft [F28]) » | **grave** (phrase-thèse) |
| 4 | 03-bear.md (l. 53) | Bear | « 5 % des actions + 2 % à chaque hausse de 50 % de la valeur [F57] — le succès est taxé en actions » | KO-valeur (conditions omises) | [F57] : + 2 % **à la discrétion du conseil**, pour chaque hausse de 50 % **au-delà d'un seuil**, **sous réserve d'approbation des actionnaires** | Rétablir les trois conditions | moyen |
| 5 | 03-bear.md (l. 57) | Bear | « La mission d'intérêt public [S1] prime statutairement sur le rendement » | KO-fait | [S1] : mission déclarée ; [R12] : le S-1 avertit que les décisions « may conflict » avec les intérêts financiers. Aucune primauté statutaire dans la fiche | « peut entrer en conflit avec l'intérêt financier des actionnaires [R12] » | mineur |
| 6 | 03-bear.md (l. 61) | Bear | « concentration clients, guidance, use of proceeds : tous [F--] » | KO-valeur (obsolète) | [R08] : deux clients ≈ 12 % chacun du CA 2025 ; top 5 ≈ 25 % du CA 9 mois 2026 | Retirer la concentration clients de la liste [F--], citer [R08] | moyen |
| 7 | 05-replique-bear.md (l. 32) | Bear | « Concentration clients : [F--] » | KO-valeur (obsolète) | [R08] (idem #6) | Citer [R08] | moyen |
| 8 | 05-replique-bear.md (l. 36) | Bear | « Google + AWS + Microsoft portent ≈ 269,4 Md$ […] ; leur ticket en vaut 9,7 % » | KO-fait / KO-calcul | Les 26,0 Md$ [F38] sont souscrits par AMD, Broadcom, Google, Micron, Microsoft, NVIDIA et TSMC Partners : **Amazon/AWS n'y figure pas** ; la part de Google et Microsoft n'est pas détaillée → le « ticket » de ces trois fournisseurs est introuvable | « Le placement total (7 souscripteurs, sans Amazon [F38]) vaut 9,7 % des trois principaux engagements [F28] » ; part Google + Microsoft : introuvable [F--] | **grave** |
| 9 | 05-replique-bear.md (l. 44) | Bear | « le calcul est loué hors bilan » | KO-fait | [F27] : « engagements d'achat et de location » ; traitement comptable (bilan / hors bilan) non indiqué | Supprimer « hors bilan » ou écrire « introuvable » | mineur |
| 10 | 05-replique-bear.md (l. 57) | Bear | « Le risque est à 3-5 ans » | KO-sans-source | Seul calcul étayé : 249 / 69,8 ≈ 3,6 ans, à tranche annuelle constante ; borne de 5 ans sans entrée | « ≈ 3,6 ans à engagements annuels constants (calcul) » ou signaler « hypothèse » | mineur |
| 11 | 06-risques.md (l. 9) | Risk manager | « > 3 Md$ réclamés dans un seul dossier musical [R03], quatre autres en cours [R03][R04] » | KO-calcul (comptage) | Hors *Concord II* : *Concord I*, BMG, Round Hill, Sony/Warner [R03] + Reddit [R04] = **cinq** autres (Sony et Warner comptés ensemble) | « cinq autres » (cohérent avec « au moins cinq » l. 34, qui est juste) | mineur |
| 12 | 06-risques.md (l. 20 et l. 39) | Risk manager | « Dette de 130,5 Md$ […], rang avant l'action » ; « 895,4 Md$ d'engagements [F27] et 134 986 M$ de dette [F25] **passent avant l'action** » | KO-fait | Nature, échéances et **traitement à l'IPO** de la dette : introuvables ; « vraisemblablement » des convertibles réévaluées (§5 note, §11). Si elles sont converties à l'IPO, elles ne passent pas avant l'action. La fiche ne dit rien du rang des engagements d'achat | Mettre au conditionnel : « si cette dette n'est pas convertie à l'IPO (à vérifier dans le 424B4) » ; revoir la justification du « risque de perte définitive : moyen » | **grave** (fonde le verdict de risque) |
| 13 | 06-risques.md (l. 28) | Risk manager | « Deux clients ≈ 24 % du CA 2025 […], sans contrat long [R08] » | KO-valeur | [R08] : « **beaucoup** de grands clients sans contrat de long terme » ; rien de spécifique sur ces deux clients | « parmi des grands clients souvent sans contrat long [R08] » | mineur |
| 14 | 06-risques.md (l. 34) | Risk manager | « 1,5 Md$ payés [R01] » | KO-valeur | [R01] : payable en plusieurs versements ; [R02] : 1,2 Md$ encore en passif courant au 30/06/2026 | « 1,5 Md$ concédés, dont 1,2 Md$ encore dus au 30/06/2026 [R02] » | moyen |
| 15 | 07-dca.md (l. 49) | Conseiller DCA | « dette et 895,4 Md$ d'engagements passent avant l'action [F25][F27] » | KO-fait (reprise du #12) | idem #12 | idem #12 | **grave** |
| 16 | 07-dca.md (l. 63) | Conseiller DCA | « NVIDIA […] vend la puissance de calcul dont dépendent les 895,4 Md$ d'engagements [F27] » | KO-fait | La fiche ne présente NVIDIA que comme souscripteur du placement privé [F38] ; contreparties de calcul nommées : Google, AWS, Microsoft, Broadcom [F28] ; TSMC et HBM [R09] | « NVIDIA a souscrit au placement privé [F38] » ; lien fournisseur : introuvable [F--] | **grave** (argument central de concentration) |
| 17 | 07-dca.md (l. 64) | Conseiller DCA | « avec la même dépendance Taïwan / TSMC [R09] » | KO-fait | [R09] concerne Anthropic seulement ; dépendance d'Alphabet et NVIDIA à TSMC absente de la fiche | Retirer ou écrire « hors fiche » | mineur |

## Remarques (non KO)
- 03-bear.md l. 64 : la valeur issue de 6× le CA est comparée à la **VE** puis divisée par le nombre d'actions comme une capitalisation. Calcul juste ; écart VE / capitalisation faible ([F36]), mais à préciser.
- 03-bear.md l. 70 et 05 l. 54 : « +23 % au-dessus de la série H » compare une post-money privée (965 Md$ [F47]) à une capitalisation qui inclut ≈ 117,6 Md$ levés depuis ([F37][F38]). Calcul juste, comparaison à nuancer.
- 03-bear.md l. 51 : « SBC ×20 en deux ans » compare 2024 (annuel) à 12 mois au 30/09/2026 [F22] : ≈ 21 mois, toléré.
- 02-bull.md l. 26 : « croissance du CA de ×12 à ×13 par an » utilisée pour projeter jusqu'en 2036 : c'est un taux passé, l'extrapolation est une opinion, à formuler comme telle.
- 04-replique-bull.md l. 5 : « non résiliables [F28] » : la fiche dit « généralement non résiliables » (§10).
- 07-dca.md l. 55 : « plus-values taxées au CTO » : règle fiscale générale, absente de la fiche et du profil ; non chiffrée, tolérée.

## 3. Conclusion
**Corrections à renvoyer à : Bear (03, 05), Risk manager (06), Conseiller DCA (07), Bull (02, mineur).**
Priorité : #12 et #15 (rang de la dette, qui fonde le verdict « perte définitive : moyen »), #8 (AWS absent du placement privé), #16 (NVIDIA présenté comme fournisseur), #3 (895 Md$ « auprès de concurrents »), puis #6-#7 (concentration clients désormais sourcée par [R08]).
