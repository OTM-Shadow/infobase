# Infobase

## Generelle Anleitungen**

- Benutzer in der Windows Computerverwaltung anlegen
In der Windows-Computerverwaltung kannst du neue Benutzerprofile erstellen, bestehende Benutzer verwalten und ihnen Rechte zuteilen. Das hilft dir, unterschiedliche Benutzerkonten für verschiedene Personen oder Zwecke zu organisieren.


**Wichtige Windows Tastenkürzel**

**Nützliche Tastenkombinationen für den schnelleren Umgang mit Windows:**

* Strg + C = Kopieren von Text oder Dateien.
* Strg + V = Einfügen von kopierten Inhalten.
* Alt + Tab = Zwischen offenen Fenstern wechseln.
* Windows + E = Explorer öffnen.
* Windows + R = Ausführen-Fenster öffnen.


**ISO-Abbild mit genisoimage auf Linux erstellen**

Ein ISO-Abbild ist eine komplette Kopie einer CD, DVD oder Festplatte in einer einzigen Datei. Auf Linux kannst du mit dem Befehl ``genisoimage -o abbild.iso/verzeichnis`` eine ISO-Datei erstellen. Dabei steht ``/verzeichnis`` für den Ordner, den du als ISO speichern möchtest.

**Wichtige Tools**

``dxdiag``
dxdiag ist ein Windows-Tool, das dir detaillierte Infos über deine Hardware zeigt, z. B. Grafikkarte, Soundkarte und Treiber. Nützlich, um Probleme zu diagnostizieren.

``ipconfig``
Mit ipconfig kannst du deine Netzwerkeinstellungen aufrufen, z. B. deine IP-Adresse und das Standard-Gateway (wichtige Daten für Netzwerkverbindungen).

``ping``
ping ist ein Befehl, mit dem du testen kannst, ob eine Verbindung zu einem bestimmten Server oder Gerät besteht. Einfach z. B. ping google.com eingeben, um zu prüfen, ob du eine Verbindung zum Internet hast.

``nslookup``
Ein Tool, um DNS-Informationen abzurufen, also herauszufinden, welche IP-Adresse zu einer bestimmten Website gehört und umgekehrt.

## Einführung in Computersysteme

**Was ist ein Computer?**

Ein Computer ist ein Gerät, das Informationen (Daten) verarbeiten, speichern und mit anderen Geräten teilen kann. Er führt Programme aus, die bestimmte Aufgaben automatisieren.

**EVA-Prinzip**

Das EVA-Prinzip steht für Eingabe, Verarbeitung und Ausgabe – so funktioniert ein Computer grundsätzlich. Daten werden eingegeben, verarbeitet und dann als Ergebnis ausgegeben.

**ALU (Arithmetic Logic Unit)**

Die ALU ist der Teil der CPU, der Berechnungen durchführt und logische Operationen wie Vergleiche anstellt.

**CPU (Central Processing Unit)**

Die CPU ist das "Gehirn" des Computers. Sie führt alle Berechnungen und Befehle aus, die ein Programm vorgibt.

**RAM (Random Access Memory)**

RAM ist der Arbeitsspeicher, in dem Daten kurzfristig gespeichert werden, während sie benötigt werden. Je mehr RAM ein Computer hat, desto mehr Programme kann er gleichzeitig ausführen.

**Architektur**

Der Aufbau des Computersystems, also wie die Komponenten wie CPU, Speicher und Ein-/Ausgabegeräte verbunden sind.

**Maschinenbefehl**

Ein einzelner, direkter Befehl, den die CPU ausführen kann (z. B. eine einfache Berechnung).

**Programm**

Eine Serie von Befehlen, die zusammen eine Aufgabe erfüllen, z. B. ein Textverarbeitungsprogramm.

## Zahlensysteme

**Binärsystem (Dualsystem)**

Das Binärsystem nutzt nur die Zahlen 0 und 1. Es ist das grundlegende Zahlensystem für Computer, da sie mit elektrischen Schaltungen arbeiten, die entweder ein- (1) oder ausgeschaltet (0) sind.

**Umrechnen zwischen Zahlensystemen**

Zahlen lassen sich von einem Zahlensystem ins andere umrechnen, z. B. von Binär (Basis 2) zu Dezimal (Basis 10).

Wert einer Zahl anderer Zahlensysteme erkennen
Jede Stelle in einer Zahl hat einen bestimmten Wert. Dieser basiert auf der Position und der Basis des Systems (z. B. 2er Basis im Binärsystem).

**Fachbegriffe in Zahlensystemen**

