<!-- .slide: class="master-cover" -->

## Rust Fullstack Development

<br/>

### Tech Kafi <br>?.?.2024
### Daniel Tschan<br>Iwan Imsand
<!-- .element style="margin-bottom: 12rem" --->

-*-*-

# Agenda

- Voraussetzungen
- Rechtliches
- Übersicht Coding AIs
- Demo
- Free vs Paid

-*-*-

## Voraussetzungen

* Einsatz von Coding AI mit Kunden abgeklärt
* Unverschlüsselte Credentials aus Repo entfernt
    * z.B. mit [TruffleHog](https://github.com/trufflesecurity/trufflehog)

-*-*-

## Rechtliches

* Vorsicht bei permissiv lizenzierten Open Source Projekten
    * BSD, Apache, MIT, ...
* Falls nicht anders dokumentiert generieren Coding AIs Copyleft lizenzierten Code
    * Nicht kompatibel mit permissiven Lizenzen
* Bei anderen Projekten rechtliches Risiko momentan vernachlässigbar

Weitere Informationen: https://www.bloomberglaw.com/external/document/X4H9CFB4000000/copyrights-professional-perspective-ip-issues-with-ai-code-gener

-*-*-

## Privacy bei Coding AIs

* Benutzt die Coding AI Benutzerdaten fürs Training?
* Welche Daten werden raufgeladen?
* Ausschliessen von Dateien vom Indexing/Context

-*-*-

## Warum Codeium AI

-*-*-


## Codeium AI

* Autocompletion
* Chat
* Command Mode
* Forge (Code Reviews, nur Bezahlversion)

-*-*-

## Beispiele

* Generierung von Codefragmenten
* Generierung ganzer Funktionen
* Generierung von Dokumentation
* Generierung von Tests
* Unterstützung bei der Fehlerbehebung
* Unterstützung bei Refactorings
* Erklärung von vorhandemem Code
* Unterstützung bei Schätzungen
* Analysieren von Logs

-*-*-

## Demo Autocomplete

-*-*-

## Demo Chat

* Iteratives vorgehen
* Zuerst nach Projektstruktur Fragen
* Dateien Erstellen, allenfalls mit Scaffolding Tool
* Coding AI verwenden um Inhalte in einzelne Dateien zu generieren

-*-*-

## Wann welchen Modus einsetzen

* Autocomplete: Nur für Codefragmente, Zeit und Kontext ist limitiert
* Command Mode: Generierung von Funktionen, TODO: Ist der Kontext und die Zeit hier limitiert?
* Chat: Generierung ganzer Klassen. Stellen von Fragen, Erklären  

-*-*-

## Was schickt Codeium mit?

-*-*-

## Steuern des Kontexts

* Ingorieren von Dateien
* Hinzufügen von Dateien
* Löschen des Contexts
* Local indexing
* Remote indexing (nur Bezahlversion)
* Context pinning

-*-*-

## Tipps und Tricks

* Sprechende Variabel- und Funktionsnamen helfen AI
* Kommentare helfen der AI

-*-*-

## Empfehlung für Einsatz

* OK von Kunde ist ein Muss
* Codeium Gratis Version ausprobieren

-*-*-

## Diskussion

Authors: \
Daniel Tschan, Iwan Imsand \
Puzzle ITC

Licensed under the terms of the GNU GPL-3.0 license.

https://github.com/puzzle/tws24-fullstack-rust-slides
