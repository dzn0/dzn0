<div align="center">

# Olá, meu nome é André Pieri.
### DESENVOLVEDOR FULL-STACK
### Node.js • Express • Next.js • React

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-121212?style=for-the-badge&logoColor=white)](https://andrepieri.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dzn0)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andr%C3%A9-pieri-914563358/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:andrepereirapieri@gmail.com)

<br/>

<img src="ulquiorra-ulquiorra-cifer.gif" width="100%" alt="Ulquiorra Cifer">

</div>

---

## SOBRE MIM

Sou desenvolvedor full-stack focado em construir aplicações web do zero, entendendo bem cada camada antes de pular para abstrações prontas. Gosto de aprender pelos fundamentos: comecei com Node.js e Express puro antes de migrar para frameworks mais robustos, porque prefiro entender o "porquê" antes do "como".

Hoje trabalho em projetos que vão de ferramentas de automação a plataformas com uso real por outras pessoas, sempre buscando código limpo e decisões de arquitetura que façam sentido a longo prazo.

> [!IMPORTANT]
> Dá uma olhada nos meus **[projetos](#projetos)** ou me manda uma mensagem se quiser trocar uma ideia sobre algum deles.

---

## PROJETOS

### [Analisa CV](https://analisacv.com.br) — 🟢 em produção

Produto completo em produção, usado por pessoas reais em [analisacv.com.br](https://analisacv.com.br).

O fluxo é simples do lado do usuário: ele sobe o currículo em PDF, responde 5 perguntas rápidas de personalização e recebe uma análise completa em menos de um minuto. Por trás disso:

- **Frontend** em JavaScript puro (sem framework), HTML e CSS — decisão deliberada para manter o app leve e sem overhead de build.
- **PDF.js** extrai o texto do currículo enviado direto no navegador.
- O texto extraído vai para o **backend**, que roda como **Vercel Edge Functions** (também em JavaScript puro), garantindo baixa latência.
- O backend envia o conteúdo para a **API da Anthropic (Claude Haiku)**, que faz a análise e reescrita estruturada do currículo.
- O resultado final é exportado em PDF com **html2pdf**.
- **Cobrança** integrada via **Pix (Mercado Pago)** e **cartão (Stripe)**, ou seja, é um produto com monetização real, não só um projeto de portfólio.

**Stack:** JavaScript · HTML/CSS · PDF.js · html2pdf · Vercel Edge Functions · Claude API · Mercado Pago · Stripe

**Links:** [Produto](https://analisacv.com.br) · [Código](https://github.com/dzn0/analisa-cv)

---

### [Portfólio](https://github.com/dzn0/portfolio) — 🟢 ativo

Meu site pessoal, estruturado como monorepo com frontend e backend separados — um projeto que uso também como espaço de aprendizado deliberado de backend.

**Frontend** em Next.js 16 (App Router) com React 19 e Tailwind CSS 4:

- Seção de atividade do GitHub (`GithubActivity.tsx`) usando `react-github-calendar` para mostrar o calendário de contribuições direto na página.
- Efeitos de interação como reveal-on-scroll (`revealOnScreen.tsx`) e resposta a movimento do mouse (`onMouseMove.tsx`) para dar mais vida à interface.
- Lightbox próprio para visualização de imagens/projetos e um toggle de tema claro/escuro persistente.
- Contador de visitantes (`VisitCount.tsx`) que consome o backend em tempo real.

**Backend** em Node.js com Express 5, TypeScript e Prisma 7 sobre PostgreSQL:

- Um único model, `Visit` (ip, createdAt, com `ip` único), que registra visitantes únicos por IP — é o que alimenta o contador "x pessoas" do frontend.
- Escrito em Express puro (sem NestJS ou outro framework de abstração) de forma intencional: a ideia é consolidar o entendimento de rotas, middlewares e integração com banco na mão antes de migrar para um framework mais opinativo mais adiante.
- Deploy serverless (há `vercel.json` e uma pasta `api/` dedicada), então o backend roda como funções na Vercel, assim como o frontend.

**Stack:** Next.js · React · TypeScript · Tailwind CSS · Express · Prisma · PostgreSQL

**Link:** [github.com/dzn0/portfolio](https://github.com/dzn0/portfolio)

---

## STACK

**Linguagens & Runtime**
Node.js · JavaScript · TypeScript

**Backend**
Express · NestJS (aprendendo)

**Frontend**
React · Next.js · HTML · CSS

**Ferramentas**
Git · GitHub · VS Code · npm


## CONTATO

<sub>Aberto a trocar ideia sobre projetos full-stack, automações e sistemas web práticos.</sub>

- **GitHub:** [github.com/dzn0](https://github.com/dzn0)
- **Portfólio:** [andrepieri.vercel.app](https://andrepieri.vercel.app/)
- **LinkedIn:** [in/andré-pieri](https://www.linkedin.com/in/andr%C3%A9-pieri-914563358/)
- **Email:** [andrepereirapieri@gmail.com](mailto:andrepereirapieri@gmail.com)

<br/>
