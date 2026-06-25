<!-- ═══════════════════════════════════════════════════════════════════════════
     Iago Munhoz — README
     Estrutura: Hero · Proof · Engineering · Product Suite · Stack · Tools · CTA
     ═══════════════════════════════════════════════════════════════════════════ -->


<!-- ┌─────────────────────────────────────────────────────────────────────────┐
     │  HERO                                                                   │
     └─────────────────────────────────────────────────────────────────────────┘ -->

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=800&size=42&duration=1&pause=999999&color=1d4ed8&center=true&vCenter=true&width=900&height=80&lines=Iago+Munhoz" alt="Iago Munhoz" />
</p>

<p align="center">
  <strong>Engenheiro full stack — Next.js · TypeScript · Supabase · Postgres.</strong>
</p>

<p align="center">
  Construo aplicações B2B de ponta a ponta: arquitetura, banco, engine de regras e UI.<br/>
  Pra provar que a engenharia aguenta produto sério, construí o <a href="#-dualisai"><strong>Dualisai</strong></a> sozinho —<br/>
  SaaS multi-tenant com engine fiscal testada para a Reforma Tributária brasileira.
</p>

<p align="center">
  <a href="https://munhoz-iago.vercel.app"><strong>Portfolio →</strong></a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/munhoz-iago"><strong>LinkedIn →</strong></a> &nbsp;·&nbsp;
  <a href="mailto:iagomunhoz48@gmail.com"><strong>iagomunhoz48@gmail.com →</strong></a>
</p>

<br/>

<!-- ┌─────────────────────────────────────────────────────────────────────────┐
     │  PROOF BAR                                                              │
     └─────────────────────────────────────────────────────────────────────────┘ -->

<p align="center">
  <kbd>&nbsp;<strong>138</strong> testes em engine fiscal&nbsp;</kbd>
  <kbd>&nbsp;<strong>3</strong> produtos enviados&nbsp;</kbd>
  <kbd>&nbsp;<strong>C1</strong> Inglês (EF SET 62/100)&nbsp;</kbd>
  <kbd>&nbsp;<strong>2</strong> MCP servers próprios&nbsp;</kbd>
  <kbd>&nbsp;<strong>~40</strong> alunos formados em DEV&nbsp;</kbd>
</p>

<br/>

---

<!-- ┌─────────────────────────────────────────────────────────────────────────┐
     │  WHY ME — tese de contratação                                          │
     └─────────────────────────────────────────────────────────────────────────┘ -->

## 🧠 O que eu trago

Não sou júnior de tutorial. Construo software que precisa estar certo — fiscal, multi-tenant, com dinheiro real do outro lado.

- **2 anos de comércio exterior na Bosch Campinas** (SAP, Excel macros, Power BI, negociação C1 diária com times europeus e americanos) — entendo o domínio de negócio antes de codificar.
- **Professor titular de Desenvolvimento de Sistemas** na rede SEDUC-SP — explico arquitetura, back-end, mobile e redes todo dia. Se não dá pra ensinar, eu não entendi.
- **Tecnólogo em Análise e Desenvolvimento de Sistemas** (SENAI Roberto Mange, 2024) + Técnico em Mecatrônica (2022).
- **Inglês C1 verificado** — leio RFC, escrevo issue em open source, trabalho remoto sem fricção.

> Domínio do problema + engenharia que aguenta produção = a combinação que faltava no Dualisai, e a que levo pra qualquer time.

<br/>

---

<!-- ┌─────────────────────────────────────────────────────────────────────────┐
     │  PRODUCT SUITE                                                          │
     └─────────────────────────────────────────────────────────────────────────┘ -->

## 🚀 Produtos que enviei

Três produtos, três estágios de maturidade, mesmo padrão de engenharia.

<br/>

<!-- ┌─── DUALISAI ─────────────────────────────────────────────────────────────┐ -->

### 📊 [Dualisai](https://dualisia.com.br) &nbsp;·&nbsp; <sup>**MVP · em construção ativa**</sup>

> SaaS B2B multi-tenant para escritórios contábeis apurarem CBS e IBS sob a Reforma Tributária — o regime que entra em paralelo ao atual durante a transição.

<p>
  <code>Next.js 15</code>&nbsp;·&nbsp;<code>Supabase RLS</code>&nbsp;·&nbsp;<code>Inngest</code>&nbsp;·&nbsp;<code>Stripe</code>&nbsp;·&nbsp;<code>decimal.js</code>
</p>

<p>
  <strong>O problema:</strong> a partir de 2026, contadores brasileiros precisam apurar tributos em dois regimes durante a transição. ERPs grandes vão demorar; escritórios menores ficam sem ferramenta. Dualisai é a ponte.
</p>

<p>
  <strong>Engenharia:</strong> engine fiscal com <strong>138 testes automatizados</strong> · arithmetic 100% em <code>decimal.js</code> (zero float em cálculo de tributo) · schema multi-tenant com RLS em todas as tabelas · pipeline assíncrono de processamento de NF-e via Inngest · CI/CD em GitHub Actions.
</p>

<p>
  <sub>Engine e schema são privados (dados fiscais). Posso fazer walkthrough técnico em call.</sub>
</p>

<br/>

<!-- ┌─── NOBELLO ──────────────────────────────────────────────────────────────┐ -->

### 🛒 [Nobello](https://nobello.com.br) &nbsp;·&nbsp; <sup>**em produção**</sup>

> E-commerce com módulo de CRM nativo. Pipeline de retenção, gestão de fornecedores, automação de pós-compra.

