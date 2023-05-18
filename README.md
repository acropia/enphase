Enphase Solar / PV monitoring
=============================



## Endpoints
https://envoy.local/home#auth

- Login with Enlighten Owner account: basic interface
- Login with Enlighten Installer account: advanced interface


https://envoy.local/home.json
- Description: 
- Format: JSON
- Example: [home.json](./output_examples/envoy_home.json)


https://envoy.local/info.xml
- Description: Software versions of the firmware 
- Format: XML
- Example: [info.xml](./output_examples/envoy_info.xml)

https://envoy.local/inventory.json
- Description: Inventory of devices (inverters)
- Format: JSON
- Example: [inventory.json](./output_examples/envoy_inventory.json)


https://envoy.local/production.json
- Description: Production statistics and measurements
- Format: JSON
- Example: [production.json](./output_examples/envoy_production.json)


https://envoy.local/production.json?details=1
- Description: Same as production.json, but with more detail
- Format: JSON
- Example: [production.json?details=1](./output_examples/envoy_production_with_details.json)

https://envoy.local/prov
- Description: Provisioned devices
- Format: JSON
- Example: [prov](./output_examples/envoy_prov)

https://envoy.local/event.json
- Description: Table of Enphase events (Power on, Reports, etc.)
- Format: Graphical web page


https://envoy.local/admin/home?locale=en
- Description: Admin panel
- Format: Graphical web page


### API v1
https://envoy.local/api/v1/consumption
- Description: Consumption summary (always zero?)
- Format: JSON
- Example: [consumption](./output_examples/api_v1_consumption)

https://envoy.local/api/v1/production
- Description: Production summary (always zero?)
- Format: JSON
- Example: [production](./output_examples/api_v1_production)

https://envoy.local/api/v1/production/inverters
- Description: Production summary per inverter
- Format: JSON
- Example: [inverters](./output_examples/api_v1_production_inverters)

### IVP
https://envoy.local/ivp/livedata/status
- Description: Status data
- Format: JSON
- Example: [status](./output_examples/ivp_livedata_status)

https://envoy.local/ivp/meters
- Description: Listing of meters (production & net-consumption)
- Format: JSON
- Example: [meters](./output_examples/ivp_meters)

https://envoy.local/ivp/meters/readings
- Description: Details readings per meter (production & net-consumption)
- Format: JSON
- Example: [readings](./output_examples/ivp_meters_readings)

https://envoy.local/ivp/meters/reports/consumption
- Description: Consumption report (detailed)
- Format: JSON
- Example: [consumption](./output_examples/ivp_meters_reports_consumption)

https://envoy.local/ivp/meters/reports/production
- Description: Production report (detailed)
- Format: JSON
- Example: [production](./output_examples/ivp_meters_reports_production)


https://envoy.local/installer/setup/home
- Auth: Enlighten Installer account
- Format: Graphical web interface
- Sections:
  - Overview:
    - Metering
    - Monitoring
    - Wireless Connection Links
    - Microinverters
    - Enpower
    - AC Batteries
    - Encharge Batteries
    - Q Relays
    - About this Envoy
    - Date & Time
    - Events
    - System
    - Connection to Enphase Support
  - Micros
    - Microinverter Production
    - Status - Comm
    - Status - Profile
    - Status - Power
  - AC Battery
  - Enpower
  - Encharge
  - Meters
  - Network

