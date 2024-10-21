# Theoretische Aufgabe 1

### 1. Erkläre die Aufgabe des Mainboards!

Das Mainboard, auch als Hauptplatine oder **Motherboard** bezeichnet, ist die zentrale Platine eines Computers, die alle wichtigen Komponenten miteinander verbindet. 

Es ist verantwortlich für die Kommunikation zwischen der CPU, dem Arbeitsspeicher, den Erweiterungskarten, dem Speicher und anderen Peripheriegeräten. Zu den Hauptaufgaben gehören:

- **Stromverteilung**: Bereitstellung von Strom für andere Komponenten.
- **Datenübertragung**: Ermöglichen der Kommunikation zwischen der CPU, dem RAM und anderen Geräten.
- **Erweiterungsmöglichkeiten**: Bereitstellung von Steckplätzen für Erweiterungskarten und andere Hardware.
- **Anschlussmöglichkeiten**: Bereitstellung von Ports für externe Geräte, wie USB, HDMI, Ethernet usw.
- **BIOS/UEFI-Firmware**: Bereitstellung eines grundlegenden Systems, um den Computer zu starten.[^uefi]


[^uefi]: Die UEFI Firmware ist Software welche auf einem EEPROM Speicherchip am Mainboard hinterlegt ist und geladen wird wenn der Computer gestartet wird

---------------------------
### 2. Was ist der Formfaktor des Mainboards? Erstelle eine Tabelle mit verschiedenen Standards, ihren Maßen und typischen Einsatzgebieten!

Der Formfaktor des Mainboards bestimmt wie und wo das Mainboard in einem Gehäuse befestigt wird. Außerdem gibt er die Größe des Mainboards sowie die Maße und Position des hinteren I/O Shields (die externen Anschlüsse hinten am Gehäuse).

Außerdem wird spezifiziert, wo sich die Slots für Erweiterungskarten befinden müssen.

Der ATX Standard z.B. ist ein sehr umfangreicher Standard für Motherboards: https://web.archive.org/web/20120725150314/http://www.formfactors.org/developer/specs/atx2_2.pdf (Seite 8 enthält einen Überblick)

Der Formfaktor beschreibt die physikalischen Maße und die Layout-Spezifikationen eines Mainboards. Hier ist eine Tabelle mit verschiedenen Standards:

| Formfaktor     | Abmessungen                     | Typische Einsatzgebiete            |
|----------------|---------------------------------|------------------------------------|
| ATX            | 305 mm x 244 mm                 | Desktop-PCs, Gaming-Systeme        |
| Micro-ATX      | 244 mm x 244 mm                 | Kompakte Desktop-PCs               |
| Mini-ITX       | 170 mm x 170 mm                 | HTPCs (Home Theater PCs), sehr kompakte Systeme |
| E-ATX          | 305 mm x 330 mm                 | High-End Gaming-PCs, Workstations  |
| XL-ATX         | 345 mm x 262 mm                 | Extreme Gaming-Systeme             |

Es gibt außerdem noch eine Vielzahl an weiteren Standards.

https://en.wikipedia.org/wiki/Motherboard_form_factor#Tabular_information
  
-------------------------
### 3. Nenne die wichtigsten Komponenten auf dem Mainboard! Gib zu jeder Komponente Bilder an!

- CPU-Sockel, umgeben von VRMs (Voltage Regulator Modules)
- RAM-Slots
- Chipsatz
- Interne Anschlüsse & Header (z.B. SATA, m.2, interne USB Header)
- Slots für Bussysteme wie PCI/PCIe
- Stromanschlüsse (namentlich 24p ATX + 4/8p CPU Power)
- BIOS Batterie
- BIOS/UEFI EEPROM
- etwaige notwendige Prozessoren für weitere Funktionalität des Mainboards (z.B. eigener Soundprozessor, etc.)
  
--------------------
### 4. Nenne die wichtigsten Bussysteme für Mainboards! Erstelle eine kurze Liste wichtigster Erweiterungsbussysteme und in etwa dem Zeitbereich ihrer Verbreitung!
Heutzutage finden wir 2 Bussysteme für Erweiterungskarten:
* PCIe (Peripheral Component Interconnect express) (aktuell, ca seit 2007 groß im Umlauf)
* PCI (Peripheral Component Interconnect) (Mitte 90er bis Anfang 2000er), veraltet

Die meisten Mainboards unterstützen außerdem einen SPI Bus welcher für die Kommunikation mit internen Systemrelevanten Komponenten verwendet wird (z.B. TPM Module)

Veraltete Bussysteme:
* PCI-x (extended PCI für Server)
* AGP (Accelerated Graphics Port) - Verbreitung: 1997 bis 2000er Jahre
* ISA/EISA (Extended Industry Standard Architecture)
* VESA Local Bus
* etwaige Riser-Bussysteme für spezielle Karten
* uvm.

https://en.wikipedia.org/wiki/Bus_(computing)#Examples_of_internal/external_computer_buses

