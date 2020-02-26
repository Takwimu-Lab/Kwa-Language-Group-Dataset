# KwaLanguageGroupNLPDataset
This is a dataset of fon, ewe and kabiye sentences annotated for NLP tasks / Ceci est un datasets de phrases fon, éwé et kabyè annoté pour des tâches NLP

## ENGLISH 

This dataset was created by an association of data scientists professionals and	enthusiasts from Benin and Togo called Takwimu Lab. We came together in 2019 with two main objectives : 

* Attract, train and share our experience with data science enthusiasts across francophone West Africa. 
* Learn together and build solutions that solve specific typical west african solutions that companies and any random citizen can benefit from 

The data was submitted and won best submission in the [AI4D-African Language Dataset Challenge](https://zindi.africa/competitions/ai4d-african-language-dataset-challenge) for the month of January 2020.

### Composition of the dataset

The dataset is composed of sentences in three different languages all arranged in separate files :

* The dataset in file kabiyeData.txt comprises monolingual data instances described as follows :  The seven first kabiye text bodies are collections of short stories written by learners and teachers in  literacy program organized by the Christian Association for literacy in Kabiye and Fulfilment (Association Chrétienne pour l’Alphabétisation en Kabiyè et l'Épanouissement ) based in Sotouboua Togo. The rest of the the kabiye text bodies are wikipedia articles scraped from the wikipedia	 website. We collected  text from 9 pdf files in kabiye (8 novels and 1 file containing proverbs in kabiye). We also collected data from 1567 wikipedia articles and the total is around 26000 sentences.

* The dataset in file fongbeData.txt comprises parallel data fongbe - french instances described as follows :
The two first instances are collections of  syntactic dictionary and complex phrases extracted from a website (beninlangues.com) that publishes content on learning fongbe language and Benin culture. The remaining instances are collections of seven documents extracted from  [ipedef-fongbe.org](https://ipedef-fongbe.org/) which publishes content on learning fongbe language and Benin culture with a categorization of the documents. Html text are 2 instances which are 20273 sentences in fongbe with their translation in french. Pdf documents are 7 instances which are about 800 sentences in fongbe with their translation in french. And the total is around 21060 sentences.

* The dataset in file eweData.txt comprises monolingual ewe data scraped from the ewe subdomain of wikipedia. The articles are mostly about countries in the world and famous personalities throughout history. 522 wikipedia articles in ewe were scraped for a total of around 4000 sentences.

### Collection Process

All data submitted was directly observable from either websites or other online documents. No derivation or translation was required from our side. Part of the data was scraped from [kbp.wikipedia.org](kbp.wikipedia.org), [ee.wikipedia.org](ee.wikipedia.org), [ipedef-fongbe.org](https://ipedef-fongbe.org) and [https://beninlangues.com/](https://beninlangues.com/). The kabye stories were copied from pdf files available at [http://www.kabiyesekuliye.net/](http://www.kabiyesekuliye.net/). All the data was collected between 13th and 25th January 2020 from wikipedia.
The kabiye short stories were initially written in 2011.

The scraping was done using Python3 code and libraries such as Requests, BeautifulSoup, pdftotext, and the wikipedia api implementation for Python. The number, categories and content of articles were checked from the statistics available on wikipedia or from some of the articles’ content themselves.

Five members of Takwimu Lab worked on this collection :

- (Godson KALIPE)[https://github.com/godsonk]
- Jamiil Toure ALI
- (Kevin DEGILA)[https://github.com/kevindegila]
- Yannick KIKI
- Bola Balogoun

### Preprocessing 

Empty articles and articles having only sections’ titles as content were removed. Articles and stories content were split to keep only one sentence per line. We also wrote a small python script to organize the data from csv format into the text format required by the competition and to remove trailing and leading white spaces. The categories assigned to the wikipedia articles, pdf documents are the ones associated with the articles online.

### CONTACT

Contributions are all welcome in order to enrich the dataset, report issues or put forward your suggestions. Also, Reach out and let us know of the ways you re using this dataset by contacting us @ takwimulab@gmail.com .

## FRANÇAIS

Ce dataset a été créé par une association de professionels et enthousiastes de la data science au Bénin et au Togo appelée Takwimu Lab. Nous nous sommes mis ensemble en 2019 avec deux objectifs principaux : 

* Attirer, Former du talent data science et partager nos expériences avec les enthousiastes de la data science à travers l'Afrique de l'Ouest Francophone. 
* Apprendre ensemble et mettre en place des solutions qui résolvent des problèmes typiquement africains dont les entreprises et la population pourraient bénéficier. 

Ce dataset a été soumis au [AI4D-African Language Dataset Challenge](https://zindi.africa/competitions/ai4d-african-language-dataset-challenge) et a été retenu meilleur dataset pour le mois de Janvier 2020.

### Composition du dataset

Ce dataset est composé de phrases en 3 différentes langues arrangées en fichiers séparés :

* Les donnés du fichier kabiyeData.txt comprennent des instances de donnés monolingues décrites comme suit :  Les sept premiers corps de texte kabyè sont des collections d'histoires courtes écrites par des apprenants et des enseignants dans le programme d'alphabétisation organisé par l'Association Chrétienne pour l’Alphabétisation en Kabiyè et l'Épanouissement basée à Sotouboua au Togo. Le reste des corps de texte kabyè sont des articles scrapés de Wikipedia. Nous avons collecté du texte de 9 pdfs kabyè (8 romans and 1 recueil de proverbes en kabyè). Nous avons également collecté 1567  articles wikipedia et le total a produit environ 26000 phrases.

* Le dataset dans le fichier fongbeData.txt comprend des pairs de phrase fongbe - français décrites comme suit :
Les deux premières instances sont des collections de données d'un dictionnaire syntaxique et des phrases complexes extraites  du site [beninlangues.com](beninlangues.com) qui publie du contenu pour apprendre la langue fongbe et des ressources sur la culture du Bénin. Les instances restantes sont des collections de sept documents extraits de [ipedef-fongbe.org](https://ipedef-fongbe.org/) , un site qui publie également des documents sur la culture et pour l'apprentissage de la langue mais avec une catégorisation des documents. 20273 phrases ont été extraites des pages web fongbe avec leur traduction correspondante en français. 800 paires de phrase ont également été extraites de 7 documents pdf pour un total de 21060 phrases.

* Les données dans le fichier eweData.txt comprennent des phrases monolingues en ewe data scrapées du sous-domaine éwé de Wikipedia. Les articles concernent principalement les pays dans le monde et les personnalités célèbres à travers l'histoire. 522 articles wikipedia en éwé ont été scrapées pour un total d'environ 4000 phrases.

### Procédure de collection

Aucune dérivation ou traduction n'a été faite par l'équipe de Takwimu. Les traductions ont été mises ensemble tel qu'observées. Une partie des données a été scrapée de [kbp.wikipedia.org](kbp.wikipedia.org), [ee.wikipedia.org](ee.wikipedia.org), [ipedef-fongbe.org](https://ipedef-fongbe.org) et [https://beninlangues.com/](https://beninlangues.com/). Les histoires kabyè ont été recueillies de fichiers pdf disponibles sur [http://www.kabiyesekuliye.net/](http://www.kabiyesekuliye.net/). Les données ont été collectées entre le 13 et le 25 Janvier 2020 de wikipedia.
Les courtes histoires kabyè ont été initialement écrites en 2011.

Le scraping a été fait en utilisant Python3 et des librairies telles que Requests, BeautifulSoup, pdftotext, et l'implémentation python de l'api wikipedia. Le nombre, les catégories et le contenu des articles ont éte vérifiées depuis les pages de statistiques disponibles sur Wikipedia.

Cinq membres de Takwimu Lab ont travaillé à la collection :

- (Godson KALIPE)[https://github.com/godsonk]
- Jamiil Toure ALI
- (Kevin DEGILA)[https://github.com/kevindegila]
- Yannick KIKI
- Bola Balogoun

### Preprocessing 

Les articles vides et les articles n'ayant que leur titre comme contenu ont été retirés. Le contenu des articles et des histoires ont été organisées pour ne garder qu'une phrase par ligne. Nous avons également écrit un petit script python pour organiser les données des fichiers csv au format texte et retirer les espaces en début et en fin de phrases. Les catégories assignées aux articles Wikipédia sont celles qui leur ont été attribuées par Wikipedia sur le site.

### CONTACT

Les contributions sont les bienvenues dans le but d'enrichier le dataset, reporter des problèmes ou faire des suggestions. Aussi, contactez nous à l'adresse takwimulab@gmail.com pour nous faire découvrir vos cas d'utilisation faisant usage de ce dataset.
