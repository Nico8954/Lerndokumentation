+++
title = "Recherche AI Projekt"
date = 2026-08-07
description = "Recherche zum Projekt im 2. Lehrjahr."
[extra]
tags = ["AI", "Projekt"]
+++

# Rechercheauftrag: On-Device-AI für mobile Apps

## Auftrag

Während der nächsten zwei bis drei Tagen recherchiert ihr verschiedene
Möglichkeiten für eine mobile App mit einem LLM.

Die App soll später grundsätzlich auf folgenden Plattformen umgesetzt werden
können:

- iOS mit Swift
- Android mit Java

Ihr müsst noch keine fertige Projektidee entwickeln und noch keine App
programmieren.

Zuerst sammelt ihr möglichst viele interessante Technologien, AI-Modelle, APIs
und mögliche Funktionen.

---

## Ziel

Am Ende der Recherche sollt ihr wissen:

- Welche AI-Modelle gibt es?
- Welche Modelle könnten auf einem Smartphone laufen?
- Welche Aufgaben können diese Modelle lösen?
- Welche APIs könnten für eine mobile App verwendet werden?
- Welche Technologien gibt es für iOS und Android?
- Welche Themen interessieren euch besonders?
- Welche Möglichkeiten wären für ein späteres Projekt realistisch?

---

## 1. AI-Modelle recherchieren

Sucht mindestens **15 verschiedene AI-Modelle**, die euch interessieren.

Ihr könnt unter anderem auf folgenden Plattformen suchen:

- Hugging Face Models
- Kaggle Models
- ModelScope
- TensorFlow Hub
- PyTorch Hub
- ONNX Model Zoo
- Apple Core ML Models
- Qualcomm AI Hub Models
- NVIDIA NGC Catalog
- Ollama Library

Ihr müsst nicht nur Sprachmodelle suchen.

Mögliche Arten von AI-Modellen:

- Textgenerierung
- Chatbots
- Übersetzung
- Zusammenfassung
- Spracherkennung
- Text-to-Speech
- Bilderkennung
- Objekterkennung
- Texterkennung aus Bildern
- Bildgenerierung
- Sentimentanalyse
- Rechtschreibkorrektur
- Klassifikation
- Frage-Antwort-Systeme
- Modelle für Dokumente

Zusätzlich könnt ihr Technologien untersuchen, mit denen AI-Modelle in Apps
integriert oder lokal ausgeführt werden können:

- Core ML
- MLX
- LiteRT
- MediaPipe
- ONNX Runtime
- llama.cpp
- TensorFlow
- PyTorch

### Fragen zu jedem Modell

Beantwortet zu jedem gefundenen Modell kurz folgende Fragen:

1. Wie heisst das Modell?
2. Wo wurde das Modell gefunden?
3. Wer hat das Modell entwickelt? (optional wäre nice zu wissen)
4. Was kann das Modell?
5. Warum interessiert euch das Modell?
6. Welche Eingaben verarbeitet es?
7. Welche Ergebnisse erstellt es?
8. Welche Sprachen unterstützt es?
9. Wie gross ist das Modell?
10. Kann es ohne Internet verwendet werden?
11. Könnte es auf einem Smartphone laufen?
12. Gibt es eine kleinere oder quantisierte Version?
13. Welche Lizenz besitzt das Modell?
14. Welche Einschränkungen hat das Modell?
15. Wofür könnte man es in einer App verwenden?

#### MiniCPM-V 1.0

1. MiniCPM-V 1.0
2. Hugging Face
3. MiniCPM-V-Team
4. Bilder analysieren, beschreiben und fragen dazu beantworten.
5. Es interessiert mich, weil ich die Idee mag, dass ich unterwegs von etwas ein
   Bild machen kann und dann gesagt bekomme, was es ist (Pflanzen Art z.B.).
6. Es verarbeitet Bilder und Text.
7. Es gibt Text zurück.
8. Englisch und Chinesisch
9. C.a. 3 Milliarden Parameter
10. Ja
11. Ja (Android)
12. Nein
13. Apache-2.0-Lizenz
14. ältere und schwächere Version von aktuellen MiniCPM-V-Modellen
15. Um nach der Klassifizierung von Dingen auf Bildern zu fragen.

#### Krea 2 Raw

