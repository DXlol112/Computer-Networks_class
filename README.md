# Компьютерные сети

Этот репозиторий заменяет тетрадь: здесь собраны конспекты занятий, домашние работы и материалы по предмету **«Компьютерные сети»**.

## Оглавление

| Занятие | Конспект | Домашняя работа |
| :---: | :---: | :---: |
| 1 | — | [Создать сеть аудитории](lesson_01/hw/hw.md) |
| 2 | [Коммутация Ethernet](lesson_02/class/class.md) | [Wireshark](lesson_02/hw/hw.md) |
| 3 | — | [Схема MAC-адреса](lesson_03/hw/hw.md) |
| 4 | — | [Cisco Packet Tracer](lesson_04/hw/hw.md) |
| 5 | [IPv4: адресация и подсети](lesson_05/class/class.md) | [Cisco Packet Tracer и распределение адресов по подсетям](lesson_05/hw/hw.md) |
| 6 | [Расчёт IP-сетей и подсетей](lesson_06/class/class.md) | [Создание сети Cisco](lesson_06/hw/hw.md) |
| 7 | — | [Расчёт масок и диапазонов подсетей](lesson_07/hw/hw.md) |
| 8 | [Маршрутизация в сети Интернет](lesson_08/class/class.md) | [Схемы в Cisco Packet Tracer](lesson_08/hw/hw.md) |
| 9 | [Маршрутизация в информационных сетях](lesson_09/class/class.md) | — |
| 10 | [Протокол DHCP](lesson_10/class/class.md) | — |
| 11 | [Транспортный уровень TCP и UDP](lesson_11/class/class.md) | [Краткая выжимка по TCP и UDP](lesson_11/hw/hw.md) |
| 12 | [Технология NAT](lesson_12/class/class.md) | [Настройка NAT в Cisco Packet Tracer](lesson_12/hw/hw.md) |
| 13 | [Система доменных имён DNS](lesson_13/class/class.md) | [Настройка DNS в Cisco Packet Tracer](lesson_13/hw/hw.md) |
| 14 | — | [TCP и UDP в Wireshark](lesson_14/hw/hw.md) |
| 15 | — | [HTTP и HTTPS: разбор и составление запросов](lesson_15/hw/hw.md) |

### Проверочные работы

1. [Проверочная работа №1](control-test/test_01.md)
2. [Финальная работа, билет № 10](control-test/final-test.md)

## Структура

Конспекты и домашние работы находятся в `lesson_XX/class/class.md` и `lesson_XX/hw/hw.md`. Изображения хранятся в `assets/lesson_XX/images/`, файлы Cisco Packet Tracer — в `assets/lesson_XX/pkt/`. В пустых папках оставлен `.gitkeep`.

