# 🌸 Projeto Hanami Backend - API de Análise de Dados 

Este repositório contém o backend do Projeto Hanami, uma API corporativa para processamento de arquivos CSV/XLSX, persistência de dados e geração de relatórios analíticos.
O foco deste projeto é padronização, reprodutibilidade e escalabilidade, permitindo que qualquer desenvolvedor consiga iniciar o ambiente sem atritos.

## 📘 1. Visão Geral

Esse projeto de API foi projetado para:

- Receber arquivos CSV/XLSX via endpoint de upload

- Padronizar, validar e armazenar registros no banco de dados

- Disponibilizar relatórios analíticos de vendas, clientes, produtos e logística

- Servir como base para análises posteriores (BI, dashboards, insights)

A arquitetura segue os princípios:

- Separação clara entre Model, Repository, Service e Controller

- Baixa complexidade inicial

- Documentação integrada

- Logs e padronizações consistentes

## 🧭 2. Requisitos
| Ferramenta     | Versão Recomendada                |
| -------------- | --------------------------------- |
| Java           | 17+                               |
| Maven          | 3.8+                              |
| Spring Boot    | 4.x                               |
| Git            | Última versão estável             |

## ⚙️ 3. Setup Rápido (5 minutos)

Este guia garante que qualquer desenvolvedor consiga iniciar o ambiente sem fricção.

### 1️⃣ Clonar o repositório
```bash
git clone https://github.com/sua-organizacao/hanami-api.git

cd hanami-api
```
### 2️⃣ Construir o projeto
```bash
mvn clean install
```

### 3️⃣ Executar a aplicação
```bash
mvn spring-boot:run
```

## 🏗️ 4. Estrutura de Diretórios
```bash
/src
 └── /main
      └── /java/com/hanami/hanamiapi
           ├── controller/      # Entrada da API
           ├── service/         # Regras de negócio
           ├── repository/      # Persistência (JPA)
           ├── model/           # Entidades principais
 └── resources/
      ├── application.properties
      └── exemplos/             # Exemplos de arquivos CSV/XLSX
```