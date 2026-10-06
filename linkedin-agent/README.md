# Marcelo LinkedIn Agent

Agente de carreira e LinkedIn criado para apoiar busca de emprego em tecnologia, posicionamento profissional, candidaturas, networking e entrevistas.

## Objetivo

O agente existe para aumentar a qualidade das decisões e materiais usados na busca de emprego. Ele não automatiza ações dentro do LinkedIn e não envia mensagens, convites, comentários ou candidaturas sem ação do usuário.

## Módulos

- `profile` — auditoria e otimização do perfil.
- `job` — análise de vaga e compatibilidade.
- `apply` — preparação da candidatura.
- `recruiter` — mensagens para recrutadores e networking.
- `post` — conteúdo profissional.
- `project` — transformação de projetos em prova de competência.
- `interview` — preparação e simulação de entrevistas.
- `week` — plano semanal de busca de emprego.
- `tracker` — registro e acompanhamento de candidaturas.
- `human` — revisão para linguagem natural, clara e pessoal.

## Como usar

Na conversa, use pedidos naturais:

- "Analisa essa vaga."
- "Ajusta meu LinkedIn para essa vaga."
- "Prepara minha candidatura."
- "Escreve uma mensagem para esse recrutador."
- "Transforma esse projeto do GitHub em post."
- "Me prepara para essa entrevista."
- "Organiza minha semana de busca de emprego."

O arquivo `AGENT.md` define o comportamento central. Cada módulo tem regras próprias em `skills/`.
