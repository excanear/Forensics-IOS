<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d0d,100:1a1a2e&height=200&section=header&text=APEX%20FORENSICS&fontSize=60&fontColor=00d4ff&fontAlignY=38&desc=Intelligence%20Platform%20for%20iOS%20Analysis&descAlignY=60&descColor=ffffff" width="100%"/>

<br/>

```
 █████╗ ██████╗ ███████╗██╗  ██╗
██╔══██╗██╔══██╗██╔════╝╚██╗██╔╝
███████║██████╔╝█████╗   ╚███╔╝ 
██╔══██║██╔═══╝ ██╔══╝   ██╔██╗ 
██║  ██║██║     ███████╗██╔╝ ██╗
╚═╝  ╚═╝╚═╝     ╚══════╝╚═╝  ╚═╝
```

### **Plataforma de Inteligência Forense iOS**
*Nível governamental. Cadeia de custódia. Correlação de dados.*

<br/>

![Status](https://img.shields.io/badge/STATUS-EM%20DESENVOLVIMENTO-ff6b00?style=for-the-badge&labelColor=0d0d0d)
![Version](https://img.shields.io/badge/VERSÃO-1.0.0%20ALPHA-00d4ff?style=for-the-badge&labelColor=0d0d0d)
![Platform](https://img.shields.io/badge/PLATAFORMA-iOS%20Forense-white?style=for-the-badge&logo=apple&labelColor=0d0d0d)
![License](https://img.shields.io/badge/LICENÇA-Restrita%20LEO-red?style=for-the-badge&labelColor=0d0d0d)

<br/>

> **"O dispositivo não mente — mas somente se você souber como lê-lo."**

</div>

---

<div align="center">

## ⚠️ PROJETO EM DESENVOLVIMENTO ATIVO ⚠️

### O que está sendo construído vai redefinir como investigações iOS são conduzidas.

</div>

---

## O que é o APEX?

O **APEX Forensics Intelligence Platform** é uma plataforma profissional de análise forense para dispositivos iOS, desenvolvida desde o zero com foco em:

- **Inteligência acionável** — não apenas dados brutos, mas correlações reais
- **Cadeia de custódia blindada** — cada evidência rastreada criptograficamente
- **Análise de grafo social** — quem fala com quem, padrões ocultos, intermediários
- **Laudos prontos para o tribunal** — PDF judicial com verificação de integridade SHA256

Não é uma ferramenta de hobbyista. É uma **plataforma de inteligência**.

---

## O que está por vir

<table>
<tr>
<td width="50%">

### 🔬 Extração de Artefatos
Análise profunda de múltiplas fontes:
- SMS / iMessage (incluindo deletados)
- WhatsApp, Telegram, Signal
- Histórico Safari + Favoritos
- Chamadas, Contatos, Localização
- Apple Notes, Fotos (EXIF), Wi-Fi

</td>
<td width="50%">

### 🧠 Inteligência de Grafo
Motor de correlação social com:
- Grafo de comunicação Neo4j
- PageRank e detecção de comunidades
- Identificação de chips descartáveis
- Vinculação de identidade cross-app (E.164)
- Pontuação de risco 0-10

</td>
</tr>
<tr>
<td width="50%">

### 🕒 Linha do Tempo Unificada
Reconstrução cronológica completa:
- Stream de eventos UTC unificado
- Detecção de lacunas suspeitas
- Análise estatística de padrões
- Indicadores de limpeza de dispositivo

</td>
<td width="50%">

### 📄 Laudos Judiciais
Relatórios prontos para uso pericial:
- PDF com 10 seções obrigatórias
- Verificação de integridade SHA256
- Cadeia de custódia auditável
- Classificação: Restrito / Confidencial

</td>
</tr>
</table>

---

## Stack Tecnológica

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-00A551?style=flat-square&logo=neo4j&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

</div>

---

## Arquitetura em 8 Camadas

```
┌─────────────────────────────────────────────────────────────┐
│  CAMADA 1  →  Ingestão de Evidências + Cadeia de Custódia   │
│  CAMADA 2  →  Motor de Extração de Artefatos (plugável)     │
│  CAMADA 3  →  Normalização de Dados + Schema Unificado      │
│  CAMADA 4  →  Correlação de Inteligência + Grafo Social     │
│  CAMADA 5  →  Reconstrução de Linha do Tempo                │
│  CAMADA 6  →  Detecção Comportamental e de Anomalias        │
│  CAMADA 7  →  Espaço de Trabalho de Investigação            │
│  CAMADA 8  →  Motor de Relatórios Judiciais                 │
└─────────────────────────────────────────────────────────────┘
```

---

## Status de Desenvolvimento

| Módulo | Status |
|---|---|
| Pipeline de Ingestão + Cadeia de Custódia | ✅ Completo |
| Parsers: SMS, WhatsApp, Safari, Contatos, Chamadas, Localização | ✅ Completo |
| Normalização de Schema + Conversores de Timestamp | ✅ Completo |
| Grafo Social Neo4j + Vinculação de Identidade | ✅ Completo |
| Motor de Linha do Tempo + Detecção de Lacunas | ✅ Completo |
| Detecção de Anomalias + Scanner de Palavras-chave | ✅ Completo |
| API REST FastAPI + Autenticação JWT + RBAC | ✅ Completo |
| Motor de Relatórios PDF + Exportação JSON | ✅ Completo |
| Interface Desktop Electron + React | ✅ Completo |
| Criptografia AES-256-GCM por Caso | ✅ Completo |
| Testes de Penetração + Hardening de Produção | 🔄 Em progresso |
| Parsers: Telegram, Signal, Notes, Mail, Health | 🔜 Em breve |
| Interface de Análise Avançada de IA | 🔜 Em breve |

---

## Segurança em Primeiro Lugar

O APEX foi projetado sobre uma base de segurança sólida:

```
Criptografia  →  AES-256-GCM + HKDF-SHA256 por caso
Autenticação  →  JWT HS256 + bcrypt (custo 12)
Controle de Acesso  →  RBAC 4 papéis, 18 permissões granulares
Integridade  →  SHA256 por arquivo + HMAC-SHA256 no log de custódia
Frontend  →  Electron com contextIsolation + sandbox + CSP rígido
Banco de Dados  →  Acesso somente-leitura às evidências (SQLite URI ?mode=ro)
```

---

## Para Quem é

> Esta plataforma é desenvolvida **exclusivamente** para uso legal e autorizado por:

- Delegacias e unidades de crimes cibernéticos
- Peritos forenses digitais credenciados
- Ministérios Públicos e órgãos judiciais
- Agências de inteligência e segurança governamentais

---

<div align="center">

## Em Breve.

<br/>

```
Construído para investigadores.
Projetado para a justiça.
Engenheirado para a verdade.
```

<br/>

![Watching](https://img.shields.io/badge/⭐_Star_para_acompanhar-ff6b00?style=for-the-badge&labelColor=0d0d0d)

<br/>

*— APEX Forensics Intelligence Platform v1.0*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:0d0d0d&height=120&section=footer" width="100%"/>

</div>