**Stellenwertsystem:** Ein System, bei dem die Stelle einer Ziffer ihren Wert bestimmt.
**Basis:** Die Anzahl der Ziffern, die in einem Zahlensystem genutzt wird, z. B. Basis 2 für das Binärsystem.
**Stellenzahl:** Die Anzahl der Ziffern in einer Zahl.
**Oktalsystem:** Ein Zahlensystem mit Basis 8, das die Ziffern 0 bis 7 verwendet.
**Hexadezimalsystem:** Ein Zahlensystem mit Basis 16, das die Ziffern 0 bis 9 und die Buchstaben A bis F verwendet.


## Mainboard

**Mainboard (Motherboard)**

Das Mainboard, oder Motherboard, ist die zentrale Platine im Computer, auf der alle wichtigen Komponenten wie CPU, RAM und Festplatten miteinander verbunden sind. Es ermöglicht, dass diese Komponenten miteinander kommunizieren. Es enthält auch die Anschlüsse für Peripheriegeräte (z. B. USB-Ports).

**Wichtige Anschlüsse am Mainboard:**

**USB:** Zum Anschließen von Geräten wie Tastatur, Maus oder externer Festplatte.
**RJ45/LAN-Port:** Netzwerkkabelanschluss für eine kabelgebundene Internetverbindung.
**SATA:** Anschluss für Festplatten und SSDs.
**PS/2:** Ein älterer Anschluss für Maus und Tastatur.
**COM:** Serieller Anschluss für ältere Geräte.
**LPT:** Paralleler Anschluss, z. B. für ältere Drucker.
**Audio-Anschlüsse:** Für Kopfhörer, Mikrofon und Lautsprecher.

**Stromanschlüsse**

Das Mainboard hat Anschlüsse für das Netzteil, das die gesamte Stromversorgung des Computers sicherstellt. Ohne Stromversorgung könnten CPU, Festplatte, Grafik und andere Komponenten nicht arbeiten.

**Formfaktor**

Der Formfaktor beschreibt die Größe und den Aufbau des Mainboards. Bekannte Formfaktoren sind ATX und ITX. Der Formfaktor bestimmt auch, welches Gehäuse und welches Netzteil du brauchst.

**CPU-Sockel**

Der CPU-Sockel ist der Steckplatz, in den die CPU eingesetzt wird.

**Wichtige Sockelarten:**

**PGA** (Pin Grid Array): Die CPU hat Pins, die in den Sockel auf dem Mainboard gesteckt werden.
**LGA** (Land Grid Array): Die Pins befinden sich im Sockel, und die CPU wird darauf gelegt.
**ZIF** (Zero Insertion Force): Ein Sockel, bei dem die CPU ohne großen Druck eingesetzt wird.


**BIOS und UEFI**

Das BIOS (Basic Input/Output System) oder UEFI (Unified Extensible Firmware Interface) ist die Software, die den Computer startet und grundlegende Hardwareeinstellungen verwaltet.

**PCIe (Peripheral Component Interconnect Express)**

Ein Steckplatz für Erweiterungskarten wie Grafikkarten, Netzwerkkarten oder Soundkarten. PCIe bietet hohe Übertragungsgeschwindigkeiten und kann Daten über "Lanes" (Datenkanäle) senden.

**Chipsatz**

Der Chipsatz steuert die Datenflüsse zwischen CPU, Speicher und anderen Komponenten. Er ist wichtig für die Gesamtleistung und bestimmt, welche Funktionen das Mainboard unterstützt.

## Boolesche Algebra & Schaltnetze

**Boolesche Algebra**

Eine Form der Mathematik, die mit den Werten "wahr" und "falsch" arbeitet. Sie ist die Grundlage für die digitale Logik, die Computer verwenden.

**Wahrheitstabellen**

Tabellen, die zeigen, welche Kombinationen von Eingaben zu welchem Ergebnis führen. Zum Beispiel, ob bei einer AND-Verknüpfung das Ergebnis "wahr" oder "falsch" ist.

**Logikgatter und Verknüpfungen**

Logikgatter sind die elektronischen Bausteine, die logische Operationen wie UND, ODER, NICHT, XOR umsetzen.

**Grundlegende Verknüpfungen:**

**UND (AND):** Nur "wahr", wenn beide Eingaben wahr sind.
**ODER (OR):** "Wahr", wenn mindestens eine Eingabe wahr ist.
**XOR (Exclusive OR):** "Wahr", wenn genau eine der Eingaben wahr ist.
**NICHT (NOT):** Kehrt das Ergebnis um – aus "wahr" wird "falsch" und umgekehrt.

## Normalformen
In der Booleschen Algebra gibt es Standardformen, die helfen, logische Ausdrücke zu vereinheitlichen:

**Disjunktive Normalform (DNF):** Eine OR-Verknüpfung von AND-Verknüpfungen.
**Konjunktive Normalform (KNF):** Eine AND-Verknüpfung von OR-Verknüpfungen.
