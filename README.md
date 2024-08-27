# Vorlage für wissenschaftliche Arbeiten an der DHBW für WISEB

> [!CAUTION]
> Die Vorlage kann auf den ersten Blick etwas überwältigend wirken. Lernt am besten zuerst die Basics mit LaTeX und kommt dann auf dieses Repo zurück.
> 
> Für den Anfang empfehle ich euch, [Overleaf](https://de.overleaf.com/) für das Erstellen der Arbeit zu nutzen. Sobald ihr euch sicher fühlt, könnt ihr euch einen LaTeX Compiler herunterladen und die Arbeit lokal kompilieren.

Die Vorlage basiert auf diesem [Repository](https://github.com/pfisterer/DHBW_LaTeX_Template) und wurde leicht abgeändert.

Dieses Repo dient als *Hilfestellung* für wissenschaftliche Arbeiten. Unter Umständen kann der wissenschaftliche Betreuer, bzw. die korrigierende Person andere Anforderungen haben, die dieser Vorlage **nicht** gerecht werden. 

Meldet euch bei Fragen gerne bei mir oder bei euren Paten.

## Wichtig
- Alle Daten in *master.tex* anpassen (beginnt ab Zeile 112)
  - Falls Informationen nicht benötigt werden, löscht die jeweilige Zeile aus *titlepage.tex* (beginnt ab Zeile 19)
- Falls gewisse Abschnitte nicht benötigt werden (zB Abkürzungsverzeichnis, Kurzfassung etc.), löscht die jeweiligen *\input{}* Befehle aus *master.tex*
- Die Kapitel werden auf Dateien im Ordner *sections/* aufgeteilt
  - In *content/* befinden sich alle Dateien bzgl. des Inhalts (Einleitung, Kapitel 1, Kapitel 2 etc.)
  - In *form/* befindet sich alles andere, wie die ehrenwörtliche Erklärung, Anhänge, das *config* File etc.