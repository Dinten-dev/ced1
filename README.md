# CED1

## Ordnerstruktur

```
ced1
├── .gitignore
├── README.md
├── data
    └── SNC_240387
    └── strukturerhebung
    └── volkszählung
├── notebooks
    └── final.html
    └── final.Rmd
    └── fragenstellung_1.Rmd
    └── fragenstellung_3.Rmd
    └── fragenstellung_7.Rmd
    └── fragenstellung_8.Rmd
    └── fragenstellung_9.Rmd
    └── fragenstellung_11.Rmd
└── scripts
    └── all_hh_data.R
    └── all_zp_data.R
    └── haushalte.R
    └── zp_2021.R
```


## Getting started

#### Clone Branch

```
git clone git@gitlab.fhnw.ch:ds-trio/ced1.git
```

#### Benötigte Libraries installieren

```
install.packages(dplyr)
install.packages(ggplot2)
install.packages(tidyverse)
install.packages(ggpubr)
install.packages(reshape)
install.packages(magrittr)
install.packages(stringr)
```

#### Benötigte Daten importieren

Die Daten des Bundesamts für Statistik werden in dem Ordner ```data``` in der oben aufgeführten Ordnerstruktur erwartet.
Dieser ist leer und wird von git ignoriert.


#### Markdown File starten

Das Markdown File mit dem Namen ```final.rmd``` ist unser Bericht und sollte nun lauffähig sein. Ein zusätzliches HTML ist noch verfügbar.


## Anderes

Die anderen Markdown Files sind vereinzelt auf anderen Branches als auf dem Hauptbranch ```main``` zu finden und nur bedingt lauffähig.