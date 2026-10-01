# IMRS – Intelligent Merge Request Review System

> AI-powered, rule-based automated code review system for GitLab Merge Requests.

## Overview

IMRS (Intelligent Merge Request Review System), GitLab Merge Request'lerini otomatik olarak analiz eden yapay zekâ destekli bir kod inceleme sistemidir.

Sistem, GitLab Webhook'ları aracılığıyla Merge Request olaylarını alır, ilgili kod değişikliklerini GitLab API üzerinden getirir ve yeni eklenen Java kodlarını aktif Rule Set'ler ile birlikte analiz eder.

Analiz sonucunda tespit edilen ihlaller yapılandırılmış şekilde işlenir ve ilgili Merge Request'e geri bildirim sağlanır. Analiz kayıtları PostgreSQL veritabanında saklanır.

## Key Features

- GitLab Webhook integration
- Merge Request change analysis
- Java code diff filtering
- Dynamic Rule Set management
- AI-powered code review
- Structured violation detection
- Automatic GitLab feedback
- PostgreSQL-based analysis records
- Jmix / Vaadin management interface
- MCP / JSON-RPC integration

## Architecture

```text
GitLab Merge Request
        ↓
GitLab Webhook
        ↓
Change / Diff Analysis
        ↓
Active Rule Sets
        ↓
LLM Analysis
        ↓
Structured Violations
        ↓
GitLab Feedback
        ↓
PostgreSQL
## Technology Stack

- Java 17
- Spring Boot
- Jmix
- Vaadin Flow
- Spring Security
- PostgreSQL
- Liquibase
- GitLab API
- GitLab Webhook
- LangChain4j
- Ollama
- Docker

## Internship Work

During my software engineering internship, I studied and analyzed the IMRS architecture and development workflow.

My work included:

- Understanding the overall project architecture and code structure
- Analyzing the GitLab Webhook and GitLab API workflow
- Examining the Merge Request diff analysis process
- Studying the Rule Set and LLM-based review flow
- Reviewing data flow and database interactions
- Analyzing security considerations
- Identifying potential improvements and future development areas

## Project Scope

This repository provides a high-level overview of the IMRS project for portfolio purposes.

The original source code, company-specific implementation details, credentials, configurations, and internal project files are not included in this repository.

## Note

IMRS was developed as part of an internship project in a company environment. This repository contains documentation and a high-level technical overview only.