---------------------
### 5. Nenne die wichtigsten externen Anschlüsse des Mainboards und ihre Aufgabe! Gib zu jedem Anschluss Bilder an!
| Anschluss Typ       | Bild                                   | Beschreibung |
| ------------------- | -------------------------------------- | ------------ |
| USB-A               | ![image](https://github.com/user-attachments/assets/9cd06443-84d9-4ef2-971a-220d1ce549e3) | Standard USB-Anschluss. Zu finden an allen möglichen Geräten. Die Farbe kann etwas über den Standard z.B. 3.0 sagen. |
| USB-B               | ![image](https://github.com/user-attachments/assets/026e0a1c-ad00-4685-b9f8-d8c69c58b44d) | Häufig an Drucker und großen Externen-Festplatten zu finden. |
| USB-C               | ![image](https://github.com/user-attachments/assets/7d1193ab-eedd-4f09-829c-813fd110a712) | Neuer Universal USB Standard. Die Form sagt leider nichts über den Funktionen aus. Über diesen Anschluss kann ein Gerät mit Strom versorgt werden oder auch ein Monitor angeschlossen werden. |
| mini USB            | ![image](https://github.com/user-attachments/assets/c6a73c2e-79f5-46fd-90a4-0270e5a560b3) | USB-Anschluss welcher an älteren externen Festplatten oder Smartphones zu finden ist. Wurde durch Micro-USB ersetzt. |
| micro USB           | ![image](https://github.com/user-attachments/assets/a888b0b3-b66c-441e-9762-1b66d5188b1e) ![image](https://github.com/user-attachments/assets/9fae33bc-0857-4071-9e31-0984065ad104) | USB-Anschluss für kompakte Geräte. Oft an USB-Festplatten oder Smartphones zu finden. Wird teilweise nur zum Aufladen von Geräten genutzt. Der Stecker nebendran, ist für einen schneller Datenübertragung über USB 3.0 gedacht und ist abwärtskompatibel. Diese Geräte funktionieren auch mit dem einfachen Kabel. Sehr verbreitet bei USB-Festplatten. |
| VGA                 | ![image](https://github.com/user-attachments/assets/b4263d19-8185-406e-bb97-7775bdf0e0ab) | Analoger Anschluss zum verbinden eines Monitors oder Beamers. |
| DVI                 | ![image](https://github.com/user-attachments/assets/be5c592f-081c-4b76-9932-35e3e1acb4b4) | Digitaler Anschluss zum Verbinden eines Monitors. |
| HDMI                | ![image](https://github.com/user-attachments/assets/bd871283-a6fc-47ca-a851-c2d7439b9ab2) | Digitaler Anschluss zum Verbinden eines Monitors, Beamers oder TV. Standard für TV-Geräte. Über diesen Anschluss kann unter anderem auch Ton übertragen werden. |
| Display Port (DP)   | ![image](https://github.com/user-attachments/assets/40169d82-1332-45b5-b3cb-3a8d74119480) | Digitaler Anschluss zum Verbinden eines Monitors. Standard für Monitore. Über diesen Anschluss kann unter anderem auch Ton übertragen werden. |
| mini Display Port   | ![image](https://github.com/user-attachments/assets/0f9eb683-fd09-4bb5-a8ce-742a9f656a18) | Digitaler Anschluss zum Verbinden eines Monitors. Oft an Dockingstation zu finden. Über diesen Anschluss kann unter anderem auch Ton übertragen werden. |
| Ethernet RJ-45      | ![image](https://github.com/user-attachments/assets/8a7df004-7349-4699-9cf8-fae8c3aa9bfd) | Standardanschluss für ein Netzwerkkabel. Die Form sagt nichts über die Geschwindigkeit aus. |
| PS/2                | ![image](https://github.com/user-attachments/assets/0cc0890d-f23f-4c3b-88f8-b865fbd710f8) ![image](https://github.com/user-attachments/assets/8b3ac78d-4368-4d9d-b4ca-ffab98d9e7b4) | Ein alter Anschluss für Maus und Tastatur. Grün für die Maus und Lila für die Tastatur. Nach dem Anschließen sind die Geräte erst nach einem Neustart nutzbar. |

#### Quelle: https://josuweit-it.de/uebersicht-pc-anschluesse/

Andere evtl. veraltete Schnittstellen:
* 3.5mm Klinkenanschluss (AUX) (TRS, TRRS, bei Notebooks auch TRRRS)
* Firewire IEEE1394
* COM / Console Port (D-Sub 9 Stecker, m. oder w.)
* LPT / Line Printer (D-Sub 25 Stecker)
* Joystick Port (D-Sub 15, 2 Reihen)

-----------------------
### 6. Nenne die wichtigsten internen Anschlüsse des Mainboards und ihre Aufgabe! Gib zu jedem Anschluss Bilder an!
* RAM Slots
* PCI/e Slots
* CPU Sockel
* USB3 Header für USB3 am Frontpanel
* SATA Anschlüsse
* m.2 Slots
* ATX 24p Power Connector
* 4+4p CPU Power
* Fan Header (Für Lüfter)
* Frontpanel-Connector für Einschaltknopf, Reset und LEDs
* Interner Audio Anschluss
* Etwaige Interfaces wie USB, etc. welche nach außen ausgeführt werden

Jeweilige interne Anschlüsse vom jeweiligen Board findet man in der Bedienungsanleitung.

-----------------------
### 7. Was ist eine Riser-Karte?

Eine Riser-Karte ist eine Erweiterungskarte, die es ermöglicht, andere Karten parallel zum Mainboard zu installieren, um Platz zu sparen oder spezielle Gehäusekonfigurationen zu ermöglichen.
