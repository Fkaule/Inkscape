# Erstellung der Sonne

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

## Objekthierarchie

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

## Linie bearbeiten mit `Edit Path by Nodes` Tool

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