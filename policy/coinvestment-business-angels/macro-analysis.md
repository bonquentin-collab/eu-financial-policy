# Analyse macro-financière — Un dispositif de co-investissement transfrontalier pour les business angels dans l'UE

**Agent :** `macro-financial-analyst`
**Date :** 1er septembre 2026
**Question traitée :** quels effets agrégés attendre d'un mécanisme de co-investissement destiné à faire investir des business angels de pays « sources » (capital angel abondant) dans des start-up de pays « cibles » (écosystèmes moins capitalisés mais riches en projets), et quelles contraintes l'analyse agrégée impose-t-elle à un tel mécanisme.

**Périmètre :** asymétries géographiques agrégées, biais domestique, effets systémiques, stabilité macroprudentielle, positionnement contre les objectifs UMC/UEE et de compétitivité.
**Hors périmètre :** état du droit applicable (`current-regulation-analyst`), rationalité de l'investisseur individuel et économie d'un deal (`micro-financial-analyst`), design détaillé de l'instrument (`policy-innovator`). La section 7 formule des *contraintes* issues des données agrégées, pas des propositions.

**Document autonome.** Il reprend, en les revérifiant ou en signalant explicitement l'absence de revérification, certains éléments de `policy/macro-analysis.md` (7 août 2026), dont l'objet était plus large (efficience de l'investissement angel en Europe) et non le transfrontalier.

---

## 0. Avertissement méthodologique — à lire avant toute quantification

**(a) Le marché angel n'est pas mesuré, il est estimé.** EBAN, seule source paneuropéenne annuelle, indique que le marché angel est « difficile à quantifier précisément », qu'une part significative des investissements n'est pas déclarée, et que son Compendium sous-estime l'activité réelle. Le multiplicateur ×10 historiquement appliqué au « marché visible » (issu d'une étude CSES de 2012 pour la Commission) a été **retiré** des éditions récentes, sans substitut publié. Toute quantification du marché angel européen porte donc sur un périmètre visible dont le taux de couverture est **inconnu**. Ceci vaut *a fortiori* pour toute décomposition géographique de ce marché.

**(b) Ce que je n'ai pas pu vérifier dans cette recherche.** L'extraction de texte des PDF a échoué systématiquement dans l'environnement d'exécution (poppler absent ; réponses HTTP 403 de `eif.org`, `tandfonline.com`, `investeurope.eu`, `sifted.eu`, `pitchbook.com` ; PDF non décodables pour EBAN 2024, Invest Europe 2025, EIF WP 2020/62, profils pays du Tableau de bord européen de l'innovation). Plusieurs données ci-dessous proviennent donc de **résumés d'index de recherche ou de sources secondaires**, ce qui est signalé au cas par cas et récapitulé en §9. Les tableaux pays construits à partir de Dealroom (§1.2) proviennent en revanche de pages HTML consultées directement.

**(c) Les « écarts de financement » sont des construits de modèle.** Les chiffrages UE/US en circulation (0,2 % vs 0,7 % du PIB ; 0,3 % vs « plus du triple ») reposent sur des périmètres, sources commerciales et années différents et ne sont pas réconciliables. Ils sont donnés en fourchettes attribuées.

**(d) Le mot « startup » n'a pas de définition statistique officielle.** Il n'existe aucun registre public paneuropéen des start-up. Les comptages par pays utilisés en §1.2 sont ceux d'un fournisseur commercial (Dealroom), fondés sur la détection d'entreprises ayant levé des fonds. Ils mesurent donc un **stock d'entreprises déjà financées**, ce qui biaise mécaniquement à la baisse les pays où le financement est rare — biais qui joue *contre* la thèse défendue ici et rend la comparaison conservatrice.

---

## 1. L'asymétrie géographique : quantification

### 1.1 Le capital angel visible est concentré sur trois à cinq pays

| Pays | Investissement angel visible 2023 (M€) | 2024 (M€) |
|---|---|---|
| Royaume-Uni *(hors UE)* | 307,4 | 291,3 |
| Allemagne | 198,5 | 162,3 |
| France | 142,5 | 130,7 |
| Espagne | 69,8 | n.d. |
| Italie | 62,9 | n.d. |
| **Total marché visible (38-39 pays européens)** | **1 255** | **1 220** |

*Sources : EBAN, Statistics Compendium, données 2023 reprises via Statista (top 5) ; données 2024 (total et top 3) reprises de l'analyse antérieure du 7 août 2026, le PDF n'ayant pas pu être rouvert.*

Calculs propres à partir de ce tableau :
- **Top 5 = 62 % du marché visible européen en 2023** ; **top 3 = 52 %**.
- En 2024, le top 3 représente **48 %** du total.
- Hors Royaume-Uni, le marché visible européen est d'environ **929 M€ en 2024**, dont **293 M€ (31,5 %) pour l'Allemagne et la France seules**.

Ordre de grandeur du reste : les 34 à 36 autres pays couverts se partagent environ **630 M€ par an**, soit une moyenne inférieure à **20 M€ par pays et par an** de capital angel visible. Les seuls mouvements pays documentés pour 2024 sont des reculs marqués en **Estonie (−41 %)**, **Bulgarie (−74 %)** et **Turquie (−39 %)**, avec des hausses agrégées en Europe centrale et orientale et dans certains pays nordiques (Finlande, Norvège, Suède).

*Confiance : moyenne sur les niveaux (source unique, auto-déclarative, incohérences internes connues) ; **élevée sur le degré de concentration**, qui est robuste à toute correction plausible du périmètre.*

### 1.2 Les pays cibles ont le vivier, pas le capital — quantification

C'est le cœur du dossier. Comparaison sur données homogènes (même fournisseur, même date de consultation, 1er septembre 2026) :

| | Vivier de start-up financées | dont pre-seed | dont seed | **Vivier pre-seed + seed** | VC investi (M$) | Population (M) |
|---|---|---|---|---|---|---|
| **Pays « sources »** | | | | | | |
| Suède | 2 621 | 940 | 800 | **1 740** | 3 500 | 10,6 |
| Pays-Bas | 2 810 | 1 117 | 832 | **1 949** | 3 500 | 18,0 |
| *Sous-total* | *5 431* | | | ***3 689*** | *7 000* | *28,6* |
| **Pays « cibles »** | | | | | | |
| Espagne | 3 727 | 1 796 | 1 080 | **2 876** | 3 300 | 49,1 |
| Italie | 2 119 | 991 | 643 | **1 634** | 1 800 | 59,0 |
| Pologne | 1 140 | 607 | 298 | **905** | 393 | 36,5 |
| Portugal | 605 | 276 | 166 | **442** | 518 | 10,6 |
| Roumanie | 341 | 171 | 106 | **277** | 143 | 19,0 |
| *Sous-total* | *7 932* | | | ***6 134*** | *6 154* | *174,2* |

*Sources : Dealroom, profils pays, consultés le 1er septembre 2026 (période exacte du champ « VC invested » non précisée par la source — vraisemblablement 12 mois glissants ; voir §9). Populations : ordres de grandeur Eurostat 2025.*

Ratios calculés (calculs propres) :

| Indicateur | Sources (SE+NL) | Cibles (ES+IT+PL+PT+RO) | Rapport |
|---|---|---|---|
| Entreprises au stade pre-seed/seed | 3 689 | **6 134** | **0,60×** (les cibles en ont 1,66 fois plus) |
| VC investi (M$) | 7 000 | 6 154 | 1,14× |
| **VC par habitant ($)** | **245** | **35** | **7,0×** |
| VC par start-up financée (M$) | 1,29 | 0,78 | 1,65× |

**Trois lectures, dans l'ordre de robustesse décroissante :**

1. **Le vivier existe et il est plus grand dans les pays cibles.** Cinq pays cibles totalisant 174 millions d'habitants comptent environ **6 100 entreprises au stade pre-seed/seed** — le segment exactement adressé par l'investissement angel — contre **3 700** pour deux pays sources totalisant 28,6 millions d'habitants. L'Espagne compte à elle seule **plus de start-up financées (3 727) que la Suède (2 621)** avec un volume de VC inférieur. *(Confiance : moyenne-élevée — le sens de l'écart est robuste ; les niveaux dépendent de la couverture du fournisseur.)*

2. **L'écart d'intensité capitalistique est massif rapporté à la population (7×) mais modéré rapporté au nombre d'entreprises financées (1,65×).** Ce second résultat est important et va contre une lecture naïve du dossier : les entreprises des pays cibles *qui parviennent à se financer* ne sont pas dramatiquement sous-dotées par tour ; c'est la **densité de projets financés par habitant** qui est faible. La contrainte s'exerce donc davantage sur la **sélection à l'entrée** — combien de projets trouvent un premier investisseur — que sur la taille du chèque. C'est précisément le point où un investisseur angel supplémentaire agit. *(Confiance : moyenne — sensible au biais de mesure décrit en §0(d), qui joue dans le sens d'une sous-estimation du vivier des pays cibles.)*

3. **Confirmation par des sources indépendantes.** Le capital-investissement en Europe centrale et orientale s'établit à **675 M€ de VC en 2025** selon Invest Europe (périmètre : opérations des gérants membres), soit environ **3,4 % des 20 Md€ de VC européen** de la même source, pour une région d'environ 100 millions d'habitants. Sur un périmètre plus large (toutes transactions, source Dealroom), la CEE totalise **3,8 milliers de start-up financées**, **243 Md€ de valeur d'entreprise cumulée** et **2,3 Md€ de VC en 2024**. Aucun pays d'Europe centrale, orientale ou balte ne figure dans le top 10 européen des investissements tech en 2025 (RU 21,5 Md€, DE 11,5 Md€, FR 8,7 Md€, puis NL, SE, CH, FI 2,9 Md€, IT, ES, et l'Ukraine à 944 M€, sur un total européen de 72 Md€). *(Confiance : élevée sur la structure ; les trois périmètres ne sont pas réconciliables entre eux — voir §9.)*

### 1.3 Dans les pays cibles, le capital d'amorçage est presque intégralement local

Donnée la plus directement pertinente pour le sujet, et la plus tranchée :

> **Les dix investisseurs les plus actifs au stade pre-seed/seed en Europe centrale et orientale depuis 2020 sont, sans exception, des acteurs locaux. À partir de la série B, cinq des dix plus actifs sont des fonds américains.**
> *Dealroom, « Central and Eastern European Startups 2025 ».*

Autrement dit : les écosystèmes cibles sont **ouverts au capital étranger en aval et fermés en amont**. Le capital transfrontalier arrive — mais tard, et depuis les États-Unis, pas depuis les pays voisins de l'UE. La même source relève que **48 % des scale-up de la CEE ont déplacé leur siège hors de leur pays d'origine, dont 56 % vers les États-Unis**.

La BCE documente le même phénomène côté investisseurs : les petits écosystèmes développés comme l'Estonie sont « fortement dominés par les investisseurs américains », les start-up qui réussissent ciblant tôt une expansion mondiale et recherchant des investisseurs « aux poches plus profondes, à l'expertise sectorielle et à l'accès aux réseaux internationaux ».

**Implication centrale :** le déficit transfrontalier des pays cibles n'est pas un déficit de capital étranger *en général*, c'est un déficit de capital **intra-européen et précoce**. C'est un segment que ni le VC américain ni les instruments européens de croissance ne desservent, et c'est le seul segment où l'argument d'un dispositif dédié tient. *(Confiance : élevée sur le constat qualitatif ; moyenne sur les parts exactes — source commerciale unique pour le classement des investisseurs les plus actifs.)*

---

## 2. Le biais domestique : où il se situe réellement, et pourquoi l'angel en est le cas extrême

### 2.1 Au niveau du VC européen, le biais domestique n'est pas là où on le croit

Résultat contre-intuitif mais bien établi, qu'il faut poser avant de raisonner sur l'angel :

- **Plus de 50 % des investissements totaux des fonds VC localisés dans l'UE sont réalisés dans des entreprises situées hors de l'UE**, contre **environ 20 %** pour les fonds américains investissant hors des États-Unis [BCE, *Financial Integration and Structure in the Euro Area*, encadré « Exploring the investor landscape for venture capital », mai 2026, d'après PitchBook].
- **≈ 70 %** des *limited partners* établis dans l'UE souscrivent à des fonds localisés dans l'UE, contre **82 %** des LP américains souscrivant à des fonds américains [même source]. **Les LP américains sont donc *plus* domestiques que les européens.**
- Le FMI : « Les frontières nationales sont *moins* un obstacle pour les fonds VC lorsqu'ils investissent dans des start-up que lorsqu'ils lèvent des capitaux » [IMF WP/24/146, §29].
- L'analyse de réseau de la BCE conclut à une intégration limitée des investisseurs à travers l'Europe, l'**EIF jouant le rôle de hub central**, et l'activité transfrontalière passant essentiellement par le Luxembourg et l'Irlande.

**Conséquence pour ce dossier :** l'argument « le VC européen est cloisonné par les frontières » est faux au niveau du déploiement institutionnel. Il ne peut pas être recyclé tel quel pour justifier un dispositif angel. Le biais domestique de l'angel doit être démontré **pour lui-même**.

### 2.2 Le segment angel : la localité y est intrinsèque, et mesurée

| Fait | Valeur | Source |
|---|---|---|
| Part transfrontalière des investissements des angels partenaires de l'EIF | **12 %** | EIF WP 2020/062 (Gvetadze, Pal & Torfs), repris par Mason, Botelho & Duggett (2022) |
| Ticket moyen par investisseur et par tour | **≈ 25 600 €** | EBAN 2024 |
| Investissement moyen par entreprise (tour angel) | **≈ 204 900 €** | EBAN 2024 |
| Angels ayant accru ou anticipant d'accroître leurs investissements transfrontaliers | **≈ 4 sur 10** (autant déclarant l'inverse) | EIF *Business Angels Survey* 2019, n = 60 |

Le contraste avec le VC institutionnel (§2.1) est net : **12 % de transfrontalier pour l'angel contre ≈ 40 % de transfrontalier intra-européen pour le VC**. Et ces 12 % sont mesurés sur une population **sélectionnée par le haut** — les angels partenaires de l'EIF, c'est-à-dire les plus professionnalisés du marché européen. Le taux du marché angel dans son ensemble est vraisemblablement inférieur, sans qu'il soit possible de le chiffrer.

L'explication n'est pas mystérieuse et elle est arithmétique : sur un ticket de 25 600 €, **tout coût fixe de diligence, de structuration juridique, de fiscalité ou de suivi transfrontalier est prohibitif**, indépendamment de la qualité du projet. La littérature attribue de longue date le biais domestique du financement en fonds propres au « temps et à l'effort nécessaires pour surveiller une entreprise distante » — coût qui croît avec la distance et décroît avec la taille du ticket, donc **maximal pour l'angel**.

### 2.3 Trois barrières documentées, dans l'ordre où la littérature les classe

La seule étude académique dédiée à la question exacte du sujet — Mason, Botelho & Duggett, « Promoting cross-border investing by business angels in the European Union », *Regional Studies*, 56(8), 2022, pp. 1391-1403 — identifie trois contraintes :

1. **L'absence d'information sur les opportunités transfrontalières** (déficit de deal flow structuré) ;
2. **La préférence des angels pour l'investissement local** (préférence révélée, liée au coût de monitoring et à la valeur ajoutée opérationnelle qu'ils apportent) ;
3. **La territorialité des incitations fiscales** : les avantages fiscaux ne sont ouverts qu'aux investissements réalisés dans le pays de l'investisseur.

Les auteurs relèvent que l'extension des incitations fiscales aux investissements dans d'autres États membres est une piste, mais **politiquement contestée** (« bénéficier à des entreprises étrangères »), et proposent des mécanismes relationnels — modèles de « chapitres » de groupes d'angels opérant sous une marque commune avec des gestionnaires locaux.

Élément de contexte quantitatif sur la barrière fiscale : **46 dispositifs** d'incitation fiscale distincts recensés dans l'UE-28, avec un contraste marqué entre **9 des 15 « anciens » États membres** dotés d'incitations et **3 seulement des 13 autres** [Commission, TAXUD/2015/DE/330, 2017]. La fragmentation fiscale n'est donc pas neutre géographiquement : **elle est elle-même concentrée dans les pays sources**, ce qui aggrave l'asymétrie plutôt que de la compenser. Pour ordre de grandeur du coût d'opportunité pour l'investisseur, le dispositif français IR-PME offre une réduction de **18 %, majorée à 25 %** [IGF, octobre 2023] : un angel français investissant dans une start-up polonaise renonce donc à un avantage de l'ordre du quart de son investissement.

**Point de preuve manquant, à dire explicitement :** aucune source institutionnelle consultée — Commission, EIF, BCE, FMI, OCDE, ESRB — ne produit d'estimation quantifiée du **montant de flux angel transfrontaliers perdus** du fait de ces barrières. Ce chiffrage n'existe pas. *(Confiance : élevée sur cette absence, après recherche ciblée dans le présent travail et dans l'analyse antérieure.)*

### 2.4 Le biais domestique est *institutionnalisé* par la conception des instruments publics existants

C'est le constat le plus opérationnel de cette analyse, et il est peu relevé dans le débat.

**(a) L'European Angels Fund (EAF) de l'EIF est structuré en compartiments nationaux.** L'EIF le reconnaît explicitement : « L'European Angels Fund est structuré autour de compartiments nationaux en collaboration avec les institutions nationales de promotion, **les investissements transfrontaliers sont donc limités par les exigences de mandat**. Le compartiment paneuropéen récemment lancé encourage les stratégies transfrontalières » [EIF WP 2019/060]. Le taux de 12 % de transfrontalier (§2.2) est donc en partie un **artefact du design de l'instrument**, pas seulement une préférence des investisseurs.

**(b) La couverture géographique de l'EAF reproduit exactement la carte de la concentration.** Volume total supérieur à **800 M€**, plus de **330 M€ engagés** auprès de plus de **120 business angels**, pour plus de **800 co-investissements** en PME. Programmes nationaux dédiés : **Autriche, Belgique (Flandre), Danemark, Finlande, Allemagne, Irlande, Italie, Pays-Bas, Espagne**, plus une allocation paneuropéenne. **Aucun programme national dans un État membre d'Europe centrale, orientale ou balte ; aucun en France, au Portugal, en Grèce.** Autrement dit, le seul instrument européen de co-investissement angel existant est déployé, à l'exception de l'Italie et de l'Espagne, dans des écosystèmes déjà capitalisés. *(Confiance : moyenne-élevée — liste obtenue via l'index de recherche, `eif.org` répondant 403 ; à revérifier sur la page EIF.)*

**(c) Le droit des aides d'État autorise cette territorialité.** Les lignes directrices sur les aides d'État visant à promouvoir les investissements en faveur du financement des risques permettent aux États membres d'exiger que les bénéficiaires finals aient un **établissement et exercent une activité économique sur leur territoire**. Une mesure de financement des risques financée par une institution nationale de promotion peut donc **légalement** être fermée aux investissements transfrontaliers — et l'est en pratique. Le plafond d'aide au financement des risques par entreprise bénéficiaire au titre du RGEC est de **16,5 M€** [RGEC, art. 21, tel que modifié en 2023].

**Synthèse de la section :** le biais domestique de l'investissement angel européen a trois couches — une couche **économique irréductible** (coût de monitoring rapporté au ticket), une couche **fiscale** (territorialité des 46 dispositifs nationaux), et une couche **institutionnelle auto-infligée** (mandats nationaux des instruments publics de co-investissement). Seules les deux dernières sont des variables de politique publique. C'est là que se situe le gisement d'action.

---

## 3. Pourquoi ce dossier n'est pas celui du financement scale-up — et pourquoi la distinction doit être tenue

Le macro-financial case d'un instrument angel dédié repose entièrement sur cette distinction. S'il n'est pas distinct, il est redondant avec ce qui existe déjà et bien mieux doté.

### 3.1 Trois à quatre ordres de grandeur séparent les deux segments

| | Segment angel | Segment scale-up institutionnel |
|---|---|---|
| Ticket unitaire de référence | **≈ 25 600 €** (par investisseur et par tour) | **≈ 100 M€** (tickets du Scaleup Europe Fund) |
| Décideur | Personne physique, décision individuelle, capital propre | Comité d'investissement, capital de tiers, mandat |
| Instrument public de référence | European Angels Fund : **> 800 M€** de volume depuis 2012 | Scaleup Europe Fund : **5 Md€** de cible, dont 1 Md€ Commission (EIC/Horizon Europe) et ≥ 2 Md€ privés au premier tour ; gérant EQT désigné en mai 2026 ; premiers investissements attendus à l'automne 2026 |
| Autres instruments | — | ESCALAR (enveloppe pilote 300 M€, effet de levier visé ×4) ; InvestEU Equity ; **TechEU : 70 Md€ 2025-2027** du Groupe BEI, visant ≥ 250 Md€ d'investissements |
| Déficit officiellement identifié par la Commission | *non chiffré* | tours **> 100 M€** [COM(2025) 270, p. 7] |

Le rapport entre le ticket angel et le ticket du Scaleup Europe Fund est de l'ordre de **1 à 4 000**. Aucun de ces instruments n'est structurellement capable de descendre au ticket angel : les coûts fixes de gestion d'un fonds de plusieurs milliards l'interdisent.

### 3.2 Le déficit agrégé européen est en aval ; le déficit géographique est en amont

Il faut tenir les deux propositions simultanément, car elles sont toutes deux vraies et souvent confondues.

**Le déficit agrégé UE/US est en aval.** Convergence de sources institutionnelles : la taille agrégée des fonds VC est de **≈ 150 Md€ dans l'UE contre ≈ 930 Md€ aux États-Unis**, soit un facteur six, et l'écart « se creuse substantiellement aux tours tardifs » ; la collecte moyenne par fonds et par an est de **73 M€ dans l'UE contre 103 M€ aux États-Unis** [BCE, Bulletin économique 5/2026, « Europe's venture capital gap and the financing of high-growth firms »]. La Commission situe le déficit sur les tours **supérieurs à 100 M€** [COM(2025) 270]. Sur ce terrain, l'angel n'a rien à apporter.

