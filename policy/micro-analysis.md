# Analyse micro-financière — L'investissement des business angels en Europe

**Périmètre** : mécanique des transactions, des dispositifs et des comportements individuels (investisseur, deal, société de portefeuille). Hors périmètre : effets d'agrégat / système financier (macro), et propositions de réforme (policy).

**Date de rédaction** : 7 août 2026. Sauf mention contraire, les données les plus récentes disponibles à cette date sont utilisées.

**Convention de fiabilité** — chaque énoncé est étiqueté :
- **[D]** *Documenté* : chiffre ou mécanisme attesté par une source primaire (statistique officielle, texte réglementaire, évaluation, article à comité de lecture).
- **[C]** *Calculé* : dérivation arithmétique de l'auteur à partir de données [D]. La formule est explicitée.
- **[I]** *Inférence plausible non vérifiée* : raisonnement de l'auteur, cohérent avec les mécanismes documentés mais **non testé empiriquement**. À ne pas citer comme un fait.
- **[?]** *Non vérifié / incohérent* : la source est contradictoire, non datée, ou n'a pas pu être authentifiée.

---

## 1. Ordres de grandeur : ce que finance réellement un business angel européen

### 1.1 Le marché « visible »

| Indicateur (marché visible, 39 pays) | 2020 | 2021 | 2022 | 2023 | 2024 |
|---|---|---|---|---|---|
| Investissement BA (M€) | 767 | 1 456 | 1 419 | 1 255 | **1 220** |
| Nombre de tours avec participation BA | 3 583 | 5 073 | 6 310 | 4 789 | **4 582** |
| Nombre de BA recensés | 32 255 | 39 440 | 43 340 | 45 340 | **47 610** |
| Investissement moyen par société (€) | 214 150 | 287 000 | 261 600 | 221 400 | **204 900** |
| Ticket moyen par BA et par tour (€) | 26 800 | 35 900 | 32 700 | 27 700 | **25 600** |

