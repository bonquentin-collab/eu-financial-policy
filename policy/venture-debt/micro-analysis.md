# Venture debt : mécanique micro-financière et implications pour un compartiment « specialised lending » (art. 147 CRR)

*Brief micro-financier (fact base), dossier `policy/venture-debt/`. Rédigé le 22 septembre 2026. Point de vue : une banque prêteuse soumise au CRR/CRD. Il ne s'agit pas d'un fonds de dette non bancaire.*

**Légende de fiabilité**, utilisée partout dans le document :
- **[D]** : fait documenté, avec la source indiquée entre parenthèses et la liste complète des sources en fin de document.
- **[C]** : calcul de l'auteur à partir de données documentées. La méthode est donnée ; ce sont des ordres de grandeur.
- **[I]** : inférence plausible mais non vérifiée empiriquement. À traiter comme une hypothèse de travail.

---

## 0. Résumé exécutif

1. **La venture debt ne remplit aucun des trois critères de l'art. 147(8) CRR** (entité ad hoc portant des actifs physiques, contrôle substantiel du prêteur sur les actifs et leurs revenus, remboursement par les revenus des actifs financés). Elle est remboursée principalement par un **événement de financement futur** : le tour d'equity suivant, une acquisition ou une introduction en bourse. Le revenu d'un actif n'y joue presque aucun rôle. Une nouvelle sous-catégorie exige donc une **définition autonome**, fondée sur la source de remboursement (dépendance à l'investisseur, sur le modèle de la classe « investor dependent » de SVB). Étendre simplement les définitions existantes ne suffira pas. [D pour le texte, I pour la conséquence]
2. **Le prêt est beaucoup moins risqué que l'emprunteur.** Sur 1 079 emprunteurs de BDC américaines (2005-2022), 11 % ont été liquidés ou cédés en détresse, et 5 % à 24 % de plus ont été cédés sous leur dernière valorisation. Pourtant, seuls environ 4,3 % du principal par an ont été classés « à risque de perte ». Ce chiffre est un majorant ; les pertes réalisées tournent autour de 2 % du portefeuille par an (González-Uribe & Mann, 2024). [D] Trois raisons : le prêt est senior, il est court (demi-vie d'environ 2 ans), et il est remboursé à environ 100 % lors des événements de liquidité. [D]
3. **Le risque est fortement stratifié par stade et cyclique.** Dans le portefeuille SVB/First Citizens, les charges nettes (NCO) des prêts « early stage » (0 à 5 M$ de revenus) atteignent 9,63 % (4T23 annualisé) et 9,73 % (année 2024). Les prêts « growth stage » (plus de 5 M$) sont à 1,31 % et 1,50 %. La moyenne historique early stage 2008-2010 est d'environ 6 %. [D] **Aucune grille unique ne peut couvrir les deux segments.**
4. **Le régime standard (SA) actuel ne discrimine pas.** Une start-up non notée reçoit 100 %, soit environ 76 % à 85 % avec le facteur de soutien PME de l'art. 501. En SA, l'early stage est donc **sous-capitalisé** par rapport aux pertes observées en période de stress. Le growth stage est traité de façon adéquate, voire prudente. [C] Pour une banque NI, un modèle PD produit des RW de 130 % à 240 % sur l'early stage (sans ajustement PME). La banque NI est alors désavantagée face aux banques SA et aux fonds non bancaires. [C]
5. **Les warrants ont peu de poids dans le coût en capital mais soulèvent de réels problèmes de qualification.** Juste valeur initiale : 1,4 % (médiane) à 3 % (moyenne) du principal [D]. Le RW actions de l'art. 133 est de 250 % ou 400 %, avec une montée en charge jusqu'en 2030 [D]. Cela ajoute moins de 0,1 point de spread [C]. Les frictions sont ailleurs : 400 % contre 250 % (exception « relation d'affaires de long terme » ou détention d'au moins 3 ans), la qualification dérivé ou equity, le test SPPI d'IFRS 9, les AVA de valorisation prudente, et le **régime de déduction** lorsque l'emprunteur est une fintech « entité du secteur financier ». **L'art. 89 n'est pratiquement jamais déclenché** : les participations issues de warrants restent bien sous 10 % du capital. [C/I]
6. **La compensation par le warrant est inter-temporelle, pas contingente à l'état du monde.** Chez SVB, les gains nets sur warrants ont dépassé les NCO early stage de 1,1 Md$ en cumul 2002-2022 [D]. Mais les gains arrivent dans les phases hautes du cycle VC, les pertes dans les phases basses [I, cohérent avec les données SVB et Hercules]. **Une grille actuariellement saine ne doit donc pas imputer le rendement attendu des warrants en déduction de la LGD ou de l'EL.**
7. **Les covenants ne sont pas des tests de couverture de flux** : l'EBITDA est négatif et le DSCR est structurellement inférieur à 1. Ce sont des **déclencheurs de contrôle** : trésorerie minimale, performance par rapport au plan, MAC, clause d'« investor abandonment », jalons de levée. Ils peuvent provoquer des défauts auto-réalisateurs en phase basse du cycle. [D pour la typologie, I pour l'effet]
8. **Sur les 5 facteurs du slotting PF, deux se transposent bien** (solidité du sponsor, paquet de sûretés et contrôle). **Deux doivent être entièrement redéfinis** (solidité financière, où le runway remplace le DSCR ; caractéristiques de la transaction, où le risque technologique et commercial remplace le risque de construction et d'offtake). **Un se transpose partiellement** (environnement juridique, centré sur l'opposabilité des sûretés sur la PI et la procédure de pre-pack). Il manque au moins quatre dimensions : dépendance au refinancement, facteur systémique « cycle VC », concentration par sponsor et qualité de l'équipe. [I]
9. **Calibrage indicatif** [C/I] : le growth stage se situe autour de « satisfaisant » (115 %), voire « bon » (90 %). L'early stage se situe autour de « faible » (250 %) en conditions de stress. Les RW préférentiels à moins de 2,5 ans (50 % et 70 %) sont **inadaptés**, car presque toute la venture debt a une maturité effective inférieure à 2,5 ans. L'analogue le plus pertinent est la **HVCRE** de Bâle (95/120/140/250 %, corrélation 12-30 %), qui existe précisément pour les expositions dont le remboursement dépend d'une vente ou d'un refinancement futur incertain. L'UE ne l'a pas transposée.
10. **Frontière du périmètre.** Les agrégats « venture debt » de PitchBook incluent des méga-financements adossés à des actifs : GPU et data centres (Mistral AI, 830 M$ en mars 2026 ; Nscale), lignes « warehouse » de fintechs (Capital on Tap, FINN). Ces opérations relèvent déjà de l'object finance, du project finance ou de la titrisation. Elles doivent **être exclues** de la nouvelle catégorie, sous peine de contaminer les données de calibrage et d'ouvrir un arbitrage. [D pour les deals, I pour la recommandation]

---

## 1. Périmètre et définitions opérationnelles

### 1.1 Ce qu'est (et n'est pas) la venture debt

La venture debt est une **dette à terme accordée à une entreprise non profitable, soutenue par du capital-risque**, par un prêteur extérieur au syndicat VC. Elle intervient typiquement dans les 0 à 12 mois qui suivent un tour d'equity. Elle sert à **allonger le runway** (le nombre de mois de trésorerie avant épuisement) jusqu'à l'événement suivant : tour, cession, IPO, ou atteinte de la rentabilité. Les études montrent qu'elle **complète** l'equity et ne s'y substitue pas : elle n'intervient pratiquement jamais avant la Série A et rarement après la Série D (González-Uribe & Mann, 2024). [D]

Il faut distinguer quatre familles, que les statistiques de marché mélangent :

| Famille | Source principale de remboursement | Collatéral dominant | Proximité avec les catégories existantes |
|---|---|---|---|
| (a) **Venture debt « runway »** (Séries A à C, pré-revenus ou revenus faibles) | Prochain tour d'equity ou M&A | PI, comptes, nantissement général | Aucune : corporate non noté |
| (b) **Growth debt / venture growth** (revenus récurrents, ARR supérieur à environ 5-10 M€) | Tour suivant, M&A ou flux futurs | PI, créances, comptes | Aucune : corporate |
| (c) **Financements adossés à des actifs d'entreprises VC** (GPU, data centres, flottes, warehouses de créances fintech) | Revenus ou valeur des actifs financés | Actifs physiques ou créances isolés en SPV | **Object finance, project finance, titrisation** |
| (d) **Quasi-equity publique** (BEI, prêts à rémunération indexée) | Bullet à la sortie ou à maturité, kicker | Variable (sécurisée ou non) | Hybride : risque de défaillance du test SPPI |

**Recommandation de périmètre [I]** : la nouvelle sous-catégorie devrait couvrir (a) et (b), et exclure explicitement (c) (déjà couvert) et les formes subordonnées ou convertibles de (d), qui relèvent de l'art. 128 (150 %) ou de l'art. 133.

### 1.2 Pourquoi les agrégats divergent

- **Définition large (PitchBook).** Europe : 20,1 Md€ en 2025 (656 deals), contre 28,9 Md€ en 2024 (848 deals), soit −30,7 %. La venture debt représente 29 % de la valeur totale du VC européen en 2025, contre 47 % en 2024. [D] (Houlihan Lokey/PitchBook, juin 2026, données au 7 mai 2026)
- **Définition étroite (Atomico, *State of European Tech* 2025).** Environ 5,6 Md$ en 2025, un record. La venture debt pèserait historiquement 5 à 10 % du financement VC européen, contre 20 à 25 % aux États-Unis. [D]
- L'écart de un à quatre vient surtout de la famille (c). En 2025, les services financiers pèsent 4,98 Md€ (62 deals, ticket moyen d'environ 80 M€), l'essentiel étant des lignes warehouse. Les plus gros deals 2025-2026 sont des financements de GPU et de data centres, ou des financements de flotte et de créances. [D pour les chiffres, I pour l'interprétation]

