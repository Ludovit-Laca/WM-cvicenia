## Identifikácia sedení: STT_Q

Identifikujte sedenia na základe kvartilového odhadu časového okna (STT_Q). (= hornyQ + 1.5*Qrozpatie)

Odovzdajte zdrojový kód programu + logovací súbor doplnený o identifikáciu používateľov (v jednom zip).

Príkazy v Pythone vhodné pre riešenie tohto zadania:

```
import pandas as pd
pd.read_csv() - načítanie log súboru
quantile() - metóda na vypočítanie kvartilu (0.25 - dolný kvartil, 0.75 - horný kvartil)
```