*Source [D] : [EBAN, Statistics Compendium 2024](https://www.eban.org/wp-content/uploads/2025/12/Stats-Compendium-2024.pdf), fig. 6 et fig. 11 (pp. 12, 18).*

Trois faits structurants pour l'analyse micro :

1. **Le ticket unitaire est très petit** : **25 600 €** par angel et par tour en 2024 [D]. C'est l'unité de compte réelle de toute politique publique visant les BA. Un dispositif dont le coût de conformité par transaction dépasse quelques milliers d'euros consomme une fraction non triviale du ticket.
2. **La contraction 2022-2024 s'est faite par compression des tickets, pas par abandon des deals** : −2,8 % en montant contre −4,3 % en nombre de tours entre 2023 et 2024 ; le montant moyen par société recule de −7,4 % [D] (EBAN 2024, pp. 5-7).
3. **Les BA ont perdu la position dominante du segment early-stage** : leur part du marché européen early-stage (BA + VC seed + crowdfunding equity) passe de **50 % en 2023 à 43 % en 2024**, tandis que le VC seed passe de 40 % à 53 % [D] (EBAN 2024, p. 10). En 2013, les BA représentaient 73 % de ce marché [D].

### 1.2 Concentration par taille de tour

Sur un sous-échantillon de 318 tours « angel ou fonds d'angels » totalisant 276 M€ [D] (EBAN 2024, p. 9) :

- tours **≤ 1 M€** : **67 % des transactions**, mais **31,5 % du capital** (87 M€), soit ~0,41 M€ par tour ;
- tours **1–4 M€** : **33 % des transactions**, mais **68 % du capital** (188 M€), soit ~1,77 M€ par tour.

**Lecture micro** : le marché angel européen se scinde en deux régimes distincts. Un régime de *découverte* (petits tours nombreux, dominé par l'Allemagne, l'Italie, le Danemark) et un régime de *syndication professionnalisée* (tours de 1–4 M€, dominé par l'Irlande, la France, le Royaume-Uni) [D]. **[I]** Un dispositif public unique appliqué aux deux régimes produira mécaniquement des effets opposés : sur le premier segment, le coût administratif par euro déployé est prohibitif ; sur le second, le risque d'effet d'aubaine est maximal puisque la syndication professionnelle mobilise déjà des capitaux suffisants.

### 1.3 Réserve de fiabilité sur la source EBAN

Le Compendium EBAN est la source de référence, mais il présente des incohérences internes qu'il faut signaler :

- **[?]** La France est indiquée à **130,66 M€** dans le tableau fig. 8 et dans le résumé exécutif (p. 5), mais à **98,6 M€** p. 14. L'écart est de 32 %. Le chiffre de 130,66 M€ apparaît deux fois et est retenu ici, mais la donnée n'est pas fiable.
- **[?]** Le nombre de réseaux (BAN) est donné à **359** p. 7 et à **339** p. 13.
- **[?]** Les en-têtes du tableau fig. 8 sont décalés : la première page indique « 2024 / 2023 / 2022 », la page de continuation « 2023 / 2022 / 2021 » pour les mêmes colonnes.
- **[C]** Incohérence arithmétique : 1 220 M€ / 204 900 € = **5 954 sociétés** implicites, contre **4 582 tours** déclarés. Il est impossible qu'il y ait plus de sociétés que de tours. Les deux séries ne reposent donc pas sur la même base d'échantillon. Le même problème existe pour 2023 (5 669 sociétés implicites contre 4 789 tours).
- **[D]** EBAN indique explicitement ne couvrir que le marché « visible » et avoir **abandonné** le multiplicateur ×10 (issu d'une étude CSES de 2012 pour la Commission) qui servait auparavant à estimer le marché total, dans l'attente de nouvelles recherches (EBAN 2024, pp. 2, 13). **Il n'existe donc actuellement aucune estimation publiée et défendable du marché angel européen total.** C'est une lacune de données majeure pour tout calibrage de dispositif.

---

## 2. Mécanique des deals : instruments, syndication, structures

### 2.1 L'instrument n'est pas neutre fiscalement — et c'est ce qui détermine son usage en Europe

Le SAFE américain (equity différée, ni dette ni capital) est **structurellement inadapté** à la plupart des juridictions européennes, non pour des raisons de préférence mais pour des raisons de qualification fiscale et de droit des sociétés :

| Juridiction | Instrument dominant en pré-amorçage | Mécanisme de friction identifié |
|---|---|---|
| Royaume-Uni | **ASA** (Advance Subscription Agreement) | Un SAFE pur **ne donne pas accès au SEIS/EIS avant conversion**, potentiellement plusieurs années plus tard. L'ASA est conçu pour être éligible immédiatement, sous réserve d'une *long-stop date* et d'une clause de non-remboursement exigées par HMRC. |
| France | **BSA-AIR** | Bon de souscription d'actions : instrument de valeurs mobilières, non de dette. L'investisseur n'est pas créancier avant conversion. Formalités sociétaires et inscription au registre requises. |
| Allemagne | **Wandeldarlehen** (prêt convertible) | Le droit allemand qualifie mal l'instrument hybride. Les augmentations de capital de GmbH et les cessions de parts exigent une **forme notariée**, ce qui ajoute un coût et un délai fixes par opération. |
| Espagne | Prêt convertible | Résolution d'assemblée générale requise pour la renonciation au droit préférentiel de souscription. |

*Source [D] pour la structure et les mécanismes : [Outlex, « SAFE Notes Don't Work in Europe »](https://outlex.ai/blog/safe-notes-europe-legal-differences) ; [service-public.fr, IR-PME](https://entreprendre.service-public.gouv.fr/vosdroits/F37091) pour l'exigence de souscription en numéraire au capital.*

**[?]** La même source avance des coûts de structuration de **2 000–5 000 € de revue juridique locale par juridiction** et **1 000–3 000 € de conseil fiscal**. Ce sont des estimations de cabinet, non des données d'enquête ; elles ne sont pas vérifiables et sont citées uniquement comme ordre de grandeur.

**[C]** Si l'on retient même la borne basse de cette fourchette (3 000 € de frais fixes de structuration) et le ticket moyen européen de 25 600 € [D], les frais fixes représentent **~12 % du ticket d'un angel unique**. C'est l'argument mécanique le plus fort en faveur de la syndication : les frais fixes ne deviennent supportables qu'une fois répartis sur 5 à 15 co-investisseurs.

**[?]** Une statistique fréquemment citée — 64 % des tours d'amorçage en SAFE, 27 % en equity prix ferme, ~10 % en obligations convertibles — provient de données **américaines** (type Carta). Elle ne s'applique pas au marché européen et ne doit pas être transposée. **Je n'ai pas trouvé de série équivalente publiée pour l'Europe** : c'est une lacune de données réelle.

### 2.2 Effet de bord fiscal : le choix d'instrument est endogène au dispositif fiscal

**[D]** Au Royaume-Uni, l'ASA existe *parce que* le SEIS/EIS exige une émission d'actions ordinaires immédiate. **[D]** En Allemagne, INVEST verse l'*Erwerbszuschuss* de 15 % aussi bien pour l'acquisition directe de parts que pour un *Wandeldarlehen* ([BAND](https://www.business-angels.de/en/invest-english/)) — ce qui neutralise la distorsion. **[D]** En France, la réduction IR-PME exige une **souscription en numéraire au capital** : un BSA-AIR n'ouvre le droit à réduction qu'à la conversion.

**[I]** Conséquence probable, non mesurée : dans les juridictions où la relief fiscale exige une souscription immédiate au capital (France, Royaume-Uni), le dispositif fiscal **pousse les tours vers l'equity à prix ferme prématurément**, c'est-à-dire vers une valorisation négociée à un stade où l'information est trop pauvre pour la fixer. Cela transfère du risque de valorisation au fondateur et allonge la négociation. Le dispositif allemand, qui couvre le convertible, ne produit pas cet effet. Cette hypothèse est cohérente avec la mécanique juridique, mais **aucune étude ne l'a testée**.

---

## 3. Mécanique des dispositifs de co-investissement : où se situe réellement le filtre qualité ?

C'est la question centrale. Un dispositif où l'euro public suit automatiquement l'euro privé n'exerce aucune sélectivité propre : il **délègue** la sélection. Toute la question est de savoir *à qui*, *à quel niveau*, et *sous quelle contrainte*. Les quatre dispositifs examinés résolvent ce problème de quatre façons distinctes.

### 3.1 European Angels Fund (EIF) — filtre déplacé en amont, sur l'investisseur

**Mécanique [D]** ([EIF Working Paper 2020/62](https://www.econstor.eu/bitstream/10419/213873/1/1689254033.pdf), pp. 8-9) :

- Sélection des angels **sur la base de leur expérience d'investissement antérieure**, à l'entrée dans le programme.
- Une fois sélectionné, l'EAF co-investit **pari passu**, typiquement **1:1**.
- **« There is no deal-by-deal review by the EAF and investment decisions are fully delegated to the BA. »** L'EIF **n'examine aucun dossier individuel**.
- Horizon **10 ans**, capital patient.
- Volumes de **250 000 € à 5 M€ par investisseur**, sur base 50:50 ([EIF/EAF](https://www.eif.org/what_we_do/equity/eaf/), via sources secondaires).

**Lecture** : l'EAF répond explicitement au risque de « tampon automatique ». Le filtre n'est **pas** au niveau du deal — il est **entièrement en amont**, au niveau de l'accréditation de l'angel. Le pari du dispositif est que le *track record* d'un angel est un meilleur prédicteur de la qualité de son flux futur que ne le serait une instruction dossier par dossier par une institution publique. C'est un choix de conception défendable et cohérent : il évite à la fois le coût d'instruction (prohibitif sur des tickets de ~128 k€, cf. infra) et le risque de capture réglementaire.

**Contrepartie mécanique [I]** : ce design ne peut pas corriger une dérive de qualité *à l'intérieur* du portefeuille d'un angel accrédité. Si un angel sélectionné voit son flux se dégrader, ou s'il utilise la ligne EAF pour des tours de suivi défensifs sur des sociétés en difficulté (*bridge rounds*), rien dans la mécanique ne le détecte avant la liquidation du portefeuille à 10 ans. Le contexte 2024 rend ce risque saillant : EBAN observe que les BA ont géré leur risque de portefeuille en **priorisant les tours de pont et en conservant du capital pour les tours de suivi** [D] (EBAN 2024, p. 6). **Cette hypothèse n'a pas été testée** ; aucune évaluation publique de la performance du portefeuille EAF ventilée entre premiers investissements et suivis n'a été identifiée.

**Données de portefeuille [D]** (EIF WP 2020/62, données arrêtées Q2-Q4 2019) :
- **438 sociétés** en portefeuille fin 2019.
- **Investissement médian d'un BA dans une société au premier tour : ~128 000 €.** Plus grand investissement enregistré : 5,25 M€.
- Les tickets EAF dépassent légèrement la littérature antérieure (40 k€ – 200 k€), ce que les auteurs attribuent à la sélection sur des angels **expérimentés** donc plus fortunés.
- Sociétés investies : **médiane de 5 salariés** au moment de l'investissement ; **+50 %** (à 12 salariés en moyenne) deux ans après.
- Compartiments nationaux : Allemagne 70 M€ + 65 M€ (abondement), Espagne 30 M€, Autriche 22,5 M€ + 10 M€, Irlande 20 M€, Pays-Bas 45 M€, Danemark 26,9 M€, plus la Flandre (2019) et un compartiment paneuropéen **EAF Europe** dédié aux investissements transfrontaliers.
- **[?]** Une source secondaire non primaire évoque un volume actuel « supérieur à 800 M€, dont plus de 330 M€ engagés auprès de plus de 120 business angels et plus de 800 co-investissements ». **Chiffre non confirmé sur source EIF primaire** (la page eif.org renvoie un HTTP 403) ; à traiter comme indicatif.

### 3.2 Angel CoFund (Royaume-Uni) — filtre par exigence de syndicat qualifié + plafond de participation

**Mécanique [D/?]** :
- Fonds de **100 M£** ([ACF Investors](https://www.acfinvestors.com/), [British Business Bank](https://www.british-business-bank.co.uk/ourpartners/angel-cofund/)).
- Tickets de **100 000 £ à 1 M£**, **pari passu**.
- **Le fonds ne peut être approché directement par une société** : la société doit d'abord réunir un syndicat d'angels.
- Exigence structurante [D] : **un syndicat d'au moins 3 business angels sectoriellement spécialisés, incluant un lead apportant au moins 40 000 £** (ACF Investors).
- Participation publique **plafonnée à 49 % du tour** [D] (repris par l'[OCDE, note pays Royaume-Uni 2025](https://www.oecd.org/content/dam/oecd/en/publications/reports/2025/06/benchmarking-government-support-for-venture-capital-country-notes_2cacbf3f/united-kingdom_3c219488/5454ad97-en.pdf)).
- Due diligence et termes d'investissement **partagés** avec les angels.
- **[?]** Le ratio de levier annoncé — « chaque 1 £ investi par l'Angel CoFund a mobilisé environ 5 £ de syndicats d'angels » — est repris de communications de la British Business Bank **sans date de référence identifiable**. La page primaire renvoie un HTTP 403. Chiffre à ne pas citer comme courant.

**Lecture** : l'Angel CoFund empile **trois filtres mécaniques** que l'EAF n'a pas :
1. **Pluralité** (≥ 3 angels) — élimine le deal porté par un seul investisseur, donc réduit le risque d'investissement d'initié ou de complaisance ;
2. **Engagement du lead** (≥ 40 000 £) — impose un *skin in the game* minimal concentré, non dilué sur la foule ;
3. **Plafond à 49 %** — garantit que le capital privé reste majoritaire dans le tour.

**[I]** Ce triptyque est, sur le plan de la théorie de l'agence, un dispositif de sélectivité substantiellement plus contraignant que le simple *matching*. Le point 2 est le plus important : un plafond public en pourcentage ne dit rien de la **concentration** de l'exposition privée. Un tour où 40 angels mettent 1 000 £ chacun et un tour où un lead met 40 000 £ ont le même ratio public/privé mais des propriétés de sélection radicalement différentes — dans le premier cas, aucun investisseur n'a une exposition suffisante pour justifier une due diligence sérieuse. L'exigence d'un lead minimal corrige exactement ce défaut. **Je n'ai identifié aucune évaluation publiée mesurant l'effet propre de cette clause** ; c'est une inférence de conception.

### 3.3 French Tech Seed (Bpifrance) — double filtre : co-investissement **et** prescripteur labellisé

**Mécanique [D/?]** ([Bpifrance, OC French Tech Seed](https://www.bpifrance.fr/catalogue-offres/oc-french-tech-seed) — page primaire en HTTP 403, données issues de sources secondaires convergentes) :

- Fonds doté de **400 M€** dédié à l'amorçage deeptech, et **500 M€** au total pour le dispositif French Tech Seed selon les sources, dont 100 M€ gérés par l'équipe Investissements Transverses pour la phase 2. **[?]** Les deux montants (400 M€ / 500 M€) coexistent dans les sources ; non arbitré.
- Instrument public : **obligations convertibles (OC)**, pas de l'equity directe.
- Ratio : **2 € d'OC pour 1 € d'equity privée**, dans la limite de **50 000 € à 250 000 €** ; jusqu'à **500 000 €** dans la même limite de 2:1.
- Co-investissement privé exigé à hauteur d'au moins **30 % du tour** pour le mécanisme French Tech Seed.
- **Condition de labellisation** : la société doit être identifiée par un **prescripteur labellisé French Tech Seed**, via une lettre de prescription argumentant la sélection — **ou** être lauréate du Concours i-Lab ou du Concours national PIA.
- Fenêtre temporelle : tour d'amorçage bouclé depuis moins de 3 mois ou en cours de finalisation ; accord Bpifrance dans les 6 mois suivant la date d'effet du tour.

**Lecture** : deux différences de conception majeures par rapport à l'EAF et à l'Angel CoFund.

1. **Le filtre est doublé.** À la sélection par le co-investisseur privé s'ajoute une **accréditation tierce** (le prescripteur labellisé). C'est le seul des quatre dispositifs examinés qui n'accepte pas la seule signature privée comme preuve de qualité.
2. **L'argent public entre en obligations convertibles**, donc **senior à l'equity** dans l'ordre de liquidation, et avec un ratio de 2:1 en faveur du public.

**[I]** Ces deux traits ont des effets opposés sur l'efficience de l'euro public, et il faut le dire explicitement :
- Le double filtre **augmente** la sélectivité mais ajoute un coût de transaction et un délai (obtention de la lettre de prescription), et introduit un risque de capture : le réseau de prescripteurs devient un goulet d'étranglement dont la qualité conditionne tout le dispositif.
- La séniorité de l'OC **protège** le contribuable en cas d'échec partiel, mais **désaligne** l'exposition publique de l'exposition privée : contrairement au *pari passu* de l'EAF et de l'Angel CoFund, l'investisseur public ne partage pas le même profil de perte que l'angel. À ratio 2:1, l'angel apporte un tiers du capital tout en portant l'intégralité du risque de premier rang. **[I]** Cela renforce l'incitation de l'angel à la sélection (il est en première perte) mais réduit sa capacité à absorber le risque : sur un tour de 750 k€ dont 500 k€ d'OC publiques, l'angel qui met 250 k€ d'equity est effectivement en position de tranche equity d'une structure à levier 2×. **Cette caractérisation du profil de risque est une déduction de la structure de l'instrument, pas un résultat empirique.**

### 3.4 INVEST (Allemagne) — subvention directe à l'investisseur, sans sélection au niveau du deal

**Mécanique [D]** ([BAFA](https://www.bafa.de/DE/Wirtschaft/Beratung_Finanzierung/Invest/invest.html), [BAND](https://www.business-angels.de/en/invest-english/)) :

| Paramètre | Valeur |
|---|---|
| *Erwerbszuschuss* (subvention à l'acquisition) | **15 %** du prix d'acquisition des parts (taux abaissé depuis les 20-25 % antérieurs ; lignes directrices en vigueur depuis le 06/02/2023) |
| Investissement minimal | **10 000 €** par investisseur |
| Plafond de subvention | **50 000 € par investissement unique** ; **100 000 € cumulés par investisseur** |
| Plafond au niveau de la société | **3 M€** par année civile, tous investisseurs confondus |
| *Exitzuschuss* (subvention de sortie) | **25 %** du gain de cession, gain minimal 2 000 €, plafonné au montant de l'*Erwerbszuschuss* perçu |
| Durée de détention | **≥ 3 ans**, cession dans les 10 ans |
| Éligibilité société | < 7 ans, < 50 salariés, ≤ 10 M€ de CA ou de bilan, siège dans l'EEE **avec au moins un établissement en Allemagne**, caractère innovant (secteur, brevet, financement R&D public antérieur ou prix d'innovation) |
| Éligibilité investisseur | Personne physique **résidant dans l'EEE**, sans lien avec la société ; ou *Business Angels GmbH/UG* de 10 associés personnes physiques maximum ; émission d'actions nouvelles uniquement ; participation ≤ 25 % |

**[?]** Le plafond d'assiette par opération est incohérent entre sources : la déduction du plafond de subvention de 50 000 € à 15 % donne **333 333 €** d'assiette, tandis que BAND indique « maximum 200 000 € par investissement ». Non arbitré ; retenir le chiffre BAFA (source primaire).

**Bilan cumulé du dispositif [D]** ([BAND, chiffres BAFA au 30/09/2025](https://www.business-angels.de/posts/invest-zuschuss-fuer-wagniskapital-die-september-zahlen-2025-aus-dem-bafa-244/)) :
- **18 940** demandes de sociétés ; **32 259** demandes d'investisseurs.
- **353,44 M€** de subventions accordées (*Erwerbszuschuss*) depuis mai 2013.
- **177** demandes d'*Exitzuschuss*.
- **[?]** Une source rapporte 353,64 M€ au 31/12/2024, soit **plus** qu'au 30/09/2025. L'écart (−0,2 M€) suggère des annulations/révisions, ou une erreur de reprise. Non résolu.

**[C]** À un taux moyen situé entre 15 % (actuel) et 20-25 % (historique), 353,44 M€ de subventions correspondent à un volume d'investissement angel subventionné compris entre **~1,4 Md€ et ~2,4 Md€** sur 12 ans, soit de l'ordre de **120 à 200 M€ par an**. À rapprocher du marché angel allemand visible de **162,3 M€ en 2024** [D] (EBAN 2024, fig. 8). **[I]** Cela suggère qu'INVEST couvre une part très substantielle — possiblement la majorité — du marché angel allemand visible. Ce rapprochement est fragile (bases de mesure différentes, périmètres différents, marché visible sous-estimé) et **ne doit pas être présenté comme un taux de couverture**.

**[C]** Le ratio **177 demandes d'*Exitzuschuss* pour 18 940 demandes de sociétés** est frappant : ~0,9 %. Trois précautions avant toute interprétation : (i) l'*Exitzuschuss* n'existe que depuis 2017 ; (ii) il exige une **plus-value réalisée** ≥ 2 000 €, donc exclut toutes les sorties à perte ou en *pari passu* ; (iii) les demandes de sociétés ne sont pas des participations. **[I]** Sous ces réserves, ce ratio est néanmoins cohérent avec un régime où les sorties profitables sont rares — ce qui est la caractéristique attendue d'une distribution de rendements à queue épaisse, et non en soi un signe de mauvaise sélection.

### 3.5 Synthèse comparée : où se situe le filtre ?

| Dispositif | Niveau du filtre public | L'euro public suit-il automatiquement l'euro privé ? | Séniorité publique | Concentration privée imposée |
|---|---|---|---|---|
| **EAF (EIF)** | **Amont** : accréditation de l'angel sur *track record* | **Oui**, aucune revue deal par deal | *Pari passu* | Aucune (angel unique possible) |
| **Angel CoFund (UK)** | **Deal** : syndicat ≥ 3 + lead ≥ 40 k£ + plafond 49 % | Non : conditions cumulatives par tour | *Pari passu* | **Oui** (lead minimal) |
| **French Tech Seed (FR)** | **Double** : co-investisseur privé ≥ 30 % **+** prescripteur labellisé | Non : accréditation tierce requise | **Senior** (OC) | Non spécifiée |
| **INVEST (DE)** | **Aucun au niveau du deal** : critères d'éligibilité formels uniquement | **Oui**, de façon quasi automatique sous conditions d'éligibilité | Sans objet (subvention) | Aucune (min. 10 k€) |

**Conclusion analytique.** L'hypothèse d'un « tampon automatique » — l'euro public validant mécaniquement un flux privé de qualité quelconque — **n'est vérifiée telle quelle pour aucun des trois dispositifs de co-investissement**, mais pour des raisons différentes et avec des angles morts différents :

- L'EAF **assume** la délégation totale au niveau du deal, et compense par une sélection stricte en amont. Son angle mort est la dérive intra-portefeuille [I].
- L'Angel CoFund refuse la délégation totale et impose des conditions structurelles de syndication. Son coût est un flux de deals plus étroit (les tours sans lead qualifié sont exclus).
- French Tech Seed refuse la signature privée comme preuve suffisante. Son coût est un filtre administratif supplémentaire et un désalignement de séniorité.
- **INVEST est le seul dispositif où la critique du tampon automatique s'applique pleinement** : dès lors que la société et l'investisseur satisfont des critères formels, la subvention est due. Aucune caractéristique de conception ne fait dépendre la subvention de la qualité du deal, de la qualité de l'investisseur, ou de la présence d'un syndicat. C'est précisément le design que la littérature empirique disponible identifie comme le plus exposé (§ 5).

---

## 4. Effets d'incitation des dispositifs fiscaux au niveau de l'investisseur

### 4.1 Les paramètres en vigueur

**Royaume-Uni — EIS / SEIS** [D] ([HMRC / GOV.UK](https://www.gov.uk/guidance/venture-capital-schemes-apply-for-the-enterprise-investment-scheme), [synthèse Saffery 2026](https://www.saffery.com/insights/articles/eis-seis-vct-and-uk-investment-tax-reliefs-explained/)) :

| | EIS | SEIS |
|---|---|---|
| Réduction d'IR | **30 %** | **50 %** |
| Plafond annuel investisseur | **1 M£** (2 M£ si *knowledge-intensive*) | **200 000 £** |
| Plafond société | 12–24 M£ à vie ; 5–10 M£ / 12 mois (toutes VCS confondues) | **250 000 £** à vie |
| Éligibilité société | < 7 ans depuis 1re vente commerciale ; < 250 ETP ; actifs bruts < 30 M£ | < 3 ans ; < 25 salariés ; actifs bruts ≤ 350 000 £ |
| Détention minimale | 3 ans | 3 ans |
| Autres | Exonération de plus-value ; *loss relief* imputable sur le revenu ; report de plus-value | Exonération ; *reinvestment relief* de 50 % sur plus-values de l'année |

**France — IR-PME / Madelin** [D] ([service-public.fr](https://entreprendre.service-public.gouv.fr/vosdroits/F37091?lang=fr)) :

| Cible | Taux | Plafond de versement (célib. / couple) | Plafonnement des niches |
|---|---|---|---|
| PME classique (< 10 ans) | **18 %** | 50 000 € / 100 000 € | **Dans** le plafond global de 10 000 €/an, reportable 5 ans |
| ESUS/SFS (28/06/2024 – 30/09/2026) | 25 % | 50 000 € / 100 000 € | Dans le plafond global |
| **JEI** (< 8 ans, 2024–2028) | **30 %** | **75 000 € / 150 000 €** | **Hors** plafond de 10 000 € |
| **JEII** (21/02/2026 – 31/12/2028) | **40 %** | 50 000 € / 100 000 € | **Hors** plafond de 10 000 € |
| **JEIR** (2024–2028) | **50 %** | 50 000 € / 100 000 € | **Hors** plafond de 10 000 € |

- Réservé aux personnes **fiscalement domiciliées en France** [D].
- Société éligible : siège dans un **État membre de l'UE ou de l'EEE** [D].
- Détention : **5 ans** [D].
- Les réductions JEI/JEIR/JEII sont **exclues du plafonnement global de l'article 200-0 A du CGI**, mais soumises à un plafond cumulé propre de **50 000 € par foyer fiscal sur 2024–2028** [D] ; elles ne sont **pas reportables** [D].

**Allemagne — INVEST** : cf. § 3.4. Il ne s'agit pas d'une réduction d'impôt mais d'une **subvention en numéraire non imposable**, ce qui la rend accessible indépendamment du niveau d'imposition de l'investisseur [D].

### 4.2 Ce qui est documenté sur le comportement des investisseurs

**(a) Le levier fiscal opère sur l'allocation d'actifs, non sur la sélection du deal.**

C'est le résultat qualitatif le plus net et le plus directement pertinent pour la question de la sélectivité. Mason, Botelho & Duggett (2022), sur la base d'une enquête en ligne et de **21 entretiens semi-directifs** (15 en République d'Irlande, 6 en Irlande du Nord) [D] :

> « angels in both jurisdictions were unanimous that whereas the existence of tax incentives had an influence on how much of their investment portfolio that they would allocate to early stage businesses **they did not influence their investment decisions**. »

Et, dans les mots d'un angel interrogé [D] :

> « on the broad level of deciding how many investments to make in a year tax is important. But when evaluating a specific opportunity tax is not important. The quality and likelihood of success of a given opportunity are much more important. »

*Source [D] : [Mason, Botelho & Duggett, « Promoting cross-border investing by business angels in the European Union », Regional Studies 56(8), 2022, pp. 1391-1403](https://eprints.gla.ac.uk/247233/1/247233.pdf), p. 1397.*

**Implication mécanique directe** : un dispositif fiscal au niveau de l'investisseur agit sur la **marge extensive** (combien de capital l'individu alloue à la classe d'actifs early-stage) et non sur la **marge intensive** (quel deal il choisit). Il ne peut donc pas, par construction, améliorer la sélectivité — au mieux il est neutre sur ce plan. En revanche, il *peut* la dégrader s'il modifie la composition de la population d'investisseurs (cf. point (c)).

**(b) La sensibilité au taux est réelle mais non linéaire, et l'effet du retrait total est massif.**

Évaluation du SEIS commandée par HMRC (travaux Ipsos/Kantar/London Economics, publiés 2023) [D] ([GOV.UK, SEIS evaluation, executive summary](https://www.gov.uk/government/publications/evaluation-of-venture-capital-schemes/seed-enterprise-investment-scheme-evaluation-2022-executive-summary)) :

- La **suppression totale** de la réduction dissuaderait environ **46 %** des investisseurs de réaliser ces investissements à haut risque.
- Une **baisse de 5 points** du taux : **60 %** investiraient le même montant, **32 %** investiraient moins.
- Une **hausse de 5 points** : **55 %** investiraient le même montant, **42 %** investiraient davantage.
- Impacts estimés sur les sociétés (appariement par score de propension) : **+23 % de chiffre d'affaires**, **+12 % d'emploi**, **+245 % d'actifs** vs groupe de contrôle.
- **Résultat contre-intuitif à ne pas omettre** : « Participation in the SEIS is associated with **an increased probability of ceasing to trade** ».
- Limite reconnue par l'évaluation : les sociétés **s'auto-sélectionnent** dans le SEIS ; le PSM ne neutralise pas les différences inobservables.

Évaluation EIS/VCT (Kantar Public, 2022, publiée novembre 2023) [D] ([GOV.UK, EIS/VCT evaluation](https://www.gov.uk/government/publications/evaluation-of-venture-capital-schemes/venture-capital-scheme-eis-vct-evaluation-2022-executive-summary)) :

- **Deux tiers** des investisseurs auraient investi **différemment** sans la réduction, en choisissant des supports moins risqués.
- **Un peu plus d'un quart** auraient investi dans les **mêmes sociétés ou des sociétés similaires** sans le dispositif → **c'est la mesure directe du *deadweight* déclaré : ~27 %.**
- Ciblage : **95 %** des sociétés bénéficiaires de l'EIS sont des start-ups indépendantes nouvelles (contre 87 % dans le groupe de comparaison) ; **48 %** répondent à la définition *knowledge-intensive* (contre 17 %).
- **53 %** des sociétés bénéficiaires estiment qu'elles auraient probablement échoué sans l'EIS.
- **L'effet sur la survie est non concluant.**

**Nuance importante** : ces 27 % sont un *deadweight* **auto-déclaré par les bénéficiaires**, dans une enquête où l'incitation à sous-déclarer est évidente. C'est très probablement une **borne inférieure**. **[I]**

Mason et al. (2022) rapportent, sur l'île d'Irlande [D] : **46 %** des angels cesseraient d'investir si toutes les incitations fiscales étaient supprimées, **34 %** réduiraient leur activité. L'écart entre Irlande du Nord (**56 %** cesseraient) et République d'Irlande (**41 %**) est attribué par les auteurs à la générosité supérieure du SEIS/EIS britannique par rapport à l'EII irlandais — les angels irlandais jugeant l'EII moins favorable, notamment par l'**absence d'exonération de plus-value** [D].

**(c) L'effet de composition : les incitations attirent des investisseurs différents — et c'est le résultat le plus préoccupant.**

Denes, Howell, Mezzanotti, Wang & Xu, *Journal of Finance* 78(5), 2023, exploitant l'introduction et la suppression échelonnées de crédits d'impôt angels dans **31 États américains** entre 1988 et 2018 [D] ([NBER WP 27751](https://www.nber.org/papers/w27751), version de travail [Kellogg](https://www.kellogg.northwestern.edu/faculty/mezzanotti/documents/tax_credit_DHMWX.pdf)) :

| Résultat | Estimation |
|---|---|
| Effet sur le **nombre d'investissements** angels | **+18 %** |
| Effet sur le **nombre d'investisseurs** angels | **+32 %** |
| Effet sur la création d'entreprises high-tech et l'emploi | **Nul**, statistiquement non significatif, intervalles de confiance étroits |
| Puissance : effet estimé sur le nombre de jeunes sociétés high-tech | **−0,3 %**, contre un MDE de **1,9 %** à 80 % de puissance et un *prior* de **3,3 %** |
| Sociétés bénéficiaires ayant ≥ 1 investisseur dirigeant ou membre de la famille d'un dirigeant | **35 %** (contre **8 %** parmi les sociétés angel-backed sur AngelList) |
| Investisseurs jugeant les crédits d'impôt « pas du tout importants » | **51 %** de l'échantillon ; **71 %** parmi les plus expérimentés |
| Investisseurs jugeant l'équipe dirigeante « très ou extrêmement importante » | **97 %** |
| Motif invoqué pour l'indifférence aux crédits | **57 %** : « j'investis selon le potentiel de *home run* » |
| Taille de l'enquête | **1 411** répondants |

Résultats qualitatifs clés [D] :
- L'investissement additionnel va vers **des sociétés plus âgées, à croissance de l'emploi plus faible, et portées par moins d'entrepreneurs sériels**. Les caractéristiques de croissance ex ante des sociétés angel-backed de l'État **se dégradent** après l'introduction du crédit.
- **Éviction** : l'investissement early-stage **non-angel diminue**, tandis que l'investissement early-stage total **ne change pas**. Une partie de l'effet est donc du **ré-étiquetage** d'opérations qui auraient eu lieu de toute façon.
- Les investisseurs bénéficiaires sont **plus jeunes, plus locaux et moins expérimentés** que l'angel moyen ; l'entrée de professionnels *arm's length* est faible.
- Mécanisme théorique proposé et formalisé : dans une distribution de rendements à **queue droite épaisse**, le bénéfice marginal d'une subvention proportionnelle **décroît** quand le rendement espéré augmente. Les investisseurs les plus performants sont donc **structurellement les moins sensibles** à ce type d'incitation.

**Portée et limites de ce résultat** — à énoncer explicitement :
- Il s'agit de **crédits d'impôt d'États américains**, pas de dispositifs européens. Les paramètres diffèrent (taux, plafonds, conditions d'éligibilité, existence ou non d'un test anti-optimisation).
- Le dispositif britannique comporte une **condition de risque en capital** (§ 4.3) explicitement conçue pour bloquer le mécanisme de préservation de capital, que la plupart des programmes d'États américains n'ont pas.
- **[I]** Le mécanisme théorique (décroissance du bénéfice marginal de la subvention quand la queue droite s'épaissit) est en revanche **indépendant de la juridiction**. Il implique que *tout* dispositif proportionnel au montant investi sera, mécaniquement, plus attractif pour les investisseurs à faible espérance de rendement que pour les meilleurs. C'est une propriété structurelle, pas un accident de conception américain. **Aucune réplication européenne de ce résultat n'a été identifiée** — c'est la principale lacune de la littérature sur le sujet.
- Mason et al. (2022) résument par ailleurs la littérature antérieure dans le même sens [D] : les incitations fiscales augmentent l'activité d'investissement et les rendements des angels, mais « there is also evidence that they **disproportionately attract inexperienced investors, distort resource allocation, predominantly to poor quality deals and has poorer exit outcomes** » (Carpentier & Suret 2016 ; Denes et al. 2019 ; Harrison et al. 2020).

### 4.3 Le seul mécanisme de sélectivité intégré à un dispositif fiscal européen : la *risk-to-capital condition*

**[D]** Le Royaume-Uni a introduit en 2018 (Finance Act 2018) une **condition de risque en capital** applicable au SEIS et à l'EIS. Elle est **fondée sur des principes** (pas de règles chiffrées) et comporte **deux volets cumulatifs** ([HMRC VCM8540](https://www.gov.uk/hmrc-internal-manuals/venture-capital-schemes-manual/vcm8540), [VCM8530](https://gov.uk/hmrc-internal-manuals/venture-capital-schemes-manual/vcm8530)) :

1. la société doit avoir des **objectifs de croissance et de développement à long terme** ;
2. l'investissement doit comporter un **risque significatif que l'investisseur perde plus de capital qu'il n'obtient de retour, réductions fiscales incluses**.

**[D]** L'objectif explicite est d'exclure les montages de **préservation de capital** offrant un rendement à faible risque dont le bénéfice principal serait la réduction d'impôt. HMRC surveille notamment le fractionnement d'une même activité entre plusieurs sociétés (SPV parallèles, mêmes promoteurs, activités alignées dans des géographies différentes) pour multiplier la réduction.

**Lecture micro.** C'est le seul exemple identifié, parmi les dispositifs examinés, d'un **filtre de sélectivité intégré à l'incitation fiscale elle-même**, opérant au niveau du deal. Il attaque directement le mécanisme le plus nocif décrit par Denes et al. — celui par lequel une subvention proportionnelle rend attractive une opération dont le rendement pré-fiscal est médiocre mais le risque faible.

**Coût de ce filtre [D]** : la nature principielle du test, sans seuils chiffrés, transfère l'incertitude sur l'émetteur. C'est mesurable dans les taux d'agrément préalable (*advance assurance*) 2025-26 [D] ([HMRC, statistiques EIS/SEIS 2026](https://www.gov.uk/government/statistics/enterprise-investment-scheme-and-seed-enterprise-investment-scheme-may-2026/enterprise-investment-scheme-and-seed-enterprise-investment-scheme-2026)) :
- EIS : **3 310** demandes reçues, **2 365 approuvées (72 %)**.
- SEIS : **4 085** demandes reçues, **3 090 approuvées (76 %)**.

**[C]** Environ **un quart des demandes d'agrément préalable n'aboutit pas**. Sur des tours dont la médiane SEIS est faible (cf. § 4.4), le coût d'option — conseil, délai, incertitude — porté par des sociétés de moins de 25 salariés est réel. **[I]** Ce taux d'échec est le prix explicite de la sélectivité principielle : un test à seuils chiffrés serait plus prévisible mais immédiatement contournable par ingénierie, ce qui est précisément ce que HMRC cherche à éviter.

### 4.4 Distribution et concentration : qui capte réellement la dépense fiscale

**Données HMRC, exercice fiscal 2024-25** [D] ([GOV.UK, EIS/SEIS statistics 2026](https://www.gov.uk/government/statistics/enterprise-investment-scheme-and-seed-enterprise-investment-scheme-may-2026/enterprise-investment-scheme-and-seed-enterprise-investment-scheme-2026)) :

| | EIS | SEIS |
|---|---|---|
| Sociétés ayant levé | **3 735** (vs 3 775 en 2023-24) | **2 430** (vs 2 310) |
| Montant levé | **1 575 M£** (stable) | **276 M£** (+14 %) |
| Dont sociétés nouvelles au dispositif | 1 145 sociétés / **333 M£** (21 % du total) | 1 775 sociétés / **229 M£** (83 % du total) |
| Investisseurs réclamant la réduction d'IR | **33 220** (vs 35 675, **−7 %**) | **11 200** (vs 10 290) |
| Secteur *Information & Communication* | 550 M£ (**35 %**) | 115 M£ (**42 %**) |
| Londres & Sud-Est | 948 M£ (**60 %**) | 181 M£ (**66 %**) |
| Concentration par ticket | Investissements > 500 000 £ = **20 % du montant total** | Investissements > 25 000 £ = **66 % du montant** ; **56 %** des investisseurs à ≤ 10 000 £ |

**[C]** Ticket moyen par investisseur : **EIS 1 575 M£ / 33 220 = ~47 400 £** ; **SEIS 276 M£ / 11 200 = ~24 600 £**. (Réserve : une part de l'investissement EIS transite par des fonds, ce qui gonfle le montant par investisseur déclarant.)

**Trois observations micro qui ne ressortent pas d'une lecture juridique :**

1. **Le SEIS et l'EIS ne financent pas la même chose.** 83 % des montants SEIS vont à des sociétés **nouvelles au dispositif**, contre 21 % pour l'EIS. L'EIS est majoritairement un instrument de **refinancement de sociétés déjà dans le système** — ce qui, en soi, n'est pas un défaut (les tours de suivi sont nécessaires), mais signifie que **l'additionnalité à l'entrée doit être évaluée quasi exclusivement sur le SEIS**. Une évaluation d'additionnalité menée sur l'agrégat EIS+SEIS mélange deux fonctions économiques distinctes.

2. **La distribution des tickets est extrêmement asymétrique et diffère entre les deux dispositifs.** Côté SEIS, 56 % des investisseurs sont à ≤ 10 000 £ mais les tickets > 25 000 £ concentrent 66 % des montants. Côté EIS, les tickets > 500 000 £ représentent 20 % du total. **[I]** Cela signifie que le coût budgétaire marginal du dispositif est déterminé par une **petite minorité d'investisseurs à fort ticket**, alors que le discours de politique publique porte généralement sur la démocratisation de l'investissement. Un plafonnement par investisseur et un plafonnement par société ont des effets budgétaires et sélectifs très différents, et c'est le premier qui pilote la dépense.

3. **Le nombre d'investisseurs EIS recule (−7 %) alors que le montant est stable.** **[C]** Mécaniquement, le ticket moyen augmente : la base d'investisseurs se **concentre**. **[I]** Si cette tendance se confirme, l'EIS évolue d'un dispositif de mobilisation large vers un dispositif de subvention d'un noyau réduit d'investisseurs fortunés — ce qui change la nature de la question d'additionnalité (un noyau expérimenté est, d'après Denes et al., précisément la population **la moins sensible** aux incitations fiscales, donc celle où le *deadweight* est le plus élevé). Une seule année d'observation ne permet pas de conclure.

### 4.5 Un effet de seuil français : la discontinuité JEIR

**[C]** Le régime français crée une discontinuité de subvention d'une amplitude rarement égalée. Pour un même versement de 50 000 € :

| | PME classique | JEIR |
|---|---|---|
| Taux | 18 % | 50 % |
| Réduction brute | 9 000 € | 25 000 € |
| Plafonnement des niches (10 000 €/an) | **Applicable** | **Non applicable** |
| Coût net de 1 € investi | **0,82 €** (si le plafond de 10 000 € n'est pas déjà saturé) | **0,50 €** |
| Coût net de 1 € investi **si le plafond de 10 000 € est déjà saturé par d'autres niches** | **1,00 €** (réduction marginale nulle) | **0,50 €** |

*Sources [D] : [service-public.fr](https://entreprendre.service-public.gouv.fr/vosdroits/F37091?lang=fr) ; art. 199 terdecies-0 A bis et ter du CGI (hors plafonnement de l'art. 200-0 A), plafond cumulé propre de 50 000 € par foyer sur 2024-2028.*

**Lecture** : le rapport des **taux de subvention** entre une PME ordinaire et une JEIR est de **2,78×** (50 % / 18 %), et le rapport des **coûts nets** de 1 € investi de **1,64×** (0,82 € / 0,50 €). Dans le cas — courant chez les contribuables aisés — où le plafond global de 10 000 € est déjà consommé par d'autres niches, la réduction marginale sur une PME ordinaire tombe à **zéro** tandis que celle sur une JEIR reste à 50 % : l'écart devient **infini**. **[I]** Cette discontinuité crée une incitation puissante à **orienter le capital angel vers le label JEIR plutôt que vers le meilleur couple rendement/risque disponible**, et une incitation symétrique pour les sociétés à structurer leur activité (intensité de R&D, ancienneté) pour franchir le seuil. C'est un exemple canonique d'effet de seuil (*cliff-edge*) : la subvention ne varie pas continûment avec la caractéristique visée (l'intensité de recherche) mais saute discrètement au franchissement d'un critère administratif. **Aucune donnée sur le *bunching* effectif de sociétés autour du seuil JEI/JEIR n'a été identifiée** ; l'effet est déduit de la structure du barème, non mesuré.

**[C]** Second effet, plus discret : le plafond général de **10 000 €/an** de l'article 200-0 A est atteint par un versement de **55 556 €** à 18 %, soit **au-dessus** du plafond de versement de 50 000 € pour un célibataire. Pour un célibataire n'ayant aucune autre niche, le plafond de versement est donc mordant avant le plafonnement global. Pour un couple (plafond de versement 100 000 €), le plafonnement global mord dès **55 556 €** de versement, soit à 56 % du plafond de versement affiché. **Le plafond de versement de 100 000 € annoncé pour un couple est donc, en pratique, largement fictif** dès lors qu'aucune autre niche n'est mobilisée.

---

## 5. Efficience de l'euro public au niveau transactionnel

### 5.1 Sélection adverse : ce que dit et ne dit pas la littérature

**Le raisonnement de conception, tel que formulé par l'OCDE [D]** ([OCDE, *Understanding Government Venture Capital*, STI Working Paper 2025/06](https://www.oecd.org/content/dam/oecd/en/publications/reports/2025/04/understanding-government-venture-capital_e8417edc/2157a5b3-en.pdf), p. 31-32) :

> les gestionnaires de fonds de co-investissement publics « cannot make independent investment decisions, but need to find private co-investment partners alongside which they make their investment. While this limits the scope of investment opportunities that the government co-investment fund managers can pursue, **it serves to prevent investments in dimly positioned business models as private investors should have a stronger incentive to safeguard their investments** ».

C'est exactement l'argument du filtre par le co-investissement privé. L'OCDE le présente comme un raisonnement de conception, formulé au conditionnel (« *should have* »), **pas comme un résultat empirique**.

**Ce que l'OCDE documente par ailleurs [D]** (même source) :
- La littérature sur les fonds de VC publics est **ambiguë** : effets positifs de comblement de lacunes (Cumming 2007 ; Avnimelech & Teubal 2006) *versus* éviction du privé (Cumming & MacIntosh 2006), financement d'innovations marginales (Kovner & Lerner 2015 ; Bertoni & Tykvová 2015), impact faible sur la performance (Grilli & Murtinu 2014 ; Cumming, Grilli & Murtinu 2017).
- Sur la **syndication** spécifiquement, les résultats sont **positifs** : effet positif de la syndication avec des co-investisseurs privés (Alperovych, Groh & Quas 2020), dépassant même en matière d'innovation la performance des investissements purement privés (Bertoni & Tykvová 2015 ; Clò, Frigerio & Vandone 2022).
- **Problème d'agence côté public** : « Since the government observes outcomes and does not take investment decisions itself, **it is difficult for it to know whether failures are a result of increased idiosyncratic risk in investment opportunities (as intended by the government) or lower effort by the fund manager.** » C'est le cœur du problème d'aléa moral dans tout dispositif délégué — et il s'applique intégralement à l'EAF.
- L'OCDE cite explicitement l'EAF comme exemple de fonds de co-investissement public : « Investment decisions are taken by the Business Angels and their investments are then matched on a pari-passu basis by EAF. »

**Sur la sélection adverse en co-investissement, le résultat empirique de référence est plutôt rassurant [D]** : Braun, Jenkinson & Schemmerl, « Adverse selection and the performance of private equity co-investments », *Journal of Financial Economics* 136(1), 2020, pp. 44-62 — **aucune preuve de sélection adverse**, les distributions de rendements bruts des co-investissements et des autres opérations étant similaires. **Réserve importante [I]** : cette étude porte sur le *private equity* institutionnel (co-investissements de LP aux côtés de GP), **pas sur le co-investissement public aux côtés de business angels**. La structure d'information et les incitations diffèrent substantiellement. La transposition n'est pas acquise.

### 5.2 Effet d'aubaine (*deadweight*) et éviction : les estimations disponibles

| Source | Population | Estimation |
|---|---|---|
| Évaluation EIS/VCT HMRC 2022 [D] | Investisseurs EIS/VCT UK | **~27 %** auraient investi dans les mêmes sociétés ou des sociétés similaires sans le dispositif (*deadweight* auto-déclaré, borne inférieure probable) |
| Évaluation EIS/VCT HMRC 2022 [D] | Investisseurs EIS/VCT UK | **~2/3** auraient investi **différemment** (supports moins risqués) → additionnalité sur le profil de risque |
| Évaluation SEIS HMRC 2022 [D] | Investisseurs SEIS UK | **46 %** dissuadés par la suppression totale de la réduction |
| Mason et al. 2022 [D] | Angels île d'Irlande | **46 %** cesseraient, **34 %** réduiraient si toutes incitations supprimées |
| Denes et al. 2023 [D] | 31 États US, 1988-2018 | Éviction : investissement early-stage **non-angel diminue**, total **inchangé** ; **35 %** des bénéficiaires ont un investisseur initié (vs 8 % de référence) |
| Évaluations HMRC [D] | Sociétés / investisseurs / conseils | « businesses and investors were **more likely to think that investment would have gone ahead anyway** in some form, without the facility, compared to the agents » |

**[I]** Ces estimations ne sont pas commensurables : elles portent sur des populations, des dispositifs et des contrefactuels différents, et les mesures déclaratives (HMRC, Mason) sont structurellement biaisées vers la sous-déclaration du *deadweight* tandis que la mesure quasi-expérimentale (Denes) capte un effet net d'équilibre local. **Il n'existe, à ma connaissance, aucune estimation quasi-expérimentale de l'additionnalité d'un dispositif fiscal angel européen.** C'est la lacune la plus lourde de ce dossier.

**[I]** Une occasion d'identification est disponible et non exploitée : l'Allemagne a **abaissé le taux de l'*Erwerbszuschuss* INVEST de 20-25 % à 15 %** avec effet au 6 février 2023 [D]. Il s'agit d'une variation exogène, datée, de l'intensité de la subvention, sur un dispositif dont l'administration (BAFA) dispose de données individuelles investisseur-société. **Aucune évaluation exploitant cette discontinuité n'a été identifiée.**

### 5.3 Caractéristiques de conception associées à la sélectivité — état de la preuve

| Caractéristique | Mécanisme d'action | État de la preuve |
|---|---|---|
| **Exigence d'un lead privé avec engagement minimal** (Angel CoFund : ≥ 40 k£) | Concentre l'exposition privée sur un acteur ayant intérêt à supporter le coût de la due diligence | **[I]** Cohérent avec la théorie de l'agence. **Aucune évaluation isolant cet effet identifiée.** |
| **Pluralité du syndicat** (≥ 3 angels) | Réduit le risque d'investissement d'initié et de complaisance | **[I]** Le contre-exemple de Denes et al. (35 % d'initiés dans un dispositif *sans* exigence de pluralité, vs 8 % de référence) est cohérent mais indirect [D]. |
| **Plafond de participation publique** (≤ 49 % du tour) | Garantit la majorité privée du tour | **[D]** Documenté comme paramètre de l'Angel CoFund. Effet propre non évalué. |
| **Accréditation ex ante de l'investisseur sur *track record*** (EAF) | Déplace le filtre en amont, évite le coût d'instruction par deal | **[D]** Le mécanisme est documenté ; **son efficacité relative n'a pas été évaluée publiquement.** |
| **Accréditation tierce de la cible** (prescripteur French Tech Seed) | Ajoute un filtre indépendant du co-investisseur | **[D]** Mécanisme documenté. Effet non évalué. Risque de goulet/capture [I]. |
| **Test principiel anti-optimisation** (*risk-to-capital*, UK) | Exclut ex ante les montages de préservation de capital | **[D]** Mécanisme et objectif documentés (HMRC VCM8530/8540). **Effet quantitatif non évalué publiquement** ; les taux de refus d'agrément (24-28 %) en donnent une mesure indirecte du mordant [C]. |
| **Plafond par société** | Limite l'exposition concentrée et le fractionnement | **[D]** Paramètres documentés (SEIS 250 k£ à vie ; INVEST 3 M€/an/société ; EIS 12-24 M£ à vie). HMRC documente explicitement la surveillance du fractionnement en SPV parallèles. |
| **Séniorité de l'instrument public** (OC French Tech Seed) | Protège le contribuable ; désaligne l'exposition | **[D]** Mécanisme documenté. **[I]** Arbitrage protection/alignement non évalué. |
| **Subvention proportionnelle sans condition de deal** (INVEST) | Aucun filtre au niveau du deal | **[D]** C'est le design pour lequel les résultats de Denes et al. sont les plus directement pertinents — mais ceux-ci portent sur des dispositifs **américains** [I]. |

### 5.4 Une asymétrie de conception rarement relevée : le coût d'instruction par euro déployé

**[C]** Rapprochement des ordres de grandeur :
- Ticket angel moyen européen : **25 600 €** [D].
- Investissement médian d'un angel EAF dans une société au premier tour : **~128 000 €** [D].
- Ticket public EAF correspondant (1:1) : **~128 000 €** [C].
- Ticket public Angel CoFund : **100 000 – 1 000 000 £** [D].
- Ticket public French Tech Seed : **50 000 – 500 000 €** [D].

**[I]** À ces montants, une instruction publique dossier par dossier avec due diligence propre coûterait probablement plusieurs pourcents du montant déployé. C'est l'argument économique — rarement explicité dans les documents de programme — qui justifie la délégation de la décision d'investissement. La question de conception pertinente n'est donc pas « faut-il déléguer ? » (à ces tickets, la délégation est quasi imposée par les coûts) mais **« à quel niveau placer le filtre, et quelle contrainte structurelle imposer au délégataire ? »**. Les quatre dispositifs examinés répondent différemment ; aucun n'a été évalué contre les autres.

---

## 6. Frictions transfrontalières : mécanismes concrets

### 6.1 La mesure de référence : le biais domestique persiste même quand le dispositif l'autorise

Le portefeuille EAF fournit le test le plus propre disponible, parce que la contrainte contractuelle y est **explicite et non saturée** [D] ([EIF WP 2020/62](https://www.econstor.eu/bitstream/10419/213873/1/1689254033.pdf), pp. 17-21) :

| Indicateur | Valeur |
|---|---|
| Part internationale **contractuellement autorisée** par angel | **20 % à 50 %** du portefeuille |
| Part internationale **effectivement réalisée** | **12 %** |
| Sociétés investies situées dans le **même pays** que l'investisseur | **88 %** (recevant **81 %** du capital) |
| Investissements dans la **même commune** que l'angel | **> 1 sur 4** |
| Investissements dans la **même région NUTS3** | **~4 sur 10** |
| **Distance médiane** angel–société | **124 km** |
| Distance **moyenne** | **458 km** (écart médiane/moyenne dû à des valeurs extrêmes intercontinentales) |
| 95e percentile de distance | **945 km** |
| Flux domestiques intra-NUTS3 | **45 %** des flux domestiques |

**Ce résultat est décisif pour l'analyse.** Chez des angels **expérimentés, sélectionnés, dotés de capital public apparié, et contractuellement autorisés** à consacrer jusqu'à la moitié de leur portefeuille à l'international, la part internationale réalisée est de **12 %** — soit **moins du quart de la borne haute autorisée**. Les auteurs concluent : « This reflects BAs' natural tendency to invest locally » [D].

**Implication mécanique** : la contrainte qui limite l'investissement transfrontalier des angels **n'est pas, en première approximation, une contrainte réglementaire ou contractuelle**. Retirer la contrainte ne suffit pas : elle n'était pas mordante. La contrainte est dans la **fonction de production de l'investissement angel** elle-même.

Deux confirmations dans les mêmes données [D] :
- Les investissements lointains sont **plus gros** : les flux intra-NUTS3 sont en moyenne **15 % plus petits** que les flux domestiques inter-NUTS3 (13 % hors 5 % de valeurs extrêmes). Cohérent avec un **coût fixe** d'investigation à distance qu'il faut amortir sur un ticket plus élevé.
- Les angels ne cherchent des opportunités lointaines **qu'après épuisement des opportunités locales** [D] (les auteurs le documentent par la distance moyenne croissante selon le rang chronologique de l'investissement dans le portefeuille).

### 6.2 Les six mécanismes de friction, du plus au moins documenté

**(1) Non-portabilité des incitations fiscales — la friction la mieux documentée.**

Mason et al. (2022) [D] : « with few exceptions, governments **restrict tax incentives to individuals and businesses in their own jurisdictions**, potentially discouraging angels from making investments in other countries » ; et « Government funding programmes that **co-invest alongside business angels are also restricted to their own jurisdiction** ».

L'examen des paramètres des trois dispositifs nationaux montre que la non-portabilité opère sur **deux dimensions distinctes qui ne se recoupent jamais complètement** :

| Dispositif | Condition sur l'**investisseur** | Condition sur la **société cible** |
|---|---|---|
| **IR-PME (FR)** [D] | **Domicilié fiscalement en France** | Siège dans **l'UE ou l'EEE** ✔ ouvert |
| **INVEST (DE)** [D] | Résidence principale dans **l'EEE** ✔ ouvert | Siège dans l'EEE **avec au moins un établissement en Allemagne** |
| **EIS/SEIS (UK)** [D] | Contribuable britannique (relief d'IR britannique) | Société ayant un établissement permanent au Royaume-Uni |

**[C] Conséquence pratique — trois couples pays-investisseur × pays-cible** :

| Couple | IR-PME (FR) | INVEST (DE) | EIS/SEIS (UK) | Résultat |
|---|---|---|---|---|
| Angel **FR** → start-up **DE** | ✔ (domicile FR ✔, cible UE/EEE ✔) | ✔ (résidence EEE ✔, établissement DE ✔) | — | **Cumul des deux dispositifs** |
| Angel **DE** → start-up **FR** | ✘ (non domicilié en France) | ✘ (cible sans établissement allemand) | — | **Subvention nulle** |
| Angel **FR** → start-up **UK** | ✘ (cible hors UE/EEE depuis le Brexit) | — | ✘ (aucun impôt britannique à réduire) | **Subvention nulle** |

Le premier cas résulte d'une combinaison fortuite : la France ouvre son dispositif aux cibles de l'UE/EEE, l'Allemagne ouvre le sien aux investisseurs résidant dans l'EEE. **Aucune coordination n'a produit ce résultat** — c'est le recoupement accidentel de deux ouvertures unilatérales portant sur des dimensions différentes. Le cas symétrique (angel allemand vers cible française) ne bénéficie d'aucune des deux ouvertures.

**Lecture** : la non-portabilité ne produit pas une friction uniforme mais une **matrice très irrégulière** de couples pays-investisseur × pays-cible, dont certaines cases sont doublement subventionnées et d'autres nulles. **[I]** Cette irrégularité est probablement plus dommageable qu'un niveau de subvention uniformément bas, parce qu'elle introduit un différentiel de coût du capital arbitraire entre destinations, sans rapport avec la qualité des projets. **Aucune quantification de cette matrice n'a été identifiée.**

Illustration empirique documentée [D] (Mason et al. 2022, île d'Irlande) : un angel d'Irlande du Nord investissant en République d'Irlande **perd le bénéfice de l'EIS/SEIS** sans acquérir celui de l'EII irlandais ; réciproquement pour un angel de la République investissant en Irlande du Nord. Les auteurs mesurent l'asymétrie qui en résulte : **56 %** des angels nord-irlandais cesseraient d'investir sans incitations fiscales, contre **41 %** au Sud — écart attribué à la générosité supérieure du régime britannique, l'EII étant jugé moins favorable notamment par l'**absence d'exonération de plus-value**.

**(2) Restriction géographique des dispositifs de co-investissement public.**

**[D]** Confirmé par les paramètres eux-mêmes : les compartiments EAF sont **nationaux** (Allemagne, Espagne, Autriche, Irlande, Pays-Bas, Danemark, Flandre) avec obligation contractuelle pour l'angel de consacrer « the lion share » de ses investissements au marché domestique du compartiment. Un compartiment paneuropéen **EAF Europe** existe spécifiquement pour les investissements transfrontaliers [D]. Détail mécanique révélateur [D] : deux angels rattachés au compartiment **EAF Germany** sont physiquement établis en Belgique et en Suisse — **la restriction géographique porte sur le pays du programme, non sur la localisation de l'angel**. Leurs investissements sont donc majoritairement dirigés vers l'Allemagne.

**(3) Coût d'information et de sourcing.**

**[D]** Enquête EBAN 2020 auprès de **90 business angels actifs dans 11 pays européens** : **55 % de ceux ayant réalisé des investissements transfrontaliers** les ont jugés « difficult » ou « very difficult » (citée par Mason et al. 2022, p. 1391).

**[D]** Mason et al. identifient le mécanisme : l'investissement à distance impose de gérer des **coûts d'information plus élevés** (asymétries d'information, incertitude, coûts de transaction du maintien de la relation). Les angels expérimentés y parviennent parce qu'ils disposent de réseaux géographiquement dispersés — donc d'un flux de deals non local et de personnes de confiance sur place à qui déléguer la due diligence et le suivi post-investissement. Cowling et al. (2021) montrent que **les investisseurs plus expérimentés sont beaucoup plus disposés à investir à distance** [D].

**(4) Proximité requise par la nature même du travail d'angel.**

**[D]** Mason et al. : au stade de la due diligence, l'attention porte sur des **intangibles** — capacité de leadership, fiabilité, enthousiasme — et non sur des attributs vérifiables. « Trust is particularly important » ; les facteurs humains sont la raison dominante de rejet d'une opportunité. **[I]** C'est le mécanisme le plus fondamental et le moins réductible par la politique publique : l'input critique de la sélection angel (le jugement sur des personnes) a un rendement décroissant à la distance qu'aucun dispositif fiscal ou de co-investissement ne compense.

**(5) Hétérogénéité juridique, fiscale et de forme sociale.**

**[D]** Mason et al. citent Shane (2005) : les différences de régimes juridique, fiscal, réglementaire et de gouvernance, et les coûts liés au recours à des avocats et comptables étrangers et à la traduction de documents, créent des obstacles. Une enquête paneuropéenne (Ali et al. 2017) identifie **l'absence de cadres juridiques harmonisés** comme barrière.

Mollen (2019) décompose la friction fiscale en **trois strates** [D] :
1. la **fiscalité de la start-up** dans le pays cible (IS, charges sociales) ;
2. la **fiscalité locale de la cession** de la participation de l'angel ;
3. les **incitations fiscales** offertes aux angels — « the most influential », car restreintes aux résidents et aux entreprises nationales.

**[D]** À cela s'ajoute la friction de forme sociale documentée au § 2.1 : la conversion d'un instrument convertible exige, selon la juridiction, une résolution d'associés notariée (Allemagne), une assemblée (France, Espagne) ou une résolution statutaire (Royaume-Uni) — chaque syndicat transfrontalier devant se conformer au droit de la cible.

**(6) Risque de change.**

**[D]** Mason et al. : « The existence of different currencies creates additional risks arising from exchange rate fluctuations. » Mécanisme direct mais de portée limitée à l'intérieur de la zone euro ; il concerne principalement les couples impliquant SEK, DKK, PLN, CZK, HUF, CHF et GBP.

### 6.3 Le mécanisme qui fonctionne empiriquement : le modèle « chapter »

**[D]** Mason et al. documentent que des groupes d'angels opérant selon un **modèle de chapitres internationaux** (ex. Keiretsu) parviennent à surmonter les facteurs inhibant l'investissement à distance. Mécanique précise : les chapitres opèrent dans deux localisations ou plus **sous la même marque et le même management** (mais avec leur propre *gatekeeper*), utilisent des **procédures standardisées** de génération de flux, de screening et de due diligence, et organisent des formations et événements communs créant un espace de construction de relations de confiance entre membres des différents chapitres. Cela donne à l'angel individuel accès à un **flux de deals déjà filtré auquel il peut se fier**, et facilite le co-investissement aux côtés d'angels d'autres chapitres avec qui la confiance est déjà établie. **[D]** HBAN a adopté cette approche en remplacement de son modèle antérieur de partenariat entre organisations distinctes en Irlande du Nord et en République d'Irlande.

**[I]** Ce mécanisme agit directement sur les frictions (3) et (4) — les deux que le levier fiscal ne peut pas atteindre — en **industrialisant la production de confiance et de flux filtré**. Il ne traite ni (1) ni (2) ni (5). L'existence d'un compartiment **EAF Europe** dédié au transfrontalier [D] indique que l'EIF a identifié le même besoin, mais aucune donnée publique sur la taille ou la performance de ce compartiment n'a été identifiée.

### 6.4 Contexte réglementaire en cours (2025-2026)

**[D]** La Commission a adopté le **28 mai 2025** la *EU Startup and Scaleup Strategy* (COM(2025) 270 final), comportant **26 mesures** législatives, réglementaires et financières. Éléments pertinents identifiés :
- **Soutien aux business angels européens et à leurs réseaux**, annoncé pour **2026**.
- **« 28e régime »** : cadre juridique de société optionnel, à l'échelle de l'UE, parallèle aux droits nationaux, visant notamment une constitution en **48 heures** ; proposition attendue **T1 2026**. Consultation publique lancée le **8 juillet 2025**.
- **Scaleup Europe Fund** : véhicule à gestion privée et cofinancé, lancement soutenu en **2026**.

**[?]** Je n'ai pas pu extraire le texte du document COM(2025) 270 final (PDF principalement composé d'images ; extraction textuelle infructueuse). Les éléments ci-dessus proviennent de **sources secondaires** ([Morgan Lewis](https://www.morganlewis.com/pubs/2025/07/a-union-of-innovation-the-eu-strategy-for-startups-and-scale-ups), Chambers, BSP) et doivent être vérifiés sur le texte officiel avant citation. **En particulier, aucune source secondaire consultée ne mentionne de mesure portant sur la portabilité transfrontalière des incitations fiscales aux investisseurs** — la friction (1), la mieux documentée. Cette absence est notable mais ne peut être affirmée sans lecture du texte primaire.

---

## 7. Points de friction transactionnels : synthèse

| Friction | Mécanisme précis | Ordre de grandeur | Fiabilité |
|---|---|---|---|
| **Coût fixe de structuration** | Revue juridique + fiscale par juridiction, forme notariée (DE), formalités sociétaires (FR/ES) | ~3 000–8 000 € par opération → **~12 % à 31 % d'un ticket angel moyen de 25 600 €** | [?] coûts issus d'un blog de cabinet ; [C] pour le ratio |
| **Incertitude d'agrément préalable** | Test principiel *risk-to-capital* sans seuils | **28 %** des demandes EIS et **24 %** des demandes SEIS non approuvées en 2025-26 | [D] HMRC ; [C] pour les compléments |
| **Décalage instrument/relief** | SAFE non éligible SEIS/EIS avant conversion ; IR-PME exige souscription au capital | Pousse vers l'equity à prix ferme prématurée | [D] pour la règle ; [I] pour l'effet |
| **Effet de seuil JEIR (FR)** | 18 % dans le plafond de 10 000 € vs 50 % hors plafond | Coût net de 1 € investi : **0,82 €** vs **0,50 €** ; **1,00 €** vs **0,50 €** si plafond saturé | [D] pour les taux ; [C] pour le calcul |
| **Plafond de niches mordant (FR)** | Le plafond de 10 000 € mord à **55 556 €** de versement à 18 % | Rend le plafond de versement couple de 100 000 € **largement fictif** | [C] |
| **Non-portabilité transfrontalière** | Résidence de l'investisseur ET/OU établissement de la cible | Matrice très irrégulière ; certains couples à **subvention nulle** (DE→FR ; FR→UK) | [D] pour les règles ; [C] pour la matrice |
| **Coût d'information à distance** | Asymétrie, due diligence, suivi | **55 %** des angels ayant investi hors frontières jugent l'exercice difficile ou très difficile (n=90, 11 pays, 2020) | [D] |
| **Proximité irréductible** | Jugement sur intangibles humains, confiance | Distance médiane **124 km** ; **12 %** d'international réalisé contre 20-50 % autorisé | [D] |
| **Sélection adverse dans un dispositif sans filtre deal** | Subvention proportionnelle sans condition sur le deal | US : **35 %** de bénéficiaires avec investisseur initié (vs 8 %) ; investissement vers sociétés **plus âgées, moins créatrices d'emploi** | [D] pour les US ; [I] pour la transposition |
| **Insensibilité des meilleurs investisseurs** | Bénéfice marginal d'une subvention proportionnelle décroissant quand la queue droite s'épaissit | **71 %** des angels les plus expérimentés jugent les crédits « pas du tout importants » (n=1 411, US) | [D] pour l'enquête ; [I] pour la portée européenne |

---

## 8. Lacunes de données identifiées

Points sur lesquels **aucune donnée fiable n'a pu être établie** et que toute analyse ultérieure devrait traiter comme inconnus, non comme approximations :

1. **La taille réelle du marché angel européen.** EBAN a explicitement abandonné le multiplicateur ×10 issu de l'étude CSES de 2012 sans lui substituer d'estimation [D]. Le chiffre de 1,22 Md€ ne couvre que le marché « visible » et le sous-estime d'un facteur inconnu.
2. **La part transfrontalière du marché angel européen dans son ensemble.** Le seul chiffre robuste (12 % / 88 % / 81 %) porte sur le portefeuille EAF, c'est-à-dire une population **sélectionnée d'angels expérimentés soumis à une contrainte contractuelle de localisation** — donc probablement non représentative, et biaisée dans une direction indéterminée.
3. **Toute estimation quasi-expérimentale de l'additionnalité d'un dispositif fiscal angel européen.** Les estimations disponibles sont déclaratives (HMRC, Mason) ; la seule estimation quasi-expérimentale disponible (Denes et al.) est américaine.
4. **La prévalence relative des instruments** (equity à prix ferme / convertible / BSA-AIR / ASA) sur le marché européen d'amorçage. Les séries disponibles sont américaines.
5. **Toute évaluation isolant l'effet propre d'une caractéristique de conception de co-investissement** (lead minimal, pluralité de syndicat, plafond de participation, accréditation ex ante). Les mécanismes sont documentés ; leurs effets ne le sont pas.
6. **Le coût budgétaire de l'EIS/SEIS pour le Trésor britannique** : les statistiques HMRC consultées documentent les montants levés et le nombre de déclarants, pas la dépense fiscale correspondante.
7. **Les données de performance/sortie du portefeuille EAF** : le working paper EIF 2020/62 s'arrête aux données de 2019 et à la croissance post-investissement ; aucune donnée de rendement réalisé n'est publiée.
8. **Le texte primaire de la stratégie COM(2025) 270 final** n'a pas pu être extrait ; les mesures relatives aux business angels reposent sur des sources secondaires.

---

## Sources

**Statistiques de marché**
- [EBAN, *Statistics Compendium 2024 — European Early Stage Market Statistics*](https://www.eban.org/wp-content/uploads/2025/12/Stats-Compendium-2024.pdf) (publié 2025, données 2024, 39 pays)
- [Invest Europe, *Investing in Europe: Private Equity Activity 2024*](https://www.investeurope.eu/media/aywhjtsp/20250508_invest-europe_pe-activity-data-2024-report.pdf)

**Statistiques fiscales et réglementaires**
- [HMRC / GOV.UK, *Enterprise Investment Scheme and Seed Enterprise Investment Scheme: 2026*](https://www.gov.uk/government/statistics/enterprise-investment-scheme-and-seed-enterprise-investment-scheme-may-2026/enterprise-investment-scheme-and-seed-enterprise-investment-scheme-2026) (données 2024-25 et AAR 2025-26)
- [HMRC, *Venture Capital Schemes Manual* VCM8530](https://gov.uk/hmrc-internal-manuals/venture-capital-schemes-manual/vcm8530) et [VCM8540](https://www.gov.uk/hmrc-internal-manuals/venture-capital-schemes-manual/vcm8540) — *risk-to-capital condition*
- [GOV.UK, guidance EIS](https://www.gov.uk/guidance/venture-capital-schemes-apply-for-the-enterprise-investment-scheme)
- [Saffery, *EIS, SEIS, VCT and UK investment tax reliefs explained*](https://www.saffery.com/insights/articles/eis-seis-vct-and-uk-investment-tax-reliefs-explained/) (paramètres 2025-26)
- [service-public.fr / Entreprendre, *Réduction d'impôt (IR-PME) pour souscription au capital d'une société*](https://entreprendre.service-public.gouv.fr/vosdroits/F37091?lang=fr)
- [BAFA, *INVEST – Zuschuss für Wagniskapital*](https://www.bafa.de/DE/Wirtschaft/Beratung_Finanzierung/Invest/invest.html)
- [BAND, *INVEST – Zuschuss für Wagniskapital* (page anglaise)](https://www.business-angels.de/en/invest-english/) et [chiffres BAFA au 30/09/2025](https://www.business-angels.de/posts/invest-zuschuss-fuer-wagniskapital-die-september-zahlen-2025-aus-dem-bafa-244/)

**Évaluations**
- [GOV.UK / HMRC, *Seed Enterprise Investment Scheme evaluation 2022 — executive summary*](https://www.gov.uk/government/publications/evaluation-of-venture-capital-schemes/seed-enterprise-investment-scheme-evaluation-2022-executive-summary)
- [GOV.UK / HMRC, *Venture Capital Scheme (EIS, VCT) evaluation 2022 — executive summary*](https://www.gov.uk/government/publications/evaluation-of-venture-capital-schemes/venture-capital-scheme-eis-vct-evaluation-2022-executive-summary)

**Dispositifs de co-investissement**
- [Gvetadze, Pal & Torfs, *The Business Angel portfolio under the European Angels Fund: An empirical analysis*, EIF Working Paper 2020/62](https://www.econstor.eu/bitstream/10419/213873/1/1689254033.pdf)
- [ACF Investors / Angel CoFund](https://www.acfinvestors.com/) ; [British Business Bank, Angel CoFund](https://www.british-business-bank.co.uk/ourpartners/angel-cofund/) (HTTP 403 au moment de la consultation)
- [Bpifrance, OC French Tech Seed](https://www.bpifrance.fr/catalogue-offres/oc-french-tech-seed) (HTTP 403 au moment de la consultation ; données via sources secondaires)
- [OCDE, *Benchmarking government support for venture capital — country note: United Kingdom* (2025)](https://www.oecd.org/content/dam/oecd/en/publications/reports/2025/06/benchmarking-government-support-for-venture-capital-country-notes_2cacbf3f/united-kingdom_3c219488/5454ad97-en.pdf)

**Littérature académique et analytique**
- [Mason, C., Botelho, T. & Duggett, J. (2022), « Promoting cross-border investing by business angels in the European Union », *Regional Studies* 56(8), 1391-1403](https://eprints.gla.ac.uk/247233/1/247233.pdf) (accès libre CC BY-NC-ND)
- [Denes, M., Howell, S. T., Mezzanotti, F., Wang, X. & Xu, T. (2023), « Investor Tax Credits and Entrepreneurship: Evidence from U.S. States », *Journal of Finance* 78(5), 2621-2671](https://www.nber.org/papers/w27751) ; [version de travail complète](https://www.kellogg.northwestern.edu/faculty/mezzanotti/documents/tax_credit_DHMWX.pdf)
- [OCDE, *Understanding Government Venture Capital*, STI Working Paper 2025/06](https://www.oecd.org/content/dam/oecd/en/publications/reports/2025/04/understanding-government-venture-capital_e8417edc/2157a5b3-en.pdf)
- Braun, R., Jenkinson, T. & Schemmerl, C. (2020), « Adverse selection and the performance of private equity co-investments », *Journal of Financial Economics* 136(1), 44-62, [doi:10.1016/j.jfineco.2019.01.009](https://doi.org/10.1016/j.jfineco.2019.01.009)
- [Zhang, I. (2025), « The Hidden Trade-off in Public Venture Capital », Oxford Business Law Blog](https://blogs.law.ox.ac.uk/oblb/blog-post/2025/10/hidden-trade-public-venture-capital) — à paraître, *Journal of Empirical Legal Studies* (données chinoises ; **non transposable directement**)

**Structuration des deals**
- [Outlex, *SAFE Notes Don't Work in Europe: Use ASA, BSA-AIR or CLA*](https://outlex.ai/blog/safe-notes-europe-legal-differences) (source de cabinet ; estimations de coûts **non vérifiées**)

**Cadre européen**
- Commission européenne, *EU Startup and Scaleup Strategy*, COM(2025) 270 final, 28 mai 2025 — [document officiel](https://research-and-innovation.ec.europa.eu/document/download/2f76a0df-b09b-47c2-949c-800c30e4c530_en) (extraction textuelle infructueuse) ; [synthèse Morgan Lewis](https://www.morganlewis.com/pubs/2025/07/a-union-of-innovation-the-eu-strategy-for-startups-and-scale-ups)
