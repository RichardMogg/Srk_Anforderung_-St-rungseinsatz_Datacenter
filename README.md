# Wartungsprotokoll Kältetechnik

Lokale browserbasierte Web-App zur Erstellung von Prüf-/Wartungsprotokollen für Kältetechnik.

## Projektstruktur

```text
/
├─ index.html
├─ assets/
│  ├─ logo.svg
│  └─ frontpage-gear.svg
├─ css/
│  └─ app.css
├─ data/
│  └─ kaeltemittel.txt
├─ js/
│  ├─ form-config.js
│  └─ app.js
└─ vendor/
   └─ html2pdf.bundle.min.js
```

| Datei                           | Aufgabe                                                                                              |
| ------------------------------- | ---------------------------------------------------------------------------------------------------- |
| `index.html`                    | Seitenstruktur, Formularabschnitte, Buttons, Script- und CSS-Einbindung                             |
| `css/app.css`                   | Layout, Farben, Formularoptik, Tabellen, Bottom-Bar, responsive Darstellung                         |
| `js/form-config.js`             | Checklisten, Messpunkte, Storage-Key, Print-Gear-Konfiguration                                      |
| `js/app.js`                     | Formularlogik, Validierung, lokale Speicherung, Fotoverwaltung, Signatur, Import/Export, ZIP-Export |
| `data/kaeltemittel.txt`         | Auswahlliste der Kältemittel                                                                         |
| `assets/logo.svg`               | Logo in App und Druckansicht                                                                         |
| `assets/frontpage-gear.svg`     | Zahnradgrafik für Druckansicht                                                                       |
| `vendor/html2pdf.bundle.min.js` | PDF-Erzeugung aus der Druckansicht                                                                   |

## Git-Mini-Ablauf für Einsteiger

1. `git status` zeigt dir, was verändert wurde.
2. `git add <datei>` markiert Änderungen für den nächsten Commit.
3. `git commit -m "Beschreibung"` speichert einen lokalen Versionsstand.
4. `git push` lädt deine Commits ins entfernte Repository (z. B. GitHub/GitLab).

Kurz gesagt: **ändern → add → commit → push**.
