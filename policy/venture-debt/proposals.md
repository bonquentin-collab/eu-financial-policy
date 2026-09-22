# Propositions — Compartiment prudentiel bancaire dédié à la « venture debt » dans le cadre CRR/CRD

**Agent :** `policy-innovator` — dossier `policy/venture-debt/`
**Mode :** jeu initial de propositions (avant les tours `impact-assessment-auditor` et `stakeholder-mapper`)
**Date :** 22 septembre 2026
**Entrées lues intégralement :** `current-regulation.md`, `micro-analysis.md`, `macro-analysis.md`, `benchmarking.md`, `stakeholder-map.md` (tous dans `policy/venture-debt/`).
**Statut :** propositions de politique publique argumentées. Ce document ne contient **aucune rédaction législative**. Les références d'articles et les paramètres chiffrés servent à rendre les propositions opérationnelles. Ils restent indicatifs et devront être repris par `legal-drafter` si cette étape est déclenchée.

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

**Thèse de ce document : un compartiment « incrémental par la méthode, sui generis par la définition ».** Concrètement :

1. **Ce qui reste dans l'architecture existante.** Le compartiment réutilise, sans rien inventer de disjoint :
   - la classe d'exposition « entreprises » ;
   - l'architecture à deux étages que CRR3 a créée pour le *specialised lending*, avec un volet standard (art. 122a) et un volet IRB en *slotting* (art. 153(5)) ;
   - la gouvernance du *slotting* : catégories supervisées et critères fixés par RTS de l'EBA (art. 153(9)) ;
   - la technique du facteur de soutien appliqué en aval du calcul des actifs pondérés (art. 501a) ;
   - le traitement des programmes publics (art. 133(5)) ;
   - les orientations EBA existantes sur l'octroi de prêts.
2. **Ce qui doit être nouveau, et qu'il serait malhonnête de masquer.** Il faut une **définition autonome** fondée sur la source de remboursement, avec des critères de qualification et de *slotting* **conçus pour la venture debt**. Cela suppose une **modification de niveau 1 par codécision** : l'art. 147 est limitatif et un RTS ne peut pas créer de catégorie (`current-regulation.md` §2.5 ; `stakeholder-map.md`, synthèse n° 1).
3. **Ce que cela n'est pas.** Ce n'est pas, au sens strict, une sixième sous-catégorie de *specialised lending*. C'est une **sous-catégorie sui generis de la classe « entreprises »**. Elle emprunte au *specialised lending* sa logique et sa gouvernance, mais pas son étiquette juridique ni son triple test.

**Pourquoi ne pas coller l'étiquette « specialised lending » :**
- **(i) Contamination.** Réécrire le triple test de l'art. 147(8) pour y faire entrer la venture debt affaiblirait la définition pour toutes les autres sous-catégories (`current-regulation.md` §2.2).
- **(ii) Sortie automatique des lignes directrices BCE.** Les lignes directrices BCE sur les opérations à effet de levier (2017) excluent le *specialised lending*. Une étiquette « SL » ferait sortir mécaniquement la venture debt de leur champ, ce que le garde-fou n° 4 de `macro-analysis.md` §6 interdit. Une catégorie sui generis évite cette sortie par construction.
- **(iii) Chantier de la Commission.** La communication COM(2026) 615 rattache explicitement le *specialised lending* aux « investissements stratégiques » et au financement de projets (`macro-analysis.md` §4.5). Rester hors de l'étiquette évite d'entrer en collision avec ce chantier, tout en permettant de voyager dans le même paquet législatif.
- **(iv) Agenda déjà engagé.** L'agenda de l'EBF sur le *specialised lending* (planchers de LGD, collatéral, output floor) est déjà occupé et ne mentionne pas la venture debt (`stakeholder-map.md` §1.2). Une catégorie distincte évite d'hériter de ces revendications.

### 0.2 Cinq principes de conception tirés du cadrage

| # | Principe | Ancrage |
|---|---|---|
| 1 | **Sensibilité au risque plutôt que subvention.** L'allègement en capital d'un compartiment de type *slotting* est de l'ordre de 5 à 100 pb/an. C'est un ordre de grandeur de moins que les rendements (7-13 %) et que la variation cyclique des pertes (200-350 pb). Aucune source ne montre que le traitement prudentiel explique l'écart transatlantique. | `macro-analysis.md` §4.4, §5.1 ; `micro-analysis.md` §5.2 |
| 2 | **Deux paliers, pas une grille unique.** Les pertes nettes (NCO, pertes nettes des recouvrements) sont de 9,6-9,7 % en *early stage* contre 1,3-1,5 % en *growth stage* (First Citizens, 2023-2024). | `micro-analysis.md` §0 point 3, §3.2, §8.1(3) |
| 3 | **Deux étages, standard et IRB, indissociables.** Sans pondération standard dédiée, l'output floor neutralise tout allègement IRB. | `current-regulation.md` §3.4 ; `micro-analysis.md` §8.1(4) ; `macro-analysis.md` §4.3 |
| 4 | **Un paquet, pas un pari sur le seul pilier 1.** Le précédent étranger le plus directement transposable est une guidance de pilier 2 (OCC 2023-34, puis 2025-45). Les contraintes effectives sont l'expertise, la culture du risque, la fragmentation et la profondeur de l'equity. | `benchmarking.md` §2.3, §6 ; `macro-analysis.md` §5.2 |
| 5 | **Les conditions de neutralité macroprudentielle sont des contraintes de conception, pas des options.** | `macro-analysis.md` §6 (voir 0.3) |

### 0.3 Les sept garde-fous macroprudentiels et leur traduction obligatoire

`macro-analysis.md` §6 énonce sept conditions minimales pour qu'un compartiment ne dégrade pas la stabilité financière. Elles sont traitées ici comme **obligatoires** :

