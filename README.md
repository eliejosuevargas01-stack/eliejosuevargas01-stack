# Eliezer Josué Vargas Gamboa

**Desenvolvedor de Software | Desenvolvimento com IA e Spec-Driven Development (SDD)**

[GitHub](https://github.com/eliejosuevargas01-stack) · [LinkedIn](https://www.linkedin.com/in/eliezer-josu%C3%A9-vargas-gamboa-863b4a408/) · [E-mail](mailto:eliejosuevargas01@gmail.com)

Gaspar, SC, Brasil. Disponível para trabalho remoto, híbrido ou presencial em Gaspar, Brusque, Ilhota e Blumenau.

Criei Moto Na Prática e Deep Research primeiro no n8n e depois migrei para sistemas próprios em código com ajuda de IA e SDD. Essa contribuição é autoria declarada por mim; os repositórios abaixo permitem examinar implementações e artefatos, sem pressupor operação contínua em produção.

## Desenvolvimento com IA e SDD

Meu foco é converter problemas em requisitos, contratos e critérios de aceite, implementar com auxílio de IA e manter relação verificável entre especificação, código e testes. No Deep Research, essa cadeia aparece em requisitos RF-01–RF-10, cenários Gherkin, tarefas, domínio de briefing e testes de lifecycle. Validação contra provedor real permanece pendente.

## Projetos com código público examinado

Referência da revisão: **13/10/2026**. Os resultados se limitam aos commits e escopos indicados; leitura de código, testes locais e CI não equivalem a produção comprovada.

### [Moto Na Prática — automação n8n](https://github.com/eliejosuevargas01-stack/motonapratica-n8n-workflows)

Automação editorial com agentes, webhooks, HTTP, tratamento de JSON e geração de conteúdo. Stack observada: n8n, JavaScript, HTTP, Webhooks e LLMs.

- Inventário: 8 exports em workflows/active/ somam 174 nós; snapshot estático do commit, não estado atual de produção.
- Revisão dos exports: nenhum workflow acionado. Integração configurada não prova resposta externa.
- Commit examinado: `f985313081bad8a702793a5e40bf9fbb115cfe12`.
- Antes de republicar exports: revisar referências de credenciais e dados de execução; não assumir sanitização completa.

### [Deep Research — backend](https://github.com/eliejosuevargas01-stack/Deep-Research)

Backend Python/FastAPI com orquestração asyncio, personas de pesquisa, auditor e writer, APIs de consulta/callback, autenticação e controles SSRF observados no código.

- Evidência de execução: 22 testes puros passados, sem LLM, DB ou provedores reais; não precisão de pesquisa.
- CI completo não aprovado; validação de API, serviços externos e produção não demonstrada por esses testes.
- Commit examinado: `8bfd5299904a40e00e23f2e5c4151bc7b78126b9`.

### [Blog Moto Na Prática — portal](https://github.com/eliejosuevargas01-stack/blog-moto-na-pratica)

Portal TypeScript/Next.js com Prisma e PostgreSQL, API de posts e contrato editorial. CI remoto de typecheck, testes e build aprovado no commit examinado. Isso não prova deploy do commit nem publicação/indexação de conteúdo.

- Commit examinado: `cbc9f92598368243a9dc6c51116e2104f9907807`.

### [Controle de Validades — projeto complementar](https://github.com/eliejosuevargas01-stack/controle_validades_py)

Projeto Python de gestão de validade: CRUD por usuário e ordenação por vencimento. Código público examinado; não executado na auditoria. Impacto empresarial e economia de tempo não medidos nessa revisão.

- Commit examinado: `6795b8f3126b677b30421bc9cda0eb8b9f48b421`.

## Formação e idiomas

- Engenharia de Software — Uniasselvi, Gaspar; desde janeiro de 2026, em andamento.
- Espanhol nativo.
- Português fluente.
- Inglês básico a intermediário, autodeclarado: leitura mais forte que conversação; sem certificação de nível.

Experiência anterior em produção e operações no varejo ajuda a identificar problemas de rotina; não é apresentada como vínculo profissional de desenvolvimento de software.
