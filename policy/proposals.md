# Propositions de réforme — Règlement EuVECA (UE) n° 345/2013, modifié par (UE) 2017/1991

**Agent : policy-innovator — Pipeline d'analyse de politique financière européenne**
**Mode : ensemble initial de propositions**
**Date de production : 4 août 2026**

---

## 0. Mandat et méthode

Ce document ne part pas d'une page blanche : chaque proposition ci-dessous répond à un constat précis identifié dans les cinq briefs produits en amont (`current-regulation.md`, `micro-analysis.md`, `macro-analysis.md`, `benchmarking.md`, `stakeholder-map.md`). Le mandat n'est pas d'amender EuVECA en isolation, mais de chercher systématiquement des points de levier dans l'architecture juridique adjacente de l'UE — AIFMD, ELTIF 2.0, Solvency II, IORP II, CRR/CRD, GBER, InvestEU, le Listing Act, le paquet d'intégration des marchés et de supervision (MISP) de décembre 2025, et les labels sectoriels existants (STEP, matières premières critiques, EDIP) — plutôt que de dupliquer ou de contredire ces cadres.

Chaque proposition suit le même canevas : **problème** (avec renvoi à la source), **mécanisme** (seuil, article, renvoi croisé précis), **cadre(s) connecté(s)**, **effet micro**, **effet macro**, et, le cas échéant, **lien au benchmarking** (ce qui devrait changer pour adapter un mécanisme étranger à l'architecture UE) ou **arbitrage de partie prenante** adressé.

Une réserve méthodologique s'applique à l'ensemble du document, dans le même esprit que les briefs en amont : les numéros d'articles de droit dérivé cités (Solvency II, CRR, GBER, STEP, CRMA) ont été vérifiés par recherche web au moment de la rédaction, mais certains points — notamment le détail d'application de l'EDIP, entré en vigueur le 30 décembre 2025 — restent à confirmer sur source primaire avant toute mise en forme législative.

**Sommaire des 13 propositions**

| # | Titre | Cadre(s) connecté(s) principal(aux) |
|---|---|---|
| P1 | Seuil AIFMD progressif à paliers, différencié selon l'effet de levier | AIFMD art. 3, §2(b) |
| P2 | Passerelle d'éligibilité fondée sur la stratégie du fonds (plafonnée) | AIFMD ; inspiration US Rule 203(l)-1 |
| P3 | Passeport de gestion via le mécanisme de renvoi ESMA du paquet MISP | Paquet d'intégration des marchés et de supervision (déc. 2025) |
| P4 | Seuils de capital fixés en niveau 1, indexés automatiquement | Règlement délégué (UE) 2022/30 |
| P5 | Double piste EuVECA Standard / EuVECA Pro | Inspiration Suisse (L-QIF), adaptée |
| P6 | Marge de sortie post-IPO sur marché de croissance des PME | Listing Act — règlement (UE) 2024/2809 |
| P7 | Extension du facteur soutenant les PME au cofinancement bancaire parallèle | CRR — règlement (UE) n° 575/2013, art. 501 |
| P8 | Passerelle de reconnaissance mutuelle EuVECA ↔ ELTIF 2.0 et repositionnement du retail | ELTIF — règlement (UE) 2015/760 / 2023/606 |
| P9 | Calibrage explicite du traitement Solvency II « LTEI » pour les parts EuVECA | Solvency II — règlement délégué (UE) 2015/35, art. 168b |
| P10 | Sauf-conduit IORP II pour l'allocation par défaut des régimes de pension DC | IORP II — directive (UE) 2016/2341 |
| P11 | Alignement du seuil de l'article 21 GBER + clause habilitante fiscale nationale | GBER — règlement (UE) n° 651/2014, art. 21 |
| P12 | Fenêtre de garantie InvestEU dédiée, éligibilité automatique par le label | InvestEU — règlement (UE) 2021/523 ; ETCI |
| P13 | Bonus sectoriel par renvoi aux labels STEP / matières premières critiques / EDIP | STEP (UE) 2024/795 ; CRMA (UE) 2024/1252 ; EDIP |

---

## A. Architecture du seuil AIFMD et du statut de gestionnaire

### P1 — Seuil AIFMD progressif à paliers, différencié selon l'effet de levier

**Problème.** Le franchissement des 500 M€ (ou 100 M€ pour les fonds à effet de levier) déclenche un passage binaire et non gradué vers l'AIFMD complète. La Commission qualifie elle-même ce seuil de « devenu obsolète » dans sa consultation de janvier 2026 (`current-regulation.md`, §6). `micro-analysis.md` (§2.1) documente le comportement de calibrage stratégique qui en résulte — gérants qui plafonnent délibérément la taille de leur fonds sous 500 M€, ou au contraire qui franchissent le seuil d'un coup plutôt que de croître linéairement — et note (§2.1) que le seuil identique pour fonds endettés et non endettés pénalise structurellement le venture debt et les stratégies hybrides.

**Mécanisme.** Remplacer le saut binaire par trois paliers explicitement définis dans le texte de niveau 1, en modifiant le renvoi de l'article 2 du règlement EuVECA à l'article 3, §2, point b), de l'AIFMD :
- **Palier 1 (< 500 M€ non endetté / < 100 M€ endetté)** : régime EuVECA actuel inchangé.
- **Palier 2 (500 M€ – 2,5 Md€ non endetté / 100 M€ – 500 M€ endetté)** : nouvelle catégorie « EuVECA Croissance », proportionnalité progressive — dépositaire simplifié (pas de dépositaire pleinement indépendant, mais obligation de séparation fonctionnelle), fonction de gestion des risques pouvant rester déléguée sous conditions, reporting AIFMD allégé plutôt que complet.
- **Palier 3 (> 2,5 Md€ ou > 500 M€ endetté)** : AIFMD complète, avec maintien de la faculté d'utiliser le label EuVECA (acquis du règlement 2017/1991).
Le seuil endetté est relevé proportionnellement (de 100 M€ à 500 M€ au palier 2) pour cesser de traiter à l'identique un fonds equity pur et un fonds à effet de levier modéré — corrigeant directement la distorsion notée en `micro-analysis.md` §2.1.

