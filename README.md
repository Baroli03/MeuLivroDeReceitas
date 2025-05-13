# 🍽️ API Livro de Receitas - Curso: Domine .NET

Este repositório contém o projeto prático desenvolvido durante o curso **"Domine .NET: das boas práticas ao Azure, do zero à publicação"**. A proposta é construir uma **API robusta de livro de receitas**, onde usuários poderão **compartilhar receitas, imagens, e muito mais**, utilizando as melhores práticas e ferramentas do ecossistema .NET.

---

## 🚀 O que este projeto cobre

Durante o curso, você aprenderá de forma **prática, simples e divertida**, com foco em 20% teoria e 80% prática:

- ✅ Criação de API RESTful com ASP.NET Core
- 🔒 Login com Google (OAuth 2.0)
- 🤖 Integração com ChatGPT
- ☁️ Publicação no Microsoft Azure
- 🧪 Testes unitários e de integração
- 📦 Docker e Docker Compose
- 🔁 Pipelines CI/CD com Azure DevOps
- 🧠 Domain-Driven Design (DDD)
- 🧱 Princípios SOLID
- 🔍 SonarCloud e análise de código
- 📋 Clean Code e boas práticas
- 🔐 Autenticação com JWT e Refresh Token
- 💬 Mensageria
- 🔄 Migrations com Entity Framework
- 🔧 FluentValidation
- 💉 Injeção de dependência
- 🔀 Git & GitFlow
- 📈 SCRUM e colaboração em equipe

---

## 📚 Sobre o projeto

A aplicação desenvolvida simula um **livro de receitas colaborativo**, permitindo:

- Cadastro e login de usuários
- Compartilhamento de receitas com título, descrição, ingredientes e imagem
- Busca e filtragem de receitas
- Sugestão de receitas com auxílio do ChatGPT
- Autenticação segura com OAuth e JWT
- Deploy automatizado no Azure

---

## 🧑‍💻 Para quem é este projeto

Este curso e projeto são ideais para:

- Pessoas com conhecimento básico em .NET (C#)
- Devs que querem dominar a criação de APIs REST do zero até a produção
- Profissionais que desejam aplicar boas práticas de desenvolvimento
- Quem quer se destacar com uso de ferramentas modernas como Docker, Azure, SonarCloud, etc.

---

## ✅ Pré-requisitos

Antes de iniciar, é recomendado que você tenha:

- Conhecimento básico em .NET e C#
- Visual Studio ou VS Code instalado
- Conta no GitHub e Azure (para deploy)
- Git instalado na máquina

---

## 🛠️ Tecnologias e Ferramentas

| Tecnologia        | Uso                                 |
|-------------------|--------------------------------------|
| ASP.NET Core      | Construção da API                   |
| Entity Framework  | ORM para banco de dados             |
| Azure DevOps      | CI/CD e Deploy                      |
| Docker            | Contêineres                         |
| SonarCloud        | Análise de código                   |
| JWT               | Autenticação                        |
| Google OAuth      | Login social                        |
| ChatGPT API       | Geração de sugestões de receita     |
| xUnit / NUnit     | Testes unitários                    |
| SCRUM             | Metodologia ágil usada no projeto   |

---

## 📦 Como rodar o projeto localmente

```bash
# Clone o repositório
git clone https://github.com/Baroli03/MeuLivroDeReceitas.git

# Acesse a pasta
cd MeuLivroDeReceitas

# Configure os secrets (variáveis de ambiente)

# Restaure os pacotes
dotnet restore

# Rode o projeto
dotnet run
