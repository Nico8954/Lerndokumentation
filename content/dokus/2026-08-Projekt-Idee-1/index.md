+++
title = "1. Projekt Idee"
date = 2026-08-10
description = "2. Projekt Idee."
[extra]
tags = ["AI", "Projekt"]
+++


# Projektauftrag: Zwei Ideen für eine On-Device-AI-App

## Auftrag

Ihr habt bereits verschiedene AI-Modelle, APIs, Technologien und mögliche
Funktionen für mobile AI-Apps recherchiert.

Nun verwendet ihr diese Recherche, um **zwei unterschiedliche Projektideen** für
unser nächstes Projekt zu entwickeln.

Die spätere App soll grundsätzlich auf folgenden Plattformen umgesetzt werden
können:

- iOS mit Swift
- Android mit Java

Das Ziel ist noch nicht, die App zu programmieren.

Ihr sollt herausfinden, welche zwei Ideen technisch interessant und realistisch
wären und welche davon sich besser für unser Projekt eignet.

---

## Wichtig

Verwendet für eure Projektideen möglichst Ergebnisse aus eurer bisherigen
Recherche.

Zum Beispiel:

- ein interessantes AI-Modell
- eine interessante API
- eine Funktion, die ihr gefunden habt
- eine iOS-Technologie
- eine Android-Technologie

Ihr dürft zusätzliche Informationen recherchieren, wenn ihr sie für eure
Projektidee benötigt.

---

## 1. Zwei Projektideen auswählen

Entwickelt **zwei unterschiedliche Projektideen**.

Die Ideen dürfen verschiedene AI-Funktionen kombinieren.

Mögliche Beispiele:

- Lernassistent
- Übersetzer
- Notizen-Assistent
- Dokumenten-Assistent
- Offline-Chatbot
- Sprachassistent
- App zur Texterkennung und Zusammenfassung
- App zur Analyse von Bildern
- App für Sprache-zu-Text
- App zur Unterstützung beim Lernen

Ihr dürft selbstverständlich auch eigene Ideen entwickeln.

---

## Projektidee 1

### 1. Idee

Beschreibt eure App kurz.

Beantwortet:

1. Wie heisst eure Projektidee?
2. Was soll die App machen?
3. Welches Problem löst sie?
4. Wer würde die App benutzen?
5. Was ist die wichtigste Funktion?
6. Daily Tracker
7. Sie soll, eine möglichkeit haben, einen Kalender und To-Dos zu erstellen und
   Bilderkennung haben
8. Sie soll helfen den Tag und die Aufgaben zu planen, ausserdem soll sie bei
   der Ernährung helfen durch das scannen von Essen und die darauf folgende
   Analyse.
9. Ich und alle die Ihren Tag gerne Planen würden und ihre Ernährung verbessern
   wollen.
10. Das Scannnen von Essen um die Nährwerte zu erhalten und das Vorschlagen von
    Rezepten, mit den angegebenen Zutaten.

---

### 2. AI-Funktion

Beschreibt, wofür AI in der App verwendet wird.

Zum Beispiel:

- Texte zusammenfassen
- Fragen beantworten
- Sprache erkennen
- Texte übersetzen
- Bilder analysieren
- Texte verbessern
- Informationen aus Dokumenten erkennen

Beantwortet:

1. Was macht die AI?
2. Welche Eingaben bekommt sie?
3. Welche Ergebnisse liefert sie?
4. Soll die AI lokal auf dem Gerät laufen?
5. Warum ist On-Device-AI für diese App sinnvoll?
6. Die AI wird verwendet, um die hochgeladenen Bilder zu analysieren und Rezept
   vorschläge zu machen.
7. Bilder
8. Text
9. Es wäre gut, aber sie ist mit 3 Milliarden Parameter relativ gross.
10. Damit sie überall auch ohne Internet funktioniert

---

### 3. Passendes AI-Modell

Wählt aus eurer bisherigen Recherche mindestens **ein geeignetes AI-Modell** für
die Projektidee aus.

Falls keines eurer bisherigen Modelle passt, dürft ihr ein neues suchen.

Dokumentiert:

- Name des Modells
- Aufgabe des Modells
- Modellgrösse
- unterstützte Sprachen
- Lizenz
- Offline-Nutzung möglich?
- Smartphone geeignet?
- Quelle / Link

