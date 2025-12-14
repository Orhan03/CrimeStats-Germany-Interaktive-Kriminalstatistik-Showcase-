# 🗺️ CrimeStats Germany - Interaktive Kriminalstatistik

🎥 Demo & Workflow
<div align="center">
  <img src="[https://github.com/user-attachments/assets/ee2e29ef-e9b7-4bf8-8be2-8718c5a16cbb" alt="CrimeStats Demo" width="100%" />
  <br>
  <p><i>Interaktive Navigation: Von der Karten-Auswahl zur dynamischen Daten-Analyse.</i></p>
</div>

## ✨ Features

### 📍 Interaktive SVG-Karte
* **Vektorbasiert:** Eine hochauflösende Deutschlandkarte, bei der jedes Bundesland einzeln als Pfad (`<path>`) ansteuerbar ist.
* **Smart Routing:** Ein Klick auf ein Bundesland leitet via URL-Parameter weiter (z.B. `ergebnis.html?stadt=bayern&straftat=alle-straftaten`), wodurch der Zustand ohne Backend übertragen wird.
* **Visuelles Feedback:** CSS-Transitionen sorgen für flüssige Hover-Effekte beim Überfahren der Karte.

### 📊 Dynamische Datenvisualisierung
* **Chart.js Integration:** Rohdaten werden in Echtzeit in interaktive Grafiken umgewandelt.
* **Multi-View System:** Nutzer können die Darstellung der Daten live zwischen **Säulen-**, **Linien-** und **Kreisdiagrammen** umschalten, ohne die Seite neu zu laden.
* **Live-Filter:** Über Dropdown-Menüs lassen sich Delikte (z.B. *Mord, Raub, Betrug*) und Bundesländer sofort vergleichen.

### 🎨 Responsive UI
* **Dynamische Inhalte:** Texte, Titel und Wappen-Bilder (`img src`) passen sich automatisch der gewählten Region an.
* **Theming:** Ein Farbschema basierend auf seriösen Blau-Tönen passend zur Datenverarbeitung.
