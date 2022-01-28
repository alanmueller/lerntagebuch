---
title: "Dritter Tag - Funktion und Aufbau von Bibliothekssystemen 2/2"
date: 2021-10-08
---

In diesem Artikel wird auf die dritte Sitzung des Moduls Bibliothek und Archivinformatik eingegangen. Thema dabei waren der zweite Teil von Funktion und Aufbau von Bibliothekssystemen. 

Zunächst wurden wieder die Lerntagebücher besprochen bzw. die Erkenntnisse daraus. Dies diente als kurzer Wrap-up der letzten Lerneinheit. 

Es wurde auch auf den komplexen Standard MARC21 aus der letzten Sitzung eingegangen. Durch eine Übung mit Koha sollte dies verständlicher werden. 


**Koha-Übung**

Der Start mit Koha war bereits in der letzten Sitzung. Hier gab es Probleme mit der Konfiguration bei manchen Studenten. Unsere Dozenten haben sich den Stunden mit den Problemen angenommen und ich konnte die Zeit nutzen, die neue Übung bereits anzusehen, die bereits erfassten Lerntagebücher durchzulesen und mich kurz zu organisieren.

Ich konnte die erste Übung ohne Probleme abschliessen, wobei es mit der Kopie mit dem Passwort manchmal zu Problemen kam. Nun mit der zweiten Übung in Koha «TEIL 2: DAS BIBLIOGRAFISCHE FRAMEWORK – WIE MAN KOHA INSTALLIERT UND FÜR SCHULEN EINRICHTET» ging es um die Konfiguration des Frameworks. Das Tutorial geht nochmals auf Marc 21, ein welches ja im Teil 1 ausgewählt wurde. 

Im Abschnitt MARC-Framework fehlte mir das Framework FA – Schnellaufnahme. 

In der Anwendung mit Koha wurden noch das Erfassen von Medien und Benutzern oder darauf eingegangen, wie Medien ausgeliehen und zurückgenommen werden. 
Anschliessend folgte noch ein Datenimport über eine SRU-Schnittstelle zum gemeinsamem Bibliotheksverbund (GBV). Dabei werden über diese SRU-Schnittstelle ähnlich wie bei der mir bekannten REST-Schnittstelle Daten über eine URL gesucht und übernommen. Parameter werden in der URL mitgegeben. Das entsprechende Protokoll basiert auf XML. 
Die Anwendungsfälle in Bibliothekssystem sind für mich persönlich fremdes Feld und deshalb war mein Interessensfokus doch stärker auf den technischen Aspekt der Abfragen usw. gelegt. 

**Schnittstellen und OAI-PMH**
Nun folgte die Aktivierung der OAI-PMH-Schnittstelle in Koha. Diese diente dazu Datenbestände aktuell zu halten oder für die Aggregation von Verbundsrecherchen oder für den Abruf von Daten zur Weiterverarbeitung.

** Marktüberblick Bibliothekssysteme**
Im letzten Abschnitt des heutigen Kurses gab es eine Einsicht in die Marktsituation von Bibliothekssystemen. Es gibt von Marshall Breeding ein jährlich veröffentlichter Report dazu, wodurch man eine Übersicht erhält. Für mich persönlich ist das alles neu, aber der Excel-Report zeigte die Menge auf und bot eine erste Übersicht. 

**Ausblick auf die nächste Sitzung: **

Hier folgte nun der Auftrag der Installation von Archive Spaces

Dazu muss zunächst Java 8 auf unserer virtuellen Maschine installiert werden. Diese Installationen funktionieren in der Regel problemlos, und sind mitunter mit weniger Aufwand als über eine Benutzeroberfläche verbunden. 

Im Gegensatz zu Koha muss, muss ArchivesSpace in der Standardinstallation manuell gestartet werden. Es läuft auch nur so lange wie der Prozess im Terminal läuft. Archive Space ist eine Webanwendung welches über den Terminal (als Server) läuft. Ich kenne diese Art von Umgebung bereits von Lokalen Servern wie XAMPP

Hier war noch spannend, dass unter http://localhost:8089/ die REST API erreichbar ist, und unter http://localhost:8090/ die Suchmaschine Apache Solr.

![image](https://user-images.githubusercontent.com/71718724/150852383-18fe4a11-5588-483f-a748-efff2517d160.png)





