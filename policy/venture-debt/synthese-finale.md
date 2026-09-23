# Synthèse finale — Un compartiment prudentiel bancaire pour la venture debt (CRR/CRD)

**Pipeline :** `/eu-financial-policy`, dossier `policy/venture-debt/`
**Date :** 23 septembre 2026
**Statut :** propositions de politique publique stress-testées (évaluation d'impact Better Regulation + faisabilité politique). Aucune rédaction législative (non demandée).

---

## 1. La question et la réponse en une phrase

**Question posée :** peut-on introduire, dans la régulation bancaire européenne (CRR/CRD), un compartiment prudentiel spécifique pour la venture debt, à la manière du traitement « specialised lending » du project finance — en tenant compte de ses spécificités (séniorité/subordination, warrants, covenants, insolvabilité) ?

**Réponse :** oui, mais pas littéralement comme une sixième sous-catégorie de *specialised lending*. La venture debt échoue structurellement au triple test de l'art. 147(8) CRR (entité ad hoc, contrôle sur un actif physique, remboursement par les revenus de cet actif) : ce n'est pas un oubli du texte, c'est une incompatibilité de définition. La voie retenue est un compartiment **« incrémental par la méthode, sui generis par la définition »** : une nouvelle sous-catégorie de la classe « entreprises » — l'**exposition de venture debt qualifiée (VDQ)** — qui réutilise l'architecture, la gouvernance et la logique du *specialised lending* (slotting supervisé, RTS de l'EBA, volets standard et IRB) sans en porter l'étiquette juridique.

Le paquet est **neutre en capital au lancement** : aucune exposition conforme aux critères de qualité ne voit sa pondération changer. La valeur ajoutée immédiate est ailleurs — lisibilité, sécurité juridique, données, garde-fous — et tout recalibrage futur (à la hausse comme à la baisse) est conditionné à des données de pertes européennes qui n'existent pas encore.

---

## 2. La méthode : cinq rapports de cadrage, treize propositions, deux rounds de stress-test

| Étape | Agent | Résultat |
|---|---|---|
| Cadrage 1 | `current-regulation-analyst` | `current-regulation.md` — la venture debt échoue au triple test de l'art. 147(8) ; CRR3 a créé un traitement standardisé dédié pour le *specialised lending* (art. 122a) ; aucune position EBA/Commission/BCE spécifique identifiée |
| Cadrage 2 | `micro-financial-analyst` | `micro-analysis.md` — profil de risque bimodal par stade (NCO ~9,7 % *early stage* vs ~1,4 % *growth stage*) ; warrants faible effet en capital, forte friction juridique ; covenants = déclencheurs de contrôle, pas des tests de couverture |
| Cadrage 3 | `macro-financial-analyst` | `macro-analysis.md` — pas de risque systémique par la taille (~0,06-0,09 % des actifs bancaires zone euro) ; SVB est une leçon de passif, pas de crédit ; un compartiment n'est « ni nécessaire ni suffisant » pour combler l'écart transatlantique |
| Cadrage 4 | `benchmarking-analyst` | `benchmarking.md` — aucun précédent de compartiment Pilier 1 dédié dans le monde ; le précédent le plus transposable est une guidance de Pilier 2 (OCC, États-Unis) |
| Cadrage 5 | `stakeholder-mapper` (initial) | `stakeholder-map.md` — modification de niveau 1 par codécision requise ; agenda EBF/EBA déjà occupé ; insolvabilité = ligne rouge potentielle pour les États membres |
| Proposition | `policy-innovator` | `proposals.md` — 13 propositions initiales |
| Impact round 1 | `impact-assessment-auditor` | **P2 en échec** (pondération à 130 % du stade précoce jugée infondée) ; 12 autres propositions « passent avec modification » |
| Réponse round 2 | `policy-innovator` | Paquet révisé : neutralité en capital au lancement, 4 désaccords motivés soumis |
| Impact round 2 | `impact-assessment-auditor` | **Paquet PASSE**, avec 7 réserves (R-1 à R-7) |
| Faisabilité round 1 | `stakeholder-mapper` | Viable politiquement, 2 ajustements recommandés (trancher R-5, intégrer R-1 à R-4 avant dépôt) |
| Réponse round 3 | `policy-innovator` | Ajustements intégrés dans `proposals.md` |
| Faisabilité round 2 (finale) | `stakeholder-mapper` | **Verdict final : PASSE.** Risque dominant (abandon faute de portage politique dans un calendrier 2027 chargé) inchangé mais non aggravé |

Le paquet final est donc passé deux fois devant un contrôle de rigueur réglementaire (Better Regulation) et deux fois devant un contrôle de faisabilité politique, avec des corrections effectivement intégrées à chaque tour — pas seulement déclarées.

---

## 3. Glossaire minimal

