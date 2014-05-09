Rapport
==========================

Rapport for ServiciosDeVivienda, prosjektoppgave i programutvikling - HiOA

Rapporten skrives i LaTeX fordi
* Vi sparer tid
* Eksepel over kode blir lagt til i tekst og formatert
* Det blir pent formatert

[En god tutorial for LaTeX](http://en.wikibooks.org/wiki/LaTeX)

***
##Rapportstruktur
Strukturen i rapporten er definiert i [følgende fil](https://docs.google.com/document/d/1F9SR3I25yFMPApa8F2xsuQjYgwtAkmtV-niFmDJDfmk/edit?usp=sharing)
***

#Oppsett
Det som man trenger er:
1. LaTeX kompilator
2. Eventuelle tillegspakker (fesk for kodemarkering)
3. Vagfri texteditor

##Linux
* ~~Anbefalt editor [Kile](http://kile.sourceforge.net/)~~
* **Bruk [TexMaker](http://www.xm1math.net/texmaker/download.html)**
* Installer ~~Kile~~ TeXMaker via en pakkemanager som apt-get (ubuntu) eller yum (fedora) da vil de fleste pakker følge med som dependecies. Hvis det blir problem ved kompilering av tex filer søk etter følgende pakker (som er i bruk i rapporten)
  * babel (norsk)
  * parskip
  * titlepic
  * a4wide
  * listings
  
Se i **Rapport.tex** for komplett definisjon av alle pakker som brukes

##Mac
Har ingen erfaring men det finnes en LaTeX kompilator til Mac OS, [her finnes noen tips](http://guides.macrumors.com/Installing_LaTeX_on_a_Mac).

~~Det skal være mulig å installere Kile på Mac, men hvis det er mye jobb så finnes det LaTeX plugin til Eclipse eller [følgende editorer](https://discussions.apple.com/message/18653515#18653515).~~

Som editor **bruk [TexMaker](http://www.xm1math.net/texmaker/download.html)**

#Struktur
Rapporten består av **Rapport.tex** i denne inkluderes underfiler, for tilfedet er det **Fremside.tex** og ekesempelfil **Bruksanvisning.tex**. Allt her er også lagret som et Kile prosjekt så hvis man tar en **clone** så kan prosjektet åpnes direkte i Kile som det er. 
Bilder og kode finnes i respektive **./img/** samt **./kode/** i disse skal det være **en mappe per kapitel**, det er også tankten at vi skal oprette en ny *.tex fil per kapitel. Hvis det blir for "grovt" så kan vi jobbe med en fil per seksjon.
