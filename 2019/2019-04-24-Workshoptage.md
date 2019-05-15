# CH Open Workshoptage

## About

- Date: 10. - 12. September 2019
- Location: HSR Rapperswil
- Länge: 9:10 - 17:00 (probably?)

## Timeline

- Die Eingabefrist ist Freitag, 17. Mai 2019.
- Der Durchführungsentscheid wird spätestens zwei Wochen vor den Workshop-Tagen kommuniziert.
- Die Bereitstellung der Inhalte erfolgt ebenfalls bis spätestens zwei Wochen vor dem Workshop, damit die Teilnehmenden ihre Arbeitsumgebung bereits vor Kursbeginn aufsetzen können. Alternativ kann der Inhalt auf einer ausreichenden Anzahl USB-Sticks am Kurstag verteilt werden.

## Links

- [Website](https://workshoptage.ch/)
- [CfP Infos](https://workshoptage.ch/call-for-proposals-2019/)
- [CfP submission](https://workshoptage.ch/call-for-proposals-2019/workshop-erfassen/)
- [Referenten-Informationen](https://workshoptage.ch/referenten-informationen/)
- Programm von früheren Jahren: [2018](https://workshoptage.ch/programm-2018/), [2017](https://workshoptage.ch/archiv/programm-2017/)

## Talk information

- Titel: **Test-Driven-Development für Python mit pytest**
- Thema: Software-Entwicklung mit Open Source
- Durchführungstage: alle

## Einleitung

*Beschreiben Sie kurz Ihren Workshop.*

Automatisiertes Testen ist ein essenzielles Werkzeug für qualitativen Python-Code. Das pytest-Framework ermöglicht es, Tests sowohl übersichtlicher als auch unkomplizierter umzusetzen, als dies mit Python-Bordmitteln wie dem "unittest"-Modul möglich wäre. Pytest lässt sich nahtlos mit existierenden Testsuites integrieren und bietet auch da viele Vorteile. Weiterhin lässt es sich problemlos an die eigenen Ansprüche anpassen und mit diversen Plugins erweitern.

Dieser Workshop bietet eine Einführung zu pytest mit zahlreichen Übungen. Teilnehmende lernen anhand von Beispielen die "best practices" für das Testen von Python-Code.

## Programm

*Bitte beschreiben Sie den Ablauf Ihres Workshops.*

Folgende Programmpunkte sind für den Workshop geplant:

- Einleitung und Terminologie: Warum automatisierte Tests, Arten von Tests, Aufgaben eines Test-Frameworks.
- Tests schreiben mit pytest: Installation, wichtige Features, Konfiguration, Assertions.
- Tests organisieren: "markers", Tests parametrisieren mit Daten, Tests überspringen.
- Abhängigkeiten modularisieren mit "fixtures": Setup/Teardown, Dependency Injection.
- Abhängigkeiten vermeiden mit Patching/Mocking: Warum, wann, wann lieber nicht, und wie.
- Mit bestehenden Testsuites und Frameworks umgehen: Existierende unittest/nose/Django-Testsuites ausführen, Strategien bei der Migration zu pytest.
- Plugins: Automatisch Testdaten generieren mit "hypothesis" (property-based testing), Testabdeckung (coverage), Nutzung mehrerer CPU-Cores/Maschinen und vieles mehr.
- Eigene Plugins verfassen: Verfügbare Hooks, Plugins als Teil einer Testsuite, Paketierung und Verteilung.
- Offene Fragerunde: Platz für Fragen und Probleme bei der Integration von pytest in bestehende Projekte der Teilnehmenden.

Je nach Zeit und Interessen des Publikums kann auch auf weitere Themen zu pytest oder zu verwandten Projekten (tox/devpi) eingegangen werden.

Der Workshop ist als "Hands-on"-Kurs konzipiert und enthält viele Übungen, womit die Teilnehmenden von Anfang an ihre eigenen Tests mit pytest schreiben können.

## Kursziel

*Bitte beschreiben Sie das Kursziel Ihres Workshops.*

Die Teilnehmenden haben mit dem Workshop erste Praxiserfahrung gesammelt und Basiswissen erhalten, um mit pytest bestehende oder neue Python-Projekte zu testen.

## Adressaten

*An welche Zielgruppe richtet sich der Workshop?*

Der Workshop richtet sich an Python-Programmierer*innen, welche gerne mehr über Testing lernen wollen. Personen, welche noch nie einen Test geschrieben haben sind gleichermassen willkommen wie solche, die bereits Test-Frameworks nutzen und mehr Wissen zu pytest sammeln wollen.

## Voraussetzungen

*Was für Voraussetzungen müssen die Teilnehmenden mitbringen?*

Grundkenntnisse zu Python und zu objektorientiertem Programmieren (beispielsweise was eine Klasse oder Instanz ist) werden vorausgesetzt. Vorkenntnisse zum Software-Testing werden keine benötigt.

Der Kurs wird auf Deutsch durchgeführt, die dazugehörigen Slides sind jedoch in Englisch verfasst.

## Infrastruktur

*Bitte beschreiben Sie die nötige Infrastruktur für die Teilnehmenden.*

Eigener Laptop (Betriebssystem egal) mit einer Installation von [Python 3](https://www.python.org).

## Biografie

*kurze Biografie (2-3 Sätze)*

Florian Bruhin ("The Compiler") hat 2015 das pytest-Framework entdeckt und seither in diversen Firmen sowie an Konferenzen Vorträge und Workshops zu pytest durchgeführt. Er ist Mitentwickler und -maintainer von pytest selbst sowie diversen Plugins.
