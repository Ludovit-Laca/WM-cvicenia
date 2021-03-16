## Reprezentácia textu III

Pokračujte s textami z predchádzajúceho cvičenia (Texty z webu.zip). Spracujte nasledujúce zadanie s pomocou knižnice nltk v Pythone:

- Rozdeľte texty na vety a identifikujte v nich slová, pre ktoré si budete pamätať, ku ktorej vete patria.
- Odstráňte z matice tzv. stop slová a priraďte slovám poradie v danej vete.
- Pomocou morfologickej anotácie otagujte jednotlivé slová.
- Vytvorte dátový súbor, ktorý bude obsahovať všetky dané slová z identifikátorom vety, daným slovom, jeho slovným základom (lema), tagom a poradím vo vete.
- Odovzdajte výsledný súbor a zdrojový kód v jednom zip súbore.

Importy v Pythone vhodné pre riešenie tohto zadania:

```
import nltk
from nltk.corpus import stopwords 
from nltk.tokenize import word_tokenize, sent_tokenize 
from nltk.stem import WordNetLemmatizer 

nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('stopwords')
nltk.download('wordnet')

stop_words = set(stopwords.words('english')) 

tagged = nltk.pos_tag(wordsList)
```
