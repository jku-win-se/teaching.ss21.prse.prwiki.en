
# Project Management with Redmine

Redmine ist eine freie, webbasierte Projektmanagement-Software. Sie kann für Benutzer- und Projektverwaltung, Diskussionsforen, Wikis, zur Ticketverwaltung oder Dokumentenablage genutzt werden. Das	 Ticket-Modul	 gilt	 als das	 „Herzstück“	 Redmines,	 welches	 das	
Projektbearbeitungsprogramm	ausmacht.	Es	ermöglicht	die	Anzeige	von	Aufgaben	und	Problemen,	 welche	 zu	 lösen	 sind,	 um	 das	 Projekt	 zu	 bearbeiten.	 Tickets	 bestimmen somit	die	Richtung	und	den	Weg	der	Projektbearbeitung


## Neues Ticket (Issue) anlegen
Neue Tickets können im Reiter "Neues Ticket" angelegt werden. Unter Tickets versteht man in Redmine alle Arten von Aufgaben, die zu erledigen sind (z.B. Requirements, Tasks, Bugs, etc.).
Beim Erstellen müssen alle notwendigen Daten angegeben werden:
* **Tracker:** Art der Aufgabe
* **Thema:** Titel der Aufgabe
* **Status:** in welchem Status sich die Aufgabe befindet (z.B. New für gerade erstellt, oder Closed für bereits abgeschlossen)
* **Priorität:** gibt an wie dringend die Aufgabe erledigt werden muss

Es können zudem optionale Felder ausgefüllt werden (sollten auf jeden Fall ausgefüllt werden):
* **Beschreibung:** eine genaue Beschreibung der Aufgabe, damit der Developer später die Aufgabe möglichst schnell und richtig abarbeiten kann
* **Zugewisen an:** der Verantwortliche für die Aufgabe
* **Zielversion:** gibt an in welchem Release diese Aufgabe erledigt werden muss
* **Beginn und Abgabedatum:** Zeitspanne, in der die Aufgabe erledigt werden muss
* **Geschätzter Aufwand:** Aufwand der ungefähr für die Aufgabe aufgebracht werden muss
* **% erledigt:** prozentualer Fortschritt der Aufgabe

Es könne auch Dateien (z.B. Bilder) angehängt werden, damit die Aufgabe z.B. verständlicher wird.

*Hinweis: Die #TaskNr, die wir bei jedem Commit angeben müssen, wird von Redmine automatisch vergeben.*

![Creating a new ticket](/wiki/redmine/new_ticket.png)



## Ticket Übersicht
Im Reiter Tickets sind alle erstellten Tickets in einer Tabelle aufgelistet. Die Tickets können nach verschiedenen Filter-Typen gefiltert werden (Default: Filtern nach Status; weitere Filter könne über das DropDown „Filter hinzufügen“ angelegt werden).

![Tickets overview](/wiki/redmine/overview_tickets.png)



## Ticket Detailansicht und Bearbeitung
Mit einem Klick auf das Thema in der Übersichtsseite gelangt man zur Detailansicht des Tickets. Hier können die Fortschritte dokumentiert werden und das Ticket aktualisiert werden.
Es kann der Fortschritt aktualisiert werden (über „Aufwand buchen“ oder „Bearbeiten“) und die Felder aktualisiert/erweitert werden.
Alle Änderungen werden in der Detailansicht in einer Historie dargestellt, somit kann immer nachvollzogen werden, wer, was, wann gemacht hat.

![Ticket detail](/wiki/redmine/ticket_detail.png)



## Kalender
Der Kalender von Redmine gibt eine gute Übersicht über alle Aufgaben, wann sie beginnen und wann sie fertig sein müssen. Auch hier können die Tickets wieder mit Filter eingeschränkt werden. Die Legende befindet sich unterhalb des Kalenders.

![Redmine calendar](/wiki/redmine/redmine_calendar.png)



### Weitere Informationen
Die Seminararbeit von Martynas Pareigis (Uni Hamburg, 20.09.2014) gibt eine weitere gute Übersicht über die wichtigsten Funktionen von Redmine.
Diese ist unter dem Link https://hps.vi4io.org/_media/teaching/sommersemester_2014/wwa14-pareigis-redmine-ausarbeitung.pdf abrufbar.