Beantwortet zusätzlich:

**Warum passt dieses Modell zu eurer Projektidee?**

1. MiniCPM-V 1.0
2. Analysiert Bilder
3. 3 Milliarden Parameter
4. Englisch und Chinesisch
5. Apache-2.0-Lizenz
6. Ja
7. Ja (Vielleicht zu gross)
8. Hugging Face

---

### 4. Benötigte APIs

Überlegt, welche APIs oder Geräteschnittstellen eure App benötigt.

Zum Beispiel:

- Kamera
- Mikrofon
- Dateien
- lokale Datenbank
- Bildergalerie
- Spracherkennung
- Text-to-Speech
- Benachrichtigungen
- Kalender
- Standort

Erstellt eine Tabelle:

| API / Schnittstelle     | Wofür benötigt?                 | iOS | Android | Internet nötig? |
| ----------------------- | ------------------------------- | --- | ------- | --------------- |
| Kamera                  | Bild-Upload                     | Ja  | Ja      | Nein            |
| Kalender                | Kalender in der App             | Ja  | Ja      | Nein            |
| Fatsecret Nutrition API | Analyse, der Bilder und Rezepte | Ja  | Ja      | Ja              |

---

### 5. Umsetzung auf iOS

Beschreibt kurz, wie die App auf iOS umgesetzt werden könnte.

Beantwortet:

1. Welche Technologie würdet ihr verwenden?
2. Kann das ausgewählte Modell auf iOS laufen?
3. Wie könnte das Modell lokal ausgeführt werden?
4. Welche Apple-Technologien könnten verwendet werden?
5. Gibt es besondere Geräteanforderungen?
6. Welche Probleme könnten entstehen?
7. Core ML
8. Ja
9. über Xcode
10. Core MLa
11. Ja
12. Falsche Version

Mögliche Technologien:

- Swift (am besten mit Swift)
- Core ML
- MLX
- Vision
- Speech
- Foundation Models
- weitere passende Technologien

---

### 6. Umsetzung auf Android

Beschreibt kurz, wie die App auf Android umgesetzt werden könnte.

Beantwortet:

1. Welche Technologie würdet ihr verwenden?
2. Kann das ausgewählte Modell auf Android laufen?
3. Wie könnte das Modell lokal ausgeführt werden?
4. Kann die Umsetzung mit Java erfolgen?
5. Gibt es besondere Geräteanforderungen?
6. Welche Probleme könnten entstehen?
7. Executorch
8. Ja
9. Ja mit Executorch
10. Ja
11. Ja
12. Keine Offensichtlichen

Mögliche Technologien:

- Java (am besten mit Java)
- LiteRT
- MediaPipe
- ONNX Runtime
- llama.cpp
- ML Kit
- weitere passende Technologien

---

### 7. Machbarkeit

Bewertet eure Projektidee.

| Bereich             | Bewertung |
| ------------------- | --------- |
| Nutzen der App      | hoch      |
| Entwicklungsaufwand | mittel    |
| Smartphone-Eignung  | mittel    |
| Offline-Fähigkeit   | mittel    |
| iOS-Umsetzung       | mittel    |
| Android-Umsetzung   | mittel    |

Beantwortet:

1. Ist die Idee realistisch?
2. Ist das Modell klein genug?
3. Funktioniert die wichtigste Funktion offline?
4. Kann die App auf iOS und Android umgesetzt werden?
5. Was wäre wahrscheinlich das grösste Problem?
6. Ja
7. Wahrscheinlich nicht
8. Nein
9. Ja
10. Die grösse des Modells und die Bild Analyse

---

### 8. Fazit

Gebt eure eigene Meinung ab:

1. Findet ihr die Idee interessant?
2. Was ist der grösste Vorteil?
3. Was ist der grösste Nachteil?
4. Würdet ihr diese Idee als Projekt auswählen?
5. Warum?
6. ich finde die Idee sehr interessant, weil mir die App in meinem Alltag helfen
   würde
7. Die benutzung während der Lehre und in der Schule, um nichts zu vergessen.
8. Die Bild Analyse könnte sehr unakurat sein
9. Ja
10. Weil sie mir sehr nützen würde

---
