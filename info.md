# homeassistant-kostalplenticore

Home Assistant Component for Kostal Plenticore 

<a href="https://www.buymeacoffee.com/ittv" target="_blank"><img height="41px" width="167px" src="https://cdn.buymeacoffee.com/buttons/default-blue.png" alt="Buy Me A Coffee"></a>

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)

### Installation

Copy this folder to `<config_dir>/custom_components/kostal_plenticore/`.

### HACS
Search for Kostal Plenticore

Add the following to your `configuration.yaml` file:

```yaml
# Example configuration.yaml entry
sensor:
    - platform: kostal_plenticore
      host: <IP>
      password: <Password>
      monitored_conditions:
        - BatteryPercent
        - BatteryCycles
        - HomeGridPower
        - HomeOwnPower
        - HomePVPower
        - HomeBatteryPower
        - PVPower
        - AutarkyDay
        - AutarkyMonth
        - AutarkyTotal
        - AutarkyYear
        - CO2SavingDay
        - CO2SavingMonth
        - CO2SavingTotal
        - CO2SavingYear
```
