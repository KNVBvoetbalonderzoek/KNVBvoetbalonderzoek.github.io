# Team voetbalonderzoek

## KNVB voetbalonderzoek coding style

* Bestanden
  + Naamgeving
* Syntax
  + Naamgeving objecten
  + Spacing
  + Argument names
  + Comments
 
## Repository Templates
Voor iedere analyse maken we een aparte repository aan. De naam van deze repository voldoet aan de naamgevingsregels die we binnen het team gebruiken
De reposity bestaat altijd uit de volgende 

```
repository-naam
├── data/                  # Main source code directory
├── code/                  # Deze map zouden al je code moeten in R- moeten bevatten.
│                          # Je kunt kiezen voor een paar grote scripts, of meerdere scripts die alleen specifieke acties uitvoeren.
├── results/               # Deze map en submappen bevatten resultaten die door de code zijn geproduceerd, zoals figuren en tabellen, en andere bestanden.
├── output                 # De bestanden binnen deze map zouden alle output van je project moeten bevatten.
│                          # Voor een typisch analyseproject zal dit het eindrapport zijn.
│                          # Als een figuur of ander bestand wordt gemaakt door het uitvoeren van code, 
│                          # zou dit in een submap binnen /results moeten worden geplaatst.
├── docs                   # De mappen binnen deze map zouden alle output van je project moeten bevatten.
└── README.md              # Project documentatie
```
