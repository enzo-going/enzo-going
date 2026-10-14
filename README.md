## Olá, me chamo Enzo Liutkus Going 👋

Estudante de Ciência da Computação · Backend em Python e Node.js · Automação e monitoramento de infraestrutura

[![Email](https://img.shields.io/badge/Email-enzogoingpro%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:enzogoingpro@gmail.com) [![Portfolio](https://img.shields.io/badge/Portfolio-ff9100?style=flat&logo=vercel&logoColor=white)](https://portfolio-enzo-going.vercel.app/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-enzo--going-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/enzo-going-4a1917306/) [![GitHub](https://img.shields.io/badge/Projetos-GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/enzo-going?tab=repositories) [![PCE - Clinica de Psicologia](https://img.shields.io/badge/Org-PCE%20Cl%C3%ADnica%20de%20Psicologia-6f42c1?style=flat&logo=github&logoColor=white)](https://github.com/pce-clinica-psicologia)

---

Sou estudante de Ciência da Computação na Universidade Católica de Santos (5º de 8 semestres) e construo sistemas de backend e automação que rodam de verdade: uma plataforma de TV corporativa em produção, monitores de rede e de impressoras e um helpdesk empacotado para Windows. Também desenvolvo projetos de análise de dados e Machine Learning. Gosto de código bem organizado, testes automatizados e documentação clara.

Atualmente em estágio na área de TI, onde aplico desenvolvimento e automação no dia a dia.

### Organização e projeto em equipe

<a href="https://github.com/pce-clinica-psicologia"><img src="https://github.com/pce-clinica-psicologia.png" width="76" alt="PCE — Clínica de Psicologia"></a>

Integro a organização **[PCE — Clínica de Psicologia](https://github.com/pce-clinica-psicologia)**, onde a equipe desenvolve o **[clinica-app](https://github.com/pce-clinica-psicologia/clinica-app)** (*psicomanager*) — sistema de gestão de clínica construído por squads que trabalham em paralelo no mesmo repositório.

| | |
|---|---|
| **Arquitetura** | Monorepo `client` + `server`, com ambiente idêntico para toda a equipe via Docker Compose (React na 3000 · Spring Boot na 8080 · MySQL) |
| **Testes** | JUnit nas regras de negócio, testes de componente no React e E2E com Cypress validando client + server + banco de ponta a ponta |
| **CI/CD** | GitHub Actions com *path filtering*: mudança só em `/client` dispara apenas a esteira do React, sem recompilar a API Java à toa |
| **Stack** | Java · Spring Boot · React · TypeScript · MySQL · Docker · Cypress · GitHub Actions |

### Foco atual

- **corptv** — plataforma de TV corporativa em produção no estágio: painel com playlists e agendamento por ambiente, player que se atualiza sozinho com cache offline, e Raspberry Pi como player atrás das TVs. Auditoria com exportação CSV, monitor de tráfego e watchdog que confirma a falha antes de reiniciar.
- **netpulse** — monitor de ativos de rede que agrupa falhas simultâneas da mesma sub-rede em um único incidente, em vez de disparar um alerta por equipamento. Marco v0.1 completo: coleta, API FastAPI, dashboard React e motor de incidentes testados, com análise de causa por IA sob demanda.
- **print-monitor-local** — monitor de impressoras de rede: leitura de contadores via SNMP (Python puro), histórico em SQLite, cálculo de volume por período pela diferença entre leituras (com tratamento de reset), dashboard local com filtros e ranking, importação por CSV e descoberta segura na sub-rede. Empacotado como executável Windows ([release](https://github.com/enzo-going/print-monitor-local/releases)).
- **ti-chamados-whatsapp** — helpdesk de TI que transforma mensagens em chamados: triagem automática por palavras-chave, rodízio entre atendentes, idempotência, persistência SQLite e painel local somente leitura. Agora com app Windows empacotado (PyInstaller): atalho na área de trabalho, sem instalar Python. Núcleo em Python puro, zero dependências de runtime.
- Aprofundando SQL, SQLAlchemy e arquitetura de APIs REST
- Explorando a integração com a WhatsApp Cloud API — borda local (webhook, validação de assinatura HMAC, transporte plugável) testável sem rede, ainda sem conexão com produção

### Tecnologias

**Backend** &nbsp; [![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/) [![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/) [![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)](https://flask.palletsprojects.com/) [![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)](https://nodejs.org/) [![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)](https://expressjs.com/) [![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)](https://openjdk.org/) [![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)

**Dados** &nbsp; [![SQL](https://img.shields.io/badge/SQL-003B57?style=flat&logo=sqlite&logoColor=white)](https://www.sqlite.org/) [![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)](https://www.mysql.com/) [![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/) [![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)

**Frontend** &nbsp; [![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/) [![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)](https://react.dev/) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

**Infra e automação** &nbsp; [![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/) [![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)](https://www.kernel.org/) [![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat&logo=raspberrypi&logoColor=white)](https://www.raspberrypi.com/) [![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTQgNWw3IDctNyA3TTEyIDE5aDgiIGZpbGw9Im5vbmUiIHN0cm9rZT0id2hpdGUiIHN0cm9rZS13aWR0aD0iMi41IiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiLz48L3N2Zz4=)](https://learn.microsoft.com/powershell/) [![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)](https://github.com/features/actions) [![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)](https://git-scm.com/)

---

### Projetos

| Projeto | Descrição | Stack |
|---|---|---|
| [corptv](https://github.com/enzo-going/corptv) | Plataforma de TV corporativa em produção: playlists e agendamento por ambiente (inclusive virando a meia-noite), player com cache offline e atualização sem reinício, uploads validados pela assinatura do arquivo e auditoria com verificação de integridade. | Node.js · Express · NeDB · Raspberry Pi |
| [netpulse](https://github.com/enzo-going/netpulse) | Monitoramento de ativos de rede com correlação de falhas: agrupa quedas simultâneas da mesma sub-rede em um incidente só, com dashboard React, análise de causa por IA sob demanda e demo completa em um `docker compose up`. | Python · FastAPI · React · SQLite · Docker |
| [print-monitor-local](https://github.com/enzo-going/print-monitor-local) | Monitor de impressoras de rede: coleta de contadores via SNMP, histórico em SQLite, cálculo de volume por período, dashboard com filtros e ranking, descoberta na sub-rede e executável Windows. | Python · SNMP · SQLite · Flask · PyInstaller |
| [ti-chamados-whatsapp](https://github.com/enzo-going/ti-chamados-whatsapp) | Helpdesk de TI que transforma mensagens em chamados: triagem automática, rodízio entre atendentes, idempotência, persistência SQLite e painel local somente leitura. App Windows empacotado e borda da WhatsApp Cloud API testável sem rede. | Python · SQLite · HTTP · unittest · PyInstaller |
| [clinica-app](https://github.com/pce-clinica-psicologia/clinica-app) — *equipe [@pce-clinica-psicologia](https://github.com/pce-clinica-psicologia)* | Sistema de gestão para clínica de psicologia em monorepo: client React/TypeScript, server Java Spring Boot e MySQL, com Docker Compose para ambiente único, E2E em Cypress e CI por path filtering. | Java · Spring Boot · React · TypeScript · MySQL · Docker |
| [international-conflict-risk-ml](https://github.com/enzo-going/international-conflict-risk-ml) | Pipeline de ML para previsão de risco de conflito em 194 países. F1-score 0.87, validação temporal, dashboard público via GitHub Pages. | Python · scikit-learn · SQL · Pandas |
| [pdf-document-manager](https://github.com/enzo-going/pdf-document-manager) | Gerenciador web de documentos PDF: autenticação JWT com papéis, upload e metadados, registro de auditoria e painel de métricas. Suíte de testes da API rodando em CI. | Python · Flask · SQLAlchemy · JWT · pytest |
| windows-deploy-kit *(código privado)* | Pendrive que prepara e restaura máquinas Windows sem acompanhamento: etapas idempotentes, modo simulação e entrada no domínio sem senha em disco. | PowerShell · Windows · Active Directory |
| [tactical-autobattler-python](https://github.com/enzo-going/tactical-autobattler-python) | Jogo tático por turnos jogável no navegador: o mesmo pacote Python roda via Pyodide, sem servidor. Uma ordem por unidade e alvo confirmado, com um laboratório de simulação ao lado — estratégias de bot, torneios e relatórios JSON. | Python · OOP · Pyodide · unittest |
| [analise-cesta-basica-brasil](https://github.com/enzo-going/analise-cesta-basica-brasil) | Análise exploratória da evolução da cesta básica em capitais do Sudeste com dados DIEESE. Dashboard via GitHub Pages. | Python · Pandas · Plotly · Jupyter |
| [network-folder-search](https://github.com/enzo-going/network-folder-search) | Busca em pastas e compartilhamentos de rede por índice local, somente leitura: cataloga uma vez e responde em segundos. | PowerShell · Windows · CSV |

---

### Estatísticas

[![Métricas do perfil](https://github.com/enzo-going/enzo-going/raw/main/metrics.svg)](https://github.com/enzo-going/enzo-going/blob/main/metrics.svg)
