# Adafruit nRF52 Bootloader

This fork is intented for providing additional LED functionality for my keyboard and mouse.

## Lariska

Lariska is reverse engineered VGN F1 moba mouse with nrf52840 on the board. It uses LDO for led power supply so it should be enabled through `LDO_PIN`.

You can find ZMK config [here](https://github.com/greengrocer98/keyatura_zmk/tree/mouse_esb). It uses keyboard as dongle and mouse is connected to keyboard through [esb](https://github.com/badjeff/zmk-feature-split-esb).


https://github.com/user-attachments/assets/b8f6b0e3-1a40-4c13-8154-6c36f5f5801a


## Keyatura

[Keyatura](https://github.com/greengrocer98/keyatura) is my custom keyboard with nice!nano and three additional LEDS on the board. It uses `LED_PRIMARY_PIN`, `LED_SECONDARY_PIN` and `LED_TERTIARY_PIN`.

You can find ZMK config [here](https://github.com/greengrocer98/keyatura_zmk).


https://github.com/user-attachments/assets/515b668a-2dfb-4acc-9f14-c1512fe1c803

