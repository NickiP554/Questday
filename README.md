# QuestDay – GitHub APK Builder

Dieses Repository ist so vorbereitet, dass GitHub Actions automatisch eine Android-APK baut.

## Handy-Anleitung

1. Erstelle auf github.com ein **öffentliches Repository** namens `QuestDay`.
2. Lade ALLE Dateien und Ordner dieses Projekts in das Repository hoch.
   Wichtig: `.github/workflows/build-apk.yml` muss ebenfalls vorhanden sein.
3. Öffne im Repository den Tab **Actions**.
4. Wähle **Build QuestDay APK**.
5. Drücke **Run workflow** und danach nochmals **Run workflow**.
6. Warte, bis der Build mit einem grünen Haken abgeschlossen ist.
7. Öffne den abgeschlossenen Workflow.
8. Scrolle zu **Artifacts**.
9. Lade **QuestDay-debug-APK** herunter.
10. ZIP entpacken und `app-debug.apk` öffnen.
11. Android fragt eventuell nach der Erlaubnis, Apps aus dieser Quelle zu installieren. Erlaube sie nur für die von dir verwendete vertrauenswürdige Quelle und installiere danach QuestDay.

## Hinweis

Das ist ein Debug-Build zum Testen auf deinem eigenen Handy. Für eine öffentliche Veröffentlichung im Google Play Store brauchen wir später einen signierten Release-Build.
