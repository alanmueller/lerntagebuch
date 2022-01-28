---
title: "Neunter und letzter Tag – Linked Data"
date: 2022-01-14
---

In diesem Artikel wird auf die neunte und letzte Sitzung des Moduls Bibliothek und Archivinformatik eingegangen. Zunächst wurden die Lerntagebücher und deren Fortschritte besprochen. Anschliessend folgte eine thematische Wiederholung zu VuFind und SOLR. 
Haupthemen dieses Kurses waren durch konkrete Projekte der Dozenten die Praxis hinter dem erlernten zu erfahren. Noch vor diesem Kurs hatte ich Probleme die Themen in der Praxis zuzuordnen da ich thematisch im meinem Arbeitsumfeld entfernt bin bzw. auch keine praktischen Erfahrungen mit Bibliotheken habe. Als thematischer Abschluss folgte noch Linked Data. Bevor es losging mit den Praxisbeispielen haben wurden noch die Kurs-Evaluationen besprochen und es wurde auf Kritik eingegangen. 

**Beispiel aus der Praxis**

Hierbei wurden zwei Projekte aus dem Arbeitsumfeld der Dozenten herangezogen. Dies half mir persönlich stark die vermittelten Inhalte in einem realen Umfeld zu sehen und der daraus generierte Nutzen. Die folgende Grafik, bezüglich Datenprozessierung wurde dabei aufgezeigt. Das Projekt lautete dabei «Entwicklung eines neuen Online-Katalogs für das Deutsche Literaturarchiv Marbach».

![image](https://user-images.githubusercontent.com/71718724/151584105-58f3651f-eb8c-4143-b276-d33d9831b247.png)
Beispiel aus der Praxis.

In dieser Darstellung wurden Daten aus dem Ursprungssystem Kallías gesammelt. Im Gegensatz zu dem was wir kennen (OAI-PMH-Schnittstelle) wurden die Daten im txt Format zur Verfügung gestellt. Per Python-Bibliothek Pandas, werden die Daten aufbereitet und danach im CSV-Format ausgegeben. Anschliessend folgte über OpenRefine die Weiterverarbeitung. OpenRefine stellt die Daten in einem einheitlichen Metadatenstandard in verschiedenen Dateiformaten bereit. Danach können Sie entweder über in Solr eingespielt und mit TYPO-3 gesucht werden oder für einen OAI-PMH-Schnittstelle verwendet werden. Diese Veranschaulichung half mir sehr für mein persönliches Big Picture zu diesem 

**Linked Data**

Nach dem Blick auf das Beispiel aus der Praxis folgte der Theorieblock zu Linked Data. Dabei wurden die Datenmodelle für Metadaten BIBFRAME und Records in Contexts präsentiert. Bibframe ist ein Modell für bibliographische Daten und Nachfolger von MARC21. Nachfolger deshalb, weil MARC21 zunehmend nicht mehr den wachsenden Anforderungen gerecht werden kann. BIBFRAME benutzt Technologien aus Linked-Daten und Semantic Web. Durch BIBFRAME soll das Anlegen, Speichern, Transportieren und Bereitstellen von Daten optimiert werden [^1].Es werden Events und deren Eigenschaften beschrieben, was der grosse Unterschied zu MARC21 ist. Es basiert auf dem Linked-Data-Prinzip wodurch Entitäten eindeutig identifiziert werden. Dadurch müssen Daten nicht einzeln bearbeite oder gepflegt werden, sondern dies kann durch die Verknüpfungen passieren. Bei Records on Context (RiC) handelt es sich um eine Technologie, welche für Archive und deren Aufgaben konzipiert wurde. Gleich wie BIBFRAME basiert es, nicht überraschend, auf Linked-Data und bedient sich der gleichen Vorteile wie der angesprochenen Verknüpfung von Entitäten. 

Nach diesem Theoretischem Abschluss um das ganze abzurunden wurde der heutige Kurs und das Modul beendet. Ein persönliches Wrap-Up findet im letzten Blogpost statt.


 [^1]: oA. 2016. Overview of the BIBFRAME 2.0 Model. https://www.loc.gov/bibframe/docs/bibframe2-model.html abgerufen am 15.01.2022.
