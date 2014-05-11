Rapport
==========================

Rapport for ServiciosDeVivienda, prosjektoppgave i programutvikling - HiOA

#Linker og referanser
[En god referanse for LaTeX](http://en.wikibooks.org/wiki/LaTeX)

[Anbefalt editor](http://www.xm1math.net/texmaker/download.html)
[Brukt TeX miljø](https://www.tug.org/texlive/)

[Preliminær rapportstruktur](https://docs.google.com/document/d/1F9SR3I25yFMPApa8F2xsuQjYgwtAkmtV-niFmDJDfmk/edit?usp=sharing)

#Struktur
Hovedfil er rapport.tex, denne innholder linker til alle kapitler, resterende filere finnes i **./tex/kappitelnavn/kapittelnavn.tex**, denne file innholder linker til underseksjoner i et kapitel. Filer tilhørende hvert kapitel finnes i mappe med samme navn som selve kapitelet, f.eks. **./tex/kappitelnavn/seksjon.tex**.
Bilder og kode finnes i respektive **./img/** samt **./kode/** i disse skal det være **en mappe per kapitel**, det er også tankten at vi skal oprette en ny *.tex fil per kapitel. Hvis det blir for "grovt" så kan vi jobbe med en fil per seksjon.

#LaTeX pakker
Foreløpig trenger du følgende TeX pakker for å kompilere rapporten (for aktuelle og oppdatert liste se rapport.txt:
```
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{lmodern}
\usepackage[norsk]{babel}
\usepackage{parskip}
\usepackage{graphicx}
\usepackage{titlepic}
\usepackage{a4wide}
\usepackage{enumitem}
\usepackage{color}
\usepackage{hyperref}
\usepackage{listings}
\usepackage[section]{placeins}
\usepackage{fancyhdr}
