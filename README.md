Successfully designed and implemented a temperature-controlled fan system using the ATmega32 microcontroller. Here's a sneak peek into the project's key features:

- 🌡️ The fan turns on or off automatically based on temperature.
- ⚙️ Utilizes the LM35 temperature sensor for continuous temperature measurement.
- 🖥️ Displays temperature data on an LCD.
- 🌬️ Fan speed is dynamically adjusted based on the temperature:
 - 🌬️ < 30°C: Fan is turned off.
 - 🌬️ ≥ 30°C: Fan operates at 25% speed.
 - 🌬️ ≥ 60°C: Fan operates at 50% speed.
 - 🌬️ ≥ 90°C: Fan operates at 75% speed.
 - 🌬️ ≥ 120°C: Fan operates at 100% speed.
- 📦 Utilizes a layered architecture model for robust design.
 - HAL Layer: LCD, LM35, and DC motor.
 - MCAL Layer: GPIO, ADC, and Timer0 PWM.
