<!-- ════════════════════════════════════════════════════════════════════════
     Paulo Marcos Lucio · perfil GitHub — VIGÍLIA REV. B (Centro de Comando)
     Assets SVG próprios, auto-hospedados em ./assets — autocontidos (SMIL),
     zero refs externas, animados via <img> atrás do camo do GitHub.
     Regras de manutenção:
       · camo cacheia por URL de forma agressiva: NUNCA editar um asset
         reaproveitando o nome antigo — asset novo = nome de arquivo NOVO.
       · TEMA CLARO é do VISITANTE, não do dono da página — metade de quem
         abre o perfil vê fundo #ffffff. Todo painel de largura cheia precisa
         de: fundo opaco + rx=16 + rim hairline + conteúdo dentro de <clipPath>.
         Sem isso vira laje de canto vivo boiando no branco. (A leva "abismo"
         de 28/07 nasceu sem essa proteção; corrigida na série -v2.)
       · Zero shields.io nesta página. Um <img> = um link só.
       · Alt significativo em PT-BR em toda imagem. Quando o SVG é uma
         imagem-de-texto, o alt do <img> tem de CARREGAR a informação: o
         aria-label interno do SVG é descartado pelo camo do GitHub.
       · Números SÓ de fatos reais, arredondados PARA BAIXO (466 → 460+).
       · SARIF 2.1.0 existe no Sentinela, no Guardião e na Esteira.
         O Chaveiro NÃO tem SARIF. (Conferido no código público em 29/07/2026;
         o comentário anterior, que dizia que o Sentinela não tinha, era falso.)
       · "OWASP Top 10" no Laboratório SEMPRE com o qualificador: são
         8 vulnerabilidades cobrindo 4 categorias — A01, A02, A03 e A10.
       · SMIL não respeita prefers-reduced-motion. Toda peça pesada precisa
         de um par -parado.svg servido via <picture media="...">.
       · Nenhuma certificação é mencionada — não inventar OSCP/CEH/clientes.
       · Ética no footer em SVG E em <sub> de texto real, sempre.
     ════════════════════════════════════════════════════════════════════════ -->

<a href="https://paulo-marcos-lucio.github.io">
  <picture>
    <source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/hero-abismo-v3-parado.svg">
    <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/hero-abismo-v3.svg" alt="Paulo Marcos Lucio — Segurança de Aplicações Web (AppSec): diagnóstico e correção de vulnerabilidades web. Olho de vigília com radar no abismo bioluminescente. Rodapé do painel: 5 ferramentas · 460+ testes automatizados · MIT · CI verde." width="100%"/>
  </picture>
</a>

<div align="center">

<a href="https://www.linkedin.com/in/paulo-marcos-a07379174/">
  <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/btn-linkedin-v2.svg" alt="LinkedIn — falar com Paulo Marcos Lucio" width="210"/>
</a>
<a href="mailto:pmlsp23@gmail.com">
  <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/btn-email-v2.svg" alt="E-mail — pmlsp23@gmail.com" width="210"/>
</a>
<a href="https://paulo-marcos-lucio.github.io">
  <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/btn-site.svg" alt="Site — serviços, pacotes e valores" width="210"/>
</a>
<a href="https://github.com/Paulo-Marcos-Lucio?tab=repositories">
  <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/btn-repos.svg" alt="Todos os repositórios no GitHub" width="210"/>
</a>

<br/><sub>São Paulo, BR — remote-first</sub>

</div>

<br/>

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/divider-scan.svg" alt="Divisor de seção — linha de varredura de dados" width="100%"/>

<br/>

<div align="center"><a href="https://github.com/Paulo-Marcos-Lucio/sentinela">
  <picture>
    <source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/console-sentinela-parado.svg">
    <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/console-sentinela.svg" alt="Console do Sentinela: diagnóstico real de paulo-marcos-lucio.github.io em 21/07/2026, com o comando `sentinela scan paulo-marcos-lucio.github.io -f markdown`. 8 checagens executadas, modo não-intrusivo, sob autorização e escopo definido. Resultados: TLS válido e HSTS ativo (OK); Content-Security-Policy ausente (MÉDIO, OWASP A02); sem proteção contra clickjacking (MÉDIO, A02); registro DMARC ausente (MÉDIO, A07); Referrer-Policy ausente (BAIXO, A02); X-Content-Type-Options ausente (BAIXO, A02); mais 4 informativos (COOP, Permissions-Policy, DNSSEC, HSTS sem includeSubDomains). Resumo: 0 críticos, 0 altos, 3 médios, 2 baixos, 4 informativos — nota de higiene 70/100, conceito C. Reproduzível." width="88%"/>
  </picture>
</a></div>

<br/>

## `~/` Sobre

