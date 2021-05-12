# Voreinstellungen

## Programminstallation

Falls noch nicht geschehen, [**Laden Sie sich Inkscape runter**](https://inkscape.org/de/release/inkscape-1.0.1/) und **installieren** Sie es.

## **Programmaufbau**

```{figure} Inkscape/Untitled_3.png 
--- 
width: 500px 
name: Untitled_3
--- 
caption 
``` 

[Bild aus Inkscape Dokumentation](https://inkscape-manuals.readthedocs.io/en/latest/interface.html)

In meiner Version ist die `Commands-Bar` über der `Tool-controls bar`

Wir öffnen Inkscape sehen viele verschiedene Menüleisten und Bereiche. Wir werden die meisten mehr oder weniger kennenlernen und fokussieren uns zunächst auf die **Seiteneinstellung,** die den Bereich der **`Page Area`** definiert.

### Icons zu klein?

Sind die Icons zu klein, so kann dies unter **Einstellungen** (`SHIFT` + `STR` + `P` oder `Menu-Bar`: `Bearbeiten` → `Einstellungen`) unter `Benutzeroberfläche` → `Thema` geändert werden. 

→ **Die Einstellungen werden nach einem Neustart übernommen**

```{figure} Inkscape/Untitled_4.png 
--- 
width: 500px 
name: Untitled_4
--- 
caption 
``` 

## Datei speichern

Speichern Sie ihre Datei mit dem Namen "Solarzelle.svg" auf ihrem Computer.

**DATEI SPEICHERN UNTER**
(`SHIFT` + `STR`+ `S`) oder (`Menu bar` → `Datei` →  `Speichern Unter...`)

**DATEI SPEICHERN** 
(`STR`+ `S`) oder (`Menu bar` → `Datei` →  `Speichern`)

Später sollten Sie sich angewöhnen regelmäßig `STR` + `S` zu drücken um im Falle des Programmabsturzes nicht Ihre Zeichnung zu verlieren.

## **Seite Einrichten**

Wir legen zu Beginn die Größe der `Page Area` über die `**Dokumenteneinstellung**`, welche in der **`Docking Area`** erscheint. Gegeben falls muss man den **`Scrollbalken`** verwenden um die **`Dokumenteneinstellungen`** zu finden.

```{figure} Inkscape/Untitled_5.png 
--- 
width: 500px 
name: Untitled_5
--- 
caption 
``` 

**DOKUMENTENEINSTELLUNGEN**
(`SHIFT` + `STR` + `D`) oder (`Menu bar` → `Datei` →  `Dokumenteneinstellungen...`)

**Reiter**: **`Seite`**

```{figure} Inkscape/Untitled_6.png 
--- 
width: 500px 
name: Untitled_6
--- 
caption 
``` 

Die **Seitenbreite** sollte so eingestellt werden, wie sie im **späteren LaTeX Dokument verwendet wird**, um die Schriftgrößen konsistent zu halten.

Die Höhe kann später an die fertige Abbildung angepasst werden.

```{figure} Inkscape/Bildbreite.png 
--- 
width: 500px 
name: Bildbreite
--- 
caption 
``` 

Veranschaulichung der Seitenbreite im LaTeX Dokument

Wir wählen also eine `Seitenbreite` von `180mm`. Dafür auch die `Einheit` auf `mm` setzen. Die `Höhe` lassen wir erstmal auf der `Standardeinstellung`.

```{figure} Inkscape/Untitled_7.png 
--- 
width: 500px 
name: Untitled_7
--- 
caption 
``` 

## Gitter einstellen

Als nächstes stellen wir ein Gitter ein, welches uns beim erstellen von Geometrien hilft in definierten Abständen zu arbeiten.

Klicken Sie in den `Dokumenteneinstellungen` auf `Gitter` und Stellen Sie ein Gitter mit 1mm Abstand und dicken Linien aller 5mm ein.

**DOKUMENTENEINSTELLUNGEN**
(`SHIFT` + `STR` + `D`) oder (`Menu bar` → `Datei` →  `Dokumenteneinstellungen...`)

**Reiter**: **`Gitter`**

```{figure} Inkscape/Untitled_8.png 
--- 
width: 500px 
name: Untitled_8
--- 
caption 
``` 

Durch den Button `Neu` erstellen wir ein neues Gitter und Stellen auf `mm` um und wählen alle 1mm in x und y Richtung ein Gitter. Alle **5 Gitterlinien** soll eine **Dicke Gitterlinie** erstellt werden (Standardeinstellung)

```{figure} Inkscape/Untitled_9.png 
--- 
width: 500px 
name: Untitled_9
--- 
caption 
``` 

Mit der Taste `#` kann die **Sichtbarkeit des Gitters an/aus geschaltet** werden.

### Änderung der Ansicht

Hier eine kurze Übersicht der Befehle die Sie benötigen um die Ansicht im `Canvas` zu verändern:

🔍 **Zoom**: `STR` + `Mausrad`

🔍 **Zoom (Auswahl** in Fenster einpassen**)**: `3`

🔍 **Zoom (Zeichnung** in Fenster einpassen**)**: `4`

🔍 **Zoom (Seite** in Fenster einpassen**)**: `5`

🔍 **Zoom (Seitenbreite** in Fenster einpassen**)**: `6`

↔️ **Verschieben (horizontal)**: `SHIFT` +  `Mausrad`   **ODER**   `**Scrollbalken** unten`

↕️ **Verschieben (vertikal)**: `Mausrad`   **ODER**   `**Scrollbalken** rechts`

**Außerdem**: 

- Durch **halten** der `mittleren Maustaste` kann die **Ansicht** `mit der Maus` in die **gewünschte Richtung bewegt** werden
- Durch **halten** der `mittleren Maustaste`  + `**STR**` kann die **Ansicht** `mit der Maus` in die **gewünschte Richtung gedreht** werden

Rechts unten kann dies wieder zurück gesetzt werden

```{figure} Inkscape/Untitled_10.png 
--- 
width: 500px 
name: Untitled_10
--- 
caption 
``` 

Bei kleineren Zoom-Stufen werden **nur die Dicken Gitterlinien** (*im Beispiel 5mm*) **angezeigt.**  Die **normalen Gitterlinien** (*im Beispiel 1mm*) werden ab einer **Vergrößerung von 200%** angezeigt

```{figure} Inkscape/Gitter_Zoom.gif 
--- 
width: 500px 
name: Gitter_Zoom
--- 
caption 
``` 
