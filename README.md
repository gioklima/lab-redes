![GitHub License](https://img.shields.io/github/license/gioklima/lab-redes?style=flat)
# 🖧 Laboratório de Redes 01 – Projeto de Rede Local

Projeto desenvolvido na disciplina de **Redes de Computadores** do **Curso Técnico em Informática do SENAC**, com o objetivo de aplicar na prática conceitos básicos de **redes locais (LAN)** e comunicação entre dispositivos.

**Aluna:** Giovanna Lima dos Santos  
**Professor:** José de Assis  
**Data:** 09/03/2026

---

## 1. Objetivo

Implementar uma rede local simples conectando **3 notebooks**, um **roteador wireless com switch integrado** e uma **impressora de rede**.

O projeto será realizado em duas etapas:

1. **Simulação da rede** no Cisco Packet Tracer  
2. **Implementação da rede** no laboratório real

---

## 2. Equipamentos Utilizados

- 3 notebooks  
- 1 roteador wireless (1 porta WAN e 4 portas LAN)  
- 1 impressora de rede  
- Cabos de rede

---

## 3. Topologia da Rede

Diagrama da rede lógica utilizada neste laboratório.

```mermaid
graph TD

WAN[Internet / WAN do Provedor]
Roteador[Roteador Wireless<br>1 Porta WAN<br>4 Portas LAN]
Notebook1[Notebook 1]
Notebook2[Notebook 2]
Notebook3[Notebook 3]
Impressora[Impressora de Rede]

WAN -->|Porta WAN| Roteador
Roteador -->|LAN 1| Notebook1
Roteador -->|LAN 2| Notebook2
Roteador -->|LAN 3| Notebook3
Roteador -->|LAN 4| Impressora
```
Imagem da topologia utilizada no laboratório

![](TOPOLOGIA.png)
