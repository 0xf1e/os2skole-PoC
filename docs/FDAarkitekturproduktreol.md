# 🎓  Os2Skole
## Arkitekturprodukter


Dette dokument adresserer, hvordan en formaliseret rammearkitektur – som den fællesoffentlige Digital Arkitektur (FDA), kan implementeres pragmatisk i en iterativ open source udviklingsproces.

Arkitekturprodukter udstilles i et **åbent, versionsstyret repositorie**. Dokumentationen følger principperne i `FDA arkitekturreolen` og realiseres ved at beskrive diagrammer vha. `C4-modellen` og levere dem direkte i åbne versionstyrbare standard-formater som f.eks `Mermaid` i `Markdown`. Denne tilgang sikrer, at arkitekturbeskrivelserne er tæt integreret med koden og understøtter en hurtig, iterativ udvikling.

_En mere dybdegående beskrivelse af strategien for arkitekturcompliance er beskrevet seperat her: [Plamlagt arkitektur compliance](./arkitektur_compliance.md)_

<br>

## Arkitekturprodukter
Modeleret efter [FDA Arkitekturreolen](https://arkitektur.digst.dk/metoder/arkitekturmetoder/introduktion-til-retningslinjer-formidling-og-dokumentation-af-0#arkitekturreol)

<br>

|  | Konceptuel (Overbliksniveau) | Logisk (Designniveau) | Fysisk (Realiseringsniveau) |
| :--- | :--- | :--- | :--- |
| **Styring** | **Styringsrammer:** <br> - Governancemodel <br> - Forretningsmål <br> - Interessentanalyse <br> - Kvalitetsplan | **Fremgangsmåde:** <br> - Gevinstmodel <br> - Metodeanvendelse | **Relaliseringsforløb:** <br> - Ændringsanmodningslog <br> - Arkitekturbeslutningslog <br> - Deployment-/stagingplan |
| **Strategi** | **Vision og mål:** <br> - Vision / målbillede: <br> - Stretegiske kapabiliteter <br> - Udfordringer | **Målearkitektur (resumé):** <br> - [ ✅ Pricipper](https://github.com/OS2sandbox/os2skole-PoC/blob/main/docs/udviklings.manual_dk.md#principper) <br> - Arkitekturprincipper <br> - Arkitekturcompliance <br> - Målarkitektur-resumé <br> - Migreringsstrategi | **Løsningsarkitektur (resumé):** <br> - Løsningsarkitektur-resumé |
| **Jura** | **Juridiske rammer:** <br> - Juridiske bindinger | **Juridisk fortolkning:** <br> - Krav(samling) | **Juridisk praksis:** <br> - Databehandleraftaler <br> - Serviceaftaler (SLA) |
| **Sikkerhed** | **Sikkerhedsstandard:** <br> - Sikkerhedsstrategi / -mønstre <br> - Trussels- og risiskokatalog | **Sikkerhedsmodeller og regler:** <br> - Sikkerhedsmodel | **Sikkerhedskontrol:** <br> - Sikkerhedskontroller |
| **Opgaver** | **Forretningsstruktur:** <br> - Opgave- / servicekatalog <br> - Domænekatalog <br> - Proceslandskab | **Processer:** <br> - Aktør / roller <br> - Use case / user story <br> - Brugerrejse | **Arbejdstilrettelæggelse:** <br> - Arbejdsgang / -beskrivelse |
| **Information** | **Forretningsobjekter og begreber:** <br> - Centrale forretningsobjekter <br> - Begrebsliste / model | **Logiske datamodeller:** <br> - Informationsmodel <br> - Logisk datamodel <br> - Masterdata <br> - Datakvalitet | **Fysiske datamodeller:** <br> - Datasæt <br> - Dataudvekslingsformat |
| **Applikation** | **Applikationsstruktur og integrationsmønstre:** <br> - Systemlandskab / kontektsdiagram | **Applikationslandskab og integrationer:** <br> - Applikationslandskab / +integration <br> - Applikationer mappet til forretning og information | **Applikationsdesign og konfiguration:** <br> - Snitfladebeskrivelser <br> - Applikationsdesign <br> - Løsningskomponent <br> - Testscenarier |
| **Infrastruktur** | **Infrastrukturmønstre:** <br> - Infrastrukturkoncept og mønstre | **Infrastrukturlandskab:** <br> - Infrastrukturlandskab | **Infrastrukturkonfiguration:** <br> - Infrastrukturopsætning |
