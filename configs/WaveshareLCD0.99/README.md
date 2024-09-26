# GP2040 Configuration for the Waveshare RP2040 LCD 0.99

Basic pin setup for the Waveshare RP2040 LCD 0.99.

## Main Pin Mapping Configuration

| RP2040 Pin  | Action                      | GP2040 | Xinput | Switch | PS3/4/5  | Dinput | Arcade |
|-------------|-----------------------------|--------|--------|--------|----------|--------|--------|
| GPIO_PIN_26 | GpioAction::BUTTON_PRESS_B1 | B1     | A      | B      | Cross    | 2      | K1     |
| GPIO_PIN_27 | GpioAction::BUTTON_PRESS_B2 | B2     | B      | A      | Circle   | 3      | K2     |
| GPIO_PIN_28 | GpioAction::BUTTON_PRESS_B3 | B3     | X      | Y      | Square   | 1      | P1     |
| GPIO_PIN_29 | GpioAction::BUTTON_PRESS_B4 | B4     | Y      | X      | Triangle | 4      | P2     |

Note: These are the 4 GPIO pins exposed on the external connector.
