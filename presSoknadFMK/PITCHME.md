@title[Forside]
# Modernisering av Rapporteket
FMK NIKT HF, Gardermoen 23. april 2018
<br>
_Are Edvardsen_
<br>
Presentasjonen er åpen og tilgjengelig [her](https://gitpitch.com/SKDE-Felles/moderniseringRapporteket?p=presSoknadFMK#/)

---

@title[Konseptfasen]
## Konsept
- Servicemiljøet, fordelt på 4 regionale helseforetak
- I alt 10 databehandlingsansvarlige (selvstendige juridiske enheter) for de 54 nasjonale kvalitetsregistrene

+++

### Status
- Eneste fungerende resultattjeneste på mikrodata
- Benyttes av mange nasjonale registre
- Ingen "fornying" siden etablering 2011
- "Tungrodd" teknisk drift
- Tett kobling mellom teknisk drift og produksjon av innhold

+++

### Behov
- Forenkling av teknisk drift
- Forenkling av innholdsproduksjon
- Klarere rollefordeling (innhold vs drift)
- Fornying av teknologi

+++

### Valg av konsept
- Innhold: rendyrking av det primære verktøyet __R__
- Teknisk drift: fjerne avhengigheter og vanskelig konfigurasjon
- Etablere delt forvaltning: teknologi og innhold

+++

### Gevinster
- Enklere teknisk drift (oppgradering, konfigurasjon, integrasjon)
- Flyttbar til annen driftsleverandør og bruk av skytjenester
- Enklere for statistikere å etablere og vedlikehold innhold
- Større fleksibilitet i hva som kan lages av innhold
- Modernisering av teknologi og metodikk gir resultattjenesten forelenget levetid 

---
@title[Kontekst]
## Historikk og framtid
Prosjektet _Modernisering av Rapporteket_ representerer et viktig bidrag for å videreføre og forbedre __Rapporteket__ som resultattjeneste for de nasjonale medisinske kvalitetsregistrene

+++

### Historie
|År|Hendelse|
|:---|:---|
|2009|Prototype Jasper Report Server CE og R|
|2011|Jasper Report Server Pro|
|2015|Registre som R-pakker og delt kode på GitHub|
|2015|Utredning og vedtak om flytting til NHN|
|2016|De første OQR-registre flyttes til NHN|
|2017|Redegjøresler for risiko ved flytting av Rapporteket|

+++

### Framtid
|År|Hendelse|
|:---|:---|
|2018|Modernisering av Rapporteket|
|2019|Flytting av driftsansvar til NHN|

---
@title[Kostnader]
## Oversikt prosjektkostnader
|Kilde|Beløp|
|:---|---:|
|FMK|454 580|
|Egenfinansiering Servicemiljøet|794 910|
|||
|Sum|1 249 490|

+++

### Aktiviet finansiert av FMK
- Design og dokumentasjon
- Reise og hospitering KRG
- Lisens Shiny Server Pro i etableringsfasen
- Intallasjon og konfigurasjon
- Testing
- Prosjektledelse

+++

### Egenfinansiert aktivitet
- Migrering rapporter fra Jasper til Shiny
- Migrering regisre fra R til R-Shiny
- GUI
- Brukerhåndtering i Shiny
- Prosjektledelse

+++

### Følgekostnader drift
<em>Gjennomføring av prosjeket vil IKKE gi økte kostnader for teknisk drift:</em>
- gjeldende kostnadsmodell forblir uendret
- årlig kostnad for teknisk drift av Rapporteket vil være ca. kr 70.000 per register uavhengig om drift skjer hos HNIKT eller NHN
- lisenskostnad for Shiny Server Pro er litt lavere enn for Jasper Server Pro
- forenklet teknisk drift vil gi redusert arbeidsomfang

---
@title[Bakside]
## Ferdig
@fa[flag-ceckered]