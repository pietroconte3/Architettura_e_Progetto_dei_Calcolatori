# Architettura_e_Progetto_dei_Calcolatori
Sistema domotico smart controllabile via Wi-Fi con ESP8266 e STM32, per la gestione remota di luci, porte, allarme e display OLED, con focus su accessibilità e automazione domestica.

# Smart Home IoT System con ESP8266 e STM32F3

Questo progetto è stato sviluppato per il corso di *Architettura e Progetto dei Calcolatori* e ha come obiettivo la realizzazione di un sistema domotico low-cost, accessibile da remoto tramite una rete Wi-Fi, con microcontrollori ESP8266 e STM32.

## Obiettivo

Fornire una soluzione smart home semplice ed efficace, che permetta di controllare dispositivi (luci, porta, allarme, schermo OLED) tramite un'interfaccia web da smartphone o PC

## Componenti

- **ESP8266** – gestisce il Wi-Fi e l'interfaccia web
- **STM32F3DISCOVERY** – controlla i dispositivi collegati
- **LED RGB** – simula l’illuminazione domestica
- **Servo SG90** – gestisce l'apertura della porta
- **Buzzer e sensore ultrasuoni HC-SR04** – attivazione allarmi
- **Display OLED SSD1306** – visualizzazione messaggi
- **UART / I2C** – per la comunicazione tra i moduli

## Funzionalità Implementate

- Accensione/spegnimento luce tramite LED RGB
- Apertura/chiusura porta con servo
- Attivazione schermo OLED con messaggio dinamico
- Attivazione sensore di prossimità con allarme sonoro
- Visualizzazione pagine HTML e PNG da ESP8266 via browser

## Tecnologie e Librerie

- `ESP8266WiFi.h`, `ESP8266WebServer.h`, `FS.h`
- `HAL_UART`, `PWM`, `CubeMX` (per la configurazione STM32)
- OLED display driver SSD1306
- IDE: Arduino IDE + STM32CubeIDE

Professore: Nicola Mazzocca  
Università Federico II – A.A. 2024-2025
