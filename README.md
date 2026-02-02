Rocket Tracking System

A high-altitude tracking solution utilizing the Heltec Wireless Tracker V1.1 and Seeed Studio Wio L1 Pro.

    [!IMPORTANT]
    Amateur Radio License Required: Operation of this equipment in the USA requires a valid Amateur Radio License. 
    Regulations in other countries may vary; please check your local laws before transmitting.

🛠 Prerequisites

Ensure you have the Arduino IDE installed along with the following libraries:
Required Libraries

    U8g2

    RadioLib

    Adafruit LittleFS

    TinyGPSPlus

    Adafruit GFX

    Adafruit ST7335

Board Manager Configuration

    Open Arduino IDE Preferences and add these URLs to Additional Boards Manager URLs:

        https://files.seeedstudio.com/arduino/package_seeeduino_boards_index.json

        https://github.com/Heltec-Aaron-Lee/WiFi_Kit_series/releases/download/0.0.9/package_heltec_esp32_index.json

    Install the following via the Board Manager:

        Seeed nRF52 Boards

        Silicon Labs

        Seeed nRF52 mbed-enabled Boards

        Heltec ESP32 Series Dev-Boards

        esp32

        Arduino nRF52 Boards

🚀 Setup & Usage
1. Identity Configuration

To comply with radio regulations, you must identify your transmission.

    Search the code for the comment: // Insert your callsign, then delete this comment

    Replace it with your registered Callsign.

    Delete the comment line.

2. Frequency Hopping

The system is not configured for frequency hopping by default. If you intend to use a frequency hopping, manual code modifications are required.
