# memory.md

- Nettsiden: https://tombonator3000.github.io/Sam-Max-HD-Web/ (Pages med GitHub Actions som kilde).
- Arbeidsflyten `.github/workflows/pages.yml` sjekker ut Sam-Max-HD (main, eller `ref` ved manuell kjøring), kjører `engine/build-web.sh` og `engine/build-pages.py`, og publiserer fra main. Pull requests bygges og testes uten å publiseres.
- Sam-Max-HD er offentlig, så siden henter spillfilene uten nøkkel (fillister fra api.github.com, filene fra raw.githubusercontent.com). Nøkkel trengs bare når GitHub begrenser forespørsler.
- Musikken: AdLib-emulering (Web MIDI er stengt av siden). Spillet har ingen CD-lydspor.
