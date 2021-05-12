# Unterschied `Objekt` / `Pfad`

## Objekt in Pfad umwandeln

In der Menüleiste unter `Pfad` → `Objekt in Pfad umwandeln` ( oder `Shift` + `Str` + `C` ) können Objekte in Pfade umgewandelt werden

```{figure} Inkscape_(Advanced)/Untitled.png 
--- 
width: 500px 
name: Untitled
--- 
caption 
``` 

## Pfadecken / Anstiege

Zeichnen Sie mit dem `Rechtecktool` ein Rechteck und benutzen Sie das `Edit Path by Nodes` Tool um die Ecken abzurunden

Konvertieren Sie das Rechteck mit dem abgerundeten Ecken in einen Pfad

```{figure} Inkscape_(Advanced)/Untitled_1.png 
--- 
width: 500px 
name: Untitled_1
--- 
caption 
``` 

Rechteck Objekt ohne Kantenverrundung

```{figure} Inkscape_(Advanced)/Untitled_2.png 
--- 
width: 500px 
name: Untitled_2
--- 
caption 
``` 

Rechteck Objekt mit Kantenverrundung

```{figure} Inkscape_(Advanced)/Untitled_3.png 
--- 
width: 500px 
name: Untitled_3
--- 
caption 
``` 

Rechteck Pfad mit einzelnen Knotenpunkten und Anstiegen

Durch die Überführung eines **Objektes** **in einen Pfad**, gehen **Objekteigenschaften verloren und können nicht wieder zurück transformiert werden.**

An den **Eckpunkten entstehen Knoten (**ggf. mit Anstiegen**).** 

**Linien** und **Objektkonturen** können auch in Pfade umgewandelt werden.

In unserem Fall geht also die Option verloren, die Verrundung an dem Rechteck zu ändern.

Versuchen Sie nun die Verrundung an dem Pfad wieder zu entfernen, so dass das Rechteck aussieht wie vorher

`**Variante 1**`: **Ausrichten Tool** mit **Knoten**

```{figure} Inkscape_(Advanced)/Untitled_4.png 
--- 
width: 500px 
name: Untitled_4
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_5.png 
--- 
width: 500px 
name: Untitled_5
--- 
caption 
``` 

`**Variante 2**`: Position der Knoten über Fenster oben definieren

```{figure} Inkscape_(Advanced)/Untitled_6.png 
--- 
width: 500px 
name: Untitled_6
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Pfadpunkte_Vektor.gif 
--- 
width: 500px 
name: Pfadpunkte_Vektor
--- 
caption 
``` 

An jedem Knoten kann der Anstieg geändert werden. 

Soll der Anstieg entfernt werden, so muss der Kreis wieder auf den Punkt geführt werden (zum snapping müssen mindestens die zwei Sachen rechts aktiviert sein)

```{figure} Inkscape_(Advanced)/Untitled_7.png 
--- 
width: 500px 
name: Untitled_7
--- 
caption 
``` 

`**Variante 3**`: Verwendung der **Optionen** in der `Tool-Control-Bar`

Die Optionen sind auch hilfreich um z.B. in einer beliebigen Form einen stetigen Übergang zu erzeugen (mit `Symmetric nodes`)

```{figure} Inkscape_(Advanced)/Pfadpunkte_Vektor4.gif 
--- 
width: 500px 
name: Pfadpunkte_Vektor4
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_8.png 
--- 
width: 500px 
name: Untitled_8
--- 
caption 
``` 

