# Vérification — Anthropic, PBC (ANT) — 2026-11-22 (décision finale)

Référence : `01-fiche.md` ([F01]-[F59], [R01]-[R15]), `profil-investisseur.md` ([P]). Texte contrôlé : `decision.md` (non modifié). Attributions recoupées dans `04-replique-bull.md`, `06-risques.md`, `07-dca.md`, `08-verification-passe2.md`. Calculs refaits (python).

## 1. Bilan

| Fichier | Chiffres contrôlés | KO |
|---|---|---|
| decision.md | 62 | 3 |

**Attributions aux agents : conformes.**
- Seuil ≈ 93 $ du Bull : `04-replique-bull.md` l. 24 (25 × 67 824 / 18 270 = 92,8 $).
- Conseiller DCA : 0 % aujourd'hui, 5 % du DCA, plafond ligne 3 % du PEA + CTO, plafond IA cumulé (ANT + Alphabet + NVIDIA) 12 %, conditions (424B4 lu, ≥ 1 publication trimestrielle, premiers déblocages [F59], cours < ≈ 93 $, entrée sur 12 mois minimum) : `07-dca.md` l. 30-39.
- Risk manager « perte définitive : moyen (limite basse) », fondé sur [F27], [R05][R07][R09], gouvernance, plus sur la dette : `06-risques.md` l. 36-46.

**Calculs refaits, justes** : 4 585 / 386 = ×11,9 ; 18,27 / 13,22 = +38,2 % ; 131,8 + 91,6 + 26,0 = 249,4 Md$ ; 5 011 − 3 829 = 1 182 M$ ; 1 182 / 1 188 428 = 0,099 % (« ≈ 0,1 % ») ; 69 800 / (16 956 × 4) = 1,029 (« ≈ 1,03 »). Valeurs sourcées conformes : [F02] [F03] [F05] [F12] [F13] [F14] [F19] [F22] [F27] [F28] [F34] [F36] [F39] (33,68-33,77 → « 33,7 ») [F41] (237,16) [F45] [F48] [F50] [F54] [F59] [R05] [R07] [R08] [R09] [R12] [R14] [R15] [P].

## 2. KO

| # | Ligne | Citation exacte | Type de KO | Ce que disent la fiche / les textes | Correction demandée |
|---|---|---|---|---|---|
| D1 | 46 | « Monte au-dessus de ≈ 1,0 (69,8 Md$ [F27] / (16 956 M$ [F05] × 4) ≈ 1,03) » | KO-calcul (seuil incohérent) | Le ratio actuel calculé est 1,03 : il est **déjà** au-dessus du seuil de 1,0. Le signal serait déclenché dès aujourd'hui. | Fixer un seuil supérieur au niveau actuel (ex. « remonte au-dessus de 1,03, niveau au 30/09/2026 ») ou formuler « ne baisse pas sous ≈ 1,0 au prochain trimestre ». Choix du seuil : Président. |
| D2 | 59 | « 4 KO mineurs restent […] : ils décrivent encore la dette comme « de nature inconnue » » | KO-fait | `08-verification-passe2.md` : N1 (07-dca) est de gravité **moyen**, pas mineur ; N2 (06-risques) ne dit pas « nature inconnue » mais attribue à tort les 134 986 M$ [F25] entiers aux convertibles, alors que [R14] n'en couvre que 130 502 M$ (≈ 4,5 Md$ de nature introuvable). | « 4 KO restent (1 moyen, 3 mineurs) dans 03, 05, 06, 07 : la dette y est décrite comme de nature inconnue (03, 05, 07) ou entièrement assimilée aux convertibles (06 : 130 502 M$ sur 134 986 M$ seulement [R14]). » |
| D3 | 35 | « Anthropic reste un des 2-3 fournisseurs de modèles de pointe » | KO-sans-source | Aucun classement ni nombre de fournisseurs de pointe dans la fiche. | « Anthropic reste un fournisseur de modèles de pointe » (ou nombre « introuvable [F--] »). |

## 3. Conclusion
Corrections à renvoyer à : **Président** (`decision.md`, D1 à D3). Aucun KO sur les éléments attribués au Bull, au Conseiller DCA et au Risk manager.
