# Kommundata-arkiv

Kallt arkiv-repo för rå-dokument (protokoll-PDF:er + kallelsebilagor)
från Faktagranskaren-pipelinen. Se huvudrepot
[Kommundata](https://github.com/Knarrbyn/Kommundata) för koden, och
`DECISION_LOG.md` där för det fullständiga resonemanget bakom
uppdelningen (2026-07-23) — kort sagt: håller huvudrepot smått och
snabbt att checka ut vid varje pipeline-körning genom att flytta de
stora, långsamt växande dokumenten hit istället.

Filerna under `data/raw/` är strukturerade likadant som de tidigare låg
i huvudrepot: `data/raw/{instans}/{datum}/protokoll.pdf` +
`data/raw/{instans}/{datum}/bilagor/`.