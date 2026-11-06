# Quizsachen

**Barrierefreie Quizze ganz einfach** – ein Editor für Lern-Quizze mit Texten, Bildern, Tönen und Vorlesefunktion für den Unterricht, z. B. für ByCS mebis/Moodle.

**▶ Direkt im Browser starten:** https://majort0m0.github.io/Quizsachen/

**⬇ Herunterladen:** [Quizsachen.html](https://github.com/Majort0m0/Quizsachen/releases/latest/download/Quizsachen.html) (eine einzige Datei, läuft offline – einfach doppelklicken)

- Fragetypen: Einfachauswahl, Mehrfachauswahl, Richtig oder falsch (mit Daumen hoch/runter), Reihenfolge (untereinander oder nebeneinander)
- Frage und Antworten aus Text, Bild (Upload, ARASAAC, Wikimedia Commons) und Ton (Upload oder Aufnahme mit Schnitt-Editor) – auch kombiniert
- Vorlesen per Sprachausgabe oder eigener Aufnahme, gut lesbare Schriften (u. a. Atkinson Hyperlegible, Andika), Bildbeschreibungen für Screenreader, Bedienung per Tastatur, automatischer Umbruch auf Handys
- Vorlagen mit fertiger Anordnung – oder frei gestalten; eigene Vorlagen speichern, exportieren und importieren
- Hintergrund als Farbe, Farbverlauf, Bild oder frei gestaltet im Editor – mit Texten, Bildern, Tönen und eigenen Zeichnungen
- Schnelle Eingabe vieler Fragen als Text (auch GIFT aus Moodle und Aiken) und Erstellung mit KI – per Prompt für jeden KI-Chat oder direkt über eine API (Claude, OpenAI-kompatible Dienste, lokale KI wie Ollama oder LM Studio)
- Rückmeldung nach jeder Frage oder am Ende, Fortschrittsanzeige, Abschlusskarte mit Übersicht, „Falsche wiederholen“
- Export als HTML-Datei (auch zum Einbetten per iframe), SCORM-1.2-Paket mit Bewertung, PDF-Arbeitsblatt mit Lösung und als Text (Quizsachen-Format, GIFT, Aiken)
- Keine Anmeldung, kein Server, keine Cookies – siehe [Datenschutz](DATENSCHUTZ.md)

## Lizenz

Quizsachen – Lizenz: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.de) Lernsachen.blog ([https://lernsachen.blog](https://lernsachen.blog))

Du darfst Quizsachen kopieren, weitergeben und verändern – auch in deiner Schule und im Kollegium –, solange du Lernsachen.blog als Urheber nennst, auf die Lizenz verweist, es nicht kommerziell nutzt und Veränderungen unter derselben Lizenz weitergibst. Die Quizze, die du damit erstellst, gehören dir; für darin verwendete Bilder und Töne gelten deren eigene Lizenzen.

Enthaltene Bausteine: [Preact](https://preactjs.com), [Immer](https://immerjs.github.io/immer/), [Excalidraw](https://excalidraw.com) (MIT-Lizenz); [Anthropic TypeScript SDK](https://github.com/anthropics/anthropic-sdk-typescript) für die KI-Schnittstelle ([Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)); Schriften Lexend, Nunito, Atkinson Hyperlegible, Andika, Merriweather, Caveat (SIL Open Font License 1.1). Bilder aus der Suche behalten ihre eigenen Lizenzen (ARASAAC: CC BY-NC-SA 4.0). Silbentrennung (Silben rot und blau): [Hypher](https://github.com/bramstein/hypher) (© 2011 Bram Stein, BSD-3-Clause) mit den deutschen TeX-Trennmustern dehyphn-x-2011-06-01 (© 2007–2011 Werner Lemberg, [LaTeX Project Public License 1.3c](https://www.latex-project.org/lppl/)), von Bram Stein ins Hypher-Format umgewandelt (npm-Paket hyphenation.de 0.2.1); die Silbenregeln für Sprechsilben kommen danach dazu. Die Autoren der Trennmuster sind für diese App nicht verantwortlich. Unverändertes Original: [tex-hyphen](https://github.com/hyphenation/tex-hyphen) (hyph-de-1996.tex, Stand 2011-06-01) bzw. CTAN (hyph-utf8).

<details><summary>Lizenztext von Hypher (BSD-3-Clause)</summary>

```
Copyright (c) 2011, Bram Stein
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:

 1. Redistributions of source code must retain the above copyright
    notice, this list of conditions and the following disclaimer.
 2. Redistributions in binary form must reproduce the above copyright
    notice, this list of conditions and the following disclaimer in the
    documentation and/or other materials provided with the distribution.
 3. The name of the author may not be used to endorse or promote products
    derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE AUTHOR "AS IS" AND ANY EXPRESS OR IMPLIED
WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO
EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT,
INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING,
BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY
OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE,
EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

</details>

---

# Anleitung

Diese Anleitung steht auch in der App unter „Anleitung“.

## Schnellstart

Mit Quizsachen erstellst du barrierefreie Quizze: Fragen mit Antworten zum Anklicken, Richtig-oder-falsch-Aussagen und Reihenfolgen – mit Texten, Bildern und Tönen, Vorlesefunktion und Rückmeldungen. Alles läuft direkt in deinem Browser, ohne Anmeldung.

### In 6 Schritten zum fertigen Quiz

1. **Vorlage wählen oder leer starten** – Datei-Menü (Ordner-Symbol) → „Neues Quiz …“. Bei einer Vorlage ist die Anordnung schon fertig. Dort kannst du auch gleich „Fragen als Text eingeben“ oder „Mit KI erstellen“ – das bisherige Quiz wird dann durch das neue ersetzt.
2. **Titel eingeben** – oben in der Leiste oder im Schritt „1 Start“.
3. **Hintergrund und Aussehen** – Schritte „2 Hintergrund“ und „3 Gestaltung“ (Schrift, Antwortkarten, Farben).
4. **Fragen anlegen** – im Schritt „4 Fragen“ einzeln, oder viele auf einmal mit „Fragen per Text eingeben“ bzw. mit Hilfe einer KI.
5. **Ablauf einstellen** – Schritt „5 Ablauf“ (Rückmeldung, Fortschritt, Abschlusskarte).
6. **Testen und speichern** – oben auf „Testen“ klicken, dann „Speichern“: als HTML-Datei, SCORM-Paket für mebis/Moodle, PDF-Arbeitsblatt oder als Text.

### So ist der Editor aufgebaut

- **Obere Leiste:** Titel, Rückgängig/Wiederholen, „Bearbeiten“/„Testen“, Datei-Menü, Anleitung, Datenschutz und „Speichern“.
- **Schrittleiste** (links): die fünf Arbeitsschritte.
- **Seitenleiste:** alle Einstellungen des gewählten Schritts.
- **Vorschau:** zeigt die gewählte Folie genau so, wie die Lernenden sie sehen. Richtige Antworten sind hier grün gestrichelt markiert.
- **Folienleiste** (unten): Startkarte, alle Fragen und die Abschlusskarte. Klicke eine Folie an, um sie zu bearbeiten. Fragen lassen sich hier per Ziehen umsortieren; „+ Frage“ legt neue an.

> **Tipp:** Deine Arbeit wird automatisch im Browser gespeichert. Sichere wichtige Quizze zusätzlich als Datei (Datei-Menü → „Als HTML-Datei speichern“).

## Vorlagen

Vorlagen geben Format, Farben, Schrift und die Anordnung von Frage und Antworten vor. Du musst nur noch Inhalte eintragen. Die Vorschau im Dialog zeigt jede Vorlage so, wie die Lernenden sie sehen.

- **Bunte Kacheln** – vier kräftige Antwort-Kacheln mit Buchstaben.
- **Bilderrätsel** – großes Bild links, Antworten rechts.
- **Bilder auswählen** – Bilder als Antworten, auch für Kinder, die noch nicht lesen.
- **Hör-Quiz** – Fragen werden vorgelesen oder abgespielt, alle Antworten haben einen Vorlese-Knopf.
- **Richtig oder falsch?**, **Reihenfolge** und **Zeitstrahl** – für die jeweiligen Fragetypen.
- **Leicht lesen** – große, besonders gut lesbare Schrift, wenige Antworten, alles wird vorgelesen.

Bei einem Quiz aus einer Vorlage ist die Anordnung gesperrt (Schloss-Symbol bei „Anordnung“). Mit „Anordnung selbst ändern“ gibst du sie frei.

### Eigene Vorlagen

Gestalte ein Quiz und speichere es über Datei-Menü → „Als Vorlage speichern …“ (oder im Schritt „Start“). Übernommen werden Format, Hintergrund mit Bildern und Elementen, Schrift, Farben, Antwortkarten, Ablauf und die Anordnung – auf Wunsch auch ein leeres Gerüst der Fragen. Die Vorlage steht dann unter „Neues Quiz“ bei „Eigene Vorlagen“: dort lädst, exportierst oder löschst du sie. Als Datei (`.quizvorlage.json`) gibst du Vorlagen an Kolleginnen und Kollegen weiter; sie importieren sie mit „Vorlage importieren …“.

> **Tipp:** Im Browser gespeicherte Vorlagen gibt es nur auf diesem Gerät und in diesem Browser – auch mit großen Hintergrundbildern. Beim Löschen der Browserdaten gehen sie verloren: Sichere wichtige Vorlagen zusätzlich als Datei.

## Fragen anlegen

### Fragetypen

- **Einfachauswahl** – genau eine Antwort ist richtig (Kreis anklicken).
- **Mehrfachauswahl** – eine oder mehrere Antworten sind richtig (Häkchen setzen). Die Lernenden sehen eckige Kästchen und den Hinweis „Wähle alle richtigen Antworten“.
- **Richtig oder falsch** – eine Aussage, darunter zwei große Knöpfe mit Daumen hoch / Daumen runter. Die Beschriftungen kannst du ändern (z. B. „Ja / Nein“), die Daumen im Schritt „Gestaltung“ abschalten.
- **Reihenfolge** – gib die Teile in der richtigen Reihenfolge ein. Beim Spielen sind sie gemischt und werden per Ziehen oder Tastatur sortiert – wahlweise untereinander oder nebeneinander.

### Frage und Antworten

Frage und jede Antwort können aus **Text, Bild, Ton** oder einer Kombination bestehen. Klicke bei einer Antwort auf „…“, um Bild, Ton und Vorlesen einzustellen. Mit `Enter` springst du zur nächsten Antwort bzw. legst eine neue an. Bis zu 8 Antworten sind möglich.

Unter „Rückmeldung“ kannst du einen Text für richtige und falsche Antworten eingeben – etwa eine kurze Erklärung. Klickst du in der Vorschau auf einen Kasten, springt die Seitenleiste zum passenden Feld; ein Doppelklick setzt den Cursor direkt hinein.

### Anordnung

Die Frage steht oben, links oder rechts, die Antworten als Raster, Liste oder Reihe. „Auto“ wählt passend zur Anzahl und Länge der Antworten. Mit dem Regler stellst du die Größe des Fragekastens ein. Lange Texte werden automatisch kleiner, damit sie in ihren Kasten passen.

**Frei anordnen:** Mit „Kästen frei anordnen“ verschiebst du Frage- und Antwortkästen direkt in der Vorschau und änderst ihre Größe an den Ecken (Pfeiltasten verschieben fein, mit `Umschalt` in großen Schritten). „Wieder automatisch anordnen“ macht das rückgängig.

> **Tipp:** Auf schmalen Bildschirmen (Handy) oder bei starker Vergrößerung ordnet das Quiz Frage und Antworten automatisch untereinander an – mit gut lesbarer Schrift.

## Fragen per Text & mit KI

Viele Fragen gibst du am schnellsten als Text ein: Folienleiste „+ Frage“ → „Mehrere per Text eingeben …“ (oder Datei-Menü). Rechts siehst du sofort, was erkannt wurde.

```
? Welches Tier hält Winterschlaf? [Bild: Igel]
( ) Reh
(x) Igel
> Der Igel schläft von November bis März.

? Welche Tiere sind Säugetiere?
[x] Wildschwein
[ ] Specht

? Spechte bauen Höhlen in Baumstämme.
= richtig

? Bringe in die richtige Reihenfolge.
1. Laich
2. Kaulquappe
3. Frosch
```

- `?` beginnt eine Frage, `(x)`/`( )` Einfachauswahl, `[x]`/`[ ]` Mehrfachauswahl, `= richtig`/`= falsch`, `1.` `2.` … Reihenfolge, `>` Erklärung.
- `[Bild: Igel]` sucht beim Übernehmen automatisch ein passendes Piktogramm bei ARASAAC.
- Fragen im **GIFT-Format** (z. B. aus der Moodle-Fragensammlung) und im **Aiken-Format** werden ebenfalls erkannt.

### Mit einer KI

In „Fragen mit KI erstellen“ legst du Thema, optional Material oder Stichpunkte, Anzahl, Zielgruppe, Fragetypen, Antworten pro Frage, Bilder und Erklärungen fest. Die Auswahl merkt sich Quizsachen für das nächste Mal. Dann gibt es zwei Wege:

- **Über einen KI-Chat:** Klicke eine KI-Anwendung an (z. B. AIS.chat, ByLKI, Duck.ai, ChatGPT). Der fertige Prompt mit deiner Auswahl wird automatisch übernommen: in die Zwischenablage (dort mit `Strg`+`V` einfügen), bei ChatGPT, Claude und Mistral zusätzlich direkt ins Eingabefeld. Für jede andere KI gibt es „Andere KI (Zwischenablage)“. Den Block mit dem Quiz kopieren und über „Ergebnis einfügen …“ übernehmen.
- **Über eine API-Schnittstelle:** mit einem eigenen API-Schlüssel (Claude von Anthropic oder ein Dienst mit OpenAI-kompatibler Schnittstelle wie OpenAI, Mistral, Gemini, OpenRouter) oder einer **lokalen KI** (Ollama, LM Studio – ohne Schlüssel). „Fragen erzeugen“ schickt den Prompt direkt ab; das Ergebnis erscheint in der Vorschau der Texteingabe. Den Schlüssel speichert Quizsachen nur, wenn du das einschaltest.

> **Achtung:** Gib keine personenbezogenen Daten von Schülerinnen und Schülern in eine KI ein und prüfe die Fragen vor dem Einsatz.

## Bilder & Töne

### Bilder

- **Hochladen** per Klick, Ziehen oder Einfügen (`Strg`+`V`). Bilder werden automatisch verkleinert und direkt in das Quiz eingebettet (Base64) – es entstehen keine externen Abhängigkeiten.
- **Suchen** bei [ARASAAC](https://arasaac.org) (Piktogramme, deutsche Suche) und [Wikimedia Commons](https://commons.wikimedia.org). Die Lizenz wird angezeigt und als Bildnachweis gespeichert.
- **Bildbeschreibung:** Für Screenreader. Bei Suchergebnissen wird das Suchwort vorgeschlagen. Besonders wichtig bei Antworten, die nur aus einem Bild bestehen.

### Töne

Tondateien hochladen oder direkt aufnehmen (Mikrofon). Im Schnitt-Editor wählst du mit Start- und Endmarke den gewünschten Ausschnitt. Ein Ton erscheint als runder Abspiel-Knopf.

## Vorlesen & Barrierefreiheit

- **Vorlese-Knöpfe:** Für jeden Text (Titel, Einleitung, Frage, Antwort, Hintergrund-Texte) einschaltbar. Die Computerstimme des Geräts liest vor – oder eine eigene Aufnahme. Im Schritt „Gestaltung“ schaltest du alle auf einmal ein.
- **Automatisch vorlesen:** Im Schritt „Ablauf“ – jede Frage wird beim Erscheinen vorgelesen.
- **Schriften:** u. a. *Lexend* (besonders leicht lesbar), *Atkinson Hyperlegible* (besonders gut unterscheidbare Buchstaben) und *Andika* (für Leseanfänger). Die zuletzt gewählte Schrift merkt sich Quizsachen für neue Quizze.
- **Silben rot und blau** (rot-blauer Silben-Knopf): Die Wörter erscheinen in Sprechsilben, abwechselnd blau und rot (Silbenmethode) – statt der Schriftfarbe, auf einer weißen Hinterlegung, damit sie auf bunten Karten und Hintergründen gut lesbar bleiben.
- **Tastatur:** Alle Antworten sind mit `Tab` und Pfeiltasten erreichbar, `Leertaste` wählt aus, die Zifferntasten `1`–`9` wählen direkt. Reihenfolgen: `Leertaste` nimmt ein Teil auf, Pfeiltasten verschieben, `Leertaste` legt ab.
- **Screenreader:** Fragen sind Überschriften, Antworten echte Auswahlfelder; Rückmeldungen werden angesagt.
- **Unterscheidung ohne Farbe:** Richtig/falsch wird zusätzlich mit Häkchen bzw. Kreuz gezeigt, Antworten tragen auf Wunsch Buchstaben.
- **Kleine Bildschirme und Zoom:** Das Quiz ordnet sich automatisch untereinander an (Reflow).

## Gestaltung & Hintergrund

Im Schritt „Gestaltung“ wählst du das Aussehen der Antwortkarten (weiß, kräftig bunt oder pastell), eine Akzentfarbe, die Buchstaben A, B, C … und die Schrift für Fragen und Antworten. Die Schriftgröße ist eine Höchstgröße: Längere Texte werden automatisch kleiner.

Im Schritt „Hintergrund“ gibt es vier Möglichkeiten:

- **Farbe** oder **Farbverlauf** (mit Vorschlägen, linear oder kreisförmig).
- **Bild** – hochladen oder suchen, danach den Ausschnitt festlegen.
- **Editor** – auf einer Farbe, einem Verlauf oder Bild ordnest du Texte, Bilder, Töne und eigene Zeichnungen frei an. Sie liegen auf allen Folien hinter den Fragen.

## Ablauf & Feedback

- **Rückmeldung nach jeder Frage:** „Überprüfen“ zeigt sofort, ob die Antwort stimmt – mit Ton, Erklärung und auf Wunsch der richtigen Lösung. Optional zwei Versuche (im zweiten Versuch halbe Punktzahl).
- **Rückmeldung erst am Ende:** Alle Fragen beantworten (auf Wunsch mit „Zurück“), dann gibt es das Ergebnis.
- **Fortschritt:** Balken, Punkte (grün/rot) oder Zahl.
- **Abschlusskarte:** Sterne, Punkte und Prozent, Übersicht aller Fragen (jede lässt sich noch einmal ansehen), „Falsche wiederholen“ und „Nochmal von vorn“.
- **Bewertung:** jede Frage ein Punkt; mit „Teilpunkte“ gibt es bei Mehrfachauswahl und Reihenfolge anteilige Punkte.

## Testen und speichern

„Testen“ startet das Quiz mit dem echten Player – auch in Tablet- und Handy-Größe. Mit „Ab Frage …“ beginnst du bei der gerade gewählten Frage.

- **HTML-Datei:** eine einzige Datei, läuft offline in jedem Browser und lässt sich in Quizsachen wieder öffnen und weiterbearbeiten. Zum Einbetten in mebis/Moodle führt dich „Einbetten in mebis/Moodle“ Schritt für Schritt zum fertigen iframe-Code.
- **SCORM-Paket (1.2):** für mebis/Moodle mit Punkten, bestanden/nicht bestanden, Antworten je Frage und Fortsetzen angefangener Versuche.
- **PDF-Arbeitsblatt:** alle Fragen mit Kästchen zum Ankreuzen bzw. Nummerieren, auf Wunsch mit Lösungsblatt.
- **Text:** im Quizsachen-Format, als GIFT für die Moodle-Fragensammlung oder im Aiken-Format.

## Speichern & Weiterbearbeiten

Quizsachen speichert das aktuelle Quiz automatisch in deinem Browser (nur auf diesem Gerät). Für ein zweites Quiz, zum Sichern oder Weitergeben: Datei-Menü → „Als HTML-Datei speichern“. Du bekommst eine HTML-Datei: Sie läuft in jedem Browser, lässt sich in Lernsachen-Heft einfügen, und „Öffnen …“ lädt sie wieder in den Editor. Das geht auch mit älteren JSON-Dateien.

Am Namen erkennst du, aus welcher App eine Datei stammt: „Titel (Quizsachen).html“, „(Schiebesachen)“, „(Textsachen)“ oder „(Heft)“ für Lernsachen-Heft. Öffnest du die Datei einer anderen App, sagt dir Quizsachen, wohin sie gehört.

> **Achtung:** Beim Löschen der Browserdaten geht das automatisch gespeicherte Quiz verloren. Sichere wichtige Quizze als Datei („Speichern“).

### Im Lernsachen-Heft

Im Lernsachen-Heft öffnet die Vorlage „Quiz“ Quizsachen direkt im Heft. Oben rechts stehen dann „Ins Heft übernehmen“ und „Abbrechen“. Bis das Quiz im Heft ist, speichert Quizsachen es als eigenen Entwurf – getrennt von dem Quiz, an dem du sonst in Quizsachen arbeitest. Wurde das Heft zwischendurch geschlossen, bietet Quizsachen beim nächsten neuen Quiz an, den Entwurf fortzusetzen. Weil die Seiten im Heft quer sind, gibt es dort nur die Formate 16:9 und 4:3 im Querformat.

### Tastenkürzel im Editor

- `Strg`+`Z` rückgängig, `Strg`+`Umschalt`+`Z` wiederholen
- In der Folienleiste: `Alt`+`←`/`→` verschiebt die gewählte Frage
- In der Vorschau: Pfeiltasten verschieben frei angeordnete Kästen und Hintergrund-Elemente
