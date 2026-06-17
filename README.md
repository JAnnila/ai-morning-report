# ai-morning-report

Automaattinen päivittäinen AI-aamuraportti, jonka Claude Code Routine generoi joka
aamu ja committaa tähän repositoryyn.

## Miten se toimii
- Claude Code Routine ajetaan ajastetusti (arkiaamuisin klo 07:00) Anthropicin
  pilvessä – omaa konetta ei tarvitse pitää päällä.
- Routine hakee viimeisen vuorokauden merkittävimmät tekniset AI-uutiset web-haulla,
  suodattaa ja tiivistää ne, ja kirjoittaa raportin tiedostoon `reports/YYYY-MM-DD.md`.
- Raportin sisältö ja lähteet on määritelty tiedostossa `routine-prompt.md`.
- Käytössäännöt (commit suoraan mainiin, ei PR:ää) ovat tiedostossa `CLAUDE.md`.

## Rakenne
- `reports/` – päivämäärällä nimetyt raportit (selattava arkisto)
- `routine-prompt.md` – routinen prompti
- `CLAUDE.md` – ohjeet Claudelle ajojen aikana

## Raportin osiot
TL;DR · Uudet mallit ja versiot · Repot ja yhteisön tekniikat · Tietoturvavahti ·
Saatavuus- ja sääntelyriskit · Hinnoittelu · Syväluentaehdokkaat

## Kiinnostusprofiili (lyhyesti)
Tekninen AI-kehitys: uudet LLM-mallit ja versiot, yhteisön hyvät käytännöt ja repot,
AI/LLM-tietoturva, saatavuuteen vaikuttavat sääntelyriskit, mallien hinnoittelu.
Ei sijoitus- tai osakekulmaa.
