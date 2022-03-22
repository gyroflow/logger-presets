# gyroflow logger presets

A simple way to configure your Betaflight Flight Controller to a nice motion logger for gyroflow.

## How to use

![](/misc/img/logger-preset-how-to-use.png)

### Pre-requisites

- Betaflight Configurator 10.8.0 or later
- Betaflight 4.3 or later
- A flight controller with a flash memory chip or SD card

### Add gyroflow logger presets source

1. Open Betaflight Configurator
2. Click on the **Presets** tab
3. Click on the **Presets source..** button on the right corner
4. Click on **Add new source** button
5. Type our repo URL to the **URL** field
6. Type ``master`` in the **Branch** field
7. Click on **Save** button and hit **Make Active**
8. Enjoy!

## Categories
| Category | Preset | Notes |
| ----------- | ----------- | ----------- |
| Blackbox | Gyroflow minimal settings | For users who use their blackbox data from main FC |
| | Sencondary FC as Gyroflow motion logger | For users who use a sencondary FC as a motion logger |
| Filters | BMI270 | For FC with BMI270 gyroscope sensor|
| Kit | flowbox | All-in-one settings for flowbox and flowbox+flowshutter |

## Credits

The Preset system was developed by @limonspb for Betaflight 4.3.

