0) Les introduksjon til JavaScript på http://w3schools.com/js/js_intro.asp og svar på følgende
spørsmål, hva
kan JavaScript brukes til?


1) Les minst de to gitte linkene og forklar med dine egne ord forskjell på CSS id og class
elementer
http://www.tizag.com/cssT/cssid.php
http://csstricks.
com/thedifferencebetweenidandclass/

	CSS Klasse blir brukt hvis man ønsker å bruke formateringen på flere elementer.
	Dette er greit hvis man har mange sider hvor utseende skal være likt. Istedenfor å kopiere koden for
	designet, så kan man heller bruke klasser.
	CSS ID derimot brukes kun en gang. 


2) Vurder og sammenlign brukbarhet til versjoner i deloppgave 0 og deloppgave 1 av designet
for presentasjon av en liste (ta utgangspunkt at listen er mye lengre enn vist i skjermbildene,
over 100 elementer).

	begge er brukbare, men til forskjellig bruk. Hvis presentasjonen er hovedpoenget med siden
	så vil oppg 0 være best, men er det mye annen informasjon på siden vil det være bedre
	med en dropdown meny for å gjøre informasjonen oversiktlig. Ved bruk av over 100 elementer i 
	en liste kunne det kanskje vært smart å gi listen en mulighet for alfabetisk søk?


3) Med hvilken HTML teknikk og designløsning løser Wikipedia
(http://en.wikipedia.org/wiki/List_of_programming_languages) problemstilling med en lang liste
av programmeringsspråk?

	som nevnt i forrige oppgave vil en liste uten dropdown være en god løsning hvis listen er
	fokuset på nettsiden. Her tar de og i bruk alfabetisering for å dele opp innholde, som gjør
	det lettere for brukeren å navigere.


4) Ved å søke på WWW finn ut selv og forklar kort hva som er hovedforskjeller mellom et
<div> og et <span> element (tagg) i HTML.

	Begge brukes hvis man ønsker å style teksten som er imellom taggene. 
	Forskjellen er at <div> brukes for å style større menge innhol (block element).
	<span> brukes hvis man ønsker å endre en enkel linje, kanskje til og med inni
	en  <div> tag.(innline element)


5) Hvike brukbarhetsproblemer er det med den siste versjonen av implementeringen i
deloppgaven 2? Nevn gjerne hvordan man kunne løse problemene. (Tips: overlapp mellom
forskjellige grafiske elementer og tilfelle hvor man ønsker å selektere det første navnet på
programmeringsspårket i listen)

	Man kan opprette et element i listen som heter f.eks "ikke valgt" slik at det første språket man
	da kan velge blir element 2 i listen.


6) EKSTRA (bare for de spesielt interesserte): hvordan kunne man bruke URLene
som man
finner i Wikipedia’s artikkelen “List_of_programming_languages”, for å gjøre navnet på
programmeringsspråket i teksten “Du har selektert programmeringsspråket BASIC” til en
hypertext som peker til Wikipedia artikkelen (eller en annen WWWressurs)
med beskrivelsen
av dette språket? Linken åpnes i et nytt nettleservindu.