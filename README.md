# Компьютерные сети

Этот репозиторий заменяет тетрадь: здесь собраны конспекты занятий, домашние работы и материалы по предмету **«Компьютерные сети»**.

## Оглавление

| Занятие |                           Конспект                           |                                 Домашняя работа                                  |
| :-----: | :----------------------------------------------------------: | :------------------------------------------------------------------------------: |
|    1    |                              —                               |             [Создать сеть аудитории](lesson_01/hw/Create_network.md)             |
|    2    | [Коммутация Ethernet](lesson_02/class/Ethernet_switching.md) |                      [Wireshark](lesson_02/hw/Wireshark.md)                      |
|    3    |                              —                               |              [Схема MAC-адреса](lesson_03/hw/MAC_address_scheme.md)              |
|    4    |                              —                               |            [Cisco Packet Tracer](lesson_04/hw/Cisco_Packet_Tracer.md)            |
|    5    |     [IPv4: адресация и подсети](lesson_05/class/ipv4.md)     | [Cisco Packet Tracer и распределение адресов по подсетям](lesson_05/hw/hw_05.md) |
|    6    |    [Расчёт IP-сетей и подсетей](lesson_06/class/class.md)    |           [Создание сети Cisco](lesson_06/hw/Cisco-Network-create.md)            |
|    7    |                              —                               |           [Расчёт масок и диапазонов подсетей](lesson_07/hw/hw_07.md)            |

## Структура

```text
├── .github/
│   ├── assets/
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
│   │   └── lesson_06/
│   │       ├── Cisco-Network-create.png
│   │       ├── Cisco-Network-ping.png
│   │       └── Cisco-Network-simulator-ping.png
│   └── pkt/
│       ├── .gitkeep
│       └── lesson_06/
│           └── Cisco-Network-1.pkt
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
├── .gitignore
├── LICENSE.md
└── README.md
```
