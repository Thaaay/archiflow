# ArchiFlow - Sistema de Gestão para Arquitetura e Design

![ArchiFlow Logo](https://img.shields.io/badge/ArchiFlow-Architecture%20Management-blue)
![Ruby on Rails](https://img.shields.io/badge/Ruby%20on%20Rails-7.0-red)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)
![Docker](https://img.shields.io/badge/Docker-✓-blue)

Sistema completo para gestão de projetos de arquitetura, design de interiores e construção.

## 🚀 Funcionalidades

- 📋 **Gestão de Projetos** - Controle completo do ciclo de vida
- 🎨 **Moodboards Digitais** - Coleções visuais organizadas
- 📐 **Biblioteca de Materiais** - Catálogo com fornecedores
- 💰 **Orçamentos Automáticos** - Cálculo baseado em áreas
- 📅 **Agenda de Visitas** - Gestão de cronogramas
- 👁️ **Visualizador 3D** - Integração com modelos

## 🛠️ Tecnologias

- **Backend:** Ruby on Rails 7.0
- **Frontend:** React + TypeScript
- **Banco de Dados:** PostgreSQL
- **Container:** Docker + Docker Compose
- **Uploads:** AWS S3 / Active Storage

## 📦 Instalação Rápida

```bash
# Clone o projeto
git clone https://github.com/seu-usuario/archiflow.git
cd archiflow

# Suba os containers
docker-compose build
docker-compose up

# Execute as migrações
docker-compose exec web rails db:create
docker-compose exec web rails db:migrate
docker-compose exec web rails db:seed
