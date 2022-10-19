# Bauteilliste

## Gehäuse
Wo bekommt man das Gehäuse her oder wie baut man es?

## Computer
1. Raspberry Zero W
2. ...

## Software

### Betriebssystem
Als Betriebssystem sollte ein Linux Derivat, passend für die HW-Plattform verwendet werden.
Die Bluetooth Verbindungen sollten aus Energie-Spargründen immer abgeschaltet sein.

### Applikationen
Damit eine höchstmögliche, schnelle UND energiesparende Verarbeitung möglich ist, sollte alles eine HTML Seite sein.
Da keine Daten gespeichert werden, zumindest nicht für lange, können hier geringe Datenschutz-Maßnahmen verwendet werden.

## Energieversorgung
Ohne autarke Energieversorgung ist ein C-Kit relativ schnell nutzlos.
Die Energieversorgung muß so ausgelegt sein, daß sie selbststartend ist. 
Sollte der Akku leer geworden sein, weil längere Zeit weder der Wind wehte noch die Sonne schien, so muß sich das C-Kit selbst ständig wieder
in Betrieb nehmen, sobald wieder genügend Energie zur Verfügung steht, sprich entweder der Akku wieder aufgeladen ist oder die beiden Energieerzeuger wieder 
arbeiten.

Die Priorität ist, daß zunächst der Akku zu mindestens 10% geladen sein muß, damit nicht bei der ersten Wolke oder kurzen Windstille das C-Kit wieder 
stromlos wird. Erst dann nimmt das C-Kit seine Arbeit wieder auf und stellt eine Netzwerk-Verbindung her.

### Photovoltaik
Photovoltaik ist leicht, kostengünstig und sehr zuverlässig einsetzbar.

### Windrad
Ein Windrad liefert auch dann Strom, wenn die Sonne untergegangen ist und bildet im Zweifelsfall eine zusätzliche Energiequelle zur Photovoltaik.
Eine Bauanleitung befindet sich hier: LINK

### Akku / Powerbank
Sollte mal weder die Sonne scheinen, noch der Wind ausreichend wehen, dann übernimmt die Powerbank oder die Akkus die Energieversorgung.
Der Akku / Powerbank sollte in der Lage sein über den aktuellen Ladestand Auskunft zu geben.
