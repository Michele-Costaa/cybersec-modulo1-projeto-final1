# Projeto Final - Formação CyberSec - Módulo 1  
## Laboratório: Segmentação de Rede em Ambiente Docker

### Descrição

Este repositório contém os artefatos do projeto final do Módulo 1 da Formação CyberSec, que consistiu em analisar a segmentação de uma rede corporativa simulada em ambiente Docker. O objetivo foi identificar exposições, mapear hosts e avaliar riscos operacionais.

---


### Ferramentas Utilizadas

- `nmap`
- `rustscan`
- `netdiscover`
- `ping`
- `Docker`

---


### O que foi feito

- Coleta ativa de dados nas três sub-redes:
  - `corp_net (10.10.10.0/24)`
  - `guest_net (10.10.30.0/24)`
  - `infra_net (10.10.50.0/24)`
- Identificação de dispositivos e serviços expostos.
- Análise de riscos baseada nas portas e funções observadas.
- Geração de relatório técnico e diagrama da topologia de rede.
---

### Relatórios

- [Diagrama da Rede](./Prints/Diagrama%20de%20Rede.png)
- [Versão PDF do Relatório](./Relatorio%20Lab%20Rede.pdf)
---

### Conclusões

A análise revelou a exposição de serviços como `rpcbind`, ausência de firewall visível entre redes e riscos na segmentação atual. A aplicação de práticas de segmentação mais rígidas e filtragem de tráfego é altamente recomendada.

---

### Autor

- **Michele Costa**