# Drittkomponenten

- Debian und Arch Linux beziehen die dynamischen Qt-Laufzeitbibliotheken über den jeweiligen Paketmanager. Die verwendeten Qt-Module sind unter LGPLv3/GPLv3 bzw. den jeweiligen Qt-Lizenzbedingungen erhältlich. Debian-Pakete liefern Lizenztexte unter `/usr/share/doc/<paket>/copyright`.
- Android-Entwicklungsbuilds enthalten die dynamischen Qt-6.8.2-Bibliotheken und SVG-Plugins aus den offiziellen Qt-Binärarchiven. [Qt-6.8.2-Quellen](https://download.qt.io/archive/qt/6.8/6.8.2/single/)
- Die Windows- und macOS-ZIPs enthalten die dynamischen Qt-6.8.2-Bibliotheken samt den für die App benötigten QML-Modulen und Plugins. Das Windows-ZIP enthält auch die MinGW-Laufzeitbibliotheken und Lizenztexte im Ordner `Lizenzen`. [Qt-6.8.2-Quellen](https://download.qt.io/archive/qt/6.8/6.8.2/single/)
- Eigen 3.4.0: MPL-2.0; Header-Bibliothek aus Debian `libeigen3-dev`. Keine Eigen-Quelldateien wurden geändert. Lizenz-/Copyrighttext des Buildpakets liegt unter `.build-deps/root/usr/share/doc/libeigen3-dev/copyright` bzw. systemweit `/usr/share/doc/libeigen3-dev/copyright`.
- SciPy/NumPy werden ausschließlich in optionalen unabhängigen Tests verwendet und gehören nicht zu den App-Laufzeitabhängigkeiten.
- Originalarchive, Originalinstaller und CHM/PDF-Hilfe dienen als lokale fachliche Referenz und werden nicht mit dem Debian-Paket ausgeliefert. Keine Zugehörigkeit oder Unterstützung durch die TU Ilmenau wird behauptet.

Vor einer öffentlichen Veröffentlichung sind Projektlizenz, Marken-/Namensfragen und Distributionspflichten abschließend festzulegen. Das lokal erzeugte Paket ist eine Entwicklungsfassung.
