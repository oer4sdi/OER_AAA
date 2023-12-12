# Allgemeines

## Einführung in das AAA Datenmodell

**Worum geht´s?**

Wie viel Waldfläche befindet sich in einem Landkreis? Wie gut ist eine Gemeinde mit Kindertagesstätten versorgt? Wo befinden sich eventuell Lücken in der medizinischen Grundversorgung? All das sind Fragen, für deren Beantwortung räumliche Daten benötigt werden. Für Deutschland liegen solche Geodaten flächendeckend in Form von Geobasisdaten vor. Im AFIS-ALKIS-ATKIS Datenmodell werden diese Daten geordnet und Nutzern zur Verfügung gestellt.

In dieser kurzen videobasierten Lerneinheit wird dieses Datenmodell vorgestellt und die Möglichkeit gegeben erste Erfahrungen im Umgang mit den Daten zu sammeln.

**Folgende Themen werden behandelt:**

- Wofür benötigen wir Geobasisdaten?
- Anwendungsbereiche und Datentypen im AAA-Datenmodell?
- Struktur der Daten im AAA-Modell.
- Zugriff auf die Daten über Geodatenbanken und Webservices.
- Beantwortung räumlicher Fragestellungen mit ATKIS Daten.
  
**Zeitaufwand:**
ca. 35 Minuten.

### Voraussetzungen:

**Inhaltlich:**

Die Einheit kann ohne Vorkenntnisse durchgeführt werden. Punktuell sind erste Erfahrungen im Umgang mit GIS-Software generell oder QGIS im Speziellen von Vorteil.

**Technisch:**

Die praktischen Übungen erfordern eine aktuelle Version der GIS-Software QGIS:

**Download:**
https://www.qgis.org/de/site/forusers/download.html

# 1. Geobasisdaten im AAA Datenmodell

### Was ist das AFIS, ALKIS, ATKIS Datenmodell? < Zum Inhalt!!
Wir starten mit einem kurzen Explainer Video zum AAA-Schema. Das Video gibt einen Überblick über die Charakteristika der Daten, ihre Struktur sowie die Zugänglichkeit.

Mit einem kurzen Quiz am Ende können sie überprüfen, ob sie die Kernpunkte des Abschnittes kennen. 

