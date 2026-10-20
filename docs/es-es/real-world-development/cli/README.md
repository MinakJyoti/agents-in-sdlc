---
slug: es-es/real-world-development/cli
title: "GitHub Copilot CLI"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

**[GitHub Copilot CLI](https://docs.github.com/copilot/concepts/agents/about-copilot-cli)** incorpora GitHub Copilot a tu terminal como asistente de programación con agentes. Explora bases de código, genera código, ejecuta comandos y se conecta a herramientas externas, todo desde la línea de comandos, para que puedas mantener el flujo sin cambiar a un editor gráfico.

El taller sigue un único flujo de trabajo continuo en Tailspin Toys: preparar el proyecto en GitHub Codespaces, añadir una valoración con estrellas y, después, implementar el filtrado a partir de una incidencia. Planificarás el enfoque, usarás Autopilot para implementar la funcionalidad y la revisarás en Interactive. También actualizarás las instrucciones del repositorio, personalizarás la habilidad `quality-checks`, validarás el filtrado con Playwright MCP, crearás un agente de control de calidad (QA) y revisarás la solicitud de incorporación de cambios (PR) final. Para mantener el taller centrado, crearás dos PR: una para las valoraciones y otra para el filtrado y el trabajo relacionado de calidad.

## Ejercicios

| Ejercicio | Tema | Descripción |
|----------|-------|-------------|
| [0. Requisitos previos][ex0] | Configuración | Crea tu repositorio y tu codespace |
| [1. Instalación de Copilot CLI][ex1] | Instalación | Instala y autentica Copilot CLI |
| [2. Añade valoraciones con estrellas][ex2] | Primer cambio | Muestra las valoraciones existentes y combina tu primera PR |
| [3. Modos de agente: Plan y Autopilot][ex3] | Modos de agente | Planifica una funcionalidad desde una incidencia, impleméntala y revísala |
| [4. Guía a Copilot con instrucciones personalizadas][ex4] | Contexto | Actualiza las instrucciones y aplícalas al filtrado |
| [5. Personaliza y usa una habilidad de comprobaciones de calidad][ex5] | Comprobaciones | Personaliza la habilidad existente y ejecuta las comprobaciones |
| [6. Valida con Playwright MCP][ex6] | Navegador | Configura MCP y examina el filtrado en el navegador |
| [7. Crea y usa un agente de QA][ex7] | Requisitos y cobertura | Revisa los requisitos, la cobertura y las pruebas |
| [8. Crea y combina la PR de la funcionalidad][ex8] | Revisión y combinación | Revisa el cambio completo y usa Agent Merge |
| [9. Comandos de barra de Copilot CLI][ex9] | Funciones de CLI | Explora el contexto, los modelos y el uso compartido |
| [10. Repaso y próximos pasos][ex10] | Resumen | Repasa el flujo de trabajo y los recursos adicionales |
| [Opcional: incorpora Foundry][foundry] | Agentes hospedados | Prepara un modelo, despliega un agente basado en un catálogo y conéctalo al sitio web |

## Requisitos previos

Antes de asistir a este taller, asegúrate de tener:

- [ ] Una cuenta de GitHub con un plan activo de **Copilot Student, Pro, Pro+, Business o Enterprise**
- [ ] Conocimientos básicos de operaciones de terminal/línea de comandos
- [ ] Git instalado y configurado

> [!TIP]
> ¿No tienes un plan de pago? Los estudiantes verificados pueden obtener GitHub Copilot gratis a través de [GitHub Education][callout-student-plan-education]. El plan **Copilot Student** incluye las funciones de agente, MCP, revisión de código y Copilot CLI que utiliza este taller, así que puedes completar con él todos los recorridos.

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> Si usas Copilot Business o Copilot Enterprise, asegúrate de que tu administrador haya habilitado Copilot CLI.

## Primeros pasos

**[Empieza con el ejercicio 0: Requisitos previos →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-install-copilot-cli/
[ex2]: 2-add-star-rating/
[ex3]: 3-agent-modes/
[ex4]: 4-custom-instructions/
[ex5]: 5-agent-skills/
[ex6]: 6-mcp-playwright/
[ex7]: 7-qa-agent/
[ex8]: 8-create-pull-request/
[ex9]: 9-cli-power-tools/
[ex10]: 10-review/
[foundry]: 8-foundry-agent/
