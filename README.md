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
       · Números SÓ de fatos reais, arredondados PARA BAIXO (819 → 800+).
       · SARIF 2.1.0 existe no Sentinela, no Guardião e na Esteira.
         O Chaveiro NÃO tem SARIF. (Conferido no código público em 29/07/2026;
         o comentário anterior, que dizia que o Sentinela não tinha, era falso.)
       · "OWASP Top 10" no Laboratório SEMPRE com o qualificador: são
         8 vulnerabilidades cobrindo 3 categorias do OWASP Top 10:2025 — A01, A04 e A05.
       · SMIL não respeita prefers-reduced-motion. Toda peça pesada precisa
         de um par -parado.svg servido via <picture media="...">.
       · Nenhuma certificação é mencionada — não inventar OSCP/CEH/clientes.
       · Ética no footer em SVG E em <sub> de texto real, sempre.
     ════════════════════════════════════════════════════════════════════════ -->

<a href="https://paulo-marcos-lucio.github.io">
  <picture>
    <source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/hero-abismo-v3-parado.svg">
    <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/hero-abismo-v3.svg" alt="Paulo Marcos Lucio — Segurança de Aplicações Web (AppSec): diagnóstico e correção de vulnerabilidades web. Olho de vigília com radar no abismo bioluminescente. Rodapé do painel: 5 ferramentas · 800+ testes automatizados · MIT · CI verde." width="100%"/>
  </picture>
</a>

<div align="center">

**Eu escrevi as implementações de referência do Pix, do Open Finance e do DICT — sistemas onde errar em segurança não é opção. Agora eu procuro o que está exposto na _sua_ aplicação, antes que vire incidente.**

<br/>

<a href="https://www.linkedin.com/in/paulo-marcos-a07379174/">
  <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/btn-linkedin-v2.svg" alt="LinkedIn — falar com Paulo Marcos Lucio" width="210"/>
</a>
<a href="mailto:contatopml26@gmail.com">
  <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/btn-email-v2.svg" alt="E-mail — contatopml26@gmail.com" width="210"/>
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

<div align="center">

**Este é o meu próprio site — achei, corrigi, retestei.** O primeiro scan (21/07/2026, acima) deu **C · 70/100** e listou o quê. Corrigi o que a plataforma permite (CSP via `<meta>`) e o reteste subiu para **B · 89/100** — publicado assim, sem maquiar. E **por que não é A?** Os pontos que faltam (X-Frame-Options, X-Content-Type-Options, HSTS com subdomínios) são cabeçalhos que o **GitHub Pages não deixa nenhum site definir** — limite da hospedagem, não do site, e a própria ferramenta me diz isso com a linha exata e a saída (domínio próprio + CDN). Um scanner te dá um número; um diagnóstico te diz **por que** o número é esse. Quem esconde a própria nota é quem tem medo dela.

</div>

<br/>

## `~/` Sobre

Eu **sou o time de dev** que escreveu segurança em produção. Desenvolvedor **Java/Spring**, autor de **implementações de referência** dos sistemas financeiros regulados brasileiros — Pix Automático, Pix por Aproximação, Open Finance (PISP), DICT, Open Insurance —, com mTLS ICP-Brasil, FAPI, arquitetura hexagonal e teste. São **6 repositórios públicos** aqui do lado; abra qualquer um. Essa é a régua que eu trago para a **sua** aplicação: minhas recomendações de correção cabem no sprint do time — porque eu já estive do lado que teria que aplicá-las.

Hoje atuo com **segurança de aplicações web (AppSec)**: **diagnóstico e correção de vulnerabilidades**, hardening e prevenção em sistemas expostos na internet — cabeçalhos de segurança, TLS/PKI, cookies, CORS, exposição de arquivos, DNS/e-mail e superfície de injeção — tudo mapeado ao **OWASP Top 10** e à **LGPD (art. 46)**.

Sem OSCP, sem CEH, sem cliente famoso para citar. A minha credencial é **auditável**: cinco ferramentas abertas, com teste e CI verde, e o auto-scan do meu próprio site publicado com a nota que deu. E eu não vendo ferramenta-milagre — nenhum scanner sozinho vence, o gitleaks é mais enxuto que o meu e eu digo isso em voz alta. O que você contrata não é o scanner: é o **método**, a triagem que separa o real do ruído, a correção e o laudo datado.

