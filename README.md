
<img width="1814" height="965" alt="cyber 40" src="https://github.com/user-attachments/assets/42fc98d2-3300-4b27-b3c2-0561cead74be" />
<img width="1855" height="914" alt="ciber 34" src="https://github.com/user-attachments/assets/68b7b3c6-8596-4e36-9325-fb38cfc7daad" />
<img width="1807" height="896" alt="ciber 30" src="https://github.com/user-attachments/assets/619ac349-1be9-4956-a421-31aede956533" />
<img width="1781" height="903" alt="cyber 22" src="https://github.com/user-attachments/assets/4feb7054-ef59-4291-9295-289f7f623d32" />
<img width="1816" height="931" alt="cyber10" src="https://github.com/user-attachments/assets/301f042e-dd6d-4733-b23c-b45da15f03ef" />










<div align="center">

<br>

🔴 PH — CENTRO DE DEFESA CIBERNÉTICA
<span style="color:#1565C0">PLATAFORMA DE MONITORAMENTO SOC</span>

<br>

🛡️ CYBER DEFENSE • 🔎 THREAT HUNTING • 🚨 INCIDENT RESPONSE • 🐧 LINUX • 🐍 PYTHON

<br>

<img src="https://img.shields.io/badge/PH-CYBER%20DEFENSE-D50000?style=for-the-badge&logo=shield&logoColor=white"> <img src="https://img.shields.io/badge/SOC-MONITORING-1565C0?style=for-the-badge&logo=security&logoColor=white"> <img src="https://img.shields.io/badge/STATUS-EM%20DESENVOLVIMENTO-00C853?style=for-the-badge"> <img src="https://img.shields.io/badge/PLATAFORMA-AUTORAL-6A1B9A?style=for-the-badge">

<br><br>

Projeto autoral desenvolvido por Paulo Henrique (PH)
Uma plataforma de defesa cibernética criada para centralizar monitoramento, detecção, investigação, threat hunting e resposta a incidentes em uma única estação de operação.

<br>

🔴 DETECTAR   →  
🔵 ANALISAR   →  
🟢 RESPONDER

</div>

<div align="center">

🔴 ━━━━━━━━━━━━━━━━━━━━━━━ 🔴
CENTRO DE OPERAÇÕES
🔴 ━━━━━━━━━━━━━━━━━━━━━━━ 🔴

</div>

🖥️ O QUE É ESTE PROJETO?

O PH — Centro de Defesa Cibernética — Plataforma de Monitoramento SOC é um projeto autoral desenvolvido para representar uma estação operacional de segurança cibernética, reunindo diferentes áreas de uma operação SOC em uma única interface.

A plataforma foi pensada para trabalhar com:

┌─────────────────────────────────────────────────────────────┐
│                    PH — CYBER DEFENSE                       │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  🌐 REDE              🚨 AMEAÇAS             🖥️ ENDPOINTS   │
│                                                             │
│  🔎 THREAT HUNTING    🔬 INVESTIGAÇÃO         🧩 MITRE       │
│                                                             │
│  ⚙️ AUTOMAÇÃO         🛡️ RESPOSTA            📡 TELEMETRIA  │
│                                                             │
└─────────────────────────────────────────────────────────────┘

<div align="center">

🔵 ━━━━━━━━━━━━━━━━━━━━━━━ 🔵
VISÃO OPERACIONAL
🔵 ━━━━━━━━━━━━━━━━━━━━━━━ 🔵

</div>

🎯 PROPÓSITO

O objetivo do projeto é transformar eventos técnicos de segurança em informação operacional para análise e tomada de decisão.

                    EVENTO
                      │
                      ▼
              ┌───────────────┐
              │    COLETA     │
              └───────┬───────┘
                      │
                      ▼
              ┌───────────────┐
              │    ANÁLISE    │
              └───────┬───────┘
                      │
                      ▼
              ┌───────────────┐
              │   DETECÇÃO    │
              └───────┬───────┘
                      │
                      ▼
              ┌───────────────┐
              │    TRIAGEM    │
              └───────┬───────┘
                      │
                      ▼
              ┌───────────────┐
              │ INVESTIGAÇÃO  │
              └───────┬───────┘
                      │
                      ▼
              ┌───────────────┐
              │   RESPOSTA    │
              └───────┬───────┘
                      │
                      ▼
                 ENCERRAMENTO

<div align="center">

🟢 ━━━━━━━━━━━━━━━━━━━━━━━ 🟢
ARQUITETURA DO AMBIENTE
🟢 ━━━━━━━━━━━━━━━━━━━━━━━ 🟢

