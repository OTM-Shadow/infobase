# Chipsatz - Mainboard

## Theoretische Fragen 4

1. **Was ist der Chipsatz und was ist seine Aufgabe?**
* Die Hauptaufgabe des Chipsatzes auf dem Mainboard ist die Verbindung und Kommunikation zwischen den einzelnen Komponenten und der CPU. Ältere CPUs konnten nicht direkt mit dem RAM oder dem PCIe kommunizieren und benötigten daher den Chipsatz, um diese Kommunikation zu ermöglichen. Neuere CPUs hingegen sind in der Lage, direkt mit dem RAM und dem PCIe zu kommunizieren. Dennoch ist auch bei neuen Mainboard-Modellen ein Chipsatz erforderlich, um langsamere Datenübertragungen und andere Kommunikationswege, wie beispielsweise externe Anschlüsse, zu steuern.
    * Dies liegt daran, dass die CPU sich nur um die wichtigen Aufgaben des Computersystems kümmern sollte. Langsame oder weniger wichtigere Aufgaben werden an den Chipsatz abgegeben.

* Moderne CPUs haben tatsächlich Funktionen übernommen, die früher dem Chipsatz vorbehalten waren, aber der Chipsatz ist nach wie vor für ergänzende, langsamere Verbindungen und Funktionen entscheidend.

* Beispiele für Geräte welche über den Chipsatz mit der CPU kommunizieren: (üblich, je nach Plattform unterschiedlich)
    * Externe I/O wie LAN Ports, USB Ports
    * SATA Ports
    * etc
  
2. **Inwiefern unterscheiden sich verschiedene chipsatz-platformen voreinander?**
3. **Erkläre, inwiefern funktionspläne eines Mainboards hilfreich sind!**
  
* Funktionspläne eines Mainboards sind äußerst hilfreich, da sie einen detaillierten Überblick über den Aufbau und die Funktionsweise der verschiedenen Komponenten und Verbindungen des Mainboards bieten.
* Techniker können mithilfe der Funktionspläne Fehler auf einem Mainboard leichter identifizieren und beheben. Der Plan zeigt die Position und Verknüpfung von Bauteilen wie Kondensatoren, Widerständen, Transistoren und Chips, was hilft, defekte Komponenten schnell zu lokalisieren und zu ersetzen.
* Funktionspläne verdeutlichen die Signalwege zwischen den Komponenten, z. B. von der CPU zum RAM oder zu anderen Controllern. Dies ist wichtig, um zu verstehen, wie die Daten im System fließen und wo es zu Engpässen oder Störungen kommen könnte.

4. **Was ist PCIe? Erstelle eine Tabelle der verschiedenen PCIe-Revisionen, den Jahren ihrer Verbreitung sowie ihrer Übertragungsgeschwindigkeit!**

PCIe (Peripheral Component Interconnect express) ist ein Bussystem welches Komponenten am Mainboard untereinander verbindet.

PCIe existiert inzwischen in verschiedenen Revisionen, welche jeweils die Zuverlässigkeit und Geschwindigkeit des Bussystems verbessern.

https://en.wikipedia.org/wiki/PCI_Express

https://nascompares.com/answer/what-is-pcie-speed-from-gen1-to-gen6/

![](https://hedgedoc.itlabs.at/uploads/1ae45398-a5a5-43bf-8dac-7a763fd68d29.png)
