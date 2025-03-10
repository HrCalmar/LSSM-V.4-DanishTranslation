---
title: Indstillinger ⚙️
lang: da_DK
---

# Indstillinger ⚙️

Indstillingerne for alle moduler administreres centralt i indstillingerne. Kun indstillingerne for aktive moduler kan ændres.

Ved hjælp af knapperne `Eksportér` og `Importér` kan du gemme dine indstillinger i en fil og/eller dele dem med dine venner.
I den nærmeste fremtid ønsker vi at tilbyde muligheden for at gemme indstillingerne profilbundet. Dette betyder, at indstillingerne ikke længere vil være bundet til en enhed.

::: tip Ændringer
Så snart du forlader indstillingerne og har gemt ændringer, genindlæses spillet automatisk for at anvende alle indstillinger.
Hvis du har ugemte ændringer, kan du ikke lukke indstillingerne – du vil få en lille advarselsbesked.
:::

::: danger Nulstil indstillingerne
Advarsel: Hvis du nulstiller indstillingerne, kan de ikke gendannes uden en tidligere eksport!
:::

## Moment.js

Dette afsnit giver information om, hvordan du konfigurerer dato- og tidsindstillinger, f.eks. i modulet [ur](modules/clock.md).

Vi bruger [Moment.js](https://momentjs.com) til at tilbyde et bredt udvalg af konfigurationsmuligheder. Hvis du ønsker at se den originale dokumentation, kan du finde den [her](https://momentjscom.readthedocs.io/en/latest/moment/04-displaying/01-format/).

### Live-editor

Prøv dit eget format her og se en live-forhåndsvisning! Se information om konfiguration nedenfor.

<momentjs-preview/>

### Variabler

<momentjs-variables/>

### Lokale forkortelser

<momentjs-shorts/>

### Normal tekst

Hvis du vil inkludere anden tekst sammen med dit ur, såsom `time`, vil blot at skrive `LTS time` ikke fungere.
Dette vil resultere i `11:13:27 AM 11ime`.
For at inkludere tekst, der ikke skal formateres, skal du omgive den med `[]`.
Eksempelvis vil `LTS [Time]` eller `LTS [T]ime` begge resultere i `11:13:27 AM Time` som visning.

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
