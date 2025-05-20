[ 🇬🇧 English](/README-en.md)

# hyb-tud-thesis-starterkit


Dieses Repository enth#lt eine Sammlung von Vorlagen für Bachelor-, Master- und Praktikumsarbeiten, am Beispiel der Anforderungen der Hydrobiologie an der TU Dresden. Die Vorlagen können selbstverständlich auch für andere Studiengänge verwendet werden. Informiere dich bei deiner Betreuerin oder Betreuer nach den jeweils geltenden Regeln.

## Für eilige Microsoft Word-Nutzer

* Datei [template-praktikumsbericht-einfach.docx](https://github.com/tpetzoldt/hyb-tud-thesis-starterkit/raw/refs/heads/main/word/template-praktikumsbericht-einfach.docx) herunterladen und mit dem Schreiben anfangen.

## Warum dieses Repository?

* **Schneller Einstieg:** Spare Zeit und konzentriere dich auf den Inhalt deiner Arbeit, anstatt dich mit der Formatierung herumzuschlagen.
* **Konsistenz:** Gewährleiste eine einheitliche Gestaltung deiner Arbeit.
* **Flexibilität:** Die Vorlagen können an deine individuellen Bedürfnisse angepasst werden.
* **Open Source:** Teile deine Verbesserungen mit der Community und profitiere von den Beiträgen anderer.

Die Vorlagen basieren auf dem Corporate Design der TU Dresden (Word-Vorlage) bzw. dem LaTeX-Paket "TUD-Script" von Falk Hanisch (https://www.ctan.org/pkg/tudscr) und gewährleisten eine konsistente Gestaltung in Anlehnung an das Corporate Design der Universität.

## Welche Textverarbeitung verwenden?

Für deine Studienarbeiten stehen verschiedene Textverarbeitungsprogramme zur Auswahl. Hier sind einige Empfehlungen, die dir bei der Entscheidung helfen sollen:

### Microsoft Word

Wenn du mit Microsoft Word vertraut bist, kannst du einfach die entsprechende Word-Datei herunterladen und bearbeiten. Word ist weit verbreitet und bietet eine intuitive Benutzeroberfläche.

### LaTeX und Quarto für professionelles Layout

Für ein professionelleres Layout und zusätzliche Funktionalität sind LaTeX und Quarto hervorragende Optionen. 
Beide Systeme ermöglichen eine präzise Kontrolle über das Erscheinungsbild deines Dokuments.

**Quarto ist dabei das modernste System**

* Leicht zu lernen: Im Vergleich zu LaTeX ist Quarto einfacher und schneller zu erlernen.
* Reproduzierbar und portabel: Deine Dokumente lassen auf verschiedenen Systemen reproduzieren und teilen.
* Integration von R- und Python-Grafiken und Tabellen: du kannst R- und Python-Code direkt in dein Dokument einbetten, um Grafiken und Tabellen dynamisch zu erstellen. Das ist besonders nützlich, wenn du datenintensive Arbeiten schreibst.

**Wichtiger Tipp**

Besprich die Auswahl des Textprogramms unbedingt mit deiner Betreuerin oder deinem Betreuer. Sie können spezifische Empfehlungen geben und dich bei deinem gewählten Tool unterstützen.


## Welche Formatvorlage wofür?

* **Word-Vorlage:** 
    * Eine pragmatische Formatvorlage, basierend auf der Word-Vorlage des TU-Dresden CD (Corporate Design).
* **LaTeX-Vorlagen:** 
    * Konfigurierte LaTeX-Vorlagen, für Seminar- und Abschlussarbeiten 
    * `template-article-basic.tex` enthält ein Deckblatt, ist aber absichtlich einfach gehalten.
    * `template-tud-script.tex` basiert auf dem tud-script-Paket und enthält alle wesentlichen Elemente einer wissenschaftlichen Arbeit.
* **Quarto-Vorlagen:** 
    * Die Vorlage `template-quarto-basic` ist besonders einfach zu nutzen und benötigt nur R und Rstudio. Sie eignet sich gut, um mit dem Schreiben anzufangen. Ein Deckblatt kan später hinzugefügt werden.
    * Die Vorlage `template-quarto-koma-script.qmd` basiert auf der Artikelvorlage `scrartcl` aus dem KOMA-Script-Paket.
    * Die Vorlage `template-quarto-tud-script.qmd` basiert auf der tud-script LaTeX-Vorlage, ist aber einfacher zu nutzen und erlaubt die Einbettung von R-, Python- und Julia-Code. Sie enthält alle wichtigen Elemente einer wissenschaftlichen Arbeit (Deckblatt, Inhaltsverzeichnis, Abbildungsverzeichnis, Literaturverzeichnis).


## Installation der LaTeX und Quarto-Vorlagen

### Schritt 1: Lade die Dateien herunter.

* Lade das gesamte Repository oder einen Teil davon über den **Code**-Button als ZIP-Datei herunter.
* Experte: clone das Repository mit `git`.

**Wichtig:** 

Zusätzlich zur `template-*`-Datei sind bei LaTeX und Quarto gegebenenfalls 
weitere Dateien erforderlich. Deshalb bitte immer einen ganzen Ordner 
herunterladen.

* `tudcolors.sty`: Farbschemata der TU Dresden
* `apa.csl`: Bibliographie-Stil nach American Psychological Association (APA)
* `references.bib` ist ein Beispiel für eine Literaturdatenbank im BibTex-Format. 
Man kann sie von Hand erstellen oder aus einem Literaturprogramm exportieren, z.B. [Zotero](https://www.zotero.org/).
* Die Dateien `pdf-plot.pdf` und `mountains.jpg` sind Beispielgrafiken. 
Eigene Grafiken können auch in Unterverzeichnissen organisiert werden.

### Schritt 2: Installiere das TUD-Script-Paket

* Nicht erforderlich für die Word-Version und die Quarto-Basic-version.
* Voraussetzung für die Latex-Versionen und die Markdown-Versionen außer Quarto-Basic:
    * Installiere zunächst eine Tex-Umgebung, z.B. Texlive, Miktex oder tinytex
    * Nutze den Paketmanager von TexLive oder Miktex und installiere das Paket **tudscr**
    * Die Dokumentation dazu findet sich auf: https://github.com/tud-cd/tudscr
    
### Schritt 4: Öffne die Vorlagendatei

* Fertige eine Kopie der Vorlagendatei an (erkennbar an "template-" im Namen)
* Öffne die Datei in Word, TexStudio oder RStudio
* Lies die Hinweise im Template
* Beginne mit dem Schreiben

## Weitere Tipps

* Teile Deine Erfahrungen und sende Kommentare und Verbesserungsvorschläge an den Package-Maintainer
* Erstelle einen Fork des Repositories, modifiziere es nach Deinen Bedürfnissen und melde Verbesserungsvorschläge, z.B. als Pull-Request



Viel Erfolg!