</div>

                         INTERNET
                            │
                            ▼
                    ┌──────────────┐
                    │   FIREWALL   │
                    └───────┬──────┘
                            │
              ┌─────────────┴─────────────┐
              │                           │
              ▼                           ▼
       ┌──────────────┐            ┌──────────────┐
       │    WAZUH     │            │   SURICATA   │
       │  SIEM / XDR  │            │   IDS / IPS  │
       └───────┬──────┘            └───────┬──────┘
               │                           │
               └────────────┬──────────────┘
                            │
                            ▼
                  ┌───────────────────┐
                  │   PYTHON / API    │
                  │     FASTAPI       │
                  └─────────┬─────────┘
                            │
                            ▼
              ┌────────────────────────────┐
              │ PH — CENTRO DE DEFESA      │
              │        CIBERNÉTICA         │
              └────────────┬───────────────┘
                           │
          ┌────────────────┼────────────────┐
          │                │                │
          ▼                ▼                ▼
     THREAT HUNTING   INVESTIGAÇÃO     MITRE ATT&CK
          │                │                │
          └────────────────┼────────────────┘
                           │
                           ▼
                       RESPOSTA

O Wazuh é utilizado como referência para a arquitetura de monitoramento de segurança e coleta de eventos. A plataforma oficial descreve componentes como agentes, servidor, indexador e dashboard.

<div align="center">

🔴 ━━━━━━━━━━━━━━━━━━━━━━━ 🔴
MÓDULOS DO SOC
🔴 ━━━━━━━━━━━━━━━━━━━━━━━ 🔴

</div>

🛰️ 01 — CENTRO DE COMANDO

O centro de comando apresenta uma visão geral da operação.

Recursos:

🟢 Estado dos componentes
🚨 Incidentes ativos
📡 Fluxo de eventos
🌐 Topologia da rede
📊 Indicadores operacionais
⚡ Atualizações da atividade
🔴 Alertas críticos
🌐 02 — OPERAÇÕES DE REDE

Representação operacional da infraestrutura:

                INTERNET
                    │
                    ▼
               FIREWALL
                    │
        ┌───────────┼───────────┐
        ▼           ▼           ▼
      WAZUH      LINUX-01      KALI
        │           │           │
        └───────────┼───────────┘
                    │
                    ▼
               PH SOC CORE
Indicadores
Indicador	Finalidade
📡 Mbps	Tráfego de rede
📦 PPS	Pacotes por segundo
🚨 Eventos	Atividade detectada
🔴 Alertas	Eventos relevantes
🟢 Status	Saúde dos componentes
🚨 03 — MONITOR DE AMEAÇAS

Centralização dos eventos de segurança.

🔴 CRÍTICO
████████████████████████

🟠 ALTO
████████████████

🟡 MÉDIO
██████████

🔵 BAIXO
████

🟢 INFORMATIVO
██
Ciclo

DETECÇÃO → TRIAGEM → INVESTIGAÇÃO → CONTENÇÃO → MITIGAÇÃO → ENCERRAMENTO

🖥️ 04 — ENDPOINT SECURITY

Monitoramento dos ativos.

╔══════════════════════════════════════╗
║             LINUX-01                 ║
╠══════════════════════════════════════╣
║ STATUS       : 🟢 ONLINE             ║
║ WAZUH AGENT  : 🟢 ACTIVE             ║
║ CPU          : 31%                   ║
║ MEMORY       : 48%                   ║
║ DISK         : 61%                   ║
║ ALERTAS      : 🔴 03                 ║
╚══════════════════════════════════════╝
🔎 05 — THREAT HUNTING

Área destinada à investigação proativa.

┌──────────────────────────────────────────────┐
│ PH-SOC > THREAT-HUNT                        │
├──────────────────────────────────────────────┤
│                                              │
│ query: event.level >= HIGH                   │
│                                              │
│ host: linux-01                               │
│ source: ssh                                  │
│                                              │
│ [ EXECUTAR CONSULTA ]                        │
└──────────────────────────────────────────────┘
Recursos
Pesquisa avançada
Filtros
Eventos brutos
JSON
Indicadores
Investigação por host
Exportação CSV
Correlação
🔬 06 — INVESTIGAÇÃO DE INCIDENTES

Cada incidente pode possuir seu próprio caso.

╔══════════════════════════════════════════╗
║              CASO #000421                ║
╠══════════════════════════════════════════╣
║ STATUS      : 🔴 INVESTIGAÇÃO            ║
║ ORIGEM      : KALI                       ║
║ ALVO        : LINUX-01                   ║
║ SEVERIDADE  : ALTA                       ║
║ TÉCNICA     : MITRE ATT&CK               ║
╚══════════════════════════════════════════╝
Linha do tempo
14:21:03  ● EVENTO DETECTADO
              │
14:21:07  ● REGRA ACIONADA
              │
