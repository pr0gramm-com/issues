![pr0gramm](https://pr0gramm.com/media/pr0gramm.svg)
# Öffentlicher Issue Tracker

Dieses Repository dient als öffentlicher Issue Tracker für das pr0gramm Redesign. Hier werden aktuelle Bugs und geplante Features/TODOs dokumentiert.


## Inhaltsverzeichnis
- [Bekannte Bugs](#-bekannte-bugs)
    - [UI/Design Probleme](#uidesign-probleme)
    - [Scroll & Navigation](#scroll--navigation)
    - [Video-bezogene Probleme](#video-bezogene-probleme)
    - [Funktionale Fehler](#funktionale-fehler)
- [Geplante Features & TODOs](#-geplante-features--todos)
    - [UI/UX Verbesserungen](#uiux-verbesserungen)
    - [Umsetzung alte Features](#umsetzung-alte-features)
    - [Umsetzung neue Features](#umsetzung-neue-features)
    - [System & Performance](#system--performance)
    - [Funktionalitäten](#funktionalitäten)
    - [Sonstiges](#sonstiges)
- [Leitfaden zum Erstellen von Issues](#leitfaden-zum-erstellen-von-issues)


## 🐛 Bekannte Bugs

### UI/Design Probleme
- Themewechsel Radiobutton springt nicht um
- Tag Scroll Container braucht Schatten links
- Gradient in Score-Graph mobil fehlerhaft
- "Small"-Textbox hat zu kleine Font
- Blussi rotiert nicht mobil
- Links in BookmarkBar teilweise falsch

### Scroll & Navigation
- Itemsquery mit Around zeigt falschen Skeleton an
- Stream scrollt beim tippen nach oben
- Klick auf Item geht nicht zur Post-Übersicht von User, wenn man im Uploads-eines-Users ist

### Video-bezogene Probleme
- Videos manchmal nicht klickbar um sie zu schließen
- Videotimeline ruckelt

### Funktionale Fehler
- Antworten-Button ausblenden, wenn maximale Kommentartiefe erreicht
- Fehler bei erfolgreichem Upload
- Mancher State wird bei CheckSimilar-Responses zurückgesetzt
- Session zerstört, Seite fehlert, Logout nicht möglich
- Lade-Placeholder bleibt da, wenn Suche leer ausging

## ✨ Geplante Features & TODOs

### UI/UX Verbesserungen
- Auto-Grow-TextArea
- Details-Element beim auf UND zuklappen animieren
- Ripple-Effekt nur bei Linksklick
- Spacing auf der Upload-Seite
- Tagleiste mobil horizontal machen
- Umbruch in Einstellungen

### Umsetzung alte Features
- Meme Generator
- Profilbilder
- Registrierung
- pr0mium Kauf
- Repost-Anzeige beim Upload
- Username-Vervollständigung für Textfelder

### Umsetzung neue Features
- Wichteln 2.0
- Quick Polls in der Seitenleiste
- Unterstützung mehrerer Tonspuren
- Upload Editor
- Video Editor
- Komplette Überarbeitung des Suchservices

### System & Performance
- Item Stream Desktop noch nicht fertig
- Support für Ersatzserver

### Funktionalitäten
- noch unfertige Einstellungsmenüs
- Gesehen Status schreiben
- Kommentarverlinkungen Inbox
- Sammlungseinstellungen, Kuratoren, verschieben/kopieren

### Sonstiges
- Impressum-Links auf der Beta-Login-Seite
- Scroll to top in Impressum/AGB
- Werbung
- Mobiler Player: Bei Pause immer anzeigen, dass gerade pausiert ist

📝 Dieser Issue Tracker wird regelmäßig aktualisiert. Neue Issues werden entsprechend kategorisiert und hinzugefügt.



# Leitfaden zum Erstellen von Issues
Inhaltsverzeichnis
- [Aussagekräftiger Titel](#aussagekräftiger-titel)
- [Detaillierte Fehlerbeschreibung](#detaillierte-fehlerbeschreibung)
- [Reproduzierbarkeit](#reproduzierbarkeit)
- [Erwartetes Verhalten](#erwartetes-verhalten)
- [Umgebungsinformationen](#umgebungsinformationen)
- [Beispielformat](#beispielformat)


## Aussagekräftiger Titel
   - Wähle einen kurzen, aber präzisen Titel
   - Der Titel sollte das Hauptproblem klar beschreiben
## Detaillierte Fehlerbeschreibung
   - Beschreibe genau, was nicht funktioniert
   - Füge wenn möglich Screenshots oder Fehlermeldungen hinzu
   - Sei so spezifisch wie möglich
## Reproduzierbarkeit
   - Liste alle Schritte auf, die zum Fehler führen
   - Nummeriere die Schritte chronologisch
   - Beschreibe den Ausgangspunkt (z.B. "Startseite von pr0.app")
## Erwartetes Verhalten
   - Erkläre, wie die Funktion eigentlich arbeiten sollte
   - Beschreibe das gewünschte Ergebnis
## Umgebungsinformationen
   - Browser und Version (z.B. Firefox 129)
   - Betriebssystem (z.B. Windows 10)
   - Bei mobilen Geräten: Gerät und OS-Version
   - Zusätzliche Tipps
   - Verwende eine sachliche und professionelle Sprache
   - Strukturiere dein Issue übersichtlich mit Überschriften und Aufzählungen
   - Prüfe vor dem Erstellen, ob das Problem bereits gemeldet wurde
   - Reagiere zeitnah auf Rückfragen der Entwickler
   - Markiere das Issue mit passenden Labels (z.B. "bug")
## Beispielformat
```markdown
### Fehlerbeschreibung
[Detaillierte Beschreibung des Problems]

### Schritte zur Reproduktion
1. Gehe zu pr0.app
2. [Weiterer Schritt]
3. [Weiterer Schritt]

### Erwartetes Verhalten
[Beschreibung des erwarteten Verhaltens]

### Tatsächliches Verhalten
[Beschreibung des aktuellen, fehlerhaften Verhaltens]

### Umgebung
- Browser: [Browser & Version]
- Betriebssystem: [OS & Version]

```
Bei Fragen oder Unklarheiten kannst du dich jederzeit an uns wenden.