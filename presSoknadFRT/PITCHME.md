@title[Forside]
# Modernisering av Rapporteket
Fagråd for resultattjenester, Gardermoen 17. april 2018
<br>
_Are Edvardsen_
<br>
<span style="font-size:0.4em;">Presentasjonen er åpen og tilgjengelig [her](https://gitpitch.com/SKDE-Felles/moderniseringRapporteket?p=presSoknadFMK#/)</span>

---

@title[Konseptfasen]
## Konsept
- Rapporteket konseptuelt uendret siden etablering
- Nye og endrede krav (_e.g._ flytting, funksjonalitet)
- Fortløpende behov for endring av teknologi og metodikk

<br>
@fa[rocket fa-3x fa-rhf]

+++

### Status
- Eneste fungerende resultattjeneste på mikrodata
- Benyttes av mange nasjonale registre
- Ingen "fornying" siden etablering 2011
- "Tungrodd" teknisk drift
- Tett kobling mellom teknisk drift og produksjon av innhold

<br>

@fa[battery-half fa-3x fa-rhf]

+++

### Behov
- Forenkling av teknisk drift
- Forenkling av innholdsproduksjon
- Klarere rollefordeling (innhold vs drift)
- Fornying av teknologi

<br>

@fa[wheelchair fa-3x fa-rhf]
+++

### Valg av konsept
- Innhold: rendyrking av det primære verktøyet __R__
- Teknisk drift: fjerne avhengigheter og vanskelig konfigurasjon
- Etablere delt forvaltning: teknologi og innhold

<br>

@fa[compass fa-3x fa-rhf]

+++

### Gevinster
- <span style="font-size:0.9em;">Enklere teknisk drift (oppgradering, konfigurasjon, integrasjon)</span>
- <span style="font-size:0.9em;">Flyttbar til annen driftsleverandør og bruk av skytjenester</span>
- <span style="font-size:0.9em;">Enklere for statistikere å etablere og vedlikehold innhold</span>
- <span style="font-size:0.9em;">Større fleksibilitet i hva som kan lages av innhold</span>
- <span style="font-size:0.9em;">Modernisering av teknologi og metodikk gir resultattjenesten forelenget levetid</span>

<br>
@fa[trophy fa-3x fa-rhf]

---

## Aktivitet
- Endriger omfatter både teknologi/programvare i driftsmiljø og innhold (rapporter) som eksisterer på Rapporteket i dag
- Identifisere god og delt forvaltning
- Arbeidet krever samarbeid mellom driftsleverandør og servicemiljøet 

+++

### Teknologi (HNIKT)
- Innføring av Shiny Server Pro
- Utfasing av Jasper Server Pro (TIBCO)
- Endring (forenkling) av konfigurasjon og rutiner for drift av Rapporteket
- Dokumentasjon
- Etablering av forvaltningsregime

+++

### Innhold (Servicemiljøet)
- Innføring av Shiny (R-pakke)
- GUI og brukerstyring i rapporter/datatilgang
- Migrering av eksisterende innhold fra R til R-Shiny
- Migrering av (innhold og ansvar for) eksisterende Jasper-rapporter til R-Shiny- Etablering av forvaltningsregime 

+++

### Økonomi
|Kilde|Beløp|
|:---|---:|
|FMK|454 580|
|Egenfinansiering Servicemiljøet|794 910|
|||
|Sum|1 249 490|




---



## Eierskap og styring
- Delt prosjekteierskap mellom HNIKT og Servicemiljøet
- Prosjekteier velger selv hvorvidt styringsgruppe for prosjektet skal etableres
- Prosjektledelse delt i to linjer
- Prosjektledere rapporterer til prosjekteier

---

## Referansegruppe
- Prosjektet er formelt sett ikke igang og referansegruppe er derfor ikke etablert
- Forespørsel om mulig deltagelse er gjort og samtlige helseregioner, Kreftregisteret og Norsk Helsenett vil være representert

---


@title[Kontekst]
## Historikk og framtid
Prosjektet _Modernisering av Rapporteket_ representerer et viktig bidrag for å videreføre og forbedre __Rapporteket__ som resultattjeneste for de nasjonale medisinske kvalitetsregistrene

<br>

@fa[history fa-3x fa-rhf]

+++

### Historie
|År|Hendelse|
|:---|:---|
|2009|Prototype Jasper Report Server CE og R|
|2011|Jasper Report Server Pro|
|2015|Utredning og vedtak om flytting til NHN|
|2015|Registre som R-pakker, kode på GitHub|
|2016|De første OQR-registre flyttes til NHN|
|2017|Høy risiko ved flytting av Rapporteket|

+++

### Framtid
|År|Hendelse|
|:---|:---|
|2018|Modernisering av Rapporteket|
|2019|Flytting av driftsansvar til NHN|
<br>
@fa[road fa-3x fa-rhf]

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

### Aktivitet finansiert av FMK
- Teknisk design og dokumentasjon
- Reise og hospitering KRG HNIKT
- Lisens Shiny Server Pro i etableringsfasen
- Intallasjon og konfigurasjon
- Testing
- Prosjektledelse

+++

### Egenfinansiert aktivitet
- Migrering rapporter fra Jasper til Shiny
- Migrering registre fra R til R-Shiny
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

@fa[coffee fa-5x fa-rhf]
