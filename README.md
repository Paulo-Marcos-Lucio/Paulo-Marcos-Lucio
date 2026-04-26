<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--                              BANNER                                    -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

<a href="https://github.com/Paulo-Marcos-Lucio">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:1f6feb,100:8957e5&height=240&section=header&text=Paulo%20Marcos%20Lucio&fontSize=64&fontColor=ffffff&fontAlignY=38&desc=Eng.%20Java%20%C2%B7%20Consultor%20em%20Integra%C3%A7%C3%B5es%20Regulat%C3%B3rias%20BR&descAlignY=58&descSize=18&animation=fadeIn"
       alt="Paulo Marcos Lucio · Engenheiro Java · Consultor em integrações regulatórias BR" />
</a>

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--                          TAGLINES ROTATIVAS                           -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

<div align="center">

<a href="https://github.com/Paulo-Marcos-Lucio">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=2200&color=58A6FF&center=true&vCenter=true&width=820&lines=Engenheiro+Java+pleno+%E2%80%94+Spring+Boot+%2B+arquiteturas+distribu%C3%ADdas;Consultor+em+integra%C3%A7%C3%B5es+regulat%C3%B3rias+do+mercado+financeiro+BR;Pix+Autom%C3%A1tico+%C2%B7+Open+Finance+%C2%B7+DICT+%C2%B7+Open+Insurance;Adequa%C3%A7%C3%A3o+de+c%C3%B3digo+Java+legado+%E2%80%94+arquitetura+hexagonal%2C+DDD%2C+resilience;Pra+fintechs+que+n%C3%A3o+podem+errar."
       alt="taglines rotativas" />
</a>

<br/>

<a href="https://www.linkedin.com/in/paulo-marcos-a07379174/">
  <img src="https://img.shields.io/badge/LinkedIn-Conectar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
&nbsp;
<a href="mailto:pmlsp23@gmail.com">
  <img src="https://img.shields.io/badge/E--mail-pmlsp23%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
&nbsp;
<a href="https://github.com/Paulo-Marcos-Lucio?tab=repositories">
  <img src="https://img.shields.io/badge/Su%C3%ADte%20Regulat%C3%B3ria%20BR-Ver%20repos-1f6feb?style=for-the-badge&logo=github&logoColor=white" alt="Repos" />
</a>
&nbsp;
<img src="https://img.shields.io/badge/Localiza%C3%A7%C3%A3o-S%C3%A3o%20Paulo%2C%20BR-238636?style=for-the-badge&logo=googlemaps&logoColor=white" alt="São Paulo" />

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--                              SOBRE                                    -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

## 👋 Sobre

Sou **engenheiro Java desde 2020**, com foco em **Spring Boot, arquiteturas distribuídas e padrões production-grade** (hexagonal, idempotência, outbox, saga, resilience). Hoje atuo como **consultor em integrações regulatórias do mercado financeiro brasileiro** — Pix, Open Finance e Open Insurance — e em **adequação de código Java legado** (uplift de monolitos crus pra arquitetura limpa, observabilidade end-to-end e CI/CD profissional).

Construo aqui no GitHub uma **suíte pública de implementações de referência** dos contratos regulatórios mais críticos do BCB e da Susep — código que sua fintech, banco médio ou PSP pode clonar, estudar ou usar como baseline pra adequação. Cada repo tem ADRs explicando *por quê* cada decisão foi tomada, observabilidade real ligada a Grafana, simuladores in-process pra testar sem certificado de produção, e CI com 7+ jobs paralelos. **Padrão de código que sobrevive a auditoria.**

