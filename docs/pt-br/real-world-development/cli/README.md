---
slug: pt-br/real-world-development/cli
title: "CLI do GitHub Copilot"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

O **[GitHub Copilot CLI](https://docs.github.com/copilot/concepts/agents/about-copilot-cli)** coloca o GitHub Copilot no seu terminal como um assistente de programação baseado em agentes. Ele explora bases de código, gera código, executa comandos e se conecta a ferramentas externas — tudo pela linha de comando, para que você mantenha o foco sem trocar para um editor gráfico.

O workshop acompanha um fluxo contínuo de trabalho no Tailspin Toys: preparar o projeto no GitHub Codespaces, adicionar classificações por estrelas e, depois, implementar a filtragem a partir de uma issue. Você definirá a abordagem no modo Plan, implementará com Autopilot e revisará com Interactive. Também atualizará as instruções do repositório, personalizará a skill `quality-checks`, validará a filtragem com o Playwright MCP, criará um agente de garantia de qualidade (QA) e revisará a PR final. Para manter o foco, você criará duas PRs: uma para as classificações e outra para a filtragem e o trabalho de qualidade relacionado. Você também pode seguir uma [série opcional de três módulos com GitHub Copilot CLI e Foundry][foundry] para preparar um modelo, criar e implantar um agente hospedado e integrá-lo ao site.

## Lições

| Lição | Tópico | Descrição |
|----------|-------|-------------|
| [0. Pré-requisitos][ex0] | Configuração | Crie seu repositório e seu codespace |
| [1. Instalar o Copilot CLI][ex1] | Instalação | Instale e autentique o Copilot CLI |
| [2. Adicione classificações por estrelas][ex2] | Primeira alteração | Exiba as classificações existentes e mescle sua primeira PR |
| [3. Modos de agente: Plan e Autopilot][ex3] | Modos de agente | Planeje um recurso a partir de uma issue, implemente e revise |
| [4. Oriente o Copilot com instruções personalizadas][ex4] | Contexto | Atualize as instruções e aplique-as à filtragem |
| [5. Personalize e use uma skill de verificações de qualidade][ex5] | Verificações | Personalize a skill existente e execute as verificações |
| [6. Valide com o Playwright MCP][ex6] | Navegador | Configure o MCP e examine a filtragem no navegador |
| [7. Crie e use um agente de QA][ex7] | Requisitos e cobertura | Revise requisitos, cobertura e evidências de verificação |
| [8. Crie e mescle a PR da funcionalidade][ex8] | Revisão e mesclagem | Revise a alteração completa e use o Agent Merge |
| [9. Comandos de barra do Copilot CLI][ex9] | Recursos da CLI | Explore contexto, modelos e compartilhamento |
| [10. Revisão e próximos passos][ex10] | Resumo | Revise o fluxo de trabalho e outros recursos |
| [Opcional: Incorpore o Foundry][foundry] | Agentes hospedados | Prepare um modelo, implante um agente baseado em catálogo e conecte-o ao site |

## Pré-requisitos

Antes de participar deste workshop, verifique se você tem:

- [ ] Uma conta do GitHub com um plano ativo **Copilot Student, Pro, Pro+, Business ou Enterprise**
- [ ] Familiaridade básica com operações de terminal e linha de comando
- [ ] O Git instalado e configurado

> [!TIP]
> Não tem um plano pago? Estudantes verificados podem obter o GitHub Copilot gratuitamente por meio do [GitHub Education][callout-student-plan-education]. O plano **Copilot Student** inclui os recursos de agente, MCP, revisão de código e Copilot CLI usados neste workshop. Portanto, você pode concluir todos os percursos com esse plano.

> [!NOTE]
> Se você usa o Copilot Business ou o Copilot Enterprise, verifique se o administrador habilitou o Copilot CLI para uso.

## Começar

[**Comece pela Lição 0: Pré-requisitos →**][ex0]

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
[callout-student-plan-education]: https://github.com/education/students
