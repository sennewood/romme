# Spielregeln für Rommé

- Für Rommé gibt es eine Vielzahl an Varianten; dies ist meine.
- Unter **Releases** findet ihr immer die aktuellste PDF: https://github.com/sennewood/romme/releases


## Installation & Generierung

### MiKTeX installieren
1. Download der Portable-Edition: https://miktex.org/howto/portable-edition
1. Installation nach: `romme\miktex-x.y`

### PDF generieren
1. Ausführen von: `miktex-portable.cmd`
1. Rechtsklick auf das Taskbar-Icon und Auswahl von: `Terminal`
1. Zur Überprüfung folgenden Befehl ausführen: `pdflatex --version`
1. Änderungen durchführen.
1. Ausführen von: `pdflatex -quiet -aux-directory=R:\ns-aux\ -output-directory=R:\ romme.tex`
