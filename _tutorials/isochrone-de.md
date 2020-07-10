---
title: Isochrone
permalink: /de/tutorials/isochrone/
lang: de
---

#### Beschreibung des Features
Isochronen sind Isolinien, die alle Punkte verbinden, die von einem bestimmten Startpunkt aus innerhalb eines bestimmten Zeitintervalls erreicht werden können.
GOAT ermöglicht die Berechnung von Isochronen und erlaubt die Anpassung der Reisegeschwindigkeit, der Reisezeit und des Routingprofils. Gegenwärtig kann zwischen den Routinprofilen Gehen (Standard oder Senior), Radfahren (Standard oder Pedelec) und Rollstuhl ausgewählt wird. Isochronen sind besonders geeignet um die Erreichbarkeit an einem spezifischen Ort aufzuzeigen. 

#### Mögliche Anwendungsfälle (Planungsfragen)

- Wie viele Supermärkte können von einem bestimmten Punkt aus innerhalb von 10 Gehminuten erreicht werden?
- Wie viele Menschen können eine ÖV Haltestelle innerhalb von 5 Minuten mit dem Fahrrad erreichen? 
- Wie unterscheidet sich die 10-minütige Erreichbarkeit des Klinikums zwischen einem nicht eingeschränktem Fußgänger und einer mobilitätseingeschränkten Person? 


#### Schritt-für-Schritt-Anleitung für die beispielhaften Planungsaufgaben
##### 1 Erreichbarkeit von Supermärkten
###### 1.1 Planungsfrage

Wie viele Supermärkte können von einem bestimmten Punkt aus innerhalb von 10 Gehminuten erreicht werden?

###### 1.2 Arbeitsschritte

1. Wählen Sie im Menü „Filter Thematische Daten“ die Einrichtung „Supermarkt“ (zu finden in der Kategorie „Einkaufen“).  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/amenity_supermarket.png" title="amenity supermarket" style="height:200px;">

2. Zoomen Sie zu dem Bereich, in dem Sie die Isochrone berechnen möchten.

3. Stellen Sie die maximale Reisezeit auf 10 Minuten.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/isochrone_range_walking.png" title="Adjusting isochrone range" style="height:200px;">

4. Platzieren Sie den Startpunkt für die Isochronenberechnung an einem beliebigen Punkt.
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/starting-point-isochrone.png" title="Starting point isochrone" style="height:150px;">

5. Nachdem die Berechnung ausgeführt wurde, öffnet sich automatisch ein Fenster mit den Ergebnissen. Diesem können Sie die erreichbaren Supermärkte entnehmen.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/isochrone_supermarkets.png" title="Reached supermarkets">


##### 2 Fahrradrouting
###### 2.1 Planungsfrage
Wie viele Menschen können den Bahnhof innerhalb von 5 Minuten mit dem Fahrrad erreichen? 
###### 2.2 Arbeitsschritte
1. Ändern Sie den Routingmodi zu „Radfahrer“.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/cycling-mode.png" title="Routing mode cycling" style="height:200px;">


2. Stellen Sie die Isochronen Reichweite auf 5 Minuten.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/isochrone-range.png" title="Adjusting isochrone range" style="height:200px;">


3. Platzieren Sie den Startpunkt für die Isochronenberechnung auf dem Bahnhof.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/starting-point-isochrone.png" title="Starting point isochrone" style="height:150px;">


4. Nachdem die Berechnung ausgeführt wurde, öffnet sich automatisch ein Fenster mit den Ergebnissen. Diesem können Sie entnehmen, wie viele Menschen den Bahnhof innerhalb von 5 Minuten mit dem Fahrrad erreichen können.
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/isochrone_trainstation.png" title="Reached population">


##### 3 Rollstuhlrouting
###### 3.1 Planungsfrage
- Wie unterscheidet sich die 10-minütige Erreichbarkeit des Klinikums zwischen einem nicht eingeschränktem Fußgänger und einer mobilitätseingeschränkten Person? 
- Wo befinden sich Barrieren im Netzwerk und wie könnten diese behoben werden? 


###### 3.2 Arbeitsschritte

1. Wählen Sie den Routingmodus „Fußgänger“.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/walking-mode.png" title="Routing mode walking" style="height:200px;">

2. Stellen Sie die Isochronen Reichweite auf 10 Minuten.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/isochrone_range_walking.png" title="Adjusting isochrone range" style="height:200px;">

3. Platzieren Sie den Startpunkt für die Isochronenberechnung am Eingang des Klinikums.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/starting-point-isochrone.png" title="Starting point isochrone" style="height:150px;">

4. Wählen Sie den Routingmodus „Rollstuhl“ und wiederholen Sie die Berechnung.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/wheelchair-mode.png" title="Routing mode wheelchair" style="height:200px;">

5. Zur besseren Vergleichbarkeit kann die Isochrone für den Fußgänger im Menu blau eingefärbt werden. Bei Betrachtung der Isochronen wird sichtbar, wie sich die Erreichbarkeit einer mobilitätseingeschränkten Person (rote Isochrone) im Vergleich zu einem Fußgänger (blaue Isochrone) unterscheidet.
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/isochrone_wheelchair.png" title="Isochrone comparison">

6. Um die konkreten Barrieren im Netwerk zu finden, können Sie für beide Isochronen das verwendete Straßennetzwerk einblenden. Diesem können Sie entnehmen, welche Straßen für das entsprechende Routing verwendet wurden.  
<img class="img-responsive" src="../../img/Docs/training materials/Isochrone/additional-layer.png" title="Activate additional layers" style="height:250px;">

 