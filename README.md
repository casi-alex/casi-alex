<div align="center">

# Alejandro Casillas

### AI Automation & QA Engineer &nbsp;·&nbsp; LLM Agents &nbsp;·&nbsp; MCP & RAG &nbsp;·&nbsp; Python &nbsp;·&nbsp; n8n

<p>
  <a href="mailto:alexcasillaslab@gmail.com">
    <img src="https://img.shields.io/badge/alexcasillaslab%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/casillasalex" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-casillasalex-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  &nbsp;
  <a href="https://www.notion.so/Portfolio-2cd3f54380c280d4a6f8d993283b232f" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-Notion-000000?style=flat&logo=notion&logoColor=white" alt="Portfolio"/>
  </a>
</p>

<p>
  <img src="https://img.shields.io/badge/Guadalajara%2C%20Mexico-222?style=flat&logo=googlemaps&logoColor=white"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Remote--Ready-00b894?style=flat&logo=checkmarx&logoColor=white"/>
  &nbsp;
  <img src="https://img.shields.io/badge/EN%20%7C%20ES-Bilingual-6c5ce7?style=flat"/>
</p>

</div>

---

## About

I build and test **LLM agent systems end to end** (n8n, PostgreSQL, Google Calendar, WhatsApp) and publish what I build so it can be inspected. I founded **CupoTotal**, an AI appointment assistant for healthcare and beauty businesses, with separate AI agents for administrators and patients, **AES-256-GCM field encryption**, an audit trail and **18 documented architecture decisions**. My latest public project is a **read-only MCP server over a RAG index** (PostgreSQL + pgvector) that returns sourced results, with a reproducible retrieval evaluation.

I started in QA: a portfolio of **7 projects** and **150+ defects identified**, using Selenium + Python + Page Object Model and boundary value analysis. Before that, 4+ years of technical support for U.S. telecommunications customers. A troubleshooting guide I wrote was adopted by **150+ agents and 10 supervisors within a week**, and team average handle time dropped 34%.

> *I don't just find bugs — I document them in a way that shortens the path from detection to resolution.*

---

## Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">ADR Knowledge Base &mdash; MCP Server &amp; RAG</h3>
      <div align="center">
        <a href="https://github.com/casi-alex/adr-rag-mcp" target="_blank">
          <img src="https://img.shields.io/badge/CODE-0d1117?style=for-the-badge&logo=github&logoColor=white"/>
        </a>
        <br/><br/>
        <p align="left">
          <strong>Python &middot; MCP SDK &middot; PostgreSQL &middot; pgvector &middot; pytest</strong><br/>
          Read-only MCP server over a RAG index of architecture decision records. Every result
          carries its provenance (document, heading, similarity score). Read-only database session,
          corpus treated as untrusted data, index that fails closed if the embedding model changes.
          Evaluated on 18 questions (hit@3 14/14 on the answerable ones); 63 tests.
        </p>
      </div>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">CupoTotal &mdash; Architecture Case Study</h3>
      <div align="center">
        <a href="https://github.com/casi-alex/cupototal-case-study" target="_blank">
          <img src="https://img.shields.io/badge/CODE-0d1117?style=for-the-badge&logo=github&logoColor=white"/>
        </a>
        <br/><br/>
        <p align="left">
          <strong>n8n &middot; PostgreSQL &middot; WhatsApp &middot; LLM agents</strong><br/>
          Architecture case study of an AI appointment assistant I founded: separate agents for
          administrators and patients, AES-256-GCM field encryption, audit trail, rate limiting
          and 18 architecture decision records. Pilot with a medical center in final validation.
        </p>
      </div>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">Urban Routes &mdash; E2E Automation</h3>
      <div align="center">
        <a href="https://github.com/casi-alex/qa-project-Urban-Routes-es" target="_blank">
          <img src="https://img.shields.io/badge/CODE-0d1117?style=for-the-badge&logo=github&logoColor=white"/>
        </a>
        <br/><br/>
        <p align="left">
          <strong>Selenium WebDriver &middot; Python &middot; pytest &middot; Page Object Model</strong><br/>
          9 automated E2E tests covering the complete taxi booking flow. POM architecture separates
          test logic from UI locators. Explicit waits for dynamic elements; Selenium Manager
          handles ChromeDriver automatically.
        </p>
      </div>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">Urban Grocers &mdash; API Automation</h3>
      <div align="center">
        <a href="https://github.com/casi-alex/qa-project-Urban-Grocers-app-es" target="_blank">
          <img src="https://img.shields.io/badge/CODE-0d1117?style=for-the-badge&logo=github&logoColor=white"/>
        </a>
        <br/><br/>
        <p align="left">
          <strong>Python &middot; requests &middot; pytest &middot; REST API</strong><br/>
          9 automated API tests targeting boundary values (1/511/512 chars), special input types,
          and error handling. Shared assertion helpers isolate HTTP logic from test cases.
          Built around boundary value analysis as a core methodology.
        </p>
      </div>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">Urban Scooter &mdash; Manual &amp; API Testing</h3>
      <div align="center">
        <a href="https://www.notion.so/Portfolio-2cd3f54380c280d4a6f8d993283b232f?p=3563f54380c280b69373df29b43373d6&pm=c" target="_blank">
          <img src="https://img.shields.io/badge/VIEW%20PROJECT-000?style=for-the-badge&logo=notion&logoColor=white"/>
        </a>
        <br/><br/>
        <p align="left">
          <strong>Jira &middot; Postman &middot; Chrome &middot; Opera &middot; Android Studio</strong><br/>
          <strong>58 defects &mdash; 12 critical, 10 flow-blocking.</strong> Expanded coverage to
          Chrome + Opera in parallel; Opera surfaced a complete order flow blocker invisible
          in Chrome alone. API checklists structured by HTTP response code with direct
          database validation. Approved first submission.
        </p>
      </div>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">Urban Grocers &mdash; Manual API Testing</h3>
      <div align="center">
        <a href="https://www.notion.so/Portfolio-2cd3f54380c280d4a6f8d993283b232f?p=33c3f54380c28075a0d2ec3096280deb&pm=c" target="_blank">
          <img src="https://img.shields.io/badge/VIEW%20PROJECT-000?style=for-the-badge&logo=notion&logoColor=white"/>
        </a>
        <br/><br/>
        <p align="left">
          <strong>Postman &middot; Jira &middot; Boundary Value Analysis</strong><br/>
          57 test cases &middot; <strong>24 defects</strong> including 6 high-priority boundary
          failures. The API accepted <code>productsCount=16</code> (max:15),
          <code>productsWeight=6.1kg</code> (max:6.0), and <code>deliveryTime=7</code>
          and <code>23</code> (valid window: 8&ndash;22). All three tested parameters
          failed at their limits. Approved first submission.
        </p>
      </div>
    </td>
  </tr>
