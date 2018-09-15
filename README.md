# Numerik-Klausurvorbereitung-2018

Antworten zu den Fragen auf dem Klausurvorbereitungsbogen

## Auslöschung
 
1. Was ist Auslöschung?:

Wenn 2 fast gleich große Zahlen subtrahiert werden gibt es einen Präzisionsverlust.

2. Was ist die Kondition eine Problems, einer Rechenoperation, oder einer Matrix?:

eines Problems:
unvermeidbare Fehlerverstärkung bei optimaler Lösungsmethode

einer Rechenoperation:

einer Matrix:

3. Wie ist die Menge der Gleitkommazahlen definiert?

## Direkte Lösungsverfahren für lineare Gleichungssysteme
1. Wieviele Operationen werden für die Lösung eines Gleichungssystems benötigt?

vollbesetzt

Bandmatrizen

symmetrische Matrizen

2. Wie werden Zerlegungen von Matrizen dafür verwendet?:

Durch Zerlegungen entstehen leichter lösbare LGS welche man mit Vorwärts- und Rückwärtssubstitution löst.

## Lineare Ausgleichsrechnung
1. Wozu ist Ausgleichsrechnung erforderlich?:

Wenn eine LGS nicht oder nicht eindeutig Lösbar ist.

2. In welchen Fällen wird eine Regularisierung benötigt? Warum?:

Die Aufgabe ist schlecht konditioniert. z. B. $Ax = b$ mit $\kappa(A) >> 1$

oder die Aufgabe ist nicht sachgemäß gestellt und nicht eindeutig lösbar, oder Lösung nicht stetig abhängig der Daten.
z. B. $|Ax-b|_2 = min$ 


## Eigenwertberechnung
1. Für welche Anwendungen werden Eigenwerte und Eigenvektoren benötigt?:

PageRankverfahren

Schwingungen (Eigenfrequenzen)

2. Wieviele Operationen werden für die Eigenwertapproximation durch die QR-Iteration benötigt?:

$O(N^3)$
 
## Iterationsverfahren für lineare Gleichungssysteme
1. Wozu benötigt man iterative Lösungsverfahren?
2. Was ist der Unterschied von Jacobi- und Gauß-Seidel-Verfahren?
3. Was ist die Iterationsmatrix von einem iterativen Lösungsverfahren?
4. Was sagen die Eigenwerte der Iterationsmatrix über die Konvergenz aus?

## Iterationsverfahren für nichtlineare Gleichungssysteme
1. Was ist das Newton-Verfahren?:

iteratives Verfahren zum approximieren von Nullstellen

$x_{n+1} = x_n - \frac{f(x_n)}{f'(x_n)}$

2. Wie wird z. B. die $n$-te Wurzel mit dem Newton-Verfahren berechnet?

Erstelle die Funktion $f: x \mapsto x^n - a$ und suche die Nullstelle.

3. Wie wird eine Minimierungsaufgabe mit dem Newton-Verfahren berechnet?

## Polynom-Interpolation
1. Was berechnet das Neville-Schema?

Auswertung des interpolierenden Polynom in $O(n^2)$ ohne explizit das Polynom berechnen zu müssen. 

2. Durch wieviele Punktwerte ist ein Polynom vom Grad N eindeutig bestimmt?
 
 
 
3. Wie groß ist ist der Rechenaufwand, wenn ein Punkt hinzugefügt wird?

## Splines
1. Was ist der Unterschied zu einer Polynom-Interpolation und einem Spline?

Splines haben einen geringeren Grad und sind somit flacher. 

2. Mit welcher Randbedingungen ist ein kubischer Spline eindeutig bestimmt?



3. Wie groß ist der Rechenaufwand zur Bestimmung von einem Spline?



4. Wie berechnet man einen Spline durch 3 Punkte?
 

## Trigonometrische Interpolation und FFT
1. Wozu kann man FFT verwenden?



2. Wieviele Operationen benötigt die diskrete Fourier-Transformation?

 
## Numerische Integration
1. Was ist eine Quadraturformel?



2. Wie berechnet man die Gewichte einer Quadraturformel?



3. Wie wird die Genauigkeit einer Quadraturformel gemessen?
 
## Integrationsverfahren für gewöhnliche Differentialgleichungen
1. Was ist das Runge-Kutta-Verfahren? Geben Sie zwei Beispiele an.



2. In welchen Eigenschaften unterscheiden sich diese Verfahren?
