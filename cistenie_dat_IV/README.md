## Čistenie dát IV

Čistenie dát od robotov vyhľadávacích služieb:

- identifikujte robotov na základe poľa User-Agent (Agent) - kľúčové slová bot, crawl, spider.

- zmažte prístupy robotov vyhľadávacích služieb na základe prístupov z IP adries a kľúčových slov v User-Agent.

Odovzdajte zdrojový kód programu + očistený logovací súbor (v jednom zip).

Príkazy v Pythone vhodné pre riešenie tohto zadania:

```
import pandas as pd
pd.read_csv() - načítanie log súboru
```

Po očistení by ste mali mať približne 20000 záznamov.