**Le déficit géographique intra-UE est en amont.** Comme montré en §1.3, les pays cibles reçoivent du capital étranger **tardif** et principalement américain, et n'ont pratiquement aucun capital **précoce** non local. Le segment « premier chèque externe, transfrontalier, intra-européen » est un **trou structurel** que ni les instruments scale-up ni les fonds américains ne comblent, par construction.

**Le macro-financial case d'un instrument angel dédié tient donc à une seule chose :** il est le seul instrument capable d'agir sur le maillon *pre-seed/seed transfrontalier intra-européen*, qui est vide. Il ne doit pas être justifié par le comblement de l'écart UE/US, qui est ailleurs. Argumenter l'inverse affaiblirait le dossier et serait factuellement faux. *(Confiance : élevée — le double constat est soutenu par BCE, FMI, BEI, Commission et Dealroom indépendamment.)*

### 3.3 Ce que l'angel apporte et que le capital institutionnel n'apporte pas

Le canal par lequel un dispositif angel produit un effet macro n'est pas volumétrique (§4 le montre chiffres à l'appui). Il est de nature **institutionnelle** :

- **Fonction de sélection à l'entrée.** §1.2 établit que la contrainte des pays cibles porte davantage sur le nombre de projets trouvant un premier financeur que sur la taille des tours. L'angel est le premier financeur externe par définition.
- **Transfert de compétence et de réseau.** Le VC ne transmet pas seulement du capital mais « de la connaissance, du conseil et des réseaux professionnels » ; le modèle d'Akcigit et al. (2022), calibré sur données américaines, estime que si les start-up n'étaient adossées qu'aux banques, la croissance annuelle agrégée baisserait de **0,5 point de pourcentage** [IMF WP/24/146, §§10-11]. Un angel allemand ou néerlandais expérimenté investissant en Roumanie ou en Pologne transporte cette fonction, pas seulement 25 000 €.
- **Formation d'une base d'investisseurs locale.** Le résultat de §1.3 (les dix premiers investisseurs seed de la CEE sont tous locaux) signifie qu'il existe une base locale, mince, à laquelle un co-investisseur étranger expérimenté peut se syndiquer. C'est un canal de **densification**, pas de substitution.
- **Signal pour les tours suivants.** L'EIF joue déjà ce rôle de hub et de signal de crédibilité au niveau institutionnel [BCE, FIE 2026]. La question ouverte est de savoir si le même effet existe au niveau angel — **il n'est pas documenté**.

