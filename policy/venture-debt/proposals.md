# Propositions — Compartiment prudentiel bancaire dédié à la « venture debt » dans le cadre CRR/CRD

**Agent :** `policy-innovator` — dossier `policy/venture-debt/`
**Version :** **révisée à l'issue du round 1 de l'`impact-assessment-auditor`** (round 2 du débat d'impact). La réponse argumentée, point par point, figure dans `impact-debate.md`, section « Round 2 — Réponse du policy-innovator ». Ce document est **autoportant** : il se lit sans avoir à recouper le débat.
**Date :** 22 septembre 2026 (version initiale et révision)
**Entrées lues intégralement :** `current-regulation.md`, `micro-analysis.md`, `macro-analysis.md`, `benchmarking.md`, `stakeholder-map.md`, `impact-debate.md` (round 1), tous dans `policy/venture-debt/`.
**Statut :** propositions de politique publique argumentées. Ce document ne contient **aucune rédaction législative**. Les références d'articles et les paramètres chiffrés servent à rendre les propositions opérationnelles. Ils restent indicatifs et devront être repris par `legal-drafter` si cette étape est déclenchée.

---

## Journal des révisions (round 2)

| # | Verdict du round 1 | Révision apportée |
|---|---|---|
| P1 | Passe avec modification | Deux types de critères : **caractérisation** (C1-C3), qui déclenche un classement obligatoire, et **qualité** (Q1-Q5), qui détermine le traitement à l'intérieur de la catégorie. Aucune sortie vers le *corporate* générique ni vers la clientèle de détail. LTER ≤ 40 % calculé **sur la dette totale**. Critère « investisseur de pays tiers » objectivé. Retrait du critère lié au dossier de crédit du prêteur. Définition de reporting dès la phase 0. |
| P2 | **Échec** | Le 130 % est retiré du texte. VDQ conforme à 100 % cumulable avec l'art. 501, soit le statu quo. VDQ non conforme à 100 % **sans** facteur PME. Le 130 % devient une hypothèse de calibrage soumise au rapport EBA à 3 ans ; s'il est confirmé, la voie est législative. Le « test de suffisance » est retiré. |
| P3 | Passe avec modification | Catégorie 2 VDQ-P dormante. Catégorie 2 VDQ-C maintenue comme **exception motivée** : effective à l'application du RTS, sous le plafond de P9, désactivable sur données. EL fixées au niveau 1. Règle transitoire jusqu'au RTS. Choix entre PD et *slotting* au niveau du portefeuille. Les hypothèses VDQ-P de l'approche PD sont renvoyées au rapport à 3 ans. |
| P4 | Passe avec modification | **Facteur 0,85 retiré.** Catégories dormantes conservées. Habilitation réécrite selon les conditions (i) à (vi) de l'auditeur. Désactivation symétrique fondée sur les pertes. Revue de l'effet d'offre par rapport, sans extinction automatique des catégories fondées sur le risque. |
| P5 | Passe avec modification | Clarification sur la *forbearance* reformulée dans les limites de l'art. 47b CRR, sans présomption. Hystérésis symétrique. Indicateurs agrégés : interdits comme **seul** motif de dégradation. |
| P6 | Passe avec modification | **Extension de l'exclusion titrisation retirée**, remplacée par une demande de Q&A. Architecture limitée aux **facilités distinctes**. *Unitranche* à accord entre prêteurs exclu. LTER sur la dette totale. Avis de place. |
| P7 | Passe avec modification | 7.2 par Q&A, dans la lettre de l'art. 133(4) ; le niveau 1 ne sert qu'à codifier. **7.3 retiré.** 7.6 conditionné à l'insuffisance de l'art. 91(2). |
| P8 | Passe avec modification mineure | Recommandation à la BCE, avec un plan B. Écart assumé par rapport à l'OCC. Reprise des limites de portefeuille et du reporting à l'organe de direction. |
| P9 | Passe avec modification mineure | Seuils de proportionnalité pour la liquidité. Imputation au prorata au-delà du plafond. Distinction d'avec le plafond de l'art. 133(5). |
| P10 | Passe avec modification mineure | Devient le **préalable séquentiel** du paquet. Indicateurs sur sources officielles. Le chiffre de « 30 % du marché » est retiré. |
| P11 | Passe avec modification substantielle | **Découplé** du volet CRR. Garantie **non plafonnée** pour l'allègement en capital (art. 234). Fenêtre recentrée sur les tickets de croissance de 8,25 à 25 M€ ; VDQ-P renvoyée au produit I&D existant. Coût budgétaire chiffré. Éligibilité propre dès la phase 0. |
| P12 | Passe avec modification | Niveau 1 (cartographie) seul à ce stade. **Définition autonome** de l'instrument, sans renvoi au CRR. Niveau 2(a) conditionné à la cartographie. L'élément (b) est requalifié en mesure de rang substantiel et traité à part. EU Inc n'est pas chargé. |
| P13 | Passe avec modification | Trois écarts bâlois favorables recensés, dont les warrants. Matérialité appréciée par composante, en cumul. Trajectoire sans facteur de soutien. Analyse de coalition corrigée. Reséquencement selon C.6 du round 1. |
| Transversal | — | Objectif général reformulé (§0.2). Convention de calcul unique pour les coûts et convention distincte, unique, pour les tests de couverture (§0.6). Quinze incohérences numériques corrigées, dans les propositions concernées et dans H.1. Ordres de grandeur des coûts (H.6). |

---

## 0. Thèse, méthode et mode d'emploi

### 0.1 La tension centrale et la façon dont ce document la résout

**Ce que souhaite l'utilisateur.** Une approche incrémentale : étendre l'art. 147 CRR et la méthode du *specialised lending* (financement spécialisé), sur le modèle du *project finance*.

**Ce que montre le cadrage factuel, de façon convergente.** La venture debt échoue **structurellement** au triple test cumulatif de l'art. 147(8) CRR. Ce test exige une entité ad hoc portant des actifs physiques, un contrôle substantiel du prêteur sur ces actifs et leurs revenus, et un remboursement assuré par les revenus des actifs financés. Les sources sont les suivantes :
- `current-regulation.md` §2.2 ;
- `micro-analysis.md` §0 point 1 et §6 friction n° 1 ;
- `macro-analysis.md` §4.2 ;
- `benchmarking.md` §5.

La venture debt se rembourse par un **événement de financement futur** : tour de table suivant, cession ou introduction en bourse. Le coefficient de remboursement à l'événement de liquidité est de 0,92 à 1,0 (`micro-analysis.md` §2.1). Il ne s'agit pas d'un oubli du texte mais d'une incompatibilité de définition.

**Thèse de ce document : un compartiment « incrémental par la méthode, sui generis par la définition », neutre en capital au lancement.** Concrètement :

1. **Ce qui reste dans l'architecture existante.** Le compartiment réutilise, sans rien inventer de disjoint :
   - la classe d'exposition « entreprises » ;
   - l'architecture à deux étages que CRR3 a créée pour le *specialised lending*, avec un volet standard (art. 122a) et un volet IRB en *slotting* (art. 153(5)) ;
   - la gouvernance du *slotting* : catégories supervisées et critères fixés par RTS de l'EBA ;
   - le facteur PME existant (art. 501), maintenu tel quel pour les expositions conformes. **Aucun nouveau facteur de soutien n'est créé** ;
   - les orientations EBA existantes sur l'octroi de prêts ;
   - des statuts réglementaires existants (AIFMD, EuVECA, ELTIF, partenaires InvestEU) pour définir le sponsor.
2. **Ce qui doit être nouveau, et qu'il serait malhonnête de masquer.** Il faut une **définition autonome** fondée sur la dépendance au financement externe et sur le soutien d'un investisseur qualifié, avec des critères de *slotting* **conçus pour la venture debt**. Cela suppose une **modification de niveau 1 par codécision** : l'art. 147 est limitatif et un RTS ne peut pas créer de catégorie (`current-regulation.md` §2.5 ; `stakeholder-map.md`, synthèse n° 1). Le mandat de RTS est lui aussi **nouveau** : l'art. 153(9) ne vise que le *specialised lending*.
3. **Ce que cela n'est pas.** Ce n'est pas, au sens strict, une sixième sous-catégorie de *specialised lending*. C'est une **sous-catégorie sui generis de la classe « entreprises »**. Elle emprunte au *specialised lending* sa logique et sa gouvernance, mais pas son étiquette juridique, ni son triple test, ni son exclusion du champ de la titrisation.

**Pourquoi ne pas coller l'étiquette « specialised lending » :**
- **(i) Contamination.** Réécrire le triple test de l'art. 147(8) pour y faire entrer la venture debt affaiblirait la définition pour toutes les autres sous-catégories (`current-regulation.md` §2.2). Un paragraphe distinct de l'art. 147(8) réduirait ce risque, mais ne supprimerait pas les deux motifs suivants.
- **(ii) Garde-fou n° 4 garanti par construction.** Les lignes directrices BCE sur les opérations à effet de levier (2017) excluent le *specialised lending*. La BCE maîtrise le champ de sa guidance et pourrait ne pas étendre l'exclusion à une nouvelle sous-catégorie SL. Mais une catégorie sui generis rend le respect du garde-fou n° 4 **indépendant** d'une décision de la BCE.
- **(iii) Chantier de la Commission.** La communication COM(2026) 615 rattache le *specialised lending* aux « investissements stratégiques » et au financement de projets (`macro-analysis.md` §4.5). Rester hors de l'étiquette évite d'entrer en collision avec ce chantier, tout en permettant de voyager dans le même paquet législatif.
- **(iv) Agenda déjà engagé.** L'agenda de l'EBF sur le *specialised lending* (planchers de LGD, collatéral, output floor) est déjà occupé et ne mentionne pas la venture debt (`stakeholder-map.md` §1.2).

**Coût de ce choix, assumé.** L'emprise de niveau 1 d'une catégorie sui generis est **plus large** que celle d'une sixième sous-catégorie SL. Chaque renvoi du CRR au SL (art. 122a, 153(5), 153(9), 158(6)) doit être dupliqué. Le paquet révisé réduit cette emprise au minimum (voir P13, tableau de l'emprise).

### 0.2 Objectif général reformulé et logique d'intervention

**Objectif général (reformulé, et assumé comme tel).** Le dossier part d'un objectif de **facilitation** : COM(2026) 615 veut un cadre permettant de financer « y compris les start-up et les scale-ups », et l'ECON demande de la « flexibilité » dans la mise en œuvre de Bâle III (`macro-analysis.md` §4.5 ; `stakeholder-map.md` §6). Ce document **redéfinit** cet objectif, à la lumière du fact-base :
- l'écart de venture debt suit l'écart d'equity (`macro-analysis.md` §1) ;
- le traitement prudentiel n'explique pas l'écart transatlantique (§5.1) ;
- un compartiment n'est « ni nécessaire ni suffisant » (§5.3).

L'objectif retenu est le suivant : **rendre le traitement prudentiel de la venture debt bancaire lisible, mesurable et sensible au risque, et lever les frictions non capitalistiques documentées, sans créer d'allègement en capital qui ne soit fondé sur des données de pertes européennes.** La facilitation passe par la sécurité juridique, le pilier 2 et le partage des risques budgété. Elle ne passe pas par les pondérations.

**Logique d'intervention : chaque problème appelle l'instrument le moins lourd qui le traite.**

| Problème | Statut dans le fact-base | Instrument retenu | Proposition |
|---|---|---|---|
| (i) Insécurité juridique : warrants, guidance BCE, *forbearance*, frontière avec la titrisation | Documenté | Q&A, orientations, recommandation à la BCE ; niveau 1 seulement pour codifier si les Q&A sont insuffisantes | P5, P6, P7, P8 |
| (ii) Angle mort statistique : part bancaire inconnue, aucune série de pertes | Documenté | ITS de reporting (art. 430), collecte au titre de l'art. 35 du règlement EBA, protocole avec la BEI | **P10 (préalable)** |
| (iii) Insensibilité au risque de l'approche standard ; sélection adverse vers l'*early stage* | **Inféré** [I] | Pilier 2 (limites par stade, stress, présomption de revue) ; pondérations neutres au lancement ; recalibrage renvoyé au rapport sur données | P2, P8, P9, P10 |
| (iv) Obstacle de validation des modèles IRB | **Inféré** [I], mais seul problème qui exige une sous-catégorie de pilier 1 | *Slotting* dédié, optionnel, par modification de niveau 1 et nouveau RTS | P1, P3 |
| (v) Concentration actif-passif de type SVB | Documenté (SVB) | Pilier 2, liquidité, résolution | P9 |
| (vi) Fragmentation de l'insolvabilité | Documenté qualitativement | Cartographie d'abord ; harmonisation conditionnelle | P12 |
| (vii) Faible profondeur du partage des risques sur les tickets de croissance | Documenté (plafond de 8,25 M€ du produit I&D) | Budgétaire, InvestEU puis FEC | P11 |

**Cinq principes de conception.**

| # | Principe | Ancrage |
|---|---|---|
| 1 | **Lisibilité et sensibilité au risque plutôt que subvention ; aucun durcissement ni allègement de pilier 1 sans données.** L'allègement en capital d'un compartiment est de l'ordre de 5 à 100 pb/an, soit un ordre de grandeur de moins que les rendements (7-13 %) et que la variation cyclique des pertes (200-350 pb). Un durcissement de pilier 1 destiné à corriger un risque seulement inféré n'est pas proportionné quand le pilier 2 est disponible. | `macro-analysis.md` §4.4, §5.1 ; round 1, P2 |
| 2 | **Deux paliers, pas une grille unique.** Les pertes nettes (NCO) sont de 9,6-9,7 % en *early stage* contre 1,3-1,5 % en *growth stage* (First Citizens, 2023-2024). | `micro-analysis.md` §0 point 3, §3.2, §8.1(3) |
| 3 | **Deux étages, standard et IRB, indissociables.** Sans article standard dédié, l'output floor neutralise tout paramètre IRB. L'article standard sert donc de réceptacle, même à pondérations neutres. | `current-regulation.md` §3.4 ; `micro-analysis.md` §8.1(4) |
| 4 | **Un paquet, pas un pari sur le seul pilier 1.** Le précédent étranger le plus directement transposable est une guidance de pilier 2 (OCC 2023-34, puis 2025-45). Les contraintes effectives sont l'expertise, la culture du risque, la fragmentation et la profondeur de l'equity. | `benchmarking.md` §2.3, §6 ; `macro-analysis.md` §5.2 |
| 5 | **Les conditions de neutralité macroprudentielle sont des contraintes de conception, pas des options.** | `macro-analysis.md` §6 (voir 0.3) |

### 0.3 Les sept garde-fous macroprudentiels et leur traduction obligatoire

`macro-analysis.md` §6 énonce sept conditions minimales pour qu'un compartiment ne dégrade pas la stabilité financière. Elles sont traitées ici comme **obligatoires**.

