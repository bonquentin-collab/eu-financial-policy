# Jeu de propositions — Financement, rentabilité et demande des startups et scale-ups européennes

**Agent :** policy-innovator
**Date :** 8 août 2026
**Base factuelle :** `current-regulation.md`, `micro-analysis.md`, `macro-analysis.md`, `benchmarking.md`, `stakeholder-map.md`
**Destinataires :** `impact-assessment-auditor` (rigueur réglementaire) puis `stakeholder-mapper` (faisabilité politique)

**Avertissement de méthode.** Ce document propose ; il n'arbitre pas. Plusieurs propositions sont délibérément situées au-delà de ce qui est aujourd'hui négociable, dès lors qu'elles restent greffées sur une base juridique identifiable et sur un point de friction documenté. L'auto-évaluation du risque en fin de chaque fiche est une information transmise aux agents suivants, pas une réserve de l'auteur : aucune proposition n'a été édulcorée pour améliorer sa note de risque.

---

## 0. Logique d'ensemble

La base factuelle converge sur cinq constats que les propositions ci-dessous prennent comme axiomes de conception.

1. **Le levier réglementaire domine le levier budgétaire d'un ordre de grandeur.** Le compartiment fonds propres/garantie du FEC pèse ~11 Md€ sur 409 Md€ (macro §7.4), quand 0,5 point de réallocation des bilans d'assurance représente 45-50 Md€ de stock (macro §3.2(a)). Toute proposition purement budgétaire doit donc justifier pourquoi elle n'a pas d'équivalent réglementaire.
2. **Les seuils, pas les niveaux.** Les points de rupture documentés sont des discontinuités (500 M€ EuVECA, 16,5 M€ RGEC art. 21, 49 %/22 % Solvabilité II, 12 M€/5 M€ prospectus — micro §4.1), pas des insuffisances de calibrage. Une proposition qui déplace un seuil sans supprimer la discontinuité reproduit le problème 300 M€ plus loin.
3. **La vitesse est un paramètre de conception, pas d'exécution** (micro §4.3 : 149 startups en attente à l'EIC Fund ; 332 M€ payés par le Fonds pour l'innovation à juin 2025). Plusieurs propositions ci-dessous remplacent une décision discrétionnaire par une règle automatique — c'est le seul moyen structurel de tenir un délai.
4. **La boucle collecte → sortie → recyclage est fermée du mauvais côté** (macro §0.5, §2.6). Les propositions sur la sortie (F9, F10, F14) ne sont pas un complément : elles sont la condition d'efficacité des propositions sur l'entrée.
5. **L'appariement domine l'abondance.** La BCE documente que les entreprises européennes non financées par du VC sont plus grandes et croissent plus vite que leurs homologues américaines (macro §0.1, §10.1). Le problème est un défaut d'appariement entre ~10 000 Md€ d'épargne et une demande de capital de qualité — pas une pénurie de projets. Plusieurs propositions attaquent donc le canal de distribution (F7, F8, F9) plutôt que le stock de capital public.

**Arbitrage juridique transversal.** Trois des mesures à effet le plus élevé relèvent de la fiscalité directe (art. 115 TFUE, unanimité) : stock-options, plus-values de l'investisseur, biais dette/fonds propres. Trois techniques de contournement sont utilisées systématiquement dans ce document et doivent être testées comme telles par l'auditeur :
- **la substitution budgétaire** (F3, R3) : produire l'effet d'un crédit d'impôt remboursable par un versement du budget de l'Union sous l'article 173 TFUE (majorité qualifiée, et hors champ des aides d'État puisqu'il s'agit de fonds de l'Union en gestion directe) ;
- **la conditionnalité de bénéfice** (F7) : ne pas imposer une allocation, mais conditionner l'accès à un avantage européen (label, passeport, garantie) à cette allocation ;
- **la coopération renforcée** (F2, R1, R2) : articles 20 TUE et 326-334 TFUE, minimum neuf États membres, explicitement prévue comme voie de repli lorsque l'unanimité est hors d'atteinte.