- **RWA / pondération (RW)** : montant d'exposition pondéré par le risque. Fonds propres minimaux = 8 % des RWA (+ coussins). 100 % de pondération = 8 centimes de fonds propres par euro prêté.
- **Approche standard (SA)** : pondérations forfaitaires fixées par le règlement.
- **Approche IRB** : la banque estime elle-même PD (probabilité de défaut) et LGD (perte en cas de défaut), sous agrément du superviseur.
- **Slotting** : méthode IRB simplifiée — l'exposition est classée dans une catégorie qualitative (solide/bon/satisfaisant/faible/défaut) à pondération fixe. Conçue pour les actifs dont l'historique de défauts est trop mince pour estimer une PD — exactement le cas de la venture debt aujourd'hui.
- **EL / UL** : perte attendue (absorbée par les provisions) / perte inattendue (couverte par les fonds propres).
- **Output floor** : plancher — les RWA calculés en IRB ne peuvent descendre sous 72,5 % (à partir de 2030) des RWA calculés en approche standard. Conséquence directe pour ce dossier : sans volet standard dédié, tout allègement IRB serait neutralisé.
- **Facteur de soutien** (*supporting factor*) : coefficient réducteur appliqué après le calcul des RWA (ex. facteur PME, art. 501 CRR). Le paquet n'en crée aucun nouveau.
- **VDQ** : « exposition de venture debt qualifiée », la nouvelle sous-catégorie sui generis proposée. Deux paliers : **VDQ-P** (stade précoce, revenus < 5 M€) et **VDQ-C** (croissance, ≥ 5 M€).

---

## 4. Pourquoi pas une sixième catégorie « specialised lending »

Trois raisons, au-delà de l'incompatibilité du triple test :

1. **Garde-fou macroprudentiel.** Les lignes directrices BCE sur les opérations à effet de levier (2017) excluent le *specialised lending*. Coller cette étiquette à la venture debt en ferait sortir automatiquement le risque de levier bancaire — un effet de bord non désiré. Une catégorie *sui generis* rend ce garde-fou indépendant d'une décision de la BCE.
2. **Collision avec l'agenda de la Commission.** La communication COM(2026) 615 réserve le *specialised lending* aux « investissements stratégiques » et au financement de projets. Rester hors de l'étiquette évite une collision, tout en permettant de voyager dans le même paquet législatif.
3. **Agenda déjà occupé.** L'EBF et l'EBA travaillent déjà sur le *specialised lending* classique (planchers de LGD, collatéral, output floor), sans mention de la venture debt.

**Coût assumé** : une catégorie *sui generis* a une emprise de niveau 1 (modification par codécision Parlement/Conseil) plus large qu'une simple sixième sous-catégorie. Chaque renvoi du CRR au *specialised lending* doit être dupliqué pour la VDQ.

---

## 5. Les treize propositions, par thème

### A. Le compartiment de Pilier 1 (socle réduit)

