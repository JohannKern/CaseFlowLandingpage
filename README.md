# CaseFlow AI – Landingpage für Dokumentenprozesse

Eine responsive, deutsch- und englischsprachige Landingpage für CaseFlow AI mit Fokus auf Procurement V1 im Handwerk: Auftragsbestätigungen, Rechnungen und Belege sowie Lieferanten und Nachweise.

## Live ansehen

[johannkern.github.io/CaseFlowLandingpage](https://johannkern.github.io/CaseFlowLandingpage/)

## Projektdateien

- [`index.html`](./index.html) – vollständige Landingpage mit eingebettetem CSS und JavaScript; externe Build-Tools oder Laufzeitabhängigkeiten sind nicht erforderlich.
- [`impressum.html`](./impressum.html) und [`datenschutz.html`](./datenschutz.html) – zweisprachige Rechtstexte.
- [`sitemap.xml`](./sitemap.xml) – Sitemap für Startseite, Impressum und Datenschutz. Die `robots.txt` liegt zur Dokumentation bei; GitHub-Pages-Projektseiten verwenden die Robots-Datei auf Host-Ebene, nicht diese Datei im Projektpfad.
- [`assets/favicon.svg`](./assets/favicon.svg) und [`assets/og-caseflow.png`](./assets/og-caseflow.png) – Favicon und Social-Preview-Bild.
- [`.github/workflows/pages.yml`](./.github/workflows/pages.yml) – veröffentlicht die Website über GitHub Pages.

## Lokal ansehen

`index.html` direkt in einem aktuellen Webbrowser öffnen.

## Veröffentlichung

GitHub Actions veröffentlicht die Seite bei jedem Push auf den Branch `main`. Die Workflow-Ausführung kann außerdem in GitHub unter **Actions** verfolgt werden. GitHub Pages muss im Repository unter **Settings → Pages** als Quelle **GitHub Actions** verwenden.

## Inhalte der Landingpage

- Vorstellung des geplanten Procurement-V1-Umfangs und ausdrücklich als Konzept markierte Produktansicht mit fiktiven Beispieldaten; CaseFlow ist noch nicht gebaut.
- Typische Büroaufgaben und der CaseFlow-Ablauf
- Geplante Anwendungsfälle für Beschaffungsdokumente und Lieferantennachweise; weitere Ideen wie Immobilien und Datenschutzanfragen sind als nicht verfügbare Zukunftsthemen gekennzeichnet.
- FAQ zum Entwicklungsstand, zu geplanten Funktionen und zur Datenverarbeitung
- Überblick zu Integrationen mit bestehender Unternehmenssoftware
- Anfrageformular, das eine vorbereitete E-Mail im E-Mail-Programm der anfragenden Person öffnet; die Nachricht muss dort manuell abgeschickt werden. Eine funktionsfähige Produktdemo ist noch nicht verfügbar.
- Impressum und Datenschutzhinweise
- Canonical- und Social-Media-Metadaten sowie Organization-/WebSite-JSON-LD auf der Startseite
