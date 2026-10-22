# PBTM – Satirisches Besuchsterminportal

Privates, statisches Spassportal mit 24 Schritten und vier Terminvorschlägen. Alle Inhalte sind rein privat und offensichtlich satirisch.

## GitHub Pages veröffentlichen

1. Bei github.com mit einem **privaten** GitHub-Konto anmelden.
2. Neues **öffentliches** Repository erstellen, z. B. `pbtm-besuch`. Beachte: Die Repository-Dateien und die Webseite sind öffentlich einsehbar.
3. `index.html` und `.nojekyll` in die oberste Ebene des Repositorys hochladen.
4. Im Repository unter **Settings → Pages** bei **Build and deployment → Source** `Deploy from a branch` wählen; Branch `main`, Folder `/ (root)` und `Save`.
5. Nach dem Deployment zeigt GitHub Pages einen Link der Form `https://BENUTZERNAME.github.io/pbtm-besuch/` an. **Nicht vorab raten oder als veröffentlicht ausgeben.**
6. Den Link in einer privaten E-Mail an den Kollegen senden. Nach der Terminwahl kann die Pages-Veröffentlichung deaktiviert oder das Repository gelöscht werden.

## Optional für Rückantwort direkt an dich

In `index.html` direkt am Anfang des Skripts `empfaengerEmail:''` durch `empfaengerEmail:'DEINE-PRIVATE-ADRESSE'` ersetzen. Die E-Mail-Adresse ist danach **öffentlich im Quelltext lesbar**. Ohne Eintrag wird ein Mailentwurf ohne Empfänger geöffnet; der Kollege trägt deine Adresse selbst ein oder kopiert den Antworttext.

## Grenzen und Datenschutz

- Nur HTML/CSS/JavaScript, kein PHP, keine serverseitigen Prozesse, keine Datenbank, keine externen Bibliotheken, keine Netzwerkanfragen aus dem Portal.
- Die Seite fordert keine Passwörter oder echten Codes an. Alle Prüfungen laufen lokal im Browser und sind bewusst keine echte Authentifizierung.
- Der Name ist optional auch als Pseudonym verwendbar. Antworten bleiben im RAM des Browsers bis die Seite geschlossen/neu geladen wird.
- Das letzte Formular öffnet einen E-Mail-Entwurf. Er wird **nicht** automatisch versendet.
- GitHub Pages ist öffentlich und bietet keinen personenbezogenen Zugriffsschutz; GitHub oder Browser/Infrastruktur können gewöhnliche Zugriffsprotokolle haben.
- GitHub Pages ist keine offizielle Unternehmensplattform. Nur über private Konten verwenden und keine Firmenlogos oder vertraulichen Informationen hochladen.
- Falls HTML-Anhänge in der Firma gesperrt sind, lieber den Pages-Link schicken, nicht Filter umgehen.
