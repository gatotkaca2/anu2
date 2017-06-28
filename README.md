# anu2
1. Login als root

2. wget https://raw.githubusercontent.com/gatotkaca2/anu2/master/xt_1.0.60-inst.sh

3. chmod 755 xt_1.0.60-inst.sh

4. ./xt_1.0.60-inst.sh

5. Fragen zu Aktualiserungen alle mit J oder Y bestätigen.

6. 
[*] Please wait while Script is selecting the best mirror for you...
[*] Enter Your ipTV Panel PRO licence: z.B 3d5b0f8e468c332 (oder was ihr wollt)

(Wichtig: Lizenz merken und speichern in einer .txt Datei wird gebraucht falls mal reinstall & Backup restore)

7.
[+] Checking System...
[+] Debian based OS Found...
[+] Installing LSB-RELEASE...
[+] Installing Sources (trusty)... (das kann etwas dauern also warten..)

8.
[+] Installing MySQL...
[+] Please write your desired MySQL Root Password(Minimum: 5 chars): root Password oder anderes

(Wichtig: MySQL Passwort merken und zusammen mit Lizenz in einer .txt Datei 
speichern wird gebraucht falls mal reinstall & Backup restore)

9.
[+] Password Accepted. Please Wait...
[*] Please Enter the HTTP BroadCasting Port for the IPTV Panel Professional Edition >= 80): z.B 24621

10.
[+] Please write your desired Admin Password(Minimum: 5 chars): Password Deiner Wahl
[+] Installing MySQL Tables..

11. Konfiguriere iptables-persistent

Aktuelle Iptables-Regeln kÃ¶nnen in der Konfigurationsdatei /etc/iptables/rules.v4 gespeichert werden. Diese Regeln werden dann beim â
â Systemstart automatisch geladen. â
â â
â Regeln werden nur automatisch wÃ¤hrend der Paketinstallation gespeichert. Lesen Sie die Handbuchseite von iptables-save(8), um zu erfahren, â
â wie die Regeln aktuell gehalten werden kÃ¶nnen. â
â â
â Aktuelle IPv4-Regeln speichern? = YES 

Aktuelle Iptables-Regeln kÃ¶nnen in der Konfigurationsdatei /etc/iptables/rules.v6 gespeichert werden. Diese Regeln werden dann beim â
â Systemstart automatisch geladen. â
â â
â Regeln werden nur automatisch wÃ¤hrend der Paketinstallation gespeichert. Lesen Sie die Handbuchseite von ip6tables-save(8), um zu â
â erfahren, wie die Regeln aktuell gehalten werden kÃ¶nnen. â
â â
â Aktuelle IPv6-Regeln speichern? = YES

12.
######################################################################

Xtream Codes 1.0.60 edited by maxdata755...have fun

Installation abgeschlossen...

Der Server muss nun neu gestartet werden !!! Bevor 1x einloggen in das Panel !!!

Reboot (y/n)? = y —> enter und alles ist erledigt :)

cu

maxdata755
