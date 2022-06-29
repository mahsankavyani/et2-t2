# Berechnungsverfahren für Gleichstromnetzwerke


# Inhaltsverzeichnis

> **Verzweigte Stromkreise**<script input="button" onClick="location.href='#3'" style="float:right;">"Zum Kapitel"</script>

> **Kirchhoffsche Gleichungen**<script input="button" onClick="location.href='#3'" style="float:right;">"Zum Kapitel"</script>

> **Zweigstromverfahren**<script input="button" onClick="location.href='#3'" style="float:right;">"Zum Kapitel"</script>

> **Machsenstromverfahren**<script input="button" onClick="location.href='#3'" style="float:right;">"Zum Kapitel"</script>

> **Knotenpotentialverfahren**<script input="button" onClick="location.href='#3'" style="float:right;">"Zum Kapitel"</script>

> **Stern-Dreieck-Schaltung**<script input="button" onClick="location.href='#3'" style="float:right;">"Zum Kapitel"</script>

# Verzweigte Stromkreise


Bei den verzweigten Stromkreise teilt sich der Strom auf und fließt durch verschiedene Widerstände.  Im  Folgenden verwenden wir die Begriffe wie Strom, Spannung, Widerstand, Ohmsches Gesetz etc, die vorher in dem Kurs Grundbegriffe der Elektrotechnik erklärt würden.

Elektrische Stromkreise bestehen normaleweise aus zwei elementaren Strukturelementen:

<iframe src="http://www.falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcMBMcUHYMGZIA4UA2ATmIxAUgoqoQFMBaMMAKADcRjCRtC9PuAFn5Uqg2lEkwELAO4CQw8MRSL+reWBVqQKPPyWQ5u-Tux5BOo5u1bVe9dusnHq85btRjD3Sks-PZx8UP2V7UKMAZxdff1NcS1EQADMAQwAbSLoWaM8Qj20EqRSMrOMuHj4wypFjT15+HwavACcYvCoAwUTkOG9TMG6YwP7+DpjDFjbPcc9mVSoweCnqsD1VwiSlvrb3BT21kV7nGcXtSZtVedX1k9tN1adjPaU9iucD9YOntqbIOP42F4km2RmmhX+1SB3EWy3kTWBTSqdzcwPqyJYQA" width="100%" height="600px" overflow="auto" frameborder="0" allowfullscreen="allowfullscreen"></iframe>

