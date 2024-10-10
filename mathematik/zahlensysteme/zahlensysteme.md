# Zahlensysteme

## Theoretische Fragen 1


1. ### **Was sind Zahlensysteme?**

	A: Zahlensysteme sind Methoden zur Darstellung von Zahlen mithilfe bestimmter Ziffern und einer Basis. Beispiele sind das Dezimalsystem (Basis 10), das Binärsystem (Basis 2), das Hexadezimalsystem (Basis 16) und das Oktalsystem (Basis 8). Sie definieren, wie Zahlen geschrieben und berechnet werden.



2. ### **Was sind Stellenwertsysteme und wie funktionieren sie?**

	A: Stellenwertsysteme sind Zahlensysteme, bei denen der Wert einer Ziffer von ihrer Position abhängt. Jede Stelle entspricht einer Potenz der Basis des Systems, und die Zahl ergibt sich aus der Summe der Werte aller Ziffern.



3. ### **Was ist die Basis eines Stellenwertsystems und wofür benötigt man die Basis?**

	A: **Die Basis eines Stellenwertsystems gibt an, wie viele verschiedene Ziffern verwendet werden. Sie bestimmt, welche Potenzen für die Stellenwerte genutzt werden. Man benötigt die Basis, um den Wert jeder Ziffer in einer Zahl zu berechnen.**



4. ### **Was ist die Stellenzahl und wie ermittelt man sie?**

	A: Die Stellenzahl gibt an, wie viele Ziffern eine Zahl in einem bestimmten Zahlensystem hat. Man ermittelt sie, indem man die Anzahl der Ziffern von links nach rechts zählt, beginnend bei der höchsten Stelle.



5. ### **Wie ermittelt man den Stellenwert einer Stelle im Stellenwertsystem?**

	A: Den Stellenwert einer Stelle ermittelt man, indem man die Basis des Zahlensystems mit der Potenz der Position der Stelle multipliziert. Die Potenz entspricht der Position der Ziffer von rechts nach links, beginnend bei 0.



6. ### **Wie wird die Wertigkeit einer Zahl im Stellenwertsystem ermittelt? Bringe ein Beispiel anhand des Dezimalsystems (Basis=10).**

	A: Die **Wertigkeit** einer Zahl im Stellenwertsystem wird ermittelt, indem man die Produkte der Ziffern mit ihren entsprechenden Stellenwerten summiert.

**Beispiel im Dezimalsystem (Basis 10):**  
Für die Zahl **452**:

- 4 steht an der Stelle \(10^2\) (Hundert): \(4 \times 10^2 = 400\)
- 5 steht an der Stelle \(10^1\) (Zehner): \(5 \times 10^1 = 50\)
- 2 steht an der Stelle \(10^0\) (Einer): \(2 \times 10^0 = 2\)

**Wertigkeit:**  
\(400 + 50 + 2 = 452\)**



7. ### **Nenne Zahlensysteme, die du im Alltag verwendest!**

	A: Im Alltag verwenden wir hauptsächlich folgende Zahlensysteme:

- **Dezimalsystem (Basis 10):** Für alltägliche Rechnungen und Zahlen.
- **Binärsystem (Basis 2):** In der Informatik und digitalen Geräten.
- **Hexadezimalsystem (Basis 16):** In der Programmierung und Computertechnik.
- **Römisches Zahlensystem:** Für bestimmte historische oder kulturelle Kontexte (z. B. in Uhren oder Namen von Monarchen).



8. ### **Welche Zahlensysteme sind in der IT wichtig?**
  
	A: **In der IT sind folgende Zahlensysteme besonders wichtig:**

- **Binärsystem (Basis 2):** Grundlage der digitalen Technik, da Computer mit 0 und 1 arbeiten.
- **Hexadezimalsystem (Basis 16):** Wird häufig in der Programmierung verwendet, insbesondere zur Darstellung von Speicheradressen und Farbwerten.
- **Oktalsystem (Basis 8):** Weniger verbreitet, aber in einigen Unix-Systemen und älteren Programmiersprachen genutzt.
- **Dezimalsystem (Basis 10):** Für Benutzereingaben und Ausgaben in Anwendungen.