1. Krea 2 Raw 1.0
2. Hugging Face
3. Krea-Team
4. Macht Bilder aus eingegebenen Text.
5. Ich finde es interessant, weil man durch die eingabe alles visualisieren
   kann.
6. Text
7. Bilder
8. Englisch
9. 12 Milliarden Parameter
10. Ja
11. Nein nur über Cloud API
12. Ja Krea 2 Turbo
13. Krea 2 Community License
14. Benötigt viel leistung und wahrscheinlich nicht auf handy benutzbar
15. Um beschriebene Dinge zu visualisieren.

#### Qwen2.5-1.5B-Instruct

1. Qwen2.5-1.5B-Instruct
2. Hugging Face
3. Qwen-Team von Alibaba Cloud
4. Text generieren
5. Ich finde es interessant, weil es sehr klein ist und viele Sprachen
   unterstützt.
6. Text
7. Text
8. über 29
9. 1.54 Milliarden Parameter
10. Ja
11. Ja
12. Ja Qwen2.5-0.5B-Instruct
13. Apache License 2.0
14. nicht mega leistungsfähig
15. Als Assistent oder support, der direkt antwortet

#### SmolLM2-360M-Instruct

1. SmolLM2
2. Hugging Face
3. Hugging Face-Team
4. Text generieren
5. Ich finde es interessant, weil es von Hugging Face selbst entwickelt wurde.
6. Text
7. Text
8. Englisch
9. Es gibt verschiedene Versionen: 135 mio., 360 mio., 1,7 mia.
10. Ja
11. Ja
12. Ja
13. Apache 2.0
14. die kleinen Versionen sollen eher ungenau sein.
15. Um Texte zusammenzufassen, oder als Rechtschreibehilfe

#### LFM2-1.2B

1. LMF2-1.2B
2. Hugging Face
3. Liquid AI
4. Text generieren
5. Ich war interessiert, weil es eher klein aber anscheinend schnell und relativ
   gut ist.
6. Text
7. Text
8. 8 (Englisch, Deutsch ...)
9. 1.2 Milliarden
10. Ja
11. Ja
12. Ja (LFM2-350M / LFM2-700M)
13. LFM Open License v1.0
14. Kann falsche Informationen geben
15. Als Assistent oder support, der direkt antwortet

#### Ministral 3 3B Instruct 2512

1. Ministral 3 3B Instruct
2. Hugging Face
3. Mistral AI
4. Bilder Analysieren und Texte generieren
5. Ich finde es interessant, da es Bilder generieren kann und auch programmieren
   etc.
6. Text, Bilder, System Prompts
7. Text
8. über 40
9. 3.8 Milliarden Parameter
10. Ja
11. knapp, mit etwas weniger leistung
12. Nein
13. Apache Lisence 2.0
14. Sehr gross
15. Einen Bild analysierer oder Code-Assistenz

#### Gemma 3 1B Instruction-Tuned

1. Gemma 3 1B IT
2. Hugging Face
3. Google DeepMind
4. Text generieren
5. Weil es von Google entwickelt wurde
6. Text
7. Text
8. über 140
9. 1 Miliarde Parameter
10. Ja
11. Ja
12. Ja / INT4- und Q4_0-Version
13. Gemma Terms of use
14. eher klein
15. Auto completion/ Assistent

#### meta-llama/Llama-3.2-1B-Instruct

1. Llama 3.2 1B Instruct.
2. Hugging Face
3. Meta
4. Text generieren
5. Weil es von Facebook ist
6. Nur Text
7. Text und Code
8. Deutsch, Englisch ...
9. 1,23 Milliarden Parameter
10. Ja
11. Ja
12. Ja
13. Llama 3.2 Community License
14. kleine grösse macht die generierung etwas schlechter
15. Schreibassistet, NPC in einem Game

#### OpenELM-450M-Instruct

1. OpenELM-450M-Instruct
2. Hugging Face
3. Apple
4. Text generieren
5. Sehr klein und von apple
6. Text
7. Text
8. Englisch
9. 450 Milllionen
10. Ja
11. Ja
12. Ja (OpenELM-270M-Instruct)
13. Apple Machine Learning Research License
14.
15. kleine lernübungen und korrekturen davon.

#### TinyLlama-1.1B-Chat-v1.0

