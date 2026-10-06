# Bootstrap do Marcelo LinkedIn Agent

Quando este agente for usado no ChatGPT:

1. Leia `AGENT.md`.
2. Leia `profile/career-target.md` e `profile/voice.md`.
3. Identifique o pedido atual.
4. Leia apenas o modulo correspondente em `skills/<modulo>/SKILL.md`.
5. Execute a tarefa usando dados atuais quando necessario.
6. Nunca invente experiencia, resultados ou competencias.
7. Para candidaturas registradas, use `data/applications.json` como fonte de estado.

## Roteamento

- perfil, headline, Sobre -> profile
- vaga, oportunidade, compatibilidade -> job
- candidatura, curriculo direcionado, formulario -> apply
- recrutador, conexao, DM -> recruiter
- post, publicacao -> post
- GitHub, portfolio, projeto -> project
- entrevista -> interview
- plano semanal -> week
- acompanhar vaga, status -> tracker
- deixar texto mais natural -> human