| Garde-fou (`macro-analysis.md` §6) | Traduction dans ce jeu de propositions |
|---|---|
| 1. Neutralité de calibrage : aucune pondération standard sous 100 % sans série de pertes européenne validée par l'EBA | **P2** : 130 % en *early stage*, 100 % en *growth* au lancement. **P4** : tout élément inférieur à 100 % reste **dormant** jusqu'à la validation des données par l'EBA. |
| 2. Plafond de concentration, sur le modèle de l'art. 133(5) (10 % des fonds propres) | **P9** : les éléments préférentiels sont plafonnés à 10 % des fonds propres, avec une présomption de revue de pilier 2 au-delà de 5 %. |
| 3. Volet liquidité obligatoire (concentration des dépôts de l'écosystème VC) | **P9** : suivi des dépôts de l'écosystème VC dans les outils ALMM et l'ILAAP, et clarification sur les dépôts « opérationnels ». |
| 4. Pas de sortie automatique des lignes directrices BCE sur l'effet de levier | **§0.1(ii)** : catégorie sui generis hors *specialised lending*. **P8** : **substitution conditionnelle**, et non sortie. |
| 5. Composante contracyclique (sSyRB activable, ou calibrage à travers le cycle) | **P5** : hystérésis et facteur systémique traité au niveau du portefeuille. **P9** : sous-ensemble sSyRB préidentifié. |
| 6. Clause de revoyure et extinction faute d'effet d'offre | **P10** : rapports EBA à 3 et 5 ans, avec extinction des éléments préférentiels. |
| 7. Priorité aux canaux budgétés et plafonnés | **P11** : fenêtre InvestEU dédiée, qui porte le levier de capital principal. |

### 0.4 Glossaire minimal (pour le lecteur non spécialiste)

- **RWA / pondération (RW)** : montant d'exposition « pondéré » par le risque. Les fonds propres minimaux sont égaux à 8 % des RWA, plus les coussins. Une pondération de 100 % signifie que 1 € prêté consomme 8 centimes de fonds propres minimaux.
- **Approche standard (SA)** : pondérations forfaitaires fixées par le règlement.
- **Approche IRB** : la banque estime elle-même les paramètres de risque, sous agrément de son superviseur :
  - **PD** : probabilité de défaut ;
  - **LGD** : perte en cas de défaut ;
  - la variante « fondation » (F-IRB) utilise des LGD réglementaires.
- **Slotting** : méthode IRB simplifiée. L'exposition est classée dans une catégorie qualitative (solide, bon, satisfaisant, faible, défaut) à pondération fixe. Elle est conçue pour les actifs où l'historique de défauts est trop mince pour estimer une PD.
- **Output floor** : plancher. Les RWA calculés en IRB ne peuvent descendre sous 72,5 % (à partir de 2030) des RWA calculés en approche standard.
- **Facteur de soutien (supporting factor)** : coefficient réducteur appliqué **après** le calcul des RWA. Il vaut 0,7619 ou 0,85 pour les PME (art. 501) et 0,75 pour les infrastructures (art. 501a).
- **Runway** : nombre de mois de trésorerie avant épuisement.
- **LTER** : montant du prêt rapporté au cash d'equity effectivement levé sur 24 mois (`micro-analysis.md` §7).
- **Warrant / equity kicker** : bon de souscription d'actions reçu par le prêteur en complément des intérêts.
- **Test SPPI (IFRS 9)** : test comptable qui détermine si un prêt peut être comptabilisé au coût amorti. S'il échoue, le prêt passe en juste valeur par résultat.

### 0.5 Sommaire des propositions

| # | Titre | Instrument / niveau | Cadres connectés principaux | Phase |
|---|---|---|---|---|
| **A. Le compartiment de pilier 1** |||||
| P1 | Définition sui generis « exposition de venture debt qualifiée » (VDQ), à deux paliers | Niveau 1 (CRR, art. 147) | AIFMD, EuVECA, ELTIF, InvestEU (définition des investisseurs qualifiés) | 1 |
| P2 | Volet standard : nouvel article calqué sur l'art. 122a (130 % / 100 %) | Niveau 1 (CRR) | Art. 122a, 128, 501, 465 CRR | 1 |
| P3 | Volet IRB : *slotting* dédié, corrélation de type HVCRE, LGD par palier | Niveau 1 + RTS EBA | Art. 153(5), 153(9) CRR ; règlement délégué (UE) 2021/598 ; EBA/CP/2026/09 ; Bâle CRE33 | 1 |
| P4 | Clause d'activation sur données : facteur de type 501a et catégories dormantes. Comparaison des options | Niveau 1 + acte délégué conditionnel | Art. 501, 501a, 461a CRR | 1 puis 2 |
| **B. Covenants, séniorité, tranches** |||||
| P5 | Covenants : reconnaissance comme outils de contrôle et neutralisation de leurs effets procycliques | RTS + orientations / Q&A EBA | Art. 178 CRR ; EBA/GL/2016/07 ; EBA/GL/2018/06 | 0 puis 1 |
| P6 | Séniorité et tranches : banque en senior, fonds en junior ; frontière avec la titrisation | Niveau 1 (CRR, règlement titrisation) + RTS | Art. 128, 161, 194 CRR ; règlement (UE) 2017/2402, art. 2(1) ; AIFMD II | 1 |
| **C. Warrants** |||||
| P7 | Warrants et equity kickers : qualification, 250 % au lieu de 400 %, programmes publics, conversion dette-actions | Niveau 1 + Q&A | Art. 133, 495a, 36, 44-46, 89-91 CRR ; C(2025) 7231 ; IFRS 9 ; directives 2019/1023 et 2026/799 | 0 puis 1 |
| **D. Pilier 2 et garde-fous** |||||
| P8 | Pilier 2 : section « venture debt » dans EBA/GL/2020/06 (adaptation de l'OCC 2025-45) et substitution de la guidance BCE sur l'effet de levier | Orientations EBA, guidance BCE | CRD art. 74, 79 ; EBA/GL/2020/06 ; EBA/GL/2022/03 | 0 |
| P9 | Concentration, liquidité, coussin sectoriel, résolution | Niveau 1 (plafond) + pilier 2 + orientations | Art. 133(5) CRR ; CRD art. 104, 105, 133 ; règlement délégué (UE) 2015/61 ; EBA/GL/2020/13 ; BRRD art. 10 | 1 |
| P10 | Données, calibrage, revoyure et extinction | ITS de reporting + niveau 1 (clause de revoyure) | Art. 430 CRR ; AnaCredit / IReF ; groupe BEI | 0 puis 1 |
| **E. Partage des risques** |||||
| P11 | Fenêtre InvestEU « VDQ » et articulation avec l'art. 133(5), le GBER et TechEU | Budgétaire (InvestEU), sans niveau 1 CRR | Règlement (UE) 2021/523 ; art. 117(2), 213-215 CRR ; GBER art. 21 | 0 |
| **F. Insolvabilité** |||||
| P12 | Rang des créances : trajectoire graduée en trois niveaux, sur le modèle ciblé de la directive (UE) 2017/2399 | Niveau 1 insolvabilité (volet séparé) | Directives 2019/1023 (art. 9, 11, 33), 2026/799, 2017/2399 (BRRD art. 108) ; EU Inc COM(2026) 321 | 0 (niveau 1 de la trajectoire), puis volet autonome |
| **G. Cohérence et séquençage** |||||
| P13 | Cohérence bâloise, véhicule législatif, séquençage, positionnement vis-à-vis de COM(2026) 615 | Stratégie | COM(2026) 615 ; Bâle / RCAP ; SIU | Transversal |

**Phases :**
- **Phase 0 (2026-2027)** : mesures sans modification du niveau 1 (orientations, Q&A, reporting ad hoc, produit InvestEU).
- **Phase 1** : paquet législatif du T1 2027 issu de COM(2026) 615. Adoption vers 2028, application vers 2029-2030, en même temps que la montée de l'output floor à 70-72,5 %.
- **Phase 2 (2031 et après)** : décision d'activation sur données (P4).

### 0.6 Conventions de fiabilité

Les constats repris des cinq rapports conservent leur qualification d'origine (documenté, calculé ou inféré). Quatre éléments **ajoutés par ce document** ont été vérifiés par recherche au moment de la rédaction et sont signalés **[vérifié]** (sources en fin de document) :
- l'art. 33 de la directive 2019/1023 ;
- le chapitre insolvabilité de la proposition EU Inc ;
- les critères de la communication C(2025) 7231 ;
- le § 39 InsO et l'arrêt BGH IX ZR 85/21.

Les éléments non vérifiés sont signalés **[à vérifier]**. Les calculs d'effet en capital reprennent la formule de `macro-analysis.md` §4.4 : coût annuel ≈ pondération × 1,04 %, soit environ 1 pb par point de pondération. Ce sont des ordres de grandeur.

---

## A. Le compartiment de pilier 1

### P1 — Définition sui generis de l'« exposition de venture debt qualifiée » (VDQ), à deux paliers

**Résumé exécutif.** Créer, dans la classe « entreprises », une sous-catégorie définie par la **source de remboursement**. Elle s'appuie sur des critères d'éligibilité vérifiables, qui renvoient à des définitions existantes du droit de l'Union (AIFMD, EuVECA, ELTIF, InvestEU). Elle est scindée en deux paliers :
- **VDQ-P** (stade précoce, revenus des 12 derniers mois < 5 M€) ;
- **VDQ-C** (croissance, revenus récurrents ≥ 5 M€).

Elle exclut explicitement les financements adossés à des actifs, qui relèvent déjà de l'*object finance*, du *project finance* ou de la titrisation. C'est la brique sur laquelle reposent toutes les autres propositions.

**Problème et ancrage factuel.**
- **Le triple test échoue.** Le critère n° 1 (SPV à actif physique) et le critère n° 3 (remboursement par les revenus de l'actif) échouent presque toujours ; le critère n° 2 (contrôle) échoue au sens du SL (`current-regulation.md` §2.2 ; `macro-analysis.md` §4.2 ; `benchmarking.md` §5).
- **Le remboursement se fait par l'événement de liquidité.** Le taux de remboursement trimestriel bondit à 25 % au trimestre d'un événement ; seuls environ 11 % des prêts arrivent à maturité (`micro-analysis.md` §2.1).
- **Quatre familles sont mélangées dans les statistiques** : (a) *runway*, (b) *growth*, (c) financements adossés à des actifs d'entreprises VC (GPU, data centres, lignes *warehouse*), (d) quasi-equity publique. La famille (c) biaise les données de calibrage et ouvre un arbitrage (`micro-analysis.md` §1.1, §1.2, §6 friction n° 12). Exemples : Mistral AI, 830 M$ pour 13 800 GPU ; Nscale, 790 M$.
- **Le profil est bimodal par stade** (`micro-analysis.md` §3.2), avec une frontière opérationnelle déjà utilisée par SVB/First Citizens autour de 5 M$ de revenus (§8.1(3)).
- **Arbitrage de classe « clientèle de détail ».** Sous 1 M€, une exposition PME peut être classée en clientèle de détail à 75 % (`micro-analysis.md` §5.1 et §6 friction n° 3), soit environ 57 % après facteur PME. C'est une porte d'arbitrage pour les petits tickets *early stage*, alors que la médiane européenne est de 1,7 M€ (`macro-analysis.md` §2.2).

**Mécanisme.**
1. **Emplacement.** Un nouveau paragraphe de l'art. 147 CRR (numérotation à arrêter, par exemple 147(8a)) crée, **dans la classe « entreprises » mais hors *specialised lending***, la sous-catégorie VDQ. Elle est répliquée dans la classe « entreprises » de l'approche standard par un nouvel article sur le modèle de l'art. 122a (voir P2).
2. **Définition (critères cumulatifs).** Est une VDQ une exposition sur une entreprise (hors établissements, entreprises d'assurance et entreprises d'investissement) qui remplit les conditions suivantes :
   - **(a) Source de remboursement.** Le dossier de crédit identifie à l'octroi, comme source principale de remboursement, un financement futur en fonds propres, une cession ou une introduction en bourse. **Ou bien** l'emprunteur a un EBITDA négatif sur les 12 derniers mois. C'est la formule de `micro-analysis.md` §8.1(1), qui s'inspire de la classe « investor dependent » de SVB.
   - **(b) Soutien d'un investisseur professionnel qualifié.** Au moins un tour de fonds propres a été réalisé dans les 18 mois précédant l'octroi, mené ou co-mené par un investisseur défini **par renvoi** :
     - (i) un FIA géré par un gestionnaire agréé au titre de l'art. 6 AIFMD ;
     - (ii) un fonds EuVECA (règlement (UE) n° 345/2013) ;
     - (iii) un ELTIF (règlement (UE) 2015/760 modifié par 2023/606) ;
     - (iv) le groupe BEI (dont le Fonds EIC et le FEI), ou une banque ou institution nationale de développement au sens du droit budgétaire de l'Union (partenaires chargés de la mise en œuvre d'InvestEU) ;
     - (v) un fonds de pays tiers géré par un gestionnaire supervisé dans une juridiction couverte par un accord de coopération au titre de l'art. 42 AIFMD.

     Le point (v) est indispensable : plus de 4 opérations de scale-up sur 5 dans l'UE ont un chef de file étranger (`macro-analysis.md` §1.1).
   - **(c) Plafond de levier sur l'equity.** LTER ≤ 50 % (`micro-analysis.md` §8.1(2), fourchette de 35-50 % ; la médiane de marché est à 14-18 % du financement cumulé, §2.1).
   - **(d) Rang.** L'exposition doit être senior, avec une sûreté de premier rang sur l'ensemble des actifs, y compris la PI, **ou** un *negative pledge* sur la PI. Un *split-lien* avec un prêteur ABL/RCF est admis sous accord inter-créanciers. Toute dette junior ou subordonnée est exclue et reste à l'art. 128 (voir P6).
   - **(e) Covenants minimaux.** Un covenant de trésorerie minimale et un reporting financier mensuel (voir P5).
   - **(f) Kicker détachable.** Toute participation au capital accordée au prêteur doit prendre la forme d'un instrument **détachable**. Le remboursement du principal et des intérêts ne doit pas être indexé sur la valeur des titres. C'est la condition pour que le prêt passe le test SPPI et reste au coût amorti (`micro-analysis.md` §2.4). Elle est inspirée du 12 CFR 7.1006 américain, adapté (voir P7).
   - **(g) Maturité contractuelle ≤ 6 ans.** Les maturités usuelles sont de 3 à 5 ans ; la BEI pratique le *bullet* à 5-6 ans par tranche (`micro-analysis.md` §2.1).
3. **Exclusions explicites (anti-arbitrage) :**
   - les expositions qui remplissent l'art. 147(8) (PF, OF, CF, IPRE) ;
   - les expositions ADC ;
   - les positions de titrisation ;
   - les créances achetées ;
   - **tout financement dont la source principale de remboursement est le revenu ou la valeur d'actifs spécifiquement financés** (GPU, data centres, flottes, *warehouses* de créances), c'est-à-dire la famille (c) ;
   - les formes subordonnées ou convertibles de quasi-equity (famille (d)).

   Un mandat EBA (orientations) précisera la frontière entre VDQ, OF/PF et titrisation, selon la **source effective** de remboursement.
4. **Paliers.** VDQ-P si les revenus des 12 derniers mois sont inférieurs à 5 M€ ; VDQ-C au-delà. La migration de P vers C intervient après deux trimestres consécutifs au-dessus du seuil.
5. **Sortie par le haut.** Un EBITDA positif sur quatre trimestres consécutifs, avec un flux d'exploitation suffisant pour assurer le service de la dette, fait sortir l'exposition vers le « corporate » générique à la revue suivante.
6. **Primauté sur la clientèle de détail.** Une exposition qui remplit la définition VDQ ne peut pas être classée en clientèle de détail (art. 123 et art. 147(5)).
7. **Clause d'antériorité.** Les expositions octroyées avant la date d'application conservent leur traitement jusqu'à échéance. La demi-vie étant d'environ 2 ans (`micro-analysis.md` §2.1), l'extinction du stock est rapide.

**Cadres connectés et synergies.**
- **AIFMD (art. 6 et 42), EuVECA, ELTIF, InvestEU.** Le critère (b) **réutilise** des statuts réglementaires existants au lieu de créer un label « investisseur VC qualifié » ad hoc. La qualité de sponsor est ainsi adossée à un contrôle de marché déjà exercé par les autorités nationales et l'ESMA.
- **Lignes directrices BCE (2017).** La catégorie étant hors *specialised lending*, elle ne bénéficie pas de l'exclusion automatique prévue pour le SL. Le garde-fou n° 4 est respecté par construction (voir P8).
- **EU Inc (COM(2026) 321).** La proposition définit une « start-up innovante » [vérifié] : dépenses de R&D ≥ 10 % des coûts d'exploitation ou ≥ 5 % du chiffre d'affaires, moins de 100 salariés, chiffre d'affaires ≤ 10 M€, moins de 10 ans d'existence. Cette définition **ne doit pas** remplacer la frontière des paliers, qui est une frontière de **risque** alors que celle d'EU Inc est une frontière de **politique**. Elle est cependant largement compatible avec le palier VDQ-P, ce qui ouvre une synergie en matière d'insolvabilité (P12).

**Bénéfices attendus.**
- **Micro :** fin de l'incertitude de classement ; base juridique commune au standard, à l'IRB, au pilier 2, à InvestEU et à l'insolvabilité ; suppression de l'arbitrage par la classe « clientèle de détail ».
- **Macro :** périmètre étanche, donc données de calibrage propres (`micro-analysis.md` §1.2) ; création d'une ligne de reporting identifiable, ce qui est un « gain net pour la surveillance macroprudentielle » quelle que soit la pondération (`macro-analysis.md` §2.6).

**Risques et limites.**
- (i) La frontière de 5 M€ de revenus est un seuil binaire, mais elle se manipule moins facilement qu'un ratio.
- (ii) Le critère (a) « EBITDA négatif » pourrait capter des entreprises non financées par du VC ; le critère (b) filtre ce cas.
- (iii) Toute définition propre à l'UE est une divergence vis-à-vis de Bâle, traitée en P13.
- (iv) L'articulation de la nouvelle sous-classe avec les classes d'exposition de l'approche standard post-CRR3 est à vérifier par `current-regulation-analyst` [à vérifier].

---

### P2 — Volet approche standard : un nouvel article calqué sur l'art. 122a

**Résumé exécutif.** Créer en approche standard trois pondérations dédiées, en reprenant exactement la **grammaire du *project finance* de l'art. 122a** (130 % en phase pré-opérationnelle, 100 % en phase opérationnelle, 80 % en haute qualité) :
- **VDQ-P = 130 %** : le « pré-revenus » joue le rôle du « pré-opérationnel » ;
- **VDQ-C = 100 %** ;
- **VDQ-C haute qualité = 80 %**, **dormante** au lancement (voir P4).

Pour VDQ-P, le facteur PME de l'art. 501 n'est **pas cumulable**. Pour VDQ-C, il reste cumulable, afin de ne pas dégrader le statu quo.

**Problème et ancrage factuel.**
- **L'approche standard ne distingue pas les stades.** Une start-up non notée reçoit 100 %, soit 76 à 85 % avec le facteur PME. Le capital de pilier 1 d'une exposition *early stage* ressort à environ 6,1 % (8 % × 76 %), alors que les pertes nettes ont atteint 9,6 à 9,7 % en une seule année de stress (`micro-analysis.md` §5.1). Le *growth stage* (1,3 à 1,5 %) est confortablement couvert.
- **Il en résulte une sélection adverse vers l'*early stage* en approche standard** : à capital égal, le spread y est plus élevé (`micro-analysis.md` §5.1). Ce schéma rejoint l'observation macro selon laquelle « le crédit se développe au moment où le soutien des investisseurs en fonds propres s'affaiblit » (`macro-analysis.md` §2.3).
- **Sans volet standard, l'IRB est neutralisé par l'output floor** (`current-regulation.md` §3.4 ; `macro-analysis.md` §4.3).
- **Garde-fou n° 1** : aucune pondération standard sous 100 % sans données validées (`macro-analysis.md` §6).

**Mécanisme.**
1. **Nouvel article** (par exemple 122b, numérotation à arrêter), placé à la suite de l'art. 122a :

   | Sous-catégorie | Pondération | Analogue existant | Justification |
   |---|---|---|---|
   | VDQ-P | **130 %** | PF pré-opérationnel, art. 122a (130 %) | Le capital minimal vaut 10,4 % de l'exposition, au-dessus de la perte d'une année de stress (9,7 %) : le test de suffisance de `micro-analysis.md` §5.1 est franchi. L'exposition senior (130 %) reste sous la dette subordonnée (art. 128 : 150 %). |
   | VDQ-C | **100 %** | PF opérationnel (100 %) ; corporate non noté (100 %) | Statu quo, conforme au garde-fou n° 1. Pertes observées de 1,3 à 1,5 %, couvertes. |
   | VDQ-C « haute qualité » | **80 %** — **dormant** | PF opérationnel haute qualité (80 %) | Activable seulement selon P4. Critères indicatifs : dette / ARR ≤ 0,5x, runway ≥ 24 mois sans nouveau tour, rétention nette ≥ 100 %, sponsors de premier rang. |

2. **Alternative plus sévère pour VDQ-P : 150 %**, sur le modèle de l'ADC (art. 122a), équivalent européen de la HVCRE (`current-regulation.md` §2.3). Elle est défendable : un remboursement qui dépend d'une vente ou d'un refinancement futur est la raison d'être de la HVCRE (`micro-analysis.md` §8.2). Ce document retient toutefois **130 %**. Le prêt senior de venture debt est court (demi-vie d'environ 2 ans) et il est remboursé à environ 100 % lors des événements de liquidité (`micro-analysis.md` §0 point 2), ce qui le distingue d'un financement de construction. Le paramètre reste à trancher par l'`impact-assessment-auditor`.
3. **Articulation avec l'art. 501 (facteur PME) :**
   - **VDQ-P : pas de cumul.** Avec le facteur, 130 % × 0,7619 donnerait environ 99 %, soit 7,9 % de capital, sous les 9,7 %. Le test de suffisance échouerait et la mesure perdrait sa cohérence. Il faut une modification ciblée de l'art. 501(2).
   - **VDQ-C : cumul maintenu.** Une scale-up dont le chiffre d'affaires est inférieur ou égal à 50 M€ reste à 76-85 %, comme aujourd'hui. Le compartiment n'aggrave pas le traitement du palier C.
4. **Mise en œuvre progressive pour VDQ-P** : 100 % la première année, 115 % la deuxième, 130 % à partir de la troisième. Ce calendrier est cohérent avec la montée de l'output floor (60 % en 2027, puis 72,5 % en 2030 ; `current-regulation.md` §1.2).
5. **Output floor.** Ces pondérations deviennent la base du plancher : 72,5 % × 130 % ≈ 94 % pour VDQ-P, et 72,5 % pour VDQ-C.

**Cadres connectés.** Art. 122a (gabarit), art. 128 (cohérence senior/junior), art. 501 (modification ciblée), art. 465 (plancher).

**Bénéfices attendus.**
- **Micro.** Pour une banque en approche standard :
  - VDQ-P passe de 76 % à 130 %, soit un surcoût d'environ **+56 pb/an** (de 79 à 135 pb) ;
  - VDQ-C est neutre ;
  - la sélection adverse vers l'*early stage* disparaît ;
  - pour une banque contrainte par le plancher, le plancher de VDQ-P devient cohérent avec son risque.
- **Macro.** La mesure est stabilisatrice : elle renchérit le segment le plus procyclique (`macro-analysis.md` §2.3) sans toucher au segment le moins risqué. Les volumes concernés sont faibles et la part bancaire est inconnue (`macro-analysis.md` §1.4).

**Risques et limites.**
- **(i) Un durcissement pour VDQ-P.** Il faut le dire clairement : le compartiment n'est pas une subvention. Il rééquilibre. Opposition attendue :
  - de l'écosystème start-up (`stakeholder-map.md` §3.2) ;
  - des banques spécialisées (§1.1) ;
  - de l'EBF (§1.2).
  L'effet est compensé de manière ciblée et budgétée par P11 : avec une garantie FEI de 70 %, la pondération effective tombe à environ 39 %.
- **(ii) Un possible report de l'*early stage* vers les fonds et la BEI.** Ce n'est pas un effet négatif du point de vue de la stabilité : ces acteurs n'ont pas de canal de ruée sur les dépôts (`macro-analysis.md` §2.5).
- **(iii) Des paramètres fixés en l'absence de données européennes** (P10).

---

### P3 — Volet IRB : *slotting* dédié, corrélation de type HVCRE, LGD par palier

**Résumé exécutif.** Ouvrir aux banques IRB un *slotting* propre à la venture debt, avec deux grilles :
- **VDQ-C : 90 / 115 / 250 %** ;
- **VDQ-P : 120 / 140 / 250 %**, reprenant les poids HVCRE de Bâle.

Trois règles encadrent ces grilles :
- aucune pondération préférentielle pour maturité courte ;
- la catégorie « solide » reste **dormante** au lancement ;
- les critères sont définis par un RTS de l'EBA qui **réutilise la structure** du règlement délégué (UE) 2021/598 tel que modifié à l'issue d'EBA/CP/2026/09.

Les banques qui savent estimer une PD gardent cette possibilité, avec pour VDQ-P une **corrélation de type HVCRE** et une LGD F-IRB de 50 %.

**Problème et ancrage factuel.**
- **Obstacle des données.** Un portefeuille de quelques centaines de prêts, qui migre beaucoup et fait défaut rarement, est « difficile à valider » comme modèle de PD. C'est « l'argument le plus solide en faveur d'un *slotting* » (`micro-analysis.md` §5.2 ; `current-regulation.md` §2.4, §3.3).
- **Les banques IRB sont désavantagées.** Un modèle PD donne des pondérations de 100 à 130 % en *growth* et de 170 à 240 % en *early stage*, soit **deux à trois fois plus qu'une banque en approche standard** (`micro-analysis.md` §5.2).
- **Les facteurs du *slotting* PF ne se transposent pas tels quels.** Deux se transposent bien (sponsor ; sûretés et contrôle), deux sont à redéfinir (solidité financière ; caractéristiques de la transaction), un se transpose partiellement (environnement juridique), et **quatre dimensions manquent** : dépendance au refinancement, cycle VC, concentration par sponsor, qualité de l'équipe (`micro-analysis.md` §7).
- **Les pondérations de 50 et 70 % pour une maturité inférieure à 2,5 ans sont inadaptées**, puisque la maturité effective est d'environ 2 ans (`micro-analysis.md` §6 friction n° 11).
- **L'analogue bâlois pertinent est la HVCRE** (95/120/140/250 %, corrélation de 12 à 30 %). Elle est **plus pénalisante**, pas plus favorable (`micro-analysis.md` §8.2 ; `macro-analysis.md` §2.2(3)).
- **Risque de compression.** Un *slotting* à 70-115 % comprimerait la différenciation et attirerait les risques les plus élevés chez les banques IRB non contraintes par le plancher (`macro-analysis.md` §4.3(3)).

**Mécanisme.**
1. **Tableaux de *slotting* dédiés** (nouveau paragraphe de l'art. 153, par exemple 153(5a)). La colonne unique vaut quelle que soit la maturité résiduelle :

   | Palier | Cat. 1 « solide » | Cat. 2 « bon » | Cat. 3 « satisfaisant » | Cat. 4 « faible » | Cat. 5 « défaut » |
   |---|---|---|---|---|---|
   | VDQ-C | *70 % — dormante (P4)* | **90 %** | **115 %** | **250 %** | 0 % (perte attendue, art. 158) |
   | VDQ-P | *95 % — dormante (P4)* | **120 %** | **140 %** | **250 %** | 0 % (perte attendue, art. 158) |

   Ancrage du calibrage (`micro-analysis.md` §8.2) :
   - pour le *growth stage*, la catégorie « naturelle » est « satisfaisant », et le meilleur quart relève de « bon » ;
   - pour l'*early stage*, la tendance est « faible », et « satisfaisant » ne vaut que pour les meilleurs profils.
2. **Perte attendue (EL).** Les valeurs de l'art. 158(6) s'appliquent : 0,4 / 0,8 / 2,8 / 8 / 50 %. L'EBA devra toutefois vérifier si l'EL de 8 % en catégorie « faible » suffit pour VDQ-P, puisque la perte de stress (9,7 %) la dépasse (`micro-analysis.md` §8.2). Cela pourrait justifier une EL « faible » spécifique plus élevée.
3. **Approche PD maintenue, mais encadrée :**
   - pour VDQ-P, application de la **fonction de corrélation HVCRE de Bâle** (de 12 à 30 %, au lieu de 12 à 24 %) ;
   - **pas d'ajustement de taille PME** (art. 153(4)) pour VDQ-P : cet ajustement, qui réduit la corrélation des petites entreprises, contredit l'existence d'un facteur systémique commun, le cycle VC. Il produit le « paradoxe » relevé par `micro-analysis.md` §5.2 : une formule plus clémente pour les emprunteurs les plus petits et les plus risqués ;
   - **LGD F-IRB senior** : 40 % pour VDQ-C et **50 % pour VDQ-P**. Le proxy de marché est une juste valeur rapportée au coût d'environ 48 % sur les prêts en difficulté d'Horizon (`micro-analysis.md` §3.2, §4.3). La valeur de 40 % est jugée « probablement optimiste pour l'*early stage* ».
4. **Mandat RTS** (extension de l'art. 153(9)). L'EBA précise les facteurs et leur pondération indicative, en **réutilisant la structure** du règlement délégué (UE) 2021/598 modifié. Trois apports de la consultation CP/2026/09 sont repris : le sous-facteur « position dans la cascade de pertes », la suppression possible du plancher de 5 % pour un facteur non discriminant, et la catégorie 4 par défaut en cas de données manquantes.

   | Facteur (réécrit) | Contenu (d'après `micro-analysis.md` §7 et §8.5) | Poids indicatif |
   |---|---|---|
   | Solidité financière | Runway sans nouveau tour ; LTER ; pour le palier C, dette / ARR, marge brute, rétention nette, *burn multiple* ; stress de 12 à 18 mois sans tour | 25-35 % |
   | Solidité du sponsor | Qualité des chefs de file, réserves allouées, âge du fonds, largeur du syndicat, historique de soutien, co-investisseurs publics | 25-35 % |
   | Sûretés et contrôle | Premier rang y compris sur la PI, contrôle des comptes, *negative pledge*, covenants (P5), position dans la cascade (P6) | 15-25 % |
   | Transaction et technologie | Stade (TRL, phase clinique), traction, risque homme-clé, redéployabilité de la PI | 10-20 % |
   | Environnement juridique | Opposabilité des sûretés sur la PI, lieu de détention de la PI, disponibilité du *pre-pack* (directive 2026/799), risque réglementaire sectoriel | 5-10 % |

5. **Règles de migration anti-falaise** : revue trimestrielle, hystérésis et dérogations forcées (voir P5).
6. **Aucune imputation des warrants** en réduction de la LGD, de l'EL ou dans le classement (voir P7.4).
7. **Propriété intellectuelle.** La PI n'est pas une sûreté éligible en F-IRB (`micro-analysis.md` §4.3 ; `macro-analysis.md` §3 point 4). Plutôt que de la rendre éligible, ce qui constituerait un écart à Bâle sans méthode de valorisation robuste, la PI est reconnue **comme sous-facteur du *slotting*** : inscription, redéployabilité, familles de brevets. L'EBA est chargée d'un rapport, à remettre après la publication du cadre d'évaluation de la PI annoncé par la Commission (COM(2026) 615), sur l'opportunité d'une reconnaissance ultérieure en tant que « autre sûreté ».

**Cadres connectés.** Art. 153(5) et 153(9), art. 158(6), art. 161 (LGD F-IRB) ; règlement délégué 2021/598 ; EBA/CP/2026/09 ; Bâle CRE33 (HVCRE) ; directive (UE) 2026/799 (*pre-pack* comme élément du facteur juridique) ; COM(2026) 615 (évaluation de la PI).

**Bénéfices attendus.**
- **Micro :**
  - pour VDQ-C, une banque IRB non contrainte passe d'environ 115-130 % (modèle PD) à 90-115 %, soit **jusqu'à −26 pb/an** pour les profils « bons » ;
  - pour VDQ-P, 140 à 250 % au lieu de 170 à 240 %, donc un résultat à peu près neutre, avec **moins de dispersion** et sans coût de modélisation ;
  - l'obstacle de validation des modèles disparaît.
- **Macro :**
  - la différenciation est préservée : pas de pondération à 50 ou 70 %, et le palier P est plus lourd ;
  - la catégorie 4 par défaut en cas de données manquantes rend la méthode conservatrice.

**Risques et limites.**
- (i) Le *slotting* hors *specialised lending* est une divergence vis-à-vis de Bâle, que P13 traite.
- (ii) Une banque IRB non contrainte bénéficie d'un allègement dès le lancement pour VDQ-C (catégorie 2 à 90 %). Cet allègement est modeste, borné par le plafond de P9 et soumis au suivi de P10.
- (iii) La charge de travail de l'EBA est déjà engagée (`stakeholder-map.md` §4). Elle est atténuée par la réutilisation de la structure existante, avec un délai de 18 à 24 mois.
- (iv) Les poids des facteurs doivent être validés empiriquement (`micro-analysis.md` §8.3(5)).

---

### P4 — Clause d'activation sur données : facteur de type 501a et catégories dormantes. Comparaison des options

**Résumé exécutif.** Plutôt que de choisir entre un *slotting* complet et un facteur de soutien de type 501a, ce document les **combine en les séquençant** :
- le *slotting* et l'approche standard dédiée (P1 à P3) constituent l'architecture de **sensibilité au risque** ;
- un **facteur de soutien de 0,85** pour VDQ-C, qui vise précisément le « trou » laissé par l'art. 501 au-delà de 50 M€ de chiffre d'affaires, et les **catégories dormantes** (80 % en approche standard, catégorie 1 en IRB) sont **inscrits au niveau 1 mais inactifs**.

Ces éléments ne s'activent, par acte délégué de la Commission, que si un rapport de l'EBA fondé sur des données européennes couvrant un retournement du cycle VC le justifie. Ils s'éteignent automatiquement faute d'effet d'offre.

**Problème et ancrage factuel.**
- **L'art. 501a offre une voie légère** : un facteur en aval des RWA, sans nouvelle classe, applicable en approche standard comme en IRB, avec un rapport d'évaluation de l'EBA intégré (`current-regulation.md` §4). L'analogie économique est toutefois fragile : l'infrastructure a des flux prévisibles, la venture debt non (§4, nuance).
- **Le facteur PME disparaît au stade *growth*** : au-delà de 50 M€ de chiffre d'affaires, précisément là où l'entreprise devient moins risquée. C'est une falaise (`current-regulation.md` §5 ; `micro-analysis.md` §6 friction n° 2).
- **Le garde-fou n° 1** interdit toute pondération effective inférieure à 100 % sans données validées (`macro-analysis.md` §6).
- **Aucune série de pertes européenne n'existe** (`micro-analysis.md` §8.3(7) ; `macro-analysis.md` §8.4 ; `benchmarking.md` §6).
- **Risque de « calibrage de complaisance »** ouvrant la voie à d'autres dérogations (`macro-analysis.md` §4.5, conclusion).

**Comparaison des options.**

| Option | Contenu | Avantages | Inconvénients | Verdict |
|---|---|---|---|---|
| **0. Pilier 2 seul** (voie OCC) | Guidance, sans niveau 1 | Rapide, conforme à Bâle, précédent testé (`benchmarking.md` §2.3) | Ne règle ni l'obstacle des données IRB, ni la non-discrimination en approche standard, ni l'insécurité sur les warrants, ni l'invisibilité statistique | **Retenue comme socle** (P8), mais insuffisante seule |
| **A. Sixième sous-catégorie SL au sens strict** | Réécriture de l'art. 147(8) | Étiquette familière | Contamine le triple test, fait sortir automatiquement du champ des lignes directrices BCE (garde-fou n° 4), s'emmêle avec l'agenda EBF et la réserve de COM(2026) 615, divergence bâloise plus visible | **Écartée** (§0.1) |
| **B. Facteur de type 501a seul** | Par exemple 0,75 ou 0,85 sur toute la venture debt | Simplicité, approche standard et IRB, précédent | Subventionne à plat l'*early stage*, déjà sous-capitalisé ; viole le garde-fou n° 1 au lancement ; ne règle pas l'obstacle des données IRB ; les facteurs de soutien sont précisément ce que le RCAP 2014 a critiqué (`stakeholder-map.md` §8) ; exige de toute façon une définition | **Écartée comme mesure autonome** |
| **C. Hybride séquencé** (recommandé) | P1 à P3 plus un facteur et des catégories **dormants**, activables sur données | Sensibilité au risque dès le lancement ; allègement conditionné à la preuve ; crédibilité prudentielle ; utilise la technique de l'art. 501a là où elle est la plus défendable | Allègement différé, qui peut ne jamais venir ; complexité | **Recommandée** |

**Mécanisme (option C).**
1. **Inscription au niveau 1** d'un nouvel article, placé à la suite de l'art. 501a (numérotation à arrêter) :
   - un facteur de **0,85** appliqué aux RWA des expositions VDQ-C sur des emprunteurs **qui ne bénéficient pas de l'art. 501** (chiffre d'affaires supérieur à 50 M€). Il est non cumulable avec l'art. 501. Il **comble la falaise** de 50 M€ au même niveau que le facteur PME au-delà de 2,5 M€ ;
   - les catégories dormantes : 80 % en approche standard pour VDQ-C « haute qualité » (P2), catégorie 1 en *slotting* (P3).
2. **Condition d'activation.** Un rapport de l'EBA (P10) doit établir, sur au moins 5 ans de données européennes au niveau du prêt **couvrant au moins une phase basse du cycle VC** comparable à 2022-2024, et hors famille (c), que les pertes réalisées de VDQ-C sont compatibles avec l'EL des catégories visées. Il doit aussi établir que la corrélation observée ne dépasse pas celle retenue.
3. **Instrument d'activation.** La Commission est habilitée à fixer **par acte délégué la date d'application** des éléments dormants, avec droit d'objection du Parlement et du Conseil. Le précédent est l'**art. 461a CRR**, qui habilite la Commission à différer par acte délégué l'application du cadre FRTB, habilitation déjà utilisée (`current-regulation.md` §1.2). Solution de repli si l'art. 290 TFUE est jugé bloquant, au motif qu'une pondération serait un élément essentiel : le rapport de l'EBA déclenche l'obligation pour la Commission de présenter une proposition législative ciblée.
4. **Plafond.** Les éléments activés ne s'appliquent que dans la limite du plafond de 10 % des fonds propres (P9).
5. **Extinction.** Si, cinq ans après l'activation, l'**intensité** de venture debt bancaire rapportée à l'equity VC levée n'a pas augmenté, les éléments activés deviennent caducs. L'indicateur est l'intensité et non le volume, parce que l'offre suit le cycle de l'equity (`macro-analysis.md` §1.5, §5.1). La démarche applique directement les enseignements du facteur PME (EBA 2016 : « aucune preuve » d'effet ; `macro-analysis.md` §5.1).

**Cadres connectés.** Art. 501 et 501a (technique), art. 461a (précédent d'acte délégué sur la date d'application), art. 290 TFUE.

**Bénéfices attendus.**
- **Micro (après activation) :**
  - VDQ-C d'un emprunteur au-dessus de 50 M€ de chiffre d'affaires, en approche standard : 100 % puis 85 %, soit **−16 pb/an** ;
  - banque IRB contrainte par le plancher : 72,5 % puis 61,6 % ;
  - la falaise de 50 M€ disparaît.
- **Macro :** l'allègement **suit la preuve**, et non le lobbying. C'est la réponse directe au risque de calibrage de complaisance et à l'objection RCAP.

**Risques et limites.**
- (i) L'activation peut ne jamais intervenir. Les acteurs y verront un compartiment « vide » au lancement. Il faut l'assumer : c'est la condition de la crédibilité.
- (ii) Une pression politique pour une activation anticipée est probable.
- (iii) La question de l'art. 290 TFUE demeure.
- (iv) Il faudra environ 5 ans de données, ce qui repousse une activation au mieux vers 2032-2033.

---

## B. Covenants, séniorité et tranches

### P5 — Covenants : les reconnaître comme outils de contrôle et neutraliser leurs effets procycliques

**Résumé exécutif.** Les covenants de venture debt ne sont pas des tests de couverture de flux. Ce sont des **déclencheurs de contrôle**. La proposition :
- (i) en fait une condition d'éligibilité minimale (P1) ;
- (ii) les valorise dans le facteur « sûretés et contrôle » du *slotting* ;
- (iii) neutralise leurs effets procycliques par trois règles de migration : hystérésis, dérogations dures limitées, facteur de cycle VC traité au niveau du portefeuille ;
- (iv) clarifie qu'un **réaménagement de covenant accompagné d'une injection d'equity** qui restaure au moins 12 mois de runway n'est pas, en soi, une mesure de *forbearance* (restructuration pour difficultés financières).

**Problème et ancrage factuel.**
- **Les covenants ne mesurent pas une couverture.** L'EBITDA est négatif, le DSCR est inférieur à 1 par construction et l'ICR est négatif. Les covenants sont une « option de sortie ou de contrôle » : trésorerie minimale, performance par rapport au plan, clause MAC, clause d'*investor abandonment*, jalons de levée, *equity cure* (`micro-analysis.md` §2.5).
- **Ils peuvent provoquer des défauts auto-réalisateurs** en phase basse du cycle, en particulier par les clauses d'abandon et les jalons de levée (`micro-analysis.md` §0 point 7 ; §6 friction n° 9).
- **Falaise du *slotting*.** Quand le runway tombe sous 6 à 9 mois sans *term sheet*, la pondération double d'un coup (`micro-analysis.md` §6 friction n° 10). Un retournement ferait migrer simultanément de nombreuses expositions (`macro-analysis.md` §2.3).
- **Migrations fréquentes.** Environ 17 à 34 % des portefeuilles BDC sont en grade 3 ou pire, même hors crise (`micro-analysis.md` §3.3).
- **Précédent OCC.** Les covenants de liquidité résiduelle ne suffisent pas, seuls, à garantir le remboursement (`benchmarking.md` §2.3).

**Mécanisme.**
1. **Socle d'éligibilité** (P1(e)) : covenant de trésorerie minimale et reporting mensuel.
2. **Valorisation dans la grille** (RTS, P3). Sont valorisés les covenants de **contrôle** : trésorerie minimale ou runway, contrôle des comptes, reporting mensuel, tirages conditionnés à des jalons. Les clauses à « détente brusque » (*investor abandonment*, MAC) sont **neutres** : elles ne rapportent aucun point dans la grille, pour ne pas inciter à leur multiplication.
3. **Règles de migration** (RTS) :
   - **hystérésis** : une dégradation de catégorie n'intervient qu'après deux évaluations trimestrielles consécutives défavorables (`micro-analysis.md` §8.3(1)) ;
   - **dérogations dures** (immédiates) : classement automatique en catégorie 4 si le runway est inférieur à 6 mois sans *term sheet* signé, en cas de défaut de paiement, ou si la juste valeur du warrant est ramenée à zéro, signal prédictif de faillite (`micro-analysis.md` §8.3(3), §2.4) ;
   - **le cycle VC n'est pas un déclencheur individuel.** Aucune dégradation ne peut être motivée par des indicateurs de marché globaux. Le facteur systémique est traité par le calibrage (corrélation, P3) et par le pilier 2 (stress « gel VC », P9), conformément à `micro-analysis.md` §7 (dimension absente n° 2).
4. **Clarification défaut et *forbearance*.** L'EBA procède par Q&A ou par modification ciblée des orientations EBA/GL/2018/06 (expositions non performantes et restructurées), en cohérence avec EBA/GL/2016/07 (définition du défaut, art. 178 CRR) :
   - un **réaménagement ou une renonciation** à un covenant, **concomitant à une injection d'equity engagée** qui restaure un runway d'au moins 12 mois, **n'est pas en soi** une mesure de *forbearance* ;
   - à l'inverse, une extension de maturité, une capitalisation d'intérêts (PIK) ou un rééchelonnement **sans** *equity cure* est **présumé** constituer une *forbearance*.

   Cette règle distingue le soutien réel du sponsor du renouvellement artificiel d'un prêt compromis (*evergreening*).
5. **Attente de pilier 2** (P8) : évaluation, au niveau du portefeuille, du risque auto-réalisateur des clauses d'abandon.
6. **Responsabilité du prêteur.** Le risque qu'un exercice intensif des droits de contrôle soit requalifié en gestion de fait ou en soutien abusif, selon les droits nationaux, est traité dans la cartographie de P12, niveau 1.

**Cadres connectés.** Art. 178 CRR ; EBA/GL/2016/07 ; EBA/GL/2018/06 ; règlement délégué 2021/598 (fréquence de revue) ; OCC 2025-45.

**Bénéfices attendus.**
- **Micro :** trajectoires de pondération plus stables ; moins d'accélérations forcées ; distinction nette entre un covenant « outil de pilotage » et un covenant « détonateur ».
- **Macro :** c'est la réponse la plus directe au risque de **dégradations synchronisées** propre au *slotting* (`macro-analysis.md` §2.3 ; garde-fou n° 5).

**Risques et limites.**
- (i) L'hystérésis retarde d'un trimestre la reconnaissance d'une dégradation. Les dérogations dures en bornent l'effet.
- (ii) La clarification sur la *forbearance* pourrait servir à maquiller des renouvellements artificiels. Elle est donc strictement conditionnée (equity engagée, runway d'au moins 12 mois) et reste sous contrôle du superviseur.
- (iii) L'EBA pourrait refuser une règle sectorielle dans des orientations transversales. Solution de repli : une Q&A interprétative.

---

### P6 — Séniorité et tranches : une architecture « banque en senior, fonds en junior » et une frontière claire avec la titrisation

**Résumé exécutif.** La proposition repose sur cinq éléments :
- réserver la catégorie VDQ au **senior** ; le junior reste à l'art. 128 (150 %), sans nouvel allègement ;
- reconnaître dans le *slotting* la **position dans la cascade de pertes** (sous-facteur de CP/2026/09), pour les *split-liens* avec un prêteur ABL comme pour les montages où **un fonds de prêt AIFMD, un ELTIF ou le groupe BEI porte la tranche junior** ;
- **écarter le risque de requalification en titrisation** du découpage senior/junior d'une facilité unique, en étendant l'exclusion déjà prévue pour le *specialised lending* ;
- conditionner la reconnaissance prudentielle du rang contractuel à un **avis juridique** ;
- transformer ainsi l'asymétrie banques/fonds relevée par `stakeholder-map.md` en **complémentarité**.

**Problème et ancrage factuel.**
- **La structure dominante est le senior de premier rang.** Le junior est rare et fourni surtout par des fonds ; le HoldCo PIK européen se prête à 10-17 % (`micro-analysis.md` §2.3).
- **Falaise de subordination.** De 100 % à 150 % en approche standard, de 40 % à 75 % de LGD en F-IRB (`micro-analysis.md` §6 friction n° 4).
- **La coexistence avec un ABL exige un accord inter-créanciers.** Le sous-facteur « position dans la cascade de pertes » de CP/2026/09 est directement pertinent (`micro-analysis.md` §2.3, §7).
- **Asymétrie concurrentielle.** Les fonds relèvent d'AIFMD II (plafonds de levier de 175 et 300 %, limites par emprunteur) alors que les banques relèvent du CRR. « Aucune version de la réforme qui allégerait unilatéralement le capital bancaire sans traiter cette asymétrie » ne satisfait à la fois l'objectif de développement du marché et l'absence de distorsion (`stakeholder-map.md` §2, synthèse n° 3).
- **La subordination contractuelle est reconnaissable dès aujourd'hui en prudentiel, mais son opposabilité transfrontière est incertaine** (`current-regulation.md` §7.3, §8).

**Mécanisme.**
1. **Senior seulement** (P1(d)). Toute tranche junior, subordonnée ou mezzanine détenue par une banque reste traitée à 150 % (art. 128) et à 75 % de LGD F-IRB (art. 161). **Aucun allègement n'est créé pour le junior** (`micro-analysis.md` §1.1).
2. **Cascade de pertes.** Le RTS (P3) valorise la position de la tranche bancaire. Un *split-lien* défavorable face à l'ABL fait descendre en catégorie « satisfaisant » au mieux (`micro-analysis.md` §8.5). Une tranche senior protégée par une tranche junior tierce **financée en cash** et contractuellement subordonnée, **représentant au moins 20 à 25 % de la facilité**, peut accéder à la meilleure note du facteur « sûretés et contrôle ». Pas de modification de l'approche standard (100 / 130 %), par souci de simplicité et en application du garde-fou n° 1.
3. **Architecture banque-fonds.** Les porteurs éligibles de la tranche junior sont définis par renvoi :
   - FIA octroyant des prêts au sens d'AIFMD II (directive (UE) 2024/927), soumis à ses limites de levier et de rétention ;
   - ELTIF (le règlement ELTIF 2.0 permet l'octroi de prêts) ;
   - groupe BEI et banques nationales de développement.

   La banque garde le risque qu'elle sait gérer (senior, court, surveillé mensuellement). Le fonds porte le risque junior sans RWA et avec l'appétit qui lui est propre.
4. **Frontière avec la titrisation.** Le découpage d'une facilité unique en tranches senior et junior entre deux prêteurs, avec un accord inter-créanciers, peut réunir les éléments de la définition de la titrisation : risque de crédit « tranché », subordination qui détermine la répartition des pertes. Or cette définition, reprise par le CRR (art. 4(1)(61)), **exclut déjà** les montages qui créent des expositions présentant les caractéristiques du *specialised lending* (règlement (UE) 2017/2402, art. 2(1), condition (c)). La proposition **étend cette exclusion aux VDQ** : le découpage d'une facilité VDQ entre prêteurs, sous accord inter-créanciers, ne constitue pas une titrisation. [à vérifier : portée exacte du risque de requalification des structures *unitranche* « first-out / last-out » ; position de l'EBA et de l'ESMA]
5. **Sécurité juridique.** La banque ne peut reconnaître le rang contractuel (senior face au junior tiers ou face à l'ABL), dans le *slotting* ou dans la LGD, que sur la base d'un **avis juridique écrit et motivé**. Cet avis porte sur l'opposabilité dans l'État membre d'immatriculation **et** dans celui du centre des intérêts principaux de l'emprunteur. Le modèle est l'exigence d'efficacité juridique des techniques d'atténuation du risque (art. 194(1) CRR). Le coût de ces avis est réduit par la cartographie comparative de P12, niveau 1.

**Cadres connectés.** Art. 128, 161, 194 CRR ; CP/2026/09 ; AIFMD II ; ELTIF 2.0 ; règlement titrisation, art. 2(1) ; directive 2019/1023 (classes de créanciers, P12).

**Bénéfices attendus.**
- **Micro :** meilleure note pour les tranches senior protégées ; clarté juridique du montage (pas de titrisation accidentelle) ; possibilité pour les banques de coopérer avec les fonds plutôt que de les concurrencer frontalement.
- **Macro :** conversion de la friction n° 3 de `stakeholder-map.md` en division du travail ; le risque junior, le plus sensible au cycle, reste hors des bilans de dépôt ; cohérence avec le constat que la structure non bancaire européenne « ne présente pas le canal de ruée » (`macro-analysis.md` §2.5).

**Risques et limites.**
- (i) **Interconnexion banques-fonds.** Canal 3 de `macro-analysis.md` §2.5, à surveiller dans P9 : les prêts bancaires aux fonds de venture debt relèvent du *fund finance* et restent hors VDQ.
- (ii) L'extension de l'exclusion de titrisation peut être contestée par les autorités européennes de surveillance au titre de l'anti-contournement. Elle est bornée aux facilités unitaires VDQ.
- (iii) L'efficacité de l'accord inter-créanciers en procédure collective reste une question nationale (P12).

---

## C. Warrants

### P7 — Warrants et equity kickers : sécuriser la qualification et la pondération, sans leur faire absorber de pertes

**Résumé exécutif.** L'effet des warrants sur le coût en capital est faible : moins de 0,1 point de spread (`micro-analysis.md` §0 point 5). Les vraies frictions sont d'ordre **juridique** : 400 % ou 250 % selon la durée de détention, qualification en dérivé ou en action, test SPPI, régime des fintechs, conversion dette-actions. La proposition règle ces points en sept volets :
- une qualification claire ;
- 250 % au lieu de 400 % pour les warrants accessoires à une VDQ, quelle que soit la voie de monétisation, sous plafonds ;
- 100 % via l'art. 133(5) lorsque le prêt s'inscrit dans un programme public (P11) ;
- l'interdiction d'imputer la valeur des warrants sur les pertes ;
- une clarification du régime applicable aux emprunteurs fintechs ;
- une exemption temporaire à l'art. 89 pour les conversions dette-actions opérées **dans le cadre des procédures européennes** de restructuration et de *pre-pack* ;
- le statu quo comptable, assumé.

**Problème et ancrage factuel.**
- **Art. 133.** La pondération est de 250 %, ou de **400 %** pour les « investissements dans des entreprises de capital-risque ou similaires acquis en anticipation de plus-values significatives à court terme ». Une exception existe pour une détention d'au moins 3 ans ou une « relation d'affaires de long terme » (`current-regulation.md` §3.5 ; `micro-analysis.md` §2.4, §5.3). **Insécurité juridique** : une monétisation rapide, par revente à l'entreprise (pratique de la BEI) ou à un tiers, peut faire basculer à 400 %. Il en découle une incitation à conserver les warrants (`micro-analysis.md` §6 friction n° 5).
- **Qualification.** Le warrant est-il une exposition actions (art. 133(1)(d)) ou un dérivé traité en risque de contrepartie (SA-CCR) ? « Aucune Q&A EBA spécifique n'a été trouvée » (`micro-analysis.md` §5.3).
- **SPPI.** Un kicker incorporé au prêt fait passer **tout** le prêt en juste valeur par résultat (`micro-analysis.md` §2.4, friction n° 6).
- **Fintechs.** Les warrants pris sur une « entité du secteur financier » pourraient relever du régime de déduction du CET1 (art. 36(1)(h) et 44-46). Or le secteur financier est le premier secteur de la venture debt européenne en valeur (`micro-analysis.md` §2.4, [à vérifier]).
- **Art. 89.** Le seuil n'est pratiquement jamais atteint par les warrants (0,1 à 1 % du capital). Il ne devient plausible qu'après une **conversion dette-actions**, que les exclusions de l'art. 91 ne couvrent pas clairement (`micro-analysis.md` §5.3 ; `current-regulation.md` §3.5).
- **Pas d'effet d'assurance.** La compensation par les warrants est **inter-temporelle**, pas contingente à l'état du monde. Les imputer en déduction de la LGD serait « actuariellement faux » (`micro-analysis.md` §3.4, §4.3).
- **Précédents.** Le Royaume-Uni maintient 400 % pour l'equity VC (`benchmarking.md` §3.1). Aux États-Unis, le 12 CFR 7.1006 interdit de conditionner le remboursement du principal à la valeur du warrant (`micro-analysis.md` §2.4).

**Mécanisme.**
- **7.1 Qualification.** Les warrants et kickers reçus en contrepartie d'une VDQ sont des **expositions actions du portefeuille bancaire au sens de l'art. 133(1)(d)**. Ce ne sont pas des expositions de contrepartie traitées en SA-CCR. Mise en œuvre : clarification au niveau 1 (considérant et article) ; dans l'intervalle, une Q&A de la Commission via la procédure de l'art. 16b du règlement EBA.
- **7.2 Pondération.** Ces warrants sont pondérés à **250 %, jamais à 400 %**, quelles que soient la durée de détention et la voie de monétisation (put vers l'entreprise, cession secondaire, exercice net), sous trois conditions :
  - (i) ils sont accessoires à une VDQ ;
  - (ii) ils donnent droit à **10 % au plus** du capital ou des droits de vote de l'emprunteur, seuil cohérent avec l'art. 89 et avec la « sphère de sécurité » de P12 ;
  - (iii) leur valeur exposée agrégée ne dépasse pas **1 % des fonds propres**.

  Au-delà du plafond, le régime général de l'art. 133 s'applique. Les dispositions transitoires de l'art. 495a restent applicables (130 et 160 % en 2026, 250 et 400 % en 2030). Cette précision reste **dans la lettre de Bâle** : l'exclusion des participations liées à une relation d'affaires de long terme y figure déjà. Le texte européen ne fait que lever l'ambiguïté.
- **7.3 Programmes publics.** Lorsque la VDQ est octroyée dans un programme public **notifié au registre** de la Commission au titre de l'art. 133(5) et de la communication C(2025) 7231, les warrants associés peuvent être pondérés à **100 %**, dans la limite de 10 % des fonds propres. Il peut s'agir de la fenêtre InvestEU de P11 ou d'un dispositif d'une banque nationale de développement. Les trois critères de la communication sont compatibles avec une fenêtre de garantie InvestEU [vérifié] : soutien public significatif (y compris par des garanties ou des mécanismes de partage des risques), supervision publique, restrictions sur les investissements. En revanche, **la communication ne dit pas** si des warrants attachés à des prêts garantis sont des « expositions actions encourues dans le cadre du programme » [vérifié : point non traité]. Une confirmation de la Commission est donc requise.
- **7.4 Interdiction d'imputation.** La valeur ou le rendement attendu des warrants ne peut être reconnu ni comme atténuation du risque, ni en réduction de la LGD ou de l'EL, ni dans le classement *slotting* (disposition expresse du RTS, P3).
- **7.5 Emprunteurs fintechs.** Une Q&A de l'EBA doit préciser si les warrants sur des instruments CET1 d'entités du secteur financier constituent des « détentions synthétiques » au sens de l'art. 36(1)(h). La recommandation est de les traiter **dans le seuil de 10 % du CET1 de l'art. 46**, comme les autres détentions non significatives, sans régime particulier. L'enjeu est la clarté, pas l'allègement.
- **7.6 Conversion dette-actions.** L'art. 91 est complété : les titres reçus par conversion de créances dans le cadre d'un **plan de restructuration adopté au titre de la directive (UE) 2019/1023** ou d'une **procédure de *pre-pack* au titre de la directive (UE) 2026/799** sont exclus du calcul des limites de l'art. 89 **pendant 5 ans**. Le régime prudentiel s'**adosse ainsi aux procédures européennes harmonisées** au lieu de créer une notion autonome de « sauvetage ». La logique est proche des privilèges d'assainissement nationaux, par exemple le § 39(4) InsO allemand [à vérifier pour la portée exacte].
- **7.7 IFRS 9.** Aucune modification prudentielle. Les normes IFRS sont adoptées par l'Union via le règlement (CE) n° 1606/2002 et ne se modifient pas unilatéralement. L'exigence d'un kicker **détachable** (P1(f)) garantit que la VDQ est au coût amorti et provisionnée en pertes attendues. Un kicker incorporé fait sortir le prêt de la catégorie VDQ : il redevient une exposition corporate générique, en juste valeur par résultat, avec ajustements de valorisation prudente (art. 34 et 105). Les amendements de l'IASB de 2024 sur la classification ne semblent pas couvrir les rémunérations indexées sur la valeur des titres [à vérifier].

**Cadres connectés.** Art. 133, 495a, 36(1)(h), 44-46, 89-91, 34, 105 CRR ; C(2025) 7231 ; règlement (CE) n° 1606/2002 ; directives 2019/1023 et 2026/799 ; règlement EBA, art. 16b.

**Bénéfices attendus.**
- **Micro :** l'effet en capital est minime (passer de 400 à 250 % sur des warrants valant environ 2 % du principal représente environ 3 pb/an). En revanche, la **sécurité juridique** supprime l'incitation à conserver les warrants et permet une gestion active de leur liquidité. La conversion dette-actions dans une restructuration n'est plus bloquée par l'art. 89.
- **Macro :** effet neutre. Le seuil de 10 % devient cohérent entre le prudentiel (art. 89) et l'insolvabilité (P12).

**Risques et limites.**
- (i) La mesure peut être perçue comme un encouragement à la spéculation. Les plafonds et le caractère accessoire obligatoire y répondent.
- (ii) L'articulation avec le régime de déduction des fintechs reste à trancher par `current-regulation-analyst`.
- (iii) Le volet 7.3 dépend d'une interprétation de la Commission.

---

## D. Pilier 2 et garde-fous macroprudentiels

### P8 — Pilier 2 : une section « venture debt » dans les orientations EBA sur l'octroi et le suivi des prêts, et la substitution conditionnelle de la guidance BCE sur l'effet de levier

**Résumé exécutif.** Transposer le précédent **OCC 2023-34 / 2025-45**, en l'adaptant, **dans un instrument européen existant** : les orientations EBA/GL/2020/06, qui comportent déjà des dispositions propres à certains types de financement. Parallèlement, la BCE modifierait sa guidance de 2017 sur l'effet de levier : les VDQ en sortiraient **uniquement si** la banque applique la nouvelle section « venture debt ». C'est une **substitution** d'un cadre adapté à un cadre inadapté, et non une sortie. Cette proposition ne requiert **aucune modification du niveau 1** et peut commencer dès 2026-2027.

**Problème et ancrage factuel.**
- **Le précédent le plus directement transposable, sans toucher au pilier 1,** est la guidance OCC : appétit au risque approuvé par le conseil d'administration, limites par stade, secteur et facteur de risque, agrégation des expositions, standards de souscription, provisionnement renforcé (`benchmarking.md` §2.3, §6).
- **Les lignes directrices BCE sur l'effet de levier sont inadaptées.** Une entreprise financée par du VC, détenue à plus de 50 % par des « sponsors financiers » et à EBITDA négatif, entre vraisemblablement dans leur champ, **sans ratio de levier calculable** (`micro-analysis.md` §5.4 ; `macro-analysis.md` §2.6).
- **Garde-fou n° 4** : pas de sortie automatique de leur champ (`macro-analysis.md` §6).
- **La contrainte liante n'est pas le capital** mais « la culture du risque et l'encadrement de supervision » (`macro-analysis.md` §5.2(3)). La sortie des lignes directrices serait peut-être « plus significative que l'allègement en capital » (`macro-analysis.md` §2.6).
- **Priorités de supervision de la BCE** : qualité des critères de souscription (`stakeholder-map.md` §4).

**Mécanisme.**
1. **Nouvelle section d'EBA/GL/2020/06**, placée à côté des dispositions sectorielles existantes [numérotation à vérifier]. Base juridique : art. 16 du règlement EBA ; art. 74 et 79 CRD. Contenu :
   - **(a) Appétit au risque** approuvé par le conseil d'administration, avec des limites par palier (P/C), par secteur (y compris l'IA, compte tenu de `macro-analysis.md` §2.3), **par sponsor** et **par millésime**.
   - **(b) Agrégation** de toutes les expositions venture, quel que soit leur portefeuille ou leur intitulé comptable (repris de l'OCC).
   - **(c) Souscription : adaptation plutôt que transplantation.** L'OCC pose qu'un tour futur non engagé n'est **pas** une source de remboursement primaire acceptable. Cette règle est **incompatible** avec la définition VDQ, qui repose précisément sur cette source. La version européenne la convertit en **test quantitatif** : le prêt doit pouvoir être servi jusqu'à maturité, ou jusqu'à un niveau d'amortissement défini, **sans nouveau tour pendant 12 à 18 mois**, grâce au runway existant et aux tranches engagées (`micro-analysis.md` §7, facteur 1). Le principe de prudence de l'OCC est conservé ; le texte s'adapte à une architecture où le risque de refinancement est **reconnu et mesuré** plutôt qu'interdit.
   - **(d) Diligence sur le sponsor** : âge du fonds, réserves allouées, historique de soutien (`micro-analysis.md` §7, facteur 4).
   - **(e) Suivi** : reporting mensuel, revue trimestrielle du *slotting*, signaux de marché (P5).
   - **(f) Gouvernance des warrants** : valorisation indépendante, ajustements de valorisation prudente, interdiction d'imputation (P7).
   - **(g) Provisionnement IFRS 9** : correction prospective liée au cycle VC ; indicateurs de hausse significative du risque de crédit (tour en baisse, juste valeur du warrant à zéro, bris de covenant de trésorerie).
   - **(h) Lien actif-passif** : les clauses de domiciliation de la trésorerie sont recensées et reliées au suivi de liquidité (P9).
   - **(i) Proportionnalité** pour les portefeuilles de petite taille.
2. **Guidance BCE sur l'effet de levier (MSU).** Les VDQ sont exclues de son champ **à condition que** la banque applique la section « venture debt » et que l'équipe de supervision conjointe ne s'y oppose pas. À défaut, elles restent dans le champ. Pour les établissements moins importants, le même résultat passe par les orientations de l'EBA et les autorités nationales.
3. **SREP.** Référence à la section « venture debt » dans l'évaluation du risque de crédit et de concentration (EBA/GL/2022/03).

**Cadres connectés.** Art. 74, 79 et 97 CRD ; règlement EBA, art. 16 ; EBA/GL/2020/06 ; guidance BCE de 2017 ; EBA/GL/2022/03 ; OCC 2025-45.

**Bénéfices attendus.**
- **Micro :** remplacer un cadre inopérant (levier non calculable) par un cadre adapté réduit une friction qualitative que la macro-analyse juge potentiellement plus lourde que le capital. Des standards communs réduisent aussi le coût d'entrée pour une banque sans expertise préalable.
- **Macro :** meilleure qualité de souscription ; limites par sponsor et par millésime (dimensions « absentes » du *slotting*, `micro-analysis.md` §7) ; aucune création de canal de ruée.

**Risques et limites.**
- (i) Charge de l'EBA et réticence possible de la BCE, qui a durci sa supervision du levier depuis 2017.
- (ii) Des orientations appliquées selon le principe « se conformer ou s'expliquer » peuvent être mises en œuvre de manière hétérogène d'un État à l'autre.
- (iii) La mesure peut être lue comme un « allègement déguisé ». La conditionnalité et la discrétion du superviseur y répondent.

---

### P9 — Concentration, liquidité, coussin sectoriel et résolution : les leçons de SVB

**Résumé exécutif.** Mettre en œuvre les garde-fous n° 2, 3 et 5 :
- un **plafond de 10 % des fonds propres** pour les éléments préférentiels ;
- une **présomption de revue de pilier 2** au-delà de 5 % ;
- un **suivi des dépôts de l'écosystème VC** (ALMM, ILAAP, clarification sur les dépôts opérationnels) ;
- un **sous-ensemble sSyRB préidentifié** ;
- une prise en compte dans la **planification de la résolution**.

Le compartiment ne doit pas recréer la double exposition corrélée actif-passif qui a fait tomber SVB.

**Problème et ancrage factuel.**
- **SVB relève du passif, pas des pertes de crédit.** Les prêts « investor dependent » représentaient 9 % du portefeuille, les passages en pertes 0,10 %. Les dépôts non assurés atteignaient 88 à 94 %, et plus de 40 Md$ ont été retirés en une journée (`macro-analysis.md` §2.4 ; `benchmarking.md` §2.2).
- **Un canal de ruée à ne pas introduire.** Faire migrer l'activité vers des banques de dépôt introduirait ce canal (`macro-analysis.md` §2.5).
- **Granularité faible** : le risque de concentration relève du pilier 2 (`macro-analysis.md` §2.2(2)). Le risque de concentration par sponsor et par millésime n'est pas capté par les grands risques (`micro-analysis.md` §5.4).
- **Liquidité** : le taux de sortie de 40 % sur 30 jours appliqué dans le LCR est « dépassé en une journée » (`macro-analysis.md` §2.6).
- **sSyRB** : il suppose un sous-ensemble identifiable et une pertinence systémique, non démontrable aujourd'hui (`macro-analysis.md` §2.6).
- **Résolution** : les portefeuilles de prêts à des entreprises non rentables assortis de warrants non cotés se valorisent mal en urgence (`macro-analysis.md` §2.7).
- **Scénario C** : l'émergence d'une ou deux banques spécialisées ferait revenir un point de défaillance unique (`macro-analysis.md` §5.3 ; §2.4, leçon n° 4).

**Mécanisme.**
1. **Plafond (niveau 1, sur le modèle de l'art. 133(5)).** Les éléments préférentiels ne s'appliquent qu'à hauteur d'une valeur exposée VDQ agrégée égale à **10 % des fonds propres**. Ces éléments sont la catégorie 2 en *slotting* et, après activation, le facteur 0,85 et les catégories dormantes (P4). Au-delà, les expositions sont affectées **au minimum en catégorie 3** et ne bénéficient d'aucun élément activé. **Ce n'est pas une interdiction** : une banque peut prêter au-delà, sans préférence.
2. **Présomption de revue de pilier 2.** Une revue renforcée dans le cadre du SREP est présumée si les VDQ dépassent **5 % des fonds propres**, **ou** si les dépôts de l'écosystème VC dépassent un seuil de l'ordre de **15 % des dépôts** [paramètre indicatif]. La revue porte sur :
   - la concentration dans l'ICAAP par sponsor, millésime et secteur, y compris l'IA ;
   - un **stress « gel VC »** de 12 à 18 mois sans tour, sur le modèle de 2022-2024 (`micro-analysis.md` §8.3(6)) ;
   - le cas échéant, une exigence de pilier 2 (art. 104 CRD).
3. **Liquidité.** Trois mesures :
   - (i) l'EBA ajoute un **groupe de contreparties « écosystème VC »** (entreprises financées par VC, fonds VC, clients de *fund finance*) au modèle de concentration du financement des ALMM ;
   - (ii) clarification : les dépôts détenus en application de **clauses de domiciliation liées à un prêt de venture debt** ne sont pas présumés « opérationnels » au sens du règlement délégué (UE) 2015/61 (art. 27) sans preuve spécifique ;
   - (iii) l'ILAAP intègre un scénario de sortie en un jour calibré sur SVB (environ 25 % des dépôts). Le superviseur peut recourir à l'art. 105 CRD (exigences spécifiques de liquidité).
4. **sSyRB.** L'EBA complète ses orientations EBA/GL/2020/13 sur les sous-ensembles d'expositions sectorielles en y ajoutant **les VDQ**. Cela est rendu possible par leur identification dans le COREP (P10). **Pas d'activation** tant que la pertinence systémique n'est pas démontrée (0,06 % des actifs au maximum ; `macro-analysis.md` §2.1). L'outil est prêt si l'exposition agrégée croît.
5. **Résolution.** Pour les banques dont les VDQ dépassent 10 % des fonds propres, le CRU et les autorités nationales de résolution tiennent compte, dans les plans de résolution (art. 10 BRRD), de la valorisation sous stress des portefeuilles de prêts et de warrants et de la concentration des dépôts. C'est cohérent avec l'extension de l'évaluation de l'intérêt public aux banques petites et moyennes par la réforme CMDI (`macro-analysis.md` §2.7).

**Cadres connectés.** Art. 133(5) CRR (modèle du plafond) ; art. 104, 105 et 133 CRD ; règlement délégué (UE) 2015/61 ; ALMM (ITS de reporting) ; EBA/GL/2020/13 ; art. 10 BRRD ; réforme CMDI.

**Bénéfices attendus.**
- **Micro :** une banque spécialisée reste possible, mais elle paie sa concentration.
- **Macro :** le scénario C n'est plus favorisé ; la leçon n° 2 de SVB (le canal effectif est le passif) est intégrée ; le coussin sectoriel est prêt sans être activé.

**Risques et limites.**
- (i) Le plafond **pénalise l'acteur le plus actif** : le modèle HSBC Innovation Banking (`stakeholder-map.md` §1.1). C'est un **arbitrage délibéré** entre développement d'un champion spécialisé et absence de point de défaillance unique, conforme à `macro-analysis.md` §2.4, leçon n° 4.
- (ii) Le seuil de dépôts est un paramètre à calibrer.
- (iii) Les dépôts de l'écosystème VC sont difficiles à identifier sans attribut dans le reporting. P10 y répond.

---

### P10 — Données, calibrage, clause de revoyure et extinction

**Résumé exécutif.** Faire du compartiment un **instrument de connaissance** avant d'en faire un instrument d'allègement :
- une ligne VDQ dans le COREP ;
- un attribut dans AnaCredit, puis dans le futur cadre de reporting intégré (IReF) ;
- une collecte de pertes par l'EBA, **complétée par les données du groupe BEI**, qui détient le plus long historique européen ;
- des rapports à 3 et 5 ans ;
- l'extinction des éléments préférentiels faute d'effet d'offre mesuré en intensité.

**Problème et ancrage factuel.**
- **Aucune série européenne de défaut ou de LGD n'existe.** C'est « le principal risque de mauvais calibrage » (`micro-analysis.md` §8.3(7) ; `macro-analysis.md` §8.4 ; `benchmarking.md` §6).
- **La part bancaire est inconnue.** « Aucune catégorie de reporting prudentiel ne permet d'identifier ces expositions » (`macro-analysis.md` §1.4).
- **Biais de calibrage** : calibrer sur 2010-2021, inclure la famille (c) ou retenir les seuls prêteurs survivants rendrait la grille « actuariellement fausse » (`micro-analysis.md` §8.4).
- **Garde-fou n° 6** : clause de revoyure et extinction (`macro-analysis.md` §6).
- **Le groupe BEI est le premier fournisseur européen** : 338 opérations, 8,4 Md€ en cumul (`micro-analysis.md` §2.2). Le FEI soutiendrait environ 30 % du marché par ses garanties (`stakeholder-map.md` §1.3).

**Mécanisme.**
1. **COREP.** Les VDQ, par palier, sont identifiées dans les modèles de risque de crédit, via les ITS de reporting au titre de l'art. 430 CRR. Un **modèle complémentaire** porte sur le stade, le type de sponsor, le LTER, le runway, la catégorie de *slotting* et la valeur des warrants.
2. **Phase 0, sans attendre le niveau 1.** L'EBA lance une collecte ad hoc au titre de l'art. 35 de son règlement, adossée à ses exercices de suivi, sur les expositions de type venture debt existantes, selon la définition de P1 appliquée **rétrospectivement**.
3. **AnaCredit / IReF.** Ajout d'un attribut « venture debt » (finalité ou type de financement) au règlement BCE sur AnaCredit, puis intégration dans l'IReF.
4. **Groupe BEI.** Un protocole d'accord EBA–groupe BEI organise la transmission de données anonymisées au niveau du prêt (défauts, recouvrements, stades, sponsors), y compris sur les portefeuilles garantis par le FEI. La BEI n'est pas soumise au CRR : l'accord est volontaire.
5. **Règles de calibrage.** Un cycle complet, **incluant 2022-2024** ; exclusion de la famille (c) ; correction du biais de survie ; pas de valeur des warrants dans les pertes.
6. **Clause de revoyure (niveau 1) :**
   - un **rapport de l'EBA à 3 ans** sur la qualité des données et l'adéquation des paramètres de P2 et P3 : 130 / 100 %, EL « faible » pour VDQ-P, corrélation, LGD de 50 % ;
   - un **réexamen complet à 5 ans**, qui inclut l'examen des conditions d'activation de P4.
7. **Extinction.** Voir P4(5) : les éléments activés deviennent caducs en l'absence de hausse de l'**intensité** (VDQ bancaires rapportées à l'equity VC).

**Cadres connectés.** Art. 430 CRR ; règlement EBA, art. 35 ; AnaCredit ; IReF ; statut de la BEI ; `macro-analysis.md` §6.6.

**Bénéfices attendus.**
- **Micro :** coût de reporting marginal.
- **Macro :** il s'agit du « gain net pour la surveillance macroprudentielle, indépendamment de la pondération » (`macro-analysis.md` §2.6), et de la condition de toute activation future.

**Risques et limites.**
- (i) La coopération de la BEI est volontaire.
- (ii) Les données peuvent **confirmer** que l'allègement n'est pas justifié. C'est l'objet même du dispositif.
- (iii) La transition d'AnaCredit vers l'IReF peut retarder l'ajout de l'attribut.

---

## E. Partage des risques public

### P11 — Une fenêtre InvestEU « VDQ », articulée avec l'art. 133(5), le GBER et TechEU

**Résumé exécutif.** Placer le **levier de capital principal** là où la Commission et la macro-analyse le recommandent : dans un **partage des risques budgété et plafonné**, pas dans une pondération générale. La proposition consiste en un produit de garantie du FEI dans le cadre d'InvestEU :
- l'éligibilité est définie **par renvoi à la définition VDQ du CRR** : une seule définition pour le prudentiel et la garantie ;
- la garantie atteint 70 % pour VDQ-P et 50 % pour VDQ-C, avec un plafond par prêt relevé pour les tickets de croissance ;
- le produit est ouvert **aux banques comme aux fonds de prêt AIFMD** ;
- le partage de l'*upside* des warrants avec le FEI réduit le coût budgétaire.

La réduction de pondération passe par la substitution de risque déjà prévue par le CRR, puisque le FEI est une banque multilatérale de développement pondérée à 0 %.

**Problème et ancrage factuel.**
- **COM(2026) 615** privilégie, pour l'« économie immatérielle », le renforcement des capacités, les cadres d'évaluation de la PI et le **partage des risques**, pas les pondérations (`macro-analysis.md` §3, §4.5).
- **Garde-fou n° 7** : « Priorité aux canaux budgétés et plafonnés (garanties InvestEU, TechEU) plutôt qu'à un allègement général » (`macro-analysis.md` §6).
- **La garantie InvestEU « Innovation & Digitalisation » existe déjà** : jusqu'à 80 %, plafond de pertes jusqu'à 25 %, prêts jusqu'à 8,25 M€, intermédiaires bancaires et alternatifs (`macro-analysis.md` §5.2(6)). Mais son plafond par prêt est inférieur aux tickets de croissance : 10 à 40 M€ à la BEI, P75 américain de 27,7 M$ (`micro-analysis.md` §2.1).
- **Benchmarking.** Singapour (EFS-VD) est le seul dispositif **explicitement dédié à la venture debt**, ouvert aux banques **et aux non-banques** (`benchmarking.md` §4.1). Le dispositif britannique (Growth Guarantee Scheme) est généraliste (§3.2).
- **Effet de P2** : le durcissement de VDQ-P appelle une contrepartie ciblée.
- **Asymétrie banques/fonds** (`stakeholder-map.md` §2).

**Mécanisme.**
1. **Produit FEI « VDQ »** dans le cadre du règlement (UE) 2021/523 (InvestEU), par extension ou déclinaison du produit « Innovation & Digitalisation » :
   - éligibilité : toute exposition qui remplit la définition VDQ (P1) ;
   - taux de garantie : **jusqu'à 70 %** pour VDQ-P, **jusqu'à 50 %** pour VDQ-C ;
   - plafond de pertes du portefeuille : de l'ordre de 20 à 25 % ;
   - plafond par prêt **relevé à environ 25 M€** pour VDQ-C ;
   - **rétention d'au moins 30 %** par le prêteur, pour préserver sa responsabilité de souscription ;
   - commission de garantie.
2. **Effet prudentiel par substitution** (art. 213-215 CRR ; le FEI est une banque multilatérale de développement pondérée à 0 % au titre de l'art. 117(2), avec une contre-garantie de l'Union) :
   - VDQ-P : 130 %, puis **39 %** avec 70 % de garantie ;
   - VDQ-C : 100 %, puis **50 %** avec 50 % de garantie.

   Aucune nouvelle règle prudentielle n'est nécessaire.
3. **Neutralité concurrentielle.** Le produit est ouvert aux banques et aux FIA octroyant des prêts, comme le produit « Innovation & Digitalisation » actuel et comme le dispositif singapourien. Pour les fonds, la garantie améliore le rendement ajusté du risque ; pour les banques, elle allège le capital. Aucun des deux n'est privilégié.
4. **Partage de l'*upside*.** Une fraction des produits de warrants des prêts garantis est reversée au FEI. Les warrants compensent les pertes **dans le temps** (`micro-analysis.md` §3.4) : les recycler vers le budget de garantie **finance les pertes des phases basses par les gains des phases hautes**, là où le bilan bancaire seul ne le peut pas.
5. **Articulation avec l'art. 133(5).** Le programme est notifié au registre de la Commission afin de rendre les warrants associés éligibles à 100 % (P7.3).
6. **Déclinaisons nationales et BEI :**
   - les banques nationales de développement (Bpifrance, KfW…) peuvent adosser des dispositifs nationaux à la **même définition**, soit via le compartiment « États membres » d'InvestEU, soit au titre de l'**art. 21 du GBER** (aides au financement des risques), sous réserve de ses conditions ;
   - **TechEU** (70 Md€ en 2025-2027, dont de la « dette de scale-up » ; `macro-analysis.md` §1.2) peut cofinancer aux côtés d'une banque, en pari passu ou en tranche junior (P6).
7. **Adaptation du modèle singapourien.** Le dispositif EFS-VD impose une détention locale d'au moins 30 %. Une telle condition est **incompatible** avec le marché intérieur et avec le constat que 4 opérations de scale-up sur 5 ont un chef de file étranger. La condition européenne est l'établissement dans un État membre, selon les règles d'InvestEU. EFS-VD est un engagement de garantie gouvernemental ; la version européenne est **plafonnée budgétairement** par la provision InvestEU.
8. **Pérennité.** Le produit doit être inscrit dans l'instrument qui succédera à InvestEU dans le cadre financier pluriannuel 2028-2034 (Fonds européen pour la compétitivité, proposé en 2025 [à vérifier]).

**Cadres connectés.** Règlement (UE) 2021/523 ; produit FEI « Innovation & Digitalisation » ; art. 117(2) et 213-215 CRR ; art. 133(5) et C(2025) 7231 ; GBER art. 21 ; TechEU ; COM(2026) 615 ; EFS-VD (Singapour).

**Bénéfices attendus.**
- **Micro :** c'est le **plus gros levier de capital du paquet** : de −65 à −96 pb/an pour VDQ-P, environ −52 pb/an pour VDQ-C. Il est **ciblé** sur le stade où la défaillance de marché est la plus forte.
- **Macro :** budgété, plafonné, conditionnel (garde-fou n° 7) ; aligné sur la préférence déclarée de la Commission, donc la **mesure la plus faisable politiquement** ; il entraîne l'investissement privé au lieu de généraliser un allègement.

**Risques et limites.**
- (i) **Coût budgétaire**, dans un contexte de négociation du cadre financier pluriannuel.
- (ii) **Aléa moral.** La garantie peut réduire l'effort de sélection ; la rétention de 30 % et le plafond de pertes y répondent.
- (iii) **Garantir ne crée pas d'equity.** Le plafond du marché fixé par le flux d'equity demeure (`macro-analysis.md` §1.5).
- (iv) Le produit relève de la gouvernance InvestEU (Commission et FEI) et non du CRR. Il n'est donc pas « prudentiel », mais il est **complémentaire par construction** grâce à la définition commune.

---

## F. Insolvabilité

### P12 — Rang des créances : une trajectoire graduée en trois niveaux, sur le modèle ciblé de la directive (UE) 2017/2399

**Résumé exécutif.** La proposition ne vise **pas** à harmoniser le rang de la venture debt face à l'ensemble des créanciers. Elle propose une trajectoire graduée :
- **Niveau 1 (immédiat, prudentiel)** : avis juridique obligatoire (P6) et **cartographie comparative** par État membre.
- **Niveau 2 (harmonisation ciblée, à explorer)**, sur le **modèle étroit et conditionnel de la directive (UE) 2017/2399**, qui a créé la dette senior non préférée dans la BRRD :
  - (a) **reconnaissance, entre les parties seulement**, des subordinations contractuelles et des accords inter-créanciers dans les distributions et dans la formation des classes des plans de restructuration ;
  - (b) une **sphère de sécurité** : un prêteur qui détient au plus 10 % du capital par des warrants accessoires n'est pas requalifié en associé-prêteur subordonné.

  Deux véhicules existent : le **réexamen de la directive 2019/1023**, dont l'art. 33 vise expressément la formation des classes [vérifié], et le **chapitre insolvabilité de la proposition EU Inc** [vérifié].
- **Niveau 3 (rang opposable à tous les créanciers)** : **non recommandé** à ce stade.

Ce volet est **politiquement plus risqué** que le volet prudentiel. Il en est **découplé** : aucune proposition prudentielle n'en dépend.

**Problème et ancrage factuel.**
- **Le rang des créances est une compétence nationale.** La directive 2019/1023 organise le *processus* mais pas le rang (`current-regulation.md` §7.2). La directive (UE) 2026/799 a **laissé le rang hors de son champ à chaque étape de 2022 à 2026** (§7.4). Ses cinq piliers ne reprennent pas le volet « transparence » de COM(2022) 702, qui en comptait sept (§7.4).
- **Hétérogénéité nationale** : privilèges publics, sûretés globales, **reconnaissance de la subordination contractuelle** en procédure collective (neutralisée partiellement dans certains droits), rang des obligataires (`current-regulation.md` §8). Sûretés sur la PI très différentes d'un État à l'autre (`micro-analysis.md` §4.2).
- **Précédent BRRD.** Le rang d'**une** catégorie a été harmonisé pour un objectif étroit (résolution, MREL/TLAC). Cet objectif systémique est **absent** ici (`current-regulation.md` §7.5).
- **Sensibilité politique.** Le volet est probablement une « ligne rouge » pour plusieurs États membres, « nettement plus dure » que le volet prudentiel (`stakeholder-map.md` §7.2, synthèse n° 5).
- **Élément ajouté par ce document [vérifié] : les règles nationales de subordination des prêts d'associés.**
  - En Allemagne, le § 39(1) n° 5 InsO **subordonne les prêts d'associés**. Le § 39(5) exempte l'associé non dirigeant qui détient **10 % au plus**.
  - Le **BGH (IX ZR 85/21, 26 janvier 2023)** a restreint ce privilège : il agrège les participations en cas de **coordination du financement** entre associés.
  - Or un prêteur de venture debt qui a exercé ses warrants, puis qui coordonne jalons et *equity cure* avec les fonds VC, s'approche précisément de ce cas de figure. Le risque ne vient pas du rang contractuel : c'est une **requalification légale** du prêt senior en créance subordonnée.
  - Des régimes comparables existeraient ailleurs [à vérifier] : en Espagne (personnes spécialement liées, seuil de participation), en Autriche (EKEG) et en Italie (art. 2467 du code civil).
  - Ce risque croise directement la **séniorité**, les **warrants** et les **covenants**.

**Mécanisme.**

**Niveau 1 : prudentiel, immédiat, sans harmonisation.**
- L'avis juridique est obligatoire pour la reconnaissance du rang contractuel (P6(5)).
- **Cartographie comparative** établie par la Commission et l'EBA, pour chaque État membre :
  - (i) reconnaissance de la subordination contractuelle et des accords inter-créanciers en procédure collective et dans les classes des plans de restructuration ;
  - (ii) seuils et conditions de requalification des prêts d'associés ;
  - (iii) opposabilité et réalisation des sûretés sur la PI ;
  - (iv) doctrines de responsabilité du prêteur (gestion de fait, soutien abusif).

  C'est une **reprise ciblée du volet « transparence »** de COM(2022) 702. Véhicules possibles : le rapport de réexamen de la directive 2019/1023 ou le portail e-Justice.

**Niveau 2 : harmonisation minimale ciblée, sur le modèle de la directive 2017/2399.**

| Élément de conception | Précédent BRRD (directive 2017/2399, art. 108 BRRD) | Transposition proposée pour la venture debt |
|---|---|---|
| Objet | Une seule catégorie de créances (senior non préférée) | Une seule catégorie d'instruments : les créances de venture debt qualifiées (définition P1, **indépendamment du type de prêteur**) |
| Effet | Rang **opposable à tous** : nouvelle strate dans la hiérarchie nationale | Effet **entre les parties uniquement** : la subordination convenue est respectée entre les créanciers qui l'ont acceptée, **sans modifier la position des tiers** (fisc, salariés, créanciers garantis hors accord). Beaucoup moins intrusif. |
| Conditions | Maturité initiale ≥ 1 an ; absence de dérivé incorporé ; référence contractuelle explicite au rang | Maturité initiale ≥ 1 an ; **kicker détachable** (équivalent de l'« absence de dérivé incorporé ») ; référence contractuelle explicite à la subordination et à l'accord inter-créanciers |
| Justification | Stabilité financière (résolvabilité) | Sécurité juridique transfrontière d'un instrument ciblé par la politique de l'Union ; cohérence avec la reconnaissance prudentielle (P6) |
| Harmonisation | Minimale, une strate | Minimale, **procédurale et inter-créanciers** |

Contenu :
- **(a) Reconnaissance inter-créanciers.** Les États membres veillent à ce que les subordinations contractuelles et les accords inter-créanciers entre créanciers d'un emprunteur VDQ soient respectés :
  - (i) dans les distributions en procédure d'insolvabilité, **entre les parties** ;
  - (ii) dans la **formation des classes** (art. 9 de la directive 2019/1023) et dans les **règles de priorité** du *cram-down* (art. 11).

  C'est une règle de **processus**. Elle s'insère naturellement dans une directive elle-même procédurale, sans toucher à la hiérarchie substantielle nationale.
- **(b) Sphère de sécurité contre la requalification.** Un prêteur qui détient, par des warrants détachables acquis en contrepartie d'un prêt qualifié, **10 % au plus** du capital ou des droits de vote, et qui ne participe pas à la gestion, n'est pas soumis à la subordination des prêts d'associés **du seul fait** de ces warrants **ou** de l'exercice de droits de covenant standards (information, consentement, contrôle des comptes, *equity cure*). Le seuil de 10 % est aligné sur le § 39(5) InsO [vérifié] et sur l'art. 89 CRR. Pour la plupart des États membres, l'harmonisation serait donc **confirmative** et viserait les cas atypiques et l'insécurité jurisprudentielle.
- **Champ fondé sur l'instrument.** C'est une exception explicite, et motivée, au périmètre « banques uniquement ». Une règle d'insolvabilité réservée aux banques créerait exactement la distorsion que `stakeholder-map.md` (synthèse n° 3) invite à éviter. De plus, le droit de l'insolvabilité s'applique aux créances, pas aux statuts des créanciers.
- **Véhicules :**
  - **(i) Réexamen de la directive 2019/1023.** L'art. 33 impose à la Commission un rapport **au plus tard le 17 juillet 2026, puis tous les cinq ans**, qui porte notamment sur « l'application des règles de formation des classes et de vote », accompagné le cas échéant d'une proposition législative [vérifié ; la publication du rapport de 2026 reste à vérifier]. Modifier les art. 9 et 11 est cohérent avec l'objet procédural de la directive.
  - **(ii) EU Inc (COM(2026) 321, 18 mars 2026).** Le règlement proposé crée une **liquidation simplifiée pour les « start-up innovantes »** EU Inc : R&D ≥ 10 % des coûts d'exploitation ou ≥ 5 % du chiffre d'affaires, moins de 100 salariés, chiffre d'affaires ≤ 10 M€, moins de 10 ans. Il prévoit une admission accélérée des créances, un sursis aux poursuites et des enchères électroniques obligatoires. Il **ne traite pas** du rang des créances et **préserve** expressément la directive 2019/1023 et le règlement insolvabilité refondu [vérifié]. Y insérer les règles (a) et (b) **pour les seules sociétés EU Inc** n'harmonise **aucun** des 27 droits nationaux, puisque le régime est optionnel : c'est la voie la **moins coûteuse politiquement**. Son champ recoupe largement VDQ-P. **Synergie supplémentaire** : les enchères électroniques de la procédure EU Inc pourraient améliorer la valeur de réalisation de la PI, troisième canal de recouvrement de `micro-analysis.md` §4.1. **Limites** : l'insertion s'écarte du caractère purement « complémentaire » voulu par la proposition ; le champ se limite aux sociétés qui optent pour EU Inc ; l'adoption est incertaine.

**Niveau 3 : non recommandé à ce stade.** Un rang de la venture debt **opposable à tous les créanciers**, sous forme d'une nouvelle strate dans chaque hiérarchie nationale, n'est pas recommandé pour quatre raisons :
- (i) le précédent BRRD reposait sur un objectif systémique **absent** ici ;
- (ii) la directive 2026/799 vient d'exclure le rang après quatre ans de négociation ;
- (iii) cela toucherait aux privilèges fiscaux et salariaux ;
- (iv) le gain marginal par rapport au niveau 2 est faible, car le prêteur de venture debt est déjà senior et sécurisé ; son problème est la **reconnaissance** de son rang, pas l'obtention d'un rang supérieur.

**Cadres connectés.** Directive 2019/1023 (art. 9, 11, 33) ; directive 2026/799 ; directive 2017/2399 (art. 108 BRRD) ; COM(2026) 321 (EU Inc) ; règlement (UE) 2015/848 (insolvabilité, refonte) ; art. 89 et 194 CRR.

**Bénéfices attendus.**
- **Micro :** une LGD senior plus prévisible ; des coûts d'avis juridiques réduits grâce à la cartographie ; un prêt transfrontière facilité ; la fin du risque de requalification lié aux warrants.
- **Macro :** une réponse partielle à la **fragmentation**, désignée comme une contrainte « plus déterminante que la pondération » (`macro-analysis.md` §5.2(4)).

**Risques et limites.**
- (i) **Risque politique élevé**, même pour le niveau 2 (`stakeholder-map.md` §7.2).
- (ii) Le découplage du volet prudentiel est **indispensable** pour ne pas le contaminer.
- (iii) La base factuelle comparative reste **qualitative** (`current-regulation.md` §8 et limite n° 3).
- (iv) Si la plupart des États membres reconnaissent déjà la subordination entre les parties, le niveau 2 aura une portée surtout confirmative. Ce peut être une force (faible coût politique) ou un argument contre son utilité.

---

## G. Cohérence internationale, véhicule et séquençage

### P13 — Cohérence bâloise, véhicule législatif, séquençage et positionnement vis-à-vis de COM(2026) 615

**Résumé exécutif.** La proposition repose sur quatre choix :
- **véhicule** : le paquet législatif du T1 2027 issu de COM(2026) 615, avec un chapitre distinct du réexamen du *specialised lending* et **articulé** avec lui (la famille (c) y est orientée) ;
- **stratégie bâloise** : **super-équivalence ou équivalence au lancement**, argument de **matérialité**, allègements conditionnés aux données, et contribution européenne aux travaux du Comité de Bâle ;
- **séquençage** en trois phases, fondé sur la **collecte de données préalable** ;
- **charge de l'EBA** réduite par la réutilisation des structures existantes.

**Problème et ancrage factuel.**
- **Aucun véhicule n'est engagé.** CP/2026/09 ne peut pas créer de catégorie (`current-regulation.md` §2.5, §9.5).
- **Codécision requise** (`stakeholder-map.md`, synthèse n° 1).
- **Agendas concurrents** de l'EBF et de l'EBA (`stakeholder-map.md`, synthèse n° 2).
- **Précédent RCAP 2014** : l'UE a été jugée « matériellement non conforme » (`stakeholder-map.md` §4, §8 ; `macro-analysis.md` §4.2).
- **Positionnement de COM(2026) 615** : start-up et scale-up citées ; partage des risques et évaluation de la PI privilégiés ; *specialised lending* réservé aux investissements stratégiques (`macro-analysis.md` §4.5). Il s'agit de la fenêtre politique, qualifiée de « plus probable, pas plus utile ».
- **Aucun précédent dans le monde** : l'UE serait pionnière (`benchmarking.md` §6).

**Mécanisme.**
1. **Véhicule.** Le paquet du T1 2027 comporterait un chapitre « financement bancaire des entreprises innovantes » regroupant P1 à P4, P6, P7 (niveau 1) et P9 (plafond). Il est **distinct du réexamen du SL** mais s'y **articule** : la famille (c) (GPU, data centres, gigafactories, flottes) est explicitement renvoyée à l'OF et au PF, et le réexamen du SL « pour investissements stratégiques » devrait couvrir ces financements d'actifs d'entreprises financées par VC. C'est le « véhicule naturel » identifié par `macro-analysis.md` §3 point 2.
2. **Positionnement vis-à-vis de COM(2026) 615 :**
   - **convergences** : partage des risques (P11), évaluation de la PI (P3, sous-facteur et rapport), renforcement des capacités (P8, orientations), mention explicite des start-up et scale-up ;
   - **écart assumé** : la Commission **n'annonce pas** de sous-catégorie de pilier 1 pour la venture debt. La proposition en ajoute une, mais en la justifiant par la **sensibilité au risque et la lisibilité**, pas par l'allègement. Elle ne heurte pas la réserve du SL aux investissements stratégiques, puisqu'elle n'en porte pas l'étiquette ;
   - **point de vigilance** : si la mesure transitoire de 65 % pour les entreprises non notées de PD ≤ 0,5 % devient permanente, elle favorisera les grandes entreprises bien notées, pas les scale-ups (`macro-analysis.md` §4.5). Le compartiment n'en dépend pas.
3. **Stratégie bâloise :**
   - **(i) Super-équivalence au lancement.** Pour VDQ-P, 130 % en approche standard contre 100 % pour un corporate non noté à Bâle, et des poids HVCRE en IRB. Pour VDQ-C, 100 % en approche standard, comme Bâle. Aucune pondération préférentielle pour maturité courte.
   - **(ii) Matérialité.** L'évaluation RCAP pèse l'impact quantitatif des écarts. Même intégralement bancarisée, la venture debt pèserait environ 0,06 % des actifs (`macro-analysis.md` §2.1). Les seuls écarts favorables (*slotting* hors SL en catégorie 2 ; éléments dormants) sont **immatériels** et **conditionnés aux données**.
   - **(iii) Précision sur les warrants (P7.2)** : elle reste dans la lettre de Bâle.
   - **(iv) Contribution au Comité de Bâle.** Proposer, une fois les données de P10 disponibles, un travail sur le « prêt aux entreprises innovantes adossé au capital-risque ». L'UE jouerait ainsi le rôle de **premier fournisseur de preuves** plutôt que de dérogataire.
4. **Séquençage :**

   | Phase | Période indicative | Contenu | Instruments |
   |---|---|---|---|
   | **0** | 2026-2027 | P8 (orientations EBA, guidance BCE) ; P10 (collecte ad hoc, protocole avec la BEI) ; P11 (produit InvestEU) ; P7.1 et P7.5 (Q&A) ; P5(4) (Q&A *forbearance*) ; P12 niveau 1 (cartographie) | Sans niveau 1 |
   | **1** | Proposition au T1 2027 ; adoption vers 2028 ; application vers 2029-2030 | P1 à P3 ; P4 (dormant) ; P5 (RTS) ; P6 ; P7.2 à P7.6 ; P9 ; clause de revoyure de P10 | Niveau 1, puis RTS (18-24 mois) |
   | **2** | À partir de 2031-2032 | Rapport de l'EBA, décision d'activation ou non de P4 | Acte délégué (précédent de l'art. 461a) |
   | **Insolvabilité** | En parallèle, découplée | P12 niveau 2 via le réexamen de la directive 2019/1023 et/ou la négociation d'EU Inc | Niveau 1, volet autonome |

5. **Charge de l'EBA.** Le RTS de *slotting* VDQ réutilise la structure du règlement 2021/598 modifié à l'issue de CP/2026/09. Les orientations de P8 s'insèrent dans EBA/GL/2020/06 au lieu de créer un nouvel instrument.
6. **Coalition probable** (à confronter à `stakeholder-map.md`) :
   - **superviseurs** : palier P durci, garde-fous, données ;
   - **Commission** : partage des risques, alignement sur COM(2026) 615 ;
   - **commission ECON du Parlement** : « flexibilité » pour les scale-ups (`stakeholder-map.md` §6) ;
   - **fonds de dette** : neutralité par P6 et P11 ;
   - **banques** : warrants, P8, P11, falaise de 50 M€ comblée à terme.

   **Point faible** : l'industrie bancaire obtient peu d'allègement de pilier 1 au lancement.

**Bénéfices attendus.** Un chemin législatif réaliste, une crédibilité prudentielle et une défense internationale préparée.

**Risques et limites.**
- (i) La bande passante du paquet 2027 est limitée : le chapitre VDQ pourrait être jugé secondaire.
- (ii) La complexité du paquet (13 propositions) exige un dossier d'impact solide (`stakeholder-map.md` §5).
- (iii) La lecture « durcissement » de VDQ-P peut être instrumentalisée contre l'ensemble.

---

## H. Synthèse

### H.1 Effets en capital indicatifs par configuration

Coût annuel du capital calculé selon `macro-analysis.md` §4.4 : environ 1,04 pb par point de pondération. Ce sont des ordres de grandeur.

| Configuration | Aujourd'hui | Lancement (phase 1) | Après activation (P4) | Avec garantie InvestEU (P11) |
|---|---|---|---|---|
| VDQ-C, approche standard, CA > 50 M€ | 100 % (104 pb) | 100 % (104 pb) | 85 % (88 pb) | 50 % de garantie : 50 % (52 pb) |
| VDQ-C, approche standard, CA ≤ 50 M€, ticket > 2,5 M€ | 85 % (88 pb) | 85 % (88 pb) | 85 % (inchangé, non cumul) | 42,5 % (44 pb) |
| VDQ-C, IRB non contraint, PD ≈ 3 % | ≈ 115 % (120 pb) | Cat. 2 : 90 % (94 pb) ; cat. 3 : 115 % (120 pb) | Cat. 1 : 70 % (73 pb) pour les meilleurs profils | substitution sur la part garantie |
| VDQ-C, IRB contraint par l'output floor | 72,5 % (75 pb) | 72,5 % (75 pb) | ≈ 61,6 % (64 pb) | substitution sur la part garantie |
| VDQ-P, approche standard, ticket ≤ 2,5 M€ | 76 % (79 pb) | **130 % (135 pb)** | 130 % (pas d'activation pour le palier P) | 70 % de garantie : **39 % (41 pb)** |
| VDQ-P, IRB, PD ≈ 10 % (sans ajustement PME) | ≈ 170 % (177 pb) | Cat. 3 : 140 % (146 pb) ; cat. 4 : 250 % (260 pb) | — | substitution sur la part garantie |
| Warrants (juste valeur ≈ 2 % du principal) | 250-400 %, qualification incertaine | 250 % sécurisé (≈ −3 pb sur l'équivalent prêt si l'on partait de 400 %) | — | 100 % via l'art. 133(5) si le programme est notifié |

**Lecture.** Au lancement, le compartiment est **quasi neutre** en capital pour le palier C, **plus exigeant** pour le palier P et **modérément favorable** pour les banques IRB sur les bons profils du palier C. Le levier de capital significatif est **budgétaire et ciblé** (P11). L'allègement de pilier 1 éventuel est **différé et conditionné aux données** (P4). La valeur ajoutée du compartiment tient à sa **sensibilité au risque**, à sa **lisibilité** (définition, reporting), à la **levée de frictions non capitalistiques** (warrants, lignes directrices sur l'effet de levier, obstacle des modèles IRB) et aux **garde-fous**. Cette conclusion est cohérente avec `macro-analysis.md` §4.4 et §5 : le capital n'est pas la ressource rare, et un compartiment n'est « ni nécessaire ni suffisant » pour combler l'écart de financement.

### H.2 Correspondance entre frictions micro et propositions

| Friction (`micro-analysis.md` §6) | Proposition(s) |
|---|---|
| 1. Définition du SL (binaire) | P1 |
| 2. Facteur PME (2,5 M€ ; 50 M€) | P2 (cumul pour le palier C), P4 (falaise de 50 M€ comblée sur données) |
| 3. Portefeuille « clientèle de détail » (1 M€) | P1(6) (primauté de la VDQ) |
| 4. Subordination (100 à 150 % ; 40 à 75 %) | P6 (pas d'allègement junior ; architecture banque-fonds) |
| 5. Warrants (400 % ou 250 %) | P7.2 |
| 6. SPPI (IFRS 9) | P1(f), P7.7 |
| 7. Art. 89 | P7.6 (conversion dette-actions) |
| 8. Guidance BCE sur l'effet de levier | P8 (substitution conditionnelle) |
| 9. Covenants de levée et d'abandon | P5 |
| 10. Falaise du *slotting* | P5 (hystérésis, dérogations), P3 (paliers) |
| 11. Pondérations préférentielles pour maturité inférieure à 2,5 ans | P3 (supprimées) |
| 12. Frontière avec la famille (c) | P1(3), P13(1) |

### H.3 Carte des synergies avec les cadres adjacents

| Cadre | Renvoi ou synergie précise | Proposition |
|---|---|---|
| AIFMD (art. 6, 42) / EuVECA / ELTIF | Définition de l'« investisseur professionnel qualifié » | P1 |
| AIFMD II (fonds de prêt) / ELTIF 2.0 | Porteurs de la tranche junior ; neutralité de la garantie | P6, P11 |
| Règlement titrisation, art. 2(1)(c) | Extension de l'exclusion SL aux VDQ découpées entre prêteurs | P6 |
| Art. 122a CRR | Gabarit du volet standard (130 / 100 / 80) | P2 |
| Art. 501 et 501a CRR | Technique du facteur ; comblement de la falaise de 50 M€ | P2, P4 |
| Art. 461a CRR | Précédent d'acte délégué fixant la date d'application | P4 |
| Art. 133(5) CRR / C(2025) 7231 | Plafond de 10 % (modèle) ; warrants à 100 % dans les programmes publics | P7, P9, P11 |
| Règlement délégué 2021/598 / EBA/CP/2026/09 | Structure du RTS ; sous-facteur « cascade de pertes » ; catégorie 4 par défaut | P3, P6 |
| EBA/GL/2020/06 ; EBA/GL/2022/03 | Véhicule du pilier 2 | P8 |
| EBA/GL/2016/07 ; EBA/GL/2018/06 | Clarification défaut et *forbearance* (*equity cure*) | P5 |
| Règlement délégué (UE) 2015/61 ; ALMM ; art. 105 CRD | Volet liquidité (leçon SVB) | P9 |
| CRD art. 133 ; EBA/GL/2020/13 | Sous-ensemble sSyRB préidentifié | P9 |
| BRRD art. 10 ; CMDI | Planification de la résolution | P9 |
| InvestEU (règlement 2021/523) ; FEI ; TechEU ; GBER art. 21 | Partage des risques ; définition commune | P11 |
| Directive 2019/1023 (art. 9, 11, 33) | Formation des classes ; véhicule du réexamen | P12 |
| Directive 2026/799 | *Pre-pack* dans le facteur juridique ; conversion dette-actions (art. 91) | P3, P7, P12 |
| Directive 2017/2399 (art. 108 BRRD) | Modèle de conception d'une harmonisation étroite | P12 |
| EU Inc (COM(2026) 321) | Définition de la start-up innovante ; liquidation simplifiée ; véhicule du rang entre les parties | P1, P12 |
| COM(2026) 615 | Véhicule législatif ; évaluation de la PI ; partage des risques | P3, P11, P13 |
| OCC 2025-45 ; EFS-VD (Singapour) | Adaptations explicites (test de runway ; pas de condition de détention locale) | P8, P11 |

### H.4 Ce que ce jeu de propositions ne fait pas, délibérément

- Il ne crée **aucune pondération standard inférieure à 100 % au lancement** (garde-fou n° 1).
- Il ne porte pas l'étiquette « *specialised lending* » et ne réécrit pas le triple test de l'art. 147(8).
- Il n'étend pas le compartiment prudentiel aux fonds AIFMD. L'asymétrie avec AIFMD II est traitée par la complémentarité (P6) et la neutralité de la garantie (P11), non par un alignement de régimes.
- Il ne propose pas d'harmonisation générale du rang des créances (P12, niveau 3 écarté).
- Il ne prétend pas combler l'écart transatlantique : celui-ci reflète d'abord l'écart d'equity (`macro-analysis.md` §1).

### H.5 Points ouverts à vérifier par les agents suivants

1. Le texte consolidé de l'art. 122a (pondérations PF 130 / 100 / 80, ADC 150), de l'art. 153(5) et de l'art. 158(6), ainsi que le statut historique de la HVCRE dans le droit de l'Union. Les rapports divergent légèrement (`current-regulation.md` §2.3 et limite n° 1 ; `micro-analysis.md` §7).
2. L'articulation de l'art. 501 avec une nouvelle sous-catégorie de la classe « entreprises », et la prise en compte des facteurs de soutien dans le calcul des RWA standard qui sert de base à l'output floor.
3. La qualification des fonds VC comme « sponsors financiers » au sens de la guidance BCE de 2017 (`macro-analysis.md` §8.7).
4. La qualification des warrants (art. 133(1)(d) ou SA-CCR) et l'application des art. 36(1)(h) et 44-46 aux fintechs (`micro-analysis.md` §5.3, §10).
5. La portée exacte des exclusions de l'art. 91 et du § 39(4) InsO.
6. La numérotation des dispositions sectorielles d'EBA/GL/2020/06.
7. La publication effective du rapport prévu par l'art. 33 de la directive 2019/1023 (échéance au 17 juillet 2026).
8. L'état de la négociation d'EU Inc et la stabilité de son chapitre insolvabilité.
9. Les régimes de requalification des prêts d'associés en Espagne, en Autriche et en Italie ; les suites de l'arrêt BGH IX ZR 85/21.
10. L'éligibilité de warrants attachés à des prêts garantis au registre de l'art. 133(5).
11. Le risque de requalification en titrisation des structures senior/junior d'une facilité unique.
12. La compatibilité de la clause d'activation par acte délégué avec l'art. 290 TFUE.
13. L'instrument successeur d'InvestEU dans le cadre financier pluriannuel 2028-2034.
14. La portée des amendements IFRS 9 de 2024 sur les rémunérations indexées sur la valeur des titres.

---

## Sources ajoutées par ce document (au-delà des cinq rapports de cadrage)

- [Directive (UE) 2019/1023 — EUR-Lex (art. 33, clause de réexamen)](https://eur-lex.europa.eu/eli/dir/2019/1023/oj/eng)
- [Freshfields — EU Inc.: the insolvency provisions of the Commission's draft 28th regime proposal](https://www.freshfields.com/en/our-thinking/blogs/transactions/eu-inc-the-insolvency-provisions-of-the-commissions-draft-28th-regime-proposal-102mq7y)
- [Commission européenne — proposition EU Inc, COM(2026) 321](https://commission.europa.eu/document/download/3e9822aa-8cef-40a1-904e-a53fc68e7265_en)
- [Commission européenne — Questions and answers on legislative programmes under the CRR (29 octobre 2025)](https://finance.ec.europa.eu/news/questions-and-answers-legislative-programmes-under-capital-requirements-regulation-2025-10-29_en)
- [Commission européenne — communication C(2025) 7231](https://ec.europa.eu/finance/docs/law/251029-communication-crr-legislative-programmes_en.pdf)
- [§ 39 InsO — gesetze-im-internet.de](https://www.gesetze-im-internet.de/inso/__39.html)
- [CMS — BGH urteilt zur Beschränkung des Kleinbeteiligtenprivilegs (IX ZR 85/21)](https://cms.law/de/deu/legal-updates/bgh-urteilt-zur-beschraenkung-des-kleinbeteiligtenprivilegs)
- [EBA — Guidelines on loan origination and monitoring (EBA/GL/2020/06)](https://www.eba.europa.eu/activities/single-rulebook/regulatory-activities/credit-risk/guidelines-loan-origination-and-monitoring)
