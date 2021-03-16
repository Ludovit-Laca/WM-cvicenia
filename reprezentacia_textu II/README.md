## Reprezentácia textu II

Pomocou knižnice nltk v Pythone extrahujte lemy slov (základy slov) z anglických textov získaných z webu (Texty z webu.zip).

Následne vytvorte dátovú maticu, ktorá bude obsahovať frekvenciu lém v jednotlivých dokumentoch, z ktorej odvodíte binárnu, logaritmickú a inverznú frekvenciu.

Odovzdajte výsledný súbor a zdrojový kód v jednom zip súbore.

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
```

Postup dosiahnutia výsledkov:

načítajte texty do Pythonu;
rozdeľte vety na slová pomocou príkazu: wordsList = nltk.word_tokenize(word)
inicializovať lematizátor: lemmatizer = WordNetLemmatizer();
získajte základ slova (lemmu) pre dané slová: lemmatizer.lemmatize(word);
