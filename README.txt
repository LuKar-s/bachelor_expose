Anmerkungen:

0.) Diese Dokument ist eine mögliche Grundlage für ein Exposé; die Verwendung des Dokuments ist nicht verpflichtend. Das Dokument kann auch an die eigenen Anforderungen angepasst werden. 

1.) Das Dokument verwendet die Dokumentenklasse "article" (bzw. die konkrete Variante "scrartcl" aus dem Paket Koma-Script). Für ein Exposé ist das in Ordnung, für eine Bachelor- oder Masterarbeit ist die Klasse "book" oder eine Variante wie "scrbook" besser geeignet.

2. Für die Literaturliste habe ich biber (statt bibtex) verwendet. Als Kommando für das vollständige Übersetzen des Projekts (also Text + Literatur) verwende ich:

"pdflatex" -synctex=1 -interaction=nonstopmode %.tex|"biber" %|"pdflatex" -synctex=1 -interaction=nonstopmode %.tex|"pdflatex" -synctex=1 -interaction=nonstopmode %.tex|open %.pdf

3.) Es wird kein Support geboten, bei Fragen also bitte an das Internet wenden ;-)

Viele Grüße und viel Spaß mit der Vorlage,
Thorsten Teschke
