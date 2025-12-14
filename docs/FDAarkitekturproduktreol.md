# 🎓  Os2Skole
## Arkitekturprodukter


Dette dokument adresserer, hvordan en stor, formaliseret rammearkitektur – som den fællesoffentlige Digital Arkitektur (FDA), inspireret af `TOGAF` – kan implementeres pragmatisk i en `open source iterativ udviklingsproces`.

Arkitekturprodukter udstilles i et **åbent, versionsstyret repositorie**. Dokumentationen følger principperne i `FDA arkitekturreolen` men realiseres ved at beskrive diagrammer vha. `C4-modellen` og kode dem direkte i `Mermaid` i `Markdown`. Denne tilgang sikrer, at arkitekturbeskrivelserne er tæt integreret med koden og understøtter en hurtig, iterativ udvikling.

<br>

## Arkitekturprodukter
Modeleret efter [FDA Arkitekturreolen](https://arkitektur.digst.dk/metoder/arkitekturmetoder/introduktion-til-retningslinjer-formidling-og-dokumentation-af-0#arkitekturreol)

<br>

|  | Konceptuel (Overbliksniveau) | Logisk (Designniveau) | Fysisk (Realiseringsniveau) |
| :--- | :--- | :--- | :--- |
| **Styring** | **Styringsrammer:** <br> - Governancemodel <br> - Forretningsmål <br> - Interessentanalyse <br> - Kvalitetsplan | **Fremgangsmåde:** <br> - Gevinstmodel <br> - Metodeanvendelse | **Relaliseringsforløb:** <br> - Ændringsanmodningslog <br> - Arkitekturbeslutningslog <br> - 💡[1] *Deployment-/stagingplan* |
| **Strategi** | **Vision og mål:** <br> - Vision / målbillede: <br> - Stretegiske kapabiliteter <br> - Udfordringer | **Målearkitektur (resumé):** <br> - [ ✅ Pricipper](https://github.com/OS2sandbox/os2skole-PoC/blob/main/docs/udviklings.manual_dk.md#principper) <br> - Arkitekturprincipper <br> - Arkitekturcompliance <br> - Målarkitektur-resumé <br> - Migreringsstrategi | **Løsningsarkitektur (resumé):** <br> - 💡[2] *Løsningsarkitektur-resumé* |
| **Jura** | **Juridiske rammer:** <br> - Juridiske bindinger | **Juridisk fortolkning:** <br> - Krav(samling) | **Juridisk praksis:** <br> - Databehandleraftaler <br> - 💡[3] *Serviceaftaler (SLA)* |
| 🔍[1] **Sikkerhed** | **Sikkerhedsstandard:** <br> - 💡[4] *Sikkerhedsstrategi / -mønstre* <br> - 🔍[2] Trussels- og risikokatalog | **Sikkerhedsmodeller og regler:** <br> - Sikkerhedsmodel | **Sikkerhedskontrol:** <br> - 💡[5] *Sikkerhedskontroller* |
| **Opgaver** | **Forretningsstruktur:** <br> - 🔍[3] Opgave- / servicekatalog <br> - Domænekatalog <br> - Proceslandskab | **Processer:** <br> - Aktør / roller <br> - 💡[6] *Use case / user story* <br> - 💡[7] *Brugerrejse* | **Arbejdstilrettelæggelse:** <br> - 💡[8] *Arbejdsgang / -beskrivelse* |
| **Information** | **Forretningsobjekter og begreber:** <br> - Centrale forretningsobjekter <br> - Begrebsliste / model | **Logiske datamodeller:** <br> - 💡[12] *Informationsmodel* <br> - Logisk datamodel <br> - Masterdata <br> - Datakvalitet | **Fysiske datamodeller:** <br> - Datasæt <br> - Dataudvekslingsformat |
| **Applikation** | **Applikationsstruktur og integrationsmønstre:** <br> - Systemlandskab / kontektsdiagram | **Applikationslandskab og integrationer:** <br> - 💡[9] *Applikationslandskab / +integration* <br> - Applikationer mappet til forretning og information | **Applikationsdesign og konfiguration:** <br> -  Snitfladebeskrivelser <br> -  Applikationsdesign <br> - 💡[10] *Løsningskomponent* <br> - Testscenarier |
| **Infrastruktur** | **Infrastrukturmønstre:** <br> - Infrastrukturkoncept og mønstre | **Infrastrukturlandskab:** <br> - Infrastrukturlandskab | **Infrastrukturkonfiguration:** <br> - 💡[11] *Infrastrukturopsætning* |


Items where we have some information that we can refer to are marked with a 💡:

💡[1] My CI/CD pipeline diagram, and I might also have some info in my initial summary 
ttps://github.com/0xf1e/os2skole-PoC/blob/updated-architecture-progress/docs/deployment.md -- the deployment process in the second diagram, and the different environments in the first diagram. Also this: https://github.com/0xf1e/os2skole-PoC/blob/updated-architecture-progress/docs/deployment.md  
**Potential Action Items:** TBD

💡[2] My initial description of the architecture: https://github.com/0xf1e/os2skole-PoC/blob/updated-architecture-progress/docs/architecture.md#automated-testing-and-cicd  
**Potential Action Items:** TBD

💡[3] Our text about non-technical requirements: https://github.com/0xf1e/os2skole-PoC/blob/updated-architecture-progress/docs/non_functional_requirements.md -- here we can replace all specific numbers with placeholders. Note that I have notes from a call with minor updates that I haven't uploaded yet.
**Potential Action Items:** TBD

💡[4 or 5] The requirements that I have described in the example install: https://github.com/0xf1e/os2skole-PoC/blob/updated-architecture-progress/docs/deployment.md#infrastructure-architecture -- in this diagram we can turn the specific technology blocks into generic design principles
**Potential Action Items:** TBD

💡[6] Notes from our user story session: This issue describes the progress we've made so far in creating high-level user stories https://github.com/OS2sandbox/os2skole-PoC/issues/23
**Potential Action Items:** TBD

💡[7] Our Sample Student story from the workshop: This currently lives in a spreadsheet on an internal data drive.
**Potential Action Items:** TBD

💡[8] My summary after my meeting with Jan about iterative work: https://github.com/OS2sandbox/os2skole-PoC/issues/23#issuecomment-3596994415 - also the open questions listed in these issues: https://github.com/OS2sandbox/os2skole-PoC/issues/33  https://github.com/OS2sandbox/os2skole-PoC/issues/34 https://github.com/OS2sandbox/os2skole-PoC/issues/36 
**Potential Action Items:** TBD

💡[9] This is information that we have collected for Zangenberg's cost estimate. It is currently in a spreadsheet on an internal data drive. The interactions between the components (which comprise most of the development work) is also reflected in this diagram as relations between components: https://github.com/0xf1e/os2skole-PoC/blob/updated-architecture-progress/docs/architecture.md#os2skole-infrastructure-overview
**Potential Action Items:** TBD

💡[10] The same spreadsheet also contains a list of the components that we would be ordering. The components are reflected in my diagrams as component blocks. Zangenberg has also, in their final presentation, listed the components of the system and their assessment of the work required. I am unsure if Zangenberg's presentation has been published.
**Potential Action Items:** TBD

💡[11] This is information that is implied by the diagrams https://github.com/0xf1e/os2skole-PoC/blob/updated-architecture-progress/docs/diagrams/architecture.png and https://github.com/0xf1e/os2skole-PoC/blob/updated-architecture-progress/docs/diagrams/files_deployment_from_vendors_perspective.png. As in [4/5], the specific implementations that I have listed can be rewritten into a diagram of the concerns that those impelmentations address.
**Potential Action Items:** TBD

💡[12] Note the work taking place in this issue: https://github.com/OS2sandbox/os2skole-PoC/issues/32. Also, my high-level view diagram provides some clues on the way, information is moving in the system: https://github.com/0xf1e/os2skole-PoC/blob/updated-architecture-progress/docs/diagrams/architecture.png
**Potential Action Items:** TBD

This document might contain more information on what KL are hoping to see in diagrams: https://arkitektur.digst.dk/Vejledning-til-arkitekturdokumentation-med-Archimate

Items where I think that we should look more closely into them are marked with a 🔍:

🔍[1] I wasn't sure where to place it in the security domain, but I think we are missing some workflows related to ensuring a secure system. Like: Are we going to run regular penetration testing? Also: We expect suppliers to act NIS2 and CRA compliant, but we might want to have a process to ensure that their promises and documentation actually mean something. Both NIS2 and CRA are new, and there are going to be substantial differences in how peopole interpret them.
**Potential Action Items:** TBD

🔍[2] I don't think it makes sense to define these right at the start of the project, but we should probably introduce a regular threat modeling as part of our sprints.
**Potential Action Items:** TBD

🔍[3] I think that this point is related to Henrik's original request to us: "[en] overbliksfigur i forbindelse med indkøb/udbud; skal afspejle hovedbestanddelene i OS2skole-platformen (login, datakilder, test bla-bla-bla-bla), samt afspejle hvilke elementer, som skal kodes, og hvilke der blot skal konfigureres;" How many different solutions are we going to procure? How are we going to describe the deliverables we expect from them?
**Potential Action Items:** TBD

**Potential immediate next steps:**
- Refining the TOGAF mapping: I'm struggling with the TOGAF language that is used in the Architecture Framework. The mapping of existing work to TOGAF items could probably be refined. 
- Developing an Agile Documentation Strategy: We need a strategy to work around the framework's desire around static waterfall descriptions. My input: I am thinking one way to "hack" the framework is to provide *process descriptions*. Maybe even something inspired by BPM notation. 
- Contextualizing and extending the current diagrams: My diagrams currently describe example implementations of certain business needs. Basically my process has been that I need to paint a sketch of the full system in front of me, so I can better envision where things are headed, how parts are interacting, and which risks are ocurring. I believe that there is a lot of useful information in my work, but this context has to be clearly communicated. I can also describe the business needs that are being addressed more explicitly.

What do you think about those next steps? Where you do see the most value when it comes to having this information ready for our meeting on Monday?