Atuo com **segurança de aplicações web (AppSec)**: **diagnóstico e correção de vulnerabilidades**, hardening e prevenção de falhas em sistemas expostos na internet — cabeçalhos de segurança, TLS/PKI, cookies, CORS, exposição de arquivos e segurança de DNS/e-mail — tudo mapeado ao **OWASP Top 10** e à **LGPD (art. 46)**.

Não venho "de fora" da engenharia. Meu background é **backend Java para o mercado financeiro regulado** — autenticação, mTLS ICP-Brasil, FAPI, integrações Pix e Open Finance — ou seja, venho de construir sistemas **onde errar em segurança não é uma opção**. Trago essa régua para o diagnóstico da sua aplicação: minhas recomendações de correção são realistas para o time de dev, porque eu **fui** o time de dev.

> **Precisa saber onde sua aplicação web está exposta — e como corrigir?**
> **[Fale comigo no LinkedIn](https://www.linkedin.com/in/paulo-marcos-a07379174/)** · ou veja os pacotes em **[paulo-marcos-lucio.github.io](https://paulo-marcos-lucio.github.io)**

<br/>

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/ops-telemetry-v2.svg" alt="Telemetria da operação: 5 ferramentas abertas, 460+ testes automatizados, licença MIT com CI verde nas cinco ferramentas da suíte, mapeamento OWASP Top 10 e LGPD art. 46" width="100%"/>

<br/>

## `~/` Suíte AppSec

Um portfólio de **ferramentas de segurança de aplicações** — cada uma cobre uma frente do OWASP Top 10, do perímetro à autenticação, dos segredos vazados à cadeia de suprimentos. Todas com **testes, CI e documentação de nível de produto**: a ferramenta **é** a prova do critério técnico.

<a href="https://github.com/Paulo-Marcos-Lucio/sentinela"><picture>
<source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-sentinela-abismo-v2-parado.svg">
<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-sentinela-abismo-v2.svg" alt="Sentinela — diagnóstico externo não-intrusivo: o que o atacante vê. Chips: TLS, Cabeçalhos, DNS/CT. Selo &quot;PRO · privado&quot;: a leitura profunda fica na edição Pro, que é privada. &quot;O olho que vela a sua superfície — no escuro.&quot;" width="100%"/>
</picture></a>

<a href="https://github.com/Paulo-Marcos-Lucio/guardiao"><picture>
<source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-guardiao-abismo-v2-parado.svg">
<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-guardiao-abismo-v2.svg" alt="Guardião — scanner de segredos no código e no histórico Git. Chips: regex+entropia, baseline, pre-commit. Selo &quot;PRO · privado&quot;: a leitura profunda fica na edição Pro, que é privada. &quot;O escudo que guarda a fronteira.&quot;" width="100%"/>
</picture></a>

<a href="https://github.com/Paulo-Marcos-Lucio/chaveiro"><picture>
<source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-chaveiro-abismo-v2-parado.svg">
<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-chaveiro-abismo-v2.svg" alt="Chaveiro — auditor de tokens JWT/JWS. Chips: alg:none, alg-confusion, HMAC crack. Ilustração do token em três partes: eyJ… .payload. sig. Selo &quot;PRO · privado&quot;: a leitura profunda fica na edição Pro, que é privada." width="100%"/>
</picture></a>

<a href="https://github.com/Paulo-Marcos-Lucio/esteira"><picture>
<source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-esteira-abismo-v2-parado.svg">
<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-esteira-abismo-v2.svg" alt="Esteira — segurança de pipelines · GitHub Actions. Chips: script-injection, SHA-pinning, pr-target. Selo &quot;PRO · privado&quot;: a leitura profunda fica na edição Pro, que é privada. &quot;O ataque moderno entra pela correnteza. Ela vigia o fluxo.&quot;" width="100%"/>
</picture></a>

<a href="https://github.com/Paulo-Marcos-Lucio/laboratorio-owasp"><picture>
<source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-laboratorio-abismo-v2-parado.svg">
<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-laboratorio-abismo-v2.svg" alt="Laboratório OWASP — laboratório de vulnerabilidades. Chips: OWASP Top 10 (na prática, 8 vulnerabilidades em 4 categorias: A01, A02, A03 e A10), Java, hands-on. Selo &quot;PRO · privado&quot;: a leitura profunda fica na edição Pro, que é privada. &quot;Onde a falha é de propósito — pra você aprender a defender.&quot;" width="100%"/>
</picture></a>

<sub>**Sobre o selo `PRO · privado`:** cada ferramenta tem uma **edição Pro privada**. O que está público é a vitrine auditável — código, testes e critério à vista de quem quiser conferir. A leitura mais profunda (a que aponta exatamente onde apertar) fica fora do alcance de quem não deveria tê-la. Quem contrata um diagnóstico recebe o resultado da edição Pro.</sub>

| | Projeto | O que faz | Frente | Testes |
| :---: | --- | --- | :---: | :---: |
| `01` | **[Sentinela](https://github.com/Paulo-Marcos-Lucio/sentinela)** | Diagnóstico não-intrusivo de config web: cabeçalhos, TLS, cookies, CORS, DNS/e-mail (SPF/DMARC/MTA-STS), CSP profunda, descoberta de subdomínios via Certificate Transparency (`--descobrir`) e detecção de subdomain takeover; relatórios console/markdown/HTML/JSON e **SARIF 2.1.0** com plano de ação. `Python` | Perímetro | `160+` |
| `02` | **[Guardião](https://github.com/Paulo-Marcos-Lucio/guardiao)** | Scanner de segredos vazados no código **e no histórico Git**: regex + entropia de Shannon, baseline, **SARIF 2.1.0**, hook pre-commit; detecta CPF/CNPJ (LGPD). `Python` | Segredos | `79` |
| `03` | **[Chaveiro](https://github.com/Paulo-Marcos-Lucio/chaveiro)** | Auditor de tokens **JWT/JWS**: `alg:none`, confusão RS→HS, brute de segredo HMAC (inclui segredo vazio), `kid`/`jku` SSRF, validação de claims + referência de validação correta. `Python` | Autenticação | `67` |
| `04` | **[Esteira](https://github.com/Paulo-Marcos-Lucio/esteira)** | Auditor de segurança de **CI/CD (GitHub Actions)**: script injection, actions não-fixadas por SHA, `pull_request_target`, permissões, `secrets: inherit`, imagens não-fixadas; saída **SARIF 2.1.0**. `Python` | Cadeia de suprimentos | `120+` |
| `05` | **[Laboratório OWASP](https://github.com/Paulo-Marcos-Lucio/laboratorio-owasp)** | **8 vulnerabilidades** cobrindo **4 categorias do OWASP Top 10**, cada uma no par **vulnerável → exploit → corrigido** com teste JUnit provando os dois lados: **A01** IDOR, Path Traversal, Open Redirect · **A02** MD5→BCrypt · **A03** SQLi, XSS, Command Injection · **A10** SSRF. `Java 21` · `Spring Boot` | Correção | `36` |

<div align="center">

**[Ver todos os repositórios →](https://github.com/Paulo-Marcos-Lucio?tab=repositories)**

</div>

<br/>

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/divider-scan.svg" alt="Divisor de seção — linha de varredura de dados" width="100%"/>

<br/>

## `~/` Serviços

<a href="https://paulo-marcos-lucio.github.io">
  <picture>
    <source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/services-pipeline-parado.svg">
    <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/services-pipeline.svg" alt="Como trabalho · o que entrego — pipeline em 4 etapas. 1) DIAGNÓSTICO: diagnóstico de vulnerabilidades web, com relatório com severidade, evidência e remediação priorizada. 2) CORREÇÃO &amp; HARDENING: CSP, HSTS, TLS moderno, cookies seguros, CORS restrito. 3) RETESTE: reteste e acompanhamento, com comprovação da redução de risco e varredura recorrente por release. 4) EVIDÊNCIA LGPD: adequação à LGPD (art. 46), com evidência datada e auditável das medidas técnicas." width="100%"/>
  </picture>
</a>

| | Serviço | O que entrego |
| :---: | --- | --- |
| `01` | **Diagnóstico de vulnerabilidades web** | Relatório com severidade, evidência e remediação priorizada. |
| `02` | **Correção & hardening** | CSP, HSTS, TLS moderno, cookies seguros, CORS restrito. |
| `03` | **Reteste & acompanhamento** | Comprovação da redução de risco + varredura recorrente por release. |
| `04` | **Adequação à LGPD (art. 46)** | Evidência datada e auditável das medidas técnicas de segurança. |

<div align="center">

**[Pacotes e valores no site →](https://paulo-marcos-lucio.github.io)**

</div>

<br/>

## `~/` Stack

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/stack-bom.svg" alt="Lista de materiais da stack: segurança de aplicações web, engenharia e automação, e background em fintech regulada — Spring, mTLS ICP-Brasil, FAPI, Pix, Open Finance, OAuth2/OIDC" width="100%"/>

<br/>

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/divider-scan.svg" alt="Divisor de seção — linha de varredura de dados" width="100%"/>

<br/>

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/footer-vigilia.svg" alt="Vigília: diagnóstico sob autorização e escopo definido — prompt aguardando o seu comando" width="100%"/>

<div align="center"><sub>Diagnóstico conduzido sempre sob autorização e escopo definido. Segurança é redução de risco — não promessa de perfeição.</sub></div>
<!-- profile-readme -->
