# Rolando Vásquez

**Desarrollador full stack y móvil · IA aplicada** — Tarija, Bolivia · abierto a trabajo remoto

Construyo apps con Flutter, interfaces web con React y backends con TypeScript (NestJS) y Python,
con pruebas automatizadas y CI desde el primer commit. Publiqué 4 apps en Google Play y App Store para empresas de delivery
y movilidad, y aplico IA (RAG, agentes y visión) a problemas concretos.

[CV web](https://rolandocesar-prog-dev.github.io/cv-web/) ·
[CV en PDF](https://rolandocesar-prog-dev.github.io/cv-web/CV_Rolando_Vasquez_Tavera.pdf) ·
[LinkedIn](https://www.linkedin.com/in/rolando-cesar-vasquez-tavera-b62235222) ·
[rolando.sha256@gmail.com](mailto:rolando.sha256@gmail.com)

**English:** [summary below](#in-english) ·
[CV in English](https://rolandocesar-prog-dev.github.io/cv-web/en/) ·
[PDF](https://rolandocesar-prog-dev.github.io/cv-web/CV_Rolando_Vasquez_Tavera_EN.pdf)

## Proyectos

Cada repositorio tiene requisitos y diseño escritos, pruebas automatizadas, CI y una demo.

| Proyecto | Qué resuelve | Stack | Probar |
| --- | --- | --- | --- |
| [Asistente RAG sobre documentación](https://github.com/rolandocesar-prog-dev/docs-rag-assistant) | Responde preguntas sobre la documentación de Kubernetes citando cada fuente, y avisa cuando la respuesta no está. Evaluación automática: documento correcto en el 100 % de las preguntas de prueba. | Python · FastAPI · PostgreSQL + pgvector · Docker | [Demo](https://github.com/rolandocesar-prog-dev/docs-rag-assistant/blob/main/docs/demo.gif) |
| [API de inventario](https://github.com/rolandocesar-prog-dev/inventory-api-nestjs) | Inventario con historial auditable, JWT con renovación rotativa y stock que nunca queda negativo con operaciones simultáneas. 184 pruebas. | NestJS · TypeScript · PostgreSQL · Docker | [API en vivo](https://inventory-api-c5yi.onrender.com/docs) |
| [Panel web de inventario](https://github.com/rolandocesar-prog-dev/inventory-web-react) | Interfaz web de la API de inventario: catálogo, kardex, movimientos y administración. Tokens rotativos con una sola renovación y escrituras que nunca se reintentan solas. 143 pruebas y 16 de extremo a extremo con accesibilidad. | React · TypeScript · TanStack Query · Tailwind | [Panel en vivo](https://rolandocesar-prog-dev.github.io/inventory-web-react/) |
| [Reservas de turnos](https://github.com/rolandocesar-prog-dev/turnos-app-flutter) | Reservas sin turnos duplicados para canchas y consultorios, con panel del negocio y recordatorios push. 173 pruebas de la app. | Flutter · Firebase · Cloud Functions | [Web en vivo](https://turnos-rv-portafolio.web.app) |
| [Escáner de facturas con IA](https://github.com/rolandocesar-prog-dev/invoice-scanner-flutter) | Lee la foto de una factura con un modelo de visión local y, tras la revisión de una persona, registra las entradas de stock sin duplicados. 10/10 facturas de prueba perfectas. | Flutter · Riverpod · Ollama | [Demo](https://github.com/rolandocesar-prog-dev/invoice-scanner-flutter/blob/main/docs/demo.gif) |
| [Agente de inventario con MCP](https://github.com/rolandocesar-prog-dev/inventory-agent-mcp) | Servidor MCP y agente que mueven el inventario conversando en español. Ningún movimiento se registra sin aprobación humana: 0 escrituras sin aprobación en 18 escenarios. | TypeScript · MCP · Ollama | [Demo](https://github.com/rolandocesar-prog-dev/inventory-agent-mcp/blob/main/docs/demo.gif) |
| [Suite E2E con Playwright](https://github.com/rolandocesar-prog-dev/qa-e2e-playwright) | 139 pruebas en cuatro navegadores, 13 defectos reales documentados, accesibilidad, regresión visual y 0 pruebas inestables en 30 ejecuciones del CI. | Playwright · TypeScript · Docker | [Reporte](https://rolandocesar-prog-dev.github.io/qa-e2e-playwright/) |

## Tecnologías

- **Núcleo:** Flutter, Dart, TypeScript, JavaScript, React, NestJS, Python, PostgreSQL, Firebase,
  Docker.
- **IA y calidad:** RAG y búsqueda híbrida, agentes con MCP, pruebas E2E con Playwright, CI/CD con
  GitHub Actions.
- **También:** React Native, Angular, Spring Boot, Java, PHP, MySQL.

Las apps publicadas en las tiendas y mi experiencia están en el
[CV web](https://rolandocesar-prog-dev.github.io/cv-web/).

## In English

**Full stack and mobile developer · Applied AI** — Tarija, Bolivia · open to remote work

I build apps with Flutter, web interfaces with React and backends with TypeScript (NestJS) and
Python, with automated tests and CI from the first commit. I published 4 apps on Google Play and
the App Store for delivery and ride-hailing companies, and I apply AI (RAG, agents and vision) to
concrete problems.

Every project above has written requirements and design, automated tests, CI and a demo. Each
README starts with a short summary in English; the code and the documentation are in Spanish.

- **RAG assistant for documentation** — answers from the Kubernetes docs, citing every source.
- **Inventory API** — REST API whose stock never goes negative under concurrent requests.
- **Inventory web dashboard** — React app that never duplicates a stock movement.
- **Appointment booking** — Flutter and Firebase booking app with no double bookings.
- **AI invoice scanner** — reads supplier invoices with a local vision model, with human review.
- **Inventory agent with MCP** — conversational agent that never writes without human approval.
- **E2E suite with Playwright** — 139 tests on four browsers and 0 flaky tests in 30 CI runs.

**Skills:** Flutter, Dart, TypeScript, React, NestJS, Python, PostgreSQL, Firebase, Docker, RAG,
MCP agents, Playwright and GitHub Actions. **Languages:** Spanish (native), English (B1,
technical).

[CV in English](https://rolandocesar-prog-dev.github.io/cv-web/en/) ·
[PDF](https://rolandocesar-prog-dev.github.io/cv-web/CV_Rolando_Vasquez_Tavera_EN.pdf) ·
[LinkedIn](https://www.linkedin.com/in/rolando-cesar-vasquez-tavera-b62235222) ·
[rolando.sha256@gmail.com](mailto:rolando.sha256@gmail.com)