**Cadre connecté.** AIFMD, article 3, §2, point b) — le seuil lui-même n'est pas dans EuVECA mais y est importé par renvoi ; c'est ce renvoi qu'il faut modifier, pas réécrire l'AIFMD.

**Effet micro.** Supprime l'incitation au « saut » ou au plafonnement artificiel de la taille de fonds (`micro-analysis.md` §2.1) ; ouvre une trajectoire de croissance linéaire pour les gérants qui aujourd'hui perdent l'accès au label en dépassant 500 M€, sans les faire basculer immédiatement dans le coût fixe complet de l'AIFMD.

**Effet macro.** S'attaque directement au goulot d'étranglement identifié par la BCE au stade croissance/scale-up (`macro-analysis.md` §2.1-2.2) — c'est précisément le segment de taille intermédiaire que le seuil actuel décourage de se développer en Europe plutôt qu'ailleurs.

---

### P2 — Passerelle d'éligibilité fondée sur la stratégie du fonds (plafonnée)

**Problème.** `benchmarking.md` note que l'UE ne dispose que d'un seul levier — la taille du gestionnaire — alors que les États-Unis distinguent un test fondé sur l'AUM (proche d'EuVECA) d'un test fondé sur la stratégie du fonds, sans plafond d'actifs (exemption « venture capital fund adviser », Rule 203(l)-1 : ≥80 % en participations directes non cotées, effet de levier ≤15 % du capital, pas de droits de rachat).

**Mécanisme.** Ouvrir, pour les gérants du palier 2 de P1 (500 M€ – 2,5 Md€), une voie d'éligibilité alternative fondée sur la stratégie plutôt que sur la seule taille : un fonds respectant un test renforcé — ≥80 % (contre 70 % dans le régime standard) en participations directes dans des entreprises non cotées au sens de l'article 3 EuVECA, effet de levier plafonné, aucun droit de rachat, verrouillage ≥8 ans — reste éligible au régime allégé indépendamment de son AUM exact dans la fourchette du palier 2.

**Cadre connecté.** AIFMD art. 3 (seuil d'exemption), inspiration du régime américain Rule 203(l)-1 (Investment Advisers Act).

**Adaptation par rapport au modèle source (exigée par le mandat, étape 3).** Le modèle américain n'a **aucun** plafond d'AUM — inadapté tel quel à l'architecture UE, où le seuil de proportionnalité prudentielle reste un principe structurant (voir la ligne rouge documentée de Finance Watch et du CFA Institute en `stakeholder-map.md` §5.1 et §1.3). La version UE plafonne donc la passerelle au palier 2 (2,5 Md€ maximum) et relève l'exigence d'actifs éligibles de 70 % à 80 % pour compenser l'absence de plafond strict — un compromis qui n'existe dans aucun des deux modèles sources pris isolément.

**Effet micro.** Donne un second chemin d'accès au label pour des gérants dont la stratégie reste authentiquement « capital-risque » (peu de dette, pas de rachat) mais dont la taille de fonds dépasse 500 M€ du simple fait du succès de levée — répond au constat `micro-analysis.md` §2.1 sans ouvrir un boulevard réglementaire non plafonné.

**Effet macro.** Contribue à combler l'écart de taille moyenne de fonds documenté par le rapport Draghi (fonds européens near sept fois plus petits qu'aux États-Unis, cité en `benchmarking.md` §Repère) sans reproduire le risque prudentiel qu'un gate purement comportemental et illimité en AUM ferait courir dans un marché où la supervision reste fragmentée par 27 autorités nationales (`current-regulation.md` §4).

---

### P3 — Passeport de gestion via le mécanisme de renvoi ESMA du paquet MISP

**Problème.** `current-regulation.md` (§2, §4) documente l'absence de passeport de **gestion** (par opposition au passeport de commercialisation) pour les petits gérants sous-seuil : pour s'établir dans un autre État membre, ils restent soumis aux régimes nationaux d'enregistrement. `stakeholder-map.md` §8.3 documente en parallèle un blocage politique frontal sur la supervision centralisée : le bloc E6 (France, Allemagne, Italie, Espagne, Pays-Bas, Pologne) pousse vers un transfert de compétences à l'ESMA, tandis que l'Irlande et le Luxembourg (91 % des actifs de fonds transfrontières de l'UE à eux deux) y résistent fermement pour protéger leur modèle de domiciliation. Une extension classique du passeport de gestion, calquée sur le chapitre III de l'AIFMD, rouvrirait directement ce conflit.

**Mécanisme.** Ne pas créer un nouveau mécanisme de supervision centralisée. À la place, étendre explicitement à l'établissement transfrontière des gérants EuVECA sous-seuil le **pouvoir de renvoi de l'ESMA** déjà créé par le paquet d'intégration des marchés et de supervision (MISP) du 4 décembre 2025 pour arbitrer les désaccords entre autorité d'accueil et gérant sur la commercialisation transfrontière (`macro-analysis.md` §1). Concrètement : lorsqu'une autorité d'accueil impose au gérant EuVECA sous-seuil une exigence supplémentaire d'enregistrement pour s'y établir, le gérant peut saisir le même mécanisme de médiation/renvoi ESMA que celui déjà agréé par les 27 États membres pour la commercialisation — sans transfert de supervision directe et sans nouvel acte de niveau 1 créant une compétence ESMA inédite.

