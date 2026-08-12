# Feuille de route de mise en œuvre — Grappe A : financement, registre réglementaire et prudentiel

**Agent :** `legal-drafter`
**Date :** 12 août 2026
**Périmètre :** 7 réformes retenues comme faisables après double stress-test — **F1** (régime EuVGF proportionné), **F5** (escalier de charge Solvabilité II), **F7** (label « Épargne Productive Européenne »), **F9** (plateformes de liquidité pré-IPO), **F12** (recyclage du bilan de garantie par titrisation), **N3** (utilité européenne de valorisation des actifs privés), **N5** (collège de stabilité financière de l'innovation).

---

## Avertissement de méthode — lire avant toute reprise du texte

**Ce document part de la version corrigée de chaque proposition, non de sa rédaction d'origine.** Les fiches `proposals.md` (F1-F14) et `round2-proposals.md` (N1-N6) sont conservées ici à titre de contexte historique uniquement. Sept corrections issues de la vérification indépendante (`impact-verification.md`, 9 août 2026) sont **structurantes** et ont été intégrées en amont de toute rédaction :

| Réforme | Correction intégrée, et ce qu'elle change |
|---|---|
| **F1** | Plafond du continuum ramené de 5 Md€ à **2 Md€** (le plafond de 5 Md€ n'est appuyé par aucune donnée) ; modification **concomitante et explicite de l'article 3 de l'AIFMD**, un règlement ne pouvant écarter les obligations d'une directive ; suppression de l'exemption de gestion du risque de liquidité, redondante avec l'article 16(1) de l'AIFMD ; ajout d'un collège de superviseurs. |
| **F5** | Le sous-module « actions d'innovation » à 17 % est **retiré de la voie de l'acte délégué** (excède l'habilitation de l'article 111 de la directive 2009/138/CE au regard de la calibration VaR 99,5 % de l'article 101(3)) ; les actions cotées sur marché réglementé EEE/OCDE sont **déjà à 39 %**, non 49 % ; les paliers intermédiaires ne sont **pas fixés a priori** mais renvoyés à une étude de calibration d'EIOPA. |
| **F7** | Le volet fiscal (recommandation aux États membres de réserver les avantages fiscaux aux produits labellisés) est **retiré** : inopérant sous l'article 288 TFUE, ultra vires s'il est rendu contraignant. L'avantage conditionné devient purement réglementaire. Ajout d'un audit indépendant périodique du respect du seuil. |
| **F9** | La « quatrième catégorie » d'infrastructure de marché est **abandonnée** : l'article 1(7) de la directive 2014/65/UE l'interdit frontalement. Reconstruction en **sous-régime proportionné de MTF** sur le modèle de l'article 33. Périmètre restreint aux formes à titres librement cessibles et dématérialisés. Fenêtre de liquidité obligatoire convertie en présomption favorable. Régime LCB-FT explicite. |
| **F12** | **Le tranchage est inversé** : céder la première perte ou la mezzanine, retenir une part verticale (ou une tranche senior), et non l'inverse — la perte attendue, qui commande le provisionnement, est concentrée dans la première perte. Abandon de la catégorie « position résiliente » distincte au profit de la voie **déjà ouverte** des titrisations synthétiques de bilan STS (articles 26 *bis* à 26 *sexies* du règlement 2017/2402). |
| **N3** | Pas d'organisme nouveau : logement dans le **comité mixte des autorités européennes de surveillance** existant. Présomption portant sur le **respect de la méthode**, jamais sur l'exactitude du résultat. Publication de **fourchettes et de dispersions**, jamais de valeurs ponctuelles, pour éviter une monoculture de valorisation. |
| **N5** | Pas d'organe nouveau : sous-structure dédiée du **CERS** (règlement (UE) n° 1092/2010). Le Groupe BEI et les banques nationales de promotion sont **entités déclarantes**, non membres. L'obligation légale de déclaration est **la seule véritable nouveauté juridique** du dispositif. |

**Convention de chiffrage.** Aucun chiffre nouveau n'est produit dans ce document. Tout chiffre cité est repris de la base factuelle avec sa source et son niveau de confiance tels qu'ils y sont déjà documentés. Là où aucun ordre de grandeur n'existe, c'est écrit en toutes lettres — l'absence de chiffre est une information, sa fabrication est une faute.

**Réserve de citation.** Plusieurs références de niveau 2 et de numérotation d'articles doivent être vérifiées sur EUR-Lex avant toute circulation externe ; elles sont listées en annexe. Cette réserve prolonge celle déjà formulée au §5 de `current-regulation.md` et le constat D.10 de la vérification (citation du règlement financier 2018/1046, **abrogé et remplacé par le règlement (UE, Euratom) 2024/2509**).

---

## 0. Synthèse opérationnelle

### 0.1 Tableau de commande

| # | Réforme | Instrument juridique | Procédure | Fenêtre législative concrète | Entrée en vigueur réaliste | Effet plein |
|---|---|---|---|---|---|---|
| **F1** | Régime EuVGF proportionné | Règlement nouveau + directive de modification corrélative de l'AIFMD | Législative ordinaire (art. 114 TFUE + art. 53(1) TFUE pour le volet directive), MQ | **Proposition EuVECA/EuSEF, T3 2026** | Publication fin 2028 - S1 2029 | 2030-2031 (après transposition du volet directive) |
| **F5** | Escalier Solvabilité II | Acte délégué modifiant le règlement délégué (UE) 2015/35 | Art. 290 TFUE, habilitation art. 111 dir. 2009/138/CE, non-objection PE/Conseil | Revue post-application du RD (UE) 2026/269, à ouvrir 2028 | 2029-2030 | 2030 |
| *F5 bis* | *Sous-module « innovation »* | *Directive de niveau 1 modifiant 2009/138/CE* | *Législative ordinaire, MQ* | *Prochaine revue Solvabilité II* | **2031-2033 au mieux** | *Hors cycle CFP 2028-2034* |
| **F7** | Label « Épargne Productive Européenne » | Règlement nouveau | Législative ordinaire (art. 114 TFUE), MQ | **Revue à mi-parcours de la SIU, T2 2027** | 2029-2030 | 2031 |
| **F9** | Sous-régime MTF de liquidité pré-IPO | Directive modifiant MiFID II + règlement d'exécution/normes techniques | Législative ordinaire (art. 53(1) TFUE), MQ | Paquet intégration des marchés / suites du Listing Act, 2027-2028 | 2030 | 2031-2032, et **conditionné à EU Inc.** |
| **F12** | Recyclage du bilan de garantie | Amendements au trilogue titrisation + article dans le règlement FEC | Législative ordinaire, MQ — **fenêtre la plus courte du lot** | **Trilogue titrisation, S2 2026** | 2027 (texte), 2028 (première opération) | 2028-2029 |
| **N3** | Utilité de valorisation des actifs privés | Règlement modifiant les règlements 1094/2010 et 1095/2010 (mandat du comité mixte) | Législative ordinaire, MQ | Paquet intégration des marchés et supervision, en trilogue 2026-2027 | 2028 | Première publication trimestrielle 2029 |
| **N5** | Collège de stabilité financière de l'innovation | Règlement modifiant le règlement (UE) n° 1092/2010 | Législative ordinaire, MQ (art. 114 TFUE) | Véhicule à ouvrir — **aucun texte porteur identifié** | 2028-2029 | 2029 |

MQ = majorité qualifiée au Conseil (art. 16(4) TUE et 238(3) TFUE : 55 % des États membres représentant 65 % de la population).

### 0.2 Chemin critique — quatre contraintes de calendrier qui commandent tout le reste

**(1) La fenêtre titrisation (F12) se referme au S2 2026 et ne se rouvrira pas avant plusieurs années.** La position du Parlement a été adoptée le 5 mai 2026, les trilogues sont attendus au second semestre 2026. F12 n'est pas un texte autonome : c'est un jeu d'amendements à un texte déjà en navigation. S'ils ne sont pas déposés pendant ce trilogue, la prochaine occasion est la revue suivante du règlement Titrisation et du CRR, soit un horizon 2030+. **C'est la seule réforme du lot dont l'échéance utile se compte en semaines, pas en trimestres.**

**(2) La proposition EuVECA/EuSEF du T3 2026 est le seul véhicule disponible pour F1, et il ne repassera pas.** Le programme de travail 2026 de la Commission annonce la proposition au T3 2026 après une consultation close le 12 mars 2026. Une révision de ces règlements intervient environ tous les quatre à cinq ans (2013, 2017, 2026). Si les paliers proportionnés et le passeport de gestion ne sont pas dans la proposition initiale de la Commission, il faudra les obtenir par amendement parlementaire — chemin praticable mais nettement plus fragile pour un dispositif qui exige une modification concomitante d'une directive tierce.

**(3) L'échéance électorale de 2029 est une contrainte dure sur tous les textes déposés à partir du T3 2026.** Un dossier de services financiers de cette taille consomme, en pratique de rédaction, 18 à 30 mois entre la proposition et la publication au JOUE (estimation de praticien, non un chiffre mesuré). Un texte déposé au T3 2026 doit donc conclure son trilogue au plus tard fin 2028 pour éviter le gel pré-électoral du printemps 2029 et le risque de reprise par une nouvelle législature et une nouvelle Commission. **F1, F7 et N5 sont dans cette fenêtre ; F9 ne l'est probablement pas et doit être conçu pour la législature suivante.**

**(4) Le 30 janvier 2027 est une date à ne pas perturber.** Le règlement délégué (UE) 2026/269, qui aligne Solvabilité II sur la directive (UE) 2025/2 et porte la charge LTEI à 22 %, est applicable à cette date. C'est, de l'aveu de la base factuelle, « le changement paramétrique le plus puissant de tout le corpus examiné » (macro §3.2(a)). Rouvrir le règlement délégué avant que cette réforme n'ait produit une seule année de données serait une faute de séquencement : cela fournirait à EIOPA et au CERS l'argument le plus simple pour tout suspendre. **F5 doit être présenté comme la suite de cette réforme, calibrée sur ses données, et non comme sa correction.**

### 0.3 Ordre d'engagement recommandé

```
S2 2026   F12  (amendements au trilogue titrisation)        ← fenêtre qui se referme
          N5   (préparation du véhicule, non le dépôt)
T3-T4 26  F1   (contribution à la proposition EuVECA)
2027      N3   (greffe sur le paquet intégration/supervision)
          N5   (dépôt — de préférence AVANT F5 et F9)
          F7   (revue à mi-parcours de la SIU, T2 2027)
2028      F5   (acte délégué, après 1 an de données post-30/01/2027)
          F9   (proposition, pour la législature 2029-2034)
2031+     F5bis (sous-module innovation, niveau 1 — hors cycle)
```

**Justification de l'ordre.** N5 est placé délibérément **avant** F5 et F9, alors qu'il ne produit aucun financement. Raison : la vérification indépendante et le débat convergent pour faire de la cohérence macroprudentielle une condition de recevabilité de l'ensemble du compartiment financement, et le rapport conjoint BCE-CERS du 12 février 2026 a déjà recommandé un mécanisme centralisé de partage de données resté sans suite. Déposer N5 en premier retire à EIOPA, à la BCE et au CERS l'objection la plus forte qu'ils opposeront à F5 (incitation structurelle à l'illiquide) et à F9 (opacité des marchés privés, valorisation de niveau 3). **C'est un texte sans effet économique dont la fonction est d'acheter la recevabilité des textes qui en ont.**

### 0.4 Carte des dépendances

| Dépendance | Nature | Conséquence de rédaction |
|---|---|---|
| F5 → F1 | La catégorie « parts d'EuVGF » doit exister pour être visée par renvoi croisé dans le règlement délégué Solvabilité II | Si F1 glisse, F5 doit viser les FIA fermés non levierisés au sens de l'AIFMD, catégorie déjà existante — **prévoir la double rédaction dès le départ** |
| F7 → F1 | Le seuil de 10 % renvoie aux actifs éligibles ELTIF **et** aux parts d'EuVGF | Rédiger le renvoi EuVGF comme une clause d'ajout automatique, activée à l'entrée en application de F1 |
| F9 → EU Inc. | Le sous-régime est réservé aux formes à titres librement cessibles et dématérialisés | F9 ne peut pas entrer en application avant les premières immatriculations EU Inc. — dépendance **externe au périmètre**, non maîtrisable |
| N3 → F9 | Les données de transaction des plateformes alimentent les méthodologies | **À découpler** : concevoir N3 en deux phases, la phase 1 sur les données existantes (reporting Annexe IV de l'AIFMD, données ESMA), la phase 2 sur les données F9. Sinon N3 hérite du calendrier de F9 et perd quatre ans |
| N5 → F1, F5, F9, F12 | Le collège surveille l'exposition agrégée produite par les autres réformes | Aucune dépendance juridique ; dépendance **d'opportunité politique**, dans le sens N5 d'abord |
| F12 → règlement FEC | La libération de provision doit être expressément prévue | Sans article dans le règlement FEC, l'effet de recyclage est juridiquement inexistant même si le montage financier est correct |

---

# F1 — Régime EuVGF proportionné

## 1. Nom et résumé du mécanisme final

**Règlement relatif aux fonds européens de capital-risque et de croissance (EuVGF)**, abrogeant et remplaçant les règlements (UE) n° 345/2013 (EuVECA) et n° 346/2013 (EuSEF).

Le seuil couperet de 500 M€ d'actifs sous gestion, qualifié d'« effet de falaise » par la Commission elle-même, est remplacé par **trois paliers cumulatifs d'obligations jusqu'à 2 Md€**, au-delà desquels s'applique l'AIFMD de droit commun. Chaque franchissement de palier ouvre une **période de grâce de 36 mois** avec application progressive, de sorte que la falaise devient une pente. Le régime ouvre en outre un **passeport de gestion transfrontalière** — aujourd'hui réservé aux gestionnaires pleinement agréés — par extension du mécanisme de l'article 33 de l'AIFMD aux gestionnaires enregistrés EuVGF, et élargit les actifs éligibles à la dette de croissance, aux instruments convertibles et aux secondaires de portefeuilles de fonds européens, sous limite quantitative. Le dispositif repose sur une **modification concomitante de l'article 3 de l'AIFMD** et non sur un règlement parallèle, et s'accompagne d'un **collège de superviseurs** pour organiser la coordination entre autorité d'origine et autorités d'accueil.

## 2. Base juridique et procédure

**Volet règlement.** Article 114 TFUE (rapprochement des législations pour l'établissement et le fonctionnement du marché intérieur) — base des règlements 345/2013 et 346/2013 qu'il remplace, et de l'ensemble des régimes de fonds européens (ELTIF, PEPP). Procédure législative ordinaire (article 294 TFUE), majorité qualifiée au Conseil.

**Volet directive corrélative.** Article 53(1) TFUE (coordination des dispositions relatives à l'accès aux activités non salariées et à leur exercice), base juridique de l'AIFMD elle-même, le cas échéant combiné à l'article 114 TFUE. Procédure législative ordinaire. **Le point est déterminant et doit être écrit dans l'exposé des motifs :** un règlement ne peut pas écarter des obligations posées par une directive ; les paliers 500 M€-2 Md€ déplacent l'AIFMD pour une part significative du marché et exigent donc une modification de son article 3, adoptée **dans le même paquet et entrant en application à la même date**.

**Rôle des institutions.** Commission : droit d'initiative exclusif, la proposition est annoncée pour le T3 2026. Parlement : commission ECON compétente au fond ; **aucun rapporteur n'est désigné à ce jour, le texte n'étant pas déposé**. Conseil : formation ECOFIN, groupe « Services financiers ». Il faut noter un point de rapport de force souvent mal compris : l'Irlande et le Luxembourg, dont la résistance est documentée, **ne disposent d'aucun droit de veto** sur ce dossier et représentent ensemble une fraction de population très inférieure au seuil de minorité de blocage (au moins quatre États représentant plus de 35 % de la population). Leur stratégie documentée est de chercher des alliés, non de bloquer seuls.

**Niveau 2.** Prévoir une habilitation à l'ESMA pour des projets de normes techniques de réglementation (article 10 du règlement (UE) n° 1095/2010) sur : le contenu du dossier d'enregistrement par palier, le format du reporting simplifié, et les modalités de fonctionnement du collège.

## 3. Ce qu'il faut rédiger concrètement

### 3.1 Considérants clés

- **Considérant sur l'échec d'adoption, non sur le paramètre.** Poser que le problème traité n'est pas le niveau du seuil mais le taux d'adoption : 29 % seulement des 704 fonds de capital-risque de l'Union utilisent EuVECA, usage minoritaire en France et en Espagne, 2 % pour EuSEF (macro §2.4). Ce considérant est la charnière du test de proportionnalité : il justifie une refonte plutôt qu'un ajustement de seuil.
- **Considérant sur la progressivité.** Énoncer que l'application binaire d'un corps d'obligations au franchissement d'un seuil unique produit trois comportements documentés — plafonnement volontaire du fonds, segmentation en véhicules jumeaux, saut réglementaire complet — et que la gradation des obligations est le moyen le moins contraignant d'atteindre l'objectif.
- **Considérant de hiérarchie des normes.** Énoncer expressément que le régime proportionné est établi **par modification de la directive 2011/61/UE** et non par dérogation à celle-ci, et que les deux actes entrent en application à la même date. Ce considérant est la réponse écrite à l'objection principale de la vérification.
- **Considérant sur l'absence d'exemption de liquidité.** Énoncer que les exigences de gestion du risque de liquidité de l'article 16(1) de la directive 2011/61/UE **ne s'appliquent déjà pas** aux FIA de type fermé non levierisés, de sorte qu'aucune exemption n'est nécessaire ni accordée. Écrire ce considérant plutôt qu'un article d'exemption : c'est la différence entre un texte propre et un texte déclaratoire qui affaiblit l'acquis.
- **Considérant sur la coordination prudentielle.** Fonder le collège sur la circonstance qu'un passeport de gestion dissocie l'État d'agrément de l'État d'activité et appelle une coordination structurée, sur le modèle éprouvé des collèges existants en assurance et en banque.

### 3.2 Articles à rédiger — règlement EuVGF

| Article | Contenu |
|---|---|
| **Art. 1-2** | Objet, champ, définitions. Définir « gestionnaire EuVGF enregistré », « palier », « actif sous gestion » par renvoi à l'article 3(2) et à la méthode de calcul du règlement délégué (UE) n° 231/2013 — **ne pas créer une méthode de calcul concurrente**, c'est la source d'arbitrage la plus prévisible. |
| **Art. 3** | **Table des paliers.** Palier 1 (< 500 M€) : enregistrement, règles de conduite, reporting annuel simplifié. Palier 2 (500 M€ - 1,2 Md€) : + dépositaire allégé au sens de l'article 21(3) de la directive 2011/61/UE (dépositaire non bancaire admis pour les actifs non conservables), + fonds propres réglementaires calculés sur les seules commissions de gestion. Palier 3 (1,2 - 2 Md€) : + reporting Annexe IV complet, + fonction permanente de gestion des risques. Au-delà de 2 Md€ : AIFMD de droit commun. *Le point de coupure interne entre paliers 2 et 3 est un paramètre de négociation ; le plafond de 2 Md€ ne l'est pas — il est la limite qu'appuie la base factuelle.* |
| **Art. 4** | **Période de grâce.** 36 mois à compter du franchissement, avec application palier par palier. Prévoir la clause anti-contournement : franchissement apprécié sur une moyenne mobile pour éviter la gestion de bilan de fin d'exercice, et non-cumul des périodes de grâce successives. |
| **Art. 5** | **Actifs éligibles.** Fonds propres et quasi-fonds propres d'entreprises de portefeuille éligibles ; dette de croissance avec bons de souscription attachés ; instruments convertibles ; parts d'autres EuVGF (structures nourricières) ; secondaires de portefeuilles de fonds de capital-risque européens. **Limite quantitative exigée par la vérification : plafonner en pourcentage des actifs du fonds l'ensemble « parts d'autres fonds + secondaires »** — un plafond de l'ordre de 20 % est le paramètre à discuter, sa fonction étant d'empêcher qu'un régime conçu pour le financement primaire ne devienne un régime de fonds de fonds. |
| **Art. 6-7** | **Passeports.** Commercialisation (reprise de l'acquis 345/2013) et **gestion**. Rédiger l'article de gestion par renvoi au mécanisme de notification de l'**article 33 de la directive 2011/61/UE** — notification à l'autorité d'origine, transmission à l'autorité d'accueil, absence d'exigence d'établissement local ou d'agrément additionnel. Point de rédaction essentiel : présenter le passeport de gestion comme **l'extension d'un mécanisme existant à une catégorie qui en est aujourd'hui exclue**, non comme une création. C'est la formulation qui neutralise le mieux l'objection de subsidiarité. |
| **Art. 8** | **Collège de superviseurs.** Déclencheur : gestionnaire de palier 2 ou 3 exerçant dans au moins deux États membres d'accueil. Composition : autorité d'origine (présidence), autorités d'accueil, ESMA. Fonctions : programme annuel commun d'examen prudentiel, échange d'informations, coordination des inspections. Articulation contentieuse : **médiation contraignante de l'ESMA au titre de l'article 19 du règlement (UE) n° 1095/2010** en cas de désaccord, et article 17 en cas de violation du droit de l'Union. Modèle rédactionnel : article 248 de la directive 2009/138/CE et article 116 de la directive 2013/36/UE. |
| **Art. 9-11** | Enregistrement, retrait, registre public tenu par l'ESMA, sanctions. |
| **Art. 12** | **Renvois croisés.** Ajout des parts d'EuVGF à la liste des actifs éligibles de l'article 10 du règlement (UE) 2015/760 (ELTIF) ; renvoi au règlement délégué (UE) 2015/35 pour l'appréciation au niveau du fonds (voir F5). |
| **Art. 13-15** | Abrogation des règlements 345/2013 et 346/2013 ; **régime transitoire** : les fonds enregistrés EuVECA/EuSEF sont réputés enregistrés EuVGF, avec conservation de la dénomination pendant une période de transition ; entrée en application alignée sur la date de transposition de la directive corrélative. |

### 3.3 Directive corrélative — une seule disposition de fond

Un article unique modifiant l'**article 3 de la directive 2011/61/UE** : insérer un paragraphe disposant que les gestionnaires enregistrés au titre du règlement EuVGF sont soumis, en lieu et place du paragraphe 2, aux obligations graduées fixées par ce règlement, et que les articles 32 et 33 leur sont applicables dans les conditions qu'il prévoit. Délai de transposition à aligner sur la date d'application du règlement.

**Conseil de rédaction :** garder la surface de modification de l'AIFMD au strict minimum. Chaque article de la directive rouvert est une invitation à rouvrir l'ensemble du dossier AIFMD en trilogue, deux ans après l'entrée en application d'AIFMD II (directive (UE) 2024/927, applicable depuis avril 2026). Un seul article modifié, une seule finalité, un seul délai de transposition.

## 4. Séquencement et dépendances

**F1 est la clef de voûte de la grappe.** Trois des six autres réformes s'y adossent par renvoi croisé : F5 (parts d'EuVGF comme sous-jacent du traitement prudentiel), F7 (parts d'EuVGF comme actif comptant dans le seuil de 10 %), N3 (méthodologies de valorisation par millésime des parts d'EuVGF). Aucune ne dépend de F1 pour exister, mais toutes trois perdent en précision si la catégorie n'existe pas.

**Parade obligatoire :** rédiger chaque renvoi croisé en **double branche** — « parts d'EuVGF au sens du règlement [F1] ou, à défaut, parts de FIA de type fermé sans levier au sens de la directive 2011/61/UE satisfaisant [critères] ». Cette technique coûte une ligne et protège trois textes contre un glissement de calendrier de F1.

**Dépendance interne critique :** le règlement et la directive corrélative doivent être **adoptés dans le même paquet**. S'ils sont dissociés en cours de négociation — hypothèse plausible, le Conseil préférant souvent traiter le règlement seul — l'ensemble du dispositif devient juridiquement inopérant tout en paraissant adopté. **C'est le point de vigilance n°1 pour le suivi du trilogue.**

## 5. Calendrier réaliste

| Étape | Échéance |
|---|---|
| Contribution aux travaux préparatoires de la Commission | **immédiat — la proposition est annoncée pour le T3 2026** |
| Proposition de la Commission | T3-T4 2026 |
| Rapport ECON, position du Conseil | 2027 - S1 2028 |
| Trilogue et accord politique | S2 2028 (impératif : **avant le gel pré-électoral du printemps 2029**) |
| Publication au JOUE | fin 2028 - S1 2029 |
| Application du règlement / transposition de la directive | + 18 à 24 mois → **2030-2031** |

**Fenêtre concrète :** la révision EuVECA/EuSEF annoncée au T3 2026, consultation close le 12 mars 2026. Il n'existe pas de véhicule de substitution avant la révision suivante, historiquement espacée de quatre à cinq ans.

## 6. Acteurs institutionnels

- **DG FISMA** — unité en charge de la gestion d'actifs : rédaction de la proposition, arbitrage sur le plafond du continuum et sur le passeport de gestion.
- **Commissaire chargée des services financiers et de l'union de l'épargne et de l'investissement** : arbitrage politique sur le passeport de gestion, seul élément véritablement contesté.
- **ESMA** : normes techniques, tenue du registre, présence au collège, médiation contraignante.
- **Parlement, commission ECON** : rapporteur à désigner après dépôt.
- **Conseil, groupe Services financiers puis ECOFIN.**

**Obstacle politique principal, déjà documenté.** Le passeport de gestion touche directement le modèle de domiciliation de fonds de l'Irlande et du Luxembourg, dont la résistance à toute centralisation est documentée (`stakeholder-map` §3.3, friction n°4), face à six grands États membres — Allemagne, France, Italie, Espagne, Pays-Bas, Pologne — qui poussent en sens inverse sur le transfert de pouvoirs vers l'ESMA. Le rapport de force numérique est nettement défavorable aux opposants, qui n'ont pas de minorité de blocage et doivent chercher des alliés.

**Recommandation de conduite :** séquencer la négociation en deux blocs — paliers proportionnés (non contestés, soutenus par Invest Europe, ESN/Allied for Startups, France Digitale) d'abord, passeport de gestion ensuite. Le collège de superviseurs est **l'instrument de concession** : il donne aux autorités d'accueil une présence institutionnelle formelle en contrepartie de la disparition de l'exigence d'établissement local. Sa fonction politique est d'empêcher la constitution d'une coalition élargie sur le terrain de la subsidiarité, non de résoudre un problème prudentiel réel.

## 7. Impact attendu, chiffré honnêtement

**Ce qui est mesuré et solide :**
- Taux d'adoption d'EuVECA : **29 % des 704 fonds de capital-risque de l'Union**, usage minoritaire en France et en Espagne, **2 % pour EuSEF** (macro §2.4). C'est le constat qui fonde la réforme.
- Collecte de capital-risque européenne 2025 : **22,3 Md€ pour 186 fonds** (confiance **élevée**, mesure directe). C'est l'univers sur lequel la réforme opère.
- Coût budgétaire pour l'Union : **nul** (macro §9, rang 5).

**Ce qui est modélisé et doit être présenté comme tel :** micro §2.2 estime qu'un fonds de 800 M€ à 1,2 Md€ devient administrativement viable, portant le ticket initial d'environ 4 M€ à 15-20 M€ et permettant de mener un tour de série B sans syndication à six signataires. **C'est une illustration de mécanisme, pas une estimation d'impact.** Elle ne doit pas être présentée comme un effet quantifié dans une analyse d'impact.

**Ce qui n'est pas disponible, et doit être dit :** il n'existe **aucune estimation du nombre de gestionnaires qui franchiraient effectivement la bande 500 M€-2 Md€** à la faveur de la réforme, ni du capital additionnel qui en résulterait. La base factuelle ne fournit pas cette donnée et elle ne peut pas être dérivée des chiffres disponibles. Toute analyse d'impact devra la produire par enquête auprès des gestionnaires — c'est un travail à commander maintenant si l'on veut disposer du chiffre au moment du trilogue.

**Confiance globale sur l'effet :** *moyenne* (macro §9, rang 5 : « condition de faisabilité des fonds de 300 M€-1 Md€ que ETCI 2 vise à financer ; corrige un taux d'adoption de 29 % »). La formulation honnête est que F1 est une **condition de faisabilité** d'autres instruments, pas un instrument à effet direct chiffrable.

## 8. Risques résiduels

La dissociation du règlement et de la directive corrélative en cours de négociation produirait un dispositif juridiquement inopérant mais politiquement présenté comme adopté — c'est le risque le plus sérieux et il est procédural, non substantiel. Le plafond de 2 Md€ reste une borne de proportionnalité défendue par la donnée mais non démontrée par elle : il sera attaqué des deux côtés, à la hausse par l'industrie, à la baisse par les superviseurs, et la ligne de défense doit être préparée. Enfin, l'élargissement aux secondaires et aux structures nourricières, même plafonné, ouvre un vecteur de transformation du régime en véhicule de fonds de fonds que la limite quantitative contient sans l'éliminer.

---

# F5 — Escalier de charge Solvabilité II

## 1. Nom et résumé du mécanisme final

**Escalier de charge du sous-module « actions de type 2 » selon la durée de détention effective.**

Le couple binaire actuel — 49 % + ajustement symétrique pour les actions de type 2, 22 % pour les investissements en actions de long terme (LTEI) — est remplacé par un barème progressif à quatre marches selon l'horizon de détention documenté : **moins de 2 ans, 49 % inchangé ; 2 à 3 ans, palier intermédiaire ; 3 à 5 ans, second palier intermédiaire ; 5 ans et plus sous critères LTEI, 22 % inchangé.** Les deux marches intermédiaires **ne sont pas fixées dans la proposition** : elles sont renvoyées à une étude de calibration d'EIOPA, conduite sur les données de la première année d'application du régime LTEI. Le dispositif s'accompagne d'une orientation de niveau 3 d'EIOPA avec cas chiffrés de démonstration de la capacité de détention, destinée à supprimer la divergence d'interprétation entre superviseurs nationaux — identifiée par la base factuelle comme le premier frein pratique, **devant le niveau du taux lui-même**.

**Ce qui est retiré du dispositif et pourquoi.** Le sous-module « actions d'innovation européennes » à 17 % ne peut pas emprunter la voie de l'acte délégué : l'article 111 de la directive 2009/138/CE n'autorise à préciser la formule standard que dans le respect de la calibration de l'article 101(3) — valeur en risque à 99,5 % à horizon un an — qu'un taux de 17 % sur des actions non cotées de sociétés de moins de quinze ans ne peut vraisemblablement pas satisfaire. Il exigerait un **acte de niveau 1** et sort du cycle de cette feuille de route (voir §5).

**Correction factuelle à intégrer dans tout document de travail.** Sous l'article 168 du règlement délégué (UE) 2015/35, les actions cotées sur un marché réglementé de l'EEE ou de l'OCDE sont de **type 1 et chargées à 39 % + ajustement symétrique**, et non à 49 %. L'asymétrie coté / non coté existe (39 % contre 22 %) mais elle est **deux fois moindre** que ce que la rédaction d'origine affirmait. L'escalier ne concerne donc que le type 2.

## 2. Base juridique et procédure

**Voie retenue — acte délégué.** Article 290 TFUE, sur l'habilitation de l'**article 111 de la directive 2009/138/CE**, dans les limites de l'article 101(3). Acte modifiant le **règlement délégué (UE) 2015/35**, articles 168 (classification type 1 / type 2), 169 (niveaux de choc), 171 *bis* (investissements en actions de long terme) et 172 (ajustement symétrique).

**Déroulé procédural :**
1. **Demande d'avis technique de la Commission à EIOPA** (*call for advice*) portant sur la calibration des deux marches intermédiaires, incluant expressément une analyse de compatibilité avec l'article 101(3).
2. Consultation publique d'EIOPA, avis technique.
3. Adoption de l'acte délégué par la Commission.
4. **Non-objection du Parlement et du Conseil**, période d'objection de trois mois prorogeable de trois mois (article 301 *bis* de la directive 2009/138/CE — *référence à vérifier*).

**Ce que cela implique politiquement :** le Parlement et le Conseil n'amendent pas, ils acceptent ou rejettent en bloc. C'est un avantage de vitesse et un risque de tout-ou-rien. La qualité de l'avis EIOPA est donc le facteur déterminant : **un acte délégué dont la calibration n'est pas adossée à un avis EIOPA sera rejeté, et une analyse d'impact comportant des taux prudentiels inventés est irrecevable.**

**Voie du sous-module « innovation » (F5 bis).** Directive modifiant la directive 2009/138/CE, procédure législative ordinaire, majorité qualifiée. À traiter comme un dossier distinct, de la législature suivante.

## 3. Ce qu'il faut rédiger concrètement

### 3.1 Demande d'avis technique à EIOPA — le vrai document à rédiger d'abord

Le premier livrable n'est pas un texte normatif mais un **mandat de calibration**. Sa structure :

- **Objet.** Déterminer, pour des expositions en actions de type 2 détenues sur des horizons documentés de 2 à 3 ans et de 3 à 5 ans, les niveaux de choc satisfaisant la calibration de l'article 101(3) de la directive 2009/138/CE.
- **Données.** Séries de rendement d'actions non cotées européennes sur cycle complet ; comportement effectif de détention observé sur la première année d'application du régime LTEI (à compter du 30 janvier 2027) ; données de dispersion des valorisations (articulation avec N3, qui produit précisément cette matière).
- **Questions expressément posées :** (i) la relation entre horizon de détention et perte à 99,5 % est-elle suffisamment documentée pour supporter une gradation ? (ii) quelle preuve de capacité de détention exiger, et à quel coût de conformité pour une entreprise d'assurance de taille moyenne ? (iii) l'ajustement symétrique doit-il s'appliquer, être réduit, ou être écarté à chaque marche ?
- **Exigence méthodologique explicite :** EIOPA est invitée à indiquer si la donnée disponible **ne permet pas** de calibrer une marche donnée. Cette formulation est essentielle : elle rend acceptable un avis qui conclut à l'impossibilité, et évite de forcer une calibration de complaisance.

### 3.2 Considérants de l'acte délégué

- **Considérant de continuité.** Poser que l'acte prolonge la réforme applicable au 30 janvier 2027 et s'appuie sur ses données d'application, sans en modifier les paramètres — ni le 22 % LTEI, ni les conditions de non-vente forcée, ni l'appréciation au niveau du fonds.
- **Considérant sur la prime au montage.** Énoncer que le couple binaire actuel récompense la documentation d'une intention de détention plutôt que la détention elle-même, et que la gradation aligne l'exigence prudentielle sur le comportement réel. C'est la justification de proportionnalité du dispositif.
- **Considérant de calibration.** Renvoyer expressément à l'avis technique d'EIOPA et à la conformité à l'article 101(3). Sans ce considérant, l'acte est attaquable pour excès de l'habilitation.
- **Considérant macroprudentiel.** Reprendre l'objection avant qu'elle ne soit formulée : le régime LTEI échange un amortisseur contracyclique (l'ajustement symétrique) contre une incitation structurelle à l'illiquide ; la gradation ne renforce pas cet arbitrage puisqu'elle maintient l'ajustement symétrique aux marches intermédiaires et n'abaisse aucun taux en dessous du plancher LTEI existant. **C'est l'argument à écrire dans le texte, pas à garder pour la réunion.**

### 3.3 Articles à modifier

| Disposition | Modification |
|---|---|
| **Art. 169 du RD 2015/35** | Insérer, au sein du sous-module actions de type 2, la gradation par horizon de détention documenté. Les taux des deux marches intermédiaires sont les seuls chiffres à insérer **après** réception de l'avis EIOPA. |
| **Art. 171 bis du RD 2015/35** | Inchangé quant au taux de 22 % et aux conditions. Ajouter seulement l'articulation avec les marches inférieures : conditions de preuve, et traitement en cas de cession avant l'horizon annoncé. |
| **Art. 172 du RD 2015/35** | Préciser l'application de l'ajustement symétrique à chaque marche (les bornes actuelles sont élargies à ±13 %). Paramètre à trancher sur avis EIOPA. |
| **Art. 168** | Aucune modification. **Point de rédaction :** ne pas toucher à la classification type 1 / type 2, sous peine de rouvrir tout le sous-module actions. |
| **Nouvel article de preuve** | Définir l'« horizon documenté de détention » : décision formelle de l'organe d'administration, adossement à un passif de duration correspondante, conséquence en cas de cession anticipée (reclassement rétroactif à la marche supérieure sur l'exercice en cours). Sans mécanisme de conséquence, la gradation est déclarative. |

### 3.4 Orientation EIOPA de niveau 3

Orientation au titre de l'article 16 du règlement (UE) n° 1094/2010, assortie du mécanisme « se conformer ou s'expliquer » applicable aux autorités nationales, comportant **des cas chiffrés de démonstration de capacité de détention**. C'est le livrable qui traite le frein identifié comme premier par la base factuelle — la divergence d'interprétation entre superviseurs nationaux — et il produit son effet indépendamment de l'issue de l'acte délégué. **À commander en parallèle, pas après.**

## 4. Séquencement et dépendances

**Dépendance amont impérative — le 30 janvier 2027.** L'acte délégué (UE) 2026/269 est applicable à cette date. F5 doit être calibré sur au moins **une année complète de données d'application**, ce qui interdit toute ouverture avant début 2028. Cette contrainte n'est pas subie : elle est l'argument principal de recevabilité du dossier devant EIOPA.

**Dépendance sur F1 :** utile, non nécessaire. La rédaction doit viser les FIA de type fermé sans levier au sens de l'AIFMD — catégorie déjà existante et déjà visée par la réforme de 2026 — et ajouter les parts d'EuVGF par renvoi conditionnel.

**Dépendance sur N3 :** réelle et sous-estimée. La calibration d'un escalier par horizon de détention suppose des séries de valorisation d'actifs privés dont la dispersion est mesurée. N3 produit exactement cette matière. **N3 avant F5** améliore matériellement la qualité de l'avis EIOPA.

**Dépendance sur N5 :** politique. Le CERS et la BCE opposeront l'incitation structurelle à l'illiquide. L'existence préalable d'un dispositif de suivi macroprudentiel dédié (N5) transforme cette objection en condition déjà satisfaite.

## 5. Calendrier réaliste

| Étape | Échéance |
|---|---|
| Rédaction et envoi de la demande d'avis technique à EIOPA | S2 2027 |
| Application du RD (UE) 2026/269 — début de la collecte de données | **30 janvier 2027** |
| Consultation et avis technique EIOPA | 2028 |
| Adoption de l'acte délégué par la Commission | S1 2029 |
| Période de non-objection PE/Conseil | 3 à 6 mois |
| **Entrée en application** | **2029-2030** |
| *Orientation EIOPA de niveau 3 (voie parallèle, plus rapide)* | *2027-2028* |

**Sous-module « innovation » à 17 % (F5 bis) :** exige un acte de niveau 1. En tenant compte du délai de procédure législative ordinaire et de transposition, **l'horizon réaliste est 2031-2033**, soit **hors du cycle CFP 2028-2034 pour l'essentiel de ses effets**. Il doit être inscrit à la feuille de route comme objectif de moyen terme et retiré de tout document présentant des effets attendus sur la période 2028-2034. Le présenter autrement serait la faute d'honnêteté la plus visible du dossier.

## 6. Acteurs institutionnels

- **DG FISMA** — unité assurance et pensions : rédaction de la demande d'avis et de l'acte délégué.
- **EIOPA** : acteur déterminant. Sans avis technique favorable, le dossier n'existe pas.
- **Parlement (ECON) et Conseil (ECOFIN)** : non-objection, sans pouvoir d'amendement.
- **CERS et BCE** : pas de rôle formel dans la procédure, rôle réel considérable par voie d'avis public.

**Obstacle politique principal.** Il est prudentiel et institutionnel, non politique au sens partisan. La cartographie ne documente **aucune opposition nommément identifiée** au sous-module lui-même, et un soutien explicite d'Insurance Europe, qui conditionne son appui à la SIU à un traitement prudentiel plus favorable des actifs longs. L'obstacle est ailleurs : EIOPA et le CERS opposeront que le régime LTEI a déjà échangé un amortisseur contracyclique contre une incitation à l'illiquide, et qu'une gradation supplémentaire accentue cet arbitrage. **La réponse est le plafonnement de l'exposition, le suivi EIOPA dédié, et l'existence préalable de N5 — à assumer explicitement dans le texte plutôt qu'en réunion.**

## 7. Impact attendu, chiffré honnêtement

**Le chiffre de cadrage, avec sa source et sa confiance :** sur une base d'actifs des assureurs européens de l'ordre de **9 000 à 10 000 Md€**, une réallocation de **0,5 point de pourcentage** vers l'*equity* de long terme représente **45-50 Md€ de stock** — soit plus de quatre fois la composante InvestEU du Fonds européen pour la compétitivité sur sept ans (~11 Md€). Source : macro §3.2(a), calcul propre. **Confiance : moyenne.** Motif documenté de cette confiance : « l'ordre de grandeur est robuste ; le taux de réallocation effectif est une hypothèse comportementale non testée ». Décomposition linéaire : chaque **0,1 point** de réallocation représente **9-10 Md€ de stock**.

**Trois précautions d'attribution, sans lesquelles ce chiffre est trompeur :**

1. **Ce chiffre décrit le canal, pas la réforme.** Le mouvement paramétrique le plus puissant — 49 % → 22 % sur les LTEI — **est déjà du droit en vigueur** et applicable au 30 janvier 2027. F5 n'en est pas l'auteur. Sa contribution marginale porte sur le segment intermédiaire, de 2 à 5 ans de détention, qui est une fraction non estimée du canal. **Attribuer 45-50 Md€ à F5 serait une faute.**
2. **La réforme de 2026 bénéficiera principalement aux grands assureurs vie dotés d'équipes de gestion actif-passif sophistiquées ; l'adoption sera faible chez les acteurs moyens** (micro §3.1). L'apport propre de F5, et surtout de l'orientation EIOPA de niveau 3, est d'élargir cette population — effet réel mais non chiffrable en l'état de la donnée.
3. **L'effet de réduction du péage prudentiel de « 5-6 points de rendement annuel à moins de 2 points » figurant dans la fiche d'origine reposait sur le sous-module à 17 %**, retiré du dispositif. Il ne doit pas être repris.

**Ce qui n'est pas disponible :** aucune estimation du taux de réallocation effectif, ni de la part du canal imputable à la gradation intermédiaire. La formulation honnête est : *le levier prudentiel est le plus puissant du corpus par ordre de grandeur, à coût budgétaire nul ; la part de ce levier attribuable à cette réforme précise n'est pas estimable avant l'étude de calibration d'EIOPA.*

## 8. Risques résiduels

Le risque dominant est que l'étude EIOPA conclue que la donnée disponible ne permet pas de calibrer les marches intermédiaires de manière compatible avec l'article 101(3) — hypothèse sérieuse, puisque la relation entre horizon de détention et perte à 99,5 % est précisément ce que le cadre prudentiel mesure mal. Le dossier doit être construit pour survivre à cette issue, l'orientation de niveau 3 restant acquise dans tous les cas. Subsiste par ailleurs l'objection macroprudentielle de fond, que le plafonnement et le suivi atténuent sans la lever : le cadre continue d'échanger un amortisseur contracyclique contre une incitation à l'illiquide. Enfin, le retrait du sous-module à 17 % de la voie déléguée prive le dispositif de l'essentiel de son effet annoncé ; il faut l'assumer explicitement plutôt que laisser un document de présentation continuer à porter les chiffres de la version d'origine.

---

# F7 — Label « Épargne Productive Européenne »

## 1. Nom et résumé du mécanisme final

**Règlement établissant le label « Épargne Productive Européenne » (EPE).**

Un produit d'épargne — compte d'épargne et d'investissement, PEPP, unité de compte d'assurance vie, plan d'épargne d'entreprise — obtient le label si **au moins 10 % de ses encours** sont investis en actifs productifs européens de long terme, définis par renvoi croisé à l'article 10 du règlement ELTIF et aux parts d'EuVGF. **Il ne s'agit en aucun cas d'une obligation d'allocation :** aucun produit n'est tenu de solliciter le label, et aucun gestionnaire n'est tenu d'allouer quoi que ce soit. Le label conditionne l'accès à deux avantages strictement réglementaires : le **droit d'employer une dénomination commerciale faisant référence à l'Europe**, et le bénéfice du **passeport de distribution simplifié** prévu par le paquet SIU. Le respect du seuil fait l'objet d'un **audit indépendant périodique**, avec période de remédiation avant retrait du label.

**Ce qui est retiré du dispositif et pourquoi.** Le volet fiscal — recommandation aux États membres de réserver aux produits labellisés les avantages fiscaux attachés aux comptes d'épargne — est supprimé. Motif : une recommandation au sens de l'article 288 TFUE ne contraint personne, et rendue contraignante elle deviendrait une mesure fiscale relevant de l'unanimité de l'article 115 TFUE. La fiche d'origine en faisait pourtant le cœur de son effet. **Le retrait est substantiel : il faut dire ce qu'il coûte, et non le présenter comme un simple nettoyage rédactionnel.**

## 2. Base juridique et procédure

**Article 114 TFUE**, procédure législative ordinaire, majorité qualifiée. La base est solide et documentée par quatre précédents de régimes de label ou de dénomination protégée adoptés sur ce fondement : **ELTIF** (règlement (UE) 2015/760), **EuVECA** (règlement (UE) n° 345/2013), **PEPP** (règlement (UE) 2019/1238) et **obligations vertes européennes** (règlement (UE) 2023/2631). Ce dernier est le précédent le plus proche par sa structure : dénomination protégée, seuil quantitatif d'affectation, vérification par un tiers indépendant enregistré auprès de l'ESMA.

**Point de droit à traiter dans l'exposé des motifs.** Le retrait du volet fiscal désamorce l'objection principale au titre de l'**article 63 TFUE** (libre circulation des capitaux) : la jurisprudence invoquée — *Verkooijen* (C-35/98), *Manninen* (C-319/02) — sanctionne des **avantages fiscaux nationaux** conditionnés à la localisation de l'investissement, et rejette de longue date l'objectif purement économique comme justification. Un régime de label purement réglementaire, sans avantage fiscal attaché, se situe sur le terrain d'EuVECA — qui exige lui-même que les entreprises de portefeuille éligibles soient établies dans l'Union sans que cela ait été censuré. **La réserve doit néanmoins être inscrite au dossier** (voir §8).

**Rôle des institutions.** Commission (DG FISMA) : initiative. Parlement : ECON. Conseil : ECOFIN. ESMA : registre public des produits labellisés et des vérificateurs ; EIOPA pour les produits relevant de son périmètre (PEPP, unités de compte).

## 3. Ce qu'il faut rédiger concrètement

### 3.1 Considérants clés

- **Considérant de nature du dispositif — le plus important du texte.** Énoncer sans ambiguïté que le règlement **n'impose aucune obligation d'allocation**, que la sollicitation du label est volontaire, et que l'absence de label n'emporte aucune conséquence défavorable autre que l'impossibilité d'employer une dénomination réservée. Ce considérant est la réponse écrite au front d'opposition documenté.
- **Considérant anticipant expressément la lecture en « pression fonctionnelle ».** C'est la demande explicite du mandat, et elle est fondée. Les fédérations de fonds de pension allemande et italienne ont déjà rejeté un seuil **non contraignant** de 2 % proposé en révision d'IORP II par l'eurodéputé Damian Boeselager, au motif que « la gestion d'actifs doit rester ancrée dans les principes de prudence et de diversification » (`stakeholder-map` §7.3, friction n°5 — la mieux documentée de toute la cartographie). Elles liront donc très probablement un label conditionnant un avantage de distribution comme une contrainte d'allocation par un autre chemin. Le considérant doit **énoncer et traiter** cette lecture : rappeler que le principe de la personne prudente de l'article 19 de la directive (UE) 2016/2341 demeure la norme de conduite exclusive, qu'aucune disposition du règlement n'y déroge, et qu'un gestionnaire dont l'analyse prudentielle conduit à ne pas atteindre le seuil est fondé à ne pas solliciter le label sans conséquence.
- **Considérant de protection de l'épargnant.** BEUC et Finance Watch objecteront l'orientation de l'épargne des ménages vers des actifs illiquides et opaques (friction n°10). Le considérant doit renvoyer aux outils de gestion de la liquidité applicables au produit sous-jacent et à l'information précontractuelle, et **assumer que le seuil de 10 % est un plafond de fait d'exposition à l'illiquide pour un produit labellisé**, non un objectif à dépasser.
- **Considérant sur la vérification.** Justifier l'audit indépendant par le fait qu'un label auto-déclaré n'a aucune valeur informationnelle et expose au risque d'écoblanchiment par analogie.

### 3.2 Articles

| Article | Contenu |
|---|---|
| **Art. 1-3** | Objet, champ (énumération limitative des produits éligibles), définitions. |
| **Art. 4** | **Critère du label.** Au moins 10 % des encours en actifs productifs européens de long terme, définis par renvoi à l'article 10 du règlement (UE) 2015/760 **et** aux parts d'EuVGF (double branche de rédaction — voir §4). Calcul en moyenne sur l'exercice, non à date d'arrêté, pour éviter l'habillage de fin de période. |
| **Art. 5** | **Effets du label.** (a) Droit exclusif d'employer, dans la dénomination et la communication commerciale, une référence à l'Europe ou à l'Union ; (b) bénéfice du passeport de distribution simplifié du paquet SIU. **Énumération limitative et fermée** : tout autre effet ouvrirait la porte à la requalification en obligation indirecte. |
| **Art. 6** | **Audit indépendant périodique.** Vérification annuelle du respect du seuil par le contrôleur légal des comptes du producteur du produit ou par un vérificateur tiers **enregistré auprès de l'ESMA** — structure directement reprise du règlement (UE) 2023/2631 sur les obligations vertes européennes. Contenu du rapport, seuil de significativité, publication d'une synthèse. |
| **Art. 7** | **Remédiation et retrait.** Franchissement à la baisse : notification, période de remédiation (six mois est le paramètre à discuter), retrait du label et interdiction de la dénomination à défaut. Prévoir expressément le cas du franchissement **par effet de marché** et non par décision de gestion — sans cette clause, le dispositif crée une obligation d'achat en marché baissier, soit exactement l'effet procyclique que le CERS reprochera. |
| **Art. 8** | Registre public tenu par l'ESMA (produits labellisés, vérificateurs, retraits). |
| **Art. 9** | Sanctions : usage indu de la dénomination, harmonisation minimale des sanctions administratives nationales. |
| **Art. 10** | **Clause de réexamen à cinq ans**, portant expressément sur : le taux de recours au label, l'effet mesuré sur l'allocation, et l'opportunité d'ajuster le seuil de 10 %. |

### 3.3 Ce qu'il ne faut surtout pas rédiger

- **Aucun article sur la fiscalité nationale**, pas même sous forme de recommandation ou de considérant incitatif. La tentation sera forte de réintroduire le volet par la voie d'un considérant « les États membres sont encouragés à… ». C'est inopérant juridiquement et cela rouvre à la fois l'objection d'article 115 et l'objection d'article 63. **Le retrait doit être complet.**
- **Aucune extension au volet IORP « se conformer ou s'expliquer »** dans ce texte. La modification de l'article 19 de la directive (UE) 2016/2341 est un dossier distinct, dont l'opposition documentée est frontale, et qui contaminerait la négociation du label. Si ce volet est jugé indispensable, il relève de la révision d'IORP II et de son rapporteur, non de ce règlement.

## 4. Séquencement et dépendances

**Dépendance sur F1 :** le seuil de 10 % renvoie aux parts d'EuVGF. Si F1 n'est pas adopté au moment où F7 est rédigé, le renvoi doit être formulé en double branche : actifs éligibles ELTIF au sens de l'article 10 du règlement (UE) 2015/760, **et** parts de fonds relevant du règlement EuVGF « lorsque celui-ci sera applicable ». Une clause d'ajout automatique évite de rouvrir F7 plus tard.

**Dépendance sur N3 :** indirecte mais substantielle sur le plan politique. N3 traite la **cause déclarée** de l'opposition des fédérations de fonds de pension — le coût unitaire de la diligence et l'absence de méthode de valorisation — là où F7 la contourne. Les deux textes forment un couple : **présenter F7 seul, c'est présenter la contrainte sans la réponse.** Recommandation : annoncer les deux dans le même paquet politique, même si les véhicules législatifs diffèrent.

**Aucune dépendance sur F5, F9, F12.**

## 5. Calendrier réaliste

| Étape | Échéance |
|---|---|
| Fenêtre législative | **Revue à mi-parcours de la SIU, T2 2027** |
| Proposition de la Commission | T2-T3 2027 |
| Négociation PE/Conseil | 2027-2028 |
| Accord politique | S2 2028 (avant gel pré-électoral 2029) |
| Publication | fin 2028 - 2029 |
| Application (différé pour la mise en place du registre ESMA et des vérificateurs) | + 12 à 18 mois → **2030** |
| Premiers produits labellisés | **2030-2031** |

## 6. Acteurs institutionnels

- **DG FISMA** — unité produits d'épargne de détail et distribution.
- **ESMA** : registre, enregistrement des vérificateurs, normes techniques. **EIOPA** pour les produits d'assurance et de retraite.
- **Parlement, commission ECON.** Point de vigilance : l'eurodéputé Damian Boeselager, rapporteur documenté sur la révision d'IORP II et auteur de la proposition de seuil contraignant de 2 %, est un allié naturel sur le fond **et** le porteur de la mesure que les fédérations de pension ont explicitement rejetée. Un rapprochement trop visible entre F7 et le seuil de 2 % ferait basculer F7 dans le champ de la friction n°5.
- **Conseil, ECOFIN.**

**Obstacle politique principal, documenté.** Double front. (i) Les fédérations de fonds de pension allemande et italienne : opposition explicite et déjà exercée contre un seuil pourtant non contraignant, au nom de la prudence et de la diversification. Risque réel qu'elles lisent le mécanisme de label comme une pression fonctionnelle équivalente — **c'est précisément ce que les considérants doivent anticiper.** (ii) BEUC et Finance Watch, sur l'orientation de l'épargne des ménages vers des actifs illiquides (friction n°10). À l'inverse, Insurance Europe, EFAMA et PensionsEurope soutiennent la mobilisation de l'épargne **sous réserve explicite d'absence d'obligation d'allocation** — condition que le dispositif respecte par construction, ce qui doit être rappelé à chaque échange.

Aucun de ces deux fronts n'est rédhibitoire seul. Le risque est leur conjonction.

## 7. Impact attendu, chiffré honnêtement

**Le gisement, tel qu'il est documenté :**
- Allocation des fonds de pension au capital-risque : **0,01 % des actifs dans l'Union contre 0,03 % aux États-Unis**, avec une estimation de **~210 Md$ supplémentaires sur dix ans** en cas d'alignement (micro §3.1). **Confiance : moyenne**, avec une réserve explicite déjà documentée — ce chiffre n'est pas réconcilié avec la mention « 5-15 % en *private equity* » issue de la même source, les définitions étant probablement différentes. **Ne pas citer le 210 Md$ sans cette réserve.**
- Une source distincte (Invest Europe, via `stakeholder-map` §7.3) situe l'allocation à **~0,12 % de quelque 3 000 Md€** d'actifs gérés par les fonds de pension européens. **L'écart avec le 0,01 % ci-dessus n'est pas résolu** et tient vraisemblablement à des périmètres différents. C'est un point à trancher avant toute analyse d'impact.
- Canal IORP : sur une base de l'ordre de **2 500 Md€**, environ **40 % en fonds d'investissement dont seulement 4 % en FIA**, soit **~40 Md€**. Porter la part de FIA de 4 % à 10 % ajouterait **~60 Md€** aux alternatifs, dont peut-être 10-20 % en capital-risque et croissance, soit **6-12 Md€** (macro §2.2 et §3.2(a)). Qualification de la base factuelle elle-même : « **significatif mais pas transformateur** ».

**Ce qui n'est pas disponible, et doit être dit :** **aucune estimation du taux de recours au label** n'existe, et aucune ne peut être dérivée des données disponibles. Or c'est la variable qui détermine entièrement l'effet. Un label dont l'avantage se limite à une dénomination et à un passeport de distribution simplifié peut avoir un taux de recours élevé ou quasi nul selon la valeur commerciale que le marché attache à ces deux éléments — et cette valeur est très difficile à anticiper depuis le retrait du volet fiscal.

**Formulation honnête recommandée pour tout document externe :** *le gisement d'allocation est le plus important identifié par la base factuelle ; l'effet de cet instrument précis sur ce gisement n'est pas estimable en l'état, faute de toute donnée sur le taux de recours attendu à un label dont l'avantage est purement réglementaire.* Le précédent britannique cité en `benchmarking` §2 (Mansion House Accord) est instructif en sens inverse : l'écart documenté entre engagement politique et déploiement réel est précisément ce qui justifie de préférer une conditionnalité juridique à un engagement volontaire — mais il rappelle aussi qu'un engagement d'allocation, même politiquement acquis, ne produit pas mécaniquement l'allocation.

## 8. Risques résiduels

Le retrait du volet fiscal prive le label de l'essentiel de son pouvoir d'attraction : ce qui reste est un avantage de distribution dont la valeur commerciale n'est pas établie, et le risque principal est désormais un texte adopté mais peu utilisé. La réserve au titre de l'article 63 TFUE est atténuée mais non éteinte : si un État membre attache ultérieurement un avantage fiscal national au label — ce que la conception d'origine recherchait explicitement — l'objection de restriction aux mouvements de capitaux ressurgira, contre l'État membre et non contre le règlement, et le texte doit être rédigé en sachant que c'est l'issue la plus probable de son succès. Enfin, l'anticipation des considérants ne garantit rien : une fédération professionnelle qui a construit sa position sur « la prudence l'exige » peut maintenir son opposition indépendamment de la réponse apportée à son motif déclaré.

---

# F9 — Sous-régime proportionné de MTF pour la liquidité pré-IPO

## 1. Nom et résumé du mécanisme final

**Sous-régime proportionné de système multilatéral de négociation dédié aux titres d'entreprises non cotées** — construit sur le modèle des marchés de croissance des PME de l'article 33 de la directive 2014/65/UE.

La catégorie d'infrastructure de marché entièrement nouvelle envisagée à l'origine est **abandonnée**. Motif dirimant : l'**article 1(7) de la directive 2014/65/UE impose que tout système multilatéral rapprochant des intérêts acheteurs et vendeurs multiples fonctionne comme marché réglementé, MTF ou OTF** — disposition insérée précisément pour fermer la faille qu'une quatrième catégorie rouvrirait. Le dispositif devient donc un **label de MTF**, exploité par une entreprise d'investissement ou un opérateur de marché agréé, fonctionnant par **enchères périodiques trimestrielles au maximum** (jamais en continu), avec un régime d'information proportionné, une exemption de prospectus plafonnée, et une application ciblée du règlement Abus de marché.

Deux restrictions structurantes issues de la correction : le régime est **réservé, au départ, aux formes de société à titres librement cessibles et dématérialisés — EU Inc. en priorité** — parce que le règlement CSDR ne règle pas les formalités nationales de transfert de parts sociales (l'acte notarié exigé pour les parts de GmbH en est le cas type) ; et l'**obligation de fenêtre de liquidité devient une présomption favorable de gouvernance**, non une obligation contraignante. Un **régime LCB-FT explicite** complète le dispositif.

## 2. Base juridique et procédure

**Article 53(1) TFUE**, base de la directive 2014/65/UE, le cas échéant combiné à l'article 114 TFUE. Procédure législative ordinaire, majorité qualifiée. **Instrument : une directive modifiant MiFID II** (insertion d'un chapitre ou d'articles après l'article 33), complétée par des normes techniques de l'ESMA.

**Pourquoi une directive et non un règlement.** Le régime des plateformes de négociation est établi par directive, et les marchés de croissance des PME — modèle explicite du dispositif — le sont à l'article 33 de cette directive. Créer un régime parallèle par règlement reproduirait exactement le vice de hiérarchie des normes corrigé sur F1. **Le coût est le délai de transposition** (18 à 24 mois), qui est la principale raison pour laquelle F9 est le texte le plus tardif de la grappe.

**Niveau 2.** Habilitation à l'ESMA pour des normes techniques sur : le contenu du dossier standardisé d'information, les modalités de l'enchère périodique, les critères d'enregistrement du MTF sous le label, et les modalités de dénouement.

**Rôle des institutions.** Commission (DG FISMA) : initiative. Parlement : ECON. Conseil : ECOFIN. ESMA : normes techniques et registre ; l'agrément demeure national, l'enregistrement sous le label suivant le modèle de l'article 33(2)-(3).

## 3. Ce qu'il faut rédiger concrètement

### 3.1 Considérants clés

- **Considérant de cohérence avec l'article 1(7).** Énoncer expressément que le dispositif ne crée aucune catégorie nouvelle de système multilatéral et que toute plateforme relevant du label est un MTF au sens de l'article 4(1)(22), soumis à l'ensemble des obligations applicables sauf allègement expressément prévu. **C'est le considérant qui répare l'erreur d'origine ; il doit être le premier des considérants de fond.**
- **Considérant de proportionnalité par analogie.** Fonder le régime allégé sur le précédent des marchés de croissance des PME : le législateur a déjà admis qu'un MTF dédié à des émetteurs de petite taille supporte un régime d'information adapté. Le dispositif étend cette logique un cran plus tôt dans le cycle de vie de l'entreprise.
- **Considérant sur le périmètre de forme sociale.** Énoncer que l'efficacité du dispositif suppose des titres librement cessibles et représentés sous forme dématérialisée, que le règlement (UE) n° 909/2014 **ne se substitue pas aux formalités de droit national relatives au transfert de parts sociales**, et que le régime est en conséquence ouvert en priorité aux formes de société de droit de l'Union et aux formes nationales satisfaisant ces conditions. **Ne pas prétendre que le CSDR règle la question : c'est l'erreur d'origine, et elle serait relevée en première lecture.**
- **Considérant sur la fenêtre de liquidité.** Justifier le passage de l'obligation à la présomption : une obligation d'organiser une fenêtre impose à une société d'admettre des actionnaires qu'elle n'a pas choisis, affecte les droits des associés existants au regard de l'article 17 de la Charte des droits fondamentaux, et — argument décisif — **rendrait la forme EU Inc. moins attractive que les formes nationales, à rebours de l'objet même du 28e régime.**
- **Considérant LCB-FT.** Rappeler que l'opérateur du MTF relève des entités assujetties au titre du cadre européen de lutte contre le blanchiment et le financement du terrorisme, et que les cessions opérées sur la plateforme sont soumises aux obligations de vigilance à l'égard de la clientèle.

### 3.2 Articles à insérer dans la directive 2014/65/UE

| Article | Contenu |
|---|---|
| **Art. 33 bis** | **Enregistrement en tant que « MTF de liquidité d'entreprise ».** Demande de l'opérateur à son autorité nationale, critères, notification à l'ESMA, registre public, retrait. Structure directement décalquée de l'article 33(2) et (3). |
| **Art. 33 ter** | **Périmètre des titres admis.** Titres de capital de sociétés établies dans l'Union, non admises sur un marché réglementé, de moins de vingt ans, ayant levé au moins 20 M€ en fonds propres, **dont les titres sont librement cessibles et représentés sous forme dématérialisée**, sur décision d'ouverture de l'organe de direction de l'émetteur. L'adhésion de l'émetteur est volontaire et révocable. |
| **Art. 33 quater** | **Modalités de négociation.** Enchères périodiques, fréquence maximale trimestrielle, interdiction de la négociation en continu. Fixation du prix, information sur le carnet, publication post-négociation limitée aux participants. La périodicité n'est pas un détail technique : c'est ce qui distingue le dispositif d'un marché de croissance et ce qui limite les effets de signal sur la valorisation privée. |
| **Art. 33 quinquies** | **Régime d'information proportionné.** Dossier standardisé obligatoire — comptes audités des deux derniers exercices, synthèse de la table de capitalisation, préférences de liquidation, valorisation de la dernière opération primaire, résumé des engagements hors bilan — mis à disposition des seuls participants quinze jours avant chaque fenêtre. Contenu précisé par normes techniques de l'ESMA. |
| **Art. 33 sexies** | **Participants éligibles.** Investisseurs professionnels, ELTIF, EuVGF, entreprises d'assurance, IORP, ainsi que salariés et anciens salariés de l'émetteur. Le maintien des salariés dans la liste est l'objet principal du dispositif et doit être protégé en négociation. |
| **Art. 33 septies** | **Dénouement.** Par un dépositaire central de titres agréé au titre du règlement (UE) n° 909/2014, **sans préjudice des formalités de droit national applicables au transfert de propriété** — rédaction expresse de la réserve, en cohérence avec le périmètre de l'article 33 *ter*. |
| **Art. 33 octies** | **LCB-FT.** Renvoi exprès aux obligations pesant sur l'opérateur en tant qu'entité assujettie, et obligation d'identification du bénéficiaire effectif de chaque acquéreur. *Les références précises du paquet LCB-FT sont à vérifier — voir annexe.* |

### 3.3 Modifications corrélatives dans d'autres actes

- **Règlement Prospectus (UE) 2017/1129, article 1er, paragraphe 4 :** insertion d'un point exemptant de prospectus les cessions opérées sur un MTF de liquidité d'entreprise, **en deçà de 50 M€ par fenêtre et par émetteur**. Rédiger comme une exemption plafonnée et non comme une exclusion de champ.
- **Règlement Abus de marché (UE) n° 596/2014 :** application des seules interdictions d'opération d'initié et de manipulation de marché, à l'exclusion des obligations de publication périodique et de tenue de listes d'initiés ; obligation pour l'émetteur de communiquer aux participants toute information significative dans les cinq jours précédant la fenêtre.
- **Règlement EU Inc. :** insertion d'une disposition de **gouvernance « se conformer ou s'expliquer »** — l'organe de direction d'une EU Inc. employant plus de 250 salariés, saisi par des détenteurs représentant au moins 10 % des instruments de participation salariée, **délibère** sur l'organisation d'une fenêtre de liquidité et motive publiquement sa décision. Aucune obligation d'organiser la fenêtre. C'est la conversion exacte de l'obligation d'origine en présomption favorable.

## 4. Séquencement et dépendances

**Dépendance externe déterminante et non maîtrisable : EU Inc.** Le règlement COM(2026) 321 final (procédure 2026/0074(COD), présenté le 18 mars 2026) est en tout début d'examen ; la Commission vise un accord avant fin 2026 pour des premières immatriculations début 2027, le règlement s'appliquant douze mois après son entrée en vigueur. **Tant qu'il n'existe pas un stock significatif d'EU Inc., le périmètre de F9 est quasi vide.** C'est l'argument le plus fort pour ne pas presser ce dossier.

**Dépendance sur F1 :** faible (les EuVGF figurent parmi les participants éligibles ; double branche de rédaction suffit).

**Dépendance en sens inverse : N3 dépend des données de F9.** C'est cette dépendance qu'il faut **couper**. N3 doit être conçu pour fonctionner sur les données existantes et n'ajouter les données de transaction F9 que dans une seconde phase. Faute de quoi la meilleure proposition de l'exercice hérite du calendrier de la plus tardive.

**Dépendance politique sur N5.** Le CERS et la BCE opposeront l'opacité des marchés privés et la valorisation de niveau 3. N5 en amont neutralise partiellement cette objection.

## 5. Calendrier réaliste

| Étape | Échéance |
|---|---|
| Travaux préparatoires, analyse d'impact | 2027 |
| Proposition de la Commission | 2028 |
| Négociation PE/Conseil | 2028-2030 — **traverse l'échéance électorale de 2029** |
| Publication | 2030 |
| Transposition | + 18 à 24 mois → **2031-2032** |

**Fenêtre concrète :** les suites du paquet intégration des marchés et supervision (proposé le 4 décembre 2025, en trilogue en 2026), ou un paquet « suites du Listing Act » une fois achevée la transposition des directives (UE) 2024/2810 et 2024/2811 (échéances des 6 décembre 2026 et 5 juin 2026).

**Recommandation franche :** F9 doit être présenté comme un dossier de la **législature 2029-2034**, dont les travaux préparatoires commencent maintenant. Le présenter comme livrable du cycle en cours n'est pas soutenable et affaiblirait la crédibilité des six autres réformes.

## 6. Acteurs institutionnels

- **DG FISMA** — unité marchés de titres.
- **ESMA** : normes techniques, registre. **DG JUST** en second rideau, pour l'articulation avec le droit des sociétés et le règlement EU Inc.
- **Parlement, ECON**, en articulation avec **JURI** sur le volet EU Inc. — le rapporteur du 28e régime, **René Repasi** (S&D, Allemagne), rapporteur du rapport d'initiative JURI 2025/2079(INL), est l'interlocuteur naturel du volet gouvernance.
- **Conseil, ECOFIN**, avec les autorités nationales de marché en arrière-plan.

**Obstacle politique principal, documenté.** Le rattachement au 28e régime expose F9 à l'opposition syndicale documentée contre EU Inc. — CES/ETUI, UNI Europa, Corporate Europe Observatory (`stakeholder-map` §7.1, friction n°7, position la plus radicale de toute la cartographie) — alors même que l'objet de F9 (liquidité) n'est pas celui que visent ces organisations (droit du travail). **La conversion de l'obligation de fenêtre en présomption réduit substantiellement cette exposition**, puisqu'elle supprime la contrainte imposée à l'employeur. Second obstacle, structurel : les autorités nationales de marché contesteront tout dispositif perçu comme échappant à MiFID II — objection que la reconstruction en sous-régime de MTF prive de son objet, ce qui doit être dit en première ligne de tout échange technique.

## 7. Impact attendu, chiffré honnêtement

**Le seul chiffre disponible est un chiffre de comparaison, pas d'impact :** le marché américain des secondaires privés est chiffré à **plus de 120 Md$ en 2025** (`benchmarking` §2), contre un marché européen resté bilatéral et notarial. Ce chiffre décrit un écart, il ne prédit rien.

**Ce qui n'est pas disponible, et doit être dit sans détour :** **il n'existe aucun ordre de grandeur, dans la base factuelle, du volume de transactions secondaires qui émergerait en Europe** sous ce régime. Ni le nombre d'émetteurs susceptibles d'ouvrir une fenêtre, ni le volume par fenêtre, ni le taux d'adhésion. Toute estimation avancée à ce stade serait fabriquée. La seule affirmation défendable est directionnelle.

**Ce qui est documenté qualitativement et constitue le vrai fondement du dossier :** l'absence de marché secondaire est un **coût opérationnel réel**, non un simple manque de liquidité (micro §3.3) — les salariés ne peuvent pas monétiser leurs instruments, ce qui dégrade l'attractivité des plans de participation, augmente la part de rémunération en numéraire, dégrade la trésorerie et raccourcit la piste de financement. Micro §2.3 en fait l'une des micro-incitations documentées du transfert vers le Delaware. Micro §5.1 relève que cette proposition **est absente de tous les textes en discussion** — c'est le seul dispositif de la grappe qui ne double aucun chantier existant.

**Formulation honnête recommandée :** *le problème traité est documenté et n'est traité par aucun texte en discussion ; l'ampleur de l'effet n'est pas estimable et le sera au mieux après une phase pilote.* Prévoir dans le texte une **clause de réexamen à trois ans avec obligation de publication des volumes par l'ESMA** — c'est le moyen d'obtenir la donnée que l'on n'a pas.

## 8. Risques résiduels

La restriction aux formes à titres librement cessibles et dématérialisés, juridiquement nécessaire, réduit fortement le périmètre utile tant que le stock d'EU Inc. reste faible — le dispositif peut donc être adopté puis rester inutilisé plusieurs années, non par défaut de conception mais par dépendance à un texte tiers. La fixation d'un prix par enchère trimestrielle sur des titres non cotés produira des références de valorisation dont l'usage débordera la plateforme, avec des conséquences comptables et prudentielles pour les détenteurs qui ne participent pas — effet de bord réel, que le caractère périodique atténue sans le supprimer. Enfin, l'exemption de prospectus plafonnée à 50 M€ par fenêtre et par émetteur sera contestée comme une brèche dans le régime d'information des investisseurs, et le plafond devra être défendu par un raisonnement de proportionnalité que le texte doit porter dès les considérants.

---

# F12 — Recyclage du bilan de garantie par titrisation

## 1. Nom et résumé du mécanisme final

**Programme de titrisation synthétique de bilan du portefeuille de garanties du Fonds européen d'investissement, adossé au cadre STS existant.**

Le FEI structure, sur base annuelle, une titrisation synthétique de son portefeuille de garanties aux entreprises innovantes et de dette de croissance, **au sein de la catégorie des titrisations synthétiques de bilan STS déjà prévue aux articles 26 *bis* à 26 *sexies* du règlement (UE) 2017/2402**, qui accueille précisément les portefeuilles de PME garantis par le FEI. Aucune catégorie nouvelle n'est créée.

**Correction arithmétique centrale, qui inverse le montage d'origine.** La version initiale prévoyait de **retenir la tranche de première perte** (jusqu'à 8 %) et de céder les tranches mezzanine et senior. C'est l'inverse de ce qu'il faut faire : le provisionnement d'une garantie budgétaire est déterminé par la **perte attendue**, et la perte attendue d'un portefeuille est concentrée dans la première perte. En retenant la première perte, l'Union cède l'essentiel du risque **inattendu** et conserve l'essentiel du risque **attendu** — sa provision n'est donc pas libérée, et l'affirmation d'origine selon laquelle « chaque euro provisionné supporte environ trois générations successives de garantie » ne tient pas. **Le montage correct est : céder la première perte ou une tranche mezzanine, et retenir une part verticale.** La calibration *through-the-cycle* des critères de résilience est conservée telle quelle.

## 2. Base juridique et procédure

**Deux volets, deux véhicules :**

**(i) Volet titrisation.** Amendements au **règlement (UE) 2017/2402** et au **règlement (UE) n° 575/2013 (CRR)**, actuellement en révision : position du Parlement adoptée le **5 mai 2026**, trilogues attendus au **second semestre 2026**. Base : article 114 TFUE, procédure législative ordinaire, majorité qualifiée. **Il ne s'agit pas de déposer un texte mais d'alimenter un trilogue en cours** — l'action porte sur des amendements et sur la position de la Commission en trilogue, non sur une initiative législative.

**(ii) Volet budgétaire.** Article dans le **règlement établissant le Fonds européen pour la compétitivité** (COM(2025) 555 final, en négociation ITRE/Conseil), disposant que le transfert de risque significatif réduit à due proportion le provisionnement de la garantie budgétaire correspondante. Base : article 173 TFUE et suivants, procédure législative ordinaire. **Sans cet article, l'effet de recyclage n'existe pas juridiquement, quelle que soit la qualité du montage financier.**

**Rôle des institutions.** Commission : DG FISMA (volet titrisation), DG BUDG et DG ECFIN (volet provisionnement), DG GROW/RTD (règlement FEC). Parlement : ECON pour la titrisation, ITRE pour le FEC (co-rapporteurs **Christian Ehler**, PPE, Allemagne, et **Dan Nica**, S&D, Roumanie). Conseil : ECOFIN et Compétitivité. **Groupe BEI et FEI :** acteurs opérationnels, non législateurs, mais leur avis technique sur la faisabilité du montage conditionne la crédibilité de l'ensemble.

## 3. Ce qu'il faut rédiger concrètement

### 3.1 Volet titrisation — trois amendements, pas un régime nouveau

**Amendement 1 — confirmation d'éligibilité.** Vérifier et, si nécessaire, préciser aux articles 26 *bis* à 26 *sexies* que les portefeuilles d'expositions couvertes par une garantie budgétaire de l'Union satisfont les exigences d'homogénéité et de granularité, et que le FEI peut avoir la qualité d'initiateur au sens de l'article 2(3). **Rédaction préférable : un considérant de clarification plutôt qu'un article nouveau** — l'ajout d'un article invite à rouvrir le régime STS entier en trilogue.

**Amendement 2 — forme de la rétention. C'est l'amendement décisif, et il découle directement de la correction arithmétique.** L'article 6 du règlement (UE) 2017/2402 impose à l'initiateur de conserver un intérêt économique net significatif d'au moins 5 %, selon des formes limitativement énumérées à son paragraphe 3 : notamment la **part verticale** de 5 % de chaque tranche cédée, et la **tranche de première perte**. Il faut noter, et écrire dans la note de position, que **la rétention d'une tranche senior seule ne figure pas parmi les formes de rétention admises**. Il en résulte que, des deux options ouvertes par la correction, **une seule satisfait simultanément l'exigence de rétention et l'objectif de libération de provision : la part verticale.**

C'est le point technique le plus important de toute la fiche : *la correction arithmétique (« retenir senior ou une part verticale ») se réduit en pratique, sous le droit de la rétention, à la seule part verticale.* **Réserve expresse : la rédaction finale de l'article 6 issue du trilogue en cours doit être vérifiée avant de figer cette conclusion.**

**Amendement 3 — calibration *through-the-cycle*.** Ancrer les critères de résilience sur un cycle complet et non sur les performances récentes, et insérer une **clause de revue automatique si l'encours ABS européen dépasse 800 Md€** (macro §6.2(3), point médian de la trajectoire 600 Md€ → 1 000 Md€+ anticipée par le marché). Cet amendement est le meilleur atout politique du dossier : il est demandé par le CERS et donne au reste du paquet une couleur de responsabilité macroprudentielle.

**Ce qu'il ne faut pas rédiger :** la catégorie « position de titrisation résiliente » définie par la qualité de l'Union comme sponsor. Elle fait doublon avec le régime STS de bilan et expose à l'objection d'un **rehaussement public implicite dans le capital bancaire** — objection qui serait soulevée par la BCE et à laquelle il n'existe pas de bonne réponse.

### 3.2 Volet FEC — un article et un considérant

**Article « Transfert de risque et provisionnement ».** Structure :
1. Principe : lorsqu'une part significative de la perte attendue d'un portefeuille couvert par une garantie budgétaire est transférée à des tiers dans une opération satisfaisant les articles 26 *bis* à 26 *sexies* du règlement (UE) 2017/2402, le taux de provisionnement est **révisé à la baisse à due proportion de la perte attendue transférée**.
2. Méthode : la perte attendue transférée est établie sur la base d'une estimation documentée et **publiée** de la perte attendue du portefeuille par compartiment, révisée annuellement.
3. Garde-fou : la révision ne peut abaisser le provisionnement en deçà de la perte attendue de la part retenue, majorée d'une marge de prudence.
4. Transparence : publication annuelle, par compartiment, du taux de provisionnement, de la perte attendue estimée et de la perte constatée.

**Considérant associé :** énoncer que le règlement financier impose déjà que le taux de provisionnement soit fixé au regard de la perte attendue et révisé périodiquement, et que la disposition **précise l'application de cette règle** au cas du transfert de risque — présentation en application d'une règle existante, non en innovation. C'est à la fois exact et considérablement plus facile à faire passer.

## 4. Séquencement et dépendances

**Aucune dépendance sur les six autres réformes.** F12 est le seul dispositif de la grappe entièrement autoportant.

**Dépendance externe forte et à échéance courte :** le trilogue titrisation du S2 2026, et la négociation du règlement FEC, elle-même suspendue à l'accord global sur le CFP — le Conseil européen des 18-19 juin 2026 n'ayant pas abouti, la présidence irlandaise du second semestre 2026 est chargée de faire progresser la boîte de négociation avant le sommet d'octobre 2026, avec un objectif d'accord politique avant la fin de 2026.

**Séquence interne obligatoire :** l'article FEC sur le provisionnement doit être adopté **avant ou en même temps** que la première opération. Une opération conduite sans base juridique de libération de provision produirait un transfert de risque sans effet budgétaire — c'est-à-dire un coût sans contrepartie.

## 5. Calendrier réaliste

| Étape | Échéance |
|---|---|
| Note de position et amendements au trilogue titrisation | **S2 2026 — immédiat, fenêtre courte** |
| Article de provisionnement dans le règlement FEC | pendant la négociation FEC, 2026-2027 |
| Adoption du paquet titrisation | 2027 |
| Application | 2027-2028 selon le différé retenu |
| Première opération du FEI sous le nouveau régime | **2028** |
| Deuxième génération de garantie adossée à la provision libérée | **2029** |

**C'est la réforme la plus rapide de la grappe** — parce qu'elle ne crée rien et se greffe sur deux textes déjà en navigation. C'est aussi celle dont la fenêtre se referme le plus tôt.

## 6. Acteurs institutionnels

- **DG FISMA** (titrisation), **DG BUDG** (provisionnement et règlement financier), **DG ECFIN**.
- **Groupe BEI et FEI** : structuration effective. Leur avis technique sur le montage inversé est le premier livrable à obtenir — avant tout amendement.
- **Parlement : ECON** (titrisation) et **ITRE** (FEC, co-rapporteurs Ehler et Nica).
- **Conseil : ECOFIN**, présidence irlandaise au S2 2026.
- **BCE et CERS** : avis, sur la procyclicité.

**Obstacle politique principal.** La cartographie ne documente **aucune résistance nommée** sur ce mécanisme, et un soutien directionnel de la Fédération bancaire européenne à la complémentarité banque/marché. L'opposition attendue, telle qu'anticipée à l'origine, portait sur le fait que le budget de l'Union conserve la première perte tout en cédant le rendement — **objection que la correction du tranchage fait précisément disparaître**, ce qui est un argument de communication à exploiter : le montage corrigé est plus défendable que le montage d'origine, et il faut le dire. L'objection résiduelle est celle du CERS sur la procyclicité, traitée par la calibration *through-the-cycle* et la clause de revue à 800 Md€.

## 7. Impact attendu, chiffré honnêtement

**L'affirmation d'origine est retirée.** « Chaque euro provisionné supporte environ trois générations successives de garantie » reposait sur le montage inversé et ne tient pas. **Elle ne doit reparaître dans aucun document.**

**Ce qui peut être dit avec le montage corrigé :** le facteur de recyclage est, par construction, égal à la **part de la perte attendue effectivement transférée**. Une cession portant sur X % de la perte attendue libère X % de la provision. Ce n'est pas une estimation, c'est une identité — et c'est précisément pour cela qu'elle est utilisable : elle est vraie quel que soit le portefeuille.

**Ce qui manque pour convertir cette identité en chiffre :** **l'estimation de la perte attendue du portefeuille de garanties du FEI par compartiment n'est pas publique** et ne figure pas dans la base factuelle. Sans elle, aucun facteur de recyclage ne peut être avancé. **C'est le premier document à demander au FEI**, et c'est aussi ce que l'article FEC proposé rendrait obligatoire pour l'avenir.

**Chiffres de contexte disponibles, avec leur confiance :**
- Dette de croissance : **12,7 % du capital total levé en 2025, soit 5,6 Md$** (micro §2.5). **Mais** la base factuelle documente un désaccord non résolu d'un facteur ~5 entre sources sur le venture debt européen (4,6 Md$ selon Statista *contre* ~29 % de la valeur des transactions de capital-risque selon Houlihan Lokey) — **confiance très faible**, symptôme d'une absence de définition harmonisée. **Ne pas citer un chiffre unique de venture debt européen.**
- Expansion du marché ABS européen de ~600 Md€ à plus de 1 000 Md€ : **confiance faible** — estimations de marché *sell-side*, non validées par une institution officielle, à traiter comme scénario haut.
- Composante InvestEU du FEC : **~11 Md€ de garanties sur sept ans** — c'est l'ordre de grandeur du bilan sur lequel le recyclage opère.

**La réserve d'honnêteté déjà inscrite dans la fiche d'origine doit être maintenue et mise en avant :** la titrisation **ne finance pas directement les fonds propres de scale-up**. Son effet passe par la libération de bilan bancaire et par la création d'une classe d'actifs de dette structurée ; l'effet sur le financement en fonds propres est **de second ordre**, et il serait analytiquement malhonnête de présenter ce mécanisme comme une réponse à l'écart de financement en capital (macro §2.5).

## 8. Risques résiduels

Le montage corrigé n'est un gain budgétaire que si la cession de la première perte ou de la mezzanine trouve preneur à un prix qui n'annule pas l'économie de provision — question de marché que le droit ne règle pas, et sur laquelle l'avis du FEI est indispensable avant tout engagement. La contrainte de l'article 6 sur les formes admises de rétention réduit vraisemblablement les options à la seule part verticale, ce qui doit être confirmé sur le texte issu du trilogue. Enfin, l'effet reste de second ordre pour le financement en fonds propres, ce qui est la limite intrinsèque du dispositif et non un défaut d'exécution.

---

# N3 — Utilité européenne de valorisation des actifs privés

## 1. Nom et résumé du mécanisme final

**Fonction de méthodologie de valorisation des actifs privés, exercée par le comité mixte des autorités européennes de surveillance.**

Le comité mixte — structure **déjà existante**, réunissant l'ABE, EIOPA et l'ESMA — reçoit mandat de produire et publier **trimestriellement** des **méthodologies de référence de valorisation** par catégorie d'actif : parts de fonds de capital-risque et de croissance non cotés, par millésime et par stade, ELTIF, dette de croissance. Les méthodologies sont mises gratuitement à disposition de tout IORP et de toute entreprise d'assurance de l'Union. **Aucun organisme nouveau n'est créé.**

Deux garde-fous sont constitutifs du dispositif, non accessoires :

- **La présomption porte sur le respect de la méthode, jamais sur l'exactitude du résultat.** La responsabilité de la valorisation demeure intégralement celle du gestionnaire au titre de l'article 19 de la directive 2011/61/UE et des articles 67 à 74 du règlement délégué (UE) n° 231/2013 ; la valorisation prudentielle demeure régie par l'article 75 de la directive 2009/138/CE. Une présomption opposable au contrôleur légal des comptes heurterait par ailleurs son indépendance au titre de la directive 2006/43/CE.
- **Publication de fourchettes et de dispersions, jamais de valeurs ponctuelles uniques.** Une méthodologie officielle unique employée par l'ensemble du secteur institutionnel produirait une **monoculture de valorisation** qui corrélerait les erreurs de tout le secteur et amplifierait la procyclicité en cas de choc — exactement le mécanisme de latence de valorisation identifié en macro §6.2(4). **C'est le seul instrument de l'exercice qui crée un vecteur de corrélation nouveau ; le correctif doit être dans le dispositif, pas dans le commentaire.**

## 2. Base juridique et procédure

**Article 114 TFUE**, procédure législative ordinaire, majorité qualifiée. **Instrument : un règlement modifiant les règlements (UE) n° 1094/2010 (EIOPA) et (UE) n° 1095/2010 (ESMA)** — et, si le comité mixte est saisi dans sa composition complète, également le règlement (UE) n° 1093/2010 (ABE), les dispositions relatives au comité mixte figurant aux articles 54 à 57 de chacun des trois règlements.

**Nature de l'acte produit.** Les méthodologies ne sont **ni des normes techniques contraignantes** (elles ne sont pas adoptées par la Commission), **ni de simples publications**. La qualification correcte est celle d'**orientations au titre de l'article 16 des règlements fondateurs**, assorties du mécanisme « se conformer ou s'expliquer » applicable aux autorités compétentes et, dans les conditions de cet article, aux entités financières. C'est le régime qui produit l'effet recherché — une référence que l'on peut invoquer — sans créer l'abri juridique que la correction interdit.

**Financement.** Le Fonds européen pour la compétitivité peut financer le dispositif, mais la **voie budgétaire ordinaire des autorités européennes de surveillance est préférable** : elle évite de rattacher une fonction de supervision permanente à un instrument budgétaire à durée déterminée dont la survie n'est pas garantie au-delà de 2034.

## 3. Ce qu'il faut rédiger concrètement

### 3.1 Considérants clés

- **Considérant de diagnostic.** Énoncer que le coût unitaire de la diligence et l'absence de méthode de valorisation standardisée constituent un frein documenté et **distinct de la charge prudentielle**, pesant spécifiquement sur les investisseurs institutionnels de taille moyenne dépourvus d'équipe de gestion actif-passif sophistiquée (micro §3.1). Ce considérant est ce qui distingue N3 de tout le reste de la grappe : il traite une cause déclarée d'opposition plutôt qu'il ne la contourne.
- **Considérant de responsabilité — à rédiger avec un soin particulier.** Énoncer expressément que le règlement **ne modifie ni ne transfère la responsabilité de valorisation** incombant au gestionnaire au titre de l'article 19 de la directive 2011/61/UE et des articles 67 à 74 du règlement délégué (UE) n° 231/2013, ni les obligations de valorisation prudentielle de l'article 75 de la directive 2009/138/CE, ni l'indépendance du contrôleur légal des comptes au titre de la directive 2006/43/CE.
- **Considérant anti-monoculture.** Énoncer que la publication de valeurs ponctuelles uniques induirait une convergence artificielle des valorisations et une corrélation des erreurs à l'échelle du système, et que la publication sous forme de fourchettes et de mesures de dispersion est **une exigence de stabilité financière, non une précaution méthodologique**. Ce considérant est la réponse écrite au seul risque systémique que le dispositif crée.
- **Considérant de proportionnalité institutionnelle.** Justifier le recours au comité mixte existant plutôt qu'à un organisme nouveau.

### 3.2 Articles

| Article | Contenu |
|---|---|
| **Art. 1** | Insertion, dans les règlements 1094/2010 et 1095/2010, d'une **mission nouvelle du comité mixte** : élaborer, publier et actualiser des méthodologies de référence de valorisation des actifs privés. |
| **Art. 2** | **Contenu et forme de la publication.** Périodicité trimestrielle. Catégories couvertes. **Obligation expresse de publier des fourchettes et des mesures de dispersion, et interdiction expresse de publier une valeur ponctuelle unique par catégorie.** Rédiger l'interdiction comme telle : une simple faculté serait abandonnée à la première demande d'utilisateur. |
| **Art. 3** | **Effet juridique.** Orientations au sens de l'article 16 des règlements fondateurs. Un gestionnaire ou une entreprise appliquant la méthodologie est réputé avoir respecté **les exigences procédurales** de valorisation qui lui incombent ; **la conformité du résultat de la valorisation demeure appréciée selon les règles qui lui sont applicables.** La formulation en deux membres de phrase est le cœur du dispositif — c'est elle qui distingue une présomption de méthode d'un abri juridique. |
| **Art. 4** | **Sources de données — deux phases.** *Phase 1* : données de levée et de valorisation transmises par les gestionnaires agréés, y compris au titre du reporting de l'Annexe IV de la directive 2011/61/UE, et données déjà détenues par l'ESMA et EIOPA. *Phase 2* : données de transaction issues des MTF de liquidité d'entreprise (F9), **lorsque celles-ci seront disponibles**. **Cette rédaction en deux phases est la disposition la plus importante du texte pour le calendrier** : elle rend N3 opérationnel sans attendre F9. |
| **Art. 5** | **Gouvernance.** Sous-comité du comité mixte, coprésidence ESMA/EIOPA, participation des autorités nationales compétentes, consultation obligatoire des parties prenantes avant chaque révision méthodologique majeure. |
| **Art. 6** | Confidentialité et protection des données transmises ; publication agrégée uniquement. |
| **Art. 7** | Clause de réexamen à quatre ans, portant expressément sur **la mesure de la dispersion effective des valorisations sur la période** — c'est-à-dire sur l'indicateur qui révélerait une monoculture naissante. |

## 4. Séquencement et dépendances

**Dépendance sur F9 : réelle mais à couper par la rédaction en deux phases** (article 4). C'est la décision de conception la plus importante de la fiche. F9 n'entrera pas en application avant 2031-2032 ; N3 conçu en phase 1 peut publier dès 2029.

**Dépendance sur F1 :** faible. La granularité par millésime et par stade est plus fine si la catégorie EuVGF existe, mais les méthodologies peuvent être établies par stratégie de fonds indépendamment du statut réglementaire du véhicule.

**N3 est un intrant de F5.** La calibration d'un escalier par horizon de détention suppose des séries de valorisation dont la dispersion est mesurée : N3 produit cette matière. **N3 avant F5** améliore matériellement le dossier soumis à EIOPA.

**N3 est le complément politique de F7.** F7 contourne l'opposition des fédérations de fonds de pension, N3 traite sa cause déclarée. Les annoncer ensemble change la nature de la conversation ; annoncer F7 seul, c'est présenter la contrainte sans la réponse.

## 5. Calendrier réaliste

| Étape | Échéance |
|---|---|
| Greffe sur le paquet intégration des marchés et supervision (proposé le 4 décembre 2025, en trilogue en 2026) | **2026-2027 — fenêtre ouverte** |
| Adoption | 2027-2028 |
| Constitution du sous-comité, méthodologie initiale, consultation | 2028 |
| **Première publication trimestrielle** | **2029** |
| Phase 2 (intégration des données de transaction F9) | 2032+ |

**Fenêtre concrète :** le paquet intégration des marchés et supervision est le véhicule idéal — il modifie déjà les règlements fondateurs des autorités européennes de surveillance et la gouvernance de l'ESMA. Y insérer N3 par amendement est **considérablement plus rapide que de déposer un texte autonome**, et c'est ce qu'il faut viser. À défaut, la revue à mi-parcours de la SIU du T2 2027 constitue un véhicule de repli.

## 6. Acteurs institutionnels

- **ESMA et EIOPA** : acteurs principaux et futurs opérateurs. Leur avis technique préalable est le premier livrable — un mandat de méthodologie confié à des autorités qui ne le veulent pas est un mandat mort.
- **DG FISMA** : rédaction et arbitrage du véhicule.
- **Parlement : ECON. Conseil : ECOFIN.**
- **Comité mixte des autorités européennes de surveillance** : structure d'accueil.

**Obstacle politique principal — et c'est ici que N3 se distingue.** La cartographie ne documente **aucune résistance**, ni nommée ni inférée. Les deux passages d'évaluation convergent pour en faire la proposition la mieux construite politiquement du corpus entier, **parce qu'elle traite la cause déclarée d'une friction majeure plutôt que de la contourner** : le motif documenté de l'opposition des fédérations de fonds de pension allemande et italienne est « les principes de prudence et de diversification », et le mécanisme concret derrière cette prudence est le coût unitaire de la diligence et l'absence de méthode de valorisation.

**Réserve documentée à conserver :** une fédération professionnelle qui a construit sa position sur « la prudence l'exige » peut être réticente à admettre que l'obstacle réel était plus opérationnel que doctrinal. La résistance attendue est **sensiblement plus faible** que sur F7, mais un soutien actif n'est pas garanti.

Obstacle secondaire, à ne pas sous-estimer : la profession du contrôle légal des comptes réagira à toute rédaction pouvant être lue comme opposant une méthodologie officielle à son jugement professionnel. Le considérant de responsabilité et la formulation en deux membres de l'article 3 sont la réponse — **et il faut les avoir écrits avant la première réunion avec la profession, pas après.**

## 7. Impact attendu, chiffré honnêtement

**Aucun chiffre d'impact n'est disponible, et il faut le dire d'emblée.** La base factuelle documente le frein **qualitativement** (micro §3.1 : sélectionner un gérant de capital-risque coûte le même travail que sélectionner un gérant obligataire pour vingt fois moins de montant) sans jamais le quantifier. Il n'existe ni estimation du coût unitaire de diligence, ni estimation de sa réduction attendue, ni estimation de l'allocation additionnelle qui en résulterait. **Toute figure avancée ici serait entièrement fabriquée.**

**Le plafond du canal auquel N3 contribue**, à titre de cadrage seulement : sur une base IORP de l'ordre de 2 500 Md€, dont ~40 % en fonds d'investissement mais seulement 4 % de cette poche en FIA (~40 Md€), porter la part de FIA de 4 % à 10 % ajouterait ~60 Md€ aux alternatifs, dont peut-être 10-20 % en capital-risque et croissance, soit **6-12 Md€** (macro §2.2). **Ce chiffre est le plafond de tout le canal IORP, toutes causes confondues ; N3 ne traite qu'une des frictions qui l'obstruent, et sa part n'est pas isolable.**

**Coût pour le budget de l'Union :** faible mais non nul — dotation d'un sous-comité permanent au sein du comité mixte, collecte et traitement de données. Aucun chiffrage n'est disponible dans la base factuelle ; il devra être établi par les deux autorités concernées.

**Formulation honnête recommandée :** *l'instrument traite un frein documenté qualitativement, à coût faible, sans créer d'obligation nouvelle ; son effet quantitatif n'est pas estimable en l'état et ne le sera qu'après plusieurs cycles de publication.* Prévoir la mesure dans la clause de réexamen de l'article 7.

## 8. Risques résiduels

Le risque de monoculture de valorisation est atténué par la publication en fourchettes mais n'est pas éliminé : des acteurs cherchant une référence défendable convergeront naturellement vers le centre de la fourchette publiée, et c'est précisément ce que la clause de réexamen doit mesurer. La frontière entre présomption de méthode et présomption de résultat, claire dans le texte, sera brouillée dans la pratique par les utilisateurs qui invoqueront la méthodologie comme un abri — la vigilance de rédaction doit se doubler d'une vigilance de communication des deux autorités. Enfin, l'absence de résistance documentée est aussi un signal d'absence de données : aucune partie prenante ne s'est prononcée sur ce dispositif précis, trop récent, et le verdict de faisabilité repose donc sur une inférence solide mais non confirmée.

---

# N5 — Collège de stabilité financière de l'innovation

## 1. Nom et résumé du mécanisme final

**Sous-structure dédiée du Comité européen du risque systémique, chargée du suivi de l'exposition agrégée du dispositif européen de financement de l'innovation.**

Aucun organe nouveau n'est créé. Le CERS dispose **déjà** du mandat de surveillance macroprudentielle de l'ensemble du système financier de l'Union (règlement (UE) n° 1092/2010, article 3), d'un conseil général réunissant les mêmes acteurs que ceux qu'un collège nouveau aurait réunis, et d'un pouvoir d'alerte et de recommandation assorti du mécanisme « agir ou s'expliquer » (articles 16 et 17). Le dispositif consiste donc à **loger un mandat spécialisé dans une structure existante**, rendant compte au conseil général et opérant au sein du comité technique consultatif.

**La seule véritable nouveauté juridique nécessaire — et c'est le cœur du texte :** une **obligation légale de déclaration pesant sur le Groupe BEI (BEI et FEI) et sur les banques nationales de promotion**, aujourd'hui hors de tout périmètre de reporting prudentiel de l'Union. Ces entités sont **entités déclarantes, non membres du collège** : un organe ne peut pas surveiller ses propres expositions. **Sans cette obligation, le collège se réunit sans données et le dispositif est cosmétique.**

## 2. Base juridique et procédure

**Article 114 TFUE**, procédure législative ordinaire, majorité qualifiée. **Instrument : un règlement modifiant le règlement (UE) n° 1092/2010** relatif à la surveillance macroprudentielle du système financier dans l'Union et instituant le CERS.

**Point de droit à traiter dans l'exposé des motifs.** L'obligation de déclaration pesant sur le Groupe BEI appelle une justification particulière : la BEI est une institution de l'Union régie par le protocole n° 5 annexé aux traités et par ses propres statuts. L'obligation doit donc être rédigée comme une **obligation de transmission d'informations à des fins de surveillance macroprudentielle**, et non comme une soumission à une supervision prudentielle — distinction juridiquement essentielle et politiquement décisive pour obtenir l'accord du Groupe. *Point à faire expertiser par le service juridique avant tout dépôt.*

Pour les **banques nationales de promotion**, la difficulté est différente : elles relèvent de statuts nationaux hétérogènes, certaines étant des établissements de crédit soumis au CRR, d'autres non. L'obligation doit être rédigée par référence à une **fonction** (octroi de financements ou de garanties à des entreprises innovantes pour le compte ou avec le soutien d'un État membre ou de l'Union) et non par référence à un statut.

**Rôle des institutions.** Commission (DG FISMA) : initiative. Parlement : ECON. Conseil : ECOFIN. CERS et BCE : consultation, et opérateurs du dispositif. Groupe BEI et banques nationales de promotion : entités déclarantes.

## 3. Ce qu'il faut rédiger concrètement

### 3.1 Considérants clés

- **Considérant de constat.** Énoncer que les vecteurs de concentration produits par l'expansion du financement de l'innovation sont **corrélés** et qu'aucun organe ne les observe ensemble — constat déjà posé par la base factuelle (macro §6.3) avant tout débat contradictoire.
- **Considérant d'exécution d'une recommandation existante.** Renvoyer expressément au **rapport conjoint BCE-CERS du 12 février 2026**, qui a déjà recommandé un mécanisme centralisé de partage de données, resté sans suite. **C'est l'argument le plus fort du dossier :** le texte n'invente rien, il exécute une recommandation publiée par les institutions mêmes qui seraient fondées à s'y opposer.
- **Considérant de proportionnalité institutionnelle.** Justifier le logement dans le CERS plutôt que la création d'un organe : mandat existant, composition existante, pouvoir d'alerte existant.
- **Considérant sur la qualité d'entité déclarante.** Énoncer que le Groupe BEI et les banques nationales de promotion **ne sont pas membres** de la structure, au motif exprès qu'un organe ne peut pas surveiller ses propres expositions. Écrire le motif, et non seulement la règle : c'est ce qui rendra la disposition difficile à renverser en négociation.
- **Considérant sur la nature des pouvoirs.** Rappeler que la structure ne dispose d'aucun pouvoir contraignant nouveau et exerce, dans son champ, les pouvoirs d'alerte et de recommandation que le CERS détient déjà.

### 3.2 Articles

| Article | Contenu |
|---|---|
| **Art. 1** | **Institution de la structure.** Sous-structure permanente rendant compte au conseil général du CERS, adossée au comité technique consultatif. Composition : Commission, EIOPA, ESMA, ABE, BCE, autorités nationales compétentes et macroprudentielles. Réunion trimestrielle. |
| **Art. 2** | **Mandat.** Suivi de l'exposition agrégée du système financier de l'Union aux vecteurs de concentration du financement de l'innovation, incluant expressément : concentration sectorielle des expositions du Groupe BEI et du FEI, expositions croisées entre instruments publics et privés, exposition des ELTIF *evergreen* de détail, conditions de non-vente forcée du régime LTEI, et encours de titrisation adossée à des portefeuilles garantis. |
| **Art. 3** | **Entités déclarantes — l'article central.** Le Groupe BEI et les entités exerçant une fonction de banque nationale de promotion transmettent périodiquement au CERS les données relatives à leurs expositions au financement des entreprises innovantes. **Rédiger avec précision : périmètre des données, périodicité, format, destinataire, régime de confidentialité, conséquence du défaut de transmission.** Une obligation de déclaration sans conséquence attachée n'est pas une obligation. |
| **Art. 4** | **Normes techniques.** Habilitation à définir le format et le contenu du reporting, par acte d'exécution de la Commission ou par norme technique élaborée par les autorités européennes de surveillance. **Point à trancher tôt : sans format harmonisé, les données arriveront dans vingt-sept formats incomparables et le dispositif échouera par la donnée, non par le droit.** |
| **Art. 5** | **Alerte.** Exercice, dans le champ du mandat, des pouvoirs d'alerte et de recommandation des articles 16 et 17 du règlement (UE) n° 1092/2010, y compris le mécanisme « agir ou s'expliquer ». **Aucun pouvoir nouveau.** |
| **Art. 6** | Publication annuelle d'un tableau de bord agrégé, en cohérence avec le tableau de bord des risques existant du CERS. |
| **Art. 7** | Clause de réexamen à quatre ans, portant notamment sur la qualité et la comparabilité des données reçues. |

## 4. Séquencement et dépendances

**Aucune dépendance juridique.** N5 peut être adopté seul, à tout moment, et ne suppose l'adoption d'aucune autre réforme.

**Forte dépendance d'opportunité, en sens inverse de l'intuition.** N5 doit être adopté **le plus tôt possible et de préférence avant F5 et F9**, parce que sa fonction politique est de retirer aux autorités macroprudentielles l'objection qu'elles opposeront à ces deux textes. C'est un investissement de recevabilité.

**Articulation avec les obligations de reporting instrument par instrument.** Plusieurs réformes de la grappe créent leurs propres obligations de déclaration (F5 sur le suivi EIOPA, F12 sur la publication du provisionnement par compartiment). N5 est le lieu où ces flux se rencontrent. **Rédiger l'article 3 de manière à absorber ces flux plutôt qu'à les dupliquer** : une obligation de déclaration qui fait doublon avec une obligation existante est le premier grief que soulèvera toute entité déclarante.

## 5. Calendrier réaliste

| Étape | Échéance |
|---|---|
| Consultation préalable du CERS, de la BCE et du Groupe BEI | **S2 2026 - S1 2027** |
| Identification ou création d'un véhicule législatif | 2027 — **point faible du dossier, voir ci-dessous** |
| Proposition | 2027 |
| Négociation | 2027-2028 |
| Publication | 2028-2029 |
| Premier cycle de déclaration | **2029** |

**Difficulté de calendrier propre à N5 : aucun véhicule porteur n'est identifié.** À la différence des six autres réformes, N5 ne se greffe sur aucun texte déjà en navigation. Trois options :
1. **Amendement au paquet intégration des marchés et supervision** — le plus rapide, mais le rattachement thématique est indirect (ce paquet porte sur la supervision microprudentielle des marchés, non sur le macroprudentiel).
2. **Texte autonome de modification du règlement (UE) n° 1092/2010** — le plus propre juridiquement, le plus lent, et il consomme un créneau d'initiative de la Commission.
3. **Volet d'un futur paquet macroprudentiel**, si la Commission en ouvre un à la suite du rapport BCE-CERS de février 2026 — le plus naturel, mais son existence n'est pas acquise.

**Recommandation :** engager la consultation du CERS dès le S2 2026 **précisément pour faire émerger l'option 3**. Une demande portée par le CERS lui-même, exécutant sa propre recommandation, est un chemin plus court qu'une initiative de la Commission.

## 6. Acteurs institutionnels

- **CERS** : futur opérateur et meilleur porteur politique du dossier.
- **BCE** : coauteur du rapport de février 2026 dont N5 exécute la recommandation.
- **DG FISMA** : véhicule et rédaction.
- **Groupe BEI et FEI** : entités déclarantes — leur accord n'est pas juridiquement requis mais leur opposition rendrait le dispositif inopérant en pratique.
- **Banques nationales de promotion** (KfW, Bpifrance, CDP, ICO et leurs homologues) : entités déclarantes, à consulter tôt.
- **Parlement : ECON. Conseil : ECOFIN.**

**Obstacle politique principal.** La cartographie ne documente **aucune résistance, ni identifiée ni inférée** : c'est un organe de coordination et d'alerte sans effet direct sur aucun intérêt économique cartographié, et le verdict de faisabilité est « praticable, sans réserve ».

**Mais l'obstacle réel n'est pas celui-là, et il est prévisible :** l'obligation de déclaration est **la seule disposition contraignante nouvelle de tout le dispositif**, et elle vise des institutions qui n'ont jamais été soumises à un reporting prudentiel de l'Union. La résistance viendra d'elles, sur le terrain de la charge administrative et du statut institutionnel, non des États membres ni des fédérations professionnelles. **C'est là que se jouera le texte, et c'est pourquoi la consultation du Groupe BEI doit précéder le dépôt, pas le suivre.**

## 7. Impact attendu, chiffré honnêtement

**N5 ne produit aucun financement, et il faut le dire en première ligne de toute présentation.** La base factuelle est explicite sur ce point : les garde-fous macroprudentiels « ne créent pas de financement ; ils **protègent la soutenabilité de tout ce qui précède** » (macro §9, rang 9). Coût budgétaire : **nul** pour l'Union. Confiance sur la nécessité : **élevée** — c'est le seul élément du corpus dont la nécessité soit qualifiée d'élevée dans la base factuelle.

**Ce qui est documenté :** aucun des instruments examinés — ETCI 2, FEC/InvestEU, ELTIF 2.0, LTEI Solvabilité II, titrisation — ne comporte de limite de concentration ni d'obligation de reporting consolidé, alors même que la BCE et le CERS ont identifié en février et mars 2026 l'opacité des marchés privés et la concentration des expositions comme **les vulnérabilités les moins bien mesurées du système**.

**Ce qui n'est pas disponible :** aucun chiffrage de l'exposition agrégée actuelle — c'est précisément l'objet du dispositif. Aucun chiffrage du coût de mise en conformité pour les entités déclarantes ; il devra être estimé avec le Groupe BEI et un échantillon de banques de promotion **avant** le dépôt, faute de quoi l'analyse d'impact sera contestée sur son point le plus sensible.

**Formulation honnête recommandée :** *effet de financement nul par construction ; fonction de condition de soutenabilité et de recevabilité des autres réformes ; l'ampleur du risque qu'il surveille n'est pas mesurée aujourd'hui, ce qui est le motif même du dispositif.*

## 8. Risques résiduels

Le risque dominant est celui d'un dispositif adopté mais vide : si l'obligation de déclaration est affaiblie en négociation, ou si le format harmonisé n'est pas produit, la structure se réunira sans données comparables et deviendra exactement ce que la correction cherchait à éviter. L'absence de véhicule législatif identifié est une fragilité de calendrier réelle, qui peut repousser le dossier de plusieurs années sans qu'aucune opposition de fond ne se soit jamais exprimée. Enfin, un pouvoir d'alerte sans pouvoir d'action peut produire des avertissements répétés et ignorés — limite inhérente au mandat du CERS, assumée ici comme le prix de la proportionnalité.

---

# Partie transversale

## T1. Ce que cette feuille de route ne livre pas

Un document de travail honnête doit dire ce qu'il ne contient pas.

1. **L'essentiel du levier prudentiel est déjà acquis et n'est pas l'œuvre de ces réformes.** Le passage de 49 % à 22 % sur les investissements en actions de long terme est du droit en vigueur, applicable au 30 janvier 2027. Les réformes de cette grappe ajoutent au bord, elles ne créent pas le levier.
2. **Le sous-module « actions d'innovation » à 17 %, qui portait l'essentiel de l'effet annoncé de F5, sort du cycle.** Il exige un acte de niveau 1 et son horizon réaliste est 2031-2033.
3. **Le volet fiscal de F7, qui portait l'essentiel de son effet annoncé, est retiré.** Ce qui reste est un avantage de distribution dont la valeur commerciale n'est pas établie.
4. **F9 est un dossier de la législature suivante**, dépendant d'un texte tiers (EU Inc.) qui n'est pas encore adopté.
5. **Trois des sept réformes n'ont aucun effet de financement chiffrable** : N3 et N5 par construction, F1 parce qu'elle est une condition de faisabilité d'autres instruments plutôt qu'un instrument à effet direct.
6. **La seule réforme au calendrier court, F12, est aussi celle dont l'effet sur les fonds propres de scale-up est de second ordre**, ce que la base factuelle qualifie explicitement.

**Lecture d'ensemble : cette grappe est un travail d'infrastructure réglementaire.** Elle enlève des obstacles, crée des catégories juridiques, produit de la donnée et organise la surveillance. Aucun de ses éléments ne produit à lui seul un effet macroéconomique mesurable dans le cycle CFP 2028-2034. C'est un constat, pas une objection : le levier réglementaire domine le levier budgétaire d'un ordre de grandeur dans ce dossier (compartiment fonds propres/garantie du FEC ~11 Md€ sur sept ans contre 45-50 Md€ de stock pour 0,5 point de réallocation assurance), mais il agit avec un décalage de plusieurs années et par accumulation.

## T2. Les cinq décisions à prendre maintenant

| # | Décision | Échéance | Conséquence du report |
|---|---|---|---|
| 1 | Déposer les amendements F12 au trilogue titrisation, après avis technique du FEI sur le montage inversé | **S2 2026** | Fenêtre perdue jusqu'en 2030+ |
| 2 | Porter les paliers, le plafond de 2 Md€ et le passeport de gestion dans la proposition EuVECA | **T3 2026** | Passage par amendement parlementaire, chemin nettement plus fragile pour un dispositif exigeant une modification concomitante de l'AIFMD |
| 3 | Ouvrir la consultation du CERS, de la BCE et du Groupe BEI sur N5 | **S2 2026** | Aucun véhicule législatif ne se dégagera de lui-même |
| 4 | Commander la demande d'avis technique à EIOPA sur la calibration de l'escalier | **S2 2027** | Décale F5 d'un cycle entier |
| 5 | Décider si N3 est porté par amendement au paquet intégration/supervision ou par texte autonome | **2026** | La voie autonome coûte deux ans |

## T3. Points à vérifier sur EUR-Lex avant toute circulation externe

Cette liste prolonge la réserve du §5 de `current-regulation.md` et le constat D.10 de la vérification indépendante.

1. **Numérotation des articles du règlement délégué (UE) 2015/35** : répartition exacte entre les articles 168, 169, 171 *bis* et 172 des éléments cités (classification type 1/type 2, niveaux de choc, LTEI, ajustement symétrique).
2. **Article 301 *bis* de la directive 2009/138/CE** : durée exacte de la période d'objection aux actes délégués et conditions de prorogation.
3. **Correspondance 26 *bis* à 26 *sexies* du règlement (UE) 2017/2402** : contenu exact de chaque article et, surtout, **rédaction de l'article 6 relative aux formes admises de rétention du risque telle qu'elle ressortira du trilogue en cours** — la conclusion sur la part verticale en dépend directement.
4. **Références du paquet LCB-FT** applicable aux opérateurs de MTF, et date d'application effective.
5. **Règlement (UE) 2023/2631** sur les obligations vertes européennes : vérifier le numéro et le régime exact des vérificateurs externes enregistrés auprès de l'ESMA, invoqué comme modèle pour l'audit indépendant de F7.
6. **Articles 54 à 57 des règlements (UE) n° 1093/2010, 1094/2010 et 1095/2010** : dispositions exactes relatives au comité mixte.
7. **Règlement financier** : toute citation doit viser le **règlement (UE, Euratom) 2024/2509**, le règlement 2018/1046 ayant été abrogé.
8. **Protocole n° 5 et statuts de la BEI** : compatibilité d'une obligation de transmission d'informations à des fins macroprudentielles.
9. **Date exacte de la clause de réexamen de la directive (UE) 2025/2**, qui détermine la fenêtre de niveau 1 pour F5 *bis*.

---

*Fin de la feuille de route — grappe A. Les grappes B (rentabilité) et C (demande) font l'objet de documents distincts.*
