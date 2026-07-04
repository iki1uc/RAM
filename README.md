# RAM — 4-Wertigkeiten-Speichermodul

Das RAM-Modul ist ein technisches Hardware-Modul, das vier Speicher-Wertigkeiten hält
und pro Zyklus weiterreicht. RAM dient als neutrale Zwischenebene für schnelle Datenzugriffe.

## Wertigkeiten

RAM liefert pro Zyklus vier neutrale Speicherwerte:

1. **BLOCK** – Speicherblock / Segment  
2. **CACHE** – Zwischenspeicher / Kurzzeitwert  
3. **FLOW** – Datenfluss / Transferrate  
4. **STATE** – Speicherzustand / Stabilität  

Alle vier Werte werden synchron gehalten, aber jeder besitzt seinen eigenen Verlauf.

## Funktionen

Das RAM-Modul führt folgende Aufgaben aus:

- **BLOCK-Control** – Segmentierung des Speichers  
- **CACHE-Control** – Kurzzeitpuffer  
- **FLOW-Control** – Datenflussberechnung  
- **STATE-Control** – Stabilitätsbewertung  

Jede Funktion arbeitet unabhängig, aber alle vier Werte werden gemeinsam weitergereicht.

## Ressourcen

RAM nutzt geschätzte Systemwerte:

- **RAM-Größe:** 4096 MB  
- **RAM-Speed:** 12 Gbps  
- **CACHE-Level:** 3  
- **STEP_A:** Block-Schritt  
- **STEP_B:** Flow-Schritt  

## Systemwerte

RAM übernimmt globale Werte:

- **GATE:** GATE_21  
- **EICH:** EICH_04  
- **KETTE:** KETTE_33  
- **CLUSTER:** 33~33(1)  

## Modi

RAM unterstützt zwei Betriebsmodi:

- **4all** – Vierfach-Speicherzyklus  
- **32all** – Zweiunddreißigfach-Speicherzyklus  

Beide Modi steuern die Geschwindigkeit der Speicherzyklen.

## Dateien

### index.html

Die Oberfläche besteht aus vier Anzeige-Elementen:

- jeder Wert = eigenes Feld  
- alle Felder aktualisieren synchron  
- RAM liefert alle Werte pro Zyklus

### ram.js

ram.js steuert:

- Speicherblöcke  
- Cache  
- Datenfluss  
-