**Cadre connecté.** Paquet MISP (règlement-cadre du 4 décembre 2025, point d'accès unique de commercialisation transfrontalière et pouvoir de renvoi ESMA) — un cadre déjà adopté et déjà accepté politiquement par tous les États membres pour un usage voisin (la commercialisation), qu'il suffit d'étendre par renvoi plutôt que de reconstruire.

**Effet micro.** Comble l'écart identifié en `current-regulation.md` §2 sans réactiver la bataille de compétence — solution de second best praticable politiquement, contrairement à une extension pure du passeport de gestion AIFMD.

**Effet macro.** Réduit la fragmentation géographique documentée en `micro-analysis.md` §3.3 (forte adoption en Allemagne/Pays-Bas/Autriche/Finlande/Suède, faible en Espagne/France) sans se heurter frontalement à l'intérêt économique direct de Dublin et Luxembourg (`stakeholder-map.md` §3.3) — un compromis qui laisse la question de la supervision centralisée à son propre calendrier politique (le MISP), plutôt que de la lier au calendrier plus resserré d'EuVECA (proposition attendue au T3 2026).

---

### P4 — Seuils de capital fixés en niveau 1, indexés automatiquement

**Problème.** `current-regulation.md` (§3) documente un choix technique regretté a posteriori : le règlement 2017/1991 a renvoyé la fixation des règles de capital initial et de fonds propres à un acte délégué de niveau 2, ce qui a créé un décalage de près de quatre ans entre l'application du texte modifié (mars 2018) et l'entrée en vigueur effective du règlement délégué (UE) 2022/30 (octobre 2021/2022) — un délai qui a probablement atténué l'effet d'entraînement escompté sur l'adoption du label pendant l'intervalle.

**Mécanisme.** Inscrire directement dans le texte de niveau 1 de la révision 2026 les paramètres déjà calibrés par le règlement délégué 2022/30 (capital initial 50 000 €, fonds propres au plus élevé de 50 000 € ou 1/8 des frais généraux fixes, supplément de 0,02 % au-delà de 250 M€ d'AUM), assortis d'une clause d'indexation automatique sur l'indice des prix à la consommation harmonisé (IPCH) tous les cinq ans, appliquée par un acte d'exécution simple de la Commission (et non un acte délégué), réservant le niveau 2/RTS ESMA aux seuls paramètres techniques marginaux (méthode de calcul des frais généraux fixes, par exemple), pas aux montants eux-mêmes.

**Cadre connecté.** Règlement délégué (UE) 2022/30 — dont le contenu matériel est repris, pas la méthode de renvoi qui l'a produit.

**Effet micro.** Élimine le risque de répétition du délai 2018-2022 pour toute recalibration future des seuils de capital, garantissant que les gérants disposent d'une base de coût de mise en conformité stable et prévisible dès l'entrée en application du texte modifié.

**Effet macro.** Un choix procédural plutôt que substantiel, mais dont l'absence a concrètement retardé, selon `current-regulation.md` §3, l'appropriation du régime EuVECA II par le marché pendant près de quatre ans — un effet à ne pas répéter dans un contexte où la Commission cible une adoption effective au T3 2026 avec un calendrier politique resserré (SIU, agenda Draghi).

---

## B. Test d'actifs éligibles et mécanique du portefeuille

### P5 — Double piste EuVECA Standard / EuVECA Pro

**Problème.** `benchmarking.md` (§2 « ce qui est le plus instructif ») identifie un angle mort explicite : la consultation 2026 interroge le seuil de 500 M€ et le périmètre des gérants éligibles, mais ne remet pas en question le test des 70 % lui-même, alors que deux juridictions comparables l'ont soit allégé (Singapour, 80 % dans un régime de licence unique) soit purement supprimé pour les investisseurs qualifiés (Suisse, L-QIF, depuis mars 2024). En parallèle, `stakeholder-map.md` §8.2 et §8.7 documentent une ligne de fracture non transigeable : Finance Watch s'oppose frontalement à toute ouverture retail d'EuVECA et à toute dilution de son identité par élargissement du périmètre d'actifs, tandis qu'Invest Europe et EFAMA poussent pour plus de flexibilité.

**Mécanisme.** Créer une seconde piste, « EuVECA Pro », réservée aux fonds commercialisés exclusivement auprès de clients professionnels au sens strict de l'annexe II, section I, de MiFID II, et d'investisseurs semi-professionnels avec un ticket minimal relevé à 500 000 € (contre 100 000 € dans le régime standard). Pour cette seule piste, le test de composition des actifs de l'article 5 (les 70 %) est supprimé et remplacé par des garde-fous exclusivement au niveau du gérant, déjà présents ailleurs dans le règlement : fonds fermé, verrouillage minimal de 5 ans, absence de droits de rachat, plafond d'effet de levier. Le régime standard (test des 70 %, ticket à 100 000 €) reste strictement inchangé pour tout gérant ne choisissant pas la piste Pro.

**Cadre connecté / adaptation par rapport au modèle source (étape 3 du mandat).** Inspiré du L-QIF suisse, mais avec deux différences délibérées imposées par l'architecture UE : (i) contrairement au L-QIF, qui ne requiert **aucune** autorisation FINMA du véhicule, EuVECA Pro conserve l'enregistrement obligatoire auprès de l'autorité nationale compétente — nécessaire parce que le passeport de commercialisation UE dépend d'un dossier d'enregistrement national de référence, absence que le régime suisse (marché domestique uniquement) n'a pas à gérer ; (ii) le ticket minimal est fixé nettement au-dessus du régime standard (500 000 € contre 100 000 €) précisément pour garantir que la piste dérégulée ne touche jamais, même indirectement, la même base d'investisseurs semi-professionnels que le régime protégé — une segmentation qui n'existe pas dans le modèle suisse mais qui répond directement à l'objection documentée de Finance Watch.

**Effet micro.** Donne aux grands gérants professionnels la flexibilité de structuration qu'ils réclament (Invest Europe, `stakeholder-map.md` §1.1) sans toucher au régime que les petits gérants et les défenseurs de la protection des investisseurs veulent préserver intact.

**Effet macro.** Résout par segmentation, plutôt que par arbitrage à somme nulle, la friction 8.2/8.7 de `stakeholder-map.md` — la seule proposition de ce document qui permet aux deux camps identifiés d'obtenir simultanément ce qu'ils demandent, parce qu'elle les adresse à des tickets d'entrée différents plutôt que de choisir un seul design pour tout le marché.

---

### P6 — Marge de sortie post-IPO sur marché de croissance des PME

**Problème.** `micro-analysis.md` §3.6 documente, en s'appuyant sur la Banque de France, un facteur de marché qui déborde du texte EuVECA lui-même mais conditionne son efficacité : les fonds de capital-risque européens font face à des sorties plus limitées (IPO moins fréquentes qu'aux États-Unis), ce qui réduit la rotation du capital. `micro-analysis.md` §2.2 documente par ailleurs que la marge des 30 % sert déjà, de façon informelle, à loger des positions de suivi dans des entreprises ayant dépassé les seuils d'éligibilité après cotation — un palliatif non formalisé. `current-regulation.md` §1 note que le Listing Act (règlement (UE) 2024/2809 et actes associés) n'amende pas textuellement EuVECA malgré une parenté d'objectifs politiques (marchés de capitaux plus attractifs pour les PME) — un cas net de deux cadres adjacents qui n'interagissent pas.

**Mécanisme.** Insérer dans l'article 3 EuVECA un renvoi croisé explicite : lorsqu'une entreprise de portefeuille éligible réalise une introduction en bourse sur un marché de croissance des PME au sens de l'article 4, §1, point 12, de MiFID II, en bénéficiant du régime de prospectus simplifié introduit par le Listing Act, sa participation continue de compter dans le quota des 70 % pendant une période bornée de 24 mois suivant la cotation, indépendamment du plafond de capitalisation de 200 M€ qui s'appliquerait autrement immédiatement.

**Cadre connecté.** Listing Act — règlement (UE) 2024/2809 modifiant le règlement Prospectus, et actes associés (directives (UE) 2024/2810 et 2024/2811).

**Effet micro.** Formalise et borne dans le temps ce qui n'est aujourd'hui qu'un usage informel de la marge des 30 % (`micro-analysis.md` §2.2), donnant aux gérants une visibilité juridique claire au moment de décider d'accompagner une entreprise vers une IPO plutôt que de la céder prématurément à un acquéreur.

**Effet macro.** Donne au Listing Act une incidence concrète et positive sur le financement du capital-risque — c'est précisément le pont manquant identifié en `current-regulation.md` §1 entre deux textes de la même famille politique (DG FISMA, compétitivité des marchés de capitaux) qui, en l'état, ne se référencent pas juridiquement l'un l'autre — et adresse indirectement le goulot de sortie documenté en `micro-analysis.md` §3.6.

---

### P7 — Extension du facteur soutenant les PME (CRR art. 501) au cofinancement bancaire parallèle

**Problème.** `micro-analysis.md` §2.2 documente que le test des 70 % plafonne la part de dette dans l'enveloppe éligible, poussant structurellement les gérants EuVECA vers l'instrument actions plutôt que vers le prêt direct — cohérent avec l'objectif politique du texte mais restrictif pour les stratégies mezzanine/venture debt. Rouvrir directement le ratio des 70 % reviendrait à raviver la friction 8.7 de `stakeholder-map.md` (Finance Watch s'inquiétant d'une dilution de l'identité du label). Par ailleurs, une vérification factuelle effectuée pour cette note confirme un décalage définitionnel précis : l'article 501 du CRR (règlement (UE) n° 575/2013) applique le facteur soutenant les PME (multiplicateur 0,7619, soit une réduction d'environ 23,81 % de l'exigence de fonds propres pour risque de crédit) sur la base de la définition PME standard de la recommandation 2003/361/CE (moins de 250 salariés, chiffre d'affaires inférieur à 50 M€), alors qu'EuVECA, depuis 2017, retient un test PME distinct fondé uniquement sur l'effectif (jusqu'à 499 salariés, sans plafond de chiffre d'affaires ni de bilan). Les entreprises de croissance ciblées par l'élargissement EuVECA II (250-499 salariés) ne bénéficient donc pas automatiquement du facteur CRR lorsqu'une banque prête à leurs côtés.

