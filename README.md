<h1 align="center">Sérgio Guthyerres</h1>

<p align="center">
  <b>Desenvolvedor Fullstack · Segurança de Aplicações</b><br>
  Python & TypeScript · Teresina-PI, Brasil · Aberto a vagas remotas
</p>

<p align="center">
  <a href="https://linkedin.com/in/guthyerres">LinkedIn</a> ·
  <a href="mailto:guthyerressergio@gmail.com">E-mail</a> ·
  <a href="https://controle-estoque.sergioguthyn.workers.dev/">Sistema em produção</a>
</p>

---

Trabalho com **Django, FastAPI, React e Node** no ciclo completo de entrega, do levantamento de requisitos com o setor demandante até o deploy e os testes automatizados.

Atualmente sou **residente no InovaTech** (IFPI · Piauí GovTech · FAIFPI), bolsa de 20h semanais, sem vínculo empregatício. programa que selecionou 15 pessoas entre cerca de 700 inscritos. Lá desenvolvo, de ponta a ponta, funcionalidades de um sistema institucional sujeito a requisitos da LGPD. Em paralelo, curso o último ano de **Sistemas para Internet no IFMA** e escrevo meu TCC sobre **criptografia pós-quântica aplicada a APIs RESTful**.

Segurança é o fio que costura essas coisas. Não por escolha de currículo, mas porque foi para onde meu trabalho foi me levando.

### Um achado do qual me orgulho

Durante o processo seletivo do InovaTech, encontrei uma incompatibilidade entre `passlib` 1.7.4 e `bcrypt` ≥ 4.0.0 nos projetos base: o `passlib` lê `bcrypt.__about__.__version__` para detectar a versão, e esse módulo foi removido na 4.0.0, quebrando a autenticação com `AttributeError`.

Reportei formalmente. O IFPI corrigiu as versões de todos os projetos base e publicou o agradecimento em **[nota técnica oficial](https://inovatech.ifpi.edu.br/media/publicacoes/2026/04/Nota_Tecnica_05_2026_INOVATECH_1_UOcLNr9.pdf?v=2)**.

---

## Projetos

### 📦 [Controle de Estoque](https://github.com/SergioGuthyerres/CONTROLE-ESTOQUE): em produção
PWA **offline-first** para gestão de estoque em comércio, em uso real. Funciona sem internet e sincroniza quando a conexão volta.
Inclui **16 testes automatizados de segurança**: anti-enumeração de usuários, RBAC, invalidação de sessão, rate limiting e política de CORS.
`React` `Vite` `Dexie/IndexedDB` `Node` `Express` `Prisma` `SQLite` `Oracle Cloud` `Cloudflare Workers`
**[→ Ver aplicação no ar](https://controle-estoque.sergioguthyn.workers.dev/)**

### 🔐 TCC: Criptografia pós-quântica em APIs RESTful *(em andamento)*
Framework experimental **open source** que compara RSA-2048 e ECDSA P-256 com **ML-KEM (Kyber)** e **ML-DSA (Dilithium)** no handshake TLS 1.3. Meta de projeto: ambiente containerizado e reproduzível com um único comando.
360 execuções, 4 grupos criptográficos, 3 cenários de rede, análise por teste de Wilcoxon.
`Docker` `OpenSSL 3.x + oqs-provider` `FastAPI` `Locust` `tshark` `Python`

### 🎓 [Certifica](https://github.com/SergioGuthyerres/Certifica): gestão de certificados de eventos *(em desenvolvimento)*
Projeto em equipe no qual respondo pela arquitetura, modelagem de dados, contrato de API e escolha da stack.
`FastAPI` `SQLModel` `SQLAlchemy async` `PostgreSQL` `React` `TypeScript` `Docker Compose`

### 📅 [Controle de Eventos — API REST](https://github.com/SergioGuthyerres/Controle_de_Eventos-API)
API com documentação completa: requisitos funcionais e não funcionais, casos de uso, modelo entidade-relacionamento e dicionário de dados.
`AdonisJS v7` `Lucid ORM` `JWT` `PostgreSQL` `TypeScript`

### 🎮 [CodeSurv](https://github.com/SergioGuthyerres/CodeSurv-Backend): desafios de código em tempo real
Partidas de lógica e algoritmos em tempo real, com execução do código dos jogadores em sandbox isolado com uma instância própria da Piston API em VM Azure.
`Fastify` `TypeScript` `MongoDB` `Socket.IO` `Azure`

### 🌊 Sonda IoT multiparâmetros — PIBIT/IFMA · ago/2025 – ago/2026 *(concluído · código privado)*
Sonda de monitoramento de qualidade da água com ESP32 e C++: pH, turbidez, temperatura, condutividade, oxigênio dissolvido e TDS. Invólucro em impressão 3D. Em processo de proteção intelectual.

---

## Stack

**Linguagens** — Python · TypeScript · JavaScript · SQL · C++

**Back-end** — Django · FastAPI · Node.js · Express · Fastify · AdonisJS · SQLAlchemy · Prisma

**Front-end** — React · Vite · Tailwind · PWA / offline-first · Socket.IO

**Dados** — PostgreSQL · SQLite · MongoDB · IndexedDB

**Segurança** — JWT · RBAC · gestão de sessão · rate limiting · CORS · testes de segurança

**Em pesquisa (TCC)** — TLS 1.3 · liboqs / oqs-provider · Locust

**Infra** — Docker · Oracle Cloud · Cloudflare Workers · Azure · Linux · Git

---

<p align="center"><i>Cursando o último ano de Sistemas para Internet no IFMA · conclusão em junho de 2027<br>Inglês B2 · Aberto a conversas sobre vagas remotas</i></p>

### 🐍 The Ender-Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SergioGuthyerres/SergioGuthyerres/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SergioGuthyerres/SergioGuthyerres/output/github-contribution-grid-snake.svg">
    <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/SergioGuthyerres/SergioGuthyerres/output/github-contribution-grid-snake.svg" width="80%">
  </picture>



