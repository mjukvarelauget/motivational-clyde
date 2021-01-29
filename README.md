# Motiverende Clyde

Trenger du hjelp til å huske å commite og pushe kode? Nei? Well too bad. Mjukvarelauget smeller til _Motvierende Clyde_ (TM) som sender deg oppmuntrende meldinger og lydklipp når du commiter og pusher kode.

---

Instalasjon:

- Flytt filene i `hooks`-mappen til `.git/hooks`
- Chmod begge filene. Eks: `chmod +x pre-push`

---

Mac bruker `afplay` for å spille av filer fra terminal. Det kan hende at ditt OS ikke har dette, så bytt til din ønskede avspiller i `pre-push`

**NB:** Du kan ha denne gående i alle repo som bruker git, men du vil kanskje ikke dytte disse filene til repo som arbeidsgiver kan se. Husk derfor å putt `hooks` og `motivation` i din `.gitignore`, så slipper du rare samtaler med sjefen din. Lykke til
