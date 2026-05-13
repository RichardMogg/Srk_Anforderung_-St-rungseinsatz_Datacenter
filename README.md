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


## Pull Request (GitHub) – Schritt für Schritt

Wenn du das zum ersten Mal machst, gehe exakt so vor:

1. `git checkout -b <feature-branch>` erstellt einen neuen Branch (nur einmal nötig).
2. Änderungen an Dateien speichern.
3. `git status` prüfen.
4. `git add <datei>` oder `git add .` ausführen.
5. `git commit -m "Kurze Beschreibung"` ausführen.
6. `git push -u origin <feature-branch>` ausführen.
7. Den Link aus dem Terminal öffnen (`.../pull/new/<feature-branch>`).
8. Auf GitHub prüfen: **base = main**, **compare = <feature-branch>**.
9. Titel/Beschreibung eintragen und auf **Create pull request** klicken.

Wenn GitHub "There isn’t anything to compare" anzeigt, sind `main` und dein Branch identisch; dann fehlen neue Commits auf dem Branch.

## Pull Request (GitHub) – Schritt für Schritt

Wenn du das zum ersten Mal machst, gehe exakt so vor:

1. `git checkout -b <feature-branch>` erstellt einen neuen Branch (nur einmal nötig).
2. Änderungen an Dateien speichern.
3. `git status` prüfen.
4. `git add <datei>` oder `git add .` ausführen.
5. `git commit -m "Kurze Beschreibung"` ausführen.
6. `git push -u origin <feature-branch>` ausführen.
7. Den Link aus dem Terminal öffnen (`.../pull/new/<feature-branch>`).
8. Auf GitHub prüfen: **base = main**, **compare = <feature-branch>**.
9. Titel/Beschreibung eintragen und auf **Create pull request** klicken.

Wenn GitHub "There isn’t anything to compare" anzeigt, sind `main` und dein Branch identisch; dann fehlen neue Commits auf dem Branch.
