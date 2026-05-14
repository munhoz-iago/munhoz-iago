<!-- ═══════════════════════════════════════════════════════════════════════════
     Iago Munhoz — README como landing page de SaaS
     Estrutura: Hero · Proof · Product Suite · Stack · Numbers · CTA
     ═══════════════════════════════════════════════════════════════════════════ -->


<!-- ┌─────────────────────────────────────────────────────────────────────────┐
     │  HERO                                                                   │
     └─────────────────────────────────────────────────────────────────────────┘ -->

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=800&size=42&duration=1&pause=999999&color=1d4ed8&center=true&vCenter=true&width=900&height=80&lines=Iago+Munhoz" alt="Iago Munhoz" />
</p>

<p align="center">
  <strong>Building B2B SaaS that solves expensive Brazilian problems.</strong>
</p>

<p align="center">
  Engenheiro full stack focado em produtos para o mercado fiscal e contábil brasileiro.<br/>
  Atualmente construindo o <a href="#-fiscalia"><strong>Fiscalia</strong></a>, plataforma para escritórios contábeis<br/>
  navegarem a transição da Reforma Tributária de R$ 2,3 trilhões (2026–2033).
</p>

<p align="center">
  <a href="https://munhoz-iago.vercel.app"><strong>Portfolio →</strong></a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/munhoz-iago"><strong>LinkedIn →</strong></a> &nbsp;·&nbsp;
  <a href="mailto:iagomunhoz48@gmail.com"><strong>iagomunhoz48@gmail.com →</strong></a>
</p>

<br/>

<!-- ┌─────────────────────────────────────────────────────────────────────────┐
     │  PROOF BAR — números que destoam de júnior                              │
     └─────────────────────────────────────────────────────────────────────────┘ -->

<p align="center">
  <kbd>&nbsp;<strong>3</strong> produtos em produção&nbsp;</kbd>
  <kbd>&nbsp;<strong>138</strong> testes em engine fiscal&nbsp;</kbd>
  <kbd>&nbsp;<strong>C1</strong> Inglês (EF SET 62/100)&nbsp;</kbd>
  <kbd>&nbsp;<strong>2</strong> MCP servers próprios&nbsp;</kbd>
  <kbd>&nbsp;<strong>~40</strong> alunos formados em DEV&nbsp;</kbd>
</p>

<br/>

---

<!-- ┌─────────────────────────────────────────────────────────────────────────┐
     │  PRODUCT SUITE — Nobello · Fiscalia · SimulaMEI                         │
     └─────────────────────────────────────────────────────────────────────────┘ -->

## 🚀 Product Suite

Três produtos. Três etapas distintas de maturidade. Mesmo padrão de engenharia.

<br/>

<!-- ┌─── PRODUTO 1: NOBELLO ───────────────────────────────────────────────────┐ -->

### 🛒 [Nobello](https://nobello.com.br) &nbsp;·&nbsp; <sup>**em produção · Google Ads ativo**</sup>

> E-commerce com módulo de CRM nativo. Pipeline de retenção, gestão de fornecedores, automação de pós-compra. Não é vitrine — é receita.

<p>
  <code>Next.js</code>&nbsp;·&nbsp;<code>Supabase</code>&nbsp;·&nbsp;<code>Stripe</code>&nbsp;·&nbsp;<code>TypeScript</code>&nbsp;·&nbsp;<code>Tailwind</code>
</p>

<p>
  <strong>O que ele resolve:</strong> e-commerces pequenos perdem cliente por não terem CRM. Plataformas de CRM custam R$ 300+/mês e não falam com o catálogo. Nobello unifica os dois.
</p>

<p>
  <strong>Decisões de arquitetura:</strong> stack server-first (RSC) pra não pagar JS desnecessário · webhooks Stripe idempotentes · RLS Supabase isolando dados de fornecedor.
</p>

<p>
  <a href="https://nobello.com.br"><strong>🌐 Ver em produção</strong></a>
</p>

<br/>

<!-- ┌─── PRODUTO 2: FISCALIA ──────────────────────────────────────────────────┐ -->

### 📊 Fiscalia &nbsp;·&nbsp; <sup>**MVP semana 7/12 · launch Q3/2026**</sup>

> B2B SaaS multi-tenant para escritórios contábeis brasileiros calcularem CBS e IBS em paralelo ao regime atual durante a transição da Reforma Tributária.

<p>
  <code>Next.js 15</code>&nbsp;·&nbsp;<code>Supabase RLS</code>&nbsp;·&nbsp;<code>Inngest</code>&nbsp;·&nbsp;<code>Stripe</code>&nbsp;·&nbsp;<code>decimal.js</code>
