# Mind Planner – Website-Demo

## Lokal testen
`index.html` im Browser öffnen. Für eine lokale Server-Vorschau kann z. B. VS Code mit Live Server verwendet werden.

## Auf GitHub Pages veröffentlichen
1. Neues GitHub-Repository erstellen, z. B. `mind-planner`.
2. Alle Dateien und den Ordner `assets` hochladen.
3. Unter **Settings → Pages** als Quelle `Deploy from a branch` wählen.
4. Branch `main`, Ordner `/ (root)` auswählen und speichern.
5. Nach dem Deployment die angezeigte GitHub-Pages-Adresse öffnen.

## Logo
Das Original-Logo als `assets/mindplanner-logo.jpeg` ablegen. Es wird im Header automatisch angezeigt. Der Footer verwendet vorerst ein neutrales Herzsymbol.

## Demo-Grenzen
- Selbsttest: lokale Selbstreflexion, keine Diagnose und keine Datenübertragung.
- Wochenplan: Speicherung im Browser dieses Geräts via localStorage.
- Community: Beispielgruppen, lokal erstellbare Demo-Gruppe; keine echte Registrierung oder Nachrichten.
- Veranstaltungen: Beispieldaten; Anmeldung wird nur visuell vorgemerkt.
- Newsletter: keine E-Mail wird versendet.
- Videos: Platzhaltertexte; echte Video-URLs/Embeds müssen ergänzt werden.
- App-Store-Buttons/Downloads sind noch nicht angebunden.
- Impressum und Datenschutz sind Platzhalter und müssen vor Veröffentlichung rechtlich vervollständigt werden.

## Dateien
Mehrere eigenständige HTML-Seiten, gemeinsames `styles.css` und `app.js`.


## Neue Community-Demo-Funktionen
- Das Zitat auf der Startseite wechselt automatisch täglich zwischen acht Zitaten.
- Die Stimmungsabstimmung und Pinnwand speichern Daten nur lokal im jeweiligen Browser. Besucher:innen sehen daher noch keine gemeinsamen Ergebnisse oder Beiträge.
- Vor Veröffentlichung bitte in `community.html` Die Kontaktadresse `MindPlaner@help.com` ist eine fiktive Demo-Adresse und muss vor Veröffentlichung durch eine erreichbare Adresse ersetzt werden.
- Für eine echte gemeinsame Abstimmung und einen öffentlichen Community-Chat werden Backend, Datenschutzinformationen und Moderation benötigt.


Das verwendete Logo ist die vom Projektteam bereitgestellte Datei `assets/mindplanner-logo.jpeg`. Bestehende Website-Bilder und Bildbereiche bleiben erhalten.
