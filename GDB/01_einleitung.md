layout: page
title: "Einleitung"
permaleink: /gdb/einleitung
# Einleitung

## Motivation für DBMS (database management system)

- Redundanz und Inkonsistenz
  - Daten müssen oft in verschiedenen Kontexten gespeichert sein
- Zugriffsbeschränkung
  - Wenn Daten in unterschiedlichen Dateien liegen ist Verknüpfung schwierig
- Mehrbenutzerbetrieb
- Verlust von Daten
- Integritätsverletzung
  - Bedingungen die an die Daten gestellt werden
- Sicherheit
  - Rechte für unterschiedliche Nutzer
- Entwicklungskosten
  - Dateiverwaltung muss nicht neu implementiert werden

## Datenbankabstraktion
1. Physische Ebene (Daten im Speicher)
2. Logische Ebene (Schema)
3. Sichten (zugeschnittene Teilmenge der Informationen)

Eine Änderung in der physischen Ebene darf die logische Ebene nicht verändern.

## Datenmodelle 
Um die Realität in einer Datenbank zu modellieren muss man erst selbst ein konzeptuelles Schema entwerfen.
Danach kann man dieses Schema halbautomatisch in verschiedene festgelegte logische Datenmodelle übersetzen.
Das hier verwendete Modell nennt sich relationales Modell und beschreibt Relationen anhand von Tabellen.

Andere Darstellungsmöglichkeiten wären XML, Hierarchische Modelle oder Objektorientierte Datenmodelle (...)
