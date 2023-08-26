# Die Random-Bibliothek
Es kann außerdem wichtig sein, Zufallszahlen in Python zu erhalten. Um einen Bereich zwischen zwei Zahlen zu bestimmen,
verwenden wir `randint()`:
```py
import random
x = random.randint(0, 100)
print(x)
```
Die Zahl ist jetzt eine zufällige Zahl zwischen 0 und 100.

## Liste aller Unterfunktionen der Math-Bibliothek

|     Funktion      | Beschreibung                                                                                                                                                                                          |
|:-----------------:|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|      seed()       | Initialisiert den Zufallszahlengenerator                                                                                                                                                              |
|    getstate()     | Gibt den aktuellen internen Zustand des Zufallszahlengenerators zurück                                                                                                                                |
|    setstate()     | Stellt den internen Zustand des Zufallszahlengenerators wieder her                                                                                                                                    |
|   getrandbits()   | Gibt eine Zahl zurück, die die zufälligen Bits repräsentiert                                                                                                                                          |
|    randrange()    | Gibt eine Zufallszahl im angegebenen Bereich zurück                                                                                                                                                   |
|     randint()     | Gibt eine Zufallszahl im angegebenen Bereich zurück                                                                                                                                                   |
|     choice()      | Gibt ein zufälliges Element aus der angegebenen Sequenz zurück                                                                                                                                        |
|     choices()     | Gibt eine Liste mit einer zufälligen Auswahl aus der gegebenen Sequenz zurück                                                                                                                         |
|     shuffle()     | Nimmt eine Sequenz und gibt die Sequenz in einer zufälligen Reihenfolge zurück                                                                                                                        |
|     sample()      | Gibt eine bestimmte Stichprobe einer Sequenz zurück                                                                                                                                                   |
|     random()      | Gibt eine zufällige Gleitkommazahl zwischen 0 und 1 zurück                                                                                                                                            |
|     uniform()     | Gibt eine zufällige Gleitkommazahl zwischen zwei gegebenen Parametern zurück                                                                                                                          |
|   triangular()    | Gibt eine zufällige Gleitkommazahl zwischen zwei gegebenen Parametern zurück, wobei auch ein Mode-Parameter festgelegt werden kann, der den Mittelpunkt zwischen den beiden anderen Parametern angibt |
|   betavariate()   | Gibt eine zufällige Gleitkommazahl zwischen 0 und 1 basierend auf der Beta-Verteilung zurück                                                                                                          |
|   expovariate()   | Gibt eine zufällige Gleitkommazahl basierend auf der Exponentialverteilung zurück                                                                                                                     |
|  gammavariate()   | Gibt eine zufällige Gleitkommazahl basierend auf der Gamma-Verteilung zurück                                                                                                                          |
|      gauss()      | Gibt eine zufällige Gleitkommazahl basierend auf der Gaußschen Verteilung zurück                                                                                                                      |
| lognormvariate()  | Gibt eine zufällige Gleitkommazahl basierend auf einer log-normalen Verteilung zurück                                                                                                                 |
|  normalvariate()  | Gibt eine zufällige Gleitkommazahl basierend auf der normalen Verteilung zurück                                                                                                                       |
| vonmisesvariate() | Gibt eine zufällige Gleitkommazahl basierend auf der von Mises Verteilung zurück                                                                                                                      |
|  paretovariate()  | Gibt eine zufällige Gleitkommazahl basierend auf der Pareto-Verteilung zurück                                                                                                                         |
| weibullvariate()  | Gibt eine zufällige Gleitkommazahl basierend auf der Weibull-Verteilung zurück                                                                                                                        |

Tabelle siehe [w3schools](https://www.w3schools.com/python/module_random.asp).