# Leistungsportal Android

Native Android-App für Android 8 oder neuer. Beim ersten Start wird die Portaladresse eingegeben. Unterstützt HTTPS-Domains und HTTP-Adressen innerhalb eines privaten VPN. Kamera- und Mehrfachauswahl werden an das Portal weitergereicht.

## APK bauen

Projekt in Android Studio öffnen und **Build → Build APK(s)** wählen. Alternativ das Projekt in ein privates GitHub-Repository übertragen und den enthaltenen Workflow **Android APK** starten. Die erzeugte `app-debug.apk` kann direkt installiert werden; dafür muss „Unbekannte Apps installieren“ für Browser oder Dateimanager erlaubt sein.

## Sicherheit

HTTP nur innerhalb eines vertrauenswürdigen VPN verwenden. Für Zugriffe über das Internet ausschließlich HTTPS nutzen. Die App ignoriert keine Zertifikatsfehler. Die Portaladresse lässt sich über das Zahnrad ändern.
