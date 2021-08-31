# Blogg for DAT-156 Praksis i arbeidslivet

### Dette er en blogg som jeg kommer til å oppdatere 2 ganger i uken(eller oftere) i mitt arbeid som praktikant hos FanaSparebank


## Fredag 27.08
Idag fikk jeg implementert controller-en som skal kalle repository funksjonen i anonymiseringsløsningen. Det mangler fortsatt noe testing på repository og controller, men jeg har skrevet ferdig tester for Utility-klassen.

I slutten av dagen presenterte jeg også anonyiseringsløsningen for min nærmeste leder og hadde muntlig gjennomgang og forklaring av kodenendringene som ble lagt til.

Pga at vi hadde møte på en gjennomgang av en endring i en av bankens løsninger jobbet jeg idag fra 08:00-16:00.


## Torsdag 26.08
Idag fikk jeg fullført PR på repository funksjonen. Når dette skulle merges opp til master branch feilet build prosessen. Siden alle som skal jobbe på dette prosjektet brancher ut fra master er det ganske kritisk at master fungerer slik som den skal.
Grunnen til feilen var at jeg hadde jobbet på to forskjellige brancher i samme klasse. Siden jeg ikke hadde jobbet på akkurat samme plass i koden fikk jeg ikke opp varsel om konflikt før merge. Problemet var at jeg hadde endret en variabel til å bruke en klasse property istedenfor. Løsningen var derfor enkel med å bare endre fra bruk av variabel til bruk av property.

Dette viser viktigheten av å være nøyaktig når man jobber på brancher og at man helst bør gjøre endringer på samme plass i en branch og ikke to. Spesielt er de lett å glemme små detaljer når man jobber med det noen dager etterpå.

Idag hadde vi også statusmøte med Utviklerene òg avdelingsmøte med alle på Teknologi og Innovasjon.

Jeg jobbet fra 08:00-16:00

## Onsdag 25.08
Idag hadde vi møte med veileder.
Videre gikk dagen på å jobbe med tilbakemeldinger og utbedringer fra funksjonen som ble laget på fredag. I tillegg måtte jeg sette opp en testklasse for tester til en "Utilities" klasse som jeg bruker i repository. Dette er for å sikre at funksjonen gjør det som er tenkt, og at den kan takle scenarioer med tom string og null som input uten å knekke funksjonalitet.

Jeg jobbet fra 08:00-16:00

## Fredag 20.08
Dagen i dag gikk til å sette opp en funksjon i et Repository. Alle de siste arbeidsoppgavene er i tråd med Kravspesifiseringen som ble gjort tidligere.
På fredager har vi også noe som kalles "Keeping together". Det er et sosialt arrangement som alle på avdelingen er med på. Dette kom som et tiltak for å holde kontakt med medarbeidere selv når alle satt på hejmmekontor under lockdown. De går ut på at en gruppe på avdeleingen feks Utvikling lager et underholdende opplegg på en halvtime. Et eksempel er at vi hadde en digital versjon av rykte går og ble delt opp i mindre grupper på ca 6stk på teams.

Jeg jobbet fra 08:00-16:00


## Torsdag 19.08
De kodeendringene som jeg programmerte igår hadde endel feil i logikk som jeg måtte utbedre. Mesteparten av dagen gikk til å gå gjennom kommentarer på Pull Requesten og diskutere og implementere endringer i koden. Mye av det som var feil handlet om min begrensede erfaring med Databasehåndtering og oppsett for dette.

Jeg jobbet fra 07:45-16:00

## Onsdag 18.08
Idag har jeg endret på de arbeidsoppgavene som jeg satte opp på mandag. Etter tilbakemeldinger fra andre på jobb har jeg fått gode innspill til hvordan jeg kunne forbedre arbeidsoppgavene som jeg hadde satt opp. Jeg har ogå tegnet opp programflyt for kodeendringen som jeg skal gjennomføre. Iløpet av dagen fikk jeg også programmert inn første delen av arbeidsoppgavene som jeg satte opp.

Jeg jobbet fra 08:00-17:15

## Tirsdag 17.08
Idag har jeg og hun andre som er i praksis hos FanaSparebank jobbet sammen på en oppgave. Oppgaven vi jobbet med var i utgangspunktet bare enkle endringer i et frontendprosjekt, men siden prosjektet er ganske stort og innviklet så endte vi opp med å bruke hele dagen på denne oppgaven. Dette står i kontrast til en typisk studieverdag der vi gjerne jobber med prosjekter av begrensede størrelser.

Jeg jobbet fra 08:00-16:00

## Mandag 16.08
Dagen idag har gått til å skrive tester og sette opp arbeidsstruktur for kravspesifikasjonen jeg lagde før helgen. I tillegg til dette har jeg lest endel PR på FrontEnd prosjekter da jeg har jobbet mye med Backend i det siste.

Jeg jobbet fra 07:30-16:00

## Fredag 13.08
Jeg fikk tilbakemeldinger på kravspesifikasjonen og jobbet for det meste med videreutviklingen av denne og godkjenning av ulike PR.

Jeg jobbet fra 08:00-16:00

## Torsdag 12.08
Jeg startet dagen med kaffi og PR. Siden PR av og til kan være vanskelig å forstå kan vi i verktøyet som benyttes av banken (Azure DevOps) legge inn kommentarer å be den som har pushet koden om mer forklaring eller kommentarer. Idag leste jeg nettopp en slik PR som jeg trengte litt ekstra forklaring for å forstå. Siden jeg er ny i endel prosjekter er det ofte jeg må spørre om diverse funksjoner i koden.

Senere på dagen skrev jeg mitt første kravSpec!
KravSpec er i dette tilfellet en spesifisering av en kodeendring som skal gjøres. Da må man blandt annet presisere hva som skal gjøres, hvorfor og hvordan, og deretter presentere dette for de andre på utvikling for innspill.

Jeg jobbet fra 07:30-16:30

## Onsdag 11.08
Dagen idag har gått ut på å skrive flere Unit-tester for samme prosjekt som igår itillegg til mer parprogrammering.

Jeg jobbet fra 08:00-16:30

## Tirsdag 10.08
Idag gikk dagen frem til kl 12:00 til å reise å ta Covid test.
Når jeg fikk logget på hjemmekontoret var dagens oppgaver å lese mer Pull Request(heretter PR) i tillegg til å parprogrammere tester til en intern løsning her hos banken.

På grunn av at jeg mistet noen timer idag, skal jeg jobbe litt mer i noen av de kommende dagene for å hente inn de timene.

Jeg jobbet fra 12:00-16:00

## Mandag  09.08
Idag var første dag tilbake fra ferie. Siden jeg har jobbet deltid hos FanaSparebank en stund nå handlet dagen idag mest om å lese e-post og Pull Request som har kommet i tiden jeg har vært på ferie. Pga jeg hadde hatt kontakt med endel familiemedlemmer den siste tiden hadde jeg ogå hjemmekontor. Dette skulle vise seg å være et smart valg da jeg senere på kvelden fikk vite at jeg hadde vært nærkontakt til en som testet positivt for Covid-19.

Jeg jobbet fra 08:00-16:00
