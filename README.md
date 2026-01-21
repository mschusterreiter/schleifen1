# Übung 10 - Schleifen


## 1. Aufgabe

Folgendes Klassendiagramm soll umgesetzt werden:

<p align="center">
  <img src="/assets/images/UML1.png" alt="Bildbeschreibung" />
</p>

**Folgende Bedingungen gelten für die Eigenschaften:**
- `grenze` hat den Wertebereich 0 bis 200.

**Folgende Bedingungen gelten für die Methoden:**
- Im Konstruktor müssen statt der Zuweisung die `set`-Methoden aufgerufen werden.
- Die Parameternamen des Konstruktors müssen gleich den Eigenschaftsnamen sein. 
- `while1()`: Gibt die Zahlen von 0 bis 10 mit Schrittweite 1 aus.
- `while2()`: Gibt die Zahlen von 10 bis 20 mit Schrittweite 2 aus.
- `while3()`: Gibt die Zahlen von 10 bis -10 mit Schrittweite -1 aus.
- `while4(int anzahl)`: Gibt eine bestimmte Anzahl von Zahlen, bei null beginnend, mit der Schrittweite 5 aus.
- `while5()`: Schleife von 0 bis `grenze`. Gibt jedoch bei jedem Durchlauf ein Minus vor der Zahl aus.
- `while6(int start)`: Gibt alle Zahlen von `start` bis `grenze` mit folgender Schrittweite aus:
	- `start < grenze`: Schrittweite +1
	- `start > grenze`: Schrittweite -1
- `while7(int gr1, int gr2)`: Zählt vom kleineren Parameter zum größeren Parameter. Schrittweite 1.
- `while8(int start)`: Gibt die geraden Zahlen von `start` bis `grenze` aus. Sollte start ungerade sein, mindern Sie den Wert um eins.
- `while9()`: Gibt eine Folge von Brüchen aus bis der Zähler gleich der `grenze` ist. 
**Beispiel:** 1/5, 2/6, 3/7, 4/8, …

Um Ihr Programm zu testen, erstellen Sie eine `Main`-Klasse, welche die `main`-Methode beinhaltet:
- `main(String[] args)`: Testen Sie Ihr Programm. Verwenden Sie den Scanner!

## 2. Aufgabe

Folgendes Klassendiagramm soll umgesetzt werden:

<p align="center">
  <img src="/assets/images/UML2.png" alt="Bildbeschreibung" />
</p>

**Folgende Bedingungen gelten für die Methoden:**
- `einmaleinsTabelle(int zahl)`: Überprüft, ob sich die angegebene Zahl im Intervall [1, 10] befindet. In diesem Fall gibt die Methode das Einmaleins der Zahl aus. Andernfalls eine geeignete Fehlermeldung.
**Beispiel:** einmaleinsTabelle(5)

<p align="center">
  1 * 5 = 5 <br>
   2 * 5 = 10 <br>
   3 * 5 = 15 <br>
   4 * 5 = 20 <br>
   5 * 5 = 25 <br>
   6 * 5 = 30 <br>
   7 * 5 = 35 <br>
   8 * 5 = 40 <br>
   9 * 5 = 45 <br>
   10 * 5 = 50
</p>

- `teilbar(int von, int bis, int zahl)`: Gibt jene Zahlen im Intervall `[von, bis]` aus, die durch `zahl` teilbar sind. 
**Beispiel:** teilbar(15, 40, 3)
<p align="center">
  Im Intervall [15, 40] sind die folgenden Zahlen durch 3 teilbar: <br>
  15, 18, 21, 24, 27, 30, 33, 36, 39
</p>

- `produkt(int von, int bis)`: Gibt das Produkt aller Zahlen im Intervall `[von, bis]` aus. 
**Beispiel:** produkt(5,7)
<p align="center">
5 * 6 * 7 = 210
</p>

Um Ihr Programm zu testen, erstellen Sie eine `Main`-Klasse, welche die `main`-Methode beinhaltet:
- `main(String[] args)`: Testen Sie Ihr Programm. Verwenden Sie den Scanner!

## 3. Aufgabe

Bauen Sie die Klasse `Kaffeemaschine` aus der letzten Übung um. In der `kochen`-Methode sollen nun keine Zahlen mehr vom Benutzer eingelesen werden, sondern gleich die Art des Kaffees. Es soll dabei egal sein, ob der Benutzer mit großen oder kleinen Buchstaben schreibt. Zudem muss die Kaffeemaschine nicht nur eingeschalten sein, wenn sie verwendet werden soll, sondern auch mindestens 200 Wasser beinhalten. Sollten Sie den Zusatz der letzten Übung noch nicht umgesetzt haben, so implementieren Sie diesen auch. Erstellen Sie für die Kaffeemaschinen-Klasse eine Java-Doc.

Der Zusatz war: Setzen Sie auch das Auffüllen von Wasser und Bohnen mit dem Scanner um.


Um Ihr Programm zu testen, erstellen Sie eine `Main`-Klasse, welche die `main`-Methode beinhaltet:
- `main(String[] args)`: Erstellen Sie eine Instanz der Kaffeemaschinenklasse. Erstellen Sie einen Scanner und testen Sie mit verschiedenen Eingaben Ihr Programm.
