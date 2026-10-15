# Компьютерные сети

Этот репозиторий заменяет тетрадь: здесь собраны конспекты занятий, домашние работы и материалы по предмету **«Компьютерные сети»**.

## Оглавление

| Занятие |                                             Конспект                                              |                                 Домашняя работа                                  |
| :-----: | :-----------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------: |
|    1    |                                                 —                                                 |             [Создать сеть аудитории](lesson_01/hw/Create_network.md)             |
|    2    |                   [Коммутация Ethernet](lesson_02/class/Ethernet_switching.md)                    |                      [Wireshark](lesson_02/hw/Wireshark.md)                      |
|    3    |                                                 —                                                 |              [Схема MAC-адреса](lesson_03/hw/MAC_address_scheme.md)              |
|    4    |                                                 —                                                 |            [Cisco Packet Tracer](lesson_04/hw/Cisco_Packet_Tracer.md)            |
|    5    |                       [IPv4: адресация и подсети](lesson_05/class/ipv4.md)                        | [Cisco Packet Tracer и распределение адресов по подсетям](lesson_05/hw/hw_05.md) |
|    6    |                      [Расчёт IP-сетей и подсетей](lesson_06/class/class.md)                       |           [Создание сети Cisco](lesson_06/hw/Cisco-Network-create.md)            |
|    7    |                                                 —                                                 |           [Расчёт масок и диапазонов подсетей](lesson_07/hw/hw_07.md)            |
|    8    |        [Маршрутизация в сети Интернет](<lesson_08/class/Маршрутизация в сети Интернет.md>)        |               [Схемы в Cisco Packet Tracer](lesson_08/hw/hw_08.md)               |
|    9    | [Маршрутизация в информационных сетях](<lesson_09/class/Маршрутизация в информационных сетях.md>) |                                         —                                        |
|   10    |                 [Протокол DHCP](<lesson_10/class/Протокол DHCP.md>)                 |                                         —                                        |
|   11    | [Транспортный уровень TCP и UDP](<lesson_11/class/Транспортный уровень TCP и UDP.md>) | [Краткая выжимка по TCP и UDP](lesson_11/hw/hw.md) |
|   12    | [Технология NAT](<lesson_12/class/Технология NAT.md>) | [Настройка NAT в Cisco Packet Tracer](lesson_12/hw/hw.md) |
|   13    | [Система доменных имён DNS](<lesson_13/class/Система доменных имён DNS.md>) | [Настройка DNS в Cisco Packet Tracer](lesson_13/hw/hw.md) |
|   14    | — | [TCP и UDP в Wireshark](lesson_14/hw/hw.md) |

### Проверочные работы

1. [Проверочная работа №1](control-test/Проверочная_№1.md)

## Структура

