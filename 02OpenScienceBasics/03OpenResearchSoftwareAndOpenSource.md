<img src="/Images/Icons/open_source_software.png" width="150" height="150" /> <img src="/Images/Icons/publish.png" width="150" height="150" />
## 3. Logiciels de recherche ouverts et logiciels libres

### Qu'est-ce que c'est ?

Un logiciel de recherche ouvert, ou logiciel de recherche libre, désigne l'utilisation et le développement de logiciels d'analyse, de simulation, de visualisation, etc. lorsque le code source complet est disponible. En outre, selon la [Définition de l'Open Source](https://opensource.org/osd), les logiciels libres doivent être distribués sous forme source et/ou compilée \(avec le code source disponible dans ce dernier cas\), et doivent être partagés sous une licence qui permet leur modification, leur dérivation et leur redistribution.

### Raison d'être

La recherche moderne repose sur les logiciels et, en s'appuyer sur - ou reproduire - cette recherche exige l'accès au code source complet du logiciel \([Barnes, 2010](https://doi.org/10/cj8t6n) ; [Morin et al., 2012](https://doi.org/10/m5t) ; [Ince et al., 2012](https://doi.org/10/hqg) ; [Prins et al. 2015](https://doi.org/10/f3mn4p) ; [Lowndes et al., 2018](https://doi.org/10/gc4jb3)\). Comme l'ont dit Buckheit et Donoho, paraphrasant Jon Claerbout, "Un article sur un résultat de calcul est de la publicité et non de la recherche. L'érudition réelle est l'environnement logiciel complet, le code et les données, qui ont produit le résultat" \([Buckheit & Donoho, 1995](https://doi.org/10.1007/978-1-4612-2544-7_5)\). Le libre accès au code source du logiciel de recherche contribue également à améliorer l'impact de la recherche \([Vandewalle, 2012](https://doi.org/10/gc5sjp)\).

Le partage des logiciels utilisés pour la recherche (qu'ils soient de nature informatique ou qu'ils reposent sur une analyse ou une interprétation logicielle) est une condition nécessaire, mais non suffisante, de la reproductibilité. Cela est dû à l'ambiguïté inévitable qui surgit lorsqu'on essaie de décrire un logiciel en utilisant le langage naturel, par exemple, dans un article \([Ince et al., 2012](https://doi.org/10/hqg)\). En outre, de nombreux logiciels (sinon la plupart) peuvent contenir des erreurs non détectées ([Soergel, 2015](https://doi.org/10/gc5sjg)\), de sorte que même une description écrite "parfaite" du logiciel ne serait pas en mesure de prendre en compte tous les résultats.

En plus de la reproductibilité, le partage de logiciels permet aux développeurs de recevoir des crédits de carrière pour leurs efforts, soit par citation directe \([Smith et al., 2016](https://doi.org/10/bw3g)\) ou par le biais de méta-articles logiciels publiés, par exemple, dans le [Journal of Open Research Software](http://openresearchsoftware.metajnl.com) ou le [Journal of Open Source Software](http://joss.theoj.org) \([Smith et al., 2018](https://doi.org/10/gc5sjf)\). Neil Chue Hong tient à jour une [liste de nombreuses revues spécialisées](https://www.software.ac.uk/which-journals-should-i-publish-my-software) qui publient des articles sur les logiciels.

## <img src="/Images/Icons/finish.png" width="150" height="150" />
### Objectifs d'apprentissage

1. Apprendre les caractéristiques des logiciels ouverts ; comprendre les arguments éthiques, juridiques, économiques et d'impact de la recherche pour et contre les logiciels ouverts, et mieux comprendre les exigences de qualité du code ouvert.

2. Apprendre à utiliser les logiciels ouverts existants et à les attribuer de manière appropriée.

3. Apprendre à utiliser des outils et des services communs pour partager ouvertement les codes de recherche.

4. Etre capable de choisir la licence appropriée pour leur logiciel, et comprendre la différence entre les licences permissives et non permissives.

### Composants-clés

## <img src="/Images/Icons/brain.png" width="150" height="150" />
#### Savoirs

Il existe plusieurs plates-formes différentes qui favorisent le partage ouvert et la collaboration en matière de logiciels, de recherche ou autres. Tout d'abord, vous pouvez utiliser cette liste de contrôle pour évaluer l'ouverture des logiciels de recherche existants :

* Le logiciel est-il disponible pour téléchargement et installation ?

* Le logiciel peut-il être facilement installé sur différentes plates-formes ?

* Le logiciel a-t-il des conditions d'utilisation ?

* Le code source est-il disponible pour inspection ?

* L'historique complet du code source est-il disponible pour inspection par le biais d'un historique des versions accessible au public ?

* Les dépendances du logiciel (matériel et logiciel) sont-elles décrites correctement ? Ces dépendances ne requièrent-elles qu'un minimum d'efforts pour les obtenir et les utiliser ?

Ces qualités se rapportent à la [Définition de l'Open Source](https://opensource.org/osd) et s'appuient sur elle.

[git](https://git-scm.com/) est un outil populaire qui permet le contrôle de version : gestion et suivi global des changements dans un logiciel particulier. Des services tels que [GitHub](www.github.com), [GitLab](https://about.gitlab.com/), [Bitbucket](https://bitbucket.org/), et d'autres fournissent une interface à l'outil ainsi que des services de stockage à distance qui peuvent être utilisés pour maintenir, partager et collaborer sur des logiciels de recherche. En tant qu'outil, il est très répandu et, bien qu'il ait une courbe d'apprentissage initiale, il s'est avéré inestimable pour établir un flux de travail de recherche ouvert et reproductible.

Avoir le logiciel de recherche sur GitHub n'est que la première partie ; il est tout aussi important d'avoir un identifiant publié et persistant qui lui est associé, comme un DOI. Il y a plusieurs façons d'associer un DOI à un dépôt GitHub ; la plus simple est d'utiliser [Zenodo](www.https://zenodo.org/) \(un dépôt libre et ouvert créé par [OpenAIRE](https://www.openaire.eu/) et le [CERN](https://home.cern/)\) pour faire le travail, bien que d'autres dépôts pour archiver des logiciels et obtenir un DOI existent, tel que [Figshare](https://figshare.com/). [Zenodo s'intègre avec GitHub](https://guides.github.com/activities/citable-code/) pour archiver le logiciel et fournir un DOI lorsque les développeurs font une version officielle sur GitHub.

Un logiciel partagé publiquement n'est en fait pas un logiciel libre à moins d'être accompagné d'une licence appropriée, car par défaut, le logiciel \(ainsi que toute autre œuvre de création\) relève du droit d'auteur exclusif des créateurs, ce qui signifie que personne d'autre ne peut utiliser, copier, distribuer ou modifier votre œuvre \([choosealicense.com](https://choosealicense.com/no-permission/)\). \(Si vous voulez vraiment partager votre code sans aucune restriction, vous pouvez [le dédier au domaine public](https://choosealicense.com/licenses/#unlicense)\). Au lieu de cela, vous devriez choisir une licence appropriée pour votre logiciel, basée sur ce que vous préféreriez laisser les autres faire \(ou les empêcher de faire\) avec votre code ; le site [choosealicense.org](https://choosealicense.com) est une ressource utile pour différencier les licences, bien qu'il ne comporte pas [chaque licence open-source disponible ou populaire](https://opensource.org/licenses). Une fois que vous avez sélectionné une licence, mettez le texte - édité pour inclure le nom de l'auteur\(s\) et l'année - dans le référentiel du logiciel sous forme de fichier LICENSE en texte clair.

![](/Images/02%20Open%20Science%20Basics/02_open_research_software_open_source.png)

Bien qu'il soit préférable de partager un logiciel sous quelque forme que ce soit plutôt que de ne pas le partager, votre logiciel aura plus d'impact et sera plus facilement utilisé par les autres - et par vous-même à l'avenir - si vous incluez la documentation. Cela peut inclure des commentaires utiles dans le code qui expliquent **pourquoi** vous avez fait quelque chose \(plutôt que ce que vous avez fait, ce qui devrait être évident\), un fichier README informatif qui décrit ce que fait votre logiciel et donne quelques informations utiles \(par exemple, comment installer, comment citer, comment exécuter, dépendances importantes\), tutoriels / exemples, et/ou documentation API \(qui peuvent être générés automatiquement à partir de commentaires correctement formatés dans le code @).

Des dépendances manquantes ou inaccessibles ou une documentation insuffisante de l'environnement informatique sont des obstacles très courants à la réutilisation et à la reproductibilité. Une approche pour surmonter ces obstacles consiste à partager votre code avec votre environnement informatique à l'aide de la technologie des conteneurs. Les conteneurs empaquettent le code avec les dépendances et l'environnement de calcul pour que d'autres puissent plus facilement exécuter votre analyse. Parmi les exemples de mise en œuvre de conteneurs dans le cadre de la recherche, mentionnons [Rocker](https://arxiv.org/abs/1710.03675), [Binder](https://mybinder.readthedocs.io/en/latest/), et [Code Ocean](https://codeocean.com/).

Lorsque vous utilisez un logiciel - que vous l'ayez écrit ou que quelqu'un d'autre l'ait fait et l'ait rendu disponible - une citation appropriée est importante pour la reproductibilité \(discutée plus en détail dans la [Section 4](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_FR/blob/master/02OpenScienceBasics/04ReproducibleResearchAndDataAnalysis.md) ; brièvement, la version utilisée peut changer vos résultats ou votre interprétation\) et donner crédit aux développeurs du logiciel \([Niemeyer 2016](doi.org/10/gc5sjd), [Smith 2016](https://doi.org/10/bw3g)\). La décision de citer un logiciel dépend de vous en tant que chercheur, mais nous vous recommandons une citation chaque fois que le logiciel a fait un travail qui fait partie intégrante de vos résultats, de votre interprétation ou de vos conclusions. La meilleure façon de rendre _votre_ code facilement citable est d'utiliser l'intégration GitHub-Zenodo décrite précédemment et de fournir le DOI résultant dans un endroit évident comme le README du logiciel, peut-être avec un format de citation suggéré. Lorsque vous citez un logiciel, vous devez inclure au minimum le nom de l'auteur\(s\), le titre du logiciel, le numéro de version et l'identificateur/localisateur unique \([Smith 2016](https://doi.org/10/bw3g)\). Si vous utilisez le logiciel de quelqu'un d'autre et qu'il a fourni un DOI, alors vous pouvez facilement l'utiliser pour identifier et pointer vers le logiciel ; s'il n'a pas archivé son logiciel, alors vous devriez inclure une URL où le logiciel peut être trouvé et le numéro de version ou \(par exemple \) commit hash.

Parmi les autres concepts plus complexes, mentionnons les tests automatisés et l'intégration continue des logiciels, l'emballage des logiciels en format binaire et la gouvernance et la gestion de projets de logiciels libres pour plusieurs personnes (c.-à-d. codes de conduite, guides de contribution, etc.). Certains de ces sujets sont décrits par [Scopatz et Huff \(2015\)](http://lilith.fisica.ufmg.br/~dickman/transfers/comp/textos/Effective%20Computation%20in%20Physics%20(Python).pdf).  [Wilson et al. \(2017\)](https://doi.org/10/gbkbwp) fournit également un guide pratique des meilleures pratiques en matière de calcul scientifique qui comprend des conseils spécifiques sur le développement de logiciels de recherche.

## <img src="/Images/Icons/laptop.png" width="150" height="150" />
##### Matériel Open Source

Les principes open source ci-dessus s'étendent au matériel. Les chercheurs utilisent souvent des instruments ou du matériel exclusifs qui ne sont pas librement accessibles, réutilisables ou adaptables dans le cadre de leurs recherches. Le matériel scientifique comprend des outils de séquençage, des microscopes, du matériel d'essai spécialisé et des collisionneurs de particules. La communauté Open Science Hardware \(OScH\), par exemple, est à la tête d'un mouvement en faveur de l'inclusion des outils scientifiques, du matériel et des infrastructures de recherche dans le mouvement open source par le biais de sa [Global Open Science Hardware Roadmap] (http://openhardware.science/global-open-science-hardware-roadmap/).

## <img src="/Images/Icons/gears.png" width="150" height="150" />
#### Savoir-faire

* Créer un référentiel sur GitHub, et permettre l'intégration avec Zenodo. Menthez la première version du logiciel.

* Choisissez une licence de logiciel en utilisant \(e.g.\)[choosealicense](https://choosealicense.com) ou l'[Open Source Initiative](https://opensource.org/licenses).

* Créer la documentation d'un progiciel, y compris le README, les commentaires et les exemples.

* Citer de façon appropriée le logiciel utilisé pour un article.

## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Questions, obstacles et idées fausses courantes

Q : "Je ne peux pas partager mon logiciel - c'est trop salissant / il n'a pas une bonne documentation / je n'ai pas laissé de bons commentaires !

R : Les développeurs de logiciels de recherche du monde entier sont sensibles à ce sentiment - les gens ont rarement l'impression que leur code est "prêt" à partager publiquement ou qu'il est "fini". Cependant, comme l'a dit [Barnes \(2010\(2010\)](https://doi.org/10/cj8t6n), "si votre code est assez bon pour faire le travail, alors il est assez bon pour le publier - et le publier aidera votre recherche et votre domaine". En d'autres termes, si vous vous sentez suffisamment à l'aise avec votre logiciel pour publier une étude ou un rapport de résultats, alors le code est suffisamment développé pour être partagé avec vos collègues. \(Dans l'autre sens, si vous ne vous sentez pas à l'aise de partager le code, alors peut-être que cela nécessite plus de développement ou de tests avant de l'utiliser dans une publication\). De plus, le partage de votre code permet aux autres de l'améliorer et de s'en inspirer, ce qui mène à un impact et à une innovation encore plus grands (et des citations pour vous !).

Q : "Et si quelqu'un prend le code que j'ai partagé et l'utilise à des fins malveillantes, ou prétend l'avoir écrit ?"

R : Choisir une licence appropriée pour votre logiciel vous aidera à vous protéger contre toute utilisation de votre logiciel par d'autres ; par exemple, la [licence MIT] (https://choosealicense.com/licenses/mit/) inclut à la fois des limitations de responsabilité et indique qu'aucune garantie n'est fournie. Si quelqu'un d'autre essaie de prétendre qu'il a écrit le logiciel que vous avez mis à disposition, vous pouvez alors pointer les horodatages sur votre référentiel ou les versions archivées comme preuve de votre travail antérieur.

Q : "Si je partage mon code dans un référentiel en ligne, je serai inondé de demandes de support utilisateur."

R : Bien que les utilisateurs potentiels puissent vous demander de l'aide, soit par courriel, soit par des problèmes déposés dans le dépôt en ligne, vous n'êtes pas obligé de fournir de l'aide si vous préférez ne pas le faire ou ne pouvez pas le faire. Une licence appropriée vous fournit même une protection légale pour cela \(par exemple, la clause de non-garantie de la [licence MIT] (https://choosealicense.com/licenses/mit/)\).

Idée fausse courante : le simple fait de mettre du code en ligne en fait un logiciel open-source. En fait, à moins que le logiciel ne soit accompagné d'une licence qui autorise d'autres personnes à utiliser, copier, modifier et/ou distribuer le logiciel, le développeur conserve le droit d'auteur exclusif. Une licence open-source doit accompagner le code pour en faire un logiciel open-source.

## <img src="/Images/Icons/output.png" width="150" height="150" />
### Résultats d'apprentissage

1. Être en mesure de partager le logiciel sous la licence la plus appropriée (c.-à-d. les outils et la licence).

2. Pouvoir télécharger, versionner et enregistrer un morceau de code sous un identificateur persistant.

3. Être capable de citer un logiciel utilisé pour un article de recherche.

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Lectures complémentaires

* Balasegaram et al. (2017). An open source pharma roadmap. [doi.org/10.1371/journal.pmed.1002276](https://doi.org/10.1371/journal.pmed.1002276) 

* Dryden et al. (2017). Upon the Shoulders of Giants: Open-Source Hardware and Software in Analytical Chemistry. [doi.org/10.1021/acs.analchem.7b00485](https://pubs.acs.org/doi/abs/10.1021/acs.analchem.7b00485) 

* Ince et al. (2012). The case for open computer programs.[doi.org/10.1038/nature10836](https://doi.org/10.1038/nature10836)

* Iskoujina and Roberts (2015). Knowledge sharing in open source software communities: motivations and management. [PDF](https://pdfs.semanticscholar.org/f2a2/c5129cf5656af7acc7ffaf84c9c9bafe72c5.pdf)

* Jiménez et al. (2017).Four simple recommendations to encourage best practices in research software. [doi.org/10.12688/f1000research.11407.1](https://doi.org/10.12688/f1000research.11407.1) 

* Martinez-Torres and Diaz-Fernandez (2013).Current issues and research trends on open-source software communities [PDF](https://idus.us.es/xmlui/bitstream/handle/11441/32245/Current%20issues%20and%20research%20trends.pdf?sequence=1) 

* Morin et al. (2012). Shining Light into Black Boxes. [PDF](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4203337/pdf/nihms588981.pdf)

* Oishi et al. (2018). Perspectives on Reproducibility and Sustainability of Open-Source Scientific Software from Seven Years of the Dedalus Project. [arXiv:1801.08200v1 [astro-ph.IM]](https://arxiv.org/abs/1801.08200)

* Scacchi (2010). The Future of Research in Free/Open Source Software Development. [PDF](http://www.ics.uci.edu/~wscacchi/Papers/New/FoSER-Scacchi-2010.pdf)

* Sandve et al. (2013). Ten simple rules for reproducible computational research [doi.org/10.1371/journal.pcbi.1003285](https://doi.org/10.1371/journal.pcbi.1003285) 

* Shamir et al. (2013).Practices in source code sharing in astrophysics. [arXiv:1304.6780v1 [astro-ph.IM]](https://arxiv.org/abs/1304.6780) 

* Steinmacher et al. (2014). A systematic literature review on the barriers faced by newcomers to open source software projects. [PDF](http://igor.pro.br/publica/papers/IST_SysReview_PrePrint.pdf) 

* Stodden (2010). The Scientific Method in Practice: Reproducibility in the Computational Sciences.[PDF](http://datascienceassn.org/sites/default/files/The%20Scientific%20Method%20in%20Practice%20-%20Reproducibility%20in%20the%20Computational%20Sciences.pdf)

* Vandewalle (2012). Code Sharing Is Associated with Research Impact in Image Processing. [PDF](https://infoscience.epfl.ch/record/206184/files/Vandewalle12.pdf) 