Darstellung der Gemischte Widerstandschaltung von Mahsan Kaviani, lizenziert unter CC BY NC ND (4.0), erstellt mit der [App](http://www.falstad.com) von Paul Falstad.

Zweige/Kanten: Verbindungen zwischen zwei Knoten

Knoten: Verbindungspunkte mehrerer Zweige

<!-- class = "animated infinite bounce" style = "animation-delay: %s; color: red" -->ACHTUNG!

<!-- style="background-color: #DDACAC;"-->
>> Zweige haben ~~mindestens~~ ein Bauteil.
>
>> Knoten konnen mehr als zwei Zweige verbinden.


# Kirchhoffsche Gleichungen
!?[Video](https://youtu.be/qkKaNsHdxgc)


## Der Knotensatz [^*]

![Bild](https://upload.wikimedia.org/wikipedia/commons/thumb/7/73/Netzwerkanalyse_-_Knoten_1.svg/110px-Netzwerkanalyse_-_Knoten_1.svg.png " Das [Bild](https://de.wikipedia.org/wiki/Netzwerkanalyse_(Elektrotechnik) von Cepheiden ist lizenziert unter CC 0 ")
Für jeden Knoten ist die Summe der zufließenden Ströme gleich der Summe der abfließenden Ströme

[^*]: empfehlenswert sind die Themen Parallelschaltung von Widerständen und Stromteiler im  Kurs Grundbegriffe der Elektrotechnik.

<figure style="text-align:center">
  <iframe width=420 height=250  src="https://youtu.be/JmX8qO0krFE " frameborder="0" allowfullscreen></iframe>
  <figcaption>Das [Video](https://www.youtube.com/watch?v=JmX8qO0krFE) von
  Wolfgang Bengfort ist lizenziert unter [CC-BY 3.0](https://support.google.com/youtube/answer/2797468)</figcaption>
</figure>



## Der Maschensatz [^*]

Alle Teilspannungen eines Umlaufs bzw. einer Masche in einem elektrischen Netzwerk addieren sich zu null. Die Richtung des Umlaufes kann beliebig gewählt werden; sie legt dann aber die Vorzeichen der Teilspannungen fest.
> Soweit Zählpfeile entgegen der Umlaufrichtung zeigen, sind die Spannungen mit umgekehrten Vorzeichen einzusetzen.

 Zwischen zwei Punkten eines Netzwerks ergibt sich nur eine Potentialdifferenz. Die Potentialdifferenz ist damit insbesondere *unabhängig* davon auf welchem Weg ein Netzwerk zwischen den Punkte
 durchlaufen wird. Dies lässt sich durch die Betrachtung von Maschen beschreiben.

 <figure style="text-align:center">
   <iframe width=420 height=250  src="https://youtu.be/wiLqQ0W7Zcw " frameborder="0" allowfullscreen></iframe>
   <figcaption>Das [Video](https://www.youtube.com/watch?v=JmX8qO0krFE) von
   Wolfgang Bengfort ist lizenziert unter [CC-BY 3.0](https://support.google.com/youtube/answer/2797468)</figcaption>
 </figure>


[^*]: empfehlenswert sind die Themen: Reihenschaltung von Widerständen und Spannungsteiler im  Kurs Grundbegriffe.

## Zweigstromverfahren
Im Zweigstromverfahren werden fast alle Gleichungen der Schaltung aufgestellt.
Für jeden Knoten und jede *unabhängige* Masche die Knoten- und Maschengleichungen aufgeschrieben:

<!-- style="background-color: #82C9C2;"-->
>> für alle Knoten k jeweils die Gleichung: $\sum_{k=0}^{N_k}{I_k}=0$
>
>> für alle unabhängige Maschen m jeweils die Gleichung: $\sum_{m=0}^{N_m}{U_m}=0$
>
> => bildet sich ein lineares Gleichungssystem=> mit Hilfe der Matrixgleichung einfach lösbar

### Allgemeine Schritte


<figure style="text-align:center">
  <iframe width=420 height=250  src="https://youtu.be/d0zVtOhJ-8A " frameborder="0" allowfullscreen></iframe>
  <figcaption>Das [Video](https://www.youtube.com/watch?v=d0zVtOhJ-8A) von
Mathias Magdowski ist lizenziert unter [CC-BY 3.0](https://support.google.com/youtube/answer/2797468)</figcaption>
</figure>

1. Aufschreiben der gegebenen Schaltung und Größen
2. Einzeichnen und Bezeichnen der Knoten
3. Einzeichnen und Bezeichnen der Maschen
4. Einzeichnen und Bezeichnen der Zweigströme
5. Einzeichnen und Bezeichnen der Zweigspannungen
6. Knotengleichungen und Maschengleichungen aufstellen
7. Umwandeln in Matrix-Schreibweise
8. Einfügen der Zahlenwerte
9. Berechnung der Matrix mittels Taschenrechner

# Maschsenstromverfahren

 Mit dieser Methode lassen sich die Zweigströme bestimmen. Denn jedes elektrische Netzwerk kann auf diese Weise durch ein lineares Gleichungssystem beschrieben und berechnet werden.
Im Maschenstromverfahren werden nur für alle Maschen m jeweils die Gleichung: $\sum\limits_{j=0}^{N_j}{U_j}=0$ betrachtet. Diese werden aber in der Form $R\cdot I = U $ dargestellt.

>**Vorteil:** Die Anzahl der zu lösenden Gleichungen reduziert sich auf die Anzahl der unabhängigen Maschenströme.

## Allgemeine Schritte

<figure style="text-align:center">
  <iframe width=420 height=250  src="https://youtu.be/HT0XNq8cjig " frameborder="0" allowfullscreen></iframe>
  <figcaption>Das [Video](https://www.youtube.com/watch?v=HT0XNq8cjig) von
Mathias Magdowski ist lizenziert unter [CC-BY 3.0](https://support.google.com/youtube/answer/2797468)</figcaption>
</figure>

1. Zweigströme festlegen
2. Maschenströme festlegen
3. Zweigströme durch Maschenströme ausdrücken
4. Maschengleichungen aufschreiben
5. Zweigspannungen durch Maschenströme ausdrücken
6. Gleichungssystem in Matrixform
7. Eigenschaften der Matrix
8. Werte der Bauelemente einsetzen
9. Gleichungssystem lösen
10. Zweigströme berechnen



# Knotenpotentialverfahren

<figure style="text-align:center">
  <iframe width=420 height=250  src="https://youtu.be/tpeu84Zq63g " frameborder="0" allowfullscreen></iframe>
  <figcaption>Das [Video](https://www.youtube.com/watch?v=tpeu84Zq63g) von Gerald Oberschmidt ist lizenziert unter [CC-BY 3.0](https://support.google.com/youtube/answer/2797468)</figcaption>
</figure>

!?[Video](https://youtu.be/hnlPFAvIhkY)

Im Knotenpotentialverfahren werden nur für alle Knoten k jeweils die Gleichung: $\sum\limits_{i=0}^{N_i}{I_i}=0$ betrachtet. Diese werden aber in der Form ${1\over R} \cdot U = I $ bzw. $G \cdot U = I $ dargestellt.

>**Vorteil:** Die Anzahl der zu lösenden Gleichungen reduziert sich auf die Anzahl der vorhandenen Knoten (minus 1).


# Stern-Dreieck-Schaltung
![Bild](https://upload.wikimedia.org/wikipedia/commons/5/5f/Stern-Dreieck-Transformation.png) "Das [Bild](https://de.wikipedia.org/wiki/Stern-Dreieck-Transformation#/media/Datei:Stern-Dreieck-Transformation.png) von wdwd ist lizenziert unter CC 0")

<iframe src="https://tinyurl.com/24vfa36p/" width="400" height="600" overflow="auto" frameborder="0" allowfullscreen="allowfullscreen" onload="resizeIframe(this)"></iframe>


Bei einige Schaltungen kommt man mit dem Knoten- und Maschensatz nicht unmittelbar zur Lösung. Da dort viele dreieckförmige Maschen bzw. sternförmige Knoten vorhanden sind.Durch entsprechende Anwendung dieser beiden Transformationen und der Regeln für Parallelschaltung und Reihenschaltung von Widerständen können im Rahmen der Schaltungsanalyse vereinfachte Ersatzwiderstände komplizierter Widerstandsnetzwerke gebildet werden.

## Dreieckschaltung

<iframe src="https://www.falstad.com/circuit/circuitjs.html?ctz=CQAgjA7CAMB00IQVhvCEAcGGYMzQjABZoUkA2EFI3KgUwFowwAoAJRCaKPAkqbAAmXpWgwQJcMLEzYSFgHdOxHpH5hyYteBYAnToIjDtDQYJ7mZ4RHuV8RBow6039TeybMXJLhIs74qvamWA6sHAyBDpG4lNpWkmBWsvJKpuYghsLpFhQ6EV6ZTjmZoQliouJw8gAeBgCctGb1BuQYmbjC3iBsAJ0sdaYQquTZguQj1ODtAIb+Ie2eTvHzGlrB2iuDghi0YBgtpprg9V0SYoAzpAPKB9OHGnGnEucgV9uxmUhgBmBNSDwAy7XJgYFAaWjuMHkSiqdoAI2BgiSnzG0G+giQU32IAAxvNChj+ASfIinIIPqYkE1cC1Ybi5oM1h11ER0TTnti4XjGRh0YJ7nlyWcMn1ETRwER2qZsWAvs8Rf1tmZwJiDNBjEh2nSZgigA" width="100%" height="600px" overflow="auto" frameborder="0" allowfullscreen="allowfullscreen"></iframe>

Darstellung der Dreieckschaltung von Mahsan Kaviani, lizenziert unter CC BY NC ND (4.0), erstellt mit der [App](http://www.falstad.com) von Paul Falstad.

Bei der Dreieckschaltung sind die 3 Widerstände $R_{ab}^1$, $R_{bc}^1$ und $R_{ca}^1$ in einer Masche verschalten.

Für die Widerstände zwischen den zwei Anschlüssen (z.B. $a$ und $b$) wird die dritte ($c$) als nicht angeschlossen betrachtet. Damit ergibt sich eine Parallelschaltung des direkten Dreieckswiderstands $R_{ab}^1$ mit der Reihenschaltung der anderen beiden Dreieckswiderstände $R_{ca}^1 + R_{bc}^1$:

$R_{ab} = R_{ab}^1 || (R_{ca}^1 + R_{bc}^1) $
$R_{ab} = {{R_{ab}^1 \cdot (R_{ca}^1 + R_{bc}^1)}\over{R_{ab}^1 + (R_{ca}^1 + R_{bc}^1)}} =  {{R_{ab}^1 \cdot (R_{ca}^1 + R_{bc}^1)}\over{R_{ab}^1 + R_{ca}^1 + R_{bc}^1}} $

Gleiches gilt für die anderen Anschlüssen. Damit ergibt sich:


$R_{ab} = {{R_{ab}^1 \cdot (R_{ca}^1 + R_{bc}^1)}\over{R_{ab}^1 + R_{ca}^1 + R_{bc}^1}} $

$R_{bc} = {{R_{bc}^1 \cdot (R_{ab}^1 + R_{ca}^1)}\over{R_{ab}^1 + R_{ca}^1 + R_{bc}^1}} $

$R_{ca} = {{R_{ca}^1 \cdot (R_{bc}^1 + R_{ab}^1)}\over{R_{ab}^1 + R_{ca}^1 + R_{bc}^1}} $

## Sternschaltung

<iframe src="https://www.falstad.com/circuit/circuitjs.html?ctz=CQAgjA7CAMB00IQVhvCEAcGGYMzQjABZoUkA2EFI3KgUwFowwAoAdxAYCYsqBOLpy4RBSATHacw5aP0FMIlMYOgsASkK5EQEaNu5adXWSZAkQlU3CSSD23fq6HyvVhob5tyzrlxLxpuZgVqg2HB56ckK83qwATlKKUXYWhrK+uLAZ2SwJKeSG3CJR6b5Z2b65mtoFjs7FpZkVleHEXuJMMlFuUkTt8syiATBmsmAqI9YsAB5CuFBIGPJc41QY1CCGagCdM0LSa3xSfP6C2mAYIABGqrPcfDVclNzkRwVH2lu7d8K05L5CJB-PxmcCXACGtyEBAs5H0F0E5HIUE+2h2eyYGEoyLAUmRFgg2nOlwAxlDuBgoDJHHCLDCibJADOkGOElyQ6CELjWsmJIHBGIutHZRwUQqWoIu1wFlLpKE6NWglwZIGZPyIlxczy4uDeGA+YJAJJZINejjAfz4KNGKtsThqxXyvFUQA" width="100%" height="600px" overflow="auto" frameborder="0" allowfullscreen="allowfullscreen"></iframe>




Darstellung der Sternschaltung von Mahsan Kaviani, lizenziert unter CC BY NC ND (4.0), erstellt mit der [App](http://www.falstad.com) von Paul Falstad.

Die Widerstände zwischen den Anschlüssen müssen nun denen bei der Sternschaltung gleichen. Auch bei der Sternschaltung sind 3 Widerstände verschalten, diese aber in Sternform. Die Sternwiderstände sind also alle mit einem weiteren Knoten $0$ in der Mitte verbunden: $R_{a0}^1$, $R_{b0}^1$ und $R_{c0}^1$

Auch hier wird vorgegangen wie bei der Dreieckschaltung: der Widerstand zwischen zwei Anschlüssen (z.B. $a$ und $b$) wird ermittelt, der weitere Anschluss ($c$) wird als offen betrachtet. Der Widerstand des weiteren Anschlusses ($R_{c0}^1$) ist nur an einer Seite angeschlossen. Dadurch fließt durch diesen kein Strom - er ist damit nicht zu berücksichtigen. Es ergibt sich:


$ R_{ab} = R_{a0}^1 + R_{b0}^1 $

$R_{bc} = R_{b0}^1 + R_{c0}^1  $

$R_{ca} = R_{c0}^1 + R_{a0}^1  $


Aus den Gleichungen erhält man:

$ R_{ab} = {{R_{ab}^1 \cdot (R_{ca}^1 + R_{bc}^1)}\over{R_{ab}^1 + R_{ca}^1 + R_{bc}^1}} = R_{a0}^1 + R_{b0}^1 $

$ R_{bc} = {{R_{bc}^1 \cdot (R_{ab}^1 + R_{ca}^1)}\over{R_{ab}^1 + R_{ca}^1 + R_{bc}^1}} = R_{b0}^1 + R_{c0}^1 $

$ R_{ca} = {{R_{ca}^1 \cdot (R_{bc}^1 + R_{ab}^1)}\over{R_{ab}^1 + R_{ca}^1 + R_{bc}^1}} = R_{c0}^1 + R_{a0}^1 $


Diese Gleichungen lassen sich nun so geschickt zusammenfassen, dass auf einer Seite nur noch ein Widerstand steht.

Eine Variante ist die Formeln als ${{1}\over{2}} \cdot \left(R_{ab} + R_{bc} - R_{ca}\right)$ zu kombinieren. Damit ergibt sich $R_{b0}^1$




## Stern-Dreieck-Transformation

Umwandlung der **Dreieckschaltung in eine Sternschaltung**:


<figure style="text-align:center">
  <iframe width=420 height=250  src="https://youtu.be/xvucxI3yOyw " frameborder="0" allowfullscreen></iframe>
  <figcaption>
  Das [Video](https://www.youtube.com/watch?v=xvucxI3yOyw) von Gerald Oberschmidt ist lizenziert unter [CC-BY 3.0](https://support.google.com/youtube/answer/2797468)</figcaption>
</figure>


<iframe src="https://h5p.org/h5p/embed/1274196" width="1090" height="295" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *" title="test1"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>


<iframe src="/test.html" width="100%" height="759" frameborder="0" scrolling="no"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>
