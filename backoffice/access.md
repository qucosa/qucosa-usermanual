##### 

## [Login und Zugang zum Backoffice](#login-und-zugang-zum-backoffice)

Das Backoffice ist im neuen System in die Contentmanagementsoftware TYPO3 integriert.  
Dieses ist über folgenden Link:  
[https://web-redaktion.slub-dresden.de/typo3/](https://web-redaktion.slub-dresden.de/typo3/ "Qucosa- Administrationsbereich")

oder über die Qucosa-Webseite (Menüpunkt "Administration") zu erreichen:


#### Start Backoffice TYPO3

1. linke Menüleiste - Qucosa - Manager anklicken
* mittlere Menüleiste - gewünschten Mandantenbereich anklicken (Beispiel Qucosa - SLUB)
* mit der Dokumentenverwaltung kann begonnen werden, wenn im rechten Anzeigefeld die Meldung:

"Es wurde kein gültiger Mandantenordner ausgewählt"

![](/assets/no_mandant.png)

nicht mehr angezeigt wird und über den Schaltflächen "Dokumente" und "Suche" der Name des Mandanten sichtbar ist:

![](/assets/mandant_anzeige.png)

* Andernfalls noch einmal Schritt 2 wiederholen und nochmals den Mandant in der mittleren Menüleiste anklicken

* Um möglichst viel Platz im rechten Anzeigefeld zu haben, können die beiden Menuleisten durch Zusammenschieben verkleinert werden. Hierzu muss die Maus auf den Rand der jeweiligen Leiste bewegt werden, bis sich die Zeigerform in ein Pfeilesysmbol ändert.
Duch "Doppelklick" wird die mittlere Menüleiste eingeklappt.



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



