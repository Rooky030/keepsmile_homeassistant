# Keepsmile Home Assistant

Home Assistant custom integration for Keepsmile devices controlled by the Keepsmile app over Bluetooth LE.

There are some btsnoop HCI logs in the `bt_snoops` folder if you want to examine them.

## Supported Features in this integration

- On/Off
- RGB colour
- Brightness
- Fancy colour Modes (not speed)
- Automatic discovery of supported devices

## Installation

### Requirements

You need to have the bluetooth component configured and working in Home Assistant in order to use this integration.

### HACS

Add this repo to HACS as a custom repo.  Click through:

- HACS -> Integrations -> Top right menu -> Custom Repositories
- Paste the Github URL to this repo in to the Repository box
- Choose category `Integration`
- Click Add
- Restart Home Assistant
- Keepsmile devices should start to appear in your Integrations page

## Credits

Thanks to themooer1 for the OG fork:

<https://github.com/themooer1/keepsmile_homeassistant>

This integration was possible thanks to the work done by raulgbcr in this repo:

<https://github.com/raulgbcr/lednetwf_ble>

which in turn is thanks to:

<https://github.com/dave-code-ruiz/elkbledom> for most of the base code adapted to this integration.