**Conséquence pour le calibrage [I]** : les données de défaut d'un « marché venture debt » défini à la PitchBook sont biaisées vers le bas par les financements adossés à des actifs. Un calibrage doit s'appuyer sur des données **au niveau du prêt**, filtrées sur les familles (a) et (b).

---

## 2. Mécanique des transactions

### 2.1 Anatomie d'un prêt type

| Paramètre | Valeur typique | Fiabilité / source |
|---|---|---|
| Moment | 0 à 12 mois après un tour. Après un prêt, le tour suivant arrive en moyenne en 0,94 an (médiane 0,66 an), contre 1,4 an (médiane 1,2 an) après un tour d'equity | [D] González-Uribe & Mann (GUM) 2024, Preqin |
| Taille relative | Prêt / financement cumulé à date : moyenne 20-25 %, médiane 14-18 %. Les tours suivants font environ 5 fois le montant du prêt | [D] GUM ; UCLA Anderson Review |
| Taille absolue | US 2025 : médiane 5,5 M$, P75 27,7 M$. Échantillon BDC : médiane d'environ 3 M$. BEI : 10-40 M€ (jusqu'à 120 M€ pour les scale-ups) | [D] Runway/PitchBook 2026 ; GUM ; BEI juin 2025 |
| Tirage | Engagement ferme, tirages en 2-3 tranches **conditionnées à des jalons** (levée, jalon technique ou commercial). Période de disponibilité jusqu'à 36 mois (BEI) | [D] BEI |
| Profil | Période d'intérêts seuls de 6 à 12 mois, puis amortissement ; ou bullet (BEI, à 5-6 ans par tranche) | [D] BEI ; pratiques de marché |
| Maturité contractuelle / effective | 3 à 5 ans contractuels. **Seuls environ 11 % des prêts arrivent à maturité.** Durée résiduelle médiane au remboursement : 7 trimestres. Demi-vie d'environ 2 ans | [D] GUM |
| Prix (fonds, US) | Prime + 5 à 10 points. Rendement de portefeuille 2025 : Hercules 12,5 % (« core », 3T25) ; TriplePoint 13,7 % (année 2025) | [D] GUM ; 8-K Hercules, TPVG |
| Commissions | Frais de fin de prêt dans environ 84 % des prêts (environ 5 % du principal en moyenne) ; commissions d'engagement ; pénalités de remboursement anticipé | [D] GUM |
| Warrants | Voir §2.4 | |
| Nombre de prêteurs | En général **un seul** prêteur (contre 2 à 4 investisseurs dans un tour d'equity) | [D] GUM |

**Mécanisme central : le remboursement par l'événement de liquidité.** Le taux de remboursement trimestriel moyen est d'environ 10 %. Il bondit à 25 % au trimestre d'un événement de liquidité (tour, cession, LBO, IPO). Si l'on instrumente cet événement par la résolution d'une incertitude (brevet accordé, fin d'essai clinique), l'événement entraîne le **remboursement quasi intégral** du prêt (coefficient IV de 0,92 à 1,0). [D] (GUM, 2024) Le nouvel investisseur ou l'acquéreur veut contrôler l'entreprise sans créancier senior disposant d'un droit de veto ; il rembourse donc le prêteur en priorité.

### 2.2 Qui prête, et combien

| Segment | Acteurs | Données récentes |
|---|---|---|
| Banques spécialisées | SVB (First Citizens depuis 2023), HSBC Innovation Banking (UK), CIBC Innovation Banking, etc. | Encours « investor dependent » SVB : 6,7 Md$ fin 2022, puis 4,3 Md$ fin 2023, 3,2 Md$ fin 2024 et 2,7 Md$ au 1T26 [D]. Un **désengagement** net depuis la reprise |
| Fonds / BDC (US) | Hercules, Horizon, TriplePoint, Runway Growth, Trinity | Encours cumulé des 5 BDC : plus de 6 Md$ fin 2022 [D] |
| Fonds européens | Kreos (BlackRock), Claret, Atempo, Columbia Lake, Harbert, Bootstrap… | Pas de données agrégées publiques [D : absence] |
| Public | BEI (premier fournisseur européen), Bpifrance, KfW… | BEI : 338 opérations, 8,4 Md€ cumulés ; 1,0 Md€ en 2024 (37 entreprises) [D] |
| Grandes banques universelles (tickets « venture growth ») | BNP Paribas, Crédit Agricole CIB, Natixis, HSBC, La Banque Postale, ING, Rabobank, ABN AMRO, Nordea, SEB, DNB… | Mistral AI : 830 M$ auprès de 7 banques (mars 2026, **pour financer 13 800 GPU et un data centre**). Nscale : 790 M$ (Narvik, data centre). United Petfood : 1,4 Md€ [D]. Il s'agit surtout de la famille (c) |

**Marché US 2025** : record de 68,8 Md$ pour environ 1 000 deals, dont 12,3 Md$ de « follow-on » (156 deals, contre 4,7 Md$ en 2024). Le SaaS représente plus de 28 Md$. Les entreprises financées par dette représentent 37 % de la valeur des sorties 2025. [D] (Runway Growth/PitchBook, mai 2026) Au 1S25, l'early stage captait 34,7 % des 30,67 Md$. [D]

**Marché européen 2025** : le Royaume-Uni domine avec 34 % de la valeur et 41 % des deals, devant l'Allemagne (3,97 Md€), la Belgique (1,87 Md€) et la France (1,56 Md€, 89 deals). Sur 2023-2025, la venture growth représente 58 % de la valeur et 28 % des deals ; l'early stage VC 27 % de la valeur ; seed et pré-seed 1 %. La faillite de Northvolt, gros emprunteur en 2024, a pesé sur les volumes 2025. [D] (HL/PitchBook, juin 2026)

### 2.3 Séniorité, subordination et interaction avec les autres apporteurs

**Structure dominante : dette senior de premier rang.** Dans l'échantillon BDC, les prêts sont **toujours** en position senior sécurisée. La séniorité passe soit par un nantissement général incluant la PI, soit par un **negative pledge** sur la PI si celle-ci n'est pas nantie. Il n'y a pas de convertibles. [D] (GUM)

```
Structure de capital type d'une scale-up financée par venture debt (illustration [I])

   Créanciers privilégiés légaux (salaires, fisc, frais de procédure)  ← rang légal, variable selon l'EM
   ─────────────────────────────────────────────────────────────
   Prêteur ABL / revolver (1er rang sur créances et stocks)             ← split-lien éventuel
   Venture lender senior (1er rang sur PI, comptes, titres des filiales, reste)
   ─────────────────────────────────────────────────────────────
   Venture debt junior / mezzanine / PIK HoldCo (rare)                   ← 150 % SA (art. 128)
   ─────────────────────────────────────────────────────────────
   Actions de préférence Séries C > B > A (préférences de liquidation empilées)
   Actions ordinaires (fondateurs, BSPCE/stock-options)
```

