# rgp Website – Entwurf

Diese Website ist ein **Entwurf für regio gis+planung** und stellt **nicht den derzeitigen offiziellen Internetauftritt** dar.

Das auf der Startseite dargestellte Kontaktformular ist in dieser Entwurfsversion **noch nicht funktionsfähig**.

## Projektstruktur

```text
index.html
style.css

1_buero.html
1_geoinformatik.html
1_landschaftsplanung.html
1_stadtplanung.html

2_karriere.html
2_initiativbewerbung.html

3_datenschutz.html
3_impressum.html

bilder/
├── projekt-gruenflaechen.png
├── projekt-landesgartenschau.png
└── projekt-logport-iv.png
```

### Bedeutung der Dateinamen

- `index.html` – Startseite der Website
- `style.css` – Gestaltung aller Seiten
- `1_...` – Hauptseiten des Büros und der Leistungsbereiche
- `2_...` – Unterseiten zum Bereich Karriere
- `3_...` – Rechtliche Seiten
- `bilder/` – Bilder, die auf der Website verwendet werden

`index.html` sollte **nicht umbenannt** werden, da sie von GitHub Pages als Startseite verwendet wird.

## Website lokal testen

Die Website kann ohne zusätzliche Software lokal geöffnet werden:

1. Den gesamten Projektordner auf dem Computer speichern.
2. `index.html` doppelt anklicken.
3. Die Seite öffnet sich im Standardbrowser.
4. Nach Änderungen die Seite neu laden.

Falls Änderungen nicht sofort sichtbar werden, im Browser `Strg + F5` drücken.

## Texte ändern

Texte befinden sich direkt in den jeweiligen HTML-Dateien.

Beispiel:

```html
<p>
  Seit mehr als 15 Jahren beraten und unterstützen wir öffentliche
  Planungsträger, Behörden, Kommunen und private Investoren.
</p>
```

Für eine Textänderung nur den Inhalt zwischen den HTML-Tags ändern. Die Tags selbst sollten bestehen bleiben.

## Aufzählungen ändern

Aufzählungen sind so aufgebaut:

```html
<ul>
  <li>Flächennutzungsplanung</li>
  <li>Bebauungspläne</li>
</ul>
```

Eine neue Leistung wird durch eine weitere `<li>`-Zeile ergänzt.

## Bilder austauschen

Die Projektbilder liegen im Ordner `bilder`.

Die einfachste Möglichkeit zum Austausch:

1. Neues Bild vorbereiten.
2. Dem neuen Bild exakt denselben Dateinamen geben wie dem bisherigen Bild.
3. Die alte Datei im Ordner `bilder` ersetzen.

Dann muss der HTML-Code nicht geändert werden.

Aktuell verwendete Bilder:

```text
projekt-landesgartenschau.png
projekt-logport-iv.png
projekt-gruenflaechen.png
```

Dateinamen sollten möglichst:

- klein geschrieben sein,
- keine Leerzeichen enthalten,
- keine Umlaute enthalten,
- keine Sonderzeichen enthalten.

## Navigation und Links

Die Seiten sind untereinander über relative Links verbunden.

Beispiel:

```html
<a href="1_stadtplanung.html">Stadtplanung</a>
```

Wenn eine HTML-Datei umbenannt wird, müssen deshalb auch alle Links geändert werden, die auf diese Datei verweisen.

Aus diesem Grund sollten die vorhandenen Dateinamen möglichst beibehalten werden.

## Gestaltung ändern

Die Gestaltung der gesamten Website befindet sich in:

```text
style.css
```

Dort werden unter anderem geregelt:

- Farben
- Schriftgrößen
- Abstände
- Spalten
- Buttons
- Projektbilder
- Darstellung auf Smartphone und Tablet

Für reine Textänderungen ist normalerweise keine Änderung der CSS-Datei erforderlich.

## Karriere

Das aktuelle Stellenangebot befindet sich in:

```text
2_karriere.html
```

Die Seite für Initiativbewerbungen befindet sich in:

```text
2_initiativbewerbung.html
```

## Rechtliche Seiten

```text
3_impressum.html
3_datenschutz.html
```

Vor einer endgültigen Veröffentlichung sollten insbesondere die Datenschutzerklärung, der tatsächliche Hostinganbieter und ein später aktiviertes Kontaktformular nochmals geprüft und an die reale technische Umsetzung angepasst werden.

## Kontaktformular

Das Kontaktformular ist in der aktuellen Entwurfsversion nur zur Darstellung eingebaut.

Es versendet **keine Daten und keine E-Mails**.

Vor dem produktiven Einsatz muss hierfür eine technische Lösung eingerichtet und anschließend auch die Datenschutzerklärung entsprechend angepasst werden.

## Veröffentlichung mit GitHub Pages

Die Website kann über GitHub Pages als Vorschau veröffentlicht werden.

Nach Änderungen:

1. Geänderte Dateien in das GitHub-Repository hochladen.
2. Vorhandene Dateien mit den neuen Versionen ersetzen.
3. Änderungen mit `Commit changes` bestätigen.
4. Einige Minuten warten.
5. GitHub-Pages-Adresse neu laden.

Der Ordner `bilder` muss ebenfalls vollständig im Repository vorhanden sein.

## Hinweis zur Entwurfsversion

Der derzeitige GitHub-Pages-Auftritt dient ausschließlich als Präsentations- und Entwurfsversion.

Er ist nicht der offizielle Internetauftritt von regio gis+planung.

---

**Stand:** August 2026