_________


## Theoretische Fragen 2


1. ### **Erkläre Anwendungsbereiche des Binärsystems!**

	A: Das Binärsystem hat mehrere wichtige Anwendungsbereiche:

- **Computertechnik:** Alle Daten und Instruktionen werden in Form von 0 und 1 gespeichert und verarbeitet, da Computer mit elektrischen Signalen arbeiten, die zwei Zustände (ein/aus) repräsentieren.
- **Digitale Schaltungen:** Logikgatter und digitale Schaltungen nutzen das Binärsystem, um komplexe Berechnungen und Funktionen zu realisieren.
- **Programmierung:** In vielen Programmiersprachen werden Werte und Daten in binärer Form dargestellt, insbesondere bei der Arbeit mit Bits und Bytes.
- **Datenübertragung:** Netzwerke und Kommunikationsprotokolle verwenden das Binärsystem zur Codierung und Übertragung von Informationen.
- **Kryptografie:** Verschlüsselungstechniken basieren oft auf binären Operationen zur Sicherung von Daten.



2. ### **Erkläre Anwendungsbereiche des Hexadezimalsystems!**

	A: Anwendungsbereiche des Hexadezimalsystems:

- **Programmierung:** Verwendung zur Darstellung von Speicheradressen und Farbwerten in Webdesign (z. B. #FF5733 für Farben).
- **Computerspeicher:** Hexadezimale Darstellung vereinfacht das Lesen und Verstehen von Speicherinhalten.
- **Debugging:** Programmierer nutzen Hexadezimalzahlen, um Daten in Debugging-Tools besser zu interpretieren.
- **Kryptografie:** Verwendung in Verschlüsselungstechniken und Hash-Funktionen.
- **Netzwerkprotokolle:** Darstellung von IP-Adressen und MAC-Adressen in einer kompakteren Form.



3. ### **Erkläre die Umrechnung einer Dezimalzahl in Binär!**

	A: Die Umrechnung einer Dezimalzahl in eine Binärzahl erfolgt durch wiederholte Division. Hier sind die Schritte:

Teile die Dezimalzahl durch 2. Notiere den ganzzahligen Quotienten und den Rest (0 oder 1).
Wiederhole den Vorgang mit dem Quotienten, bis der Quotient 0 ist.
Die Binärzahl wird aus den Resten gebildet, beginnend mit dem letzten Rest bis zum ersten.
Beispiel: Umrechnung von 13 in Binär

13 ÷ 2 = 6, Rest 1

6 ÷ 2 = 3, Rest 0

3 ÷ 2 = 1, Rest 1

1 ÷ 2 = 0, Rest 1

Die Reste von unten nach oben ergeben die Binärzahl: 1101.



4. ### **Erkläre die Umrechnung einer Binärzahl in Dezimal!**

	A: Die Umrechnung einer Binärzahl in eine Dezimalzahl erfolgt durch die Summierung der Produkte der Ziffern mit den entsprechenden Potenzen von 2. Hier sind die Schritte:

- **Schreibe die Binärzahl auf** und nummeriere die Ziffern von rechts nach links, beginnend mit 0.
- **Multipliziere jede Ziffer** (0 oder 1) mit \(2^{\text{Position}}\) (der Position).
- **Summiere die Ergebnisse** der Produkte.

**Beispiel: Umrechnung von 1011 in Dezimal**


1. Ziffern: 1 0 1 1 (von rechts nach links: 3, 2, 1, 0)
2. Berechnung:
   
   - ( 1 0 1 1 )
   - ( 1 * 2³ + 0 * 2² + 1 * 2 + 1 * 2^0 )
     
4. **Summiere die Ergebnisse:** \(8 + 0 + 2 + 1 = 11\)

Die Binärzahl **1011** entspricht also der Dezimalzahl **11**.

















