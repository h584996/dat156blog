# Blogg for DAT-156 Praksis i arbeidslivet

### Dette er en blogg som jeg kommer til å oppdatere 1 gang i uken(eller oftere) i mitt arbeid som praktikant hos FanaSparebank


## Fredag 24.09.21
Gikk gjennom eksisterende modaler på hjemmesidene og sørget for at alle skulle oppdateres ifht ny endring.
Jobbet også med modaler i et av administrasjonsverktøyene banken har laget og drifter selv.

Dagens keeping-together var en slags internvariant av bingo med hendelser som man evt har opplevd eller sett på arbeidsplassen de siste to ukene.

jeg jobbet fra 12:00-16:00


## Torsdag 23.09.21
Jobbet med en repository funksjon til et internt verktøy.
Leste PR ved ledig tid.
Var med på møte ang manuell testing og senere avdelingsmøte.

Jeg jobbet fra 08:00-16:00

## Onsdag 22.09.21
Gikk gjennom PR fra tidligere i uken.
Ved ledige tider ila dagen så jeg også litt gjennom en Kotlin tutorial.
Måtte lese litt og repetere litt bruk av Mock i et av prosjektene til banken.

Jeg jobbet fra 08:00-16:00


## Fredag 17.09.21
På dagen idag rakk jeg å gjøre en endring på nettsidene som omhandelt bruk av modaler i frontend.
Som vanlig på fredager hadde vi "Keeping Together" og idag hadde vi "Scattegories" som aktivitet.


## Torsdag 16.09.21
Leste mye PR og holdt på med tutorial for Episerver CMS stort sett hele dagen.

Jeg jobbet fra 08:00-16:00

## Onsdag 15.09.21
Som vanlig på onsdager gikk endel av dagen til å lese PR fra når jeg har vært borte. De gikk mye i back-end og controllere, samt endel tester.
Jeg fikk også inn endringer på hjemmesiden på banken. Der endret jeg på en modal for nettbankpåloggingen. Det var både styling og strukturelle endringer.

Innimellom fortsatte jeg også med tutorial som nevnt tidligere.

Jeg jobbet fra 08:00 - 16:00

## Fredag 10.09.21
Idag fikk jeg fullført de endringene jeg startet på igår, og fikk PR godkjendt.
Jeg fikk tildelt en ny oppgave der noe skulle endres på hjemmesidene og satte opp tasks, userstory og lagde oversikt for hvor og hvordan endringen skulle implementeres.

Jeg hadde hjemmekontor idag, da jeg reiste hjem til sunnmøre.
Det var noen problemer knyttet til hjemmekontoret da jeg skulle koble meg på en database til en løsning som vanligvis kobles på på internt på kontoret. Det løste seg heldigvis lett.

Jeg jobbet fra 08:15-13:00


## Torsdag 09.09.21
Idag fikk jeg være med på møte som handlet om gjennomgang av "Change management". Det er et dokument som skal forklare hvilke rutiner banken har for endringer av diverse it-løsninger.

Jeg jobbet også med noen oppgaver knytt til hjemmesidene til banken. Det var i hvoedsak styling-endringer. Samt å endre på en modul på en av nettsidene.

Jeg jobbet fra kl 07:30-15:30

## Onsdag 08.09.21
Idag gikk endel av dagen til møter. Vi hadde møte ang Bacheloroppgave. Vi hadde også statusmøte der alle i utviklingsteamet snakker om hva de jobber med nå, hva de har jobbet med den siste tiden og hva som skal jobbes med femover. Dette synes jeg er en veldig fin ting da man får vite litt om hva de andre sitteer å jobber med.
Idag gikk jeg også litt tidligere fra jobb da jeg mmåtte innom skolen.

Jeg jobbet fra kl 08:00-14:40

## Fredag 03.09.21
Idag leste jeg gjennom endel andre PR.
Jeg måtte også lese noe dokumentasjon for Episerver som brukes i en av bankens løsninger.
Senere starteg jeg også på tutorials for dette for å få et bedre innblikk av hvordan prosjektet er bygd opp og hvordan det fungerer.

Jeg jobbet fra kl 08:00-16:00


## Torsdag 02.09.21
Idag fortsatte jeg med supplerende tester for repository funksjonen fra igår og endret noe kode ifht tilbakemeldinger fra de andre.
Jeg måtte også lære meg endel om mocking i testene. Dette er noe vi bruker for å kunne kalle på enkelte metoder og få et bestemt svar tilbake. Når det gjelder testing av service funksjoner til forskjellige repository funksjoner mocker vi gjerne tilbakemeldingen av de kallede funksjonene fra repo slik at vi kan konsentrere oss om å teste den faktiske servicemetoden.

Jeg jobbet fra kl 08:00-16:00

## Onsdag 01.09.21
Idag skrev jeg for det meste tester for en repositoryfunksjon. I tillegg leste jeg over og godkjendte PR fra de andre utviklerene.

Jeg var også med på en gjennomgang av OCS som vi har i nettbanken. OCS er som en informasjonsboks som dukker opp for et utvalg av brukere og kan informere om tips, avtaler eller andre ting.

Jeg jobbet fra kl 07:50-16:00


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
