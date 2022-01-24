---
title: "Sechster Tag - Metadaten modellieren und Schnittstellen nutzen 1/2"
date: 2021-11-19

In diesem Artikel wird auf die sechste Sitzung des Moduls Bibliothek und Archivinformatik eingegangen. Thema dabei waren dabei die Besprechung der vergangenen Übung (Post ex_02_OAI-PMH-Schnittstellen), ein kurzer Punkt zum aktuellen Stand der Vorlesung und das Thema Metadaten über OAI-PMH harvesten mit VuFindHarvest. 

**OAI-PMH-Übung**

Auch andere Studenten hatten scheinbar in dieser Übung Ihre Schwierigkeiten. Ich konnte dies Übung nicht erfolgreich durchführen aber mit dem besprochenen Nachtrag konnte ich dies nun absolvieren. Dabei war es wichtig, dass damit die Daten aus der Übung zu OAI-PMH weiterverwenden zu können das Dublin Core XML-File angepasst werden muss. Beim Generieren scheint einen die Deklarationen der Namesspaces verloren gegangen zu sein, was zu einem Error in von MarcEdit führe. Durch einen manuellen Eingriff mittels Editors konnte dies aber durch Ersetzen der ersten Zeile korrigiert werden.


**Zwischenstand**

Auf den Zwischenstand einzugehen auch anhand der Grafik half mir persönlich nochmals sehr mich zu orientieren und auch die Zusammenhänge zu erkennen. Es wurde bereits die Demo DSpace gestet und mit der Übung die Daten über dia OAI-PM-Schnittstelle abgreufen. Dasselbe machen wir nun mit unseren lokalen Installationen Koha und Archivespace. Die Daten werden anschliessend mit marcEdit bearbeitet. Open Refine wird anschliessend ebenfalls Thema sein. 

 


**Austauschprotokolle für Metadaten**

Die drei am weitest verbreiteten Protokolle sind Dabei Z39.50 (Library of Congress) als sehr altes Protokoll aber noch micht Einsatz, SRCU – Search/REtriebe via URL (Library of Congress) speziell im Bereich Live-Abfragen und OAI-PMH- Open Archives Initiative Protocol for Metadata Harvesting (Open Archives Initiative) welches auf grössere Datenabzüge und regelmässige Aktualisierungen abzielt. Letzteres kennen wir bereits aus den vergangenen Stunden. OAI-PMH und auch SRU können die die Anfragen direkt der URL mitgegeben werden und als Antwort erhält man die angeforderten Daten im XML-Format. 


**VuFind Harves**

In diesem Abschnitt geht es um die Installation und anschliessende Übung mit VuFindHarvest. Beim Harvesten handelt es sich hier in diesem Kontext um das Sammeln oder Ernten von Metadaten. Dabei war das Vorgehen zunächst das Sicherstellen, dass die OAI-PMH-Ebdpoint für Koha und ArchiveSpace in meiner virtuellen Umgebung verfügbar sind. Anschliessend mit den Anwendungen die Daten abrufen und als XML auf der Festplatte speichern. 

Ich hatte in dieser Phase immer wieder Probleme mit der Verbindung zu Pulse Secure damit ich die Virtuelle Maschine starten konnte. Die Installation wurde deshalb zu einem späteren Zeitpunkt durchgeführt.


**XLST-Crosswalk**
Der Name kommt daraus, dass hier, Daten von einem Metadatenstand in einen anderen kovertiert werden aber nicht die Konvertierung des Datenformats selber. Dies kann durch Mapping möglichst verlustfrei durchgeführt werden. Das Mapping ist dabei eine Art Regelwerk. Dies konnten wir in der Praxis direkt anwenden. 
Wir haben dafür mit der Software MarcEdit21 Daten aus dem Ursprungsformaten EAD (in ArchivesSpace verwendet) und OAIDC (in DSpace) in MARC21XML konvertiert.


**Nachtrag:**  Durch eine komplette Neuinstallation von PulseSecure nach Anleitung im Intranet der Fachochschule konnte ich mich mit dem VPN wieder verbinden und die Virtuelle Maschine starten. Nachdem die Virtuelle Maschine wieder funktionierte konnte ich die Installation von VuFindHarvest ausführen.

![image](https://user-images.githubusercontent.com/71718724/150863615-2f8befc2-fb0d-4557-a442-0388a5d32bce.png)






