# Rolando Vásquez

**Desarrollador full stack y móvil · IA aplicada** — Tarija, Bolivia · abierto a trabajo remoto

Construyo apps con Flutter y backends con TypeScript (NestJS) y Python, con pruebas automatizadas
y CI desde el primer commit. Publiqué 4 apps en Google Play y App Store para empresas de delivery
y movilidad, y aplico IA (RAG, agentes y visión) a problemas concretos.

[CV web](https://rolandocesar-prog-dev.github.io/cv-web/) ·
[CV en PDF](https://rolandocesar-prog-dev.github.io/cv-web/CV_Rolando_Vasquez_Tavera.pdf) ·
[rolando.sha256@gmail.com](mailto:rolando.sha256@gmail.com)

## Proyectos

Cada repositorio tiene requisitos y diseño escritos, pruebas automatizadas, CI y una demo.

| Proyecto | Qué resuelve | Stack | Probar |
| --- | --- | --- | --- |
| [Asistente RAG sobre documentación](https://github.com/rolandocesar-prog-dev/docs-rag-assistant) | Responde preguntas sobre la documentación de Kubernetes citando cada fuente, y avisa cuando la respuesta no está. Evaluación automática: documento correcto en el 100 % de las preguntas de prueba. | Python · FastAPI · PostgreSQL + pgvector · Docker | [Demo](https://github.com/rolandocesar-prog-dev/docs-rag-assistant/blob/main/docs/demo.gif) |
| [API de inventario](https://github.com/rolandocesar-prog-dev/inventory-api-nestjs) | Inventario con historial auditable, JWT con renovación rotativa y stock que nunca queda negativo con operaciones simultáneas. 184 pruebas. | NestJS · TypeScript · PostgreSQL · Docker | [API en vivo](https://inventory-api-c5yi.onrender.com/docs) |
| [Reservas de turnos](https://github.com/rolandocesar-prog-dev/turnos-app-flutter) | Reservas sin turnos duplicados para canchas y consultorios, con panel del negocio y recordatorios push. 173 pruebas de la app. | Flutter · Firebase · Cloud Functions | [Web en vivo](https://turnos-rv-portafolio.web.app) |
| [Escáner de facturas con IA](https://github.com/rolandocesar-prog-dev/invoice-scanner-flutter) | Lee la foto de una factura con un modelo de visión local y, tras la revisión de una persona, registra las entradas de stock sin duplicados. 10/10 facturas de prueba perfectas. | Flutter · Riverpod · Ollama | [Demo](https://github.com/rolandocesar-prog-dev/invoice-scanner-flutter/blob/main/docs/demo.gif) |
| [Agente de inventario con MCP](https://github.com/rolandocesar-prog-dev/inventory-agent-mcp) | Servidor MCP y agente que mueven el inventario conversando en español. Ningún movimiento se registra sin aprobación humana: 0 escrituras sin aprobación en 18 escenarios. | TypeScript · MCP · Ollama | [Demo](https://github.com/rolandocesar-prog-dev/inventory-agent-mcp/blob/main/docs/demo.gif) |
| [Suite E2E con Playwright](https://github.com/rolandocesar-prog-dev/qa-e2e-playwright) | 139 pruebas en cuatro navegadores, 13 defectos reales documentados, accesibilidad, regresión visual y 0 pruebas inestables en 30 ejecuciones del CI. | Playwright · TypeScript · Docker | [Reporte](https://rolandocesar-prog-dev.github.io/qa-e2e-playwright/) |

## Tecnologías

- **Núcleo:** Flutter, Dart, TypeScript, JavaScript, NestJS, Python, PostgreSQL, Firebase, Docker.
- **IA y calidad:** RAG y búsqueda híbrida, agentes con MCP, pruebas E2E con Playwright, CI/CD con
  GitHub Actions.
- **También:** React, React Native, Angular, Spring Boot, Java, PHP, MySQL.

Las apps publicadas en las tiendas y mi experiencia están en el
[CV web](https://rolandocesar-prog-dev.github.io/cv-web/).
