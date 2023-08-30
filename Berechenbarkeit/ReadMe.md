# Berechenbarkeit #

Ein Zirkel zu Problemen, die Computer nicht lösen können (Endliche Automaten, Kellerautomaten, Turingmaschinen)

Kapitel 2,3,4 und 5 sind im Wesentlichen unbhängig voneinander


## Vorwissen ##

* keines


## Benötigte Materialien ##

* keine (man kann zur Erklärung von Automaten gut ein einfaches Prop aus einem Streifen Papier (dem Band) und einem Blatt Papier mit einem Fenster darin verwenden)


## Ziele/Motivation ##

Verstehen, dass es (interessante/relevante!) Probleme gibt, die kein Computerprogramm lösen kann. Um dies beweisen zu können muss man sich ein formales (abstraktes) Modell für einen Computer überlegen. Dafür gibt es verschiedene Möglichkeiten (Endliche Automaten, Kellerautomaten, Turingmaschinen)


## Erfahrungen ##

Einmal gehalten, in ca. 2 1/2 Stunden, nur Kapitel zu Endlichen Automaten, dafür mit viel Interaktion und Zeit zum Selberlösen

Pumping-Lemma sollte genauer erklärt werden. Insbesondere im Hinblick darauf, was man selbst wählen darf und was gegeben ist. Evtl. als Spiel mit einem Gegenspieler darstellen? Gibt es ein einfacheres Beispiel für eine derartige Aussage, mit der man anfangen könnte?

Evtl. den ersten Beweis zur Existenz nicht-entscheidbarer Probleme weglassen. An sich wäre es schön diesen gesehen zu haben um später die Analogie im Beweis zur Unentscheidbarkeit des Halteproblems sehen zu können. Aber wenn man dann gar nicht so weit kommt, ist das vielleicht nicht so sinnvoll.


## Mathematische Caveats ##

Endliche Automaten/Kellerautomaten/Turingmaschinen werden nicht formal definiert. Ich habe aber den Eindruck, dass ein Beispiel genügt um das Konzept zu verstehen. Verbleibende Unklarheiten (z.B.: Darf es mehrere ausgehende Kanten mit dem selben Buchstaben geben) bieten dann einen guten Ausgangspunkt für Diskussionen.

Das Pumping-Lemma für Kellerautomaten verwenden wir hier ohne Beweis, da der übliche Beweis über Grammatiken läuft (was wir hier nicht einführen). Es scheint auch einen direkten Beweis zu geben, analog zu dem für das Pumping-Lemma für Endliche Automaten ( https://arxiv.org/abs/1207.2819 ) - der wirkt auf mich aber deutlich aufwändiger.

## Quellen ##

* Die Skripten von Prof. Vogler und Prof. Hagerup zu "Theoretischer informatik"