GlanzWerkstatt Alzey - Website
================================

Premium-Singlepage für GlanzWerkstatt Alzey mit Leistungen, Paketübersicht, Preisliste, Galerie, Kontakt und Rechtlichem.

Start lokal
-----------
1. Den kompletten Ordner entpackt lassen.
2. `index.html` per Doppelklick öffnen.
3. Den Ordner `assets` nicht verschieben oder löschen.

Alternativ in PowerShell:

```powershell
Start-Process .\index.html
```

Projektstruktur
---------------
- `index.html` - komplette Website mit HTML, CSS und JavaScript
- `assets/images/gallery` - Galerie-Bilder für die Website
- `assets/images/brand` - Logo- und Markenbilder
- `assets/documents` - Dokumente und PDFs
- `assets/source/originals` - gesicherte Originaldateien
- `START_HIER.txt` - kurze Startanleitung

Inhalte bearbeiten
------------------
Die wichtigsten Texte stehen direkt in `index.html`:
- Leistungen im Abschnitt `#leistungen`
- Pakete Gold, Platin und Diamant im Abschnitt `#pakete`
- Preise im Abschnitt `#preise`
- Kontakt- und Rechtsangaben in den Abschnitten `#kontakt` und `#rechtliches`

Die Paketdetails sind aktuell hochwertig formulierte Platzhalter und können später durch die finalen Leistungsumfänge ersetzt werden.

Bilder
------
Die Galerie nutzt bereits umbenannte, webtaugliche Dateien. Kennzeichen in den verwendeten Galerie-Bildern sind unkenntlich gemacht. Neue Bilder am besten sprechend benennen und in `assets/images/gallery` ablegen.

Live stellen
------------
Für GitHub Pages, Netlify oder klassischen Webspace reicht es, den kompletten Ordner hochzuladen. Es ist kein Build-System, kein npm und kein Backend erforderlich.

Kontaktformular
---------------
Das Formular öffnet eine vorbereitete E-Mail an:
`glanzwerkstatt.alzey@gmail.com`

Für einen späteren echten Formularversand kann ein Backend oder Formularservice ergänzt werden.