1. TinyLlama 1.1B Chat v1.0.
2. Modelscope
3. Peiyuan Zhang, Guangtao Zeng, Tianduo Wang und Wei Lu
4. Text generieren
5. Weil es von Privatpersonen entwickelt wurde
6. Text
7. Text
8. Englisch
9. 1.1 Milliarden Parameter
10. Ja
11. Ja
12. Ja
13. Apache-2.0-Lizenz
14. es kann falsche dinge erfinden und ist eher langsam
15. Antwortvorschläge

### Tabelle für die Modelle

| Nr. | Modell                           | Aufgabe                            | Grösse                      | Offline möglich | Smartphone geeignet | Quelle       |
| --: | -------------------------------- | ---------------------------------- | --------------------------- | --------------- | ------------------- | ------------ |
|   1 | MiniCPM-V 1.0                    | Bild erkennung/ Beschreibung       | 3 Milliarden                | Ja              | Ja                  | Hugging Face |
|   2 | Krea 2 Raw                       | Bild generierung                   | 1,2 Milliarden              | Nein            | Nein                | Hugging Face |
|   3 | Qwen2.5-1.5B-Instruct            | Text generierung                   | 1,54 Milliarden             | Ja              | Ja                  | Hugging Face |
|   4 | SmolLM2-360M-Instruct            | Text generierung                   | 135 mio / 360 mio / 1,7 mia | Ja              | Ja                  | Hugging Face |
|   5 | LFM2-1.2B                        | Text generierung                   | 1,2 Milliarden              | Ja              | Ja                  | Hugging Face |
|   6 | Ministral 3 3B Instruct 2512     | Text generierung, Bild generierung | 3,8 Milliarden              | Ja              | Ja                  | Hugging Face |
|   7 | Gemma 3 1B Instruction-Tuned     | Text generierung                   | 1 Milliarde                 | Ja              | Ja                  | Hugging Face |
|   8 | meta-llama/Llama-3.2-1B-Instruct | Text generierung                   | 1,23 Milliarden             | Ja              | Ja                  | Hugging Face |
|   9 | OpenELM-450M-Instruct            | Text generierung                   | 450 Millionen               | Ja              | Ja                  | Hugging Face |
|  10 | TinyLlama-1.1B-Chat-v1.0         | Text generierung                   | 1,1 Milliarden              | Ja              | Ja                  | Modelscope   |

---

## 2. APIs und Geräteschnittstellen recherchieren

Sucht APIs und Schnittstellen, die für eine mobile AI-App interessant sein
könnten.

Mögliche Beispiele:

- Kamera
- Mikrofon
- Dateisystem
- Bildergalerie
- lokale Datenbank
- Standort
- Kalender
- Kontakte
- Benachrichtigungen
- Spracherkennung
- Text-to-Speech
- Texterkennung
- Bluetooth
- Internetzugriff
- Zwischenablage
- Sensoren
- lokale AI-Schnittstelle

Sucht mindestens **10 verschiedene APIs oder Schnittstellen**.

### Fragen zu jeder API

1. Wie heisst die API oder Schnittstelle?
2. Was kann sie?
3. Für welche App-Funktion könnte sie verwendet werden?
4. Gibt es sie auf iOS?
5. Gibt es sie auf Android?
6. Benötigt sie Internet?
7. Welche Berechtigungen werden benötigt?
8. Welche Daten verarbeitet sie?
9. Verarbeitet sie persönliche oder sensible Daten?
10. Könnte sie mit einem lokalen AI-Modell kombiniert werden?

#### IMDb-API

1. IMDb API
2. Sie kann Filme, Cast, Bewertungen und andere Dinge rund um Filme.
3. Bei einer Filmapp kann sie alles, was man möchte ausgeben.
4. Ja
5. Ja
6. Ja
7. keine
8. Filme und Daten dazu
9. Nein
10. Ja

#### Spotify Web API

1. Spotify Web API
2. Sie kann Alles auf Spotify ausgeben
3. Sie kann bei einer Musik App verwendet werden.
4. Ja
5. Ja
6. Ja
7. keine
8. Alles auf Spotify
9. Ja aber nur wenn man bei Spotify angemeldet ist und der Applikation die
   Rechte gibt.
10. Ja

#### NASA Open API

1. NASA Open API
2. Picture of the day und verschiedene andere Weltraum dinge
3. z.B., dass beim vÖffnen der App das Picture of the day angezeigt wird. Oder
   bei einer Sternen App, dass man den aktuellen Himmel sieht.
