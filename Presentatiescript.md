# Presentatiescript – Go/No-go
## Armoede in Nederland | Tiemen & Thijs

*Spreektijd: ca. 2,5 minuten*

---

### TIEMEN – Introductie & Data (ca. 1 minuut)

"Ons onderzoek gaat over armoede in Nederland. We wilden dit kwantificeren: hoe groot is het probleem, voor wie, en waar?

Als databron hebben we twee CBS-tabellen gebruikt. De eerste geeft nationale armoedecijfers per huishoudenstype van 2011 tot 2024, de tweede geeft provinciale cijfers voor het jaar 2022. Die data hebben we zelf gedownload van CBS Open Data en ingeladen in R.

De data was niet meteen klaar voor analyse. We moesten eerst filteren: de dataset bevat zowel nationale als regionale rijen, dus we hebben alleen de nationale rijen geselecteerd. Daarna hebben we de juiste inkomensgrens gekozen, want er zijn meerdere varianten. Ten slotte moesten we de provincienamen harmoniseren, want de kaart gebruikte 'Friesland' terwijl CBS 'Fryslân' schrijft. Dat soort dingen ga je pas zien als je écht met de data aan de slag gaat.

We hebben ook twee nieuwe variabelen aangemaakt. De eerste is het jaar-op-jaar verschil in armoede, zodat je kunt zien hoe snel het stijgt of daalt. De tweede is een logische variabele die aangeeft of een provincie boven het nationale gemiddelde zit."

---

### THIJS – Visualisaties & Conclusie (ca. 1,5 minuut)

"We hebben vier visualisaties gemaakt om de data te analyseren.

De eerste is een tijdreeks van 2011 tot 2024. Daarin zie je duidelijk dat armoede piekte in 2013 op bijna 9%, en daarna gestaag daalde naar 3,6% in 2024. Dat is een enorme daling over 10 jaar.

De tweede grafiek splitst dat uit per huishoudenstype. En daar zie je een groot verschil: eenoudergezinnen zitten structureel veel hoger dan andere typen. In 2013 zat dat op 21%, terwijl paren met kinderen maar op 4 tot 5% zaten. Dat verschil is belangrijk voor beleid.

De derde visualisatie is een kaart van Nederland. Daarin zie je dat Zuid-Holland en Groningen de hoogste armoedecijfers hebben, wat waarschijnlijk komt door de grote steden in die provincies. Zeeland en Drenthe scoren juist het laagst.

Als laatste hebben we gekeken naar de impact van COVID-19. Wat opvalt is dat armoede na 2020 juist verder daalde, ondanks de economische schok. Het gemiddelde daarvoor lag op 8%, daarna op 5,8%. Dat is waarschijnlijk te verklaren door de overheidssteun, zoals de NOW-regeling.

Onze conclusie is dat armoede in Nederland sterk is gedaald, maar niet voor iedereen even snel. Eenoudergezinnen en alleenstaanden blijven kwetsbaar. In de rest van het onderzoek willen we hier dieper op ingaan en ook kijken of er causale verbanden te vinden zijn."

---

*Tip: oefen het één keer hardop, dan zit de tijd goed.*
