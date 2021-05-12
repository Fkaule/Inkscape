# Inkscape

# Infomaterial / Links

**[📖 Inkscape Dokumentation](https://inkscape-manuals.readthedocs.io/en/latest/why-use-inkscape.html)**

**[⬇️ Inkscape (Ver. 1.0.1) Download](https://inkscape.org/de/release/inkscape-1.0.1/)**

# Funktions- / Themenübersicht

*️⃣ = **Advanced** ( [zweite Veranstaltung](https://www.notion.so/Inkscape-Advanced-1fe01d20969442bb8fc381e2a72845ce) )

**ALLGEMEIN**

**[Seite Einrichten]()**

- [Größe]()
- [Gitter]()

**[Änderung der Ansicht]()**

- Zoom
- Bewegung

**[Ebenen]()**

- Erstellen
- Sichtbarkeit
- Sperren

**Speichern**

- [Vorbereitungen]()
- [png]()
- [svg]()

**OBJEKTE ERSTELLEN**

**Inkscape Tools zur Objekterstellung**

- [Rechteck]()
- [Kreis]()
- [Bezier-Pen]()
- [Text]()

**[Klone erstellen](https://www.notion.so/Inkscape-Advanced-1fe01d20969442bb8fc381e2a72845ce)** *️⃣

**Pfadeffekte** *️⃣

- [Bemessung](https://www.notion.so/Inkscape-Advanced-1fe01d20969442bb8fc381e2a72845ce)

**[Texthintergrund](https://www.notion.so/Inkscape-Advanced-1fe01d20969442bb8fc381e2a72845ce)** *️⃣

**[Path vs Object](https://www.notion.so/Inkscape-Advanced-1fe01d20969442bb8fc381e2a72845ce)** *️⃣

- [Node Aligment](https://www.notion.so/Inkscape-Advanced-1fe01d20969442bb8fc381e2a72845ce)
- [Boolean Operations](https://www.notion.so/Inkscape-Advanced-1fe01d20969442bb8fc381e2a72845ce)

**[Vektorgrafik aus Pixelgrafik erstellen](https://www.notion.so/Inkscape-Advanced-1fe01d20969442bb8fc381e2a72845ce)** *️⃣

$**[\LaTeX$ Formeln](https://www.notion.so/Inkscape-Advanced-1fe01d20969442bb8fc381e2a72845ce)** *️⃣

**OBJEKTE VERÄNDERN**

**[Objekteigenschaften]()**

- **Füllung (**Farbe / Alpha)
- **Kontur** ( Farbe / Alpha / Linientyp / Liniendicke)

**Zusätzliche** **Inkscape Tools**

- [Edit Path by Nodes]()
- [Pipette (Color Picker)]()

**Objekte ausrichten**

- [Objekthierarchie]()
- [Alignment Tool (Zueinander / Aufteilung)]()

**Objekte verschieben / skalieren / drehen**

- [Bewegung]()
- [Einrasten]()
- [Objektgröße ändern]()

[Gruppieren]()

# Vorzeigebeispiel: Solarzelle

Wir wollen nun den **Aufbau** und die **Funktionen** von **Inskcape** direkt an Beispielen kennenlernen. Beginnend dazu verwenden wir eine Darstellung zum **schematischen Aufbau einer Solarzelle**.

## Vorlauf

### Recherchematerial

```{figure} Inkscape/Untitled.png 
--- 
width: 500px 
name: Untitled
--- 
caption 
``` 

In der Kunst gibt es ein schönes **Zitat** von **Gary Panter**:

> "*If you have one person you’re influenced by, everyone will say you’re the next whoever. But if you rip off a hundred people, everyone will say you’re so original*!"  **Gary Panter**

Um etwas mehr in der Wissenschaft zu bleiben noch ein **Zitat** von **Isaac Newton**:

> "*If I have seen further it is by standing on the shoulders of giants.*" **Isaac Newton**

**Im Kern geht es darum: Alles was man erstellt ist ein Produkt von Dingen die man zuvor gesehen hat.** 

Besonders wenn man etwas neues lernen will (wie wir jetzt mit Inkscape) hilft es sehr, sich an  Abbildungen zu orientieren, die einen optisch ansprechen und versucht diese selbst zu erstellen bzw. zu reproduzieren. Nun also zurück zu unserem Solarzellen Beispiel. 

Wir fangen an und suchen uns Referenzbilder für den Aufbau der Solarzelle. Im besten Fall kann man auch Fachliteratur zurückgreifen, wir verwenden zur Vereinfachung die Bildersuche mit der Suchmaschine Ihrer Wahl z.B. hier die **[Bildersuche mit Ecosia (Link)](https://www.ecosia.org/images?q=schematischer%20aufbau%20solarzelle)**

 [](https://www.ecosia.org/images?q=schematischer%20aufbau%20solarzelle)

```{figure} Inkscape/Untitled_1.png 
--- 
width: 500px 
name: Untitled_1
--- 
caption 
``` 

Wir nehmen uns nun eine Abbildung die uns inhaltlich und optisch am ehesten zusagt als Vorlage für unser erstes Beispiel.

```{figure} Inkscape/Untitled_2.png 
--- 
width: 500px 
name: Untitled_2
--- 
caption 
``` 

Quelle: [https://www.solaranlage.de/technik/solarzellen](https://www.solaranlage.de/technik/solarzellen)

Um frei verwendbare Referenzen zu bekommen, empfiehlt sich die Verwendung von **[pixabay](pixabay.com/de)** oder **[unsplash](https://unsplash.com/)**

Zur Vereinfachung würde ich die Abbildung auf eine 2D Darstellung zurückführen. Hier nun das Ergebnis was wir erstellen wollen:

```{figure} Inkscape/00-Solarzelle.png 
--- 
width: 500px 
name: 00-Solarzelle
--- 
caption 
``` 

### Programminstallation

Falls noch nicht geschehen, [**Laden Sie sich Inkscape runter**](https://inkscape.org/de/release/inkscape-1.0.1/) und **installieren** Sie es.

### **Programmaufbau**

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

### Datei speichern

Speichern Sie ihre Datei mit dem Namen "Solarzelle.svg" auf ihrem Computer.

**DATEI SPEICHERN UNTER**
(`SHIFT` + `STR`+ `S`) oder (`Menu bar` → `Datei` →  `Speichern Unter...`)

**DATEI SPEICHERN** 
(`STR`+ `S`) oder (`Menu bar` → `Datei` →  `Speichern`)

Später sollten Sie sich angewöhnen regelmäßig `STR` + `S` zu drücken um im Falle des Programmabsturzes nicht Ihre Zeichnung zu verlieren.

### **Seite Einrichten**

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

### Gitter einstellen

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

## Erstellung der Solarzelle

### Ebenen

**Ebenen** sind hilfreich um Sachen zum **gruppieren** von Objekten bzw diese zu **blockieren** (damit Sie nicht angeklickt und verändert werden können) oder um die **Sichtbarkeit ein/auszuschalten**.

```{figure} Inkscape/Untitled_11.png 
--- 
width: 500px 
name: Untitled_11
--- 
caption 
``` 

**EBENEN**
(`SHIFT` + `STR` + `L`) oder  (`Icon` in der `Commands-Bar` (oben)) 
oder (`Menu bar` → `Ebene`→  `Ebenen`)

```{figure} Inkscape/Untitled_12.png 
--- 
width: 500px 
name: Untitled_12
--- 
caption 
``` 

Erstellen Sie eine neue Ebene mit dem Namen (**Recherchematerial**) und positionieren Sie diese unter der "Ebene 1"

```{figure} Inkscape/Ebene_Erzeugen.gif 
--- 
width: 500px 
name: Ebene_Erzeugen
--- 
caption 
``` 

Bei der **Ebenenpositionierung** wird festgelegt in welcher Reihenfolge die Objekte übereinander dargestellt werden. 

Durch das **Blockieren** können Ebenen nicht mehr ausgewählt und verändert werden. Dies ist besonders hilfreich um nicht ungewollt etwas auszuwählen.

Die **Sichtbarkeit** kann ausgeblendet werden und beim Export werden diese Ebenen dann auch nicht im Bild sichtbar sein.

```{figure} Inkscape/Ebenen_Erklaerung.png 
--- 
width: 500px 
name: Ebenen_Erklaerung
--- 
caption 
``` 

Kopieren Sie das Bild aus der Bildersuche (im Browser Rechtsklick auf das Bild → `Kopieren` ).

Wählen Sie die Ebene "Recherchematerial" aus und fügen Sie das kopierte Bild mit (`STR` + `V`) in Inkscape ein. 

*Wenn Das Bild als Datei vorliegt können Sie Bilder aus dem Dateiexplorer direkt per Drag&Drop in das Inkscape Fenster ziehen*

**Positionieren** Sie nun das **Bild** mit dem `Auswahltool` durch **Anklicken** und **verschieben** so wie Sie es haben wollen (vermutlich außerhalb der `Page Area`) 

```{figure} Inkscape/Untitled_13.png 
--- 
width: 500px 
name: Untitled_13
--- 
caption 
``` 

**AUSWAHL TOOL**
(`S`) oder (`Icon` in der `Toolbox` (links))

**Blockieren** Sie die Ebene "**Recherchematerial"** anschließend mit dem **Klick auf das Schloss** neben dem Namen im Ebenenfenster.

### Objekterstellung `Rechteck-Tool`

Wählen Sie nun die "**Ebene 1**" aus benennen Sie diese um in "**Solarzelle**" (Doppelklick auf den Namen im Ebenenfenster)

Objekte werden immer in der ausgewählten Ebene erstellt. Wenn Sie kein Objekt erzeugen können kann es daran liegen, dass Sie eine Ebene ausgewählt haben die blockiert ist.

Wählen Sie das `Rechteck-Tool` aus

```{figure} Inkscape/Untitled_14.png 
--- 
width: 500px 
name: Untitled_14
--- 
caption 
``` 

**RECHTECK TOOL**
(`R`) oder (`Icon` in der `Toolbox` (links))

### Snapping

Wir wollen nun bei der Erstellung der Geometrie unser Gitter nutzen. 

Überprüfen Sie ob Sie die Standardeinstellung für das Snapping (Bild Rechts) so eingestellt haben.

Das **Ein** und **Ausschalten des Snapping** erfolgt über den **obersten Button** oder die Taste `%` (`SHIFT` + `5`)

Das **Snapping** ist auch hilfreich beim **ändern der Größe** oder **beim verschieben.**

Wenn Sie mit dem Cursor **über das jeweilige Feld in der Snapping Leiste rechts** fahren wird Ihnen erklärt was jede Option genau macht.

```{figure} Inkscape/Untitled_15.png 
--- 
width: 500px 
name: Untitled_15
--- 
caption 
``` 

Erstellen Sie nun mit dem `Rechteck Tool` ein den unteren blauen Bereich der Solarzelle (*z.B. in Breite 70mm und Höhe 50mm*)

```{figure} Inkscape/Untitled_16.png 
--- 
width: 500px 
name: Untitled_16
--- 
caption 
``` 

Falls Sie das Gitter ausgeblendet haben, können Sie es mit `#` wieder einblenden,

### Füllung und Kontur

Flächenobjekte (wie z.B. Rechtecke und Kreise) haben immer eine Füllung und eine Kontur. Beides kann eine Farbe haben oder nicht vorhanden sein. Weiterhin kann man den Linientyp ändern (dazu gleich später mehr). 

 

**Von der ausgewählten Geometrie** wird unten links wird immer die **Kontur**- und **Füllfarbe** angezeigt, sowie die **Konturdicke** und die **aktuelle Ebene**

```{figure} Inkscape/Stroke_Fill.png 
--- 
width: 500px 
name: Stroke_Fill
--- 
caption 
``` 

Mit Rechtsklick auf die Konturdicke kann diese geändert werden. 

Änderung der **Konturfarbe** : `SHIFT` + `Mausklick auf Farbe (aus Palette unten)`

Änderung der **Füllfarbe** :  `Mausklick auf Farbe (aus Palette unten)`

Möchte man die Kontur ausstellen kann man mit `SHIFT` + `Mausklick auf das X (ganz links in der Palette)`. Gleiches funktioniert für die Füllung (ohne die `Shift` Taste)

Hier wird die Einstellung der Konturdicke sowie das Ausstellen der Kontur und die Einstelliung der Füllfarbe demonstriert:

```{figure} Inkscape/Fill_Stroke.gif 
--- 
width: 500px 
name: Fill_Stroke
--- 
caption 
``` 

Es wird wird jedoch **empfohlen Farben mit weniger Sättigung zu nehme**n. Dazu gibt es im Bereich der Farbpaletten einige Auswahl. 

```{figure} Inkscape/Untitled_17.png 
--- 
width: 500px 
name: Untitled_17
--- 
caption 
``` 

Eine weitere Möglichkeit wäre mit  `Füllung und Kontur` 

```{figure} Inkscape/Untitled_18.png 
--- 
width: 500px 
name: Untitled_18
--- 
caption 
``` 

**FÜLLUNG UND KONTUR** 
(`Shift` + `STR` + `F`) oder (`Icon` in der `Commands-Bar` (oben))

```{figure} Inkscape/Untitled_19.png 
--- 
width: 500px 
name: Untitled_19
--- 
caption 
``` 

Im Reiter `Füllung`  kann über die Option `HSL` folgenes eingestellt werden:

- `H` der Hue (also die Farbe)
- `S` die Sättigung (wie intensiv ist die Farbe)
- `L` die Helligkeit
- `A` der Alphawert (also die Transparenz)

### Pipetten Tool

Zuletzt kann die Füllung noch mit dem Pipetten Tool (z.B. aus unserer Referenz gezogen werden)

```{figure} Inkscape/Untitled_20.png 
--- 
width: 500px 
name: Untitled_20
--- 
caption 
``` 

**PIPETTEN TOOL**
(`R`) oder (`Icon` in der `Toolbox` (links))

mit der Tastenkombination `Shift` + `Mausklick auf den Farbbereich` kann die Farbe auch für die **Kontur** übernommen werden

```{figure} Inkscape/Pipette.gif 
--- 
width: 500px 
name: Pipette
--- 
caption 
``` 

Erstellen Sie nun ein **weiteres Rechteck über dem ersten mit einer dunkleren Farbe**  
(*z.B. in Breite 70mm und Höhe 30mm*)

So sollte unsere Solarzelle jetzt nun aussehen:

```{figure} Inkscape/Untitled_21.png 
--- 
width: 500px 
name: Untitled_21
--- 
caption 
``` 

### Bezierkurven Tool

Wir zeichnen nun die **Linie zwischen den zwei Bereichen** mit dem `Bezierkurven Tool`

```{figure} Inkscape/Untitled_22.png 
--- 
width: 500px 
name: Untitled_22
--- 
caption 
``` 

**BEZIERKURVEN TOOL**
(`B`) oder (`Icon` in der `Toolbox` (links))

Wählen Sie das `Bezierkurven Tool` und zeichnen Sie eine `weiße Linie` der `Dicke 0,75mm` zwischen die zwei Rechtecke

Um den **Endpunkt** beim `Bezierkurven Tool` zu setzen müssen die einen `Doppelklick` verwenden

```{figure} Inkscape/Mittellinie.gif 
--- 
width: 500px 
name: Mittellinie
--- 
caption 
``` 

Duplizieren Sie die mittlere Linie (`Str` +`D`) und verschieben Sie diese mit `SHIFT` + `PFEILTASTE HOCH` zwei mal nach oben. Wiederholen Sie den Vorgang um eine Linie unterhalb zu erzeugen.

```{figure} Inkscape/Mittellinie-duplizieren.gif 
--- 
width: 500px 
name: Mittellinie-duplizieren
--- 
caption 
``` 

Selektieren Sie die obere und untere Linie und öffnen Sie `Füllung und Kontur` (`Shift` + `Str` + `F`) und wählen Sie einen `Liniendicke von 0,4mm` und einen `gepunkteten Linientyp` Ihrer Wahl.

### Füllung und Kontur (Linientyp)

```{figure} Inkscape/Untitled_18.png 
--- 
width: 500px 
name: Untitled_18
--- 
caption 
``` 

**FÜLLUNG UND KONTUR** 
(`Shift` + `STR` + `F`) oder (`Icon` in der `Commands-Bar` (oben))

```{figure} Inkscape/Untitled_23.png 
--- 
width: 500px 
name: Untitled_23
--- 
caption 
``` 

Erstellen Sie **ein positiv geladenes Teilchen** mit dem `Kreis Tool` (Shift gedrückt halten für Kreis) und dem `Bezierkurven-Tool` mit `weißer Farbe` und einer Linienstärke von `0,5mm`

### Kreis/Ellipse/Bogen Tool

```{figure} Inkscape/Untitled_24.png 
--- 
width: 500px 
name: Untitled_24
--- 
caption 
``` 

**KREIS/ELLIPSE/BOGEN TOOL**
(`E`) oder (`Icon` in der `Toolbox` (links))

**Kreis/Ellipse** vom **Mittelpunkt** aus erstellen**: `SHIFT`** gedrückt halten

**Kreis** erstellen**: `STR`** gedrückt halten

```{figure} Inkscape/Untitled_25.png 
--- 
width: 500px 
name: Untitled_25
--- 
caption 
``` 

Wenn Sie nur eine **Kreiskontur** erstellen wollen, **entfernen Sie vorher die Füllung** (`Mausklick auf X` in der Farbpalette) und wählen Sie eine **Farbe für die Kontur** (`Shift` + `Mausklick auf Farbe in Palette`) 

So würde dies dann aussehen:

```{figure} Inkscape/Elektronen.gif 
--- 
width: 500px 
name: Elektronen
--- 
caption 
``` 

### Gruppieren

**Neben den Ebenen** gibt es eine **weitere Möglichkeit der** **Strukturierung** von Objekten, dies ist die Gruppierung. In unserem Fall können wir unsere positiv geladenes Teilchen (`Kreis` mit dem `+ Symbol`) als eine Gruppe zusammenfassen um diese Gruppe dann durch einen Klick auswählen und damit einfacher zu positionieren.

```{figure} Inkscape/Untitled_26.png 
--- 
width: 500px 
name: Untitled_26
--- 
caption 
``` 

**GRUPPIERUNG ERSTELLEN** 
`Objekte auswählen` + `STR` + `G` oder (`Icon` in der `Commands-Bar` (oben))

```{figure} Inkscape/Untitled_27.png 
--- 
width: 500px 
name: Untitled_27
--- 
caption 
``` 

**GRUPPIERUNG AUFHEBEN** 
`Gruppierung auswählen` + `STR` +  `SHIFT` +  `G`  oder (`Icon` in der `Commands-Bar` (oben))

**Duplizieren** Sie das positive Teilchen und verschieben es, so das man beide sehe kann. Anschließend löschen Sie die vertikale Linie um ein negativ geladenes Teilchen zu erstellen. Anschließend Gruppieren (`STR`+`G`) Sie beide Teilchen jeweils einzeln wieder. 

Nun wollen wir jeweils `3 positive` und `3 negative` Teilchen auf der Solarzelle verteilen. Dafür müssen wir diese jeweils Duplizieren (`STR`+`D`) und diese bewegen bzw. ausrichten. Wie dies geschieht erfahren wir im folgenden:

### Objekte bewegen

Prinzipiell gibt es drei Möglichkeiten zur Positionierung von Objekten

1. Mit der `Maus` (mit/ohne [Snapping]())
2. Mit den `Pfeiltasten` in definierten Schritten (klein/normal/groß) 
3. Mit dem Tool `Objekte Ausrichten`

Ich persönlich benutze am meisten das `Objekte Ausrichten` Tool, weil es am vielfältigsten ist und man die Sachen genau ausrichten kann.

### Objekt Bewegung mit den Pfeiltasten ⬅️/➡️/⬆️/⬇️

Dies ist besonders hilfreich wenn man Objekte dupliziert (`STR`+`D`) und diese dann in einem definierten Abstand davon weg bewegen will 

Ich nutze oft die Option mit den großen Schritten (`SHIFT`+`PFEILTASTEN`) und zähle dann z.B. die Schritte um es bei der Wiederholung im gleichen Abstand zu erstellen.

**BEWEGUNG MIT DEN PFEILTASTEN**

**kleiner** Bewegungsschritt**:**  `ALT` +  ⬅️/➡️/⬆️/⬇️ 

**normaler** Bewegungsschritt**:**   ⬅️/➡️/⬆️/⬇️ 

**großer** Bewegungsschritt**:**  `SHIFT` +  ⬅️/➡️/⬆️/⬇️ 

### Objekt Bewegung mit dem `Objekte Ausrichten` Tool

```{figure} Inkscape/Untitled_28.png 
--- 
width: 500px 
name: Untitled_28
--- 
caption 
``` 

**OBJEKTE AUSRICHTEN** 
(`Shift` + `STR` + `A`) oder (`Icon` in der `Commands-Bar` (oben))

Wir beschränken uns zunächst auf den **Ausrichten Teil** des Tools:

```{figure} Inkscape/Untitled_29.png 
--- 
width: 500px 
name: Untitled_29
--- 
caption 
``` 

Wenn wir an einem Objekt ausrichten wollen was in einer Gruppierung ist, müssen wir dieses ggf aus der Gruppierung entfernen (`STR` + `SHIFT` + `G`)

Wir starten mit dem Ausrichten Relativ zu `Zuletzt gewählt` und wollen **nun ein Teilchen** **mittig an einer Linie** (**die wir zuletzt auswählen**) ausrichten:

```{figure} Inkscape/Ausrichten_vertikal-mittig.gif 
--- 
width: 500px 
name: Ausrichten_vertikal-mittig
--- 
caption 
``` 

```{figure} Inkscape/Untitled_30.png 
--- 
width: 500px 
name: Untitled_30
--- 
caption 
``` 

Nun wollen wir, dass das Teilchen direkt an der Oberkante unseres unteren Rechtecks liegt. Damit wir das untere Rechteckt anklicken können muss man es ggf. aus der Gruppierung entfernen (`Gruppierung auswählen` + `STR` + `SHIFT` + `G`)

```{figure} Inkscape/Ausrichten_vertikal-unterkante.gif 
--- 
width: 500px 
name: Ausrichten_vertikal-unterkante
--- 
caption 
``` 

```{figure} Inkscape/Untitled_31.png 
--- 
width: 500px 
name: Untitled_31
--- 
caption 
``` 

Neben der vertikalen Ausrichtung gibt es das gleiche natürlich auch für die horizontale Ausrichtung

Zur Veranschaulichung der **Verteilungsfunktion** habe ich ein paar mehr Teilchen erstellt, dies ist nicht Teil der finalen Abbildung

Besonders praktisch ist die Funktion `Verteilen` die sich unterhalb von Ausrichten befindet. Hier ein Beispiel wo wir zunächst vertikal ausrichten am letzten Objekt und diese  Objekte anschließend im gleichen Abstand verteilen

```{figure} Inkscape/Verteilen1.gif 
--- 
width: 500px 
name: Verteilen1
--- 
caption 
``` 

```{figure} Inkscape/Untitled_32.png 
--- 
width: 500px 
name: Untitled_32
--- 
caption 
``` 

Wenn wir nun die äußerste Teilchen weiter nach außen bewegen und dann neu verteilen sie es so aus:

```{figure} Inkscape/Verteilen2.gif 
--- 
width: 500px 
name: Verteilen2
--- 
caption 
``` 

```{figure} Inkscape/Untitled_33.png 
--- 
width: 500px 
name: Untitled_33
--- 
caption 
``` 

Nun könnte man z.B. alle 7 Teilchen gruppieren (`STR`+`G`) und diese Gruppe wiederum z.B. an der Linie ausrichten

```{figure} Inkscape/Verteilen2-ausrichten3.gif 
--- 
width: 500px 
name: Verteilen2-ausrichten3
--- 
caption 
``` 

```{figure} Inkscape/Untitled_34.png 
--- 
width: 500px 
name: Untitled_34
--- 
caption 
``` 

Besonders praktisch ist die Funktion, wenn man wie im unten gezeigten Beispiel ein Objekt dupliziert (das Duplikat ist dann automatisch ausgewählt) und danach ein Referenzobjekt zur Ausrichtung auswählen, an dessen man das neue Duplikat ausrichten möchte

```{figure} Inkscape/Duplizieren_ausrichten.gif 
--- 
width: 500px 
name: Duplizieren_ausrichten
--- 
caption 
``` 

```{figure} Inkscape/Untitled_35.png 
--- 
width: 500px 
name: Untitled_35
--- 
caption 
``` 

Neben `Zuletzt gewählt` gibt es viele andere Referenzmöglichkeiten. 

Ich persönlich nutze fast immer `Zuletzt gewählt` und in seltenen Fällen `Seite` als Referenz.

```{figure} Inkscape/Untitled_36.png 
--- 
width: 500px 
name: Untitled_36
--- 
caption 
``` 

Verteilen Sie die Teilchen so wie unten in dem Bild und benutzen Sie dafür das `Ausrichten Tool`

```{figure} Inkscape/Untitled_37.png 
--- 
width: 500px 
name: Untitled_37
--- 
caption 
``` 

Damit die gepunktete Linie nicht im Kreis sichtbar ist, kann man mit dem `Pipetten-Tool` die **Füllung der Rechtecke** übernehmen. 

```{figure} Inkscape/Untitled_38.png 
--- 
width: 500px 
name: Untitled_38
--- 
caption 
``` 

Ohne Füllung im Kreis

```{figure} Inkscape/Untitled_39.png 
--- 
width: 500px 
name: Untitled_39
--- 
caption 
``` 

Mit Füllung im Kreis

### Objektgröße ändern

Um die Objektgröße zu ändern gibt es drei Optionen:

1. Im Objekt selber 
2. In der `Tool-Control-Bar`
3. Mit dem `Transformations` Tool 

Wir behandeln zunächst die ersten zwei, das `Transformation-Tool` lernen wir später kennen.

### Objektgröße im Objekt ändern

```{figure} Inkscape/Gre_aendern_Objekt_mit_Snapping.gif 
--- 
width: 500px 
name: Gre_aendern_Objekt_mit_Snapping
--- 
caption 
``` 

```{figure} Inkscape/Untitled_40.png 
--- 
width: 500px 
name: Untitled_40
--- 
caption 
``` 

**`Snapping` An**

```{figure} Inkscape/Untitled_41.png 
--- 
width: 500px 
name: Untitled_41
--- 
caption 
``` 

`Knoten/Pfad einrasten` 
**`Eckpunkte**einrasten` ****

Hier ist der Eckpunkt im Gitter eingerastet,, wenn dieser im Bild nicht sichtbar ist, funktioniert das Einrasten auch nicht. 

Aktivieren wir den Punkt Mittelpunkte einrasten, kann auch der Mittelpunkt einrasten, was uns im Zoom hilft, weil wir hier die Eckpunkte nicht sehen.

```{figure} Inkscape/Gre_aendern_Objekt_mit_Snapping_Mittelpunkt.gif 
--- 
width: 500px 
name: Gre_aendern_Objekt_mit_Snapping_Mittelpunkt
--- 
caption 
``` 

```{figure} Inkscape/Untitled_40.png 
--- 
width: 500px 
name: Untitled_40
--- 
caption 
``` 

**`Snapping` An**

```{figure} Inkscape/Untitled_42.png 
--- 
width: 500px 
name: Untitled_42
--- 
caption 
``` 

`Knoten/Pfad einrasten` 
**`Mittelpunkte** einrasten` ****

Komplett ohne Snapping geht es natürlich auch. Das ist besonders hilfreich wenn man dünne Strukturen erstellen will die kleiner als das Gitter sind

```{figure} Inkscape/Gre_aendern_Objekt_ohne_Snapping.gif 
--- 
width: 500px 
name: Gre_aendern_Objekt_ohne_Snapping
--- 
caption 
``` 

```{figure} Inkscape/Untitled_43.png 
--- 
width: 500px 
name: Untitled_43
--- 
caption 
``` 

**`Snapping` Aus**

### Größe eines Kontur ändern (mit/ohne) Skalierung

Wenn Sie die Größe Ihrer Teilchen ändern und die Position behalten, so müssen sie STR+SHIFT gedrückt halten. Zusätzlich gibt es in der `Tool-Control-Bar` eine Option die definiert ob sich die Kontur mit skaliert wird. Schauen wir uns dies mal im Beispiel an:

```{figure} Inkscape/Objektvergroeserung_ohne_Kontur.gif 
--- 
width: 500px 
name: Objektvergroeserung_ohne_Kontur
--- 
caption 
``` 

```{figure} Inkscape/Untitled_44.png 
--- 
width: 500px 
name: Untitled_44
--- 
caption 
``` 

`Konturskalierung` Aus

```{figure} Inkscape/Objektvergroeserung_mit_Kontur.gif 
--- 
width: 500px 
name: Objektvergroeserung_mit_Kontur
--- 
caption 
``` 

```{figure} Inkscape/Untitled_45.png 
--- 
width: 500px 
name: Untitled_45
--- 
caption 
``` 

`Konturskalierung` An

### Objektgröße in der `Tool-Control-Bar`

Wollen wir die Höhe genau auf einen Wert einstellen, so kann man dies über die `Tool-Control-Bar` machen.

```{figure} Inkscape/Untitled_46.png 
--- 
width: 500px 
name: Untitled_46
--- 
caption 
``` 

**Position (x/y) ändern**

```{figure} Inkscape/Untitled_47.png 
--- 
width: 500px 
name: Untitled_47
--- 
caption 
``` 

**Breite/Höhe ändern + Seitenverhältnis sperren**

```{figure} Inkscape/Untitled_48.png 
--- 
width: 500px 
name: Untitled_48
--- 
caption 
``` 

**Einheit festlegen**

```{figure} Inkscape/Untitled_49.png 
--- 
width: 500px 
name: Untitled_49
--- 
caption 
``` 

```{figure} Inkscape/Gre_aendern_ToolContBar.gif 
--- 
width: 500px 
name: Gre_aendern_ToolContBar
--- 
caption 
``` 

### Objektgröße mit dem `Transformations` Tool

Wollen wir nun ein Objekt **prozentual skalieren** oder **mehrere Objekte gleichzeitig ändern**, so ist das `Transformations` Tool das Mittel der Wahl

```{figure} Inkscape/Untitled_50.png 
--- 
width: 500px 
name: Untitled_50
--- 
caption 
``` 

**TRANSFORMATION** 
(`Shift` + `STR` + M) oder (`Menu bar` → `Objekt`→  `Transformation..`)

```{figure} Inkscape/Untitled_51.png 
--- 
width: 500px 
name: Untitled_51
--- 
caption 
``` 

Wollen wir z.B. alle Teilchen gleichzeitig skalieren (jedes Teilchen muss dabei eine eigene Gruppe sein) so kann dies der Option ☑️`Auf jedes Objekt getrennt anwenden` erfolgen 

```{figure} Inkscape/Transformation_Individuell3.gif 
--- 
width: 500px 
name: Transformation_Individuell3
--- 
caption 
``` 

```{figure} Inkscape/Untitled_52.png 
--- 
width: 500px 
name: Untitled_52
--- 
caption 
``` 

```{figure} Inkscape/Untitled_53.png 
--- 
width: 500px 
name: Untitled_53
--- 
caption 
``` 

Zeichnen Sie nun noch **zwei graue Metallkontakte ohne Kontur** auf der Oberseite mit dem `Rechteck` Tool. Verwenden Sie das `Pipetten` Tool um die gleiche Füllfarbe wie im unteren Kontakt zu erhalten.

```{figure} Inkscape/Untitled_54.png 
--- 
width: 500px 
name: Untitled_54
--- 
caption 
``` 

### Linien mit Pfeilen

Zeichnen Sie **einen Pfeil von oberen negativen Teilchen zum Kontakt** mit dem `Bezierkurven` Tool und `Füllung und Kontur` 

**Zur Erinnerung:**

```{figure} Inkscape/Untitled_22.png 
--- 
width: 500px 
name: Untitled_22
--- 
caption 
``` 

**BEZIERKURVEN TOOL**
(`B`) oder (`Icon` in der `Toolbox` (links))

```{figure} Inkscape/Untitled_18.png 
--- 
width: 500px 
name: Untitled_18
--- 
caption 
``` 

**FÜLLUNG UND KONTUR** 
(`Shift` + `STR` + `F`) oder (`Icon` in der `Commands-Bar` (oben))

Will man eine **vertikale Linie** mit dem **`Bezierkurven`** Tool erzeugen muss man `STR` **gedrückt** halten 

```{figure} Inkscape/Linie_mit_Pfeil.gif 
--- 
width: 500px 
name: Linie_mit_Pfeil
--- 
caption 
``` 

Wenn Sie nun die Länge des Pfeiles ändern wollen ohne die Linienstärke zu ändern, müssen Sie die Option der Konturskalierung (in der `Tool-Control-Bar`) **ausschalten**

```{figure} Inkscape/Untitled_55.png 
--- 
width: 500px 
name: Untitled_55
--- 
caption 
``` 

Wählen Sie eine entsprechende eine `Pfeilgeometrie` , `Liniendicke` und `Farbe` aus 

In meinem Fall habe ich eine **Liniendicke von 0,3mm** verwendet und das **erste Gelb unten in der Palette** verwendet.

```{figure} Inkscape/Untitled_56.png 
--- 
width: 500px 
name: Untitled_56
--- 
caption 
``` 

```{figure} Inkscape/Spiegeln.gif 
--- 
width: 500px 
name: Spiegeln
--- 
caption 
``` 

Den oberen Pfeil können Sie durch **duplizieren** (`STR`+`D`) und **spiegeln** auch für die Unterseite verwenden

Erstellen Sie nun einen zweiten Pfeil zwischen den mittleren Teilchen

**Ein möglicher Lösungsweg:** 

1. Den ersten Pfeil **duplizieren** (`STR` + `D`) 
2. Mit `Ausrichten` den duplizierten Pfeil **mittig vom Teilchen ausrichten**

```{figure} Inkscape/Untitled_35.png 
--- 
width: 500px 
name: Untitled_35
--- 
caption 
``` 

3. In `Füllung und Kontur` die zweite `Knotenmarkierung` einstellen damit Pfeil in beide Richtungen zeigt

```{figure} Inkscape/Untitled_57.png 
--- 
width: 500px 
name: Untitled_57
--- 
caption 
``` 

4. Vertikale Position mit `Pfeiltasten` + `SHIFT` grob einstellen 
5. **Länge des Pfeils direkt am Objekt final einstellen** 

```{figure} Inkscape/Untitled_58.png 
--- 
width: 500px 
name: Untitled_58
--- 
caption 
``` 

Somit ist unsere Solarzelle erstmal fertig:

Ich habe die höhe des unteren Kontaktes noch mal erhöht, damit der Pfeil auch im Kontakt zu sehen ist

```{figure} Inkscape/Untitled_59.png 
--- 
width: 500px 
name: Untitled_59
--- 
caption 
``` 

Blockieren Sie nun die `Ebene` "**Solarzelle**" (da wir damit erstmal fertig sind) und erstellen Sie eine neue `Ebene` "**Sonne**" über der **Ebene** "**Solarzelle".**

## Erstellung der Sonne

Wir wollen nun die Sonne zeichnen und lernen dabei die `Objekt-Hierarchie` und nachfolgend die `boolschen Operationen` kennen.

So soll die Sonne final aussehen: 
(erstmal nur in Schwarz)

```{figure} Inkscape/Untitled_60.png 
--- 
width: 500px 
name: Untitled_60
--- 
caption 
``` 

Um dies zu erreichen, erstellen wir Linien mit dem `Bezierkurven` Tool  und Kreise mit/ohne Kontur mit dem `Kreis` Tool und legen die verschiedenen Objekte so übereinander, dass bestimmte Bereiche verdeckt sind und somit die Sonne entsteht.

Da der Trick mit weißen Konturen und Füllungen arbeitet wurde zur Erstellung ein grauer Hintergrund (ein großes graues Rechteck) verwendet um die Technik besser sichtbar zu machen

```{figure} Inkscape/Sonne1.png 
--- 
width: 500px 
name: Sonne1
--- 
caption 
``` 

Links die Übereinanderlagerung der Objekte, rechts das gleiche mit zusätzlich weißen Hintergrund

**Wir erstellen also:**

- Linien (L1) für die Sonnenstrahlen
- zwei Ringe (R1 und R2)  die die Sonnenstrahlen innen und außen abgrenzen
- ein Kreis (K1) der die Sonne darstellt

```{figure} Inkscape/Sonne2.png 
--- 
width: 500px 
name: Sonne2
--- 
caption 
``` 

**Tipps zum Erstellen der Sonnenstrahlen**

1. Durch Doppelklick auf das Objekt können diese gedreht werden

```{figure} Inkscape/Untitled_61.png 
--- 
width: 500px 
name: Untitled_61
--- 
caption 
``` 

2. Wird das Objekt an dem äußeren Rand gedreht kann durch gleichzeitiges drücken von `STR` in definierten Winkeln gedreht werden

```{figure} Inkscape/Untitled_62.png 
--- 
width: 500px 
name: Untitled_62
--- 
caption 
``` 

### Objekthierarchie

Mit Objekthierarchie ist gemeint, in welcher Reihenfolge die Objekte übereinander liegen und sich dadurch teilweise überdecken.

In der `Tools-Control-Bar` finden sich folgende Buttons zur Veränderung der Objekthierarchie. 

```{figure} Inkscape/Untitled_63.png 
--- 
width: 500px 
name: Untitled_63
--- 
caption 
``` 

Ebenfalls zu finden unter  `Menu Bar` → `Objekt` 

```{figure} Inkscape/Untitled_64.png 
--- 
width: 500px 
name: Untitled_64
--- 
caption 
``` 

Da ich diese Funktion sehr oft benutze, habe ich für `Anheben` und `Absenken` einen ShortCut auf meine Maus gelegt, das beschleunigt den Workflow enorm.

Hier wird gezeigt wie durch das Anheben und Absenken des Objektes sich die Sichtbarkeit verändert

```{figure} Inkscape/Objekthierarchie.gif 
--- 
width: 500px 
name: Objekthierarchie
--- 
caption 
``` 

Wollen Sie ein **Objekt durch ein darauf liegendes hindurch selektieren,** so halten Sie `ALT` gedrückt während der Auswahl

```{figure} Inkscape/Objekt_Selektion_Drunterliegend.gif 
--- 
width: 500px 
name: Objekt_Selektion_Drunterliegend
--- 
caption 
``` 

Erstellen Sie nun mit Hilfe der gezeigten Methoden die Sonne und färben Sie diese am Ende gelb.

### Linie bearbeiten mit `Edit Path by Nodes` Tool

Erstellen Sie nun mit dem `Bezierkurven` Tool ein Pfeil von der Sonne bis zur Grenzschicht

Wenn Sie nur den Start und Endpunkt der Linie bearbeiten wollen, empfiehlt es sich das `Edit Path by Nodes` Tool zu verwenden.

```{figure} Inkscape/Untitled_65.png 
--- 
width: 500px 
name: Untitled_65
--- 
caption 
``` 

**EDIT PATH BY NODES TOOL**
(`N`) oder (`Icon` in der `Toolbox` (links))

 

Das Tool erlaubt auf die **Knotenpunkte des Objektes** zuzugreifen und diese zu verschieben.

```{figure} Inkscape/EditPathByNodes.gif 
--- 
width: 500px 
name: EditPathByNodes
--- 
caption 
``` 

Blockieren Sie nun die `Ebene` "**Sonne**" und erzeugen Sie eine neue `Ebene` "**Beschriftung**"

## Beschriftung

Zur Beschriftung verwenden wir Linien mit dem `Bezierkurven` Tool und Text mit dem `Text` Tool 

```{figure} Inkscape/Untitled_66.png 
--- 
width: 500px 
name: Untitled_66
--- 
caption 
``` 

**TEXT TOOL**
(T) oder (`Icon` in der `Toolbox` (links))

Zum Text Tool gibt es in der `Tool-Control-Bar` die allseits bekannten Einstellungen zur Textgestaltung

 

```{figure} Inkscape/Untitled_67.png 
--- 
width: 500px 
name: Untitled_67
--- 
caption 
``` 

Bei Text bietet sich das Ausrichten besonders gut an

```{figure} Inkscape/Untitled_28.png 
--- 
width: 500px 
name: Untitled_28
--- 
caption 
``` 

**OBJEKTE AUSRICHTEN** 
(`Shift` + `STR` + `A`) oder (`Icon` in der `Commands-Bar` (oben))

**Ausrichtung des Textes in der richtigen Höhe des Objektes** was beschriftet werden soll

```{figure} Inkscape/Text_an_Objekt_Ausrichten.gif 
--- 
width: 500px 
name: Text_an_Objekt_Ausrichten
--- 
caption 
``` 

```{figure} Inkscape/Untitled_34.png 
--- 
width: 500px 
name: Untitled_34
--- 
caption 
``` 

**Ausrichtung aller Beschriftungen zueinander** (linksbündig)

```{figure} Inkscape/Text_an_Text_Ausrichten.gif 
--- 
width: 500px 
name: Text_an_Text_Ausrichten
--- 
caption 
``` 

```{figure} Inkscape/Untitled_68.png 
--- 
width: 500px 
name: Untitled_68
--- 
caption 
``` 

Erstellen Sie die restliche Beschriftung mit den bisher gelernten Methoden

## Vorbereitungen zum Export

### Größe aller Objekte zusammen ändern

Falls Ihre Grafik doch größer geworden ist, als Sie wollten, so können Sie dies zum Schluss noch mal anpassen.

**Hierbei gibt es jedoch einige Punkte zu beachten:**

1. Bei der Skalierung alle Objekte **selektieren**, aber **nie gruppieren**!

    Durch die Gruppierung über alle Ebenen werden alle Objekte zur aktivieren Ebene gezogen, die anderen Ebenen haben dann also keinen Inhalt mehr.

2. Wenn Sie wollen, dass sich die **Konturbreite** **nicht mit skaliert** wird, müssen Sie die **Option** der **Konturskalierung** (in der `Tool-Control-Bar`) **ausschalten**

```{figure} Inkscape/Untitled_55.png 
--- 
width: 500px 
name: Untitled_55
--- 
caption 
``` 

### Seitengröße an Zeichnung anpassen

Markieren Sie alle Objekte die zum Bild gehören sollen und öffnen anschließend die `Dokumenteneinstellung` mit der Option `Ändern der Seitegröße auf Inhalt ...`

**DOKUMENTENEINSTELLUNGEN**
(`SHIFT` + `STR` + `D`) oder (`Menu bar` → `Datei` →  `Dokumenteneinstellungen...`)

**Reiter**: **`Seite`**

```{figure} Inkscape/Untitled_69.png 
--- 
width: 500px 
name: Untitled_69
--- 
caption 
``` 

Hier können Sie noch wenn gewünscht einen Rand eingeben und dann durch den Button `Seitengröße auf Zeichnungs-/Auswahlgröße anpassen` die Seitengröße neu einstellen. So würde dies dann z.B. mit dem Rändern von 5mm aussehen:

```{figure} Inkscape/Groesse_an_Inhalt_Anpassen.gif 
--- 
width: 500px 
name: Groesse_an_Inhalt_Anpassen
--- 
caption 
``` 

### Hintergrundfarbe (für Export) einstellen

Um den Einfluss der Hintergrundfarbe und des Randes beim Export zu verdeutlichen, habe ich die Grafik in drei verschiedenen Varianten exportiert und auf einem Hintergrund mit Farbverlauf eingefügt.

```{figure} Inkscape/Untitled_70.png 
--- 
width: 500px 
name: Untitled_70
--- 
caption 
``` 

**png** transparent

**MIT TRANSPARENTEM HINTERGRUND**

- ✅ kann z.B. in Powerpoint Präsentationen (bei Folien die nicht weiß sind) besser aussehen
- ❌ Unser Trick bei der Sonne funktioniert so nicht mehr (kann aber auch anders gelöst werden)

```{figure} Inkscape/Untitled_71.png 
--- 
width: 500px 
name: Untitled_71
--- 
caption 
``` 

**png** weißer Hintergrund **ohne** Rand

**MIT WEISSEN HINTERGRUND OHNE RAND**

- Genau das Gegenteil zum vorherigen Beispiel. Es sieht bei nicht-weißem Hintergrund oft nicht schön aus, dafür fällt der Trick bei der Sonne nicht mehr auf
- Zusätzlich fällt es auf, dass kein Rand verwendet wurde, wodurch der Text im Außenbereich nicht so schön lesbar ist

```{figure} Inkscape/Untitled_72.png 
--- 
width: 500px 
name: Untitled_72
--- 
caption 
``` 

**png** weißer Hintergrund **mit** Rand

**MIT WEISSEN HINTERGRUND MIT RAND**

- durch den zusätzlichen Rand wirkt das Bild harmonischer und der Text ist nun auch besser lesbar

**Grundsätzlich gibt es zwei Varianten einen Hintergrund für den Export einzustellen:**

1. **Einen Hintergrund als Objekt erstellen**
    - Ebene "Hintergrund" erstellen und diese ganz unten einfügen.
    - Rechteck ziehen mit dem `Rechteck Tool` und Farbe vergeben
    - ggf. kann snapping für die Seitenränder aktiviert werden damit genau die Größe des Seitenrandes verwendet werden kann

```{figure} Inkscape/Untitled_73.png 
--- 
width: 500px 
name: Untitled_73
--- 
caption 
``` 

2. **Hintergrundfarbe** in `Seiteneinstellungen` (`Shift` + `Str` + `D`) 

```{figure} Inkscape/Untitled_74.png 
--- 
width: 500px 
name: Untitled_74
--- 
caption 
``` 

    - Wenn Sie das `Icon für den Hintergrund` (siehe Bild oben) anklicken können sie mit dem Schieber A den **Alpha-Wert** (also die Transparenz ändern)
        - A=100 (ohne Transparenz)
        - A=0 (voll Transparenz)
    - Standardwert ist `#ffffff00`

### [`PixelGrafik`] Export als `png`

**PNG-BILD EXPORTIEREN**
(`SHIFT` + `STR` + `E`) oder (`Menu bar` → `Datei` →  `PNG-Bild exportieren...`)

```{figure} Inkscape/Untitled_75.png 
--- 
width: 500px 
name: Untitled_75
--- 
caption 
``` 

**Hierbei wichtige Einstellungen:**

**`Exportbereich`**: `Seite` / `Zeichnung` / `Auswahl` wird exportiert

**`Bildgröße`**: Vorgabe von dpi (Seitengröße wird angepasst) oder Vorgabe von Breite bzw. Höhe (dpi wird angepasst)

**`Dateiname`**: Pfad mit Dateinamen angeben

**`Exportieren`: Zum Speichern `Exportieren` drücken!**

### [`VektorGrafik`] Speichern als `svg`

**DATEI SPEICHERN UNTER + Dateityp: Inkscape-SVG (*.svg)**
(`SHIFT` + `STR`+ `S`) oder (`Menu bar` → `Datei` →  `Speichern Unter...`)

Sie sollten die Datei immer als **Inkscape-SVG (*.svg)** speichern. Dies ist das native Inkscape Dateiformat in dem alle Eigenschaften (z.B. auch Ebenen) gespeichert werden können. Weiterhin können `.svg` manchmal auch Programmen direkt verwendet werden (z.B. in $\LaTeX$).

### [`VektorGrafik`] Speichern als `pdf`

Manchmal ist es auch sinnvoll die Datei als pdf zu speichern, dafür dann den Dateityp **Portable Document Format (*.pdf)** verwenden.

**DATEI SPEICHERN UNTER + Dateityp: Portable Document Format (*.pdf)**
(`SHIFT` + `STR`+ `S`) oder (`Menu bar` → `Datei` →  `Speichern Unter...`)

# Übungsbeispiele

## Alltag

```{figure} Inkscape/Untitled_76.png 
--- 
width: 500px 
name: Untitled_76
--- 
caption 
``` 

Quelle: [https://pixabay.com/de/illustrations/fahrrad-rad-bike-mountainbike-757914/](https://pixabay.com/de/illustrations/fahrrad-rad-bike-mountainbike-757914/)

```{figure} Inkscape/Untitled_77.png 
--- 
width: 500px 
name: Untitled_77
--- 
caption 
``` 

Quelle: [https://pixabay.com/de/vectors/schreibtisch-notizen-notizbuch-2906792/](https://pixabay.com/de/vectors/schreibtisch-notizen-notizbuch-2906792/)

```{figure} Inkscape/Untitled_78.png 
--- 
width: 500px 
name: Untitled_78
--- 
caption 
``` 

Quelle: [https://pixabay.com/de/vectors/android-handy-iphone-mobil-telefon-2027560/](https://pixabay.com/de/vectors/android-handy-iphone-mobil-telefon-2027560/)

## technisch

```{figure} Inkscape/Untitled_79.png 
--- 
width: 500px 
name: Untitled_79
--- 
caption 
``` 

Quelle: [https://www.researchgate.net/publication/7323590_Local_mechanical_properties_of_the_head_articulation_cuticle_in_the_beetle_Pachnoda_marginata_Coleoptera_Scarabaeidae](https://www.researchgate.net/publication/7323590_Local_mechanical_properties_of_the_head_articulation_cuticle_in_the_beetle_Pachnoda_marginata_Coleoptera_Scarabaeidae)

```{figure} Inkscape/Untitled_80.png 
--- 
width: 500px 
name: Untitled_80
--- 
caption 
``` 

Quelle: [https://www.researchgate.net/publication/7323590_Local_mechanical_properties_of_the_head_articulation_cuticle_in_the_beetle_Pachnoda_marginata_Coleoptera_Scarabaeidae](https://www.researchgate.net/publication/7323590_Local_mechanical_properties_of_the_head_articulation_cuticle_in_the_beetle_Pachnoda_marginata_Coleoptera_Scarabaeidae)

```{figure} Inkscape/Untitled_81.png 
--- 
width: 500px 
name: Untitled_81
--- 
caption 
``` 

Diese Skizze in schön :)

# Informationen zur Theorie

## Color

[https://youtu.be/_2LLXnUdUIc](https://youtu.be/_2LLXnUdUIc)

## Typography

[https://youtu.be/sByzHoiYFX0](https://youtu.be/sByzHoiYFX0)

[https://youtu.be/QrNi9FmdlxY](https://youtu.be/QrNi9FmdlxY)

## Layout and Composition

[https://youtu.be/a5KYlHNKQB8](https://youtu.be/a5KYlHNKQB8)

# Tutorials

**offizielle Inkscape Tutorials**: 
[https://inkscape.org/de/doc/tutorials/shapes/tutorial-shapes.html](https://inkscape.org/de/doc/tutorials/shapes/tutorial-shapes.html)

**YouTube**:

[https://youtu.be/qq7HsMvEVmU](https://youtu.be/qq7HsMvEVmU)

[https://youtu.be/XFFZXgBtNlg](https://youtu.be/XFFZXgBtNlg)

[https://youtu.be/ifLfVsI9UBE](https://youtu.be/ifLfVsI9UBE)

[https://youtu.be/KuETd1uIF8U](https://youtu.be/KuETd1uIF8U)

[https://youtu.be/eaWbzMs7-n4](https://youtu.be/eaWbzMs7-n4)

[https://youtu.be/s-kPg4vYKfk](https://youtu.be/s-kPg4vYKfk)

[https://youtu.be/WM2enc0pgls](https://youtu.be/WM2enc0pgls)

# Ressourcen

## Inspiration

[Logo inspiration](https://www.logomoose.com/)

Für Logos

## Stockfotos

[](https://pixabay.com/de/)

[Beautiful Free Images & Pictures | Unsplash](https://unsplash.com/)

## Schriftarten

[DOWNLOAD: Free Fonts - at Fontfabric™](https://www.fontfabric.com/free-fonts/)

## Color Themes

[Coolors - The super fast color schemes generator!](https://coolors.co/)

## Icons

[Endless Icons](http://endlessicons.com/)

## Imagecompressor

[Compressor.io - optimize and compress JPEG photos and PNG images](https://compressor.io/)