*(Confiance : moyenne. Ces canaux sont plausibles et partiellement étayés, mais aucun n'a fait l'objet d'une évaluation causale au niveau angel transfrontalier — voir §5.3.)*

---

## 4. Effet agrégé attendu : ordres de grandeur et choix du dénominateur

Exercice de cadrage, entièrement en calculs propres, avec hypothèses explicites. **Ces chiffres sont des ordres de grandeur destinés à situer l'enjeu, pas des prévisions.**

**Base de départ.** Marché angel visible européen hors Royaume-Uni : **≈ 929 M€/an** (2024, §1.1). Part transfrontalière observée sur la population la plus professionnalisée : **12 %**, soit **≈ 110 M€/an** de flux angel transfrontaliers visibles en Europe continentale. Une part indéterminée de ce montant circule déjà entre pays sources (Allemagne–Autriche, Estonie–Finlande…) plutôt que vers les pays cibles.

**Scénarios (flux transfrontalier annuel incrémental) :**

| Scénario | Part transfrontalière atteinte | Flux transfrontalier total | **Flux incrémental** |
|---|---|---|---|
| Statu quo | 12 % | 110 M€ | — |
| Doublement | 24 % | 223 M€ | **+ 113 M€/an** |
| Alignement sur le VC intra-européen (≈ 40 %) | 40 % | 372 M€ | **+ 262 M€/an** |

Sur le marché *total* (visible + non déclaré), si l'on retenait l'ancien multiplicateur ×10 — **que la source elle-même ne valide plus** —, ces montants seraient multipliés par dix, soit **+1,1 à +2,6 Md€/an**. Ce chiffre est à traiter comme une borne haute très incertaine.

**Le choix du dénominateur détermine entièrement la conclusion :**

| Dénominateur | Montant | Effet du scénario médian (+113 M€) |
|---|---|---|
| PIB de l'UE-27 (≈ 17 900 Md€) | 17 900 000 M€ | **+ 0,0006 %** — négligeable |
| Objectif Draghi d'investissement additionnel (750-800 Md€/an) | 775 000 M€ | **+ 0,015 %** — négligeable |
| VC européen total (Invest Europe 2025) | 20 000 M€ | **+ 0,6 %** — marginal |
| VC en Europe centrale et orientale (Invest Europe 2025) | 675 M€ | **+ 17 %** — matériel |
| VC des 5 pays cibles du §1.2 (≈ 5 700 M€) | 5 700 M€ | **+ 2,0 %** — modeste |
| Marché angel visible des pays cibles *(non mesurable)* | n.d. | probablement **> 30 %** |

**Conclusion de cadrage, à énoncer sans ambiguïté :**

> Un dispositif de co-investissement angel transfrontalier est, au niveau de l'agrégat européen, **sans effet macro-économique mesurable**. Il devient potentiellement **matériel au niveau de l'écosystème d'amorçage des pays cibles**, où il peut représenter un ordre de grandeur de 15 à 30 % du flux existant. Toute justification du dispositif par sa contribution aux objectifs agrégés (Draghi, écart UE/US, UMC en volume) est arithmétiquement indéfendable ; toute évaluation de son efficacité doit se faire au dénominateur local.

Cela emporte une conséquence directe sur les indicateurs de suivi (§7).

*(Confiance : élevée sur les ordres de grandeur relatifs ; faible sur les niveaux absolus, entièrement dépendants de la base EBAN et de l'hypothèse de comportement.)*

---

## 5. Stabilité macroprudentielle

### 5.1 Position, énoncée explicitement

> **Ce dossier ne présente aucun enjeu macroprudentiel. Il n'existe aucun canal crédible par lequel l'expansion, la contraction ou la défaillance d'un dispositif de co-investissement angel transfrontalier affecterait la stabilité financière de l'UE.** Construire un argument de stabilité sur ce dossier serait analytiquement faux et affaiblirait la crédibilité du reste du raisonnement.

### 5.2 Justification par les ordres de grandeur et par le traitement officiel

| Agrégat | Montant | Source |
|---|---|---|
| Intermédiation financière non bancaire (UE, fin 2024) | **50 700 Md€** (42 % des actifs du secteur financier de l'UE) | ESRB, *EU NBFI Risk Monitor 2025* |
| Actifs du secteur financier de l'UE *(déduit : 50 700 / 0,42)* | **≈ 120 700 Md€** | calcul propre |
| Fonds d'investissement UE (actif net) | **20 200 Md€** | ESRB 2025 |
| VC européen investi (2025) | **20 Md€** | Invest Europe |
| Marché angel européen visible (2024) | **1,22 Md€** | EBAN |
| **Flux transfrontalier angel incrémental, scénario médian (§4)** | **0,113 Md€** | calcul propre |

Le marché angel visible représente **≈ 0,001 % des actifs du secteur financier de l'UE** et **≈ 0,0024 % des actifs NBFI**. Le flux *incrémental* visé par un dispositif transfrontalier représente **≈ 0,0001 %** des actifs NBFI.

Traitement par l'autorité macroprudentielle compétente : l'ESRB, dans le *EU Non-bank Financial Intermediation Risk Monitor 2025*, ne comporte **aucune catégorie de suivi ni aucune évaluation de risque distincte pour le capital-risque**, et classe les fonds de private equity en **« engagement faible »** (*low engagement*) au regard des activités génératrices de risque systémique, avec une unique réserve portant sur les opérations à effet de levier (LBO) — sans objet pour l'amorçage. *(Aucune édition 2026 du NBFI Monitor n'était publiée à la date de rédaction ; l'édition 2025 date du 1er septembre 2025.)*

Les trois canaux canoniques de risque systémique NBFI identifiés par l'ESRB — **effet de levier, asymétrie de liquidité, interconnexion** — sont tous absents : capital en fonds propres non levier, détenu en direct par des personnes physiques, sans promesse de liquidité ni mécanisme de rachat susceptible de générer une ruée, sans exposition bancaire matérielle, sans transformation de maturité. Les pertes, y compris totales, sont absorbées par le patrimoine d'individus.

Là où la BCE localise effectivement une préoccupation de stabilité dans le non-coté, c'est sur le **private credit**, pas sur le capital-risque.

### 5.3 Ce qui reste néanmoins à traiter, et qui n'est pas macroprudentiel

Trois risques réels, à ne pas confondre avec du risque systémique :

1. **Risque budgétaire / passif éventuel.** Un dispositif de co-investissement engage des fonds publics dans un actif dont le taux de perte attendu est élevé par nature. C'est un enjeu de finances publiques et de gestion de portefeuille, dimensionné à l'échelle de quelques centaines de millions d'euros au maximum — sans commune mesure avec les enveloppes scale-up (§3.1).
2. **Risque de protection de l'investisseur, non macroprudentiel mais réel.** Tout élargissement de la participation au-delà des investisseurs réellement fortunés et avertis déplace le dossier vers le terrain de la conduite (classification client MiFID II, commercialisation transfrontalière), qui relève de l'ESMA et non de l'ESRB. La preuve américaine sur ce point est défavorable : les incitations fiscales angel attirent des investisseurs **plus jeunes, plus locaux, moins expérimentés**, sans entrée significative d'angels professionnels [Denes, Howell, Mezzanotti, Wang & Xu, *Journal of Finance*, 78(5), 2023].
3. **Procyclicalité et dépendance structurelle au public.** Le marché angel visible recule depuis 2021 (1 456 → 1 419 → 1 255 → 1 220 M€ de 2021 à 2024) tandis que la part publique dans la collecte des fonds VC européens atteint **39 % en 2025** selon Invest Europe (« agences gouvernementales »), ou **≈ 25 % en 2024** selon le rapport FIVE (périmètre « institutions nationales de promotion » — les deux chiffres ne sont pas combinables). Le rapport FIVE relève lui-même des préoccupations « quant à l'ampleur de l'implication du secteur public et au risque de créer une **dépendance structurelle au financement public** ». Un dispositif contracyclique par construction est un argument en sa faveur ; un dispositif permanent ajoutant une couche publique supplémentaire dans un marché déjà majoritairement public à la marge en est un contre.

---

## 6. Positionnement contre les objectifs européens explicites et l'évaluation officielle courante

### 6.1 Les objectifs invocables, et ce qu'ils disent réellement

| Instrument | Date | Contenu pertinent |
|---|---|---|
| **Plan d'action UMC** — COM(2020) 590 | 24 sept. 2020 | Accès au financement des entreprises, en particulier PME |
| **Rapport Letta**, *Much more than a market* | avr. 2024 | ≈ **300 Md€/an** d'épargne des ménages quittant les marchés de l'UE |
| **Rapport Draghi** | sept. 2024 | **750-800 Md€/an** d'investissement additionnel (4,4-4,7 % du PIB) ; achèvement de l'UMC |
| **Communication UEE/SIU** — COM(2025) 124 | 19 mars 2025 | « Favoriser la richesse des citoyens et la compétitivité » ; revue à mi-parcours **Q2 2027** |
| **Stratégie start-up et scale-up** — COM(2025) 270 | 28 mai 2025 | Volet II « Better finance for startups and scaleups » |
| **Rapport FIVE** (Kukies-Noyer) | 19 janv. 2026 | Combler l'écart de financement scale-up ; mobilisation du capital de pension |
| **Proposition « EU Inc. » / 28e régime** | **18 mars 2026** | Forme sociale européenne optionnelle ; immatriculation ≤ 48 h pour ≤ 100 € ; opérations et transferts de parts entièrement numériques ; harmonisation d'aspects de droit des sociétés, de l'insolvabilité, du travail et de la fiscalité ; régime harmonisé de *stock options* |
| **Révision EuVECA** | annoncée pour **Q3 2026** | Appel à contributions 15 janv. – 12 mars 2026 ; porte sur les **fonds**, pas sur les personnes physiques investissant en direct |

Trois textes sont directement structurants pour ce dossier, et il faut les citer pour ce qu'ils disent :

**(a) La Commission reconnaît l'obstacle, en une phrase, sans le chiffrer :**
> « Le potentiel des business angels européens reste limité par des obstacles à l'investissement transfrontalier et par des pratiques d'affaires qui immobilisent l'investissement des business angels sur une longue période. »
> *COM(2025) 270, p. 8.*

C'est, à notre connaissance, la seule évaluation officielle explicite de la Commission portant spécifiquement sur le transfrontalier angel. Elle n'est assortie d'aucune quantification.

**(b) L'action correspondante est la moins instrumentée du volet financement :**
> « La Commission soutiendra les business angels européens et leurs réseaux afin de créer davantage de possibilités de croissance pour les jeunes start-up (2026). »
> *COM(2025) 270, volet « Better finance for startups and scaleups ».*

**Aucun instrument juridique, aucun budget, aucun indicateur** ne sont associés à cette ligne — contrairement aux autres actions du même volet (Scaleup Europe Fund, ETCI 2.0, European Innovation Investment Pact, cadre de valorisation de la PI en Q2 2027). À la date de rédaction (1er septembre 2026), aucune traduction opérationnelle de cette action n'a pu être identifiée.

**(c) Le diagnostic de fragmentation est officiel et récent :**
> « La petite taille du marché VC de l'UE s'explique par un manque de culture de l'action, l'aversion au risque et la fragmentation des marchés de capitaux due à la divergence des règles nationales… **Le niveau des investissements transfrontaliers reste faible.** »
> *COM(2025) 270, p. 7.*

L'étude commanditée par DG FISMA (Civitta, EBAN, Bourse Consult, 15 octobre 2025) confirme : les écosystèmes de capital-risque et de croissance de l'UE demeurent « fragmentés et sous-développés », avec des barrières juridiques, réglementaires, fiscales et de marché.

### 6.2 État d'avancement officiel : ce qui est disponible et ce qui ne l'est pas

- **UEE/SIU :** aucun rapport d'avancement officiel de la Commission n'était publié à la date de rédaction. La **revue à mi-parcours est programmée pour le Q2 2027**. Toute affirmation sur « l'évaluation officielle des progrès » de l'UEE ne peut donc s'appuyer que sur les diagnostics contenus dans les communications elles-mêmes et sur l'étude commanditée d'octobre 2025. Éléments livrés depuis mars 2025 et pertinents pour le canal *retail* : recommandation sur les **comptes d'épargne et d'investissement**, stratégie d'éducation financière (30 septembre 2025), paquet intégration de marché et supervision (décembre 2025), position du Conseil sur la révision du PEPP (juin 2026).
- **Draghi :** la Commission revendique, un an après, **33 initiatives phares adoptées**, **plus de 1 000 Md€ mobilisés** (dont 200 Md€ IA, 150 Md€ SAFE défense, > 100 Md€ Clean Industrial Deal), **8,4 Md€** d'économies de coûts de conformité, et **90 % de ses initiatives phares « directement inspirées »** des recommandations Draghi. Un décompte largement cité — **11 % des 383 recommandations pleinement mises en œuvre, 20 % partiellement, 46 % en cours, 23 % non traitées** — circule dans le débat ; **je n'ai pas pu en identifier la source primaire avec certitude et ne le retiens qu'à titre indicatif** (voir §9).
- **Cour des comptes européenne :** dernier rapport spécial dédié à l'UMC, n° 25/2020 (« un démarrage lent vers un objectif ambitieux »). Aucun rapport plus récent identifié.

### 6.3 Les trois décalages entre objectifs affichés et instrumentation

1. **Décalage d'échelle.** L'objectif Draghi est calibré à 750-800 Md€/an ; le flux incrémental atteignable par un dispositif angel transfrontalier est de l'ordre de 0,1 à 0,3 Md€/an (§4). **Le dispositif ne peut pas être présenté comme contributif à cet agrégat.**
2. **Décalage de segment.** Le déficit officiellement identifié porte sur les tours **> 100 M€** ; le ticket angel est trois à quatre ordres de grandeur inférieur. Les deux dossiers ne sont pas substituables.
3. **Décalage d'instrumentation.** Le seul obstacle spécifiquement angel reconnu par la Commission — le transfrontalier — **n'est traité par aucun instrument financier identifié**. La révision EuVECA (Q3 2026) porte sur les *fonds* et ne couvre pas, par construction, la personne physique investissant en direct. La seule action de l'UE explicitement conçue sur un couloir source→cible d'investissement angel identifiée dans cette recherche est le projet **4NGELS** (Horizon Europe, action de coordination et de soutien) reliant EstBAN (Estonie) et FiBAN (Finlande) à Cobin Angels (Pologne) et au Klub Poslovni Angeli Slovenije (Slovénie), **doté de 500 000 € au total**, clos le 28 février 2025. Rapporté à l'enjeu, c'est un ordre de grandeur d'écart de **1 à 10 000** avec le Scaleup Europe Fund.

**Le point de convergence à ne pas manquer :** la proposition **EU Inc. du 18 mars 2026** est, de tous les chantiers en cours, celui qui agit le plus directement sur la barrière la plus contraignante pour l'angel — le **coût fixe juridique par opération**. Immatriculation numérique en 48 heures pour moins de 100 €, transferts de parts entièrement numériques, forme sociale unique reconnue dans les 27 États membres : c'est exactement ce qui rend économiquement soutenable un ticket de 25 600 € dans une juridiction étrangère. Un dispositif de co-investissement conçu **indépendamment** d'EU Inc. serait très inférieur à un dispositif conçu **par-dessus** EU Inc. *(Confiance : élevée sur le contenu et la date de la proposition ; l'appréciation d'articulation est un jugement analytique, pas une donnée.)*

---

## 7. Contraintes de conception imposées par l'analyse agrégée

Formulées comme contraintes issues des données, non comme propositions — le design relève de `policy-innovator`.

**C1 — Le véhicule ne peut pas reposer sur des mandats nationaux.** §2.4 établit que les compartiments nationaux de l'EAF limitent le transfrontalier « par les exigences de mandat », que les lignes directrices sur le financement des risques autorisent l'exigence d'établissement territorial, et que la couverture géographique de l'EAF reproduit la carte de la concentration. **Un dispositif financé par des institutions nationales de promotion reproduira mécaniquement le biais qu'il prétend corriger.** Le financement doit provenir d'un compartiment européen (EIF sur ressources UE, InvestEU compartiment UE) ou d'un pool multi-pays mutualisé assumé comme tel.

**C2 — L'économie du ticket est la contrainte binding, pas le rendement.** À 25 600 € par investisseur et par tour, la structure doit maintenir le coût fixe par opération à un niveau très bas. Cela oriente vers des architectures à **délégation de diligence à un lead local** dans le pays cible, documentation standardisée, et adossement à une forme sociale unique (EU Inc.). Un dispositif qui améliore le rendement sans réduire le coût fixe échouera : la littérature identifie le coût de monitoring, pas le rendement, comme déterminant du biais domestique.

**C3 — La fiscalité ne peut pas être réglée par le dispositif seul, mais son effet est calibrable.** La territorialité des 46 dispositifs nationaux est une barrière hors de portée d'un instrument financier. En revanche, l'ordre de grandeur de l'avantage perdu est mesurable (18-25 % pour l'IR-PME français) et peut servir de **paramètre de calibrage** du taux de co-investissement public — à condition d'assumer que ce paramétrage compense une distorsion fiscale plutôt qu'il ne corrige une défaillance de marché, ce qui est une justification plus faible.

**C4 — Le sens du flux doit être contraint explicitement, sinon le dispositif ira du source vers le source.** Les 12 % de transfrontalier existants circulent en partie entre pays déjà capitalisés (couloirs Estonie-Finlande, Allemagne-Autriche). Un dispositif neutre géographiquement financera d'abord les couloirs les moins coûteux, qui sont ceux qui existent déjà. L'objectif « pays cible » doit être une condition d'éligibilité, pas un résultat espéré.

**C5 — Les indicateurs de suivi doivent être au dénominateur local.** §4 établit que l'effet est invisible au dénominateur européen et matériel au dénominateur du pays cible. Les indicateurs pertinents sont : nombre d'entreprises des pays cibles recevant un premier chèque externe transfrontalier intra-UE ; nombre d'angels locaux syndiqués à un lead étranger ; taux de tour de suivi à 24 mois. **Pas** : montant total investi, part dans le VC européen, contribution à l'objectif Draghi.

**C6 — Le design d'évaluation doit être intégré ex ante, parce que la base de preuve est vide.** C'est la contrainte la plus importante et la moins confortable.
- **Aucune évaluation contrefactuelle** d'un dispositif de co-investissement public spécifiquement angel n'a été identifiée à l'échelle européenne. Concernant l'EAF, les éléments publiés relèvent de l'analyse de portefeuille et de l'enquête auto-déclarative auprès des bénéficiaires — design **sans contrefactuel** et sujet au biais de désirabilité.
- Le **seul design causal propre disponible sur les incitations à l'investissement angel** — Denes, Howell, Mezzanotti, Wang & Xu (*Journal of Finance*, 2023 ; différences-de-différences sur l'introduction et la suppression échelonnées de crédits d'impôt angel dans **31 États américains, 1988-2018**, 8,1 Md$ de crédits) — trouve **+18 % d'investissements angel et +31 % d'investisseurs, mais aucun effet significatif** sur l'emploi des jeunes entreprises, la création d'entreprises, les sorties réussies ou les brevets, avec une puissance statistique explicitement calculée et jugée suffisante. Mécanismes identifiés : orientation vers des entreprises à faible potentiel, afflux d'investisseurs **non professionnels**, et requalification (35 % des entreprises bénéficiaires comptent au moins un investisseur dirigeant ou membre de la famille d'un dirigeant, contre 8 % sur AngelList). Validité externe pour l'UE non établie, et l'instrument étudié (crédit d'impôt) diffère d'un co-investissement en capital — mais le résultat porte sur un mécanisme dont rien n'indique qu'il soit spécifiquement américain.
- L'OCDE (juin 2025) identifie explicitement des lacunes : résultats d'évaluation limités, absence d'évaluations systématiques comparables entre pays, preuves insuffisantes sur l'additionnalité de long terme.
- Ce qui est établi côté co-investissement institutionnel : les régions dans lesquelles l'EIF a investi connaissent des hausses significatives d'entrées de capitaux privés sur trois ans, la relation étant forte en private equity ; **pour le VC, les auteurs observent des schémas hétérogènes et aucune preuve d'éviction** [*Applied Economics*, 2026, données régionales 2010-2020]. « Absence de preuve d'éviction » n'est pas « preuve d'additionnalité ».

**Formulation la plus défendable en l'état :** un dispositif de co-investissement angel transfrontalier est une **hypothèse de politique publique non testée**, dans un domaine où le seul test rigoureux existant sur un instrument voisin est négatif. Cela ne condamne pas l'idée — le mécanisme visé ici (réduction d'un coût d'information et de monitoring) est différent du mécanisme testé par Denes et al. (subvention du rendement) — mais cela impose un **déploiement échelonné avec contrefactuel** plutôt qu'un déploiement uniforme.

---

## 8. Tableau récapitulatif des niveaux de confiance

| Affirmation | Confiance |
|---|---|
| Le capital angel visible européen est concentré à ≈ 50-60 % sur trois à cinq pays | **Élevée** |
| Niveaux absolus du marché angel par pays (EBAN) | **Moyenne** |
| Taille réelle du marché angel européen (visible + non déclaré) : inconnue | **Élevée** |
| Les pays cibles (ES, IT, PL, PT, RO) comptent au total plus d'entreprises au stade pre-seed/seed que SE + NL | **Moyenne-élevée** |
| L'écart de VC par habitant entre pays sources et cibles est d'un facteur ≈ 7 | **Moyenne** (source commerciale unique, périodes non explicitées) |
| L'écart de VC par entreprise financée est nettement plus faible (≈ 1,6×) que l'écart par habitant | **Moyenne** |
| Le capital d'amorçage des pays d'Europe centrale et orientale est presque intégralement local, le capital étranger n'arrivant qu'en série B+ | **Élevée** (constat qualitatif) / **Moyenne** (parts exactes) |
| La part transfrontalière de l'investissement angel est de ≈ 12 % (population EIF, la plus professionnalisée) | **Moyenne-élevée** |
| Le VC institutionnel européen est *plus* extraverti que le VC américain au déploiement | **Moyenne** (source unique : BCE/PitchBook) |
| Le biais domestique européen du VC est concentré côté LP/collecte, non côté déploiement | **Moyenne-élevée** |
| Les compartiments nationaux de l'EAF limitent le transfrontalier par construction de mandat | **Élevée** (déclaration de l'EIF lui-même) |
| Liste exacte des pays couverts par un programme national EAF | **Moyenne** (obtenue via index de recherche, `eif.org` inaccessible) |
| Les lignes directrices sur le financement des risques autorisent une exigence d'établissement territorial | **Moyenne-élevée** |
| L'effet propre de la fragmentation fiscale sur les flux angel transfrontaliers n'est pas quantifié dans la littérature | **Élevée** (sur l'absence) |
| Le déficit de financement agrégé UE/US est concentré en aval, pas à l'amorçage | **Élevée** |
| Un dispositif angel transfrontalier est sans effet mesurable sur les agrégats européens | **Élevée** |
| Un tel dispositif peut représenter 15-30 % du flux d'amorçage des écosystèmes cibles | **Faible-moyenne** (dépend entièrement de l'hypothèse comportementale) |
| L'investissement angel ne présente aucun enjeu macroprudentiel | **Élevée** |
| La Commission reconnaît l'obstacle transfrontalier angel sans l'avoir quantifié ni instrumenté | **Élevée** |
| Les incitations fiscales angel augmentent le volume investi sans effet réel agrégé détectable (US) | **Élevée** (validité interne) / **Moyenne** (transposition UE, et instrument différent d'un co-investissement) |
| Les dispositifs de co-investissement public *pari passu* produisent une additionnalité nette positive | **Faible — non démontré** |

---

## 9. Éléments non vérifiés, limites et alertes

1. **Échec systématique de l'extraction PDF dans l'environnement d'exécution** (`pdftoppm` absent ; réponses 403 sur `eif.org`, `tandfonline.com`, `investeurope.eu`, `sifted.eu`, `pitchbook.com`, `oecd-ilibrary.org`, `eprints.gla.ac.uk`). Documents dont le texte intégral n'a **pas** pu être consulté : EBAN *Statistics Compendium 2024* ; Invest Europe *Investing in Europe: Private Equity Activity 2025* ; EIF WP 2020/062 (EAF) et WP 2019/060 (enquête angels) ; Mason, Botelho & Duggett (2022) ; profils pays du Tableau de bord européen de l'innovation 2025 ; document de consultation de la Commission sur la réforme des fonds de capital-risque et de croissance (janvier 2026). Les données correspondantes proviennent de résumés d'index de recherche ou de sources secondaires et sont signalées comme telles.
2. **Données Dealroom du §1.2 : période du champ « VC invested » non précisée** par la source (vraisemblablement 12 mois glissants à la date de consultation). Les comparaisons entre pays sont valides car réalisées à la même date sur le même fournisseur ; les niveaux absolus ne doivent pas être rapprochés d'autres sources. Les « rangs européens » affichés par Dealroom sont incohérents entre pages (Italie, Pologne et Portugal tous annoncés « #12 en Europe ») et n'ont donc pas été utilisés.
3. **Non-réconciliation des mesures de VC.** Quatre périmètres circulent dans ce document et **ne doivent pas être combinés** : Invest Europe *industry statistics* (20 Md€ de VC 2025, opérations des gérants membres) ; Dealroom/tech.eu (72 Md€ d'investissement tech européen 2025 ; 63,8 Md$ de financement start-up européen 2025) ; ECB/PitchBook (tailles de fonds) ; EBAN (marché early-stage visible). Les écarts tiennent aux définitions, pas à des erreurs.
4. **Écart CEE non résolu.** VC en Europe centrale et orientale : **675 M€** (Invest Europe 2025) vs **≈ 3,6 Md€ pour l'« Europe de l'Est » en 2025** (source secondaire, article sous paywall, non vérifiable) vs **2,3 Md€ pour la CEE en 2024** (Dealroom). Périmètres géographiques et méthodologiques différents ; le premier chiffre est le plus restrictif et le mieux documenté.
5. **Décompte de mise en œuvre des recommandations Draghi (11 % / 20 % / 46 % / 23 %) : source primaire non identifiée.** Ce chiffrage provient d'un résumé d'index de recherche et n'a pas pu être rattaché à un tracker nommé. Il est mentionné à titre indicatif et **ne doit pas être cité comme donnée établie** sans vérification.
6. **Chiffres 2024 par pays d'EBAN (top 3) repris de l'analyse antérieure du 7 août 2026 sans revérification sur le PDF source.** Cette analyse antérieure signalait par ailleurs des incohérences internes dans EBAN 2024 (France à 130,66 M€ dans le tableau contre 98,6 M€ dans le texte ; 359 contre 339 réseaux d'affaires). La prudence s'impose sur les deuxièmes décimales.
7. **Indicateur non exploité faute d'accès :** le Global Entrepreneurship Monitor mesure, par pays et par enquête sur population adulte, le taux d'« investisseurs informels » (part des adultes ayant financé une entreprise créée par un tiers dans les trois dernières années). C'est **le meilleur proxy disponible du marché angel invisible, comparable entre pays**, et il figure au rapport GEM 2024/2025 (figure 2.7). Les valeurs par pays européen n'ont pas pu être extraites. **Recommandation méthodologique : cette série devrait être mobilisée pour toute quantification ultérieure de l'asymétrie source/cible.**
8. **Chiffre du marché angel américain : à ne pas utiliser.** L'ordre de grandeur repris par EBAN (≈ 27,8 Md USD, ≈ 66 000 angels en 2024) est sourcé sur un site commercial et n'est pas comparable au périmètre européen.
9. **Aucun rapport d'avancement officiel de la Commission sur l'UEE** n'existait à la date de rédaction (revue à mi-parcours prévue Q2 2027) ; aucune traduction opérationnelle de l'action « soutenir les business angels européens et leurs réseaux (2026) » de COM(2025) 270 n'a pu être identifiée au 1er septembre 2026.
10. **Statut de la révision EuVECA au 1er septembre 2026 non confirmé.** L'adoption était annoncée pour le Q3 2026 ; je n'ai pas pu établir si la proposition avait été publiée. À vérifier par `current-regulation-analyst`.

---

## Sources

**Institutions de l'Union européenne**
- Commission européenne, *A Capital Markets Union for people and businesses — new action plan*, COM(2020) 590, 24 sept. 2020.
- Commission européenne, *Savings and Investments Union — A Strategy to Foster Citizens' Wealth and Economic Competitiveness in the EU*, COM(2025) 124 final, 19 mars 2025. — https://finance.ec.europa.eu/
- Commission européenne, *EU Startup and Scaleup Strategy*, COM(2025) 270 final, 28 mai 2025. — https://research-and-innovation.ec.europa.eu/document/download/2f76a0df-b09b-47c2-949c-800c30e4c530_en
- Commission européenne, *EU Inc. — a new harmonised corporate legal regime* (28e régime), proposition du 18 mars 2026. — https://commission.europa.eu/topics/business-and-industry/doing-business-eu/company-law-and-corporate-governance/eu-inc-new-harmonised-corporate-legal-regime_en
- Commission européenne (DG FISMA), *Study on venture and growth capital funds* (Civitta, EBAN, Bourse Consult), 15 oct. 2025 ; consultation sur la réforme des fonds de capital-risque et de croissance, 15 janv. – 12 mars 2026. — https://finance.ec.europa.eu/publications/study-venture-and-growth-capital-funds_en
- Commission européenne (DG TAXUD), *Effectiveness of tax incentives for venture capital and business angels…*, TAXUD/2015/DE/330, juin 2017.
- Commission européenne, *The Draghi report: one year on*. — https://commission.europa.eu/topics/competitiveness/draghi-report/one-year-after_en
- Commission européenne, lignes directrices sur les aides d'État visant à promouvoir les investissements en faveur du financement des risques ; RGEC art. 21 (modification 2023). — https://competition-policy.ec.europa.eu/state-aid/legislation/regulations_en
- CORDIS, projet **4NGELS**, n° 101096732, Horizon Europe (CSA), nov. 2022 – févr. 2025, 500 000 €. — https://cordis.europa.eu/project/id/101096732/en
- Parlement européen, *Review of the Regulation on European venture capital funds (EuVECA)*, Legislative Train Schedule. — https://www.europarl.europa.eu/legislative-train/theme-a-new-plan-for-europe-s-sustainable-prosperity-and-competitiveness/file-review-of-the-european-venture-capital-funds-regulation
- Eurostat, *High-growth enterprises — statistics* (180 200 entreprises à forte croissance dans l'UE en 2023, 10,5 % des entreprises actives d'au moins 10 salariés ; de 21,1 % en Irlande à 2,8 % à Chypre). — https://ec.europa.eu/eurostat/statistics-explained/index.php?title=High-growth_enterprises_-_statistics
- Cour des comptes européenne, rapport spécial 25/2020, *Union des marchés des capitaux — un démarrage lent vers un objectif ambitieux*.

**Banques centrales et autorités**
- BCE, *Europe's venture capital gap and the financing of high-growth firms*, Bulletin économique n° 5/2026. — https://www.ecb.europa.eu/press/economic-bulletin/focus/2026/html/ecb.ebbox202605_01~4453cc2a34.en.html
- BCE, *Exploring the investor landscape for venture capital*, encadré, *Financial Integration and Structure in the Euro Area*, mai 2026. — https://www.ecb.europa.eu/press/fie/box/html/ecb.fiebox202605_04.en.html
- ESRB, *EU Non-bank Financial Intermediation Risk Monitor 2025*, 1er sept. 2025. — https://www.esrb.europa.eu/pub/nbfi/html/esrb.nbfi202509.en.html
- EIF, *European Angels Fund*. — https://www.eif.org/what_we_do/equity/eaf/index.htm *(403 lors de la consultation ; données via index de recherche)*
- EIF, *The business angel portfolio under the European Angels Fund: An empirical analysis*, Working Paper 2020/062 ; *EIF Business Angels Survey 2019*, Working Paper 2019/060. *(non consultés intégralement)*
- EIF, ESCALAR Pilot Programme. — https://www.eif.org/what_we_do/equity/escalar/
- BEI, TechEU (70 Md€ 2025-2027). — https://www.eib.org/en/press/all/2025-314-europe-s-innovative-companies-get-boost-as-eib-group-launches-techeu-platform-to-simplify-financing
- EIC, Scaleup Europe Fund (cible 5 Md€ ; 1 Md€ Commission ; gérant EQT, mai 2026). — https://eic.ec.europa.eu/news/call-expression-interest-launched-fund-manager-scaleup-europe-fund-2025-12-08_en

**Rapports de haut niveau**
- M. Draghi, *The future of European competitiveness*, sept. 2024.
- E. Letta, *Much more than a market*, avr. 2024.
- J. Kukies & C. Noyer, *Financing Innovative Ventures in Europe (FIVE)*, 19 janv. 2026. — https://www.bundesfinanzministerium.de/Content/EN/Downloads/Europe/report-five-taskforce.html

**Organisations internationales**
- FMI, *Stepping Up Venture Capital to Finance Innovation in Europe*, WP/24/146, juil. 2024. — https://www.elibrary.imf.org/view/journals/001/2024/146/article-A001-en.xml
- OCDE, *Benchmarking government support for venture capital*, juin 2025.
- GEM, *Global Entrepreneurship Monitor 2024/2025 Global Report* (indicateur « investir dans la nouvelle entreprise d'autrui, % d'adultes », fig. 2.7). — https://www.gemconsortium.org/report

**Données de marché**
- EBAN, *Statistics Compendium 2024 — European Early Stage Market Statistics*, oct. 2025. — https://www.eban.org/news/eban-annual-statistics-compendium-for-2024-2/
- EBAN via Statista, *Business angel investments via networks by country* (2023). — https://www.statista.com/statistics/439669/business-angel-investments-by-country-in-europe/
- Invest Europe, *Investing in Europe: Private Equity Activity 2025*, 7 mai 2026 ; *2025 Central and Eastern Europe Private Equity Statistics* (VC CEE 675 M€ en 2025). — https://www.investeurope.eu/news/newsroom/central-and-eastern-european-exits-reach-17bn-in-2025-as-trade-sales-drive-second-best-year-on-record/
- Dealroom, profils pays (Espagne, Italie, Pologne, Portugal, Roumanie, Pays-Bas, Suède) et profil UE, consultés le 1er sept. 2026. — https://dealroom.co/regions/european-union/
- Dealroom, *Central and Eastern European Startups 2025*. — https://dealroom.co/reports/central-and-eastern-european-startups-2025
- Tech.eu, *Inside the numbers: Ten countries leading Europe's tech investment in 2025*, 29 janv. 2026. — https://tech.eu/2026/01/29/inside-the-numbers-ten-countries-leading-europes-tech-investment-in-2025/

**Littérature académique et évaluations**
- C. Mason, T. Botelho & J. Duggett, « Promoting cross-border investing by business angels in the European Union », *Regional Studies*, 56(8), 2022, pp. 1391-1403. — https://www.tandfonline.com/doi/full/10.1080/00343404.2021.1960961
- M. Denes, S. T. Howell, F. Mezzanotti, X. Wang & T. Xu, « Investor Tax Credits and Entrepreneurship: Evidence from U.S. States », *The Journal of Finance*, 78(5), oct. 2023, pp. 2621-2671.
- « Crowding-in or crowding-out? The mobilization effect of the European Investment Fund equity investments », *Applied Economics*, 2026.
- Inspection générale des finances, *Évaluation des réductions d'impôt sur le revenu Madelin pour l'investissement des particuliers dans les PME*, oct. 2023.
