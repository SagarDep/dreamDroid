## 1.2.419
* FIX: Verbesserung an der "TV" Version von dreamDroid
* FIX: Abstürze behoben
* DEV: Code Cleanups

## 1.2.418
* FIX: Die Picon-Synchronisation schrieb leere Dateien (Picons müssen ggf. erneut synchronisiert werden)

## 1.2.417
* NEU: Neuer Dialog für Änderungen
* FIX: Diverse Probleme und Abstürze die durch das Drehen des Handys oder bei einem späteren Aufruf der App enstanden sind
* IMP: Die Audio Qualität des Signal Meters wurde verbessert. Der Bildschirm bleibt nun dauerhaft an während Es offen ist

## 1.2.416
* FIX: Absturz beim Start auf Gerät mit älteren Android Versionen (vor Lollipop)

## 1.2.415
* Hinweis: Für Nutzer des Google Play Store sind alle Einträge nach Version 1.2-400 gültig!
* FIX: Virtual Remote Widget unter Android >= Oreo

## 1.2.414
* Weitere Änderungen am VideoPlayer
* Schnelles Blättern (FastScroll) funktioniert wieder

## 1.2.409
* DreamDroid ist jetzt freie Software, lizensiert unter GPLv3
* Einige Änderungen für die Veröffentlichung auf f-droid

## 1.2-405
* FIX: Sync-Benachrichtigungen unter Android >= Oreo

## 1.2-404
* Adaptives Icon für Android >= Oreo

## 1.2-403
* FIX: Update auf neusten VLC, hilft hoffentlich Video/Audio Probleme zu beseitigen

## 1.2-400
* FIX: Screenshots

## 1.2-398
* FIX: Diverse Abstürze
* FIX: Reload Button

## 1.2-397
* FIX: Abstürze beim Verlassen langer Listen (z.B. Timer Bearbeiten aus dem Sender-EPG)

## 1.2-396
* FIX: Diverse Abstürze
* FIX: Eine Änderung des Themes trat erst nach einem Neustart der App in Effekt

## 1.2-395
* FIX: Crash bei "Timer Bearbeiten" aus der EPG-Liste
* FIX: Fehlender Text bei Ja/Nein Dialogen

## 1.2-394
* NEU: Initiale Unterstützung von Android TV
* NEU: Interne Updates und Anpassungen
* NEU: Einige coole Verbesserungen der Navigation durch F. Edelmann
* NEU: Viele kleinere optische Anpassungen
* FIX: Einige potentielle Zertifikatsprobleme wurden behoben
* BESSER: Performance verbessert

## 1.1-386
* FIX: Abstürze im VideoPlayer

## 1.1-385
* FIX: Abstürze unter Android 7.0
* FIX: Kaputte Apspekt-Ratio im VideoPlayer in Verbindung mit Rotation/MultiWindow

## 1.1-384
* NEU: Tonspur/Untertitel Auswahl im Videoplayer
* FIX: Ein paar (mögliche) Abstürze
* BESSER: kleinere Verbesserungen an der Benutzeroberfläche

## 1.1-381
* FIX: "Lade..." wurde nach rotation in einer Liste angezeigt

## 1.1-380
* FIX: Fehlerbehandlung in diversen Listen verbessert
* FIX: Workaround für die Probleme mit der Funktion "EPG" in Verbindung mit älteren Dreamboxen

## 1.1-379
* FIX: der fix für Profilnamen ist nun tats. enthalten

## 1.1-378
* NEW: Picons können nun direkt über http(s) geladen werden und müssen nicht mehr vorab synchronisiert werden (Vorsicht wg. Datenvolumen!)
* FIX: Profil-Namen konnten nicht mehr geändert werden da das Feld nicht zu sehen war
* FIX: Beim Wechsel von "EPG" nach "Einstellungen" blieb die Datums/Zeitwahl des EPG stehen

## 1.1-377
* NEU: EPG Infos werden nun nicht mehr in einem Popup sondern in einem "Bottom Sheet" angzeigt
* BESSER: Das Verhalten des Videoplayers in Sachen "was wird angezeigt und was nicht" wurde verbessert
* NEU: Videoplayer kann nun in Aufnahmen springen, leider ist es derzeit nicht möglich den Fortschritt anzuzeigen :(
* NEU: Videoplayer-Gesten für Helligkeit und Lautstärke im (Helligkeit links, Lautstärke rechts)
* FIX: Kanalliste im Video Player crashte wenn man einen Marker wählte
* FIX: Zeilenumbrüche werden nicht mehr aus dem EPG gefiltert, könnte zu Problemen auf älteren Boxen führen (falls ja, bitte mitteilen)
* FIX: Unter Android >= 6.0 wir die Berechtigung für den Standort jetzt erst angefragt wenn das Thema manuell auf "Auto" gestellt wird. Neues Standard Thema ist "Tag"
* BESSER: Die Ordnerwahl in der Filmliste basiert nun auf einem Floating Action Button
* BESSER: Die Bouquetwahl unter "Umschalten" gleicht nun der aus "EPG"
* BESSER: Die überprüfung des Verbindungsprofils wird nicht mehr ständig neu durchgeführt
* TEC: Viele Grafiken durch Vector-Grafiken ersetzt
* TEC: Wechsel von UniversalImageLoader zu Picasso
* TEC: Cleanups und Aktualisierung externer Bibliotheken

## 1.1-372
* FIX: Diverse kleinere Fehler behoben die unter gewissen Umständen zu Abstürzen führten
* FIX: Die App ist nun wieder deutlich kleiner

## 1.1
* NEU: Integrierter Videoplayer auf VLC-Basis
* NEU: Support für Encoder-basierte Streams auf DM820 und DM7080
* NEU: Unterstützung der Android 6.x Berechtigungen
* NEU: Automatisches Tag/Nacht Thema (Einstellbar, Automatik benötigt ungefähren Standort zur Tag/Nacht-Berechnung)
* NEU: Android N MultiWindow Unterstützung
* UPD: UI wurde auf aktuelle Technologien aktualisiert (GROSSE interne Änderungen)
* FIX: Diverse Fehlerbehbungen (defekter EPG auf älteren Dreamboxen, doppelte Tags, ...)
* NEU: Fehler die wir noch nicht gefunden haben ;)

