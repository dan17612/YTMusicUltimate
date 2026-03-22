# YTMusicUltimate
<p align="center">
<img src=https://user-images.githubusercontent.com/38832025/235781424-06d81647-b3db-4d9b-94dc-cd65cdf09145.png?raw=true) />
</p>    

<p align="center">
<img src=https://user-images.githubusercontent.com/38832025/235781207-6d1ad44e-0c32-4aec-9c75-cb928ca8a0d3.png?raw=true) />
</p>

<p align="center">
Der beste Tweak für YouTube Music auf iOS.
</p>

> **Hinweis:** Dieses Repository ist ein Fork des originalen Projekts __[ginsudev/YTMusicUltimate](https://github.com/ginsudev/YTMusicUltimate)__ von Ginsu und Dayanch96.

## Download-Links

* **Jailbreak:**
Füge __[https://ginsu.dev/repo](https://ginsu.dev/repo)__ zu deinem bevorzugten Installer hinzu und lade die neueste Version von dort herunter, oder von der __[Releases](https://github.com/dan17612/YTMusicUltimate/releases)__-Seite.

(arm.deb für Rootful- und arm64.deb für Rootless-Geräte)

* **Sideloading:**
  Wir stellen keine fertige Sideloading-IPA mehr bereit, du kannst sie aber selbst erstellen – lies weiter:

## IPA mit GitHub Actions selbst erstellen

Falls du das hier zum ersten Mal machst, beginne bei Schritt 1. Falls du schon einmal eine YTMU-IPA erstellt hast, überspringe Schritte 1 und 2, klicke stattdessen auf den „Sync fork"-Button, um die neueste Version des Tweaks zu erhalten, und fahre mit Schritt 3 fort.

1. Forke dieses Repository über den Fork-Button oben rechts.
2. Gehe in deinem geforkten Repository zu Repository-Einstellungen > Actions und aktiviere Lese- und Schreibberechtigungen.
3. Gehe im geforkten Repo auf den Tab „Actions", klicke links auf „Build and Release YTMusicUltimate" und dann rechts auf den Button „Run workflow".
4. Besorge dir eine entschlüsselte YTMusic-.ipa-Datei (wir können diese aus rechtlichen Gründen nicht bereitstellen) und lade sie auf einen Dateihost hoch (filebin.net oder Dropbox werden empfohlen). Füge die URL in das entsprechende Feld ein und klicke auf „Run workflow".
5. Warte, bis der Build abgeschlossen ist. Die fertige IPA kannst du im Releases-Bereich deines geforkten Repos herunterladen. (Falls du den Releases-Bereich nicht findest, rufe dein geforktes Repo auf und füge /releases zur URL hinzu, z. B. github.com/benutzername/YTMusicUltimate/releases.)

## Fehlerbehebung beim IPA-Build (IPA lässt sich nicht erstellen / GitHub Action schlägt fehl / Releases-Bereich nicht auffindbar usw.)

In 99,9 % der Fälle liegt das Problem an der angegebenen IPA-URL. Du MUSST eine entschlüsselte IPA angeben. Es darf keine andere Dateiendung sein – es muss eine **.ipa**-Datei sein. Besorge dir eine entschlüsselte YTMusic-IPA (dabei können wir dir nicht helfen), lade sie auf filebin.net oder Dropbox hoch und gib den direkten Link in die GitHub Action ein. Wenn du eine funktionierende IPA findest und sie korrekt hochlädst, wird alles einwandfrei funktionieren, versprochen.

Falls die GitHub Action erfolgreich war und du das Ergebnis nicht findest, musst du /releases zur URL deines geforkten Repositories hinzufügen. Es sieht dann ungefähr so aus: https://github.com/DEINBENUTZERNAME/YTMusicUltimate/releases – vergiss nicht, DEINBENUTZERNAME durch deinen tatsächlichen Benutzernamen zu ersetzen. Es mag unsichtbar wirken, aber wenn die GitHub Action erfolgreich war, ist die IPA dort zu finden.


## Paket selbst auf deinem Gerät erstellen
1. Installiere __[Theos](https://theos.dev/docs/installation)__
2. Klone dieses Repo __[mit git](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)__
3. Wechsle in deinen YTMusicUltimate-Ordner und führe aus:

   • '**make clean package**' – erstellt ein Deb für Rootful-Geräte
   
   • '**make clean package ROOTLESS=1**' – erstellt ein Deb für Rootless-Geräte
   
   • '**make clean package SIDELOADING=1**' – erstellt ein Deb zum Injizieren in eine IPA
   
   

   • Wie man Tweaks in eine IPA injiziert, erfährst du __[hier (Azule)](https://github.com/Al4ise/Azule)__




Erstellt mit ❤ von Ginsu und Dayanch96
