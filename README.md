
Komplettpaket WordPress für Freifunk-Communities mit FFAC Template

Alle PlugIns und das Basis-Modul sind auf dem Softwarestand 02.12.2016


Hinweise
--------

Die für Freifunk gemachten Änderungen stehen unter einer CC-BY-3.0 Lizenz by Felix Bosseler und Freifunk Aachen.

Das Theme ist für Communities die sich in Sachen Freifunk ehrenamtlich engagieren. Kommerziellen Anbietern wird die Nutzung ausdrücklich untersagt.

Alle Lizenzhinweise / Credits z. B. im Impressum bzw. an den Bildern und sonstigen Inhalten bitte beibehalten.

Das Theme ist abgeleitet von "TwentyFourteen". Also Vorsicht, wenn das original Theme aktualisiert werden soll...

Die Aachen Skyline und das Freifunk Aachen Logo sollte ersetzt werden.

Die Disclaimer / Datenschutzerklärung sollte auf Aktualität geprüft werden (Impressum).

Alle Kontakt-Infos sollten geändert werden :)

Es handelt sich um eine Sicherung mit dem PlugIn "Duplicator", welches auch Bestandteil des Systems ist.


Keine Gewähr, kein Support (Fragen im Forum werden trotzdem gerne beantwortet).

Installation:
Die Zieldatenbank muss leer sein oder man muss dem Installer erlauben diese zu leeren. Doof ist aber so!

Backend-Zugang:
http://DeineDomain.borg/wp-admin
Name: admin
Passwort: admin

1.)
Einfach das Backupfile 20161202_freifunkfunk_basic_setup_584163f4bc89e6402161202120716_archive.zip und die installer.php auf dem Webspace ins htdoc-Root (oder einem Unterverzeichnis) einspielen.

2.)
Installer aufrufen
http://www.freifunk-DummyTown.de/installer.php starten. Der Rest geht via dem Wizard Dialog. mySql muss installiert sein. DB wird vom Installer angelegt. Ihr braucht Name und Passwort für den mySQL User. Der Wizard kann bei entsprechender Berechtigung auch eine neue DB anlegen.

3.)
Admin-User Passwort ÄNDERN!

aktuell
User: admin
Passwort: admin

3.)
Seite "Impressum" korrekt ausfüllen und die rechtlichen Angaben prüfen und ggf. aktualisieren. Hinweise auf Freifunk Aachen bitte drin lassen

4.)
Unter Einstellungen/Allgemein die E-Mail Kontaktadresse und Claims anpassen

5.)
Seite "Kontakt" anpassen (unten sind div. Social Media Links / Mailadressen)

6.)
Unter "Design/Widgets" den Bereich "Inhalt-Seitenleiste" runterklappen und das Kontakt Widget anpassen

7.)
Das Hauptmenü ggf. anpassen ("Design/Menüs")

8.)
Alles Seiten mal durchlesen und ggf. an eigene Präferenzen anpassen (z. B. hinsichtlich Treffen o. ä.)

9.)
Unter "Formulare/Kontaktforumlar1" auf der Karte "E-Mail" die eigene E-Mail Adresse hinterlegen und Nachrichten anpassen

11.) Das Headerbild austauschen
Benötige Größe 1260 x 240 Pixel. Menüpunkt in WP: "Design/Header"

11.)
Eine Datensicherung mit dem Duplicator PlugIn anlegen :)

12.)
Die Installer Files auf dem Webspace im htdocs-root wieder löschen siehe Punkt 1 (inkl. Logfiles etc.):

installer.php
installer-backup.php
installer.log
installer-data.sql
20161202_freifunkfunk_basic_setup_584163f4bc89e6402161202120716_archive.zip




Sonstige Hinweise
Beiträge erscheinen nur auf der Startseite, wenn diese in der Post-Kategorie "News" enthalten sind. Wollten wir so :)

Falls die Präsenz
in einem Unterverzeichnis betrieben wird (http://freifunk-hempelhusen/wp/index.html), dann müssen die Links im Footer angepasst werde. Bei Installation im Doc-Root (http://freifunk-hempelhusen/index.html) ist das _nicht_ erforderlich

.\wp-content\themes\freifunkaachen\footer.php



Empfehlenswerte PlugIns
die wir auch benutzen, aber hier nicht rein getan haben, um die Komplexität gering zu halten:

Auto-Optimze (Free Edition))
WP Fastest Cache (Free Edition)

Was fehlt
Die Map ist nicht drin, das wäre zu komplex. Die benötigt ein, zwei Leute die sich da drum kümmern und wissen was Sie tun ;-)

Ansonsten viel Spaß damit!

Felix (Fx))

Felix.Bosseler@Freifunk-Aachen.de
https://twitter.com/textheld


