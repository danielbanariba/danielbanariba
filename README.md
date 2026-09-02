# <img width="30px" margin="0px" src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif"> Hi, I'm Daniel Banariba <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50">

### 💻 Data Engineer & AI Engineer  |  Tegucigalpa, Honduras

<img src="/img/banner.png">

## About

**Daniel Banariba — Data Engineer and AI Engineer based in Tegucigalpa, Honduras.**
Currently RPA Developer & Data Engineer at Grupo Farinter.

I build tools that let AI operate production infrastructure, and the data
pipelines underneath it.

**AI engineering — my differentiator.** Five MCP (Model Context Protocol) servers
running in production, letting Claude Code operate Dagster, SQL Server, SMB,
Microsoft Graph and API health checks directly. Hardened with a read-only SQL
validator, blast-radius policies with hard stops on destructive operations, and
OAuth2 via Zitadel. Token consumption optimized ~10–20x. Day to day I work with
sub-agent orchestration, Anthropic Agent Skills, slash commands and hooks across
Claude Code, Codex CLI and OpenCode — under SDD and strict TDD.

**Data engineering.** Production ETL pipelines in Dagster over a corporate SQL
Server DWH: automated banking reconciliation (Credomatic/BAC, Ficohsa) and
transactional reconciliation via SMB, with file sensors for automatic new-file
detection. Cut a monthly demand forecast of ~23,000 series from ~18 hours to
~61 minutes in production — byte-identical, deterministic output, no new
dependencies.

**Data platform reliability.** An autonomous watchdog that detects stuck pipelines
by comparing runtimes against baselines learned from 100+ executions, cancels and
relaunches them, and alerts over Telegram as a systemd service. Redesigned Dagster
failure alerts from send-immediate to freshness-aware, which killed the noise from
transient self-recovered failures. A generic AssetCheckEvaluation sensor uncovered
a silent 182,928-row duplicate that had been passing with every run green.

**Power BI as Code.** A PBIR/TMDL pipeline with a custom bind-check validator
against the official schemas, CI in GitHub Actions, and agentic verification: a
watcher that on every push validates, reloads and screenshots the report so an AI
can verify what actually rendered.

**Backend & systems.** hvault — a service written in pure Rust (CLI + daemon) that
synchronizes TLS certificates across nodes using HashiCorp Vault (KV-v2), with
atomic hot-reload, x509 validation without OpenSSL, and a Leptos/WASM admin UI over
OIDC. Also a full-stack competitive pricing dashboard in Python (Reflex): 8
analytical views over ~7,700 competitor SKUs with SCD2 margin-erosion detection,
801 tests, CI/CD to Dokploy.

**Earlier.** REST APIs with FastAPI and NestJS. VITEK medical-equipment integration
over ASTM/HL7 protocols at Analiza Laboratorios Clínicos. E2E test automation with
Playwright at GuabaBIT.

- 📍 Tegucigalpa, Honduras — remote-friendly (LATAM and US time zones)
- 🌐 Portfolio: https://www.danielbanariba.dev
- 📧 danielbanariba@protonmail.com
- 🗣️ Spanish (native), English

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class SoftwareEngineer:

    def __init__(self):
        self.name = "Daniel Barrientos Anariba"
        self.role = "Data Engineer & AI Engineer"
        self.location = "Tegucigalpa, Honduras"
        self.language_spoken = ["es_HN", "en_US"]
        self.passions = ["Data Pipelines", "AI Engineering", "Clean Code"]
        self.coffee_level = 100  # Always full

    def say_hi(self):
        print("¡Hola! Thanks for dropping by - hope you find some of my work interesting.")
        print("Code with passion, debug with patience!")

    def refill_coffee(self):
        if self.coffee_level < 50:
            self.coffee_level = 100
            print("☕ Coffee refilled, ready to code again!")
        else:
            print("☕ Still have enough fuel to keep coding...")


