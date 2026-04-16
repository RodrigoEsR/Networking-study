# 🌐 Estudo de Redes (Networking-study)

Este repositório é dedicado ao estudo prático de redes de computadores, utilizando o **Cisco Packet Tracer** como principal ferramenta de simulação e aprendizado. O foco é documentar a implementação de infraestruturas que simulam cenários reais de redes corporativas e conectividade ISP.

---

## 🚀 Visão Geral do Projeto

O projeto apresenta a implementação de redes locais (LAN) robustas e conectividade com Provedores de Internet (ISP). O objetivo é demonstrar a configuração e o funcionamento de protocolos de camadas 2, 3 e 4, além de serviços avançados de segurança e redes sem fio.

## 🛠️ Conceitos e Tecnologias Aplicados

Neste laboratório, foram implementados e configurados os seguintes tópicos:

* **Camada 2 (Enlace):** Configuração de VLANs, STP (Spanning Tree Protocol) para prevenção de loops, DTP (Dynamic Trunking Protocol) e otimização de BPDUs.
* **Camada 3 (Rede):** Endereçamento IPv4, Subnetting (VLSM) e ACLs (Listas de Controle de Acesso) para filtragem de tráfego e segurança.
* **Protocolos de Roteamento:** Implementação de roteamento dinâmico com RIP e OSPF, além de configuração de ASN (Autonomous System Number).
* **Redes Sem Fio (Wi-Fi):** Configuração de Pontos de Acesso (APs) com foco em **mitigação de interferência de rádio** (ajuste fino de canais e potência) para garantir estabilidade de sinal.
* **Segurança e Autenticação:** Implementação de um servidor **RADIUS/EAP** para autenticação centralizada, garantindo que os terminais utilizem credenciais individuais (WPA Enterprise).
* **Serviços de Rede:** DHCP para atribuição dinâmica de IPs e compreensão prática de fluxos TCP e UDP.

---

## 📂 Arquivos do Projeto

* **Projeto_redes.pkt:** Simulação da topologia de rede estruturada, roteamento e serviços.
* **projetoWIFI.pkt:** Laboratório focado em infraestrutura sem fio, segurança EAP e ajustes de interferência.

---

## 📝 Como Utilizar

1.  Instale o **Cisco Packet Tracer** (versão recomendada: 8.x ou superior).
2.  Clone este repositório:
    ```bash
    git clone [https://github.com/seu-usuario/Networking-study.git](https://github.com/seu-usuario/Networking-study.git)
    ```
3.  Abra os arquivos `.pkt` diretamente na raiz do projeto para explorar as configurações via CLI.

---

# 🌐 Networking Study (English Version)

This repository contains a comprehensive study on computer networking, using **Cisco Packet Tracer** as the primary simulation tool.

## 🛠️ Concepts & Technologies Applied

* **Layer 2 & 3:** VLANs, STP, DTP, IPv4 Addressing (VLSM), and ACLs.
* **Routing:** RIP, OSPF, and ASN configuration.
* **Wireless & Security:** AP configuration with **interference mitigation** and **RADIUS/EAP** authentication (WPA Enterprise).
* **Services:** DHCP and TCP/UDP data flow analysis.

## 📂 Project Files

* **Projeto_redes.pkt:** Main network topology, routing, and services.
* **projetoWIFI.pkt:** Focused lab for wireless infrastructure and EAP security.

## 📝 How to Use

1.  Open **Cisco Packet Tracer**.
2.  Clone the repo and open the `.pkt` files directly from the root folder.
