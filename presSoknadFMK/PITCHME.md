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
|---:|:|
|2009|Første prototype Jasper Report Server CE og R|
|2011|Jasper Report Server Pro|
|2015|Registre som R-pakker og delt kode på GitHub|
|2015|Utredning og vedtak om flytting til NHN|
|2016|De første OQR-registre flyttes til NHN|
|2017|Redegjøresler for risiko ved flytting av Rapporteket|

+++

### Framtid
|År|Hendelse|
|:|:|
|2018|Modernisering av Rapporteket|
|2019|Flytting av driftsasvar til NHN|

---
@title[Kostnader]
## Økonomi
<span style="font-size:0.6em;">
- Hvert register skal potensielt kunne fange data fra EPJ i alle helseforetak
@fa[arrow-right]
<mark>
Må benytte samme metodikk og alle helseforetak må håndtere datautveksling likt
</mark>
<br>
- Behov for koordinering og styring av måten EPJ-ene samhandler med andre systemer
@fa[arrow-right]
<mark>
Krever nasjonal styring av regionale oppsett av EPJ
</mark>
</span>

+++

### Under

---

### Generelle forutsetninger for automastisk datafangst: utfordringer

#### Spørsmål:
- Hvilke nasjonale aktører (med styringrett) kan/bør koordinere regionenes arbeid med dataflyt fra/til (regionalt konsolidert) EPJ?
- Hvordan skal en slik koordinering foregå?
- Hva er tidsperspektiv i dette?

---

### Bidrag fra NSMK/SKDE: metadata
- <span style="font-size:0.9em;">Piloter for metadata fra kvalitetsregister til Eutro/Nestar (HRR)</span>
- <span style="font-size:0.9em;">Avstemming mot nasjonalt system/portal (*e.g.* HealthTerm)</span>
- <span style="font-size:0.9em;">(Nødvendig) Berikelse av metadata(felter)</span>
- <span style="font-size:0.9em;">Bistå implementering for alle kvalitetsregistre</span>

@fa[arrow-right]
<mark>
<span style="font-size:0.9em;">Målet er at alle nasjonale kvalitetsregistre fortløpende (automatisert) tilgjengeliggjør egne metadata til alle relevanter mottakere/portaler</span>
</mark>

---


### Bidrag fra NSMK/SKDE: harmonisering av variabler
- <span style="font-size:0.9em;">Gi nasjonal oversikt over variabler i kvalitetsregistrene</span>
- <span style="font-size:0.9em;">Bidra til samordning mot felles variabeldefinisjoner</span>
- <span style="font-size:0.9em;">Bidra til å innarbeide felles/standardiserte kodeverk og begreper/terminologier</span>
- <span style="font-size:0.9em;">Bidra til etablering/bruk av felles informasjonsmodeller som variabler kan "pakkes inn i"</span>

@fa[arrow-right]
<mark>
<span style="font-size:0.9em;">Målet er entydig utveksling av informasjon mellom system og mennesker samt automatisert mellom systemer</span>
</mark>

---

### NSMK/SKDE: egen status og vurdering
- Har fått oppdrag fra IRS angående metadata og harmonisering
- Pt store begrensninger i kapasitet
- Oppfatter stor risiko ved at implementering skjer nå (*e.g.* Dips Arena, Helseplattformen) mens fundamentet ikke er på plass (*e.g.* felles standarder)