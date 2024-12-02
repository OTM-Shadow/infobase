# RAM (Random Access Memory) - Arbeitsspeicher

## Thoretische Fragen 1

---
1. **Was ist Arbeitsspeicher?**
   
  * Arbeitsspeicher, auch RAM (Random Access Memory) genannt, ist ein Bauteil in deinem Computer. Er speichert Daten und Programme, die der Computer gerade verwendet, damit der Prozessor schnell auf sie zugreifen kann.

  **Einfach gesagt:**
  Stell dir vor, dein Computer ist ein Büro. Der RAM ist der Schreibtisch, auf dem du aktuelle Dokumente liegen hast. Du kannst sie schnell greifen und bearbeiten. Wenn du fertig bist, kommen die Dokumente ins Archiv (z. B. Festplatte oder SSD).


---
2. **Was ist die Speicherhierarchie eines Computers? (mit Diagramm!)**
   
  * Die Speicherhierarchie beschreibt, wie Daten in einem Computer organisiert werden, um einen guten Mix aus Geschwindigkeit, Kapazität und Kosten zu haben.
    
    ![image](https://github.com/user-attachments/assets/ebff85b4-1d80-44ca-a075-03e8bf7df581)


---
3. **Wie unterscheidet sich RAM von anderen Speichergeräten wie z.B. der Festplatte?**
   
  * RAM und Festplatten (z. B. SSDs) haben unterschiedliche Aufgaben und Eigenschaften:
    
  |Merkmal         |Ram                                |Festplatte                           |
  |----------------|-----------------------------------|-------------------------------------|
  |Geschwindigkeit |Sehr schnell (Nanosekunden-Bereich, Datenübertragung: 10-40GB/s)|Langsamer (Millisekunden-Bereich, Datenübertragung: (HDD) 100-200MB/s, (SSD) 1-2 GB/s)|
  |Speicherart     |Flüchtig (Daten gehen verloren)	   |Dauerhaft (Daten bleiben gespeichert)|
  |Kapazität       |Meist kleiner (z. B. 16 GB)	       |Viel größer (z. B. 1 TB)             |
  |Aufabe          |Kurzzeit-Speicher                  |Langzeit-Speicher                    |
  |Datenzugriff    |Byte                               |Sektoren (512B üblicherweise)        |

---
4. **Welche Arten von RAM gibt es?**

  * Es gibt verschiedene Typen von RAM, die sich in ihrer Geschwindigkeit, Bauweise und Funktion unterscheiden. Zwei Haupttypen sind:

**SRAM (Static RAM):**

Schnell, aber teuer. (Transistorschaltung)
Wird z. B. für Cache im Prozessor benutzt.
Speichert Daten ohne ständiges "Auffrischen".
Benötigt sehr wenig Strom

SRAM besteht aus reinen Logikgattern. (NAND/NOR Bausteine die miteinander verschalten sind)

**DRAM (Dynamic RAM):**

Günstig und in großen Mengen verfügbar.
Muss ständig "aufgefrischt" werden, damit Daten erhalten bleiben.
Wird als Arbeitsspeicher im PC genutzt.

DRAM besteht aus Kondensatoren welche eine Ladung für eine kurze Zeit halten (den Wert). Diese müssen jedoch andauernd aufgefrischt werden.

**Synchron und Asynchron:**

**Synchron:** Arbeitet synchron mit der Taktfrequenz des Prozessors (moderner Standard).
**Asynchron:** Arbeitet unabhängig vom Prozessor (veraltet).

Single Data Rate (SDR) vs. Double Data Rate (DDR):

**SDR (Single Data Rate):** Sendet Daten einmal pro Takt.
**DDR (Double Data Rate):** Sendet Daten zweimal pro Takt – schneller!
