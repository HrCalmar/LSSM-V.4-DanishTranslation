---
title: LSS-Manager V.4
lang: en-GB
sidebarDepth: 2
---

# Wiki 🇬🇧 <Badge :text="'v' + $theme.variables.versions.short"/>

> stable: _{{ $theme.variables.versions.stable }}_ [![Online Status for stable](https://status.lss-manager.de/api/badge/71/status?style=flat&upLabel=online&downLabel=offline)][lssm.status]
>
> beta: _{{ $theme.variables.versions.beta }}_ [![Online Status for beta](https://status.lss-manager.de/api/badge/72/status?style=flat&upLabel=online&downLabel=offline)][lssm.status]

<discord style="float: right;"><img src="https://discord.com/api/guilds/254167535446917120/embed.png?style=banner1" alt="Our Discord-Server: United Dispatch" data-prevent-zooming></discord>

[LSSM-Server-Status][lssm.status]

[Game-Online-Status](https://status.lss-manager.de/status/missionchief)

<!-- Do NOT edit anything above this line! Any edits will be removed as content is auto generated! -->

## Om LSSM

LSS-MANAGER V.4 er en udvidelse til [Missionchief.co.uk][games.self] og dens andre sprogversioner.

BEMÆRK : VIRKER IKKE PÅ DEN DANSKE UDGAVE - VI OVERSÆTTER I ØJEBLIKKET.

Med denne udvidelse tilføjes en appstore til spillet, som gør det muligt at bruge plugins. Alle funktioner er modulære – du kan selv vælge, hvad der skal aktiveres, helt ned til det sidste modul.

Plugins, der ikke er aktiveret, vil heller ikke blive indlæst – dette gør administrationen meget nem og giver en bedre ydeevne.

## Installation 📥

Ved at bruge LSSM accepterer du, at vi indsamler metadata. Du kan finde mere information om dette under [Metadata][docs.metadata].

En tabel over, hvilke browsere LSSM er kompatibel med, findes i vores [FAQ](faq.md#i-hvilke-browsere-fungerer-lss-manager).

:::tip Brug af LSSM på din mobiltelefon
Vi understøtter officielt ikke en mobil version. Dog tilbyder browseren Firefox muligheden for at bruge add-ons, selv i sin mobile version. Vi garanterer dog ikke et attraktivt design eller fuld funktionalitet for mobile browsere.

Officiel understøttelse af mobile browsere er i øjeblikket **ikke** planlagt.
:::

### Trin 1: Tampermonkey

Hvis du endnu ikke har installeret Tampermonkey i din browser, skal du stadig gøre det. Her er en oversigt over links til de mest almindelige browsere:

<tampermonkey-download-table/>

For andre browsere kan du downloade Tampermonkey på [tampermonkey.net][tampermonkey].

:::warning
Bemærk venligst, at vi ikke officielt understøtter ældre browsere, mobile browsere eller Apple Safari. Support for disse browsere er derfor hverken garanteret eller sandsynlig.
:::

### Trin 2: Userscript

Hvis Tampermonkey blev installeret korrekt i din browser, kan du enten klikke [her][lssm.userscript] eller oprette et nyt userscript med følgende indhold:

@[code js](@userscript)

#### Trin 2.5: Aktivér udviklertilstand eller skift til Firefox

Hvis du bruger "Google Chrome" eller en browser baseret på Chromium, kan det være nødvendigt at aktivere udviklertilstand for at kunne køre userscripts. Hvis du ikke vil skifte til Firefox, kan du finde instruktioner om, hvordan du aktiverer udviklertilstand på [https://www.tampermonkey.net/faq.php?locale=en#Q209](https://www.tampermonkey.net/faq.php?locale=en#Q209).

### Trin 3: Aktivér

LSSM-indikatoren er enten LSSM-logoet eller (hvis indstillet i [indstillingerne](settings.md)) en grøn tekst `LSSM V.4`.
Hvis du er på missionchief, men ikke kan se denne indikator i øverste højre hjørne, skal du klikke på tampermonkey-ikonet i din browser og kontrollere, om kontakten til LSS-Manager-scriptet er sat til `on`.

Hvis du har problemer, kan du altid kontakte [Support][docs.support].

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
