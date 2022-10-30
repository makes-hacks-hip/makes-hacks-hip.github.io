# Github Überblick

Wir verwenden Github um unsere Projekte zu planen und zu dokumentieren.

## Wie kann ich mit Github arbeiten?

Zunächst brauchst du einen Github Acount. Diesen kannst du dir [hier](https://gothub.com) anlegen.
Um auf deinem Rechner mit den Dateien in den Repositories zu arbeiten brauchst du einen git Client. Eine einfache Möglichkeit ist die [Github Desktop App](https://desktop.github.com).
Um Dokumentation auf deinem Rechner zu bearbeiten empfehlen wir [Zettlr](https://www.zettlr.com).

## Wie verwenden wir Github?

![github.png](github.png)

Wir verwenden Github vor allem zur Planung von Projekten mit "Projects" und zur Dokumentation der Projekte.

### Zugriffsrechte

Für die Zugriffsrechte benutzen wir Teams.
Es gibt ein Team für alle aktiven Makerspace Mitglieder: [makerspace-hip](https://github.com/orgs/makes-hacks-hip/teams/makerspace-hip)
Für jede Projekt-Gruppe gibt es ein Sub-Team. Wir haben z.B. ein Team [lotstation](https://github.com/orgs/makes-hacks-hip/teams/lotstation), für alle die an der Make Lötstation arbeiten und ein Team [feinstaub-sensor](https://github.com/orgs/makes-hacks-hip/teams/feinstaub-sensor) für unser LoRaWan Feinstaubsensor-Projekt.

Pull-requests und andere Beiträge sind von allen willkommen, unabhängig davon ob jemand "aktives Mitglied" ist oder nicht!

Wir sind eine Projekt-Gruppe des Repair-Café Hilpoldstein, und offen für jeden, ohne Mitgliedsbeitrag. Falls du Interesse hast mitzukommen findest du unsere Termine auf der [Seite des Repair-Café](https://www.repaircafe-hilpoltstein.de). 

### Projektplanung mit Github

![projects.png](projects.png)
Zur Projektplanung verwenden wir Github Projects.

![Kanban-Board.png](Kanban-Board.png)
Für jedes Projekt gibt es ein Kanban-Board um die Ziele zu planen.

![Doku-Repo.png](Doku-Repo.png) 
Weiter gibt es für jedes Projekt ein "Dokumentations-Repository", in dem die Projekt Dokumente abgelegt werden und das Projekt mit Hilfe des statischen Seitengenerators Mkdocs dokumentiert wird.
Die Dokumentation in Form von [Markdown](https://www.markdownguide.org/basic-syntax/) Dokumenten befindet sich im Unterordner "docs".
Die Dokumentation von Mkdocs findest du [hier](https://www.mkdocs.org/user-guide/writing-your-docs/). 

![Action.png](Action.png) 
Wir haben für jedes Dokumentations-Repository eine Github Action die automatisch die generierte Dokumentation aktualisiert.

## Informationssammlung für Projekte

Die Diskussion zu neuen Projekten findet in der Regel im [Forum des Repaircafé](https://forum.makes-hacks-hip.de) statt.

Um schnell, und relativ unstrukturiert Informationen zu Projekten zu sammeln verwenden wir das im Dokumentations-Repository integrierte Wiki.
![wiki.png](wiki.png) 

Für die strukturierte Dokumentation verwenden wir [Mkdocs](https://www.mkdocs.org). Die Markdown-Dokumente liegen im Repository im Unterordner "docs".

## Probleme mit Projekten
Zur Dokumentation und Bearbeitung von Problemen mit der bisherigen Projektumsetzung verwenden wir Github Issues.
![issues.png](issues.png) 