| Garde-fou (`macro-analysis.md` §6) | Traduction dans ce jeu de propositions |
|---|---|
| 1. Neutralité de calibrage : aucune pondération standard sous 100 % sans série de pertes européenne validée par l'EBA ; à défaut, un compartiment « à visée statistique et de supervision » | **P2** : toutes les pondérations de l'article standard dédié valent 100 % au lancement. Le facteur PME préexistant reste cumulable pour les expositions conformes : c'est le statu quo, pas un allègement nouveau. **P3** : en IRB, tout élément plus favorable que la catégorie « satisfaisant » est dormant, à **une exception motivée et bornée**, la catégorie 2 VDQ-C (P3, point 3). **P4** : activation sur critères objectifs. |
| 2. Plafond de concentration, sur le modèle de l'art. 133(5) (10 % des fonds propres) | **P9** : éléments préférentiels plafonnés à 10 % des fonds propres, avec imputation au prorata. Présomption de revue de pilier 2 au-delà de 5 %. |
| 3. Volet liquidité obligatoire (concentration des dépôts de l'écosystème VC) | **P9** : suivi ALMM et ILAAP, proportionné par des seuils ; Q&A sur les dépôts « opérationnels ». |
| 4. Pas de sortie automatique des lignes directrices BCE sur l'effet de levier | **§0.1(ii)** : catégorie sui generis. **P8** : substitution conditionnelle, présentée comme **recommandation** à la BCE. |
| 5. Composante contracyclique (sSyRB activable, ou calibrage à travers le cycle) | **P5** : hystérésis symétrique ; aucune dégradation fondée sur les **seuls** indicateurs agrégés. **P9** : sous-ensemble sSyRB préidentifié. |
| 6. Clause de revoyure et extinction faute d'effet d'offre | **P10** : rapports EBA à 3 et 5 ans ; P10 devient le préalable du paquet. **P4** : désactivation automatique fondée sur les pertes, caducité de l'habilitation, et revue de l'effet d'offre par rapport de la Commission. L'écart par rapport à la lettre du garde-fou (pas d'extinction automatique d'une **catégorie de risque** pour absence d'effet d'offre) est motivé en P4, point 6. |
| 7. Priorité aux canaux budgétés et plafonnés | **P11** : mesure **autonome** de partage des risques, justifiée par ses propres mérites. Elle n'est plus présentée comme la contrepartie d'une surcharge. |

### 0.4 Glossaire minimal (pour le lecteur non spécialiste)

- **RWA / pondération (RW)** : montant d'exposition « pondéré » par le risque. Les fonds propres minimaux sont égaux à 8 % des RWA, plus les coussins. Une pondération de 100 % signifie que 1 € prêté consomme 8 centimes de fonds propres minimaux.
- **Approche standard (SA)** : pondérations forfaitaires fixées par le règlement.
- **Approche IRB** : la banque estime elle-même les paramètres de risque, sous agrément de son superviseur :
  - **PD** : probabilité de défaut ;
  - **LGD** : perte en cas de défaut ;
  - la variante « fondation » (F-IRB) utilise des LGD réglementaires.
- **Slotting** : méthode IRB simplifiée. L'exposition est classée dans une catégorie qualitative (solide, bon, satisfaisant, faible, défaut) à pondération fixe. Elle est conçue pour les actifs dont l'historique de défauts est trop mince pour estimer une PD.
- **EL / UL** : perte attendue (*expected loss*), absorbée par les provisions et la marge ; perte inattendue (*unexpected loss*), couverte par les fonds propres.
- **Output floor** : plancher. Les RWA calculés en IRB ne peuvent descendre sous 72,5 % (à partir de 2030) des RWA calculés en approche standard.
- **Facteur de soutien (supporting factor)** : coefficient réducteur appliqué **après** le calcul des RWA. Il vaut 0,7619 ou 0,85 pour les PME (art. 501) et 0,75 pour les infrastructures (art. 501a).
- **Runway** : nombre de mois de trésorerie avant épuisement.
- **LTER** : dette financière totale de l'emprunteur rapportée au cash d'equity effectivement versé sur 24 mois (définition révisée, P1).
- **VDQ conforme / non conforme** : VDQ qui remplit, ou non, les critères de qualité Q1 à Q5 (P1).
- **Warrant / equity kicker** : bon de souscription d'actions reçu par le prêteur en complément des intérêts.
- **Test SPPI (IFRS 9)** : test comptable qui détermine si un prêt peut être comptabilisé au coût amorti. S'il échoue, le prêt passe en juste valeur par résultat.

### 0.5 Sommaire des propositions

| # | Titre | Instrument / niveau | Cadres connectés principaux | Phase |
|---|---|---|---|---|
| **A. Le compartiment de pilier 1 (socle réduit)** |||||
| P1 | Définition sui generis « VDQ » : caractérisation et qualité, deux paliers | Niveau 1 (art. 147) ; définition de reporting par ITS dès la phase 0 | AIFMD (art. 3(2), 6, 42), EuVECA, ELTIF, InvestEU ; art. 123, 153(4), 430 CRR | 0 (reporting), puis 1 |
| P2 | Volet standard : article dédié à pondérations neutres ; 130 % renvoyé au rapport sur données | Niveau 1 | Art. 122a, 128, 501, 465 CRR | 1 |
| P3 | Volet IRB : *slotting* dédié optionnel, règle transitoire, EL au niveau 1 | Niveau 1 + nouveau RTS | Art. 153, 158 CRR ; règlement délégué (UE) 2021/598 ; EBA/CP/2026/09 ; Bâle CRE33 | 1 (RTS vers 2031) |
| P4 | Catégories dormantes fondées sur le risque, sans facteur de soutien ; activation et désactivation sur données | Niveau 1 + acte délégué (art. 290 TFUE) | Art. 122a (analogue PF 80 %), CRE33 ; art. 290 TFUE | 1 puis 2 |
| **B. Covenants, séniorité, tranches** |||||
| P5 | Covenants, migrations, *forbearance* dans les limites de l'art. 47b | Q&A, orientations EBA, RTS | Art. 47b, 47c, 178 CRR ; EBA/GL/2016/07 ; EBA/GL/2018/06 | 0 puis 1 |
| P6 | Séniorité et facilités distinctes ; frontière avec la titrisation par Q&A | Q&A (EBA / Comité mixte) + RTS | Art. 128, 161, 194 CRR ; règlement (UE) 2017/2402, art. 2(1) ; AIFMD II ; ELTIF 2.0 | 0 puis 1 |
| **C. Warrants** |||||
| P7 | Warrants : qualification et 250 % par Q&A ; conversion dette-actions | Q&A ; niveau 1 seulement pour codifier | Art. 133, 36, 44-46, 89-91 CRR ; IFRS 9 ; directives 2019/1023 et 2026/799 | 0 (niveau 1 conditionnel) |
| **D. Pilier 2, garde-fous, données** |||||
| P8 | Section « venture debt » dans EBA/GL/2020/06 ; recommandation à la BCE sur sa guidance | Orientations EBA ; recommandation | CRD art. 74, 79 ; EBA/GL/2020/06 ; EBA/GL/2022/03 ; OCC 2025-45 | 0 |
| P9 | Concentration, liquidité, coussin sectoriel, résolution | Niveau 1 (plafond) + pilier 2 + Q&A | Art. 133(5) CRR (modèle) ; CRD art. 104, 105, 133 ; règlement délégué (UE) 2015/61 ; EBA/GL/2020/13 ; BRRD art. 10 | 0 (pilier 2), 1 (plafond) |
| P10 | **Préalable du paquet** : données, calibrage, revoyure | Collecte art. 35 + ITS + niveau 1 (revoyure) | Art. 430 CRR ; règlement EBA art. 35 ; AnaCredit / IReF ; groupe BEI | **0**, puis 1 et 2 |
| **E. Partage des risques (mesure autonome)** |||||
| P11 | Fenêtre InvestEU/FEC « dette de croissance » non plafonnée, découplée du CRR | Budgétaire | Règlement (UE) 2021/523 ; produit I&D non plafonné ; art. 117(2), 213-215, 234 CRR ; GBER art. 21 ; FEC | 0 (programmation) |
| **F. Insolvabilité (volet découplé)** |||||
| P12 | Rang des créances : cartographie d'abord ; définition autonome ; harmonisation conditionnelle | Niveau 1 insolvabilité (conditionnel) | Directives 2019/1023, 2026/799, 2017/2399 | 0 (cartographie) |
| **G. Cohérence et séquençage** |||||
| P13 | Cohérence bâloise, véhicule, séquençage en trois phases | Stratégie | COM(2026) 615 ; Bâle / RCAP ; SIU | Transversal |

**Phases (reséquencement retenu, voir P13) :**
- **Phase 0 (fin 2026 à 2028), cœur du paquet et solution de repli autonome.** Mesures sans modification du niveau 1 : collecte de données (P10), orientations, Q&A, recommandation à la BCE, programmation InvestEU/FEC, cartographie de l'insolvabilité.
- **Phase 1 : socle de niveau 1 réduit.** Proposition dans le paquet législatif du T1 2027 issu de COM(2026) 615 ; adoption vers 2028 ; application vers 2029-2030 ; RTS de *slotting* applicable vers 2031.
- **Phase 2 (à partir de 2031) : paramètres de pilier 1.** Rapport de l'EBA à 3 ans après l'entrée en vigueur, fondé sur les données de la phase 0 ; décisions d'activation (acte délégué) ou de recalibrage (voie législative).

### 0.6 Conventions de fiabilité et de calcul

**Fiabilité.** Les constats repris des cinq rapports conservent leur qualification d'origine (documenté, calculé ou inféré). Les éléments ajoutés par ce document sont signalés ainsi :
- **[vérifié]** : vérifié par recherche lors de la version initiale ;
- **[vérifié, round 2]** : vérifié lors de la révision, à savoir le texte des art. 47b, 123 et 150 CRR et l'échéance de l'art. 33 de la directive 2019/1023 ;
- **[vérifié-auditeur]** : vérifié par l'`impact-assessment-auditor` au round 1 ;
- **[à vérifier]** : non vérifié.

Les sources figurent en fin de document.

**Deux grandeurs distinctes, une convention unique pour chacune.** La version initiale mélangeait deux choses. Elle justifiait un paramètre avec un capital à 8 % comparé à une perte **totale**, et en chiffrait le coût avec un capital à 13 % (round 1, P2). La version révisée sépare deux questions qui ne doivent jamais être croisées.

- **(a) Coût d'un paramètre pour la banque (tous les chiffres en pb de ce document).** Coût annuel ≈ pondération × 13 % (exigence cible de fonds propres) × 8 points (surcoût des fonds propres), soit **1,04 pb par point de pondération** (`macro-analysis.md` §4.4). `micro-analysis.md` §5.2 utilise une convention voisine (0,9 pb par point) ; elle n'est pas reprise ici. Ce sont des ordres de grandeur.
- **(b) Adéquation prudentielle d'un paramètre (tests de couverture, P2, P4 et P10).** Deux comparaisons séparées :
  - la **perte inattendue** (perte de l'année défavorable moins l'EL) est comparée à l'exigence **minimale** de pilier 1 (8 % × pondération) ;
  - la **perte attendue** est comparée aux provisions IFRS 9 et à la marge.
  
  Le minimum de pilier 1 est la bonne référence, car c'est lui que le législateur calibre ; les coussins sont utilisables et l'exigence de pilier 2 est propre à chaque banque. Aucun chiffre de ce document ne compare une perte **totale** à un capital.

---

## A. Le compartiment de pilier 1 (socle réduit)

### P1 — Définition sui generis de l'« exposition de venture debt qualifiée » (VDQ) : critères de caractérisation, critères de qualité, deux paliers

**Résumé exécutif.** Créer, dans la classe « entreprises », une sous-catégorie définie par la **dépendance de l'emprunteur au financement externe** et par le **soutien d'un investisseur professionnel qualifié**. La définition sépare deux types de critères :
- **Critères de caractérisation (C1 à C3).** Ils sont objectifs, portent sur l'emprunteur et échappent au contrôle du prêteur. Dès qu'ils sont remplis, le classement en VDQ est **obligatoire**.
- **Critères de qualité (Q1 à Q5).** Ils portent sur la structure du prêt et déterminent le traitement **à l'intérieur** de la catégorie. Une VDQ qui ne les remplit pas est « **non conforme** » : elle est traitée moins favorablement qu'une VDQ conforme. Elle ne sort **jamais** vers le *corporate* générique ni vers la clientèle de détail.

La catégorie comporte deux paliers :
- **VDQ-P** : stade précoce, revenus des 12 derniers mois inférieurs à 5 M€ ;
- **VDQ-C** : croissance, revenus au moins égaux à 5 M€.

Elle exclut explicitement les financements adossés à des actifs. Les critères de caractérisation servent aussi, **dès la phase 0**, de définition de reporting (P10), de noyau d'éligibilité à la garantie (P11) et de base à la définition autonome du volet insolvabilité (P12).

**Problème et ancrage factuel.**
- **Le triple test échoue.** Le critère n° 1 (SPV à actif physique) et le critère n° 3 (remboursement par les revenus de l'actif) échouent presque toujours ; le critère n° 2 (contrôle) échoue au sens du SL (`current-regulation.md` §2.2 ; `macro-analysis.md` §4.2 ; `benchmarking.md` §5).
- **Le remboursement se fait par l'événement de liquidité.** Le taux de remboursement trimestriel bondit à 25 % au trimestre d'un événement ; seuls environ 11 % des prêts arrivent à maturité (`micro-analysis.md` §2.1).
- **Quatre familles sont mélangées dans les statistiques** : (a) *runway*, (b) *growth*, (c) financements adossés à des actifs d'entreprises VC (GPU, data centres, lignes *warehouse*), (d) quasi-equity publique. La famille (c) biaise les données de calibrage et ouvre un arbitrage (`micro-analysis.md` §1.1, §1.2, §6 friction n° 12). Exemples : Mistral AI, 830 M$ pour 13 800 GPU ; Nscale, 790 M$.
- **Le profil est bimodal par stade** (`micro-analysis.md` §3.2), avec une frontière opérationnelle déjà utilisée par SVB/First Citizens autour de 5 M$ de revenus (§8.1(3)).
- **Arbitrage de classe « clientèle de détail ».** Sous 1 M€, une exposition PME peut être classée en clientèle de détail à 75 %, soit environ 57 % après facteur PME (`micro-analysis.md` §5.1 et §6 friction n° 3).
- **Défaut de la version initiale : l'incitation inversée (round 1).** Les critères de structure (LTER, covenant, maturité, *kicker* détachable) étaient des conditions d'**entrée** cumulatives. Faute de les remplir, l'exposition revenait au *corporate* générique. Un prêt plus risqué, par exemple sans covenant de trésorerie ou à 7 ans, sortait ainsi de la catégorie qui devait le discipliner. Toute définition servant de base à un traitement différencié doit être **inévitable par structuration**.

**Mécanisme.**
1. **Emplacement.** Un nouveau paragraphe de l'art. 147 CRR (numérotation à arrêter, par exemple 147(8a)) crée, **dans la classe « entreprises » mais hors *specialised lending***, la sous-catégorie VDQ. Elle est répliquée dans l'approche standard par un nouvel article placé à la suite de l'art. 122a (voir P2).
2. **Critères de caractérisation.** Est une VDQ toute exposition sur une entreprise (hors établissements, entreprises d'assurance et de réassurance, entreprises d'investissement et organismes de placement collectif) qui remplit les trois critères suivants. Le classement est **obligatoire**.
   - **(C1) Soutien d'un investisseur professionnel qualifié.** Dans les 18 mois précédant l'octroi, l'emprunteur a réalisé un tour de fonds propres dans lequel un investisseur qualifié a souscrit **au moins 25 % du montant du tour, ou la part la plus élevée**. L'investisseur qualifié est défini **par renvoi** :
     - (i) un FIA géré par un gestionnaire agréé au titre de l'art. 6 AIFMD ;
     - (ii) un fonds EuVECA (règlement (UE) n° 345/2013) ;
     - (iii) un ELTIF (règlement (UE) 2015/760 modifié par 2023/606) ;
     - (iv) le groupe BEI (dont le Fonds EIC et le FEI), ou une banque ou institution nationale de développement éligible comme partenaire chargé de la mise en œuvre d'InvestEU ;
     - (v) **critère objectivé** : un fonds de pays tiers dont le gestionnaire remplit **deux** conditions. D'une part, il est agréé ou enregistré auprès d'une autorité de surveillance d'un pays tiers couvert par un accord de coopération au titre de l'art. 42(1)(b) AIFMD, ou il y dépose des déclarations réglementaires périodiques ; ce second cas couvre notamment les conseillers américains relevant du statut d'*exempt reporting adviser*, qui déposent le formulaire ADV. D'autre part, ses encours gérés atteignent au moins **100 M€**, seuil **repris de l'art. 3(2)(a) AIFMD**, utilisé ici comme indicateur objectif de taille institutionnelle. [à vérifier : présence de la SEC parmi les autorités signataires des accords de coopération AIFMD]

     Le point (v) est indispensable : plus de 4 opérations de scale-up sur 5 dans l'UE ont un chef de file étranger (`macro-analysis.md` §1.1). Il s'applique à partir de registres publics, sans appréciation du prêteur.
   - **(C2) Dépendance au financement externe.** L'emprunteur présente, sur les 12 derniers mois, un **EBITDA négatif ou un flux de trésorerie disponible avant service de la dette négatif**. Ces deux grandeurs sont tirées de ses comptes et ne dépendent pas de la structure du prêt. Le critère de la version initiale (« le dossier de crédit identifie à l'octroi un financement futur comme source de remboursement ») est **retiré de la définition**. Il dépendait du prêteur ; il devient une exigence de documentation de pilier 2 (P8).
   - **(C3) Nature de la créance.** Il s'agit d'un prêt ou d'une facilité de crédit, à l'exclusion des financements dont la source principale de remboursement est le revenu ou la valeur d'actifs spécifiquement financés (famille (c)). Le test objectif (actifs identifiés, base d'emprunt ou *borrowing base*, SPV) est précisé par le RTS (P3, point 7).
3. **Critères de qualité (traitement interne à la catégorie).**
   - **(Q1) LTER ≤ 40 %, calculé sur la dette financière totale de l'emprunteur** : senior, junior, ABL et RCF tirés, venture debt de tous les prêteurs. Les prêts d'associés contractuellement subordonnés à toute la dette financière sont exclus du numérateur. Le dénominateur est le cash d'equity effectivement versé sur les 24 derniers mois.
     - **Justification du seuil.** `micro-analysis.md` §8.1(2) propose 35 à 50 % pour **un** prêt. Le calcul porte désormais sur la dette **totale** ; 40 % laisse passer la structure typique (un prêt de 25 à 35 % du dernier tour, `macro-analysis.md` §1.5) et une tranche junior modeste. Il écarte la queue la plus levierisée, par exemple un senior à 50 % plus un junior à 25 % (round 1, P6).
     - **Pourquoi ce seuil plus strict est acceptable.** Un critère de qualité ne fait plus sortir de la catégorie : un seuil plus exigeant ne pousse plus vers une structuration plus risquée. Le seuil est réexaminé à 3 ans (P10).
   - **(Q2) Covenant de trésorerie minimale** (ou de runway) et reporting financier mensuel (voir P5).
   - **(Q3) Maturité contractuelle ≤ 6 ans.** Les maturités usuelles sont de 3 à 5 ans ; la BEI pratique le *bullet* à 5-6 ans par tranche (`micro-analysis.md` §2.1).
   - **(Q4) Kicker détachable.** Toute participation au capital accordée au prêteur prend la forme d'un instrument détachable. Le principal et les intérêts ne sont pas indexés sur la valeur des titres (test SPPI, `micro-analysis.md` §2.4 ; inspiré du 12 CFR 7.1006). Un *kicker* incorporé **ne fait plus sortir** de la catégorie. Le prêt, comptabilisé en juste valeur par résultat, reste une exposition de crédit du portefeuille bancaire et reçoit le traitement « non conforme ». Cela rend inutile le plancher suggéré au round 1.
   - **(Q5) Sûretés.** Sûreté de premier rang sur l'ensemble des actifs, y compris la PI, **ou** *negative pledge* sur la PI. Un *split-lien* avec un prêteur ABL/RCF est admis sous accord inter-créanciers.
4. **Traitement de la VDQ non conforme** (échec à un ou plusieurs des critères Q1 à Q5) :
   - **approche standard :** 100 %, **sans** application du facteur PME de l'art. 501 (P2) ;
   - ***slotting* :** classement plafonné à la catégorie 3 et abaissé d'un cran par rapport au résultat de la grille (P3) ;
   - **approche PD :** facteur PME non applicable.
   
   **La dette subordonnée n'est pas une VDQ non conforme.** Elle relève de l'art. 128 (150 %), plus lourd, qui prime (voir P6). Il n'y a donc pas de sortie favorable.
5. **Exclusions explicites (anti-arbitrage) :**
   - les expositions qui remplissent l'art. 147(8) (PF, OF, CF, IPRE) ;
   - les expositions ADC ;
   - les positions de titrisation ;
   - les créances achetées ;
   - la famille (c) ;
   - les formes subordonnées ou convertibles de quasi-equity (famille (d)), qui relèvent de l'art. 128 ou de l'art. 133 ;
   - les facilités *unitranche* avec accord entre prêteurs (P6). Si elles ne sont pas des positions de titrisation, elles reçoivent le traitement « non conforme », afin que l'exclusion ne constitue pas une sortie favorable.
6. **Paliers.** VDQ-P si les revenus des 12 derniers mois sont inférieurs à 5 M€ ; VDQ-C au-delà. La migration de P vers C intervient après deux trimestres consécutifs au-dessus du seuil. La frontière SVB est à 5 M$, soit environ 4,4 M€ à 1,13 $/€. Le seuil retenu de 5 M€ est **aussi la borne basse de l'intervalle de chiffre d'affaires de l'ajustement de corrélation PME de l'art. 153(4) CRR** : c'est un point d'ancrage existant du CRR. L'écart avec 4,4 M€ est inférieur à la précision des données ; il est réexaminé à 3 ans.
7. **Sortie par le haut.** L'exposition sort vers le *corporate* générique à la revue suivante si le critère C2 n'est plus rempli pendant **quatre trimestres consécutifs** : EBITDA **et** flux de trésorerie disponible positifs. Sans facteur de soutien propre à la VDQ, la sortie ne pénalise plus la rentabilité : une VDQ conforme et une exposition *corporate* PME reçoivent le même traitement.
8. **Primauté sur la clientèle de détail.** Une exposition qui remplit les critères de caractérisation ne peut pas être classée en clientèle de détail (art. 123 et 147(5)).
   - **Justification.** L'art. 123(1)(c) CRR subordonne ce classement à l'appartenance à « un nombre significatif d'expositions présentant des caractéristiques similaires, de sorte que les risques associés […] sont substantiellement réduits » [vérifié, round 2]. Or les VDQ partagent un facteur systématique dominant, le cycle VC (`macro-analysis.md` §2.2 ; `micro-analysis.md` §3.4), qui contredit cette réduction du risque.
   - **Coût.** Pour un ticket de moins de 1 M€, la pondération passe de 57 % à 76 %, soit **+20 pb** (au plus 2 000 €/an pour 1 M€). C'est la seule hausse de pondération pour une VDQ **conforme** au lancement. Elle est affichée en H.1.
   - **Option pour les colégislateurs.** Si ce coût est jugé disproportionné, la primauté peut être limitée à la définition de reporting. Il faudrait accepter un trou de périmètre : les plus petits tickets, les plus risqués, resteraient hors de l'article dédié.
9. **Clause d'antériorité.** Les expositions octroyées avant la date d'application conservent leur traitement jusqu'à échéance. La demi-vie étant d'environ 2 ans (`micro-analysis.md` §2.1), l'extinction du stock est rapide.
10. **Définition de reporting dès la phase 0.** Les critères C1 à C3 et la distinction entre paliers servent, **avant tout niveau 1**, de définition de reporting : collecte au titre de l'art. 35 du règlement EBA et ventilation par ITS au titre de l'art. 430 (P10). Ils sont objectifs et indépendants du prêteur, et peuvent donc être repris tels quels par le produit de garantie (P11) et, sous forme adaptée, par le volet insolvabilité (P12).

**Cadres connectés et synergies.**
- **AIFMD (art. 3(2)(a), 6 et 42), EuVECA, ELTIF, InvestEU.** Le critère C1 **réutilise** des statuts réglementaires et un seuil existants au lieu de créer un label ad hoc.
- **Art. 153(4) CRR.** Le seuil de 5 M€ coïncide avec la borne basse de l'ajustement de taille.
- **Art. 123(1)(c) CRR.** Fondement de la primauté sur la clientèle de détail.
- **Art. 430 CRR / règlement EBA, art. 35.** Définition de reporting en phase 0.
- **EU Inc (COM(2026) 321).** La proposition définit une « start-up innovante » [vérifié] : dépenses de R&D ≥ 10 % des coûts d'exploitation ou ≥ 5 % du chiffre d'affaires, moins de 100 salariés, chiffre d'affaires ≤ 10 M€, moins de 10 ans d'existence. Cette définition **ne remplace pas** la frontière des paliers, qui est une frontière de **risque**, alors que celle d'EU Inc est une frontière de **politique**.

**Bénéfices attendus.**
- **Micro :**
  - fin de l'incertitude de classement ;
  - une définition inévitable par structuration ;
  - une discipline des structures par les critères de qualité, au coût modéré de la perte du facteur PME ;
  - la suppression de l'arbitrage par la classe « clientèle de détail ».
- **Macro :**
  - un périmètre étanche, donc des données de calibrage propres (`micro-analysis.md` §1.2) ;
  - une ligne de reporting identifiable **dès la phase 0**, soit le « gain net pour la surveillance macroprudentielle » quelle que soit la pondération (`macro-analysis.md` §2.6).

**Risques et limites.**
- (i) La frontière de 5 M€ de revenus est un seuil binaire, mais elle se manipule moins facilement qu'un ratio.
- (ii) Le critère C2 pourrait capter des entreprises non financées par du VC ; le critère C1 filtre ce cas.
- (iii) Le critère C1 suppose que le prêteur connaisse la table de capitalisation. C'est une information standard du dossier de venture debt.
- (iv) Les emprunteurs à EBITDA négatif **non** soutenus par un investisseur qualifié restent en *corporate* générique. Cette frontière est sans effet au lancement, où les traitements sont identiques. Elle devra être examinée avant tout recalibrage du palier P (P2, point 5).
- (v) Toute définition propre à l'UE est une divergence vis-à-vis de Bâle, traitée en P13.
- (vi) L'articulation de la nouvelle sous-catégorie avec les classes d'exposition de l'approche standard post-CRR3 reste à vérifier par `current-regulation-analyst` [à vérifier].

---

### P2 — Volet approche standard : un article dédié à pondérations neutres au lancement ; calibrage renvoyé aux données

**Résumé exécutif.** Créer en approche standard un article dédié, placé à la suite de l'art. 122a. Il sert de **réceptacle** : sans lui, l'output floor neutralise tout paramètre IRB, et aucun recalibrage futur n'aurait de support. Ses pondérations sont **neutres au lancement** :
- **VDQ conforme (P ou C) : 100 %, cumulable avec l'art. 501.** C'est le statu quo effectif : 76 % jusqu'à 2,5 M€ et environ 85 % au-delà pour une PME, 100 % sinon ;
- **VDQ non conforme : 100 %, sans facteur PME** ;
- **VDQ-C « haute qualité » : 80 %, dormante** (P4), non cumulable avec l'art. 501.

**Le 130 % du stade précoce de la version initiale est retiré du texte.** Il devient une **hypothèse de calibrage**. Le rapport de l'EBA à 3 ans (P10) doit la tester selon une méthode fixée à l'avance. Si elle est confirmée, la voie est législative.

