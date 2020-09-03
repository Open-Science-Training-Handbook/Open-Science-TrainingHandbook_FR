<img src="/Images/Icons/open_source_software.png" width="150" height="150" /> <img src="/Images/Icons/publish.png" width="150" height="150" />

## 3.Logiciels de Recherche Ouverts et de Source ouverte

### De quoi parle t-on ?

Les logiciels de recherche ouverts, ou logiciels libres de recherche, font référence à l'utilisation et au développement de logiciels d'analyse, de simulation, de visualisation, etc. dont le code source complet est disponible. En outre, selon la *Définition du logiciel libre*, un logiciel libre doit être distribué sous forme de source et/ou de compilation (avec le code source disponible dans ce dernier cas), et doit être partagé sous une licence qui en autorise la modification, la dérivation et la redistribution.

### Fondement 

La recherche moderne s'appuie sur des logiciels et, pour pouvoir la développer ou la reproduire, il faut avoir accès au code source complet de ces logiciels ([Barnes, 2010](https://doi.org/10/cj8t6n); [Morin et al., 2012](https://doi.org/10/m5t); [Ince et al., 2012](https://doi.org/10/hqg); [Prins et al. 2015](https://doi.org/10/f3mn4p); [Lowndes et al., 2018](https://doi.org/10/gc4jb3)). Comme l'ont déclaré Buckheit et Donoho, en paraphrasant Jon Claerbout, "Un article sur un résultat de calcul est une annonce publicitaire, pas de la recherche. La véritable contribution à la recherche est l'environnement logiciel complet, le code et les données qui ont produit le résultat" (Buckheit & Donoho, 1995). Un accès ouvert au code source des logiciels de recherche contribue également à améliorer l'impact de la recherche (Vandewalle, 2012).