4. Ja
5. Ja
6. Ja
7. NASA API Key
8. Weltraum und Forschungsdaten
9. Nein
10. Ja

#### SBB API

1. SBB Swiss Mobility APIs
2. Fahrplan anzeigen und Fussweg
3. Um bei einem Tagesplaner zu schauen, wann man aufstehen muss um rechtzeitig
   bei der Arbeit zu sein.
4. Ja
5. Ja
6. Ja
7. keine
8. SBB Fahrplan und Fusswege
9. Nein
10. Ja

#### Fatsecret Nutrition API

1. Fatsecret Nutrition API
2. Essen und Nährwerte und Rezepte.
3. Bei einem Tagesplaner kann sie Essen analysieren und vorschlagen (mit AI
   kombiniert).
4. Ja
5. Ja
6. Ja
7. Entwicklerkonto
8. Essen, Nährwerte und Rezepte
9. Nein
10. Ja

#### Baditicker API Zürich

#### SRF Weather API

#### Bored API

1. bei dayly planner App, wenn man nichts zu tun hat

### Tabelle für die APIs

| Nr. | API oder Schnittstelle  | Funktion                                        | iOS | Android | Internet nötig | Verarbeitete Daten    |
| --: | ----------------------- | ----------------------------------------------- | --- | ------- | -------------- | --------------------- |
|   1 | IMDb API                | Gibt Daten zu Filmen                            | Ja  | Ja      | Ja             | Filmdaten             |
|   2 | Spotify Web API         | Gibt Daten rund um Spotify (Musik, Artists ...) | Ja  | Ja      | Ja             | Musik                 |
|   3 | NASA Open API           | Gibt Forschungsdaten und picture of the day.    | Ja  | Ja      | Ja             | Weltraum              |
|   4 | SBB API                 | Gibt Fahrpläne und Fusswege.                    | Ja  | Ja      | Ja             | ÖV und Fusswege       |
|   5 | Fatsecret Nutrition API | Gibt Nährwerte und Rezepte                      | Ja  | Ja      | Ja             | Rezepte und Nährwerte |

---

## 3. Technologien für iOS recherchieren

Sucht Technologien, mit denen AI-Funktionen auf iOS umgesetzt werden können.

Mögliche Suchbegriffe:

- Swift AI
- Swift On-Device AI
- Core ML
- Apple Intelligence
- Foundation Models Framework
- MLX Swift
- Vision Framework
- Natural Language Framework
- Speech Framework
- Create ML

### Fragen zur iOS-Recherche

1. Welche AI-Technologien bietet Apple an?
2. Welche Technologien funktionieren direkt auf dem Gerät?
3. Welche Modellformate werden unterstützt?
4. Wie kann ein Modell in Swift verwendet werden?
5. Welche Technologien unterstützen Text?
6. Welche Technologien unterstützen Bilder?
7. Welche Technologien unterstützen Sprache?
8. Welche Geräte werden benötigt?
9. Welche iOS-Version wird benötigt?
10. Welche Einschränkungen gibt es?
11. Können Modelle von Hugging Face verwendet werden?
12. Müssen Modelle zuerst konvertiert werden?

### Antworten

1. Core ML, MLX
2. Core ML
3. Safetensors, MLX native
4. Lokal, mit dem Apple LMX Swift framework
5.
6.
7.
8. Macbook
9. ios 26.0
10. Es können nicht alle Modell Formate verwendet werden
11. Ja
12. Kommt darauf an, welches Format sie haben

### Tabelle für iOS-Technologien

| Technologie | Aufgabe           | Lokal ausführbar | Programmiersprache | Einschränkungen                  |
| ----------- | ----------------- | ---------------- | ------------------ | -------------------------------- |
| Core ML     | llm laufen lassen | Ja               | Swift              | kein llm training, Speicherlimit |
| MLX         | llm laufen lassen | Ja               | Swift              | Nur Apple Silicon                |
|             |                   |                  | Swift              |                                  |
|             |                   |                  | Swift              |                                  |
|             |                   |                  | Swift              |                                  |

---

## 4. Technologien für Android recherchieren

Sucht Technologien, mit denen AI-Funktionen auf Android umgesetzt werden können.

Mögliche Suchbegriffe:

