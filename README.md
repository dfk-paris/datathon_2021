# Données préparées pour le Datathon conjoint de l'IHA et du DFK Paris en novembre 2021

Here you will find the data that DFk Paris has prepared for the joint datathon with the IHA in November 2021.

The data will be presented one after the other 

1. the Critical Edition of the "Correspondence between Henri Fantin-Latour and Otto Scholderer, 1858-1902"
2. the research project "Deutsch-Französische Kunstvermittlung 1871–1940 und 1945–1960" 

All data are offered under the license [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 

---

## 1. Correspondence between Henri Fantin-Latour and Otto Scholderer, 1858-1902

Lien vers la publication électronique: https://quellen.perspectivia.net/fr/fantin-scholderer/start


### Overview

The data collection consists of 306 letters and four indices. The indices serve to index persons and places as well as the works of Fantin-Latour and Scholderer mentioned in the letters. Not all persons are explicitly mentioned in the letters, i.e. by name, but it was possible to identify them in the course of the scholarly work. Accordingly, comments by the editors can be found on these mentions in the edited letters. 

Other files contain the texts displayed in perspectivia.net on the introduction and the procedure of the scholarly edition, as well as the table of contents and other textual elements of the online presentation. 

### Indices
The four indices are available as individual files in .csv (comma separated values) format, and also summarised as sheets in an Excel table document. 

| table | the linkage between each other | content  |
|---|---|---|
|index\_of_letters | ID of the letters | letters with author, recipient, date, place of issue, works and persons mentioned |
|index\_of_works | ID of the letters | works by Fantin-Latour and Scholderer mentioned |
|index\_of_places | ID of the letters | places and sites as well as exhibitions mentioned |
|index\_of_persons | ID of the letters | persons mentioned |


### Index of works

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


### Index of persons

A total of 364 persons named in Fantin-Latour and Scholderer's correspondence were identified in the course of the letter edition. The index contains an ID, the name and a list of all letters in which the respective person appears. The field "Nom" can also contain an alias name in addition to the surname and first name.

| ID | Nom | Renvoi dans lettre no |
| --- | --- | --- |
| #17662 | Veronese, Paolo |  1858_03 |


#### Index of places

The index of places lists all 124 places mentioned in the letters. These are geographical places as well as exhibition sites and exhibitions. In each case, the geographical name is placed in front and separated from the other details by a comma. Exceptions are those places where the letters are issued. In addition to a field for the ID, the index contains a field for the sites ("Lieu mentionné") and another field in which the places of evidence, i.e. the letters, are entered.

| ID | Lieu mentionné | Renvoi dans lettre no |
| --- | --- | --- |
| #11133 | Dijon |  1858_04 |

#### Index of letters

The index of the 306 letters provides the synopsis of the persons, works and places mentioned together with the metadata of the letters (sender, addressee, place of issue and date). In the fields "Personnes mentionnées", "Lieux mentionnés", and "Œuvres mentionnées" several values may be entered, separated by a teaching position. The letters F and S in the field "Œuvres mentionnées" indicate Fantin-Latour or Scholderer and thus the author of the subsequently mentioned work. Words and values in square brackets are additions made in the course of scholarly editing.

| Lettre | Date | Lieu de création | Auteur | Destinataire | Personnes mentionnées | Lieux mentionnés | Œuvres mentionnées |
| --- | --- | --- | --- | --- | --- | --- | --- | 
|1858_03 | 1858-07-05 | Francfort [sur le Main] | Scholderer, Otto | 	Fantin-Latour, Henri | Mozart, Wolfgang Amadeus Rembrandt Legros, Alphonse ...  | Paris Francfort-sur-le-Main | S Selbstbildnis des 24jährigen Künstlers (autoportrait de l'artiste âgé de 24 ans) S Kopie nach Ferdinand Bol, Bildnis eines jungen Herren (copie d'après Ferdinand Bol, portrait d'un jeune homme) ...|

### Scientifically edited letters

The 306 edited letters are each stored as a single HTML file.  In addition to the transcription, which also included an adjustment of the orthography, of the respective letter, they include the scholarly comments. All files are structured and labelled in the same way. 

1. ID of the letter (\<div data-meta_source_id="index_of_letters#1880_19" data-template_id="text_with_meta.tpl">).
2. link to preceding and following letter in the edition (\<nav class="non-source prev_next">\<a class="refprev" href="1880_18" rel="prev">1880_18\</a> \<a class="refnext" href="1881_01" rel="next">1881_01\</a>\</nav>).
3. then following as numbered paragraphs (\<p class="flush" id="1">).

* Place of issue, if necessary enclosed in square brackets if the place was identified in the course of the critical edition.
  
* Date of issue, if necessary enclosed in square brackets, the supplemented indication of the century. 
  
* Salutation *"Mon cher Fantin.... "* 
* Text of the letter. 

Inserted in the paragraphs are the scholarly annotations (\<span class="note">\<a class="note" data-sign="2" href="#n2">\</a>\<small class="non-source note" data-sign="2 " id="n2">Scholderer, Preparing for a Fancy Ball, B.188.\</small>\</span> citation of a work by Scholderer with title).
