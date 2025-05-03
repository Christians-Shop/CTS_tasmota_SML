# WiFi IR Smart Meter Interface – Moderne Schnittstelle für Smart-Home-Systeme - Angepasste Tasmota Firmware

![Christians Technikshop](https://www.christians-shop.de/bilder/intern/shoplogo/Shop_logo_V4.png)

Dieses Repository enthält eine speziell angepasste Version der Tasmota Firmware für das Produkt "Christians Technikshop WiFi IR Smart Meter Interface". Diese Firmware-Version integriert das SML-Protokoll, um die nahtlose Kommunikation mit Ihrem Smart Meter zu ermöglichen. Mit dieser Firmware können Sie Ihr Smart Meter über WLAN steuern und überwachen.

## Produktinformationen

- **Produktname**: WiFi IR Smart Meter Interface – Moderne Schnittstelle für Smart-Home-Systeme
- **Produktlink**:  [WiFi Smartmeter Interface (ESP8266)](https://www.christians-shop.de/wifi-ir-smart-meter-interface-auswahl), [WiFi Smartmeter Interface (ESP32C3)](https://www.christians-shop.de/)
- **Firmware-Version**: Entwicklungs Branch
- **Basierend auf Tasmota-Version**: [Tasmota v14.5.0 Ruth](https://github.com/arendst/Tasmota/releases/tag/v14.5.0)
- **Hardware-Basis**:   ESP8266EX, ESP32C3

## Anpassungen und Funktionen

- **SML-Erweiterung**: Wir haben das SML-Protokoll in die Firmware integriert `user_config_override.h`, um die Kommunikation mit Ihrem Smart Meter zu ermöglichen.

- **Update-Server**: In der Datei `platformio_tasmota_env.ini` und `platformio_tasmota_env32.ini` haben wir unseren Update-Server hinzugefügt, um Ihnen einfache Produktaktualisierungen zu ermöglichen.

- **User-Modul**: Die `my_user_config.h` wurde angepasst, um ein benutzerdefiniertes Modul zu integrieren, das speziell auf die Anforderungen unseres Produkts zugeschnitten ist.

- **GUI-Anpassungen**: Wir haben Änderungen an den Namensparametern vorgenommen, damit die Software in der Geräte-GUI korrekt erkannt wird und eine benutzerfreundliche Erfahrung gewährleistet ist.

## Installation und Verwendung

Um diese Firmware auf Ihrem Christians Technikshop WiFi IR Smart Meter Interface zu verwenden, folgen Sie bitte den Anweisungen in der offiziellen Tasmota-Dokumentation. Stellen Sie sicher, dass Sie die richtige Firmware-Version für Ihr Gerät auswählen.

## Lizenz

Diese angepasste Tasmota Firmware unterliegt den gleichen Lizenzbedingungen wie die ursprüngliche Tasmota-Firmware. Weitere Informationen finden Sie in der [Tasmota-Lizenz](https://github.com/arendst/Tasmota/blob/development/LICENSE.md).

## Unterstützung und Kontakt

Wenn Sie Fragen oder Probleme mit dieser Firmware haben, können Sie sich gerne an [Christians Technikshop](https://www.christians-shop.de/) wenden, um Unterstützung zu erhalten. Wir freuen uns darauf, Ihnen zu helfen und Ihr Smart Meter Interface-Erlebnis zu verbessern.

**Hinweis:** Dieses Repository dient ausschließlich zu Referenzzwecken und enthält möglicherweise Informationen und Funktionen, die sich seit dem letzten Update geändert haben. Es wird empfohlen, die offizielle Tasmota-Dokumentation für die aktuellsten Informationen zu konsultieren.