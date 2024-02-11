- 👋 Hi, I’m @karefor
- 👀 I’m interested in publishing simple Tasmota Script examples.
-  🌱 I’m currently learning Tasmota Script
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

Einfacher Dimmer über Tasmota Script mit Kommentaren.
Steuert GPIO2 und man kann es an der blauen Reset-LED beobachten. 
Vorher muss in den Templates und der Modulkonfiguration GPIO2 pwm_i eingestellt werden. 

Zweiter Schritt: Auslesen des analog-Eingangs über das Script zur Steuerung der LED. ESP01 hat keinen Analog Eingang. Habe einen Node MCU 12E verwendet. Manche vertragen am A0 nur 1V. Wenn er mit 1V aber nur einen Wert um 300 am Ausgang liefert verträgt er 3,3V (War bei meinem so) Als Maximalwert werden 1024 ausgegeben. 
Anleitungen für Tasmota flashen und Einstellungen des Moduls gibts viele im Internet. 

<!---
karefor/karefor is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
