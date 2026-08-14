# Quatre reconstructions — mécanismes equity du compartiment FEC, corrigés à partir de leur propre échec documenté

**Agent :** reprise directe par l'orchestrateur (méthode déjà utilisée avec succès dans `roadmap-cluster-B` et `roadmap-cluster-D` du dossier source lorsque les sous-agents dédiés ont échoué sur une limite de dépense API).
**Date :** 14 août 2026
**Statut :** propositions nouvelles, jamais soumises à un tour de critique — à transmettre à un audit d'impact et un audit de faisabilité politique indépendants avant toute inscription dans une feuille de route (voir `02-verification-independante.md`).
**Règle de méthode reprise du dossier source :** aucune enveloppe n'est présentée comme un calcul. Chaque montant proposé ici est un ordre de grandeur explicitement illustratif, calibré par comparaison avec le compartiment fonds propres et garanties du FEC (~11 Md€ sur sept ans), et assorti d'une règle de rationnement dès l'origine — la vérification indépendante a démontré, sur F3 (enveloppe 2,5 fois trop grande) et R3 (aucune règle de rationnement, épuisement en quelques mois), que l'absence de cette discipline est la faute de conception la plus fréquente du dossier source.

---

## F6bis — Garantie mezzanine du compartiment fonds propres, adossée à une réduction de charge en capital calculée

### Ce que corrige cette version
F6 échouait pour trois raisons cumulatives (`impact-verification.md` §F6) : (i) une couverture de première perte à 10 % ne peut pas justifier une charge ramenée à 10 %, parce que le SCR mesure une perte en queue de distribution à 99,5 % sur un an, très supérieure à ce que couvre une tranche de première perte aussi étroite ; (ii) provisionner cette tranche à 25 % contredit sa propre perte attendue, structurellement bien supérieure ; (iii) le dilemme de tarification n'était pas traité (une prime actuarielle juste n'apporte aucun gain net à l'assureur ; une prime plus basse est une subvention non maîtrisée).

### Mécanisme corrigé
Le FEC émet, au bénéfice d'une entreprise d'assurance ou d'un IORP, une garantie **mezzanine** sur un portefeuille identifié d'actifs relevant du sous-module « actions d'innovation européennes » (proposition F5 du dossier source, elle-même sous condition de calibration EIOPA) : la garantie couvre les pertes du portefeuille **entre 10 % et 40 %**, l'assureur conservant intégralement le risque de première perte (0-10 %) et le risque extrême au-delà de 40 %.
- **Réduction de charge calculée, non décrétée.** La réduction de la charge en capital applicable au portefeuille garanti n'est pas fixée dans le texte : elle est **calculée par l'assureur lui-même**, selon la méthodologie de la formule standard applicable aux techniques d'atténuation du risque (articles 208 à 215 du règlement délégué (UE) 2015/35), sur la base de la structure de la tranche mezzanine effectivement souscrite. EIOPA publie, par orientation de niveau 3, une méthodologie de référence pour ce calcul spécifique à la classe d'actifs du sous-module F5 — condition posée explicitement par la vérification indépendante (« recevable devant EIOPA »).
- **Tarification actuarielle sur la tranche réellement couverte.** La prime est calibrée sur la perte attendue historique de la tranche 10-40 %, dont l'ordre de grandeur est très inférieur à celui d'une tranche de première perte — ce qui rend un provisionnement dans la fourchette 25-60 % déjà retenue pour F11 arithmétiquement défendable, sans le redimensionnement que le dossier source a dû appliquer à F3.
- **Portefeuille éligible et plafonds** : repris de F6 sans modification — 500 M€ de portefeuille par entité, plafond d'encours garanti total à fixer politiquement (voir échelle ci-dessous), extinction programmée après sept ans, amortissement linéaire à partir de l'année 5.
- **Phase pilote obligatoire.** Compte tenu de la nouveauté de l'instrument et de l'absence de précédent européen de garantie mezzanine adossée au SCR, le dispositif s'ouvre par une phase pilote de trois ans, plafonnée à un encours garanti total très inférieur à celui envisagé initialement pour F6 (15 Md€), avec clause de revue obligatoire avant toute extension — le dossier source documente que F6 est « l'idée la plus intéressante du jeu » mais que son échec initial est d'ordre technique et non politique ; une échelle pilote réduit le risque que l'erreur d'arithmétique se reproduise à grande échelle.

