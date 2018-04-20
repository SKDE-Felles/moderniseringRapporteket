@title[Forside]
# Modernisering av Rapporteket
FMK NIKT HF, Gardermoen 23. april 2018
<br>
_Are Edvardsen_
<br>
<span style="font-size:0.4em;">Presentasjonen er åpen og tilgjengelig [her](https://gitpitch.com/SKDE-Felles/moderniseringRapporteket?p=presSoknadFMK#/)</span>

---

## Hvor i løypa?
![Difi prosjektveiviser](assets/difipv.png)

Note:
Et som viser hvor prosjektet er i forhold til fasene i prosjektveiviseren:  konsept, planlegge, gjennomføre, avslutte, realisere (ta i bruk) – gjerne med tidsangivelser
  
---
    
## Flytting til NHN (1/2)

- [NHN utredning av flytting april 2015](assets/NHN_utredning.pdf)
- IRS behandling av NHN utredning mai 2015 [sak 14-15](https://www.kvalitetsregistre.no/sites/default/files/mote_150610_saksframlegg.pdf)
- IRS behandling av flyttekostnader november 2015 [sak 33-15](assets/Mote_151125_saksframleggx.pdf)
- [FMK rapport om kostnader til AD-arbeidsgruppa mai 2016](assets/FMKkostnaderTilADarbgr.pdf)
- IRS orientering om diskrepans november 2016 [sak 49-16](https://www.kvalitetsregistre.no/sites/default/files/2016_11_30_referat_irs_godkjent.pdf)

Note:
Et som viser hva som er avtalt/forpliktet omkring flytting av Rapporteket til NHN, og hva som vil være de kostnadsmessige konsekvensene i forbindelse med en flytting (les: vil det være behov for ny finansiering som ikke allerede er besluttet)

---

## Flytting til NHN (2/2)

- [FMK revidert rapport om kostnader februar 2017](assets/FMKkostnader.pdf)
- IRS orientert om revidert FMK-rapport mars 2017 [referatsak 14-17](https://www.kvalitetsregistre.no/sites/default/files/2017_03_06_referat_irs_godkjent.pdf)
- IRS orientert av FMK om status flytting Rapporteket september 2017 [sak 43-17](https://www.kvalitetsregistre.no/sites/default/files/2017_09_17_referat_irs_godkjent.pdf)
- FMK orientert om risiko ved flytting og behov for modernisering oktober 2017 [sak 64/17](assets/RN-FlyttingavRapporteketfraHNIKTtilNHN-021017-1314.pdf)
- IRS orientert om risiko ved flytting desember 2017 [sak 58-17](https://www.kvalitetsregistre.no/sites/default/files/2017_12_14_referat_irs_godkjent.pdf)

Note:
Et som viser hva som er avtalt/forpliktet omkring flytting av Rapporteket til NHN, og hva som vil være de kostnadsmessige konsekvensene i forbindelse med en flytting (les: vil det være behov for ny finansiering som ikke allerede er besluttet)

---

## Driftskostnader etter flytting

- Bytte av driftsleverandør vil gi endring i pris
- Enhetspris anslått i [underlaget til kostnadsmodell](assets/FMKkostnaderTilADarbgr.pdf)
- Prisen er styrt av valgt "oppsett"
- Endelig "oppsett"" er et resultat av prosjektet

> Pt umulig å angi nøyaktig pris. Vedtatt kostnadsmodell tar høyde for kr 50.000 per register og år

Note:
Et som viser eventuell endring i driftskostnader etter at modernisering og flytting er gjennomført

---

## Fungerende dataleveranse: forutsetniger
- Alle data(formater) som [kan importeres i R](https://cran.r-project.org/doc/manuals/r-release/R-data.html) kan også benyttes av Rapporteket
- Dette gjelder både før og ev etter en modernisering
- Dataformat må være *formålstjenelig* (_e.g._ kroniske tilstander)
- Informasjon må være korrekt (både verdier og metadata)

---

## Fungerende dataleveranse: tiltak

> Spesifikasjon for å oppnå korrekte og formålstjenelige formater og innhold når data leveres til resulattjenester er under utarbeidelse av statistikernettverket i servicemiljøet

Note:
Et som viser til planlagt aktivitet om å utrede forutsetningene for at MRS-registre skal kunne bruke Rapporteket

---
    
## Status risiko (1/5)

|Id|Sårbarhet|Risiko|Mulige tiltak|
|---:|:---|---:|:---|
|1|Mangelfull finansiering av prosjektet|6|Avvente prosjektstart til finansiering er sikret|
|2|<s>Statistikere har ikke kapasitet til migrering av rapporter fra Jasper til Shiny</s>|<s>6</s>|<s>Øke kapasitet eller endre prioritering. Forlenge lisens for Jasper Server i ett år (ut 2019)</s>|

Note:
Et som viser gjenværende usikkerhet/risiko for gjennomføring og realisering

---

## Status risiko (2/5)
|Id|Sårbarhet|Risiko|Mulige tiltak|
|---:|:---|---:|:---|
|3|Statistikere har ikke kapasitet til migrering av R-rapporter til Shiny|6|Øke kapasitet eller endre prioritering|
|4|Manglende finansiering av "doble" lisenskostnader i overgangsfasen|4|Avvente prosjektstart til finansiering er sikret|

Note:
Et som viser gjenværende usikkerhet/risiko for gjennomføring og realisering

---

## Status risiko (3/5)

|Id|Sårbarhet|Risiko|Mulige tiltak|
|---:|:---|---:|:---|
|5|<s>Shiny Server er ikke egnet teknologi på Rapporteket</s>|<s>3</s>|<s>Avslutte prosjektet og ev finne annen teknologi</s>|
|6|Statistikere kan ikke filtre data ut fra brukerhåndtering i Shiny|3|Øke R-kompetanse|

---

## Status risiko (4/5)

|Id|Sårbarhet|Risiko|Mulige tiltak|
|---:|:---|---:|:---|
|7|<s>Statistikere har ikke kapasitet til å lære Shiny</s>|<S>3</s>|<s>Øke kapasitet eller endre prioritering</s>|
|8|Servicemiljøet er ikke i stand til å etablere og vedlikeholde brukergrensesnitt i Shiny|2|Dekkes gjennom kjøp av eksterne tjenester og/eller HNIKT|

---

## Status risiko (5/5)
|Id|Sårbarhet|Risiko|Mulige tiltak|
|---:|:---|---:|:---|
|9|Statistikere er ikke i stand til å håndtere "registernavigasjon" ut fra brukerhåndtering i Shiny|2|Øke R-kompetanse|

Note:
Et som viser gjenværende usikkerhet/risiko for gjennomføring og realisering


---
    
## Hva innebærer endringene for registrenes bruk av Rapporteket    
<!--
Et som viser «hva blir endringen» i forhold til registrenes bruk av Rapporteket (det vil bli enklere å utvikle rapporter…?)
-->    
---

## Forankring
- FMK
- IRS
- FRT
<!--
Et som viser forankringen av planene i Fagrådet for resultattjenester
-->

+++

<!-- This is the initial pres -->

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
