---
title: "Achter Tag - Suchmaschinen und Discovery-Systeme"
date: 2021-12-17
---

In diesem Artikel wird auf die achte Sitzung des Moduls Bibliothek und Archivinformatik eingegangen. Ich konnte an diese Sitzung nicht Live teilnehmen so habe ich zu einem späteren Zeitpunkt bereits über die Weihnachtszeit die Aufzeichnung angeschaut und den achten Kurs durchgeführt. Dies ist damit bereits die letzte Vorlesung in 2021 und die Verletze dieses Moduls. Mein Ziel war es in dieser Einheit mein Wissen zu Suchmaschinen vertiefen und neues zu lernen. In meinen Unternehmen welches ERP Software entwickelt können unsere Kunden bereites mittels der Suchtechnologie SOLR Ihre gewünschten Datensätze finden. Hierbei haben wir manchmal Probleme, bei denen ich mit dem DevOps-Teams zusammenschliessen muss und eine Lösung für den Kunden suchen muss. 

Der Start des Kurses war wieder administrativ und es wurden Rückmeldungen zu der Lerntagebüchern gegeben. Danach folgte der Start mit JSON:

**JSON**
Hier wurde nun auf Schnittstellen, die auf JSON aufbauen eingegangen. Bei einer solchen API (application programming interface oder auf Deutsch Programmierschnittstelle) werden die Daten von der Schnittstelle im JSON-Format mitgegeben bzw. geliefert. Das Format ist dabei textbasiert das ähnlich wie eine JavaScript Objekt aufgebaut ist. Ich persönlich kenne JASON stark aus dem Webumfeld und hab es bereits in vorherigen Kursen erlernt. Das Beispiel mit der Autovervollständigung zeigte dabei die Einsatzmöglichkeiten von JSON. Hier werden in z.B. Webformularen wie «Wohnort» Daten per AJAX über die JSON API geladen. 

**Suchmaschinen und Discovery Systeme**
Nun das Hauptthema des Kurses. Der Begriff des Discovery Systems waren dabei noch neu für mich. Schnell wurde klar warum. Bei Discovery Systemen handelt es sich um Suchmaschinen im Bibliothekarischem Umfeld. Technologisch ist es gleich wie bei den anderen Suchmaschinen. Mit der Open-Source-Software VuFind haben wir ein bekanntes Discovery System, das von internationalen Bibliotheken und Universitäten benutzt wird. Damit lässt sich einfach ein Bibliothekskatalog erstellen mit einer starken Individualisierbarkeit. Wie im Intro angesprochen ist SOLR eine Suchmaschinentechnologie oder ein Suchserver, der Daten ausfindig macht. SOLR ist eine weit verbeitete Open-Source-Software, mit grossem Funktionsumfang. So biete sie unter anderem eine Suchoberfläche an. VuFind basiert dabei auf SOLR. Dadurch wurde bei der Installation von VuFind, SOLR gleich mitinstalliert. 

**Übung 1**

Hierbei sollten in der Suchoberfläche von Solr und VuFind eine Suche durchgeführt und verglichen werden. Die Übung wurde als Gruppenarbeit durchgeführt. Ich führte den Kurs zu einem späteren Zeitpunkt durch und machte die Übung deshalb allein.  Da VuFind auf derselben Technologie basiert warten die Resultate dieselben. Die Darstellung bzw. Aufbereitung waren dabei unterschiedlich. Bei SOLR werden die gesamten Resultate in JSON-Format ausgegeben. Bei VuFind in der OPAC-Ansicht und sind bereits gefiltert. Die Ergebnisse von VuFind waren dabei deutlich einfacher lesbar. 

**Übung 2**

In dieser Übung zur Datenintegration werden die generierten Daten in MARCXML in Vufind importiert damit ein eigener Katalog erstellt werden kann. Die Daten wurden von den Dozenten bereitgestellt und kommen dabei aus Koha, doaj, ArchiveSpace und DSpace.
Ich habe durch den Chat und meine Kommilitonen bereits erfahren, dass die Files von ArchiveSpace und Space nicht eingelesen werden können. Hier fehlt gemäss Terminal eine ID. Ein Kollege hat mir mitgeteilt, dass die ID von VuFind über das controlfied mit dem tag=001 importiert wird. 

die ID wird von VuFind das Feld controllfield mit dem Tag 001 importiert. Dieses war bei den fehlerhaften Datensätzen tatsächlich nicht vorhanden. Als Lösung könnte beispielsweise das XML manuell mit einer ID ergänzt werden. Schlussendlich konnten dann aber doch elf Datensätze erfolgreich importiert werden, welche über eine leere Suchanfragen abgerufen wurden.

Mit dieser Übung wurde nun der letzte Schritt unseres bekanntes Schaubilds aufgezeigt:

![upload_6f65912f937ad0643db6dd982043e148](https://user-images.githubusercontent.com/71718724/148580506-00e2ee7b-6d14-4fc1-99ca-7479cd680118.png)
Darstellung Kursinhalte [^1].

[^1]: Lohmeier, Meyer (2021). Skript BAIN, 1. Technische Grundlagen. https://bain.felixlohmeier.de/#/01_technische-grundlagen, abgerufen am 21.09.2021.



