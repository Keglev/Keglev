[🇬🇧 English](https://github.com/Keglev/Keglev/blob/main/README.md) | 🇩🇪 Deutsch

# Carlos Keglevich

**Java Full Stack Entwickler** — Backend-fokussiert, domänengetrieben.

Ich entwickle Software, die reale Geschäftsprobleme löst: KI-gestützte 
Wartungswissen-Suche (RAG), Bestandskontrolle, Einkaufsprozesse — aus Aufgaben, 
die ich vor meiner Zeit als Entwickler selbst bearbeitet habe. Jedes Projekt ist 
bereitgestellt, dokumentiert und durch Tests abgedeckt, mit vollständiger 
CI/CD-Pipeline und Sicherheitsarchitektur.

Wohnhaft in Fürth. Aktuell im Aufbau domänengetriebener Backend-Systeme — immer offen für Gespräche über sinnvolle Engineering-Herausforderungen.

**Portfolio:** [carloskeglevich.vercel.app](https://carloskeglevich.de/) | **Docs & Projekte:** [keglev.github.io](https://keglev.github.io/) | **LinkedIn:** [linkedin.com/in/carloskeglevich](https://www.linkedin.com/in/carloskeglevich)

---

## Projekte

Alle Projekte sind dokumentiert und verlinkt unter → **[keglev.github.io](https://keglev.github.io/)**

| Projekt | Beschreibung | Stack |
|---|---|---|
| **AI Maintenance Assistant** | Retrieval-augmentierte Antworten aus den Wartungsprotokollen eines Werks. Fundierte Antworten mit Quellenangabe; rollenbasierte Filterung serverseitig; sprachübergreifende Suche (EN/DE). Live-Demo unter [maintenance.smartsupply.com.de](https://maintenance.smartsupply.com.de) — über 500 automatisierte Tests inkl. Playwright End-to-End und visueller Regression. | Java 21, Spring Boot 4.1, Angular 22, PostgreSQL + pgvector, Keycloak, Playwright |
| **Bestandskontrolle (StockEase)** | Produktionsreifes Bestands-Backend für KMU — Kapitalwert-Tracking, Excel-BI-Export, zustandsloses JWT, Flyway-verwaltete Schema-Versionierung. Live unter [bestandskontrolle.vercel.app](https://bestandskontrolle.vercel.app) — ohne teure ERP-Software. | Java 17, Spring Boot 3, PostgreSQL, JWT, Docker, Koyeb |
| **SmartSupplyPro** | Enterprise-System für Bestand & Einkauf — WAC-Finanzanalytik, SAP-artiges Soft-Delete, OAuth2/OIDC mit serverseitigen Sessions, zweisprachige Oberfläche (EN/DE). Live unter [smartsupplypro.de](https://www.smartsupplypro.de) mit Ein-Klick-Demo-Modus, kein Konto nötig. | Java 21, Spring Boot 4.1, React 19, TypeScript, Oracle Autonomous DB, Fly.io |

Alle drei Systeme sind bereitgestellt, dokumentiert und durch Tests abgedeckt — CI/CD-Pipelines (GitHub Actions), containerisierte Builds (Docker) und veröffentlichte Dokumentation (arc42, OpenAPI, ADRs).
---

## Kenntnisse & Technologien

### Backend & Datenbanken

[![Java](https://img.shields.io/badge/Java_21-007396?style=flat-square&logo=openjdk&logoColor=white)](https://github.com/Keglev)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot_4-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)](https://github.com/Keglev)
[![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=spring&logoColor=white)](https://github.com/Keglev)
[![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate)](https://github.com/Keglev)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL_17-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://github.com/Keglev)
[![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://github.com/Keglev)
[![Oracle](https://img.shields.io/badge/Oracle_Autonomous_DB-F80000?style=flat-square&logo=oracle&logoColor=white)](https://github.com/Keglev)
[![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)](https://github.com/Keglev)
[![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=flat-square&logo=keycloak&logoColor=white)](https://github.com/Keglev)
[![OAuth2](https://img.shields.io/badge/OAuth2%2FOIDC-3C3C3C?style=flat-square&logo=auth0&logoColor=white)](https://github.com/Keglev)
[![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=json-web-tokens&logoColor=white)](https://github.com/Keglev)

### Frontend & UI

[![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)](https://github.com/Keglev)
[![Angular](https://img.shields.io/badge/Angular_22-DD0031?style=flat-square&logo=angular&logoColor=white)](https://github.com/Keglev)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/Keglev)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)](https://github.com/Keglev)
[![Material-UI](https://img.shields.io/badge/MUI-007FFF?style=flat-square&logo=mui&logoColor=white)](https://github.com/Keglev)
[![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=react-query&logoColor=white)](https://github.com/Keglev)
[![i18n](https://img.shields.io/badge/i18n_EN%2FDE-0d1117?style=flat-square&logo=google-translate&logoColor=white)](https://github.com/Keglev)

### Testing & Qualität

[![JUnit 5](https://img.shields.io/badge/JUnit_5%2F6-25A162?style=flat-square&logo=junit5&logoColor=white)](https://github.com/Keglev)
[![Mockito](https://img.shields.io/badge/Mockito-5A9F7C?style=flat-square&logo=java&logoColor=white)](https://github.com/Keglev)
[![Testcontainers](https://img.shields.io/badge/Testcontainers-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/Keglev)
[![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)](https://github.com/Keglev)
[![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)](https://github.com/Keglev)
[![JaCoCo](https://img.shields.io/badge/JaCoCo_Coverage-B07219?style=flat-square&logo=java&logoColor=white)](https://github.com/Keglev)

### DevOps & Infrastruktur

[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/Keglev)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)](https://github.com/Keglev)
[![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apache-maven&logoColor=white)](https://github.com/Keglev)
[![Fly.io](https://img.shields.io/badge/Fly.io-8B5CF6?style=flat-square&logo=flydotio&logoColor=white)](https://github.com/Keglev)
[![Koyeb](https://img.shields.io/badge/Koyeb-121212?style=flat-square&logo=koyeb&logoColor=white)](https://github.com/Keglev)
[![Trivy](https://img.shields.io/badge/Trivy_Security_Scan-1904DA?style=flat-square&logo=aqua&logoColor=white)](https://github.com/Keglev)

### Architektur & Dokumentation

[![arc42](https://img.shields.io/badge/arc42-2A6DF4?style=flat-square&logo=readthedocs&logoColor=white)](https://github.com/Keglev)
[![ADRs](https://img.shields.io/badge/Architecture_Decision_Records-6B7280?style=flat-square&logo=markdown&logoColor=white)](https://github.com/Keglev)
[![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?style=flat-square&logo=openapi-initiative&logoColor=white)](https://github.com/Keglev)
[![ReDoc](https://img.shields.io/badge/ReDoc-E6522C?style=flat-square&logo=redocly&logoColor=white)](https://github.com/Keglev)
[![Typedoc](https://img.shields.io/badge/Typedoc-2A6DF4?style=flat-square&logo=typescript&logoColor=white)](https://github.com/Keglev)

---

## Zertifizierungen in Vorbereitung

- **Oracle Certified Associate (OCA)** — Java SE — in Vorbereitung (Comcave College, Fürth)
- **Oracle Certified Professional (OCP)** — Java SE — in Vorbereitung (Comcave College, Fürth)

---

## Sprachen

- Portugiesisch — Muttersprache
- Englisch — Fließend
- Deutsch — Fließend

---

## GitHub-Statistiken

[![Carlos Keglevich's GitHub stats](https://github-stats-extended-frontend-theta-nine.vercel.app/api?username=Keglev&show_icons=true&theme=dark&hide_border=true&count_private=true)](https://github.com/Keglev)

[![Top Langs](https://github-stats-extended-frontend-theta-nine.vercel.app/api/top-langs/?username=Keglev&layout=compact&langs_count=6&theme=dark&hide_border=true&hide=jupyter%20notebook)](https://github.com/Keglev)

[![Contribution Grid](https://ghchart.rshah.org/38bdf8/Keglev)](https://github.com/Keglev)