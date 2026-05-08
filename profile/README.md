# Pulsar

Pulsar é uma plataforma de descoberta de eventos culturais via mapa interativo, com foco inicial em Salvador-BA. O objetivo é conectar pessoas a experiências culturais de forma simples, visual e personalizada.

---

## Status do Projeto

| Etapa | Status |
|---|---|
| Concepção e arquitetura | ✅ Concluída |
| Documentação (SDD, PRD, Roadmap) | ✅ Concluída |
| Desenvolvimento do backend (pulsar-api) | 🔄 Em andamento |
| Desenvolvimento do frontend (pulsar-app) | 🔄 Em andamento |
| Desenvolvimento do scraper (pulsar-scraper) | 🔄 Em andamento |
| Portal administrativo (pulsar-admin) | 📋 Planejado |

> O projeto encontra-se em fase de MVP.

---

## Repositórios

### 🗄️ pulsar-api
Backend da plataforma. API REST construída com **.NET 10** e banco de dados **PostgreSQL + PostGIS**. Responsável pela autenticação social, busca geoespacial de eventos e webhooks para integração com o scraper.

### 📱 pulsar-app
Aplicativo mobile desenvolvido com **React Native / Expo**. Oferece mapa interativo, busca de eventos, salvamento de favoritos e login social.

### 🕷️ pulsar-scraper
Worker para coleta automatizada de eventos do **Instagram** e **Sympla** usando **Playwright**. Implementação em **.NET ou Python** (a definir).

### 📚 pulsar-docs
Documentação centralizada do projeto. Contém SDD, Product Strategy, Roadmap, Design Guides e Database Scripts.

### 🛠️ pulsar-admin *(planejado)*
Portal administrativo desenvolvido com **Blazor** para curadoria e moderação de eventos.

---

## Stack Tecnológica

| Repositório | Tecnologias Principais |
|---|---|
| pulsar-api | .NET 10, ASP.NET Core, PostgreSQL, PostGIS, Entity Framework Core |
| pulsar-app | React Native, Expo, TypeScript |
| pulsar-scraper | .NET ou Python, Playwright |
| pulsar-docs | Markdown, Docusaurus (a definir) |
| pulsar-admin | Blazor, .NET |

---

## Documentação

A documentação completa está centralizada no repositório **pulsar-docs**. Principais documentos:

- [Product Strategy](https://github.com/cultural-app/pulsar-docs/blob/main/product/product-strategy.md)
- [Product Roadmap](https://github.com/cultural-app/pulsar-docs/blob/main/product/roadmap.md)
- [PRD — Product Requirements Document](https://github.com/cultural-app/pulsar-docs/blob/main/product/prd.md)
- [SDD — Backend (pulsar-api)](https://github.com/cultural-app/pulsar-docs/blob/main/architecture/sdd-backend.md)
- [SDD — Frontend (pulsar-app)](https://github.com/cultural-app/pulsar-docs/blob/main/architecture/sdd-frontend.md)
- [SDD — Scraper (pulsar-scraper)](https://github.com/cultural-app/pulsar-docs/blob/main/architecture/sdd-scraper.md)
- [Design Guides](https://github.com/cultural-app/pulsar-docs/blob/main/design/design-guides.md)
- [Database Scripts](https://github.com/cultural-app/pulsar-docs/blob/main/database/scripts.md)

---

## Como Contribuir

Consulte o guia de contribuição disponível em cada repositório (`CONTRIBUTING.md`) antes de enviar alterações. O projeto adota o seguinte padrão de branches:

- `main` — código estável e revisado
- `develop` — branch de integração
- `feature/*` — novas funcionalidades
- `fix/*` — correções de bugs
- `chore/*` — tarefas técnicas e manutenção

Pull requests devem ser abertos contra a branch `develop` e passarão por revisão antes do merge.

---

## Licença

Este projeto é proprietário. Todo o código-fonte e documentação são de uso interno e não podem ser copiados, distribuídos ou utilizados sem autorização expressa.

---

## Time

Pulsar é desenvolvido pela equipe da organização **cultural-app**. Para dúvidas ou contato, abra uma issue no repositório correspondente ou entre em contato diretamente com os mantenedores da organização.
