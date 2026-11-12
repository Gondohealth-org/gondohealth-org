# Gondohealth

[English](https://github.com/Gondohealth-org) | **Português**

🚁 **Entrega de medicamentos por drone para comunidades remotas em África, em horas e não em dias.**

Drones de carga autónomos que transportam vacinas, medicamentos, sangue e testes de diagnóstico para clínicas
rurais, postos de saúde e regiões afetadas por conflitos onde as estradas não chegam em segurança. Já ultrapassámos
a fase inicial, com aeronaves e sistemas de carga em desenvolvimento e testes a partir de Quelimane, Zambézia, Moçambique.

- 🌍 **Website** → [gondohealth.com](https://gondohealth.com)
- 💼 **Vagas** → [gondohealth.com/careers](https://gondohealth.com/careers)
- 🤝 **Parcerias** → [gondohealth.com/contact](https://gondohealth.com/contact)

## Código aberto

Pequenos utilitários sem dependências para logística com drones, em
[**gondohealth-utils**](https://github.com/Gondohealth-org/gondohealth-utils/blob/main/README.pt.md):

| ficheiro | o que é |
|---|---|
| [`geo.ts`](https://github.com/Gondohealth-org/gondohealth-utils/blob/main/geo.ts) | Distância, rumo e verificação de zonas de exclusão aérea entre unidades de saúde |
| [`flight-estimate.ts`](https://github.com/Gondohealth-org/gondohealth-utils/blob/main/flight-estimate.ts) | Tempo de voo e margem de bateria corrigidos pelo vento |
| [`cold-chain.ts`](https://github.com/Gondohealth-org/gondohealth-utils/blob/main/cold-chain.ts) | Desvios de temperatura nos registos dos sensores da carga |
| [`qgc-plan.ts`](https://github.com/Gondohealth-org/gondohealth-utils/blob/main/qgc-plan.ts) | Missões `.plan` do QGroundControl para PX4 / ArduPilot |
| [`contingency.ts`](https://github.com/Gondohealth-org/gondohealth-utils/blob/main/contingency.ts) | Ponto de não retorno, desvios e rotas através de estações de carregamento ou de troca de baterias |
| [`solar.ts`](https://github.com/Gondohealth-org/gondohealth-utils/blob/main/solar.ts) | Dimensionamento de estações solares de carregamento e de troca de baterias |
| [`station-panel.qml`](https://github.com/Gondohealth-org/gondohealth-utils/blob/main/station-panel.qml) | Painel tátil Qt / QML para estações de troca de baterias (sistemas embarcados) |
| [`sail_track.cpp`](https://github.com/Gondohealth-org/gondohealth-utils/blob/main/sail_track.cpp) | Analisador de regatas à vela: VMG, perdas nas viragens e polares a partir de trilhos GPS |

## Tecnologia aberta que estamos a explorar

| projeto | para quê |
|---|---|
| [PX4](https://github.com/PX4/PX4-Autopilot) / [ArduPilot](https://github.com/ArduPilot/ardupilot) | Controlo de voo para aeronaves de carga VTOL |
| [MAVLink](https://github.com/mavlink/mavlink) / [MAVSDK](https://github.com/mavlink/MAVSDK) | Comunicação drone ↔ estação terrestre e automação de missões |
| [QGroundControl](https://github.com/mavlink/qgroundcontrol) | Estação terrestre para planear e acompanhar voos |
| [Gazebo](https://github.com/gazebosim) | Simulação de rotas e largadas de carga antes de voar |
| [OpenDroneID](https://github.com/opendroneid) | Remote ID para transparência no espaço aéreo |
| [DHIS2](https://github.com/dhis2) | Ligação das entregas aos sistemas nacionais de informação de saúde |

*Gondo — A Águia.*
