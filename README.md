# Growtainer

**Mineralreicher Bio-Eigenanbau — einfach gemacht.**

Open-Source-Pflanzsystem mit Anleitungen, 3D-Druck-Vorlagen und Substrat-Rezepten für selbstbewässernde, selbstdüngende Pflanzkübel mit maximaler Mineraldichte.

→ **Live-Seite mit Substrat-Rechner: [growtainer.org](https://growtainer.org)**

---

## Was der Growtainer leistet

Drei Vorteile in einem genial einfachen System:

1. **Selbstbewässernd** — Wasserreservoir versorgt mehrere Tage, Pflanze nimmt per Kapillarwirkung was sie braucht
2. **Selbstdüngend** — Volldünger als Streifen oben unter Folie, hält die ganze Saison
3. **Maximale Mineralverfügbarkeit** — Urgesteinsmehl, Wurmhumus, Dolomit als lebendige Matrix

Klassischer Anbau wäscht Dünger und Mineralien aus. Das Growtainer-Prinzip kehrt das um — überall wo es genug Licht für Pflanzen gibt.

## Inhalt dieses Repos

```
growtainer/
├── index.html              ← Hauptseite mit Substrat-Rechner
├── diy.html                ← DIY-Bauanleitung (2 Varianten)
├── substrat.html           ← Substrat-Theorie und Rezepte
├── 3d-druck.html           ← 3D-Druck-Vorlagen mit Anleitungen
├── microgreens.html        ← Microgreens-Anbau und Stammlösung
├── stl/
│   ├── growtainer_inlay.stl       ← empfohlener Erdrost-Einsatz
│   └── growtainer_honeycomb.stl   ← experimentelle Variante mit größerem Reservoir
├── assets/
│   ├── style.css           ← gemeinsames Stylesheet
│   └── images/             ← Skizze, Fotos, Bauschritt-Bilder
├── CNAME                   ← Custom-Domain-Konfiguration
└── README.md
```

## Live-Seite — was wo ist

| Seite | Inhalt |
|---|---|
| [growtainer.org](https://growtainer.org) | Prinzip, Substrat-Rechner mit Düngerwahl, Fahrplan |
| [growtainer.org/diy.html](https://growtainer.org/diy.html) | Doppeleimer-Bauanleitung, Eigenbau aus Eimer-Deckel, Zeitraffer-Video |
| [growtainer.org/substrat.html](https://growtainer.org/substrat.html) | Drei Substrat-Varianten, CRH-Theorie, Frustrationswarnungen |
| [growtainer.org/3d-druck.html](https://growtainer.org/3d-druck.html) | STL-Downloads, Druck-Settings, Skalierung, Spritzguss-Sammelbestellung |
| [growtainer.org/microgreens.html](https://growtainer.org/microgreens.html) | Stammlösung, Sortenwahl, Mehrfach-Ernte-Praxis |

## 3D-Druck-Dateien

Beide STLs haben einen Außendurchmesser von 280 mm — passend zu typischen 15–20-Liter-Lebensmitteleimern. Vor dem Drucken den Innendurchmesser des Pflanzgefäßes auf Erdrost-Höhe messen und ggf. proportional skalieren ([Anleitung](https://growtainer.org/3d-druck.html#skalieren)).

| Variante | Höhe | Material | Wasserkapazität* | Status |
|---|---|---|---|---|
| `growtainer_inlay.stl` | 53 mm | ~245 g PETG | ~2,4 L | empfohlen |
| `growtainer_honeycomb.stl` | 72 mm | ~115 g PETG | ~3,5 L | experimentell |

\* im 20-L-Eimer mit ~270 mm Innendurchmesser

Druck-Settings: PETG, Layer 0,2 mm, Infill 15–20 % (Inlay) bzw. 50 %+ (Honeycomb). Online-Druckservice ab ~15 € — siehe [3D-Druck-Seite](https://growtainer.org/3d-druck.html#drucken-lassen).

## Praxisprotokoll 3 — die Theorie dahinter

Die wissenschaftlichen Grundlagen zu Mineralien-Bedarf, Glutamat-Recycling, Dolomit-Logik und Substrat-Aufbau stehen im **Praxisprotokoll 3**:

→ [Schlüssel-Mineralien für die Regeneration (PDF, 26 Seiten)](https://www.dropbox.com/scl/fi/ygs2a4gu77epndvwu9dvp/sk_mineralien_protokoll.pdf?rlkey=2fz45aro3x9w3eq7z88y4dqxq&dl=0)

## Saison 2026 — mitforschen

Wo besonders viel Spielraum ist und Mit-Forscher willkommen sind:

- **Honeycomb-Stabilität** — verbessertes Wabendesign mit besserer Lastverteilung
- **Parametrische STL-Quellen** — Fusion 360 / FreeCAD / OpenSCAD-Skripte für saubere Re-Generierung statt Skalier-Verzerrung
- **Anpassungen für andere Eimer-Formate** — Mörtelkübel (eckig), 30-L-Tonnen, kleine Balkonkübel
- **Dünger-Schadstoff-Recherche** — unabhängige Tests gängiger Bio-Düngermarken (RAL, ÖkoTest 2024/2025, Hersteller-Datenblätter)
- **DIY-Phosphor-Booster** für Blüte/Fruchtphase, angelehnt an Solomon „Gardening When It Counts" — angepasst an mitteleuropäische Schimmelbedingungen
- **Brix-Messreihen** — Refraktometer als günstige Annäherung an Mineraldichte: Growtainer vs. Bio-Supermarkt
- **Microgreens-Substrat-Vergleiche** mit Mineral-Gießwasser und Stammlösung

Beobachtungen, Saisonberichte, Sorten-Notizen, Designs gerne als [Issue](https://github.com/growtainer/growtainer/issues) oder Pull Request.

## Sammelbestellung Spritzguss

Bei einer kollektiven Bestellung von ~1.000 Einheiten Inlay wird Spritzguss in Lebensmittel-Polypropylen attraktiv (~8–12 € pro Stück statt ~15–20 € im 3D-Druck), bei größerer Auflage entsprechend günstiger. Interesse an Sammelbestellung? E-Mail an [mail@growtainer.org](mailto:mail@growtainer.org?subject=Sammelbestellung%20Spritzguss) mit gewünschter Stückzahl.

## Lizenz

Inhalte und Dokumentation: **[CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)**
3D-Druck-Daten und Hardware-Designs: **[CERN-OHL-S 2.0](https://cern-ohl.web.cern.ch/)**

Du darfst alles bauen, anpassen, weitergeben — mit Namensnennung „Project Growtainer" und unter derselben Lizenz.

## Material und Hintergrund

| | |
|---|---|
| Webseite | [growtainer.org](https://growtainer.org) |
| Video-Archiv | [youtube.com/@growtainer](https://www.youtube.com/@growtainer) — erste Bauvideos aus Berlin 2010 |
| Aktuelle Videos | [@stefankutter](https://www.youtube.com/@stefankutter) — Zeitraffer und Inlay-Demos |
| Alte DIY-Anleitung | [SlideShare 2009](https://de.slideshare.net/slideshow/diy-growtainer/1459523) — Vintage, wird ins Repo überführt |
| Community | [Facebook-Seite](https://www.facebook.com/profile.php?id=100064641941504) |
| Newsletter | [Praxisprotokolle abonnieren](https://mailchi.mp/stefankutter/newsletter-eintragen) — P1 Stoffwechsel · P2 Neuro-Emotional · P3 Mineralien |
| Kontakt | [mail@growtainer.org](mailto:mail@growtainer.org) |

---

*Stefan Kutter · Open Source · CC-BY-SA 4.0*
