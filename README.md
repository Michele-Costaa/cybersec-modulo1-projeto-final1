# Projeto Final - Formação CyberSec - Módulo 1  
## Laboratório: Segmentação de Rede em Ambiente Docker

### Descrição

Este projeto tem como objetivo analisar uma rede simulada, identificar seus dispositivos conectados e avaliar se há riscos de segurança ou falhas de organização. O ambiente foi criado com ferramentas gratuitas, simulando uma empresa com diferentes setores conectados em rede.

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

## Por que isso é importante?

Redes mal organizadas podem facilitar ataques, vazamentos de dados ou mau funcionamento. Aqui analisamos uma rede dividida em três partes:

- **corp_net** – Simula a rede interna da empresa (estações de trabalho).
- **guest_net** – Onde visitantes se conectam.
- **infra_net** – Parte que simula servidores e infraestrutura.

O projeto mostra se os dispositivos estão bem separados, se há serviços expostos sem necessidade, e como isso pode ser melhorado.

---

### Relatórios

- [Diagrama da Rede](./Prints/Diagrama%20de%20Rede.png)
- [Relatório Técnico.pdf](https://github.com/user-attachments/files/21518466/Relatorio.Tecnico.pdf)
---

### Conclusões

A análise revelou a exposição de serviços como `rpcbind`, ausência de firewall visível entre redes e riscos na segmentação atual. A aplicação de práticas de segmentação mais rígidas e filtragem de tráfego é altamente recomendada.

---

### Autor

- **Michele Costa**
