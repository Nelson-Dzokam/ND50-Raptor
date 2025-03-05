### Projektbeschreibung: Nachrüstung einer Bluetooth-Maus mit wiederaufladbarem Akku

Dieses  Projekt zielt darauf ab, eine herkömmliche Bluetooth-Maus, die ursprünglich mit nicht wiederaufladbaren Batterien betrieben wird, auf einen fest verbauten Li-Ion/LiPo-Akku umzurüsten. Dazu wurde eine maßgeschneiderte Lade- und Energieverwaltungsleiterplatte entwickelt, die eine zuverlässige Stromversorgung sicherstellt und gleichzeitig den kontinuierlichen Betrieb der Maus während des Ladevorgangs ermöglicht.
Funktionalität & Zielsetzung
•	Ersetzen der herkömmlichen 1,5V-Batterie durch einen wiederaufladbaren Li-Ion/LiPo-Akku
•	Integration einer Ladeelektronik basierend auf dem TP4056, um den Akku sicher über USB-C zu laden
•	Betrieb während des Ladevorgangs: Die Maus bleibt voll funktionsfähig, selbst wenn sie geladen wird
•	Automatische Umschaltung nach dem Ladevorgang, sodass die Maus ausschließlich mit dem aufgeladenen Akku betrieben wird
•	Spannungswandlung mit TPS62841DGRR, um die benötigte 1,5V für die Maus aus der 3,7V-Akkuspannung bereitzustellen
•	Sicherheitsschaltung mit DW01A + FS8025, um den Akku vor Überladung, Tiefentladung und Kurzschluss zu schützen
•	Platzoptimierte Leiterplatte, die sich in das Gehäuse der Maus integriert
•	Anpassung des Gehäuses durch 3D-Druck, um die neue Leiterplatte optimal unterzubringen
Technische Spezifikationen
•	Laderegler: TP4056 mit integriertem Schutzschaltkreis
•	Akku-Schutz:
o	DW01A: Li-Ion Schutz-IC zur Über- und Tiefentladesicherung
o	FS8025: MOSFET-Doppeltransistor für Überstrom- und Kurzschlussschutz
•	Spannungsregler:
o	TPS62841DGRR: Hocheffizienter DC-DC-Abwärtswandler, der die 3,7V Akkuspannung auf 1,5V für die Maus reduziert
o	Sehr niedriger Ruhestrom (60 nA) für maximale Energieeffizienz
o	Hoher Wirkungsgrad, um die Akkulaufzeit zu verlängern
•	Anschluss: USB-C (nur für Stromversorgung)
•	Akku: 3,7V Li-Ion oder LiPo (Kapazität abhängig vom verfügbaren Platz)
•	Statusanzeigen: Zwei LEDs zur Anzeige des Ladestatus
•	Sichere Energieverteilung zur Trennung von Lade- und Entladeströmen
•	3D-gedrucktes Gehäuse-Modifikationen, um die Leiterplatte passgenau zu integrieren
Sicherheitsmechanismen durch DW01A & FS8025
•	Überspannungsschutz (Overcharge Protection, OVP): Schützt den Akku vor Überladung
•	Tiefentladeschutz (Overdischarge Protection, ODP): Verhindert eine Tiefentladung des Akkus, die ihn beschädigen könnte
•	Kurzschlussschutz (Short Circuit Protection, SCP): Erkennt einen Kurzschluss und trennt den Akku sicher ab
•	Überstromschutz (Overcurrent Protection, OCP): Stoppt den Stromfluss bei zu hoher Last
Vorteile & Nutzen
✅ Kein Wechsel von Einwegbatterien mehr – nachhaltige Lösung
✅ Maus bleibt auch während des Ladens nutzbar
✅ Effiziente 1,5V-Versorgung mit TPS62841DGRR für maximale Akkulaufzeit
✅ Kompakte und zuverlässige Schaltung mit SMD-Bauteilen
✅ Gehäuse kann mit 3D-Druck individuell angepasst werden
✅ Erweiterte Sicherheit durch Schutzschaltung (DW01A & FS8025)
✅ Einfache Integration in bestehende Hardware


