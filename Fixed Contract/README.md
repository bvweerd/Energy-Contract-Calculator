# Energy contract calculator
These scripts are made to cope with the Dutch 'salderingsregeling' and tariff calculations in Home Assistant. It is specifically meant for fixed contracts, not for variable or dynamic contracts.

## Electricity meter
The balancing is done first on the high tariff (tariff 2), the rest is done on the low tariff (tariff 1).
Energy tax return is implemented fully on the electricity meter. 

return fees per kWh scale (e.g. up to 1000 kWh, up to 1250 kWh, etc.) have to be set in the template.

Use the input_booleans to choose if a kWh scale or a fee per kWh has to be used.

## Gas meter
The gas meter is the simple implementation of a cost calculations according to Dutch contracts.

# Installation
- Point the utility meters to the ones from your DSMR meter
- Set all helpers to the correct value
- Enjoy!
