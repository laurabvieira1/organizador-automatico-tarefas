# Organizador Automático de Tarefas

Automação desenvolvida com **n8n**, integrada ao **Google Sheets** e ao **Gmail**, para facilitar o registro e a organização de tarefas.

## Sobre o projeto

O projeto surgiu da necessidade de centralizar tarefas recebidas por diferentes meios, evitando esquecimentos e facilitando o acompanhamento de atividades e prazos.
Por meio de um formulário, o usuário informa os dados de uma tarefa. O fluxo automatiza o processamento dessas informações, registra os dados em uma planilha e envia uma confirmação por e-mail.

## Tecnologias utilizadas

- **n8n:** construção e execução dos fluxos de automação.
- **Google Sheets:** armazenamento e organização das tarefas.
- **Gmail:** envio automático de confirmações.
- **JavaScript:** aplicação de expressões e regras de processamento de dados.

## Funcionalidades implementadas

- Recebimento de tarefas por formulário.
- Registro automático no Google Sheets.
- Geração automática de identificador.
- Classificação de prioridade conforme o prazo.
- Registro da data de criação.
- Definição inicial do status como pendente.
- Armazenamento do e-mail informado pelo usuário.
- Envio automático de confirmação por e-mail.

## Funcionamento

1. O usuário preenche o formulário.
2. O n8n recebe e processa os dados.
3. A prioridade é definida conforme o prazo informado.
4. A tarefa é registrada no Google Sheets.
5. O Gmail envia uma confirmação ao usuário.

## Status do projeto

**Versão 1.0 — Implementada e testada.**

O projeto poderá receber novas funcionalidades e melhorias em versões futuras.