<p>
  <code>Next.js</code>&nbsp;·&nbsp;<code>Supabase</code>&nbsp;·&nbsp;<code>Stripe</code>&nbsp;·&nbsp;<code>TypeScript</code>&nbsp;·&nbsp;<code>Tailwind</code>
</p>

<p>
  <strong>Decisões de arquitetura:</strong> stack server-first (RSC) pra não pagar JS desnecessário · webhooks Stripe idempotentes · RLS Supabase isolando dados de fornecedor.
</p>

<p>
  <a href="https://nobello.com.br"><strong>🌐 Ver em produção</strong></a>
</p>

<br/>

<!-- ┌─── SIMULAMEI ────────────────────────────────────────────────────────────┐ -->

### 🧮 [SimulaMEI](https://simulamei.com.br) &nbsp;·&nbsp; <sup>**no ar**</sup>

> Simulador tributário B2C que mostra quando um MEI deveria virar Simples Nacional — incluindo análise de Fator R.

<p>
  <code>Next.js</code>&nbsp;·&nbsp;<code>TypeScript</code>&nbsp;·&nbsp;<code>Tailwind</code>
</p>

<p>
  <strong>O problema:</strong> 14 milhões de MEIs no Brasil; a maioria não sabe quando ultrapassar o teto vira armadilha fiscal. Calculadoras existentes ignoram Fator R. SimulaMEI mostra o ponto exato de cruzamento e o custo de cada cenário.
</p>

<p>
  <a href="https://simulamei.com.br"><strong>🌐 Ver no ar</strong></a>
</p>

<br/>

---

<!-- ┌─────────────────────────────────────────────────────────────────────────┐
     │  STACK                                                                  │
     └─────────────────────────────────────────────────────────────────────────┘ -->

## 🛠️ Stack

<table>
<tr>
<td valign="top" width="33%">

**Frontend**

- Next.js 15 (App Router, RSC)
- React 19
- TypeScript estrito
- Tailwind + shadcn/ui
- Framer Motion

</td>
<td valign="top" width="33%">

**Backend & Data**

- Node.js / Bun
- PostgreSQL + Supabase
- Row-Level Security
- Inngest (jobs assíncronos)
- Prisma · decimal.js

</td>
<td valign="top" width="33%">

**Infra & DX**

- Vercel · GitHub Actions
- Stripe · webhooks idempotentes
- MCP servers (TypeScript)
- Claude Code (multi-agent)
- Figma · design tokens

</td>
</tr>
</table>

<p>
  <strong>Estudando agora:</strong> Java + Spring Boot · System Design · AWS fundamentals.
</p>

<br/>

---

<!-- ┌─────────────────────────────────────────────────────────────────────────┐
     │  DEVTOOLS                                                               │
     └─────────────────────────────────────────────────────────────────────────┘ -->

## 🧰 Ferramentas que construí pra mim mesmo

Quando o tooling não existe, eu construo. Mesmo padrão dos produtos: TypeScript, testes, README sério.

- **MCP Trello Server** — 17 ferramentas TypeScript pra operar Trello via Model Context Protocol.
- **MCP Windows Server** — automação de computador via `nut-js`, 10 ferramentas.
- **99Hunter** — extensão Chrome que escaneia 99Freelas e usa a Claude API pra dar score de fit.
- **wellfound-hunter / gupy-hunter** — scrapers Python pra mercado de trabalho.

<p>
  <a href="https://github.com/munhoz-iago"><strong>→ Ver no GitHub</strong></a>
</p>

<br/>

---

<!-- ┌─────────────────────────────────────────────────────────────────────────┐
     │  NUMBERS                                                                │
     └─────────────────────────────────────────────────────────────────────────┘ -->

## 📈 Números (atualizados pelo GitHub)

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=munhoz-iago&show_icons=true&theme=transparent&hide_border=true&title_color=0f172a&icon_color=0f172a&text_color=334155&include_all_commits=true&count_private=true&hide=issues" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=munhoz-iago&layout=compact&theme=transparent&hide_border=true&title_color=0f172a&text_color=334155&langs_count=6&hide=html,css" />
</p>

<br/>

---

<!-- ┌─────────────────────────────────────────────────────────────────────────┐
     │  TEACHING                                                               │
     └─────────────────────────────────────────────────────────────────────────┘ -->

## 🎓 Também ensino

Professor titular do curso **Técnico em Desenvolvimento de Sistemas** na EE Tenista Maria Esther Bueno (SEDUC-SP, Campinas). Cubro back-end, mobile, redes e lógica de programação.

> Se eu não consigo explicar uma arquitetura pra um adolescente de 16 anos, eu não entendi a arquitetura.

<br/>

---

<!-- ┌─────────────────────────────────────────────────────────────────────────┐
     │  CTA                                                                    │
     └─────────────────────────────────────────────────────────────────────────┘ -->

## 📬 Conversemos

Estou aberto a conversar sobre:

- **Vagas full stack pleno** — remoto, ou Campinas/SP presencial.
- **Consultoria pontual** — Next.js, Supabase, Stripe, arquitetura B2B SaaS.
- **Parceria em produto** — especialmente no espaço fiscal/contábil brasileiro.

<p>
  <a href="mailto:iagomunhoz48@gmail.com"><img src="https://img.shields.io/badge/iagomunhoz48@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/munhoz-iago"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://munhoz-iago.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
</p>

<p>
  <sub>📞 +55 19 99863-3898 · 🇧🇷 Campinas, SP</sub>
</p>

<br/>

<p align="center">
  <sub><i>"Mercado bom é problema caro, regulado e com dor recorrente. É onde engenharia decente vira vantagem real."</i></sub>
</p>
