# LaTeX-Lebenslaufvorlage

Ein einseitiger Lebenslauf auf Deutsch im A4-Format. Die Vorlage enthält Platzhalter und fiktive Beispiele für Bildungsweg, Berufserfahrung, Aktivitäten und Kenntnisse.

[PDF-Vorschau ansehen](lebenslauf-vorschau.pdf)

## In Overleaf bearbeiten

1. Ein leeres Projekt erstellen und den Inhalt der dortigen `main.tex` durch den Inhalt dieser [main.tex](main.tex) ersetzen.
2. Als Compiler **pdfLaTeX** auswählen und das Projekt kompilieren.
3. Die Platzhalter durch eigene Angaben ersetzen und das fertige PDF herunterladen.

## Lokal kompilieren

Du brauchst eine LaTeX-Installation wie TeX Live oder MiKTeX mit pdfLaTeX und den Paketen `geometry`, `hyperref`, `enumitem` und `lmodern`. Führe im Projektordner aus:

```sh
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

Das Ergebnis heißt `main.pdf`.

## Vorlage anpassen

- Im Kopfbereich Namen, Ort und Kontaktdaten ändern. Bei der E-Mail-Adresse sowohl das Ziel nach `mailto:` als auch den sichtbaren Text ersetzen.
- Ganze Blöcke unter Bildungsweg oder Berufserfahrung ergänzen, kürzen oder entfernen. `\hfill` richtet Ort und Zeitraum rechts aus.
- Vor dem Export prüfen, ob alle Platzhalter ersetzt sind und der Lebenslauf auf eine Seite passt.