### Base juridique
Inchangée sur le principe : règlement FEC (nouvelle catégorie de garantie budgétaire) ; règlement délégué Solvabilité II, article 101(5) et articles 208-215 (atténuation du risque, cette fois appliqués selon leur méthodologie réelle plutôt que par assertion) ; F5 (portefeuille éligible) ; règlement financier (UE, Euratom) 2024/2509 pour le provisionnement des passifs éventuels.

### Risque résiduel assumé
La méthodologie de calcul EIOPA n'existe pas encore et doit être élaborée avant toute rédaction législative — ce n'est pas un détail d'exécution, c'est une condition préalable. Le corrélation garant/garanti relevée par la vérification indépendante (le FEC finance par ailleurs une partie du sous-jacent via F1, F3 et F4) demeure et doit être traitée par le collège N5, dont c'est précisément le mandat.

---

## F10bis — Cornerstone discrétionnaire du Groupe BEI pour les introductions en bourse, sans souscription automatique

### Ce que corrige cette version
F10 échouait pour deux raisons économiques et une raison arithmétique (`impact-verification.md` §F10) : (i) une souscription automatique de 15 % sans appréciation produit une antisélection structurelle — seuls les émetteurs dont le livre ne se remplit pas la demanderaient ; (ii) un calendrier de cession publiquement annoncé sur cinq ans crée un surplomb intégré dans le prix dès l'introduction, ce qui peut faire baisser le produit de l'émission que la facilité prétend soutenir ; (iii) 10 Md€ provisionnés à 100 % dans un compartiment de 11 Md€ est arithmétiquement impossible.