**Mécanisme.** Sans toucher au ratio des 70 % d'EuVECA lui-même, proposer un mandat à l'ABE (dans le cadre de la prochaine révision du CRR) pour étendre le facteur de l'article 501 aux expositions de prêt bancaire consenties en parallèle (pari passu) d'un investissement en fonds propres d'un fonds labellisé EuVECA dans la même entreprise de portefeuille éligible, en substituant, pour ce cas précis, le test d'effectif d'EuVECA (≤499 salariés) au test de chiffre d'affaires du CRR — ouvrant un canal de cofinancement bancaire complémentaire plutôt que de relâcher la contrainte interne au véhicule EuVECA.

**Cadre connecté.** CRR — règlement (UE) n° 575/2013, article 501 (facteur soutenant les PME).

**Effet micro.** Répond au besoin de financement mezzanine/venture debt identifié en `micro-analysis.md` §2.2 sans rouvrir le débat sur le périmètre des actifs éligibles d'EuVECA lui-même (évite la friction 8.7).

**Effet macro.** Crée un canal de dette bancaire explicitement couplé au capital-risque plutôt qu'un canal de crédit autonome aux jeunes entreprises — ce qui répond à la mise en garde du rapport Draghi (`macro-analysis.md` §2.3) sur la dépendance excessive des jeunes entreprises innovantes au crédit bancaire mal adapté à leur profil de risque, en le rendant cette fois structurellement adossé à une prise de risque en fonds propres plutôt qu'isolé.

