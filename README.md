# Christians Technikshop WiFi IR Smart Meter Interface - Angepasste Tasmota Firmware

![Christians Technikshop Logo](https://www.christians-shop.de/wp-content/uploads/2019/04/Christians-Technikshop-Logo.png)

Dieses Repository enthält eine speziell angepasste Version der Tasmota Firmware für das Produkt "Christians Technikshop WiFi IR Smart Meter Interface". Diese Firmware-Version integriert das SML-Protokoll, um die nahtlose Kommunikation mit Ihrem Smart Meter zu ermöglichen. Mit dieser Firmware können Sie Ihr Smart Meter über WLAN steuern und überwachen.

## Produktinformationen

- **Produktname**: Christians Technikshop WiFi IR Smart Meter Interface
- **Produktlink**: [Hier erhältlich](https://www.christians-shop.de/WiFi-IR-Smart-Meter-Interface_1)
- **Firmware-Version**: 1.0
- **Basierend auf Tasmota-Version**: 13.1.0.3 von Theo Arends
- **Hardware-Basis**: ESP8266EX

## Anpassungen und Funktionen

- **SML-Erweiterung**: Wir haben das SML-Protokoll in die Firmware integriert, um die Kommunikation mit Ihrem Smart Meter zu ermöglichen.

- **Update-Server**: In der Datei `platformio_tasmota_env.ini` haben wir unseren Update-Server hinzugefügt, um Ihnen einfache Produktaktualisierungen zu ermöglichen.

- **User-Modul**: Die `my_user_config.h` wurde angepasst, um ein benutzerdefiniertes Modul zu integrieren, das speziell auf die Anforderungen unseres Produkts zugeschnitten ist.

- **GUI-Anpassungen**: Wir haben Änderungen an den Namensparametern vorgenommen, damit die Software in der Geräte-GUI korrekt erkannt wird und eine benutzerfreundliche Erfahrung gewährleistet ist.

## Installation und Verwendung

Um diese Firmware auf Ihrem Christians Technikshop WiFi IR Smart Meter Interface zu verwenden, folgen Sie bitte den Anweisungen in der offiziellen Tasmota-Dokumentation. Stellen Sie sicher, dass Sie die richtige Firmware-Version für Ihr Gerät auswählen.

## Lizenz

Diese angepasste Tasmota Firmware unterliegt den gleichen Lizenzbedingungen wie die ursprüngliche Tasmota-Firmware. Weitere Informationen finden Sie in der [Tasmota-Lizenz](https://github.com/arendst/Tasmota/blob/development/LICENSE.md).

## Unterstützung und Kontakt

Wenn Sie Fragen oder Probleme mit dieser Firmware haben, können Sie sich gerne an [Christians Technikshop](https://www.christians-shop.de/) wenden, um Unterstützung zu erhalten. Wir freuen uns darauf, Ihnen zu helfen und Ihr Smart Meter Interface-Erlebnis zu verbessern.

**Hinweis:** Dieses Repository dient ausschließlich zu Referenzzwecken und enthält möglicherweise Informationen und Funktionen, die sich seit dem letzten Update geändert haben. Es wird empfohlen, die offizielle Tasmota-Dokumentation für die aktuellsten Informationen zu konsultieren.
