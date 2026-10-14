# log.md

## 2026-10-14 09:43 (Claude)

- Repoet satt opp: arbeidsflyt `.github/workflows/pages.yml` som bygger ScummVM med HD-patchen for nettleseren fra Sam-Max-HD og publiserer på Pages, readme, AGENTS, memory og todo.
- Bygget kunne ikke kjøres i Claude sin sandkasse: proxyen stopper nedlastingen av SDL3-kilden fra GitHub-arkivet (HTTP 403). Første bygg skjer i Actions.

## 2026-10-14 10:10 (Claude)

- PR 1 flettet. Bygget på main (38531720202) publiserte siden. Testet i Chromium uten skjerm: siden startet uten nøkkel, hentet spillet og HD-modden fra Sam-Max-HD og viste kontoret i HD.
