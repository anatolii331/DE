---
id: 12851
title: Wie deaktivieren von «Windows Defender»
date: 2019-10-05T12:24:04+00:00
author: user
layout: post
guid: https://de.bestwow.net/wie-deaktivieren-von-windows-defender/
permalink: /wie-deaktivieren-von-windows-defender/
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
  - https://lifehacker.ru/kak-otklyuchit-zashhitnik-windows/
  - https://lifehacker.ru/kak-otklyuchit-zashhitnik-windows/
post_views_count:
  - "6"
  - "6"
categories:
  - Instagram
---
Microsoft Hintergedanken integrierte Virenschutz «Windows Defender» in Ihr Betriebssystem: dieses Tool schützt das System vor Malware seit seiner ersten Einführung. Also «Verteidiger» — eine nützliche Funktion, die notwendige Mehrheit der Benutzer.

Wenn Sie lieber ein Drittanbieter-Anti-Virus, dann «Verteidiger» kann mit ihm streiten. In der Regel integrierte Antivirus deaktiviert, nach der Installation des neuen, aber manchmal dies nicht geschieht und Schutzmaßnahmen beginnen, sich gegenseitig stören: die Bremssysteme oder sehen einander unerwünschte Software.

In solchen Fällen können Sie deaktivieren Sie «Windows Defender» und völlig Vertrauen auf Drittanbieter-Anti-Virus.

## So deaktivieren Sie «Defender» in Windows 10 und 8

1. Starten Sie den Windows-Registrierungs-Editor. Drücken Sie dazu die Tasten Win + R, geben Sie im Fenster «Ausführen» den Befehl _regedit ein,_ und drücken Sie die EINGABETASTE.

2. Auf der linken Seite im Fenster der Registrierung navigieren Sie zum Verzeichnis HKEY\_LOCAL\_MACHINE → SOFTWARE → Policies → Microsoft → Windows Defender.

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-otklyuchit-zaschitnik-windows-1.jpg) 

3. Im rechten Fensterteil doppelklicken Sie den Eintrag DisableAntiSpyware, ändern Sie den Wert auf 1 und klicken Sie auf OK.

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-otklyuchit-zaschitnik-windows-2.jpg) 

Wenn Parameter mit der Bezeichnung DisableAntiSpyware bei Ihnen nicht angezeigt wird, erstellen Sie es selbst: klicken Sie mit der rechten Maustaste auf einen leeren Bereich des Fensters, wählen Sie «Neu» → «DWORD-Wert (32-bit)» und benennen Sie es entsprechend.

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-otklyuchit-zaschitnik-windows-3.jpg) 

Dann klicken Sie ihn per Doppelklick, ändern Sie den Wert auf 1 und klicken Sie auf OK.

4. Starten Sie den Computer neu. Nach diesem «Verteidiger» trennen muss.

Um ihn zu aktivieren, öffnen Sie erneut den Registrierungseditor und ändern Sie den Wert DisableAntiSpyware auf 0.

## So deaktivieren Sie «Defender» in Windows 8, 7, Vista und XP

1. Starten Sie den Windows-Dienste-Manager. Dazu verwenden Sie die Tastenkombination Win + R, geben Sie im Fenster «Ausführen» _services.msc_ und drücken Sie die EINGABETASTE.

2. In der angezeigten Liste suchen Sie den Dienst «Windows Defender» (Windows Defender) oder mit einem ähnlichen Namen und klicken Sie darauf doppelt.

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-otklyuchit-zaschitnik-windows-4.jpg) 

3. Wenn ein neues Fenster wird geöffnet, im Feld «Starttyp» wählen Sie «Deaktiviert» und klicken Sie dann auf OK.

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-otklyuchit-zaschitnik-windows-5.jpg) 

4. Starten Sie den Computer neu, damit die änderungen wirksam werden.

Um Sie zu aktivieren, navigieren Sie erneut in den Manager-Diensten «Windows Defender» und ändern Sie den Starttyp auf «Automatisch».

## Wie schnell deaktivieren «Verteidiger» in jeder Windows-Version

Wenn Sie aus irgendeinem Grund nicht in der Lage, deaktivieren Sie die «Verteidiger» von den standardmäßigen Mitteln, versuchen Sie das Kostenlose Programm Win-Updates Disabler. Es ist kompatibel mit allen Versionen von Windows und ermöglicht den Schutz zu deaktivieren in zwei Klicks.

Indem Sie dieses Tool, markieren Sie dort den Punkt «Windows Defender Deaktivieren» und klicken Sie auf «jetzt Anwenden». Danach starten Sie den Computer neu, um die änderungen zu übernehmen.

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-otklyuchit-zaschitnik-windows-6.jpg) 

Um Sie zu aktivieren, starten Sie Win-Updates Disabler, klicken Sie auf die Registerkarte «Einfügen», markieren Sie «Windows Defender Aktivieren» und klicken Sie auf «jetzt Anwenden».

Win Updates Disabler →

## Lesen Sie auch

  * Was passiert, wenn ein Computer verlangsamt mit Windows →
  * 12 Kostenlose Software für Windows, die sollte jeder →
  * Wie man Programme in Windows ohne eine Spur →