| # | Proposition | En bref |
|---|---|---|
| **P1** | Définition *sui generis* « VDQ » | Deux types de critères : **caractérisation** (C1-C3, objectifs, classement obligatoire — soutien d'un investisseur qualifié, dépendance au financement externe, nature de la créance) et **qualité** (Q1-Q5 — LTER ≤ 40 %, covenant de trésorerie, maturité ≤ 6 ans, warrant détachable, sûretés). Une VDQ non conforme aux critères de qualité est traitée moins favorablement mais ne sort jamais vers le *corporate* générique. Deux paliers : VDQ-P (< 5 M€ de revenus) et VDQ-C (≥ 5 M€) |
| **P2** | Volet approche standard | Article dédié, pondérations **neutres au lancement** : 100 % pour toute VDQ conforme (cumulable avec le facteur PME existant — c'est le statu quo). Seule hausse : les VDQ **non conformes** (100 % sans facteur PME). Toute hypothèse de durcissement (ex. 130 % pour le stade précoce) est renvoyée à un rapport EBA sur données réelles |
| **P3** | Volet IRB : *slotting* dédié | Grille de classement optionnelle, calquée sur les valeurs bâloises HVCRE (jamais transposées en UE) pour le stade précoce, et sur les valeurs *specialised lending* classiques pour le stade croissance. Règle transitoire encadrée jusqu'au RTS (~2031) |
| **P4** | Catégories dormantes | Aucun allègement n'est actif au lancement. L'activation future exige des critères objectifs sur données de l'Union (profondeur, couverture d'une phase basse du cycle VC, pertes attendues, parité avec la formule IRB à 99,9 %, corrélation). Tout élément activé s'éteint de plein droit après 5 ans sauf reconduction sur preuve — **réversibilité garantie par construction** |

### B. Covenants, séniorité et tranches

| # | Proposition | En bref |
|---|---|---|
| **P5** | Covenants | Reconnus comme des **déclencheurs de contrôle**, pas des tests de couverture de flux (l'EBITDA est négatif par construction). Migrations de pondération lissées (hystérésis symétrique), dérogations dures inscrites au niveau 1, clarification de la *forbearance* dans les strictes limites de l'art. 47b CRR |
| **P6** | Séniorité et tranches | Architecture « **banque en senior, fonds en junior** » via des facilités **distinctes** liées par un accord inter-créanciers (pas un découpage d'un même prêt, pour éviter la requalification en titrisation). Le junior reste traité normalement (art. 128, 150 %) — aucun allègement du junior. Frontière avec le règlement Titrisation clarifiée par une simple demande de Q&A, sans toucher au règlement lui-même (en cours de trilogue) |

### C. Warrants

| # | Proposition | En bref |
|---|---|---|
| **P7** | Warrants / *equity kickers* | L'effet en capital est marginal (~3 pb/an). La vraie friction est juridique : une Q&A confirme que les warrants détenus avec une intention de long terme (≥ 3 ans) restent pondérés à 250 % (et non 400 %) même en cas de cession **subie** (sortie forcée, rachat imposé) ; interdiction d'imputer leur valeur en réduction des pertes ; clarification pour les conversions dette-actions en restructuration |

### D. Pilier 2, garde-fous et données

| # | Proposition | En bref |
|---|---|---|
| **P8** | Section « venture debt » dans les orientations EBA sur l'octroi de prêts | Transpose la guidance de supervision américaine (OCC), qui n'a jamais touché au Pilier 1. Recommandation à la BCE d'adapter sa guidance sur l'effet de levier |
| **P9** | Concentration, liquidité, résolution | Plafond de 10 % des fonds propres pour tout élément préférentiel futur ; suivi des dépôts liés à l'écosystème VC (leçon de SVB : le risque était au passif, pas au crédit) ; coussin sectoriel macroprudentiel prêt mais non activé |
| **P10** | **Préalable du paquet** : collecte de données | Aucune série de pertes européenne n'existe aujourd'hui. Collecte rétrospective depuis 2019, nouveau reporting réglementaire, protocole avec le groupe BEI. Conditionne tout recalibrage futur, à la hausse comme à la baisse |

### E. Partage des risques public (mesure autonome)

| # | Proposition | En bref |
|---|---|---|
| **P11** | Garantie InvestEU/FEC « dette de croissance » | **Découplée** du volet CRR (une garantie plafonnée ne produit pas l'allègement en capital annoncé initialement — erreur corrigée). Fenêtre non plafonnée ciblée sur les tickets de croissance (8,25-25 M€) que le produit existant ne couvre pas ; partage de l'*upside* des warrants avec le garant public |

### F. Insolvabilité (volet découplé)

| # | Proposition | En bref |
|---|---|---|
| **P12** | Rang des créances | Approche graduée : **niveau 1** (immédiat) = cartographie comparative des 27 droits nationaux ; **niveau 2** (conditionnel aux résultats de la cartographie) = reconnaissance de la subordination contractuelle **entre les parties seulement**, sur le modèle étroit de la directive BRRD 2017/2399 (rang harmonisé pour une seule catégorie d'instruments, à un objectif limité) ; **niveau 3** (rang opposable à tous les créanciers) : **écarté** — le prêteur de venture debt est déjà senior et sécurisé, son problème est la reconnaissance de son rang, pas l'obtention d'un rang supérieur |

### G. Cohérence et séquençage

| # | Proposition | En bref |
|---|---|---|
| **P13** | Cohérence bâloise, véhicule, séquençage | Recensement honnête des écarts par rapport à Bâle (un seul écart de méthode au lancement, immatériel) ; véhicule = chapitre distinct et séparable du paquet législatif T1 2027 |

---

## 6. Le calendrier en trois phases

| Phase | Période | Contenu | Sans niveau 1 ? |
|---|---|---|---|
| **0 — cœur du paquet, solution de repli autonome** | Fin 2026 → 2028 | Collecte de données, Q&A (warrants, *forbearance*, titrisation), recommandation à la BCE, programmation de la garantie InvestEU, cartographie de l'insolvabilité | **Oui — aucune codécision nécessaire** |
| **1 — socle de niveau 1 réduit** | Proposition T1 2027 ; adoption ~2028 ; application ~2029-2030 ; RTS ~2031 | Définition VDQ, volets standard et IRB à pondérations neutres, catégories dormantes, plafond de concentration | Non — codécision requise |
| **2 — paramètres de Pilier 1 sur données** | À partir de 2031 | Rapport EBA à 3 ans ; activation, désactivation ou reconduction des catégories dormantes selon les données réelles | Actes délégués, sous double contrôle du Parlement et du Conseil |

**Point clé de robustesse politique** : la phase 0 tient seule. Si le chapitre de niveau 1 n'entre pas dans le paquet législatif de 2027, l'essentiel de la valeur ajoutée (données, sécurité juridique, garde-fous) est déjà acquis.

---

## 7. Impact en capital : ce qui change vraiment

| Configuration | Aujourd'hui | Au lancement (Phase 1) |
|---|---|---|
| VDQ-C conforme, non PME | 100 % | 100 % — **neutre** |
| VDQ-C conforme, PME | ~78-84 % (facteur combiné) | idem — **neutre** |
| VDQ-P conforme | 76 % | 76 % — **neutre** |
| VDQ-P conforme < 1 M€, clientèle de détail | 57 % | 57 % — **neutre** (maintenu) |
| VDQ **non conforme** aux critères de qualité | 76 % (ou 57 % en détail) | **100 %** — seule hausse, +25 à +45 pb, évitable |

**Aucune exposition conforme ne voit sa pondération augmenter ou diminuer au lancement.** L'allègement, s'il vient, viendra après 2031, sur preuve, et seulement pour le meilleur quart du palier croissance (banques IRB spécialisées) — de l'ordre de −40 pb/an dans ce cas précis. La garantie publique découplée (P11) apporte, elle, un allègement immédiat mais ciblé (−43 à −52 pb/an) sur un segment de tickets aujourd'hui mal couvert.

**Pourquoi si peu d'allègement ?** Parce que l'allègement en capital n'est structurellement pas le facteur qui limite le marché européen de la venture debt. L'écart transatlantique reflète d'abord l'écart de capital-risque disponible (equity), pas le traitement prudentiel de la dette qui le complète. Le compartiment n'est donc pensé ni comme une subvention déguisée, ni comme la solution au déficit de financement des scale-ups — mais comme un outil de lisibilité, de données et de sécurité juridique, condition nécessaire (mais pas suffisante) à tout recalibrage futur fondé sur la preuve.

---

## 8. Ce que ce paquet ne fait délibérément pas

- Il ne modifie aucune pondération d'exposition conforme au lancement, sans exception.
- Il ne crée aucun nouveau facteur de soutien (type « subvention »), ni actif ni dormant.
- Il n'impose aucun durcissement de Pilier 1 fondé sur une simple inférence.
- Il ne rend aucun allègement futur irréversible.
- Il ne modifie pas le règlement Titrisation.
- Il ne porte pas l'étiquette « *specialised lending* » et ne réécrit pas le triple test de l'art. 147(8) CRR.
- Il n'étend pas le compartiment prudentiel aux fonds de dette non bancaires (AIFMD) — l'asymétrie potentielle est traitée par la complémentarité des rôles (P6), l'ouverture de la garantie à tous les prêteurs (P11) et une définition d'insolvabilité indépendante du type de prêteur (P12).
- Il ne fait dépendre le volet prudentiel ni d'un budget (P11) ni d'une harmonisation de l'insolvabilité (P12) : chaque brique tient seule.
- Il ne propose pas d'harmonisation générale du rang des créances — seulement, à titre conditionnel, une reconnaissance étroite entre les parties d'un accord de subordination, sur le modèle BRRD.
- Il ne prétend pas combler l'écart transatlantique de financement des scale-ups.

---

## 9. Verdict final et risque résiduel

**Évaluation d'impact (Better Regulation)** : PASSE, avec 7 réserves documentées (R-1 à R-7), toutes intégrées ou closes au round 3 — bloquantes seulement pour une éventuelle rédaction législative future, pas pour la faisabilité politique actuelle.

**Faisabilité politique** : PASSE. Risque dominant identifié : non pas un blocage actif par un opposant puissant, mais un **abandon par manque de portage politique** dans un calendrier législatif 2027 chargé — le paquet ayant délibérément renoncé à tout allègement immédiat pour désamorcer les objections prudentielles, il ne dispose pas d'un lobby bancaire pleinement mobilisé pour le porter. C'est un arbitrage assumé : un paquet plus difficile à attaquer sur le fond, mais moins porté par un intérêt économique immédiat. La séparabilité de la phase 0 (aucune codécision requise) est la principale protection contre ce risque : même en cas d'abandon du volet législatif, l'essentiel de la valeur (données, sécurité juridique) reste acquis.

---

## 10. Documents complets

Tous les documents intermédiaires sont dans `policy/venture-debt/` :
- `current-regulation.md`, `micro-analysis.md`, `macro-analysis.md`, `benchmarking.md`, `stakeholder-map.md` — cadrage factuel
- `proposals.md` — le paquet complet et détaillé (13 propositions, ~1 400 lignes, autoportant)
- `impact-debate.md` — les deux rounds d'évaluation d'impact
- `feasibility-debate.md` — les deux rounds de faisabilité politique
