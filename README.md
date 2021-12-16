# Des données préparées pour le Datathon conjoint de l'IHA et du DFK Paris en novembre 2021

Here you will find the data that the DFK Paris has prepared for the joint datathon with the IHA in November 2021.

The data will be presented one after the other 

* the Critical Edition of the "Correspondence between Henri Fantin-Latour and Otto Scholderer, 1858-1902" (description in english by Anne Klammt)

* the research project "Deutsch-Französische Kunstvermittlung 1871–1940 und 1945–1960" (description in french by Deborah Schlauch)

All data are offered under the license [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 

---

## Correspondence between Henri Fantin-Latour and Otto Scholderer, 1858-1902

Lien vers la publication électronique: https://quellen.perspectivia.net/fr/fantin-scholderer/start


### 1. Overview

The data collection consists of 306 letters and four indices. The indices serve to index persons and places as well as the works of Fantin-Latour and Scholderer mentioned in the letters. Not all persons are explicitly mentioned in the letters, i.e. by name, but it was possible to identify them in the course of the scholarly work. Accordingly, comments by the editors can be found on these mentions in the edited letters. 
 

### 2. Indices
The four indices are available as individual files in .csv (comma separated values) format, and also summarised as sheets in an Excel-alike table document (.ods). 

| table | the linkage between each other | content  |
|---|---|---|
|index\_of_letters | ID of the letters | letters with author, recipient, date, place of issue, works and persons mentioned |
|index\_of_works | ID of the letters | works by Fantin-Latour and Scholderer mentioned |
|index\_of_places | ID of the letters | places and sites as well as exhibitions mentioned |
|index\_of_persons | ID of the letters | persons mentioned |


### 2.1 Index of works

A total of 368 different works mentioned in the correspondence were recorded. 359 of them can be determined and assigned to known works. The catalogue numbers from the work catalogues are entered for these accordingly. 

| record | content |
|---|---|
| B+Number | Catalog Number in: Jutta Bagdahn, *Otto Franz Scholderer 1834-1902*. Monographie und Werkverzeichnis, thèse de doctorat inédite, Freiburg i. Brsg., 2002 |  
| F+Number | Catalog Number in: Mme Fantin-Latour, *Catalogue complet 1849-1909 de Fantin-Latour*. Paris, Henri Floury éditeur 1911, rééd. Amsterdam-New-York, 1969 |
| H+Number | Catalog Number in: Germain Hédiard, *Fantin-Latour : catalogue de l’œuvre lithographique du maître, précédé d’une étude*. Paris, Librairie d’art ancien et moderne, 1906 |

The whereabouts of 244 of the works are known (as of 2010). Information on the technique and size is taken from the catalogues raisonnés mentioned above. 

| ID | Auteur | No de catalogue | Titre | Date | Technique | Dimensions | Lieu de conservation | Renvoi dans lettre no |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| #17662 | Scholderer | Reh mit Fischen (chevreuil et poissons) | 1873 |  | |  |  | 1873_04,... |


### 2.2 Index of persons

A total of 364 persons named in Fantin-Latour and Scholderer's correspondence were identified in the course of the letter edition. The index contains an ID, the name and a list of all letters in which the respective person appears. The field "Nom" can also contain an alias name in addition to the surname and first name.

| ID | Nom | Renvoi dans lettre no |
| --- | --- | --- |
| #17662 | Veronese, Paolo |  1858_03 |


#### 2.3 Index of places

The index of places lists all 124 places mentioned in the letters. These are geographical places as well as exhibition sites and exhibitions. In each case, the geographical name is placed in front and separated from the other details by a comma. Exceptions are those places where the letters are issued. In addition to a field for the ID, the index contains a field for the sites ("Lieu mentionné") and another field in which the places of evidence, i.e. the letters, are entered.

| ID | Lieu mentionné | Renvoi dans lettre no |
| --- | --- | --- |
| #11133 | Dijon |  1858_04 |

#### 2.4 Index of letters

The index of the 306 letters provides the synopsis of the persons, works and places mentioned together with the metadata of the letters (sender, addressee, place of issue and date). In the fields "Personnes mentionnées", "Lieux mentionnés", and "Œuvres mentionnées" several values may be entered, separated by a teaching position. The letters F and S in the field "Œuvres mentionnées" indicate Fantin-Latour or Scholderer and thus the author of the subsequently mentioned work. Words and values in square brackets are additions made in the course of scholarly editing.

| Lettre | Date | Lieu de création | Auteur | Destinataire | Personnes mentionnées | Lieux mentionnés | Œuvres mentionnées |
| --- | --- | --- | --- | --- | --- | --- | --- | 
|1858_03 | 1858-07-05 | Francfort [sur le Main] | Scholderer, Otto | 	Fantin-Latour, Henri | Mozart, Wolfgang Amadeus Rembrandt Legros, Alphonse ...  | Paris Francfort-sur-le-Main | S Selbstbildnis des 24jährigen Künstlers (autoportrait de l'artiste âgé de 24 ans) S Kopie nach Ferdinand Bol, Bildnis eines jungen Herren (copie d'après Ferdinand Bol, portrait d'un jeune homme) ...|

### 3. Scientifically edited letters

The 306 edited letters are each stored as a single HTML file.  In addition to the transcription, which also included an adjustment of the orthography, of the respective letter, they include the scholarly comments. All files are structured and labelled in the same way. 

1. ID of the letter (\<div data-meta_source_id="index_of_letters#1880_19" data-template_id="text_with_meta.tpl">).
2. link to preceding and following letter in the edition (\<nav class="non-source prev_next">\<a class="refprev" href="1880_18" rel="prev">1880_18\</a> \<a class="refnext" href="1881_01" rel="next">1881_01\</a>\</nav>).
3. then following as numbered paragraphs (\<p class="flush" id="1">).

* Place of issue, if necessary enclosed in square brackets if the place was identified in the course of the critical edition.
  
* Date of issue, if necessary enclosed in square brackets, the supplemented indication of the century. 
  
* Salutation *"Mon cher Fantin.... "* 
* Text of the letter. 

Inserted in the paragraphs are the scholarly annotations (\<span class="note">\<a class="note" data-sign="2" href="#n2">\</a>\<small class="non-source note" data-sign="2 " id="n2">Scholderer, Preparing for a Fancy Ball, B.188.\</small>\</span> citation of a work by Scholderer with title).

---

# La critique d’art franco-allemande 1870-1940 et 1945-1960
## 1.	Résumé
La collection de données appartenant à la base de données « Deutsch-Französische Kunstvermittlung » (La critique d’art franco-allemande) comprend à l’origine plus de 8000 jeux de données. Ils renseignent sur des périodiques, des articles de presse et des personnes (auteurs et artistes mentionnés). Environ 4500 noms de personnes et 288 périodiques sont désormais reliés aux notices d’autorité de Wikidata, de la Getty Union List of Artist Names (ULAN), de la Gemeinsame Normdatei (GND) ou de la Bibliothèque nationale de France (data.bnf.fr). Pour certains articles, des liens aux manifestes IIIF de gallica.bnf.br et de la bibliothèque universitaire de Heidelberg ont pu être identifiés.
Les données sont organisées dans deux tableaux, DFKV_Data_complet et DFKV_Master. Le tableau DFKV_Data_complet rassemble les données tirées de l’ancienne base de données, conservée dans un fichier JSON. L’autre tableau, DFKV_Master, comprend dix dossiers : volume id, type de texte, sujet, rubrique, lieu de publication, maison d’édition, personnes, rôles des personnes et attributs.

## 2. Les tableaux
Vous trouverez ci-dessous la structure des tableaux (en format xls) DFKV_Data_complet et DFKV_Master ainsi que la répartition des intitulés des colonnes du tableau DFKV_Data_complet et leur équivalent dans le tableau DFKV_Master.

### DFKV_Master
Ce tableau se compose de dix dossiers différents qui sont listés ci-après : 

#### Volume_ID
Le dossier Volume_ID contient sept colonnes : le numéro d’identification du jeu de données (à retrouver dans le tableau DFKV_Data_complet), le numéro d’identification du volume , et le numéro d'identification du journal. En plus on y trouve le lien IIIF qui relie le jeu de données à l’article numérisé en ligne, le lien de citation de l'article ou de la revue où la citation se trouve, et les détails de la référence bibliographique de la citation. 

|ID|Volume_ID|journal_id| liens iiif |liens de citation (page)| liens de citation (volume)|bibliographie|
| ------------- | ------------- | ------------- | ------------- |----|------|-------|
|14453|1634|1579|https://gallica.bnf.fr/iiif/ark:/12148/bpt6k6111456s/canvas/f258 | https://gallica.bnf.fr/ark:/12148/bpt6k6111456s/f258.item|    |.7, S. 239-240|

#### Journal
Le dossier Journal contient le numéro d’identification du journal, le nom du journal en trois langues (allemand, français, anglais) et le numéro d’identification des notices d’autorité de la GND, de la BnF et de Wikidata. 

|journal_id | de | fr | en | lobid_GND | BnF ID | Wikidata |
|-----------|-----|----|----|---------|-------|--------|
|1275 | A.B.C. artistique et littéraire | A.B.C. artistique et littéraire | A.B.C. artistique et littéraire |    | cb411679304 |    |

#### Type de texte, sujet, rubrique, lieu de publication, maison d’édition
Les tableaux de chacune de ces cinq catégories sont tous structurés de la même manière : ils se composent d’un numéro d’identification et de son intitulé en trois langues. Voir ci-dessous l’exemple du dossier « Type de texte ».

| id | de | fr | en |
|-----|----|----|----|
|9030 | Notiz | note | note |
|9035 | Aufsatz | article | essay |
| 9042 | Briefwechsel | correspondance | correspondence |

#### Personnes
Dans ce dossier toutes les personnes impliquées sont rassemblées. Il y a deux colonnes avec les numéros d’identification, « ID » et « ID_neu ». Le premier est l’ancienne ID qui est trouvable dans tous les autres tableaux et dossiers et qui est unique pour chaque entré de personnes. L’autre, « ID_2 », peut apparaître plusieurs fois, parce-que il indique les doublets. Ils se produisent lorsque différentes orthographes d'une même personne apparaissent dans différents textes et qu'ils ont donc été enregistrés plus d'une fois dans la base de données. 
Les colonnes « display_name », « first_name » et « last_name » indiquent différent parties des noms des personnes, le nom entier (nom, prénom), le prénom et le nom de famille. 
En fin les colonnes « ULAN » et  « Wikidata » contiennent les numéros d’identification des notices d'autorités connectés avec les personnes sur Wikidata et la Getty Union List of Artist Names (ULAN).

| ID | ID_neu | display_name | first_name | last_name | ULAN | Wikidata |
|----|------|------|--------|--------|--------|-------|
| 13 | 100013 | Hevesi, Ludwig | Ludwig | Hevesi |     | Q86534|
| 14 | 100014 | Lyka, Karl | Lyka | ulan/50008285 | Q116002 |

#### Rôles des personnes
Ce dossier contient le numéro d’identification que l’on peut retrouver dans le tableau DFKV_Data_complet.

| id | de | fr | en |
|----|----|----|----|
|12063| Ersteller | Créateur | Creator |
|12064| Beteiligt | Impliqué | Involved |
|12065| Dargestellt | Montré | Shown |
|12069| Übersetzer | Traducteur | Translator| 

#### Attributs
Ce dernier dossier rassemble des informations qui n’ont pas trouvé de place dans les autres dossiers mais qui sont attachées d’une manière ou d’une autre aux données. Il peut s’agir, par exemple, d’indications de lieux (ville) ou d’institutions (librairie, éditeur).

|id | de | fr | en |
|----|-----|----|----|
|1024| Dresden | Dresde | Dresden|
|1117| A. Bray | A. Bray | A. Bray|
|1120| Akademische Buchhandlung Max Drechsel | Akademische Buchhandlung Max Drechsel | Akademische Buchhandlung Max Drechsel |
|1121| Akademische Verlagsgesellschaft Athenaion | Akademische Verlagsgesellschaft Athenaion | Akademische Verlagsgesellschaft Athenaion|

### DFKV_Data_complet
Ce tableau est le résultat de la « décomposition » de la base de données et contient toutes les informations du fichier JSON originel. Chacune de ses deux colonnes est liée avec le tableau DFKV_Master ; voir les descriptions de leur contenu ci-dessous. 

|colonnes|description|
|----|--------|
|id| ID du jeu de données|
|project_id| Numéro du projet (publication)|
|date_human| Datation de l'entrée, indiquée par un/e chercheurs/chercheuses|
|date| Datation de l’entrée, lisible par machine
|journal_id| ID du périodique (revue, journal, etc.) ; les données associées se trouvent dans le dossier « Journal » du tableau DFKV_Master|
|volume_id| ID du volume ; les données associées se trouvent dans le dossier « Volume_ID » du tableau DFKV_Master|
|transcription| Description (textuelle) du contenu de l’entrée|
|citation| Citation originale extraite du contenu de l’entrée|
|rubric_id| ID de la rubrique ; les données associées se trouvent dans le dossier « rubrique » du tableau DFKV_Master|
|location_id| ID du lieu de publication ; les données associées se trouvent dans le dossier « lieu de publication » du tableau DFKV_Master|
|editor_id| ID de la maison d’édition ; les données associées se trouvent dans le dossier « maison d'edition » du tableau DFKV_Master|
|sujets| ID du sujet ; les données associées se trouvent dans le dossier « sujets » du tableau DFKV_Master|
|type de texte| ID du type de texte ; les données associées se trouvent dans le dossier « type de texte » du tableau DFKV_Master|
|impliqué| Personne impliquée dans le texte de l’entrée (sans définition fixe)|
|créateur_créatrice| Auteur du texte de l’entrée|
|traducteur_traductrice| Personne responsable de la traduction du texte de l’entrée|
|montré| Personne représentée sur les œuvres décrites dans l’entrée|

