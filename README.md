# PROYECTO FINAL-FUNDAMENTOS DE ENRUTAMIENTO

Este proyecto consiste en la implementación de una red en Cisco Packet Tracer que integra VLANs, EtherChannel, STP, enrutamiento entre VLANs (Router-on-a-Stick), HSRP para redundancia, DHCP y conectividad entre múltiples routers.

# OBJETIVOS
- Segmentar la red mediante VLANs
- Implementar redundancia con HSRP
- Configurar EtherChannel entre switches
- Permitir comunicación entre VLANs
- Asignar direcciones IP automáticamente con DHCP

# TOPOLOGIA

La topología está compuesta por:

- 2 switches (SW1 y SW2)
- 4 routers (R1, R2, R3, R4)
- PCs en diferentes VLANs

Conexiones principales:
- SW1 ↔ SW2 mediante EtherChannel
- R1 conectado a SW1 (Router-on-a-Stick)
- R4 conectado a SW2

# VLANS

| VLAN | Nombre       |  Red            |
|------|--------------|-----------------|
| 300  | ESTUDIANTES  | 192.168.30.0/24 |
| 500  | ACADEMICOS   | 192.168.50.0/24 |
| 999  | ADMIN        | 192.168.99.0/24 |

# TECNOLOGIAS USADAS

- VLANs
- Trunking
- EtherChannel (LACP)
- Spanning Tree Protocol (STP)
- Router-on-a-Stick
- HSRP
- DHCP
- Routing estático

# ARCHIVOS INCLUIDOS
- config.txt → Configuración completa de los dispositivos
- topologia.pkt → Archivo de Packet Tracer

  # AUTOR
  ELIANNY ADAMES REYES, MATRICULA 2025-0771
