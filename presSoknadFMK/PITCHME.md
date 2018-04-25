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

## Fungerende dataleveranse: forutsetninger
- Alle data(formater) som [kan importeres i R](https://cran.r-project.org/doc/manuals/r-release/R-data.html) kan også benyttes av Rapporteket
- Dette gjelder både før og ev etter en modernisering
- Dataformat må være *formålstjenlig* (_e.g._ kroniske tilstander)
- Informasjon må være korrekt (både verdier og metadata)

---

## Fungerende dataleveranse: tiltak

- Spesifikasjon for å oppnå korrekte og formålstjenelige formater og innhold når data leveres til resulattjenester er under utarbeidelse av statistikernettverket i servicemiljøet

- FMK vertskap for koordinering mlm statistikere og tekniske leverandører

Note:
Et som viser til planlagt aktivitet om å utrede forutsetningene for at MRS-registre skal kunne bruke Rapporteket

---
    
## Status risiko (1/5)

|Id|Sårbarhet|Risiko|Mulige tiltak|
|---:|:---|---:|:---|
|1|Mangelfull finansiering av prosjektet|<span style="color:red">6</span>|Avvente prosjektstart til finansiering er sikret|
|2|<s>Statistikere har ikke kapasitet til migrering av rapporter fra Jasper til Shiny</s>|<s><span style="color:red">6</span></s>|<s>Øke kapasitet eller endre prioritering. Forlenge lisens for Jasper Server i ett år (ut 2019)</s>|

Note:
Et som viser gjenværende usikkerhet/risiko for gjennomføring og realisering

---

## Status risiko (2/5)
|Id|Sårbarhet|Risiko|Mulige tiltak|
|---:|:---|---:|:---|
|3|<s>Statistikere har ikke kapasitet til migrering av R-rapporter til Shiny</s>|<s><span style="color:red">6</span></s>|<s>Øke kapasitet eller endre prioritering</s>|
|4|Manglende finansiering av "doble" lisenskostnader i overgangsfasen|<span style="color:#ffcc00">4</span>|Avvente prosjektstart til finansiering er sikret|

Note:
Et som viser gjenværende usikkerhet/risiko for gjennomføring og realisering

---

## Status risiko (3/5)

|Id|Sårbarhet|Risiko|Mulige tiltak|
|---:|:---|---:|:---|
|5|<s>Shiny Server er ikke egnet teknologi på Rapporteket</s>|<s><span style="color:#ffcc00">3</span></s>|<s>Avslutte prosjektet og ev finne annen teknologi</s>|
|6|Statistikere kan ikke filtre data ut fra brukerhåndtering i Shiny|<span style="color:#ffcc00">3</span>|Øke R-kompetanse|

---

## Status risiko (4/5)

|Id|Sårbarhet|Risiko|Mulige tiltak|
|---:|:---|---:|:---|
|7|<s>Statistikere har ikke kapasitet til å lære Shiny</s>|<s><span style="color:#ffcc00">3</span></s>|<s>Øke kapasitet eller endre prioritering</s>|
|8|Servicemiljøet er ikke i stand til å etablere og vedlikeholde brukergrensesnitt i Shiny|<span style="color:lime">2</span>|Dekkes gjennom kjøp av eksterne tjenester og/eller HNIKT|

---

## Status risiko (5/5)
|Id|Sårbarhet|Risiko|Mulige tiltak|
|---:|:---|---:|:---|
|9|Statistikere er ikke i stand til å håndtere "registernavigasjon" ut fra brukerhåndtering i Shiny|<span style="color:lime">2</span>|Øke R-kompetanse|

Note:
Et som viser gjenværende usikkerhet/risiko for gjennomføring og realisering


---
    
## Effekter av endringer 

- Ingen rapporter lages av IKT-leverandør
- Ingen betaling for utvikling av innhold
- Alt innhold utvikles av egne statistikere og/eller servicemiljøet
- Utvikling av innhold mer rendyrket __R__
- Nytt brukergrensesnitt
- Rikere presentasjon og dynamikk 

Note:
Et som viser «hva blir endringen» i forhold til registrenes bruk av Rapporteket (det vil bli enklere å utvikle rapporter…?)
  
---

## Forankring
Plan presentert for Fagråd resultattjenester 17. april 2018 med følgende innspill:
- etablér nasjonal styringsgruppe for prosjektet 
- avhengighet til fungerende dataleveranser også for registre som ikke er på OpenQReg
- MRS-R sensitiv legges på is og Rapporeket er (fortsatt) eneste tilgjengelige resultattjeneste på "microdata"

Note:
Et som viser forankringen av planene i Fagrådet for resultattjenester


---

@title[Bakside]

@fa[coffee fa-5x fa-rhf]