</table>

<div align="center">
  <a href="https://www.notion.so/Portfolio-2cd3f54380c280d4a6f8d993283b232f" target="_blank">
    <img src="https://img.shields.io/badge/View%20All%207%20QA%20Projects%20%E2%86%92-000?style=for-the-badge&logo=notion&logoColor=white"/>
  </a>
</div>

---

## Tech Stack

**AI, Agents & Retrieval**

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![LLM Agents](https://img.shields.io/badge/LLM%20Agents-222?style=flat)
![MCP](https://img.shields.io/badge/MCP-222?style=flat)
![RAG](https://img.shields.io/badge/RAG-222?style=flat)
![pgvector](https://img.shields.io/badge/pgvector-316192?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

**Test Automation & QA**

![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat&logo=selenium&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-fff?style=flat&logo=pytest&logoColor=000)
![Page Object Model](https://img.shields.io/badge/Page%20Object%20Model-222?style=flat)
![Boundary Value Analysis](https://img.shields.io/badge/Boundary%20Value%20Analysis-222?style=flat)
![Equivalence Partitioning](https://img.shields.io/badge/Equivalence%20Partitioning-222?style=flat)

**API & Backend**

![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-005571?style=flat)
![JSON](https://img.shields.io/badge/JSON-000?style=flat&logo=json&logoColor=fff)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

**Languages & Web**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=000)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-639?style=flat&logo=css&logoColor=fff)

**Tools & Systems**

![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-121011?style=flat&logo=github&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-1976D2?style=flat&logo=androidstudio&logoColor=white)
![DevTools](https://img.shields.io/badge/Chrome%20DevTools-4285F4?style=flat&logo=googlechrome&logoColor=white)
![Linux CLI](https://img.shields.io/badge/Linux%20CLI-FCC624?style=flat&logo=linux&logoColor=000)
![Agile Scrum](https://img.shields.io/badge/Agile%20%7C%20Scrum-0052CC?style=flat)

---

<div align="center">
  <sub>Open to remote roles in AI automation, software and QA engineering &nbsp;·&nbsp; Guadalajara, Mexico &nbsp;·&nbsp; <a href="mailto:alexcasillaslab@gmail.com">alexcasillaslab@gmail.com</a></sub>
</div>
