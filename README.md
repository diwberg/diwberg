<!-- HEADER -->
<div align="center">

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=1A56A0&center=true&vCenter=true&multiline=true&repeat=false&width=900&height=80&lines=Hey%2C+I'm+Diwberg+%F0%9F%91%8B;Full+Stack+Developer+%C2%B7+Multi-Tenant+SaaS+Architecture)](https://git.io/typing-svg)

<p>
  <a href="mailto:diwberg@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-diwberg%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/diwberg/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-diwberg-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://www.instagram.com/diwberg/" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-@diwberg-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
  </a>
</p>

</div>

---

## 🇧🇷 Sobre mim

**Desenvolvedor Full Stack** especializado em **TypeScript**, no ecossistema Next.js, NestJS e React Native, com foco em **arquitetura de plataformas SaaS multi-tenant**. Também escrevo serviços em **Go**. Atuo no ciclo completo do produto: modelagem de dados, API, interface e deploy.

Antes de programar profissionalmente, passei mais de 10 anos em operações e sistemas ERP (TOTVS Protheus). Isso definiu a forma como construo software: começo pelo processo e por quem vai usar, não pela tela. Questiono requisito, discuto escopo e entrego o que resolve o problema, inclusive quando a resposta certa é cortar funcionalidade.

Meu diferencial está na **arquitetura**. Conduzi a conversão de uma plataforma inteira de single-tenant para **multi-tenant**, com isolamento por `tenant_id` em todas as camadas: PostgreSQL, ClickHouse, Kafka, Temporal e WebSocket. Migrei os dados legados para organizações sem downtime e adotei política **fail-closed**, em que uma requisição sem tenant resolvido é rejeitada em vez de cair no escopo global. Desenho pensando em escala desde o primeiro dia: contratos de API bem definidos, estratégia de cache e consultas que não quebram quando o volume cresce.

Desenvolvo em **ambientes containerizados**, com paridade entre local e produção, e mantenho **pipelines de CI/CD** que automatizam build, teste e deploy. Isso inclui runners self-hosted e uma suíte de testes que roda com multi-tenancy ligado, então uma regressão de isolamento quebra o CI antes de chegar ao cliente.

Hoje entrego de ponta a ponta em projetos de qualquer porte: de MVP validado em semanas a plataforma multi-tenant em produção, com portal web e app mobile consumindo a mesma API. Escolho a stack pelo problema, não pela tendência do momento.

> _O código é o meio. O que entrego é o problema resolvido._

---

## 🇺🇸 About me

**Full Stack Developer** specialized in **TypeScript**, across Next.js, NestJS, and React Native, focused on **multi-tenant SaaS architecture**. I also write services in **Go**. I work the full product cycle: data modeling, API, UI, and deployment.

Before coding professionally, I spent 10+ years in operations and ERP systems (TOTVS Protheus). That shaped how I build software: I start from the process and the people using it, not from the screen. I question requirements, push back on scope, and ship what actually solves the problem, including when the right answer is to cut a feature.

My edge is **architecture**. I led the conversion of an entire platform from single-tenant to **multi-tenant**, with `tenant_id` isolation across every layer: PostgreSQL, ClickHouse, Kafka, Temporal, and WebSocket. I migrated legacy data into organizations with no downtime and adopted a **fail-closed** policy, where a request with no resolved tenant is rejected instead of falling back to global scope. I design for scale from day one: well-defined API contracts, caching and query strategies that hold up as volume grows.

I develop in **containerized environments**, keeping local and production in parity, and maintain **CI/CD pipelines** that automate build, test, and deploy. That includes self-hosted runners and a test suite running with multi-tenancy enabled, so an isolation regression breaks CI before it reaches a customer.

Today I deliver end-to-end on projects of any size: from an MVP validated in weeks to a multi-tenant platform running in production, with a web portal and a mobile app consuming the same API. I choose the stack based on the problem, not on what's trending.

> _Code is the means. What I deliver is the problem solved._

---

## 🛠️ Tech Stack

