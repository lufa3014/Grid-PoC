## Projekt Game Design (Gruppe04)   
# <b>G.R.I.D.

## Voraussetzungen  
_**Betriebssystem**_: Windows 10 & 11  
_**Eingabegeräte**_: Tastatur & Maus  
_**Grafikkarte**_: Getestet auf 3 Systemen mit NVIDIA Grafiktreibern

## Steuerung  
_**Kamera**_: WASD  
_**Zoom**_: Mausrad

**Aktionen**:  
- _**Linksklick**_:  
  _Auswahl (UI-Elemente oder direkt auf dem Spielfeld; einfach das entsprechende Tile anklicken — wenn ein Monster auf dem Tile ist)._  
- _**Rechtsklick**_:  
  _Auswahl aufheben (Aktuell ausgewähltes Element wird abgewählt. Wenn mal was verbuggt ist, sollte ein Rechtsklick das Problem fixen)._

## Benutzeroberfläche:  
- _**Mittleres UI-Element (unten)**_:  
  _Item-Auswahl: Mit Linksklick wählst du ein Item aus, dann ziehst du es per Drag & Drop aufs Spielfeld. Über die Pfeile daneben kannst du das Item wechseln._
  
- _**Linkes UI-Element (unten)**_:  
  _Info-Element: Zeigt Infos zum aktuell ausgewählten Element. Interaktion ist nicht möglich._

- _**Linke UI-Leiste**_:  
  _Beschwörungs-Auswahl: Mit Linksklick wählst du eine Beschwörung aus und platzierst sie dann auf einer freien Plattform. Eine Plattform ist ein Item und muss vorher über das Item-Menü auf dem Spielfeld platziert werden._

## Beschwörungen:  
_Nicht alle Beschwörungen passen auf jede Plattform. Es gibt 1x1 und 2x2 Plattformen. Die Größe der Beschwörung wird im UI angezeigt, und nur passende Größen können platziert werden._

## Besonderheit: Switch-Beschwörung  
_Mit Switch wählst du zwei beschworene Monster der gleichen Größe auf dem Spielfeld aus und vertauschst deren Positionen._

## Feindliche Monster  
_Die feindlichen Monster spawnen nach ca. 40-50 Sekunden, wenn sich das Portal komplett geöffnet hat._

## Kampfverhalten  
_Sowohl eigene als auch feindliche Monster greifen automatisch an. Deine Aufgabe: Items und Monster auf dem Spielfeld platzieren._

## Elemente  
Das Spiel verwendet ein Schere-Stein-Papier-Prinzip für die Elemente:  
_**Feuer > Natur > Wasser > Feuer**_

## Level-Auswahl  
Über die Zahlen-Tasten 1 bis 4 können Level ausgewählt werden:  
- Die ersten beiden Level sind Late-Game-Beispiele mit unterschiedlichen Decks.
- Das dritte Level ist ein Early-Game-Level.
- Das vierte Level zeigt ein Deck, welches nur Natur-Monster enthält. Die Feinde sind Feuer-Monster, welche das Natur-Element komplett kontern.

## Bekannte Bugs:  
- _Auswahl funktioniert nicht richtig: Manchmal wird das ausgewählte Element nicht richtig angezeigt oder kann nicht platziert werden. Rechtsklick und erneutes Auswählen sollte helfen._
  
- _Feindliche Monster buggen durch: Manchmal laufen feindliche Monster durch eigene Felder, wenn sie sich schnell bewegen._

- _Projektile nach Switch: Geschossene Projektile verfolgen nach einem Switch immer noch das alte Ziel._
