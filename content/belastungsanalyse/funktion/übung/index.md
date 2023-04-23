---
title: "Übung"
description: "Wie die Belastungsanalyse von A bis Z durchgeführt wird"
lead: "Wie die Belastungsanalyse von A bis Z durchgeführt wird"
date: 2020-10-13T15:21:01+02:00
lastmod: 2020-10-13T15:21:01+02:00
draft: false
images: []
menu:
  belastungsanalyse:
    parent: "funktion"
weight: 1010
---

In dieser Übung werden wir eine Belastungsanalyse Schritt für Schritt zusammen aufbauen und durchführen.

## Bauteil konstruieren

Bevor wir eine Belastungsanalyse durchführen können, brauchen wir ein Bauteil mit dem wir arbeiten können. Klickt hier für eine technische Zeichnung von dem Bauteil mit welchem wir weiter arbeiten werden.
![Stuhl](Stuhl.PNG)

## Grundlegende Einstellungen

Am Anfang müssen wir ein paar grundlegende Einstellungen tätigen.

In der oberen Leiste im Menü `3D-Modell` könnt ihr auf den Punkt `Belastungsanalyse` klicken.
![Belastungsanalyse_Button](Belastungsanalyse_Button.PNG)

Ihr gelangt damit in ein neues Menü, in dem ihr auf `Studie Erstellen` drücken könnt.
![Studie_Erstellen](Studie_Erstellen.PNG)

Ein Fenster öffnet sich. Hier solltet ihr oben der Studie einen Namen geben. In diesem Fall bietet sich der Name `Stuhl` an. Dann könnt ihr auf OK klicken.
![Studie_Erstellen_Window](Studie_Erstellen_Window.PNG)

Ihr werdet nun sehen, dass sich links ein Menü öffnet. Dieses gibt euch einen Überblick über alle Informationen die Ihr für die Belastungsanalyse braucht.
![Studie_Erstellen_Menu](Studie_Erstellen_Menu.PNG)

Dieses Menü ist eine sehr gute Übersicht über alles, was getan werden muss, um eine Belastungsanalyse durchzuführen.

## Materialien festlegen

Damit Inventor weiß, welche Eigenschaften ein Bauteil hat, muss man ihm ein Material zuweisen.

Dafür müsst Ihr auf den Material Reiter doppelklicken.
![Studie_Erstellen_Menu_Material](Studie_Erstellen_Menu_Material.PNG)

Damit öffnet sich ein neues Fenster, in dem Ihr für alle Komponenten Materialien zuweisen könnt. In unserem Fall haben wir nur eine Komponente, weswegen wir auch nur eine Zeile haben. Hier solltet Ihr nun in dem DropDown Menü ein Material auswählen. Welches Ihr wählt ist euch überlassen.
{{< alert icon="💡" text="Manche Materialien haben ein gelbes Ausrufezeichen neben sich. Bei diesen liegen nicht ausreichend Daten für Inventor vor, sodass wir mit diesen leider nicht weiterarbeiten können." />}}
![Materialien_Menu](Materialien_Menu.PNG)

Wenn ihr euer Material ausgewählt hab, könnt ihr das Menü unten mit OK schließen.

## Abhängigkeiten definieren

Als nächstes müssen wir dem Bauteil ein paar Abhängigkeiten definieren. Diese dienen dazu, dass Inventor weiß, wo das bauteil z.b. Fest verankert ist.
![Abhängigkeiten_Menu](Abhängigkeiten_Menu.PNG)

Bei unserem Stuhl bietet es sich an, die 4 Beine unten auf dem Boden zu fixieren. Dazu einfach auf die 4 unteren Flächen des Stuhls drücken.
![Abhängigkeiten_Festlegen](Abhängigkeiten_Festlegen.PNG)

## Lasten und Belastungen definieren

## Durchführung der Simulation

## Interpretation der Ergebnisse