> **Precisa saber onde a sua aplicação web está exposta — e como corrigir?**
> **[› Falar agora no WhatsApp](https://wa.me/5512991478991?text=Ol%C3%A1%20Paulo%2C%20vim%20pelo%20seu%20GitHub%20e%20quero%20um%20diagn%C3%B3stico%20de%20seguran%C3%A7a%20da%20minha%20aplica%C3%A7%C3%A3o.)** — me diga em uma linha qual é a aplicação e o contexto.
> Ainda medindo? Rode o **[Sentinela](https://github.com/Paulo-Marcos-Lucio/sentinela)** no seu domínio; se a nota vier abaixo de B, me manda o `relatorio.json` e a conversa já começa no seu achado, não no meu discurso.

<br/>

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/ops-telemetry-v2.svg" alt="Telemetria da operação: 5 ferramentas abertas, 800+ testes automatizados, licença MIT com CI verde nas cinco ferramentas da suíte, mapeamento OWASP Top 10 e LGPD art. 46" width="100%"/>

<br/>

## `~/` Suíte AppSec

Um portfólio de **ferramentas de segurança de aplicações** — cada uma cobre uma frente do OWASP Top 10, do perímetro à autenticação, dos segredos vazados à cadeia de suprimentos. Todas com **testes, CI e documentação de nível de produto**: a ferramenta **é** a prova do critério técnico. Os números desta seção não são folheto — **rode você mesmo, em dois comandos por repositório.**

<a href="https://github.com/Paulo-Marcos-Lucio/sentinela"><picture>
<source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-sentinela-abismo-v2-parado.svg">
<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-sentinela-abismo-v2.svg" alt="Sentinela — diagnóstico externo não-intrusivo: o que o atacante vê. Chips: TLS, Cabeçalhos, DNS/CT. Selo &quot;PRO · privado&quot;: a varredura não-intrusiva fica aberta; a edição Pro acrescenta o motor ativo que confirma a falha. &quot;O olho que vela a sua superfície — no escuro.&quot;" width="100%"/>
</picture></a>

<a href="https://github.com/Paulo-Marcos-Lucio/guardiao"><picture>
<source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-guardiao-abismo-v2-parado.svg">
<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-guardiao-abismo-v2.svg" alt="Guardião — scanner de segredos no código e no histórico Git. Chips: regex+entropia, baseline, pre-commit. Selo &quot;PRO · privado&quot;: o motor de detecção é o mesmo que fica aberto; a edição Pro é o serviço — triagem, rotação e laudo datado. &quot;O escudo que guarda a fronteira.&quot;" width="100%"/>
</picture></a>

<a href="https://github.com/Paulo-Marcos-Lucio/chaveiro"><picture>
<source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-chaveiro-abismo-v2-parado.svg">
<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-chaveiro-abismo-v2.svg" alt="Chaveiro — auditor de tokens JWT/JWS. Chips: alg:none, alg-confusion, HMAC crack. Ilustração do token em três partes: eyJ… .payload. sig. Selo &quot;PRO · privado&quot;: o detector é o mesmo que fica aberto; a edição Pro é o serviço — PoC autorizado e correção verificada." width="100%"/>
</picture></a>

<a href="https://github.com/Paulo-Marcos-Lucio/esteira"><picture>
<source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-esteira-abismo-v2-parado.svg">
<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-esteira-abismo-v2.svg" alt="Esteira — segurança de pipelines · GitHub Actions. Chips: script-injection, SHA-pinning, pr-target. Selo &quot;PRO · privado&quot;: o motor é o mesmo que fica aberto; a edição Pro é o serviço — a correção aplicada via Pull Request. &quot;O ataque moderno entra pela correnteza. Ela vigia o fluxo.&quot;" width="100%"/>
</picture></a>

<a href="https://github.com/Paulo-Marcos-Lucio/laboratorio-owasp"><picture>
<source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-laboratorio-abismo-v2-parado.svg">
<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-laboratorio-abismo-v2.svg" alt="Laboratório OWASP — laboratório de vulnerabilidades. Chips: OWASP Top 10 (na prática, 8 vulnerabilidades em 3 categorias: A01, A04 e A05), Java, hands-on. Selo &quot;PRO · privado&quot;: o laboratório é aberto por inteiro — a falha é de propósito, para você aprender; a camada Pro é a mentoria conduzida, não um motor escondido. &quot;Onde a falha é de propósito — pra você aprender a defender.&quot;" width="100%"/>
</picture></a>

**A fronteira `PRO · privado`, sem letra miúda.** O motor que está aberto é o mesmo que eu rodo no serviço — byte a byte. **Nada sai do público: o que é gratuito hoje continua gratuito, para sempre.** A edição Pro nunca tira — ela só *acrescenta*, e sempre diz por quê:

- No **Sentinela**, acrescenta **código**: o motor ativo que *confirma* a falha em vez de só apontá-la. Ele emite requisição contra o alvo — por isso só roda com autorização por escrito, não num binário que qualquer um baixa.
- Nas outras ferramentas, o motor é **idêntico** ao que você baixa; o que a Pro acrescenta é o **serviço** — a triagem que diz quais achados são reais, a correção aplicada, o laudo datado — mais o acervo de regras que eu mantenho semana a semana.
- O **Laboratório** é a exceção: é sala de aula, aberto por inteiro; ali a camada Pro é a mentoria conduzida, não um motor.

Detectar é de graça. **Corrigir é trabalho — e trabalho é o que eu vendo.**

| | Projeto | O que faz | Frente | Testes |
| :---: | --- | --- | :---: | :---: |
| `01` | **[Sentinela](https://github.com/Paulo-Marcos-Lucio/sentinela)** | Diagnóstico não-intrusivo de config web: cabeçalhos, TLS, cookies, CORS, DNS/e-mail (SPF/DMARC/MTA-STS), CSP profunda, descoberta de subdomínios via Certificate Transparency e subdomain takeover, **e superfície de injeção** (formulários, CSRF, reflexão de parâmetro/XSS); relatórios console/markdown/HTML/JSON e **SARIF 2.1.0** com plano de ação. A edição **Pro** confirma injeção ativamente. `Python` | Perímetro | `424` |
| `02` | **[Guardião](https://github.com/Paulo-Marcos-Lucio/guardiao)** | Scanner de segredos vazados no código **e no histórico Git**: regex de provedor + **entropia normalizada (Miller-Madow)**, baseline, **SARIF 2.1.0**, hook pre-commit; valida CPF/CNPJ por dígito (LGPD). Recall **13/14** no corpus bench, **0 falso-positivo**. `Python` | Segredos | `186` |
| `03` | **[Chaveiro](https://github.com/Paulo-Marcos-Lucio/chaveiro)** | Auditor de tokens **JWT/JWS**: `alg:none`, confusão RS→HS, brute de segredo HMAC, `kid`/`jku` SSRF, JWT aninhado, CPF em claim, validação de claims + referência de validação correta. **22/22** vetores no corpus, **0 falso-positivo** em 6 tokens legítimos, ~38 mil tokens/s. `Python` | Autenticação | `191` |
| `04` | **[Esteira](https://github.com/Paulo-Marcos-Lucio/esteira)** | Auditor de segurança de **CI/CD (GitHub Actions)**: script injection, actions não-fixadas por SHA, `pull_request_target`, permissões, `secrets: inherit`, imagens não-fixadas; saída **SARIF 2.1.0**. **17/17** regras e **20/20** recall no corpus, **0 falso-positivo**. `Python` | Cadeia de suprimentos | `249` |
| `05` | **[Laboratório OWASP](https://github.com/Paulo-Marcos-Lucio/laboratorio-owasp)** | **8 vulnerabilidades em 3 categorias do OWASP Top 10:2025** (A01, A04 e A05), com destaque para **A05 Injeção** (SQLi com correção parametrizada, XSS, Command Injection) — cada uma no par **vulnerável → exploit → corrigido** com teste JUnit provando os dois lados. `Java 21` · `Spring Boot` | Correção | `49` |

<div align="center">

**[Ver todos os repositórios →](https://github.com/Paulo-Marcos-Lucio?tab=repositories)**

</div>

<sub>**E onde eu perco?** Publiquei o [benchmark honesto contra gitleaks, trufflehog e zizmor](https://github.com/Paulo-Marcos-Lucio/guardiao/blob/main/BENCHMARK.md) — versões e commits fixados, reproduzível, e diz onde o incumbente é mais enxuto que eu. Nenhum scanner sozinho vence; o que eu vendo é a calibração de baixo falso-positivo e o trabalho em cima do resultado.</sub>

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

<div align="center"><sub>Diagnóstico sempre sob autorização e escopo definido. Segurança é redução de risco medível — comprovada com reteste datado.</sub></div>
<!-- profile-readme -->
