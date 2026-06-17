# Armoede in Nederland

Onderzoek naar armoede in Nederland (2011–2024) voor het vak "Quantifying a Social Problem".

**Auteurs:** Tiemen & Thijs

## Hoe te reproduceren

1. Clone deze repository
2. Download de databestanden (zie hieronder) en zet ze in de hoofdmap van het project
3. Open `Armoede - Onderzoek.Rmd` in RStudio
4. Klik op **Knit** om het rapport te genereren als PDF

### Benodigde R-packages

```r
install.packages(c("tidyverse", "sf", "knitr"))
```

### Databestanden downloaden

De databestanden zijn te groot voor GitHub en staan daarom niet in de repository. Download ze als volgt:

**Dataset 1: CBS 85678NED (Laag inkomen per regio)**
1. Ga naar https://opendata.cbs.nl/statline/#/CBS/nl/dataset/85678NED
2. Klik op "Volledige dataset downloaden"
3. Kies CSV-formaat (puntkomma gescheiden)
4. Sla het bestand op als `Observations.csv` in de projectmap
5. Download ook de bijbehorende `RegioSCodes.csv` (regiocodetabel)

**Dataset 2: CBS 83841NED (Laag inkomen huishoudens)**
1. Ga naar https://opendata.cbs.nl/statline/#/CBS/nl/dataset/83841NED
2. Download de bijbehorende `KenmerkenVanHuishoudensCodes.csv`

Het kaartbestand (GeoJSON provinciegrenzen) wordt automatisch opgehaald via internet bij het knit-proces.

## Structuur

```
armoede-onderzoek/
├── Armoede - Onderzoek.Rmd   # Hoofdrapport (R Markdown)
├── README.md                  # Dit bestand
├── .gitignore                 # Sluit grote databestanden uit
├── Observations.csv           # NIET in repo (>100MB), zelf downloaden
├── RegioSCodes.csv            # NIET in repo, zelf downloaden
└── KenmerkenVanHuishoudensCodes.csv  # NIET in repo, zelf downloaden
```
