EINBÜRGERUNGSTEST BW – VERSION 3.3 PREVIEW

Diese Version ist für das GitHub-Preview-Repository gedacht.

Wichtig:
- Erkennt URLs/Pfade mit „preview“ und speichert Lernfortschritt, Sterne, Prüfungen und Einstellungen getrennt von der stabilen hamk7.github.io-Seite.
- Auf der Preview erscheint oben klein „TESTVERSION 3.3“.
- Die stabile Hauptseite wird dadurch nicht verändert.

Änderungen:
- Untertitel unter „Einbürgerungstest Baden-Württemberg“ entfernt.
- Lern-Fortschrittsleiste im Fragenfenster entfernt.
- Lernfilter farbig.
- Offene/Neue Fragen neutral-grau; Bearbeitet blau.
- Zurück/Nächste im Lernmodus fest am unteren Bildschirmrand.
- Buttons nutzen touch-action: manipulation gegen unbeabsichtigten Doppel-Tipp-Zoom.
- Verwaiste versteckte Kompatibilitäts-Controls werden sicher ausgeblendet.
- 310 türkische Fragen + 1.240 türkische Antworten + türkische Erklärungen lokal eingebettet.
- DDR und wichtige deutsche Eigennamen/Abkürzungen bleiben erhalten.
- Erklärung öffnet sich nach dem Antworten NICHT automatisch.
- Optionaler Menüschalter „Muster-Test-Schrift“.
- Neuer PDF-Workflow:
  1. Papier-Test erzeugen
  2. PDF erstellen
  3. Nach Fertigstellung „PDF teilen / drucken“ oder „PDF herunterladen“
- Auf iPhone/iPad wird für eine fertige PDF-Datei die Web Share API benutzt, sofern unterstützt.
- Das alte window.open()/Popup-Druckverfahren wird für diesen Button nicht mehr verwendet.

Hinweis:
html2pdf.js wird in dieser Preview in Version 0.10.1 von cdnjs geladen.
