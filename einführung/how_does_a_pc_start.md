# Wie ein PC hochstartet

Der Hochstart (Boot-Prozess) eines PCs läuft in mehreren Schritten ab. Hier ist eine einfache Erklärung, wie der Computer von einem ausgeschalteten Zustand in ein voll funktionierendes System gelangt.

---

## 1. Einschalten und Stromversorgung

- Wenn du den Einschaltknopf drückst, sendet das Netzteil (Power Supply Unit) elektrische Energie zu den Hauptkomponenten des Computers, insbesondere zum Mainboard und zur CPU.
- Das Netzteil testet sich selbst, ob es korrekt funktioniert, und verteilt dann die nötige Spannung an das Mainboard und andere Komponenten. 

## 2. BIOS/UEFI startet

- Das **BIOS** (Basic Input/Output System) oder das modernere **UEFI** (Unified Extensible Firmware Interface) sind Programme, die im Mainboard gespeichert sind. Sie werden beim Einschalten sofort aktiv.
- BIOS/UEFI prüfen zuerst, ob alle grundlegenden Komponenten da sind und funktionieren – dies ist der sogenannte **Power-On Self Test (POST)**.
- Bei diesem Selbsttest werden unter anderem die CPU, der Arbeitsspeicher (RAM) und die Grafikkarte auf ihre Funktionsfähigkeit überprüft. Falls ein Problem festgestellt wird, kann der Computer Beeps (Pieptöne) ausgeben oder eine Fehlermeldung anzeigen, um auf den Fehler hinzuweisen.

## 3. Gerätekonfiguration und Boot-Einstellungen

- Nachdem POST erfolgreich abgeschlossen wurde, prüft das BIOS/UEFI die angeschlossenen Speichergeräte (z. B. Festplatte oder SSD), um das richtige Startlaufwerk zu finden, wo das Betriebssystem installiert ist.
- Das BIOS/UEFI durchsucht die **Boot-Reihenfolge**. Diese Reihenfolge bestimmt, in welcher Reihenfolge verschiedene Laufwerke (wie SSD, USB-Stick, CD) überprüft werden, um das Betriebssystem zu finden.
- Sobald das BIOS/UEFI das richtige Laufwerk findet, beginnt es, den Bootloader darauf zu laden.

## 4. Laden des Bootloaders

- Der **Bootloader** ist ein kleines Programm, das auf dem Startlaufwerk gespeichert ist und dem Computer sagt, wie das Betriebssystem gestartet wird.
- Der am häufigsten verwendete Bootloader bei Windows-Systemen ist der **Windows Boot Manager**, bei Linux-Systemen ist es oft **GRUB** (GRand Unified Bootloader).
- Der Bootloader lädt den Kernel des Betriebssystems – das ist der Kern des Betriebssystems, der die Kommunikation zwischen Hardware und Software ermöglicht.

## 5. Laden des Betriebssystems (Kernel)

- Der **Kernel** des Betriebssystems wird in den Arbeitsspeicher (RAM) geladen und gestartet. Der Kernel verwaltet alle grundlegenden Aufgaben des Systems, z. B. Speicherverwaltung, Prozessorsteuerung und Gerätesteuerung.
- Der Kernel lädt die grundlegenden Systemtreiber, damit das Betriebssystem mit den Hauptkomponenten des Computers kommunizieren kann (z. B. Grafik, Netzwerk und Speicherlaufwerke).

## 6. Initialisierung von Systemdiensten und -prozessen

- Jetzt startet das Betriebssystem seine **Systemdienste** und -prozesse. Das sind Programme, die im Hintergrund laufen und für grundlegende Funktionen des Computers sorgen, wie Netzwerkverbindung, Benutzersicherheit und viele weitere.
- Dazu gehören z. B. Treiber für die Kommunikation mit angeschlossenen Geräten wie Maus, Tastatur und Drucker.

## 7. Anmeldung und Start der Benutzeroberfläche

- Sobald alle Systemdienste geladen sind, wird die **Benutzeroberfläche** des Betriebssystems geladen. Bei Windows ist dies der Desktop, bei macOS die Finder-Oberfläche und bei Linux eine der verschiedenen grafischen Oberflächen (z. B. GNOME, KDE).
- Jetzt erscheint der Anmeldebildschirm, auf dem du dich als Benutzer anmelden kannst.

## 8. System ist betriebsbereit

- Nachdem du dich angemeldet hast, startet der Computer alle Programme und Einstellungen, die für dein Benutzerprofil festgelegt sind (z. B. Hintergrund, Taskleiste, eventuell geplante Programme).
- Jetzt ist das System vollständig hochgefahren und bereit zur Nutzung.

---

## Zusammenfassung des Ablaufs

1. **Power-On** → Strom fließt zu den Komponenten.
2. **BIOS/UEFI** → Hardware wird geprüft und die Boot-Reihenfolge festgelegt.
3. **Bootloader** → Start des Betriebssystems wird vorbereitet.
4. **Kernel** → Grundfunktionen des Systems werden geladen.
5. **Systemdienste** → Wichtige Hintergrundprozesse starten.
6. **Benutzeranmeldung** → Start der Benutzeroberfläche.
7. **Nutzung** → Der PC ist betriebsbereit.

---

Dieser Ablauf dauert oft nur ein paar Sekunden bis wenige Minuten, je nach Computerleistung und -konfiguration.
