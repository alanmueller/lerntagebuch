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

Datenformate die bearbeite werden können sind z.B. CSV, JSON oder auch XML. Mittels SQL-Abfragen können Daten von Datenbanken abgerufen werden[^1]. 

Die Installation funktionierte problemlos. Via Terminal wurde die Installation durchgeführt. Über Localhost konnte es anschliessend aufgerufen werden. 

![image](https://user-images.githubusercontent.com/71718724/150866666-ccf9007e-906b-495a-bdef-a8feea88950d.png)

In der kurzen interaktiven Übung wurden Beispieldaten erfasst. Der Beispieldatensatz in Form einer CSV-Datei haben wir von den Dozenten zur Verfügung gestellt bekommen. Anschliessend befassten wird uns mit den Funktionen des Tools. Daten konnten vereinheitlicht werden, Einträge gefiltert. Bei den Beispielen funktioniert es ähnlich wie Excel jedoch ist OpenRefine effizienter. Bei grossen Datenmengen kann dies entscheidend sein. Es wurde auch in OpenRefine die Möglichkeit gezeigt, dass die eingelesenen Metadaten mit Daten aus Wikidata ergänz werden können. 


**Transformation von Metadaten CSV - MARCXML**
Wie von XSLT Crosswalt bekannt, konvertieren wir in dieser Übung die Metadaten der Beispieldaten im CSV-Format in MARCXML. Hier wurden aber nicht das Datenformat in das andere konvertiert, sondern mittels der Sprache General Refine Expression Language (GREL) von einem Metadatenstandard in den anderen. Der Output wurde aufgrund möglicher Fehler mit dem vorinstallierten Ubuntu-Programm «xmllint» geprüft. In unserem ERP-System meines Unternehmens (Tocco AG) spielt der CSV-Import eine wesentliche Rolle. Ein Import von z.B Personendaten im CRM ist für Kunden unerlässlich. Ich komme deshlab sehr oft mi diesem Themengebiet in berührung. Mit OpenRefine wäre hier eine Datenbereinung der Kunden, falls nötig denkbar. 


<img width="660" alt="Bildschirmfoto_Tocco" src="https://user-images.githubusercontent.com/71718724/150869727-57f86557-58ea-4e5e-b34f-fc070d82e6c9.png">
CSV-Importer unter dem ERP System Tocco





[^1]: https://www.wikidata.org/wiki/Wikidata:Main_Page