# Always caffeinated, always coding
me = SoftwareEngineer()
me.say_hi()
```

## My Skill Set

<table><tr><td valign="top" width="33%">

### Languages

<div align="center">  
<img style="margin: 10px" src="/img/lenguage/python.svg" alt="Python" height="50" />  
<img style="margin: 10px" src="/img/lenguage/java.svg" alt="Java" height="50" />  
<img style="margin: 10px" src="/img/lenguage/typescript.svg" alt="TypeScript" height="50" />  
<img style="margin: 10px" src="/img/lenguage/rust.svg" alt="Rust" height="50" />  
<img style="margin: 10px" src="/img/lenguage/cpp.svg" alt="C++" height="50" />  
<img style="margin: 10px" src="/img/lenguage/r.svg" alt="R" height="50" />  
</div>

</td><td valign="top" width="33%">

### Frameworks

<div align="center">  
<img style="margin: 10px" src="/img/framework/spring.svg" alt="Spring Boot" height="50" />  
<img style="margin: 10px" src="/img/framework/fastapi.svg" alt="FastAPI" height="50" />  
<img style="margin: 10px" src="/img/framework/reflex.svg" alt="Reflex" height="50" />  
<img style="margin: 10px" src="/img/framework/astro.svg" alt="Astro" height="50" />  
<img style="margin: 10px" src="/img/framework/django.svg" alt="Django" height="50" />  
<img style="margin: 10px" src="/img/framework/expressjs_dark.svg" alt="Express.js" height="50" />  
<img style="margin: 10px" src="/img/framework/nestjs.svg" alt="NestJS" height="50" />  
</div>

</td><td valign="top" width="33%">

### Databases

<div align="center">  
<img style="margin: 10px" src="/img/database/mysql.svg" alt="MySQL" height="50" />  
<img style="margin: 10px" src="/img/database/oracle.svg" alt="Oracle" height="50" />  
<img style="margin: 10px" src="/img/database/postgresql.svg" alt="PostgreSQL" height="50" />  
<img style="margin: 10px" src="/img/database/mongodb.svg" alt="MongoDB" height="50" />  
<img style="margin: 10px" src="/img/database/sqlite.svg" alt="SQLite" height="50" />  
<img style="margin: 10px" src="/img/database/aws-dynamodb.svg" alt="DynamoDB" height="50" />  
</div>

</td></tr></table>

<table><tr><td valign="top" width="33%">

### DevOps

<div align="center">  
<img style="margin: 10px" src="/img/infraestructura/aws.svg" alt="AWS" height="50" />  
<img style="margin: 10px" src="/img/infraestructura/azure.svg" alt="Azure" height="50" />  
<img style="margin: 10px" src="/img/infraestructura/cloudflare.svg" alt="Cloudflare" height="50" />  
<img style="margin: 10px" src="/img/infraestructura/docker.svg" alt="Docker" height="50" />  
<img style="margin: 10px" src="/img/infraestructura/terraform.svg" alt="Terraform" height="50" />  
<img style="margin: 10px" src="/img/infraestructura/vercel.svg" alt="Vercel" height="50" />  
</div>

</td><td valign="top" width="33%">

### QA & Testing

<div align="center">  
<img style="margin: 10px" src="/img/qa-testing/postman.svg" alt="Postman" height="50" />  
<img style="margin: 10px" src="/img/qa-testing/selenium.svg" alt="Selenium" height="50" />  
<img style="margin: 10px" src="/img/qa-testing/jest.svg" alt="Jest" height="50" />  
<img style="margin: 10px" src="/img/qa-testing/cypress.svg" alt="Cypress" height="50" />  
<img style="margin: 10px" src="/img/qa-testing/playwright.svg" alt="Playwright" height="50" />  
<img style="margin: 10px" src="/img/qa-testing/jira.svg" alt="Jira" height="50" />  
<img style="margin: 10px" src="/img/qa-testing/apidog.svg" alt="APIdog" height="50" />  
</div>

</td><td valign="top" width="33%">

### Tools

<div align="center">  
<img style="margin: 10px" src="/img/tools/illustrator.svg" alt="Illustrator" height="50" />  
<img style="margin: 10px" src="/img/tools/photoshop.svg" alt="Photoshop" height="50" />  
<img style="margin: 10px" src="/img/tools/premiere.svg" alt="Premiere" height="50" />  
<img style="margin: 10px" src="/img/tools/after-effects.svg" alt="After Effects" height="50" />  
<img style="margin: 10px" src="/img/tools/obsidian.svg" alt="Obsidian" height="50" />  
<img style="margin: 10px" src="/img/tools/bitwarden.svg" alt="Bitwarden" height="50" />  
<img style="margin: 10px" src="/img/tools/todoist.svg" alt="Todoist" height="50" />  
<img style="margin: 10px" src="/img/tools/powertoys.svg" alt="PowerToys" height="50" />  
<img style="margin: 10px" src="/img/tools/tor.svg" alt="Tor" height="50" />  
</div>

</td></tr></table>

<table><tr><td valign="top" width="100%">

### AI Tools

<div align="center">  
<img style="margin: 10px" src="/img/ia/copilot.svg" alt="GitHub Copilot" height="50" />  
<img style="margin: 10px" src="/img/ia/claude.svg" alt="Claude" height="50" />  
<img style="margin: 10px" src="/img/ia/openai.svg" alt="OpenAI" height="50" />  
<img style="margin: 10px" src="/img/ia/gemini.svg" alt="Gemini" height="50" />  
<img style="margin: 10px" src="/img/ia/perplexity.svg" alt="Perplexity" height="50" />  
<img style="margin: 10px" src="/img/ia/ollama.svg" alt="Ollama" height="50" />  
<img style="margin: 10px" src="/img/ia/deepseek.svg" alt="DeepSeek" height="50" />  
<img style="margin: 10px" src="/img/ia/cursor.svg" alt="Cursor" height="50" />  
<img style="margin: 10px" src="/img/ia/Qwen_dark.svg" alt="Qwen" height="50" />  
</div>

</td></tr></table>

### ⚡ Tech Snapshot

```mermaid
mindmap
  root((Skills))
    ((Languages))
      Python
      Java
      TypeScript
      Rust
      C++
      R
    ((Frameworks))
      Spring Boot
      FastAPI
      Reflex
      Astro
      Django
      Express.js
      NestJS
      React
    ((Data & AI))
      Dagster
      dbt
      Polars
      Power BI as Code
      MCP - Model Context Protocol
      Agentic AI
      LLMs
      Anthropic API
      Prompt Engineering
    ((Databases))
      MySQL
      Oracle
      PostgreSQL
      MongoDB
      SQLite
      DynamoDB
    ((DevOps))
      AWS
        S3
        SNS
        DynamoDB
        Lambda
      Azure
      Cloudflare
      Docker
      Terraform
      Vercel
      Kubernetes
    ((QA & Testing))
      Postman
      Selenium
      Jest
      Cypress
      Playwright
      Jira
      Apidog
      Swagger
    ((AI Tools))
      GitHub Copilot
      Claude
      OpenAI
      Gemini
      Perplexity
      Ollama
      DeepSeek
      Cursor
      Qwen
    ((Tools))
      Adobe Suite
        Illustrator
        Photoshop
        Premiere
        After Effects
      Productivity
        Obsidian
        Bitwarden
        Todoist
        PowerToys
      Security
        Tor
```

# 🔭Actions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/holic-x/holic-x/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/holic-x/holic-x/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/adorabled4/adorabled4/output/github-contribution-grid-snake.svg">
</picture>

<img align='right' src='https://user-images.githubusercontent.com/5713670/87202985-820dcb80-c2b6-11ea-9f56-7ec461c497c3.gif' width='200"'>

## 📫 Contáctame:

<p>
  <a href="https://www.instagram.com/danielbanariba">
    <img align="left" alt="Daniel Banariba | Instagram" width="22px" src="/img/contact/instagram.svg"/>
  </a>
  <a href="https://www.linkedin.com/in/danielbanariba">
    <img align="left" alt="Daniel Banariba | LinkdeIn" width="22px" src="/img/contact/linkedin.svg"/>
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=60&section=footer&width=100"/>
</p>
