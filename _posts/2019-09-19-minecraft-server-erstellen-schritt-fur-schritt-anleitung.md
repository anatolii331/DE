---
id: 880
title: 'Minecraft-Server erstellen: Schritt für Schritt Anleitung'
date: 2019-09-19T15:16:40+00:00
author: user
layout: post
guid: http://de.bestwow.net/minecraft-server-erstellen-schritt-fur-schritt-anleitung/
permalink: /minecraft-server-erstellen-schritt-fur-schritt-anleitung/
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
  - https://lifehacker.ru/kak-sozdat-server-minecraft/
  - https://lifehacker.ru/kak-sozdat-server-minecraft/
post_views_count:
  - "14"
  - "14"
categories:
  - Fashion
---
## 1. Laden Sie die erforderlichen Dateien

Sie benötigen die neueste Java-Version <span><span> Java Download </span> </span> und Datei-Server-Minecraft — die aktuelle Release finden Sie auf der offiziellen Website des Entwicklers <span><span> HERUNTERLADEN MINECRAFT-SERVER: JAVA EDITION </span> </span>. Java installieren müssen, und Datei-Server in einem separaten Ordner platzieren, zum Beispiel C:/Games/Minecraft Server.

![](http://de.bestwow.net/wp-content/uploads/2019/09/kak-sozdat-server-minecraft-poshagovaya-instrukciya-1.png) 

## 2. Konfigurieren Sie den Server

Führen Sie die Datei server.jar. Wenn das Fenster «Öffnen mit», wählen Sie die Java-Anwendung. Im Ordner des Servers erscheint das Dokument eula.txt — öffnen Sie es und in der letzten Zeile den Wert von false auf true. Dies würde bedeuten, dass Sie die Lizenzvereinbarung. Andernfalls ist der Server nicht verdient.

![](http://de.bestwow.net/wp-content/uploads/2019/09/kak-sozdat-server-minecraft-poshagovaya-instrukciya-2.jpg) 

Starten Sie server.jar noch einmal. Es erscheint ein Fenster des Servers. Das Feld rechts ist die Konsole, in der aufgeführt alle Aktivitäten Programm. Links oben befindet sich die Statistiken, und unter ihm — die Liste der Spieler, die im Moment auf dem Server.

![](http://de.bestwow.net/wp-content/uploads/2019/09/kak-sozdat-server-minecraft-poshagovaya-instrukciya-3.png) 

Nachdem in der Konsole erscheint Done, schließen Sie das Fenster. In einem beliebigen Texteditor öffnen Sie die Datei server.properties, die sich im Ordner des Servers. Dies ist die Liste der Programmeinstellungen. Stellen Sie die gewünschten Optionen, indem Sie die Werte, die nach dem = &#8211; Zeichen in der entsprechenden Zeile.

![](http://de.bestwow.net/wp-content/uploads/2019/09/kak-sozdat-server-minecraft-poshagovaya-instrukciya-4.jpg) 

Hier ist eine Beschreibung von einigen nützlichen Parameter.

<div>
  <table class="table">
    <tr style="height: 24px">
      <td style="width: 153px;height: 24px;text-align: left">
        <strong>Option</strong>
      </td>
      
      <td style="width: 260px;height: 24px;text-align: left">
        <strong>Werte (Standard)</strong>
      </td>
      
      <td style="width: 309px;height: 24px;text-align: left">
        <strong>Beschreibung</strong>
      </td>
    </tr>
    
    <tr style="height: 24px">
      <td style="width: 153px;height: 24px">
        gamemode
      </td>
      
      <td style="width: 260px;height: 24px">
        Zahl von 0 bis 3 (0)
      </td>
      
      <td style="width: 309px;height: 24px">
        Spielmodus:</p> 
        
        <ul>
          <li>
            0 — überleben;
          </li>
          <li>
            1 — Kreativität;
          </li>
          <li>
            2 — Abenteuer;
          </li>
          <li>
            3 — Beobachtung
          </li>
        </ul>
      </td>
    </tr>
    
    <tr style="height: 24px">
      <td style="width: 153px;height: 24px">
        force-gamemode
      </td>
      
      <td style="width: 260px;height: 24px">
        true / false (false)
      </td>
      
      <td style="width: 309px;height: 24px">
        Beim Wert &#8220;true&#8221; schaltet den Server Spiele jedes neue Mitglied auf dem, was angegeben ist im gamemode. Bei false — schaltet nicht
      </td>
    </tr>
    
    <tr style="height: 24px">
      <td style="width: 153px;height: 24px">
        allow-nether
      </td>
      
      <td style="width: 260px;height: 24px">
        true / false (true)
      </td>
      
      <td style="width: 309px;height: 24px">
        Bei true können die Spieler bewegen in die Untere Welt, bei false nicht
      </td>
    </tr>
    
    <tr style="height: 24px">
      <td style="width: 153px;height: 24px">
        player-idle-timeout
      </td>
      
      <td style="width: 260px;height: 24px">
        Zahl (0)
      </td>
      
      <td style="width: 309px;height: 24px">
        Wenn der Spieler untätig ist hier innerhalb der angegebenen Minuten, dann wirft ihn vom Server. Der Wert 0 deaktiviert diese Funktion
      </td>
    </tr>
    
    <tr style="height: 24px">
      <td style="width: 153px;height: 24px">
        difficulty
      </td>
      
      <td style="width: 260px;height: 24px">
        Zahl von 0 bis 3 (1)
      </td>
      
      <td style="width: 309px;height: 24px">
        Schwierigkeit des Spiels:</p> 
        
        <ul>
          <li>
            0 — friedlich;
          </li>
          <li>
            1 — leicht;
          </li>
          <li>
            2 — normal;
          </li>
          <li>
            3 — Komplex
          </li>
        </ul>
      </td>
    </tr>
    
    <tr style="height: 24px">
      <td style="width: 153px;height: 24px">
        spawn-monsters
      </td>
      
      <td style="width: 260px;height: 24px">
        true / false (true)
      </td>
      
      <td style="width: 309px;height: 24px">
        Steuert die automatische Auftritt von Zombies, криперов und andere Monster in der Spielwelt. true — Ungeheuers erscheinen, false — Nein
      </td>
    </tr>
    
    <tr style="height: 24px">
      <td style="width: 153px;height: 24px">
        pvp
      </td>
      
      <td style="width: 260px;height: 24px">
        true / false (true)
      </td>
      
      <td style="width: 309px;height: 24px">
        true — Spieler können aufzutragen einander Schaden, false — nicht in der Lage
      </td>
    </tr>
    
    <tr style="height: 24px">
      <td style="width: 153px;height: 24px">
        level-type
      </td>
      
      <td style="width: 260px;height: 24px">
        DEFAULT / FLAT / LARGEBIOMES / AMPLIFIED (DEFAULT)
      </td>
      
      <td style="width: 309px;height: 24px">
        Art der Welt:</p> 
        
        <ul>
          <li>
            DEFAULT — normal;
          </li>
          <li>
            FLAT — flach;
          </li>
          <li>
            LARGEBIOMES — große Biome;
          </li>
          <li>
            <span>AMPLIFIED — erweiterte</span>
          </li>
        </ul>
      </td>
    </tr>
    
    <tr style="height: 24px">
      <td style="width: 153px;height: 24px">
        hardcore
      </td>
      
      <td style="width: 260px;height: 24px">
        true / false (false)
      </td>
      
      <td style="width: 309px;height: 24px">
        Aktiviert den Modus «Hardcore». true — aktiviert, false — deaktiviert
      </td>
    </tr>
    
    <tr style="height: 48px">
      <td style="width: 153px;height: 48px">
        max-players
      </td>
      
      <td style="width: 260px;height: 48px">
        Zahl von 0 bis 2147483647 (20)
      </td>
      
      <td style="width: 309px;height: 48px">
        Die maximale Anzahl von Spielern auf dem Server
      </td>
    </tr>
    
    <tr style="height: 72px">
      <td style="width: 153px;height: 72px">
        spawn-npcs
      </td>
      
      <td style="width: 260px;height: 72px">
        true / false (true)
      </td>
      
      <td style="width: 309px;height: 72px">
        Steuert die automatische Auftritt der Dorfbewohner. true Sie — zeigen, false — Nein
      </td>
    </tr>
    
    <tr style="height: 24px">
      <td style="width: 153px;height: 24px">
        allow-flight
      </td>
      
      <td style="width: 260px;height: 24px">
        true / false (false)
      </td>
      
      <td style="width: 309px;height: 24px">
        true — Spieler können Fliegen im Modus «Überleben», wenn Sie das entsprechende Plugin. false — nicht können
      </td>
    </tr>
    
    <tr style="height: 96px">
      <td style="width: 153px;height: 96px">
        spawn-animals
      </td>
      
      <td style="width: 260px;height: 96px">
        true / false (true)
      </td>
      
      <td style="width: 309px;height: 96px">
        Steuert die automatische Auftritt Hühner, Schweine und andere friedliche Tiere. true Sie — zeigen, false — Nein
      </td>
    </tr>
    
    <tr style="height: 72px">
      <td style="width: 153px;height: 72px">
        generate-structures
      </td>
      
      <td style="width: 260px;height: 72px">
        true / false (true)
      </td>
      
      <td style="width: 309px;height: 72px">
        true — in der Welt des Spiels gibt es Burgen, Dörfer und andere Gebäude. false — gibt es Sie nicht
      </td>
    </tr>
    
    <tr style="height: 72px">
      <td style="width: 153px;height: 72px">
        online-mode
      </td>
      
      <td style="width: 260px;height: 72px">
        true / false (true)
      </td>
      
      <td style="width: 309px;height: 72px">
        true — zum Server kann nicht verbinden die Spieler mit Raubkopien Versionen von Minecraft. false — es ist möglich
      </td>
    </tr>
    
    <tr style="height: 24px">
      <td style="width: 153px;height: 24px">
        max-build-height
      </td>
      
      <td style="width: 260px;height: 24px">
        Anzahl von 64 bis 256, ein Vielfaches von 16 (256)
      </td>
      
      <td style="width: 309px;height: 24px">
        Die maximale Höhe der Gebäude in Blöcken. Oberhalb dieses Wertes Blöcke können weder schaffen noch zerstören
      </td>
    </tr>
    
    <tr style="height: 72px">
      <td style="width: 153px;height: 72px">
        level-seed
      </td>
      
      <td style="width: 260px;height: 72px">
        Jede Korn
      </td>
      
      <td style="width: 309px;height: 72px">
        Korn, Regulierung der Erzeugung der Welt. Wenn leer gelassen, wird eine zufällige Welt generiert wird
      </td>
    </tr>
  </table>
</div>

## 3. Starten Sie den Server und verbinden Sie Sie mit

Nachdem alle Einstellungen ausgestellt, starten Sie server.jar. Wann erscheint «Done», zu einem Server kann eine Verbindung herstellen. Um dies zu tun, müssen Sie im Hauptmenü von Minecraft wählen Sie «Multiplayer», klicken «Server Hinzufügen», geben Sie die gewünschte IP-Adresse und klicken Sie auf «Ausführen».

Wenn der Server auf demselben Computer ausgeführt wird, und dass das Spiel, das im Feld geben Sie einfach die IP «localhost» oder «127.0.0.1». Wenn nicht, dann müssen Sie wissen, die aktuelle IP-Geräte.

![](http://de.bestwow.net/wp-content/uploads/2019/09/kak-sozdat-server-minecraft-poshagovaya-instrukciya-5.jpg) 

## 4. Verwalten Sie Server

Für die Verwaltung des Servers verwenden Sie die Befehle für die Konsole. Hier sind diejenigen, die Ihnen nützlich sein können.

<div>
  <table class="table">
    <tr style="height: 21px">
      <td style="width: 243px;height: 21px;text-align: left">
        <strong>Team</strong>
      </td>
      
      <td style="width: 705px;height: 21px;text-align: left">
        <strong>Beschreibung</strong>
      </td>
    </tr>
    
    <tr style="height: 21px">
      <td style="width: 243px;height: 21px">
        give name Anzahl Gegenstand
      </td>
      
      <td style="width: 705px;height: 21px">
        Gibt dem Spieler das angegebene Objekt
      </td>
    </tr>
    
    <tr style="height: 21px">
      <td style="width: 243px;height: 21px">
        ban name
      </td>
      
      <td style="width: 705px;height: 21px">
        Verbietet dem Spieler auf den Server
      </td>
    </tr>
    
    <tr style="height: 21px">
      <td style="width: 243px;height: 21px">
        teleport Ziel Zweck
      </td>
      
      <td style="width: 705px;height: 21px">
        Trägt das Ziel (Spieler, Gegenstand oder Wesen) zu einem Ziel (Koordinaten oder Spieler)
      </td>
    </tr>
    
    <tr style="height: 21px">
      <td style="width: 243px;height: 21px">
        summon Ziel Koordinaten
      </td>
      
      <td style="width: 705px;height: 21px">
        Erstellt das Ziel (ein Gegenstand oder ein Wesen) auf den angegebenen Koordinaten
      </td>
    </tr>
    
    <tr style="height: 21px">
      <td style="width: 243px;height: 21px">
        op name
      </td>
      
      <td style="width: 705px;height: 21px">
        Macht der Spieler dem Betreiber des Servers
      </td>
    </tr>
    
    <tr style="height: 21px">
      <td style="width: 243px;height: 21px">
        kill name
      </td>
      
      <td style="width: 705px;height: 21px">
        Tötet den Spieler
      </td>
    </tr>
    
    <tr style="height: 21px">
      <td style="width: 243px;height: 21px">
        spawnpoint name Koordinaten
      </td>
      
      <td style="width: 705px;height: 21px">
        Gibt Spawn den Spieler
      </td>
    </tr>
    
    <tr style="height: 21px">
      <td style="width: 243px;height: 21px">
        save-all
      </td>
      
      <td style="width: 705px;height: 21px">
        Speichert der Server auf der Festplatte. Der Prozess ist allmählich. Wenn durch Leerzeichen hinzufügen die Option [flush], das speichern geschieht sofort, aber der Server hängt für einige Sekunden
      </td>
    </tr>
    
    <tr style="height: 21px">
      <td style="width: 243px;height: 21px">
        stop
      </td>
      
      <td style="width: 705px;height: 21px">
        Schaltet den Server
      </td>
    </tr>
  </table>
</div>

Eine vollständige Liste der verfügbaren Befehle erhält man durch Eingabe in der Konsole das Wort help.

<div>
  <h2 class="read-also__title">
    <span>Lesen Sie auch</span> <span>🎮 </span>
  </h2>
  
  <ul class="read-also__list">
    <li>
      10 Kostenlose PC-Spiele, die lange Fesseln
    </li>
    <li>
      Wie zum Download von Minecraft kostenlos
    </li>
    <li>
      7 mods für Minecraft, die das Spiel ändern bis zur Unkenntlichkeit
    </li>
    <li>
      10 Coole Minecraft mods, die einen Download Wert
    </li>
    <li>
      Wo Download-mods für Minecraft: 5 benutzerfreundliche Websites
    </li>
  </ul>
</div>