14:21:11  ● ALERTA CRIADO
              │
14:21:25  ● INVESTIGAÇÃO INICIADA
              │
14:22:10  ● HOST ANALISADO
              │
14:23:04  ● AÇÃO DE RESPOSTA
🧩 07 — MITRE ATT&CK

O projeto utiliza o MITRE ATT&CK para contextualizar comportamentos adversários e relacionar eventos às técnicas correspondentes.

RECONHECIMENTO
      │
      ▼
ACESSO INICIAL
      │
      ▼
EXECUÇÃO
      │
      ▼
PERSISTÊNCIA
      │
      ▼
ESCALAÇÃO DE PRIVILÉGIOS
      │
      ▼
DESCOBERTA
      │
      ▼
MOVIMENTAÇÃO LATERAL
      │
      ▼
COMANDO E CONTROLE
      │
      ▼
EXFILTRAÇÃO / IMPACTO
⚔️ 08 — SIMULAÇÃO CONTROLADA

O laboratório possui cenários controlados para gerar eventos e observar o ciclo de defesa.

┌───────────────────────────────┐
│      ATAQUES CONTROLADOS      │
├───────────────────────────────┤
│                               │
│  01  Hydra SSH Brute Force    │
│  02  Nmap SYN Scan             │
│  03  Sudo Privilege Escalation│
│  04  C2 Reverse Shell          │
│                               │
└───────────────┬───────────────┘
                │
                ▼
        EVENTO DE SEGURANÇA
                │
                ▼
             DETECÇÃO
                │
                ▼
           INVESTIGAÇÃO
                │
                ▼
             RESPOSTA

⚠️ Todos os testes são destinados exclusivamente a ambientes próprios e autorizados.

<div align="center">

🔵 ━━━━━━━━━━━━━━━━━━━━━━━ 🔵
MODO DEMONSTRAÇÃO
🔵 ━━━━━━━━━━━━━━━━━━━━━━━ 🔵

</div>

🧪 DEMO MODE

A aplicação possui um modo de demonstração que permite visualizar o funcionamento da plataforma sem depender, inicialmente, de uma infraestrutura externa.

O mecanismo gera eventos controlados para demonstrar:

🚨 Alertas
📡 Telemetria
🖥️ Endpoints
🌐 Eventos de rede
🔎 Investigação
🧩 Técnicas
📊 Atualização operacional
DEMO ENGINE
     │
     ├── Wazuh Events
     ├── Suricata Events
     ├── Endpoint Events
     └── Attack Simulation
              │
              ▼
        PH SOC PLATFORM

🟡 Importante: o DEMO MODE representa uma camada de simulação. A evolução do projeto prevê a substituição progressiva dos eventos simulados por telemetria real.

<div align="center">

🟢 ━━━━━━━━━━━━━━━━━━━━━━━ 🟢
STACK TECNOLÓGICA
🟢 ━━━━━━━━━━━━━━━━━━━━━━━ 🟢

</div>

<table> <tr> <td width="33%" align="center">

🔵 FRONT-END

React
TypeScript
Vite
HTML5
CSS
SVG
Web Audio API

</td>

<td width="33%" align="center">

🟢 BACK-END

Python
FastAPI
REST API
WebSocket
JSON

</td>

<td width="33%" align="center">

🔴 SECURITY

Wazuh
Suricata
Zeek
MITRE ATT&CK
Kali Linux
Linux

</td> </tr> </table>

<div align="center">

🔴 ━━━━━━━━━━━━━━━━━━━━━━━ 🔴
AUTOMAÇÃO & INTELIGÊNCIA OPERACIONAL
🔴 ━━━━━━━━━━━━━━━━━━━━━━━ 🔴

</div>

O projeto utiliza Python como uma das tecnologias centrais para evolução da automação.

                 EVENTOS
                    │
                    ▼
             ┌──────────────┐
             │    PYTHON    │
             └──────┬───────┘
                    │
       ┌────────────┼────────────┐
       ▼            ▼            ▼
    FILTRO       CORRELAÇÃO   AUTOMAÇÃO
       │            │            │
       └────────────┼────────────┘
                    ▼
              AÇÃO OPERACIONAL

Possíveis evoluções:

Correlação automática
Classificação de eventos
Geração de indicadores
Automação de playbooks
Resposta automatizada
Notificações
Relatórios

<div align="center">

🔵 ━━━━━━━━━━━━━━━━━━━━━━━ 🔵
ESTRUTURA DO PROJETO
🔵 ━━━━━━━━━━━━━━━━━━━━━━━ 🔵

</div>

