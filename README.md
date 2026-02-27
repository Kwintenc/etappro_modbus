[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)

# home-assistant-etappro-modbus
Home assistant Custom Component for reading data from ETAPpro EV charger through modbus TCP.
Implements Inverter registers from the [ETAP Modbus TCP/IP protocol][1], which is largely based on Alfen.
# Installation
Copy contents of custom_components folder to your home-assistant config/custom_components folder or install through HACS.
After reboot of Home-Assistant, this integration can be configured through the integration setup UI

# Future Improvements
- Persist the set power budget value across HA restarts
- Update the power budget value before the ETAPpro 'valid' timer value expires and the charger drops into safe current mode

[1]: https://github.com/EV-Chargeking/etap-modbus/blob/main/README.md