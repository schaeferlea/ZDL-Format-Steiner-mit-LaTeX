# ZDL-Format-Steiner-mit-LaTeX
Eine Pandoc-Lösung um LaTeX ins Steiner-Format (docx) zu konvertieren. Das hier ist ein erster Lösungsversuch. Überarbeitungen sind willkommen!

## Verwendung

1. Pandoc installieren (vgl. https://pandoc.org)
2. Terminal-Befehl: pandoc -f latex -t docx --reference-doc=steiner.dotm  --resource-path=.:figures --bibliography=sample.bib -o output.docx text.tex
3. Spaß haben mit LaTeX

## Noch nicht ideal
Händisch muss folgendes nachbearbeitet werden:
– Grafiken float-Umgebung
– ref-Nummerierung von Tabellen und Bildern
– nummerierte Beispiele erlauben leider keine gb4e/expex-Umgebunf
– Unschöne Lösung für Kapiälchen: Autornamen mit \textsc{} in .bib-Datei auszeichnen



