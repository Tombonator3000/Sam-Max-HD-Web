# Sam & Max HD på nettet

Nettsiden for [Sam & Max HD Remake](https://github.com/Tombonator3000/Sam-Max-HD): ScummVM med HD-patchen, bygget for nettleseren.

Siden: https://tombonator3000.github.io/Sam-Max-HD-Web/

- Siden går rett inn i spillet. Spillet og HD-grafikken hentes fra grenene `spilldata` og `hd-mod` i Sam-Max-HD første gang og lagres i nettleseren. Bare filer som er endret, hentes på nytt, så ny HD-grafikk kommer med av seg selv.
- Uten nøkkel begrenser GitHub antall forespørsler i timen. Blir grensen nådd, ber siden om en lesenøkkel (Contents, Read-only for Sam-Max-HD).
- F5 er spillets meny, med raden HD Graphics. Ctrl+H bytter mellom HD og originalgrafikk.
- Valg i adressen: `?rom=7` (hopp til et rom, til testing), `?klassisk`, `?gult` (gult der HD mangler), `?programvare` (uten WebGL), `?uten-lyd` (uten talen, for maskiner med lite minne).
- Musikken spilles med AdLib-emuleringen. Sam & Max CD har ingen CD-lydspor; musikken er MIDI inne i spillfilene.

Repoet har bare arbeidsflyten som bygger siden (`.github/workflows/pages.yml`). Motoren og HD-patchen er GPL-3.0-or-later; kildekoden følger siden som `source.tar.gz`. Spillet og grafikken tilhører Disney/Lucasfilm.

Første gang: Settings > Pages > Source må stå på GitHub Actions.
