---
id: 12835
title: Wie können lokale Laufwerke oder deren Größe ändern
date: 2019-10-05T12:23:18+00:00
author: user
layout: post
guid: https://de.bestwow.net/wie-k-nnen-lokale-laufwerke-oder-deren-gr-e-ndern/
permalink: /wie-k-nnen-lokale-laufwerke-oder-deren-gr-e-ndern/
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
  - https://lifehacker.ru/kak-obedinit-diski-windows-macos/
  - https://lifehacker.ru/kak-obedinit-diski-windows-macos/
post_views_count:
  - "11"
  - "11"
categories:
  - Uncategorized
---
Alle Anleitungen eignen sich sowohl für herkömmliche Festplatten (HDD) und solid State Drives (SSD).

Wir werden erinnern: die physische Festplatte im System sichtbar, in Form von virtuellen Volumes, auch als lokale Laufwerke oder Partitionen.

## Wie ändere ich die Partitionen in Windows

### Mit systemeigenen Mitteln

In Laufwerke können unter Windows ohne Programme von Drittanbietern, aber diese Methode hat einen wichtigen Nachteil. Sie verlieren alle Daten eines zusammenzuführenden Partitionen. Also wichtige Dateien vorab verschieben mit ihm in eine andere Partition oder auf ein Medium.

Der Prozess der Zusammenführung der lokalen Festplatte besteht aus zwei Phasen. Zuerst Sie vollständig löschen einer von Ihnen zusammen mit allen Inhalten, dann gibst den frei gewordenen Raum so zweiten Platte.

Benötigen Sie ein Standard-Dienstprogramm «Datenträgerverwaltung». Um es zu starten, verwenden Sie die Tastenkombination Windows + R, geben Sie im erscheinenden Fenster den Befehl _diskmgmt.msc_ und klicken Sie dann auf OK. Im unteren Teil des Fensters «Datenträgerverwaltung» zeigt die Partitionen der Festplatte.

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-ob-edinit-lokal-nye-diski-ili-izmenit-ih-razmery-1.jpg) 

Indem Sie das Dienstprogramm, klicken Sie mit der rechten Maustaste auf das Laufwerk, das Sie löschen wollen (Z. B. bedingte Laufwerk D), und wählen Sie «Volume Löschen». Mit dem System-Volume, auf dem Windows installiert ist, solches nicht tun, da das Verfahren zerstört alle in dieser Partition gespeicherten Dateien.

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-ob-edinit-lokal-nye-diski-ili-izmenit-ih-razmery-2.jpg) 

Nun klicken Sie mit der rechten Maustaste auf den benachbarten Abschnitt (bedingtes Laufwerk C), die Sie übertragen möchten freigegebene Bereich, und wählen Sie «Volume Erweitern».

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-ob-edinit-lokal-nye-diski-ili-izmenit-ih-razmery-3.jpg) 

Wenn der Assistent das Volume erweitert wird, drücken Sie zweimal «Weiter». Die ausgewählte Partition (in unserem Beispiel C) erhält das gesamte Volumen einem.

### Mit Hilfe von Drittanbieter-Programmen

Es gibt eine Kostenlose Software von Drittanbietern, die stark vereinfacht die Verwaltung von lokalen Datenträgern. Zum Beispiel das Programm MiniTool Partition Wizard erlaubt nicht nur schnell Zusammenführen-Volumes, sondern auch leicht ändern Ihre Größe. Es speichert alle Daten. Aber wenn auf dem PC wichtige Dateien sind, trotzdem machen Sie Ihre Backups — für den Fall.

Also, Laufwerke zu kombinieren mit dem MiniTool Partition Wizard, starten Sie das Programm und klicken Sie darauf (möge C), an die Sie anfügen möchten eine andere Partition (bedingtes D). Im Kontextmenü wählen Sie die Option Merge (Zusammenführen).

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-ob-edinit-lokal-nye-diski-ili-izmenit-ih-razmery-4.jpg) 

Im geöffneten Fenster klicken Sie auf diesen Abschnitt (C) und klicken Sie auf Next.

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-ob-edinit-lokal-nye-diski-ili-izmenit-ih-razmery-5.jpg) 

