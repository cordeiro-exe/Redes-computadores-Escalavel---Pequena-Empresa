# Projeto Cisco - Rede de uma Pequena Empresa

## Objetivo

Simular a rede de uma pequena empresa, buscando criar uma
estrutura que pudesse crescer sem precisar refazer toda a rede.

## Topologia

[imagem da topologia]

## Equipamentos

- 1 Router Cisco 2811
- 1 Switch Core Cisco 2960
- 3 Switches de acesso Cisco 2960
- Computadores
- Servidores

## VLANs

| VLAN | Setor | Rede |
|---|---|---|
| 3 | Diretoria | 192.168.3.0/24 |
| 10 | Administração | 192.168.10.0/24 |
| 20 | RH | 192.168.20.0/24 |
| 30 | Financeiro | 192.168.30.0/24 |

## Implementações

- Router-on-a-Stick
- DHCP
- VLANs
- Trunks 802.1Q
- IPv4
- ACLs

## Testes

[prints]

## Troubleshooting

[problemas que aconteceram e como foram resolvidos]

## Arquivo do Packet Tracer

O arquivo `.pkt` está disponível neste repositório.
