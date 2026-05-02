# 🚀 Sistema de Suporte Técnico com Jira 

![status](https://img.shields.io/badge/status-concluído-brightgreen)
![foco](https://img.shields.io/badge/foco-Suporte%20Técnico-blue)
![ferramenta](https://img.shields.io/badge/ferramenta-Jira-orange)

---

## 👩‍💻 Sobre o projeto

Este projeto simula a rotina de um(a) Analista de Suporte Técnico utilizando o Jira para gestão de chamados, organização de atendimentos e acompanhamento de demandas.

O objetivo é demonstrar, de forma prática, como estruturar tickets, priorizar atendimentos e manter um fluxo organizado e eficiente.

---

## 🧠 Habilidades demonstradas

- Gestão de chamados (tickets)
- Organização e padronização de atendimentos
- Priorização de demandas
- Registro e rastreabilidade de informações
- Comunicação clara com o cliente
- Análise e resolução de problemas

---

## 🔄 Fluxo de atendimento (simulação Jira)

```mermaid
graph TD
A[Abertura do chamado] --> B[Análise do problema]
B --> C[Definição de prioridade]
C --> D[Atendimento]
D --> E{Resolvido?}
E -->|Sim| F[Finalização]
E -->|Não| G[Escalonamento]