### ⚛️ Frontend
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Styled Components](https://img.shields.io/badge/Styled_Components-DB7093?style=flat-square&logo=styledcomponents&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)
![Radix UI](https://img.shields.io/badge/Radix_UI-161618?style=flat-square&logo=radixui&logoColor=white)
![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?style=flat-square&logo=reacthookform&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=flat-square&logo=react&logoColor=white)

### 📱 Mobile
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Expo Router](https://img.shields.io/badge/Expo_Router-000020?style=flat-square&logo=expo&logoColor=white)
![NativeWind](https://img.shields.io/badge/NativeWind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

### 🔧 Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white)
![tRPC](https://img.shields.io/badge/tRPC-2596BE?style=flat-square&logo=trpc&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-009688?style=flat-square&logo=json&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![OAuth 2.0](https://img.shields.io/badge/OAuth_2.0-EB5424?style=flat-square&logo=auth0&logoColor=white)
![Better Auth](https://img.shields.io/badge/Better_Auth-1A1A1A?style=flat-square&logo=auth0&logoColor=white)
![NextAuth](https://img.shields.io/badge/NextAuth-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white)

### 📡 Filas, Eventos & Observabilidade
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Temporal](https://img.shields.io/badge/Temporal-000000?style=flat-square&logo=temporal&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![OpenObserve](https://img.shields.io/badge/OpenObserve-0F172A?style=flat-square&logo=grafana&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-0A0A0A?style=flat-square&logo=langchain&logoColor=white)

### 🗄️ Database & ORM
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Drizzle ORM](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Neon](https://img.shields.io/badge/Neon_DB-00E5BF?style=flat-square&logo=neon&logoColor=black)

### ⚙️ Infra, DevOps & CI/CD
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Swarm](https://img.shields.io/badge/Docker_Swarm-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Self-Hosted Runners](https://img.shields.io/badge/Self--Hosted_Runners-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-4A4A4A?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=flat-square&logo=traefikproxy&logoColor=white)
![Dokploy](https://img.shields.io/badge/Dokploy-171717?style=flat-square&logo=docker&logoColor=white)
![Portainer](https://img.shields.io/badge/Portainer-13BEF9?style=flat-square&logo=portainer&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

### 🧰 Ferramentas | Tooling
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)

### 🔌 Integrações & Serviços
![Stream.io](https://img.shields.io/badge/Stream.io-005FFF?style=flat-square&logo=stream&logoColor=white)
![Inngest](https://img.shields.io/badge/Inngest-6B21A8?style=flat-square&logo=inngest&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-FF9900?style=flat-square&logo=amazons3&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white)
![Evolution API](https://img.shields.io/badge/Evolution_API-25D366?style=flat-square&logo=whatsapp&logoColor=white)

### 🏢 ERP & Automação de Processos
![ADVPL](https://img.shields.io/badge/ADVPL-0C9ABE?style=flat-square&logo=totvs&logoColor=white)
![TOTVS Protheus](https://img.shields.io/badge/TOTVS_Protheus-0C9ABE?style=flat-square&logo=totvs&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![ClickUp](https://img.shields.io/badge/ClickUp-7B68EE?style=flat-square&logo=clickup&logoColor=white)

### 🤖 AI-Assisted Development
![Claude](https://img.shields.io/badge/Claude_(Anthropic)-D97757?style=flat-square&logo=anthropic&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=google&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white)

---

## 🎓 Formação | Education

| | |
|---|---|
| 🏛️ **Engenharia de Software** | Centro Universitário da Grande Dourados (**UNIGRAN**) |
| 📍 Polo Goiânia | Cursando · Previsão de conclusão: 2026 |
| 🚀 **Trilha Full Stack** | **Rocketseat**: React · Next.js · Node.js · TypeScript · APIs |
| 📱 **Trilha Mobile** | **Rocketseat**: React Native · Expo · Expo Router |
| 💻 **Formação Full Stack** | **Cod3r**: JavaScript · Node.js · React |

---

## 💼 Experiência Profissional | Professional Work

> Projetos de código fechado nos quais atuei. Os repositórios são privados, então não há links públicos. A descrição cobre escopo e minha contribuição.
>
> _Closed-source projects I've worked on. Repositories are private, so there are no public links. The description covers scope and my contribution._

### 💬 Zapflow · Plataforma de CRM Conversacional com IA

![Repositório Privado](https://img.shields.io/badge/Reposit%C3%B3rio-Privado-6E7681?style=flat-square&logo=github&logoColor=white)
![Produto próprio](https://img.shields.io/badge/Produto-Pr%C3%B3prio-1A56A0?style=flat-square&logo=rocket&logoColor=white)
![2026](https://img.shields.io/badge/2026-%C2%B7_em_andamento-22C55E?style=flat-square)

> Plataforma **multi-tenant** de atendimento e automação conversacional (WhatsApp, Instagram) com agentes de IA, jornadas e campanhas. Arquitetura de microsserviços com motor de jornadas em NestJS, serviços em Go, frontend Next.js e app mobile React Native, orquestrados em Docker Swarm sobre Kafka, Temporal, PostgreSQL e ClickHouse.

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Temporal](https://img.shields.io/badge/Temporal-000000?style=flat-square&logo=temporal&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker Swarm](https://img.shields.io/badge/Docker_Swarm-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Minha contribuição:** arquitetura e implementação da tenancy de ponta a ponta.

- **Conversão single-tenant → multi-tenant:** desenho e execução do contrato de tenancy em toda a stack. Coluna `tenant_id` com índices compostos e unicidade por tenant no PostgreSQL, `ORDER BY` e `PARTITION BY` por tenant no ClickHouse, `tenantId` no payload e na chave de partição do Kafka, e namespacing de `workflowId` no Temporal.
- **Migração dos dados legados:** backfill do histórico para um tenant de fallback e reorganização por organização, com rollout controlado por feature flag. A compatibilidade single-tenant seguiu funcionando durante toda a transição.
- **Isolamento fail-closed:** resolução de tenant por header `X-Tenant-ID` e claim JWT, propagada por contexto de requisição. Rota protegida sem tenant resolvido responde 403 em vez de cair no escopo global.
- **Correção de vazamento cross-organization:** diagnóstico e fix de mensagens visíveis entre organizações, incluindo escopo dos canais WebSocket por tenant.
- **Serviço de autenticação dedicado:** OAuth 2.0 e JWT com claims de tenant e papéis, login multi-conta e RBAC coberto por testes.
- **Camada de IA:** abstração de provedores de LLM configurável por ambiente, guardrails, RAG com upload de base de conhecimento e formatação de resposta por canal.
- **Plataforma e CI/CD:** pipeline de staging, runner self-hosted do GitHub Actions e suíte de testes executando com multi-tenancy ligado, em paridade com produção.

**My contribution:** end-to-end tenancy architecture and implementation.

- **Single-tenant → multi-tenant conversion:** designed and executed the tenancy contract across the whole stack. A `tenant_id` column with composite indexes and per-tenant uniqueness in PostgreSQL, per-tenant `ORDER BY` and `PARTITION BY` in ClickHouse, `tenantId` in Kafka payloads and partition keys, and `workflowId` namespacing in Temporal.
- **Legacy data migration:** backfilled historical records into a fallback tenant and reorganized them by organization, with a feature-flagged rollout. Single-tenant compatibility kept working throughout the transition.
- **Fail-closed isolation:** tenant resolution via `X-Tenant-ID` header and JWT claim, propagated through per-request context. A protected route with no resolved tenant returns 403 instead of falling back to global scope.
- **Cross-organization leak fix:** diagnosed and fixed messages visible across organizations, including per-tenant scoping of WebSocket channels.
- **Dedicated auth service:** OAuth 2.0 and JWT with tenant and role claims, multi-account login, and test-covered RBAC.
- **AI layer:** environment-configurable LLM provider abstraction, guardrails, RAG with knowledge-base upload, and per-channel response formatting.
- **Platform & CI/CD:** staging pipeline, self-hosted GitHub Actions runner, and a test suite running with multi-tenancy enabled for production parity.

---

### 🚚 Rede Logistics · Plataforma de Operações de Entrega

![Repositório Privado](https://img.shields.io/badge/Reposit%C3%B3rio-Privado-6E7681?style=flat-square&logo=github&logoColor=white)
[![SoftSapiens Solutions](https://img.shields.io/badge/Org-SoftSapiens_Solutions-1A56A0?style=flat-square&logo=github&logoColor=white)](https://github.com/softsapienssolutions)
![2026](https://img.shields.io/badge/2026-%C2%B7_em_andamento-22C55E?style=flat-square)

> Monorepo de uma plataforma de gestão de entregas: motoristas, jobs, paradas e execução em campo. Composto por API ASP.NET Core, portal de backoffice em Next.js e app mobile em Expo/React Native para os motoristas.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=flat-square&logo=react&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![NativeWind](https://img.shields.io/badge/NativeWind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Minha contribuição:** responsável por praticamente todo o front-end do portal e do app mobile.

- **Portal:** páginas e fluxos completos, biblioteca de componentes reutilizáveis e tabelas de dados com paginação server-side, ordenação e filtros combinados.
- **Formulários e estado:** dialogs multi-step, edição inline e validação por schema, com Zustand no estado da aplicação e TanStack Query no cache de servidor.
- **Dados e relatórios:** dashboard de entregas com gráficos e indicadores, tratamento de datas e fuso por preferência de conta, geração de PDF e comprovação de entrega.
- **Mobile (Expo):** internacionalização do app e layouts adaptados para tablet em retrato e paisagem.
- **Domínio:** autenticação e gestão de usuários, motoristas, frota e jobs agendados.

**My contribution:** owned virtually the entire front-end of the portal and the mobile app.

- **Portal:** full pages and flows, a reusable component library, and data tables with server-side pagination, sorting, and combined filters.
- **Forms & state:** multi-step dialogs, inline editing, and schema validation, with Zustand for app state and TanStack Query for server-state caching.
- **Data & reporting:** deliveries dashboard with charts and KPIs, date and timezone handling per account preference, PDF generation and proof of delivery.
- **Mobile (Expo):** app internationalization and tablet layouts in portrait and landscape.
- **Domain:** authentication and management of users, drivers, fleet, and scheduled jobs.

---

### 🛒 WeBe · E-commerce Headless

![Repositório Privado](https://img.shields.io/badge/Reposit%C3%B3rio-Privado-6E7681?style=flat-square&logo=github&logoColor=white)
![2026](https://img.shields.io/badge/2026-%C2%B7_em_andamento-22C55E?style=flat-square)

> Loja headless sobre **Medusa v2** com storefront em Next.js 16. Atuei no upgrade da plataforma para a v2.17.2, com análise de breaking changes, plano de migração e validação, além do setup do storefront e da tradução pt-BR da interface administrativa.

![Medusa](https://img.shields.io/badge/Medusa_v2-000000?style=flat-square&logo=medusa&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

> Headless storefront on **Medusa v2** with a Next.js 16 front end. I handled the platform upgrade to v2.17.2, covering breaking-change analysis, migration plan, and validation, plus storefront setup and pt-BR translation of the admin interface.

---

### 🏢 TOTVS Protheus · Consultoria e Customização de ERP

![Clientes corporativos](https://img.shields.io/badge/Clientes-Corporativos-6E7681?style=flat-square&logo=totvs&logoColor=white)
![10+ anos](https://img.shields.io/badge/10%2B_anos-1A56A0?style=flat-square)

> Customização e sustentação de **ERP TOTVS Protheus** para clientes corporativos, com foco no módulo de **Gestão de Contratos (GCT)**.

- **ADVPL / Protheus:** customizações e code review de fontes nos módulos de contratos, vendas e licitação.
- **Processos e documentação:** especificação de MITs, diagramas de processo e documentação de mudanças (GMUD).
- **Automação com IA:** agente RAG sobre a documentação técnica com banco vetorial, e integrações de gestão de atividades para acelerar o time.

> Customization and support of **TOTVS Protheus ERP** for enterprise clients, focused on the **Contract Management (GCT)** module: ADVPL development, source review, functional specification, change documentation, and process design.

---

## 🚀 Projetos em Destaque | Featured Projects

### 🤖 Meet AI · Plataforma de Reuniões com Agentes de IA

> Aplicação full stack de videoconferência com agentes de IA integrados. Cada reunião conta com um agente que participa em tempo real via OpenAI Realtime API, transcreve automaticamente, gera resumos pós-reunião e permite interação por chat. Background jobs orquestrados com Inngest Agent Kit, videochamadas com Stream.io Video SDK, chat em tempo real com Stream Chat e faturamento por uso com Stripe + Polar.

![Next.js 15](https://img.shields.io/badge/Next.js_15-black?style=flat-square&logo=nextdotjs)
![React 19](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![tRPC](https://img.shields.io/badge/tRPC-2596BE?style=flat-square&logo=trpc&logoColor=white)
![Stream.io](https://img.shields.io/badge/Stream.io-005FFF?style=flat-square&logo=stream&logoColor=white)
![Inngest](https://img.shields.io/badge/Inngest-6B21A8?style=flat-square&logo=inngest&logoColor=white)
![OpenAI Realtime](https://img.shields.io/badge/OpenAI_Realtime-412991?style=flat-square&logo=openai&logoColor=white)
![Better Auth](https://img.shields.io/badge/Better_Auth-1A1A1A?style=flat-square&logo=auth0&logoColor=white)
![Drizzle ORM](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

💻 [Repositório](https://github.com/diwberg/meetai)

---

### 🎙️ VoiceForge SaaS `TCC · 2026`

> Plataforma SaaS multi-tenant de geração de áudio e clonagem de voz com IA auto-hospedada (Chatterbox TTS em GPU serverless). Cobrança pay-as-you-go e API type-safe com tRPC.

![Next.js 16](https://img.shields.io/badge/Next.js_16-black?style=flat-square&logo=nextdotjs)
![tRPC](https://img.shields.io/badge/tRPC-2596BE?style=flat-square&logo=trpc&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Better Auth](https://img.shields.io/badge/Better_Auth-1A1A1A?style=flat-square&logo=auth0&logoColor=white)

---

### 💰 Financial Control System

> Dashboard financeiro completo com rastreamento de receitas/despesas, gráficos dinâmicos, filtros por período, autenticação e banco serverless. Full stack do banco à UI.

![Next.js 14](https://img.shields.io/badge/Next.js_14-black?style=flat-square&logo=nextdotjs)
![Hono](https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white)
![Drizzle ORM](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Neon DB](https://img.shields.io/badge/Neon_DB-00E5BF?style=flat-square&logo=neon&logoColor=black)
![Recharts](https://img.shields.io/badge/Recharts-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)

🔗 [Demo](https://control-tau.vercel.app/) · 💻 [Repositório](https://github.com/diwberg/control)

---

### 📦 n8n-nodes-llm-langfuse

> Pacote open source publicado no npm. Integra LLMs (OpenAI, Gemini, Groq) com observabilidade via Langfuse diretamente no ecossistema n8n.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm&logoColor=white)

💻 [Repositório](https://github.com/diwberg/n8n-nodes-llm-langfuse)

---

### ⏱️ React Pomodoro Timer

> App de produtividade com timer Pomodoro, histórico de sessões, controles completos e persistência via localStorage. Deploy em produção.

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

🔗 [Demo](https://react-pomodoro-dusky.vercel.app/) · 💻 [Repositório](https://github.com/diwberg/react-pomodoro)

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=diwberg&color=1A56A0&style=flat-square&label=Profile+Views" />
</div>
