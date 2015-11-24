# LaTeX Template für das CAD/CAM-Seminar
Ein inoffizielles LaTeX-Template für das CAD/CAM-Seminar.

## How-To
1. Repository klonen oder herunterladen.
2. In der `ausarbeitung.tex` die Kopfdaten anpassen und den Inhalt einfügen.
3. Die `.tex`-Datei mit dem jeweiligen Editor kompilieren um die PDF zu erhalten.

## BibTeX aus Datei
Das Word-Template hat relativ strenge Anforderungen an die Formatierung der Quellen.
Da diese nur aufwendig mit LaTeX aus den BibTeX-Einträgen eingehalten werden kann, hab ich das ausgelassen und auf eine manuelle Eingabe gesetzt.
Falls aber doch jemand die automatisch generierten Einträge verwenden möchte, muss man lediglich den `thebibliography`-Block durch den folgenden Block ersetzen (auch nochmal in `ausarbeitung.tex` beschrieben):
```
\bibliography{bibliography}
\bibliographystyle{abbrv}
```
Daraufhin kann man eine `bibliography.bib`-Datei im Hauptverzeichnis anlegen und dort dann die BibTeX-Einträge reinpacken.