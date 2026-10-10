# Stratum Assets

Oeffentliches technisches Asset-Repository von Stratum Studio. Aktueller Repositoryname: `daret610/Stratum-Assets`.

Dieses Repository dient als stabile Bildquelle für Homebrewery und andere veröffentlichte Produktionsstände.

## Grundregel ab Workflow v03

Hier gehören nur technisch veröffentlichte **FINAL-Assets** und freigegebene wiederverwendbare META-Assets hinein.

Nicht hierher gehören:

- CONCEPT-Varianten
- LOCKED-Arbeitsstände
- Backups
- Review-Exporte
- externe Referenz-PDFs
- Produktionsskripte
- Entwürfe ohne aktive Verwendung

Die Arbeits- und Verwaltungsbibliothek liegt in Google Drive; das private Produktionsrepository verwaltet Master, Asset-Mapping, Homebrewery-Quellen und Workflowstatus.

## Legacy-Hinweis: Der Taumelnde Greif

Das Pilotabenteuer entstand noch mit dem älteren Statusmodell `CONCEPT / APPROVED / FINAL`.

Einige Kapitelbanner und die TOC-Vignette tragen deshalb weiterhin `APPROVED` im Dateinamen. Diese Dateien werden vom akzeptierten finalen HB-v08.35-Satz **exakt unter diesen URLs verwendet** und werden daher nicht rückwirkend umbenannt oder ersetzt.

Für neue Abenteuer gilt ausschließlich:

```text
CONCEPT -> LOCKED -> FINAL
```

und nur FINAL wird hier veröffentlicht.

## META-Assets

Die wiederverwendbare Stilbibliothek liegt unter `META-Assets/`.

Jeder Stil verwendet eine standardisierte Unterordnerstruktur. Unfertige Entwürfe gehören nicht in diese Bibliothek.

Aktuelle Stilordner:

- `01_Klassisch`
- `02_Horror`
- `03_Adelig`
- `04_Daemonisch`

Technische Pfade verwenden nach Möglichkeit ASCII, keine Leerzeichen und keine problematischen Sonderzeichen.


## Lizenz / Nutzung

Die Nutzung der Assets ist in [LICENSE.md](./LICENSE.md) geregelt. Die öffentliche Verfügbarkeit dieses Repositories bedeutet keine allgemeine Freigabe zur Weiterverwendung.

## Namensmigration (beschlossen 2026-10-10)

Stratum Assets ist die gemeinsame technische Publikationsquelle fuer freigegebene Assets; dadurch entstehen keine neuen Rechte an Drittmaterialien. Der bestehende Inhalt und die FINAL-/META-Regeln bleiben unveraendert.

**WICHTIG:** Vor dem Repository-Rename die Homebrewery-Bildlinks (insbesondere `Der Taumelnde Greif`), Raw-GitHub-URLs und eventuelle Automationen inventarisieren. Alte Dateinamen/-pfade und URLs nicht vor erfolgreichem Abruf- und Render-Test ersetzen. Repository-Rename ausgefuehrt. Vollstaendiger URL-/Render-Regressionstest steht noch aus.
