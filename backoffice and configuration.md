##### 

## [Login und Zugang zum Backoffice](#login-und-zugang-zum-backoffice)

Das Backoffice ist im neuen System in die Contentmanagementsoftware TYPO3 integriert.  
Dieses ist über folgenden Link:  
[https://web-redaktion.slub-dresden.de/typo3/](https://web-redaktion.slub-dresden.de/typo3/ "Qucosa- Administrationsbereich")

oder über die Qucosa-Webseite zu erreichen:

![](/assets/Qucosa_Administrationsbereich_Pfeil.png)

#### Start Backoffice TYPO3

* linke Menüleiste - Qucosa - Manager anklicken
* mittlere Menüleiste - gewünschten Mandantenbereich anklicken
* richtig angemeldet ist man, wenn im rechten Anzeigefeld die Meldung

  ![](/assets/Hinweis.png "\(Warnung\)") **Es wurde kein gültiger Mandantenordner ausgewählt! **

nicht mehr angezeigt wird.

* um möglichst viel Platz im rechten Anzeigefeld zu haben, kann man die beiden Menüleisten links zusammenschieben, die mittlere kann auch ausgeblendet werden

## [Die Bedeutung der Schaltflächen](#die-bedeutung-der-schaltflächen)

**Generell gilt:** Etwas heller eingefärbte Schaltflächen sind für den konkreten Anwendungsfall nicht relevant und können deshalb nicht bedient werden.

| **Symbol/Button** | **Wo?** | **Aktion** |  |
| :---: | :---: | :---: | :---: |
| Neu |  | Anzeige aller neu                 angemeldeten Dokumte |  |
| In Bearbeitung |  | Anzeige aller Dokumente,  welche sich gerade im       Arbeitsbereich befinden |  |
| ![](/assets/image2016-6-15 12_10_4.png) Previewanzeige |  | Öffnet die Vorschau der      Landing-Page |  |
| ![](/assets/image2016-6-15 12_11_33.png) Duplizieren des Dokumentes |  |  |  |
| ![](/assets/image2016-6-15 12_45_40.png)Aktivieren des Dokumentes |  | Einblenden eines bereits veröffentlichten Dokumentes | ein zuvor inaktiv gesetztes Dokument soll wieder in die Suche integriert werden |
| ![](/assets/image2016-6-15 14_22_36.png)inactive document |  | Ausblenden eines bereits    veröffentlichten Dokumentes | Das Dokument kann in der Suche nicht mehr gefunden werden, die Landing- Page kann nicht mehr aufgerufen werden. <br /> Das Dokument ist im Frontend nicht mehr sichtbar.  <br />Inaktiv gesetzte Dokumente können im Arbeitsbereich gelöscht werden.  <br />Dies bietet die Möglichkeit den Arbeitsbereich für bestimmte Dokumente zu leeren. (siehe "verwerfen") |
| ![](/assets/info_button.png) |  | Download der DataCite-XML Datei |  |
| ![](/assets/image2016-10-27 10_2_11.png) | Dokumentenliste, <br />Datensatz im Editiermodus | Entfernen eines Datensatzes aus dem lokalen Arbeitsbereich | **Vor der Veröffentlichung**: Der Datensatz wird vollständig entfernt. <br /> ![](/assets/Hinweis.png) **Kann nicht rückgängig gemacht werden!!!** <br /><br /> **Bereits veröffentlichte Dokumente:** Die Kopie eines Datensatzes, die zur Aktualisierung in den lokalen Arbeitsbereich geholt wurde, wird gelöscht. |
| ![](/assets/image2016-10-27 9_58_32.png)![](/assets/image2016-10-27 9_59_19.png) | Dokumentenliste | Veröffentlichen des Datensatzes | Metadaten und Datei\(en\) werden ins Repository übertragen. Präsentation über die Recherche erfolgtDokument wird nicht mehr im lokalen Arbeitsbereich gelistet |
| ![](/assets/image2016-11-23 8_13_36.png)![](/assets/image2016-11-23 8_15_25.png) | Dokumentenliste | Abschließen der Korrektur eines bereits veröffentlichten Datensatzes | Kopie des Datensatzes wurde im lokalen Arbeitsbereich bearbeitet-                         Korrekturen werden ins Repository übertragen.Dokument wird nicht mehr im lokalen Arbeitsbereich gelistet |
| ![](/assets/image2016-10-27 9_52_48.png)![](/assets/image2016-10-27 9_54_40.png) | Datensatz im Editiermodus | Markieren eines Datensatzes als "Im Repository Löschen" | Schaltfläche steht nur für Datensätze zur Verfügung, die bereits freigeschaltet wurden, sich im Repository befinden und für die eine Kopie zur Aktualisierung in den lokalen Arbeitsbereich geholt wurde |

## [Felder und Eingaberegeln](/backoffice and configuration.md)

| **Dokumentenarten** | **Seite** | **Felder** | **Beschreibung** |
| :--- | :--- | :--- | :--- |
|  | Dokument | Jahr der Erstveröffentlichung | Jahr der Erstveröffentlichung eines Artikels in einem Journal, einer Printausgabe u.ä.relevant für die Formalerschließungnicht Jahr der Veröffentlichung auf Qucosa |
|  | Dokument | URN Qucosa | die Qucosa URN wird automatisch mit der Veröffentlichung \(Freischlatung\) des Dokuments vergebenbei Bedarf kann sie vorab durch Bedienung der Schaltfläche rechts im Feld erzeugt werden |
|  | Dokument | Identifier  Checkbox "Invalid" |  |
|  | Dokument | Bandnummer Schriftenreihe / mehrbändiges Werk mit den Feldern Sortierschlüssel und Bandnummer | Bandzählung innerhalb einer Schriftenreihe oder eines mehrbändigen Werkesnumerischer Sortierschlüssel, um die Sortierung in der Liste der mit einer Überordnung in Qucosa verknüpften Bände zu bestimmenes ist auch möglich, nur eine Sortierzählung anzugeben, wenn die Bände keine Zählung haben |
|  | Inhalt | DDC | ![](/assets/Hinweis.png) neues Pflichtfeld, nach DINI-Anforderungen mindestens  nach [DDC-Sachgruppen der Deutschen Nationalbibliografie](http://www.dnb.de/SharedDocs/Downloads/DE/DNB/service/ddcSachgruppenDNB.pdf?__blob=publicationFile) zu erschließen \(2. Ebene, hundert Klassen\) |
|  | Personen | Namenszusätze | Feld noch nicht belegen |
|  |  |  |  |
|  | Quellenangaben | URN | in dieses Feld darf keine Qucosa-URN eingetragen werden |
|  | Quellenangaben | Quellenangaben - Quelle \(Display Name: Quelle\) | in dieses Feld darf nichts eingetragen werden; es dient lediglich der Migration der Altdaten |



