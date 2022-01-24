---
title: "Siebter Tag - Metadaten modellieren und Schnittstellen nutzen 2/2"
date: 2021-12-03
---

**Metadaten transformieren**

In diesem Artikel wird auf die siebte Sitzung des Moduls Bibliothek und Archivinformatik eingegangen. Thema dabei waren der zweite Teil von Metadaten modellieren und Schnittstellen nutzen. Schwerpunkt war dabei die die Transformation von Metadaten mit OpenRefine. Der Inhalt knüpft damit direkt an die vorherige Sitzung an. 

** OpenRefine – Umwandlung von Metadaten**

Die Open-Source-Software OpenRefine wurde von Google entwickelt und ermöglicht die Umwandlung oder Bereinigung von Metadaten. Es geht hier nicht primär um Bibliotheken sondern wird auch in anderen Bereichen eingesetzt:
- Forschung
- Datenanalyse
- Aufbau von semantischem Web
- 
Datenformate die bearbeite werden können sind z.B. CSV, JSON oder auch XML. Mittels SQL-Abfragen können Daten von Datenbanken abgerufen werden. 
Bevor die Installation auf der virtuellen Maschine vorgenommen werden konnte, dauerte es bei mir noch etwas da die Verbindung mit Pulse Secure zu der Zeit nicht ging. Ich konnte das Problem anschliessend beheben und die virtuelle Maschine starten. 
Die Installation funktionierte dann anschliessend problemlos. Via Terminal wurde die Installation vorgenommen und anschliessend installiert. Über Localhost konnte es anschliessend aufgerufen werden. 


**Bild**

In der kurzen interaktiven Übung wurden Beispieldaten erfasst. Der Beispieldatensatz in Form einer CSV-Datei haben wir von den Dozenten zur Verfügung gestellt bekommen. Anschliessend befassten wird uns mit den Funktionen des Tools. Daten konnten vereinheitlicht werden, Einträge gefiltert. Bei den Beispielen funktioniert es ähnlich wie Excel jedoch ist OpenRefine effizienter. Bei grossen Datenmengen kann dies entscheidend sein. Es wurde auch in OpenRefine die Möglichkeit gezeigt, dass die eingelesenen Metadaten mit Daten aus Wikidata ergänz werden können. 
**Transformation von Metadaten CSV - MARCXML**
Wie von XSLT Crosswalt bekannt, konvertieren wir in dieser Übung die Metadaten der Beispieldaten im CSV-Format in MARCXML. Hier wurden aber nicht das Datenformat in das andere konvertiert, sondern mittels der Sprache General Refine Expression Language (GREL) von einem Metadatenstandard in den anderen. Der Output wurde aufgrund möglicher Fehler mit dem vorinstallierten Ubuntu-Programm «xmllint» geprüft. GREL wirkt dabei etwas kompliziert zu beginn. 

Fazit zum Tool


Quelle: https://www.wikidata.org/wiki/Wikidata:Main_Page