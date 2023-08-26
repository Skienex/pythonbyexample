# Die Math-Bibliothek

Bei komplexen mathematischen Berechnungen kann es notwendig sein, z.B. Wurzeln zu verwenden. Diese sind jedoch
ohne Bibliotheken schwer möglich zu berechnen. Deswegen gibt es die `math`-Bibliothek.

Um eine Bibliothek zu installieren, schreibst du ganz oben im Python Code `import <Bibliothek>`.
In unserem Fall schreiben wir:

```py
import math
```

Wenn wir nun die Quadratwurzel von 9 berechnen wollen schreiben wir den Bibliothek-Namen, einen Punkt und
unsere Operation (in unserem Fall Quadratwurzel ziehen). Wir haben also eine Funktion, die wiederum mehrere Funktionen
enthält:

```py
import math
x = math.sqrt(9)
print(x)
```

Das Programm wird uns nun 3 ausgeben, da die Wurzel aus 9, 3 ist.

## Liste aller Unterfunktionen der Math-Bibliothek

|      Funktion      | Beschreibung                                                                                                              |
|:------------------:|---------------------------------------------------------------------------------------------------------------------------|
|   `math.acos()`    | Gibt den Arkuskosinus einer Zahl zurück                                                                                   |
|   `math.acosh()`   | Gibt den inversen hyperbolischen Kosinus einer Zahl zurück                                                                |
|   `math.asin()`    | Gibt den Arkussinus einer Zahl zurück                                                                                     |
|   `math.asinh()`   | Gibt den inversen hyperbolischen Sinus einer Zahl zurück                                                                  |
|   `math.atan()`    | Gibt den Arkustangens einer Zahl in Radiant zurück                                                                        |
|   `math.atan2()`   | Gibt den Arkustangens von y/x in Radiant zurück                                                                           |
|   `math.atanh()`   | Gibt den inversen hyperbolischen Tangens einer Zahl zurück                                                                |
|   `math.ceil()`    | Rundet eine Zahl auf die nächste Ganzzahl auf                                                                             |
|   `math.comb()`    | Gibt die Anzahl der Möglichkeiten zurück, k Elemente aus n Elementen ohne Wiederholung und Reihenfolge auszuwählen        |
| `math.copysign()`  | Gibt eine Fließkommazahl zurück, die aus dem Wert des ersten Parameters und dem Vorzeichen des zweiten Parameters besteht |
|    `math.cos()`    | Gibt den Kosinus einer Zahl zurück                                                                                        |
|   `math.cosh()`    | Gibt den hyperbolischen Kosinus einer Zahl zurück                                                                         |
|  `math.degrees()`  | Konvertiert einen Winkel von Radiant in Grad                                                                              |
|   `math.dist()`    | Gibt den euklidischen Abstand zwischen zwei Punkten (p und q) zurück, wobei p und q die Koordinaten dieses Punktes sind   |
|    `math.erf()`    | Gibt die Fehlerfunktion einer Zahl zurück                                                                                 |
|   `math.erfc()`    | Gibt die komplementäre Fehlerfunktion einer Zahl zurück                                                                   |
|    `math.exp()`    | Gibt E hoch x zurück                                                                                                      |
|   `math.expm1()`   | Gibt \(E^x - 1\) zurück                                                                                                   |
|   `math.fabs()`    | Gibt den absoluten Wert einer Zahl zurück                                                                                 |
| `math.factorial()` | Gibt die Fakultät einer Zahl zurück                                                                                       |
|   `math.floor()`   | Rundet eine Zahl auf die nächste Ganzzahl ab                                                                              |
|   `math.fmod()`    | Gibt den Rest von x/y zurück                                                                                              |
|   `math.frexp()`   | Gibt die Mantisse und den Exponenten einer angegebenen Zahl zurück                                                        |
|   `math.fsum()`    | Gibt die Summe aller Elemente in einem Iterable (Tupel, Arrays, Listen usw.) zurück                                       |
|   `math.gamma()`   | Gibt die Gamma-Funktion bei x zurück                                                                                      |
|    `math.gcd()`    | Gibt den größten gemeinsamen Teiler von zwei Ganzzahlen zurück                                                            |
|   `math.hypot()`   | Gibt die euklidische Norm zurück                                                                                          |
|  `math.isclose()`  | Überprüft, ob zwei Werte einander nahe sind oder nicht                                                                    |
| `math.isfinite()`  | Überprüft, ob eine Zahl endlich ist oder nicht                                                                            |
|   `math.isinf()`   | Überprüft, ob eine Zahl unendlich ist oder nicht                                                                          |
|   `math.isnan()`   | Überprüft, ob ein Wert NaN (nicht eine Zahl) ist oder nicht                                                               |
|   `math.isqrt()`   | Rundet eine Quadratwurzelzahl auf die nächste Ganzzahl ab                                                                 |
|   `math.ldexp()`   | Gibt das Inverse von `math.frexp()` zurück, welches \(x * (2^i)\) der gegebenen Zahlen x und i ist                        |
|  `math.lgamma()`   | Gibt den Log-Gamma-Wert von x zurück                                                                                      |
|    `math.log()`    | Gibt den natürlichen Logarithmus einer Zahl oder den Logarithmus einer Zahl zur Basis zurück                              |
|   `math.log10()`   | Gibt den Basis-10-Logarithmus von x zurück                                                                                |
|   `math.log1p()`   | Gibt den natürlichen Logarithmus von 1+x zurück                                                                           |
|   `math.log2()`    | Gibt den Basis-2-Logarithmus von x zurück                                                                                 |
|   `math.perm()`    | Gibt die Anzahl der Möglichkeiten zurück, k Elemente aus n Elementen mit Reihenfolge und ohne Wiederholung auszuwählen    |
|    `math.pow()`    | Gibt den Wert von x hoch y zurück                                                                                         |
|   `math.prod()`    | Gibt das Produkt aller Elemente in einem Iterable zurück                                                                  |
|  `math.radians()`  | Konvertiert einen Gradwert in Radiant                                                                                     |
| `math.remainder()` | Gibt den nächstgelegenen Wert zurück, der den Zähler durch den Nenner vollständig teilbar macht                           |
|    `math.sin()`    | Gibt den Sinus einer Zahl zurück                                                                                          |
|   `math.sinh()`    | Gibt den hyperbolischen Sinus einer Zahl zurück                                                                           |
|   `math.sqrt()`    | Gibt die Quadratwurzel einer Zahl zurück                                                                                  |
|    `math.tan()`    | Gibt den Tangens einer Zahl zurück                                                                                        |
|   `math.tanh()`    | Gibt den hyperbolischen Tangens einer Zahl zurück                                                                         |
|   `math.trunc()`   | Gibt die abgeschnittenen Ganzzahlteile einer Zahl zurück                                                                  |

Tabelle siehe [w3schools](https://www.w3schools.com/python/module_math.asp).