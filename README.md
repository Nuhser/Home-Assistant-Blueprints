# Home Assistant Blueprints

A collection of automation blueprints for [Home Assistant](https://www.home-assistant.io/).

## Blueprints

### IKEA BILRESA Dual Button Light Controls

Controls all lights in the area assigned to an IKEA BILRESA Dual Button (connected via Matter over Thread). Supports turning lights on and off, cycling through configured lighting scenes on repeated presses, brightening/dimming while holding the buttons, custom double-press actions and excluding specific lights.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FNuhser%2FHome-Assistant-Blueprints%2Fblob%2Fmaster%2Fikea_bilresa_dual_button_light_control.yaml)

### Philips Hue Dimmer Switch (Gen 1) Light Controls

Controlls all lights in the area assigned to a Philips Hue Dimmer Switch (Gen 1) (connected via Zigbee2MQTT). Supports turning lights on and off, cycling through configured lighting scenes on repeated presses, brightening/dimming while holding the buttons and exclude specific lights.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FNuhser%2FHome-Assistant-Blueprints%2Fblob%2Fmaster%2Fphilips_hue_dimmer_switch_gen1_light_control.yaml)

### Motion Sensor Light Control

Controlls all lights in an area based on a motion sensor placed in the same area. Supports tunring on and off the lights, using lighting scenes and more (see blueprint description).

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2FNuhser%2FHome-Assistant-Blueprints%2Fblob%2Fmaster%2Fmotion_sensor_light_control.yaml)

## Manual Installation

If you prefer not to use the import button above, you can add any blueprint manually:

1. In Home Assistant, go to **Settings** → **Automations & scenes** → **Blueprints**.
2. Click **Import Blueprint** in the bottom right corner.
3. Paste the URL to the blueprint file on GitHub (for example, `https://github.com/Nuhser/Home-Assistant-Blueprints/blob/master/ikea_bilresa_dual_button_light_control.yaml`) and click **Preview**, then **Import Blueprint**.

Alternatively, download the `.yaml` file and place it directly into your Home Assistant `config/blueprints/automation/` directory, then reload automations.
