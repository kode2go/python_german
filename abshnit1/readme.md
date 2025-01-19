# Functions - Funktionen

Als nächstes könnten wir uns Funktionen anschauen. Funktionen helfen dir, wiederverwendbaren Code zu schreiben. Du kannst Funktionen definieren, um bestimmte Aufgaben zu erledigen, und sie dann im Programm aufrufen. Eine einfache Funktion sieht so aus:

```
def gruessen(name):
    print(f"Hallo, {name}!")
    
gruessen("Anna")
```

Hier definieren wir eine Funktion gruessen, die einen Namen als Parameter nimmt und eine Begrüßung ausgibt. Wenn du mehr darüber erfahren möchtest, lass es mich wissen!

Hier ist ein Beispiel für eine Funktion:

```
def addiere(a, b):
    return a + b

ergebnis = addiere(3, 5)
print(ergebnis)  # Gibt 8 aus
```

# Data Science - Datenwissenschaft

Data Science wird im Deutschen oft als Datenwissenschaft bezeichnet. Hier ist ein einfaches Beispiel für Data Science in Python:

```
import pandas as pd

# Eine einfache Datenreihe erstellen
daten = {
    'Name': ['Anna', 'Bob', 'Caro'],
    'Alter': [25, 30, 22]
}
df = pd.DataFrame(daten)

# Die Daten anzeigen
print(df)
```

Das ist ein einfaches Beispiel, um mit Daten zu arbeiten.
