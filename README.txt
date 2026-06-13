GlanzWerkstatt Alzey - Website
================================

Premium-Website fuer GlanzWerkstatt Alzey mit Startseite, Paketuebersicht, Preisliste, Kontaktbereich, Rechtstexten und separater Galerie.

Start lokal
-----------
1. Den kompletten Ordner entpackt lassen.
2. `index.html` per Doppelklick oeffnen.
3. Die Galerie ist ueber `galerie.html` erreichbar oder ueber den Button "Galerie oeffnen" auf der Startseite.
4. Den Ordner `assets` nicht verschieben oder loeschen.

Alternativ in PowerShell:

```powershell
Start-Process .\index.html
```

Projektstruktur
---------------
- `index.html` - Startseite mit Leistungen, Paketen, Preisen, Kontakt und Rechtlichem
- `galerie.html` - separate Galerie mit Bereichen fuer Bilder und Videos
- `assets/images/gallery` - Galerie-Bilder
- `assets/videos/gallery` - Galerie-Videos, aktuell vorbereitet mit Platzhalterordner
- `assets/images/brand` - Logo- und Markenbilder
- `assets/documents` - Dokumente und PDFs
- `assets/source/originals` - gesicherte Originaldateien
- `START_HIER.txt` - kurze Startanleitung

Inhalte bearbeiten
------------------
Die wichtigsten Texte stehen direkt in den HTML-Dateien:
- Leistungen im Abschnitt `#leistungen` in `index.html`
- Pakete Basis, Gold und Diamant im Abschnitt `#pakete` in `index.html`
- Preise im Abschnitt `#preise` in `index.html`
- Kontakt- und Rechtsangaben in `#kontakt` und `#rechtliches` in `index.html`
- Galerie-Bilder und Video-Platzhalter in `galerie.html`

Die Paketdetails sind aktuell hochwertig formulierte Platzhalter und koennen spaeter durch finale Leistungsumfaenge ersetzt werden.
Aktuell sind die Innenraumaufbereitungs-Pakete Basis, Gold und Diamant eingepflegt.

Galerie
-------
Neue Bilder am besten sprechend benennen und in `assets/images/gallery` ablegen.
Neue Videos spaeter in `assets/videos/gallery` ablegen und in `galerie.html` im Video-Bereich als echtes `<video>` oder als neue Kachel eintragen.

Die Galerie legt per CSS automatisch ein sichtbares Wasserzeichen `@glanzwerkstatt-alzey` ueber Bilder und Video-Kacheln. Das Wasserzeichen ist ein Overlay im Layout und wird nicht dauerhaft in die Bilddateien eingebrannt.

Kontakt
-------
Das alte Kontaktformular wurde entfernt. Die Startseite nutzt direkte Buttons fuer:
- WhatsApp
- Telefon
- E-Mail

Die Oeffnungszeiten sind Montag bis Freitag von 10:00 bis 20:00 Uhr. Im Kontaktbereich oeffnet der Route-Link ein kleines Google-Maps-Fenster auf der Website mit Button zur Routenplanung.

Live stellen
------------
Fuer GitHub Pages, Netlify oder klassischen Webspace reicht es, den kompletten Ordner hochzuladen. Es ist kein Build-System, kein npm und kein Backend erforderlich.

Hinweis Rechtliches
-------------------
Impressum, Datenschutz und AGB sind als ausfuehrliche Website-Texte vorbereitet. Vor finaler Veroeffentlichung sollten die Rechtstexte bei Bedarf juristisch geprueft werden.