</p>

<p>
  <strong>O que ele resolve:</strong> a partir de 2026, todo contador brasileiro precisa calcular tributos em <strong>dois regimes simultaneamente</strong> por 7 anos. ERPs grandes vão demorar anos para entregar. Escritórios menores vão sofrer. Fiscalia é a ponte.
</p>

<p>
  <strong>Engenharia:</strong> engine fiscal com <strong>138 testes automatizados</strong> cobrindo 12 regras de negócio (RN-001 → RN-012) · schema multi-tenant com 9 tabelas e RLS · pipeline assíncrono de processamento de NFe via Inngest · 5 sub-agents Claude Code para acelerar feature work.
</p>

<p>
  <strong>Modelo:</strong> SaaS B2B · meta R$ 50k MRR em 18–24 meses · INPI classes 09/42 em registro.
</p>

<br/>

<!-- ┌─── PRODUTO 3: SIMULAMEI ─────────────────────────────────────────────────┐ -->

### 🧮 SimulaMEI &nbsp;·&nbsp; <sup>**spec completa · em desenvolvimento**</sup>

> Simulador tributário B2C que mostra quando um MEI deveria virar Simples Nacional — incluindo análise de Fator R.

<p>
  <code>Next.js</code>&nbsp;·&nbsp;<code>TypeScript</code>&nbsp;·&nbsp;<code>Tailwind</code>
</p>

<p>
  <strong>O que ele resolve:</strong> 14 milhões de MEIs no Brasil. A maioria não sabe quando ultrapassar o teto vira armadilha fiscal. Calculadoras existentes ignoram Fator R e atividade. SimulaMEI mostra o ponto exato de cruzamento e o custo de cada cenário.
</p>

<br/>

---

<!-- ┌─────────────────────────────────────────────────────────────────────────┐
     │  WHY ME — o que sustenta os três acima                                  │
     └─────────────────────────────────────────────────────────────────────────┘ -->

## 🧠 Por que esses três produtos fazem sentido

Não saí escolhendo problema aleatório.

- **2 anos de comércio exterior na Bosch Campinas** (SAP, Excel macros, Power BI, negociação C1 com fornecedores europeus) — entendo a dor fiscal antes de codificar.
- **Professor titular de Desenvolvimento de Sistemas** na rede SEDUC-SP — explico arquitetura todo dia pra adolescente. Se não der pra ensinar, eu não entendi.
- **Tecnólogo em Análise e Desenvolvimento de Sistemas** (SENAI Roberto Mange, 2024) + Técnico em Mecatrônica (2022).
- **Inglês C1 verificado** — leio RFC, escrevo issue em projeto open source, negocio remoto sem fricção.

> Mercado fiscal brasileiro = problema caro + barreira de entrada alta + dor recorrente. Engenharia decente + domínio do problema = vantagem injusta.

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
- MCP servers (TS)
- Claude Code (5 sub-agents)
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
     │  OPEN SOURCE & DEVTOOLS                                                 │
     └─────────────────────────────────────────────────────────────────────────┘ -->

## 🧰 Ferramentas que construí pra mim mesmo

Quando o tooling não existe, eu construo. Mesmo padrão dos produtos: TypeScript, testes, README sério.

- **[MCP Trello Server](https://github.com/MunhozIago244)** — 17 ferramentas TypeScript pra Claude operar Trello via Model Context Protocol.
- **MCP Windows Server** — automação de computador via `nut-js`, 10 ferramentas.
- **99Hunter** — extensão Chrome que escaneia 99Freelas e usa Claude API pra dar score de FIT.
- **wellfound-hunter / gupy-hunter** — scrapers Python pra job market.

<br/>

---

<!-- ┌─────────────────────────────────────────────────────────────────────────┐
     │  NUMBERS                                                                │
     └─────────────────────────────────────────────────────────────────────────┘ -->

## 📈 Números (atualizados pelo GitHub)

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=MunhozIago244&show_icons=true&theme=transparent&hide_border=true&title_color=0f172a&icon_color=0f172a&text_color=334155&include_all_commits=true&count_private=true&hide=issues" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MunhozIago244&layout=compact&theme=transparent&hide_border=true&title_color=0f172a&text_color=334155&langs_count=6&hide=html,css" />
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
  <sub><i>"Mercado bom é mercado caro, regulado e com dor recorrente. O resto é hobby."</i></sub>
</p>
