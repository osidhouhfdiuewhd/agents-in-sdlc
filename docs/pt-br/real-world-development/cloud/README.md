---
title: "Agente na nuvem do GitHub Copilot"
slug: pt-br/real-world-development/cloud
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

O [**agente na nuvem do GitHub Copilot**](https://docs.github.com/copilot/concepts/agents/cloud-agent/about-cloud-agent) permite que o GitHub Copilot trabalhe de forma assíncrona na nuvem. Você atribui uma tarefa no GitHub, e o agente a executa em segundo plano — explora o repositório, faz alterações e abre um pull request — enquanto você pode cuidar de outras atividades.

Nestes exercícios, você vai adicionar instruções personalizadas para o agente e, em seguida, atribuir uma issue do GitHub para que ele implemente o trabalho. Vai revisar e usar agentes personalizados para definir a abordagem, monitorar e orientar sessões no painel de agentes e terminar revisando os pull requests e iterando sobre os resultados.

## Exercícios

| Exercício | Tópico | Descrição |
|----------|-------|-------------|
| [0. Pré-requisitos][ex0] | Configuração | Crie seu repositório e um codespace |
| [1. Instruções personalizadas][ex1] | Contexto | Adicione instruções que o agente na nuvem seguirá |
| [2. Agente na nuvem][ex2] | Agente assíncrono | Atribua issues ao agente na nuvem do GitHub Copilot |
| [3. Agentes personalizados][ex3] | Agentes especializados | Revise e use agentes personalizados |
| [4. Gerenciamento de agentes][ex4] | Monitoramento | Monitore e oriente sessões de agentes |
| [5. Iteração][ex5] | Revisão | Revise PRs, itere sobre o trabalho do Copilot e escolha os próximos passos |

## Pré-requisitos

Antes de participar deste workshop, confira se você tem:

- [ ] Uma conta do GitHub com um plano ativo **Copilot Student, Pro, Pro+, Business ou Enterprise**
- [ ] O agente na nuvem do GitHub Copilot habilitado para sua conta ou organização

> [!TIP]
> Não tem um plano pago? Estudantes verificados podem obter o GitHub Copilot gratuitamente pelo [GitHub Education][callout-student-plan-education]. O plano **Copilot Student** inclui o agente, MCP, revisão de código e os recursos do Copilot CLI usados neste workshop, para que você possa concluir todos os ambientes.

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> O agente na nuvem está disponível nos planos **Copilot Student, Pro, Pro+, Business e Enterprise**, mas não no Copilot Free. No Copilot Business ou Enterprise, um administrador precisa habilitá-lo para a organização.

> [!NOTE]
> Este ambiente não aborda MCP. Para explorar servidores MCP com o Copilot, consulte o [ambiente de CLI][cli] ou o [ambiente do VS Code][vscode].

## Comece

**[Comece pelo Exercício 0: Pré-requisitos →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-custom-instructions/
[ex2]: 2-cloud-agent/
[ex3]: 3-custom-agents/
[ex4]: 4-managing-agents/
[ex5]: 5-iterating/
[cli]: ../cli/
[vscode]: ../vscode/
