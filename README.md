# Rollladensteuerung – M. Arldt, H. Wittkopp
## Projektbeschreibung:
Über die Rollladensteuerung soll ein elektrischer Rollladen von Hand (3 Taster: AUF, AB und STOPP) oder automatisch (Zufahren bei Wind oder Dämmerung, Auffahren nach Sonnenaufgang/Windstille) gesteuert werden. 
Der aktuelle Status („Fährt auf“, „fährt zu“, „zugefahren wegen Wind“, „zugefahren wegen Dämmerung“) soll durch LEDs visualisiert werden.
## Funktionen/2do:
* Motor auf/ab (Software unproblematisch, Hardware: Sicherheit 230V Antrieb einschl. Störsicherheit)
* Windsensor auswerten (Analogsensor oder digitaler Bus (Bibliothek einbinden?))
* Dämmerungsschalter auswerten (s.o.)
* Rückmeldungen per LEDs geben (Programmlogik)
* Taster auf/ab/stopp auswerten (Programmlogik)
## Optional:
* Zeitschaltuhr (Problem: RTC Real Time Clock!)
