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


https://envoy.local/production.json
- Description: Production statistics and measurements
- Format: JSON
- Example: [production.json](./output_examples/envoy_production.json)


https://envoy.local/production.json?details=1
- Description: Same as production.json, but with more detail
- Format: JSON
- Example: [production.json?details=1](./output_examples/envoy_production_with_details.json)



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

