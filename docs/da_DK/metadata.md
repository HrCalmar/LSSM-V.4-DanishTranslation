---
title: Metadata
lang: da_DK
sidebarDepth: 0
---

# Indsamling af brugerens metadata

Ved at bruge `LSSM` (Leitstellenspiel Manager, userscript til browseren) accepterer brugeren, at metadata vil blive indsamlet. Følgende data vil blive gemt:

-   Unik bruger-ID
    -   Inklusive unik Secret (unik, ikke-offentlig tegnstreng til identifikation)
-   Brugernavn
-   Antal bygninger
-   Anvendt browser
    -   Inklusive version
-   Tidspunkt for metadata-indsamling
-   Aktiverede moduler
-   Spillets sprogversion
    -   Inklusive information om, hvorvidt politiversionen (hvis tilgængelig) er valgt eller ej
-   Hvilken korttype der er aktiveret (OSM eller Mapkit)
-   LSSM-version
-   LSSM-gren (`stable`, `beta` eller en forhåndsvisningsgren)
-   Version af det installerede LSSM-userscript

Disse data bruges til at forbedre udvidelsen samt til at styre udviklingen af eksisterende eller fremtidige moduler.
De danner også grundlaget for spændende statistikker, som f.eks. kan offentliggøres som nyheder (for mere information, se [nedenfor](#offentliggørelse-af-statistikker)).

**Brugeren kan til enhver tid (de-)aktivere indsamlingen af disse data i [indstillingerne][docs.settings].**

**En sletning af allerede indsamlede data kan anmodes om når som helst ved at sende en besked til udviklerne via en af de metoder, der er opført i [support][docs.support], eller ved at sende en uformel e-mail til `developer[at]lss-manager.de`.**

Hver gang hovedsiden af spillet åbnes, sendes telemetridata (hvis aktiveret) til LSSM-serveren.
Hvis der allerede findes en dataregistrering for brugeren, vil den blive overskrevet – en historik over individuelle data gemmes ikke.
Hvis en dataregistrering ikke har modtaget en opdatering i mere end 6 måneder, slettes den automatisk.

## Offentliggørelse af statistikker

Følgende telemetristatistikker kan offentliggøres af LSSM-teamet:

-   Samlet antal aktuelle telemetri-registreringer for følgende tidsperioder:
    -   De seneste 6 måneder
    -   De seneste 30 dage
    -   De seneste 7 dage
    -   De seneste 24 timer
    -   Dagens kalenderdato ifølge tysk tid
-   Antal telemetri-registreringer fra brugere med eller uden premium-konto
-   Antal telemetri-registreringer pr. sprogversion
    -   Inklusive opdeling i politiversion og "normal" version, hvis tilgængelig
-   Antal telemetri-registreringer pr. browser
    -   Inklusive opdeling i hovedversion af browseren, f.eks. kombineres "Firefox 100.3" og "Firefox 100.4" som "Firefox 100".
-   Antal telemetri-registreringer pr. korttype
-   Antal telemetri-registreringer pr. LSSM-version
-   Antal telemetri-registreringer for hver af de tilgængelige moduler.

Slutning til individuelle registreringer er **ikke** mulig gennem disse statistikker.

## Indsamling af metadata fra tredjepartsudbydere

LSSM anvender ikke nogen værktøjer, biblioteker, hjælpeprogrammer eller lignende, der kunne indsamle metadata fra brugerne.
Ved brug af en browser og en userscript-manager såsom [Tampermonkey][tampermonkey], kan metadata-indsamling fra disse dog ikke undgås.
Alle disse indsamlede data er ikke tilgængelige eller synlige for LSSM-teamet og kan hverken forhindres, favoriseres eller manipuleres af LSSM.
Information om dataindsamling fra den anvendte software kan findes i informationskilderne for den respektive software.

<!-- ==START_FOOTER== Do NOT edit anything below this line! Any edits will be removed as content is auto generated! -->

[lssm.status]: https://status.lss-manager.de/
[lssm.discord]: https://discord.gg/RcTNjpB
[lssm.userscript]: https://v4.lss-manager.de/lssm-v4.user.js
[lssm.donations]: https://donate.lss-manager.de/
[docs]: https://docs.lss-manager.de/
[docs.home]: /en_GB/
[docs.apps]: /en_GB/apps.md
[docs.appstore]: /en_GB/appstore.md
[docs.bugs]: /en_GB/bugs.md
[docs.error_report]: /en_GB/error_report.md
[docs.faq]: /en_GB/faq.md
[docs.metadata]: /en_GB/metadata.md
[docs.other]: /en_GB/other.md
[docs.settings]: /en_GB/settings.md
[docs.suggestions]: /en_GB/suggestions.md
[docs.support]: /en_GB/support.md
[games.self]: https://missionchief.co.uk
[tampermonkey]: https://tampermonkey.net/
[github]: https://github.com/LSS-Manager/LSSM-V.4
[github.issues]: https://github.com/LSS-Manager/LSSM-V.4/issues
[github.issues.open]: https://github.com/LSS-Manager/LSSM-V.4/issues?q=is%3Aissue+is%3Aopen+label%3Abug
