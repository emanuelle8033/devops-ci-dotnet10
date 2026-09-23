# 🚀 Integração Contínua (CI) com .NET 10, xUnit e GitHub Actions

![.NET 10](https://img.shields.io/badge/.NET-10.0-512BD4?logo=dotnet)
![Build & Test Pipeline](https://github.com/emanuelle8033/devops-ci-dotnet10/actions/workflows/ci.yml/badge.svg)
![License](https://img.shields.io/badge/license-MIT-blue.png)

Este repositório contém a implementação prática da **Unidade 2 - Integração Contínua (CI)** da disciplina de **Integração DevOps** (Curso de Ciência da Computação).

O objetivo do projeto é demonstrar a construção de uma aplicação ASP.NET Core Web API em .NET 10, com testes automatizados utilizando xUnit e um pipeline completo de Integração Contínua (CI) configurado no GitHub Actions.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem & Framework:** .NET 10 / ASP.NET Core Web API
- **Testes Automatizados:** xUnit
- **Controlo de Versão:** Git & GitHub
- **Ferramenta de CI:** GitHub Actions
- **Editor Recomendado:** VS Code / Visual Studio / JetBrains Rider

---

## 📁 Estrutura do Projeto

A solução foi estruturada separando o código da aplicação dos testes unitários, seguindo as melhores práticas de organização:

```text
devops-ci-dotnet10/
├── .github/
│   └── workflows/
│       └── ci.yml             # Workflow do GitHub Actions (Pipeline CI)
├── src/
│   └── DevOps.Api/            # Projeto ASP.NET Core Web API
│       ├── Services/
│       │   └── CalculadoraService.cs
│       ├── Program.cs
│       └── DevOps.Api.csproj
├── tests/
│   └── DevOps.Api.Tests/      # Projeto de Testes Automatizados (xUnit)
│       ├── CalculadoraServiceTests.cs
│       └── DevOps.Api.Tests.csproj
├── .gitignore
└── DevOpsCi.slnx              # Solução .NET
