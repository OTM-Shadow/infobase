# Theoretische Fragen 1

1. **Was ist die Boolesche Algebra und wie lautet ihre Grundmenge?**

Die Boolesche Algebra ist eine mathematische Struktur für logische Operationen, die auf den Zuständen (Grundmenge) {0, 1} basiert, entsprechend „wahr“ und „falsch“.

2. **Was ist die Schaltalgebra?**

Die Schaltalgebra ist eine spezielle Form der booleschen Algebra, welche bei digitalen Schaltungen genutzt wird.

Ihre Grundoperationen sind UND (∧), ODER (∨) und NICHT (¬).

Manchmal sieht man auch die Symbole "&&" sowie "||" und "!" (UND, ODER, NICHT)

3. **Was ist die Aufgabe von Logikgattern?**

Logikgatter haben 1, 2 oder mehrere Eingänge und verknüpfen diese zu einem Ausgang Q.

Für bestimmte Zustände der Eingänge ist ein bestimmter Zustand am Ausgang definiert.

Logikgatter werden miteinander zu Schaltungen verbunden.

* Liste der Logikgattern:
 * AND, OR, NOT, NAND, NOR, XOR und XNOR


4. **Inwiefern wird die Schaltalgebra bei Computern eingesetzt?**

Die Schaltalgebra bildet die Funktion des Prozessors ab. (z.B. wie eine Addition in der Schaltung umgesetzt ist)

Durch Schaltalgebra und Logikgatter können Computer logische Operationen und Berechnungen durchführen, z.B., bei Additionen in Addierwerken oder beim Vergleich von Daten.

5. **Erkläre anhand der Wahrheitstabellen die Funktionsweise folgender Gatter. Gib auch die zugehörigen Schaltsymbole (IEC, DIN und ANSI) an.**
 
https://de.wikipedia.org/wiki/Logikgatter#Typen_von_Logikgattern_und_Symbolik
 
* UND-Gatter

Ein UND Gatter wird nur Wahr, wenn alle Eingänge 1 sind.

| A| B| Q|
|--|--|--|
| 0| 0| 0|
| 0| 1| 0|
| 1| 0| 0|
| 1| 1| 1|

IEC:

![image](https://github.com/user-attachments/assets/963a85d6-e3a0-4377-b476-c0a1a588dc5b)

ANSI:

![image](https://github.com/user-attachments/assets/e260b7df-8f35-4a34-8b14-daabeb91b8a5)

DIN:

![image](https://github.com/user-attachments/assets/06e3e972-06c2-4b86-abfd-8f3f5a8c5480)


* ODER-Gatter

Ein ODER Gatter wird Wahr, wenn ein oder mehrere Eingänge 1 sind.

| A| B| Q|
|--|--|--|
| 0| 0| 0|
| 0| 1| 1|
| 1| 0| 1|
| 1| 1| 1|

IEC:

![image](https://github.com/user-attachments/assets/02f72e3f-a723-4aa6-8dc7-82f92145e0ba)

ANSI:

![image](https://github.com/user-attachments/assets/30955297-55ce-4434-a154-831ee5e31317)

DIN:

![image](https://github.com/user-attachments/assets/b3440e7c-4280-4b6e-94ad-afba7d8f62f5)





* NICHT-Gatter

Ein NICHT-GATTER Kehrt das Eingangssignal um

|A|¬A|
|---|---|
|0|1|
|1|0|

IEC:

![image](https://github.com/user-attachments/assets/8f6ad618-ec66-4c42-94d8-d0468917524c)

ANSI:

![image](https://github.com/user-attachments/assets/152658f7-27a4-41c2-9ef5-538892e5eceb)

DIN:

![image](https://github.com/user-attachments/assets/67cbee78-6073-44bf-b38a-7d440cfcf8a4)




* XOR-Gatter

Das XOR Gatter is dann wahr, wenn genau einer der Eingänge auf 1 ist, sollten jedoch alle Eingänge auf 1 sein gibt das XOR-Gatter 0 aus.

- **Wahrheitstabelle:**

|A|B|A XOR B|
|---|---|---|
|0|0|0|
|0|1|1|
|1|0|1|
|1|1|0|

IEC:

![image](https://github.com/user-attachments/assets/14b471e6-026b-498c-b083-5d452cfd6ad5)

ANSI:

![image](https://github.com/user-attachments/assets/2f5c6f64-f3fa-4ceb-94d0-d938a5cf5e6d)

DIN:

![image](https://github.com/user-attachments/assets/d99c061e-75f1-4e02-b4df-f97629864920)

oder

![image](https://github.com/user-attachments/assets/94ca3f7a-49ef-484f-9a0b-fa3a9c071d0a)




6. **Was sind negierte Gatter? Erkläre anhand von Wahrheitstabelle, gib die Schaltsymbole an!**
Negierte Gatter sind Gatter, die die Logik des Eingangs invertieren. Beispiele sind das NAND- und NOR-Gatter.

Jedes Gatter kann durch Anhängen eines NICHTs negiert werden. Dabei wird jeweils der Ausgang invertiert.

In der Schaltung kann man dies mit einem kleinen Ring am Ausgang des Symbols darstellen.

![image](https://github.com/user-attachments/assets/9376547e-52ae-40d0-a31d-f487907e62cc)
![image](https://github.com/user-attachments/assets/5b4e9045-3255-45f0-89a9-fa0c72ba1de0)



7. **Welche anderen Möglichkeiten gibt es, 2 Zustände miteinander zu verknüpfen? Wie viele einzigartige Verknüpfungen mit 2 Eingängen gibt es?**

Andere Möglichkeiten zur Verknüpfung von zwei Zuständen sind unter anderem:

- **XNOR-Gatter (Negiertes XOR):** Gibt nur dann 1 aus, wenn beide Eingänge gleich sind.
- **NAND-Gatter:** Gibt 1 aus, es sei denn, beide Eingänge sind 1.
- **NOR-Gatter:** Gibt nur dann 1 aus, wenn beide Eingänge 0 sind.

Es gibt insgesamt 16 mögliche Verknüpfungen mit 2 Eingängen, da jeder Eingang 2 Zustände haben kann (0 und 1) und es 2^4 = 16 mögliche Kombinationen von Ausgaben (true/false) gibt.

Nicht jeder davon wird oft benutzt.

Man kann die Möglichkeit, 2 Zustände zu verknüpfen angeben, in dem man alle diskreten Ausgangszustände angibt. (z.B. für "UND": $Q = \{0,0,0,1\}$). Dabei korrespondiert jeder Eintrag in der Mengenklammer zu einer Zeile für mögliche Eingangszustände.

![](https://hedgedoc.itlabs.at/uploads/64f2c518-816e-40c3-8060-8f6d2cd90e52.png)



