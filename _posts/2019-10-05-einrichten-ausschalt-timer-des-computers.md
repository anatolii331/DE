---
id: 12772
title: einrichten Ausschalt-Timer des Computers
date: 2019-10-05T12:18:26+00:00
author: user
layout: post
guid: https://de.bestwow.net/einrichten-ausschalt-timer-des-computers/
permalink: /einrichten-ausschalt-timer-des-computers/
tdc_dirty_content:
  - "1"
  - "1"
tdc_icon_fonts:
  - 'a:0:{}'
  - 'a:0:{}'
tdc_google_fonts:
  - 'a:2:{i:0;s:3:"662";i:4;s:3:"394";}'
  - 'a:2:{i:0;s:3:"662";i:4;s:3:"394";}'
ap_mark:
  - Это пост был добавлен через AftParser
  - Это пост был добавлен через AftParser
ap_link:
  - https://lifehacker.ru/tajmer-vyklyucheniya-kompyutera/
  - https://lifehacker.ru/tajmer-vyklyucheniya-kompyutera/
post_views_count:
  - "11"
  - "11"
categories:
  - Strategies
---
## Wie Ausschalt-Timer konfigurieren Computer mit Windows

### 1. Über das Menü «Ausführen»

Ausschalt-Timer zu aktivieren, benötigen Sie das einzige Team — `shutdown -s -t xxx`. Statt drei иксов brauchen, geben Sie die Zeit in Sekunden, durch das ausschalten passiert. Zum Beispiel, wenn die Eingabe `shutdown -s -t 3600`, das System schaltet sich nach einer Stunde.

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-nastroit-taymer-vyklyucheniya-komp-yutera-1.jpg) 

Drücken Sie auf die Tasten Win + R (öffnet das Menü «Ausführen», geben Sie einen Befehl in das Eingabefeld und klicken Sie Enter oder OK.

Wenn Sie den abschaltvorgang Abbrechen wollen, drücken Sie erneut die Windows-Taste + R, geben Sie `shutdown -a` ein und klicken Sie dann auf OK.

### 2. Mit dem «Taskplaner»

So werden Sie nicht starten Sie den Timer im wörtlichen Sinne: der Computer schaltet sich nicht nach Ablauf einer Frist, und genau in der angegebenen Zeit.

Zuerst öffnen Sie das Menü «Aufgabenplanung». Dazu drücken Sie Win + R, geben Sie im Feld Befehl `taskschd.msc` und drücken Sie die EINGABETASTE.

Jetzt planen Sie das Herunterfahren. Klicken Sie im rechten Bereich auf «einfache Aufgabe Erstellen», und geben Sie dann im Fenster des Assistenten Einstellungen: jeder name, Modus, Wiederholung, Datum und Laufzeit. Als Action-Aufgaben wählen Sie «Programm Starten». Im Feld «Programm / Skript» geben Sie `"shutdown"`, und im nächsten Zeile geben Sie das argument `-s`. Danach klicken Sie auf «Fertig stellen».

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-nastroit-taymer-vyklyucheniya-komp-yutera-2.jpg) 

Wenn Sie den abschaltvorgang Abbrechen wollen, erneut öffnen Sie die «Aufgabenplanung». Klicken Sie dann im linken Bereich auf «Aufgabenplanungsbibliothek», markieren Sie in der angezeigten Liste den erstellten Task und klicken Sie im rechten Bereich auf «Deaktivieren».

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-nastroit-taymer-vyklyucheniya-komp-yutera-3.jpg) 

### 3. Mit Hilfe der aussenstehenden Software

Wenn Sie nicht möchten, merken Sie sich die Befehle und Graben in den Einstellungen von Windows, verwenden Sie ein Drittanbieter-Programm. Z. B. Tool-PC-Sleep in der Lage, Ihren Computer Herunterfahren Timer oder genau in der angegebenen Zeit. Es ist kostenlos und sehr einfach.

Ausschalt-Timer zu aktivieren PC in Sleep, starten Sie das Programm und wählen Sie Herunterfahren aus dem Menü Select Function. Dann markieren Sie den Punkt Shutdown in und geben Sie an, nach welcher Zeit das System muss ausgeschaltet werden. Danach klicken Sie Start, um den Countdown starten.

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-nastroit-taymer-vyklyucheniya-komp-yutera-4.jpg) 

Um den abschaltvorgang Abbrechen, dafür müssen Sie das Fenster des Programms und klicken Sie auf die Schaltfläche Stop.

PC Sleep Sie können auch konfigurieren, um den Computer in genau der angegebenen Zeit. Dazu statt Shutdown in wählen Sie Shutdown at. Darüber hinaus können Sie planen nicht nur ausschalten, sondern auch andere Aktionen: Neustart, Winterschlaf, Ruhezustand und Abmelden. Diese Option ist auch verfügbar in der Liste Function Select.

PC Sleep →

Wenn Sie möchten, dass der Computer schlief nach dem Ende der Filme, können über das Programm auch die Ehrung der Sleep#.

## Wie Ausschalt-Timer konfigurieren Sie den Computer mit macOS

### 1. Mit «Terminal»

Der Befehl `sudo shutdown -h +xx` schaltet den Mac nach einer vorgegebenen Zeit. Statt иксов die Anzahl der Minuten verabreicht. Zum Beispiel, wenn die Einwahl `sudo shutdown -h +60`, Ausschalt-Timer funktioniert über eine Stunde.

Zur Eingabe der Befehle öffnen Sie die Anwendung «Terminal», geben Sie manuell ein oder kopieren Sie die oben genannten Zeichen und drücken Sie die EINGABETASTE. Wenn Sie aufgefordert werden, geben Sie das Administratorkennwort ein. Danach startet der Countdown bis zum ausschalten. Um abzubrechen, klicken Sie auf «Terminal», geben Sie `sudo killall "shutdown"` und drücken Sie die EINGABETASTE.

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-nastroit-taymer-vyklyucheniya-komp-yutera-5.jpg) 

### 2. Über das Menü «Energie Sparen»

In diesem Abschnitt können Sie planen das Herunterfahren des Computers zu einem angegebenen Zeitpunkt. Senken Sie das Apple-Menü und klicken Sie auf «Systemeinstellungen» → «Energiesparen» → «Zeitplan». Im geöffneten Fenster markieren Sie den Punkt «Ausschalten», geben Sie den Wochentag und die Uhrzeit.

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-nastroit-taymer-vyklyucheniya-komp-yutera-6.jpg) 

Wenn Sie fällig sind, auf dem Bildschirm erscheint die Warnung ausschalten. Wenn nicht verwenden Sie die Schaltfläche Abbrechen, wird das System schaltet sich nach 10 Minuten.

## Lesen Sie auch

  * Wie kann ich herausfinden, welches Motherboard auf Ihrem Computer installiert ist →
  * Wie blockieren Sie eine Website auf einem Computer mit Windows oder macOS →
  * Was tun, wenn der Computer lässt sich nicht einschalten →