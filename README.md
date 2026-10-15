# Eliezer Josué Vargas Gamboa

**Desenvolvedor de Software | IA aplicada, automação e Spec-Driven Development (SDD)**

[GitHub](https://github.com/eliejosuevargas01-stack) · [LinkedIn](https://www.linkedin.com/in/eliezer-josu%C3%A9-vargas-gamboa-863b4a408/) · [E-mail](mailto:eliejosuevargas01@gmail.com)

Gaspar, SC, Brasil · Disponível para trabalho remoto, híbrido ou presencial em Gaspar, Brusque, Ilhota e Blumenau.

Crio software a partir de problemas que conheço de perto e de assuntos pelos quais tenho interesse. Comecei meus projetos com **n8n, frontends próprios, APIs REST e bancos de dados**. Hoje também desenvolvo em **Python/FastAPI e TypeScript/Next.js**, com apoio de IA e SDD.

## Projetos que criei

### [Moto Na Prática](https://github.com/eliejosuevargas01-stack/motonapratica-n8n-workflows)

O Moto Na Prática nasceu da minha paixão por duas rodas e IA. Queria colocar uma IA para pesquisar na internet e encontrar informações interessantes sobre motociclismo. Levei mais de 30 dias para chegar à primeira versão entregável no n8n.

Estruturei o projeto em fluxos especializados: seleção de pautas e SEO, pesquisa, redação, auditoria editorial, imagens e áudio. Integrei feeds RSS, fontes de notícias e dados de MotoGP, Google Sheets, Supabase e n8n Data Tables. A redação prepara conteúdo em português, espanhol e inglês e o envia ao portal por API.

### [Deep Research — do n8n ao Python](https://github.com/eliejosuevargas01-stack/Deep-Research)

Criei o Deep Research no n8n e alcancei uma versão funcional em 15 dias. Até o 17º dia do projeto, nas minhas execuções, reduzi a pesquisa de pelo menos 20 para cerca de 4 minutos, varrendo mais de 100 sites.

Organizei a pesquisa em planejamento com quatro personas, coleta, auditoria e redação, com controle de etapas e entrega por callback. Integrei APIs de LLMs, busca SERP com Apify e leitura de páginas com Jina. Também uso SerpApi em fluxos auxiliares de pesquisa do meu ecossistema.

Depois acrescentei **RAG e cache vetorial no Supabase**, com embeddings e metadados de fontes, para reaproveitar informações coletadas e reduzir buscas repetidas. Agora estou migrando a ideia para **Python/FastAPI**; essa implementação continua em desenvolvimento. Os tempos relatados são da versão n8n.

### [Blog Moto Na Prática — portal e frontend](https://github.com/eliejosuevargas01-stack/blog-moto-na-pratica)

Desenvolvi o portal em TypeScript/Next.js, com Prisma, PostgreSQL e API de posts. Ele se conecta aos fluxos editoriais do n8n para receber conteúdo e organizar a publicação.

### [Controle de Validades](https://github.com/eliejosuevargas01-stack/controle_validades_py)

Esse projeto nasceu de uma dificuldade que encontrei trabalhando no mercado. Eu conseguia abastecer e manter corredores e gôndolas organizados, mas precisava melhorar o acompanhamento das validades. Criei o sistema para organizar os produtos por vencimento e apoiar a retirada no momento certo.

A primeira versão usa frontend próprio, webhooks n8n e PostgreSQL. Implementei cadastro e consulta de produtos, edição, registro de vendidos e retirados, ordenação por validade e uma rotina de avisos por WhatsApp ou e-mail para produtos próximos do vencimento. O repositório também reúne a evolução em Python.

### Cartazes de validade e PVPS

Criei outro sistema para identificar os produtos na câmara de resfriados do açougue e facilitar o **PVPS — primeiro que vence, primeiro que sai**. Informo produto, validade e quantidade de cartazes; o fluxo guarda os itens em n8n Data Tables, gera um PDF A4 em paisagem com JavaScript e prepara a entrega pelo WhatsApp.

## Como desenvolvo

Transformo necessidades em requisitos e critérios de aceite, uso IA na implementação e mantenho a relação entre especificação, código e testes. Trabalho com integração de sistemas, webhooks, APIs REST e persistência em Supabase/PostgreSQL, Google Sheets e n8n Data Tables, escolhendo cada ferramenta conforme o projeto.

## Formação e idiomas

- Engenharia de Software — Uniasselvi, Gaspar; em andamento desde janeiro de 2026.
- Espanhol nativo · Português fluente · Inglês básico a intermediário, com leitura mais forte que conversação.