### Mécanisme corrigé
- **Discrétion et pari passu, à l'image de F3.** Le Groupe BEI peut, à sa propre appréciation d'investisseur et selon son propre processus de décision (comité d'investissement, même standard de diligence que les prises de participation directes actuelles du FEI), souscrire à une introduction en bourse sur un marché réglementé ou un marché de croissance des PME de l'UE, par une société de moins de vingt ans dont la capitalisation visée est comprise entre 200 M€ et 5 Md€ — **à la condition stricte qu'un investisseur privé de référence souscrive, au même prix et aux mêmes conditions, un montant au moins égal**. C'est la clause qui restaure la discipline de marché que l'automaticité de F10 avait supprimée : la BEI ne peut plus être le souscripteur de dernier ressort d'un livre qui ne se remplit pas, puisqu'elle ne peut agir qu'en miroir d'un engagement privé de taille au moins égale.
- **Montant réduit.** Jusqu'à 8 % de l'offre (contre 15 % dans la version initiale), plafonné à 60 M€ par opération (contre 150 M€) — échelle cohérente avec un rôle de cornerstone parmi d'autres investisseurs de référence, non de souscripteur dominant.
- **Discipline de sortie sans calendrier public.** Blocage de 24 mois inchangé ; au-delà, cession laissée à l'appréciation de gestion du Groupe BEI dans une fourchette maximale de cinq ans, **sans calendrier annoncé à l'avance** — seul un rapport annuel agrégé (volume total cédé sur l'ensemble du portefeuille, pas opération par opération) est publié, ce qui supprime le surplomb daté identifié comme le second défaut de F10 sans sacrifier la transparence de gestion.
- **Conditionnalité de couverture analytique, reprise sans modification.** Élément explicitly salvable par la vérification indépendante : la souscription reste conditionnée à l'engagement de l'émetteur de financer, pendant trois ans, une couverture de recherche indépendante par au moins deux fournisseurs, sous le régime de recherche financée par l'émetteur ouvert par le Listing Act.
- **Enveloppe.** Un ordre de grandeur défendable au regard du compartiment de 11 Md€, et compte tenu du fait que ce même compartiment finance aussi F3, F4 et F6bis, serait de l'ordre de quelques centaines de millions d'euros sur la durée du CFP — une fraction, pas un chiffre calculé, à trancher en même temps que les autres lignes du compartiment.

### Base juridique
Inchangée : fonds de l'Union en gestion indirecte via le Groupe BEI, hors article 107§1 TFUE faute de « ressources d'État » ; règlement FEC ; Listing Act (règlement (UE) 2024/2809 et directive (UE) 2024/2811) pour le volet recherche.

### Risque résiduel assumé
La clause de pari passu avec un investisseur privé de taille égale réduit mais n'élimine pas le risque de sélection : un émetteur pourrait structurer artificiellement un engagement privé de façade pour déclencher la participation BEI. Une clause anti-abus (durée de détention minimale du co-investisseur privé, absence de garantie de rachat croisée) doit être ajoutée avant rédaction — non développée ici faute de precedent directement transposable.

---

## F13bis — Crédits d'engagement pluriannuels non annualisables pour le compartiment fonds propres, et indicateur de décaissements effectifs

### Ce que corrige cette version
F13 échouait pour un motif dirimant que le dossier source lui-même n'avait pas identifié comme principal : ce n'est pas l'unanimité de l'article 311 TFUE sur les ressources propres qui condamne le mécanisme, c'est le **principe d'universalité budgétaire** (article 310§1 TFUE et règles de non-affectation du règlement financier), qui interdit d'affecter une recette à une dépense déterminée hors des cas limitativement énumérés de recettes affectées — une ressource propre affectée n'en fait pas partie. Second défaut, arithmétique : 15 % du produit des nouvelles ressources propres (plusieurs dizaines de milliards par an à partir de 2028, au titre du remboursement de NextGenerationEU) représenterait un multiple du compartiment qu'il prétendait seulement sanctuariser.

### Mécanisme corrigé
Abandon complet de la logique d'affectation d'une ressource propre. Le mécanisme retenu est celui que la vérification indépendante qualifie elle-même de « meilleure idée de la fiche, [qui] ne dépend pas du reste » :
- **Crédits d'engagement pluriannuels non annualisables**, inscrits directement dans le règlement FEC de base pour le seul compartiment fonds propres et garanties — possibilité que le règlement financier (UE, Euratom) 2024/2509 reconnaît déjà explicitement pour les instruments financiers et les garanties budgétaires, sans nécessiter aucune modification du système des ressources propres ni de vote à l'unanimité additionnel. Le compartiment cesse d'être arbitrable ligne par ligne à chaque exercice annuel, sans pour autant devenir un flux affecté au sens prohibé par l'article 310 TFUE : la protection porte sur le **rythme d'engagement** pluriannuel, pas sur l'origine de la recette.
- **Indicateur de résultat unique et public** : décaissements effectifs aux bénéficiaires finaux établis dans l'Union — et non l'investissement « mobilisé », dont la Cour des comptes européenne a établi la surestimation d'environ 131 Md€ (~26 % du total déclaré) sur InvestEU. Publication semestrielle par compartiment.
- **Conséquence de transparence, pas de sanction budgétaire automatique** (pour éviter l'écueil constaté sur le volet stabilisateur de F11, où une automaticité de mobilisation de crédits futurs a été jugée incompatible avec les articles 310 et 314 TFUE) : à défaut de publication de l'indicateur dans les six mois de la clôture de l'exercice, la Commission est tenue de le signaler dans son rapport annuel au Parlement et au Conseil, qui restent seuls compétents pour en tirer les conséquences budgétaires dans le cadre de la procédure normale.

### Base juridique
Règlement financier (UE, Euratom) 2024/2509 (crédits d'engagement pluriannuels pour instruments financiers et garanties) ; règlement FEC de base (procédure législative ordinaire, majorité qualifiée — pas d'unanimité, à la différence de la version originale) ; rapport de la Cour des comptes européenne sur la méthodologie du multiplicateur InvestEU.

### Risque résiduel assumé
La protection obtenue est plus modeste que celle recherchée par F13 initial : un crédit d'engagement pluriannuel reste, en dernier ressort, modifiable par un règlement ultérieur de même rang (aucun mécanisme ne peut juridiquement lier le législateur futur) — c'est une protection de **procédure et de visibilité**, pas une garantie irréversible. C'est explicitement le compromis assumé : la version qui offrait une garantie plus forte (F13 initial) est celle que la vérification indépendante a jugée juridiquement indisponible.

---

## N1bis — Soutien à la souscription en fonds propres de long terme, assis sur le montant souscrit et détenu

### Ce que corrige cette version
N1 (FERGIL) échouait sur un motif que le débat auto-porté du dossier source n'avait vu qu'au conditionnel et que la vérification indépendante établit comme une exclusion écrite : l'article 173§3, second alinéa, TFUE dispose expressément que cette base ne peut pas servir à une mesure « contenant des dispositions fiscales » — or FERGIL indexait son versement sur l'impôt sur la plus-value effectivement acquitté par l'investisseur, ce qui rattache la dépense de l'Union à une variable fiscale nationale. Deux défauts supplémentaires, non résolus par la seule reconstruction sur l'assiette : une inégalité de traitement entre investisseurs selon le taux de leur État de résidence (versement maximal là où l'impôt est le plus élevé, nul là où la plus-value est exonérée), et une incitation à choisir le moment de la cession pour maximiser la rétrocession.

### Mécanisme corrigé
Sur le modèle exact de R3 (prime européenne d'apport en fonds propres), mais côté investisseur plutôt que côté entreprise — la généralisation que N1 visait, appliquée cette fois à une assiette qui ne touche à aucune variable fiscale :
- **Fait générateur et assiette.** Tout investisseur résident de l'Union ayant souscrit en numéraire, à l'émission, des actions d'une entreprise éligible (mêmes critères que le TJEE du dossier source : établie dans l'UE, actif brut < 100 M€, moins de dix ans, activité opérationnelle) peut demander, à ce fonds financé par le FEC et en gestion directe de la Commission, un versement égal à un pourcentage du **montant souscrit et effectivement détenu** sans interruption — non de la plus-value réalisée, non de l'impôt acquitté.
- **Barème dégressif selon la durée de détention**, sur le modèle déjà construit pour le TJEE du dossier source : un versement plus élevé pour une détention plus longue, par exemple étagé à 3, 4 et 5 ans — reprise d'un barème déjà conçu et déjà documenté comme préférable à un seuil brutal.
- **Pourquoi cette assiette échappe à l'article 173§3.** Le versement ne dépend à aucun moment d'une grandeur fiscale (taux, assiette, fait générateur d'un impôt national) : il est fonction du seul montant souscrit et de la durée de détention, deux grandeurs économiques observables indépendamment de tout événement fiscal. Il ne varie pas non plus selon l'État de résidence de l'investisseur — le second défaut de FERGIL disparaît par construction, puisque le montant versé est identique pour un même montant souscrit quel que soit le taux d'imposition national des plus-values. Et parce qu'il est versé sur la détention et non déclenché par une cession, il ne crée aucune incitation à choisir un moment de vente.
- **Plafond et règle de rationnement dès l'origine** — leçon tirée de R3 : plafond par investisseur et par an, et enveloppe annuelle fixe avec réduction au prorata en cas de dépassement, publiée en temps réel, pour éviter l'épuisement en quelques mois déjà identifié comme un défaut de conception sur R3.
- **Anti-abus** : reprise, sans modification, de la clause déjà bâtie pour le TJEE du dossier source — exclusion des montages circulaires, des souscriptions financées par la société cible ou une partie liée, des garanties de rachat ou de rendement plancher.

### Base juridique
Article 173 TFUE (industrie, majorité qualifiée), en gestion directe de la Commission — même qualification que R3 : fonds de l'Union en gestion directe, hors article 107§1 TFUE faute de « ressources d'État ». **Point de vigilance à documenter avant dépôt** : à la différence de R3 (versement à une entreprise), N1bis verse à des personnes physiques ; la jurisprudence sur la portée de l'article 173 TFUE pour des mesures bénéficiant in fine à des particuliers plutôt qu'à des entreprises n'est pas établie dans la base factuelle disponible et doit être vérifiée par un service juridique avant tout dépôt.

### Risque résiduel assumé
Le point de vigilance ci-dessus est le plus significatif : si l'article 173 TFUE s'avérait indisponible pour un versement à des personnes physiques, N1bis retomberait sur les mêmes bases fragiles que R2/TJEE (article 115 TFUE, unanimité). C'est un risque juridique non résolu par cette reconstruction, à traiter en priorité par la vérification indépendante du §7.

---

## Tableau de synthèse

| # | Nom | Corrige | Enveloppe illustrative | Risque résiduel principal |
|---|---|---|---|---|
| F6bis | Garantie mezzanine SCR | F6 (arithmétique de couverture) | Très inférieure à 15 Md€, phase pilote 3 ans | Méthodologie EIOPA à construire avant rédaction |
| F10bis | Cornerstone discrétionnaire BEI | F10 (antisélection + surplomb) | Quelques centaines de M€, 8 % max/opération | Clause anti-abus du pari passu privé à construire |
| F13bis | Crédits pluriannuels + indicateur | F13 (universalité budgétaire) | Sans coût propre | Protection de procédure, pas de garantie irréversible |
| N1bis | Soutien à la souscription longue | N1/FERGIL (article 173§3 TFUE) | À plafonner comme R3 | Disponibilité de l'article 173 TFUE pour des personnes physiques, non établie |

Ces quatre fiches sont transmises pour vérification indépendante — voir `02-verification-independante.md`.
