# CaseFlow AI – Landingpage für Dokumentenprozesse

Eine responsive, deutsch- und englischsprachige Landingpage für CaseFlow AI mit Fokus auf Procurement V1 im Handwerk: Auftragsbestätigungen, Rechnungen und Belege sowie Lieferanten und Nachweise.

## Live ansehen

[johannkern.github.io/CaseFlowLandingpage](https://johannkern.github.io/CaseFlowLandingpage/)

## Projektdateien

- [`index.html`](./index.html) – vollständige Landingpage mit eingebettetem CSS und JavaScript; externe Build-Tools oder Laufzeitabhängigkeiten sind nicht erforderlich.
- [`impressum.html`](./impressum.html) und [`datenschutz.html`](./datenschutz.html) – zweisprachige Rechtstexte.
- [`.github/workflows/pages.yml`](./.github/workflows/pages.yml) – veröffentlicht die Website über GitHub Pages.

## Lokal ansehen

`index.html` direkt in einem aktuellen Webbrowser öffnen.

## Veröffentlichung

GitHub Actions veröffentlicht die Seite bei jedem Push auf den Branch `main`. Die Workflow-Ausführung kann außerdem in GitHub unter **Actions** verfolgt werden. GitHub Pages muss im Repository unter **Settings → Pages** als Quelle **GitHub Actions** verwenden.

## Inhalte der Landingpage

- Produktvorstellung und interaktive Produktansicht
- Typische Büroaufgaben und der CaseFlow-Ablauf
- Aktive Anwendungsfälle für Auftragsbestätigungen, Rechnungen und Belege sowie Lieferantennachweise
- Zurückgestellte Anwendungsfälle im Abschnitt „In Planung“
- Überblick zu Integrationen mit bestehender Unternehmenssoftware
- Demo-Formular, das eine vorbereitete E-Mail im E-Mail-Programm der anfragenden Person öffnet; die Nachricht muss dort manuell abgeschickt werden
- Impressum und Datenschutzhinweise