- Android On-Device AI
- Java AI Android
- LiteRT
- TensorFlow Lite
- MediaPipe
- ML Kit
- ONNX Runtime Mobile
- ExecuTorch
- llama.cpp Android
- Android Neural Networks API

### Fragen zur Android-Recherche

1. Welche AI-Technologien gibt es für Android?
2. Welche Technologien können mit Java verwendet werden?
3. Welche Modelle können lokal ausgeführt werden?
4. Welche Modellformate werden unterstützt?
5. Können GPU oder NPU verwendet werden?
6. Welche Android-Versionen werden unterstützt?
7. Welche Geräteanforderungen gibt es?
8. Welche Unterschiede gibt es zwischen Android-Geräten?
9. Können Hugging-Face-Modelle verwendet werden?
10. Müssen Modelle zuerst konvertiert werden?
11. Welche Technologien eignen sich für Text?
12. Welche Technologien eignen sich für Bilder und Sprache?

#### Antworten

1. LiteRT, ML Kit, Executorch
2. LiteRT, ML Kit, Executorch
3. Die meisten, meiner oben aufgeführten Modelle laufen lokal
4. tflite, pte und gguf
5. Ja
6. API 23 +
7. guter Arbeitsspeicher
8. Verschiedene GPU und NPU
9. Ja
10. Einige meiner oben aufgeführten Modelle müssen konvertiert werden
11. ML Kit Executorch
12. ML Kit

### Tabelle für Android-Technologien

| Technologie | Aufgabe                | Lokal ausführbar | Mit Java verwendbar | Einschränkungen                              |
| ----------- | ---------------------- | ---------------- | ------------------- | -------------------------------------------- |
| LiteRT      | llm ausführen          | Ja               | Ja                  | Modelle müssen vielleicht konvertiert werden |
| ML Kit      | AI funktionen einbauen | Ja               | Ja                  | Nicht für alle Modelle verwendbar            |
| Executorch  | llm lokal ausführen    | Ja               | Ja                  | Modelle müssen vielleicht konvertiert werden |

---

## 5. Interessante AI-Funktionen sammeln

Sammelt mindestens **15 Funktionen**, die eine AI-App besitzen könnte.

Beispiele:

- Texte zusammenfassen
- Texte übersetzen
- Fragen beantworten
- Texte vereinfachen
- Notizen sortieren
- Sprache in Text umwandeln
- Text vorlesen
- Objekte in Bildern erkennen
- Dokumente analysieren
- Lernfragen erstellen
- Texte korrigieren
- Ideen vorschlagen
- Termine aus Texten erkennen
- Bilder beschreiben
- lokale Dateien durchsuchen

### Fragen zu jeder Funktion

1. Was macht die Funktion?
2. Für wen wäre sie nützlich?
3. Welches Problem löst sie?
4. Welches AI-Modell könnte dafür verwendet werden?
5. Welche APIs werden benötigt?
6. Funktioniert sie offline?
7. Könnte sie auf iOS und Android umgesetzt werden?
8. Wie schwierig wäre die Umsetzung?
9. Welche Daten verarbeitet die Funktion?
10. Welche Datenschutzprobleme könnten entstehen?

### Tabelle für mögliche Funktionen

| Nr. | Funktion                        | Mögliches Modell        | Benötigte APIs          | Offline möglich | Interesse |
| --: | ------------------------------- | ----------------------- | ----------------------- | --------------- | --------- |
|   1 | Bild Analyse                    | MiniCPM-V               | Keine                   | Ja              | hoch      |
|   2 | Fragen beantworten              | Llama 3.2 1B Instruct.  | keine                   | Ja              | mittel    |
|   3 | Coaching                        | Llama 3.2 1B Instruct.  | Fatsecret Nutrition API | Nein            | niedrig   |
|   4 | Rezept Vorschlag                | Ministral 3 3B Instruct | Fatsecret Nutrition API | Nein            | mittel    |
|   5 | Kalorien Tracken                | MiniCPM-V               | Fatsecret Nutrition API | Nein            | hoch      |
|   6 | Tasks tracken                   | Llama 3.2 1B Instruct.  | Keine                   | Ja              | hoch      |
|   7 | Notifications                   | OpenELM-450M-Instruct   | Keine                   | Ja              | niedrig   |
|   8 | Automatisches updaten von tasks | OpenELM-450M-Instruct   | Keine                   | Nein            | mittel    |
|   9 | Zeit tracken                    | OpenELM-450M-Instruct   | Keine                   | Ja              | mittel    |
|  10 | Bilder erstellen                | Krea 2 Raw              | Keine                   | Nein            | niedrig   |