```text
├── .github/
│   ├── assets/
│   │   ├── control-test/
│   │   │   └── image1.png
│   │   ├── lesson_01/
│   │   │   └── Дз (1).png
│   │   ├── lesson_02/
│   │   │   ├── duplex.png
│   │   │   ├── encapsulation.png
│   │   │   ├── ethernet-frame.png
│   │   │   ├── forwarding-methods.png
│   │   │   ├── frame-filtering.png
│   │   │   ├── mac-address.png
│   │   │   └── Wireshark.png
│   │   ├── lesson_03/
│   │   │   ├── scheme_mac.png
│   │   │   └── scheme_switch.png
│   │   ├── lesson_04/
│   │   │   └── Cisco_Packet_Tracer_bloc.png
│   │   ├── lesson_05/
│   │   │   ├── Cisco-Packet-Tracer.png
│   │   │   ├── ipv4-address-and-subnet-mask.png
│   │   │   ├── network-address-logical-and.png
│   │   │   ├── network-subnet-segmentation.png
│   │   │   ├── private-addresses-and-nat.png
│   │   │   └── vlsm-subnets-and-wan-links.png
│   │   ├── lesson_06/
│   │   │   ├── Cisco-Network-create.png
│   │   │   ├── Cisco-Network-ping.png
│   │   │   └── Cisco-Network-simulator-ping.png
│   │   ├── lesson_08/
│   │   │   ├── bgp-between-autonomous-systems.png
│   │   │   ├── distance-vector-vs-link-state.png
│   │   │   ├── ip-fragmentation.png
│   │   │   ├── ipv4-packet-format.png
│   │   │   ├── ospf-areas-and-backbone.png
│   │   │   ├── ospf-link-metrics.png
│   │   │   ├── packet-forwarding-between-networks.png
│   │   │   ├── rip-network-example.png
│   │   │   ├── rip-routing-loop.png
│   │   │   ├── routing-path-options.png
│   │   │   ├── Сеть-для-настройки RIP.png
│   │   │   └── Статическая-маршрутизация.png
│   │   ├── lesson_09/
│   │   │   ├── bgp-autonomous-systems.png
│   │   │   ├── bgp-open-packet.png
│   │   │   ├── bgp-router3-routing-table.png
│   │   │   ├── bgp-update-packet.png
│   │   │   ├── dijkstra-shortest-paths.gif
│   │   │   ├── ospf-ip-and-update-headers.png
│   │   │   ├── ospf-lsa-packet.png
│   │   │   ├── ospf-router3-routing-table.png
│   │   │   ├── packet-forwarding-principle.png
│   │   │   ├── protocol-comparison-topology.png
│   │   │   ├── rip-hub-topology.png
│   │   │   ├── rip-packet-format.png
│   │   │   ├── rip-router1-config.png
│   │   │   ├── rip-router3-routing-table.png
│   │   │   ├── route-selection-algorithm.png
│   │   │   ├── static-route-router0-config.png
│   │   │   ├── static-route-router1-config.png
│   │   │   └── static-routing-topology.png
│   │   ├── lesson_10/
│   │   │   ├── dhcp-server-relay-topology.png
│   │   │   └── rarp-request-response.png
│   │   ├── lesson_11/
│   │   │   ├── tcp-congestion-control.png
│   │   │   ├── tcp-connection-close.jpg
│   │   │   ├── tcp-header.png
│   │   │   ├── tcp-receiver-and-congestion-windows.png
│   │   │   ├── tcp-sliding-window.png
│   │   │   ├── tcp-three-way-handshake.jpg
│   │   │   ├── transport-port-addressing.jpg
│   │   │   ├── transport-segmentation.jpg
│   │   │   └── udp-header.png
│   │   ├── lesson_12/
│   │   │   ├── nat-addresses.png
│   │   │   ├── network.png
│   │   │   ├── pat.png
│   │   │   └── static-nat.png
│   │   ├── lesson_13/
│   │   │   ├── dns-browser-error.jpg
│   │   │   ├── dns-domain-levels.png
│   │   │   ├── dns-name-resolution.png
│   │   │   ├── dns-network.png
│   │   │   ├── dns-server-interaction.png
│   │   │   └── dns-soa-example.png
│   │   └── lesson_14/
│   │       ├── tcp-flags.ack.png
│   │       ├── tcp-flags.syn.png
│   │       └── udp.png
│   └── pkt/
│       ├── .gitkeep
│       ├── lesson_06/
│       │   └── Cisco-Network-1.pkt
│       ├── lesson_08/
│       │   ├── Сеть-для-настройки-RIP.pkt
│       │   └── Статическая-маршрутизация.pkt
│       ├── lesson_12/
│       │   └── nat-hw.pkt
│       └── lesson_13/
│           └── dns-hw.pkt
├── control-test/
│   └── Проверочная_№1.md
├── lesson_01/
│   ├── class/
│   │   └── .gitkeep
│   └── hw/
│       └── Create_network.md
├── lesson_02/
│   ├── class/
│   │   └── Ethernet_switching.md
│   └── hw/
│       └── Wireshark.md
├── lesson_03/
│   ├── class/
│   │   └── .gitkeep
│   └── hw/
│       └── MAC_address_scheme.md
├── lesson_04/
│   ├── class/
│   │   └── .gitkeep
│   └── hw/
│       └── Cisco_Packet_Tracer.md
├── lesson_05/
│   ├── class/
│   │   └── ipv4.md
│   └── hw/
│       └── hw_05.md
├── lesson_06/
│   ├── class/
│   │   └── class.md
│   └── hw/
│       └── Cisco-Network-create.md
├── lesson_07/
│   ├── class/
│   │   └── .gitkeep
│   └── hw/
│       └── hw_07.md
├── lesson_08/
│   ├── class/
│   │   └── Маршрутизация в сети Интернет.md
│   └── hw/
│       └── hw_08.md
├── lesson_09/
│   └── class/
│       └── Маршрутизация в информационных сетях.md
├── lesson_10/
│   └── class/
│       └── Протокол DHCP.md
├── lesson_11/
│   ├── class/
│   │   └── Транспортный уровень TCP и UDP.md
│   └── hw/
│       └── hw.md
├── lesson_12/
│   ├── class/
│   │   └── Технология NAT.md
│   └── hw/
│       └── hw.md
├── lesson_13/
│   ├── class/
│   │   └── Система доменных имён DNS.md
│   └── hw/
│       └── hw.md
├── lesson_14/
│   ├── class/
│   │   └── .gitkeep
│   └── hw/
│       └── hw.md
├── .gitignore
├── LICENSE.md
└── README.md
```