Nun klicken Sie auf den Abschnitt (D), das Sie anfügen an die bereits ausgewählten. In der unteren Hälfte des Fensters erscheint ein Feld mit dem Namen des Ordners: _merged\_partition\_content_. Das Programm erstellt die Partition und kopiert dorthin alle Dateien mit einer. Wenn Sie möchten, benennen Sie diesen Ordner. Klicken Sie Auf Finish.

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-ob-edinit-lokal-nye-diski-ili-izmenit-ih-razmery-6.jpg) 

Damit die änderungen wirksam werden, in der linken oberen Ecke in der Symbolleiste auf &#8220;Apply&#8221; («Übernehmen»). Wenn Sie aufgefordert werden, den Computer neu zu starten, klicken Sie auf OK und warten Sie, bis Windows neu zu starten. Am Ende im Explorer erscheint das Laufwerk, gleich der Größe von zwei kombinierten Abschnitten.

Wenn Ihr Ziel — nicht kombinieren lassen, und erhöht nur die Größe des einen von Ihnen (Z. B. D) auf Kosten eines anderen (wenn C wird), können Sie dies in zwei einfachen Schritten. Zuerst müssen Sie eine Partition verkleinern und anschließend dem zweiten Platz.

Um die Menge der Scheibe (C), wählen Sie im Hauptmenü MiniTool Partition Wizard und klicken Sie im linken Fensterbereich auf die Schaltfläche Move / Resize Partition («Move / resize Partition»). Im erscheinenden Fenster schieben Sie den regler so, dass die Zahl neben der Option Unallocated Space After entspricht dem Volumen, auf das Sie den markierten Bereich reduzieren möchten. Bestätigen Sie die änderung.

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-ob-edinit-lokal-nye-diski-ili-izmenit-ih-razmery-7.jpg) 

Weiter, markieren Sie im Hauptmenü auf das Laufwerk, das Sie vergrößern möchten (D). Wieder mit der Taste Move / Resize Partition und erweitern Sie das Volumen der Partition mit dem Schieberegler.

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-ob-edinit-lokal-nye-diski-ili-izmenit-ih-razmery-8.jpg) 

Klicken Sie auf Apply auf dem oberen Bedienfeld und warten Sie, bis das Programm перераспределит das gesamte Volumen. Dazu müssen Sie möglicherweise neu starten.

MiniTool Partition Wizard →

## Wie ändere ich die Partitionen unter macOS

Wenn Sie einen Mac haben, für die Verwaltung von Volumes des Laufwerks benötigen Sie das vorinstallierte Programm «Festplatten-Dienstprogramm». Es befindet sich im Menü &#8220;Finder&#8221; → «Programme» → «Dienstprogramme». Vor der Manipulation der Datenträgerverwaltung erstellen Sie unbedingt eine Sicherungskopie wichtiger Dateien.

Durch ausführen von «Festplatten-Dienstprogramm», wählen Sie im linken Fensterbereich die Festplatte, die Partitionen, die Sie editieren möchten, und klicken Sie auf die Schaltfläche «partitionieren».

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-ob-edinit-lokal-nye-diski-ili-izmenit-ih-razmery-9.jpg) 

Auf dem Bildschirm erscheint ein Fenster, in dem Sie kombinieren die gewählten Volumes (Partitionen oder ändern deren Größe. Das interface ist sehr offensichtlich: die Festplatte wird in Form eines Kreisdiagramms, und seine Abschnitte — in Form von Sektoren.

![](https://de.bestwow.net/wp-content/uploads/2019/10/kak-ob-edinit-lokal-nye-diski-ili-izmenit-ih-razmery-10.jpg) 

Um Partitionen Zusammenführen, müssen Sie sich zunächst deinstallieren Sie einer von Ihnen. Dazu markieren Sie ihn und klicken Sie auf das Minuszeichen unterhalb des Diagramms. Denken Sie daran, dass alle seine Daten gelöscht werden. Danach, wenn an der Stelle der gelöschten Partition wird ein leerer Sektor, erweitern Sie jede benachbarte ist, ziehen Sie den Cursor für seine Grenze. Und um eine Neuverteilung Maße Bände, einfach schieben Sie die Grenzen der jeweiligen Sektoren.

Wenn alle notwendigen Einstellungen vornehmen, klicken Sie auf «Übernehmen» und warten Sie, bis die änderungen wirksam werden.

## Lesen Sie auch

  * Was tun, wenn der Computer lässt sich nicht einschalten →
  * Was tun, wenn der Computer nicht sehen, die interne Festplatte →
  * Als Wärmeleitpaste ersetzen: eine einfache Anleitung, die die Lebensdauer der PC →