PH-CYBER-DEFENSE-CENTER/
│
├── 📁 public/
│
├── 📁 src/
│   │
│   ├── 📁 components/
│   ├── 📁 modules/
│   ├── 📁 services/
│   ├── 📁 data/
│   ├── 📁 types/
│   └── 📄 ...
│
├── 📄 .env.example
├── 📄 .gitignore
├── 📄 index.html
├── 📄 metadata.json
├── 📄 package.json
├── 📄 tsconfig.json
├── 📄 vite.config.ts
└── 📄 README.md

<div align="center">

🟢 ━━━━━━━━━━━━━━━━━━━━━━━ 🟢
EXECUÇÃO LOCAL
🟢 ━━━━━━━━━━━━━━━━━━━━━━━ 🟢

</div>

💻 REQUISITOS
Windows 10 / 11
Node.js
npm
Git
⚙️ INSTALAÇÃO
git clone <URL_DO_REPOSITORIO>

cd ph-cyber-defense-center

npm install
▶️ EXECUTAR
npm run dev

Depois, acessar o endereço local exibido pelo Vite.

<details> <summary>🔐 <b>CONFIGURAÇÃO DO AMBIENTE</b></summary>

<br>

Arquivo:

.env

Exemplo:

GEMINI_API_KEY=""

VITE_SOC_API_URL="http://localhost:8000"

VITE_SOC_WS_URL="ws://localhost:8000/ws/events"

VITE_SOC_MODE="DEMO"

</details>

<div align="center">

🔴 ━━━━━━━━━━━━━━━━━━━━━━━ 🔴
ROADMAP
🔴 ━━━━━━━━━━━━━━━━━━━━━━━ 🔴

</div>

🟢 FASE 01 — INTERFACE SOC

Centro de Comando

Monitoramento de ameaças

Monitoramento de endpoints

Threat Hunting

Investigação

MITRE ATT&CK

Status do sistema

DEMO MODE

Simulação de eventos

🔵 FASE 02 — INTEGRAÇÃO

FastAPI

WebSocket

Wazuh real

Recepção de alertas

Normalização

Persistência

🟠 FASE 03 — DETECÇÃO

Regras personalizadas

Correlação

Suricata

Zeek

Mapeamento MITRE automático

🔴 FASE 04 — RESPOSTA

Playbooks

Automação Python

Contenção

Notificações

Relatórios

🟣 FASE 05 — EVOLUÇÃO

Integração completa do laboratório

Telemetria real

Threat Intelligence

Automação avançada

Incident Response automatizado

<div align="center">

🔵 ━━━━━━━━━━━━━━━━━━━━━━━ 🔵
O QUE ESTE PROJETO DEMONSTRA
🔵 ━━━━━━━━━━━━━━━━━━━━━━━ 🔵

</div>

<table> <tr> <td>🐧 <b>Linux</b></td> <td>Administração, serviços, logs, processos e diagnóstico</td> </tr> <tr> <td>🛡️ <b>Cybersecurity</b></td> <td>Detecção, análise, monitoramento e resposta</td> </tr> <tr> <td>🐍 <b>Python</b></td> <td>Automação, APIs e processamento de eventos</td> </tr> <tr> <td>🌐 <b>Redes</b></td> <td>Tráfego, eventos, IDS/IPS e análise</td> </tr> <tr> <td>🖥️ <b>Desenvolvimento</b></td> <td>React, TypeScript, Vite e interfaces operacionais</td> </tr> <tr> <td>🔎 <b>Threat Hunting</b></td> <td>Pesquisa, investigação e correlação</td> </tr> <tr> <td>🚨 <b>SOC</b></td> <td>Monitoramento, triagem e resposta a incidentes</td> </tr> </table>

<div align="center">

🟢 ━━━━━━━━━━━━━━━━━━━━━━━ 🟢
FILOSOFIA
🟢 ━━━━━━━━━━━━━━━━━━━━━━━ 🟢
DADO → CONTEXTO → DETECÇÃO → INVESTIGAÇÃO → RESPOSTA

</div>

Não basta identificar um evento.
É necessário compreender o que aconteceu, onde aconteceu, por que aconteceu e qual resposta deve ser executada.

<div align="center">

🔴 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 🔴
PH — CENTRO DE DEFESA CIBERNÉTICA
PLATAFORMA DE MONITORAMENTO SOC
🔴 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 🔴

<br>

DESENVOLVIDO POR PAULO HENRIQUE — PH

<br>

🔴 DETECTAR
⬇
🔵 INVESTIGAR
⬇
🟢 RESPONDER

<br>

Linux • Cybersecurity • Python • Automação • SOC

</div>

⚠️ Aviso: este projeto é destinado a estudos, laboratório, simulação e ambientes autorizados. Técnicas de segurança devem ser utilizadas somente em sistemas para os quais exista autorização.

<div align="center">

© PH — Centro de Defesa Cibernética

</div>
