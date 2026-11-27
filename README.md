# PhysPract Native 0.8.0

Testversion zur physikalischen Messwertauswertung.

| System | Download | Teststand |
| --- | --- | --- |
| Windows 10/11, x64 | [Windows-ZIP laden](physpract-native_0.8.0_windows_x86_64.zip) | Unter Wine geprüft, auf Windows ungetestet |
| macOS, Apple Silicon (M-Chip) | [Mac-ZIP laden](physpract-native_0.8.0_macos_arm64.zip) | Automatisch geprüft, im Alltag ungetestet |
| macOS, Intel | [Mac-ZIP laden](physpract-native_0.8.0_macos_x86_64.zip) | Automatisch geprüft, im Alltag ungetestet |
| Debian 13, 64-Bit Intel/AMD | [.deb laden](physpract-native_0.8.0_amd64.deb) | Unter Debian 13 getestet |
| Arch Linux, 64-Bit Intel/AMD | [.pkg.tar.zst laden](physpract-native-0.8.0-1-x86_64.pkg.tar.zst) | Auf Arch ungetestet |
| Android 9 oder neuer, ARM64 (die meisten Smartphones und Tablets) | [ARM64-APK laden](physpract-native_0.8.0_arm64-v8a.apk) | Entwicklungsbuild |
| Android 9 oder neuer, x86_64 (z. B. PC-Emulator) | [x86_64-APK laden](physpract-native_0.8.0_x86_64.apk) | Entwicklungsbuild |

Auf GitHub die passende Datei öffnen und **Download raw file** wählen. Für iPhone und iPad gibt es vorerst keinen Download.

## Windows

ZIP vollständig entpacken und im entpackten Ordner `physpract-native.exe` öffnen. Die DLLs und Unterordner bleiben neben der EXE. Qt ist im ZIP enthalten. Die Testversion ist unsigniert.

## macOS

Das ZIP für deinen Mac laden und entpacken. **PhysPract Native.app** in **Programme** ziehen und öffnen. Qt ist in der App enthalten. Die Testversion ist ad hoc signiert und kann beim ersten Öffnen eine Bestätigung in **Systemeinstellungen → Datenschutz & Sicherheit** erfordern. [Apple-Hilfe zum Öffnen der App](https://support.apple.com/de-de/102445)

## Debian 13

Den folgenden Befehl im Downloadordner ausführen.

```bash
sudo apt install ./physpract-native_0.8.0_amd64.deb
```

APT installiert die nötigen Qt-Abhängigkeiten. Danach **PhysPract Native** im Anwendungsmenü öffnen oder im Terminal `physpract-native` ausführen.

## Arch Linux

Auf einem aktuellen Arch-System den folgenden Befehl im Downloadordner ausführen.

```bash
sudo pacman -U ./physpract-native-0.8.0-1-x86_64.pkg.tar.zst
```

Pacman installiert die nötigen Qt-Abhängigkeiten. Danach **PhysPract Native** im Anwendungsmenü öffnen oder `physpract-native` ausführen.

## Android

1. Die passende APK auf das Gerät laden und in der Dateien-App öffnen.
2. Wenn Android nachfragt, **Aus dieser Quelle zulassen** für die verwendete App aktivieren. Installation bestätigen und **PhysPract Native** öffnen.

Die APKs sind mit einem Entwicklungsschlüssel signiert. Eine bereits installierte Version mit anderer Signatur lässt sich damit nicht aktualisieren. In diesem Fall zuerst eigene Dateien und Projekte sichern, dann die alte App deinstallieren.

## Feedback

Fehler oder Wünsche gern als GitHub-Issue melden. Bei Fehlern helfen Betriebssystem, App-Version, Schritte zum Nachstellen und die genaue Fehlermeldung.

[SHA-256-Prüfsummen](SHA256SUMS) · [Drittkomponenten](THIRD_PARTY.md)

## Nutzungshinweis

PhysPract Native ist eine Nachentwicklung der Software PhysPract für das Physikpraktikum der Technischen Universität Ilmenau. Diese Testversion ist ausschließlich für den internen Einsatz in diesem Physikpraktikum vorgesehen.