[Bild aus Inkscape Dokumentation](https://inkscape-manuals.readthedocs.io/en/latest/interface.html)

Wollen wir nun gezielt ein Anstieg am Knotenpunkt erstellen, so gibt es hier zwei Möglichkeiten

`**Variante 1**`: **Am Punkt** direkt einstellen mit `Shift` + `Ziehen in gewünschte Richtung`

```{figure} Inkscape_(Advanced)/Pfadpunkte_Vektor2.gif 
--- 
width: 500px 
name: Pfadpunkte_Vektor2
--- 
caption 
``` 

`**Variante 2**`: **Linie verformen**

```{figure} Inkscape_(Advanced)/Pfadpunkte_Vektor3.gif 
--- 
width: 500px 
name: Pfadpunkte_Vektor3
--- 
caption 
``` 

Wollen wir einen stetigen Übergang zur Nachbarlinie, so empfiehlt sich die Variante über die `Tool-Control-Bar`: 

`**Variante 3**`: Verwendung der **Optionen** in der `Tool-Control-Bar`

```{figure} Inkscape_(Advanced)/Pfadpunkte_Vektor5.gif 
--- 
width: 500px 
name: Pfadpunkte_Vektor5
--- 
caption 
``` 

## Boolsche Operationen

Auf **Objekten** und **Pfaden** sind `Boolsche Operationen` möglich. Wird dies auf Objekten angewandt, so werden diese automatisch zum Pfad umgewandelt.

Die **Boolsche Operation** wird immer auf das **darunterliegende Objekt** angewandt. (siehe Roten Kreis im Beispiel unten)

```{figure} Inkscape_(Advanced)/Untitled_9.png 
--- 
width: 500px 
name: Untitled_9
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Bolean.png 
--- 
width: 500px 
name: Bolean
--- 
caption 
``` 

Beispiele für Boolsche Operationen

```{figure} Inkscape_(Advanced)/Untitled_10.png 
--- 
width: 500px 
name: Untitled_10
--- 
caption 
``` 

[Bild aus Inkscape Dokumentation](https://inkscape-manuals.readthedocs.io/en/latest/interface.html) | Das Rechteck liegt unter dem Kreis

Linien und Objektkonturen können ebenfalls in Pfade umgewandelt werden.

```{figure} Inkscape_(Advanced)/Untitled_11.png 
--- 
width: 500px 
name: Untitled_11
--- 
caption 
``` 

Möchte man eine Linie (also mit Dickeneigenschaft) von einem Objekt abziehen, so muss die Linie vorher über `Kontur in Pfad` umwandeln umgewandelt werden.

```{figure} Inkscape_(Advanced)/Bolean2.gif 
--- 
width: 500px 
name: Bolean2
--- 
caption 
``` 

**DIVISION MIT LINIE ALS `KONTUR`**

Wird der `Kreis` durch eine `Linie` (mit Kontur) geschnitten, so entstehen am Schnittpunkt zwischen dem Kreisaußenkanten und der Linie neue Knoten

```{figure} Inkscape_(Advanced)/Bolean3.gif 
--- 
width: 500px 
name: Bolean3
--- 
caption 
``` 

**DIVISION MIT LINIE ALS `PFAD`**

Wird die `Linie` in ein `Pfad` **umgewandelt**, so kann diese nun vom Kreis abgezogen werden.

Erstellen Sie nun die Sonne aus unserem ersten Praktikum mit Hilfe der **boolschen Operationen**

Sie müssen ggf. **Gruppierungen aufheben** und Objekte über `Pfad vereinigen` "neu zusammen führen" um diese mit einmal von einem anderen Objekt abzuziehen.

Wenn Sie `ALT` + `Maustaste gedrückt` halten können Sie darüber nur Objekte selektieren die Sie dabei berühren

```{figure} Inkscape_(Advanced)/Selektion_Drag.gif 
--- 
width: 500px 
name: Selektion_Drag
--- 
caption 
``` 

finale Ergebnis mit Sonne als ein  Pfad (alle zusammen mit `Vereinigung` zusammengeführt)

```{figure} Inkscape_(Advanced)/Untitled_12.png 
--- 
width: 500px 
name: Untitled_12
--- 
caption 
``` 

Auf diesen Pfad kann wiederum auch eine Kontur angebracht werden

```{figure} Inkscape_(Advanced)/Untitled_13.png 
--- 
width: 500px 
name: Untitled_13
--- 
caption 
``` 

## Pfadkontur erweitern

Durch die Konvertierung zum Pfad haben wir nun die Eigenschaft verloren die Dicke der Linie einfach zu ändern. Wollen wir trotzdem die Dicke ändern gibt es eine Option die auch für Pfade funktioniert, **jedoch nur in alle Richtungen gleichzeitig.**

```{figure} Inkscape_(Advanced)/Untitled_14.png 
--- 
width: 500px 
name: Untitled_14
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Erweitern_Original.png 
--- 
width: 500px 
name: Erweitern_Original
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Erweitern_Erweitern.png 
--- 
width: 500px 
name: Erweitern_Erweitern
--- 
caption 
``` 

Der Pfad wird um eine **feste Breite erweitert**

```{figure} Inkscape_(Advanced)/Erweitern_Schrumpfen.png 
--- 
width: 500px 
name: Erweitern_Schrumpfen
--- 
caption 
``` 

Der Pfad wird um eine **feste Breite geschrumpft**

```{figure} Inkscape_(Advanced)/Erweitern_DynVersatz.gif 
--- 
width: 500px 
name: Erweitern_DynVersatz
--- 
caption 
``` 

Der Versatz lässt sich dynamisch in beide Richtungen (Erweitern ↔ Schrumpfen)

```{figure} Inkscape_(Advanced)/Erweitern_VerbVersatz.gif 
--- 
width: 500px 
name: Erweitern_VerbVersatz
--- 
caption 
``` 

Der Versatz lässt sich dynamisch nur erweitern

# Selektionsmöglichkeiten

## Mit Maus Selektionslinie zeichnen

Wenn Sie `ALT` + `Maustaste gedrückt` halten können Sie darüber nur Objekte selektieren die Sie dabei berühren

```{figure} Inkscape_(Advanced)/Selektion_Drag.gif 
--- 
width: 500px 
name: Selektion_Drag
--- 
caption 
``` 

## Gleiche auswählen

```{figure} Inkscape_(Advanced)/Untitled_15.png 
--- 
width: 500px 
name: Untitled_15
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_16.png 
--- 
width: 500px 
name: Untitled_16
--- 
caption 
``` 

Beispiel Auswahl Referenz

```{figure} Inkscape_(Advanced)/Untitled_17.png 
--- 
width: 500px 
name: Untitled_17
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_18.png 
--- 
width: 500px 
name: Untitled_18
--- 
caption 
``` 

Ergebnis für `Füllung und Kontur`

# Pfadeffekte (Bemaßung)

Ich habe bisher nicht viel mit Pfadeffekten gearbeitet, was mir jedoch sehr praktisch erscheint ist der Effekt `Bemaßung`

```{figure} Inkscape_(Advanced)/Untitled_19.png 
--- 
width: 500px 
name: Untitled_19
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_20.png 
--- 
width: 500px 
name: Untitled_20
--- 
caption 
``` 

Pfadeffekte hinzufügen durch Anklicken des Pfades und dann das `+` Symbol im Pfadeffekte Menü (Rechts)

```{figure} Inkscape_(Advanced)/Untitled_21.png 
--- 
width: 500px 
name: Untitled_21
--- 
caption 
``` 

Übersicht über die Pfadeffekte

Hier müssen Sie mal etwas mit den Einstellungen spielen und schauen wie Ihnen die Darstellung am besten gefällt

```{figure} Inkscape_(Advanced)/Untitled_22.png 
--- 
width: 500px 
name: Untitled_22
--- 
caption 
``` 

Hilfreich ist es sicher die **Genauigkeit der Bemaßung** einzustellen und **Liniensegmente auszuschließen (über die Segementindizes, welche eingeblendet werden können**)

```{figure} Inkscape_(Advanced)/Untitled_23.png 
--- 
width: 500px 
name: Untitled_23
--- 
caption 
``` 

Anzeige der Segmentenummer die zum Ausschließen der Bemaßung verwendet werden kann

```{figure} Inkscape_(Advanced)/Untitled_24.png 
--- 
width: 500px 
name: Untitled_24
--- 
caption 
``` 

Die Bemaßung gibt immer die Größe des Objektes und nicht der Kontur wieder

```{figure} Inkscape_(Advanced)/Untitled_25.png 
--- 
width: 500px 
name: Untitled_25
--- 
caption 
``` 

Bemaßung ohne Kontur

```{figure} Inkscape_(Advanced)/Untitled_26.png 
--- 
width: 500px 
name: Untitled_26
--- 
caption 
``` 

Bemaßung mit Kontur (Kontur wird in Bemaßung nicht Berücksichtigt, in der Größe oben jedoch schon)

Wollen Sie mit Kontur arbeiten und trotzdem über die obere Leiste die Größe ändern, so müssen Sie für die Größenänderung die Kontur kurz wieder ausschalten

Falls jemand ein anderen sinnvollen Pfadeffekt kennt, bitte gerne Bescheid geben!

# Maßeinheiten auf dem Monitor einstellen

Wenn Sie die Darstellung auf dem Monitor mit den realen Maßen abgleichen wollen, können Sie z.B. über `Einstellungen` ( Menüleiste: `Bearbeiten` → `Einstellungen` oder `Shift` + `Str` + `P` ) unter `Benutzeroberfläche` unter `Zoom Korrektur` den Wert genau einstellen in dem Sie z.B. ein Linieal an Ihren Monitor halten. 

 

```{figure} Inkscape_(Advanced)/Untitled_27.png 
--- 
width: 500px 
name: Untitled_27
--- 
caption 
``` 

Damit dies auch wirklich klappt müssen Sie noch den **Zoom auf 100%:**

→ rechts unten in der Ecke oder die Taste `1` auf der Tastatur drücken

```{figure} Inkscape_(Advanced)/Untitled_28.png 
--- 
width: 500px 
name: Untitled_28
--- 
caption 
``` 

## Objekte einfügen an Originalpositon (für Kopie in andere Ebene)

Hilfreich um den Inhalt von einer Ebene in eine andere zu kopieren ohne die Position zu ändern

`STR` +  `V`

**Einfügen** an **Mausposition**

`STR` +  `ALT` + `V`

**Einfügen** an **Originalposition**

# Bezier-Pen

```{figure} Inkscape_(Advanced)/Untitled_29.png 
--- 
width: 500px 
name: Untitled_29
--- 
caption 
``` 

[Bild aus Inkscape Dokumentation](https://inkscape-manuals.readthedocs.io/en/latest/interface.html)

Durch `linke Maustaste gedrückt halten` + `Mausbewegung` entsteht eine Kurve

`Rechte Maustaste` beendet den Modus

# Textanpassungen

Um **Platz bei Beschriftungen zu sparen**, aber auch weil ich es **optisch ansprechender** finde,  verringere ich oft den `**vertikalen Zeilenabstand**` und den `**horizontalen Zeichenabstand`.** 

```{figure} Inkscape_(Advanced)/Untitled_30.png 
--- 
width: 500px 
name: Untitled_30
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Texteinstellungen.png 
--- 
width: 500px 
name: Texteinstellungen
--- 
caption 
``` 

# Pixelgrafiken automatisch in Vektor umwandeln

Um eine Pixelgrafik in eine Vektorgrafik umzuwandeln, muss die Pixelgrafik ausgewählt sein. Anschließend in der `Menüleiste`: `Pfad` → `Bitmap nachzeichnen`

```{figure} Inkscape_(Advanced)/Untitled_31.png 
--- 
width: 500px 
name: Untitled_31
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_32.png 
--- 
width: 500px 
name: Untitled_32
--- 
caption 
``` 

Quelle:  [https://pixabay.com/de/photos/nebel-nadelwald-fichte-wald-grün-3622519/](https://pixabay.com/de/photos/nebel-nadelwald-fichte-wald-gr%C3%BCn-3622519/)

Für das Beispiel habe ich auf `Mehrere Scans` (damit mehrere Farben erkannt werden), anschließend `Farben` ausgewählt und dann `4` (Anzahl der Farben) eingestellt und mit `Aktualisieren` die Vorschau aktualisieren.

Der Algorithmus arbeitet besonders gut bei großen Unterschieden in Helligkeiten und Farben wie in diesem Beispiel

```{figure} Inkscape_(Advanced)/Untitled_33.png 
--- 
width: 500px 
name: Untitled_33
--- 
caption 
``` 

Durch `Ok` wird anschließend das Vektorbild über das Pixelbild gezeichnet. Dabei entsteht eine Gruppe aus der Anzahl der Farben (**Auflösen der Gruppe** mit `Str` + `Shift` + `G`).

```{figure} Inkscape_(Advanced)/Pixel2Vektor1.png 
--- 
width: 500px 
name: Pixel2Vektor1
--- 
caption 
``` 

Bei einfarbigen Pixelgrafiken wie Logos klappt es auch sehr gut, wobei hier der `Einmalige Scan` ausreicht.

```{figure} Inkscape_(Advanced)/Inkscape_Logo.png 
--- 
width: 500px 
name: Inkscape_Logo
--- 
caption 
``` 

Inkscape Logo (png)

```{figure} Inkscape_(Advanced)/Untitled_34.png 
--- 
width: 500px 
name: Untitled_34
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Inkscape_Logo_Pixel.png 
--- 
width: 500px 
name: Inkscape_Logo_Pixel
--- 
caption 
``` 

Als `.png` gespeichert (vor der Umwandlung)

```{figure} Inkscape_(Advanced)/Inkscape_Logo_Vektor.svg 
--- 
width: 500px 
name: Inkscape_Logo_Vektor
--- 
caption 
``` 

Als `.svg` gespeichert (nach der Umwandlung)

# Ausschneidemaske (Pixelbilder croppen)

[Beispielbild](https://pixabay.com/de/photos/schule-tafel-leer-schiefertafel-3258934/)

Mit der **Maske wird** ein **darüberliegendes Objekt** (hier ein grünes Rechteck mit 50% Transparenz damit man besser sieht was darunter liegt) **das darunterliegende Objekt** (in unserem Fall ein Pixelbild) **ausgeschnitten.**

Die Farbe & Transparenz der Maske haben keinen Einfluss, **nur die** **Form ist entscheidend.**

```{figure} Inkscape_(Advanced)/Untitled_35.png 
--- 
width: 500px 
name: Untitled_35
--- 
caption 
``` 

**Beide Objekte selektieren** (und in gewünschter Reihenfolge anordnen) und danach in der Menüleiste: `Objekt` → `Ausschneidepfad` → `Setzen` 

```{figure} Inkscape_(Advanced)/Untitled_36.png 
--- 
width: 500px 
name: Untitled_36
--- 
caption 
``` 

Ergebnis ist nun ein ausgeschnittenes Bild:

```{figure} Inkscape_(Advanced)/Untitled_37.png 
--- 
width: 500px 
name: Untitled_37
--- 
caption 
``` 

**Die Maske und das darunterliegende Objekt sind jedoch weiterhin vorhanden** und können über die Menüleiste: `Objekt` → `Ausschneidepfad` → `Freigeben` wieder zurück geholt werden (wenn man z.B. die Maske anpassen möchte)

```{figure} Inkscape_(Advanced)/Untitled_38.png 
--- 
width: 500px 
name: Untitled_38
--- 
caption 
``` 

Neben dem `Ausschneidepfad` gibt es noch die `Maske` die prinzipiell sehr ähnlich funktioniert, jedoch auch Transparenz in der Maske berücksichtigt. 

Ich habe jedoch bisher keinen Anwendungsfall dafür gefunden.

```{figure} Inkscape_(Advanced)/Untitled_39.png 
--- 
width: 500px 
name: Untitled_39
--- 
caption 
``` 

# Musterfüllung

Gerade für technische Darstellung möchte man manchmal statt einer Farbfüllung eine Musterfüllung verwenden.

```{figure} Inkscape_(Advanced)/Untitled_40.png 
--- 
width: 500px 
name: Untitled_40
--- 
caption 
``` 

Dies ist in Inkscape ohne Probleme möglich, das Problem ist nur, dass die vorgegeben Füllung auf den **ersten Blick für technische Zwecke nicht sehr nützlich** sind.

```{figure} Inkscape_(Advanced)/Untitled_41.png 
--- 
width: 500px 
name: Untitled_41
--- 
caption 
``` 

Die Muster können jedoch durch in **Größe**, **Position** und **vor allem Orientierung** geändert werden. D**adurch können die Muster mit dem Namen** `Streifen` **mit einer Veränderung des Winkels gut verwendet werden**.

```{figure} Inkscape_(Advanced)/Untitled_42.png 
--- 
width: 500px 
name: Untitled_42
--- 
caption 
``` 

Um das Muster zu ändern muss dies mit dem `Edit Path by Nodes Tool`  angepasst werden, wobei mit dem Kreis der Winkel und mit dem Rechteck die Größe geändert werden kann

```{figure} Inkscape_(Advanced)/Musterfuellung.gif 
--- 
width: 500px 
name: Musterfuellung
--- 
caption 
``` 

Will man nun noch die Farbe des Musters verändern muss man einen kleinen Umweg gehen. 

Das Objekt auswählen und in der `Menüleiste`: `Erweiterung` → `Farbe` → `Farbe ersetzen` anklicken.

```{figure} Inkscape_(Advanced)/Untitled_43.png 
--- 
width: 500px 
name: Untitled_43
--- 
caption 
``` 

Anschließend die `zu ersetzende Farbe` und die `Neue Farbe` wählen.

Es werden dann ebenfalls die **Konturen** (wenn diese schwarz waren) in der Farbe angepasst. Dies kann jedoch leicht geändert werden indem die Konturfarbe einfach neu definiert wird.

```{figure} Inkscape_(Advanced)/Untitled_44.png 
--- 
width: 500px 
name: Untitled_44
--- 
caption 
``` 

Als zu ersetzende Farbe schwarz auswählen. 
ℹ️Ansonsten die **Pipette** verwenden um den Farbton zu treffen

```{figure} Inkscape_(Advanced)/Untitled_45.png 
--- 
width: 500px 
name: Untitled_45
--- 
caption 
``` 

Um Grautöne zu erhalten die Sättigung auf 0, den Alphawert auf 100 und über die Helligkeit den Grauton auswählen

So könnte es z.B. aussehen:

```{figure} Inkscape_(Advanced)/Untitled_46.png 
--- 
width: 500px 
name: Untitled_46
--- 
caption 
``` 

## Eigene Muster erstellen

Wer doch gerne sein eigenes Muster erstellen möchte, kann dies auch tun über die `Menüleiste`: `Muster` → `Objekte in Füllmuster umwandeln`

Bei der Erstellung des Musters z.B. wie unten zu sehen bei Linien die in quer gehen daran denken, dass in den Ecken das Muster auch gefüllt sein muss

```{figure} Inkscape_(Advanced)/Untitled_47.png 
--- 
width: 500px 
name: Untitled_47
--- 
caption 
``` 

# Gradient

Wenn überhaupt würde ich nur Gradienten mit **geringem Helligkeitsunterschied** empfehlen

Mit dem `Gradient Tool` kann eine Gradient-Füllung direkt in dem Objekt gezeichnet werden. 

Jedem Punkt kann (z.B. durch `Edit Path by Nodes Tool` angeklickt und eine Farbe zugeordnet werden (nicht in der Animation dargestellt)

```{figure} Inkscape_(Advanced)/Gradient.gif 
--- 
width: 500px 
name: Gradient
--- 
caption 
``` 

In Füllung und Kontur können zudem noch ein Radialer Gradient eingestellt werden:

```{figure} Inkscape_(Advanced)/Untitled_48.png 
--- 
width: 500px 
name: Untitled_48
--- 
caption 
``` 

Radialer Gradient

# Text mit Hintergrund

```{figure} Inkscape_(Advanced)/Untitled_49.png 
--- 
width: 500px 
name: Untitled_49
--- 
caption 
``` 

Wird ein Text auf Grund des Hintergrundes nicht mehr gut sichtbar, so empfiehlt es sich, diesen durch eine zusätzliche Hintergrundfüllung besser sichtbar zu machen. In Inkscape gibt es dazu ein Extra Filter der den Vorteil besitzt, dass sich die Box dann automatisch dem Text anpasst, wenn dieser geändert wird.

```{figure} Inkscape_(Advanced)/Untitled_50.png 
--- 
width: 500px 
name: Untitled_50
--- 
caption 
``` 

1. Text auswählen. Danach unter `Filter` → `Füllung und Transparrenz` → `Hintergrund füllen`

```{figure} Inkscape_(Advanced)/Untitled_51.png 
--- 
width: 500px 
name: Untitled_51
--- 
caption 
``` 

2. `Filter` → `Filtereditor`

```{figure} Inkscape_(Advanced)/Untitled_52.png 
--- 
width: 500px 
name: Untitled_52
--- 
caption 
``` 

3. `Füllen` auswählen und `Füllfarbe` und `Deckkraft` anpassen

```{figure} Inkscape_(Advanced)/Untitled_53.png 
--- 
width: 500px 
name: Untitled_53
--- 
caption 
``` 

4. Unter `Allgemeine Filtereinstellung` kann die Position und Größe angepasst werden

# Gitter 3D

**DOKUMENTENEINSTELLUNGEN**
(`SHIFT` + `STR` + `D`) oder (`Menu bar` → `Datei` →  `Dokumenteneinstellungen...`)

**Reiter**: `Gitter`

```{figure} Inkscape_(Advanced)/Untitled_54.png 
--- 
width: 500px 
name: Untitled_54
--- 
caption 
``` 

# Objekt in isometrische Ansicht verformen

ggf. anpassen für andere Orientierung

```{figure} Inkscape_(Advanced)/Untitled_55.png 
--- 
width: 500px 
name: Untitled_55
--- 
caption 
``` 

Ausgangskörper

```{figure} Inkscape_(Advanced)/Untitled_56.png 
--- 
width: 500px 
name: Untitled_56
--- 
caption 
``` 

isometrische Ansicht

```{figure} Inkscape_(Advanced)/Untitled_57.png 
--- 
width: 500px 
name: Untitled_57
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_58.png 
--- 
width: 500px 
name: Untitled_58
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_59.png 
--- 
width: 500px 
name: Untitled_59
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_60.png 
--- 
width: 500px 
name: Untitled_60
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_56.png 
--- 
width: 500px 
name: Untitled_56
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_61.png 
--- 
width: 500px 
name: Untitled_61
--- 
caption 
``` 

# Kantenverrundung

Wird wie in dem Beispiel oben für das Axonometrische Gitter eine Kontur mit größerer Dicke verwendet fällt auf, dass die Ecken überstehen. Um dies anzupasssen kann man unter `Füllung und Kontur` unter `Muster der Kontur` die Verbindungspunkte abrunden.

Für **Linien** können ebenfalls die **Endpunkte verrundet** werden, wer das möchte.

```{figure} Inkscape_(Advanced)/Untitled_62.png 
--- 
width: 500px 
name: Untitled_62
--- 
caption 
``` 

# Templates

Es gibt eine Vielzahl an Vorlagen, interessant ist es jedoch vor allem eigene Vorlagen zu erstellen mit z.B. Symbolen die man immer wieder verwendet. Die müssen in `C:\Program Files\Inkscape\share\inkscape\templates` (für Windows) als Inkscape svg abgespeichert werden.

```{figure} Inkscape_(Advanced)/Untitled_63.png 
--- 
width: 500px 
name: Untitled_63
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_64.png 
--- 
width: 500px 
name: Untitled_64
--- 
caption 
``` 

# $\LaTeX$ in Inkscape

Es gibt mehrere Möglichkeiten LaTeX in Inkscape einzubinden:

- [TexText](https://github.com/textext/textext) (Erweiterung, Installation notwendig)
- [LaTeXText](https://github.com/seebk/LaTeXText) (Erweiterung, Installation notwendig, `nicht mehr weiterentwickelt`)
- vorinstallierte LaTeX Rendering (siehe unten)
- [https://latex2image.joeraut.com/](https://latex2image.joeraut.com/) (`Webtool` - als svg einfügen)

```{figure} Inkscape_(Advanced)/Untitled_65.png 
--- 
width: 500px 
name: Untitled_65
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_66.png 
--- 
width: 500px 
name: Untitled_66
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_67.png 
--- 
width: 500px 
name: Untitled_67
--- 
caption 
``` 

# Hilfslinien

Zuerst in der Menüleiste über `Ansicht` die `Hilfslinien` **anzeigen** 

```{figure} Inkscape_(Advanced)/Untitled_68.png 
--- 
width: 500px 
name: Untitled_68
--- 
caption 
``` 

Durch das Ziehen von dem Linie können die Hilfslinien erzeugt werden

Aus den Ecken können auch 45° Linien gezogen werden

```{figure} Inkscape_(Advanced)/Hilfslinien.gif 
--- 
width: 500px 
name: Hilfslinien
--- 
caption 
``` 

Durch **Doppelklick auf die Linie** kann diese angepasst werden und z.B. auch der Winkel geändert werden.

```{figure} Inkscape_(Advanced)/Untitled_69.png 
--- 
width: 500px 
name: Untitled_69
--- 
caption 
``` 

Zum **Sperren der Hilfslinie** das 🔐-Symbol in der linken oberen Ecke auswählen

```{figure} Inkscape_(Advanced)/Untitled_70.png 
--- 
width: 500px 
name: Untitled_70
--- 
caption 
``` 

## Hilfslinien aus Objektrand

Hilfslinien sind zum Beispiel hilfreich um Seitenränder darzustellen.  

Hier zum Beispiel erstellen wir ein 10mm Rand für eine DIN A4 Seite:

- Rechteck erstellen welches jeweils 10mm am Rand kleiner ist und dieses Mittig ausrichten

```{figure} Inkscape_(Advanced)/Untitled_71.png 
--- 
width: 500px 
name: Untitled_71
--- 
caption 
``` 

- Anschließend in Menüleiste `Objekt` → `Objekt zu Hilfslinien`

```{figure} Inkscape_(Advanced)/Untitled_72.png 
--- 
width: 500px 
name: Untitled_72
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_73.png 
--- 
width: 500px 
name: Untitled_73
--- 
caption 
``` 

Hilfslinie für 10mm Rand einer A4 Seite

# Röntgen Sicht

Will man bestimmte Objekte hinter anderen wiederfinden (z.B. um Sie zu selektieren) ist der Röntgenmodus sehr praktisch der in der `Menüleiste`: `Ansicht` → `Röntgenmodus` oder mit `Alt` + `6` angeschaltet werden kann

```{figure} Inkscape_(Advanced)/Untitled_74.png 
--- 
width: 500px 
name: Untitled_74
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/RoentgenModus.gif 
--- 
width: 500px 
name: RoentgenModus
--- 
caption 
``` 

Eine **geteilte Ansicht** kann über `Menüleiste`: `Ansicht` → `Geteilte Ansicht` oder mit `Str` + `6` erzeugt werden (der Übergang kann verschoben werden):

```{figure} Inkscape_(Advanced)/Untitled_75.png 
--- 
width: 500px 
name: Untitled_75
--- 
caption 
``` 

# Übertragen von Stil (Farbe/Linie/Dicke) auf andere

`STR` + `C` von zu kopierendem Stil

`STR` + `SHIFT` + `V` (Stil einfügen)

# Clone erstellen

Änderungen am Original werden auf alle Klone angewandt

```{figure} Inkscape_(Advanced)/Untitled_76.png 
--- 
width: 500px 
name: Untitled_76
--- 
caption 
``` 

`ALT` + `D` Klon erzeugen (**funktioniert bei mir nicht**)

`SHIFT` + `ALT` + `D` Klonverbindung auftrennten

`SHIFT` + `D` Original auswählen

Die Skalierung des Klons wirkt sich nicht auf das Original aus, aber umgekehrt schon

```{figure} Inkscape_(Advanced)/Klon.gif 
--- 
width: 500px 
name: Klon
--- 
caption 
``` 

# Batch Export

Wenn Sie mehrere Bilder gleichzeitig exportieren müssen, so müssen diese als Gruppe zusammengefasst werden und anschließend über die PNG-Export Option `Batch-Export` gespeichert werden:

```{figure} Inkscape_(Advanced)/Untitled_77.png 
--- 
width: 500px 
name: Untitled_77
--- 
caption 
``` 

Beispiel für Batch Export

```{figure} Inkscape_(Advanced)/Untitled_78.png 
--- 
width: 500px 
name: Untitled_78
--- 
caption 
``` 

Einstellungen für Batch Export

Es werden dann drei `.png` Dateien erzeugt im Speicherort der `.svg`

```{figure} Inkscape_(Advanced)/Untitled_79.png 
--- 
width: 500px 
name: Untitled_79
--- 
caption 
``` 

Output des Batch Export

# Weiterführende Beispiele

## Schematischer Aufbau eines Solarmoduls

```{figure} Inkscape_(Advanced)/Untitled_80.png 
--- 
width: 500px 
name: Untitled_80
--- 
caption 
``` 

- Solarzellen klonen

```{figure} Inkscape_(Advanced)/Untitled_81.png 
--- 
width: 500px 
name: Untitled_81
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_82.png 
--- 
width: 500px 
name: Untitled_82
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_83.png 
--- 
width: 500px 
name: Untitled_83
--- 
caption 
``` 

- Isometrische Ansicht erstellen

```{figure} Inkscape_(Advanced)/Untitled_58.png 
--- 
width: 500px 
name: Untitled_58
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_60.png 
--- 
width: 500px 
name: Untitled_60
--- 
caption 
``` 

```{figure} Inkscape_(Advanced)/Untitled_61.png 
--- 
width: 500px 
name: Untitled_61
--- 
caption 
``` 
