# Fachdeutsch-Trainer

Installierbare Web-App (PWA) zum Deutschlernen für Ingenieure: Einstufungstest, Lernplan mit Mindest-Lernzeit,
adaptive Übungen (Wortschatz, Grammatik, Hören, Sprechen mit Mikrofon, Schreiben), Regeln auf Deutsch, Englisch und Persisch.

- Daten bleiben auf dem Gerät (IndexedDB). Sicherung: Profil → „Sicherung herunterladen“.
- KI-Funktionen nutzen den eigenen Anthropic-API-Schlüssel (Profil → KI-Schlüssel). Der Schlüssel bleibt auf dem Gerät.
- Installation: Seite in Chrome öffnen → Menü ⋮ → „App installieren“.

Dieses Repository enthält keine persönlichen Daten.

Adresse: https://paknejadmasih-pixel.github.io/fachdeutsch/

## Android-App (APK)
Jede Änderung auf `main` baut automatisch eine APK (GitHub Actions) und veröffentlicht sie unter **Releases**:
https://github.com/paknejadmasih-pixel/fachdeutsch/releases/latest/download/Fachdeutsch-Trainer.apk

Hinweis: Der Signaturschlüssel (`android/fachdeutsch.jks`) liegt für diese private Lern-App offen im Repository.
Installiere Updates nur aus diesem Repository.
