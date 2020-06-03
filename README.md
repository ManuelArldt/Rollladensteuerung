# Rollladensteuerung – M. Arldt, H. Wittkopp
## Projektbeschreibung
Über die Rollladensteuerung soll ein elektrischer Rollladen von Hand (3 Taster: AUF, AB und STOPP) oder per Automatik (Zufahren bei Wind oder Dämmerung, Auffahren bei Windstille und Tageslicht) gesteuert werden. 
Die Hand/Automatik - Umschaltung erfolgt über einen Betriebsartenwahlschalter.  
Der aktuelle Status wird durch LEDs visualisiert.(„Fährt auf“ grüne LED P3, „fährt zu“ grüne LED P4, „Windwarnung“ rote LED P1, „Dämmerung“ gelbe LED P2) 
Über 2 Potentiometer lassen sich die Schaltschwellen für den Windsensor sowie den Dämmerungsschalter einstellen.
Wie lange die Windwarnung sowie der Dämmerungsschalter aktiv/inaktiv sein muss bis eine Reaktion (Rollladen auf oder ab) erfolgt, lässt sich über in Variablen hinterlegten Sollwerten vorgeben.
Alle Analogwerte sowie die Betriebsart werden bei Werteänderung über den seriellen Monitor ausgegeben. 
Ebenso erfolgt eine Klartextausgabe über den seriellen Monitor, wenn er Taster betätigt wurde, in welche Richtung der Rollladen gerade fährt und ob er oben oder unten ist.
## Funktionen/2do
* Motor auf/ab (Software unproblematisch, Hardware: Sicherheit 230V Antrieb einschl. Störsicherheit)
* Windsensor auswerten (Analogwertverarbeitung)
* Dämmerungsschalter auswerten (Analogwertverarbeitung)
* Rückmeldungen per LEDs geben (Programmlogik)
* Taster AUF/STOPP/AB auswerten (Programmlogik)
* Schalter Hand/Automatik auswerten (Programmlogik)
* Schaltschwelle für Windsensor per Potentiometer vorgeben (Analogwertverarbeitung)
* Schaltschwelle für Dämmerungsschalter per Potentiometer vorgeben (Analogwertverarbeitung)
* Rückmeldung der Analogwerte Windgeschwindigkeit (DW und m/s), Helligkeit (DW und %), Sollwertvorgaben (DW und %), Tasterbetätigungen,   Betriebsart und Endlage des Rollladens über den seriellen Monitor (Programmlogik)

## Optional
* Zeitschaltuhr (Problem: RTC Real Time Clock!)

## Aufbau

![Aufbau](https://github.com/CRBK/Rolladensteuerung/blob/master/Bilder%20TinkerCad/mit_bez.PNG?raw=true)

## Beispielausgabe des seriellen Monitors

![Ausgabe](https://github.com/CRBK/Rolladensteuerung/blob/master/Bilder%20TinkerCad/Ausgabe.PNG?raw=true)

## Schaltplan
Der Schaltplan zu dem Projekt ist [hier](https://github.com/CRBK/Rolladensteuerung/blob/master/Schaltplan.pdf) zu finden.

## Komponentenliste

## Programm

## Videbeschreibung

Eine kurzes Video zur Simulation des Projektes in Tinkercad befindet sich [hier](https://github.com/CRBK/Rolladensteuerung/blob/master/Video%20TinkerCad/Rollladensteuerung.mp4).
