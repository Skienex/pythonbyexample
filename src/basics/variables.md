# Variablen
Variablen in Python sind Wörter, in denen Daten gespeichert sind. 

Wir können in Variablen Text, sowie Zahlen speichern. 
Eine Variable in Python sieht dann so aus:
```python
erste_variable = "Hallo Welt"
zweite_variable = 5
```
Um an diese Daten zu kommen, müssen wir nun nur noch den Variablennamen verwenden. Man kann Variablen auch als Argumente
von [Funktionen](hello_world.md) verwenden.

Das würde dann so aussehen:
```python
text = "Hallo Welt"
print(text)
```
Der Computer würde uns dann`Hallo Welt` ausgeben.

## Variablen als Ergebnis einer Rechnung
Man kann auch Ergebnisse von Rechnungen in Variablen speichern. Wichtig dabei ist, dass man Berechnungen nur mit Zahlen
durchführen kann. Eine Zeichenkette funktioniert nicht!

Das sieht dann so aus:
```python
ergebnis = 5 + 10
```
Die Variable `ergebnis` würde dann 15 sein.

## Variablen mit Text in print() kombinieren
Wenn man Text und Variablen in einem Satz ausgeben will, kann man dies auch direkt mit der `print()` Funktion machen.
Das sieht dann so aus:
```py
text = "Python"
print(python + " ist super!")
```

In der Konsole steht jetzt:
```cmd
Python ist super!
```