**Problème et ancrage factuel.**
- **L'approche standard ne distingue pas les stades.** Une start-up non notée reçoit 100 %, soit 76 à 85 % avec le facteur PME (`micro-analysis.md` §5.1).
- **Le « sous-capital » de l'*early stage* n'est pas établi.** La version initiale le déduisait d'un « test de suffisance » : le capital minimal (8 % × pondération) était comparé à la perte nette d'une année de stress (9,7 %). **Ce test est retiré.** Il comparait le capital, qui couvre la perte **inattendue**, à une perte **totale**, qui inclut la perte attendue. Or cette dernière est absorbée par les provisions (8,71 % de l'encours *early stage* chez First Citizens) et par une marge de 5 à 10 points (`micro-analysis.md` §3.2, §2.1).
- **Deux autres défauts du test.** Il reposait sur une convention de capital différente de celle du chiffrage des coûts (§0.6). Il s'ancrait sur un seul prêteur survivant, en une seule année de stress, ce que `micro-analysis.md` §8.4 qualifie lui-même d'« actuariellement faux ».
- **La sélection adverse vers l'*early stage* est inférée [I], non observée dans l'Union.** La part bancaire est inconnue (`macro-analysis.md` §1.4). Les banques universelles se concentrent sur la famille (c) (`micro-analysis.md` §5.5). Le pilier 2 est disponible : limites par stade (P8), stress « gel VC » et présomption de revue (P9).
- **Sans volet standard, l'IRB est neutralisé par l'output floor** (`current-regulation.md` §3.4 ; `macro-analysis.md` §4.3).
- **Garde-fou n° 1** : à défaut de données, un compartiment « à visée statistique et de supervision plutôt que d'allègement » (`macro-analysis.md` §6). C'est exactement la configuration de lancement retenue.

**Mécanisme.**
1. **Nouvel article** (par exemple 122b, numérotation à arrêter) :

   | Sous-catégorie | Pondération | Art. 501 | Pondération effective | Statut |
   |---|---|---|---|---|
   | VDQ conforme, P ou C | **100 %** | Cumulable | 76 % (≤ 2,5 M€), ≈ 85 % (au-delà), 100 % (non PME) | Actif : statu quo |
   | VDQ non conforme | **100 %** | **Non cumulable** | 100 % | Actif |
   | VDQ-C « haute qualité » | **80 %** | Non cumulable ; la plus favorable des deux options s'applique | 80 % (non PME ou ticket > 2,5 M€) | **Dormant** (P4) |
   | Venture debt subordonnée | — | — | 150 % (art. 128) | Inchangé |

2. **Choix politique documenté : cumul ou non-cumul du facteur PME pour la VDQ-P conforme.**

   | Option | Effet | Arguments pour | Arguments contre | Verdict |
   |---|---|---|---|---|
   | **Avec cumul** | Statu quo (76 %) | Pas de problème observé dans l'Union ; pas de surcharge de pilier 1 pour un risque inféré ; conforme à la demande documentée de l'ECON (`stakeholder-map.md` §6) ; option par défaut du garde-fou n° 1 | Maintient pour le segment le plus risqué un écart bâlois préexistant (le facteur PME) | **Retenue** |
   | Sans cumul | 100 %, +25 pb | Lecture la plus stricte du garde-fou n° 1 | Surcharge fondée sur une inférence ; coût politique ; les limites par stade du pilier 2 visent le même risque de façon ciblée | Écartée au lancement ; soumise au rapport à 3 ans |

   Le garde-fou n° 1 vise les pondérations **du compartiment**, qui valent toutes 100 %. Le facteur PME est une mesure horizontale préexistante : le compartiment ne la crée pas et ne l'étend pas.
3. **Art. 501 : modification ciblée.** Le facteur PME n'est pas applicable aux VDQ non conformes. C'est le levier de discipline des critères de qualité (P1(4)). Il ne crée aucune pondération nouvelle ni non calibrée. Il **retire** un écart bâlois favorable là où la structure s'écarte des standards de marché.
4. **Output floor.** Ces pondérations servent de base au plancher. Pour une VDQ conforme, la base reste celle d'aujourd'hui.
5. **Hypothèse de 130 % (non inscrite) : protocole fixé à l'avance pour le rapport de l'EBA à 3 ans (P10).**
   - (a) Données de l'Union au niveau du prêt, de la phase 0 et du reporting, hors famille (c), avec correction du biais de survie.
   - (b) Test de couverture selon §0.6(b) : UL comparée à 8 % × pondération, EL comparée aux provisions et à la marge, sans jamais comparer une perte totale à un capital.
   - (c) Coûts exprimés selon la convention §0.6(a).
   - (d) Examen de la frontière avec les emprunteurs à EBITDA négatif non soutenus par un investisseur qualifié (P1, risque (iv)), pour éviter qu'une surcharge ne rouvre une incitation inversée.
   - (e) Conclusion sur trois options : 100 % avec cumul, 100 % sans cumul, 130 % sans cumul.

   Si le rapport conclut à une surcharge, la Commission présente une proposition législative ciblée (clause de revoyure, P10).

   **Pourquoi le 130 % n'est pas inscrit comme élément dormant activable**, à la différence des catégories d'allègement de P4 :
   - (i) Il se situe **au-dessus** de la référence bâloise (100 % pour une entreprise non notée) : l'Union peut toujours décider une super-équivalence, sans risque RCAP, donc sans besoin de pré-engagement.
   - (ii) Il suppose de retirer le facteur PME à une catégorie de PME. C'est un choix politique horizontal sur l'art. 501, qui relève des colégislateurs, et un élément essentiel au sens de l'art. 290 TFUE.
   - (iii) Une surcharge « suspendue » créerait un effet d'annonce sur le segment où l'objectif est la facilitation.
6. **Pas de montée en charge.** Le calendrier 100/115/130 % de la version initiale disparaît avec le 130 %. Il était d'ailleurs incohérent avec la montée de l'output floor : le 130 % aurait été atteint en 2031-2032, après la pleine application du plancher en 2030.

**Cadres connectés.** Art. 122a (gabarit), 123 (primauté), 128 (cohérence senior/junior), 501 (modification ciblée), 465 (plancher).

**Bénéfices attendus.**
- **Micro** (convention §0.6(a)) :
  - VDQ conforme : **neutre** (79 pb jusqu'à 2,5 M€ ; 88 pb au-delà pour une PME ; 104 pb pour un emprunteur non PME) ;
  - tickets de moins de 1 M€ aujourd'hui classables en clientèle de détail : **+20 pb** (57 % → 76 %) ;
  - VDQ non conforme : **+25 pb**, ou +45 pb depuis la clientèle de détail. Le coût de la discipline porte sur les seules structures atypiques ;
  - avec le produit InvestEU « Innovation & Digitalisation » (I&D) non plafonné existant (80 %) : **inchangé** pour une VDQ conforme, à 16 pb.
- **Macro :**
  - identification statistique ;
  - discipline des structures sans signal de durcissement sur l'*early stage* ;
  - sélection adverse suivie par le pilier 2 (P8, P9) et par les données (P10), et non corrigée *ex ante* par une surcharge.

**Risques et limites.**
- (i) **Le compartiment est « vide » en capital au lancement.** C'est assumé : c'est la configuration par défaut du garde-fou n° 1 et la condition de crédibilité de toute activation ultérieure.
- (ii) Si une sélection adverse apparaît avant le rapport à 3 ans, les outils de pilier 2 sont disponibles : présomption de revue au-delà de 5 % des fonds propres (P9) et exigence au titre de l'art. 104 CRD. Ils sont propres à chaque banque et plus rapides qu'une révision législative.
- (iii) Si le rapport confirme une surcharge, la voie législative ajoute 3 à 4 ans. C'est le prix de la preuve.
- (iv) La hausse de 20 pb sur les tickets de moins de 1 M€ est la seule hausse pour une exposition conforme ; elle est motivée en P1(8).

---

### P3 — Volet IRB : *slotting* dédié et optionnel, règle transitoire, EL fixées au niveau 1

**Résumé exécutif.** Ouvrir aux banques IRB un *slotting* propre à la venture debt, **optionnel** et choisi **au niveau du portefeuille**, avec deux grilles :
- **VDQ-C : 70 / 90 / 115 / 250 %.** Catégorie 1 dormante. Catégorie 2 active, comme **exception motivée** et bornée, à compter de l'application du RTS.
- **VDQ-P : 95 / 120 / 140 / 250 %**, soit les poids HVCRE de Bâle. Catégories 1 et 2 **dormantes**.

Les règles d'encadrement sont les suivantes :
- aucune pondération préférentielle pour maturité courte ;
- les EL sont fixées **au niveau 1** ;
- une règle transitoire s'applique jusqu'au RTS, qui sera disponible vers 2031 ;
- les critères sont définis par un **nouveau** RTS de l'EBA, qui réutilise la structure du règlement délégué (UE) 2021/598 tel que modifié à l'issue d'EBA/CP/2026/09.

Au lancement, l'approche PD suit les **règles générales** des entreprises. Les hypothèses propres à VDQ-P de la version initiale (corrélation HVCRE, suppression de l'ajustement de taille, LGD de 50 %) sont **renvoyées au rapport à 3 ans**, pour la même raison que le 130 % de P2.

**Problème et ancrage factuel.**
- **Obstacle des données.** Un portefeuille de quelques centaines de prêts, qui migre beaucoup et fait défaut rarement, est « difficile à valider » comme modèle de PD. C'est « l'argument le plus solide en faveur d'un *slotting* » (`micro-analysis.md` §5.2 ; `current-regulation.md` §2.4, §3.3).
- **Les banques IRB sont désavantagées.** Un modèle PD donne des pondérations de 100 à 130 % en *growth* et de 170 à 240 % en *early stage* sans ajustement de taille, soit **deux à trois fois plus qu'une banque en approche standard** (`micro-analysis.md` §5.2).
  - Une banque IRB pour laquelle la venture debt est non significative peut déjà appliquer l'approche standard à ce type d'expositions (utilisation partielle permanente, art. 150(1), second alinéa [vérifié, round 2]).
  - Le problème se concentre donc sur les **banques IRB spécialisées**, pour lesquelles ce portefeuille est significatif.
- **Sans catégorie 2 active, le *slotting* VDQ-C serait inutilisable.** La meilleure pondération disponible serait 115 % (catégorie 3). Pour un emprunteur non PME, c'est plus que les 100 % de l'approche standard. Pour une PME, c'est plus que les 85 % de l'approche standard avec facteur PME. `micro-analysis.md` §8.1(4) décrit exactement ce cas : la catégorie deviendrait « plus coûteuse pour les banques NI qui l'adopteraient que le statu quo SA, et ne serait pas utilisée ». Le problème (iv), seul à exiger le pilier 1 (§0.2), resterait sans réponse.
- **Les facteurs du *slotting* PF ne se transposent pas tels quels.** Deux se transposent bien (sponsor ; sûretés et contrôle). Deux sont à redéfinir (solidité financière ; caractéristiques de la transaction). Un se transpose partiellement (environnement juridique). **Quatre dimensions manquent** : dépendance au refinancement, cycle VC, concentration par sponsor, qualité de l'équipe (`micro-analysis.md` §7).
- **Les pondérations de 50 et 70 % pour une maturité inférieure à 2,5 ans sont inadaptées**, puisque la maturité effective est d'environ 2 ans (`micro-analysis.md` §6 friction n° 11).
- **L'analogue bâlois pertinent est la HVCRE** (95/120/140/250 %). Elle est **plus pénalisante**, pas plus favorable (`micro-analysis.md` §8.2 ; `macro-analysis.md` §2.2(3)).
- **Risque de compression.** Un *slotting* à 70-115 % comprimerait la différenciation et attirerait les risques les plus élevés (`macro-analysis.md` §4.3(3)).

**Mécanisme.**
1. **Tableaux de *slotting* dédiés** (nouvel art. 153(5a)). Une colonne unique s'applique, quelle que soit la maturité résiduelle.

   | Palier | Cat. 1 « solide » | Cat. 2 « bon » | Cat. 3 « satisfaisant » | Cat. 4 « faible » | Cat. 5 « défaut » |
   |---|---|---|---|---|---|
   | VDQ-C | *70 % — dormante (P4)* | **90 % — exception motivée** (point 3) | **115 %** | **250 %** | 0 % (EL, art. 158) |
   | VDQ-P | *95 % — dormante (P4)* | *120 % — dormante (P4)* | **140 %** | **250 %** | 0 % (EL, art. 158) |

   Ancrage du calibrage (`micro-analysis.md` §8.2) :
   - *growth stage* : la catégorie « naturelle » est « satisfaisant », et le meilleur quart relève de « bon » ;
   - *early stage* : la tendance est « faible », et « satisfaisant » ne vaut que pour les meilleurs profils. Rien ne soutient « bon » : d'où la dormance de la catégorie 2 VDQ-P.
2. **Perte attendue, fixée au niveau 1** (nouvel art. 158(6a)). Pour les deux paliers : **0,4 / 0,8 / 2,8 / 8 / 50 %**.
   - **Ce qui est corrigé.** La version initiale demandait à l'EBA de « vérifier si l'EL de 8 % suffit » pour VDQ-P, parce que la perte de stress (9,7 %) la dépasse. Ce raisonnement reproduisait la confusion corrigée en P2 : une perte d'année de stress contient de la perte inattendue, couverte par la pondération. Pour VDQ-P catégorie 4, cette pondération est de 250 %, soit un minimum de 20 % de capital.
   - **Pourquoi 8 %.** Une EL de 8 % reste cohérente avec les ordres de grandeur disponibles pour une catégorie qui regroupe les expositions les plus fragiles : 6 % de pertes annuelles moyennes en 2008-2010, période de stress ; environ 2 % par an de pertes réalisées sur l'ensemble des portefeuilles BDC de 2005 à 2022 (`micro-analysis.md` §3.1, §3.2).
   - **Suite.** La valeur est fixée par le législateur. Elle figure parmi les paramètres du rapport à 3 ans ; toute modification passe par la voie législative.
3. **Exception motivée : catégorie 2 VDQ-C à 90 %.**
   - **Pourquoi l'exception.** Sans elle, le *slotting* VDQ-C est plus coûteux que l'approche standard pour les banques qui en ont besoin (voir ci-dessus).
   - **Pourquoi elle est bornée.**
     - 90 % reste **au-dessus** de la pondération standard effective d'une VDQ-C PME (≈ 85 %) et du plancher (72,5 %).
     - 90 % est la valeur bâloise « *good* » du SL, sans préférence de maturité.
     - Pour une PME de croissance (PD ≈ 3 %, LGD de 40 %, chiffre d'affaires proche de 5 M€), la formule IRB bâloise **avec** l'ajustement de taille donne déjà environ 87 % [calcul propre, formule ASRF, M = 2,5]. Pour ces emprunteurs, la catégorie 2 ne s'écarte donc pas matériellement d'un résultat conforme à Bâle.
   - **Conditions d'application :**
     - (a) **effective seulement à compter de l'application du RTS**, vers 2031. L'EBA calibre alors les critères d'accès à la catégorie 2 sur les données de la phase 0 (P10) ;
     - (b) **comptée dans le plafond de 10 % des fonds propres** de P9, avec imputation au prorata ;
     - (c) soumise à la **désactivation fondée sur les pertes** de P4, point 4 ;
     - (d) le facteur PME s'applique comme aux autres expositions sur PME de la classe « entreprises » [à vérifier, H.5 point 2].
4. **Règle transitoire jusqu'à l'application du RTS.** Les établissements IRB appliquent aux VDQ l'approche PD générale. S'ils optent pour le *slotting* avant le RTS :
   - la catégorie 3 est la catégorie par défaut pour VDQ-C ;
   - la catégorie 4 est la catégorie par défaut pour VDQ-P ;
   - la catégorie 2 n'est pas accessible.
   
   Cette règle suit l'ancrage de `micro-analysis.md` §8.2 et la logique de la « catégorie 4 par défaut » de CP/2026/09. Elle n'est jamais plus favorable que l'approche PD pour les profils faibles.
5. **Choix entre PD et *slotting* au niveau du portefeuille.** Le choix se fait par palier, pour l'ensemble des VDQ du palier, et reste stable au moins 3 ans, sauf accord du superviseur. Il ne se fait pas exposition par exposition, ce qui permettrait de choisir au cas par cas la pondération la plus basse. C'est la logique de l'art. 153(5) : le *slotting* s'applique faute de pouvoir démontrer des estimations de PD conformes.
6. **Approche PD : règles générales au lancement.** Trois paramètres de la version initiale sont retirés du niveau 1 et deviennent des **hypothèses soumises au rapport à 3 ans** :
   - la corrélation HVCRE pour VDQ-P ;
   - la suppression de l'ajustement de taille PME (art. 153(4)) ;
   - une LGD F-IRB de 50 % pour VDQ-P.
   
   Comme le 130 % de l'approche standard, ce sont des durcissements de pilier 1 fondés sur une inférence : la corrélation « non estimable avec les données publiques » et une LGD calculée à partir d'un seul prêteur (`micro-analysis.md` §3.4, §4.3, §9). Le *slotting* VDQ-P, **optionnel**, conserve les poids HVCRE.
7. **Nouveau mandat de RTS** (nouvel art. 153(9a) ; il ne s'agit pas d'une extension de l'art. 153(9)).
   - **Contenu.** L'EBA précise les facteurs et leur pondération indicative, en **réutilisant la structure** du règlement délégué (UE) 2021/598 modifié. Elle reprend trois apports de CP/2026/09 : le sous-facteur « position dans la cascade de pertes », la suppression possible du plancher de 5 % pour un facteur non discriminant, et la catégorie 4 par défaut en cas de données manquantes.
   - **Frontière.** Le mandat inclut la **frontière** entre VDQ, OF/PF et famille (c), selon la source effective de remboursement. Cela évite un livrable distinct sous forme d'orientations (C.5 du round 1).
   - **Calendrier.** Projet de RTS dans les 18 mois suivant l'entrée en vigueur ; application vers 2031.

   | Facteur (réécrit) | Contenu (d'après `micro-analysis.md` §7 et §8.5) | Poids indicatif |
   |---|---|---|
   | Solidité financière | Runway sans nouveau tour ; LTER sur la dette totale ; pour le palier C, dette / ARR, marge brute, rétention nette, *burn multiple* ; stress de 12 à 18 mois sans tour | 25-35 % |
   | Solidité du sponsor | Qualité des chefs de file, réserves allouées, âge du fonds, largeur du syndicat, historique de soutien, co-investisseurs publics | 25-35 % |
   | Sûretés et contrôle | Premier rang y compris sur la PI, contrôle des comptes, *negative pledge*, covenants (P5), position dans la cascade (P6) | 15-25 % |
   | Transaction et technologie | Stade (TRL, phase clinique), traction, risque homme-clé, redéployabilité de la PI | 10-20 % |
   | Environnement juridique | Opposabilité des sûretés sur la PI, lieu de détention de la PI, disponibilité du *pre-pack* (directive 2026/799), risque réglementaire sectoriel | 5-10 % |

8. **Règles de migration anti-falaise** : revue trimestrielle, hystérésis symétrique et dérogations forcées (voir P5).
9. **VDQ non conforme** (P1(4)) : classement plafonné à la catégorie 3 et abaissé d'un cran.
10. **Aucune imputation des warrants** en réduction de la LGD, de l'EL ou dans le classement (voir P7.4).
11. **Propriété intellectuelle.** La PI n'est pas une sûreté éligible en F-IRB (`micro-analysis.md` §4.3 ; `macro-analysis.md` §3 point 4). Plutôt que de la rendre éligible, ce qui constituerait un écart à Bâle sans méthode de valorisation robuste, la PI est reconnue **comme sous-facteur du *slotting*** : inscription, redéployabilité, familles de brevets. L'EBA remettra un rapport, après la publication du cadre d'évaluation de la PI annoncé par la Commission (COM(2026) 615), sur l'opportunité d'une reconnaissance ultérieure en tant que « autre sûreté ».

**Cadres connectés.** Art. 150, 153(4), 153(5), 153(9), 158(6) et 161 CRR ; règlement délégué 2021/598 ; EBA/CP/2026/09 ; Bâle CRE33 (HVCRE) ; directive (UE) 2026/799 (*pre-pack* comme élément du facteur juridique) ; COM(2026) 615 (évaluation de la PI).

**Bénéfices attendus.**
- **Micro :**
  - **VDQ-C, emprunteur non PME, banque IRB non contrainte**, à partir de l'application du RTS : de 100-130 % (modèle PD) à 90 % pour le meilleur quart, soit **jusqu'à −42 pb/an** (130 % → 90 %). En catégorie 3 (115 %), l'effet va de +16 à −16 pb ;
  - **VDQ-C, PME** : effet à peu près neutre, facteur PME compris ;
  - **VDQ-P** : *slotting* de **140 à 250 %** au lancement, puisque les catégories 1 et 2 sont dormantes, et de 95 à 250 % après activation complète. Le *slotting* étant optionnel et choisi par portefeuille, aucune banque n'est contrainte de l'adopter ;
  - l'obstacle de validation des modèles disparaît pour les banques spécialisées.
- **Macro :**
  - la différenciation est préservée : pas de pondération à 50 ou 70 %, et le palier P est plus lourd ;
  - la catégorie 4 par défaut rend la méthode conservatrice ;
  - la seule préférence active est bornée par le plafond et désactivable.

**Risques et limites.**
- (i) Le *slotting* hors *specialised lending* est une divergence de **méthode** vis-à-vis de Bâle (P13).
- (ii) La catégorie 2 VDQ-C est un écart de **paramètre** favorable, déclaré, borné et immatériel (P13).
- (iii) Le RTS est le principal livrable de niveau 2 de la phase 1 et s'ajoute à CP/2026/09 (`stakeholder-map.md` §4). La réutilisation de la structure existante et l'intégration de la frontière dans le même RTS limitent la charge.
- (iv) Les poids des facteurs doivent être validés empiriquement (`micro-analysis.md` §8.3(5)).
- (v) L'EL de 8 % pour la catégorie 4 VDQ-P repose sur des données minces ; elle est réexaminée à 3 ans.

---

### P4 — Catégories dormantes fondées sur le risque, sans facteur de soutien : activation et désactivation sur données

**Résumé exécutif.** Le niveau 1 inscrit, **inactives**, des catégories dont les valeurs sont des **analogues bâlois lisibles**. Elles ne s'activent, par acte délégué fixant leur date d'application, que si des **critères objectifs et exhaustifs** fixés par le législateur sont remplis. Elles se désactivent selon des critères symétriques. L'habilitation elle-même est limitée dans le temps. La revue de l'effet d'offre passe par un rapport de la Commission, et non par une extinction automatique.

**Le facteur de soutien de 0,85 de la version initiale est retiré.** Il visait la falaise de 50 M€ de l'art. 501 pour VDQ-C. Il tombe pour cinq raisons (round 1, P4) :
- il créait une **nouvelle** discontinuité propre à la venture debt ;
- il **pénalisait la rentabilité**, puisqu'il cessait de s'appliquer lors de la sortie par le haut ;
- il reproduisait le schéma critiqué par le RCAP 2014, que le conditionnement aux données ne cure pas ;
- il n'avait pas d'effet d'offre démontré (EBA, 2016) ;
- un critère de pertes justifie l'ouverture d'une **catégorie de risque**, pas un facteur à plat.

La falaise de 50 M€ concerne toutes les entreprises. Elle relève d'un réexamen **général** de l'art. 501, hors du champ de ce paquet.

**Problème et ancrage factuel.**
- **Le garde-fou n° 1** interdit toute pondération standard inférieure à 100 % sans données validées (`macro-analysis.md` §6).
- **Aucune série de pertes européenne n'existe** (`micro-analysis.md` §8.3(7) ; `macro-analysis.md` §8.4 ; `benchmarking.md` §6).
- **Risque de « calibrage de complaisance »** ouvrant la voie à d'autres dérogations (`macro-analysis.md` §4.5, conclusion).
- **Un chemin plus court entre la preuve et la règle.** Sans catégories dormantes, chaque ajustement fondé sur les données exigerait une nouvelle codécision, soit 5 ans ou plus. L'inscription au niveau 1 de valeurs fixées par le législateur, avec des critères objectifs, ramène ce délai à celui d'un acte délégué.

**Comparaison des options (révisée).**

| Option | Contenu | Avantages | Inconvénients | Verdict |
|---|---|---|---|---|
| **0. Pilier 2 seul** (voie OCC) | Guidance, sans niveau 1 | Rapide, conforme à Bâle, précédent testé (`benchmarking.md` §2.3) | Ne règle ni l'obstacle de validation IRB, ni l'invisibilité statistique | Insuffisante seule |
| **0+. Pilier 2 + reporting + correctifs ciblés** | P8, P9 (pilier 2), P10 (ITS, collecte), Q&A sur les warrants, la *forbearance* et la titrisation, InvestEU recentré | Couvre l'essentiel des problèmes documentés (i), (ii), (v) et (vii) de §0.2, sans codécision | Ne règle pas l'obstacle IRB (iv) ; aucun réceptacle pour un recalibrage futur | **Retenue comme phase 0 du paquet et comme solution de repli autonome** |
| **A. Sixième sous-catégorie SL au sens strict** | Réécriture de l'art. 147(8) | Emprise de niveau 1 plus faible ; étiquette familière | Contamine le triple test ; le respect du garde-fou n° 4 dépend de la BCE ; collision avec la réserve de COM(2026) 615 | Écartée (§0.1) |
| **B. Facteur de type 501a** | Par exemple 0,75 ou 0,85 | Simplicité | Subvention à plat ; schéma RCAP 2014 ; pas d'effet d'offre démontré | **Écartée**, y compris sous forme dormante |
| **C. Socle réduit + catégories dormantes** (recommandé) | 0+ ; P1 à P3 à pondérations neutres ; catégories dormantes fondées sur le risque | Règle l'obstacle IRB ; réceptacle pour le recalibrage ; chemin court de la preuve à la règle | Emprise de niveau 1 ; allègement différé, peut-être jamais activé | **Recommandée, en complément de 0+** |

**Mécanisme.**
1. **Éléments dormants, avec des valeurs fixées au niveau 1 et sans marge de la Commission sur les niveaux :**
   - **approche standard : VDQ-C « haute qualité » à 80 %**, analogue du PF opérationnel de haute qualité (art. 122a). Elle n'est pas cumulable avec l'art. 501 ; la plus favorable des deux options s'applique. Les critères d'éligibilité sont fixés au niveau 1 et sont tous quantitatifs :
     - dette financière totale / ARR ≤ 0,5x ;
     - runway ≥ 24 mois sans nouveau tour, selon la méthode du RTS ;
     - rétention nette ≥ 100 % pour les revenus récurrents.
     
     Le critère « sponsors de premier rang » de la version initiale, non objectivable, est retiré ;
   - ***slotting* : catégorie 1 VDQ-C (70 %), catégories 1 et 2 VDQ-P (95 % et 120 %)**, avec les EL de P3.
2. **Critères d'activation, objectifs et exhaustifs (condition (ii) du round 1).** Ils s'apprécient pour chaque élément. Tous doivent être remplis :
   - **(a) Profondeur des données.** Au moins 5 ans de données de l'Union au niveau du prêt, hors famille (c), portant sur au moins 250 emprunteurs distincts relevant de l'élément visé. Au moins 2 de ces années doivent provenir du reporting réglementaire (P10), et non de la seule collecte rétrospective.
   - **(b) Couverture d'une phase basse.** La fenêtre d'observation comprend au moins une année où l'investissement VC dans l'Union a baissé d'au moins 30 % sur un an. L'indicateur est mesuré par la série de référence désignée au niveau 1 (P10), à titre indicatif −45,6 % en 2023.
   - **(c) Pertes attendues.** Le taux de perte annuel moyen réalisé sur la fenêtre est au plus égal à l'EL de la catégorie. Pour la catégorie standard à 80 %, la référence est l'EL de la catégorie 2 du *slotting* (0,8 %).
   - **(d) Pertes inattendues.** Le taux de perte de l'année la plus défavorable, diminué de l'EL, ne dépasse pas l'exigence minimale de pilier 1 associée à la pondération (8 % × pondération). C'est le test §0.6(b).
   - **(e) Corrélation.** La volatilité interannuelle des taux de défaut ne dépasse pas celle que produit la corrélation de référence : 12-24 % pour VDQ-C et 12-30 % pour VDQ-P, selon la méthode fixée par l'EBA dans le RTS.
3. **Instrument (conditions (i), (iii), (iv) et (v) du round 1).**
   - **Objet de l'acte délégué.** La Commission **adopte** un acte délégué fixant la **date d'application** d'un élément dormant lorsque le rapport de l'EBA établit que les critères (a) à (e) sont remplis. Le rapport est un élément d'appréciation, non une décision, ce qui écarte la difficulté liée à la jurisprudence Meroni.
   - **Contrôle des colégislateurs.** Le Parlement et le Conseil disposent des délais d'objection standard.
   - **Durée de l'habilitation.** Elle est conférée pour **8 ans** à compter de l'entrée en vigueur, **sans reconduction tacite**. Un rapport de la Commission est dû 9 mois avant l'échéance.
   - **Portée.** Le législateur fait le choix politique (valeurs et critères). La Commission constate et date, ce qui est un élément non essentiel (C-355/10 ; C-286/14 [non re-vérifié]).
   - **Précédent.** L'art. 461a n'est **pas** invoqué comme précédent. Il servait à différer un durcissement et son habilitation est épuisée [vérifié-auditeur].
4. **Désactivation symétrique (condition (vi) du round 1).** Si, sur une fenêtre glissante de 5 ans postérieure à l'activation, le critère (c) ou le critère (d) cesse d'être rempli, la Commission adopte selon la même procédure un acte délégué mettant fin à l'application de l'élément. Les expositions migrent à la revue suivante. L'indicateur (pertes réalisées issues du reporting de P10) est défini au niveau 1.
5. **Plafond.** Les éléments activés, comme la catégorie 2 VDQ-C, ne s'appliquent que dans la limite du plafond de 10 % des fonds propres (P9).
6. **Revue de l'effet d'offre, sans extinction automatique des catégories de risque.**
   - **Rapport.** Cinq ans après une activation, la Commission rend compte de l'effet d'offre, le cas échéant avec une proposition législative. L'indicateur est officiel : l'encours bancaire VDQ issu du reporting COREP ou d'AnaCredit, rapporté à l'investissement VC dans l'Union selon la série de référence désignée au niveau 1 parmi les statistiques publiées par la BCE ou par le groupe BEI. Les données commerciales aux définitions hétérogènes sont ainsi écartées (`macro-analysis.md` §0(a)).
   - **Écart motivé par rapport à la lettre du garde-fou n° 6.** Une catégorie activée parce que ses pertes sont compatibles avec son EL est un **paramètre de risque**. La supprimer faute d'effet d'offre ferait dépendre un paramètre de risque d'une métrique d'offre. C'est l'incohérence même que le round 1 reprochait au facteur 0,85 (« un facteur à plat n'est pas un paramètre de risque »).
   - **Ce qui reste automatique.** Le garde-fou n° 6 vise les mesures de type subvention, à l'image de l'expérience du facteur PME ; le paquet révisé n'en contient plus. L'extinction automatique est remplacée par deux mécanismes : la désactivation fondée sur les pertes (point 4) et la caducité de l'habilitation (point 3).
7. **Option par défaut si les colégislateurs refusent de déléguer.** Le rapport de l'EBA oblige la Commission à présenter, le cas échéant, une proposition législative ciblée (clause de revoyure, P10). Les valeurs et critères du point 1 et du point 2 servent alors de référence.

**Cadres connectés.** Art. 290 TFUE ; art. 122a (analogue PF 80 %) ; Bâle CRE33 (SL « *strong* » 70 % ; HVCRE 95 et 120 %) ; art. 501 (non-cumul).

**Bénéfices attendus (après activation éventuelle).**
- **Micro :**
  - VDQ-C non PME en approche standard : 100 % → 80 %, soit **−21 pb/an** ;
  - VDQ-C PME, ticket de plus de 2,5 M€ : ≈ 85 % → 80 %, soit −5 pb ;
  - banque IRB contrainte par le plancher (VDQ-C non PME) : 72,5 % → 58 %, soit −15 pb. Ce chiffre est inconditionnel, car il s'agit d'une pondération standard et non d'un facteur ;
  - *slotting* : catégorie 1 à 70 % (VDQ-C) et à 95 % (VDQ-P), catégorie 2 VDQ-P à 120 %.
- **Macro :** l'allègement **suit la preuve** et **s'efface** si la preuve se retourne. Aucun facteur de soutien n'entre dans la trajectoire.

**Risques et limites.**
- (i) L'activation peut ne jamais intervenir. C'est assumé.
- (ii) Une pression politique pour une activation anticipée est probable, y compris pendant la codécision. Des valeurs et critères fixés au niveau 1 la canalisent.
- (iii) Le conditionnement aux données **ne cure pas** une non-conformité au texte de Bâle : une catégorie activée reste un écart de méthode. Il en limite la matérialité et la rend défendable (P13).
- (iv) Compte tenu de la condition (a), l'activation n'est pas possible avant 2031-2032 environ.

---

## B. Covenants, séniorité et tranches

### P5 — Covenants : les reconnaître comme outils de contrôle et neutraliser leurs effets procycliques

**Résumé exécutif.** Les covenants de venture debt ne sont pas des tests de couverture de flux. Ce sont des **déclencheurs de contrôle**. La proposition :
- (i) en fait un critère de qualité (P1, Q2) ;
- (ii) les valorise dans le facteur « sûretés et contrôle » du *slotting* ;
- (iii) neutralise leurs effets procycliques par trois règles de migration : hystérésis **symétrique**, dérogations dures limitées, et absence de dégradation fondée sur les **seuls** indicateurs agrégés ;
- (iv) précise, **dans les limites de l'art. 47b CRR**, comment apprécier la condition de difficulté financière lorsqu'une renonciation à un covenant s'accompagne d'une injection d'equity **reçue**.

**Problème et ancrage factuel.**
- **Les covenants ne mesurent pas une couverture.** L'EBITDA est négatif, le DSCR est inférieur à 1 par construction et l'ICR est négatif. Les covenants sont une « option de sortie ou de contrôle » : trésorerie minimale, performance par rapport au plan, clause MAC, clause d'*investor abandonment*, jalons de levée, *equity cure* (`micro-analysis.md` §2.5).
- **Ils peuvent provoquer des défauts auto-réalisateurs** en phase basse du cycle, en particulier par les clauses d'abandon et les jalons de levée (`micro-analysis.md` §0 point 7 ; §6 friction n° 9).
- **Falaise du *slotting*.** Quand le runway tombe sous 6 à 9 mois sans *term sheet*, la pondération double d'un coup (`micro-analysis.md` §6 friction n° 10). Un retournement ferait migrer simultanément de nombreuses expositions (`macro-analysis.md` §2.3).
- **Migrations fréquentes.** Environ 17 à 34 % des portefeuilles BDC sont en grade 3 ou pire, même hors crise (`micro-analysis.md` §3.3).
- **Précédent OCC.** Les covenants de liquidité résiduelle ne suffisent pas, seuls, à garantir le remboursement (`benchmarking.md` §2.3).
- **L'art. 47b CRR définit la *forbearance* au niveau 1** [vérifié, round 2] : une concession accordée à un débiteur qui connaît ou risque de connaître des difficultés à honorer ses engagements. Son paragraphe 2 énumère des situations qui constituent une *forbearance*. Deux sont pertinentes ici : des conditions plus favorables que celles accordées à des débiteurs de profil de risque comparable (point (b)), et une exposition qui aurait été classée non performante sans la modification (point (c)). Une Q&A ou des orientations ne peuvent pas poser de présomption contraire à ce texte.

**Mécanisme.**
1. **Critère de qualité** (P1, Q2) : covenant de trésorerie minimale et reporting mensuel.
2. **Valorisation dans la grille** (RTS, P3). Sont valorisés les covenants de **contrôle** : trésorerie minimale ou runway, contrôle des comptes, reporting mensuel, tirages conditionnés à des jalons. Les clauses à « détente brusque » (*investor abandonment*, MAC) sont **neutres** : elles ne rapportent aucun point dans la grille, pour ne pas inciter à leur multiplication.
3. **Règles de migration** (RTS) :
   - **Hystérésis symétrique.** Une migration fondée sur les facteurs qualitatifs, dégradation **comme** amélioration, n'intervient qu'après deux évaluations trimestrielles consécutives dans le même sens (`micro-analysis.md` §8.3(1)).
   - **Dérogations dures, immédiates et à la baisse.** Classement automatique en catégorie 4 si le runway est inférieur à 6 mois sans *term sheet* signé, en cas de défaut de paiement, ou si la juste valeur du warrant est ramenée à zéro, signal prédictif de faillite (`micro-analysis.md` §8.3(3), §2.4).
   - **Indicateurs agrégés.** Aucune dégradation ne peut être fondée sur les **seuls** indicateurs agrégés du marché VC, en l'absence de détérioration propre à l'emprunteur. Les conditions de marché restent prises en compte à travers la situation de l'emprunteur : runway comparé au délai probable du prochain tour dans les conditions de marché observées, sous-facteur « conditions de marché » de la solidité financière. Ce choix de calibrage « à travers le cycle » respecte le principe IRB d'utilisation de toute l'information pertinente (art. 171(2) CRR [non re-vérifié]) et le garde-fou n° 5. Le facteur systémique est traité par le pilier 2 (stress « gel VC », P9).
   - **Articulation avec le provisionnement.** Le provisionnement IFRS 9 (P8(g)) intègre une correction prospective liée au cycle VC. Il n'y a pas de contradiction : le classement *slotting*, qui détermine le capital, est calibré à travers le cycle, tandis que les provisions IFRS 9 sont par construction prospectives et « à un instant donné ».
4. **Défaut et *forbearance*, dans les limites de l'art. 47b.** Instrument : une Q&A d'interprétation de l'EBA, puis une intégration dans EBA/GL/2018/06 lors de sa prochaine révision. Cohérence avec EBA/GL/2016/07.
   - **Appréciation de la condition de difficulté, au cas par cas et sans présomption.** Trois conditions doivent être réunies et documentées :
     - (a) une injection d'equity **effectivement reçue** (et pas seulement engagée) avant la renonciation au covenant ou en même temps, qui restaure au moins 12 mois de runway ;
     - (b) une renonciation accordée à des conditions qui l'auraient été à un débiteur sain de profil comparable (test de l'art. 47b(2)(b)) ;
     - (c) une exposition qui n'aurait pas été classée non performante sans la mesure (art. 47b(2)(c)).
     
     Si elles le sont, l'établissement peut conclure qu'il n'y a pas de **concession à un débiteur en difficulté**. L'appréciation reste soumise au contrôle du superviseur.
   - **Indicateurs forts de *forbearance*, conservés.** Une extension de maturité, une capitalisation d'intérêts (PIK) ou un rééchelonnement **sans** *equity cure* est présumé constituer une *forbearance*. Cette présomption va dans le sens de l'art. 47b.
   - **Conséquences.** Une exposition restructurée non performante suit le calendrier de couverture minimale de l'art. 47c [non re-vérifié]. Une renonciation non qualifiée de *forbearance* reste soumise à l'appréciation d'une hausse significative du risque de crédit (IFRS 9, P8(g)).
   
   Cette approche distingue le soutien réel du sponsor du renouvellement artificiel d'un prêt compromis (*evergreening*).
5. **Attente de pilier 2** (P8) : évaluation, au niveau du portefeuille, du risque auto-réalisateur des clauses d'abandon.
6. **Responsabilité du prêteur.** Le risque qu'un exercice intensif des droits de contrôle soit requalifié en gestion de fait ou en soutien abusif, selon les droits nationaux, est traité dans la cartographie de P12, niveau 1.

**Cadres connectés.** Art. 47b, 47c, 171 et 178 CRR ; EBA/GL/2016/07 ; EBA/GL/2018/06 ; règlement délégué 2021/598 (fréquence de revue) ; IFRS 9 ; OCC 2025-45.

**Bénéfices attendus.**
- **Micro :** des trajectoires de pondération plus stables ; moins d'accélérations forcées ; une distinction nette entre un covenant « outil de pilotage » et un covenant « détonateur » ; une sécurité juridique sur la *forbearance* sans conflit avec le niveau 1.
- **Macro :** c'est la réponse la plus directe au risque de **dégradations synchronisées** propre au *slotting* (`macro-analysis.md` §2.3 ; garde-fou n° 5).

**Risques et limites.**
- (i) L'hystérésis retarde d'un trimestre la reconnaissance d'une migration, dans les deux sens. Les dérogations dures bornent l'effet à la baisse.
- (ii) L'appréciation au cas par cas pourrait servir à maquiller des renouvellements artificiels. Elle est conditionnée à de l'equity **reçue**, au test du débiteur sain et au contrôle du superviseur.
- (iii) L'EBA pourrait refuser une règle sectorielle dans des orientations transversales. La Q&A d'interprétation suffit.

---

### P6 — Séniorité et facilités distinctes : une architecture « banque en senior, fonds en junior » et une frontière avec la titrisation clarifiée par Q&A

**Résumé exécutif.** La proposition repose sur cinq éléments :
- réserver la VDQ au **senior** ; le junior reste à l'art. 128 (150 %), sans nouvel allègement ;
- limiter l'architecture banque-fonds à des **facilités distinctes**, chacune créant une créance directe sur la société opérationnelle et liées par un accord inter-créanciers ; les *unitranche* à accord entre prêteurs (*first-out / last-out*) sont **exclus** ;
- reconnaître dans le *slotting* la **position dans la cascade de pertes**, avec deux bornes ;
- clarifier la frontière avec la titrisation par une **demande de Q&A**, et non par une modification du règlement Titrisation ;
- conditionner la reconnaissance d'une protection contractuelle à un **avis juridique**, qui peut être un avis de place.

**Problème et ancrage factuel.**
- **La structure dominante est le senior de premier rang.** Le junior est rare et fourni surtout par des fonds ; le HoldCo PIK européen se prête à 10-17 % (`micro-analysis.md` §2.3).
- **Falaise de subordination.** De 100 % à 150 % en approche standard, de 40 % à 75 % de LGD en F-IRB (`micro-analysis.md` §6 friction n° 4).
- **La coexistence avec un ABL exige un accord inter-créanciers.** Le sous-facteur « position dans la cascade de pertes » de CP/2026/09 est directement pertinent (`micro-analysis.md` §2.3, §7).
- **Asymétrie concurrentielle.** Les fonds relèvent d'AIFMD II (plafonds de levier de 175 et 300 %, limites par emprunteur), les banques du CRR (`stakeholder-map.md` §2, synthèse n° 3).
- **La subordination contractuelle est reconnaissable dès aujourd'hui en prudentiel, mais son opposabilité transfrontière est incertaine** (`current-regulation.md` §7.3, §8).
- **Le risque de requalification en titrisation n'est pas tranché.**
  - La définition (art. 2(1) du règlement (UE) 2017/2402) vise le « tranchage » du risque de crédit d'**une** exposition ou d'un portefeuille.
  - L'exclusion prévue pour les expositions présentant les caractéristiques de l'art. 147(8) repose sur le financement d'**actifs physiques** (considérant 50 du CRR) [vérifié-auditeur]. Or la VDQ en est dépourvue par définition. **Étendre cette exclusion à la VDQ n'aurait pas de fondement.**
  - La seule Q&A de l'EBA sur cette frontière (2014_786) a été rejetée sans réponse [vérifié-auditeur].
  - Le règlement Titrisation est **transsectoriel** et **en trilogue** : trilogue du 7 juillet 2026, prochain trilogue le 29 septembre 2026 [vérifié-auditeur].

**Mécanisme.**
1. **Senior seulement** (P1, Q5 et exclusions). Toute tranche junior, subordonnée ou mezzanine détenue par une banque reste traitée à 150 % (art. 128) et à 75 % de LGD F-IRB (art. 161). **Aucun allègement n'est créé pour le junior** (`micro-analysis.md` §1.1).
2. **Architecture limitée aux facilités distinctes.** La banque accorde un prêt senior ; un fonds, un ELTIF, le groupe BEI ou une banque nationale de développement accorde un prêt junior distinct (second rang ou HoldCo). Chacun porte sa propre créance directe, et un accord inter-créanciers écrit les lie. Il n'y a pas de tranchage du risque d'une exposition unique. Les porteurs éligibles de la tranche junior sont définis par renvoi :
   - FIA octroyant des prêts au sens d'AIFMD II (directive (UE) 2024/927), soumis à ses limites de levier et de rétention ;
   - ELTIF (le règlement ELTIF 2.0 permet l'octroi de prêts) ;
   - groupe BEI et banques nationales de développement.

   La banque garde le risque qu'elle sait gérer : senior, court, surveillé mensuellement. Le fonds porte le risque junior sans RWA et avec l'appétit qui lui est propre.
3. **Exclusion de l'*unitranche* à accord entre prêteurs.** Une facilité unique découpée en *first-out* et *last-out* se rapproche du tranchage d'une exposition. Elle est **exclue** de la VDQ. Elle relève du cadre titrisation si elle en remplit la définition. À défaut, elle reçoit le traitement « non conforme » (P1(5)), pour que l'exclusion ne devienne pas une sortie favorable.
4. **Cascade de pertes dans le *slotting*, avec deux bornes.**
   - Le RTS (P3) valorise la position de la tranche bancaire. Un *split-lien* défavorable face à l'ABL fait descendre en catégorie « satisfaisant » au mieux (`micro-analysis.md` §8.5).
   - Une tranche senior protégée par une tranche junior tierce **distincte, financée en cash**, contractuellement subordonnée et **représentant au moins 20 à 25 % de la dette totale**, peut obtenir la meilleure note du facteur « sûretés et contrôle ».
   - **Première borne.** L'amélioration ne joue **que** sur ce facteur. Elle ne peut jamais ouvrir l'accès à la catégorie 1, qui est de toute façon dormante.
   - **Seconde borne.** La tranche junior entre dans le **LTER calculé sur la dette totale** (P1, Q1) : elle réduit la LGD du senior, mais elle augmente le montant à refinancer au tour suivant, donc la PD.
   - L'approche standard n'est pas modifiée.
5. **Frontière avec la titrisation : une demande de Q&A remplace l'extension législative.** Une Q&A est demandée à l'EBA, traitée le cas échéant par le **Comité mixte des AES**, puisque le règlement est transsectoriel. Elle vise à confirmer que deux facilités distinctes, chacune créant une créance directe sur l'emprunteur et liées par un accord inter-créanciers, ne constituent pas un « tranchage » au sens de l'art. 2(1).
   - **Aucune modification** du règlement Titrisation n'est proposée dans le paquet de 2027, ni insérée dans le trilogue en cours.
   - Si la Q&A infirmait cette lecture, la question serait portée au prochain réexamen du règlement Titrisation.
6. **Sécurité juridique proportionnée.** Un avis juridique écrit et motivé n'est exigé que pour **reconnaître dans le *slotting* une protection** apportée par une tranche junior tierce ou par un accord inter-créanciers. Il n'est pas exigé pour le simple statut senior, que le CRR n'impose pas aujourd'hui de démontrer par avis.
   - Les **avis de place par juridiction**, entretenus par les associations professionnelles sur le modèle des avis de compensation (art. 296 CRR [non re-vérifié]), sont admis. Ils portent sur l'opposabilité dans l'État d'immatriculation et dans celui du centre des intérêts principaux de l'emprunteur.
   - Le coût est encore réduit par la cartographie de P12, niveau 1.

**Cadres connectés.** Art. 128, 161, 194 et 296 CRR ; CP/2026/09 ; AIFMD II ; ELTIF 2.0 ; règlement (UE) 2017/2402, art. 2(1) (interprétation par Q&A, sans modification) ; directive 2019/1023 (classes de créanciers, P12).

**Bénéfices attendus.**
- **Micro :** une meilleure note pour les tranches senior protégées, dans des bornes strictes ; une clarté juridique sans rouvrir un règlement en trilogue ; un coût d'avis juridique mutualisé ; la possibilité pour les banques de coopérer avec les fonds.
- **Macro :** la friction n° 3 de `stakeholder-map.md` devient une division du travail ; le risque junior, le plus sensible au cycle, reste hors des bilans de dépôt (`macro-analysis.md` §2.5).

**Risques et limites.**
- (i) **Interconnexion banques-fonds.** Canal 3 de `macro-analysis.md` §2.5, à surveiller dans P9 : les prêts bancaires aux fonds de venture debt relèvent du *fund finance* et restent hors VDQ.
- (ii) La Q&A peut infirmer la lecture des facilités distinctes. Dans ce cas, l'architecture de P6 perdrait sa reconnaissance dans le *slotting*, sans effet sur le reste du paquet.
- (iii) L'efficacité de l'accord inter-créanciers en procédure collective reste une question nationale (P12).

---

## C. Warrants

### P7 — Warrants et equity kickers : sécuriser la qualification et la pondération dans la lettre du texte, sans leur faire absorber de pertes

**Résumé exécutif.** L'effet des warrants sur le coût en capital est faible : moins de 0,1 point de spread (`micro-analysis.md` §0 point 5). Les vraies frictions sont d'ordre **juridique**. La version révisée les traite **d'abord par Q&A**, dans la lettre de l'art. 133(4) et de l'art. 91(2). Le niveau 1 n'intervient que pour codifier, si les Q&A sont insuffisantes. Le volet « programmes publics » (7.3) est **retiré**.

**Problème et ancrage factuel.**
- **Art. 133(4)** [vérifié-auditeur]. Le premier alinéa fixe 400 % pour les actions non cotées détenues « à des fins de revente à court terme » et pour les investissements de type capital-risque acquis en vue de « plus-values significatives à court terme ». Le second alinéa applique 250 % aux investissements **de long terme**, c'est-à-dire « détenus pendant trois ans ou plus, ou contractés avec l'intention d'être détenus trois ans ou plus, approuvée par la direction générale ». La relation d'affaires de long terme en est un **sous-cas**. **Insécurité juridique** : une monétisation avant trois ans peut faire basculer à 400 %, d'où une incitation à conserver les warrants (`micro-analysis.md` §6 friction n° 5).
- **Qualification.** Le warrant est-il une exposition actions ou un dérivé traité en risque de contrepartie (SA-CCR) ? « Aucune Q&A EBA spécifique n'a été trouvée » (`micro-analysis.md` §5.3).
- **SPPI.** Un kicker incorporé au prêt fait passer **tout** le prêt en juste valeur par résultat (`micro-analysis.md` §2.4, friction n° 6).
- **Fintechs.** Les warrants pris sur une « entité du secteur financier » pourraient relever du régime de déduction du CET1 (art. 36(1)(h) et 44-46), alors que le secteur financier est le premier secteur de la venture debt européenne en valeur (`micro-analysis.md` §2.4, [à vérifier]).
- **Art. 89.** Le seuil n'est pratiquement jamais atteint par les warrants (0,1 à 1 % du capital). Il ne devient plausible qu'après une **conversion dette-actions**. L'art. 91(1)(a) renvoie à l'art. 79, qui vise les entités du secteur financier. Mais l'art. 91(2) exclut déjà les actions qui ne sont pas des « immobilisations financières » au sens de la directive 86/635/CEE [vérifié-auditeur].
- **Pas d'effet d'assurance.** La compensation par les warrants est **inter-temporelle**, pas contingente à l'état du monde (`micro-analysis.md` §3.4, §4.3).
- **Précédents.** Le Royaume-Uni maintient 400 % pour l'equity VC (`benchmarking.md` §3.1). Aux États-Unis, le 12 CFR 7.1006 interdit de conditionner le remboursement du principal à la valeur du warrant (`micro-analysis.md` §2.4).

**Mécanisme.**
- **7.1 Qualification (Q&A, phase 0).** Les warrants et kickers reçus en contrepartie d'une VDQ sont des **expositions actions du portefeuille bancaire** au sens de l'art. 133(1). Ce ne sont pas des expositions de contrepartie traitées en SA-CCR. La Q&A est posée à l'EBA et transmise à la Commission au titre de l'art. 16b(2) du règlement EBA si elle appelle une interprétation du droit de l'Union. Un considérant ou article de niveau 1 n'intervient que si la Q&A est insuffisante.
- **7.2 Pondération (Q&A, phase 0 ; niveau 1 seulement pour codifier).** La Q&A confirme trois points :
  - (i) un warrant reçu en contrepartie d'un prêt, avec une **intention de détention d'au moins trois ans approuvée par la direction générale**, est un investissement de long terme au sens du second alinéa de l'art. 133(4). Il est pondéré à **250 %** ;
  - (ii) une cession **antérieure à trois ans causée par un événement de liquidité de l'emprunteur** que la banque ne contrôle pas ne remet pas rétroactivement en cause l'intention documentée : acquisition, introduction en bourse à l'expiration de la période de blocage, clause de sortie conjointe ou forcée ;
  - (iii) un *put* vers l'émetteur à la juste valeur, exercé **après** trois ans, ne requalifie pas l'exposition (la BEI monétise à 5-7 ans).

  Le seul cas résiduel à **400 %** est la **cession secondaire volontaire avant trois ans**. C'est le cas spéculatif que Bâle vise, et il est assumé. La formule « quelles que soient la durée de détention et la voie de monétisation » de la version initiale est **retirée** : elle aurait exigé une modification explicite du second alinéa de l'art. 133(4) et constitué un écart bâlois pour un gain d'environ 3 pb. Si la voie de la Q&A échoue, une modification de niveau 1 **codifie uniquement les points (i) à (iii)**, ce qui reste dans la lettre de Bâle. Les dispositions transitoires de l'art. 495a restent applicables.
- **7.3 Programmes publics : retiré.** L'art. 133(5)(a) exige des subventions ou garanties significatives « pour l'investissement » [vérifié-auditeur], c'est-à-dire pour l'exposition en actions. La garantie de P11 couvre le **prêt**, et le partage de l'*upside* avec le FEI est l'inverse d'une subvention. Une reconception par une garantie publique portant sur le warrant lui-même n'est pas proposée : elle ferait subventionner par le budget l'*upside* de la banque, ce qui contredit la logique de P11.
- **7.4 Interdiction d'imputation.** La valeur ou le rendement attendu des warrants ne peut être reconnu ni comme atténuation du risque, ni en réduction de la LGD ou de l'EL, ni dans le classement *slotting* (disposition expresse du RTS, P3).
- **7.5 Emprunteurs fintechs (Q&A, phase 0).** Une Q&A de l'EBA doit préciser si les warrants sur des instruments CET1 d'entités du secteur financier constituent des « détentions synthétiques » au sens de l'art. 36(1)(h). La recommandation est de les traiter **dans le seuil de 10 % du CET1 de l'art. 46**, comme les autres détentions non significatives, sans régime particulier. L'enjeu est la clarté, pas l'allègement.
- **7.6 Conversion dette-actions (Q&A d'abord ; niveau 1 conditionnel).**
  - **Q&A.** Elle doit préciser si des actions reçues par conversion de créances dans le cadre d'un plan de restructuration au titre de la directive (UE) 2019/1023, ou d'un *pre-pack* au titre de la directive (UE) 2026/799, et détenues en vue de leur cession, sont exclues du calcul par l'art. 91(2).
  - **Pourquoi elle peut ne pas suffire.** Des titres conservés plusieurs années, le temps d'un redressement, peuvent être comptabilisés comme immobilisations financières.
  - **Complément de niveau 1, seulement dans ce cas.** L'art. 91 est complété : les titres reçus dans ces procédures européennes harmonisées sont exclus des limites de l'art. 89 **pendant 5 ans**.
- **7.7 IFRS 9.** Aucune modification prudentielle. Les normes IFRS sont adoptées par l'Union via le règlement (CE) n° 1606/2002 et ne se modifient pas unilatéralement. Le critère de qualité Q4 (*kicker* détachable) incite à la comptabilisation au coût amorti. Un *kicker* incorporé fait passer le prêt en juste valeur par résultat, avec ajustements de valorisation prudente (art. 34 et 105), et le rend « non conforme » (P1(4)). Les amendements de l'IASB de 2024 sur la classification ne semblent pas couvrir les rémunérations indexées sur la valeur des titres [à vérifier].

**Cadres connectés.** Art. 133, 495a, 36(1)(h), 44-46, 89-91, 34 et 105 CRR ; règlement EBA, art. 16b ; directive 86/635/CEE ; règlement (CE) n° 1606/2002 ; directives 2019/1023 et 2026/799.

**Bénéfices attendus.**
- **Micro :** l'effet en capital est minime, environ 3 pb/an en passant de 400 à 250 % sur des warrants valant environ 2 % du principal. En revanche, la **sécurité juridique** supprime l'incitation à conserver les warrants au-delà de ce qu'exige l'intention documentée. La conversion dette-actions dans une restructuration n'est plus bloquée par l'art. 89.
- **Macro :** effet neutre, **sans écart bâlois**.

**Risques et limites.**
- (i) La Q&A peut ne pas lever toute l'ambiguïté. Le niveau 1 prend alors le relais pour codifier.
- (ii) L'articulation avec le régime de déduction des fintechs reste à trancher par `current-regulation-analyst`.

---

## D. Pilier 2, garde-fous et données

### P8 — Pilier 2 : une section « venture debt » dans les orientations EBA sur l'octroi et le suivi des prêts, et une recommandation à la BCE sur sa guidance relative à l'effet de levier

**Résumé exécutif.** Transposer en l'adaptant le précédent **OCC 2023-34 / 2025-45** **dans un instrument européen existant** : les orientations EBA/GL/2020/06. En parallèle, **recommander** à la BCE, qui est seule maîtresse de sa guidance de 2017, de substituer la nouvelle section à cette guidance pour les VDQ, sous conditions. Cette proposition ne requiert **aucune modification du niveau 1** et peut commencer dès 2026-2027.

**Problème et ancrage factuel.**
- **Le précédent le plus directement transposable, sans toucher au pilier 1,** est la guidance OCC : appétit au risque approuvé par le conseil d'administration, limites par stade, secteur et facteur de risque, agrégation des expositions, standards de souscription, provisionnement renforcé (`benchmarking.md` §2.3, §6).
- **Les lignes directrices BCE sur l'effet de levier sont inadaptées.** Une entreprise financée par du VC, détenue à plus de 50 % par des « sponsors financiers » et à EBITDA négatif, entre vraisemblablement dans leur champ, **sans ratio de levier calculable** (`micro-analysis.md` §5.4 ; `macro-analysis.md` §2.6).
- **Garde-fou n° 4** : pas de sortie automatique de leur champ (`macro-analysis.md` §6).
- **La contrainte liante n'est pas le capital** mais « la culture du risque et l'encadrement de supervision » (`macro-analysis.md` §5.2(3)).
- **Priorités de supervision de la BCE** : qualité de souscription (`stakeholder-map.md` §4).

**Mécanisme.**
1. **Nouvelle section d'EBA/GL/2020/06**, placée à côté des dispositions sectorielles existantes [numérotation à vérifier]. Base juridique : art. 16 du règlement EBA ; art. 74 et 79 CRD. Elle s'applique directement à tous les établissements, significatifs ou non. Contenu :
   - **(a) Appétit au risque** approuvé par le conseil d'administration, avec des limites par palier (P/C), par secteur (y compris l'IA), **par sponsor** et **par millésime**.
   - **(b) Agrégation** de toutes les expositions venture, quel que soit leur portefeuille ou leur intitulé comptable (repris de l'OCC).
   - **(c) Souscription : un écart assumé par rapport à l'OCC.** L'OCC pose qu'un tour futur non engagé n'est **pas** une source de remboursement primaire acceptable. La version européenne le remplace par un **test de capacité** : le prêt doit pouvoir être servi jusqu'à maturité, ou jusqu'à un niveau d'amortissement défini, **sans nouveau tour pendant 12 à 18 mois**, grâce au runway existant et aux tranches engagées (`micro-analysis.md` §7, facteur 1).
     - **C'est moins exigeant que l'OCC, et le texte doit le dire.** La définition VDQ repose précisément sur cette source de remboursement : l'interdire reviendrait à interdire l'activité.
     - **Compensation.** L'écart est compensé par les limites par stade, par sponsor et par millésime (a), et par l'exigence de documenter dans le dossier de crédit la source de remboursement attendue. Cette exigence reprend le critère retiré de la définition (P1, C2).
   - **(d) Diligence sur le sponsor** : âge du fonds, réserves allouées, historique de soutien (`micro-analysis.md` §7, facteur 4).
   - **(e) Suivi** : reporting mensuel, revue trimestrielle du *slotting*, signaux de marché (P5).
   - **(f) Gouvernance des warrants** : valorisation indépendante, ajustements de valorisation prudente, interdiction d'imputation (P7).
   - **(g) Provisionnement IFRS 9** : correction prospective liée au cycle VC ; indicateurs de hausse significative du risque de crédit (tour en baisse, juste valeur du warrant à zéro, bris de covenant de trésorerie).
   - **(h) Lien actif-passif** : les clauses de domiciliation de la trésorerie sont recensées et reliées au suivi de liquidité (P9).
   - **(i) Éléments repris de la guidance BCE**, pour que la substitution ne soit pas un allègement déguisé : limites de portefeuille, reporting périodique à l'organe de direction, revue indépendante des exceptions.
   - **(j) Proportionnalité** pour les portefeuilles de petite taille.
2. **Recommandation à la BCE (MSU)**, qui ne fait pas partie du paquet législatif. Les VDQ sortiraient du champ de la guidance **à condition** que la banque applique la section « venture debt » et que l'équipe de supervision conjointe ne s'y oppose pas.
   - **Plan B, si la BCE ne donne pas suite.** Les VDQ restent dans le champ de la guidance, par la voie des « exceptions documentées » que celle-ci prévoit, instruites au regard de la section de l'EBA.
   - **Établissements moins importants.** La guidance ne s'y applique pas : la section de l'EBA s'applique directement, sans substitution.
3. **SREP.** Référence à la section « venture debt » dans l'évaluation du risque de crédit et de concentration (EBA/GL/2022/03).

**Cadres connectés.** Art. 74, 79 et 97 CRD ; règlement EBA, art. 16 ; EBA/GL/2020/06 ; guidance BCE de 2017 ; EBA/GL/2022/03 ; OCC 2025-45.

**Bénéfices attendus.**
- **Micro :** un cadre adapté remplace un cadre inopérant (levier non calculable), ce qui réduit une friction que la macro-analyse juge potentiellement plus lourde que le capital. Des standards communs réduisent aussi le coût d'entrée pour une banque sans expertise préalable.
- **Macro :** meilleure qualité de souscription ; limites par sponsor et par millésime (dimensions « absentes » du *slotting*, `micro-analysis.md` §7) ; aucun canal de ruée créé.

**Risques et limites.**
- (i) Charge de l'EBA ; réticence possible de la BCE, qui a durci sa supervision du levier depuis 2017. Le plan B existe.
- (ii) Des orientations appliquées selon le principe « se conformer ou s'expliquer » peuvent être mises en œuvre de manière hétérogène.
- (iii) L'écart avec l'OCC sera lu par certains superviseurs comme un abaissement des normes. Il est déclaré et compensé par les limites.

---

### P9 — Concentration, liquidité, coussin sectoriel et résolution : les leçons de SVB

**Résumé exécutif.** Mettre en œuvre les garde-fous n° 2, 3 et 5 de façon **proportionnée** :
- un **plafond de 10 % des fonds propres** pour les éléments préférentiels, avec imputation au prorata ;
- une **présomption de revue de pilier 2** au-delà de 5 % ;
- un **suivi des dépôts de l'écosystème VC** au-delà de seuils ;
- une Q&A sur les dépôts « opérationnels » ;
- un **sous-ensemble sSyRB préidentifié** ;
- une prise en compte dans la **planification de la résolution**.

Le compartiment ne doit pas recréer la double exposition corrélée actif-passif qui a fait tomber SVB.

**Problème et ancrage factuel.**
- **SVB relève du passif, pas des pertes de crédit.** Les prêts « investor dependent » représentaient 9 % du portefeuille et les passages en pertes 0,10 %. Les dépôts non assurés atteignaient 88 à 94 %, et plus de 40 Md$ ont été retirés en une journée (`macro-analysis.md` §2.4 ; `benchmarking.md` §2.2).
- **Un canal de ruée à ne pas introduire.** Faire migrer l'activité vers des banques de dépôt introduirait ce canal (`macro-analysis.md` §2.5).
- **Granularité faible** : le risque de concentration relève du pilier 2 (`macro-analysis.md` §2.2(2)). Le risque de concentration par sponsor et par millésime n'est pas capté par les grands risques (`micro-analysis.md` §5.4).
- **Liquidité** : le taux de sortie de 40 % sur 30 jours du LCR est « dépassé en une journée » (`macro-analysis.md` §2.6).
- **sSyRB** : il suppose un sous-ensemble identifiable et une pertinence systémique, non démontrable aujourd'hui (`macro-analysis.md` §2.6).
- **Résolution** : les portefeuilles de prêts à des entreprises non rentables assortis de warrants non cotés se valorisent mal en urgence (`macro-analysis.md` §2.7).
- **Scénario C** : l'émergence d'une ou deux banques spécialisées ferait revenir un point de défaillance unique (`macro-analysis.md` §5.3 ; §2.4, leçon n° 4).

**Mécanisme.**
1. **Plafond (niveau 1, sur le modèle de l'art. 133(5)).**
   - **Éléments visés.** Les éléments préférentiels sont la catégorie 2 VDQ-C du *slotting* (à compter de l'application du RTS) et les éléments dormants **une fois activés** (P4). Le facteur PME préexistant n'y est pas compté.
   - **Imputation au prorata.** Si la valeur exposée agrégée des expositions bénéficiant d'un élément préférentiel dépasse 10 % des fonds propres, l'élément s'applique à chacune d'elles pour une fraction égale à 10 % des fonds propres rapportés à cette valeur agrégée. Le reste reçoit le traitement non préférentiel : catégorie 3 en *slotting*, 100 % en approche standard. La règle est simple et ne se manipule pas par le choix des expositions.
   - **Ce n'est pas une interdiction** : une banque peut prêter au-delà, sans préférence.
   - **Distinction des plafonds.** Ce plafond est distinct de celui de l'art. 133(5), qui porte sur les expositions en actions des programmes législatifs. Ils ne se partagent pas.
2. **Présomption de revue de pilier 2.** Une revue renforcée dans le cadre du SREP est présumée si les VDQ dépassent **5 % des fonds propres**, **ou** si les dépôts de l'écosystème VC dépassent un seuil de l'ordre de **15 % des dépôts** [paramètre indicatif]. La revue porte sur :
   - la concentration dans l'ICAAP par sponsor, millésime et secteur, y compris l'IA ;
   - un **stress « gel VC »** de 12 à 18 mois sans tour, sur le modèle de 2022-2024 (`micro-analysis.md` §8.3(6)) ;
   - le cas échéant, une exigence de pilier 2 (art. 104 CRD).
3. **Liquidité, proportionnée :**
   - (i) **Groupe de contreparties « écosystème VC »** dans le modèle ALMM de concentration du financement : entreprises financées par VC, fonds VC, clients de *fund finance*. Il n'est déclaré que par les banques dont les VDQ dépassent **2 % des fonds propres**, ou dont les dépôts de l'écosystème VC, identifiés à partir des informations disponibles au titre de la connaissance du client, dépassent **5 % des dépôts** [paramètres indicatifs].
   - (ii) **Dépôts opérationnels : Q&A.** L'art. 27 du règlement délégué (UE) 2015/61 ne qualifie d'opérationnelle que la part du dépôt nécessaire au service [non re-vérifié]. Une Q&A doit confirmer que les dépôts détenus au titre d'une **clause de domiciliation liée à un prêt** ne sont pas, de ce seul fait, opérationnels. La question est transmise à la Commission au titre de l'art. 16b(2) du règlement EBA, car elle porte sur l'interprétation d'un acte délégué. La modification du règlement délégué relève de la Commission et n'est pas proposée.
   - (iii) **Scénario ILAAP** de sortie en un jour calibré sur SVB (environ 25 % des dépôts). Il est exigé, et l'art. 105 CRD peut être mobilisé, **uniquement au-delà des seuils de présomption du point 2**.
4. **sSyRB.** L'EBA complète ses orientations EBA/GL/2020/13 sur les sous-ensembles d'expositions sectorielles en y ajoutant **les VDQ**, ce que permet leur identification dans le reporting (P10). **Pas d'activation** tant que la pertinence systémique n'est pas démontrée (au plus 0,06 à 0,09 % des actifs ; `macro-analysis.md` §2.1 ; `micro-analysis.md` §1.2). L'outil est prêt si l'exposition agrégée croît.
5. **Résolution.** Pour les banques dont les VDQ dépassent 10 % des fonds propres, le CRU et les autorités nationales de résolution tiennent compte, dans les plans de résolution (art. 10 BRRD), de la valorisation sous stress des portefeuilles de prêts et de warrants et de la concentration des dépôts. C'est cohérent avec l'extension de l'évaluation de l'intérêt public aux banques petites et moyennes par la réforme CMDI (`macro-analysis.md` §2.7).

**Cadres connectés.** Art. 133(5) CRR (modèle du plafond) ; art. 104, 105 et 133 CRD ; règlement délégué (UE) 2015/61 ; règlement EBA, art. 16b ; ALMM (ITS de reporting) ; EBA/GL/2020/13 ; art. 10 BRRD ; réforme CMDI.

**Bénéfices attendus.**
- **Micro :** une banque spécialisée reste possible, mais elle paie sa concentration. Les banques peu exposées ne subissent pas de charge nouvelle en liquidité.
- **Macro :** le scénario C n'est plus favorisé ; la leçon n° 2 de SVB (le canal effectif est le passif) est intégrée ; le coussin sectoriel est prêt sans être activé.

**Risques et limites.**
- (i) Le plafond **pénalise l'acteur le plus actif**, sur le modèle de HSBC Innovation Banking (`stakeholder-map.md` §1.1). C'est un **arbitrage délibéré**, conforme à `macro-analysis.md` §2.4, leçon n° 4.
- (ii) Les seuils de dépôts sont des paramètres à calibrer sur les données de P10.
- (iii) Les dépôts de l'écosystème VC sont difficiles à identifier. Les informations collectées au titre de la connaissance du client et l'attribut de P10 y répondent partiellement.

---

### P10 — Données, calibrage, clause de revoyure : le préalable du paquet

**Résumé exécutif.** Faire du compartiment un **instrument de connaissance** avant tout paramètre de pilier 1. P10 est le **préalable séquentiel** du paquet, au sens suivant :
- (i) la collecte commence en **phase 0**, avant toute modification du niveau 1, sur la base de la définition de reporting de P1 ;
- (ii) **aucun paramètre de pilier 1 s'écartant de la neutralité ne s'applique avant le rapport de l'EBA à 3 ans**. La seule exception est la catégorie 2 VDQ-C, qui ne s'applique de toute façon qu'avec le RTS, vers 2031, après calibrage sur ces données ;
- (iii) les critères d'activation et de désactivation de P4 reposent sur les données de P10.

**Problème et ancrage factuel.**
- **Aucune série européenne de défaut ou de LGD n'existe.** C'est « le principal risque de mauvais calibrage » (`micro-analysis.md` §8.3(7) ; `macro-analysis.md` §8.4 ; `benchmarking.md` §6).
- **La part bancaire est inconnue.** « Aucune catégorie de reporting prudentiel ne permet d'identifier ces expositions » (`macro-analysis.md` §1.4).
- **Biais de calibrage** : calibrer sur 2010-2021, inclure la famille (c) ou retenir les seuls prêteurs survivants rendrait la grille « actuariellement fausse » (`micro-analysis.md` §8.4).
- **Garde-fou n° 6** : clause de revoyure et extinction (`macro-analysis.md` §6).
- **Le groupe BEI est le premier fournisseur européen** : 338 opérations et 8,4 Md€ en cumul selon sa présentation de juin 2025 (`micro-analysis.md` §2.2 ; `macro-analysis.md` §1.4). `stakeholder-map.md` §1.3 cite 6,8 Md€ et environ 300 entreprises, sur un périmètre et à une date différents. Le chiffre d'un FEI soutenant « environ 30 % du marché », faiblement sourcé et incompatible avec l'estimation d'une BEI à 5-6 % du marché en valeur, **n'est pas utilisé**.
- **Le reporting n'a pas besoin d'une sous-catégorie de pilier 1.** Les ITS pris au titre de l'art. 430 peuvent exiger des ventilations par caractéristique, comme pour les expositions restructurées ou les secteurs NACE (round 1, P10).

**Mécanisme.**
1. **Phase 0 : collecte au titre de l'art. 35 du règlement EBA**, lancée en 2027. Elle porte sur les expositions répondant aux critères de caractérisation de P1, **rétrospectivement depuis 2019**, afin de couvrir la phase basse de 2022-2024. Elle est adossée aux exercices de suivi de l'EBA.
2. **Phase 0 : ITS de reporting (art. 430).** Ils introduisent une ventilation « VDQ » (palier, conforme ou non conforme) dans les modèles de risque de crédit, et un **modèle complémentaire** : stade, type de sponsor, LTER sur la dette totale, runway, catégorie de *slotting* le cas échéant, valeur des warrants, montant d'equity levé par l'emprunteur. Calendrier indicatif : adoption en 2028, première date de référence en 2029. Le groupe ALMM « écosystème VC » (P9) y est intégré.
3. **AnaCredit / IReF.** Ajout d'un attribut « venture debt » au règlement de la BCE sur AnaCredit, qui doit être modifié à cette fin, puis intégration dans l'IReF, dont le calendrier est incertain.
4. **Groupe BEI.** Un protocole d'accord EBA–groupe BEI organise la transmission de données anonymisées au niveau du prêt (défauts, recouvrements, stades, sponsors), y compris sur les portefeuilles garantis par le FEI. La BEI n'est pas soumise au CRR : l'accord est volontaire.
5. **Règles de calibrage :**
   - un cycle complet, **incluant 2022-2024** ;
   - l'exclusion de la famille (c) ;
   - la correction du biais de survie ;
   - aucune valeur des warrants dans les pertes ;
   - des tests de couverture selon §0.6(b), sans jamais comparer une perte totale à un capital.
6. **Clause de revoyure (niveau 1).**
   - **Rapport de l'EBA 3 ans après l'entrée en vigueur**, vers 2031. Il s'appuie sur les données rétrospectives de la phase 0 et sur les premières données réglementaires, et porte sur :
     - (a) la qualité des données ;
     - (b) l'hypothèse de 130 % et le cumul du facteur PME pour VDQ-P (protocole de P2, point 5) ;
     - (c) les hypothèses VDQ-P de l'approche PD : corrélation HVCRE, ajustement de taille, LGD de 50 % (P3, point 6) ;
     - (d) l'EL de la catégorie 4 VDQ-P ;
     - (e) la performance de la catégorie 2 VDQ-C ;
     - (f) les seuils des critères de qualité (LTER de 40 %) et du palier (5 M€).
     
     Le rapport conclut, le cas échéant, à une proposition législative de la Commission.
   - **Réexamen à 5 ans** : conditions d'activation et de désactivation de P4, effet d'offre (P4, point 6).
7. **Indicateurs officiels désignés au niveau 1 :**
   - encours VDQ issus du reporting COREP ou d'AnaCredit ;
   - pertes réalisées issues du même reporting ;
   - investissement VC dans l'Union selon une série publiée par la BCE ou par le groupe BEI.
   
   Les données commerciales aux définitions hétérogènes sont exclues (`macro-analysis.md` §0(a)).

**Cadres connectés.** Art. 430 CRR ; règlement EBA, art. 35 ; AnaCredit ; IReF ; statut de la BEI ; `macro-analysis.md` §6.6.

**Bénéfices attendus.**
- **Micro :** un coût de reporting modéré (voir H.6).
- **Macro :** il s'agit du « gain net pour la surveillance macroprudentielle, indépendamment de la pondération » (`macro-analysis.md` §2.6), obtenu **dès la phase 0**, et de la condition de tout recalibrage.

**Risques et limites.**
- (i) La coopération de la BEI est volontaire.
- (ii) Les données peuvent **confirmer** que l'allègement n'est pas justifié, ou justifier un durcissement. C'est l'objet même du dispositif.
- (iii) Les données rétrospectives sont de moindre qualité ; P4 exige donc au moins 2 ans de données réglementaires avant toute activation.
- (iv) La transition d'AnaCredit vers l'IReF peut retarder l'ajout de l'attribut.

---

## E. Partage des risques public (mesure autonome)

### P11 — Une fenêtre InvestEU puis FEC « dette de croissance », non plafonnée, découplée du volet CRR

**Résumé exécutif.** Un produit de garantie du FEI qui se justifie **par ses propres mérites** : garde-fou n° 7, préférence de COM(2026) 615 pour le partage des risques, précédent singapourien. Il **n'est plus la contrepartie** d'une surcharge prudentielle, qui a d'ailleurs disparu (P2). Le produit :
- **renvoie le palier VDQ-P au produit « Innovation & Digitalisation » (I&D) non plafonné existant** (jusqu'à 80 %, prêts jusqu'à 8,25 M€), plus généreux que la fenêtre initialement proposée [vérifié-auditeur] ;
- **cible l'additionnalité réelle** : tickets de croissance de **8,25 à 25 M€**, partage de l'*upside* des warrants, et éligibilité alignée sur les critères de caractérisation de P1 ;
- adopte, **pour les prêteurs qui recherchent un allègement en capital**, une variante **non plafonnée**. Seule une garantie non plafonnée permet la substitution des art. 213 à 215 CRR. Une garantie plafonnée protège par tranches : l'art. 234 renvoie alors aux règles de la titrisation [vérifié-auditeur] ;
- est ancré dans la programmation de l'instrument InvestEU du **Fonds européen pour la compétitivité (FEC)** pour 2028-2034.

**Problème et ancrage factuel.**
- **COM(2026) 615** privilégie, pour l'« économie immatérielle », le renforcement des capacités, les cadres d'évaluation de la PI et le **partage des risques**, pas les pondérations (`macro-analysis.md` §3, §4.5).
- **Garde-fou n° 7** : « Priorité aux canaux budgétés et plafonnés (garanties InvestEU, TechEU) plutôt qu'à un allègement général » (`macro-analysis.md` §6).
- **Le produit I&D existe en deux variantes, que `macro-analysis.md` §5.2(6) confond.**
  - La variante **plafonnée** comporte un plafond de pertes allant jusqu'à 25 %. Elle protège par tranches et ne produit donc pas de substitution en capital.
  - La variante **non plafonnée** garantit jusqu'à 80 %, avec un taux de plafond de 100 %, pour des prêts jusqu'à 8,25 M€ ; banques et prêteurs alternatifs sont éligibles [vérifié-auditeur].
  - La version initiale de P11 avait hérité de cette confusion.
- **Le plafond de 8,25 M€ est inférieur aux tickets de croissance** : 10 à 40 M€ à la BEI, P75 américain de 27,7 M$ (`micro-analysis.md` §2.1).
- **Benchmarking.** Singapour (EFS-VD) est le seul dispositif **explicitement dédié à la venture debt**, ouvert aux banques **et aux non-banques** (`benchmarking.md` §4.1).
- **Asymétrie banques/fonds** (`stakeholder-map.md` §2).
- **Changement de cadre financier.** Les approbations InvestEU s'arrêtent fin 2027. Le Conseil a arrêté sa position sur le FEC le 16 juin 2026, et un accord sur le cadre financier pluriannuel est visé pour fin 2026 [vérifié-auditeur]. **Rien ne garantit juridiquement** qu'une fenêtre existera. C'est une raison de plus pour que le volet CRR n'en dépende pas.

**Mécanisme.**
1. **Palier VDQ-P et tickets VDQ-C jusqu'à 8,25 M€ : le produit I&D non plafonné existant.** Aucune nouvelle fenêtre n'est créée. P11 recommande deux choses : **maintenir un produit d'innovation non plafonné** dans l'instrument InvestEU du FEC, et confirmer que les emprunteurs remplissant les critères C1 à C3 y sont éligibles. L'usage du produit par ces emprunteurs est suivi grâce à l'attribut de P10.
2. **Fenêtre « dette de croissance » : tickets de 8,25 à 25 M€.**
   - **Éligibilité définie de façon autonome** dans les conditions du produit, dès la phase 0. Elle reprend les critères de caractérisation C1 à C3 de P1, qui sont objectifs et indépendants du prêteur, et le seuil de revenus du palier C. Elle ne comporte **aucun renvoi dynamique** au CRR. Si la codécision modifiait P1, le produit conserverait ses critères jusqu'au cycle de programmation suivant.
   - **Taux de garantie jusqu'à 50 %**, avec une **rétention d'au moins 50 %** par le prêteur pour préserver sa responsabilité de souscription. Commission de garantie.
   - **Deux variantes, ouvertes à tous les intermédiaires éligibles, avec une tarification qui reflète leur coût** :
     - **non plafonnée** : substitution en capital, recherchée par les banques ;
     - **plafonnée** : certitude budgétaire. Les fonds AIFMD, pour lesquels l'enjeu n'est pas le capital, peuvent la préférer.
     
     Aucun type de prêteur n'est privilégié.
3. **Effet prudentiel (variante non plafonnée seulement).** Le FEI est une banque multilatérale de développement pondérée à 0 % (art. 117(2)), avec une contre-garantie de l'Union. La part garantie est donc substituée (art. 213-215) :
   - VDQ-C, emprunteur non PME : 100 % → **50 %**, soit **−52 pb** ;
   - VDQ-C, PME (ticket de 8,25 à 25 M€, facteur PME combiné d'environ 0,83-0,84) : ≈ 85 % → ≈ **42,5 %**, soit **−44 pb** ;
   - la variante plafonnée **ne produit pas** cet effet, sauf à structurer une titrisation synthétique avec transfert significatif de risque, ce qui est lourd pour une petite banque.
   
   Aucune nouvelle règle prudentielle n'est nécessaire.
4. **Partage de l'*upside*.** Une fraction des produits de warrants des prêts garantis, par exemple 25 à 50 %, est reversée au FEI. Les warrants compensent les pertes **dans le temps** (`micro-analysis.md` §3.4) : les recycler vers le budget de garantie finance les pertes des phases basses par les gains des phases hautes. Ce reversement exclut toute éligibilité des warrants à l'art. 133(5) : P7.3 est retiré.
5. **Coût budgétaire, en ordre de grandeur** [calcul propre, hypothèses explicites] :
   - **Enveloppe indicative de la fenêtre** : 1,5 à 2 Md€ de prêts garantis sur 2028-2034, soit 0,75 à 1 Md€ d'engagement de garantie à 50 %.
   - **Pertes attendues du garant.** Hypothèses : pertes annuelles du *growth stage* de 1,3 à 1,5 % en année de stress (First Citizens, 2023-2024) et plus faibles en phase haute ; durée de vie moyenne de 2 à 3 ans (demi-vie d'environ 2 ans). La perte cumulée par millésime serait d'environ 1 à 2 % en phase haute et de 2 à 4 % en phase basse. La part du garant atteindrait ainsi 0,5 à 2 % du volume, soit **environ 8 à 40 M€** sur l'enveloppe. Dans un scénario sévère où les pertes doublent, jusqu'à environ 80 M€.
   - **Recettes.** Commission de garantie et partage de l'*upside*. La juste valeur des warrants représente 1,4 à 3 % du principal ; un partage de 25 à 50 % représente 0,35 à 1,5 % du volume à long terme, perçu surtout en phase haute.
   - **Ordre de grandeur net** : **quelques dizaines de M€ au plus** sur la période, et non des centaines.
   - **Pour mémoire**, le produit I&D existant appliqué à l'*early stage* expose déjà le budget à 80 % × 6-9,7 %, soit **4,8 à 7,8 % du volume garanti par an en phase basse**. C'est une raison de suivre son usage par l'attribut de P10.
6. **Déclinaisons nationales et BEI :**
   - les banques nationales de développement (Bpifrance, KfW…) peuvent adosser des dispositifs nationaux aux **mêmes critères de caractérisation**, soit via le compartiment « États membres » d'InvestEU, soit au titre de l'**art. 21 du GBER** (aides au financement des risques), sous réserve de ses conditions ;
   - **TechEU** (70 Md€ en 2025-2027, dont de la « dette de scale-up » ; `macro-analysis.md` §1.2) peut cofinancer aux côtés d'une banque, en pari passu ou en tranche junior **distincte** (P6).
7. **Adaptation du modèle singapourien.** EFS-VD impose une détention locale d'au moins 30 %. Cette condition est **incompatible** avec le marché intérieur et avec le constat que 4 opérations de scale-up sur 5 ont un chef de file étranger. La condition européenne est l'établissement dans un État membre, selon les règles d'InvestEU. EFS-VD est un engagement de garantie gouvernemental ; la version européenne est **budgétée** par la provision de l'instrument.
8. **Pérennité.** Inscription de la fenêtre et du maintien d'un produit d'innovation non plafonné dans la programmation de l'instrument InvestEU du FEC pour 2028-2034. La conception des produits relève des partenaires chargés de la mise en œuvre : il s'agit d'une **recommandation de programmation**, sans garantie juridique, ce qui est assumé grâce au découplage.

**Cadres connectés.** Règlement (UE) 2021/523 ; FEC (2028-2034) ; produit FEI I&D non plafonné ; art. 117(2), 213-215 et 234 CRR ; GBER art. 21 ; TechEU ; COM(2026) 615 ; EFS-VD (Singapour).

**Bénéfices attendus.**
- **Micro :** un allègement en capital de −44 à −52 pb/an sur les tickets de croissance que le produit existant ne couvre pas ; le maintien du produit existant pour le palier P, soit 16 pb pour une VDQ-P conforme.
- **Macro :** budgété, conditionnel et ciblé sur une lacune documentée (garde-fou n° 7). C'est la **mesure la plus faisable politiquement** et elle ne dépend d'aucune modification du CRR.

**Risques et limites.**
- (i) **Coût budgétaire**, dans un contexte de négociation du cadre financier pluriannuel. Il reste modéré en ordre de grandeur.
- (ii) **Aléa moral.** La rétention de 50 % et la tarification y répondent.
- (iii) **Garantir ne crée pas d'equity.** Le plafond du marché fixé par le flux d'equity demeure (`macro-analysis.md` §1.5).
- (iv) **Aucune garantie juridique** que la fenêtre existera sous le FEC. Le découplage rend ce risque sans conséquence pour le volet prudentiel.

---

## F. Insolvabilité (volet découplé)

### P12 — Rang des créances : cartographie d'abord, définition autonome de l'instrument, harmonisation conditionnelle

**Résumé exécutif.** La proposition ne vise **pas** à harmoniser le rang de la venture debt face à l'ensemble des créanciers. Elle retient une trajectoire graduée, **dont seul le niveau 1 est proposé à ce stade** :
- **Niveau 1 (immédiat)** : **cartographie comparative** par État membre, et avis juridiques de place (P6).
- **Niveau 2(a), conditionné aux résultats de la cartographie** : reconnaissance, **entre les parties seulement**, des subordinations contractuelles et des accords inter-créanciers dans les distributions et dans la formation des classes. Le modèle est la conception étroite de la directive (UE) 2017/2399. Le champ repose sur une **définition autonome de l'instrument**, sans renvoi au CRR.
- **Élément (b), requalifié et traité à part** : la sphère de sécurité contre la requalification en prêt d'associé est une règle de **rang substantiel**, qui modifie la position des tiers. Elle est évaluée politiquement comme un quasi-niveau 3.
- **Niveau 3 (rang opposable à tous)** : **non recommandé**.

Ce volet est **découplé** du volet prudentiel : aucune proposition prudentielle n'en dépend.

**Précision sur le champ.** Le texte initial retenait déjà un champ **fondé sur l'instrument**, « indépendamment du type de prêteur ». La mention d'un champ « limité aux banques » provenait d'une note de synthèse de l'orchestrateur, et non de P12 (round 1, D.7). Le vrai défaut était ailleurs : le champ déclaré « instrument » reposait sur la définition VDQ du **CRR**, qui comportait des critères liés au processus du prêteur (dossier de crédit, covenants, LTER). Par cette définition, le champ **redevenait bancaire de fait**. La version révisée donne à P12 une **définition autonome**.

**Problème et ancrage factuel.**
- **Le rang des créances est une compétence nationale.** La directive 2019/1023 organise le *processus* mais pas le rang (`current-regulation.md` §7.2). La directive (UE) 2026/799 a **laissé le rang hors de son champ à chaque étape de 2022 à 2026** (§7.4).
- **Hétérogénéité nationale** : privilèges publics, sûretés globales, **reconnaissance de la subordination contractuelle** en procédure collective (neutralisée partiellement dans certains droits), rang des obligataires (`current-regulation.md` §8). Elle n'est documentée que **qualitativement**. Aucun État membre n'est identifié dans lequel la subordination convenue entre créanciers consentants serait méconnue. D'où le conditionnement du niveau 2 à la cartographie, qui est l'étape de collecte des preuves.
- **Précédent BRRD.** Le rang d'**une** catégorie d'**instruments** a été harmonisé pour un objectif étroit (résolution). Cet objectif systémique est **absent** ici (`current-regulation.md` §7.5).
- **Sensibilité politique.** Le volet est probablement une « ligne rouge » pour plusieurs États membres (`stakeholder-map.md` §7.2, synthèse n° 5).
- **Règles nationales de subordination des prêts d'associés [vérifié].**
  - En Allemagne, le § 39(1) n° 5 InsO subordonne les prêts d'associés. Le § 39(5) exempte l'associé non dirigeant qui détient 10 % au plus.
  - Le BGH (IX ZR 85/21, 26 janvier 2023) agrège les participations en cas de coordination du financement entre associés.
  - Un prêteur qui a exercé ses warrants et coordonne jalons et *equity cure* avec les fonds VC s'approche de ce cas.
  - Des régimes comparables existeraient en Espagne, en Autriche et en Italie [à vérifier].
  - Cette subordination joue de plein droit **au profit de tous les autres créanciers** : l'écarter modifie la position des tiers.

**Mécanisme.**

**Niveau 1 : cartographie, immédiate, sans harmonisation.** Elle est établie par la Commission et l'EBA pour chaque État membre et porte sur :
- (i) la reconnaissance de la subordination contractuelle et des accords inter-créanciers en procédure collective et dans les classes des plans de restructuration ;
- (ii) les seuils et conditions de requalification des prêts d'associés ;
- (iii) l'opposabilité et la réalisation des sûretés sur la PI ;
- (iv) les doctrines de responsabilité du prêteur (gestion de fait, soutien abusif).

C'est une reprise ciblée du volet « transparence » de COM(2022) 702. Véhicules : le rapport au titre de l'art. 33 de la directive 2019/1023, dû au 17 juillet 2026 [vérifié, round 2 : échéance confirmée ; publication non identifiée par recherche en ligne au 22 septembre 2026], ou le portail e-Justice. Les résultats alimentent les avis de place de P6.

**Niveau 2(a) : reconnaissance entre les parties, conditionnée à la cartographie.** Il n'est proposé que si la cartographie identifie au moins un État membre où la subordination convenue entre créanciers consentants, ou l'accord inter-créanciers, n'est pas respectée en procédure collective ou dans la formation des classes, avec un effet transfrontière documenté.

| Élément de conception | Précédent BRRD (directive 2017/2399, art. 108 BRRD) | Transposition proposée |
|---|---|---|
| Objet | Une seule catégorie d'instruments (senior non préférée) | Une seule catégorie d'instruments, définie **de façon autonome** (voir ci-dessous) |
| Effet | Rang **opposable à tous** : nouvelle strate dans la hiérarchie nationale | Effet **entre les parties uniquement** : la subordination convenue est respectée entre les créanciers qui l'ont acceptée, **sans modifier la position des tiers** |
| Conditions | Maturité initiale ≥ 1 an ; absence de dérivé incorporé ; référence contractuelle explicite au rang | Voir la définition autonome |
| Justification | Stabilité financière (résolvabilité) | Sécurité juridique transfrontière, **si** un problème est établi par la cartographie |
| Harmonisation | Minimale, une strate | Minimale, **procédurale et inter-créanciers** |

**Définition autonome de l'instrument**, dans le texte d'insolvabilité et sans renvoi au CRR. Elle est vérifiable par un juge à partir du contrat et de registres publics :
- (i) un prêt à terme d'une durée initiale d'au moins un an ;
- (ii) un débiteur dont le capital a fait l'objet, dans les 18 mois précédant la conclusion du prêt, d'une augmentation souscrite, pour au moins 25 % du tour ou pour la part la plus élevée, par un investisseur relevant des statuts AIFMD, EuVECA, ELTIF, groupe BEI ou banque nationale de développement, ou d'un statut équivalent de pays tiers. C'est le noyau C1 de P1, **transposé** ;
- (iii) le cas échéant, un instrument de capital accordé au prêteur, **détachable** et donnant droit à 10 % au plus du capital ;
- (iv) un accord inter-créanciers écrit ou une clause contractuelle explicite de rang ;
- (v) **quelle que soit la nature du prêteur** : établissement de crédit, FIA, ELTIF, groupe BEI ou banque nationale de développement.

Aucun critère ne dépend du processus du prêteur : ni LTER, ni covenant, ni dossier de crédit. La définition peut donc s'appliquer au prêt d'un **fonds** junior comme à celui d'une banque senior, ce qu'exige l'architecture de P6.

Contenu du niveau 2(a) : les États membres veillent à ce que les subordinations contractuelles et les accords inter-créanciers relatifs à cet instrument soient respectés :
- (i) dans les distributions en procédure d'insolvabilité, **entre les parties** ;
- (ii) dans la **formation des classes** (art. 9 de la directive 2019/1023) et dans les **règles de priorité** du *cram-down* (art. 11).

C'est une règle de **processus**, qui s'insère dans une directive elle-même procédurale.

**Élément (b) : la sphère de sécurité contre la requalification, traitée à part.** Un prêteur qui détient, par des warrants détachables, **10 % au plus** du capital, et qui ne participe pas à la gestion, ne serait pas soumis à la subordination des prêts d'associés **du seul fait** de ces warrants **ou** de l'exercice de droits de covenant standards. Ce n'est **pas** une règle « entre les parties » : elle modifie la position relative des tiers, au profit desquels la subordination légale joue. Elle relève du **rang substantiel**, matière que la directive 2026/799 a exclue. Elle est donc :
- retirée du niveau 2 ;
- documentée par la cartographie, point (ii) ;
- évaluée politiquement comme un quasi-niveau 3.

Pour la plupart des États membres, elle serait confirmative : le § 39(5) InsO exempte déjà l'associé non dirigeant qui détient 10 % au plus.

**Véhicules.**
- **Réexamen de la directive 2019/1023** (art. 33). C'est le véhicule naturel du niveau 2(a), qui modifierait les art. 9 et 11, si la cartographie l'établit.
- **EU Inc (COM(2026) 321) : non chargé.** Y insérer des éléments de rang controversés ferait porter à un autre dossier un risque politique qui n'est pas le sien. Cette option est retirée.

**Variante limitée aux banques : explicitement écartée**, pour trois raisons :
- elle créerait la distorsion avec AIFMD II (`stakeholder-map.md` synthèse n° 3) ;
- elle serait autodestructrice pour P6, puisque l'accord inter-créanciers lie une banque senior et un **fonds** junior ;
- un rang fondé sur l'identité du créancier est étranger à la logique d'instrument du précédent BRRD.

**Niveau 3 : non recommandé à ce stade**, pour quatre raisons :
- (i) le précédent BRRD reposait sur un objectif systémique **absent** ici ;
- (ii) la directive 2026/799 vient d'exclure le rang après quatre ans de négociation ;
- (iii) cela toucherait aux privilèges fiscaux et salariaux ;
- (iv) le prêteur de venture debt est déjà senior et sécurisé : son problème est la **reconnaissance** de son rang, pas l'obtention d'un rang supérieur.

**Cadres connectés.** Directive 2019/1023 (art. 9, 11, 33) ; directive 2026/799 ; directive 2017/2399 (art. 108 BRRD) ; règlement (UE) 2015/848 (insolvabilité, refonte) ; AIFMD, EuVECA, ELTIF (statuts repris dans la définition autonome) ; art. 89 et 194 CRR.

**Bénéfices attendus.**
- **Micro :** des coûts d'avis juridiques réduits grâce à la cartographie ; une LGD senior plus prévisible si le niveau 2(a) est justifié.
- **Macro :** une réponse fondée sur des preuves à la **fragmentation**, désignée comme une contrainte « plus déterminante que la pondération » (`macro-analysis.md` §5.2(4)).

**Risques et limites.**
- (i) **Risque politique élevé**, même pour le niveau 2(a) (`stakeholder-map.md` §7.2) ; il est contenu par le conditionnement.
- (ii) Le découplage du volet prudentiel est **indispensable**.
- (iii) La cartographie peut conclure à l'absence de problème. Le niveau 2 n'est alors pas proposé ; c'est l'objet du conditionnement.
- (iv) La publication du rapport au titre de l'art. 33 reste à confirmer.

---

## G. Cohérence internationale, véhicule et séquençage

### P13 — Cohérence bâloise, véhicule législatif, séquençage et positionnement vis-à-vis de COM(2026) 615

**Résumé exécutif.** La proposition repose sur quatre choix :
- **Séquençage en trois phases.** Une phase 0 élargie, cœur du paquet et solution de repli autonome ; un socle de niveau 1 réduit ; des paramètres de pilier 1 fixés **après** les données.
- **Véhicule.** Un chapitre **distinct et séparable** du paquet législatif du T1 2027 issu de COM(2026) 615, articulé avec le réexamen du *specialised lending*.
- **Stratégie bâloise.** Un **recensement honnête** des écarts favorables, une matérialité appréciée **par composante et en cumul**, et une trajectoire **sans facteur de soutien**.
- **Charge de l'EBA** hiérarchisée.

**Problème et ancrage factuel.**
- **Aucun véhicule n'est engagé.** CP/2026/09 ne peut pas créer de catégorie (`current-regulation.md` §2.5, §9.5).
- **Codécision requise** (`stakeholder-map.md`, synthèse n° 1).
- **Agendas concurrents** de l'EBF et de l'EBA (`stakeholder-map.md`, synthèse n° 2).
- **Précédent RCAP 2014** : l'UE a été jugée « matériellement non conforme », notamment pour le traitement IRB des expositions PME, *corporate* et souveraines (`stakeholder-map.md` §4, §8 ; `macro-analysis.md` §4.2).
- **Positionnement de COM(2026) 615** : start-up et scale-up citées ; partage des risques et évaluation de la PI privilégiés ; *specialised lending* réservé aux investissements stratégiques (`macro-analysis.md` §4.5).
- **Aucun précédent dans le monde** : l'UE serait pionnière (`benchmarking.md` §6).
- **Bande passante et RSB.** Un chapitre de pilier 1 étendu, fondé sur une base de preuves mince, recevrait probablement un avis réservé du Regulatory Scrutiny Board. Un socle réduit, neutre en capital, a plus de chances de passer (round 1, P13).

**Mécanisme.**
1. **Séquençage (reséquencement C.6 du round 1, adopté avec trois ajustements).**

   | Phase | Période indicative | Contenu | Instruments |
   |---|---|---|---|
   | **0 : cœur du paquet et solution de repli** | Fin 2026 à 2028 | P10 : collecte au titre de l'art. 35 (rétrospective depuis 2019), ITS de reporting fondés sur la définition de caractérisation de P1, protocole avec la BEI ; P8 : section d'EBA/GL/2020/06 et recommandation à la BCE ; P9 : pilier 2, liquidité, Q&A sur les dépôts opérationnels, sSyRB ; P5(3)-(4) : Q&A sur la *forbearance* et orientations ; P6 : Q&A sur la frontière titrisation ; P7.1, P7.2, P7.5 et P7.6 : Q&A ; P11 : programmation InvestEU/FEC ; P12 : cartographie | Sans niveau 1 |
   | **1 : socle de niveau 1 réduit** | Proposition au T1 2027 ; adoption vers 2028 ; application vers 2029-2030 ; RTS applicable vers 2031 | P1 (corrigée) ; P2 (pondérations neutres ; art. 501 non applicable aux VDQ non conformes) ; P3 (*slotting* optionnel, règle transitoire, EL au niveau 1, catégorie 2 VDQ-C à compter du RTS) ; P4 (catégories dormantes, habilitation conforme à l'art. 290) ; P9 (plafond) ; P10 (clause de revoyure, indicateurs) ; art. 133(4) et 91 **seulement si les Q&A sont insuffisantes** | Niveau 1, puis RTS |
   | **2 : paramètres de pilier 1 sur données** | À partir de 2031 | Rapport de l'EBA à 3 ans après l'entrée en vigueur (hypothèses de P2 et P3, EL, seuils) ; recalibrage par voie législative ; activation ou désactivation des catégories dormantes par acte délégué (P4) ; réexamen à 5 ans | Rapport ; proposition législative ; acte délégué |
   | **Insolvabilité** | En parallèle, découplée | Niveau 2(a) seulement si la cartographie l'établit ; élément (b) à part | Réexamen de la directive 2019/1023 |

   **Les trois ajustements :**
   - (a) le chapitre de phase 1 est **séparable** : s'il n'entre pas dans le paquet de 2027, la phase 0 constitue l'option 0+ complète, sans perte ;
   - (b) le rapport à 3 ans est daté à partir de l'**entrée en vigueur**, et non de l'application, pour tirer parti des données rétrospectives ;
   - (c) la définition de **caractérisation** de P1 est un socle commun à plusieurs cadres, en couches : reporting (P10), éligibilité à la garantie (P11), définition autonome pour l'insolvabilité (P12), et, au niveau 1, classement prudentiel.

2. **Emprise de niveau 1 du socle réduit.**

   | Texte | Modifications |
   |---|---|
   | CRR, socle | Art. 147 (nouveau paragraphe : définition) ; nouvel art. 122b ; art. 123 et 147(5) (primauté) ; art. 501(2) (VDQ non conformes) ; art. 153 (nouveaux 5a et 9a) ; art. 158 (nouveau 6a) ; habilitation (art. 290 TFUE) ; plafond ; clause de revoyure et indicateurs |
   | CRR, conditionnel | Art. 133(4) (codification) et art. 91, seulement si les Q&A sont insuffisantes |
   | Retiré par rapport à la version initiale | Art. 2(1)(c) du règlement Titrisation ; nouvel art. 501b (facteur 0,85) ; hypothèses VDQ-P de l'approche PD (art. 153(4) et 161) ; montée en charge |
   | EBA | Phase 0 : une section d'orientations ; un ITS de reporting, qui intègre le groupe ALMM ; une collecte au titre de l'art. 35 ; environ cinq Q&A (warrants, fintechs, *forbearance*, dépôts opérationnels, titrisation) ; la contribution à la cartographie. Phase 1 : un RTS, qui intègre la frontière. Phase 2 : deux rapports. **Environ 10 livrables, contre 12 à 15 dans la version initiale.** |

3. **Stratégie bâloise : recensement honnête des écarts.**

   | Élément | Version initiale | Version révisée | Statut au lancement |
   |---|---|---|---|
   | *Slotting* hors *specialised lending* | Écart de **méthode** favorable | Maintenu ; pondérations égales aux valeurs bâloises SL et HVCRE ; optionnel | Écart de méthode **déclaré** |
   | Catégorie 2 VDQ-C à 90 % | Écart de **paramètre** favorable, présenté à tort comme conforme au principe de dormance | Maintenue comme exception motivée, à compter du RTS (vers 2031), sous plafond, désactivable | Écart de paramètre **déclaré**, immatériel |
   | Warrants à 250 % « quelle que soit la voie de monétisation » (P7.2) | Écart favorable, présenté à tort comme « dans la lettre de Bâle » | **Retiré** : Q&A dans la lettre de l'art. 133(4) ; 400 % maintenu pour la cession volontaire avant 3 ans | **Aucun écart** |
   | Facteur 0,85 (trajectoire) | Nouveau facteur de soutien potentiel | **Retiré** | — |
   | Catégories dormantes (trajectoire) | Analogues bâlois | Maintenues, activation sur critères objectifs, désactivation symétrique | Écart de méthode **potentiel**, conditionné |

   **Éléments plus stricts que Bâle :**
   - la grille VDQ-P aux poids HVCRE ;
   - l'absence de pondération préférentielle pour maturité courte ;
   - la catégorie 4 par défaut ;
   - la primauté sur la clientèle de détail ;
   - le **retrait du facteur PME** pour les VDQ non conformes, qui **réduit** un écart préexistant.

4. **Matérialité appréciée par composante, en cumul.** Le RCAP apprécie la matérialité **par composante**, en agrégeant les écarts.
   - **Le stock existant.** La composante « risque de crédit » de l'Union porte déjà plusieurs écarts : facteur PME (art. 501), facteur infrastructures (art. 501a), mesure transitoire à 65 % pour les entreprises non notées de PD ≤ 0,5 % (jusqu'en 2032), traitement des programmes législatifs à 100 % (art. 133(5)), notamment.
   - **La contribution du paquet révisé.** Au lancement, elle se limite à **un écart de paramètre** (catégorie 2 VDQ-C, effective vers 2031) et à **un écart de méthode** (*slotting* hors SL). Le segment pèse au plus 0,06 à 0,09 % des actifs bancaires, selon qu'on retient 19,2 ou 28,9 Md€ (`macro-analysis.md` §2.1 ; `micro-analysis.md` §1.2). Le paquet retire aussi le facteur PME sur les structures non conformes.
   - **Conclusion.** Cet ajout, **immatériel seul**, s'ajoute à un stock qui a déjà produit le constat de 2014. La configuration de lancement ne devrait **probablement** pas faire basculer la note de la composante. Le risque réel tient à la **trajectoire** (activations) et à l'**effet de précédent** : d'autres secteurs pourraient demander un *slotting* hors SL. Ces risques sont traités par des critères d'activation publics et fondés sur les pertes, et par une contribution au Comité de Bâle.
5. **Contribution au Comité de Bâle.** Une fois les données de P10 disponibles, l'Union proposerait un travail sur le « prêt aux entreprises innovantes adossé au capital-risque ». Elle y jouerait le rôle de **premier fournisseur de preuves** plutôt que de dérogataire.
6. **Véhicule.** Le paquet du T1 2027 comporterait un chapitre « financement bancaire des entreprises innovantes » regroupant le socle de phase 1. Ce chapitre est **distinct** du réexamen du SL, mais s'y **articule** : la famille (c) (GPU, data centres, gigafactories, flottes) est renvoyée à l'OF et au PF, et le réexamen du SL « pour investissements stratégiques » devrait couvrir ces financements d'actifs d'entreprises financées par VC (`macro-analysis.md` §3 point 2).
7. **Positionnement vis-à-vis de COM(2026) 615 :**
   - **convergences** : partage des risques (P11), évaluation de la PI (P3, sous-facteur et rapport), renforcement des capacités (P8), mention des start-up et scale-up ;
   - **écart assumé** : la Commission **n'annonce pas** de sous-catégorie de pilier 1 pour la venture debt. Le socle réduit en ajoute une, **neutre en capital**, justifiée par la **lisibilité, les données et l'obstacle IRB**, et non par l'allègement ;
   - **point de vigilance** : si la mesure transitoire de 65 % devient permanente, elle favorisera les grandes entreprises bien notées, pas les scale-ups (`macro-analysis.md` §4.5). Le compartiment n'en dépend pas.
8. **Coalition probable (corrigée)** :
   - **superviseurs (EBA, BCE)** : favorables à la phase 0 (données, pilier 2). Ils sont **réservés sur tout niveau 1** : l'option 0+ peut leur paraître suffisante. La neutralité en capital et les critères d'activation publics sont les arguments ;
   - **Commission** : partage des risques, alignement sur COM(2026) 615, charge du dossier d'impact réduite par le socle neutre ;
   - **commission ECON du Parlement** : la version initiale, qui retirait le facteur PME aux start-up, allait **contre** sa demande documentée de « flexibilité » (`stakeholder-map.md` §6), et l'ECON y était plus probablement opposée. La version révisée ne la heurte plus. Mais elle n'apporte pas non plus la « flexibilité » demandée : on peut s'attendre à des **pressions pour activer plus tôt** les catégories dormantes pendant la codécision. Des valeurs et critères fixés au niveau 1 les canalisent ;
   - **fonds de dette** : neutralité par P6 (facilités distinctes) et P11 (ouvert à tous, deux variantes) ;
   - **écosystème start-up** : plus aucun durcissement à redouter. La hausse de 20 pb sur les tickets de moins de 1 M€ reste un point d'attention ;
   - **banques** : peu d'allègement de pilier 1 au lancement, mais une sécurité juridique (warrants, *forbearance*, guidance BCE) et la catégorie 2 VDQ-C pour les banques IRB spécialisées.
   
   **Bilan** : une coalition **large mais peu engagée**. Aucun opposant fort, aucun champion fort : le principal risque est que le chapitre soit abandonné faute de bande passante. D'où la séparabilité : la phase 0 tient seule.

**Bénéfices attendus.** Un chemin législatif réaliste ; une crédibilité prudentielle ; une défense internationale fondée sur un recensement exact ; aucune dépendance du volet prudentiel envers le budget ou l'insolvabilité.

**Risques et limites.**
- (i) La bande passante du paquet de 2027 est limitée : la séparabilité y répond.
- (ii) Le dossier d'impact du chapitre de phase 1 reste à produire. Les ordres de grandeur de H.6 en sont l'amorce.
- (iii) Les pressions pour une activation anticipée sont probables. Les critères du niveau 1 les canalisent.

---

## H. Synthèse

### H.1 Effets en capital indicatifs par configuration (convention §0.6(a) : 1,04 pb par point)

| Configuration | Aujourd'hui | Lancement (phase 1) | Après activation éventuelle (phase 2) | Avec garantie non plafonnée |
|---|---|---|---|---|
| VDQ-C conforme, SA, emprunteur non PME (CA > 50 M€) | 100 % (104 pb) | 100 % (104 pb) : neutre | « haute qualité » 80 % (83 pb) : −21 pb | Fenêtre P11 (8,25-25 M€) à 50 % : 50 % (52 pb) : −52 pb |
| VDQ-C conforme, SA, PME, ticket > 2,5 M€ | ≈ 85 % (88 pb) | ≈ 85 % (88 pb) : neutre | 80 % (83 pb) si « haute qualité », non cumulable : −5 pb | ≤ 8,25 M€ : produit I&D existant à 80 % : ≈ 17 % (18 pb) ; 8,25-25 M€ : P11 à 50 % : ≈ 42,5 % (44 pb) |
| VDQ-P conforme, SA, ticket ≤ 2,5 M€ | 76 % (79 pb) | 76 % (79 pb) : neutre | Aucune catégorie dormante en SA pour le palier P | Produit I&D existant à 80 % : ≈ 15 % (16 pb), inchangé |
| VDQ-P conforme, ticket < 1 M€ (aujourd'hui classable en détail) | 57 % (59 pb) | 76 % (79 pb) : **+20 pb** (primauté, P1(8)) | Idem | I&D : 12 → 16 pb : +4 pb |
| VDQ non conforme, SA, ticket ≤ 2,5 M€ | 76 % (79 pb) ; 57 % (59 pb) si classée en détail | 100 % (104 pb) : **+25 pb** (+45 pb depuis le détail) | — | I&D : 20 % (21 pb) |
| *Hypothèse non inscrite, soumise au rapport à 3 ans* : VDQ-P à 130 % sans cumul | — | — | 130 % (135 pb) : +56 pb, seulement si le rapport la confirme et par voie législative | I&D : 26 % (27 pb) |
| VDQ-C, IRB non contraint, non PME, PD ≈ 2-3 % | ≈ 100-130 % (104-135 pb) | Avant RTS : approche PD inchangée, ou *slotting* catégorie 3 par défaut, 115 % (120 pb). Après RTS (vers 2031) : catégorie 2 à 90 % (94 pb) pour le meilleur quart, **jusqu'à −42 pb** ; catégorie 3 à 115 % | Catégorie 1 : 70 % (73 pb) | Substitution sur la part garantie |
| VDQ-C, IRB contraint par le plancher, non PME | 72,5 % (75 pb) | 72,5 % (75 pb) | 58 % (60 pb) si « haute qualité » SA activée | Substitution sur la part garantie |
| VDQ-P, IRB, PD ≈ 10 % | ≈ 170 % (177 pb) sans ajustement de taille ; ≈ 99 % (103 pb) avec ajustement de taille et facteur PME | Approche PD inchangée. *Slotting* optionnel : catégorie 3 à 140 % (146 pb), catégorie 4 à 250 % (260 pb) ; avant RTS, catégorie 4 par défaut | Catégorie 2 : 120 % (125 pb) ; catégorie 1 : 95 % (99 pb) | Substitution sur la part garantie |
| Warrants (juste valeur ≈ 2 % du principal) | 250-400 %, qualification incertaine | 250 % confirmé par Q&A pour une intention de détention ≥ 3 ans, y compris en cas de cession forcée par un événement de liquidité ; 400 % pour la seule cession volontaire avant 3 ans | — | (P7.3 retiré) |

**Lecture.**
- **Palier C :** au lancement, le compartiment est **neutre** en capital pour toutes les expositions conformes en approche standard. Il est modérément favorable, à partir du RTS, pour les banques IRB spécialisées sur le meilleur quart du palier C.
- **Coûts ciblés :** la hausse de 20 pb vise les plus petits tickets, classés hors détail. La hausse de 25 pb vise les structures non conformes, et elle est évitable.
- **Garantie :** le produit I&D existant reste inchangé pour le palier P. La fenêtre P11 apporte −44 à −52 pb sur les tickets de croissance qu'il ne couvre pas.
- **Suite :** tout recalibrage de pilier 1, à la hausse comme à la baisse, est **différé et conditionné aux données** (P4, P10).
- **Où est la valeur ajoutée :** la **lisibilité**, les **données dès la phase 0**, la levée de **frictions non capitalistiques** (warrants, guidance BCE, *forbearance*, obstacle IRB) et les **garde-fous**.

C'est cohérent avec `macro-analysis.md` §4.4 et §5 : le capital n'est pas la ressource rare, et un compartiment n'est « ni nécessaire ni suffisant ».

### H.2 Correspondance entre frictions micro et propositions

| Friction (`micro-analysis.md` §6) | Proposition(s) |
|---|---|
| 1. Définition du SL (binaire) | P1 |
| 2. Facteur PME (2,5 M€ ; 50 M€) | P2 : facteur maintenu pour les VDQ conformes, retiré pour les non conformes. **Falaise de 50 M€ : hors champ**, à traiter dans un réexamen général de l'art. 501 |
| 3. Portefeuille « clientèle de détail » (1 M€) | P1(8) (primauté de la VDQ, +20 pb affichés) |
| 4. Subordination (100 à 150 % ; 40 à 75 %) | P6 (pas d'allègement du junior ; facilités distinctes) |
| 5. Warrants (400 % ou 250 %) | P7.2 (Q&A) |
| 6. SPPI (IFRS 9) | P1 (Q4), P7.7 |
| 7. Art. 89 | P7.6 (Q&A, puis niveau 1 conditionnel) |
| 8. Guidance BCE sur l'effet de levier | P8 (recommandation, plan B) |
| 9. Covenants de levée et d'abandon | P5 |
| 10. Falaise du *slotting* | P5 (hystérésis symétrique, dérogations), P3 (paliers) |
| 11. Pondérations préférentielles pour maturité inférieure à 2,5 ans | P3 (supprimées) |
| 12. Frontière avec la famille (c) | P1(2)-(5), P3 (RTS), P13(6) |

### H.3 Carte des synergies avec les cadres adjacents

| Cadre | Renvoi ou synergie précise | Proposition |
|---|---|---|
| AIFMD (art. 6, 42) / EuVECA / ELTIF | Définition de l'investisseur qualifié (C1) | P1, P11, P12 |
| AIFMD, art. 3(2)(a) | Seuil de 100 M€ réutilisé pour objectiver le critère « pays tiers » | P1 |
| AIFMD II (fonds de prêt) / ELTIF 2.0 | Porteurs de la tranche junior distincte ; éligibilité à la garantie | P6, P11 |
| Règlement Titrisation, art. 2(1) | **Interprétation par Q&A** (facilités distinctes), **sans modification** | P6 |
| Art. 122a CRR | Gabarit de l'article standard ; analogue PF 80 % (dormant) | P2, P4 |
| Art. 123(1)(c) CRR | Fondement de la primauté sur la clientèle de détail | P1 |
| Art. 150 CRR | Utilisation partielle permanente : cible le *slotting* sur les banques IRB spécialisées | P3 |
| Art. 153(4) CRR | Seuil de 5 M€ (borne basse de l'ajustement de taille) | P1 |
| Art. 47b et 47c CRR | Limites de la clarification sur la *forbearance* | P5 |
| Art. 501 CRR | Maintenu pour les VDQ conformes ; retiré pour les non conformes ; non cumulable avec les catégories activées | P2, P4 |
| Art. 133(4) et 91(2) CRR | Q&A dans la lettre du texte ; codification conditionnelle | P7 |
| Art. 133(5) CRR | Modèle du plafond (distinct) | P9 |
| Art. 117(2), 213-215 et 234 CRR | Substitution par garantie non plafonnée ; protection par tranches si plafonnée | P11 |
| Règlement délégué 2021/598 / EBA/CP/2026/09 | Structure du nouveau RTS ; sous-facteur « cascade » ; catégorie 4 par défaut | P3, P6 |
| EBA/GL/2020/06 ; EBA/GL/2022/03 | Véhicule du pilier 2 | P8 |
| EBA/GL/2016/07 ; EBA/GL/2018/06 | *Forbearance* (Q&A, puis orientations) | P5 |
| Règlement délégué (UE) 2015/61 ; ALMM ; art. 105 CRD | Volet liquidité, avec seuils | P9 |
| CRD art. 133 ; EBA/GL/2020/13 | Sous-ensemble sSyRB préidentifié | P9 |
| BRRD art. 10 ; CMDI | Planification de la résolution | P9 |
| Art. 430 CRR ; règlement EBA art. 35 ; AnaCredit | Définition de reporting dès la phase 0 | P10 |
| InvestEU (règlement 2021/523) ; produit I&D non plafonné ; FEC ; TechEU ; GBER art. 21 | Partage des risques autonome ; éligibilité par critères de caractérisation | P11 |
| Directive 2019/1023 (art. 9, 11, 33) | Cartographie ; véhicule conditionnel du niveau 2(a) | P12 |
| Directive 2026/799 | *Pre-pack* dans le facteur juridique ; conversion dette-actions | P3, P7, P12 |
| Directive 2017/2399 (art. 108 BRRD) | Modèle d'une harmonisation étroite par instrument | P12 |
| Art. 290 TFUE | Habilitation à dater l'application, sans marge sur les niveaux | P4 |
| COM(2026) 615 | Véhicule législatif ; évaluation de la PI ; partage des risques | P3, P11, P13 |
| OCC 2025-45 ; EFS-VD (Singapour) | Adaptations explicites (test de capacité assumé comme moins exigeant ; pas de condition de détention locale) | P8, P11 |

### H.4 Ce que ce jeu de propositions ne fait pas, délibérément

- Il ne modifie **aucune pondération standard** des expositions conformes au lancement. La seule exception est la primauté sur la clientèle de détail, qui coûte 20 pb aux tickets de moins de 1 M€.
- Il ne crée **aucun facteur de soutien**, ni actif ni dormant.
- Il n'impose **aucun durcissement de pilier 1 fondé sur une inférence** : le 130 % et les hypothèses VDQ-P de l'approche PD sont renvoyés au rapport sur données.
- Il ne modifie pas le **règlement Titrisation**.
- Il ne porte pas l'étiquette « *specialised lending* » et ne réécrit pas le triple test de l'art. 147(8).
- Il n'étend pas le compartiment prudentiel aux fonds AIFMD. L'asymétrie est traitée par la complémentarité (P6), par l'ouverture de la garantie (P11) et par une définition d'insolvabilité indépendante du type de prêteur (P12).
- Il ne fait pas dépendre le volet prudentiel d'un budget (P11) ni d'une harmonisation de l'insolvabilité (P12).
- Il ne propose pas d'harmonisation générale du rang des créances.
- Il ne prétend pas combler l'écart transatlantique : celui-ci reflète d'abord l'écart d'equity (`macro-analysis.md` §1).

### H.5 Points ouverts à vérifier par les agents suivants

1. Le texte consolidé de l'art. 122a, de l'art. 153(5) et de l'art. 158(6), et le statut historique de la HVCRE dans le droit de l'Union (`current-regulation.md` §2.3 et limite n° 1 ; `micro-analysis.md` §7).
2. L'application de l'art. 501 aux expositions traitées en *slotting* et sa prise en compte dans le calcul standard qui sert de base à l'output floor.
3. La qualification des fonds VC comme « sponsors financiers » au sens de la guidance BCE de 2017 (`macro-analysis.md` §8.7).
4. La qualification des warrants (art. 133(1) ou SA-CCR) et l'application des art. 36(1)(h) et 44-46 aux fintechs (`micro-analysis.md` §5.3, §10).
5. La portée de l'art. 91(2) (notion d'« immobilisations financières » de la directive 86/635/CEE) pour des titres issus d'une conversion.
6. La numérotation des dispositions sectorielles d'EBA/GL/2020/06.
7. La publication du rapport au titre de l'art. 33 de la directive 2019/1023 : échéance au 17 juillet 2026 confirmée, publication non identifiée au 22 septembre 2026.
8. L'état de la négociation d'EU Inc (pour mémoire : il n'est plus proposé comme véhicule).
9. Les régimes de requalification des prêts d'associés en Espagne, en Autriche et en Italie ; les suites de l'arrêt BGH IX ZR 85/21.
10. La présence de la SEC parmi les autorités signataires des accords de coopération AIFMD (art. 42), pour le critère C1(v).
11. La réponse à la demande de Q&A sur la frontière avec la titrisation (phase 0).
12. La compatibilité de l'habilitation de P4 avec l'art. 290 TFUE, selon les conditions de conception retenues (jurisprudence C-355/10 et C-286/14 [non re-vérifiée]).
13. La programmation de l'instrument InvestEU du FEC pour 2028-2034, y compris le maintien d'un produit d'innovation non plafonné.
14. La portée des amendements IFRS 9 de 2024 sur les rémunérations indexées sur la valeur des titres.
15. Les orientations de l'EBA sur les méthodes de diversification au titre de l'art. 123 (mandat de CRR3) et leur articulation avec la primauté VDQ.
16. Le texte de l'art. 47c (couverture minimale des expositions non performantes) et de l'art. 27 du règlement délégué (UE) 2015/61.
17. Dans le fact-base, la confusion entre les variantes plafonnée et non plafonnée du produit I&D (`macro-analysis.md` §5.2(6)) et l'écart entre 19,2 et 20,1 Md€ pour le marché européen de 2025 (`macro-analysis.md` §1.3 ; `micro-analysis.md` §1.2), à corriger par les auteurs concernés.

### H.6 Ordres de grandeur des coûts (réponse à A.1 du round 1)

Il s'agit d'**estimations propres, sur hypothèses explicites, non sourcées**. Elles sont à affiner par une consultation ciblée pendant la phase 0. Le nombre de banques concernées est inconnu (`macro-analysis.md` §1.4) ; l'hypothèse de travail est de 30 à 150 banques de l'Union détenant des VDQ, dont moins de 20 en IRB avec un portefeuille significatif.

| Poste | Hypothèses | Ordre de grandeur |
|---|---|---|
| Reporting (ventilation et modèle complémentaire, P10) | Coût ponctuel de 50 à 150 k€ par banque (systèmes, données de table de capitalisation et de LTER) ; coût récurrent faible | 2 à 20 M€ au total, une fois |
| Classement et critères de qualité (P1) | Intégré au processus d'octroi existant (le reporting mensuel et la table de capitalisation sont standards en venture debt) | Marginal |
| Mise en œuvre du *slotting* (P3), optionnelle | 150 à 300 k€ par banque IRB qui l'adopte, pour moins de 20 banques | 1 à 6 M€, une fois, à partir de 2031 |
| Avis juridiques (P6) | Avis de place : 27 juridictions × 30 à 60 k€, mis à jour tous les 3 ans environ ; avis individuels seulement pour reconnaître une protection junior ou inter-créanciers | Environ 1 à 1,6 M€ par cycle pour la place ; quelques dizaines d'avis individuels par an |
| Pilier 2 et liquidité (P8, P9) | Revues renforcées seulement au-delà des seuils : probablement moins de 5 banques dans l'Union [I] | Faible |
| EBA | Environ 10 livrables sur 2027-2033 (C.5 du round 1) | Environ 10 à 15 équivalents temps plein-années, dont 40 % sur les données [estimation propre, à valider avec l'EBA] |
| Budget de l'Union (P11) | Fenêtre de 1,5 à 2 Md€ de prêts garantis sur 2028-2034 ; voir P11(5) | Environ 8 à 40 M€ de pertes attendues du garant, jusqu'à environ 80 M€ en scénario sévère, avant commissions et partage de l'*upside* |

**Mise en regard.** Les bénéfices sont surtout non monétaires : sécurité juridique, données, obstacle IRB levé, garde-fous. Les effets en capital du socle sont neutres au lancement (H.1). Les coûts de conformité, de l'ordre de 5 à 30 M€ au total une fois, sont concentrés sur le reporting. Ce dernier est justifié indépendamment du compartiment, puisqu'il comble l'angle mort statistique documenté.

---

## Sources ajoutées par ce document (au-delà des cinq rapports de cadrage)

**Version initiale**
- [Directive (UE) 2019/1023 — EUR-Lex (art. 33, clause de réexamen)](https://eur-lex.europa.eu/eli/dir/2019/1023/oj/eng)
- [Freshfields — EU Inc.: the insolvency provisions of the Commission's draft 28th regime proposal](https://www.freshfields.com/en/our-thinking/blogs/transactions/eu-inc-the-insolvency-provisions-of-the-commissions-draft-28th-regime-proposal-102mq7y)
- [Commission européenne — proposition EU Inc, COM(2026) 321](https://commission.europa.eu/document/download/3e9822aa-8cef-40a1-904e-a53fc68e7265_en)
- [Commission européenne — Questions and answers on legislative programmes under the CRR (29 octobre 2025)](https://finance.ec.europa.eu/news/questions-and-answers-legislative-programmes-under-capital-requirements-regulation-2025-10-29_en)
- [Commission européenne — communication C(2025) 7231](https://ec.europa.eu/finance/docs/law/251029-communication-crr-legislative-programmes_en.pdf)
- [§ 39 InsO — gesetze-im-internet.de](https://www.gesetze-im-internet.de/inso/__39.html)
- [CMS — BGH urteilt zur Beschränkung des Kleinbeteiligtenprivilegs (IX ZR 85/21)](https://cms.law/de/deu/legal-updates/bgh-urteilt-zur-beschraenkung-des-kleinbeteiligtenprivilegs)
- [EBA — Guidelines on loan origination and monitoring (EBA/GL/2020/06)](https://www.eba.europa.eu/activities/single-rulebook/regulatory-activities/credit-risk/guidelines-loan-origination-and-monitoring)

**Révision (round 2)**
- [Art. 47b CRR (texte consolidé) — judict.eu](https://judict.eu/en/hla/32013R0575-X/article-47B)
- [Art. 123 CRR (texte consolidé) — judict.eu](https://judict.eu/en/hla/32013R0575-X/article-123)
- [Art. 150 CRR (texte consolidé) — judict.eu](https://judict.eu/en/hla/32013R0575-X/article-150)
- [Directive (UE) 2019/1023 — EUR-Lex (échéance de l'art. 33 ; aucune publication du rapport identifiée)](https://eur-lex.europa.eu/eli/dir/2019/1023/oj/eng) ; [synthèse EUR-Lex](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=LEGISSUM%3A4406088)
- [William Fry — ESMA Publishes Signed AIFMD Co-operation Agreements](https://www.williamfry.com/knowledge/esma-publishes-signed-aifmd-co-operation-agreements/) ; [ESMA — International Cooperation](https://www.esma.europa.eu/about-esma/international-cooperation)
- Sources vérifiées par l'auditeur au round 1 et reprises ici (art. 133, 234 et 91 CRR ; règlement 2017/2402 ; Q&A EBA 2014_786 et 2018_3806 ; trilogue titrisation ; règlement délégué 2025/1496 ; produit FEI I&D non plafonné ; FEC) : voir `impact-debate.md`, fin du round 1.