Le partage des logiciels utilisés pour la recherche (qu'il s'agisse de logiciels de calcul ou d'analyse) est une condition nécessaire, mais non suffisante, de la reproductibilité. Cela est dû à l'ambiguïté inévitable qui survient lorsque l'on tente de décrire intégralement un logiciel en utilisant le langage naturel, par exemple, dans un article (Ince et al., 2012). En outre, de nombreux logiciels (sinon la plupart) peuvent contenir des erreurs non détectées (Soergel, 2015), de sorte que même une description écrite "parfaite" d'un logiciel ne saurait rendre compte de tous les résultats obtenus par son utilisation.

En plus de la reproductibilité, le partage ouvert des logiciels permet aux développeurs de recevoir une reconnaissance professionnelle pour leurs efforts, soit via une citation directe (Smith et al., 2016), soit via des méta-articles sur les logiciels publiés dans des revues telles que *The Journal of Open Research Software* ou *The Journal of Open Source Software* (Smith et al., 2018). Neil Chue Hong tient à jour une liste de nombreuses revues spécialisées qui publient des articles sur les logiciels.

## <img src="/Images/Icons/finish.png" width="150" height="150" />

### Objectifs de la formation 

1. Apprendre les caractéristiques des logiciels ouverts ; comprendre les arguments éthiques, juridiques, économiques et d'impact sur la recherche pour et contre les logiciels ouverts, et mieux comprendre les exigences de qualité du code ouvert.

2. Apprendre à utiliser les logiciels ouverts existants et à les attribuer (les citer) de manière appropriée.

3. Apprendre à utiliser des outils et des services courants pour partager librement le code des logiciels de recherche.

4. Etre capable de choisir la licence appropriée pour un logiciel et comprendre la différence entre licences permissives et non permissives.

### Éléments clés 

## <img src="/Images/Icons/brain.png" width="150" height="150" />

#### Connaissances

Il existe plusieurs plateformes différentes qui permettent le partage et la collaboration ouverts sur les logiciels, la recherche ou autre. Tout d'abord, vous pouvez utiliser cette liste de contrôle pour évaluer le degré d'ouverture des logiciels de recherche existants :

* Le logiciel est-il disponible pour être téléchargé et installé ?

* Le logiciel peut-il être facilement installé sur différentes plateformes ?

* Le logiciel est-il assorti de conditions d'utilisation ?

* Le code source est-il disponible pour vérification ?

* L'historique complet du code source est-il disponible pour vérification par le biais d'un historique des versions accessible publiquement ?

* Les interdépendances du logiciel (avec du matériel et d'autres logiciels) sont-elles correctement décrites ? Ne nécessitent-elles qu'un effort raisonnablement minimal pour les obtenir et les utiliser ?

Ces critères sont liés à la Définition de l'Open source ([Open Source Definition](https://opensource.org/osd).) et s'appuient sur celle-ci.

GitHub est un outil populaire qui permet le contrôle de versions, c'est à dire la gestion et le suivi global des changements dans un certain type de logiciel. Des services tels que GitHub, GitLab, Bitbucket et d'autres fournissent une interface à l'outil ainsi que des services de stockage à distance qui peuvent être utilisés pour maintenir, partager et collaborer sur des logiciels de recherche. En tant qu'outil, il est assez répandu et, bien qu'il ait une courbe d'apprentissage initiale, il s'est révélé inestimable pour établir un flux de travail ouvert et reproductible.

Déposer un logiciel de recherche sur GitHub n'est que la première étape ; il est tout aussi important d'y associer un identifiant publié et pérenne, tel qu'un DOI. Il existe plusieurs façons d'associer un DOI à un dépôt GitHub ; la plus simple est d'utiliser Zenodo (un entrepôt de données polyvalent gratuit et ouvert créé par OpenAIRE et le CERN), bien qu'il existe d'autres dépôts pour l'archivage de logiciels et l'obtention d'un DOI, tels que [Figshare](https://figshare.com/) ou [Zenodo integrates with ]](https://guides.github.com/activities/citable-code/), pour archiver le logiciel et fournir un DOI lorsque les développeurs en déposent une version officielle sur GitHub.

En fait, les logiciels partagés publiquement ne sont pas des logiciels libres ou open source, sauf s'ils sont accompagnés d'une licence appropriée, car par défaut, les logiciels (ainsi que tout autre travail créatif) sont soumis au régime du droit d'auteur exclusif des créateurs, ce qui signifie que personne d'autre ne peut utiliser, copier, distribuer ou modifier votre travail ([[choosealicense.com]](https://choosealicense.com/)). (Si vous souhaitez véritablement partager votre code sans aucune restriction, vous pouvez le placer dans le domaine public). Dans ce cas, vous devrez plutôt choisir une licence appropriée à votre logiciel, en fonction de ce que vous préféreriez que les utilisateurs puissent faire (ou pas) de votre code. Le site choosealicense.org est une ressource utile pour différencier les licences, bien qu'il ne présente pas toutes les licences open source disponibles ou populaires. Une fois que vous aurez sélectionné une licence, déposez le texte - modifié pour inclure le nom de l'auteur/des auteurs et la date - dans le dépôt de logiciels sous la forme d'un fichier LICENCE en texte simple.

![](/Images/02%20Open%20Science%20Basics/02_open_research_software_open_source.png)


Bien qu'il soit préférable de partager un logiciel sous quelque forme que ce soit plutôt que de ne pas le partager, votre logiciel aura plus d'impact et sera plus facilement utilisé par les autres - et par vous-même à l'avenir - si vous incluez de la documentation. Celle-ci peut inclure des commentaires utiles dans le code qui expliquent **pourquoi** vous avez fait tel ou tel choix (plutôt que ce que vous avez fait, ce qui devrait être évident), un fichier LISEZMOI informatif décrivant ce que fait votre logiciel et donnant quelques informations utiles (par exemple, comment l'installer, comment le citer, comment l'exécuter, les principaux liens), des tutoriels/exemples, et/ou de la documentation sur l'API (pouvant être générée automatiquement à partir de commentaires correctement formatés dans le code).

Des liens manquants, inaccessibles ou une documentation insuffisante sur l'environnement informatique sont des obstacles très courants à la réutilisation et à la reproductibilité. L'une des approches permettant de surmonter ces obstacles consiste à partager votre code avec votre environnement informatique en utilisant la technologie des conteneurs. Les conteneurs regroupent le code avec les liens et l'environnement de calcul afin que d'autres puissent plus facilement effectuer votre analyse. Parmi les exemples de mise en œuvre de conteneurs dans la recherche on trouve : [Rocker](https://arxiv.org/abs/1710.03675), [Binder](https://mybinder.readthedocs.io/en/latest/) et [Code Ocean](https://codeocean.com/).

Lorsque vous utilisez un logiciel - que vous l'ayez écrit ou que quelqu'un d'autre l'ait fait et l'ait mis à disposition - il est important de le citer correctement pour en assurer la reproductibilité (voir la [Section 4](https://github.com/Open-Science-Training-Handbook/Open-Science-Training-Handbook_FR/blob/master/02OpenScienceBasics/04ReproducibleResearchAndDataAnalysis.md). En bref, la version utilisée peut modifier vos résultats ou votre interprétation) et créditer les développeurs du logiciel (Niemeyer 2016, [Smith 2016](https://doi.org/10/bw3g)). La décision du moment auquel citer un logiciel vous appartient en tant que chercheur, mais nous recommandons une citation chaque fois que le logiciel a permis d'effectuer un travail faisant partie intégrante de vos résultats, de votre interprétation ou de vos conclusions. La meilleure façon de rendre *votre* code aisément citable est d'utiliser l'intégration GitHub-Zenodo décrite précédemment, et d'indiquer le DOI obtenu à un endroit évident comme le fichier LISEZMOI du logiciel, éventuellement accompagné d'une suggestion de format de citation. Lorsque vous citez un logiciel, vous devez inclure au minimum le nom de l'auteur/des auteur(s), le titre du logiciel, le numéro de la version et son identifiant/adresse unique (Smith 2016). Si vous utilisez le logiciel de quelqu'un d'autre, et que l'auteur a fourni un DOI, vous pouvez facilement l'utiliser pour identifier et pointer vers le logiciel ; si l'auteur n'a pas archivé son logiciel, vous devez alors inclure une URL à laquelle le logiciel peut être trouvé, le numéro de version ou son identifiant de commit.

Parmi d'autres concepts plus complexes, citons les tests automatisés et l'intégration continue des logiciels, le regroupement des logiciels dans des formats binaires, ainsi que la gouvernance et la gestion des projets de logiciels libres associant plusieurs personnes (codes de conduite, guides de contribution). Certains de ces sujets sont décrits par [Scopatz et Huff \(2015\)](http://lilith.fisica.ufmg.br/~dickman/transfers/comp/textos/Effective%20Computation%20in%20Physics%20(Python).pdf).  [Wilson et al. \(2017\)](https://doi.org/10/gbkbwp) fournissent également un guide utile des meilleures pratiques en matière de calcul scientifique qui comprend des conseils spécifiques au développement de logiciels de recherche.

## <img src="/Images/Icons/laptop.png" width="150" height="150" />

##### Matériel open source

Les principes de l'open source ci-dessus s'étendent au matériel. Les chercheurs utilisent souvent dans leurs recherches des instruments ou du matériel propriétaires qui ne sont pas librement accessibles, réutilisables ou adaptables. Le matériel scientifique comprend tout, des outils de séquençage et des microscopes aux équipements de test spécialisés et aux collisionneurs de particules. La communauté Open Science Hardware (OScH), par exemple, mène une campagne pour que le mouvement open source inclue les outils scientifiques, le matériel et les infrastructures de recherche au moyen de sa Feuille de Route Globale pour le Matériel Scientifique Ouvert ([Global Open Science Hardware Roadmap](http://openhardware.science/global-open-science-hardware-roadmap/)[.](http://openhardware.science/global-open-science-hardware-roadmap/)

![](/Images/Icons/gears.png)


#### Compétences 

* Créer un entrepôt sur GitHub, et activer l'intégration avec Zenodo. Publier la première version du logiciel.

* Choisir une licence logicielle en utilisant par exemple [choosealicense](https://choosealicense.com/) ou l'[[Open Source Initiative]](https://opensource.org/licenses).

* Créer la documentation pour le logiciel, y compris le fichier LISEZMOI, des commentaires et des exemples

* Citez de manière appropriée les logiciels utilisés pour un article.


![](/Images/Icons/questions.png)


### Questions, obstacles et idées fausses reçues 

Q : "Je ne peux pas partager mon logiciel -- il est trop brouillon / il ne comporte pas une bonne documentation / je n'ai pas laissé de bons commentaires ! "

R : Les développeurs de logiciels de recherche dans le monde entier sont sensibles à ce sentiment - les gens ont rarement le sentiment que leur code est "prêt" à être partagé publiquement ou qu'il est "fini". Cependant, comme [Barnes (2010)](https://doi.org/10/cj8t6n) l'a mentionné, "Si votre code est assez bon pour faire le travail, alors il est assez bon pour être publié - et sa publication aidera votre recherche et votre domaine". En d'autres termes, si vous vous sentez suffisamment à l'aise avec votre logiciel pour publier une étude ou rendre compte des résultats, alors le code est suffisamment développé pour être partagé avec vos collègues. (Dans l'autre sens, si vous ne vous sentez pas à l'aise pour partager le code, alors peut-être qu'il nécessite plus de développement ou de tests avant d'être utilisé dans une publication). De plus, le partage de votre code permet à d'autres de l'améliorer et de le développer, ce qui entraîne un impact et une innovation encore plus importants (et des citations pour vous !).

Q : "Que se passe-t-il si quelqu'un prend le code que j'ai partagé et l'utilise à des fins malveillantes, ou prétend l'avoir écrit ? "

R : Le choix d'une licence appropriée pour votre logiciel vous aidera à vous protéger contre toute utilisation de votre logiciel par d'autres personnes. Par exemple, la licence commune [MIT License](https://choosealicense.com/licenses/mit/) inclut à la fois des limitations de responsabilité et stipule qu'aucune garantie n'est fournie. Si quelqu'un d'autre essaie de prétendre avoir écrit le logiciel que vous avez mis à disposition, vous pouvez alors présenter l'horodatage figurant sur votre dépôt ou les versions archivées comme preuve de l'antériorité de votre travail.

Q : "Si je partage mon code dans un dépôt en ligne, je serai submergé de demandes d'assistance de la part des utilisateurs".

R : Bien que les utilisateurs potentiels puissent vous demander de l'aide, par courrier électronique, ou (par ex. par le biais de questions déposées sur l'entrepôt en ligne, vous n'êtes pas obligé de fournir une assistance si vous préférez ou ne pouvez pas le faire. Une licence appropriée vous offre même une protection juridique à cet égard (par exemple, la clause de non-garantie de la [MIT License](https://choosealicense.com/licenses/mit/)).

Idée fausse courante : le simple fait de mettre un code en ligne en fait un logiciel à code source ouvert. En fait, à moins que le logiciel ne soit accompagné d'une licence autorisant d'autres personnes à l'utiliser, le copier, le modifier et/ou le distribuer, le ou les développeurs en conservent le droit d'auteur exclusif. Une licence libre doit accompagner le code pour en faire un logiciel libre.

![](/Images/Icons/output.png)


### Acquis de la formation 

1.  Etre capable de partager des logiciels sous la licence la plus appropriée (c'est-à-dire à la fois les outils et la licence).

2.  Etre capable de télécharger, de versionner et d'enregistrer un élément de code sous un identifiant permanent.

3.  Etre capable de citer un logiciel utilisé pour un article de recherche.


![](/Images/Icons/magnifying_glass.png)


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


