## Praktische Aufgabe 2 - BIOS/UEFI

1.	**Wo ändert man die Uhrzeit im BIOS/UEFI?**

* BIOS-Öffnen (F2 Asus Model)
* Advanced Settings (F7 Asus Model)
* Main
* Adjust system date & system time 

2.	**Welche Spannungen sind für den Computer wichtig und wo sieht man diese?**

* Advanced Settings
* Monitor
* Da stehen die einzahlen Spannungen am Main
  * CPU Voltage
  * 3.3V Voltage - Wichtig
  * 5V Voltage - Wichtig
  * 12V Voltage - Wichtig
* Diese Spannungen werden vom Powersuply ans mainboard verteilt und wenn diese nicht die richtige Voltage entsprechen dann bekommt der mainboard nicht genug Strom und "könnte" daher nicht starten oder funktioniert nicht einwandfrei.

3.	**Wo kann man einstellen, dass das System nach einem Stromausfall automatisch wieder hochfährt und wieso sollte man das wollen?**

* Advanced Settings
* Boot
* Bei Boot Configuration in "Next Boot after AC Power loss" gehen
* Normal boot: Muss nach einem Stromausfall mit dem PWR_SW manuell eingeschaltet werden
* Fast Boot: Startet nach einem Strom Ausfall von alleine

*Es ist praktisch bei Servern z.B. wenn auf einem Server eine Website läuft und Strom ausfällt, dass nicht die Einschalttaste betetigt werden muss (nach einem Stromausfall) um die Website wieder laufen zu lassen*
 
4.	**Was ist die Bootreihenfolge und wo ändert man diese?**

* Advanced Settings
* Boot
* Boot Option Priorties
* Dort kann man die Boot Reihenfolge ändern 

5.	**Wo kann man die grundlegenden Informationen über verbaute Hardware im BIOS/UEFI finden?**

* Advanced Settings
* Main
* Dort werden die grundlegenden Hardware Informationen angezeigt
  * CPU information
  * Memory information

6.	**Wo kann man die Frontpanel-USB-Anschlüsse deaktivieren?**

* Advanced Settings
* Advanced
* USB Configuration
* Ganz unten in USB Single Port control
* Beliebige USBs ein/ausschalten
  * Achten auf Mainboard bezeichnungen! Jede USB hat eine Beschriftung am Mainboard und diese könnte man aus/einschalten

7.	**Wo kann man den Num-Lock standardmäßig anschalten?**

* Advanced settings
* Boot
* Bootup num-lock state
* On/off

8.	**Wo kann man die Onboard-Netzwerkkarte deaktivieren?**

* Advanced Settings
* Advanced
* Onboard Devices Configuration
* Realtek LAN Controller ein/ausschalten
  * Default: Ausgeschaltet!

9.	**Wo kann man die Lüfter des Systems regeln und welche Vorteile bringt das?**

* Advanced Settings
* Monitor
* CPU Fan Speed low limit
  * Das stellt man ein wenn der Kühlkörper am CPU nicht ausreichend kühlen kann, um den Prozess zu beschleunigen


10.	**Wo kann man ein BIOS-Passwort setzen? Welche Vorteile bringt das setzen eines BIOS-Passworts?**

* Advanced Settings
* Main
* Security
* Administrator Password für BIOS/UEFI Setup
* User Password für das Einschalten; Er fragt für den Passwort bevor er bootet

12.	**Was ist Wake-on-LAN und wo schaltet man dieses ein oder aus?**
13.	**Was ist SecureBoot und wofür sollte man dies aktivieren bzw. deaktivieren?**
14.	**Was ist CSM Support und wofür sollte man dies aktivieren bzw. deaktivieren?**
15.	**Was ist Fast Boot und wofür sollte man dies aktivieren bzw. deaktivieren?**
16.	**Was ist SMT bzw. Hyperthreading und wieso sollte man es aktivieren bzw. deaktivieren?**
17.	**Was bringt ein BIOS/UEFI-Update und was ist dabei zu beachten?**
18.	**Wie führt man ein BIOS-Update durch?**