---

## 6. On-Device und Cloud vergleichen

Untersucht den Unterschied zwischen lokaler AI und AI aus der Cloud.

### Fragen

#### 1. Was bedeutet On-Device-AI?

On-Device-AI bedeutet, dass das AI-Modell **direkt auf dem Smartphone oder einem
anderen Gerät ausgeführt wird**. Die Daten müssen dafür nicht an einen Server
geschickt werden.

#### 2. Was bedeutet Cloud-AI?

Cloud-AI bedeutet, dass die AI **auf einem Server im Internet ausgeführt wird**.
Die App sendet zum Beispiel einen Text oder ein Bild an den Server und erhält
danach das Ergebnis zurück.

#### 3. Welche Variante benötigt Internet?

**Cloud-AI** benötigt normalerweise eine Internetverbindung. **On-Device-AI**
kann auch ohne Internet funktionieren.

#### 4. Welche Variante schützt persönliche Daten besser?

**On-Device-AI** schützt persönliche Daten meistens besser, weil die Daten auf
dem eigenen Gerät verarbeitet werden und nicht an einen externen Server
geschickt werden müssen.

#### 5. Welche Variante ist schneller?

**On-Device-AI** kann bei kleineren Modellen schneller reagieren, weil keine
Daten über das Internet übertragen werden müssen. Cloud-AI hat dafür stärkere
Hardware und kann bei grossen oder komplizierten Modellen schneller sein.

#### 6. Welche Variante benötigt mehr Speicherplatz auf dem Gerät?

**On-Device-AI** benötigt mehr Speicherplatz, da das AI-Modell auf dem
Smartphone gespeichert werden muss.

#### 7. Welche Variante verursacht laufende Kosten?

**Cloud-AI** kann laufende Kosten verursachen, weil viele Anbieter für
API-Aufrufe oder die verwendete Rechenleistung Geld verlangen.

#### 8. Welche Variante funktioniert auf älteren Smartphones besser?

**Cloud-AI** funktioniert meistens besser auf älteren Smartphones, weil die
eigentliche Berechnung auf einem leistungsfähigen Server stattfindet.

#### 9. Welche Variante kann grössere Modelle verwenden?

**Cloud-AI** kann deutlich grössere Modelle verwenden, da Server wesentlich mehr
RAM, Speicher und Rechenleistung besitzen als Smartphones.

#### 10. Welche Variante wäre für ein Schulprojekt geeigneter?

Für ein einfaches Schulprojekt ist **Cloud-AI meistens einfacher**, weil man
über eine API schnell leistungsfähige AI-Modelle verwenden kann.

Wenn jedoch Offline-Nutzung, Datenschutz oder On-Device-AI Teil der Aufgabe
sind, ist **On-Device-AI interessanter**, zum Beispiel mit kleinen Modellen über
LiteRT, ExecuTorch oder Core ML.

### Vergleich

| Thema                   | On-Device-AI                                                         | Cloud-AI                                                     |
| ----------------------- | -------------------------------------------------------------------- | ------------------------------------------------------------ |
| **Internetverbindung**  | Nicht notwendig                                                      | Normalerweise notwendig                                      |
| **Datenschutz**         | Sehr gut, Daten bleiben auf dem Gerät                                | Daten werden häufig an einen Server übertragen               |
| **Geschwindigkeit**     | Sehr schnelle Reaktion bei kleinen Modellen                          | Abhängig von Internet und Server, aber starke Rechenleistung |
| **Modellgrösse**        | Eher kleine und optimierte Modelle                                   | Sehr grosse Modelle möglich                                  |
| **Kosten**              | Normalerweise keine Kosten pro Anfrage                               | Kann laufende API- oder Serverkosten verursachen             |
| **Geräteanforderungen** | Relativ hohe Anforderungen an RAM, CPU, GPU oder NPU                 | Geringere Anforderungen an das Smartphone                    |
| **Offline-Nutzung**     | Ja                                                                   | Normalerweise nein                                           |
| **Entwicklungsaufwand** | Eher höher, Modelle müssen integriert und teilweise optimiert werden | Meist einfacher durch fertige APIs                           |