**Carte des dépendances (à lire avant d'évaluer une proposition isolément).**

| Proposition | Préalable logique | Conséquence si le préalable manque |
|---|---|---|
| F4 (option de rachat), F11-F13 (budget) | F5-F7 (déblocage LP institutionnels) | Le fonds de fonds public finance des appels de fonds qui ne trouvent pas de co-souscripteurs (micro, réserve sur R10) |
| F1 (EuVGF) | F2 (transparence fiscale) | Le passeport reste juridiquement unifié et fiscalement fragmenté — cause identifiée du taux d'adoption de 29 % (macro §3.2(c)) |
| F5-F8 (mobilisation de l'épargne) | F9, F10, F14 (sortie) | Inflation des valorisations privées et allongement des durées de détention, pas d'approfondissement (macro §3.2(b)) |
| Tout l'axe 1 | D1-D3 (demande) | Le capital finance des entreprises sans carnet de commandes ; le déficit de sortie se reforme en aval |
| Ensemble | F11 + garde-fous macroprudentiels | Concentration corrélée non traitée (macro §6.3) — risque de rejet par le CERS/la BCE |

---

# AXE 1 — ACCÈS AU FINANCEMENT

## F1. Règlement EuVGF : remplacer EuVECA/EuSEF par un continuum réglementaire de 0 à 5 Md€ avec passeport de gestion

**Problème visé.** Le seuil de 500 M€ d'actifs sous gestion est qualifié d'« effet de falaise » par la Commission elle-même (consultation du 15 janvier au 12 mars 2026 ; `current-regulation` §1.3, micro §3.1 mécanique n°3). Il est posé exactement au niveau de l'écart de financement Series B-C, et produit trois comportements documentés : plafonnement volontaire du fonds, segmentation en véhicules jumeaux, ou saut réglementaire complet (micro §3.1). S'y ajoute un échec d'adoption : 29 % seulement des 704 fonds VC de l'UE utilisent EuVECA, usage minoritaire en France et en Espagne, 2 % pour EuSEF (macro §2.4). Le passeport ne couvre que la **commercialisation**, pas la **gestion** (`current-regulation` §1.3).

**Mécanisme.** Abrogation des règlements (UE) 345/2013 et 346/2013 et adoption d'un règlement unique **EuVGF** (*European Venture and Growth Fund*), sur la base de l'article 114 TFUE, structuré non par seuil mais par **paliers cumulatifs d'obligations** :

| Actifs sous gestion du gestionnaire | Régime applicable |
|---|---|
| < 500 M€ | Enregistrement, règles de conduite, reporting annuel simplifié. Aucune obligation AIFMD. |
| 500 M€ – 1,5 Md€ | + dépositaire allégé au sens de l'article 21(3) de la directive AIFMD (dépositaire non bancaire admis pour les actifs non conservables), + fonds propres réglementaires calculés sur les seules commissions de gestion. **Exemption expresse** des exigences de gestion du risque de liquidité (sans objet pour un véhicule fermé non levierisé) et de la politique de rémunération. |
| 1,5 – 5 Md€ | + reporting Annexe IV complet, + fonction permanente de gestion des risques. Toujours pas d'exigence de liquidité. |
| > 5 Md€ | AIFMD de droit commun. |

Trois éléments complémentaires, chacun traitant une cause documentée de non-adoption :
- **Passeport de gestion** : un gestionnaire EuVGF agréé dans son État membre d'origine peut gérer un fonds établi dans tout autre État membre sans établissement local ni agrément additionnel (aligné sur le régime OPCVM, article 16 de la directive 2009/65/CE).
- **Période de grâce de 36 mois** après franchissement d'un palier, avec application progressive palier par palier — la falaise devient une pente.
- **Élargissement des actifs éligibles** : dette de croissance (*venture debt*) avec BSA attachés, instruments convertibles, secondaires de portefeuilles de fonds VC européens, et parts d'autres EuVGF (structures nourricières), afin de couvrir les tours tardifs aujourd'hui exclus (macro §3.2(c)).

**Cadres connectés.** Directive AIFMD 2011/61/UE (art. 3, 21(3), Annexe IV) ; règlements 345/2013 et 346/2013 (abrogés) ; règlement ELTIF (UE) 2015/760 tel que modifié par 2023/606 — les parts d'EuVGF sont ajoutées à la liste des actifs éligibles d'un ELTIF ; règlement délégué Solvabilité II (UE) 2015/35 art. 171a — les EuVGF fermés non levierisés bénéficient de l'appréciation au niveau du fonds sans transparisation, par renvoi croisé explicite ; véhicule législatif : la proposition EuVECA annoncée pour le T3 2026.

**Effet attendu.** *Micro* : supprime la contrainte de construction de portefeuille décrite en micro §2.2 — un fonds de 800 M€ à 1,2 Md€ devient administrativement viable, ce qui porte le ticket initial de ~4 M€ à ~15-20 M€ et permet de mener un tour de Series B sans syndication à six signataires. *Macro* : traite un échec d'adoption plutôt qu'un paramètre (macro §3.2(c)) ; condition de faisabilité des véhicules de 300 M€ à 1 Md€ qu'ETCI 2.0 cherche précisément à financer — sans quoi l'instrument budgétaire et le régime de fonds s'annulent mutuellement.

**Risque anticipé : faible à moyen** — la direction est déjà celle de la consultation de la Commission ; le passeport de gestion et l'exemption de liquidité seront contestés par les superviseurs nationaux et par les États membres dont l'attractivité repose sur l'obligation d'établissement local (Luxembourg, Irlande — cf. `stakeholder-map` §3.3).

---

## F2. Transparence fiscale de plein droit des fonds EuVGF, par coopération renforcée si nécessaire

**Problème visé.** Macro §3.2(c) identifie « l'absence d'harmonisation fiscale de la transparence des véhicules » comme cause structurelle de la non-adoption d'EuVECA, et micro §4.4 documente l'arbitrage de domiciliation du gérant (Luxembourg, Irlande, Pays-Bas contre France, Allemagne, Italie) fondé sur le traitement du *carried interest* et de la transparence. Un investisseur institutionnel qui souscrit à un fonds établi dans un autre État membre subit un risque de double imposition ou de retenue à la source non récupérable qu'il ne subit pas sur un fonds domestique — ce qui explique que le réseau LP transfrontalier soit quasi inexistant hors du triangle luxembourgeois (macro §2.4). C'est la raison pour laquelle un régime juridiquement passeporté reste économiquement national.

**Mécanisme.** Directive sur le fondement de l'article 115 TFUE posant trois règles, sans harmoniser aucun taux :
1. **Transparence obligatoire** : tout fonds enregistré EuVGF est réputé fiscalement transparent dans l'ensemble des États membres ; l'imposition intervient au seul niveau du porteur de parts, selon le droit de sa résidence.
2. **Exonération de retenue à la source** à l'entrée et à la sortie du véhicule pour les distributions transitant par un EuVGF, sur le modèle et par renvoi aux procédures de la directive FASTER (attestation de résidence numérique, remboursement rapide).
3. **Reconnaissance mutuelle du traitement du *carried interest*** : la qualification retenue par l'État membre d'origine du gestionnaire s'impose aux autres États membres pour la part de plus-value attribuée aux personnes physiques de l'équipe de gestion, dans la limite d'un intéressement de 20 % au-delà d'un taux de rendement préférentiel de 8 %.

**Voie de repli assumée.** L'unanimité de l'article 115 TFUE étant improbable, la proposition prévoit dès l'origine son propre repli : engagement d'une **coopération renforcée** (article 20 TUE, articles 326-334 TFUE) entre au moins neuf États membres, avec clause d'adhésion ouverte. Un régime de transparence fiscale couvrant l'Allemagne, la France, les Pays-Bas, l'Espagne, l'Italie, la Suède, la Finlande, l'Irlande et le Luxembourg couvrirait déjà l'essentiel de la base LP européenne. Le coût pour un non-participant serait une exclusion de fait du réseau LP transfrontalier — ce qui crée une incitation dynamique à l'adhésion, mécanisme absent de toute la stratégie SIU actuelle.

**Cadres connectés.** F1 (règlement EuVGF, dont ceci est le volet fiscal indissociable) ; directive FASTER (procédures d'attestation et de remboursement de retenue à la source) ; ATAD 1 et 2 pour les clauses anti-abus (dispositif hybride, condition de substance minimale du gestionnaire : au moins deux dirigeants effectifs et trois professionnels d'investissement résidents) ; benchmarking §2 (ESVCLP australien, *flow-through* labellisé, et régime VCFI singapourien).

**Effet attendu.** *Micro* : supprime la prime de domiciliation qui pousse aujourd'hui les gérants vers trois juridictions et qui alourdit les frais de structure supportés par les LP (micro §4.4). *Macro* : attaque directement la cause la plus tangible de la fragmentation du réseau LP — identifiée par la BCE comme la contrainte la plus forte sur la constitution de fonds de 300 M€ à 1 Md€ (macro §3.2(c)).

**Risque anticipé : élevé** — unanimité fiscale hors d'atteinte ; la voie de coopération renforcée sera présentée par ses opposants comme une fragmentation supplémentaire du marché unique, argument sérieux qu'il faudra affronter frontalement.

---

## F3. Guichet miroir : co-investissement public automatique, sans comité, décidé par le silence

**Problème visé.** La sélection adverse par la lenteur est documentée : un instrument public plus lent que le marché sélectionne les dossiers sans alternative (micro §4.3 ; 149 startups en attente à l'EIC Fund, retards qualifiés de « revers majeur » par son propre conseil). Micro §4.3 en tire la règle : « un engagement de 5 Md€ décidé en 9 mois vaut moins qu'un engagement de 2 Md€ décidé en 6 semaines ». Les remèdes envisagés dans la base factuelle (délais maximaux d'instruction, externalisation à un gérant privé) traitent le symptôme sans supprimer la décision discrétionnaire qui en est la cause.

**Mécanisme.** Créer dans le règlement FEC un **guichet miroir** (*mirror window*) fonctionnant par règle et non par sélection :
- **Accréditation des chefs de file, non des dossiers.** Un investisseur est accrédité pour trois ans s'il satisfait des critères objectifs et vérifiables : au moins 150 M€ d'actifs sous gestion, établi dans l'UE ou l'EEE, au moins cinq ans d'historique, au moins dix opérations de premier tour réalisées, absence de sanction réglementaire. Liste publique.
- **Déclenchement automatique.** Pour tout tour de table d'au moins 15 M€ mené par un chef de file accrédité dans une entreprise éligible (siège de direction effective dans l'UE, moins de 15 ans, moins de 3 000 salariés), le FEC co-investit **jusqu'à 30 % du tour, strictement *pari passu***, sur simple notification du chef de file accompagnée du *term sheet* signé.
- **Décision par silence.** L'instrument dispose de **quinze jours ouvrables** pour opposer un refus motivé, limité à trois motifs limitativement énumérés (non-respect d'un critère d'éligibilité, sanctions internationales, dépassement de plafond). À défaut de réponse, l'engagement est réputé accordé et exécutoire.
- **Plafonds.** 100 M€ par entreprise sur sa durée de vie ; 400 M€ par chef de file et par an ; enveloppe annuelle de 4 Md€.
- **Anti-abus.** Clause de récupération intégrale si le chef de file cède sa participation dans les 24 mois ; retrait d'accréditation en cas de récupération activée deux fois ; interdiction de co-investir dans une société où le chef de file détenait déjà plus de 25 % avant le tour.

**Cadres connectés.** Règlement FEC COM(2025) 555 final (nouvel article dans le compartiment financier) ; RGEC article 21 — la structure satisfait par construction toutes les exigences de participation privée (70 % minimum), ce qui rend l'instrument compatible sans notification, et permet de proposer **en miroir** que le barème 10 %/40 %/60 % soit réputé satisfait pour tout co-investissement *pari passu* ; règlement financier (recettes affectées externes, pour le recyclage des produits de cession) ; benchmarking §2 (co-investissement direct SEEDs Capital/SGInnovate, Singapour) et §5.4 (prise de risque directe en capital par véhicule souverain, architecture que l'UE n'a pas explorée).

**Effet attendu.** *Micro* : transforme l'argent public de « option sans valeur pour un fondateur en levée compétitive » (micro §2.4) en source de capital utilisable dans le calendrier réel d'une transaction. Épaissit la queue droite de la distribution — objectif explicite de micro §1.3 — puisque le mécanisme s'applique en proportion et non en montant fixe. *Macro* : externalise la sélection au marché, ce qui supprime le risque de substitution de la logique de mérite par une logique d'allocation géographique identifié comme particulièrement destructeur pour le VC (macro §7.4.2) ; réduit la centralité du FEI comme certificateur de fait (micro §3.2) en démultipliant les certificateurs accrédités.

**Risque anticipé : élevé** — l'absence de comité d'investissement et la décision par silence heurtent frontalement la culture de contrôle financier de la Commission et de la Cour des comptes européenne ; le Conseil, qui a renforcé le rôle des États membres dans la fixation des priorités à tous les stades (macro §7.4), y verra une perte de contrôle politique.

---

## F4. Instrument d'amorçage à option de rachat : Yozma adapté aux investisseurs institutionnels européens

**Problème visé.** Le benchmarking (§2, §5.3) identifie dans le programme israélien Yozma un ressort absent de l'architecture InvestEU/FEI : une option de rachat de la participation publique à prix préférentiel, qui désamorce le risque perçu par les investisseurs privés d'entrer sur un marché jugé peu profond. Le problème européen n'est cependant pas le même qu'en Israël en 1993 : l'Europe ne manque pas de gestionnaires, elle manque de **souscripteurs institutionnels** (macro §2.2 : entités publiques ≈ 1/3 des LP contre 4 % aux États-Unis ; substitution public/privé « presque parfaite »). Une transplantation directe du dispositif israélien, qui donne l'option aux gestionnaires, raterait la cible.

**Mécanisme.** Créer dans le compartiment fonds propres du FEC un **Instrument d'amorçage à option de rachat (IAOR)** :
- Le Groupe BEI souscrit jusqu'à **40 % des engagements** d'un fonds EuVGF de première ou deuxième génération, en qualité de LP d'ancrage, aux mêmes conditions économiques que les autres LP.
- **L'option de rachat est attribuée aux LP privés du même fonds, et non au gestionnaire** — c'est l'adaptation centrale. Chaque LP privé reçoit, au prorata de son engagement, une option d'achat sur la participation publique, exerçable entre la fin de la cinquième et la fin de la huitième année, au prix de revient majoré d'un rendement fixe de 5 % par an capitalisé, sans participation à la plus-value au-delà.
- **Conséquence économique** : le LP institutionnel qui entre pour la première fois dans la classe d'actifs achète en réalité une exposition à effet de levier plafonné à la baisse par le comportement d'ancrage public et démultipliée à la hausse par l'option. Le péage prudentiel décrit en micro §3.1 (5-6 points de rendement annuel exigés en plus) devient franchissable sans modification du régime prudentiel lui-même.
- **Symétrie budgétaire** : le produit d'exercice constitue une recette affectée externe, réinjectée de plein droit dans l'IAOR — le dispositif devient partiellement autofinancé après huit ans.
- **Conditionnalité de localisation agrégée** (reprise de macro §9, rang 7) : l'option n'est exerçable que si, à la date d'exercice, au moins 70 % du montant investi par le fonds l'a été dans des entreprises dont le siège de direction effective est dans l'UE — conditionnalité posée **au niveau du portefeuille agrégé** et non ligne par ligne, pour ne pas casser la logique de diversification.

**Cadres connectés.** Règlement FEC (compartiment fonds propres) ; ETCI 2.0 et Scaleup Europe Fund, dont l'IAOR est le complément d'amorçage de la base LP ; RGEC article 21(13) sur le partage asymétrique des risques et des rendements entre investisseurs publics et privés, qui fournit la base d'exemption ; règlement financier pour l'affectation des recettes ; benchmarking §5.3 (Yozma 2.0) et §2 (*Institutional Investors Incentive Program* israélien : 450 M$ engagés ayant généré plus de 2 Md$ de levées auprès de 18 investisseurs institutionnels).

**Effet attendu.** *Micro* : le premier engagement d'un assureur ou d'un fonds de pension dans la classe d'actifs est le plus difficile ; l'option en réduit le coût d'opportunité perçu au point de le rendre défendable devant un comité d'investissement. *Macro* : traite la substitution public/privé plutôt que de l'aggraver — c'est le seul instrument du corpus qui **réduit** structurellement la part publique des LP au lieu de l'augmenter, en organisant sa propre sortie.

**Risque anticipé : moyen à élevé** — la Cour des comptes européenne et les États membres contributeurs nets contesteront un dispositif qui plafonne volontairement le rendement du budget de l'Union et transfère la plus-value aux investisseurs privés ; l'argument de contrepartie (le budget achète une base LP permanente, pas un rendement) devra être quantifié.

---

## F5. Escalier de charge Solvabilité II et sous-module dédié « actions d'innovation européennes » à 17 %

**Problème visé.** Micro §4.1 documente la discontinuité binaire : soit l'actif est éligible LTEI et coûte 22 %, soit il coûte 49 % + ajustement symétrique (bornes élargies à ±13 %), sans aucune gradation selon la durée de détention effective — ce qui « incite à des montages d'éligibilité plutôt qu'à une détention longue authentique ». Micro §3.1 anticipe une adoption concentrée sur les grands assureurs vie dotés d'équipes ALM sophistiquées, et faible chez les acteurs moyens : le bénéfice de la réforme applicable au 30 janvier 2027 se concentrerait sur quelques dizaines de bilans. Enfin, macro §3.2(b) relève une incohérence de sens opposé : rien d'équivalent au LTEI n'existe pour les **actions cotées** de croissance européennes, si bien que le régime prudentiel crée une incitation à rester privé, à rebours de l'objectif de relance des IPO.

**Mécanisme.** Modification du règlement délégué (UE) 2015/35 (articles 168 et 171a) en trois volets :

1. **Escalier continu, en remplacement du couple 49 %/22 %.** La charge du sous-module actions de type 2 devient fonction de l'horizon de détention documenté :

| Horizon documenté de détention | Charge de capital |
|---|---|
| < 2 ans | 49 % + ajustement symétrique (inchangé) |
| 2 à 3 ans | 39 % + ajustement symétrique |
| 3 à 5 ans | 30 %, ajustement symétrique réduit de moitié |
| ≥ 5 ans (critères LTEI) | 22 %, sans ajustement symétrique (inchangé) |

Cette gradation supprime la prime au montage formel : un assureur qui détient réellement trois ans est traité mieux qu'un assureur qui documente cinq ans sans les tenir.

2. **Sous-module « actions d'innovation européennes » à 17 %.** Création d'une catégorie d'actifs distincte, cotée ou non cotée, réunissant : entreprises établies dans l'UE, de moins de quinze ans, dont au moins deux tiers des effectifs et des actifs incorporels sont situés dans l'UE ; parts d'EuVGF et d'ELTIF satisfaisant la même condition au niveau agrégé du portefeuille ; **et actions cotées sur un marché réglementé ou un marché de croissance des PME de l'UE d'émetteurs de moins de 5 Md€ de capitalisation cotés depuis moins de sept ans** — cette dernière branche est essentielle : elle supprime l'asymétrie qui pénalise la cotation. Conditions : engagement de non-vente forcée sur dix ans, plafonnement de l'exposition à 5 % des actifs totaux de l'entreprise d'assurance, appréciation au niveau du fonds sans transparisation intégrale (extension de la logique déjà retenue en 2026 pour les AIF fermés non levierisés et les ELTIF).

3. **Orientation EIOPA de niveau 3 avec cas chiffrés** de démonstration de capacité de détention, pour supprimer la divergence d'interprétation entre superviseurs nationaux — identifiée en micro §3.1 comme premier frein pratique, devant le taux lui-même.

**Cadres connectés.** Directive Solvabilité II 2009/138/CE telle que modifiée par la directive (UE) 2025/2 ; règlement délégué (UE) 2015/35, art. 168 et 171a ; règlement délégué de 2026 applicable au 30 janvier 2027 ; ELTIF 2.0 et EuVGF (F1) par renvoi croisé d'éligibilité ; Listing Act (directive 2024/2810 sur les actions à droits de vote multiples et règlement 2024/2809) pour la branche cotée ; F6 ci-après, dont ce sous-module est le support.

**Effet attendu.** *Micro* : ramène le péage prudentiel d'environ 5-6 points de rendement annuel à moins de 2 points sur la catégorie ciblée, ce qui fait entrer les fonds VC/growth dans l'univers investissable d'un comité d'investissement d'assureur moyen — population aujourd'hui exclue de fait. *Macro* : chaque 0,1 point de réallocation du portefeuille agrégé des assureurs européens (~9 000-10 000 Md€) représente 9-10 Md€ de stock, soit six ans de la composante InvestEU du FEC (macro §3.2(a)). La branche cotée corrige l'incitation prudentielle à rester privé, qui est aujourd'hui l'un des mécanismes silencieux du blocage à la sortie.

**Risque anticipé : élevé** — EIOPA et le CERS opposeront que le régime LTEI échange déjà un amortisseur contracyclique (l'ajustement symétrique) contre une incitation structurelle à l'illiquide, et qu'un sous-module à 17 % accentue cet arbitrage (macro §6.2(2)) ; la réponse doit être le plafond de 5 % du bilan et le suivi EIOPA dédié, à assumer explicitement.

---

## F6. Garantie budgétaire adossée à la charge prudentielle : convertir un euro de budget en points de SCR

**Problème visé.** Deux constats de la base factuelle ne sont jamais reliés. D'un côté, la garantie budgétaire de l'Union est utilisée pour réduire le **risque économique** d'un investissement, avec un multiplicateur affiché de 15,2× que la Cour des comptes européenne juge surestimé d'environ 26 % (macro §7.4.3). De l'autre, l'obstacle documenté à l'entrée des assureurs n'est pas le risque économique mais la **charge en capital réglementaire** (micro §3.1). Autrement dit, le budget de l'Union achète aujourd'hui la mauvaise variable.

**Mécanisme.** Créer dans le FEC une **facilité de rehaussement prudentiel** :
- Le FEC émet, au bénéfice d'une entreprise d'assurance ou d'un IORP, une garantie couvrant **les 10 premiers pour cent de perte** sur un portefeuille identifié d'actifs relevant du sous-module « actions d'innovation européennes » (F5), dans la limite de 500 M€ de portefeuille par entité et de 15 Md€ d'encours garanti total.
- **Contrepartie réglementaire, inscrite dans le règlement délégué (UE) 2015/35** : la charge de capital applicable au portefeuille garanti est ramenée à **10 %**, l'atténuation étant justifiée actuariellement par la technique d'atténuation du risque (article 101(5) de la directive 2009/138/CE et articles 208 à 215 du règlement délégué relatifs aux techniques d'atténuation), et non par une décision politique — point décisif pour la recevabilité devant EIOPA.
- **Tarification** : la garantie est payante, à une prime calibrée sur la perte attendue historique du portefeuille de référence, majorée de 20 %. Le dispositif est donc conçu pour être budgétairement neutre à long terme, et sa provision peut être fixée à 25 % (cf. F11).
- **Extinction programmée** : la facilité est fermée aux nouvelles souscriptions après sept ans, et chaque garantie est amortie linéairement à partir de la cinquième année — l'objectif est d'amorcer une allocation, pas de la subventionner indéfiniment.

**Effet de levier.** À une provision de 25 % sur 15 Md€ de garantie, soit 3,75 Md€ de crédits budgétaires immobilisés, le dispositif fait passer de 49 % (ou 22 %) à 10 % la charge sur jusqu'à 150 Md€ de portefeuille d'actifs d'innovation européens. Rapporté aux 45-50 Md€ de stock qu'une réallocation de 0,5 point représenterait (macro §3.2(a)), c'est un levier réglementaire par euro budgétaire sans équivalent dans le corpus examiné — et il est mesurable, contrairement au multiplicateur d'investissement mobilisé.

**Cadres connectés.** Règlement FEC (nouvelle catégorie de garantie budgétaire) ; règlement délégué Solvabilité II art. 101(5) et 208-215 (atténuation du risque) ; F5 (définition du portefeuille éligible) ; directive IORP II art. 19 pour l'extension aux fonds de retraite professionnelle ; règlement financier (provisionnement des passifs éventuels) ; benchmarking §5.4 (prise de risque publique directe) — la présente proposition en constitue une variante indirecte, moins intrusive et à effet de levier supérieur.

**Effet attendu.** *Micro* : supprime l'obstacle du comité d'investissement d'assureur moyen là où F5 ne fait que le réduire ; le portefeuille garanti devient comparable en coût de capital à une obligation d'entreprise notée investissement. *Macro* : c'est le seul mécanisme identifié qui convertit directement du budget en capacité de bilan privé, plutôt qu'en investissement mobilisé — indicateur que la Cour des comptes européenne juge non fiable (macro §7.4.3).

**Risque anticipé : élevé** — nouveauté conceptuelle (une garantie publique utilisée comme collatéral prudentiel), risque d'aléa moral, et opposition prévisible d'EIOPA et de la BCE au motif que le budget de l'Union subventionnerait une sous-évaluation du risque dans les bilans d'assurance ; la tarification actuarielle de la prime est le point de défense central.

---

## F7. Label « Épargne Productive Européenne » : conditionner l'avantage fiscal plutôt qu'imposer l'allocation

**Problème visé.** L'écart d'allocation est le plus gros gisement identifié : 0,01 % des actifs des fonds de pension de l'UE en VC contre 0,03 % aux États-Unis, ~210 Md$ supplémentaires sur dix ans en cas d'alignement (micro §3.1), et 4 % seulement de la poche « fonds d'investissement » des IORP en FIA (macro §2.2). Mais l'obligation d'allocation contraignante est frontalement rejetée : les fédérations de fonds de pension italiennes et allemandes s'opposent explicitement au seuil de 2 % proposé en révision d'IORP II, au nom des principes de prudence et de diversification (`stakeholder-map` §7.3, friction n°5), et Insurance Europe conditionne son soutien à l'absence d'obligation d'allocation (§1.7).

**Mécanisme.** Ne pas imposer une allocation : conditionner l'accès à un avantage européen à cette allocation. Règlement créant un **label « Épargne Productive Européenne » (EPE)**, sur la base de l'article 114 TFUE :
- **Définition du label.** Un produit d'épargne (compte d'épargne et d'investissement au sens de la recommandation SIA du T3 2025, PEPP, unité de compte d'assurance vie, plan d'épargne d'entreprise) obtient le label EPE si **au moins 10 % de ses encours** sont investis en actifs productifs européens de long terme, définis par renvoi croisé à l'article 10 du règlement ELTIF (actifs éligibles) **et** aux parts d'EuVGF (F1), avec la condition de localisation agrégée de 70 % dans l'UE.
- **Effet du label.** Deux conséquences, l'une européenne, l'autre nationale :
  - européenne, immédiatement contraignante : seuls les produits labellisés peuvent être commercialisés sous une dénomination faisant référence à l'Europe, bénéficient du passeport de distribution simplifié prévu par le paquet SIU, et sont éligibles à l'option par défaut d'un dispositif d'affiliation automatique ;
  - nationale, incitative : recommandation formelle aux États membres de réserver aux seuls produits labellisés EPE les avantages fiscaux attachés aux comptes d'épargne et d'investissement, avec obligation de publier annuellement le coût fiscal du régime et sa contrepartie mesurée en encours d'actifs productifs européens.
- **Volet IORP, « se conformer ou s'expliquer ».** Modification de l'article 19 de la directive (UE) 2016/2341 : tout IORP gérant plus de 1 Md€ publie annuellement son allocation aux actifs productifs européens de long terme et, si celle-ci est inférieure à 3 %, une explication motivée approuvée par son organe de direction, communiquée aux affiliés et transmise à EIOPA, qui publie un tableau comparatif européen. **Aucune obligation d'allouer** — une obligation de s'expliquer publiquement. Complément indispensable : clarification expresse, dans le même article, que le principe de la personne prudente **n'interdit pas** une allocation diversifiée aux fonds VC/growth, et publication par EIOPA d'une méthode standardisée de valorisation des positions non cotées pour les régimes à cotisations définies (micro §3.1, mécanique n°2).

**Cadres connectés.** Recommandation de la Commission sur les comptes d'épargne et d'investissement (T3 2025) ; règlement PEPP (UE) 2019/1238 ; directive IORP II (UE) 2016/2341, art. 19 ; règlement ELTIF 2015/760 modifié, art. 10 ; F1 (EuVGF) ; stratégie SIU et sa revue à mi-parcours du T2 2027, qui fournit le véhicule ; benchmarking §5.5 (LTAF britannique rendu éligible aux ISA en avril 2026) et §2 (Mansion House Accord — dont l'écart documenté entre engagement politique et déploiement réel justifie précisément de préférer une conditionnalité juridique à un engagement volontaire).

**Effet attendu.** *Micro* : crée une demande institutionnelle stable pour les parts d'EuVGF et d'ELTIF, ce qui allonge l'horizon de collecte des GP et réduit leur dépendance au FEI comme certificateur (micro §3.2). *Macro* : traite le « problème de dénominateur » identifié en macro §3.2(a) sans obligation d'allocation, donc sans heurter frontalement la ligne de fracture n°5 de la cartographie ; le canal de distribution devient le levier, conformément au constat que l'appariement domine l'abondance (macro §10.1).

**Risque anticipé : élevé** — la conditionnalité du bénéfice fiscal empiète en pratique sur la compétence fiscale nationale même si elle ne l'atteint pas juridiquement ; BEUC et Finance Watch objecteront qu'on oriente l'épargne des ménages vers des actifs illiquides et opaques (`stakeholder-map` §6, friction n°10), objection sérieuse à laquelle seuls les garde-fous de liquidité obligatoires (cf. §4 infra) apportent une réponse.

---

## F8. PEPP-EU Inc. : une retraite paneuropéenne à affiliation par défaut greffée sur le 28e régime

**Problème visé.** La base LP européenne manque d'un investisseur institutionnel de long terme d'origine véritablement paneuropéenne : les fonds de pension relèvent de 27 systèmes nationaux, l'engagement moyen y est de 198 M€ contre 291 M$ aux États-Unis, et l'allocation VC de 0,01 % (macro §2.2). Le PEPP existe mais n'a pas décollé. Or toute tentative d'imposer un régime de retraite européen bute sur l'article 153(4) TFUE et sur la compétence des États membres en matière de sécurité sociale — obstacle réputé rédhibitoire.

**Mécanisme.** Contourner l'obstacle par la greffe : rendre le régime optionnel **au niveau de l'entreprise**, en l'attachant à une forme sociale elle-même optionnelle.
- Insertion, dans le règlement EU Inc. (COM(2026) 321 final), d'un chapitre créant l'**Épargne Retraite EU Inc.** : toute société adoptant la forme EU Inc. affilie automatiquement ses salariés à un plan d'épargne retraite paneuropéen, sous forme de PEPP d'entreprise, sauf renonciation individuelle expresse du salarié (*opt-out*), avec un taux de cotisation par défaut de 4 % du salaire brut, dont au moins un tiers à la charge de l'employeur.
- **Portabilité intégrale** entre États membres et entre employeurs, adossée au Portefeuille européen des entreprises et au portefeuille européen d'identité — c'est l'argument décisif pour un salarié de scale-up mobile, population aujourd'hui pénalisée par la non-portabilité des droits.
- **Option par défaut réglementée** : fonds à horizon (cycle de vie) obligatoirement labellisé EPE (F7), avec une allocation minimale de **12 %** aux actifs productifs européens de long terme pour les cohortes à plus de vingt ans de l'échéance, décroissant linéairement ensuite. Le mandat d'allocation est inscrit dans le règlement, pas laissé au gestionnaire.
- **Neutralité vis-à-vis des régimes nationaux** : le dispositif est expressément supplémentaire, sans effet sur les cotisations légales, et sans dispense d'affiliation aux régimes obligatoires nationaux — condition de recevabilité au regard de l'article 153(4) TFUE.
- **Contrepartie sociale, à porter dès l'origine** : le chapitre est présenté conjointement avec l'obligation, pour toute EU Inc. de plus de 50 salariés, d'un dispositif d'information-consultation conforme à la directive 2002/14/CE. Le rejet syndical du 28e régime est documenté et frontal (`stakeholder-map` §7.1) ; une proposition qui ajoute un droit social plutôt qu'elle n'en soustrait est la seule version défendable.

**Cadres connectés.** Règlement PEPP (UE) 2019/1238 (dont ceci est de fait la refonte utile) ; proposition EU Inc. COM(2026) 321 final, art. 114 TFUE ; directive IORP II ; F7 (label EPE) ; règlement sur le Portefeuille européen des entreprises (proposé en novembre 2025) ; benchmarking §2 (Mansion House Accord : 17 régimes DC, cible de 10 % en marchés privés — mais engagement volontaire, dont l'échec relatif de déploiement est documenté).

**Effet attendu.** *Micro* : crée un investisseur de long terme dont le passif est par construction paneuropéen et non adossé à un marché national, donc structurellement disposé à souscrire des fonds transfrontaliers — ce que le réseau LP actuel, quasi inexistant hors triangle luxembourgeois, ne permet pas (macro §2.4). *Macro* : constitue la seule proposition du jeu qui crée un **stock nouveau** d'épargne longue plutôt que de réallouer un stock existant. Ordre de grandeur : à 4 % de cotisation sur une masse salariale couverte de 100 Md€, environ 4 Md€ de flux annuel, dont ~480 M€ fléchés vers les actifs productifs européens — modeste au départ, mais cumulatif et croissant avec l'adoption d'EU Inc.

**Risque anticipé : extrême** — accusation immédiate de contournement des systèmes nationaux de retraite et du dialogue social, dans un dossier (le 28e régime) déjà sous tension syndicale forte ; contestation probable de la base juridique, l'article 114 TFUE étant difficile à mobiliser pour un dispositif touchant à la protection sociale complémentaire.

---

## F9. Plateformes européennes de liquidité d'entreprise : créer le marché secondaire pré-IPO qui manque

**Problème visé.** Micro §3.3 et R6 identifient l'absence de marché secondaire profond comme un **coût opérationnel réel**, et non un simple manque de liquidité : les salariés ne peuvent pas monétiser leurs instruments, ce qui dégrade l'attractivité des stock-options, augmente la part de rémunération en numéraire, dégrade la trésorerie et raccourcit la piste. Micro §2.3 en fait l'une des micro-incitations du « flip » vers le Delaware. Le benchmarking (§2) chiffre le marché américain des secondaires privés à plus de 120 Md$ en 2025, contre un marché européen resté bilatéral et notarial. Micro §5.1 signale que cette proposition est absente des textes en discussion.

**Mécanisme.** Règlement créant une catégorie d'infrastructure de marché : la **plateforme européenne de liquidité d'entreprise (PELE)**, agréée par l'ESMA.
- **Fonctionnement par enchères périodiques** : fixation de prix à intervalles trimestriels au maximum, jamais en continu — choix délibéré, qui évite d'assimiler le dispositif à un marché réglementé et limite les effets de signal sur la valorisation.
- **Périmètre.** Titres de sociétés non cotées établies dans l'UE, de moins de vingt ans, ayant levé au moins 20 M€ en fonds propres, sur décision d'ouverture de l'organe de direction de l'émetteur (adhésion volontaire de l'émetteur, sans laquelle rien ne se négocie).
- **Acheteurs éligibles** : investisseurs professionnels, ELTIF, EuVGF, entreprises d'assurance et IORP, ainsi que les salariés et anciens salariés de l'émetteur.
- **Régime d'information proportionné** : dossier standardisé obligatoire (comptes audités des deux derniers exercices, synthèse de la table de capitalisation, préférences de liquidation, valorisation de la dernière opération primaire, résumé des engagements hors bilan), publié quinze jours avant chaque fenêtre aux seuls participants. **Exemption expresse de prospectus** par insertion d'un point au paragraphe 4 de l'article 1er du règlement (UE) 2017/1129 pour les cessions opérées sur une PELE en deçà de 50 M€ par fenêtre et par émetteur.
- **Abus de marché adapté** : application des seules interdictions d'opération d'initié et de manipulation du règlement (UE) n° 596/2014, à l'exclusion des obligations de publication périodique et de listes d'initiés ; obligation pour l'émetteur de communiquer aux participants toute information significative dans les cinq jours précédant la fenêtre.
- **Dénouement** par un dépositaire central de titres agréé au titre du règlement (UE) n° 909/2014, ce qui règle la question du transfert de propriété dans les droits nationaux exigeant un acte.
- **Volet contraignant, assumé comme tel** : toute société relevant du régime EU Inc. employant plus de 250 salariés est tenue d'organiser au moins une fenêtre de liquidité tous les dix-huit mois dès lors que des détenteurs représentant au moins 10 % des instruments de participation salariée en font la demande. L'émetteur peut plafonner le volume cédé à 15 % des instruments en circulation, mais ne peut pas refuser la fenêtre.

**Cadres connectés.** Règlement Prospectus (UE) 2017/1129, art. 1(4) ; règlement MAR (UE) n° 596/2014 ; directive MiFID II 2014/65/UE (la PELE est une catégorie distincte, ni marché réglementé, ni MTF, ni OTF) ; règlement CSDR (UE) n° 909/2014 ; règlement EU Inc. (volet obligation de fenêtre) ; règlement ELTIF (les ELTIF sont acheteurs éligibles, ce qui leur ouvre une classe d'actifs et améliore leur profil de liquidité) ; paquet intégration des marchés et supervision du 4 décembre 2025, qui fournit le véhicule et le cadre de supervision ESMA.

**Effet attendu.** *Micro* : traite simultanément le problème du salarié (monétisation), du LP (distributions avant liquidation du fonds) et du GP (taux de distribution sur capital appelé) — micro §5.1 R6. Améliore mécaniquement la valeur des instruments de participation salariée sans coût fiscal. *Macro* : referme partiellement la boucle collecte-sortie-recyclage identifiée comme le nœud systémique (macro §0.5), sans dépendre de la réouverture du marché primaire des IPO ; réduit la prime d'illiquidité qui constitue, selon macro §4.1, la composante principale de l'écart de coût du capital UE/US.

**Risque anticipé : élevé** — le CERS et la BCE opposeront l'opacité des marchés privés et la valorisation de niveau 3 (macro §6.1) ; l'obligation de fenêtre pour les EU Inc. de plus de 250 salariés sera qualifiée d'ingérence dans la liberté contractuelle de l'émetteur ; les autorités nationales contesteront la création d'une catégorie d'infrastructure échappant à MiFID II.

---

## F10. Facilité européenne d'ancrage boursier : un souscripteur public de référence pour les cotations européennes

**Problème visé.** Macro §3.2(b) est explicite : « le manque réel est du côté de la demande de titres cotés, pas de l'offre ». Le point de blocage n'est pas le prospectus mais l'absence d'un socle d'investisseurs institutionnels domestiques pour les capitalisations de 200 M€ à 2 Md€, segment où les mandats européens ont été structurellement réduits, notamment par effet non intentionnel du dégroupage de la recherche sous MiFID II. Micro §2.6 confirme que la décision de cotation se joue sur la profondeur du carnet, le multiple attendu et la liquidité du flottant — une boucle auto-réalisatrice qu'aucune mesure d'allègement de procédure ne rompt. Le Listing Act réduit le coût de la cotation ; il ne crée pas la demande.

**Mécanisme.** Créer dans le FEC une **Facilité européenne d'ancrage boursier (FEAB)**, gérée par le Groupe BEI :
- **Engagement d'ancrage automatique.** Pour toute introduction en bourse sur un marché réglementé ou un marché de croissance des PME de l'UE par une société de moins de vingt ans, dont le siège de direction effective est dans l'UE, et dont la capitalisation visée est comprise entre 200 M€ et 5 Md€, la FEAB s'engage, à la demande de l'émetteur formulée au moins soixante jours avant, à souscrire **jusqu'à 15 % de l'offre au prix final du livre d'ordres**, dans la limite de 150 M€ par opération.
- **Aucune sélection discrétionnaire sur la valeur.** La FEAB ne se prononce ni sur le prix ni sur la qualité de l'émetteur : elle souscrit au prix formé par le marché, ce qui est la seule construction qui la protège du reproche de sélection des gagnants et de la responsabilité de valorisation.
- **Discipline de sortie.** Blocage de 24 mois, puis cession obligatoire, linéaire et publiquement annoncée, sur cinq ans — la facilité est un amorceur de carnet, pas un actionnaire de long terme.
- **Conditionnalité de couverture analytique.** La souscription est conditionnée à l'engagement de l'émetteur de financer, pendant trois ans, une couverture de recherche indépendante par au moins deux fournisseurs, selon le régime de recherche financée par l'émetteur ouvert par les modifications de MiFID II opérées par le Listing Act. C'est le point qui traite la cause identifiée en macro §3.2(b) plutôt que le symptôme.
- **Enveloppe** : 10 Md€ sur la durée du CFP, provisionnés à 100 % puisqu'il s'agit d'une prise de participation et non d'une garantie, avec recyclage intégral des produits de cession en recette affectée externe.
- **Effet de levier attendu sur le carnet** : un ancrage public annoncé de 15 % réduit le risque d'échec de placement pour les autres souscripteurs, mécanisme de coordination bien identifié dans la pratique de marché.

**Cadres connectés.** Règlement FEC ; règlement (UE) 2024/2809 et directive (UE) 2024/2811 (Listing Act, volet recherche sous MiFID II) ; directive (UE) 2024/2810 (actions à droits de vote multiples — l'ancrage public devient d'autant plus utile que le fondateur conserve le contrôle) ; document d'émission de croissance de l'UE et prospectus de suivi disponibles depuis le 5 mars 2026 ; F5, branche cotée du sous-module d'innovation, qui fournit la demande institutionnelle relais après la sortie de la FEAB ; benchmarking §5.4 (prise de participation directe par véhicule souverain — EDBI, Temasek).

**Effet attendu.** *Micro* : modifie la variable 1 du calcul de l'émetteur (profondeur du carnet, micro §2.6) et, par la couverture analytique, la variable 3 (liquidité post-IPO). *Macro* : agit sur le seul point du blocage à la sortie qu'aucun instrument existant ne traite ; la capitalisation boursière rapportée au PIB reste de l'ordre de 37 % dans l'UE contre plus de 200 % aux États-Unis (macro §2.6), et le marché primaire est qualifié d'« exceptionnellement atone » au T2 2026.

**Risque anticipé : élevé** — soupçon immédiat de sélection des gagnants et d'aide d'État déguisée (la construction *pari passu* au prix du livre d'ordres est la défense, mais elle sera testée) ; opposition des gestionnaires d'actifs privés dénonçant une éviction ; risque politique majeur en cas de contre-performance boursière d'une participation publique visible.

---

## F11. Provisionnement différencié par compartiment et stabilisateur budgétaire automatique contracyclique

**Problème visé.** Deux constats convergents. D'abord, le taux uniforme de provisionnement de 50 % retenu pour la garantie de 70 Md€ du FEC réduit d'environ 20 % la garantie mobilisable par euro de crédit par rapport au régime InvestEU (40 % sur 26,2 Md€), soit un différentiel de l'ordre de 265 Md€ d'investissement mobilisé au multiplicateur constaté (micro §3.4 et R7). Ensuite, macro §6.2(1) identifie une procyclicité structurelle : lorsqu'un tiers des LP sont publics, le cycle du VC européen s'indexe sur le cycle budgétaire, qui se resserre au moment où les marchés se retournent — l'ancrage public censé être contracyclique devient procyclique.

**Mécanisme.** Deux modifications du règlement FEC :

1. **Provisionnement par compartiment, calibré sur la perte attendue.** Substituer au taux unique de 50 % un taux fixé par acte délégué pour chacun des compartiments, sur la base de la perte attendue observée sur dix ans du portefeuille de référence correspondant, avec un plancher de 25 % et un plafond de 60 %. Les portefeuilles de garanties PME du FEI, dont les pertes historiques sont sensiblement inférieures à celles des opérations de projet en pays tiers, ne peuvent pas être provisionnés au même taux. Obligation de publication annuelle de la perte réalisée par compartiment et de révision du taux si l'écart dépasse deux points sur trois exercices consécutifs.

2. **Stabilisateur automatique contracyclique.** Insérer une clause de déclenchement automatique : lorsque la collecte annuelle des fonds VC européens, mesurée par un indicateur officiel publié conjointement par l'ESMA et le FEI, tombe de plus de 25 % en dessous de sa moyenne mobile sur trois ans, **le plafond annuel de déploiement du compartiment fonds propres est relevé de plein droit de 50 %**, par prélèvement anticipé sur les tranches des exercices ultérieurs, sans nouvelle décision de la Commission ni du Conseil, pour une durée de deux ans. Symétriquement, le plafond est réduit de 25 % lorsque la collecte dépasse sa moyenne mobile de plus de 40 %. Les crédits du compartiment fonds propres sont qualifiés d'engagements pluriannuels non annualisables et non résiliables en cours de cycle.

**Cadres connectés.** Règlement FEC COM(2025) 555 final ; règlement financier (règles de provisionnement des garanties budgétaires et de report des crédits) ; règlement CFP COM(2025) 571 final et article 312 TFUE (le stabilisateur suppose une flexibilité de reprofilage explicitement autorisée dans le règlement CFP lui-même) ; évaluation intermédiaire d'InvestEU (art. 29 du règlement (UE) 2021/523) et rapport de la Cour des comptes européenne sur la surestimation d'environ 131 Md€ du multiplicateur, dont découle l'obligation de mesurer par décaissements effectifs aux bénéficiaires finaux localisés dans l'UE plutôt que par investissement mobilisé.

**Effet attendu.** *Micro* : à budget constant, plusieurs dizaines de milliards d'euros d'investissement mobilisé supplémentaires par point de provisionnement économisé. *Macro* : transforme l'ancrage public en amortisseur réel plutôt qu'en amplificateur — condition, selon macro §6.2(1), pour que l'effet stabilisateur théorique du capital public se matérialise. C'est aussi le seul mécanisme du jeu qui traite la procyclicité budgétaire par une règle et non par une intention.

**Risque anticipé : élevé** — le stabilisateur automatique soustrait au Conseil et au Parlement une décision de dépense en cours de cycle, ce qui heurte l'autorité budgétaire ; les États membres frugaux et l'Allemagne, déjà demandeurs de coupes de l'ordre de 400 Md€ (`stakeholder-map` §3.1), y verront un engagement pluriannuel irréversible.

---

## F12. Recyclage du bilan de garantie : titriser le portefeuille garanti du FEI pour relever deux fois le même euro

**Problème visé.** Micro R13 relève que le traitement prudentiel bancaire (CRR) rend le prêt à une société non rentable, sans collatéral tangible et sans notation, très coûteux en capital, ce qui explique que la dette de croissance européenne soit fournie par des fonds à 10-14 % plutôt que par des banques à 7-9 %. Macro §2.5 est plus prudent : la titrisation ne finance pas directement les fonds propres de scale-up et son effet est de second ordre. Les deux constats sont compatibles si l'on cible précisément le portefeuille garanti par le FEI, plutôt que la titrisation en général.

**Mécanisme.** Programme de titrisation adossé au bilan de garantie de l'Union :
- Le FEI structure, sur une base annuelle, une titrisation synthétique de son portefeuille de garanties aux entreprises innovantes et de dette de croissance. Le FEC **retient la tranche de première perte** (jusqu'à 8 %) ; les tranches mezzanine et senior sont cédées à des investisseurs institutionnels.
- **Renvoi croisé au trilogue titrisation** : les tranches ainsi cédées, dès lors que le sous-jacent est garanti par une garantie budgétaire de l'Union, sont expressément incluses dans la catégorie des « positions de titrisation résilientes » en cours de création dans la révision du règlement Titrisation et du CRR, avec les réductions de pondération associées, et rendues éligibles comme actifs d'un ELTIF et comme sous-jacent du sous-module d'innovation de Solvabilité II (F5).
- **Effet budgétaire.** Le transfert de risque libère la provision correspondante, qui redevient disponible pour émettre une nouvelle garantie. À une cession portant sur 70 % du risque, chaque euro provisionné supporte environ trois générations successives de garantie sur la durée du CFP — sans hausse du plafond de garantie autorisé.
- **Garde-fou contracyclique.** Calibration des critères de résilience sur un cycle complet (*through-the-cycle*) et non sur les performances récentes, et clause de revue automatique si l'encours ABS européen dépasse 800 Md€ (macro §6.2(3)).

**Cadres connectés.** Règlement Titrisation (UE) 2017/2402 et CRR (UE) n° 575/2013, en trilogue au S2 2026 après la position du Parlement du 5 mai 2026 ; règlement FEC ; règlement délégué Solvabilité II et acte délégué LCR, dont les modifications corrélatives sont déjà en discussion ; règlement ELTIF (éligibilité des tranches) ; F5 et F6.

**Effet attendu.** *Micro* : abaisse le coût de la dette de croissance en Europe en rétablissant un canal bancaire, ce qui affecte directement la structure de financement d'une scale-up (12,7 % du capital total levé en 2025, 5,6 Md$ — micro §2.5). *Macro* : effet de levier budgétaire sans augmentation d'enveloppe, ce qui en fait l'une des rares propositions compatibles avec la contrainte politique de taille du CFP ; correctif honnête à apporter : l'effet sur les **fonds propres** de scale-up reste indirect, et il serait analytiquement malhonnête de présenter ce mécanisme comme une réponse à l'écart de financement en capital (macro §2.5).

**Risque anticipé : moyen** — cohérent avec un trilogue déjà engagé ; l'opposition portera sur le fait que le budget de l'Union conserve la première perte, donc le risque, tout en cédant le rendement, et sur la crainte de procyclicité relevée par le CERS.

---

## F13. Affecter juridiquement une ressource propre au compartiment fonds propres du FEC

**Problème visé.** Macro §0.8 et §7.4 documentent la conditionnalité budgétaire : le CFP n'est pas acquis, trois blocs restent ouverts (taille globale, architecture des fonds structurels, ressources propres), et le Conseil européen des 18-19 juin 2026 n'a pas conclu. Le compartiment fonds propres du FEC représente 2,7 % de l'ensemble (11 Md€ sur 409 Md€) et sera, dans toute négociation d'ajustement à la baisse, la variable d'ajustement la plus commode : petite, technique, sans circonscription électorale. Toute proposition dont l'efficacité repose sur une ligne du FEC doit donc traiter ce risque.

**Mécanisme.** Utiliser la négociation en cours sur les nouvelles ressources propres, non pour créer une ressource supplémentaire, mais pour **affecter juridiquement une fraction d'une ressource existante ou en discussion** :
- Insertion, dans la décision relative au système des ressources propres (article 311 TFUE), d'une clause d'affectation prévoyant qu'une part fixe — proposition : **15 %** — du produit annuel des nouvelles ressources propres est versée directement au compartiment fonds propres et garanties du FEC, à l'exclusion de toute autre affectation, et qu'elle échappe à l'annualité budgétaire.
- **Conséquence structurelle** : le compartiment cesse d'être une ligne de dépense arbitrable dans le cadre annuel et devient un flux affecté, sur le modèle de ce que le règlement financier permet déjà pour les recettes affectées externes.
- **Contrepartie de redevabilité, à porter ensemble** : indicateur de résultat unique et public fondé sur les **décaissements effectifs aux bénéficiaires finaux établis dans l'UE** — et non sur l'investissement « mobilisé », méthode dont la Cour des comptes européenne a établi la surestimation d'environ 131 Md€, soit ~26 % du total déclaré (macro §7.4.3) ; suspension automatique de l'affectation si l'indicateur n'est pas publié dans les six mois de la clôture de l'exercice.

**Cadres connectés.** Décision ressources propres (article 311 TFUE, unanimité et ratification nationale) ; règlement CFP COM(2025) 571 final ; règlement financier (recettes affectées) ; règlement FEC ; F11 (le stabilisateur automatique n'a de sens que si la ressource sous-jacente est sécurisée).

**Effet attendu.** *Micro* : la prévisibilité pluriannuelle est ce que recherche un LP institutionnel qui s'engage sur dix ans ; un compartiment public dont l'existence est renégociée chaque année est un co-souscripteur peu crédible. *Macro* : neutralise la dépendance de l'ensemble du dispositif à l'issue d'une négociation dont la base factuelle établit qu'elle est ouverte et conflictuelle (macro §0.8), et fait basculer le compartiment fonds propres d'une logique de dépense à une logique de fonds permanent.

**Risque anticipé : extrême** — l'unanimité et la ratification nationale requises pour la décision ressources propres, combinées à l'hostilité documentée des frugaux et de l'Allemagne à toute rigidification du budget, rendent l'adoption très improbable ; la proposition a néanmoins une valeur de négociation, en ce qu'elle rend visible le coût de l'arbitrabilité du compartiment.

---

## F14. Guichet unique européen de sortie : un seul dépôt pour le contrôle des concentrations et le filtrage des investissements étrangers en dessous de 100 M€

**Problème visé.** 43 % des investisseurs citent l'absence de voies de sortie M&A comme première contrainte de financement (micro §1.6). Micro §7 R19 documente le canal précis : l'incertitude sur le filtrage des investissements directs étrangers dans plusieurs États membres est intégrée par les acquéreurs sous forme de décote de prix ou de renoncement, coût supporté par les fondateurs et les fonds européens. Un acquéreur d'une société de 60 M€ de chiffre d'affaires présente dans huit États membres peut devoir déposer jusqu'à huit notifications de filtrage IDE distinctes, avec des délais et des critères non harmonisés — coût fixe rédhibitoire au regard de la taille de l'opération. Or micro §1.6 rappelle que le déficit de sortie est un déficit d'amorçage à retardement : un GP qui ne peut pas modéliser une sortie applique une décote qui abaisse le prix payé en Series A.

**Mécanisme.** Révision du règlement (UE) 2019/452 relatif au filtrage des investissements directs étrangers, en cours, et du règlement (CE) n° 139/2004 :
- **Guichet unique obligatoire.** Pour toute acquisition d'une entreprise établie dans l'UE réalisant moins de 100 M€ de chiffre d'affaires mondial, un **dépôt unique auprès de la Commission** remplace l'ensemble des notifications nationales de filtrage IDE et de contrôle des concentrations, quel que soit le nombre d'États membres concernés.
- **Délai ferme et silence positif.** Décision dans un délai de **45 jours ouvrables** à compter du dossier complet ; à défaut de décision, l'opération est réputée autorisée. Un seul motif de prolongation, limité à 30 jours : ouverture d'un examen approfondi motivé par un risque identifié pour la sécurité ou l'ordre public, dont la notification doit citer la technologie ou l'actif précis en cause.
- **Voie réservée pour les acquéreurs de l'UE et de l'EEE** : décision en 20 jours ouvrables, sans examen approfondi possible en dessous du seuil, afin de créer un avantage procédural explicite à l'acquisition intra-européenne — mécanisme qui répond au constat de micro §7 R19 selon lequel, en l'absence d'acquéreurs européens, la sortie M&A devient elle-même un canal de fuite de valeur.
- **Publication annuelle** par la Commission du nombre d'opérations examinées, des délais réalisés et des refus motivés, par État membre d'origine de l'acquéreur.

**Cadres connectés.** Règlement (UE) 2019/452 (filtrage IDE, en révision) ; règlement (CE) n° 139/2004 sur les concentrations et pratique des renvois au titre de son article 22 ; règlement (UE) 2022/2560 sur les subventions étrangères, dont les seuils de notification doivent être alignés pour éviter de recréer par ce canal la charge supprimée ; Industrial Accelerator Act COM(2026) 100 final, qui comporte lui-même des dispositions de filtrage IDE dans les secteurs qu'il couvre et dont la cohérence doit être assurée ; règlement EU Inc. (une EU Inc. relève de plein droit du guichet unique).

**Effet attendu.** *Micro* : supprime une décote documentée dans le prix de sortie et raccourcit un calendrier d'opération, ce qui remonte mécaniquement toute la chaîne de valorisation jusqu'à la Series A (micro §1.6). *Macro* : agit sur le nœud systémique identifié — le blocage à la sortie — par un canal que ni le Listing Act ni le paquet intégration des marchés ne traitent, puisqu'ils portent sur la cotation et non sur le M&A, qui porte pourtant l'essentiel de la liquidité au T2 2026 (macro §2.6).

**Risque anticipé : élevé** — la sécurité nationale relève des États membres (article 4(2) TUE) et plusieurs d'entre eux considèrent le filtrage IDE comme une compétence régalienne intouchable ; la voie réservée aux acquéreurs de l'UE soulève une question de compatibilité avec les engagements internationaux de l'Union en matière d'investissement.

---

# AXE 2 — RENTABILITÉ

## R1. EU-ESOP : fait générateur unique à la cession, exonération patronale, portabilité — et coopération renforcée en repli

**Problème visé.** Micro §3.3 qualifie la fiscalité des instruments de participation salariée de « point aveugle », avec un double problème : le **moment de l'imposition** (plusieurs États membres taxent à l'attribution ou à l'exercice, obligeant un salarié à payer un impôt sur un titre illiquide) et les **charges sociales patronales**, qui rendent l'attribution coûteuse indépendamment de toute liquidité. Micro R11 est catégorique : « un régime EU Inc. qui n'emporterait pas de traitement fiscal unifié des instruments de participation salariée manquerait l'essentiel de son objet, car le droit des sociétés n'est pas le poste de coût dominant ». Macro §4.2 estime qu'un 28e régime limité au droit des sociétés capte une fraction à un chiffre du frottement mesuré, et identifie le volet stock-options comme le seul gain marginal substantiel. Le benchmarking (§3) documente les deux références : article 102 israélien (imposition différée à la cession au taux de plus-value de 25 % via un trustee agréé, détention de 24 mois) et régime ISO américain.

**Mécanisme.** Directive **EU-ESOP** sur le fondement de l'article 115 TFUE, applicable aux instruments émis par toute société relevant du régime EU Inc. ou par toute PME au sens de la recommandation 2003/361/CE établie dans l'UE :
1. **Fait générateur unique.** Aucune imposition ni à l'attribution ni à l'exercice ; imposition à la **seule cession** des titres, au taux national des plus-values mobilières. Les États membres conservent leur taux : la directive harmonise le fait générateur et l'assiette, non le taux — construction qui limite l'atteinte à la souveraineté fiscale et améliore la recevabilité.
2. **Exonération de cotisations sociales patronales** sur l'attribution et sur l'exercice, dans la limite d'attributions représentant 20 % du capital de l'émetteur et d'un gain cumulé de 1 M€ par bénéficiaire sur sa vie professionnelle, indexé annuellement.
3. **Portabilité et non-déchéance.** Le départ du salarié n'entraîne pas la caducité des instruments acquis ; la mobilité entre États membres n'ouvre pas de fait générateur ; répartition du droit d'imposer au prorata des périodes de résidence, sur le modèle des commentaires OCDE, afin d'éviter la double imposition sans traité additionnel.
4. **Séquestre européen agréé** (adaptation du trustee de l'article 102 israélien) : les instruments sont inscrits auprès d'un teneur de registre agréé et interconnecté aux registres nationaux, ce qui fournit aux administrations fiscales la traçabilité qui justifie le report d'imposition — c'est la contrepartie qui rend l'exonération administrativement défendable.
5. **Liquidité corrélée** : les instruments EU-ESOP sont éligibles de plein droit aux fenêtres de négociation des plateformes européennes de liquidité d'entreprise (F9). Un report d'imposition sans marché secondaire ne résout que la moitié du problème.

**Voie de repli.** À défaut d'unanimité, coopération renforcée entre au moins neuf États membres, avec clause d'adhésion ouverte, en scindant les volets : la portabilité, la non-déchéance et le séquestre agréé relèvent, eux, de l'article 114 TFUE et peuvent être adoptés à majorité qualifiée dans le règlement EU Inc. lui-même, indépendamment du volet fiscal.

**Cadres connectés.** Règlement EU Inc. COM(2026) 321 final et son volet EU-ESOP ; recommandation 2003/361/CE (définition des PME) ; F9 (liquidité secondaire) ; initiative « Blue Carpet » de la stratégie startups et scale-ups de mai 2025, aujourd'hui dépourvue d'instrument contraignant ; benchmarking §3 (article 102 israélien, ISO américaines).

**Effet attendu.** *Micro* : rend possible une rémunération majoritairement en titres pour les profils seniors, ce qui allège la trésorerie et allonge la piste — effet direct sur la rentabilité opérationnelle, et non seulement sur l'attractivité. Supprime l'une des micro-incitations documentées du « flip » vers le Delaware (micro §2.3). *Macro* : seule composante fiscale que les parties prenantes citent comme réellement bloquante à l'échelle et sur laquelle un accord semble politiquement atteignable (macro §4.2).

**Risque anticipé : extrême par la voie de l'article 115 TFUE, moyen pour les volets non fiscaux** — l'unanimité fiscale est le point de blocage historique ; les États membres à forte taxation à l'exercice y verront une perte de recettes immédiate contre un gain différé et incertain.

---

## R2. Titres de Jeune Entreprise Européenne : un QSBS européen construit comme un plancher, non comme un régime unique

**Problème visé.** Le benchmarking (§2 et §5.6) identifie le régime américain QSBS de la section 1202 IRC comme le seul dispositif de l'échantillon combinant échelle unique, barème dégressif selon la durée de détention et indexation automatique des plafonds. Il relève surtout un point que les débats européens ignorent : « un investisseur providentiel basé dans un État membre n'a aucune garantie de traitement équivalent s'il investit dans une startup d'un autre État membre ». Les régimes nationaux (PEA-PME, IR-PME, équivalents) sont non seulement hétérogènes mais souvent **implicitement domestiques**, ce qui fait de la fiscalité de l'investisseur providentiel une barrière intra-européenne et non seulement un différentiel de compétitivité externe.

**Mécanisme.** Directive créant les **Titres de Jeune Entreprise Européenne (TJEE)**, sur le fondement de l'article 115 TFUE, construite comme un **plancher minimal** que les États membres doivent accorder, et non comme un régime unique — architecture empruntée à la directive mères-filiales, qui a précisément permis d'harmoniser un traitement sans harmoniser les taux :
- **Éligibilité de la société** à la date de souscription : établie dans l'UE, actif brut inférieur à 100 M€, moins de dix ans, activité opérationnelle (exclusion des sociétés patrimoniales, financières et immobilières), au moins 60 % des effectifs dans l'UE.
- **Éligibilité des titres** : actions souscrites en numéraire à l'émission (souscription primaire uniquement, ce qui écarte l'effet d'aubaine sur le marché secondaire).
- **Exonération dégressive obligatoire de plus-value**, que chaque État membre doit au minimum accorder : **40 % à 3 ans, 70 % à 4 ans, 100 % à 5 ans** de détention. Le barème dégressif est délibérément préféré au seuil brutal de cinq ans du régime américain, dont le benchmarking souligne l'effet de falaise.
- **Plafond** : le plus élevé de 10 M€ ou de dix fois le prix de souscription, par société et par contribuable ; **indexation annuelle automatique** sur l'indice des prix à la consommation harmonisé, à compter de 2030 (le benchmarking relève que l'indexation automatique est l'une des trois caractéristiques de design absentes des régimes européens).
- **Non-discrimination, clause centrale.** Un État membre qui accorde un avantage fiscal à l'investissement en fonds propres dans des entreprises jeunes établies sur son territoire est tenu d'accorder le même avantage, aux mêmes conditions, à l'investissement dans une entreprise éligible établie dans un autre État membre. Cette clause seule, adoptée isolément, produirait déjà un effet substantiel.
- **Dispositif anti-abus dès l'origine**, en tirant la leçon négative explicitement signalée par le benchmarking (§5.7, doctrine australienne TD 2025/3 sur les ESIC) : exclusion des montages circulaires, des souscriptions financées par la société cible ou une partie liée, des rachats croisés entre investisseurs, et condition de risque effectif (absence de garantie de rachat ou de rendement plancher accordée au souscripteur).

**Cadres connectés.** Article 115 TFUE, avec repli en coopération renforcée ; directive mères-filiales 2011/96/UE (modèle d'architecture) ; ATAD pour les clauses anti-abus ; RGEC article 21 (articulation avec les aides au financement des risques : le TJEE est un avantage fiscal général et non une aide sélective, ce qui doit être expressément constaté) ; F1 et F2 (les souscriptions via un EuVGF transparent bénéficient du régime par transparence) ; benchmarking §2, §3 et §5.6.

**Effet attendu.** *Micro* : recrée la profondeur du financement d'amorçage, dont le nombre d'opérations a chuté de 44 % au T1 2026 (micro §1.2) ; abaisse le rendement exigé par l'investisseur providentiel, donc la dilution du fondateur à valorisation donnée. *Macro* : supprime une barrière intra-européenne rarement identifiée comme telle, et donne un contenu concret à l'objectif de la SIU d'orienter l'épargne des ménages vers les fonds propres.

**Risque anticipé : extrême** — unanimité fiscale, coût budgétaire national immédiat et visible, et forte probabilité que la clause de non-discrimination soit perçue comme la partie la plus coûteuse (elle étend l'avantage à des investissements sortants). Point favorable à signaler à l'auditeur : cette clause est plausiblement déjà exigible sur le fondement de la libre circulation des capitaux (article 63 TFUE), ce qui ouvre une voie contentieuse alternative à la voie législative.

---

## R3. Prime européenne d'apport en fonds propres : produire l'effet de DEBRA par le budget plutôt que par la fiscalité

**Problème visé.** Macro §4.3 qualifie l'abandon de DEBRA de « contradiction la plus coûteuse du dispositif actuel », et souligne qu'elle est en aggravation : le système fiscal européen continue de subventionner la dette et de taxer les fonds propres, pendant que le système prudentiel commence à faire l'inverse. BEFIT est gelé au Conseil. La voie fiscale est donc fermée pour la durée du CFP.

**Mécanisme.** Contourner le blocage fiscal par un instrument budgétaire produisant le même effet économique. Créer dans le FEC une **Prime européenne d'apport en fonds propres (PEAF)** :
- **Fait générateur** : une augmentation de capital en numéraire, souscrite par des tiers, réalisée par une entreprise établie dans l'UE de moins de douze ans, employant moins de 500 personnes, dont les dépenses de R&D représentent au moins 10 % du chiffre d'affaires ou 15 % des charges d'exploitation.
- **Montant** : versement direct à l'entreprise égal à **8 % du montant des fonds propres nouvellement souscrits**, plafonné à 2 M€ par entreprise sur sa durée de vie.
- **Automaticité et délai** : versement dans les **30 jours** suivant la transmission de l'acte d'inscription de l'augmentation de capital au registre national (ou au guichet numérique EU Inc.) et de l'attestation du commissaire aux comptes. Aucune évaluation de projet, aucune sélection, aucun comité — la prime est un droit, pas une subvention discrétionnaire.
- **Qualification juridique décisive** : il s'agit de fonds de l'Union en gestion directe, et non de ressources d'État ; la mesure échappe donc à la qualification d'aide d'État au sens de l'article 107(1) TFUE et n'a pas à s'imputer sur les plafonds du RGEC ni du de minimis. C'est ce qui la distingue radicalement d'un dispositif national équivalent.
- **Base juridique** : article 173 TFUE (industrie), procédure législative ordinaire, majorité qualifiée — donc hors du champ de l'unanimité fiscale.
- **Enveloppe** : 6 Md€ sur la durée du CFP, soit environ 850 M€ par an, correspondant à un flux annuel d'environ 10 Md€ de fonds propres primés.
- **Anti-abus** : récupération intégrale en cas de réduction de capital ou de distribution dans les 36 mois ; exclusion des augmentations de capital souscrites par une partie liée à plus de 50 % ; exclusion des sociétés contrôlées par une entreprise de plus de 3 000 salariés.

**Cadres connectés.** Règlement FEC, article 173 TFUE ; proposition DEBRA (dont la PEAF est le substitut budgétaire assumé) ; RGEC (articulation : la PEAF ne s'impute pas sur le plafond de l'article 21, ce qui doit être expressément constaté dans le RGEC révisé pour éviter toute interprétation contraire des autorités nationales) ; règlement EU Inc. et Portefeuille européen des entreprises (canal de transmission automatisé de l'acte de registre, qui rend le délai de 30 jours réalisable) ; benchmarking §3 (crédit SR&ED canadien remboursable en numéraire même en l'absence de bénéfice imposable — c'est cette caractéristique de remboursabilité, décisive pour une entreprise en perte, que la PEAF reproduit sans passer par le droit fiscal).

**Effet attendu.** *Micro* : améliore directement la trésorerie au moment précis où elle est disponible pour financer du développement commercial, et abaisse mécaniquement le coût effectif des fonds propres de 8 % pour l'entreprise. Pour un tour de Series A de 10 M€, 800 k€ non dilutifs versés en un mois — à comparer au temps d'instruction d'un dossier de subvention, identifié comme un coût réel en micro §2.1. *Macro* : corrige, dans son effet sinon dans sa forme, le biais fiscal dette/fonds propres pour la population exacte que ce biais pénalise le plus, sans requérir l'unanimité — ce qui en fait la seule réponse opérationnelle disponible à la contradiction identifiée en macro §4.3.

**Risque anticipé : moyen à élevé** — critique prévisible d'effet d'aubaine (l'entreprise aurait levé de toute façon), à laquelle la réponse est que l'effet recherché est un effet de prix et non un effet de déclenchement ; contestation possible de la base juridique de l'article 173 TFUE pour un dispositif s'apparentant à une mesure fiscale par son effet ; opposition des États membres attachés à la sélectivité des dépenses de l'Union.

---

## R4. Bande de capital et instrument convertible européen : supprimer le coût de friction de chaque tour successif

**Problème visé.** Micro §2.1 documente précisément le mécanisme : le coût juridique fixe d'un tour d'amorçage allemand ou italien — acte notarié obligatoire pour toute modification du capital d'une GmbH, formalités d'enregistrement, absence d'instrument convertible standardisé — rend structurellement non rentables les tickets inférieurs à environ 250 k€ et pousse vers des tours plus gros et plus tardifs. Le benchmarking (§3 et §5.2) identifie la réponse : la bande de capital suisse en vigueur depuis le 1er janvier 2023, qui permet au conseil d'administration, sur mandat des actionnaires valable cinq ans, de faire varier le capital de ±50 % sans nouvelle assemblée générale ni acte authentique. Il souligne que le 28e régime « se concentre surtout sur l'immatriculation et la dissolution plutôt que sur la mécanique des augmentations de capital successives » — le coût récurrent, pas le coût d'entrée.

**Mécanisme.** Insertion de deux chapitres dans le règlement EU Inc. :

1. **Bande de capital européenne.** L'assemblée générale d'une EU Inc. peut autoriser son organe de direction, pour une durée maximale de cinq ans, à augmenter ou réduire le capital souscrit dans une fourchette de **±50 %**, sans nouvelle décision collective, sans acte notarié et sans intervention judiciaire. L'inscription au registre s'effectue par dépôt électronique via le guichet numérique EU Inc., avec effet dans les cinq jours ouvrables. Les articles du titre I, chapitre IV, de la directive (UE) 2017/1132 relatifs aux modifications du capital sont écartés pour les sociétés relevant du régime. Garde-fous : droit préférentiel de souscription maintenu sauf renonciation expresse à la majorité des deux tiers ; rapport annuel de l'organe de direction sur l'usage de l'autorisation ; interdiction d'utiliser la bande pour une opération avec une partie liée sans approbation spécifique.

2. **Instrument Convertible Européen (ICE).** Création d'un instrument convertible **de forme statutaire** : un modèle unique annexé au règlement, à compléter par quatre paramètres seulement (montant, décote, plafond de valorisation, événement de conversion). Sa souscription et sa conversion s'opèrent par simple inscription électronique, sans acte notarié, sans assemblée générale et sans formalité d'enregistrement additionnelle dans aucun État membre. Rang subordonné aux créanciers ordinaires en cas d'insolvabilité, expressément qualifié dans le chapitre insolvabilité du règlement EU Inc. Reconnaissance mutuelle obligatoire de sa qualification par tous les États membres, y compris fiscalement (l'ICE n'est pas requalifié en dette portant intérêt réputé avant sa conversion).

**Cadres connectés.** Règlement EU Inc. COM(2026) 321 final ; directive (UE) 2017/1132 (droit des sociétés codifié), articles relatifs au capital ; directive (UE) 2019/1151 sur les outils numériques en droit des sociétés ; Portefeuille européen des entreprises et interconnexion des registres nationaux (BRIS) ; benchmarking §3 et §5.2 (Kapitalband suisse).

**Effet attendu.** *Micro* : ramène le coût marginal d'un tour successif de plusieurs dizaines de milliers d'euros et de plusieurs semaines à quelques centaines d'euros et quelques jours ; rend de nouveau rentables les tickets inférieurs à 250 k€ et les tours d'extension, ce qui rétablit le segment d'amorçage dont le nombre d'opérations a chuté de 44 % (micro §1.2). Supprime l'un des avantages comparatifs les plus concrets du Delaware, où l'instrument convertible standardisé permet de fermer un amorçage en deux à trois semaines (micro §2.1). *Macro* : gain de rentabilité pur, sans coût budgétaire ni coût fiscal, sur une population très large.

**Risque anticipé : faible à moyen** — c'est la proposition la moins contestée du jeu sur le fond. Les frottements documentés sont techniques et localisés : l'Allemagne et l'Autriche ont un ancrage constitutionnel de l'immatriculation des sociétés dans le système judiciaire (`stakeholder-map`, friction n°8), ce que la présente construction respecte puisqu'elle conserve les registres nationaux et n'écarte que l'exigence d'acte authentique ; le notariat des États membres concernés s'y opposera néanmoins fermement.

---

## R5. Autorisation sectorielle par silence positif et passeport de bac à sable : renverser la charge de la preuve dans le marché unique

**Problème visé.** La BCE mesure un équivalent tarifaire intra-européen de 95 % sur les services, avec un gain de commerce intra-UE atteignable de +14,5 %, le plus élevé de tous les segments (macro §2.7). Pour une scale-up logicielle ou de services réglementés, la friction pertinente est celle-là. Micro §4.5 la traduit au niveau du compte de résultat : entrer sur un nouveau marché européen exige une entité ou un enregistrement, un contrat de travail conforme, une adaptation contractuelle, souvent une localisation produit et parfois un agrément sectoriel — « c'est une différence de marge brute, pas de conformité juridique », et elle explique une part de la décote de multiple appliquée aux sociétés européennes. Macro §5.3 identifie l'Acte européen sur l'innovation comme le véhicule naturel d'un passeport de bac à sable — mais ce texte a été reporté à deux reprises après deux avis négatifs du comité d'examen de la réglementation et n'existe pas au stade de proposition formelle (`current-regulation` §3.2).

**Mécanisme.** Règlement autonome — précisément parce que l'Acte européen sur l'innovation est bloqué — intitulé **règlement sur l'accès des entreprises innovantes au marché unique** :
1. **Autorisation par silence positif.** Une entreprise titulaire d'une autorisation sectorielle valide dans un État membre A, qui dépose un dossier complet auprès de l'autorité compétente d'un État membre B, bénéficie d'une **autorisation provisoire de plein droit à l'expiration d'un délai de 60 jours**, sauf refus exprès. Le refus doit citer la disposition nationale précise non satisfaite, démontrer que cette exigence poursuit une raison impérieuse d'intérêt général et qu'elle est proportionnée, et indiquer les modifications qui la satisferaient. L'autorisation provisoire devient définitive au bout de dix-huit mois d'exercice sans mesure de police.
2. **Recours accéléré.** Contestation devant un mécanisme de type SOLVIT renforcé, avec **décision contraignante de la Commission dans un délai de 90 jours** et astreinte en cas d'inexécution. Le point décisif est le caractère contraignant : la reconnaissance mutuelle existe déjà en droit et échoue en pratique faute de sanction rapide.
3. **Passeport de bac à sable.** Une autorisation ou une dérogation obtenue dans un bac à sable réglementaire national est valable de plein droit dans les 26 autres États membres pendant 24 mois, pour les entreprises de moins de dix ans réalisant moins de 50 M€ de chiffre d'affaires, avec notification préalable à la Commission et faculté pour un État membre d'y faire objection motivée dans les 30 jours pour un risque identifié.
4. **Champ d'application ciblé, non universel.** Le règlement s'applique par voie d'annexe aux secteurs où la BCE mesure les frottements les plus élevés et où l'intensité de startups est la plus forte : services professionnels, santé numérique, services financiers réglementés, mobilité, énergie décentralisée. Annexe modifiable par acte délégué.

**Cadres connectés.** Articles 49, 56 et 114 TFUE ; règlement (UE) 2019/515 sur la reconnaissance mutuelle des biens (dont la présente proposition est le pendant, plus contraignant, pour les services et les autorisations) ; directive 2006/123/CE relative aux services ; règlement (UE) 2018/1724 sur le portail numérique unique ; Acte européen sur l'innovation (dont ce règlement récupère le volet le plus opérationnel, aujourd'hui bloqué) ; règlement EU Inc. et Portefeuille européen des entreprises (canal de dépôt) ; règlement (UE) 2024/1689 sur l'intelligence artificielle, dont les bacs à sable nationaux sont les premiers candidats au passeport.

**Effet attendu.** *Micro* : abaisse le coût marginal d'entrée sur un marché européen supplémentaire — cible mesurable proposée : moins de 10 k€ et 30 jours pour le cinquième marché, contre un coût aujourd'hui documenté comme structurellement élevé (micro §4.5, R12). Effet direct sur la marge brute et donc sur le multiple de valorisation. *Macro* : agit sur le levier le plus important en potentiel mesuré (services, 95 % d'équivalent tarifaire) et le fait à coût budgétaire nul (macro §5.3, rang 4 du classement systémique).

**Risque anticipé : élevé** — le silence positif en matière d'autorisation sectorielle sera présenté comme un abandon de la protection du consommateur et de la santé publique ; les autorités nationales de régulation y verront une dépossession ; la clause de refus motivé et proportionné en est la contrepartie, mais elle inverse effectivement la charge de la preuve, ce qui est l'intention.

---

## R6. Test de proportionnalité scale-up contraignant, assorti d'une clause de caducité

**Problème visé.** Micro §4.5 et R14 posent le problème dans les bons termes : un coût de conformité de 500 k€ par an est négligeable pour un grand groupe et représente 10 % du chiffre d'affaires d'une scale-up de 5 M€ ; c'est ce **ratio**, non le montant, qui détermine la réallocation de ressources hors R&D et hors commercial. Macro §4.2 le confirme au niveau systémique : les obligations européennes (CSRD, règlement sur l'IA, DORA, AIFMD) se déclenchent à des seuils qui créent des discontinuités de coût marginal au moment précis du passage à l'échelle, et produisent une incitation mesurable à ne pas franchir le seuil ou à le franchir depuis une juridiction hors UE. 70 % des fondateurs jugent l'environnement réglementaire restrictif (macro §2.6).

**Mécanisme.** Règlement horizontal, complété par une modification de l'accord interinstitutionnel « Mieux légiférer » :
1. **Test obligatoire.** Toute proposition d'acte de l'Union imposant des obligations aux entreprises doit comporter, dans son analyse d'impact, l'estimation du coût récurrent de conformité **exprimé en pourcentage du chiffre d'affaires d'une entreprise de référence** de 50 salariés et 10 M€ de chiffre d'affaires, et non seulement en valeur absolue agrégée. Une analyse d'impact dépourvue de ce chiffrage est irrecevable devant le comité d'examen de la réglementation.
2. **Seuil de déclenchement.** Si le coût estimé dépasse **0,5 % du chiffre d'affaires** de l'entreprise de référence, l'acte doit obligatoirement contenir soit un régime proportionné, soit une exemption, pour les entreprises de moins de 500 salariés et de moins de 100 M€ de chiffre d'affaires. Le législateur peut écarter cette obligation, mais par une motivation expresse et publique figurant dans les considérants.
3. **Clause de caducité scale-up.** Toute obligation adoptée sans avoir satisfait au test devient **caduque pour les entreprises situées sous le seuil** cinq ans après son entrée en application, sauf renouvellement exprès par un acte adopté selon la même procédure. C'est le seul dispositif qui rende le test réellement contraignant : sans sanction automatique, une exigence procédurale d'analyse d'impact est ignorée dès lors que le calendrier politique se tend.
4. **Stock, et pas seulement flux.** Obligation pour la Commission de publier tous les deux ans un inventaire du coût cumulé de conformité pour l'entreprise de référence, tous actes de l'Union confondus, avec objectif chiffré de réduction. Le problème documenté est un empilement, qu'aucun examen acte par acte ne peut capter.

**Cadres connectés.** Accord interinstitutionnel « Mieux légiférer » du 13 avril 2016 ; mandat du comité d'examen de la réglementation (dont les deux avis négatifs sur l'Acte européen sur l'innovation montrent qu'il exerce effectivement son contrôle — `current-regulation` §3.2) ; recommandation 2003/361/CE et catégorie intermédiaire des entreprises de moyenne capitalisation introduite par l'agenda de simplification ; RGEC révisé (dont l'axe de simplification est convergent) ; règlement (UE) 2024/1689 sur l'IA, CSRD, DORA, NIS2 comme premiers cas d'application du réexamen de stock.

**Effet attendu.** *Micro* : protège la trésorerie et le temps de direction, qui sont les deux ressources réellement rares d'une scale-up. *Macro* : traite l'effet de seuil identifié comme le mécanisme pertinent, et non le niveau d'exigence — ce qui distingue la proposition d'une dérégulation générale et la rend défendable devant les parties prenantes attachées au niveau de protection.

**Risque anticipé : moyen à élevé** — la clause de caducité automatique sera vivement contestée par le Parlement, qui y verra une abdication du législateur, et par les organisations de protection des consommateurs et de l'environnement ; le seuil de 500 salariés et 100 M€ sera jugé trop élevé par les uns, trop bas par les autres.

---

## R7. Classe d'exposition « entreprise innovante » dans le CRR et licence d'établissement de crédit d'innovation

**Problème visé.** Micro §2.5 documente la mécanique : le traitement prudentiel bancaire rend le prêt à une société non rentable, sans collatéral tangible et sans notation très coûteux en capital, de sorte que la dette de croissance européenne est fournie par des fonds de dette à 10-14 % et non par des banques à 7-9 %. Le marché est dominé par des acteurs anglo-saxons, et la disparition de la banque spécialisée américaine de référence a été absorbée par d'autres banques spécialisées, alors que l'Europe n'en compte aucune de taille significative. Macro §2.5 signale par ailleurs que le segment est structurellement sous-mesuré, avec des estimations divergeant d'un facteur cinq — ce qui doit conduire à assortir toute intervention d'une obligation de reporting.

**Mécanisme.** Trois volets :
1. **Classe d'exposition dédiée dans le CRR.** Créer, dans le règlement (UE) n° 575/2013, une classe « exposition sur entreprise innovante » : contreparties de moins de douze ans, employant moins de 500 personnes, dont l'intensité de R&D dépasse 10 % du chiffre d'affaires, ayant levé au moins 5 M€ de fonds propres auprès d'investisseurs professionnels au cours des 36 derniers mois. Facteur de soutien de **0,65** appliqué aux exigences de fonds propres pour ces expositions, contre 0,7619 et 0,85 dans le facteur PME actuel de l'article 501, porté à **0,45** lorsque l'exposition bénéficie d'une garantie du FEI ou du FEC couvrant au moins 50 % du principal.
2. **Reconnaissance des fonds propres levés comme élément d'atténuation du risque.** Autoriser expressément la prise en compte, dans l'évaluation interne du risque de crédit, de la trésorerie disponible issue d'un tour de financement et des engagements de réinvestissement des actionnaires existants — aujourd'hui traités comme sans valeur prudentielle, ce qui est la cause technique du coût en capital prohibitif.
3. **Licence d'établissement de crédit d'innovation (ECI).** Créer, par modification de la directive 2013/36/UE, un agrément allégé : capital initial ramené de 5 M€ à **1 M€**, exigences de gouvernance et de reporting proportionnées, en contrepartie d'un objet limitatif — prêter exclusivement à des entreprises innovantes au sens du volet 1, se financer exclusivement auprès d'investisseurs professionnels et par émission obligataire, **interdiction absolue de collecter des dépôts de la clientèle de détail** et donc exclusion du système de garantie des dépôts. L'objectif est de recréer dans le cadre européen l'équivalent fonctionnel d'une banque spécialisée du financement de l'innovation, sans exposer les déposants ni le filet de sécurité public.
4. **Reporting harmonisé obligatoire** de la dette de croissance auprès de l'EBA et de l'ESMA, avec une définition unique — préalable explicitement posé par macro §2.5 à toute intervention publique calibrée.

**Cadres connectés.** Règlement CRR (UE) n° 575/2013, art. 501 (facteur de soutien PME) ; directive CRD 2013/36/UE, art. 12 (capital initial) ; révision du CRR en cours en trilogue au S2 2026, qui fournit le véhicule ; F12 (titrisation du portefeuille garanti, qui donne à l'ECI un canal de refinancement) ; règlement FEC (garanties FEI conditionnant le facteur de 0,45) ; rapport de la Commission sur la compétitivité du secteur bancaire, consultation lancée le 11 février 2026.

**Effet attendu.** *Micro* : compression du coût de la dette de croissance de plusieurs points, sur un instrument qui représente déjà 12,7 % du capital total levé en Europe et qui est non dilutif — donc effet direct et immédiat sur la dilution du fondateur et sur la rentabilité. *Macro* : crée un canal de financement dont le passif n'est ni le budget public ni les fonds propres, ce qui diversifie une structure de financement aujourd'hui très concentrée ; effet secondaire favorable sur la concentration corrélée identifiée en macro §6.3.

**Risque anticipé : élevé** — la BCE et l'ABE opposeront que le prêt à des entreprises non rentables sans collatéral justifie précisément une charge en capital élevée, et que la licence allégée rouvre le débat sur l'arbitrage prudentiel ; la mémoire de la défaillance de la banque spécialisée américaine en 2023 sera mobilisée contre le volet 3, argument auquel l'interdiction des dépôts de détail répond partiellement mais pas totalement.

---

# AXE 3 — DEMANDE

## D1. Réserve européenne d'achat d'innovation : un SBIR européen, avec le droit de gré à gré en phase 3

**Problème visé.** Le benchmarking (§4 et §5.1) documente le mécanisme le plus instructif de tout l'échantillon : aux États-Unis, chaque agence fédérale dont le budget de R&D extra-muros dépasse 100 M$ doit réserver par la loi 3,2 % (SBIR) et 0,45 % (STTR) à des marchés de R&D réservés aux petites entreprises, soit plus de 8 Md$ en 2025. Le point structurel n'est pas le pourcentage : c'est qu'il s'agit d'un **prélèvement obligatoire sur chaque ligne budgétaire existante**, et non d'un guichet unique et séparé comme l'EIC Accelerator. Le benchmarking souligne aussi la fragilité du modèle américain (interruption de cinq mois faute de réautorisation), leçon à intégrer dans la conception.

**Mécanisme.** Règlement instituant la **Réserve européenne d'achat d'innovation (REAI)** :
- **Prélèvement transversal.** Tout programme de l'Union et tout organisme de l'Union disposant d'un budget annuel de R&D et d'acquisition de solutions supérieur à 100 M€ réserve **au moins 3 %** de ce budget à des marchés publics avant commercialisation et à des marchés de solutions innovantes attribués exclusivement à des entreprises établies dans l'UE, de moins de douze ans et de moins de 500 salariés. Le prélèvement s'applique ligne par ligne — FEC, Horizon Europe, fenêtres sectorielles, agences décentralisées, Fonds européen de la défense, programme spatial — et non par constitution d'une enveloppe centrale.
- **Adaptation à l'architecture européenne, point essentiel.** L'essentiel de la commande publique européenne étant nationale et non européenne, l'obligation est étendue par voie de **conditionnalité** aux dépenses nationales cofinancées par des fonds de l'Union : les plans nationaux et régionaux de partenariat et les enveloppes nationales du FEC comportent un engagement de réserve de 3 % de leur volet R&D et acquisition, dont l'exécution conditionne la libération d'une réserve de performance de 2 %.
- **Structure en trois phases, calquée sur le modèle éprouvé.** Phase 1, faisabilité : jusqu'à 100 k€ sur six mois, procédure allégée, jusqu'à cinq attributaires par sujet. Phase 2, développement et prototype : jusqu'à 1,5 M€ sur 24 mois, réservée aux lauréats de la phase 1. **Phase 3, déploiement : l'acheteur peut attribuer un marché de production de suite à un lauréat de phase 2, sans nouvelle mise en concurrence, jusqu'à 10 M€.** C'est le mécanisme que les dispositifs européens omettent systématiquement et qui fait toute la valeur du modèle : sans lui, l'entreprise finance un prototype et perd le marché. Il exige une modification explicite de la directive 2014/24/UE, par ajout d'un cas d'ouverture à la procédure négociée sans publication préalable de son article 32.
- **Stabilité, leçon négative du modèle américain.** Le prélèvement est institué sans clause d'extinction et n'est pas subordonné à une réautorisation périodique — contrairement au dispositif américain, dont l'interruption de cinq mois a gelé environ 4 Md$ par an.
- **Publication annuelle** par entité, en pourcentage réalisé, avec nom des attributaires.

**Cadres connectés.** Directives 2014/24/UE (art. 14 — exclusion de certains services de R&D, base juridique des marchés avant commercialisation ; art. 32 — procédure négociée sans publication ; art. 46 — allotissement) et 2014/25/UE ; révision des directives marchés publics attendue le 9 septembre 2026, véhicule naturel ; règlement FEC ; règlement portant dispositions communes et plans nationaux et régionaux de partenariat pour le volet conditionnalité ; règlement financier de l'Union ; benchmarking §4 et §5.1.

**Effet attendu.** *Micro* : un contrat public pluriannuel est un revenu non dilutif qui abaisse le risque commercial perçu par les investisseurs suivants et vaut, en valeur d'entreprise, un multiple de son montant (macro §5.1). Le droit de gré à gré en phase 3 transforme un financement de prototype en carnet de commandes réel. *Macro* : macro §5.1 chiffre l'ordre de grandeur — réorienter 1 % de la commande publique de l'Union (~20 Md€/an) équivaudrait à la totalité de la collecte annuelle de capital-risque européenne (22,3 Md€ en 2025), pour un coût budgétaire net proche de zéro puisque la dépense a lieu de toute façon.

**Risque anticipé : élevé** — le prélèvement transversal sera combattu par chaque direction générale et chaque agence dont il ampute la marge de manœuvre ; la conditionnalité sur les dépenses nationales cofinancées sera dénoncée comme une ingérence par les États membres et par les régions déjà mobilisées contre la centralisation des plans de partenariat (`stakeholder-map`, friction n°11) ; le droit de gré à gré en phase 3 sera contesté au regard des principes d'égalité de traitement et de transparence.

---

## D2. Objectifs contraignants de commande publique et dé-biaisage structurel des critères d'accès

**Problème visé.** Micro §4.6 énumère les causes documentées d'inaccessibilité de la commande publique pour une jeune entreprise : exigences de références antérieures et de chiffre d'affaires historique qui excluent mécaniquement une société de trois ans, garanties financières disproportionnées, délais de paiement qui transforment un contrat gagné en risque de faillite, et fragmentation (gagner à Rotterdam n'aide pas à gagner à Lyon). Le benchmarking (§4 et §5.1) fournit le comparateur : 847 institutions publiques coréennes sont légalement tenues d'acheter au moins 50 % de leurs achats totaux auprès de PME, avec un résultat chiffré, publié et dépassé (~87 Md$ en 2025) ; l'Union n'a jamais adopté d'équivalent contraignant, la « Small Business Act for Europe » de 2008 étant restée un cadre de bonnes pratiques. Macro §5.2 avertit à l'inverse qu'une réforme « pro-innovation » mal conçue produit un effet net **anti-startup**, les critères hors-prix favorisant mécaniquement les grands soumissionnaires.

**Mécanisme.** Dans la révision des directives marchés publics attendue le 9 septembre 2026, deux blocs indissociables :

**Bloc 1 — objectifs chiffrés, mesurés et publiés.**
- Chaque État membre veille à ce que, au niveau national agrégé et par année, **au moins 15 % de la valeur** des marchés supérieurs aux seuils européens soient attribués à des PME et **au moins 3 %** à des entreprises de moins de dix ans. Les niveaux sont volontairement calibrés bien en deçà du quota coréen de 50 % pour rester atteignables ; le mécanisme, lui, est le même : une obligation légale mesurée et publiée, et non un objectif qualitatif.
- Mesure automatique à partir des données TED, sans déclaration supplémentaire ; publication annuelle par la Commission d'un tableau comparatif par État membre et, au-delà d'un volume d'achat de 50 M€, par acheteur public.
- Sanction graduée : deux exercices consécutifs sous l'objectif déclenchent l'obligation d'adopter un plan correctif national ; un troisième exercice entraîne l'inéligibilité des acheteurs publics concernés au cofinancement par le FEC et par les plans nationaux et régionaux de partenariat pour les marchés de même nature.

**Bloc 2 — suppression des critères qui excluent mécaniquement les jeunes entreprises.** Sans ce bloc, le bloc 1 est inatteignable et produirait des contournements.
- **Interdiction** (et non plus simple encadrement au titre de l'article 58(3) de la directive 2014/24/UE) d'exiger un chiffre d'affaires annuel supérieur à deux fois la valeur estimée du lot, sans possibilité de dérogation motivée en dessous de 5 M€.
- Interdiction d'exiger des références de plus de trois ans d'ancienneté ou portant sur un périmètre supérieur au marché en cause ; obligation d'accepter des références obtenues dans un autre État membre et des références obtenues auprès d'acheteurs privés.
- **Allotissement obligatoire** pour tout marché supérieur à 5 M€, avec au moins un lot inférieur à 20 % de la valeur totale.
- **Paiement à 30 jours impératif et avance de démarrage de 20 %** pour tout titulaire de moins de dix ans ; intérêts de retard automatiques et non renonçables ; renvoi croisé au dispositif de lutte contre les retards de paiement en cours de refonte.
- **Plafonnement des garanties financières à 5 %** de la valeur du marché pour les titulaires de moins de dix ans, la différence étant couverte par une garantie du FEC appelable par l'acheteur public.

**Cadres connectés.** Directives 2014/24/UE (art. 58(3), 46, 63), 2014/25/UE, 2014/23/UE ; révision annoncée pour le 9 septembre 2026 ; directive 2011/7/UE sur les retards de paiement et sa refonte ; règlement FEC (contre-garantie des garanties de bonne exécution) ; base de données TED ; benchmarking §4 et §5.1 (Corée, États-Unis).

**Effet attendu.** *Micro* : lève simultanément les quatre barrières documentées ; le délai de paiement et la garantie financière sont, pour une société sans trésorerie, plus discriminants que le prix (micro §4.6, R16). *Macro* : levier de demande au meilleur rapport effet/coût budgétaire de tout le corpus (macro §9, rang 2), agissant sur une dépense déjà engagée représentant ~14 % du PIB de l'Union.

**Risque anticipé : élevé** — les objectifs chiffrés contraignants avec sanction budgétaire heurtent frontalement la compétence des États membres et des collectivités locales, qui gèrent ~45 % de la commande publique ; l'argument de la bonne gestion des deniers publics sera opposé aux quotas ; le bloc 2, en revanche, est nettement plus consensuel et pourrait être adopté seul — ce qui constitue le repli naturel de la proposition.

---

## D3. Centrale d'achat européenne d'innovation : précertification, accession et assurance de la performance de l'acheteur

**Problème visé.** Micro §4.6 identifie une friction que ni les quotas ni les critères ne résolvent : la fragmentation. Gagner un marché à Rotterdam n'aide pas à en gagner un à Lyon, ce qui oblige une jeune entreprise à supporter le coût fixe complet d'une réponse à appel d'offres 27 fois. Le benchmarking (§4) documente le second mécanisme coréen, moins commenté que le quota : la **précertification** de produits innovants (*Public Procurement of Innovation*), qui réduit le risque perçu par l'acheteur public face à une solution non éprouvée. La base factuelle ne le dit pas explicitement, mais le blocage terminal est bien là : le risque personnel et professionnel encouru par l'acheteur public qui retient un fournisseur jeune, non le cadre juridique.

**Mécanisme.** Trois briques articulées :
1. **Centrale d'achat européenne d'innovation (CAEI).** Création, par le règlement FEC, d'une centrale d'achat au sens de l'article 2(1)(16) de la directive 2014/24/UE, habilitée à conclure des accords-cadres et des systèmes d'acquisition dynamiques auxquels **tout pouvoir adjudicateur national, régional ou local peut adhérer sans conduire sa propre procédure**. Une entreprise remporte une procédure européenne unique et devient accessible aux acheteurs des 27 États membres. La base juridique existe déjà : l'article 39 de la directive 2014/24/UE autorise le recours à une centrale d'achat située dans un autre État membre — la proposition en fait un usage systématique plutôt qu'exceptionnel.
2. **Précertification européenne des solutions innovantes.** Label technique délivré après évaluation par un organisme accrédité, valable trois ans, attestant de la maturité technologique, de la conformité réglementaire et de la sécurité d'une solution. Une solution précertifiée est réputée satisfaire les spécifications techniques correspondantes dans toute procédure européenne, ce qui dispense l'acheteur d'en refaire l'évaluation.
3. **Assurance de performance de l'acheteur public — le mécanisme décisif.** Le FEC garantit tout pouvoir adjudicateur qui retient un fournisseur précertifié de moins de dix ans contre le préjudice résultant d'une défaillance d'exécution, à hauteur de 3 M€ par marché, avec une franchise de 10 %. La garantie est appelable sur simple constat de résiliation pour inexécution. Enveloppe : 1,5 Md€ de garantie sur la durée du CFP, provisionnée à 30 %, soit 450 M€ de crédits.

Ce troisième volet traite la vraie variable : ce qui dissuade un acheteur public de retenir une startup n'est ni le droit ni le prix, c'est l'exposition personnelle en cas d'échec. Une garantie européenne déplace ce risque vers un bilan qui peut le porter — pour un coût budgétaire modeste au regard du volume de commande qu'il débloque.

**Cadres connectés.** Directive 2014/24/UE, art. 2(1)(16), 37 et 39 (centrales d'achat et achats conjoints transfrontaliers), art. 42 (spécifications techniques et labels) ; révision des directives du 9 septembre 2026 ; règlement FEC (garantie budgétaire de nouvelle catégorie) ; D1 (les lauréats de phase 2 de la REAI sont précertifiés de plein droit) ; D2 (la CAEI est l'instrument par lequel les objectifs chiffrés deviennent atteignables sans coût de réponse démultiplié) ; benchmarking §4 (précertification coréenne).

**Effet attendu.** *Micro* : divise par un ordre de grandeur le coût d'accès commercial au marché public européen, aujourd'hui multiplié par le nombre d'États membres visés. *Macro* : combine un effet demande et un effet marché unique — c'est la proposition qui rapproche le plus concrètement la commande publique européenne du marché unique nominal dont macro §5.3 mesure l'écart.

**Risque anticipé : moyen à élevé** — l'assurance de performance sera contestée comme un aléa moral et une aide indirecte ; les centrales d'achat nationales existantes y verront une concurrence institutionnelle ; l'adhésion volontaire des acheteurs, en revanche, la rend juridiquement peu attaquable sur le terrain de la subsidiarité.

---

## D4. Valeur ajoutée unionale numérique : rendre la préférence européenne applicable aux logiciels et aux services

**Problème visé.** `current-regulation` §3.1 établit le constat décisif : l'Industrial Accelerator Act (COM(2026) 100 final) détermine l'origine par renvoi aux règles d'origine non préférentielles du code des douanes de l'Union — critère qui n'a **aucun sens applicable à un logiciel, à un service numérique ou à un modèle d'intelligence artificielle**. Le texte couvre l'acier, le ciment, l'aluminium, les technologies zéro net et l'automobile, et n'inclut donc pas les produits typiquement portés par les jeunes pousses technologiques. Micro §7 R17 pose la contrainte de conception : fonder la préférence sur des critères objectivables et auditables plutôt que sur la nationalité de l'actionnariat — critère que les investisseurs américains, présents dans 59 % du financement de stade tardif, rendraient de toute façon inopérant et qui pénaliserait les scale-ups européennes ayant levé à l'international. Macro §5.2 rappelle la contrainte externe : l'Accord sur les marchés publics de l'OMC restreint le périmètre disponible bien plus que le discours politique ne le suggère.

**Mécanisme.** Insertion d'un chapitre numérique dans l'Industrial Accelerator Act, ou règlement distinct si le texte est trop avancé, définissant un critère de **valeur ajoutée unionale numérique (VAUN)**, cumulatif et vérifiable :
1. **Localisation de la création de valeur** : au moins 60 % des effectifs de conception, de développement et d'exploitation affectés à la solution sont situés dans l'EEE sur les trois exercices précédents — critère vérifiable par les déclarations sociales, donc auditable.
2. **Propriété intellectuelle** : les droits sur le code, les modèles et les bases de données sont détenus par une entité établie dans l'UE, sans licence exclusive irrévocable consentie à une entité de pays tiers.
3. **Autonomie juridictionnelle** : la solution est opérable — plan de contrôle, gestion des clés, administration — depuis le territoire de l'Union, sans que son fonctionnement dépende d'une entité soumise à une injonction extraterritoriale d'un pays tiers. Critère technique et documentaire, non un critère de nationalité de l'actionnariat.
4. **Réversibilité** : séquestre du code source et engagement de portabilité des données selon un format documenté.

**Effet dans la procédure** : pour les marchés de solutions numériques stratégiques (informatique en nuage souveraine, cybersécurité, intelligence artificielle, connectivité, traitement de données sensibles) dépassant les seuils européens, l'acheteur applique une **pondération d'évaluation de 20 %** en faveur des offres satisfaisant la VAUN — préférence par pondération et non par exclusion, techniquement plus solide et plus proportionnée.

**Traitement de la contrainte OMC, à assumer frontalement.** Trois éléments : application limitée aux marchés non couverts par les annexes de l'Union à l'Accord sur les marchés publics ; activation, pour les autres, de l'instrument relatif aux marchés publics internationaux (règlement (UE) 2022/1031), qui permet des mesures fondées sur la réciprocité à l'égard des pays tiers ne garantissant pas un accès équivalent ; et mandat explicite à la Commission d'engager la renégociation des annexes de l'Union pour en exclure les technologies émergentes — demande portée par France Digitale (`stakeholder-map` §1.2) et jamais reprise dans un texte.

**Cadres connectés.** Industrial Accelerator Act COM(2026) 100 final ; règlement (UE) 2022/1031 (instrument relatif aux marchés publics internationaux) ; règlement (UE) 2022/2560 sur les subventions étrangères ; directives 2014/24/UE et 2014/25/UE ; schéma européen de certification de cybersécurité en nuage ; D2 et D3 ; benchmarking §4 (mise en garde de Bruegel sur l'approche « Made with Europe » plutôt que « Made in Europe » strict).

**Effet attendu.** *Micro* : ouvre aux scale-ups logicielles européennes le seul levier de demande publique aujourd'hui en discussion, dont elles sont exclues par un critère d'origine douanière inapplicable à leur produit. *Macro* : la formulation par pondération et par critères auditables limite le coût de bien-être identifié en macro §5.2(2) et le risque de re-fragmentation par transposition hétérogène (§5.2(3)), puisque les critères sont définis dans un règlement d'application directe.

**Risque anticipé : élevé à extrême** — opposition documentée et puissante des fournisseurs non européens et de 26 groupes industriels sur le seul volet certification (`stakeholder-map` §2.3, friction n°9) ; risque de contentieux OMC et de rétorsion ; clivage documenté entre États membres, la stratégie « Buy European » ayant déjà été retardée pour cette raison.

---

## D5. Standards livrés avec le texte, implémentations de référence open source, et report automatique à défaut

**Problème visé.** Micro §7 R18 identifie un mécanisme rarement formulé : chaque nouvelle exigence réglementaire européenne crée un marché captif, mais le décalage de 18 à 36 mois entre le règlement et ses normes techniques laisse ce marché aux acteurs déjà installés, seuls capables d'absorber l'incertitude. Le résultat est paradoxal : la réglementation européenne, censée créer un avantage de premier entrant pour les fournisseurs européens, subventionne en pratique les fournisseurs de conformité les mieux dotés, souvent non européens. `current-regulation` §1.5 documente le même phénomène sur le Listing Act, dont certaines dispositions n'entrent en application que 15 à 18 mois après l'entrée en vigueur, le temps que les autorités européennes de surveillance produisent les normes techniques.

**Mécanisme.** Règlement modifiant le règlement (UE) n° 1025/2012 relatif à la normalisation :
1. **Synchronisation obligatoire.** Aucune obligation imposée aux entreprises par un acte de l'Union ne peut entrer en application avant la publication au Journal officiel des normes harmonisées correspondantes **et** des schémas de conformité lisibles par machine (formats de données, interfaces de programmation, jeux de test).
2. **Report automatique.** Si les normes ne sont pas publiées **douze mois avant** la date d'application prévue, celle-ci est reportée de plein droit d'une durée égale au retard constaté, sans acte modificatif. Cette automaticité est le cœur du dispositif : elle transfère la charge du retard de l'entreprise vers l'administration qui en est responsable, et crée l'incitation à produire les normes à temps.
3. **Atelier européen d'implémentations de référence.** Ligne dédiée du FEC, dotée de 100 M€ par an, finançant la production, pour chaque nouvelle obligation significative, d'une **implémentation de référence en logiciel libre** sous licence EUPL : connecteurs de reporting, bibliothèques de conformité, jeux de tests, documentation. Gouvernance ouverte, contributions des entreprises admises.
4. **Présomption de conformité.** Tout organisme d'évaluation de la conformité et toute autorité de surveillance sont tenus d'accepter l'usage de l'implémentation de référence comme présomption de conformité aux exigences correspondantes.

**Cadres connectés.** Règlement (UE) n° 1025/2012 sur la normalisation ; accord interinstitutionnel « Mieux légiférer » ; R6 (test de proportionnalité scale-up, dont le présent mécanisme est le complément opérationnel) ; règlement (UE) 2024/1689 sur l'IA, CSRD, DORA, NIS2, eIDAS 2 comme premiers champs d'application ; règlement FEC (financement de l'atelier) ; règlement (UE) 2022/868 et règlement (UE) 2023/2854 sur les données pour les formats d'interopérabilité ; mandats de normalisation confiés au CEN, au CENELEC, à l'ETSI et aux autorités européennes de surveillance.

**Effet attendu.** *Micro* : abaisse d'un facteur substantiel le coût de mise en conformité d'une scale-up, qui n'a pas d'équipe réglementaire dédiée, et supprime la période d'incertitude pendant laquelle elle ne peut ni construire ni vendre. Ouvre un marché aux fournisseurs européens de solutions de conformité, qui deviennent les premiers à disposer d'un produit conforme documenté. *Macro* : convertit l'exigence réglementaire — aujourd'hui comptabilisée comme un coût net pour la compétitivité européenne — en demande adressable par les fournisseurs européens ; c'est le seul mécanisme du jeu qui transforme le stock réglementaire existant en actif plutôt qu'en passif.

**Risque anticipé : moyen** — le report automatique de l'entrée en application sera contesté par les colégislateurs et par les parties prenantes attachées aux échéances des textes environnementaux et numériques ; les organismes de normalisation européens objecteront un manque de moyens, ce qui plaide pour assortir la mesure d'un renforcement de leur financement.

---

## D6. Engagements d'achat anticipé européens pour les technologies stratégiques

**Problème visé.** L'analyse micro établit qu'un euro de chiffre d'affaires contractualisé ne vaut pas un euro de fonds propres : il est non dilutif, réduit le taux de rendement exigé par les investisseurs suivants en abaissant le risque commercial, et vaut un multiple de son montant en valeur d'entreprise (macro §5.1). Pour les technologies à forte intensité capitalistique — quantique, semi-conducteurs, biofabrication, stockage — le blocage n'est pas seulement le capital mais l'absence de marché prévisible : un investisseur ne peut pas modéliser un chiffre d'affaires qui dépend de l'adoption incertaine d'une technologie non encore produite. C'est exactement la configuration à laquelle répond l'engagement d'achat anticipé, instrument que l'Union a déjà utilisé et maîtrise juridiquement.

**Mécanisme.** Créer dans le FEC un instrument d'**Engagement d'achat anticipé (EAA)** :
- **Objet.** La Commission, agissant pour son compte et pour celui des États membres qui y adhèrent, s'engage à acheter une quantité définie d'un produit **n'existant pas encore**, répondant à une spécification de performance publiée, à un prix unitaire garanti, sur une durée d'au moins trois ans de production.
- **Attribution** par dialogue compétitif, avec au moins deux attributaires par spécification lorsque le marché le permet, afin de préserver la concurrence en aval.
- **Paiement à la livraison et à la certification uniquement.** Aucun financement en amont — c'est ce qui distingue l'EAA d'une subvention et ce qui rend son coût budgétaire contingent à la réussite. L'engagement figure au budget comme un passif éventuel provisionné, non comme un crédit consommé.
- **Enveloppe** : 8 Md€ d'engagements sur la durée du CFP, provisionnés à 35 %.
- **Domaines prioritaires**, choisis pour leur courbe d'apprentissage marquée et leurs effets de réseau — critère que macro §5.2(2) pose comme condition de l'effet net positif : migration vers la cryptographie post-quantique, briques d'infrastructure d'informatique en nuage souveraine, stockage stationnaire d'électricité, matériaux de construction bas carbone, biofabrication de précision, composants de communication sécurisée.
- **Réservation** aux fournisseurs satisfaisant le critère de valeur ajoutée unionale numérique (D4) ou, pour les biens physiques, les critères d'origine de l'Industrial Accelerator Act.
- **Clause de partage de la surperformance** : si le fournisseur vend le même produit à des tiers à un prix inférieur au prix garanti pendant la durée de l'engagement, l'Union bénéficie du prix le plus bas rétroactivement — protection contre la captation de rente, sans laquelle l'instrument est indéfendable politiquement.

**Cadres connectés.** Règlement FEC (nouvel instrument budgétaire) ; règlement financier (engagements pluriannuels et passifs éventuels) ; directive 2014/24/UE, art. 30 (dialogue compétitif) ; précédent juridique éprouvé des accords d'achat anticipé conclus par la Commission pour le compte des États membres ; Industrial Accelerator Act et D4 pour les critères de réservation ; D1 (les lauréats de phase 3 de la REAI sont candidats naturels aux EAA, ce qui crée un continuum demande publique de bout en bout) ; règles applicables aux projets importants d'intérêt européen commun, avec lesquels l'articulation doit être clarifiée.

**Effet attendu.** *Micro* : transforme un pari technologique en actif finançable ; un engagement d'achat de 200 M€ sur trois ans permet de lever de la dette et de l'equity à des conditions incomparablement meilleures qu'un même montant de subvention, parce qu'il fournit un contrat opposable et non une promesse administrative. *Macro* : agit sur le seul levier de demande capable de tirer les technologies à très forte intensité capitalistique, où le deeptech représente désormais 36 % des dollars de VC européens (micro §4.2) et où le plafond du RGEC de 16,5 M€ démontre l'inadéquation des instruments d'offre.

**Risque anticipé : moyen** — l'instrument est juridiquement éprouvé et son coût budgétaire est contingent, ce qui le rend défendable ; les objections porteront sur le choix des technologies par la puissance publique et sur le risque de captation de rente, auquel la clause de partage de la surperformance répond partiellement.

---

# 4. Synthèse : niveau de risque anticipé et effets recherchés

| # | Proposition | Axe | Véhicule principal | Coût budgétaire UE | Risque anticipé |
|---|---|---|---|---|---|
| F1 | Règlement EuVGF, continuum 0-5 Md€, passeport de gestion | Financement | Proposition EuVECA T3 2026 | Nul | Faible-moyen |
| F2 | Transparence fiscale des EuVGF, coopération renforcée en repli | Financement | Art. 115 TFUE / art. 326-334 | Nul | Élevé |
| F3 | Guichet miroir de co-investissement, silence positif à 15 jours | Financement | Règlement FEC | 4 Md€/an | Élevé |
| F4 | Instrument d'amorçage à option de rachat (Yozma adapté aux LP) | Financement | Règlement FEC + RGEC art. 21(13) | Moyen, partiellement recyclé | Moyen-élevé |
| F5 | Escalier Solvabilité II + sous-module innovation à 17 % | Financement | Règl. délégué 2015/35 | Nul | Élevé |
| F6 | Garantie budgétaire adossée à la charge prudentielle | Financement | FEC + règl. délégué 2015/35 | 3,75 Md€ de provision | Élevé |
| F7 | Label Épargne Productive Européenne, conditionnalité SIA, IORP | Financement | Art. 114 TFUE + IORP II art. 19 | Nul | Élevé |
| F8 | Retraite paneuropéenne à affiliation par défaut dans EU Inc. | Financement | Règlement EU Inc. + PEPP | Nul | Extrême |
| F9 | Plateformes européennes de liquidité d'entreprise | Financement | Paquet intégration des marchés | Nul | Élevé |
| F10 | Facilité européenne d'ancrage boursier | Financement | Règlement FEC | 10 Md€, recyclés | Élevé |
| F11 | Provisionnement différencié + stabilisateur contracyclique | Financement | Règlement FEC + règlement CFP | Gain net de levier | Élevé |
| F12 | Recyclage du bilan de garantie par titrisation | Financement | Trilogue titrisation/CRR | Gain net de levier | Moyen |
| F13 | Affectation d'une ressource propre au compartiment fonds propres | Financement | Décision ressources propres | Réaffectation | Extrême |
| F14 | Guichet unique de sortie (concentrations + filtrage IDE) | Financement | Révision règl. 2019/452 | Nul | Élevé |
| R1 | EU-ESOP : fait générateur unique, exonération patronale | Rentabilité | Art. 115 TFUE + EU Inc. | Coût fiscal national | Extrême / moyen (volets non fiscaux) |
| R2 | Titres de Jeune Entreprise Européenne (QSBS de plancher) | Rentabilité | Art. 115 TFUE | Coût fiscal national | Extrême |
| R3 | Prime européenne d'apport en fonds propres | Rentabilité | Art. 173 TFUE, règlement FEC | 6 Md€ | Moyen-élevé |
| R4 | Bande de capital + Instrument Convertible Européen | Rentabilité | Règlement EU Inc. | Nul | Faible-moyen |
| R5 | Silence positif sectoriel + passeport de bac à sable | Rentabilité | Règlement autonome, art. 114 | Nul | Élevé |
| R6 | Test de proportionnalité scale-up + clause de caducité | Rentabilité | Règlement horizontal + AII | Nul | Moyen-élevé |
| R7 | Classe CRR « entreprise innovante » + licence ECI | Rentabilité | Trilogue CRR + CRD | Nul | Élevé |
| D1 | Réserve européenne d'achat d'innovation (SBIR européen) | Demande | Directives marchés publics + FEC | Réaffectation de 3 % | Élevé |
| D2 | Objectifs contraignants 15 %/3 % + dé-biaisage des critères | Demande | Directives marchés publics | Quasi nul | Élevé (bloc 1) / moyen (bloc 2) |
| D3 | Centrale d'achat + précertification + assurance de l'acheteur | Demande | Directives + règlement FEC | 450 M€ de provision | Moyen-élevé |
| D4 | Valeur ajoutée unionale numérique + réciprocité | Demande | Industrial Accelerator Act + IPI | Nul | Élevé-extrême |
| D5 | Standards synchrones + implémentations de référence | Demande | Règl. 1025/2012 + FEC | 100 M€/an | Moyen |
| D6 | Engagements d'achat anticipé européens | Demande | Règlement FEC | 8 Md€ d'engagements, provisionnés à 35 % | Moyen |

**Répartition par niveau de risque anticipé :** faible-moyen 2 · moyen 3 · moyen-élevé 5 · élevé 13 · extrême 4 (dont deux à risque scindé selon le volet).

---

# 5. Notes destinées aux agents adversariaux

**Ce que je n'ai délibérément pas proposé, et pourquoi.** Ces omissions sont des choix argumentés, non des oublis :
- **Une augmentation de l'enveloppe du FEC.** Macro §7.4 établit que le compartiment financier représente 2,7 % de l'ensemble et que la couverture budgétaire réaliste du besoin est de 15-35 % ; augmenter l'enveloppe sans traiter les canaux d'appariement reviendrait à financer des appels de fonds sans co-souscripteurs.
- **Une obligation d'allocation contraignante des fonds de pension au capital-risque.** Non par prudence politique, mais parce que la construction par conditionnalité de bénéfice (F7) produit un effet comparable en heurtant moins directement le principe de la personne prudente, dont la violation exposerait le dispositif à un contentieux qu'il perdrait probablement.
- **Une transplantation directe du modèle Yozma.** Le benchmarking la présente comme instructive, mais son ressort visait un déficit de gestionnaires ; le déficit européen porte sur les souscripteurs institutionnels. F4 déplace donc l'option des gestionnaires vers les LP — c'est la modification substantielle sans laquelle la greffe échouerait.
- **La création d'une juridiction européenne dédiée aux EU Inc.** Le choix de l'article 114 TFUE par la Commission l'exclut structurellement (`current-regulation` §2.2) et la rouvrir imposerait de basculer vers l'article 352 TFUE et l'unanimité, ce qui coûterait plus qu'elle ne rapporterait.

**Trois points sur lesquels j'appelle explicitement une contradiction de l'auditeur d'impact.**
1. **F6** (garantie budgétaire convertie en réduction de charge prudentielle) est le mécanisme le plus original du jeu et potentiellement le plus fragile : il suppose qu'EIOPA accepte de reconnaître une garantie budgétaire de l'Union comme technique d'atténuation du risque au sens des articles 208 à 215 du règlement délégué. Si cette qualification est refusée, la proposition tombe entièrement.
2. **F3** (décision par silence) et **R5** (autorisation par silence positif) reposent sur le même pari : que l'automaticité soit le seul remède structurel à la lenteur administrative. Si l'auditeur estime que le silence positif est incompatible avec l'obligation de bonne gestion financière ou avec les objectifs impérieux d'intérêt général, c'est tout le principe de conception qu'il faut écarter, et non les seules propositions.
3. **La cohérence macroprudentielle du jeu est incomplète et je le signale.** Macro §6.3 identifie l'absence de limite de concentration comme la lacune de conception la plus sérieuse du dispositif actuel. Plusieurs propositions ci-dessus (F5 à F10) augmentent précisément les expositions que la BCE et le CERS jugent les moins bien mesurées. Le jeu devrait être complété par un volet macroprudentiel — limites de concentration sectorielle publiées au niveau du portefeuille agrégé du Groupe BEI, reporting consolidé des expositions croisées avec les banques nationales de promotion, outils de gestion de liquidité obligatoires et calibrés ex ante pour les ELTIF ouverts commercialisés au détail, suivi EIOPA dédié de la condition de non-vente forcée. Je n'en fais pas une proposition distincte parce qu'il s'agit d'une condition de recevabilité de l'ensemble, et non d'une option — mais l'auditeur serait fondé à considérer que le jeu est incomplet sans elle.
