---
title: "Übung OAI-PMH Schnittstellen in DSpace"
date: 2021-26-11
---

In dieser Übung zu DSpace wurden zunächst die Metadaten des Beispieldokuments lokal kopiert und in einem Texteditor der virtuellen Maschine abgespeichert. 

Ich hatte mit der Konfiguration der DSpace Demo Anfang noch Probleme, da die Daten Samstagsnacht gelöscht werden, und ich die Übung zu einem späteren Zeitpunkt durchführte. Die Lösung dafür kam von einem Mitstudenten, der mir riet eine Community und Collection zu erstellen. 

Schritt für Schritt der der Anleitung nach habe ich die Metadaten abgerufen und in einem Textfile abgespeichert. 

Die Daten im XML-File schienen dabei nach einem kurzen Blick alle in Ordnung zu sein. Es sind alle Informationen enthalten. Über die OAI-Schnittstelle können die Daten des XML-Dokument nun abgerufen werden und ausgetauscht bzw. in andere Repositorien überführt. Die funktioniert so, dass DSpace strukturierte Metadaten zur Verfügung stellt, welche per Request (OAI-PMH Service-Requests) abgefragt werden können. Das Ganze passiert, wie bei den meisten Schnittstellen über das Protokoll HTTP.
 
