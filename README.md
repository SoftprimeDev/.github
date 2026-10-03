# .github — Padrões da organização Softprime

Este repositório contém **arquivos padrão da organização** `SoftprimeDev`. O GitHub
usa automaticamente o que está aqui como **fallback** para todos os repositórios da
organização que **não** possuam a sua própria versão.

## Issue Templates padrão

`.github/ISSUE_TEMPLATE/` define os tipos de Issue padrão da Softprime, alinhados ao
[Softprime Software Engineering Playbook](https://github.com/SoftprimeDev/Softprime-ProcessoSoftware):

- **Feature** — nova funcionalidade ou melhoria.
- **Bug/Fix** — correção de defeito no fluxo normal de desenvolvimento.
- **Chore** — tarefa de manutenção que não altera funcionalidade diretamente.
- **Hotfix** — correção urgente de um problema já presente em produção.

Cada formulário segue a estrutura: Contexto, Objetivo, Descrição, Critérios de
Aceitação e Observações/Restrições.

## Como a herança funciona

- Repositórios **sem** `.github/ISSUE_TEMPLATE/` próprio herdam estes templates.
- Repositórios **com** os seus próprios templates (como o `Softprime-ProcessoSoftware`)
  continuam usando os deles — que são idênticos a estes.

A fonte conceitual do processo é o
[Playbook](https://github.com/SoftprimeDev/Softprime-ProcessoSoftware).
