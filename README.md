# Rollladensteuerung – M. Arldt, H. Wittkopp
## Projektbeschreibung:
Über die Rollladensteuerung soll ein elektrischer Rollladen von Hand (3 Taster: AUF, AB und STOPP) oder automatisch (Zufahren bei Wind oder Dämmerung) gesteuert werden. 
Der aktuelle Status wird durch LEDs visualisiert.(„Fährt auf“ grüne LED P3, „fährt zu“ grüne LED P4, „zugefahren wegen Wind“ rote LED P1, „zugefahren wegen Dämmerung“ gelbe LED P2) 
Über 2 Potentiometer lassen sich die Schaltschwellen für den Windsensor sowie den Dämmerungsschalter einstellen.
Alle Analogwerte werden bei Werteänderung über den seriellen Monitor ausgegeben. 
## Funktionen/2do:
* Motor auf/ab (Software unproblematisch, Hardware: Sicherheit 230V Antrieb einschl. Störsicherheit)
* Windsensor auswerten (Analogwertverarbeitung)
* Dämmerungsschalter auswerten (Analogwertverarbeitung)
* Rückmeldungen per LEDs geben (Programmlogik)
* Taster AUF/STOPP/AB auswerten (Programmlogik)
* Schaltschwelle für Windsensor per Potentiometer vorgeben (Analogwertverarbeitung)
* Schaltschwelle für Dämmerungsschalter per Potentiometer vorgeben (Analogwertverarbeitung)
* Rückmeldung der Analogwerte Windgeschwindigkeit (DW und m/s), Helligkeit (DW und %), Sollwertvorgaben (DW und %) über den seriellen Monitor (Programmlogik)
  

## Optional:
* Zeitschaltuhr (Problem: RTC Real Time Clock!)