---

## C. Repositionnement vis-à-vis d'ELTIF 2.0

### P8 — Passerelle de reconnaissance mutuelle EuVECA ↔ ELTIF 2.0 et repositionnement du retail

**Problème.** `micro-analysis.md` §3.4 documente une dynamique de marché mesurable : ELTIF croît plus vite qu'EuVECA depuis sa révision de 2023 (226 fonds ELTIF en avril 2026 contre 57 sur 2015-2021, versus une base cumulée EuVECA de 1 229 fonds mais une croissance relative plus lente), posant la question d'un chevauchement fonctionnel et d'un choix de véhicule guidé par l'ingénierie réglementaire. `stakeholder-map.md` §8.2 documente une ligne rouge non transigeable côté investisseurs : Finance Watch s'oppose frontalement à l'ouverture retail spécifiquement pour EuVECA (contrairement à ELTIF, où elle est déjà actée), tandis qu'EFAMA pousse pour une ouverture retail généralisée. `macro-analysis.md` §3.4 identifie précisément l'élargissement de la distribution vers le retail/semi-professionnel comme le principal point de vigilance prudentiel à surveiller pour la trajectoire de la réforme.

**Mécanisme.** Deux volets :
1. **Reconnaissance mutuelle des définitions** : une entreprise de portefeuille éligible au sens de l'article 3 EuVECA (non cotée ≤499 salariés, ou cotée sur marché de croissance des PME <200 M€) est réputée satisfaire automatiquement la définition d'actif éligible de l'article 11 du règlement ELTIF (UE) 2015/760 tel que modifié par (UE) 2023/606, supprimant la double vérification d'éligibilité pour un gérant opérant des compartiments parallèles EuVECA et ELTIF.
2. **Répartition fonctionnelle explicite** : EuVECA reste strictement un véhicule d'origination professionnel/semi-professionnel (pas d'ouverture retail directe, préservant la ligne rouge Finance Watch) ; l'ambition de distribution retail de la SIU pour l'exposition au capital-risque est explicitement canalisée via une structure nourricière ELTIF détenant des parts d'un fonds EuVECA sous-jacent — le retail accède à l'exposition VC via l'architecture de protection déjà calibrée et déjà en service d'ELTIF 2.0 (outils de gestion de la liquidité, limites de diversification, test d'adéquation), sans avoir à répliquer cette architecture dans EuVECA lui-même.

**Cadre connecté.** ELTIF — règlement (UE) 2015/760, révisé par (UE) 2023/606.

**Effet micro.** Supprime le coût de double conformité pour un gérant structurant des compartiments EuVECA et ELTIF côte à côte (répondant à l'arbitrage réglementaire documenté en `micro-analysis.md` §3.4) ; préserve la fonction différenciante d'EuVECA comme régime allégé pour petits/moyens gérants (répondant à la friction 8.4 de `stakeholder-map.md` — le coût de gouvernance ELTIF, plus élevé, reste porté par la structure nourricière, pas par le fonds EuVECA sous-jacent).

**Effet macro.** Répond directement au point de vigilance prudentiel n°2 identifié en `macro-analysis.md` §3.4 : au lieu de tester de nouvelles protections retail sur un segment structurellement plus petit et moins liquide (EuVECA), la mobilisation de l'épargne des ménages visée par la SIU passe par une architecture de protection déjà éprouvée et en croissance rapide (ELTIF, 226 fonds en avril 2026) — réduisant le risque que l'élargissement de la base d'investisseurs et le déplacement du segment hors du radar macroprudentiel actuel (`macro-analysis.md` §3.2-3.4) se matérialisent simultanément.

---

## D. Mobilisation du capital institutionnel — connexions prudentielles et budgétaires

### P9 — Calibrage explicite du traitement Solvency II « LTEI » pour les parts EuVECA

**Problème.** `micro-analysis.md` §1.5 documente un mécanisme confirmé en direction mais non calibré précisément : les investissements en EuVECA/EuSEF bénéficieraient, comme les parts d'ELTIF, d'un traitement de capital aligné sur les actions « qualifiantes » sous Solvency II, sans que le facteur de choc exact applicable spécifiquement à EuVECA ait pu être vérifié. `macro-analysis.md` §2.1 et §4.3 documentent, à partir des recommandations convergentes de la BCE et du rapport Draghi, que la sous-représentation des assureurs et fonds de pension parmi les LPs européens (part publique de 30-33 % contre 4 % aux États-Unis) est directement liée aux règles prudentielles de Solvency II et d'IORP II, et que la révision des charges en capital sous Solvency II pour les actions de long terme figure parmi les recommandations Draghi explicitement citées.

**Vérification effectuée pour cette note.** L'article 168b du règlement délégué (UE) 2015/35 (Solvency II) définit une sous-catégorie « investissement en actions de long terme » (LTEI) bénéficiant d'une charge de capital réduite à 22 %, contre 39 % pour les actions de type 1 et 49 % pour le type 2, sans ajustement symétrique. Une révision en cours de ce règlement délégué, dont l'entrée en vigueur est prévue le 30 janvier 2027, assouplit précisément les critères d'éligibilité au LTEI pour les parts d'ELTIF et les FIA « à profil de risque plus faible » — un chantier déjà engagé, mais qui ne nomme pas explicitement EuVECA à ce stade.

**Mécanisme.** Profiter de cette révision en cours pour faire désigner explicitement les fonds porteurs du label EuVECA comme satisfaisant par construction le critère de « FIA à profil de risque plus faible » de l'article 168b révisé — le verrouillage ≥5 ans, l'absence de droits de rachat et le plafond d'effet de levier déjà exigés par les articles 3/6 du règlement EuVECA correspondant précisément au profil recherché — supprimant l'évaluation au cas par cas (« look-through ») que les assureurs doivent aujourd'hui effectuer fonds par fonds.

**Cadre connecté.** Solvency II — règlement délégué (UE) 2015/35, article 168b.

**Effet micro.** Transforme un avantage aujourd'hui confirmé en direction mais opaque en calibrage (`micro-analysis.md` §1.5) en un avantage quantifié et automatique (22 % contre 39-49 %) — un signal de coût de capital concret et actionnable par les gérants EuVECA cherchant à élargir leur base de LPs institutionnels.

**Effet macro.** C'est le levier le plus directement documenté par les quatre briefs en amont comme structurellement porteur : il répond simultanément au constat de la BCE sur la sur-représentation des LPs publics (`macro-analysis.md` §2.1), à la recommandation explicite du rapport Draghi sur les charges en capital Solvency II (`macro-analysis.md` §2.3, §4.3), et au point de vigilance prudentiel n°3 de `macro-analysis.md` §3.4 — à condition que la désignation explicite d'EuVECA s'accompagne, comme documenté, du maintien des garde-fous structurels du label (fonds fermés, absence de levier) qui justifient précisément ce traitement favorable.

---

### P10 — Sauf-conduit IORP II pour l'allocation par défaut des régimes de pension DC

**Problème.** `macro-analysis.md` §2.1 relie explicitement, via la BCE, la sous-représentation des fonds de pension parmi les LPs européens au principe de la « personne prudente » de la directive IORP II. `benchmarking.md` documente un précédent instructif mais imparfait : le Mansion House Compact/Accord britannique (engagement volontaire du secteur des pensions à porter les actifs non cotés à 5 % des allocations par défaut d'ici 2030, via le véhicule LTAF) affiche une allocation réelle de seulement 0,6 % en 2025 (contre 0,36 % en 2024) et seulement deux engagements contraignants vers des fonds VC recensés — un engagement purement volontaire sous-délivre nettement face à sa cible. `stakeholder-map.md` §8.5 documente en parallèle une opposition frontale et documentée de l'ETUC à toute « socialisation du risque » via une adhésion automatique ou obligatoire à l'épargne retraite orientée marché — une ligne rouge que le rapport Noyer-Kukies (task-force FIVE) ne parvient pas à lever.

**Mécanisme.** Ne pas répliquer un engagement purement politique et non contraignant. À la place, faire adopter par l'EIOPA, sous l'article 19 (principe de la personne prudente) de la directive IORP II (UE) 2016/2341, une orientation technique créant un **sauf-conduit réglementaire** explicite : une stratégie d'investissement par défaut d'un régime à cotisations définies allouant jusqu'à un plafond défini (par exemple 5 %) de ses actifs à des véhicules labellisés EuVECA (directement ou via la structure nourricière ELTIF de P8) est réputée conforme au principe de diversification et de liquidité de l'article 19, sans documentation de test de résistance spécifique au fonds à chaque allocation. L'allocation elle-même reste entièrement volontaire — seul l'obstacle administratif/de responsabilité qui décourage aujourd'hui les gestionnaires de régimes de l'exercer est levé.

**Cadre connecté / adaptation par rapport au modèle source (étape 3 du mandat).** Ce qui doit changer par rapport au Mansion House Compact pour que le mécanisme fonctionne dans l'architecture UE : remplacer un engagement purement politique et sectoriel — dont `benchmarking.md` documente empiriquement le sous-financement — par un instrument de droit dérivé (orientation EIOPA ancrée dans un article existant d'IORP II), qui ne force aucune allocation (répondant à la ligne rouge ETUC de `stakeholder-map.md` §8.5) mais rend l'allocation volontaire moins coûteuse à exercer pour un gestionnaire de régime qui le souhaite déjà.

**Effet micro.** Réduit le coût de mise en conformité pour un gestionnaire de régime DC souhaitant allouer vers EuVECA, sans imposer d'obligation nouvelle.

**Effet macro.** Adresse l'écart structurel documenté par la BCE (`macro-analysis.md` §2.1) sans reproduire l'échec empirique du seul engagement volontaire documenté par `benchmarking.md` — tout en évitant la friction politique frontale de `stakeholder-map.md` §8.5 (aucune adhésion automatique/obligatoire n'est proposée).

---

### P11 — Alignement du seuil de l'article 21 GBER + clause habilitante fiscale nationale

**Problème double.**
1. **Décalage définitionnel confirmé par vérification.** L'article 21 du GBER (règlement (UE) n° 651/2014) exempte de notification les dispositifs nationaux d'aide au financement des risques, mais réserve leur éligibilité aux « PME non cotées » au sens de la recommandation 2003/361/CE (moins de 250 salariés), avec un plafond de 15 M€ de financement à risque total par entreprise éligible. Le règlement EuVECA, depuis 2017, retient un seuil bien plus large (jusqu'à 499 salariés, sans plafond de chiffre d'affaires ni de bilan). Les entreprises de croissance que l'élargissement EuVECA II visait précisément à couvrir (250-499 salariés) ne peuvent donc pas bénéficier d'un cofinancement public structuré sous le régime GBER article 21 sans notification individuelle.
2. **Absence de tout levier fiscal côté EuVECA.** `benchmarking.md` documente que le Royaume-Uni (EIS/SEIS/VCT) et l'Australie (ESVCLP) combinent statut de véhicule et avantage fiscal, alors qu'EuVECA reste un régime exclusivement prudentiel — la fiscalité restant une compétence des États membres sous l'article 115 TFUE (unanimité). `stakeholder-map.md` §3.1 documente la recommandation de la task-force franco-allemande FIVE (rapport Noyer-Kukies, 19 janvier 2026) d'un dispositif de mobilisation de l'épargne calqué sur le programme français Tibi et « une plateforme équivalente à l'échelle de l'UE » — recommandation qui suppose une définition commune des entreprises éligibles, aujourd'hui absente.

**Mécanisme.**
1. Proposer une révision ciblée de l'article 21 GBER (ou de son annexe de renvoi) pour que, spécifiquement pour les dispositifs de financement des risques canalisés via un fonds labellisé EuVECA, le test d'éligibilité de l'entreprise bénéficiaire renvoie à la définition de l'article 3 EuVECA (≤499 salariés) plutôt qu'à la définition PME standard de l'annexe I du règlement 651/2014.
2. Insérer dans le règlement EuVECA lui-même une clause habilitante explicite : les États membres **peuvent** conditionner un avantage fiscal national au statut de fonds ou d'investissement labellisé EuVECA — non une harmonisation fiscale (hors de portée d'un règlement fondé sur l'article 114 TFUE), mais un point d'ancrage définitionnel commun que chaque État membre souhaitant répliquer un dispositif type Tibi, EIS/SEIS ou ESVCLP peut utiliser sans devoir concevoir sa propre définition d'éligibilité.

**Cadre connecté.** GBER — règlement (UE) n° 651/2014, article 21 ; et, pour le second volet, aucune modification du droit fiscal lui-même, seulement une clause de renvoi respectant la limite de compétence documentée en `benchmarking.md` (comparaison EIS/SEIS/VCT et ESVCLP).

**Effet micro.** Permet aux dispositifs nationaux de cofinancement (Tibi et équivalents) de couvrir, sous exemption GBER sans notification individuelle, les mêmes entreprises de croissance qu'EuVECA cible depuis 2017 ; réduit le coût de conception pour tout État membre lançant un nouveau dispositif fiscal national.

**Effet macro.** Opérationnalise la recommandation FIVE d'une « plateforme équivalente à l'échelle de l'UE » (`stakeholder-map.md` §3.1) en donnant à 27 systèmes fiscaux nationaux une définition commune plutôt qu'une harmonisation forcée — une réponse directe à la limite de compétence identifiée en `benchmarking.md` comme la raison structurelle pour laquelle EuVECA seul ne peut reproduire l'effet EIS/SEIS/VCT ou ESVCLP.

---

### P12 — Fenêtre de garantie InvestEU dédiée, éligibilité automatique par le label

**Problème.** `macro-analysis.md` §2.2 documente que les instruments publics de comblement du déficit de financement de croissance sont des cibles de mobilisation, non des mesures indépendantes du déficit : l'European Tech Champions Initiative (ETCI) vise 80 Md€ mobilisés, en a déjà mobilisé 10-15 Md€, et le FEI a lancé un nouveau fonds de fonds ETCI-2 de 15 Md€ pour le capital de croissance — précisément le segment que le rapport de la BEI (`macro-analysis.md` §2.2) identifie comme le plus déficitaire (-80 % de scale-ups, -85 % de licornes par rapport aux États-Unis). `micro-analysis.md` §4 documente en parallèle une sous-utilisation persistante du label EuVECA (~29 % des fonds VC UE identifiés).

**Mécanisme.** Créer, au sein de la fenêtre « marché unique » ou PME du règlement InvestEU (UE) 2021/523 (mise en œuvre notamment par le FEI), une sous-fenêtre de garantie où le statut de fonds labellisé EuVECA (enregistrement au titre de l'article 14 du règlement 345/2013) suffit à satisfaire automatiquement les critères de diligence d'éligibilité InvestEU, sans nouvelle évaluation séparée du FEI — évitant la duplication entre le processus d'enregistrement EuVECA et le filtrage propre du FEI/ETCI.

**Cadre connecté.** InvestEU — règlement (UE) 2021/523 ; European Tech Champions Initiative (ETCI/ETCI-2, FEI).

**Effet micro.** Réduit le coût et le délai d'accès des gérants labellisés EuVECA au cofinancement public ETCI-2, renforçant l'un des rares avantages concrets et directement actionnables du label identifiés en `micro-analysis.md` §2.4.

**Effet macro.** Augmente la part de l'enveloppe ETCI-2 (15 Md€) susceptible d'atteindre des véhicules labellisés et passeportables au niveau UE plutôt que des structures nationales ad hoc, renforçant la pertinence d'EuVECA précisément là où son adoption reste faible (`micro-analysis.md` §4) et où le déficit de financement de croissance est le plus documenté (`macro-analysis.md` §2.2).

---

## E. Ciblage sectoriel

### P13 — Bonus sectoriel par renvoi aux labels STEP / matières premières critiques / EDIP

**Problème.** `current-regulation.md` §6 documente que le questionnaire de la consultation de janvier 2026 interroge explicitement le ciblage sectoriel (défense, technologies numériques, sciences de la vie, matières premières critiques, transition durable) sans qu'aucun mécanisme concret ne soit encore sur la table pour l'opérationnaliser.

**Vérification effectuée pour cette note.** Le règlement (UE) 2024/795 établissant la Plateforme des technologies stratégiques pour l'Europe (STEP), applicable depuis le 1er mars 2024, crée un label de qualité — le « Sovereignty Seal » — attribué par la Commission aux projets dans trois piliers : technologies numériques/deep tech, biotechnologies, technologies propres et efficaces en ressources. Le règlement (UE) 2024/1252 relatif aux matières premières critiques (CRMA) crée de son côté un statut de « projet stratégique ». Le pilier défense n'est en revanche couvert par aucun des deux : le programme européen pour l'industrie de la défense (EDIP) n'a été adopté par le Conseil que le 8 décembre 2025, entré en vigueur le 30 décembre 2025 — trop récent pour qu'un mécanisme de labellisation de projet y soit déjà pleinement opérationnel.

**Mécanisme.** Introduire dans l'article 3 EuVECA un critère d'éligibilité bonifié, sans créer de nouvelle grille sectorielle propre à EuVECA : une entreprise de portefeuille éligible détenant le Sovereignty Seal (STEP) ou le statut de projet stratégique (CRMA) reste éligible jusqu'à 750 salariés (contre 499 dans le régime standard) et sans plafond de capitalisation boursière si elle est cotée sur un marché de croissance des PME. Pour le secteur défense, la même logique de renvoi est proposée pour être activée dès que le mécanisme de labellisation de projet de l'EDIP sera opérationnel — signalé ici comme option à confirmer plutôt que comme mécanisme prêt à légiférer, l'EDIP étant entré en vigueur trop récemment pour permettre une vérification de source primaire fiable au moment de la rédaction.

**Cadre connecté.** STEP — règlement (UE) 2024/795 ; CRMA — règlement (UE) 2024/1252 ; EDIP (règlement adopté le 8 décembre 2025, à confirmer pour le volet défense).

**Effet micro.** Donne aux gérants un test d'éligibilité bonifié à bas coût de vérification — le label STEP ou le statut CRMA étant déjà attribué par la Commission à d'autres fins, sans nouvelle couche d'évaluation sectorielle propre à EuVECA.

**Effet macro.** Oriente le capital labellisé EuVECA vers les secteurs explicitement nommés par la stratégie Startup and Scaleup (`current-regulation.md` §6) et par la SIU, en réutilisant des labels européens déjà instruits plutôt qu'en créant un nouveau critère sectoriel discrétionnaire — répondant concrètement aux questions Q-series de la consultation sur le ciblage sectoriel.

---

## F. Arbitrages non résolus par cet ensemble de propositions

Dans le même esprit de rigueur que les briefs en amont, il faut nommer ce que ces propositions ne résolvent pas :

- **Friction 8.3 (`stakeholder-map.md`) — supervision centralisée vs autorités nationales.** P3 contourne ce conflit pour le seul volet établissement transfrontière des petits gérants EuVECA, mais ne tranche rien sur la question plus large et distincte du transfert de supervision directe à l'ESMA portée par le bloc E6 dans le cadre du MISP — un arbitrage politique qui dépasse le calendrier et le périmètre d'EuVECA.
- **Friction 8.6 (`stakeholder-map.md`) — modèle bancarisé (Sparkassen allemandes) vs modèle orienté marché.** P7 crée un canal de cofinancement bancaire complémentaire mais ne répond pas à la réserve de fond des caisses d'épargne allemandes et de l'ETUC sur la titrisation et la désintermédiation bancaire — un débat structurel de la SIU dans son ensemble, pas spécifique à EuVECA.
- **Friction 8.5 (`stakeholder-map.md`) — mobilisation de l'épargne retraite.** P10 propose un sauf-conduit volontaire précisément pour éviter la confrontation frontale avec l'ETUC documentée dans ce brief, mais cela signifie aussi que P10 ne produira, par construction, qu'une fraction de l'effet d'échelle que viserait une adhésion automatique ou obligatoire — un choix délibéré de compatibilité politique plutôt qu'un optimum théorique.
- **Incertitude de calibrage.** Plusieurs propositions (P1 : bornes exactes des paliers ; P5 : ticket exact de la piste Pro ; P9 : calibrage fin du critère « profil de risque plus faible ») nécessiteront une analyse d'impact quantitative que ce pipeline n'a pas produite — les chiffres avancés ici sont des points de départ pour discussion, cohérents avec les ordres de grandeur documentés par `micro-analysis.md` et `macro-analysis.md`, pas des calibrages validés.

---

## Sources et méthode de vérification pour ce document

Ce document s'appuie en premier lieu sur les cinq briefs cités en en-tête. Les points suivants ont fait l'objet d'une vérification web complémentaire au moment de la rédaction (recherches menées le 4 août 2026), leurs résultats étant intégrés aux propositions concernées :
- CRR, article 501 (facteur soutenant les PME) — European Banking Authority, single rulebook interactif ; texte consolidé via legislation.gov.uk.
- Solvency II, règlement délégué (UE) 2015/35, article 168b (LTEI) — Commission européenne, *Questions and answers on the Solvency II delegated regulation* (29 octobre 2025) ; documentation sectorielle (DWS, Aberdeen Investments) sur la révision en cours (entrée en vigueur prévue le 30 janvier 2027).
- GBER, article 21 (aide au financement des risques) — texte consolidé via lexparency.eu et legislation.gov.uk, règlement (UE) n° 651/2014.
- Règlement (UE) 2024/795 (STEP, « Sovereignty Seal ») — EUR-Lex (résumé législatif), FASI.
- Règlement (UE) 2024/1252 (matières premières critiques, CRMA) — connaissance générale, non revérifiée par recherche primaire dans cette session (à confirmer avant usage législatif).
- Programme européen pour l'industrie de la défense (EDIP) — European Parliament Think Tank, Consilium (adoption du Conseil le 8 décembre 2025, entrée en vigueur le 30 décembre 2025) ; numéro CELEX précis non confirmé, à vérifier avant usage législatif.