---

#### Kurz gesagt

**On-Device-AI:** Mehr Datenschutz, offline möglich und keine API-Kosten,
benötigt aber ein leistungsfähigeres Gerät.

**Cloud-AI:** Grössere und leistungsfähigere Modelle und einfacher zu
integrieren, benötigt aber Internet und kann laufende Kosten verursachen.

---

## 7. Auswahl der interessantesten Ergebnisse

Wählt nach der Recherche eure **fünf interessantesten Ergebnisse** aus.

Das können sein:

- AI-Modelle
- Technologien
- APIs
- Funktionen
- Frameworks
- Bibliotheken

1. Fatsecret Nutrition API
2. MiniCPM-V
3. Task tracker
4. Bild Analyse
5. Kalorien tracken

---

## 8. Persönliches Fazit

Beantwortet am Schluss folgende Fragen:

1. Welche AI-Art interessiert euch am meisten?
2. Welches Modell fandet ihr am interessantesten?
3. Welche API würdet ihr gerne verwenden?
4. Welche iOS-Technologie fandet ihr interessant?
5. Welche Android-Technologie fandet ihr interessant?
6. Welche Funktionen wären für eine spätere App geeignet?
7. Was hat euch bei der Recherche überrascht?
8. Welche Themen möchtet ihr noch genauer untersuchen?
9. Welche drei möglichen Richtungen für ein Projekt erkennt ihr?
10. Welche Richtung würdet ihr aktuell empfehlen?
11. Ich finde natürlich die AI's, die Text eingaben und ausgaben haben am
    interessantesten, weil sie die meisten möglichkeiten haben. Ich muss aber
    auch sagen, dass ich die möglichkeit ein Bild einzugeben und eine Analyse
    davon als text zu erhalten sehr viele möglichkeiten bietet.
12. Ich fand MiniCPM-V am interessantesten, weil man Bilder und Text eingeben
    kann.
13. Ich denke, dass die Fatsecret Nutrition API sehr viele möglichkeiten in
    einer Dailyplanner App hätte.
14. MLX
15. Executorch, weil es am meisten Möglichkeiten bietet.
16. Task tracker und Bilderkennung
17. Wie viele llm Modelle es gibt.
18. Ich würde die ios technologien gerne noch einmal anschauen, weil mir die
    Recherche dort am schwierigsten fiel.
19. Ich sehe eine Planungsapp, auf der man seinen ganzen Tag planen kann,
    inklusive Essen (mit den Nährwerten), Arbeitsweg, etc. Auch könnte ich mir
    mit der NASA API eine kleine news App vorstellen, welche man anstelle von
    TikTok im Bus öffnen kann. Sonst wäre vielleicht auch noch eine Coaching App
    möglich, welche dich bei egal welchem Ziel unterstüzt es zu erreichen, durch
    tasks und so.
20. Ich würde gerne die Tagesplanungsapp umsetzen, da ich so etwas gut
    gebrauchen könnte und ich aktuell keine App kenne, die Task tracking und
    gute Ernährung vereint

---

## Anforderungen

Die Dokumentation muss mindestens enthalten:

- [ ] 15 recherchierte AI-Modelle
- [ ] 10 recherchierte APIs oder Schnittstellen
- [ ] 5 iOS-Technologien
- [ ] 5 Android-Technologien
- [ ] 15 mögliche AI-Funktionen
- [ ] einen Vergleich zwischen On-Device-AI und Cloud-AI
- [ ] fünf besonders interessante Ergebnisse
- [ ] ein persönliches Fazit
- [ ] Quellen und Links zu den gefundenen Informationen

---

## Wichtig

- Es muss noch keine feste Projektidee ausgewählt werden.
- Es muss noch keine App programmiert werden.
- Ihr dürft verschiedene AI-Bereiche untersuchen.
- Die Recherche darf nicht nur auf Hugging Face stattfinden.
- Schreibt die Informationen in eigenen Worten.
- Gebt bei allen wichtigen Informationen die Quelle an.
- Achtet auf Modellgrösse, Lizenz, Datenschutz und Geräteanforderungen.
- Überlegt immer, ob eine Technologie auf iOS und Android verwendet werden
  könnte.