```text
.
├── assets/
│   ├── control-test/
│   │   └── images/
│   │       └── image1.png
│   ├── final-test/
│   │   ├── images/
│   │   │   ├── cheme-http-https.png
│   │   │   ├── mac-address-table.png
│   │   │   └── show-ip-arp.png
│   │   └── pkt/
│   │       └── 10_HTTP_HTTPS.pkt
│   ├── lesson_01/
│   │   └── images/
│   │       └── Дз (1).png
│   ├── lesson_02/
│   │   └── images/
│   │       ├── duplex.png
│   │       ├── encapsulation.png
│   │       ├── ethernet-frame.png
│   │       ├── forwarding-methods.png
│   │       ├── frame-filtering.png
│   │       ├── mac-address.png
│   │       └── Wireshark.png
│   ├── lesson_03/
│   │   └── images/
│   │       ├── scheme_mac.png
│   │       └── scheme_switch.png
│   ├── lesson_04/
│   │   └── images/
│   │       └── Cisco_Packet_Tracer_bloc.png
│   ├── lesson_05/
│   │   └── images/
│   │       ├── Cisco-Packet-Tracer.png
│   │       ├── ipv4-address-and-subnet-mask.png
│   │       ├── network-address-logical-and.png
│   │       ├── network-subnet-segmentation.png
│   │       ├── private-addresses-and-nat.png
│   │       └── vlsm-subnets-and-wan-links.png
│   ├── lesson_06/
│   │   ├── images/
│   │   │   ├── Cisco-Network-create.png
│   │   │   ├── Cisco-Network-ping.png
│   │   │   └── Cisco-Network-simulator-ping.png
│   │   └── pkt/
│   │       └── Cisco-Network-1.pkt
│   ├── lesson_08/
│   │   ├── images/
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
│   │   └── pkt/
│   │       ├── Сеть-для-настройки-RIP.pkt
│   │       └── Статическая-маршрутизация.pkt
│   ├── lesson_09/
│   │   └── images/
│   │       ├── bgp-autonomous-systems.png
│   │       ├── bgp-open-packet.png
│   │       ├── bgp-router3-routing-table.png
│   │       ├── bgp-update-packet.png
│   │       ├── dijkstra-shortest-paths.gif
│   │       ├── ospf-ip-and-update-headers.png
│   │       ├── ospf-lsa-packet.png
│   │       ├── ospf-router3-routing-table.png
│   │       ├── packet-forwarding-principle.png
│   │       ├── protocol-comparison-topology.png
│   │       ├── rip-hub-topology.png
│   │       ├── rip-packet-format.png
│   │       ├── rip-router1-config.png
│   │       ├── rip-router3-routing-table.png
│   │       ├── route-selection-algorithm.png
│   │       ├── static-route-router0-config.png
│   │       ├── static-route-router1-config.png
│   │       └── static-routing-topology.png
│   ├── lesson_10/
│   │   └── images/
│   │       ├── dhcp-server-relay-topology.png
│   │       └── rarp-request-response.png
│   ├── lesson_11/
│   │   └── images/
│   │       ├── tcp-congestion-control.png
│   │       ├── tcp-connection-close.jpg
│   │       ├── tcp-header.png
│   │       ├── tcp-receiver-and-congestion-windows.png
│   │       ├── tcp-sliding-window.png
│   │       ├── tcp-three-way-handshake.jpg
│   │       ├── transport-port-addressing.jpg
│   │       ├── transport-segmentation.jpg
│   │       └── udp-header.png
│   ├── lesson_12/
│   │   ├── images/
│   │   │   ├── nat-addresses.png
│   │   │   ├── network.png
│   │   │   ├── pat.png
│   │   │   └── static-nat.png
│   │   └── pkt/
│   │       └── nat-hw.pkt
│   ├── lesson_13/
│   │   ├── images/
│   │   │   ├── dns-browser-error.jpg
│   │   │   ├── dns-domain-levels.png
│   │   │   ├── dns-name-resolution.png
│   │   │   ├── dns-network.png
│   │   │   ├── dns-server-interaction.png
│   │   │   └── dns-soa-example.png
│   │   └── pkt/
│   │       └── dns-hw1.pkt
│   └── lesson_14/
│       └── images/
│           ├── tcp-flags.ack.png
│           ├── tcp-flags.syn.png
│           └── udp.png
├── control-test/
│   ├── final-test.md
│   └── test_01.md
├── lesson_01/
│   ├── class/
│   │   └── .gitkeep
│   └── hw/
│       └── hw.md
├── lesson_02/
│   ├── class/
│   │   └── class.md
│   └── hw/
│       └── hw.md
├── lesson_03/
│   ├── class/
│   │   └── .gitkeep
│   └── hw/
│       └── hw.md
├── lesson_04/
│   ├── class/
│   │   └── .gitkeep
│   └── hw/
│       └── hw.md
├── lesson_05/
│   ├── class/
│   │   └── class.md
│   └── hw/
│       └── hw.md
├── lesson_06/
│   ├── class/
│   │   └── class.md
│   └── hw/
│       └── hw.md
├── lesson_07/
│   ├── class/
│   │   └── .gitkeep
│   └── hw/
│       └── hw.md
├── lesson_08/
│   ├── class/
│   │   └── class.md
│   └── hw/
│       └── hw.md
├── lesson_09/
│   └── class/
│       └── class.md
├── lesson_10/
│   └── class/
│       └── class.md
├── lesson_11/
│   ├── class/
│   │   └── class.md
│   └── hw/
│       └── hw.md
├── lesson_12/
│   ├── class/
│   │   └── class.md
│   └── hw/
│       └── hw.md
├── lesson_13/
│   ├── class/
│   │   └── class.md
│   └── hw/
│       └── hw.md
├── lesson_14/
│   ├── class/
│   │   └── .gitkeep
│   └── hw/
│       └── hw.md
├── lesson_15/
│   ├── class/
│   │   └── .gitkeep
│   └── hw/
│       └── hw.md
├── .github/
│   └── workflows/
│       └── .gitkeep
├── .gitignore
├── LICENSE.md
└── README.md
```
