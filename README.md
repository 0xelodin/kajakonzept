# kajakonzept.de

Statische Website für KajaKonzept — Sicherheitsprüfungen für Webanwendungen.

Live unter [kajakonzept.de](https://kajakonzept.de), ausgeliefert über GitHub Pages.

## Aufbau

| Datei | Inhalt |
|---|---|
| `index.html` | Startseite: Leistungen, Praxis, Fähigkeiten, Kontakt |
| `impressum.html` | Impressum nach § 5 DDG |
| `datenschutz.html` | Datenschutzerklärung |
| `style.css` | gemeinsames Stylesheet |
| `CNAME` | Custom Domain, von GitHub Pages erzeugt |

## Grundsätze

- Keine externen Requests: keine Web-Fonts, kein CDN, kein Analytics, keine
  eingebetteten Inhalte von Dritten. Schriften kommen aus dem System-Stack.
- Keine Cookies, kein Tracking.
- Kein Backend, kein Kontaktformular. Kontakt läuft über `mailto:`.
- Nur relative Pfade, damit die Seite auch ohne Custom Domain unter dem
  Unterpfad der github.io-Adresse funktioniert.

## Deployment

Push auf `main` genügt.
