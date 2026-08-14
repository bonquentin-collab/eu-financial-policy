# Brief micro-financier — Règlement EuVECA (UE) n° 345/2013, tel que modifié par (UE) 2017/1991

**Agent : micro-financial-analyst — Pipeline d'analyse de politique financière européenne**
**Date de production : août 2026**

---

## 0. Contexte immédiat

La Commission européenne a ouvert le 15 janvier 2026 une consultation ciblée sur la réforme des fonds de capital-risque et de croissance (EuVECA + AIFMD + régimes nationaux), close le 12 mars 2026, avec adoption d'une révision attendue au T3 2026. C'est la troisième révision du dispositif depuis 2013. Ce brief analyse donc un instrument dont la mécanique est bien rodée mais dont le design est activement remis en cause au moment même de la rédaction.

---

## 1. Mécanismes réels de l'instrument

### 1.1 Structure juridique et qui peut l'utiliser

EuVECA n'est pas un statut de fonds au sens de véhicule juridique dédié : c'est un **label facultatif** apposé sur un FIA (fonds d'investissement alternatif) déjà existant, sous forme juridique nationale (SCSp luxembourgeoise, FCP français, Spezial-AIF allemand, etc.). Le fonds et son gestionnaire doivent être établis dans l'UE. Concrètement, un gérant :
- constitue un FIA classique dans un véhicule national,
- s'enregistre auprès de son autorité nationale compétente (délai réglementaire garanti de deux mois pour un nouveau gérant, un mois pour l'ajout d'un nouveau fonds à un enregistrement existant, sans frais de dossier),
- obtient en échange le droit d'utiliser la dénomination « EuVECA » et le passeport de commercialisation associé.

Deux populations de gérants coexistent depuis EuVECA II (2017) : les petits gérants **sous le seuil AIFMD de 500 M€** d'actifs sous gestion, pour qui EuVECA est une alternative légère à l'agrément complet AIFMD (pas d'obligation de dépositaire, pas de règles de rémunération AIFMD, capital réduit) ; et les gérants **déjà agréés AIFMD** (donc au-dessus de 500 M€, ou en dessous mais optant volontairement pour l'agrément complet), qui peuvent aussi labelliser certains de leurs fonds EuVECA pour élargir leur base d'investisseurs commercialisables (voir 1.3).

### 1.2 Test d'éligibilité des actifs (règle des 70 %)

Un fonds EuVECA doit investir au moins 70 % du total de ses apports en capital et du capital engagé non appelé dans des « investissements éligibles » :
- instruments de fonds propres ou quasi-fonds propres émis par des « entreprises de portefeuille éligibles » : entreprises non cotées de moins de 500 salariés (seuil doublé par EuVECA II — il était de 250 salariés à l'origine en 2013, avec un plafond de 50 M€ de chiffre d'affaires ou 43 M€ de bilan), ou PME cotées sur un marché de croissance des PME avec une capitalisation boursière inférieure à 200 M€ ;
- prêts garantis ou non garantis consentis à ces entreprises, plafonnés dans l'enveloppe des 70 % ;
- parts d'autres fonds EuVECA (investissement secondaire limité).
Les 30 % restants sont libres (liquidités, instruments de couverture, autres actifs). Les entreprises cibles ne peuvent être ni organismes de placement collectif, ni établissements de crédit, ni entreprises d'investissement, ni entreprises d'assurance.

### 1.3 Contreparties typiques

- **Gérants** : équipes de capital-risque de petite et moyenne taille (majoritairement early-stage/growth), souvent des maisons indépendantes plutôt que des filiales captives de grands gestionnaires généralistes — la donnée disponible ne permet pas de trancher précisément la répartition captif/indépendant dans l'univers EuVECA, mais le profil de taille (sous 500 M€) exclut structurellement les très grandes plateformes.
- **LPs (souscripteurs)** : le passeport EuVECA permet une commercialisation transfrontière auprès de trois catégories : clients professionnels au sens MiFID, personnes fortunées (« semi-professionnels ») engageant un minimum de 100 000 € avec attestation écrite de risque, et dirigeants/cadres du gérant lui-même. C'est ce dernier point (accès élargi aux quasi-retail via le seuil de 100 000 €) qui distingue le plus nettement EuVECA de l'AIFMD classique, où la commercialisation à des particuliers fortunés hors clients professionnels MiFID est plus contrainte par les règles de placement privé national (NPPR).
- **Entreprises cibles** : PME et scale-ups non cotées de moins de 500 salariés — un périmètre qui, depuis 2017, couvre une bonne partie des « licornes » européennes en formation, bien au-delà de la définition standard UE de la PME (250 salariés).

### 1.4 Capital et coûts du gérant

Depuis le 1er mars 2018, un gérant EuVECA doit détenir un capital initial minimum de 50 000 € et des fonds propres à tout moment égaux au plus élevé de : (a) un huitième des frais généraux fixes de l'exercice précédent, ou (b) 50 000 € — avec une charge additionnelle de 0,02 % au-delà de 250 M€ d'actifs sous gestion. C'est un ordre de grandeur très inférieur aux exigences de capital et d'infrastructure de gouvernance (dépositaire, fonction de gestion des risques indépendante, politique de rémunération formalisée) qu'impose l'agrément AIFMD plein.

### 1.5 Traitement prudentiel côté investisseur assureur (mécanisme documenté partiellement)

Sous Solvency II, les investissements en EuVECA/EuSEF bénéficient — comme les parts d'ELTIF — d'un traitement de capital aligné sur celui des actions « qualifiantes » plutôt que sur le traitement plus pénalisant réservé aux investissements alternatifs non qualifiés. C'est un canal d'incitation réel pour les assureurs-LPs, documenté par la littérature réglementaire sur Solvency II, mais je n'ai pas pu vérifier le chiffre exact du facteur de choc applicable spécifiquement à EuVECA (par opposition à ELTIF ou aux infrastructures qualifiantes) dans les sources consultées — à traiter comme mécanisme confirmé en direction, non confirmé en calibrage précis.

---

## 2. Incitations des participants sous la règle actuelle

### 2.1 Le seuil des 500 M€ AIFMD comme variable de décision de croissance du gérant

Le seuil n'est pas neutre pour les décisions de levée de fonds d'un gérant individuel. Un gérant à 480 M€ d'actifs sous gestion qui envisage un nouveau véhicule a une incitation concrète à :
- **calibrer la taille cible de son prochain fonds pour rester sous 500 M€** plutôt que de lever au maximum de la demande LP disponible, afin d'éviter le basculement vers l'agrément AIFMD complet (dépositaire obligatoire, fonction de gestion des risques indépendante, reporting AIFMD complet, contraintes de rémunération) ;
- ou, à l'inverse, **franchir délibérément et rapidement le seuil** en une seule levée plutôt que de croître progressivement, pour amortir le coût fixe de mise en conformité AIFMD sur une base d'actifs plus large dès le départ — un comportement de « saut » plutôt que de croissance linéaire.
Le seuil est identique pour un fonds de capital-risque non endetté et pour un fonds à effet de levier (où le seuil tombe à 100 M€), ce qui pénalise structurellement davantage les stratégies de croissance/growth capital utilisant du financement en dette (venture debt, structures hybrides) que le capital-risque pur equity.

### 2.2 La règle des 70 % comme filtre d'allocation à la marge

Le test des 70 % ne s'applique pas transaction par transaction mais au niveau du portefeuille global du fonds. Cela crée une marge de manœuvre de 30 % que les gérants utilisent pour :
- loger des positions de suivi (follow-on) dans des entreprises qui ont grandi au-delà du seuil de 500 salariés ou dépassé 200 M€ de capitalisation après cotation sur un marché de croissance, sans perdre le label — un mécanisme qui **atténue** (plutôt qu'il ne crée) un effet de sortie forcée prématurée ;
- arbitrer entre prêts et fonds propres dans l'enveloppe éligible, la dette étant plafonnée dans les 70 % — ce qui pousse structurellement vers l'instrument actions plutôt que vers le prêt direct aux PME, cohérent avec l'objectif politique du texte mais restrictif pour les gérants qui voudraient faire du financement mezzanine/venture debt à plus grande échelle.
Le relèvement du seuil de salariés de 250 à 500 en 2017 a mécaniquement élargi l'univers investissable sans changer le ratio des 70 % lui-même — un exemple de la façon dont le texte a déjà été assoupli une fois côté actif éligible plutôt que côté seuil de gestionnaire.

### 2.3 Le passeport de commercialisation comme incitation asymétrique par taille de gérant

Le passeport bénéficie mécaniquement plus aux gérants qui cherchent à lever au-delà de leur marché national — typiquement les gérants de petits pays (Benelux, Nordiques, Autriche) plutôt que les gérants de grands marchés domestiques profonds (France, Allemagne) qui peuvent déjà lever l'essentiel de leur fonds localement. C'est cohérent avec la répartition géographique observée (§4) : forte adoption en Allemagne, Pays-Bas, Autriche, Finlande, Suède ; adoption plus faible en Espagne et en France, malgré ce dernier étant l'un des plus gros marchés de capital-risque européen.

### 2.4 L'accès aux LPs fortunés comme incitation à choisir EuVECA plutôt que le régime AIFMD/NPPR pur

Pour un gérant sous-seuil, l'alternative à EuVECA est de commercialiser via les régimes nationaux de placement privé (NPPR), qui excluent en général les personnes fortunées hors clientèle professionnelle MiFID — or ce segment est une source de capital significative et récurrente pour le capital-risque de petite taille. EuVECA, avec son seuil de ticket minimum à 100 000 €, ouvre cette poche de capital sans devoir remonter au régime AIFMD complet. C'est un des rares avantages concrets et directement actionnables du label, indépendamment du passeport transfrontière stricto sensu.

---

## 3. Points de friction

### 3.1 Effet de seuil (cliff-edge) au franchissement des 500 M€

C'est le point de friction le plus documenté dans les échanges réglementaires actuels. Le passage du régime allégé (EuVECA/sous-seuil) au régime AIFMD complet ne se fait pas de façon graduée : un gérant qui dépasse 500 M€ (ou 100 M€ avec effet de levier) doit se conformer à l'ensemble des exigences AIFMD "dans un délai resserré". La Commission qualifie elle-même ce seuil de « devenu obsolète » dans le cadre de la consultation de janvier 2026, notant qu'il capture aujourd'hui des gestionnaires de capital-risque et de croissance opérant à une échelle encore modeste au regard des standards du marché américain. La consultation envisage explicitement une **proportionnalité progressive** pour une catégorie intermédiaire de gérants « moyens » (500 M€ à plusieurs milliards d'euros) plutôt que le saut binaire actuel.

### 3.2 Coûts de mise en conformité et sous-utilisation persistante du label

Malgré trois révisions depuis 2013 et un objectif politique explicite d'en faire l'instrument de référence du capital-risque européen, EuVECA reste qualifié de dispositif « niche » et sous-utilisé par la Commission elle-même. Les données disponibles (voir §4) montrent qu'environ 29 % seulement des fonds de capital-risque européens identifiables portent le label EuVECA — la majorité opère sous le régime FIA générique sans en tirer l'avantage. Ceci suggère que, pour une majorité de gérants, le coût marginal de mise en conformité EuVECA (même allégé par rapport à l'AIFMD complet) n'est pas jugé rentable au regard du bénéfice — probablement parce que le passeport de commercialisation transfrontière n'est utile qu'aux gérants ayant une stratégie de levée hors marché domestique, ce qui n'est pas la majorité des petits gérants de capital-risque (inférence plausible, non vérifiée directement dans les sources consultées).

### 3.3 Fragmentation géographique et hétérogénéité d'adoption

L'adoption du label est très inégale selon les États membres : forte en Allemagne, Pays-Bas, Autriche, Finlande, Suède ; minoritaire en Espagne et en France ; plusieurs États membres n'ont aucun fonds enregistré sous EuVECA. Cette hétérogénéité, documentée par le rapprochement des données PitchBook et du registre public ESMA, indique que malgré l'objectif d'harmonisation du passeport, la pratique de marché reste segmentée par juridiction — un signe que les régimes nationaux de FIA restent, pour beaucoup de gérants, une alternative suffisante ou préférée à EuVECA.

### 3.4 Chevauchement avec ELTIF 2.0 — risque d'arbitrage entre labels européens

Depuis la révision ELTIF de 2024 (élargissement de l'accès retail, assouplissement des critères d'éligibilité), ELTIF est devenu un label concurrent pour des stratégies d'investissement de long terme proches de celles d'EuVECA, avec sa propre dynamique de croissance (226 fonds ELTIF enregistrés en avril 2026, contre 57 sur toute la période 2015-2021 — une accélération nette). EuVECA conserve une base cumulée plus large (1 229 fonds enregistrés depuis 2013) mais la trajectoire de croissance récente semble plus dynamique côté ELTIF, ce qui pose la question — explicitement posée dans la consultation en cours — d'un chevauchement fonctionnel entre les deux labels et d'un choix de véhicule guidé autant par l'ingénierie réglementaire (quel label donne l'accès investisseur recherché au moindre coût de conformité) que par la stratégie d'investissement sous-jacente. C'est une lecture de la dynamique de marché ; l'ampleur exacte de la substitution EuVECA→ELTIF pour des stratégies de capital-risque n'est pas quantifiée dans les sources consultées et reste une inférence plausible plutôt qu'un effet démontré.

### 3.5 Sélection adverse potentielle côté base de LPs

Les données disponibles sur la composition des LPs des fonds de capital-risque européens (toutes catégories confondues, EuVECA et hors EuVECA) montrent une part d'entités publiques d'environ 30-33 % des souscripteurs, contre environ 4 % aux États-Unis, où les fonds de pension et fondations dominent. Ce déséquilibre — documenté par la BCE et la Banque de France — n'est pas spécifique à EuVECA, mais il conditionne l'environnement dans lequel le label opère : une base de LPs plus dépendante du capital public déplace mécaniquement le pouvoir de négociation sur les conditions de fonds (frais, gouvernance, durée) vers des acteurs dont les objectifs incluent des considérations de politique industrielle en plus du rendement pur, ce qui peut diluer la discipline de marché habituellement exercée par des LPs privés sophistiqués. C'est un effet documenté au niveau du marché du capital-risque européen dans son ensemble ; son interaction spécifique avec le choix du label EuVECA plutôt qu'un FIA générique n'est pas établie dans les sources consultées.

### 3.6 Barrière structurelle indépendante du texte : la sortie (exit)

Un point relevé par la Banque de France mais qui déborde du cadre strict d'EuVECA : les fonds de capital-risque européens font face à des options de sortie plus limitées qu'aux États-Unis (IPO moins fréquente en Europe), ce qui réduit le taux de rotation du capital et, en aval, l'incitation des gérants à financer des tours amont plus risqués. Ce n'est pas un effet du règlement EuVECA lui-même, mais un facteur de marché qui conditionne l'appétit des gérants labellisés EuVECA à déployer réellement les 70 % d'actifs éligibles vers des jeunes entreprises risquées plutôt que vers des tours plus tardifs et plus sûrs.

---

## 4. Données de marché quantitatives (2024-2026)

| Indicateur | Valeur | Source / période |
|---|---|---|
| Fonds EuVECA enregistrés (cumulé depuis 2013) | 1 229 fonds | ~mi-2026 |
| Fonds ELTIF enregistrés | 226 (avril 2026) vs 57 sur 2015-2021 | avril 2026 |
| Part des fonds VC UE identifiés portant le label EuVECA | ~29 % (704/2 147 fonds rapprochés PitchBook/registre ESMA) ; ~69 % régime FIA générique, ~2 % EuSEF | données extraites avril 2025, publiées BCE mai 2026 |
| Taille cumulée des fonds VC actifs aux États-Unis vs UE | ~930 Md€ (US) vs ~150 Md€ (UE) — ratio ~6x | BCE, données 2015-2025 |
| Part des entités publiques parmi les LPs de VC | ~30-33 % (UE) vs ~4 % (US) | BCE / Banque de France |
| Investissement VC cumulé 2014-2023 | 89 Md€ (UE) vs plus de 1 000 Md€ (US) | Banque de France, CEPR |
| Investissement VC annuel UE, 2023 | >10 Md€ (contre 2,5 Md€ en 2010) | Banque de France |
| Investissement VC (méthodologie Invest Europe, capital réellement déployé par les gérants membres), 2025 | 35,3 Md€ — 2e meilleure année historique | Invest Europe, rapport publié juillet 2026 |
| Levée de capital VC (fundraising) par les gérants européens, 2025 | 17 Md€, -29 % sur un an, -16 % vs moyenne des 5 années précédentes | Invest Europe, rapport publié mai 2026 |
| Levée de capital croissance (growth), 2025 | 21 Md€ (14 % du total levé PE+VC) | Invest Europe, 2025 |
| Levée totale PE+VC en Europe, 2025 | 147 Md€ (+16 % vs 2024) | Invest Europe, 2025 |
| Investissement VC total UE (méthodologie deal-value élargie, PitchBook/Dealroom) | 66,2 Md€ | 2025 — chiffre non directement comparable à la mesure Invest Europe (méthodologies différentes) |
| Investissement VC total US | ~175-339 Md€ selon source/méthodologie (dont 222 Md€ rien que sur l'IA, 65,6 % du deal-value total) | PitchBook-NVCA Venture Monitor, année pleine 2025 |
| Fundraising VC US, 2025 | 66,1 Md$ de nouveaux engagements — plus bas niveau depuis 2018 | PitchBook-NVCA, 2025 |
| Écart d'investissement VC cumulé US vs UE (firmes basées aux États-Unis vs Europe) | >1 400 Md$ d'écart cumulé | ITIF, octobre 2025 |
| Rendement annuel moyen des fonds VC | 8,6 % (UE) vs 14,6 % (US) | Banque de France, décennies récentes |
| Part des investissements en private equity dans les bilans des assureurs européens | 1,45 % (T4 2024) | Banque de France |
| Taille moyenne d'un fonds VC européen | ~60 M€ | sources sectorielles (approximatif) |
| Nombre de fonds/gérants EuVECA au Luxembourg (illustratif d'un marché national) | ~30 fonds gérés par 17 gérants EuVECA | LPEA/ALFI, 2026 |

**Note méthodologique importante** : les chiffres « investissement VC en Europe » varient significativement selon la source (35,3 Md€ Invest Europe vs 66,2 Md€ PitchBook/Dealroom pour 2025) parce que les méthodologies diffèrent — Invest Europe agrège le capital réellement déployé par ses gérants membres reportants, tandis que PitchBook/Dealroom capture un univers de transactions plus large incluant des investisseurs non membres et des structures de deal plus variées (corporate VC, business angels organisés, etc.). Les deux chiffres sont réels et sourcés, mais ne doivent pas être additionnés ni traités comme interchangeables.

---

## 5. Effets documentés vs inférence propre — récapitulatif de fiabilité

**Bien documentés (données de marché / sources officielles ou quasi-officielles citées ci-dessus)** :
- Mécanique du test des 70 %, seuils d'éligibilité (500 salariés, 200 M€ de capitalisation), capital minimum du gérant (50 000 €), seuil AIFMD (500 M€ / 100 M€ à effet de levier).
- Effet de seuil (cliff-edge) au franchissement de 500 M€, reconnu explicitement par la Commission dans sa consultation de janvier 2026.
- Sous-utilisation relative du label (29 % des fonds VC UE identifiés) et hétérogénéité géographique d'adoption.
- Écart quantitatif massif de taille de marché et de rendement entre capital-risque UE et US.
- Chevauchement croissant avec ELTIF 2.0 en tant que dynamique de marché mesurable (226 vs 1 229 fonds, rythme d'enregistrement ELTIF en accélération).
- Traitement Solvency II favorable pour les parts EuVECA/EuSEF/ELTIF par rapport aux actifs alternatifs non qualifiants (direction confirmée, calibrage précis non vérifié).

**Inférence propre, plausible mais non vérifiée directement dans les sources consultées** :
- Le comportement de calibrage stratégique de la taille de fonds autour du seuil des 500 M€ (rester juste en dessous vs sauter délibérément au-dessus) — mécanisme cohérent avec la théorie des seuils réglementaires et avec le cliff-edge documenté, mais non observé directement via des données de fonds individuels dans les sources disponibles.
- Le lien causal précis entre sous-utilisation du label EuVECA et rapport coût/bénéfice perçu par les petits gérants sans stratégie de levée transfrontière.
- L'ampleur de la substitution EuVECA → ELTIF pour des stratégies de capital-risque spécifiquement (la croissance relative d'ELTIF est documentée ; son imputation à un arbitrage actif au détriment d'EuVECA plutôt qu'à une simple expansion du marché est une lecture, pas un fait établi).
- L'interaction entre la part élevée de LPs publics et la discipline de marché spécifiquement au sein des fonds labellisés EuVECA (l'effet LP public est documenté au niveau du marché VC européen global, pas décomposé par label réglementaire dans les sources consultées).

---

## Sources principales consultées

- Commission européenne, consultation ciblée « EU venture and growth capital funds reform », 15 janvier 2026 ([finance.ec.europa.eu](https://finance.ec.europa.eu/regulation-and-supervision/consultations-0/targeted-consultation-eu-venture-and-growth-capital-funds-reform_en))
- Parlement européen, Legislative Train Schedule — Review of the EuVECA Regulation
- Harneys, « EU reviews EuVECA Regulation for venture capital reform » (blog réglementaire)
- Sidley Austin, UK/EU Investment Management Update, février 2026
- Osborne Clarke, « The European Venture Capital Fund Regulation: an overview »
- Invest Europe, « Investing in Europe: Private Equity Activity 2025 » (rapports fundraising mai 2026 et investissement juillet 2026)
- Banque centrale européenne (BCE), « Exploring the investor landscape for venture capital », box, mai 2026
- Banque de France, « How can Europe scale its venture capital market? »
- CEPR/VoxEU, « The venture capital challenge for Europe »
- ITIF, « Fact of the Week: Over $1.4T More Venture Capital Funding... », octobre 2025
- PitchBook-NVCA Venture Monitor, Q4 2025 / année pleine 2025
- LPEA/ALFI, réponse à la consultation Commission sur les fonds VC et croissance, mars 2026
- Finance Watch, « Balancing investment growth and investor protection to support long-term innovation »

*Limite de recherche à noter* : plusieurs documents PDF (Trident Trust, CFA Institute) et une page (Finance Watch, accès direct) n'ont pas pu être extraits en texte lisible via les outils disponibles ; leur contenu a été recoupé via d'autres sources citant les mêmes données ou via les résultats de recherche associés. Le registre ESMA public n'a pas retourné de décompte agrégé exploitable en accès direct au moment de la recherche.
