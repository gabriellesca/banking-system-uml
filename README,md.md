# 🏦 Sistema Bancário — Análise de Requisitos & UML

Modelagem completa de um **sistema bancário** utilizando Diagrama de Casos de Uso UML, desenvolvida com base em análise de requisitos funcionais. O projeto define atores, fronteiras do sistema e regras de negócio para operações bancárias.

Projeto desenvolvido como atividade prática da disciplina de **Análise e Modelagem de Sistemas** no curso de Tecnólogo em Análise e Desenvolvimento de Sistemas.

---

## 📸 Diagrama de Casos de Uso

![Diagrama UML Bancário](assets/uml_bancario.jpeg)

---

## 👥 Atores do Sistema

| Ator           | Papel                                              |
|----------------|----------------------------------------------------|
| `Cliente`      | Realiza operações bancárias                        |
| `Funcionário`  | Intermedia abertura e encerramento de contas       |
| `Caixa Eletrônico` | Interface para operações autônomas do cliente  |

---

## 📋 Casos de Uso

| Caso de Uso             | Ator Principal     | Descrição                                        |
|-------------------------|--------------------|--------------------------------------------------|
| Abrir Conta             | Cliente + Funcionário | Abertura presencial com escolha do tipo de conta |
| Encerrar Conta          | Cliente + Funcionário | Apenas se saldo = zero                           |
| Depositar               | Cliente (Caixa)    | Inserção de valor via caixa eletrônico           |
| Sacar                   | Cliente (Caixa)    | Retirada conforme saldo disponível               |
| Consultar Saldo         | Cliente (Caixa)    | Exibição ou impressão do saldo atual             |
| Emitir Extrato          | Cliente (Caixa)    | Histórico completo de movimentações              |
| Registrar Movimentação  | Sistema            | Log automático de todas as operações             |

---

## ✨ Regras de Negócio Modeladas

- Conta só pode ser encerrada com **saldo zerado**
- Tipos de conta: **especial** ou **poupança**
- Todas as movimentações são **registradas automaticamente** para auditoria
- Operações de saque exigem **saldo suficiente**
- Abertura e encerramento exigem **atendimento presencial** com funcionário

---

## 🛠️ Tecnologias

![UML](https://img.shields.io/badge/UML-Use%20Case%20Diagram-FF6B6B?style=flat)
![Visual Paradigm](https://img.shields.io/badge/Visual%20Paradigm-Modeling-blue?style=flat)

---

## 👩‍💻 Autora

**Gabrielle Simone Cunha**

[![GitHub](https://img.shields.io/badge/GitHub-gabriellesca-181717?style=flat&logo=github)](https://github.com/gabriellesca)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Gabrielle%20Simone-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/gabrielle-simone-928062392)
[![Portfolio](https://img.shields.io/badge/Portf%C3%B3lio-gabriellesca.github.io-000?style=flat&logo=github-pages)](https://gabriellesca.github.io/meu-portfolio)
