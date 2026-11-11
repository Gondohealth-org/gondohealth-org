# Gondohealth

🚁 **Medical drone delivery for remote communities in Africa, in hours, not days.**

Autonomous cargo drones carrying vaccines, medicines, blood and diagnostics to rural
clinics, health posts and conflict-affected regions that roads can't safely reach. Past the early stage, with airframes and
payload systems in development and testing out of Quelimane, Zambezia, Mozambique.

- 🌍 **Website** → [gondohealth.com](https://gondohealth.com)
- 💼 **Hiring** → [gondohealth.com/careers](https://gondohealth.com/careers)
- 🤝 **Partner** → [gondohealth.com/contact](https://gondohealth.com/contact)

## Open source

Small dependency-free TypeScript utilities for drone logistics, in
[**gondohealth-utils**](https://github.com/Gondohealth-org/gondohealth-utils):

| file | what it is |
|---|---|
| [`geo.ts`](https://github.com/Gondohealth-org/gondohealth-utils/blob/main/geo.ts) | Distance, bearing and no-fly-zone checks between facilities |
| [`flight-estimate.ts`](https://github.com/Gondohealth-org/gondohealth-utils/blob/main/flight-estimate.ts) | Wind-corrected flight time and battery margin |
| [`cold-chain.ts`](https://github.com/Gondohealth-org/gondohealth-utils/blob/main/cold-chain.ts) | Temperature excursions in payload sensor logs |
| [`qgc-plan.ts`](https://github.com/Gondohealth-org/gondohealth-utils/blob/main/qgc-plan.ts) | QGroundControl `.plan` missions for PX4 / ArduPilot |

## Open tech we're exploring

| project | what for |
|---|---|
| [PX4](https://github.com/PX4/PX4-Autopilot) / [ArduPilot](https://github.com/ArduPilot/ardupilot) | Flight control for VTOL cargo airframes |
| [MAVLink](https://github.com/mavlink/mavlink) / [MAVSDK](https://github.com/mavlink/MAVSDK) | Drone ↔ ground comms and mission automation |
| [QGroundControl](https://github.com/mavlink/qgroundcontrol) | Ground station for planning and monitoring flights |
| [Gazebo](https://github.com/gazebosim) | Simulating routes and payload drops before flying |
| [OpenDroneID](https://github.com/opendroneid) | Remote ID for airspace transparency |
| [DHIS2](https://github.com/dhis2) | Linking deliveries to national health information systems |

*Gondo — The Eagle.*