- **Coussin d'equity.** La dette représente en médiane 14 à 18 % du financement cumulé [D]. Le coussin réel se mesure en **cash d'equity effectivement versé et non encore consommé**, pas en valorisation post-money. Une valorisation est un prix marginal, qui peut être divisé par deux lors d'un down round. [I]
- **Préférences de liquidation.** Elles n'affectent pas le rang du prêteur senior, qui passe avant toute l'equity. En revanche, elles conditionnent la **volonté des VC de soutenir** l'entreprise : un « overhang » de préférences peut rendre un tour de sauvetage inintéressant pour les VC existants. [I]
- **Venture debt junior ou subordonnée.** C'est rare. Elle vient en complément d'une dette senior bancaire (split-lien ou second lien), ou prend la forme d'une dette HoldCo PIK. En Europe, le prix du HoldCo PIK est de 10 à 17 %, souvent avec warrants ou participation au capital, et ce sont surtout des fonds qui la fournissent (Carlsquare, 2T 2026). [D] Pour une banque : RW de 150 % en SA (art. 128) et LGD F-IRB de 75 %. Voir la falaise au §6.
- **Coexistence avec ABL et revolvers.** Un **accord inter-créanciers** est nécessaire (split-lien : l'ABL garde le premier rang sur créances et stocks, le venture lender sur la PI et le reste). Le nouveau sous-facteur « **position dans la cascade de pertes** » proposé par l'EBA (CP du 7 mai 2026) est directement pertinent (§7). [D pour la CP]
- **Spécificité bancaire : la relation de dépôt.** Le modèle SVB liait le prêt à la **domiciliation des comptes opérationnels** (« primary banking relationship », contrôle des comptes). Cela sécurise la surveillance de la trésorerie, qui sert à la fois d'actif et d'indicateur. Mais cela concentre le passif sur le même facteur de risque que l'actif, ce qu'a montré le bank run de SVB en mars 2023. [D pour le run ; I pour l'implication]

### 2.4 Warrants et equity kickers

**Trois mesures à ne pas confondre** (pédagogie) :
1. La **couverture de warrants** (« warrant coverage ») : nombre d'actions × prix d'exercice, divisé par le montant du prêt. Fourchette usuelle de 2 à 10 % du prêt ; jusqu'à 20 % pour les fonds et les tickets risqués. [D] (Kruze ; pratiques de marché)
2. La **juste valeur** du warrant : c'est une option d'achat longue (souvent 7 à 10 ans) sur une action très volatile, dont la valeur vaut une fraction du notionnel. Dans les données BDC, elle représente **1,4 % du principal en médiane et 3 % en moyenne**, soit environ 2 % de la valeur du portefeuille. [D] (GUM)
3. La **participation implicite** au capital. Exemple [C] : couverture de 5 %, prêt égal à 30 % du dernier tour, tour égal à 25 % du post-money. Le notionnel des warrants vaut alors 0,375 % du post-money, soit environ **0,4 % du capital**. La fourchette typique va de 0,1 % à 1 %.

**Structuration.** Le prix d'exercice est en général le prix par action du dernier tour. Le sous-jacent est une action de préférence de la dernière série (parfois une action ordinaire). L'exercice est souvent « net » (cashless) à la sortie. Les warrants peuvent être émis au moment de l'engagement ou au prorata des tirages. [D] (Kruze) La BEI **monétise ses warrants au bout de 5 à 7 ans**, typiquement par revente à l'entreprise à la juste valeur, ce qui fonctionne comme un put. [D] (EIC Scaling Club)

**Distribution des gains : une loi de puissance.** SVB détenait fin 2022 des warrants dans **3 234 entreprises**, pour une juste valeur de 383 M$. **65 lignes (2 %) pesaient 51,9 % de la valeur** [D]. Les gains nets sur warrants ont atteint 148 M$ en 2022 (45 M$ d'exercices, 107 M$ de variations de valeur, −4 M$ d'expirations). [D] Hercules a vu son portefeuille actions et warrants passer d'environ 11 % de l'actif (2020) à environ 4 % (2025/26). [D] (Hunterbrook)

**Ce que cela implique pour une banque prêteuse :**

| Dimension | Traitement | Commentaire |
|---|---|---|
| Comptabilité (IFRS 9) | Warrant **détachable** : dérivé distinct, en juste valeur par résultat (niveau 3 IFRS 13). Le prêt est comptabilisé à la contrepartie diminuée de la juste valeur du warrant, puis au coût amorti (TIE) s'il passe le test SPPI | [D] principes IFRS 9 |
| | Kicker **incorporé** (frais de sortie indexés sur la valeur, participation aux résultats, conversion) : le **prêt entier échoue au test SPPI** et passe en juste valeur par résultat, sans bifurcation possible côté actif | [D] ; **incitation forte à structurer des warrants détachables** [I] |
| Valorisation | Actions non cotées, illiquides, avec préférences : méthodes OPM/backsolve, décotes. La juste valeur tombée à zéro **prédit la faillite** (GUM, tableau 6) | [D] ; utile comme **signal d'alerte** pour le re-slotting [I] |
| Fonds propres | Juste valeur en résultat, donc en CET1. **AVA de valorisation prudente** (art. 34 et 105 CRR) déduites du CET1 | [D pour le principe] |
| Pondération | Art. 133 : 250 % (général) ou **400 %** (« speculative unlisted equity » : revente à court terme, ou « investissements dans des entreprises de capital-risque ou similaires acquis en anticipation de plus-values significatives à court terme »). **Exception** : détention d'au moins 3 ans, ou intention approuvée par la direction, y compris « equities of corporate clients with which the institution has or intends to establish a long-term business relationship », à 250 %. Transitoire art. 495a (2026) : 130 % pour la catégorie 250 % et 160 % pour la catégorie 400 %, avant 250 % et 400 % en 2030 | [D] ; qualification des warrants **ambiguë** (§5.3) |
| Art. 89 (participations hors secteur financier) | Participation qualifiée = au moins 10 % du capital ou des droits de vote. Limites : 15 % des fonds propres éligibles par participation, 60 % au total. Au-delà : RW de 1 250 % ou interdiction | **Non déclenché** par les warrants (environ 0,1-1 % du capital). Seulement plausible après une **conversion dette-actions** dans une restructuration, et seulement pour une petite banque [C/I] |
| Emprunteur fintech | Si l'emprunteur est une « entité du secteur financier » (établissement de paiement, prêteur, etc.), les warrants pourraient relever du **régime de déduction** des participations en CET1 d'entités financières (art. 36(1)(h), 44-46, seuil de 10 % du CET1) plutôt que de l'art. 133 ou 89 | **[I] à vérifier** par l'agent réglementation. Enjeu non négligeable : le secteur financier est le premier secteur de la venture debt européenne en valeur |
| Comparaison US | Une banque nationale peut recevoir un warrant en contrepartie d'un prêt **à condition de ne pas l'exercer**, et ne peut pas conditionner le remboursement du principal à la valeur du warrant (12 CFR 7.1006) | [D] ; le traitement européen est plus permissif sur l'activité, plus exigeant sur le capital |

### 2.5 Covenants : une logique de contrôle, pas de couverture

**Pourquoi les covenants classiques ne fonctionnent pas** [D/I] : avec un EBITDA négatif, le ratio dette/EBITDA n'a pas de sens. Le DSCR est **inférieur à 1 par construction**, puisque le service de la dette est payé avec le cash levé en equity. L'ICR est négatif. Les covenants servent à **donner au prêteur une option de sortie ou de contrôle** au moment où l'information arrive. C'est exactement le « droit de veto sur la continuation » du modèle de GUM : le prêteur prête à hauteur de la valeur des actifs en place et bloque la poursuite de l'activité tant qu'il n'est pas remboursé. [D]

| Covenant / clause | Mécanique | Fonction économique | Risque induit |
|---|---|---|---|
| **Trésorerie minimale / runway** | Cash au moins égal à X mois de burn (souvent 3 à 6 mois), ou montant fixe ; parfois « springing » (actif seulement si les revenus fléchissent) | Équivalent fonctionnel d'un **compte de réserve (DSRA)** en PF | Falaise : bris, puis accélération, alors que le cash est justement bas [I] |
| **Performance par rapport au plan** | Revenus ou ARR au moins égaux à un pourcentage du plan, testés trimestriellement | Proxy du « product-market fit » | Incite à des plans prudents ; renégociation fréquente [I] |
| **MAC** (material adverse change) | Défaut discrétionnaire en cas de dégradation matérielle | Option de sortie non contractualisée ex ante | Contentieux ; déclenchement pro-cyclique [I] |
| **Investor abandonment** | Défaut si les investisseurs signifient qu'ils ne financeront plus | Transforme le **soutien réputationnel** du VC en déclencheur contractuel | **Défaut auto-réalisateur** : le signal d'abandon précipite la faillite [I] |
| **Jalons de levée (« equity milestones »)** | Tranche B conditionnée à une levée d'au moins X € avant une date T ; sinon amortissement accéléré, cash collatéral ou défaut | Assure que le prêt reste une passerelle vers l'equity | Aligne le calendrier de la dette sur celui du marché VC, d'où la corrélation [I] |
| **Equity cure** | Les VC injectent de l'equity pour remédier à un bris | Formalise le soutien du sponsor | Dépend des réserves du fonds VC [I] |
| **Cross-default, changement de contrôle, negative pledge sur la PI, reporting mensuel** | Standards | Information et priorité | |

---

## 3. Profil de risque des emprunteurs et du prêt

### 3.1 Distribution bimodale côté emprunteur, beaucoup plus resserrée côté prêt

- **Emprunteurs** (1 079 BDC, 2005-2022) : 629 toujours actifs fin 2022 ; **118 (11 %) liquidés ou cédés en détresse** ; 56 cédés sous leur dernière valorisation ; 203 cédés à un prix inconnu ; 73 cédés au-dessus. [D] (GUM) La valeur de l'entreprise est une option sur un succès futur. Le résultat est binaire : forte création de valeur ou disparition.
- **Prêts** : le principal classé « à risque de perte » représente environ 4,3 % par an, un **majorant** puisque des recouvrements ultérieurs ne sont pas capturés. Les pertes réalisées publiées sont d'environ 100 M$ par an, soit environ 2 % du portefeuille. [D] (GUM)
- **Pourquoi l'écart** : (i) la faillite survient souvent **après** le remboursement du prêt, grâce à la demi-vie courte ; (ii) le principal restant dû au moment de la faillite est faible, du fait de l'amortissement ; (iii) la séniorité donne le premier rang sur la valeur résiduelle (PI, équipe cédée en acqui-hire). [D pour les faits ; I pour la décomposition]

### 3.2 Données de perte disponibles (tableau de référence pour le calibrage)

| Source | Segment | Indicateur | Valeur | Fiabilité |
|---|---|---|---|---|
| SVB (Q4 2022) | Early stage investor dependent | NCO moyen 2008-2010 | ~6 % | [D] |
| First Citizens (4T23) | Early stage / growth stage | Ratio NCO (4T23, annualisé) | **9,63 % / 1,31 %** | [D] |
| First Citizens (fin 2024) | Early / growth | NCO année 2024 | **9,73 % / 1,50 %** | [D] |
| id. | Early / growth | Non-accrual / encours | 4,19 % / 2,07 % | [D] |
| id. | Early / growth | Prêts « criticized » / encours | **30,61 % / 18,54 %** | [D] |
| id. | Early / growth | Provision (ACL, CECL durée de vie) | 8,71 % / 4,91 % | [D] |
| SVB (fin 2022) | Early / growth | ACL | 5,05 % / 3,68 % | [D] |
| SVB (2002-2022) | Warrants moins NCO early stage | Cumul net | **+1,1 Md$** | [D] |
| Hercules (2004-1T25) | Portefeuille total | Pertes nettes réalisées cumulées, **nettes des gains sur equity** | −76,8 M$ ; environ 3 pb annualisés sur environ 21,6 Md$ d'engagements | [D] ; méthodologie contestée |
| Hunterbrook (fév. 2026) | Hercules, hors gains equity | Pertes réalisées cumulées à fin 3T25 | −134,7 M$ | [D], source journalistique |
| Horizon (30/09/2025) | 39 prêts, 560,2 M$ de juste valeur | Non-accrual | 4 prêts, coût 61,3 M$, JV 29,3 M$ (5,2 % du portefeuille) ; **JV/coût ≈ 48 %** | [D] |
| Moody's PF (1983-2014) | *Comparaison* project finance | Défaut cumulé à 10 ans / recouvrement moyen | 6,4 % / 79,3 % | [D] |

**Lecture [C/I]** :
- En supposant une LGD de 50 à 60 %, un NCO de 9,7 % correspond à une **PD annuelle en stress d'environ 16-19 %** pour l'early stage, et d'environ 2,5-3 % pour le growth stage. La PD « à travers le cycle » est plus basse mais **inconnue publiquement**.
- Le ratio JV/coût des prêts en non-accrual de Horizon (≈ 48 %) donne un **proxy de LGD de marché d'environ 50 %** sur des prêts déjà en difficulté.
- Contraste avec le PF : le PF perd rarement, et récupère environ 80 % quand il perd. La venture debt early stage connaît des années de perte à près de 10 %, concentrées sur le cycle.

### 3.3 Grilles internes des prêteurs : des « slotting » privés existent déjà

Les BDC notent chaque prêt sur une échelle ordinale. **Tout nouveau prêt démarre en catégorie 2** (« conforme aux attentes »), puis migre selon la performance et le financement :

| Prêteur (date) | Grade 1 | Grade 2 | Grade 3 | Grade 4 | Grade 5 |
|---|---|---|---|---|---|
| **Hercules** (31/12/2024, % JV) [C à partir de D] | 18,7 % (654,5 M$) | 47,3 % (1 650 M$) | **28,9 %** (1 010 M$) | 4,6 % (159,4 M$) | 0,5 % (18,2 M$) |
| **TriplePoint** (31/12/2025) [D] | Clear 7,0 % | White 75,1 % | Yellow 13,4 % | Orange 3,9 % | Red 0,6 % |

Définitions Hercules [D] : grade 3, « performance possiblement inférieure aux attentes, risque accru matériellement » ; grade 4, perte partielle possible. **Leçon pour le régulateur [I]** : les praticiens ne partent pas des ratios financiers mais de la **performance par rapport au plan et au financement**. Environ 17 à 34 % du portefeuille se trouve en grade 3 ou pire, même hors crise. Une grille réglementaire doit donc prévoir des **migrations fréquentes** et des critères de dégradation clairs.

### 3.4 Corrélation : le facteur systémique est le cycle VC

- Les défauts se concentrent sur les phases de contraction du VC : 2001-2002, 2008-2010, 2022-2024. [D pour SVB 2008-2010 et 2023-2024]
- SVB a elle-même réduit l'early stage de 30 % de ses prêts en 2000 à 11 % en 2009, puis 3 % en 2022. [D, présentations SVB relayées par la recherche ; à confirmer]
- **Mécanisme [I]** : la source de remboursement (le tour suivant) dépend de la liquidité du marché VC, qui est **commune à tous les emprunteurs**. Les covenants de jalons de levée transmettent directement ce facteur au risque de défaut.
- **Quantification [C]** : avec une PD moyenne de 5 % et une corrélation R = 0,12, la PD conditionnelle au 95e centile vaut environ 12,6 %. C'est compatible avec les environ 16-19 % de PD en stress inférés ci-dessus seulement si la PD à travers le cycle est d'environ 6-8 % ou si R dépasse 0,12. **Les données publiques ne permettent pas d'estimer R de façon robuste.** C'est une question ouverte, mais qui justifie une **analogie avec la HVCRE** (corrélation de 12 à 30 %).
- **Les warrants ne couvrent pas les pertes** : leur valeur et le risque de défaut dépendent du même facteur (valorisations VC). Les gains de warrants se matérialisent dans les booms (sorties M&A et IPO), les pertes de crédit dans les busts. La compensation constatée chez SVB (+1,1 Md$ sur 20 ans) est **inter-temporelle**. [I, cohérent avec la chute des warrants Hercules de 11 % à 4 % de l'actif pendant la phase basse]

---

## 4. LGD et dynamique de recouvrement en cas d'insolvabilité

### 4.1 Canaux de recouvrement, par ordre d'importance [I, cohérent avec GUM et Hochberg et al.]

1. **Remboursement par un tour de sauvetage** (insider round) ou par un tour « flat/down » : c'est le cas le plus fréquent. Le prêteur senior est remboursé ou le prêt est restructuré avec une extension et un paiement PIK.
2. **Cession en continuité (distressed M&A, acqui-hire)** : l'acquéreur paie pour la PI, l'équipe et les clients. **La mainlevée des sûretés du prêteur est une condition de la vente**, ce qui donne au prêteur un pouvoir de négociation.
3. **Vente de la PI en liquidation** : la valeur dépend de la **redéployabilité** des brevets. La liquidité du marché secondaire des brevets accroît l'offre de prêt, surtout pour les brevets redéployables (Hochberg, Serrano & Ziedonis, JFE 2018). [D] Le code, les secrets d'affaires et surtout l'équipe **ne sont pas nantissables** et perdent l'essentiel de leur valeur en liquidation.
4. **Warrants** : ils valent zéro en cas d'échec et ne contribuent pas au recouvrement dans l'état de défaut.

### 4.2 Spécificités juridiques européennes (à approfondir par l'agent réglementation) [I sauf mention]

- **Sûretés** : nantissements de brevets et de marques inscrits (INPI, EUIPO, et le brevet unitaire), nantissement de logiciels (en France), nantissements de comptes et de titres de filiales, nantissement de fonds de commerce (FR), floating charge (UK), cessions globales et transferts à titre de garantie (DE). **L'hétérogénéité nationale** rend l'opposabilité et la réalisation plus incertaines qu'avec la « blanket lien » américaine.
- **Rang en procédure** : super-privilèges salariaux, frais de procédure et créances postérieures peuvent primer ou diluer la sûreté selon l'État membre. Dans une restructuration préventive (directive 2019/1023), le **cram-down inter-classes** et le « best-interest test » encadrent les décotes imposées au créancier sécurisé.
- **Directive (UE) 2026/799 sur l'harmonisation de certains aspects du droit de l'insolvabilité** : adoptée (PE 10/03/2026, Conseil 30/03/2026, JO du 01/04/2026), transposition sous environ 2 ans et 9 mois, donc vers fin 2028. [D] Elle crée une **procédure de pre-pack** (phase de préparation sous un contrôleur, « best-interest-of-creditors test », transfert des contrats essentiels), une **obligation de déposer le bilan dans les 3 mois**, et des **périodes suspectes** harmonisées (préférences 3 mois, actes à titre gratuit ou déséquilibrés 12 mois, fraude 2 ans). [D] **Implication micro [I]** : le pre-pack devrait améliorer le recouvrement du venture lender (vente en continuité plus rapide, préservation de l'équipe et des contrats). Mais les **périodes suspectes** exposent les remboursements et sûretés consentis juste avant l'insolvabilité, ce qui est fréquent quand un tour échoue.

### 4.3 LGD : ce que disent les données et ce que dit le CRR

- **Données** : un proxy de LGD de marché d'environ 50 % sur les prêts en difficulté (Horizon) ; un recouvrement significatif après passage en perte (GUM, anecdotique) ; SVB publie des **NCO**, c'est-à-dire des pertes nettes de recouvrements, sans LGD séparée. [D]
- **F-IRB (CRR3)** : 40 % pour le senior non sécurisé corporate non financier, 75 % pour le subordonné. **La PI n'est pas une sûreté éligible** en F-IRB : le senior « sécurisé par la PI » est donc traité comme non sécurisé à 40 %. [D pour les valeurs ; I pour l'application]
- **Évaluation [I]** : 40 % est probablement **optimiste pour l'early stage** (actifs incorporels non redéployables, équipe non nantissable) et **plausible pour le growth stage** (ARR cessible, clients, base installée). Une grille dédiée devrait différencier la LGD, ou le facteur « sûretés », par stade.
- **Ne pas compenser par les warrants** : le rendement attendu des warrants rémunère le risque ex ante, par le prix. Il ne réduit pas la perte dans l'état de défaut (§3.4). Toute formule de type « LGD nette de l'upside » serait **actuariellement fausse** au quantile de 99,9 %. [I]

---

## 5. Incitations sous le régime actuel (CRR3), au niveau de la banque

### 5.1 Approche standard : une pondération plate et non discriminante

| Situation | RW SA | Base |
|---|---|---|
| Start-up non notée, exposition ≤ 2,5 M€, CA < 50 M€ | 100 % × 0,7619 ≈ **76 %** | Art. 122 et art. 501 [D] |
| Même cas, exposition > 2,5 M€ (partie excédentaire) | 100 % × 0,85 = **85 %** | Art. 501 [D] |
| Exposition PME ≤ 1 M€ en portefeuille retail | 75 % (× facteur PME) | Art. 123 [D] |
| Venture debt **subordonnée** | **150 %** | Art. 128 [D] |
| Warrant ou action détenue | 250 % ou 400 % (transitoire 2026 : 130 % ou 160 %) | Art. 133 et 495a [D] |

**Test de suffisance [C]** : en SA, le capital de pilier 1 d'une exposition early stage vaut 8 % × 76 % ≈ **6,1 %**. Or l'early stage de SVB a perdu environ 9,6 à 9,7 % par an (4T23 annualisé, puis 2024). L'EL de l'année et au-delà doit être absorbée par les provisions et la marge, mais **le coussin SA est dépassé par une seule année de stress**. À l'inverse, le growth stage (NCO de 1,3 à 1,5 %) est confortablement couvert par 6,1 à 6,8 % de capital.

**Incitations [I]** :
- **Sélection adverse vers l'early stage en SA** : à capital égal, le spread plus élevé de l'early stage rend ce segment attractif **au regard du capital réglementaire**, alors qu'il est sous-capitalisé économiquement.
- **Arbitrage de taille** : le facteur PME passe de 0,7619 à 0,85 au-delà de 2,5 M€. Le fractionnement des tickets et des tranches peut s'expliquer en partie par cette règle.

### 5.2 Approche NI : de fortes pondérations et un problème de données

**RW NI corporate** (formule ASRF, M = 2,5, sans facteur 1,06, sans ajustement PME) [C] :

| PD | 1 % | 2 % | 3 % | 5 % | 10 % | 20 % |
|---|---|---|---|---|---|---|
| LGD 40 % (F-IRB senior) | 82 % | 102 % | 114 % | 133 % | 172 % | 212 % |
| LGD 45 % | 92 % | 115 % | 128 % | 150 % | 193 % | 238 % |
| LGD 60 % (hypothèse early stage [I]) | 123 % | 153 % | 171 % | 200 % | 257 % | 318 % |
| LGD 40 %, **ajustement taille PME (CA ≤ 5 M€) et facteur PME ×0,7619** | — | — | ≈ 66 % | — | ≈ 99 % | ≈ 128 % |

**Lecture [C/I]** :
- Avec un modèle PD réaliste, une banque NI pondère le growth stage (PD d'environ 2 à 3 %) à environ 100-130 %, et l'early stage (PD d'environ 10 à 20 %) à environ 170-240 %. C'est **deux à trois fois plus** qu'une banque SA sur le même prêt.
- **Paradoxe** : l'ajustement taille PME et le facteur PME ramènent l'early stage à environ 99-128 %. La formule corporate « PME » est donc **plus clémente** justement là où les emprunteurs sont les plus petits et les plus risqués.
- **Plancher de sortie (output floor)** : 72,5 % du SA à terme (55 % en 2026). Il ne mord pas ici, puisque le SA est plus bas. Il n'y a **pas de protection** contre le « sous-capital » SA ; le problème est inverse.
- **Données** : un portefeuille de quelques centaines de prêts, avec une forte migration et peu de défauts par millésime, est **difficile à valider** comme modèle PD NI. D'où la permanent partial use du SA ou l'abstention. **C'est l'argument le plus solide en faveur d'un slotting**, qui ne demande pas d'estimation de PD. [I]

**Coût en spread du capital [C]** : si l'on retient des fonds propres à 10 % des RWA, rémunérés à 12 % contre 3 % pour la dette, le spread nécessaire vaut environ **RW × 0,9 point**. Cela donne 0,7 point à 76 %, 1,0 point à 115 %, et 2,3 points à 250 %. Les warrants (JV de 2 %, RW de 400 %) ajoutent environ 0,07 point. **Les écarts de RW se traduisent par 0,5 à 2 points de spread.** C'est significatif pour une banque, mais inférieur aux 5 à 10 points de marge des BDC. Le RW n'est donc **pas le seul verrou** : la capacité d'analyse, l'EL et les contraintes prudentielles qualitatives (§5.4) comptent autant. [I]

### 5.3 Warrants : falaises et ambiguïtés de qualification

- **400 % contre 250 %** : la lettre de l'art. 133(4)(b) vise les « investments in **venture capital firms** or similar investments » acquis en anticipation de « **short-term** capital gains ». Un warrant reçu en rémunération d'un prêt à une entreprise cliente, détenu 5 à 10 ans, relève plutôt de l'**exception « relation d'affaires de long terme »** (250 %), à condition de documenter une intention de détention d'au moins 3 ans. [D pour le texte ; I pour la qualification] **Il y a une insécurité juridique** : la monétisation rapide (revente à l'entreprise ou à un tiers en moins de 3 ans) peut basculer à 400 %. D'où une **incitation à conserver** les warrants, qui s'oppose à la gestion active de la liquidité.
- **Dérivé ou equity** : un warrant est juridiquement un dérivé de gré à gré (option d'achat). L'art. 133(1)(d) inclut les « derivatives … structured in such a way that the economic substance is similar » à l'equity. Le traitement pertinent semble donc être celui de l'**exposition actions**, en portefeuille bancaire : les actions non cotées sont en principe exclues du portefeuille de négociation. Une lecture concurrente (risque de contrepartie via SA-CCR, puis RW de l'émetteur) n'est pas exclue. **Aucune Q&A EBA spécifique n'a été trouvée.** [I, à trancher par l'agent réglementation]
- **Conversion dette-actions** (restructuration) : art. 133(1)(e), 250 %. Si la participation atteint 10 % ou plus, elle devient qualifiée au sens de l'art. 89, avec les seuils de 15 % et 60 % des fonds propres éligibles. Les exclusions de l'art. 91 (opérations d'assistance financière, prises ferme de 5 jours au plus, titres non immobilisés) ne couvrent pas clairement ce cas. [D pour le texte ; I pour l'application]

### 5.4 Frictions prudentielles qualitatives (souvent sous-estimées)

- **Guidance BCE sur les opérations à effet de levier (2017)** : est « leveraged » toute exposition dont la dette totale dépasse 4 fois l'EBITDA **ou** dont l'emprunteur est détenu à plus de 50 % par un ou plusieurs « financial sponsors ». Les PME sont exclues **sauf si elles sont détenues par des sponsors**. **Le specialised lending est exclu.** [D] Une start-up de Série B ou C, détenue majoritairement par des fonds VC et à EBITDA négatif, **tombe vraisemblablement dans le périmètre**, et sans ratio de levier calculable. Il faudrait des exceptions documentées, une validation par l'appétit au risque, et accepter un risque de P2R en SREP pour les banques du MSU. [I sur la qualification des VC en « financial sponsors », à vérifier] **Effet de bord d'une nouvelle catégorie SL** : elle **sortirait mécaniquement** la venture debt du champ de la guidance. C'est un bénéfice, mais aussi une **porte d'arbitrage** si la frontière de la catégorie est floue.
- **Grands risques et clients liés** : plusieurs sociétés en portefeuille contrôlées par un même fonds peuvent former un **groupe de clients liés**. Le plus souvent, les VC détiennent des minorités, et le contrôle comme la dépendance économique sont incertains. [I] Le vrai risque de concentration porte sur le **sponsor** (quelques fonds leaders) et sur le **millésime**, sans être capturé par les règles de grands risques. [I]
- **Liquidité (LCR)** : les dépôts d'un écosystème VC sont corrélés et volatils (SVB, mars 2023). Les prêts « liés » à la domiciliation créent une **corrélation actif-passif** que le traitement transaction par transaction ne capture pas. [D pour SVB ; I pour l'implication]

### 5.5 Concurrence non bancaire : où l'activité se loge

Les BDC et les FIA octroyant des prêts (AIFMD II) ne sont pas soumis aux RWA. Ils subissent d'autres contraintes : levier plafonné, rétention, concentration. Les BDC ont traversé 2023 sans rupture ; leurs cours sont peu corrélés à celui de SVB après ajustement de marché. [D] (GUM) **Implication [I]** : aux États-Unis, l'activité a migré vers les fonds et la banque SVB/First Citizens a réduit son exposition de 60 % entre 2022 et le 1T26. En Europe, la BEI reste le premier fournisseur. Les banques universelles se concentrent sur les **tickets venture growth adossés à des actifs** (famille c), plus proches de leurs métiers et de leurs traitements existants (OF, PF).

---

## 6. Points de friction et effets de falaise (synthèse)

| # | Falaise / friction | Seuil | Effet comportemental | Fiabilité |
|---|---|---|---|---|
| 1 | **Définition du SL** (art. 147(8) : actifs physiques, SPV, revenus de l'actif) | Binaire | La venture debt tombe dans le corporate général ; aucune reconnaissance des structures de contrôle (covenants, comptes, jalons) | [D] |
| 2 | **Facteur PME** | Exposition 2,5 M€ ; CA 50 M€ | 76 %, puis 85 %, puis 100 % : incitation au fractionnement ; perte du facteur quand une scale-up passe 50 M€ de CA, alors qu'elle devient moins risquée | [D/I] |
| 3 | **Portefeuille retail** | 1 M€ | 75 % sous le seuil | [D] |
| 4 | **Subordination** | Senior ou junior | SA de 100 % à 150 % ; LGD F-IRB de 40 % à 75 % | [D] |
| 5 | **Warrant : 400 % contre 250 %** | Détention de 3 ans ou « relation de long terme » | Incitation à conserver et à documenter l'intention ; frein à la monétisation | [D/I] |
| 6 | **SPPI (IFRS 9)** | Kicker détachable ou incorporé | Coût amorti contre juste valeur par résultat pour tout le prêt : structuration forcée en warrants détachables | [D/I] |
| 7 | **Art. 89** | 10 % du capital (qualifiée), puis 15 % et 60 % des fonds propres éligibles | Quasi jamais atteint, sauf conversion dette-actions ou petite banque spécialisée | [C/I] |
| 8 | **Guidance levier BCE** | Détention par des sponsors à plus de 50 % | Frein qualitatif pour les banques MSU ; disparaît si le SL est reconnu | [D/I] |
| 9 | **Covenants de levée et d'abandon** | Date du jalon, signal VC | Défaut auto-réalisateur, pro-cyclique | [I] |
| 10 | **Slotting transposé tel quel** | « Satisfaisant » (115 %) contre « faible » (250 %) | Quand le runway tombe sous environ 6-9 mois sans term sheet, le RW **double** d'un coup : falaise pro-cyclique au pire moment | [I] |
| 11 | **RW préférentiels à moins de 2,5 ans** (50 % et 70 %) | Maturité résiduelle | Presque toute la venture debt serait éligible (maturité effective d'environ 2 ans) : sous-pondération systématique | [C/I] |
| 12 | **Frontière avec la famille (c)** | Qualification OF/PF/titrisation | Arbitrage de classement dans la catégorie la moins chère ; données de calibrage biaisées | [I] |

---

## 7. Transposabilité des 5 facteurs du slotting PF à la venture debt

*Rappel* : Bâle (CRE33) compte 5 classes de SL (PF, OF, CF, IPRE, **HVCRE**). **L'UE n'en retient que 4** (art. 147(8) : PF, OF, CF, IPRE), sans HVCRE. [D] En slotting, les RW sont de 70/90/115/250/0 % (50/70 % pour les catégories « strong » et « good » à moins de 2,5 ans), et les EL de 0,4/0,8/2,8/8/50 % (art. 153(5) et 158(6) CRR). Pour la HVCRE, Bâle retient 95/120/140/250 % (préférentiels 70/95 %). Le règlement délégué (UE) 2021/598 impose des poids de facteurs compris entre 5 et 60 %. La CP EBA du 7 mai 2026 (clôture le 7 août 2026) propose notamment : suppression possible du plancher de 5 % pour un facteur non discriminant, nouveau sous-facteur « position dans la cascade de pertes », catégorie 4 résiduelle (données manquantes à 250 %), DSCR comme ratio unique, et intégration de l'ESG. [D] Les équivalences de notation indicatives du slotting bâlois sont : « strong » BBB- ou mieux, « good » BB+/BB, « satisfactory » BB-/B+, « weak » B à C-. [D, annexe CRE33, à confirmer]

| Facteur PF | Sous-facteurs PF | Transposabilité | Ce qui échoue | Substitut venture proposé [I] |
|---|---|---|---|---|
| **1. Solidité financière** | Conditions de marché ; ratios (DSCR, LLCR, PLCR, D/E) ; stress ; structure financière (durée du prêt contre durée de vie, amortissement) | **Faible** : à redéfinir | DSCR < 1 par construction ; pas de durée de vie d'actif ; le stress « flux » n'a pas de sens | **Runway** post-financement (cash + tranches inconditionnelles) / burn net ; **LTER** = prêt / cash d'equity levé sur 24 mois ; pour le growth : **dette / ARR**, marge brute, rétention nette (NRR), « burn multiple » ; **stress** : survie jusqu'à maturité ou amortissement **sans nouveau tour** pendant 12 à 18 mois ; **adéquation** entre période d'intérêts seuls, runway et date du jalon de levée |
| **2. Environnement politique et juridique** | Risque politique, force majeure, soutien public, stabilité réglementaire, permis, opposabilité des contrats | **Partielle** | Le risque pays compte peu ; le risque juridique porte sur la **PI** | Opposabilité et inscription des sûretés sur la PI ; **lieu de détention de la PI** (fuite vers une maison-mère hors UE) ; régime d'insolvabilité (pre-pack disponible, rang des super-privilèges) ; risque réglementaire sectoriel (autorisation de mise sur le marché en biotech, contrôle export pour le dual-use) |
| **3. Caractéristiques de la transaction ou de l'actif** | Risque de design et de technologie, de construction (garanties d'achèvement), d'exploitation (O&M), d'offtake, d'approvisionnement | **Faible à partielle** | Il n'y a ni contrat d'offtake ni garantie d'achèvement ; le risque est **commercial et technologique** | Stade (TRL, phase clinique) ; traction (croissance, cohortes, concentration clients) ; **risque homme-clé et équipe fondatrice** ; efficience du burn ; redéployabilité de la PI (brevets accordés, familles, liberté d'exploitation) |
| **4. Solidité du sponsor** | Historique ; solidité financière ; soutien (stratégique, apport d'equity, incitation à réinjecter) | **Forte** : facteur central | Le soutien VC est **réputationnel, non contractuel**, sans garantie d'achèvement | Qualité et historique des lead investors ; **réserves allouées** à l'entreprise et « dry powder » du fonds ; **âge du fonds** (fin de période d'investissement, pression de sortie) ; largeur du syndicat ; historique de soutien (insider rounds, equity cure) ; co-investisseurs publics (EIC Fund, Bpifrance) ; down rounds passés |
| **5. Paquet de sûretés** | Cession des contrats et comptes ; nantissement des actifs ; contrôle des flux (sweeps, comptes séquestres) ; covenants ; fonds de réserve | **Forte** | Les réserves sont financées par l'equity, pas par les flux | Premier rang sur tous les actifs y compris la PI ; **contrôle des comptes** ; negative pledge ; nantissement des titres des filiales ; covenants de trésorerie minimale, MAC, investor abandonment, reporting mensuel ; **position dans la cascade** face à l'ABL ou au RCF (sous-facteur EBA 2026) ; tirages conditionnés à des jalons |

**Dimensions absentes du slotting PF et essentielles ici [I]** :
1. **Dépendance au refinancement par l'equity**, c'est-à-dire la source même de remboursement. C'est l'équivalent du « refinancement incertain » qui a justifié la HVCRE.
2. **Facteur systémique du cycle VC**, par millésime : il devrait jouer au niveau de la calibration (corrélation) et du portefeuille (pilier 2), pas prêt par prêt.
3. **Concentration par sponsor** : une part excessive du portefeuille adossée aux mêmes fonds VC.
4. **Qualité de l'équipe** : le premier critère des VC, que la venture debt « emprunte » via la certification VC (Hochberg et al. ; de Rassenfosse & Fischer 2016). [D pour la certification]

---

## 8. Ce qu'une grille ou une fonction de pondération sur mesure devrait capturer

### 8.1 Architecture recommandée [I]

1. **Définition par la source de remboursement** : « exposition à une entreprise non profitable, financée par des investisseurs professionnels en capital-risque, dont la source principale de remboursement est un financement en fonds propres futur ou une cession ». La définition exclut explicitement ce qui relève de l'OF, du PF, de l'IPRE ou de la titrisation.
2. **Critères d'éligibilité** (conditions d'entrée, faute de quoi le traitement corporate s'applique) : tour d'equity mené par un investisseur professionnel réglementé (FIA agréé, EuVECA, véhicule public) dans les 12 à 18 derniers mois ; **LTER plafonné** (par exemple au plus 35-50 %, à calibrer) ; séniorité de premier rang ; covenant de trésorerie minimale ; reporting mensuel.
3. **Deux sous-classes par stade**, reprenant la frontière opérationnelle de SVB : **early stage** (revenus de 0 à 5 M€ environ) et **growth** (revenus récurrents au-delà). Les distributions de perte sont trop différentes pour une grille unique (NCO de 9,7 % contre 1,5 %).
4. **Double volet SA / NI** : le slotting ne concerne que les banques NI. Il faut **aussi** un traitement SA sur le modèle de l'art. 122a (deux ou trois RW plats). Sinon, la majorité des petites et moyennes banques garde un traitement à 76-85 % non discriminant. La nouvelle catégorie deviendrait alors **plus coûteuse pour les banques NI** qui l'adopteraient que le statu quo SA, et ne serait pas utilisée.

### 8.2 Ancres de calibrage (indicatives) [C/I]

| Sous-classe | PD en stress inférée | LGD | RW NI équivalent (M = 2,5) | Catégorie de slotting « naturelle » | Remarque |
|---|---|---|---|---|---|
| Growth (revenus > 5 M€) | 2,5-3 % | 40-45 % | ≈ 110-130 % | **Satisfaisant (115 %)**, avec un meilleur quart à **Bon (90 %)** | EL observée (NCO 1,3-1,5 %) comprise entre l'EL « good » (0,8 %) et l'EL « satisfactory » (2,8 %) |
| Early stage (revenus < 5 M€) | 10-19 % | 45-60 % | ≈ 190-320 % | **Faible (250 %)** en tendance ; satisfaisant seulement pour les meilleurs profils (runway long, sponsors de premier rang) | NCO de stress (9,7 %) **supérieure** à l'EL « weak » (8 %) |
| Toutes | — | — | — | **Pas de RW préférentiel à moins de 2,5 ans** | La maturité effective est structurellement courte |

**Option alternative** : reprendre les **poids HVCRE** (95/120/140/250 %) et la **corrélation HVCRE** (12-30 %) pour la sous-classe early stage. Cela reflète explicitement le risque de refinancement et la corrélation au cycle. L'analogie économique est directe : un remboursement dépendant d'une vente ou d'un refinancement futur incertain. [I]

### 8.3 Exigences de conception pour une grille actuariellement solide [I]

1. **Le runway comme variable pivot**, mais **lissée** : pour éviter la falaise « satisfaisant » vers « faible » au pire moment, il faut une hystérésis (migration après deux trimestres consécutifs) ou une catégorie intermédiaire. La catégorie « faible » devient automatique si le runway est inférieur à 6 mois sans term sheet signé : c'est une dérogation forcée (override).
2. **Aucune imputation des warrants en réduction de l'EL ou de la LGD** du prêt. Les warrants restent traités séparément au titre de l'art. 133, idéalement avec une **clarification** : warrants reçus comme rémunération d'un prêt à un client à 250 %, et non 400 %.
3. **Signaux de marché comme déclencheurs de révision** : un down round, une juste valeur du warrant à zéro (prédictive de faillite selon GUM), ou un bris de covenant de trésorerie.
4. **Fréquence de révision** : au moins trimestrielle, alignée sur le reporting mensuel. La révision annuelle usuelle en SL est inadaptée à la vitesse de migration (un quart du portefeuille en grade 3 ou pire dans les BDC).
5. **Pondération des facteurs** : sponsor et solidité financière (runway, LTER) en tête, par exemple 25 à 35 % chacun, puis sûretés et contrôle, transaction et technologie, et environnement juridique. À **valider empiriquement** : la CP EBA 2026 permettrait de supprimer le plancher de 5 % pour un facteur non discriminant.
6. **Garde-fous de portefeuille (pilier 2)** : limites de concentration par sponsor VC et par millésime, et **stress « gel du marché VC »** de 12 à 18 mois sans tour (scénario 2022-2024).
7. **Données et clause de revoir** : champ AnaCredit ou reporting COREP identifiant les expositions de la nouvelle catégorie (stade, sponsor, LTER, runway), suivi EBA, et clause de revue du calibrage à 3-5 ans. **Aucune série publique européenne de défaut ou de LGD sur la venture debt n'a été identifiée** : c'est le principal risque de mauvais calibrage. [D : absence constatée]

### 8.4 Ce qui rendrait la grille actuariellement fausse [I]

- Calibrer sur 2010-2021 (argent facile, peu de défauts) ou sur des données « marché » incluant la famille (c).
- Traiter l'upside des warrants comme un absorbeur de pertes.
- Ignorer la corrélation au cycle VC et la concentration par sponsor.
- Importer les RW préférentiels à moins de 2,5 ans et la révision annuelle du slotting PF.
- Fonder le coussin d'equity sur la valorisation post-money plutôt que sur le cash versé.
- Utiliser des données de prêteurs survivants (biais de survie : SVB/First Citizens, BDC cotées).

### 8.5 Esquisse de grille illustrative (seuils à calibrer) [I]

| Sous-facteur | Solide | Bon | Satisfaisant | Faible |
|---|---|---|---|---|
| Runway post-financement sans nouveau tour | ≥ 24 mois | 18-24 mois | 12-18 mois | < 12 mois (automatique si < 6 mois sans term sheet) |
| LTER (prêt / cash d'equity levé sur 24 mois) | ≤ 20 % | 20-30 % | 30-50 % | > 50 % |
| Growth : dette / ARR | ≤ 0,5x | 0,5-1,0x | 1,0-1,5x | > 1,5x |
| Sponsors | Leads de premier rang, réserves dédiées documentées, fonds en période d'investissement | Leads établis, réserves probables | Syndicat étroit, fonds en fin de vie | Pas de lead institutionnel, down rounds répétés, signaux d'abandon |
| Performance par rapport au plan (4 derniers trimestres) | ≥ 100 % | 85-100 % | 70-85 % | < 70 % |
| Sûretés et contrôle | Premier rang sur tous les actifs, PI inscrite et redéployable, contrôle des comptes, covenants complets | Premier rang, PI partiellement nantie, negative pledge | Split-lien défavorable, covenants légers | Rang second ou structurellement subordonné (relève de l'art. 128) |
| Juridique et PI | PI détenue par l'emprunteur dans l'UE, pre-pack disponible | Petites frictions d'opposabilité | PI dans une entité tierce avec licence | PI hors de portée, enforcement incertain |

---

## 9. Récapitulatif : ce qui est documenté et ce qui est inféré

| Affirmation | Statut |
|---|---|
| Volumes US (68,8 Md$ en 2025) et européens (20,1 Md€ en 2025, 29 % du VC) | [D] |
| Le prêt est remboursé par l'événement de liquidité (IV d'environ 1) ; demi-vie d'environ 2 ans ; 11 % arrivent à maturité | [D] |
| NCO early stage de 9,6-9,7 % contre 1,3-1,5 % en growth (2023-2024) ; environ 6 % en 2008-2010 | [D] |
| Warrants : JV de 1,4 à 3 % du principal ; loi de puissance chez SVB ; +1,1 Md$ net en 20 ans | [D] |
| Proxy de LGD de marché d'environ 50 % (Horizon) | [C à partir de D] |
| RW SA de 76 à 85 %, RW NI de 100 à 320 % selon PD et LGD | [C] |
| Early stage sous-capitalisé en SA ; growth adéquat | [C/I] |
| La compensation par les warrants est inter-temporelle, pas contingente à l'état du monde | [I] |
| Venture debt dans le champ de la guidance BCE sur le levier | [I, à vérifier] |
| Warrants sur des fintechs relevant du régime de déduction | [I, à vérifier] |
| Qualification des warrants (dérivé ou equity ; 400 % ou 250 %) | [I] : insécurité juridique réelle |
| Corrélation plus forte que la corrélation corporate (analogie HVCRE) | [I] : non estimable avec les données publiques |
| Seuils de la grille illustrative | [I] : à calibrer sur données de prêts |

## 10. Interfaces avec les autres agents du pipeline

- **current-regulation-analyst** : vérifier le texte CRR3 des art. 153(5) et 158(6) (tableaux), 133(4) (portée de « venture capital firms » et de l'exception de long terme), 495a, 501 et 122a ; le traitement des warrants (art. 133(1)(d) ou SA-CCR) ; l'application des art. 36(1)(h) et 44-46 aux warrants sur des fintechs ; les art. 89 et 91 après une conversion dette-actions ; la CP EBA du 7 mai 2026 sur le RTS slotting.
- **macro-financial-analyst** : la corrélation au cycle VC, la corrélation actif-passif de type SVB, la place de la BEI et d'InvestEU (environ 40 % des 26,2 Md€ de garantie InvestEU fléchés vers la venture debt, le quasi-equity et l'equity à haut risque, selon COM(2025) 270), TechEU (70 Md€ d'ici 2027).
- **benchmarking-analyst** : US (12 CFR 7.1006, l'expérience SVB et First Citizens, les BDC), UK (HSBC Innovation Banking, mise en œuvre de Bâle 3.1 par la PRA), HVCRE bâloise.
- **stakeholder-mapper** : BEI et FEI, Bpifrance, banques universelles actives dans la venture growth (BNP Paribas, Crédit Agricole CIB, Natixis, ING, Rabobank, ABN AMRO, les nordiques), fonds spécialisés (Kreos/BlackRock, Claret, Atempo), BCE/MSU (guidance levier), EBA (RTS slotting).

---

## Sources

- González-Uribe, J. & Mann, W. (2024), *Venture debt as bridge financing* : [PDF](https://uncipc.org/wp-content/uploads/2024/05/VentureDebt.pdf) ; [SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5002114)
- UCLA Anderson Review, *Lending to Startups: Not as Risky as You'd Think* : https://anderson-review.ucla.edu/venture-debt
- Davis, Morse & Wang, *The Leveraging of Silicon Valley*, NBER WP 27591 : https://www.nber.org/papers/w27591
- Hochberg, Serrano & Ziedonis, *Patent collateral, investor commitment, and the market for venture lending*, JFE : https://www.nber.org/papers/w20587 ; https://www.sciencedirect.com/science/article/abs/pii/S0304405X1830151X
- de Rassenfosse & Fischer (2016), *Venture Debt Financing: Determinants of the Lending Decision* : https://sms.onlinelibrary.wiley.com/doi/abs/10.1002/sej.1220
- Houlihan Lokey, *European Venture Debt Market Update – June 2026* (données PitchBook) : https://cdn.hl.com/pdf/2026/eu-venture-debt-market-update-june-2026.pdf
- Runway Growth Capital & PitchBook, *2025-2026 Venture Debt Review* (mai 2026) : https://www.prnewswire.com/news-releases/runway-growth-capital-and-pitchbook-release-2025-2026-venture-debt-review-venture-debt-hits-record-68-8-billion-302781920.html
- PitchBook, *Early-stage startups take a third of venture debt funding* (2025) : https://pitchbook.com/news/articles/early-stage-startups-a-third-venture-debt-dollars-q2-2025
- Atomico, *State of European Tech* 2025 : https://www.stateofeuropeantech.com/chapters/startup-investment-trends
- PitchBook, *Q2 2025 European Venture Report* : https://pitchbook.com/news/reports/q2-2025-european-venture-report
- BEI, *EIB Venture Debt* (juin 2025) : https://www.goerg.de/sites/default/files/anylink/June2025_EIB.Venture%20Debt%20Presentation.pdf ; https://www.eib.org/en/products/equity/venture-debt/index
- EIC Scaling Club, webinaire BEI venture debt : https://eicscalingclub.eu/news/eibs-venture-debt-instruments-webinar
- SVB Financial Group, Q4 2022 CEO letter & presentation : https://www.sec.gov/Archives/edgar/data/719739/000071973923000009/q42022ceoletterandpresen.htm ; 10-K 2022 : https://www.sec.gov/Archives/edgar/data/719739/000071973923000021/sivb-20221231.htm ; communiqué 4T22 : https://www.sec.gov/Archives/edgar/data/719739/000071973923000009/q422earningsrelease_991.htm
- First Citizens BancShares, présentations investisseurs 4T23 : https://www.sec.gov/Archives/edgar/data/798941/000079894124000010/a4q23_investorpresentati.htm ; 4T24 : https://www.sec.gov/Archives/edgar/data/798941/000079894125000003/a4q24investorpresentatio.htm ; 1T26 : https://www.sec.gov/Archives/edgar/data/798941/000079894126000018/a1q26investorpresentatio.htm
- Hercules Capital, 8-K 2025 : https://www.sec.gov/Archives/edgar/data/1280784/000128078425000042/htgcq32025release.htm ; 10-K 2024 : https://www.sec.gov/Archives/edgar/data/1280784/000128078425000007/htgc-20241231.htm
- Hunterbrook, *The Myth of Hercules Capital* (27 février 2026) : https://hntrbrk.com/hercules-capital/
- Horizon Technology Finance, 10-Q au 30/09/2025 : https://www.sec.gov/Archives/edgar/data/1487428/000143774925031988/hrzn20250930_10q.htm
- TriplePoint Venture Growth, résultats 4T/2025 : https://investor.tpvg.com/news/press-release-details/2026/TriplePoint-Venture-Growth-BDC-Corp--Announces-Fourth-Quarter-and-Fiscal-Year-2025-Financial-Results/default.aspx
- Kruze Consulting, *Warrant coverage* et *Investor abandonment clause* : https://kruzeconsulting.com/blog/warrant-coverage-venture-loans/ ; https://kruzeconsulting.com/blog/investor-abandonment-clause-on-venture-debt/
- Carlsquare, *European Debt Markets #2 2026* : https://carlsquare.com/insights/european-debt-markets-quarterly-insights-2-2026/
- CNBC, Mistral AI (830 M$, mars 2026) : https://www.cnbc.com/2026/03/30/mistral-ai-paris-data-center-cluster-debt-financing.html ; Nscale : https://www.nscale.com/press-releases/nscale-secures-790-million-norway
- Moody's, *Default and recovery rates for project finance bank loans* : https://www.ppiaf.org/documents/2928
- Comité de Bâle, CRE33 (slotting) : https://www.bis.org/committees/bcbs/basel-framework/standard/cre/33/inforce/2019-12-15/published/2022-12-08
- CRR (consolidé), articles 89, 91, 122, 122a, 128, 133, 147, 495a : https://judict.eu/en/hla/32013R0575-X/article-89 ; https://judict.eu/en/hla/32013R0575-X/article-91 ; https://judict.eu/en/hla/32013R0575-X/article-122 ; https://www.judict.eu/en/hla/32013R0575-X/article-122A ; https://judict.eu/en/hla/32013R0575-X/article-128 ; https://judict.eu/en/hla/32013R0575-X/article-133 ; https://judict.eu/en/hla/32013R0575-X/article-147 ; https://judict.eu/en/hla/32013R0575-X/article-495A
- Règlement délégué (UE) 2021/598 (RTS slotting) : https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32021R0598 ; https://judict.eu/en/sla/32013R0575/32021R0598-X
- EBA, CP du 7 mai 2026 modifiant le RTS slotting : https://www.eba.europa.eu/sites/default/files/2026-05/4e9f5602-0d3a-42b7-b79a-6643c266ecab/CP%20on%20RTS%20on%20slotting.pdf ; synthèse : https://regreportingdesk.com/eba-specialised-lending-rts-slotting-crr3/
- Facteur de soutien PME sous CRR3 : https://www.leaseurope.org/european-implementation-basel-iv-crr-iii-finalised ; https://judict.eu/en/hla/32013R0575/article-501
- LGD F-IRB et plancher de PD sous CRR3 : https://banking.vision/en/crr-iii-irba/
- BCE, *Guidance on leveraged transactions* (2017) : https://www.bankingsupervision.europa.eu/ecb/pub/pdf/ssm.leveraged_transactions_guidance_201705.en.pdf
- Directive (UE) 2026/799 (harmonisation de l'insolvabilité) : https://www.matheson.com/insights/eu-insolvency-harmonisation-directive-approved-practical-implications/ ; https://www.consilium.europa.eu/en/press/press-releases/2025/11/19/insolvency-proceedings-council-and-european-parliament-agree-on-common-eu-rules/
- OCC, 12 CFR 7.1006 (equity kickers) : https://occ.gov/topics/charters-and-licensing/interpretations-and-decisions/1999/int868.pdf
- IFRS 9, test SPPI : https://ifrscommunity.com/knowledge-base/ifrs-9-classification-of-financial-assets-and-financial-liabilities/
- Commission européenne, *EU Startup and Scaleup Strategy*, COM(2025) 270 : https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=celex%3A52025DC0270
- FEI, garanties InvestEU : https://www.eif.org/flagship-initiatives/investeu/guarantees