![image](https://github.com/oer4sdi/OER_AAA/assets/152982068/40824439-99a5-4536-8229-ac1bad177e07)
https://youtu.be/LWWAOAs3ALQ

**Inhalte:**

Wir starten mit einem kurzen Video zum AAA-Schema. Das Video gibt einen Überblick über die Charakteristika der Daten, ihre Struktur sowie den Zugang zu den Daten.


**Themen:**

- Geobasisdaten
- Daten in AFIS-ALKIS-AKTIS Datensätze.
- Struktur von AFIS-ALKIS-ATKIS Metadaten.
- Zugangsmöglichkeiten zu AFIS-ALKIS-ATKIS Datensätzen.


## Selbsttest: Das AAA Datenmodell

Um sicherzustellen, dass Sie gut vorbereitet in den nächsten Abschnitt gehen können, ist hier eine Gelegenheit zu überprüfen, ob Sie die Kernpunkte dieser Lerneinheit verstanden haben.

### Frage 1

**Welche Informationssysteme umfasst das AAA-Schema?**

(x) a. Amtliche Kartographische Informationssystem    
###### [Das Amtliche Kartographische Informationssystem (AKTIS) spiegelt die wesentlichen topographischen Eigenschaften der Landschaften in digitalen Modellen (Landwirtschaft, Siedlung, Wald, ...) wider.]

( ) b. Das Automatisierte Liegenschaftsbuch

(x) c. Das Amtliche Festpunktinformationssystem
###### [Das Amtliche Festpunktinformationssystem (AFIS) umfasst Lage-, Höhen- und Schwere-Festpunkte sowie GPS-Referenzstationen.]

( ) d. Die Automatisierte Liegenschaftskarte

(x) e. Das Amtliche Liegenschaftskataster
###### [Das Amtliche Liegenschaftskataster (ALKIS) umfasst Flurgrenzen und Gebäude.]


### Frage 2

**Welche Informationen können dem AAA-Basisschema entnommen werden?**

(x) a. Objekt ID (z. B. "27068")

(x) b. Objektart (z. B. "41008")

( ) c. Funktion (z. B. "Park")

( ) d. Name (z. B. "Ohrbergpark")

# 2. Zugang zu AAA Datensätzen

### Zugang zu AAA Datensätzen < Zum Inhalt!!

**Aufgabe:**

Schauen sie das Video an und vollziehen Sie die Arbeitsschritte nach! Sie benötigen eine aktuelle Version der Software QGIS.

**Download:**
https://www.qgis.org/de/site/forusers/download.html

**Im Video genutzte Datensätze:**
- [Geodatabase](https://single-datasets.opengeodata.lgln.niedersachsen.de/bdlm/20230330_nba_bkg_bdlm_ni_ohne_HB_V5_1.gdb.zip)  (* *Link dazu führt zu sofortigem Download!* *) Dateigröße: ~400mb
- WFS Layer von [Open.NRW](https://open.nrw/dataset/407373a2-422c-469c-a7e9-06a62b4d7d9a): https://www.wfs.nrw.de/geobasis/wfs_nw_alkis_aaa-modell-basiert?REQUEST=GetCapabilities&SERVICE=WFS

**Genutztes Plugin:**
WFS 2.0 Client (über die [Website](https://plugins.qgis.org/plugins/wfsclient/) downloadbar oder einfacher direkt über QGIS installierbar).

![image](https://github.com/oer4sdi/OER_AAA/assets/152982068/6776f1ff-3447-444f-ba4b-325b78e29278)
https://youtu.be/CTVSlmioViM

**Inhalte:**

Im zweiten Abschnitt werden zwei Zugangsmöglichkeiten zu den Daten demonstriert und aufgezeigt, wie sich die theoretischen Grundlagen aus dem ersten Abschnitt in den Daten praktisch widerspiegeln.


**Themen:**

- Aufrufen von AAA Daten in QGIS über Geopackages und WFS.
- Analyse der Struktur von AAA Daten.
- Arbeit mit dem AAA-Objektkartenkatalog.


## Selbsttest: Zugang zu AAA Datensätzen

Nutzen Sie den kurzen Selbsttest um sicherzustellen, dass Sie gut gerüstet sind für den nächsten Abschnitt und ob Sie die wesentlichen Punkte dieser Lerneinheit verstanden haben.

### Frage 1

**Wie kann auf AAA Datensätze zugegriffen werden?**

( ) a. Lizensiert, kostenpflichtig über das Internet

( ) b. Kostenfrei und per Anfrage an das Landesamt

(x) c. Kostenfrei, standardisiert und über das Internet

###### [Der Zugang zu den AAA Datensätzen ist zwar standardisiert, jedoch nicht homogen über eine Website oder einen Dienst abrufbar. Hierzu müssen (leider) die einzelnen Webauftritte der Länder recherchiert werden. Wir haben allerdings eine Dokumentation zu den Zugängen und dessen Webadressen hier im Moodle bereitgestellt. Zusätzlich ist leider bei einigen Anbietern eine Vorab-Registrierung notwendig.]

### Frage 2

**In welcher Form können AAA-Daten im GIS eingeladen werden?**

(x) a. Geopackage (gpkg)

( ) b. Web Processing Service (WPS)

(x) c. Web Map Service (WMS)

(x) d. Web Feature Service (WFS)

( ) e. Web Coverage Service (WCS)

( ) f. Web Map Tile Service (WMTS)


### Frage 3

**Auf welcher Ebene werden AAA-Datensätze angeboten?**

(x) a. Auf Landesebene mit Merkmalsart-Auswahlmaske in GIS

( ) b. Auf Bundesebene mit Landes-Auswahlmaske in GIS

( ) c. Auf Kommunenebene mit Auswahlmaske im GIS für jedes Bundesland



#### [Link-Sammlung Geodatenzugänge der Bundesländer](https://moodle.ruhr-uni-bochum.de/mod/resource/view.php?id=2495157)

In diesem Dokument finden Sie eine Auflistung der Zugänge zu freien Geodaten im Rahmen des AFIS ALKIS ATKIS Datenmodells. Teilweise sind Zugänge nicht intuitiv auffindbar, teilweise funktionieren sie nicht. Das Dokument soll Ihnen dabei helfen, schnell an benötigte Geodaten heran zu kommen.

# 3. Arbeiten mit AKTIS Daten

### Arbeiten mit AKTIS Daten < Zum Inhalt!!

**Aufgabe:**

Schauen Sie das Video an und vollziehen Sie die Arbeitsschritte nach! Sie benötigen eine aktuelle Version der Software QGIS.

**Download:**
https://www.qgis.org/de/site/forusers/download.html

**Im Video genutzte Datensätze:**
- WFS Layer: https://sgx.geodatenzentrum.de/wfs_vg1000
- Basis DLM NRW: https://www.opengeodata.nrw.de/produkte/geobasis/lm/akt/basis-dlm/

![image](https://github.com/oer4sdi/OER_AAA/assets/152982068/1946bc29-25a4-4a2a-826d-53abc112a3bf)
https://youtu.be/JJHQR3tLLI4

**Inhalte:**

Im dritten Teil werden zwei praxisnahe Beispiele bearbeitet, um einen Einblick in die Möglichkeiten zu geben, die die Arbeit mit dem AFIS-ALKIS-ATKIS Datenkatalog bieten. Dabei kommen einfache Methoden der Geodatenbearbeitung mit QGIS zum Einsatz.


**Themen:**

- Aufrufen von AAA Daten in QGIS über Geopackages und WFS.
- Analyse der Struktur von AAA Daten.
- Arbeit mit dem AAA-Objektkartenkatalog.


## Selbsttest: Arbeiten mit ATKIS Daten


### Frage 1

**In welcher Form ist eine Dokumentation zu den AAA-Daten einsehbar?**

( ) a. In Form einer beigefügten Textdatei

( ) b. In Form von einzelnen Websiten der jeweiligen Quelle des Datensatzes

( ) c. In Form einer Attributtabelle im GIS

(x) d. In Form eines Objektkartenkatalogs


### Frage 2

**Einzelne Objekte aus dem AAA-Datenschema können im GIS eingeladen werden als...**

(x) a. Polygone, Linestrings & Points

(x) b. Volumendaten

( ) c. .jpeg-Files

(x) d. Shapefiles

(x) e. Features

( ) f. MultiPatch

( ) g. Functions

###### [Im GIS können AAA-Geoobjekte als Features in Form von Shapefiles (z. B. als Polygone) eingeladen werden. Daher sind sowohl Features, Shapefiles als auch Polygone, Linestrings und Points richtig.]


# Evaluation

Bitte folgen Sie diesem Link zu einer kurzen Evaluation des Kurses:

[Link zur Evaluation!](https://docs.google.com/forms/d/1J5HS3y88ufsSY3Kut-ZolDeETW1-xsqgzXomKAvi8sY/edit)