> Sua empresa precisa de revisão de arquitetura, gap analysis regulatório ou implementação assistida em **Pix Automático, DICT, Open Finance Fase 4 ou Open Insurance**? **[Me chama no LinkedIn.](https://www.linkedin.com/in/paulo-marcos-a07379174/)**

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--                  SUÍTE DE REFERÊNCIA REGULATÓRIA BR                   -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

## 🇧🇷 Suíte de Referência Regulatória BR

Implementações *production-grade* dos contratos regulatórios mais críticos do mercado financeiro brasileiro. Cada repo é open source (MIT) e roda end-to-end na sua máquina em < 2 minutos.

<table>
<tr>
<td width="50%" valign="top">

### ✅ <a href="https://github.com/Paulo-Marcos-Lucio/pix-automatico-reference">pix-automatico-reference</a>
<sub>Spring Boot 3.4 · Java 21 · React + TypeScript</sub>

Implementação de referência do **Pix Automático** + **Open Finance Fase 4**, com painel operacional React empacotado no mesmo JAR. Hexagonal, **Saga** orquestrada, **Outbox**, **idempotência em 3 camadas**, OpenTelemetry end-to-end, 5 ADRs.

<a href="https://github.com/Paulo-Marcos-Lucio/pix-automatico-reference">
  <img src="https://img.shields.io/badge/-Ver%20repo-238636?style=flat-square&logo=github&logoColor=white" />
</a>

</td>
<td width="50%" valign="top">

### ✅ <a href="https://github.com/Paulo-Marcos-Lucio/dict-client-reference">dict-client-reference</a>
<sub>Spring Boot 3.4 · Java 21 · Caffeine · Resilience4j</sub>

Cliente Java pro **DICT do BCB** (diretório de chaves Pix). **mTLS via SslBundle (ICP-Brasil ready)**, cache *regulatory-aware* (clamp ao máximo BCB), **simulador local in-process**, 21 painéis Grafana versionados, 6 ADRs, CI com 7 jobs paralelos.

<a href="https://github.com/Paulo-Marcos-Lucio/dict-client-reference">
  <img src="https://img.shields.io/badge/-Ver%20repo-238636?style=flat-square&logo=github&logoColor=white" />
</a>

</td>
</tr>
<tr>
<td valign="top">

### 🔜 pix-nfc-reference
<sub>Em breve</sub>

**Pix por aproximação (NFC)** — spec recém-publicada pelo BCB. Reference do fluxo end-to-end, app demo Android opcional, integração com wallets via HCE.

</td>
<td valign="top">

### 🔜 open-finance-payments-reference
<sub>Em breve</sub>

**Iniciação de Pagamentos** do Open Finance Brasil (Fase 4). FAPI 2.0 + Brasil profile, JWS/JWE encadeados, conformance suite, integração com Diretório Central simulado.

</td>
</tr>
<tr>
<td valign="top">

### 🔜 open-insurance-transmissor-reference
<sub>Em breve</sub>

**OPIN — Open Insurance Brasil**. Padrão Susep (FAPI-CIBA), modelagem de produtos, transmissor de dados de seguros, dashboard de consents.

</td>
<td valign="top">

### 💼 Consultoria
<sub>Auditoria · Roadmap · Implementação assistida</sub>

Para sua empresa: gap analysis BCB/Susep, design de adequação, hands-on em sprint, code review recorrente. **[Conversa no LinkedIn](https://www.linkedin.com/in/paulo-marcos-a07379174/)** ou abre uma **[issue de contato](https://github.com/Paulo-Marcos-Lucio/dict-client-reference/issues/new?labels=contact)**.

</td>
</tr>
</table>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--                              STACK                                    -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

## 🛠️ Stack que entrego em produção

<details open>
<summary><b>🚀 Backend & arquitetura</b></summary>
<br/>

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=java,spring,kotlin,maven,gradle,hibernate,kafka,redis,postgres,mysql,mongodb,rabbitmq" />
</a>

`Java 21` · `Spring Boot 3.4` · `Spring Cloud` · `JPA/Hibernate` · `Flyway` · `Kafka` · `Redis` · `PostgreSQL` · `RabbitMQ` · `MapStruct` · `Lombok` · **Hexagonal Architecture · DDD · CQRS · Event Sourcing · Saga · Outbox · Idempotência forte**

</details>

<details>
<summary><b>📊 Observabilidade & resilience</b></summary>
<br/>

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=grafana,prometheus" />
</a>

`OpenTelemetry` · `Micrometer` · `Prometheus` · `Tempo` · `Loki` · `Grafana` · `Logstash JSON` · `Resilience4j` (CB · retry · rate limit · bulkhead) · **W3C Trace Context** · **dashboards versionados como código**

</details>

<details>
<summary><b>☁️ DevOps & infra</b></summary>
<br/>

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,linux,bash,git,github,githubactions,terraform,nginx" />
</a>

`Docker` · `Docker Compose` · `Kubernetes` · `Helm` · `GitHub Actions` · `Terraform` · `Nginx` · `Linux` · `Spring Boot Buildpacks (OCI)` · **CI/CD multi-stage com SAST/SBOM/SARIF**

</details>

<details>
<summary><b>🧪 Qualidade & segurança</b></summary>
<br/>

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=idea,vscode,postman" />
</a>

`JUnit 5` · `AssertJ` · `Mockito` · `Testcontainers` · `WireMock` · `Pact` · `ArchUnit` · `JaCoCo` · `CodeQL` · `Semgrep` · `Trivy` · `Dependabot` · **SBOM CycloneDX**

</details>

<details>
<summary><b>🎨 Frontend (quando faz sentido)</b></summary>
<br/>

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=ts,react,tailwind,vite" />
</a>

`React 18` · `TypeScript` · `Vite` · `Tailwind CSS` · `shadcn/ui` · `TanStack Query` · `React Router` · **single-artifact deploy (SPA bundled no JAR Spring)**

</details>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--                              STATS                                    -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

## 📈 GitHub stats

<div align="center">

<table>
<tr>
<td>
<img height="180" src="https://github-readme-stats.vercel.app/api?username=Paulo-Marcos-Lucio&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&card_width=480&title_color=58a6ff&icon_color=58a6ff&text_color=e6edf3&bg_color=0d1117" alt="GitHub stats" />
</td>
<td>
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Paulo-Marcos-Lucio&layout=compact&theme=tokyonight&hide_border=true&card_width=380&langs_count=8&title_color=58a6ff&text_color=e6edf3&bg_color=0d1117" alt="Top langs" />
</td>
</tr>
</table>

<img src="https://github-readme-streak-stats.herokuapp.com?user=Paulo-Marcos-Lucio&theme=tokyonight&hide_border=true&background=0d1117&stroke=30363d&ring=58a6ff&fire=ffa657&currStreakLabel=58a6ff&sideLabels=8b949e&dates=8b949e&currStreakNum=e6edf3&sideNums=e6edf3" alt="Streak" height="180" />

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--                          POR QUE ME CHAMAR                            -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

## 💼 Por que me chamar pro seu projeto

<table>
<tr>
<td width="33%" valign="top" align="center">

### 🎯
**Foco em risco regulatório**

Multa BCB > R$ 100k facilmente. Meu trabalho é eliminar esse risco — não adicionar features.

</td>
<td width="33%" valign="top" align="center">

### 🏗️
**Adequação de legado**

Uplift de monolito crú pra hexagonal + resilience + observabilidade, sem big-bang rewrite.

</td>
<td width="33%" valign="top" align="center">

### 📐
**Padrão production-grade**
 
ADRs, observabilidade end-to-end, CI multi-stage, SBOM, audit log. Código que **sobrevive a auditoria**.

</td>
</tr>
</table>

<br/>

<!-- ═══════════════════════════════════════════════════════════════════════ -->
<!--                              CTA FINAL                                -->
<!-- ═══════════════════════════════════════════════════════════════════════ -->

<div align="center">

## 📬 Vamos conversar

**[LinkedIn](https://www.linkedin.com/in/paulo-marcos-a07379174/)** · **[E-mail](mailto:pmlsp23@gmail.com)** · **[Issue de contato](https://github.com/Paulo-Marcos-Lucio/dict-client-reference/issues/new?labels=contact)**

<br/>

<sub>Se algum repo da Suíte ajudou seu time, ⭐ uma star nele — ajuda outros engenheiros do nicho a encontrarem.</sub>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8957e5,60:1f6feb,100:0d1117&height=120&section=footer" alt="footer" />

</div>
