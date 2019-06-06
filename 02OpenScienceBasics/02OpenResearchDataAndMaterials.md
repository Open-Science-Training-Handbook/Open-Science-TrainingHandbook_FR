## <img src="/Images/Icons/open_data.png" width="200" height="200" />
## 2. Open Research Data and Materials

### Qu'est-ce que c'est ?

Les données de recherche ouverte sont des données qui peuvent être librement consultées, réutilisées, remaniées et redistribuées, à des fins de recherche universitaire, d'enseignement et autres. Idéalement, les données ouvertes n'ont aucune restriction quant à la réutilisation ou à la redistribution, et sont soumises à des licences appropriées. Dans des cas exceptionnels, par exemple pour protéger l'identité d'individus, des restrictions spéciales ou limitées d'accès sont fixées. Le partage ouvert des données les expose à l'inspection, ce qui constitue la base de la vérification et de la reproductibilité de la recherche, et ouvre la voie à une collaboration plus large. Tout au plus, les données ouvertes peuvent être soumises à l'obligation d'attribuer et de partager des données \(voir le [Open Data Handbook](http://opendatahandbook.org/guide/en/what-is-open-data)\).

## <img src="/Images/Icons/data2.png" width="150" height="150" />

### Justification

Les données de recherche sont souvent l'accomplissement crucial de nombreux projets de recherche, elles sont utilisées comme sources primaires qui sous-tendent la recherche scientifique et permettent de dériver des résultats théoriques ou appliqués. Afin de rendre les résultats/études réplicables, ou du moins reproductibles ou réutilisables \(voir [Reproducible Research And Data Analysis](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/blob/master/02OpenScienceBasics/04ReproducibleResearchAndDataAnalysis.md)\) d'une certaine manière, la meilleure pratique recommandée pour les données de recherche doit être aussi ouverte et [FAIR](https://www.force11.org/fairprinciples) que possible, en respectant les contraintes éthiques, commerciales et la confidentialité des données sensibles ou exclusives.

## <img src="/Images/Icons/finish.png" width="150" height="150" />

### Objectifs d'apprentissage

1. Comprendre les caractéristiques et les principes de base des données de recherche ouvertes et équitables, y compris l'assemblage approprié et la documentation, afin de permettre à d'autres de comprendre, de reproduire et de réutiliser les données de manière alternative.

2. Familiarité avec les types de données qui peuvent être considérées comme sensibles et les restrictions ou contraintes liées au partage ouvert de ces données.

3. Pouvoir convertir un ensemble de données "fermées" en un ensemble "ouvert" en mettant en œuvre les mesures nécessaires dans un plan de gestion des données, avec une gestion appropriée des données et des métadonnées.

4. Être en mesure d'utiliser le plan de gestion des données de recherche et de rendre les résultats de vos recherches accessibles et trouvables, même s'ils contiennent des données sensibles.

5. Comprendre les avantages et les inconvénients du partage ouvert de différents types de données \(p. ex. confidentialité, sensibilité, dépersonnalisation, accès par médiation\).

6. Comprendre l'importance de métadonnées appropriées pour l'archivage durable des données de recherche.

7. Comprendre les flux de travail de base et les outils de partage des données de recherche.

### Composantes clés
## <img src="/Images/Icons/brain.png" width="150" height="150" height="150" /><img src="/Images/Icons/gears.png" width="150" height="150" />
##### Connaissances et compétences
###### Principes de l'équité

En 2014, un ensemble de principes de base a été rédigé afin d'optimiser la réutilisabilité des données de recherche, appelé les [Principes de données FAIR](https://www.force11.org/group/fairgroup/fairprinciples). Il s'agit d'un ensemble de lignes directrices et de pratiques élaborées par la communauté pour garantir que les données ou tout objet numérique soient **F**indable \("Trouvables"\), **A**ccessibles  **I**nteropérables et **R**éutilisables :

**Findable :** La première chose à faire pour rendre les données réutilisables est de les retrouver. Il devrait être facile de trouver les données et les métadonnées pour les humains et les ordinateurs. La découverte automatique et fiable des ensembles de données et des services dépend des identificateurs pérennes détectables par des machines \(PIDs\) et des métadonnées.

**Accessible :** Les \(méta\)données doivent pouvoir être récupérées par leur identifiant à l'aide d'un protocole de communication standardisé et ouvert, incluant éventuellement une authentification et une autorisation. De plus, les métadonnées devraient être disponibles même lorsque les données ne sont plus disponibles.

**Interopérable :** Les données doivent pouvoir être combinées et utilisées avec d'autres données ou outils. Le format des données devrait donc être ouvert et interprétable pour divers outils, y compris d'autres enregistrements de données. Le concept d'interopérabilité s'applique tant au niveau des données qu'à celui des métadonnées. Par exemple, les \(méta\)données devraient utiliser des vocabulaires qui suivent les principes FAIR.

**Réutilisable :** En fin de compte, FAIR vise à optimiser la réutilisation des données. Pour ce faire, les métadonnées et les données doivent être bien décrites afin qu'elles puissent être reproduites et/ou combinées dans différents contextes. De plus, la réutilisation des \(méta\)données devrait être indiquée avec une \(des\) licences claire\(s\) et accessible\(s\).

À la différence des initiatives entre pairs qui se concentrent sur l'intellect humain, les principes FAIR mettent l'accent sur l'amélioration de la capacité des machines à trouver et à utiliser automatiquement des données ou tout objet numérique, en plus de favoriser sa réutilisation par les individus. Les principes FAIR sont des guides et non des normes. FAIR décrit les qualités ou les comportements nécessaires pour que les données soient réutilisables au maximum \(p. ex., description, citation\). Ces qualités peuvent être atteintes par des normes différentes.

![](/Images/02%20Open%20Science%20Basics/02_open_research_data_material.png)

###### Publication de données

La plupart des chercheurs sont plus ou moins familiers avec la publication en libre accès d'articles de recherche et de livres \(voir chapitre 5\). Plus récemment, et pour les raisons mentionnées ci-dessus, la publication de données a suscité une attention croissante. De plus en plus de bailleurs de fonds s'attendent à ce que les données produites dans le cadre des projets de recherche qu'ils financent soient disponibles, accessibles et aussi ouvertes que possible.

Il existe plusieurs façons distinctes de rendre les données de recherche accessibles, notamment \([Wikipedia](https://en.wikipedia.org/wiki/Data_publishing)\) :

* Publication de données en tant que matériel supplémentaire associé à un [article de recherche](https://en.wikipedia.org/wiki/Research_article), généralement avec les fichiers de données hébergés par l'éditeur de l'article.

* Hébergement des données sur un site Web accessible au public, avec fichiers disponibles pour téléchargement.

* Dépôt de données dans un dépôt qui a été conçu pour la publication des données, p. ex. [Dataverse](https://en.wikipedia.org/wiki/Dataverse), [Dryad](https://en.wikipedia.org/wiki/Dryad_(dépôt)), [figshare](https://en.wikipedia.org/wiki/Figshare), [Zenodo](https://en.wikipedia.org/wiki/Zenodo).

* Il existe un grand nombre de dépôts de données générales et de dépôts de données spécifiques à un domaine ou à un sujet qui peuvent fournir un soutien supplémentaire aux chercheurs lorsqu'ils déposent leurs données.

* Publication d'un document sur l'ensemble de données, qui peut être publié sous forme de préimpression, dans un journal ou dans un journal dédié aux documents de données. Les données peuvent être hébergées par la revue ou séparément dans un dépôt de données. Des exemples de journaux de données comprennent [Scientific Data](https://www.nature.com/sdata/) \(par SpringerNature\) et le [Data Science Journal](http://www.codata.org/publications/data-science-journal) \(par CODATA\). Pour une revue complète de ce type de journaux, voir [Candela et al](https://doi.org/10.1002%2Fasi.23358).

Le CESSDA ERIC [Expert tour guide on Data Management](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/6.-Archive-Publish/Data-publishing-routes) donne un aperçu des avantages et des inconvénients des différentes voies de publication des données. Parfois, votre bailleur de fonds ou une autre partie externe vous demande d'utiliser un référentiel spécifique. Si vous êtes libre de choisir, vous pouvez considérer l'ordre de préférence dans les [recommandations par OpenAIRE](https://www.openaire.eu/opendatapilot-repository-guide) :

1. Utilisez une archive ou un référentiel de données externe déjà établis pour votre domaine de recherche afin de préserver les données conformément aux normes reconnues dans votre discipline.

2. Si possible, utilisez un dépôt de données de recherche institutionnel ou les installations de gestion des données établies de votre groupe de recherche.

3. Utilisez un référentiel de données gratuit tel que [Dataverse](https://dataverse.org/), [Dryad](https://datadryad.org/pages/faq#depositing-cost), [figshare](https://figshare.com/) ou [Zenodo](https://zenodo.org/).

4. Recherchez d'autres dépôts de données dans [re3data](https://www.re3data.org/). Il n'y a pas d'option de filtrage unique dans re3data couvrant les principes de FAIR, mais considérer les options de filtrage suivantes vous aidera à trouver des référentiels compatibles FAIR : catégories d'accès, licences d'utilisation de données, référentiels de données fiables \(avec un certificat ou en respectant explicitement les normes archivistiques\) et si un référentiel donne un identifiant permanent aux données \(PID\). Un autre aspect à considérer est de savoir si le référentiel supporte le versioning.

## <img src="/Images/Icons/archive.png" width="150" height="150" />
Vous devriez considérer où déposer et publier vos données dans votre plan de gestion des données de recherche. Le CESSDA propose quelques questions pratiques qu'il est recommandé de se poser. Par exemple : Quelles données et métadonnées, documentation et code associés seront déposés ? Combien de temps les données doivent-elles être conservées ? Pendant combien de temps les données doivent-elles rester réutilisables ? Comment les données seront-elles mises à disposition ? Quelle catégorie d'accès allez-vous choisir ? Pour plus de questions, consultez [Adapt your DMP part 6](https://www.cessda.eu/Research-Infrastructure/Training/Expert-Tour-Guide-on-Data-Management/6.-Archive-Publish/Adapt-your-DMP-part-6). D'autre part, n'oubliez pas de vérifier si le référentiel choisi répond aux exigences de votre recherche et de votre bailleur de fonds. Certains référentiels ont déjà obtenu une certification, comme CoreTrustSeal, qui les certifie dignes de confiance et leur permet de répondre aux exigences des référentiels de données dignes de confiance. Il convient de mentionner que certains dépôts spécifiques à un domaine peuvent n'accepter que des données de haute qualité avec un potentiel de réutilisation et qui peuvent être partagées publiquement.

Puisqu'il y a plusieurs façons de publier vos données, vous devriez noter que pour qu'un ensemble de données "compte" comme une publication, il devrait suivre un processus de publication similaire à celui d'un article \([Brase et al., 2009](https://doi.org/10.3233/ISU-2009-0595)\) et devrait être :

* Bien documenté avec des métadonnées ;

* Examiné au niveau de sa qualité, par exemple du contenu de l'étude, de la méthodologie, de la pertinence, de la cohérence juridique et de la documentation des documents ;

* Recherchable et trouvable dans les catalogues \(ou bases de données\) ;

* Citable dans les articles.

## <img src="/Images/Icons/metadata.png" width="150" height="150" />
##### Citation des données

Les services de citation de données aident les communautés de recherche à découvrir, identifier et citer des données de recherche (et souvent d'autres objets de recherche) avec confiance. Cela implique généralement la création et l'attribution d'identificateurs d'objets numériques \(DOI\) et de métadonnées d'accompagnement par le biais de services tels que [DataCite](https://www.datacite.org), et peut être intégré aux flux de travail et normes de recherche. Il s'agit d'un domaine émergent, qui comporte des aspects tels que la communication aux éditeurs de revues de l'importance d'une citation appropriée des données dans les articles, ainsi que la possibilité de relier les articles de recherche eux-mêmes à toute donnée sous-jacente. Ainsi, les données pertinentes deviennent des contributions légitimes au processus de communication savante et peuvent aider à ouvrir la voie à de nouvelles mesures et à de nouveaux modèles de publication qui reconnaissent et récompensent le partage des données.

Comme première étape vers de bonnes pratiques en matière de citation des données, le Groupe de synthèse sur la citation des données de FORCE11 a proposé la [Déclaration conjointe sur les principes de citation des données](https://doi.org/10.25490/a97f-egyk), destinée aux chercheurs et aux fournisseurs de services de données. En adhérant à ces principes, les dépôts de données fournissent habituellement aux chercheurs une référence qu'ils peuvent utiliser lorsqu'ils se réfèrent à un certain ensemble de données.

## <img src="/Images/Icons/database.png" width="150" height="150" />
##### Assemblage des données

Les ensembles de données sont des conteneurs pour décrire et partager les fichiers de données qui les accompagnent, et comprennent généralement un fichier de métadonnées décrivant les caractéristiques et le contexte d'un ensemble de données. Cela peut inclure des aspects tels que les informations de création, la provenance, la taille, le type de format, les définitions de champs, ainsi que tous les fichiers contextuels pertinents, tels que les scripts de création de données ou la documentation textuelle. Extrait du [Guide d'emballage des données](https://github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md) :

* Les données sont éternelles : Les ensembles de données survivent à leur finalité initiale. Les limites des données peuvent être évidentes dans leur contexte original, comme un catalogue de bibliothèque, mais peuvent ne pas l'être une fois que les données sont séparées de l'application pour laquelle elles ont été créées.

* Les données ne peuvent se suffire à elles-mêmes : L'information sur le contexte et la provenance des données - comment et pourquoi elles ont été créées, quels objets et concepts du monde réel elles représentent, les contraintes sur les valeurs - est nécessaire pour aider les consommateurs à les interpréter de façon responsable.

* Structurer les métadonnées sur les ensembles de données d'une manière standard et lisible par machine encourage la promotion, le partage et la réutilisation des données.

## <img src="/Images/Icons/privacy.png" width="150" height="150" />
##### Le partage de données sensibles et exclusives

Avec une planification appropriée de la gestion des données, beaucoup de données sensibles et exclusives peuvent être partagées, réutilisées et FAIR. Les métadonnées peuvent presque toujours être partagées. Les guides et les meilleures pratiques en matière de partage des données sensibles sont nécessairement propres à chaque région en raison de réglementations différentes \(voir par exemple le [Companion material for Managing and Sharing Research Data handbook](https://www.ukdataservice.ac.uk/manage-data/handbook)\) de UKDS. L'[Association internationale pour les services et technologies de l'information en sciences sociales](http://www.iassistdata.org/resources/data-management/best-practices) tient une liste d'orientations internationales en matière de gestion des données qui constitue un bon point de départ. Il existe plusieurs approches et initiatives pour aider les chercheurs à atteindre cet objectif. L'outil [DMPonline de CDC](http://www.dcc.ac.uk/dmponline) comprend un certain nombre de modèles pour les bailleurs de fonds. Le guide [CESSDA Expert Tour Guide on Data Management](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Ethics-and-data-protection) fournit des informations et des exemples pratiques sur la manière de partager des données personnelles et sur les questions de droits d'auteur et de bases de données dans les pays européens. Le guide touristique donne également un aperçu de l'impact du RGPD qui harmonisera la législation sur les données personnelles en Europe \(mai 2018\), et fournit un aperçu actualisé sur [la diversité de l'UE en matière de protection des données](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Processing-personal-data/Diversity-in-data-protection).[ ](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Processing-personal-data/Diversity-in-data-protection)

###### Courtiers en données

Les courtiers en données sont des parties bien informées et indépendantes qui gèrent les données sensibles. Les chercheurs peuvent transférer au courtier leurs données sensibles et la juridiction sur l'accès à ces données. Cette situation est particulièrement fréquente dans le cas des données sur les patients provenant d'études cliniques. Les courtiers assurent un certain degré d'indépendance dans l'évaluation des demandes de données qui sont scientifiquement valides et qui ne porteront pas atteinte à la vie privée des participants à la recherche. Voici des exemples de courtiers en données : [The YODA Project](http://yoda.yale.edu/), [ClinicalStudyDataRequest.com](https://www.clinicalstudydatarequest.com/), [National Sleep Research Resource](https://sleepdata.org/) et [Supporting Open Access for Researchers \(SOAR\)](https://dcri.org/our-approach/data-sharing/).

## <img src="/Images/Icons/data.png" width="150" height="150" />
##### Portails d'analyse

Les portails d'analyse sont des plates-formes qui permettent l'analyse approuvée des données sans permettre un accès complet \(visualisation ou téléchargement\) ni contrôler où et qui y a accès. Certains courtiers en données utilisent également des portails d'analyse. Les portails d'analyse contrôlent les ensembles de données supplémentaires qui peuvent être mis en commun avec les données sensibles ainsi que les analyses qui peuvent être effectuées pour s'assurer que les renseignements personnels ne sont pas révélés pendant la réanalyse. Des exemples de portails d'analyse virtuelle incluent [Project Data Sphere](https://www.projectdatasphere.org/projectdatasphere/html/home), [Vivli](http://vivli.org/), [RAIRD](http://raird.no/), [Corpuscle](http://clarino.uib.no/korpuskel/page), et [INESS](http://clarino.uib.no/iness/page).

Les chercheurs en sciences sociales et les autres chercheurs qui possèdent des données sensibles utilisent un portail d'analyse à site unique auquel on ne peut accéder que sous régime contrôlé. Les chercheurs approuvés peuvent accéder aux données sur place, dans une salle sécurisée, à des fins scientifiques. Toutefois, les métadonnées décrivant les données devraient être librement accessibles et respecter les principes de FAIR.

##### Données dé-identifiées et synthétiques

De nombreux ensembles de données contenant des informations privées au niveau du participant peuvent être partagés une fois que l'ensemble de données a été dépersonnalisé \(Safe Harbor method\) ou qu'un expert a déterminé que l'ensemble de données n'est pas individuellement identifiable \(Expert Determination method\). Consultez votre comité d'éthique de la recherche ou votre comité d'examen institutionnel pour savoir comment utiliser vos données à cette fin. Nous recommandons également [le guide CESSDA Expert Tour Guide on Data Management](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Ethics-and-data-protection), qui fournit des informations et des exemples pratiques sur la façon de partager des données personnelles. Toutefois, certains ensembles de données ne peuvent être dépersonnalisés et partagés en toute sécurité. Les chercheurs peuvent encore améliorer la transparence de la recherche sur ces données en créant et en partageant des données synthétiques. Les données synthétiques ont une structure, un contenu et une distribution similaires aux données réelles et visent à atteindre une "validité analytique" : l'analyse statistique donnera les mêmes résultats pour les données synthétiques que les données réelles. Le Bureau de recensement des États-Unis, par exemple, utilise [des données synthétiques et des portails d'analyse](https://census.gov/content/dam/Census/programs-surveys/sipp/methodology/SSBdescribe_nontechnical.pdf) en combinaison pour permettre la réutilisation de données très sensibles.

###### DataTags

[DataTags](https://datatags.org/) est un cadre conçu pour permettre des évaluations assistées par ordinateur des restrictions légales, contractuelles et politiques qui régissent les décisions relatives au partage des données. Le système DataTags pose à l'utilisateur une série de questions pour connaître les propriétés clés d'un certain ensemble de données et applique des règles d'inférence pour déterminer quelles lois, contrats et meilleures pratiques sont applicables. Le résultat est un ensemble de DataTags recommandés, ou de simples étiquettes iconiques qui représentent une politique de données lisible par l'homme et actionnable par machine, et un accord de licence adapté à l'ensemble de données individuel. Le système DataTags est conçu pour s'intégrer au logiciel de référentiel de données et fonctionnera également comme un outil autonome. DataTags est en cours de développement à l'Université de Harvard. En Europe, DANS travaille sur l'adaptation des DataTags à la législation européenne / Règlement général sur la protection des données \([GDPR](https://www.eugdpr.org/)\) \(cf. [DANS GDPR DataTags](https://zingtree.com/host.php?style=buttons&tree_id=442670046&persist_names=Restart&persist_node_ids=58#58)\).

Comme nous l'avons déjà mentionné, le but ultime du partage de vos données de recherche est de les rendre réutilisables au maximum. À cette fin, avant de partager vos données, vous devez les prendre en charge selon les meilleures pratiques. Cela inclut, entre autres, la documentation et le choix de formats de fichiers ouverts et sous licences. Pour en savoir plus sur ces questions, consultez la [Section 4: Reproducible Research and Data Analysis](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_FR/blob/master/02OpenScienceBasics/04ReproducibleResearchAndDataAnalysis.md) et la [Section 6: Open Licensing and File Formats](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_FR/lob/master/02OpenScienceBasicensing/AndFileFormats.md).

## <img src="/Images/Icons/usb.png" width="150" height="150" />
##### Matériels ouverts

En plus du partage des données, l'ouverture de la recherche repose sur le partage de matériels. Les matériels utilisés par les chercheurs sont propres à une discipline et parfois uniques à un laboratoire. Vous trouverez ci-dessous des exemples de matériels que vous pouvez partager, bien que vous puissiez toujours vous entretenir avec vos pairs dans votre discipline pour déterminer quels dépôts sont utilisés. Lorsque vous avez des matériels, des données et des publications d'un même projet de recherche partagés dans différents dépôts, recoupez-les avec un lien et un identificateur unique pour qu'ils puissent être facilement localisés.

###### Réactifs

Un réactif est une substance, un composé ou un mélange qui peut être ajouté à un système afin de créer une réaction chimique ou un autre type de réaction. Les réactifs peuvent être déposés dans des dépôts tels que [Addgene](https://www.addgene.org/), [The Bloomington Drosophila Stock Center](https://bdsc.indiana.edu/), et [ATCC](https://www.atcc.org/) pour les rendre facilement accessibles aux autres chercheurs. Obtenez une licence pour vos documents afin qu'ils puissent être réutilisés par d'autres chercheurs.

###### Protocoles

Un protocole décrit un enregistrement formel ou officiel des observations expérimentales scientifiques sous une forme structurée. Déposer des protocoles virtuels pour la citation, l'adaptation et la réutilisation à l'aide de [Protocols.io](https://www.protocols.io/).

###### Notebooks, conteneurs, logiciels et matériel informatique 

L'analyse reproductible est facilitée par l'utilisation d'une programmation lettrée, de la technologie des conteneurs et de la virtualisation. En plus de partager votre code et vos données, partagez également vos notebooks Jupyter, vos images Docker ou tout autre matériel d'analyse ou dépendance logicielle. Partagez vos notebooks avec des services Open tels que [mybinder](http://mybinder.org) qui permettent au public de visualiser et d'exécuter l'intégralité du notebook sur des ressources partagées. Les conteneurs et les carnets peuvent être partagés avec [Rocker](https://arxiv.org/abs/1710.03675) ou [Code Ocean](https://codeocean.com/). Les logiciels et le matériel utilisés dans le cadre de votre recherche doivent être partagés conformément aux pratiques exemplaires en matière de documentation décrites à la [Section 3](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_FR/blob/master/02OpenScienceBasics/03OpenResearchSoftwareAndOpenSource.md). Les protocoles en lecture seule devraient être déposés dans le registre de votre discipline comme [ClinicalTrials.gov](https://clinicaltrials.gov/) et [SocialScienceRegistry](https://www.socialscienceregistry.org/) ou un registre général comme [Open Science Framework](https://osf.io/). De nombreuses revues, telles que [Trials](https://trialsjournal.biomedcentral.com/), [JMIR Research Protocols](https://www.researchprotocols.org/), ou [Bio-Protocol](https://bio-protocol.org/), publieront votre protocole. Les meilleures pratiques pour la publication de votre protocole en accès libre sont les mêmes que pour la publication de votre rapport en accès libre \(voir [Section 5](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_FR/blob/master/02OpenScienceBasics/05OpenAccessToPublishedResearchResults.md)\).

## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Questions, obstacles et idées fausses courantes

Q : "Est-il suffisant de rendre mes données librement accessibles ?"

R : "Non - L'ouverture est une condition nécessaire mais non suffisante pour une réutilisation maximale. Les données doivent être FAIR en plus d'être ouvertes."

Q : "Que signifient les principes de FAIR pour les différentes parties prenantes/publics ?"

R : "C'est un excellent sujet de discussion !"

Obstacle : Les chercheurs peuvent hésiter à partager leurs données parce qu'ils craignent que d'autres ne les réutilisent avant qu'ils n'aient pu en tirer le maximum ou que d'autres ne comprennent pas entièrement les données et ne les utilisent donc pas à mauvais escient.

\(suggested\) A : Vous pouvez publier vos données pour les rendre trouvables avec les métadonnées, mais fixez une période d'embargo sur les données pour vous assurer que vous pouvez publier votre propre article\(s\) en premier.

Q : "Est-ce que le fait de rendre mes données FAIR représente beaucoup de travail supplémentaire ?"

R : "Pas nécessairement ! Rendre les données FAIRES n'est pas seulement la responsabilité des chercheurs individuels, mais aussi celle de l'ensemble du groupe. La meilleure façon de vous assurer que vos données sont FAIR est de créer un plan de gestion des données et de tout planifier à l'avance. Pendant la collecte et le traitement des données, suivre les normes et les mesures disciplinaires recommandées par un référentiel.

Q : "Je veux partager mes données. Comment devrais-je les licencier ?"

R : "C'est une bonne question. Tout d'abord, à qui appartiennent les données ? Un bailleur de fonds de la recherche ou un établissement pour lequel vous travaillez. Ensuite, pensez à la paternité de l'œuvre. L'application d'une licence appropriée à vos données est cruciale afin de les rendre réutilisables. Pour plus d'informations sur les licences, voir[6. licences ouvertes et formats de fichier] (https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/tree/master/02OpenScienceBasics/06OpenLicensingAndFileFormats).

Q : " Je ne peux pas rendre mes données directement accessibles - elles sont trop volumineuses pour être partagées de façon pratique / elles comportent des restrictions liées à la protection de la vie privée. Que dois-je faire ?"

R : "Vous devriez parler à des experts en référentiels spécifiques à un domaine sur la façon de fournir des instructions suffisantes pour rendre vos données trouvables et accessibles".

### Questions, obstacles, and common misconceptions

Q: "Is it sufficient to make my data openly available?"

A: "No—openness is a necessary but not sufficient condition for maximum reuse. Data have to be FAIR in addition to open."

Q: "What do the FAIR principles mean/imply for different stakeholders/audiences?"

A: "This is a great topic for discussion!"

Obstacle: Researchers may be reluctant to share their data because they are afraid that others will reuse them before they have extracted the maximum usage from them, or that others might not fully understand the data and therefore mis-use them.

\(suggested\) A: You may publish your data to make them findable with metadata, but set an embargo period on the data to make sure that you can publish your own article\(s\) first.

Q: "Is making my data FAIR a lot of extra work?"

A: "Not necessarily! Making data FAIR is not only the responsibility of the individual researchers but of the whole group. The best way to ensure that your data is FAIR is to create a Data Management Plan and plan everything beforehand. During the data collection and data processing follow the discipline standards and measures recommended by a repository.

Q: "I want to share my data. How should I license them?"

A: "That’s a good question. First of all think about who owns the data? A research funder or an institution that you work for. Then, think about authorship. Applying a suitable license to your data is crucial in order to make them reusable. For more information about licensing, please see [6. Open Licensing and File Formats](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_EN/tree/master/02OpenScienceBasics/06OpenLicensingAndFileFormats).

Q: "I cannot make my data directly available—they are too large to share conveniently / have restrictions related to privacy issues. What should I do?"

A: "You should talk to experts in domain specific repositories on how to provide sufficient instructions to make your data findable and accessible."


## <img src="/Images/Icons/output.png" width="150" height="150" />
### Learning outcomes

1. Understand the characteristics of open data, and in particular the FAIR principles.

2. Be familiar with some of the arguments for and against open data.

3. Be able to differentiate and address sensitive data and opFAIR data; these two categories are not necessarily incompatible.

4. Be able to transform a dataset into one that is sufficient for open sharing \(non-proprietary format\), meets the standards of the FAIR principles, and is designed for maximized accessibility, transparency and re-use by providing sufficient metadata.

5. Know the difference between raw and processed \(or cleaned\) data, and the importance of version labels.

6. Know commonly used file formats and community standards for maximum re-usability.

7. Be able to write a data management plan.

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Pour en savoir plus
* Averkamp et al. (2018). Data packaging guide. [github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md](https://github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md).

* Barend et al. (2017). Cloudy, increasingly FAIR; revisiting the FAIR Data guiding principles for the European Open Science Cloud. [doi.org/10.3233/ISU-170824](https://doi.org/10.3233/ISU-170824)

* Brase et al. (2009). Approach for a joint global registration agency for research data. [doi.org/10.3233/ISU-2009-0595](https://doi.org/10.3233/ISU-2009-0595)

* Candela et al. (2015). Data journals: A survey. [doi.org/10.1002/asi.23358](https://doi.org/10.1002/asi.23358)

* CESSDA Training Working Group (2017-2018a). CESSDA Data Management Expert Guide. Bergen, Norway: CESSDA ERIC. [cessda.eu/DMGuide](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management)

* CESSDA Training Working Group (2017-2018b). CESSDA Data Management Expert Guide: Citing your data. Bergen, Norway: CESSDA ERIC.[cessda.eu/DMGuide/citingdata](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/6.-Archive-Publish/Publishing-with-CESSDA-archives/Citing-your-data)

* FAIRsharing.org (2016). FAIR. The FAIR Principles. [doi.org/10.25504/FAIRsharing.WWI10U](https://doi.org/10.25504/FAIRsharing.WWI10U)

* Force 11 (n.y.). Guiding principles for Findable, Accessible, Interoperable, and Re-usable data publishing Version B1.0. [force11.org/fairprinciples](https://www.force11.org/fairprinciples)

* Gorgolewski et al. (2013). Making data sharing count: a publication-based solution. [doi.org/10.3389/fnins.2013.00009](https://doi.org/10.3389/fnins.2013.00009)

* Kratz and Strasser (2015). Making Data Count. [doi.org/10.1038/sdata.2015.39](https://www.nature.com/articles/sdata201539) 

* Piwowar and Vision (2013). Data reuse and the open data citation advantage. [doi.org/10.7717/peerj.175](https://doi.org/10.7717/peerj.175)

* Wilkinson et al. (2016). The FAIR Guiding Principles for scientific data management and stewardship. [doi.org/10.1038/sdata.2016.18](https://doi.org/10.1038/sdata.2016.18)

* Wilkinson et al. (2918). A design framework and exemplar metrics for FAIRness. [doi.org/10.1038/sdata.2018.118](https://doi.org/10.1038/sdata.2018.118)


#### Initiatives et projets

* DANS GDPR DataTags. [zingtree.com](https://zingtree.com/host.php?style=buttons&tree_id=442670046&persist_names=Restart&persist_node_ids=58#58)

* FAIR Metrics. [fairmetrics.org](http://fairmetrics.org/)

* GO FAIR Initiative. [go-fair.org](https://www.go-fair.org/)

*  The FAIR Data Principles explained. [go-fair.org](https://www.go-fair.org/fair-principles/)

*  5★ OPEN DATA. [5stardata.info](http://5stardata.info/en/)


