# Schärfentieferechner (Depth of Field Calculator)

Ein webbasiertes Tool zur Berechnung der Schärfentiefe und anderer optischer Parameter für die Fotografie. Dieses Tool ermöglicht es Fotografen, die Schärfentiefe, den Nahpunkt, den Fernpunkt, die hyperfokale Distanz und den Bildwinkel basierend auf Kameraeinstellungen zu berechnen.

## 📋 Funktionen

*   **Berechnung der Schärfentiefe:** Bestimmt den Bereich, in dem Objekte scharf abgebildet werden.
*   **Nahpunkt & Fernpunkt:** Der vordere und der hintere Punkt der Schärfe für die angegebene Objektentfernung.
*   **Hyperfokale Distanz:** Berechnet den Fokuspunkt, um Schärfe bis ins Unendliche zu erreichen.
*   **Bildwinkel:** Berechnung des Sichtfelds basierend auf der Brennweite und der gewählten Sensorgröße.
*   **Z-Kreis:** Anzeige des berechneten Z-Kreises.

## 🛠 Technische Details

*   **Sprachen:** HTML5, JavaScript (jQuery 1.8.1)
*   **Berechnungslogik:** Die Berechnungen erfolgen clientseitig in Echtzeit.
*   **Sensorgrößen:** Das Tool enthält eine integrierte Liste gängiger Sensorgrößen (z. B. Vollformat, APS-C, verschiedene Digitalkamera-Sensoren).

## 🚀 Nutzung

1.  Öffne die `index.htm` Datei in einem beliebigen Webbrowser.
2.  Gib die **Brennweite** (in mm) deiner Linse ein.
3.  Wähle die gewünschte **Blende** aus der Liste aus.
4.  Gib die **Objektweite** (den Abstand zum Fokuspunkt) in Metern ein.
5.  Wähle den passenden **Sensor** deiner Kamera aus.
6.  Klicke auf **"ausrechnen"**, um die Ergebnisse sofort anzuzeigen.

## 📐 Mathematische Grundlagen

Das Skript nutzt folgende Kernberechnungen:
- **Hyperfokale Distanz ($H$):** $\frac{f^2}{B \cdot d} + f$
- **Bildwinkel:** Berechnet aus der Bilddiagonale und der Brennweite.
- **Schärfentiefe:** Differenz zwischen Fernpunkt und Nahpunkt.
- **Link zum** [Wikipediaartikel](https://de.wikipedia.org/wiki/Sch%C3%A4rfentiefe).

## 📄 Lizenz
*Jeder kann den Programmcode nutzen. Es gibt keine Einschränkung.*


