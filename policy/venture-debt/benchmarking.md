# Benchmarking international — Traitement réglementaire de la venture debt

**Objet :** comparer, à l'appui d'une réflexion sur l'introduction d'un compartiment prudentiel bancaire dédié à la venture debt dans le cadre CRR/CRD (sur le modèle du « specialised lending » de l'article 147 CRR), la manière dont d'autres juridictions traitent ce type de financement — côté bancaire prudentiel, mais aussi côté véhicules non bancaires, à titre comparatif.

**Ce document compare des régimes ; il ne recommande pas de politique.** Les implications pour l'UE sont signalées comme pistes de réflexion à destination de l'analyse de politique publique en aval.

**Niveau de confiance :** élevé pour les éléments juridiques US et UK (textes officiels, cabinets d'avocats spécialisés) ; moyen pour les données de marché chiffrées (issues de communiqués d'entreprises ou de presse spécialisée, non auditées de façon indépendante par cette recherche) ; plus faible pour les juridictions où peu de sources publiques existent (Israël notamment), signalé explicitement à chaque fois.

---

## 1. Tableau de synthèse

| Juridiction | Mécanisme clé | Différence structurelle avec l'approche UE (art. 147 CRR) | Résultat observé sur le marché |
|---|---|---|---|
| **États-Unis — banques (OCC/Fed)** | Pas de catégorie prudentielle dédiée : prêt venture = exposition « corporate » générique, pondérée à 100 % en approche standard, sauf sûretés/garanties éligibles. Encadrement par **guidance supervisoire qualitative** (OCC Bulletin 2023-34, remplacé par 2025-45, déc. 2025) : limites de concentration, staff dédié, agrégation des expositions, provisionnement renforcé, interdiction de considérer un futur tour de table comme source de remboursement principale. | Le compartiment CRR art. 147 est une catégorie **Pilier 1** (pondération de risque différenciée) ; le dispositif US est un ajustement **Pilier 2 / supervisoire** sans modification du poids de risque réglementaire. | SVB détenait ~44 % des IPO tech/santé soutenues par VC en 2022 avant sa chute ; après mars 2023, réallocation significative des flux de venture debt vers les BDC et fonds de dette privés. |
| **États-Unis — BDC (SEC, Investment Company Act 1940)** | Véhicule d'investissement coté (pas une banque), régulé par la SEC, pas par un régulateur prudentiel bancaire. Ratio de couverture d'actifs minimal (200 % historiquement, 150 % depuis le Small Business Credit Availability Act de 2018 pour les BDC ayant opté pour le régime allégé), soit un levier dette/capitaux propres pouvant atteindre 2:1. | Logique entièrement différente : pas de RWA, pas d'exigence de fonds propres bancaires ; le contrôle du risque passe par la structure du véhicule coté (transparence actionnariale, plafond de levier) et non par une pondération de crédit. | Rendement effectif du portefeuille de crédit d'Hercules Capital ≈ 13,0 % (T1 2025) ; couverture en warrants typiquement 3-10 % du principal ; ratios de créances non performantes variables selon l'acteur (TriplePoint ≈ 3,7 % en valeur de marché) — signe de dispersion de qualité de portefeuille selon les BDC. |
| **Royaume-Uni — PRA (HSBC Innovation Banking)** | Pas de sous-catégorie « venture lending » identifiée dans les règles PRA ou dans Basel 3.1 UK (PS1/26, entrée en vigueur 1er janvier 2027) ; le « specialised lending » britannique reste structuré autour de project finance / object finance / commodity finance (IPRE traité à part), catégories qui excluent structurellement la venture debt (voir §5). Suppression du SME support factor Pilier 1, remplacée par un « SME Lending Adjustment » Pilier 2A. | Repose, comme la CRR, sur une définition du specialised lending centrée sur une entité ad hoc adossée à un actif — incompatible avec la structure d'un prêt à une société opérationnelle VC-backed. | Pas de données publiques de portefeuille désagrégées identifiées pour HSBC Innovation Banking UK. |
| **Royaume-Uni — British Business Bank** | Pas de garantie dédiée à la venture debt identifiée : le programme ENABLE Guarantee (garantie de portefeuille, part senior garantie par l'État) a été remplacé en juillet 2024 par le **Growth Guarantee Scheme** (garantie à 70 %, plafond £2m par facilité), généraliste PME, pas spécifique venture debt. Le soutien ciblé scale-up/VC passe plutôt par **British Patient Capital**, filiale commerciale de la BBB, qui investit en fonds de venture/growth (equity, dette et hybrides) plutôt que de garantir des prêts bancaires individuels. | Mécanisme de **partage de risque public en overlay** du bilan bancaire (ou d'investissement direct en fonds), pas un calibrage de pondération de risque réglementaire. | ENABLE/Growth Guarantee : ~21 transactions, ~£1,8 md d'engagements de garantie vivants (généraliste PME). British Patient Capital : >£1,4 md investi, effet multiplicateur revendiqué de ~x6 sur capital privé mobilisé. |
| **Singapour — MAS / Enterprise Singapore** | **Enterprise Financing Scheme – Venture Debt (EFS-VD)** : garantie publique (gouvernement, via Enterprise Singapore) sur des prêts de venture debt octroyés par des Participating Financial Institutions (banques et non-bancaires), jusqu'à S$5 M par emprunteur. Pas de règle prudentielle MAS dédiée identifiée pour les banques participantes — le risque de crédit résiduel des banques est réduit par la garantie publique, pas par un poids de risque différencié. | Partage de risque public explicitement dédié à la venture debt (contrairement au UK Growth Guarantee Scheme, généraliste) — mais logique de garantie, pas de prudentiel bancaire dédié. | Pas de données agrégées de portefeuille EFS-VD identifiées publiquement lors de cette recherche. |
| **Canada — Business Development Bank of Canada (BDC)** | Société d'État fédérale (Crown corporation), pas une banque commerciale déposante soumise au régime prudentiel standard du BSIF/OSFI ; statutairement mandatée pour faire du financement (dont venture debt) et du capital-risque aux entrepreneurs canadiens, capitalisée par l'État. | Route de financement **hors bilan bancaire commercial** : le risque est porté par l'État via une institution ad hoc, pas absorbé par le système bancaire privé régulé sous Basel. | >107 000 entreprises servies (directement et via partenaires) ; branche BDC Capital dédiée au capital-risque et à la dette de croissance technologique. |
| **Japon — Development Bank of Japan (DBJ)** | Banque de développement détenue à 100 % par l'État japonais (Ministère des Finances), offrant financement structuré, ABL, mezzanine et equity aux startups via son « Startup Support Center ». | Même logique que le modèle canadien/EIB : institution publique dédiée, hors du cadre bancaire commercial standard. | Pas de données chiffrées désagrégées sur le volume spécifique de venture debt identifiées. |
| **Israël** | Pas de régime bancaire prudentiel dédié identifié. Les grandes banques (Leumi, Hapoalim) financent l'écosystème tech via des offres classiques de crédit corporate, mais la venture debt proprement dite semble être portée principalement par des fonds de dette privés spécialisés plutôt que par le secteur bancaire réglementé. | — (absence de comparateur bancaire direct) | **Confiance faible** : aucune source consultée ne confirme ou n'infirme de façon définitive l'absence totale de pratique bancaire dédiée ; à vérifier plus avant si ce point s'avère décisif pour l'UE. |
| **Australie — APRA** | Pas de régime prudentiel bancaire dédié. Les prêteurs non bancaires (non-ADI, sans licence de dépôt) dominent le segment du financement risqué aux PME/scale-ups et échappent structurellement à la supervision macroprudentielle de l'APRA applicable aux banques ; l'APRA ne collecte des données statistiques qu'au-delà de seuils d'encours (A$50 M+). | Route de contournement **structurel** du prudentiel bancaire (absence de licence de dépôt), plutôt qu'un régime dédié au sein du système bancaire. | Part des PME envisageant un prêteur non bancaire passée de ~7 % il y a une décennie à plus de 50 % aujourd'hui (tous segments PME confondus, pas seulement venture debt) — tendance structurelle de désintermédiation bancaire, à ne pas attribuer uniquement à la venture debt. |
| **UE (pour mémoire — modèle existant hors CRR)** | Pas de compartiment CRR dédié à ce jour. La venture debt européenne est financée principalement par (i) des fonds de dette privés non régulés comme des banques (Kreos/BlackRock, Claret Capital, Bootstrap Europe, Runway Growth Europe…), (ii) la BEI en direct (« EIB Venture Debt »), et (iii) des banques publiques nationales (Bpifrance en France, KfW en Allemagne) via prêts directs et garanties de portefeuille (mécanisme proche du Growth Guarantee Scheme britannique). Le FEI déploie par ailleurs des garanties de portefeuille InvestEU pour des fonds de venture debt privés. | — | EIF/InvestEU : ~11 Md€ de capacité de garantie pour les produits equity/dette combinés (tous produits SME, pas seulement venture debt) ; Bpifrance « Prêt Croissance » : 10 k€–300 k€ par entreprise, cible PME/ETI déjà établies (pas strictement le stade « venture-backed pré-profit »). |

---

## 2. États-Unis

### 2.1 Traitement prudentiel bancaire — SVB comme cas de référence

Silicon Valley Bank était une banque à charte de l'État de Californie (agréée par le DFPI), membre du Système fédéral de réserve et donc soumise à la supervision consolidée de la Réserve fédérale au niveau de sa société holding (SVB Financial Group). Elle relevait du régime standardisé de Bâle III (« Basel III Standardized Approach »), et non des « approches avancées » (IRB) réservées aux plus grandes banques américaines — ses propres communications Pillar III le confirment (documents « Basel III Standardized Approach Disclosures »).

**Il n'existait pas de catégorie de fonds propres spécifique pour la venture debt.** Sous l'approche standardisée américaine, un prêt à une entreprise financée par du capital-risque est traité comme une exposition « corporate » générique — pondérée à 100 % sauf garanties ou sûretés éligibles réduisant ce poids. C'est exactement ce que confirme, a posteriori, le bulletin OCC 2025-45 (voir §2.3) : *« assign a 100 percent risk weight to all corporate exposures »* pour les prêts venture, sauf mitigation par garant ou collatéral éligible.

### 2.2 La cause de l'effondrement : risque de taux/ALM, pas le risque de crédit du portefeuille venture

Les analyses post-mortem — le rapport de la Fed (« Review of the Federal Reserve's Supervision and Regulation of Silicon Valley Bank », avril 2023) et l'examen du DFPI californien (mai 2023) — convergent : la défaillance de SVB est d'abord un problème de **gestion actif-passif et de risque de taux**, pas un problème de qualité de crédit sur son portefeuille de venture debt.

- SVB avait classé ~46 % de son bilan en titres détenus jusqu'à échéance (HTM), essentiellement des obligations d'État et titres adossés à des agences fédérales à duration longue, financés par des dépôts massivement non assurés et volatils issus de l'écosystème VC/tech.
- La hausse des taux de la Fed (0,25 % à mi-2022 à 4,5 % fin 2022) a fait fondre la valeur de marché de ce portefeuille HTM sans que la valeur des dépôts ne bouge, créant un décalage de duration classique.
- Le déclencheur de la panique bancaire (retrait de ~42 Md$ de dépôts en une seule journée, le 9 mars 2023) est une **crise de liquidité par la structure du passif** (concentration extrême de dépôts non assurés dans un même écosystème sectoriel), pas une vague de défauts sur les crédits venture consentis à l'actif.
- Le DFPI a certes examiné la qualité du portefeuille de prêts (fonction de revue de crédit interne, provisionnement CECL) dans le cadre de son contrôle de routine, mais aucun des rapports post-mortem ne pointe une dégradation du crédit venture comme cause de la faillite.
- Facteur aggravant indirect côté régulation : l'Economic Growth, Regulatory Relief, and Consumer Protection Act de 2018 (EGRRCPA) a relevé de 50 à 250 Md$ le seuil d'application automatique des normes prudentielles renforcées (« enhanced prudential standards » — LCR, tests de résistance renforcés) de la loi Dodd-Frank. SVB, dont le bilan est passé d'environ 50 à plus de 200 Md$ entre 2019 et 2022, est restée sous ce seuil relevé, échappant ainsi aux exigences de liquidité renforcées qui l'auraient probablement exposée plus tôt à ce risque de duration. Le Bank Policy Institute a toutefois souligné que la loi laissait à la Fed un pouvoir discrétionnaire d'appliquer ces standards aux banques de 100-250 Md$, pouvoir qu'elle n'a pas exercé pour SVB.

**Conclusion pour le sujet EU :** le précédent SVB documente une défaillance de supervision de la liquidité et du risque de taux, **pas** une lacune du cadre de pondération du risque de crédit sur la venture debt elle-même. Il ne constitue donc pas, en tant que tel, un argument empirique direct en faveur (ou en défaveur) d'un compartiment de crédit dédié — mais il illustre un risque connexe et réel pour tout établissement bancaire fortement concentré sur l'écosystème VC : la corrélation entre risque de dépôt (passif) et cycle de financement du capital-risque (actif), qui dépasse le strict risque de crédit sur les prêts venture.

### 2.3 Réponse réglementaire post-SVB spécifique à la venture debt : une guidance supervisoire, pas un changement de Pilier 1

L'OCC a réagi de façon ciblée sur le segment venture lending, mais par la voie de la **supervision qualitative (Pilier 2)**, sans toucher à la pondération de risque réglementaire (Pilier 1) :

- **Bulletin OCC 2023-34** (1er novembre 2023) : première guidance dédiée, émise dans le contexte de l'« incertitude accrue » créée par la crise bancaire régionale de mars 2023 et l'arrivée de nouveaux entrants sur le marché de la venture debt. Elle a été largement perçue par le secteur comme dissuasive (décourageant implicitement l'activité).
- **Bulletin OCC 2025-45** (5 décembre 2025) : révision qui abroge et remplace le bulletin 2023-34, en conservant l'ossature du dispositif mais avec un changement de ton explicite : *« the agency does not want to discourage prudent venture lending »*. Points clés :
  - Pas de catégorie de fonds propres dédiée ; confirmation du poids de risque de 100 % en approche standard pour les expositions corporate, sauf mitigation.
  - Exigence d'un **appétit au risque formalisé et approuvé par le conseil d'administration**, avec limites de concentration par stade de développement, secteur et facteur de risque.
  - Obligation d'**agréger** les expositions venture dispersées dans différents portefeuilles internes ou intitulés comptables — signe que le risque de sous-déclaration/fragmentation interne était identifié comme un problème réel.
  - Standards de souscription explicites : un tour de table futur non engagé (« uncommitted future equity raise ») **n'est pas** une source de remboursement primaire acceptable ; des covenants de liquidité résiduelle (« remaining-months-liquidity ») seuls ne suffisent pas à garantir le remboursement ; les prêts à revenus récurrents doivent être ancrés sur des projections de flux de trésorerie réalistes.
  - Renforcement du provisionnement (allowance for credit losses) reflétant une expérience de pertes plus élevée et plus volatile que le crédit corporate classique.

Ce dispositif est structurellement proche d'un régime de type SREP européen (limites de concentration, gouvernance, provisionnement) plutôt que d'un compartiment CRR de type article 147 (pondération de risque différenciée par slotting). **C'est le point le plus directement transposable pour l'UE** : les autorités américaines ont choisi de traiter le risque venture debt par la qualité de la gestion du risque et la gouvernance plutôt que par un recalibrage du capital réglementaire.

Les autres réformes post-SVB (relèvement de l'assurance-dépôts ciblée, projet de réforme de la FDIC sur les dépôts non assurés, resolution planning renforcé pour les banques de 50-100 Md$, propositions « Basel Endgame » pour les banques de 100 Md$+) visent le **passif** (concentration de dépôts, liquidité, résolution), pas le traitement de l'actif venture debt.

### 2.4 Le modèle BDC : financement hors bilan bancaire

Les Business Development Companies (BDC) cotées — Hercules Capital (HTGC), TriplePoint Venture Growth (TPVG), Trinity Capital (TRIN), Horizon Technology Finance, Runway Growth Finance — constituent la principale alternative structurelle au financement bancaire de la venture debt aux États-Unis.

- **Base légale :** Investment Company Act de 1940 — les BDC sont des véhicules d'investissement fermés, cotés en bourse, réglementés par la SEC, **pas** des banques déposantes soumises à un régulateur prudentiel (OCC/Fed/FDIC). Elles ne prennent pas de dépôts.
- **Encadrement du levier, pas du crédit :** le contrôle réglementaire porte sur un **ratio de couverture d'actifs** (actifs/dette), fixé à 200 % à l'origine, ramené à 150 % depuis le Small Business Credit Availability Act de 2018 pour les BDC ayant opté pour ce régime — ce qui autorise un levier dette/capitaux propres jusqu'à 2:1 (contre 1:1 auparavant). Il n'y a pas de pondération de risque de crédit par actif à la manière de Bâle.
- **Modèle économique distinct :** les BDC construisent leur rentabilité autant sur les intérêts que sur la « couverture en warrants » (typiquement 3-10 % du principal du prêt), qui capte une partie de la création de valeur en cas de succès de la société financée — un mécanisme de compensation du risque de crédit élevé qui n'a pas d'équivalent dans le cadre CRR bancaire classique.
- **Après SVB :** la presse spécialisée (PitchBook) rapporte un déplacement net de parts de marché vers les BDC spécialisées et les fonds de crédit privé après mars 2023, ces acteurs n'étant pas soumis au même risque de retrait de dépôts.
- **Qualité de portefeuille hétérogène :** le rendement effectif du portefeuille d'Hercules Capital s'établissait à ~13,0 % au T1 2025 (en baisse depuis ~13,7 % au T4 2024) ; le taux de créances en non-accrual de TriplePoint Venture Growth atteignait ~3,7 % en valeur de marché — nettement supérieur à d'autres BDC, signe que la dispersion de qualité de crédit au sein même du secteur BDC est significative et doit tempérer toute lecture d'un modèle uniformément robuste.

---

## 3. Royaume-Uni

### 3.1 HSBC Innovation Banking (ex-SVB UK) et le régime PRA

Aucune source consultée ne fait état d'un régime de fonds propres dédié à la venture debt au Royaume-Uni. Le cadre applicable est le CRR « onshored » britannique, en cours de remplacement par **Bâle 3.1 UK**, dont la version finale (PS1/26, publiée le 20 janvier 2026, entrée en vigueur au 1er janvier 2027) :

- Supprime le « SME support factor » en Pilier 1 (le rabais de pondération qui existait pour les expositions PME), en le remplaçant par un « SME Lending Adjustment » calculé en Pilier 2A — c'est-à-dire un ajustement discrétionnaire spécifique à chaque établissement plutôt qu'une règle uniforme.
- Introduit une pondération de risque de 400 % pour les expositions en **capital-risque en fonds propres** (equity venture capital) et de 250 % pour d'autres catégories d'actions — mais il s'agit d'une pondération sur des positions actions/participations, pas sur des prêts de venture debt.
- Réaffirme la structure classique du specialised lending (project finance, object finance, commodity finance ; l'income-producing real estate étant traité séparément) — sans créer de cinquième catégorie pour la venture debt.

**Aucune indication publique** trouvée que les prêts de venture debt d'HSBC Innovation Banking soient classés en « specialised lending » plutôt qu'en exposition corporate/PME générique — ce qui serait de toute façon structurellement difficile, pour les mêmes raisons juridiques que sous la CRR (voir §5).

### 3.2 British Business Bank — de l'ENABLE Guarantee au Growth Guarantee Scheme

Le programme ENABLE Guarantee a été **remplacé le 1er juillet 2024** par le **Growth Guarantee Scheme (GGS)**, prolongé jusqu'en mars 2030 lors de la revue des dépenses 2025. C'est un mécanisme de **partage de risque public**, pas un traitement prudentiel :

- L'État garantit une part senior (70 % pour le GGS) d'un portefeuille de financements PME (prêts à terme, découverts, financement d'actifs, affacturage) ; en échange, l'établissement prêteur paie une commission.
- Effet recherché : « libérer du capital réglementaire » pour les banques, augmentant ainsi leur capacité de prêt, sans modifier la pondération de risque elle-même — le mécanisme joue sur l'atténuation du risque (crédit garanti par l'État = pondération réduite via la garantie elle-même, un mécanisme déjà prévu par la CRR pour les garanties souveraines éligibles), pas sur une catégorie bespoke.
- **Ce programme n'est pas spécifique à la venture debt** : il est généraliste PME. Le véhicule le plus proche d'un soutien ciblé au capital de croissance/venture est **British Patient Capital** (filiale commerciale à 100 % de la British Business Bank, dotée de 2,5 Md£), qui investit — en fonds propres, en dette et en instruments hybrides — dans des fonds de venture/growth capital plutôt que de garantir des prêts bancaires individuels. Plus de 1,4 Md£ engagés, avec un effet de levier revendiqué sur capital privé tiers d'environ x6.

---

## 4. Autres juridictions pertinentes

### 4.1 Singapour — le seul mécanisme de garantie publique *explicitement* dédié à la venture debt identifié

Le **Enterprise Financing Scheme – Venture Debt (EFS-VD)**, opéré par Enterprise Singapore avec le soutien de la MAS, est le mécanisme le plus directement comparable à ce que l'énoncé de la tâche envisageait pour le UK ENABLE Guarantee — mais il est spécifiquement calibré pour la venture debt, contrairement au régime britannique généraliste :

- Partage de risque gouvernemental sur des prêts de venture debt et warrants octroyés par des Participating Financial Institutions (banques et non-bancaires).
- Cible les entreprises à forte croissance sans actifs suffisants pour du crédit bancaire classique (chiffre d'affaires groupe ≤ S$500 M, ≥ 30 % de détention locale).
- Plafond typique de S$5 M par emprunteur.
- Aucune règle prudentielle MAS dédiée identifiée pour les banques participantes — l'atténuation du risque de crédit passe par la garantie publique (mécanisme d'atténuation reconnu par tout cadre CRR-like), pas par une pondération de risque bespoke.

### 4.2 Canada — Business Development Bank of Canada (BDC) : le modèle « banque de développement publique »

La BDC canadienne (à ne pas confondre avec les Business Development Companies américaines — collision de sigle à noter) est une société d'État fédérale, statutairement mandatée pour le financement et le capital-risque aux entrepreneurs canadiens (Business Development Bank of Canada Act, 1995). Elle sert plus de 107 000 entreprises via un réseau national, avec une branche dédiée (BDC Capital) au capital-risque et à la dette de croissance technologique. Le risque est porté directement par le bilan de l'État plutôt que par le système bancaire commercial régulé sous le cadre prudentiel standard du BSIF (OSFI).

### 4.3 Japon — Development Bank of Japan (DBJ)

Banque de développement détenue à 100 % par le gouvernement japonais (via le ministère des Finances), le DBJ propose financement structuré, asset-based lending, mezzanine et capital-investissement aux startups via son Startup Support Center. Même logique que le modèle canadien et l'action directe de la BEI dans l'UE : une institution publique dédiée en dehors du cadre bancaire commercial standard, plutôt qu'un compartiment prudentiel au sein du secteur bancaire privé.

### 4.4 Israël — écosystème tech mature mais sans comparateur bancaire prudentiel dédié identifié (confiance faible)

Malgré un écosystème technologique et capital-risque parmi les plus denses au monde, aucune source consultée ne documente un régime prudentiel bancaire bespoke pour la venture debt en Israël. Les grandes banques (Bank Leumi, Bank Hapoalim) financent le secteur tech via des lignes de crédit corporate classiques et des investissements directs, mais la littérature accessible suggère que la venture debt proprement dite — prêts à des sociétés pré-profit adossés à la perspective d'un futur tour de table — est portée principalement par des fonds de dette privés spécialisés, pas par le bilan bancaire réglementé. **Ce point mériterait une vérification complémentaire directement auprès de la Bank of Israel (Banking Supervision Department) si l'écosystème israélien s'avère stratégique pour la comparaison finale**, cette recherche n'ayant identifié aucune publication de la Bank of Israel spécifiquement dédiée au sujet.

### 4.5 Australie — contournement structurel du prudentiel via le statut non-ADI

L'APRA ne régule les prêteurs non bancaires (« non-ADI », sans licence de dépôt) qu'a minima : collecte de données statistiques uniquement au-delà de seuils d'encours (A$50 M et plus), sans application des règles macroprudentielles bancaires. Une part croissante du financement des PME et scale-ups — y compris probablement une partie de la venture debt — passe par ces acteurs non-ADI, qui échappent structurellement au périmètre prudentiel bancaire plutôt que d'en relever avec un traitement dédié. La hausse de la part des PME envisageant un prêteur non bancaire (de ~7 % il y a dix ans à plus de 50 % aujourd'hui, tous segments confondus) illustre une tendance structurelle de désintermédiation bancaire en Australie, dont la venture debt n'est qu'une composante parmi d'autres (immobilier commercial, financement d'actifs, etc.) — attribution causale à manier avec prudence.

### 4.6 Suisse — écartée du périmètre

Aucun acteur bancaire suisse de premier plan spécialisé en venture debt n'a été identifié lors de cette recherche (les grandes banques suisses n'occupent pas de position comparable à SVB ou HSBC Innovation Banking sur ce segment), et aucun mécanisme réglementaire spécifique n'est apparu dans les recherches menées. Ce point n'est donc pas approfondi ici faute de matière significative, mais pourrait être révisé si des informations complémentaires émergent.

---

## 5. Le point conceptuel central : la venture debt ne rentre structurellement pas dans la définition existante du « specialised lending »

C'est sans doute l'élément le plus utile pour la suite du travail de `policy-innovator`.

L'article 147(8) CRR définit le specialised lending par trois caractéristiques cumulatives :
1. l'exposition porte sur une entité **créée spécifiquement pour financer ou exploiter des actifs physiques** (ou une exposition économiquement comparable) ;
2. les arrangements contractuels donnent au prêteur un **degré substantiel de contrôle** sur les actifs et les revenus qu'ils génèrent ;
3. la **source principale de remboursement est le revenu généré par les actifs financés**, et non la capacité indépendante d'une entreprise commerciale plus large.

Une opération de venture debt typique **viole structurellement les critères (1) et (3)** : l'emprunteur est une société opérationnelle (pas une entité ad hoc adossée à un actif physique), et la source de remboursement anticipée est précisément « la capacité indépendante d'une entreprise commerciale plus large » — via ses futurs revenus d'exploitation, un futur tour de table en capital, ou le produit d'une sortie (cession, IPO). C'est d'ailleurs exactement ce que l'OCC vient de formaliser côté supervision qualitative (« un tour de table futur non engagé n'est pas une source de remboursement primaire acceptable ») sans pour autant en faire un critère de catégorisation Pilier 1.

**Conséquence pratique :** un compartiment prudentiel CRR dédié à la venture debt ne pourrait pas être conçu comme une simple cinquième sous-catégorie de specialised lending par extension des critères existants — il faudrait une architecture de critères de slotting entièrement nouvelle, fondée sur des facteurs de risque différents (qualité et réputation du sponsor VC, stade de développement, probabilité et calendrier d'un futur tour de financement, structure de warrants/equity kicker, etc.) plutôt que sur la valeur et le flux de revenu d'un actif physique sous-jacent. Aucune des juridictions étudiées n'a construit un tel cadre à ce jour.

---

## 6. Synthèse narrative — ce qui est le plus instructif pour l'UE

**Aucun précédent de compartiment prudentiel bancaire Pilier 1 dédié à la venture debt n'a été identifié dans les juridictions étudiées.** Toutes les réponses observées relèvent de l'une des trois familles suivantes, structurellement distinctes de ce qu'envisage le projet UE :

1. **Supervision qualitative renforcée sur exposition générique (États-Unis, OCC)** — c'est la réponse la plus proche d'un « signal » réglementaire ciblé sur la venture debt, mais elle opère en Pilier 2 (gouvernance, concentration, provisionnement), pas en Pilier 1 (pondération de risque). C'est un précédent transposable pour l'UE **sans modification de la CRR** — via la SREP/EBA guidelines, par exemple — mais qui ne répond pas à l'objectif affiché d'un compartiment prudentiel dédié au sens de l'article 147.
2. **Sortie du bilan bancaire prudentiel vers un véhicule ad hoc** — soit un véhicule d'investissement coté encadré par un régulateur des marchés plutôt que prudentiel (BDC américaines, SEC), soit une banque de développement publique capitalisée par l'État (BDC Canada, DBJ Japon, et — au sein même de l'UE — la BEI en direct et les banques nationales de développement comme Bpifrance ou la KfW). L'UE dispose déjà, de fait, de cette famille de solutions au niveau supranational et national — ce qui interroge sur la valeur ajoutée réelle d'un compartiment CRR bancaire par rapport à un renforcement de ces canaux existants.
3. **Garantie publique en overlay du bilan bancaire (Royaume-Uni, Singapour)** — atténuation du risque de crédit par garantie plutôt que par pondération dédiée ; seul Singapour a construit un dispositif *explicitement* ciblé sur la venture debt (EFS-VD), le dispositif britannique équivalent (ENABLE/Growth Guarantee) étant généraliste PME.

**Ce que cela implique pour l'UE :**

- **L'UE serait pionnière** si elle introduisait un compartiment CRR Pilier 1 dédié — ce qui signifie l'absence de tout étalonnage empirique externe pour calibrer des paramètres de risque (pondérations, LGD, facteurs de slotting) spécifiques à la venture debt. C'est à la fois une opportunité (aucun cadre existant à corriger) et un risque de mauvais calibrage (aucune donnée de perte historique consolidée, contrairement au specialised lending classique qui s'appuie sur des décennies de données project finance).
- Le dispositif OCC 2023-34/2025-45 constitue la source la plus riche de critères qualitatifs déjà « testés » en conditions réelles (définition des sources de remboursement acceptables, exigences d'agrégation des expositions, limites de concentration) — un matériau directement réutilisable pour construire les **critères qualificatifs** d'un éventuel compartiment européen, même si celui-ci allait plus loin en touchant au Pilier 1.
- Le précédent SVB doit être manié avec prudence dans le débat : il documente un risque de **corrélation actif-passif propre aux banques fortement concentrées sur l'écosystème VC** (dépôts volatils + duration longue à l'actif), pas une défaillance du crédit venture lui-même. Un argumentaire européen qui invoquerait SVB pour justifier un tampon de capital sur le crédit venture serait donc mal fondé sur les faits ; l'argument pertinent tiré de SVB porte plutôt sur la **gestion de la concentration sectorielle et du risque de liquidité** d'un établissement spécialisé, sujet distinct de celui du compartiment CRR envisagé (qui porte sur le risque de crédit).
- L'incompatibilité structurelle de la venture debt avec la définition CRR actuelle du specialised lending (art. 147(8)) signifie qu'un compartiment dédié devrait être bâti sur une base juridique et des facteurs de risque entièrement nouveaux, non sur une extension des catégories existantes — un point de méthode à anticiper dès la conception du projet.
- Le modèle BDC américain offre un contrepoint utile : il montre qu'un cadre de fonds propres fondé sur le **levier du véhicule** (asset coverage ratio) plutôt que sur la **pondération de l'actif** peut fonctionner pour ce type de risque — une piste alternative à explorer si l'option retenue s'oriente vers un véhicule dédié plutôt que vers un compartiment bancaire CRR classique (même si cela sortirait du périmètre bancaire visé par le projet UE).

---

## Sources principales consultées

- [Federal Reserve — Review of the Federal Reserve's Supervision and Regulation of Silicon Valley Bank (avril 2023)](https://www.federalreserve.gov/publications/files/svb-review-20230428.pdf)
- [DFPI — Review of DFPI's Oversight and Regulation of Silicon Valley Bank (mai 2023)](https://dfpi.ca.gov/wp-content/uploads/sites/337/2023/05/Review-of-DFPIs-Oversight-and-Regulation-of-Silicon-Valley-Bank.pdf)
- [Bank Policy Institute — Congress's 2018 Regulatory Tailoring Law Did Not Preclude the Fed from Applying Enhanced Prudential Standards to SVB](https://bpi.com/congresss-2018-regulatory-tailoring-law-did-not-preclude-the-fed-from-applying-enhanced-prudential-standards-to-silicon-valley-bank/)
- [OCC Bulletin 2025-45 — Commercial Lending: Venture Loans to Companies in an Early, Expansion, or Late Stage of Corporate Development](https://occ.gov/news-issuances/bulletins/2025/bulletin-2025-45.html)
- [Troutman Pepper Locke — OCC Signals Openness to Venture Lending — With Clear Guardrails](https://www.troutman.com/insights/occ-signals-openness-to-venture-lending-with-clear-guardrails-for-banks-and-tech-lenders/)
- [Morrison Foerster — OCC Issues Guidance on Venture Lending (bulletin 2023-34)](https://www.mofo.com/resources/insights/231115-occ-issues-guidance-on-venture-lending)
- [PitchBook — Venture debt BDCs thrive in VC, bank pullback](https://pitchbook.com/news/articles/business-development-companies-bdcs-venture-lending-earnings-2023-q1)
- [Seward & Kissel — Operating Business Development Companies: A Brief Overview](https://www.sewkis.com/insights/operating-business-development-companies-a-brief-overview/)
- [Seeking Alpha — TriplePoint Venture Growth: Be Careful With This 15% Yield](https://seekingalpha.com/article/4855733-triplepoint-venture-growth-careful-with-15-percent-yield)
- [Grant Thornton — Basel 3.1: PRA clarifies a standardised approach to credit risk](https://www.grantthornton.co.uk/insights/basel-3.1-pra-clarifies-a-standardised-approach-to-credit-risk/)
- [Katalysys — UK Basel 3.1: Credit risk standardised approach – exposures to corporates](https://www.katalysys.com/insights/basel-3-1-cp-16-22-corporate-exposures)
- [Bank of England — SME and infrastructure lending adjustments](https://www.bankofengland.co.uk/prudential-regulation/publication/2025/may/sme-and-infrastructure-lending-adjustments)
- [British Business Bank — How the ENABLE Guarantees Programme works](https://www.british-business-bank.co.uk/finance-options/debt-finance/enable-programmes/enable-guarantees)
- [British Business Bank — Growth Guarantee Scheme (GGS)](https://www.british-business-bank.co.uk/finance-options/debt-finance/growth-guarantee-scheme)
- [British Business Bank — £2.5bn British Patient Capital Programme](https://www.british-business-bank.co.uk/news-and-events/news/2-5bn-british-patient-capital-programme-launched-enable-long-term-investment-innovative-companies-across-uk)
- [Enterprise Singapore — Enterprise Financing Scheme – Venture Debt](https://www.enterprisesg.gov.sg/financial-support/enterprise-financing-scheme---venture-debt)
- [MAS — Enterprise Financing](https://www.mas.gov.sg/development/enterprise-finance)
- [Business Development Bank of Canada Act (SC 1995, c. 28)](https://laws-lois.justice.gc.ca/eng/acts/b-9.9/FullText.html)
- [Development Bank of Japan — Support for Startups](https://www.dbj.jp/en/service/advisory/ssc/)
- [EIF — Discover EIF's InvestEU programme](https://www.eif.org/flagship-initiatives/investeu/overview)
- [EIB — Venture Debt](https://www.eib.org/en/products/equity/venture-debt/index)
- [Bpifrance — Prêt Croissance](https://www.bpifrance.fr/catalogue-offres/pret-croissance)
- [judict.eu — Article 147 CRR (texte consolidé)](https://judict.eu/en/hla/32013R0575-X/article-147)
- [EBA — Final draft RTS on assigning risk weights to specialised lending exposures](https://www.eba.europa.eu/documents/10180/1489608/e915f563-acba-485d-a05a-0756ce8360dd/EBA-2016-RTS-02%20(Final%20RTS%20on%20specialised%20lending%20exposures).pdf)
- [Herbert Smith Freehills Kramer — Private credit in Australia – the regulated "unregulated"](https://www.hsfkramer.com/insights/2024-09/private-credit-in-australia-the-regulated-unregulated)
