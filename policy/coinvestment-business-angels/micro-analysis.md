# Analyse micro-financière — Un dispositif de co-investissement UE pour amener les business angels à investir dans les écosystèmes startup moins matures de l'Union

**Question traitée** : quel type de *co-investment scheme* pourrait fonctionner, juridiquement et financièrement, à l'échelle de l'UE, pour amener des business angels (BA) à investir dans d'autres États membres dont l'écosystème startup est moins développé, alors même que ces pays comptent de nombreuses startups ?

**Périmètre de ce document** : mécanique de la transaction, incitations au niveau de l'investisseur individuel et du véhicule, points de friction et effets de seuil. **Hors périmètre** : effets macro/agrégés, et conception normative du dispositif (livrée par l'agent policy). Ce document identifie ce qu'un mécanisme de co-investissement *peut* et *ne peut pas* corriger ; il ne le dessine pas.

**Date de rédaction** : 1er septembre 2026. Sauf mention contraire, les données les plus récentes disponibles à cette date sont utilisées.

**Document autonome.** Il recoupe partiellement `policy/micro-analysis.md` (7 août 2026, périmètre plus large : efficience de l'investissement BA en Europe). Les données reprises de ce document ont été re-vérifiées ; celles qui n'ont pas pu l'être sont signalées comme telles.

**Convention de fiabilité** — chaque énoncé est étiqueté :
- **[D]** *Documenté* : chiffre ou mécanisme attesté par une source primaire ou une source secondaire vérifiable et datée.
- **[C]** *Calculé* : dérivation arithmétique de l'auteur à partir de données [D]. La formule est explicitée.
- **[I]** *Inférence plausible non vérifiée* : raisonnement cohérent avec les mécanismes documentés mais **non testé empiriquement**. À ne pas citer comme un fait.
- **[?]** *Non vérifié / incohérent* : source contradictoire, non datée, ou non authentifiable.

---

## 1. Le paradoxe à expliquer, quantifié

### 1.1 L'offre de projets existe dans les pays cibles ; le capital n'y va pas

| Indicateur | Valeur | Fiabilité |
|---|---|---|
| Investissement PE/VC en Europe, 2025 | **135 Md€** (+3 %), fundraising 147 Md€ (+16 %) | [D] Invest Europe |
| Dont venture capital, Europe 2025 | **~20 Md€**, 20 % au-dessus de la moyenne quinquennale | [D] Invest Europe |
| Investissement VC en Europe de l'Est, 2025 | **3,6 Md€** sur **1 034 transactions**, soit **5,5 %** du VC européen pour ~1/3 de la population du continent | [D] The Recursive (données Dealroom) |
| Investissement VC en CEE (périmètre Invest Europe), 2025 | **675 M€** (quasi doublé sur un an), dont **438 M€ de later-stage VC** (65 %) | [D] Invest Europe / 0100 Conferences |
| **Intensité de l'investissement PE/VC rapportée au PIB, CEE** | **0,091 %** contre une **moyenne européenne de 0,558 %** | [D] Invest Europe |
| Ratio d'intensité CEE / moyenne européenne | **0,163**, soit **~16 %** de l'intensité européenne moyenne | [C] = 0,091 / 0,558 |
| Concentration intra-CEE | Pologne : **39 %** de la valeur investie et **29 %** des sociétés financées ; Estonie seul pays CEE au-dessus de la moyenne européenne d'intensité | [D] |
| Répartition régionale du VC européen (Invest Europe 2025) | UK & Irlande 40 %, France & Benelux 30 %, Nordiques 11 %, DACH 9 %, Europe du Sud 8 %, **CEE 1 %** | [?] chiffres rapportés par recherche secondaire ; base (investissement vs fundraising) non confirmée sur le rapport primaire |

**Lecture micro.** Le déficit n'est pas un déficit de projets : la CEE compte **56 licornes** [D], **14 en Pologne, 11 en Estonie, 6 en Tchéquie, 3 en Roumanie** [D], pour une valeur d'écosystème de **243 Md€** début 2025 [D]. Le déficit est un déficit **d'intensité de capital par unité de PIB** — d'un facteur ~6 [C]. Un dispositif de co-investissement agit précisément sur ce ratio et non sur la production de projets ; c'est cohérent avec le diagnostic.

### 1.2 Le marché angel européen : l'unité de compte réelle

| Indicateur (marché « visible », 38-39 pays) | 2023 | 2024 | Fiabilité |
|---|---|---|---|
| Investissement BA | 1 255 M€ | **1 220 M€** (−2,8 %) | [D] EBAN Stats Compendium 2024 |
| Nombre de tours avec participation BA | 4 789 | **4 582** | [D] |
| Nombre de BA recensés | 45 340 | **47 610** | [D] |
| **Ticket moyen par BA et par tour** | 27 700 € | **25 600 €** | [D] |
| Investissement moyen par société | 221 400 € | **204 900 €** | [D] |
| Répartition par taille de tour (sous-échantillon 318 tours / 276 M€) | tours ≤ 1 M€ : **67 % des transactions / 31,5 % du capital** ; tours 1–4 M€ : **33 % / 68 %** | | [D] |

*Réserves de fiabilité sur EBAN, confirmées lors de cette recherche* : (i) **aucun compendium 2025 n'est publié au 1er septembre 2026** — l'édition 2024 (données 2024) reste la plus récente [D] ; (ii) EBAN a **abandonné** le multiplicateur ×10 qui servait à estimer le marché total sans lui substituer d'estimation, si bien qu'**il n'existe aucune estimation publiée et défendable du marché angel européen total** [D] ; (iii) le chiffre de « **7,5 Md€ par an** » que l'on trouve en présentation institutionnelle d'EBAN est un ordre de grandeur de secteur non daté et incompatible avec le marché visible de 1,22 Md€ — **[?] à ne pas citer** ; (iv) le PDF du compendium 2024 est composé d'images et n'a pas pu être ré-extrait dans cette session ; les chiffres ci-dessus sont repris de l'extraction du 7 août 2026 dans `policy/micro-analysis.md`, dont les incohérences internes (France à 130,66 M€ vs 98,6 M€ ; 359 vs 339 réseaux ; 5 954 sociétés implicites contre 4 582 tours) restent non résolues.

**Le chiffre structurant de tout le dossier est 25 600 €.** C'est l'unité de compte du BA européen. Toute friction dont le coût fixe dépasse quelques milliers d'euros consomme une fraction à deux chiffres de ce ticket. C'est la contrainte qui domine l'ensemble de l'analyse qui suit.

---

## 2. Mécanique de l'opération visée : décomposition d'un ticket angel transfrontalier

Un investissement angel n'est pas l'achat d'un titre : c'est une **chaîne de production** en sept étapes, dont chacune a une fonction de coût distincte et une élasticité distincte à la distance. C'est cette décomposition, et non le droit applicable, qui explique le sous-investissement transfrontalier.

| # | Étape | Coût dominant | Élasticité à la distance | Un dispositif de co-investissement peut-il l'abaisser ? |
|---|---|---|---|---|
| 1 | **Sourcing** (accès au flux) | Temps ; appartenance à un réseau local | **Très forte** : le flux arrive par réseau personnel | Indirectement seulement (via une exigence de syndication ou un réseau accrédité) |
| 2 | **Screening initial** | Temps ; jugement sur les personnes | **Très forte** | Non |
| 3 | **Due diligence** (juridique, fiscale, technique) | Honoraires externes, largement **fixes par opération** | Forte : duplication par juridiction | **Oui** (mutualisation) |
| 4 | **Négociation du term sheet / pacte** | Honoraires ; asymétrie de standards | Forte : les standards de pacte diffèrent par État membre | Partiellement (documentation type) |
| 5 | **Structuration du véhicule** (direct vs SPV) | Frais fixes de constitution + administration annuelle | Moyenne à forte | **Oui**, c'est la fonction naturelle d'un véhicule central |
| 6 | **Suivi post-investissement / gouvernance** | Temps ; présence physique ; langue | **Très forte** | Non (sauf délégation à un lead local) |
| 7 | **Sortie** | Profondeur du marché acquéreur local ; fiscalité de la cession | Forte : dépend de l'écosystème cible | Marginalement |

**Point analytique central.** Les étapes 1, 2, 6 et 7 — celles où la distance mord le plus — sont précisément celles qu'un mécanisme de co-investissement financier **ne peut pas** abaisser par transfert de capital. Les étapes 3, 4 et 5 sont celles où il peut agir. Un dispositif conçu comme un simple *matching* d'euros agit donc sur la partie **minoritaire** de la fonction de coût. C'est l'hypothèse de conception la plus importante à tester, et elle est corroborée par les deux quasi-expériences de la section 3.

### 2.1 Ordres de grandeur des coûts fixes de l'étape 5

| Poste | Montant | Fiabilité |
|---|---|---|
| SPV par deal, plateforme européenne (Roundtable, véhicule SAS/SC français ou SCSp luxembourgeois selon la résidence des co-investisseurs) | **1 % du montant levé, minimum 5 000 € HT** | [D] tarification publique Roundtable, 2026 |
| Constitution d'un SPV, fourchette de marché mondiale | **3 000 – 10 000 USD** | [?] source prestataire, « fourchettes indicatives 2026 » |
| Administration annuelle d'un SPV | **2 000 – 8 000 USD** | [?] même source |
| Audit, si requis | **3 000 – 15 000 USD** | [?] même source |

**[C] Le minimum de 5 000 € mord en dessous de 500 000 € levés** (5 000 / 0,01). Conséquences arithmétiques sur des tours de taille angel :

| Montant levé par le SPV | Frais Roundtable | En % du montant | Équivalent en tickets moyens (25 600 €) |
|---|---|---|---|
| 100 000 € | 5 000 € | **5,0 %** | 3,9 angels |
| 250 000 € | 5 000 € | **2,0 %** | 9,8 angels |
| 500 000 € | 5 000 € | **1,0 %** | 19,5 angels |
| 1 000 000 € | 10 000 € | 1,0 % | 39,1 angels |

**[C]** Un angel **seul** au ticket moyen européen (25 600 €) qui voudrait passer par un SPV supporterait **19,5 % de son ticket** en frais de véhicule. **[I]** C'est la démonstration arithmétique que le transfrontalier angel est **structurellement un jeu de syndicat** : en dessous d'environ 10 co-investisseurs, la structuration détruit plus de valeur qu'elle n'en protège. Tout dispositif public qui ne présuppose pas la syndication finance des opérations dont le coût de structuration est prohibitif. Ce raisonnement est arithmétique ; **le seuil de 10 co-investisseurs est une déduction, pas une observation de marché**.

### 2.2 Le choix du véhicule est contraint par la fiscalité, pas par la commodité

**[D]** Un SPV **opaque** (société de capitaux) interposé entre l'angel et la cible fait perdre la transparence fiscale. En droit luxembourgeois, le régime d'exonération des plus-values de cession exige une participation d'**au moins 10 % du capital** ou un **prix d'acquisition d'au moins 6 M€**, détenue ou destinée à l'être **12 mois**. Un SPV d'angels détenant typiquement 2–8 % d'une startup **ne remplit ni l'un ni l'autre critère**, et la plus-value de cession devient imposable au niveau du véhicule avant redistribution.

**[C]** D'où l'usage quasi systématique de véhicules **fiscalement transparents** (SCSp luxembourgeois, SC/SAS française, équivalents) : c'est la seule manière de préserver, pour chaque angel, le régime fiscal de son propre État de résidence.

**[I] Conséquence structurelle rarement relevée** : la transparence fiscale, qui est la solution au problème de double imposition, **réinstalle intégralement la fragmentation** que le véhicule commun était censé résoudre. Chaque angel se retrouve individuellement face à sa propre administration fiscale, avec ses propres obligations déclaratives sur une participation indirecte dans une société étrangère. Un « véhicule de co-investissement européen unique » ne peut donc pas, par construction, unifier le traitement fiscal des angels ; il ne peut unifier que la **couche opérationnelle** (documentation, cap table, appels de fonds, reporting). **Cette limite est une déduction de la structure des régimes fiscaux, non un résultat mesuré.**

---

## 3. Les deux quasi-expériences : la contrainte n'est pas juridique

C'est le résultat le plus important du dossier. Il existe deux cas où la contrainte réglementaire ou contractuelle sur l'investissement transfrontalier a été **levée**, et où l'on observe le comportement résiduel. Dans les deux cas, la part transfrontalière reste à un niveau à un chiffre ou juste au-dessus.

### 3.1 European Angels Fund (EIF) : 12 % de transfrontalier quand 20–50 % sont contractuellement autorisés

**[D]** ([EIF Working Paper 2020/62](https://www.econstor.eu/bitstream/10419/213873/1/1689254033.pdf), portefeuille arrêté 2019, 438 sociétés) :

| Indicateur | Valeur |
|---|---|
| Part internationale **contractuellement autorisée** par angel | **20 % à 50 %** du portefeuille |
| Part internationale **effectivement réalisée** | **12 %** |
| Sociétés situées dans le **même pays** que l'investisseur | **88 %** (recevant **81 %** du capital) |
| Investissements dans la **même commune** que l'angel | **> 1 sur 4** |
| **Distance médiane** angel–société | **124 km** |
| Distance moyenne / 95e percentile | 458 km / 945 km |
| Flux intra-NUTS3 en part des flux domestiques | **45 %** |
| Investissement médian d'un BA dans une société au premier tour | **~128 000 €** |

Deux régularités additionnelles dans les mêmes données [D] : les investissements lointains sont **plus gros** (les flux intra-NUTS3 sont ~15 % plus petits que les flux domestiques inter-NUTS3), ce qui est la signature d'un **coût fixe d'investigation à distance** amorti sur un ticket plus élevé ; et les angels ne cherchent des opportunités lointaines **qu'après épuisement des opportunités locales**.

**Chez des angels expérimentés, sélectionnés, dotés d'un appariement public 1:1 et contractuellement autorisés à consacrer jusqu'à la moitié de leur portefeuille à l'étranger, la part internationale réalisée est de 12 %, soit moins du quart de la borne haute autorisée.** La contrainte n'était pas mordante.

### 3.2 ECSPR : 8 % de capital transfrontalier avec un passeport européen intégral

Le règlement (UE) 2020/1503 (ECSPR) constitue le seul rail européen offrant un **passeport intégral par simple notification** pour l'offre de titres de startups à des investisseurs de tous les États membres.

| Indicateur | Valeur | Fiabilité |
|---|---|---|
| Plateformes agréées ECSPR | **181** dans 21 États membres (données ESMA 2024) ; **254** au registre ESMA début 2026 (+60 % en trois ans depuis 159 en 2023) | [D] ESMA ; [D] presse spécialisée pour 2026 |
| Capital levé, 2024 | **4,25 Md€** | [D] ESMA |
| Répartition par instrument | prêt **58 %**, dette **23 %**, **equity 12 %** (~510 M€) | [D] ESMA |
| **Part moyenne du capital levé provenant d'investisseurs résidant dans un autre pays que celui du prestataire** | **8 %** (2024) | **[D] ESMA** |
| Dispersion de cette part | Estonie **77 %**, Lettonie **47 %** — le reste très bas | [D] ESMA |
| Plateformes ayant demandé un passeport | **72 sur 227** (janvier 2025) | [D] |
| Plateformes opérant effectivement en transfrontalier | **< 30 %** début 2025 | [D] |
| Ticket moyen tous investisseurs / investisseurs « sophistiqués » | **660 €** / **2 660 €** | [D] ESMA |
| Concentration géographique | France 1,45 Md€ (20 %), Pays-Bas ~1 Md€, Espagne 450 M€, Italie 290 M€, Lituanie 280 M€ → **top 5 > 80 %** de la valeur | [D] ESMA |

*Réserve* : une autre source secondaire donne la part equity à **6 %** et non 12 %. **[?]** Non arbitré ; le chiffre ESMA de 12 % / ~510 M€ est retenu.

**Lecture décisive.** Le passeport ECSPR supprime intégralement l'obstacle juridique à la sollicitation transfrontalière d'investisseurs particuliers. **Le capital transfrontalier reste à 8 %.** Deux mécanismes distincts (contractuel à l'EAF, réglementaire à l'ECSPR), deux populations distinctes (angels expérimentés, investisseurs particuliers), deux périodes distinctes (2019, 2024) — et une part transfrontalière convergeant vers 8–12 %.

**[I]** La conclusion opérationnelle est forte et va à l'encontre de la présentation habituelle du problème : **le levier réglementaire est déjà largement épuisé sur ce segment**. Le rendement marginal d'une nouvelle levée d'obstacle juridique (28e régime, révision EuVECA) sur le comportement transfrontalier des angels est probablement faible, parce que la contrainte mordante est ailleurs — dans les étapes 1, 2, 6 et 7 de la chaîne de production (§ 2). **Cette inférence repose sur deux observations, dans deux cadres différents ; elle n'a pas été testée par une évaluation causale.**

Contre-argument à retenir [D] : l'Estonie (77 %) et la Lettonie (47 %) montrent que des taux transfrontaliers élevés sont **atteignables**. Il s'agit toutefois de très petits marchés domestiques : le transfrontalier y est moins un choix qu'une nécessité de taille. **[I]** Cela suggère que la part transfrontalière est fonction décroissante de la taille du marché domestique de l'investisseur, ce qui a une implication de ciblage inconfortable : les angels des grands marchés (DE, FR, IT, ES) — ceux dont on veut mobiliser le capital vers les écosystèmes moins matures — sont précisément ceux dont la contrainte de saturation locale est la moins mordante.

---

## 4. Les huit frictions, décomposées

### Friction 1 — Coût de sourcing à distance et absence de flux filtré

**Mécanique [D]** : le flux de deals d'un angel provient de réseaux personnels. Mason, Botelho & Duggett (2022) : « Reliance on trusted personal networks creates a local bias in both the investment opportunities that angels receive and those that pass their initial screening filter. » La localité s'exerce donc **deux fois** : à l'entrée du flux, puis au filtre.

**Ordre de grandeur [D]** : enquête EBAN 2020 auprès de **90 BA actifs dans 11 pays européens** — **55 % de ceux ayant réalisé des investissements transfrontaliers** les ont jugés « difficult » ou « very difficult ».

**Ce qu'un dispositif de co-investissement corrige** : **rien directement**. Un euro public apparié n'engendre pas de flux de deals. **[I]** Il ne peut agir qu'indirectement, en conditionnant l'accès à l'appartenance à un réseau ou à un syndicat disposant d'un flux local — ce qui déplace la question vers la sélection des intermédiaires.

**Ce qui fonctionne empiriquement [D]** : le **modèle « chapter »** (Keiretsu ; HBAN sur l'île d'Irlande) — plusieurs localisations sous une même marque et un même management, avec *gatekeeper* local propre, procédures standardisées de génération de flux, de screening et de due diligence, et événements communs construisant la confiance inter-chapitres. Mason et al. documentent que ce modèle permet de surmonter les facteurs inhibant l'investissement à distance. Il industrialise la production de **confiance et de flux filtré**, c'est-à-dire précisément les intrants des étapes 1, 2 et 6.

### Friction 2 — Fiabilité et duplication de la due diligence transfrontalière

**Mécanique [D]** : Shane (2005), cité par Mason et al. — différences de régimes juridique, fiscal, réglementaire et de gouvernance ; recours à des avocats et comptables étrangers ; traduction des documents. Ali et al. (2017), enquête paneuropéenne : **l'absence de cadres juridiques harmonisés** est identifiée comme barrière.

**[D]** Le contenu même de la due diligence angel résiste à la distance : Mason et al. observent que l'attention porte sur des **intangibles** (capacité de leadership, fiabilité, enthousiasme) et non sur des attributs vérifiables ; « Trust is particularly important » ; les facteurs humains sont la raison dominante de rejet.

**[I]** C'est la friction la moins réductible par la politique publique : l'intrant critique de la sélection angel est un jugement sur des personnes, dont le rendement décroît avec la distance et qu'aucun transfert de capital ne compense. Un dispositif de co-investissement peut mutualiser la **due diligence vérifiable** (juridique, fiscale, cap table) ; il ne peut pas mutualiser le jugement humain — sauf à le déléguer à un lead local, ce qui est le mécanisme du § 6.

### Friction 3 — Hétérogénéité du droit des sociétés et des pactes d'actionnaires

**Mécanique documentée [D]** — les formalités par juridiction :

| Juridiction | Instrument dominant en pré-amorçage | Friction de forme |
|---|---|---|
| Allemagne | *Wandeldarlehen* (prêt convertible) | Augmentations de capital de GmbH et cessions de parts en **forme notariée** obligatoire : coût et délai fixes par opération |
| France | **BSA-AIR** | Valeur mobilière ; formalités sociétaires et inscription au registre |
| Espagne | Prêt convertible | Résolution d'AG requise pour la renonciation au droit préférentiel de souscription |
| Royaume-Uni (hors UE) | **ASA** | Conçu pour l'éligibilité SEIS/EIS immédiate (*long-stop date*, clause de non-remboursement exigées par HMRC) |

*Source [D] pour la structure ; les estimations de coût associées (2 000–5 000 € de revue juridique par juridiction, 1 000–3 000 € de conseil fiscal) sont **[?]** d'origine cabinet, non vérifiables, citées comme ordre de grandeur uniquement.*

**Le développement le plus important de 2026 porte précisément sur cette friction.** **[D]** La Commission a adopté le **18 mars 2026** la proposition **COM(2026) 321 final** créant la forme sociale **« EU Inc. »** (28e régime) :

- constitution en **48 heures** pour **100 €**, formulaire harmonisé et statuts modèles européens ;
- **pas de capital minimum** ;
- principe **« digital-only »** pour l'ensemble du cycle de vie ; interface européenne centrale via **BRIS**, principe *once-only* ;
- **suppression des formalités physiques obligatoires sur les cessions de parts** : l'intervention obligatoire d'intermédiaires (notaires) imposée par certains États membres **ne s'applique pas** à une EU Inc. ;
- ouverte à toute société, pas seulement aux startups ; possibilité de conversion d'une société existante ;
- **le droit du travail et de la sécurité sociale nationaux sont expressément préservés** ; la fiscalité reste nationale ;
- objectif d'accord en trilogue **fin 2026**.

**Lecture micro.** L'EU Inc. attaque frontalement la friction 3 en supprimant le principal coût fixe non compressible du transfrontalier equity (la forme notariée allemande, et ses équivalents). **[I]** Mais elle ne touche ni la fiscalité, ni le flux de deals, ni la confiance ; et par construction, **elle ne modifie rien pour le stock de startups déjà constituées** sous forme nationale dans les pays cibles, sauf conversion — dont le coût et le délai ne sont pas documentés dans les sources consultées. **[?]** La proposition n'a pas pu être extraite du PDF primaire dans cette session ; les paramètres ci-dessus proviennent de synthèses de cabinets (Eubelius, Lexgo) et du dossier du Parlement européen.

### Friction 4 — Non-portabilité des incitations fiscales

**Mécanique [D]** : Mason et al. (2022) — « with few exceptions, governments **restrict tax incentives to individuals and businesses in their own jurisdictions** » ; et « Government funding programmes that **co-invest alongside business angels are also restricted to their own jurisdiction** ».

La non-portabilité opère sur **deux dimensions qui ne se recoupent jamais complètement** :

| Dispositif | Condition sur l'**investisseur** | Condition sur la **société cible** |
|---|---|---|
| IR-PME (FR) | **Domicilié fiscalement en France** | Siège dans **l'UE ou l'EEE** ✔ ouvert |
| INVEST (DE) | Résidence principale dans **l'EEE** ✔ ouvert | Siège EEE **avec au moins un établissement en Allemagne** |
| EIS/SEIS (UK) | Contribuable britannique | Établissement permanent au Royaume-Uni |

**[C] Matrice de résultat** : un angel **FR → cible DE** cumule les deux dispositifs (par recoupement fortuit de deux ouvertures unilatérales sur des dimensions différentes) ; un angel **DE → cible FR** n'obtient **rien** ; un angel **FR → cible UK** n'obtient **rien**. Aucune coordination n'a produit ce résultat.

**[I]** L'effet dommageable n'est pas le niveau moyen de subvention mais son **irrégularité** : elle introduit un différentiel de coût du capital arbitraire entre destinations, sans rapport avec la qualité des projets. **Aucune quantification de cette matrice sur les 27 États membres n'a été identifiée** — c'est une lacune de données directement exploitable.

**Illustration mesurée [D]** : sur l'île d'Irlande, un angel nord-irlandais investissant en République perd l'EIS/SEIS sans acquérir l'EII irlandais, et réciproquement ; **56 %** des angels nord-irlandais cesseraient d'investir sans incitations fiscales contre **41 %** au Sud, écart attribué par les auteurs à la générosité supérieure du régime britannique.

**Point crucial pour la conception d'un dispositif de co-investissement [D]** : Mason et al. établissent que le levier fiscal opère sur la **marge extensive** (combien de capital l'individu alloue à la classe d'actifs) et non sur la **marge intensive** (quel deal il choisit) : « the existence of tax incentives had an influence on how much of their investment portfolio that they would allocate to early stage businesses **they did not influence their investment decisions**. » **[I]** Si l'objectif est de réorienter géographiquement un flux existant — ce qui est exactement la question posée —, un levier fiscal est **le mauvais instrument** : il agit sur le volume alloué, pas sur la destination. Un co-investissement conditionné à la destination agit, lui, directement sur la marge intensive.

### Friction 5 — Restriction géographique des dispositifs de co-investissement publics eux-mêmes

C'est la friction la plus paradoxale : les instruments censés corriger le biais domestique le **reproduisent** dans leur propre design.

**[D] EAF, périmètre réel au 1er septembre 2026** : compartiments nationaux dédiés pour **Autriche, Belgique (Flandre), Danemark, Finlande, Allemagne, Irlande, Italie, Pays-Bas, Espagne** — **neuf marchés, tous parmi les écosystèmes les plus matures de l'Union** — plus une **allocation paneuropéenne** résiduelle pour « les angels des autres géographies et investissant à travers le continent ».

**[C] Aucun des onze États membres de la CEE (PL, RO, CZ, HU, BG, SK, HR, LT, SI, LV, EE — de l'ordre de 100 millions d'habitants, soit environ 22 % de la population de l'UE) ne dispose d'un compartiment EAF dédié.** Les pays cibles de la question posée sont, à une exception près (l'Italie, qui n'est pas un écosystème « moins développé »), exactement le complémentaire de la couverture EAF.

**[D] Détail mécanique révélateur** (EIF WP 2020/62) : la restriction géographique porte sur **le pays du programme, non sur la localisation de l'angel**. Deux angels rattachés au compartiment **EAF Germany** sont physiquement établis en Belgique et en Suisse ; leurs investissements sont dirigés majoritairement vers l'Allemagne, l'angel étant contractuellement tenu de consacrer « the lion share » de ses investissements au marché domestique du compartiment.

**[I]** C'est le point de conception le plus directement actionnable de tout le dossier. Le compartimentage national de l'EAF n'est pas un accident : il reflète le mode de financement (abondements nationaux — Enterprise Ireland pour l'Irlande, Tekes/Business Finland pour la Finlande, etc.). Mais son effet mécanique est de **subventionner le biais domestique** dans les pays qui en souffrent le moins, et de laisser sans instrument les pays qui en souffrent le plus. Un compartiment national financé par un État membre ne peut, politiquement, subventionner un investissement sortant ; seul un financement **au niveau de l'Union** peut le faire. **Cette lecture est une inférence sur la logique de financement, non un constat documenté par l'EIF.**

### Friction 6 — Devise

**[D]** Après l'adoption de l'euro par la **Bulgarie le 1er janvier 2026** (21e membre, taux fixe 1 EUR = 1,95583 BGN), **six** États membres restent hors zone euro : **Tchéquie, Danemark, Hongrie, Pologne, Roumanie, Suède**. Seule la Roumanie a une date cible active (2029).

**[C]** Quatre des principaux marchés cibles — **Pologne, Roumanie, Tchéquie, Hongrie** — sont hors zone euro. La Pologne concentre **39 % de la valeur investie en CEE** [D] et **44 tours sur 143 au T2 2026** [D]. Le risque de change s'applique donc à la majorité du flux de deals CEE adressable.

**Mécanique** [D] : Mason et al. — « The existence of different currencies creates additional risks arising from exchange rate fluctuations. » **[I]** Sur un horizon de détention angel de 7–10 ans, la couverture de change n'est ni disponible à coût raisonnable ni pratiquée à ces tailles ; le risque est simplement **porté nu**. Un dispositif de co-investissement libellé en euros aux côtés d'un angel de la zone euro **ne modifie pas** ce risque : il le partage pari passu. **Aucune donnée sur la sensibilité effective des décisions angels au risque de change n'a été identifiée** ; l'effet est déduit de la structure, non mesuré.

### Friction 7 — Profondeur des voies de sortie dans les écosystèmes cibles

C'est la friction la plus lourde en valeur actuelle, parce qu'elle affecte le rendement espéré et non le coût de transaction.

| Indicateur, CEE | Valeur | Fiabilité |
|---|---|---|
| Valeur totale des sorties PE/VC, 2025 | **1,71 Md€** (+26 %), deuxième meilleure année | [D] Invest Europe / 0100 |
| Dont **sorties VC** | **51 M€ sur 39 sociétés** | [D] |
| Ventes industrielles (*trade sales*) | **61 %** de la valeur des sorties | [D] |
| Introductions en bourse | **395 M€ sur 4 sociétés** | [D] |
| Cessions secondaires PE | 128 M€ | [D] |
| Part de la CEE dans la valeur des sorties européennes | **3,8 %** (contre 2,8 % en 2024) | [D] |
| Sorties VC-backed en CEE, pic 2024 | **76** — plus haut niveau en une décennie | [D] Dealroom |
| **Part des scale-ups CEE ayant relocalisé leur siège hors CEE** | **48 %** ; près de la moitié de la valeur d'entreprise totale de la CEE provient de sociétés au siège relocalisé | [D] Dealroom |
| Seuil de revenu pour l'intérêt des fonds secondaires | **~10 M€** de chiffre d'affaires | [D] |

**[C]** 51 M€ de sorties VC pour 39 sociétés donne **~1,3 M€ par société**. **Réserve méthodologique majeure** : les statistiques de *divestment* d'Invest Europe sont exprimées **au coût historique d'investissement**, pas en produit de cession. Ce chiffre ne mesure donc **pas** un multiple de sortie et **ne doit pas être lu comme tel**. Il mesure le **volume de capital sorti du portefeuille**, c'est-à-dire la vitesse de rotation — laquelle est très faible.

**[I]** Deux conséquences micro pour un angel étranger :
1. **Distribution des issues tronquée à droite.** Avec 61 % de la valeur en trade sales et 4 IPO dans toute la région, la queue droite qui fait le rendement angel est structurellement plus mince que sur un marché profond. Pour une classe d'actifs dont le rendement est entièrement porté par la queue, une troncature de la queue est une baisse de rendement espéré **non compensable** par un partage de risque pari passu.
2. **Le taux de relocalisation de 48 % est un signal ambigu.** Il constitue une voie de liquidité (redomiciliation vers un marché profond avant la sortie), mais il transforme la thèse d'investissement : l'angel finance une société dont le succès implique le départ. **[I]** Un dispositif public de co-investissement ciblant les écosystèmes moins matures et conditionné au maintien du siège dans le pays cible entrerait en contradiction directe avec la voie de sortie la plus fréquemment empruntée. **Cette tension n'est documentée dans aucune évaluation de programme identifiée** ; c'est une déduction du rapprochement de deux séries.

**[D]** Le diagnostic est partagé au plus haut niveau : le dialogue de mise en œuvre du 24 mars 2026 avec la commissaire Albuquerque identifie explicitement les **« underdeveloped secondary and exit markets »** parmi les obstacles au capital-risque européen.

### Friction 8 — Asymétrie d'information et absence de réseau local : ce que dit la littérature quantitative

| Résultat | Source | Fiabilité |
|---|---|---|
| Relation en **U inversé** entre distance géographique/culturelle et rendement des investissements, sur **815 investissements** d'une plateforme d'investissement angel | Wesemann & Antretter (2023), *Venture Capital* 25(4), 487-514 | [D] |
| **Les angels membres de grands syndicats sont significativement moins sensibles aux coûts de la distance géographique et culturelle, et obtiennent des rendements plus élevés de manière consistante** | idem | **[D]** |
| Les ressources de réseau permettent d'atténuer les coûts de transaction du transfrontalier et d'améliorer les rendements | idem | [D] |
| Les angels ne réalisent d'investissements transfrontaliers **que si des relations de confiance sont établies avec des lead investors locaux** dans le pays de la cible | idem / Mason et al. | [D] |
| L'expérience d'investissement **et** l'expérience entrepreneuriale favorisent l'internationalisation ; effets plus marqués en Europe qu'aux États-Unis | Croce, Schwienbacher & Ughetto (2023), *International Business Review* 32(1) | [D] |
| Les investisseurs plus expérimentés sont beaucoup plus disposés à investir à distance | Cowling et al. (2021), cité par Mason et al. | [D] |

**Ce bloc est la contribution empirique la plus directement exploitable pour la conception.** Il identifie **trois variables de conception** dont l'effet sur le transfrontalier est documenté, et non simplement postulé :

1. **La taille du syndicat** (effet mesuré sur la sensibilité à la distance *et* sur le rendement) ;
2. **La présence d'un lead local** (condition quasi nécessaire de l'investissement transfrontalier) ;
3. **L'expérience préalable de l'investisseur** (prédicteur documenté de l'internationalisation).

**[I]** Ces trois variables sont observables *ex ante* et vérifiables à faible coût — donc utilisables comme critères d'éligibilité contractuels, contrairement à la « confiance », qui ne l'est pas. C'est le principal point d'appui d'un dispositif de co-investissement qui viserait effectivement le transfrontalier plutôt que le seul volume.

**Réserve [I]** : le U inversé de Wesemann & Antretter implique que le rendement est maximal à **distance intermédiaire**, pas à distance maximale. Un dispositif optimisant le nombre de kilomètres franchis (ou le nombre de frontières) plutôt que la qualité de l'appariement irait à l'encontre de ce résultat. Une prime au transfrontalier doit être **plate au-delà de la frontière**, non croissante avec la distance. Ce corollaire de conception n'est pas énoncé dans l'article ; c'est une lecture.

---

## 5. Mécanique des dispositifs de co-investissement angels existants

### 5.1 European Angels Fund (EIF) — filtre en amont sur l'investisseur, délégation totale au niveau du deal

**Structure [D]** :

| Paramètre | Valeur |
|---|---|
| Forme juridique | **European Angels Fund S.C.A. SICAR** (Luxembourg), à compartiments |
| Volume total actuel | **> 800 M€** |
| Montant engagé auprès d'angels | **> 330 M€** |
| Nombre d'angels sélectionnés | **> 120** |
| Co-investissements en portefeuille | **> 800 PME** |
| Instrument contractuel | **Co-investment Framework Agreement (CFA)** : engagement d'un montant prédéfini **en amont**, et non deal par deal |
| Enveloppe par CFA | **250 000 € à 5 M€** |
| Ratio | **50:50**, ***pari passu*** |
| Horizon | **10 ans** |
| **Gouvernance des décisions d'investissement** | **« There is no deal-by-deal review by the EAF and investment decisions are fully delegated to the BA »** |
| Sélection | Sur **expérience d'investissement antérieure**, accès au flux, capacité financière |
| Compartiments | AT, BE (Flandre), DK, FI, DE, IE, IT, NL, ES + allocation paneuropéenne |

**[C] Enveloppe moyenne par CFA** : 330 M€ / 120 angels = **~2,75 M€**, au milieu de la fourchette 250 k€–5 M€.
**[C] Taux d'engagement** : 330 / 800 = **41 %**. Plus de la moitié du volume de la facilité n'est pas engagée auprès d'angels. *Réserve* : « volume » peut désigner la taille totale des compartiments y compris des enveloppes nationales non encore allouées ; le chiffre n'est pas daté avec précision sur les pages EIF (HTTP 403 lors de cette session ; données issues de reprises secondaires convergentes). **[?]**

**Ce que ce design résout, et à quel prix.**

Le filtre n'est **pas** au niveau du deal ; il est **entièrement en amont**, à l'accréditation de l'angel. C'est une réponse économiquement rationnelle au coût d'instruction : sur un investissement médian de premier tour de **~128 000 €** [D], une due diligence publique dossier par dossier coûterait plusieurs pourcents du montant déployé. **[I]** La question de conception pertinente n'est donc pas « faut-il déléguer ? » — à ces tickets, la délégation est quasi imposée par les coûts — mais **« à quel niveau placer le filtre, et quelle contrainte structurelle imposer au délégataire ? »**.

**Angle mort mécanique [I]** : rien dans le design ne détecte une dérive de qualité *à l'intérieur* du portefeuille d'un angel accrédité avant la liquidation à 10 ans, notamment l'usage de la ligne pour des tours de pont défensifs. **Aucune évaluation publique de la performance du portefeuille EAF ventilée entre premiers investissements et suivis n'a été identifiée.**

**Angle mort géographique [D/C]** : voir friction 5. L'EAF « fosters and supports cross border collaboration between Business Angels » selon sa propre présentation [D], mais son architecture en compartiments nationaux **ancrés dans les neuf écosystèmes les plus matures** produit mécaniquement l'effet inverse pour les pays cibles de la question posée.

### 5.2 PFR Biznest (Pologne) — co-investissement **intermédié** par des gérants de fonds

C'est le contre-modèle le plus instructif, parce qu'il se situe dans un pays cible et adopte une architecture différente de l'EAF.

**Mécanique [D]** ([PFR Ventures](https://pfrventures.pl/en/program-dla-vc/pfr-biznest) — page en HTTP 403 lors de cette session ; données issues de communiqués PFR convergents) :

| Paramètre | Valeur |
|---|---|
| Contrepartie du public | **Non pas les angels directement, mais des équipes de gestion VC** qui investissent aux côtés d'angels |
| Taille des fonds de co-investissement | **5 à 30 M PLN** de capitalisation |
| Ratio | **50:50** avec les business angels |
| Plafond par société | **jusqu'à 4 M PLN** |
| Stade | pre-seed / seed, participations minoritaires |
| Enveloppe publique totale | **260 M PLN**, appariés par 260 M PLN d'angels ; 258 M PLN à disposition |
| Nombre de véhicules | **7** fonds de capital-risque conventionnés |

**[I] Différence de conception essentielle par rapport à l'EAF** : PFR n'accrédite pas des angels, il accrédite des **gérants professionnels** chargés d'agréger les angels. Cette architecture ajoute une couche de frais et un intermédiaire, mais résout un problème que l'EAF ne résout pas : dans un écosystème où le nombre d'angels au *track record* documenté est faible, **le filtre en amont de l'EAF n'a pas de population sur laquelle s'exercer**. Un dispositif fondé sur l'accréditation d'angels expérimentés est mécaniquement plus facile à déployer là où les angels expérimentés sont déjà nombreux — c'est-à-dire dans les écosystèmes matures. **C'est une explication de conception, cohérente avec le fait que l'EAF n'a pas de compartiment CEE, mais elle n'est pas confirmée par une source EIF.**

**Friction résiduelle non résolue [C]** : PFR Biznest est libellé en **PLN**, financé par le budget polonais, et opéré par des gérants polonais. Rien n'indique dans les sources consultées qu'un angel non-résident soit exclu ; mais l'architecture (fonds nationaux, devise nationale, financement national) reproduit exactement le compartimentage de la friction 5. **[?]** La question de l'éligibilité des angels étrangers n'a pas pu être tranchée (page primaire inaccessible).

### 5.3 Angel CoFund (Royaume-Uni) — filtre au niveau du deal par exigences structurelles

**[D/?]** Fonds de **100 M£** ; tickets **100 000 £ – 1 M£**, ***pari passu*** ; la société **ne peut pas approcher le fonds directement** — elle doit d'abord réunir un syndicat ; exigence d'un **syndicat d'au moins 3 BA sectoriellement spécialisés, incluant un lead apportant au moins 40 000 £** ; participation publique **plafonnée à 49 % du tour** [D, repris par l'OCDE, note pays Royaume-Uni 2025] ; due diligence et termes partagés.

**[I]** Ce dispositif empile trois filtres que l'EAF n'a pas : **pluralité** (≥ 3 angels), **engagement concentré du lead** (≥ 40 k£), **plafond de participation publique**. Le deuxième est le plus important sur le plan de la théorie de l'agence : un plafond public en pourcentage ne dit **rien de la concentration** de l'exposition privée. Un tour où 40 angels mettent 1 000 £ et un tour où un lead met 40 000 £ ont le même ratio public/privé mais des propriétés de sélection radicalement différentes. **Aucune évaluation isolant l'effet propre de cette clause n'a été identifiée.**

**Pertinence transfrontalière [I]** : l'exigence de lead à engagement minimal correspond exactement à la condition documentée par Wesemann & Antretter et Mason et al. (« les angels n'investissent en transfrontalier que si des relations de confiance sont établies avec des lead investors locaux »). Un dispositif transfrontalier qui exigerait un **lead résident du pays de la cible** avec un engagement minimal transposerait cette clause à la géographie. **C'est une proposition de conception, non un dispositif observé.**

### 5.4 Synthèse comparée

| Dispositif | Contrepartie du public | Niveau du filtre | Ratio | Séniorité publique | Concentration privée imposée | Ouvert au transfrontalier ? |
|---|---|---|---|---|---|---|
| **EAF (EIF)** | L'angel, directement (CFA) | **Amont** : accréditation sur *track record* | 50:50 | *Pari passu* | Aucune | **Contractuellement 20–50 %** ; **12 % réalisé** ; compartiments nationaux mordants |
| **PFR Biznest (PL)** | Équipes de gestion VC | Amont sur le gérant + deal par le gérant | 50:50 | *Pari passu* | Via le gérant | **[?]** non tranché ; architecture nationale, devise PLN |
| **Angel CoFund (UK)** | Le syndicat, par tour | **Deal** : ≥ 3 angels + lead ≥ 40 k£ + plafond 49 % | ≤ 49 % du tour | *Pari passu* | **Oui** (lead minimal) | Non (dispositif national, hors UE) |
| **French Tech Seed (FR)** | La société, via prescripteur | **Double** : co-investisseur ≥ 30 % + prescripteur labellisé | 2 € public / 1 € privé | **Senior** (OC) | Non spécifiée | Non |

---

## 6. Contraintes de structuration d'un véhicule de co-investissement paneuropéen : trois rails, trois falaises

Toute architecture doit se loger dans l'un des trois régimes suivants. Chacun comporte un seuil produisant une discontinuité comportementale nette.

### 6.1 Rail AIFMD — la falaise de seuil (identifiée comme prioritaire par la Commission)

**[D]** Un véhicule qui **lève des capitaux auprès de plusieurs investisseurs selon une politique d'investissement définie** est un **AIF**. Les critères ESMA (2013/611) : « raising capital » (transfert ou engagement de capital par un ou plusieurs investisseurs) ; « number of investors » (une entité qualifie si ses documents constitutifs **ne comportent pas de restriction opposable** limitant la détention à un investisseur unique — indépendamment du nombre effectif) ; « defined investment policy » (politique fixée avant que les engagements ne deviennent contraignants, énoncée dans les documents constitutifs, opposable au gérant, spécifiant catégories d'actifs, stratégies, régions). Exclusions : sociétés holding, véhicules de titrisation, régimes de participation des salariés. **Zone grise** : les *joint ventures*, exclues si toutes les parties exercent un contrôle opérationnel ou si « capital providers and raisers are identical ».

**[I]** Un SPV de club deal où les angels sont pré-identifiés, décident collectivement et n'ont pas de politique d'investissement générale a des arguments pour échapper à la qualification d'AIF. **Un véhicule central et récurrent de co-investissement paneuropéen, avec politique d'investissement écrite et appels de fonds répétés, n'en a pas.** La qualification est quasi certaine. Cette lecture est une application des critères ESMA, non une position d'autorité.

**La falaise [D]** : seuils de l'article 3(2) AIFMD — **100 M€** d'encours avec levier, **500 M€** sans levier et sans droits de rachat pendant 5 ans. En dessous : **régime d'enregistrement**, exemption du gros de l'AIFMD, **mais aucun passeport de commercialisation** — celui-ci est réservé aux AIFM pleinement agréés. Le gérant sous-seuil ne peut commercialiser **que dans son État membre d'origine**, et doit sinon passer par les régimes nationaux de placement privé, État par État.

**[D]** C'est le point que les participants au dialogue du 24 mars 2026 ont explicitement mis en avant : « the need of addressing **threshold effects in the AIFMD**, and of designing a more proportionate and gradual framework for venture and growth capital funds ».

**[C] Traduction en effet de seuil concret pour le sujet traité** : un véhicule de co-investissement angel paneuropéen de taille réaliste (l'EAF entier engage 330 M€, la moyenne par CFA est de 2,75 M€) se situe **structurellement sous les seuils AIFMD**. Il est donc, par défaut, **privé du passeport** — c'est-à-dire privé de l'instrument juridique dont il aurait précisément besoin pour agréger des angels de 27 États membres. La falaise est franchie « à l'envers » : le véhicule est trop petit pour le passeport, et le passeport suppose un agrément complet dont le coût fixe est disproportionné à sa taille.

### 6.2 Rail EuVECA — le passeport existe, mais le seuil d'entrée exclut l'angel médian

**[D]** Règlement (UE) 345/2013. Gérants sous le seuil AIFMD de 500 M€ ; enregistrement, non agrément ; **passeport de commercialisation** dans toute l'UE/EEE ; **70 % du capital reçu** doit être investi en actifs qualifiants (equity/quasi-equity dans des PME jeunes et innovantes) ; **pas de levier** ; fonds propres minimum du gérant : **1/8e des frais généraux fixes de l'année précédente**, en actifs liquides.

**La falaise [D]** : les investisseurs éligibles sont les investisseurs professionnels **et** les investisseurs non professionnels — y compris explicitement les business angels — **à condition de s'engager pour au moins 100 000 €** et de signer une déclaration de connaissance des risques.

**[C] C'est l'effet de seuil le plus directement mordant du dossier.** Le seuil EuVECA de **100 000 €** représente **3,9 fois** le ticket angel moyen européen de **25 600 €** (100 000 / 25 600 = 3,91). Il représente **0,78 fois** l'investissement médian d'un angel EAF au premier tour dans **une seule** société (128 000 €) — mais il s'agit là d'angels expérimentés et sélectionnés, non représentatifs.

**[I] Conséquence mécanique** : un véhicule EuVECA **ne peut pas agréger l'angel européen médian**. Il ne peut agréger que le haut de la distribution. La *seule* structure juridique européenne offrant un passeport à un véhicule de la taille pertinente est donc, par son seuil d'entrée investisseur, **incompatible avec la population que le dispositif viserait**. Ce n'est ni un accident ni une omission : le seuil est un dispositif de protection des investisseurs. Mais il crée une contradiction structurelle qu'aucune ingénierie de véhicule ne résout à droit constant.

**Fenêtre de politique publique [D]** : la Commission a lancé le **15 janvier 2026** une consultation ciblée et une consultation publique sur les obstacles aux fonds de capital-risque et de croissance de l'UE (clôture **12 mars 2026**), en vue d'une **révision du règlement EuVECA dont l'adoption est prévue au T3 2026** ; une « initiative plus large au-delà du cadre EuVECA » couvrant un éventail plus large de gérants est également envisagée. **[D]** Ni la page de lancement de la consultation ni le compte rendu du dialogue du 24 mars 2026 ne mentionnent les business angels ou le co-investissement. **[I]** Cette absence est notable : la révision en cours porte sur les fonds, pas sur les investisseurs individuels, et le seuil de 100 000 € — le paramètre le plus mordant pour les angels — n'apparaît dans aucun document de consultation consulté.

### 6.3 Rail ECSPR — le seul passeport dont le plafond couvre l'intégralité du segment angel

**[D]** Règlement (UE) 2020/1503. Passeport **par simple notification** (article 18) : agrément dans un État membre, puis notification à l'autorité nationale des États d'accueil ; transmission à l'autorité d'accueil et à l'ESMA sous **10 jours ouvrés**. Plafond : **5 M€ par porteur de projet sur 12 mois glissants, toutes plateformes ECSP confondues** ; au-delà, bascule dans le régime MiFID/prospectus.

**[C] Le plafond de 5 M€ n'est pas mordant pour le segment angel.** Sur le sous-échantillon EBAN 2024, **67 % des tours angels sont ≤ 1 M€** et les 33 % restants sont dans la bande **1–4 M€** [D]. Le plafond ECSPR se situe **au-dessus de l'intégralité de la distribution observée des tours angels**. C'est le seul des trois rails dont le paramètre quantitatif est calibré sur le segment visé.

**[C] Mais la population par défaut du rail n'est pas la population angel.** Ticket moyen ECSPR : **660 €** tous investisseurs, **2 660 €** pour les investisseurs « sophistiqués » [D], contre **25 600 €** pour l'angel européen moyen [D] — un facteur **39×** et **9,6×** respectivement.

**[D] L'exception qui infirme cette objection** : la couche « syndicat » superposée à une plateforme ECSPR produit des tickets de taille angel. SeedBlink (troisième plateforme agréée pour l'ensemble de l'UE), qui a lancé en **juillet 2025** une solution de gestion de syndicats structurant les co-investissements via SPV ou nominee, rapporte un **ticket moyen de syndicat de 22 000 €** contre **9 080 €** de ticket moyen général sur la plateforme. **[C]** 22 000 € se situe à **86 %** du ticket angel moyen européen (22 000 / 25 600). La couche syndicat déplace le ticket d'un facteur ~2,4 par rapport au ticket moyen de la plateforme, et l'amène dans la fourchette angel.

**Autres données de plateforme [D]** (SeedBlink, rapport six ans) : **> 80 M€** sous administration ; **150+** sociétés financées ; **5,2 M€** de volume de secondaire cumulé ; **> 65 % des deals** structurés en convertibles ou SAFE ; **~70 % des tours** au stade seed.

**[I] Lecture de conception** : l'ECSPR est aujourd'hui le seul rail européen qui combine (i) un passeport réellement utilisable par une structure de petite taille, (ii) un plafond calibré au-dessus du segment angel, (iii) une infrastructure opérationnelle existante (SPV par deal, cap table, appels de fonds, reporting) et (iv) une couche syndicat produisant empiriquement des tickets de taille angel. Il ne résout **aucune** des frictions 1, 2, 6, 7, 8 — comme le montre le taux de 8 % de capital transfrontalier —, mais il élimine les frictions 3 et 5 sur le plan juridique et abaisse la friction de l'étape 5 de la chaîne de production. **Cette évaluation comparative des trois rails est ma propre synthèse ; je n'ai identifié aucune analyse publiée qui les compare sous cet angle.**

### 6.4 Contrainte d'aide d'État : la fenêtre GBER se referme fin 2026

Tout co-investissement public/UE aux côtés d'investisseurs privés est une **mesure de financement des risques** au sens de l'article 21 du RGEC (règlement 651/2014).

**[D]** Paramètres pertinents, sous réserve de vérification sur le texte consolidé :
- montant total de financement des risques **plafonné par entreprise éligible** (**15 M€** dans le texte en vigueur ; **16,5 M€** dans les projets de révision) — **[?]** les deux chiffres coexistent dans les sources ; non arbitré ;
- exigence de **participation minimale d'investisseurs privés indépendants**, graduée selon le stade de l'entreprise (**10 % / 40 % / 60 %** selon les catégories) — **[?]** les trois taux sont cités dans les sources secondaires mais n'ont pas pu être rattachés avec certitude à leurs catégories respectives dans cette session ;
- en cas de **partage asymétrique des pertes**, la **première perte assumée par l'investisseur public est plafonnée à 25 %** de l'investissement total (art. 21(10)(b)) [D].

**Fenêtre temporelle [D]** :
- le RGEC en vigueur **expire le 31 décembre 2026** ;
- la Commission a lancé le **25 février 2026** une consultation publique de 8 semaines (clôture fin avril 2026) sur un **projet de RGEC 2027-2034** ;
- adoption prévue **fin 2026**, entrée en vigueur **1er janvier 2027** ;
- le projet introduit notamment un cadre plus clair pour les startups et entreprises innovantes, une catégorie *small mid-cap* élargie, plus de souplesse pour les investissements de suivi et des **seuils d'éligibilité au financement des risques abaissés**.

**[I] Implication opérationnelle** : un dispositif de co-investissement angel européen conçu en 2026-2027 se calera sur le **nouveau** RGEC, dont les paramètres sont en cours de fixation. Deux paramètres conditionnent directement la faisabilité du design décrit en § 7 : (i) le **taux minimal de participation privée**, qui détermine si un ratio 1:1 (50 %) est autorisé au stade pre-seed ; (ii) le **plafond de première perte à 25 %**, qui limite la possibilité de subventionner spécifiquement le risque transfrontalier par une asymétrie de partage des pertes. **[I]** Ce second point est important et rarement relevé : si l'on voulait compenser le surcoût transfrontalier par un partage asymétrique plutôt que par un ratio d'appariement plus élevé, le plafond de 25 % borne l'ampleur de la compensation possible. **Déduction de la structure du texte, non un avis juridique.**

---

## 7. Points de friction et effets de seuil — synthèse

| Friction / seuil | Mécanisme précis | Ordre de grandeur | Fiabilité |
|---|---|---|---|
| **Coût fixe de véhicule** | SPV par deal ; minimum de facturation mordant sous 500 k€ levés | **5,0 %** du montant à 100 k€ levés ; **19,5 %** du ticket d'un angel isolé | [D] tarif ; [C] ratios |
| **Seuil investisseur EuVECA** | 100 000 € d'engagement minimum pour un non-professionnel | **3,9×** le ticket angel moyen européen → exclut l'angel médian du seul rail passeporté de taille adaptée | [D] règle ; [C] ratio |
| **Falaise AIFMD** | Passeport réservé aux AIFM agréés ; seuils 100 M€ / 500 M€ | Un véhicule angel réaliste (CFA moyen EAF : 2,75 M€) est **structurellement sous-seuil**, donc sans passeport | [D] règle ; [C] taille |
| **Plafond ECSPR** | 5 M€ par projet / 12 mois | **Non mordant** : au-dessus de 100 % de la distribution observée des tours angels (67 % ≤ 1 M€ ; reste 1–4 M€) | [D] ; [C] |
| **Compartimentage EAF** | 9 compartiments nationaux, tous dans des écosystèmes matures | **0 compartiment** dans les 11 États membres de la CEE (~22 % de la population UE) | [D] périmètre ; [C] complémentaire |
| **Biais domestique résiduel** | Après levée de la contrainte contractuelle (EAF) | **12 %** de transfrontalier réalisé contre **20–50 %** autorisés | [D] |
| **Biais domestique résiduel** | Après levée de la contrainte réglementaire (ECSPR) | **8 %** du capital levé provient d'un autre pays que celui du prestataire | [D] |
| **Non-portabilité fiscale** | Résidence de l'investisseur ET/OU établissement de la cible | Matrice irrégulière ; certains couples à **subvention nulle** (DE→FR) et d'autres **doublement subventionnés** (FR→DE) | [D] règles ; [C] matrice |
| **Marge extensive vs intensive** | Le levier fiscal agit sur l'allocation, pas sur la sélection | Résultat qualitatif unanime sur 21 entretiens semi-directifs | [D] |
| **Devise** | 4 des principaux marchés cibles hors zone euro | PL, RO, CZ, HU ; la Pologne seule = **39 %** de la valeur investie en CEE | [D] ; [C] |
| **Profondeur de sortie** | Queue droite tronquée | Sorties VC CEE : **51 M€ / 39 sociétés** (au coût historique) ; **4 IPO** ; **3,8 %** de la valeur des sorties européennes | [D] |
| **Relocalisation** | La voie de liquidité passe par le départ du siège | **48 %** des scale-ups CEE ont relocalisé leur siège | [D] |
| **Forme notariée** | Cessions de parts et augmentations de capital (DE et al.) | Coût et délai fixes par opération ; **supprimée pour l'EU Inc.** si adoptée | [D] règle ; [D] proposition |
| **Distance et rendement** | Relation en **U inversé** | La prime transfrontalière doit être **plate au-delà de la frontière**, non croissante avec la distance | [D] résultat ; [I] corollaire de conception |

---

## 8. Ce qu'un mécanisme de co-investissement peut, et ne peut pas, corriger

| Friction | Corrigeable par un dispositif de co-investissement ? | Mécanisme requis | Fiabilité |
|---|---|---|---|
| **1. Sourcing / flux de deals** | **Non directement** | Seulement par conditionnalité (syndicat, réseau accrédité, lead local) ; le modèle « chapter » est le seul mécanisme documenté comme efficace | [D] pour le modèle chapter ; [I] pour la conditionnalité |
| **2. Due diligence** | **Partiellement** | Mutualisation de la DD vérifiable ; le jugement sur les intangibles n'est pas transférable | [I] |
| **3. Droit des sociétés / pactes** | **Non — mais traité ailleurs** | L'EU Inc. (COM(2026) 321) supprime les formalités notariées de cession ; hors du champ d'un dispositif financier | [D] |
| **4. Non-portabilité fiscale** | **Non** | Compétence nationale ; un co-investissement peut **compenser** l'écart de subvention mais pas le **porter** | [D] pour la compétence ; [I] pour la compensation |
| **5. Compartimentage national des dispositifs publics** | **Oui — c'est le seul cas où le dispositif est lui-même le problème** | Financement au niveau de l'Union, seul niveau pouvant subventionner un flux sortant | [D] pour le constat ; [I] pour la solution |
| **6. Devise** | **Non** | Pari passu partage le risque de change, ne le supprime pas | [I] |
| **7. Profondeur de sortie** | **Marginalement** | Baisse le coût d'entrée, ne modifie pas la distribution des issues ; un rendement espéré plus faible n'est pas compensé par un partage de risque symétrique | [I] |
| **8. Asymétrie d'information / confiance** | **Oui, indirectement — c'est le levier le mieux documenté** | Via trois variables observables *ex ante* : taille du syndicat, présence d'un lead local, expérience de l'investisseur | **[D]** pour les trois effets ; [I] pour leur usage comme critères |

**Conclusion analytique.** Sur huit frictions, un dispositif de co-investissement en agit **directement et de façon documentée sur une seule** (friction 5, où le dispositif public existant est lui-même la cause), et **indirectement, via des critères d'éligibilité dont l'effet est documenté, sur une seconde** (friction 8). Les six autres relèvent soit d'autres instruments (fiscalité, droit des sociétés, union des marchés de capitaux), soit d'aucun instrument disponible (devise, profondeur de sortie, jugement humain).

**[I]** Cela n'invalide pas l'idée d'un dispositif : cela en fixe l'ambition réaliste. Un dispositif dont le mécanisme d'action revendiqué est « rendre le transfrontalier moins cher » agira sur une part minoritaire de la fonction de coût, et les deux quasi-expériences du § 3 prédisent un effet faible. Un dispositif dont le mécanisme d'action revendiqué est « conditionner l'euro public à la présence d'un syndicat comportant un lead résident du pays cible » agit sur la variable dont l'effet transfrontalier est le mieux établi dans la littérature. **La différence entre ces deux théories du changement est la question de conception centrale du dossier.**

---

## 9. Lacunes de données identifiées

Points sur lesquels aucune donnée fiable n'a pu être établie et qui doivent être traités comme **inconnus**, non comme approximations :

1. **La taille réelle du marché angel européen.** EBAN a abandonné le multiplicateur ×10 sans lui substituer d'estimation [D]. Le chiffre de 1,22 Md€ (2024) ne couvre que le marché « visible ». Le chiffre institutionnel de « 7,5 Md€/an » est **[?]** et incompatible avec le marché visible.
2. **Aucun compendium EBAN 2025 publié au 1er septembre 2026** ; les données angel les plus récentes ont 20 mois.
3. **Les montants d'investissement angel par pays cible (PL, RO, BG, HU, CZ, SK, HR, SI, Baltes)** n'ont pas pu être extraits : le PDF du compendium EBAN 2024 est composé d'images non extractibles dans cette session, et aucune reprise secondaire fiable n'a été identifiée. **C'est la lacune la plus gênante pour calibrer le dispositif** : on ne connaît pas la taille de la population d'angels des pays cibles, donc ni le potentiel d'appariement local, ni le nombre de leads locaux mobilisables.
4. **La part transfrontalière du marché angel européen dans son ensemble.** Les deux chiffres robustes (12 % EAF, 8 % ECSPR) portent sur des populations sélectionnées, non représentatives, et biaisées dans des directions indéterminées.
5. **L'éligibilité des angels non-résidents aux dispositifs nationaux de co-investissement des pays cibles** (PFR Biznest notamment) : page primaire inaccessible, question non tranchée.
6. **La taille et la performance du compartiment paneuropéen de l'EAF** : aucune donnée publique. C'est pourtant le seul compartiment explicitement transfrontalier, donc le seul dont l'expérience serait directement informative.
7. **Les données de performance/sortie du portefeuille EAF** : le working paper EIF 2020/62 s'arrête aux données 2019 et à la croissance post-investissement ; **aucune donnée de rendement réalisé n'est publiée**, et aucune ventilation entre premiers investissements et tours de suivi.
8. **Les paramètres exacts de l'article 21 du RGEC** (plafond 15 vs 16,5 M€ ; rattachement des taux 10 %/40 %/60 % à leurs catégories) n'ont pas pu être vérifiés sur le texte consolidé (EUR-Lex et Lexparency inaccessibles ou en 503 lors de cette session).
9. **Le texte primaire de COM(2026) 321 final** (EU Inc.) n'a pas pu être extrait (PDF image) ; les paramètres cités proviennent de synthèses de cabinets.
10. **Aucune évaluation causale d'un dispositif de co-investissement angel européen** n'existe, ni d'évaluation isolant l'effet propre d'une caractéristique de conception (lead minimal, pluralité, plafond de participation, accréditation *ex ante*).
11. **Le coût réel de conversion d'une société nationale existante en EU Inc.** — déterminant pour savoir si le 28e régime bénéficiera au stock de startups des pays cibles ou seulement au flux.

---

## Sources

**Statistiques de marché — angels et early stage**
- [EBAN, *Statistics Compendium 2024 — European Early Stage Market Statistics*](https://www.eban.org/wp-content/uploads/2025/12/Stats-Compendium-2024.pdf) (données 2024 ; PDF image, non ré-extractible ; chiffres repris de l'extraction du 07/08/2026)
- [EBAN, page publications](https://www.eban.org/eban-publications/) — confirmation qu'aucune édition 2025 n'est publiée au 01/09/2026

**Statistiques de marché — VC et écosystèmes cibles**
- [Invest Europe, *Investing in Europe: Private Equity Activity 2025*](https://www.investeurope.eu/publications-policy/publications/2026/investing-in-europe-private-equity-activity-2025/) (publié 07/05/2026)
- [Invest Europe, *2025 Central and Eastern Europe Private Equity Statistics*](https://www.investeurope.eu/publications-policy/publications/2026/2025-central-and-eastern-europe-private-equity-statistics/)
- [0100 Conferences, *CEE Private Markets 2025: The Mid-Market Is Winning, the Gap Remains*](https://0100conferences.substack.com/p/cee-private-markets-2025-the-mid) (reprise chiffrée détaillée des statistiques Invest Europe CEE 2025)
- [Dealroom, *Central and Eastern European startups — 2025 in review*](https://dealroom.co/reports/central-and-eastern-european-startups-2025-in-review)
- [Vestbee, *VC funding in CEE report Q2 2026*](https://www.vestbee.com/insights/articles/vc-funding-in-cee-report-q2-2026) et [*Q1 2026*](https://www.vestbee.com/insights/articles/vc-funding-in-cee-report-q1-2026)
- [Vestbee, *VC exits in CEE: how investors are navigating a liquidity crunch*](https://www.vestbee.com/insights/articles/vc-exits-in-cee-how-investors-are-navigating-a-liquidity-crunch)
- [Vestbee, *CEE unicorns 2025*](https://www.vestbee.com/insights/articles/cee-unicorns-2025-report)
- [The Recursive, *Eastern Europe's venture market holds steady at €3.6B in 2025*](https://therecursive.com/eastern-europe-s-venture-market-holds-steady-at-e3-6b-in-2025-as-deal-count-falls/) (accès partiel, paywall)
- [Atomico / HSBC Innovation Banking, *State of European Tech 2025*](https://www.hsbcinnovationbanking.com/gb/en/resources/state-of-european-tech)

**Dispositifs de co-investissement**
- [Gvetadze, Pal & Torfs, *The Business Angel portfolio under the European Angels Fund: An empirical analysis*, EIF Working Paper 2020/62](https://www.econstor.eu/bitstream/10419/213873/1/1689254033.pdf) — source primaire des données de biais domestique du portefeuille EAF
- [EIF, European Angels Fund](https://www.eif.org/what_we_do/equity/eaf/index.htm) (HTTP 403 lors de cette session ; paramètres via reprises secondaires convergentes) ; [EAF Finlande](https://www.eif.org/what_we_do/equity/eaf/Finland.htm) ; [EAF Irlande](https://www.eif.org/what_we_do/equity/eaf/Ireland.htm)
- [Your Europe / Commission européenne, *European Angels Fund S.C.A. SICAR — Pan-European Compartment*](https://youreurope.europa.eu/business/finance-funding/getting-funding/access-finance/en/content/european-angels-fund-sca-sicar-pan-european-compartment-0)
- [PFR Ventures, *PFR Biznest*](https://pfrventures.pl/en/program-dla-vc/pfr-biznest) (HTTP 403 ; données via communiqués PFR) ; [communiqué de lancement PFR Biznest FIZ](https://media.pfr.pl//17060-pfr-ventures-launches-pfr-biznest-fiz)
- [ACF Investors / Angel CoFund](https://www.acfinvestors.com/) ; [OCDE, *Benchmarking government support for venture capital — country note: United Kingdom* (2025)](https://www.oecd.org/content/dam/oecd/en/publications/reports/2025/06/benchmarking-government-support-for-venture-capital-country-notes_2cacbf3f/united-kingdom_3c219488/5454ad97-en.pdf)
- [EIC / ESIL — *Early Stage Investing Launchpad*](https://www.europeanesil.eu/) et [annonce du programme de formation en Tchéquie, Hongrie, Roumanie et Pologne](https://eic.ec.europa.eu/news/join-effective-angel-investing-training-programme-czechia-hungary-romania-and-poland-2024-10-15_en)

**Cadre réglementaire européen**
- [ESMA, *Guidelines on key concepts of the AIFMD*, ESMA/2013/611](https://www.esma.europa.eu/sites/default/files/library/2015/11/2013-611_guidelines_on_key_concepts_of_the_aifmd_-_en.pdf) ; [Linklaters, *Scope — Definition of AIF*](https://www.linklaters.com/en/insights/publications/aifmd/scope--definition-of-aif)
- [CSSF, *EuVECA and EuSEF*](https://www.cssf.lu/en/euveca-and-eusef/) ; [Pinsent Masons, *European venture capital funds*](https://www.pinsentmasons.com/out-law/guides/european-venture-capital-funds-facilitate-capital-raising-eu) ; [EUR-Lex, résumé EuVECA](https://eur-lex.europa.eu/EN/legal-content/summary/european-venture-capital-funds.html)
- [ESMA, *Market Report: Crowdfunding in the EU 2025*](https://www.esma.europa.eu/document/market-report-crowdfunding-eu-2025) et [*Crowdfunding in the EU 2024*](https://www.esma.europa.eu/sites/default/files/2025-01/ESMA50-2085271018-4039_ESMA_Market_Report_-_Crowdfunding_in_the_EU_2024.pdf) ; synthèse chiffrée : [Turbo Crowd](https://www.turbocrowd.it/en/crowdfunding-in-europe-esma/)
- [Commission européenne, *Commission seeks input for venture and growth capital funds reform*, 15/01/2026](https://finance.ec.europa.eu/news/commission-seeks-input-venture-and-growth-capital-funds-reform-2026-01-15_en)
- [Commission européenne, *Implementation dialogue on European venture and growth capital funds*, 24/03/2026](https://finance.ec.europa.eu/events/implementation-dialogue-european-venture-and-growth-capital-funds-commissioner-maria-luis-2026-03-24_en)
- [Commission européenne, COM(2026) 321 final — proposition « EU Inc. » / 28e régime, 18/03/2026](https://commission.europa.eu/document/download/3e9822aa-8cef-40a1-904e-a53fc68e7265_en) (PDF image, non extrait) ; synthèses : [Eubelius](https://www.eubelius.com/en/news/the-eu-inc-the-european-commissions-proposal-for-a-28th-corporate-regime), [Parlement européen — Legislative Train](https://www.europarl.europa.eu/legislative-train/theme-a-new-plan-for-europe-s-sustainable-prosperity-and-competitiveness/file-28th-regime-for-innovative-companies)
- [Commission européenne, *GBER review*](https://competition-policy.ec.europa.eu/state-aid/gber-review_en) ; [Invest Europe, *Position on the draft 2027-2034 GBER*, 17/04/2026](https://www.investeurope.eu/media/fzqedmy2/20260417-revised-gber-from-2027-to-2034-invest-europe-position-final.pdf) ; [art. 21 RGEC](https://lexparency.org/eu/32014R0651/ART_21/) (HTTP 503 lors de cette session)
- [Parlement européen, *Bulgaria to adopt the euro on 1 January 2026*](https://www.europarl.europa.eu/thinktank/en/document/EPRS_ATA(2025)775850) ; [BCE, *Bulgaria adopts the euro*](https://www.ecb.europa.eu/press/economic-bulletin/focus/2026/html/ecb.ebbox202508_01~b4379b735b.en.html)
- Commission européenne, *EU Startup and Scaleup Strategy*, COM(2025) 270 final, 28/05/2025 — [document officiel](https://research-and-innovation.ec.europa.eu/document/download/2f76a0df-b09b-47c2-949c-800c30e4c530_en) (extraction infructueuse) ; mesure « soutien aux business angels européens et à leurs réseaux » annoncée pour **2026**, sans annonce d'instrument identifiée au 01/09/2026

**Littérature académique**
- [Mason, C., Botelho, T. & Duggett, J. (2022), « Promoting cross-border investing by business angels in the European Union », *Regional Studies* 56(8), 1391-1403](https://eprints.gla.ac.uk/247233/1/247233.pdf) (accès libre)
- [Wesemann, H. & Antretter, T. (2023), « The internationalization of business angel networks: do syndicates increase cross-border investment returns? », *Venture Capital* 25(4), 487-514](https://www.tandfonline.com/doi/full/10.1080/13691066.2022.2082898) (résumé via [RePEc](https://ideas.repec.org/a/taf/veecee/v25y2023i4p487-514.html))
- [Croce, A., Schwienbacher, A. & Ughetto, E. (2023), « Internationalization of business angel investments: The role of investor experience », *International Business Review* 32(1), 102033](https://www.sciencedirect.com/science/article/abs/pii/S0969593122000610) (résumé via [RePEc](https://ideas.repec.org/a/eee/iburev/v32y2023i1s0969593122000610.html))
- [Kraemer-Eis, H., Botsari, A., Brault, J. & Lang, F. (2019), *EIF Business Angels Survey 2019*, EIF Working Paper 2019/60](https://www.econstor.eu/handle/10419/207134)

**Infrastructure de marché et coûts de structuration**
- [Roundtable, *SPV*](https://www.roundtable.eu/spv) et [calculateur tarifaire](https://www.roundtable.eu/pricing-calculator) — 1 % du montant levé, minimum 5 000 € HT
- [SeedBlink, rapport six ans](https://seedblink.com/blog/six-years-annual-report-seedblink) ; [lancement des syndicats, juillet 2025](https://seedblink.com/press-room/seedblink-launches-syndicates-for-investment-clubs-and-private-investors)
- [Auptimate, *SPV costs in 2026*](https://auptimate.com/resources/spv-costs-update/) — **[?]** fourchettes indicatives de prestataire
- [PwC Tax Summaries, Luxembourg — Income determination](https://taxsummaries.pwc.com/luxembourg/corporate/income-determination) — régime d'exonération des participations (seuils 10 % / 6 M€ / 12 mois)
