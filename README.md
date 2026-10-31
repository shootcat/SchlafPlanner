# SchlafPlaner – Adaptiver Kinder-Schlaf-Tracker (Android APK via GitHub Actions)

Dieses Repository enthält eine komplette hybride Android-App (Capacitor + HTML5/JS) inklusive des mathematischen Schlaf-Algorithmus (Zwei-Prozess-Modell nach Borbély, EWMA-Lernrate, Schlafschuld-Korrektur und Wake-up Cap).

## So lässt du GitHub automatisch die APK bauen:

1. Erstelle auf GitHub ein neues Repository (z. B. `schlaf-planer`).
2. Lade den gesamten Inhalt dieses ZIP-Archivs in dein Repository hoch (wichtig: der versteckte Ordner `.github/workflows/build-apk.yml` muss mit hochgeladen werden).
3. Gehe in deinem GitHub-Repository oben auf den Reiter **Actions**.
4. Dort läuft automatisch der Workflow **Build Android APK** an (dauert ca. 2 bis 3 Minuten).
5. Klicke nach Abschluss auf den durchgelaufenen Workflow und lade ganz unten unter **Artifacts** die Datei **`SchlafPlaner-debug-apk`** herunter. Darin befindet sich deine installierbare `app-debug.apk`.
