# Erstellung der Solarzelle

Wir wollen nun den **Aufbau** und die **Funktionen** von **Inskcape** direkt an Beispielen kennenlernen. Beginnend dazu verwenden wir eine Darstellung zum **schematischen Aufbau einer Solarzelle**.

## Recherchematerial

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

## Ebenen

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

## Snapping

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

## Füllung und Kontur

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

## Pipetten Tool

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

## Bezierkurven Tool

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

## Füllung und Kontur (Linientyp)

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

## Kreis/Ellipse/Bogen Tool

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

## Gruppieren

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

## Objekte bewegen

Prinzipiell gibt es drei Möglichkeiten zur Positionierung von Objekten

1. Mit der `Maus` (mit/ohne [Snapping]())
2. Mit den `Pfeiltasten` in definierten Schritten (klein/normal/groß) 
3. Mit dem Tool `Objekte Ausrichten`

Ich persönlich benutze am meisten das `Objekte Ausrichten` Tool, weil es am vielfältigsten ist und man die Sachen genau ausrichten kann.

## Objekt Bewegung mit den Pfeiltasten ⬅️/➡️/⬆️/⬇️

Dies ist besonders hilfreich wenn man Objekte dupliziert (`STR`+`D`) und diese dann in einem definierten Abstand davon weg bewegen will 

Ich nutze oft die Option mit den großen Schritten (`SHIFT`+`PFEILTASTEN`) und zähle dann z.B. die Schritte um es bei der Wiederholung im gleichen Abstand zu erstellen.

**BEWEGUNG MIT DEN PFEILTASTEN**

**kleiner** Bewegungsschritt**:**  `ALT` +  ⬅️/➡️/⬆️/⬇️ 

**normaler** Bewegungsschritt**:**   ⬅️/➡️/⬆️/⬇️ 

**großer** Bewegungsschritt**:**  `SHIFT` +  ⬅️/➡️/⬆️/⬇️ 

## Objekt Bewegung mit dem `Objekte Ausrichten` Tool

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

## Objektgröße ändern

Um die Objektgröße zu ändern gibt es drei Optionen:

1. Im Objekt selber 
2. In der `Tool-Control-Bar`
3. Mit dem `Transformations` Tool 

Wir behandeln zunächst die ersten zwei, das `Transformation-Tool` lernen wir später kennen.

## Objektgröße im Objekt ändern

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

## Größe eines Kontur ändern (mit/ohne) Skalierung

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

## Objektgröße in der `Tool-Control-Bar`

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

## Objektgröße mit dem `Transformations` Tool

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

## Linien mit Pfeilen

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
