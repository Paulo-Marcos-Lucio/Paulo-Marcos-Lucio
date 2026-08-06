<p align="right"><a href="README.md">🇧🇷 Ler em Português</a></p>

<!-- ════════════════════════════════════════════════════════════════════════
     Paulo Marcos Lucio · GitHub profile — VIGIL REV. B (English mirror)
     This is the English translation of README.md. By deliberate choice
     (see the "SVGs do perfil" decision in the assistant's session), only
     the REAL markdown text and every image `alt` are translated — the SVG
     artwork itself (hero, tool banners, Sentinela console, telemetry,
     pipeline, stack) stays in Portuguese. Redrawing 20+ animated SVGs in a
     second language is a separate design project; the text a recruiter or
     Google actually reads is 100% English here. The 4 small nav buttons
     (LinkedIn/Email/Website/Repositories) DO have English art — see
     assets/btn-*-en.svg.
     Keep this file a 1:1 structural mirror of README.md — same section
     order, same images, same table rows, only the language changes. For
     the full asset-maintenance rules (camo caching, light-theme contrast,
     numbers rounded down, SARIF coverage, etc.), see README.md's header
     comment — they apply here too.
     ════════════════════════════════════════════════════════════════════════ -->

<a href="https://paulo-marcos-lucio.github.io">
  <picture>
    <source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/hero-abismo-v3-parado.svg">
    <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/hero-abismo-v3.svg" alt="Paulo Marcos Lucio — Web Application Security (AppSec): diagnosing and fixing web vulnerabilities. A watchful eye with radar over a bioluminescent abyss. Panel footer: 5 tools · 800+ automated tests · MIT · green CI." width="100%"/>
  </picture>
</a>

<div align="center">

**I wrote the reference implementations of Pix, Open Finance, and DICT — systems where a security mistake isn't an option. Now I look for what's exposed in _your_ application, before it becomes an incident.**

<br/>

<a href="https://www.linkedin.com/in/paulo-marcos-a07379174/">
  <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/btn-linkedin-v2-en.svg" alt="LinkedIn — get in touch with Paulo Marcos Lucio" width="210"/>
</a>
<a href="mailto:contatopml26@gmail.com">
  <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/btn-email-v2-en.svg" alt="Email — contatopml26@gmail.com" width="210"/>
</a>
<a href="https://paulo-marcos-lucio.github.io">
  <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/btn-site-en.svg" alt="Website — services, packages, and pricing" width="210"/>
</a>
<a href="https://github.com/Paulo-Marcos-Lucio?tab=repositories">
  <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/btn-repos-en.svg" alt="All repositories on GitHub" width="210"/>
</a>

<br/><sub>São Paulo, Brazil — remote-first</sub>

</div>

<br/>

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/divider-scan.svg" alt="Section divider — data-scan line" width="100%"/>

<br/>

<div align="center"><a href="https://github.com/Paulo-Marcos-Lucio/sentinela">
  <picture>
    <source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/console-sentinela-parado.svg">
    <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/console-sentinela.svg" alt="Sentinela (&quot;Sentinel&quot;) console: a real scan of paulo-marcos-lucio.github.io on 2026-07-21, with the command `sentinela scan paulo-marcos-lucio.github.io -f markdown`. 8 checks run, non-intrusive mode, under authorization and defined scope. Results: valid TLS and HSTS active (OK); Content-Security-Policy missing (MEDIUM, OWASP A02); no clickjacking protection (MEDIUM, A02); missing DMARC record (MEDIUM, A07); missing Referrer-Policy (LOW, A02); missing X-Content-Type-Options (LOW, A02); plus 4 informational findings (COOP, Permissions-Policy, DNSSEC, HSTS without includeSubDomains). Summary: 0 critical, 0 high, 3 medium, 2 low, 4 informational — hygiene score 70/100, grade C. Reproducible." width="88%"/>
  </picture>
</a></div>

<div align="center">

**This is my own site — I found the gaps, fixed them, and retested.** The first scan (2026-07-21, above) came back **C · 70/100** and listed exactly what was wrong. I fixed what the platform allows (CSP via `<meta>`) and the retest climbed to **B · 89/100** — published as-is, no touch-ups. **So why not an A?** The remaining gaps (X-Frame-Options, X-Content-Type-Options, HSTS with subdomains) are headers that **GitHub Pages doesn't let any site set** — a hosting limit, not a site flaw, and the tool itself tells me so with the exact line and output (custom domain + CDN). A scanner gives you a number; a diagnosis tells you **why** that's the number. The only reason to hide your own score is being afraid of it.

</div>

<br/>

## `~/` About

I **am the dev team** that wrote security into production. **Java/Spring** developer, author of **reference implementations** for Brazil's regulated financial systems — Pix Automático, Pix por Aproximação (proximity payments), Open Finance (PISP), DICT, Open Insurance — with mTLS on Brazil's ICP-Brasil PKI, FAPI, hexagonal architecture, and test coverage. There are **6 public repositories** right here on the side; open any of them. That's the bar I bring to **your** application: my fix recommendations fit inside your team's sprint — because I've been on the side that would have had to apply them.

Today I work in **web application security (AppSec)**: **diagnosing and fixing vulnerabilities**, hardening, and prevention for internet-facing systems — security headers, TLS/PKI, cookies, CORS, file exposure, DNS/email, and injection surface — all mapped to the **OWASP Top 10** and to **LGPD (Brazil's data-protection law, GDPR-equivalent), art. 46**.

No OSCP, no CEH, no famous client to name-drop. My credential is **auditable**: five open tools, tested with green CI, and my own site's self-scan published with whatever grade it got. And I don't sell a miracle scanner — no single scanner wins across the board, gitleaks is leaner than mine on its own turf and I say so out loud. What you're hiring isn't the scanner: it's the **method** — the triage that separates real findings from noise, the fix, and the dated report.

> **Need to know where your web application is exposed — and how to fix it?**
> **[› Message me on WhatsApp](https://wa.me/5512991478991?text=Hi%20Paulo%2C%20I%20found%20you%20through%20your%20GitHub%20and%20I%27d%20like%20a%20security%20diagnostic%20for%20my%20application.)** — tell me in one line what the application is and the context.
> Still measuring? Run **[Sentinela](https://github.com/Paulo-Marcos-Lucio/sentinela)** ("Sentinel") against your domain; if the grade comes back below B, send me the `relatorio.json` and the conversation starts from your finding, not my pitch.

<br/>

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/ops-telemetry-v2.svg" alt="Operation telemetry: 5 open tools, 800+ automated tests, MIT license with green CI across all five suite tools, mapped to OWASP Top 10 and LGPD art. 46" width="100%"/>

<br/>

## `~/` AppSec Suite

A portfolio of **application security tools** — each one covers a front of the OWASP Top 10, from perimeter to authentication, from leaked secrets to the supply chain. All with **tests, CI, and product-grade documentation**: the tool itself **is** the proof of technical judgment. The numbers in this section aren't a brochure — **run them yourself, in two commands per repository.**

<a href="https://github.com/Paulo-Marcos-Lucio/sentinela"><picture>
<source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-sentinela-abismo-v2-parado.svg">
<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-sentinela-abismo-v2.svg" alt="Sentinela (&quot;Sentinel&quot;) — non-intrusive external diagnostic: what the attacker sees. Chips: TLS, Headers, DNS/CT. &quot;PRO · private&quot; badge: the non-intrusive scan stays open; the Pro edition adds the active engine that confirms the flaw. &quot;The eye that watches your surface — in the dark.&quot;" width="100%"/>
</picture></a>

<a href="https://github.com/Paulo-Marcos-Lucio/guardiao"><picture>
<source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-guardiao-abismo-v2-parado.svg">
<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-guardiao-abismo-v2.svg" alt="Guardião (&quot;Guardian&quot;) — secrets scanner for your code and Git history. Chips: regex+entropy, baseline, pre-commit. &quot;PRO · private&quot; badge: the detection engine is the same one that stays open; the Pro edition is the service — triage, rotation, and dated report. &quot;The shield that guards the border.&quot;" width="100%"/>
</picture></a>

<a href="https://github.com/Paulo-Marcos-Lucio/chaveiro"><picture>
<source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-chaveiro-abismo-v2-parado.svg">
<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-chaveiro-abismo-v2.svg" alt="Chaveiro (&quot;Locksmith&quot;) — JWT/JWS token auditor. Chips: alg:none, alg-confusion, HMAC crack. Illustration of the token in three parts: eyJ… .payload. sig. &quot;PRO · private&quot; badge: the detector is the same one that stays open; the Pro edition is the service — authorized PoC and verified fix." width="100%"/>
</picture></a>

<a href="https://github.com/Paulo-Marcos-Lucio/esteira"><picture>
<source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-esteira-abismo-v2-parado.svg">
<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-esteira-abismo-v2.svg" alt="Esteira (&quot;Conveyor Belt&quot;) — pipeline security · GitHub Actions. Chips: script-injection, SHA-pinning, pr-target. &quot;PRO · private&quot; badge: the engine is the same one that stays open; the Pro edition is the service — the fix applied via Pull Request. &quot;The modern attack flows in through the belt. It watches the flow.&quot;" width="100%"/>
</picture></a>

<a href="https://github.com/Paulo-Marcos-Lucio/laboratorio-owasp"><picture>
<source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-laboratorio-abismo-v2-parado.svg">
<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/banner-laboratorio-abismo-v2.svg" alt="Laboratório OWASP (&quot;OWASP Lab&quot;) — vulnerability lab. Chips: OWASP Top 10 (in practice, 8 vulnerabilities across 3 categories: A01, A04, and A05), Java, hands-on. &quot;PRO · private&quot; badge: the lab is open in full — the flaw is there on purpose, for you to learn; the Pro layer is guided mentorship, not a hidden engine. &quot;Where the flaw is on purpose — so you learn to defend.&quot;" width="100%"/>
</picture></a>

**The `PRO · private` line, no fine print.** The engine that's open is the exact same one I run in the paid service — byte for byte. **Nothing leaves the public side: what's free today stays free, forever.** The Pro edition never takes away — it only _adds_, and always says why:

- In **Sentinela**, it adds **code**: the active engine that _confirms_ the flaw instead of just flagging it. It sends requests against the target — which is why it only runs with written authorization, not as a binary anyone can download.
- In the other tools, the engine is **identical** to the one you download; what Pro adds is the **service** — the triage that says which findings are real, the fix applied, the dated report — plus the rule set I maintain week over week.
- The **Lab** is the exception: it's a classroom, open in full; there, the Pro layer is guided mentorship, not an engine.

Detection is free. **Fixing is work — and work is what I sell.**

| | Project | What it does | Front | Tests |
| :---: | --- | --- | :---: | :---: |
| `01` | **[Sentinela](https://github.com/Paulo-Marcos-Lucio/sentinela)** ("Sentinel") | Non-intrusive web config diagnostic: headers, TLS, cookies, CORS, DNS/email (SPF/DMARC/MTA-STS), deep CSP, subdomain discovery via Certificate Transparency and subdomain takeover, **plus injection surface** (forms, CSRF, parameter reflection/XSS); console/markdown/HTML/JSON reports and **SARIF 2.1.0** with an action plan. The **Pro** edition actively confirms injection. `Python` | Perimeter | `424` |
| `02` | **[Guardião](https://github.com/Paulo-Marcos-Lucio/guardiao)** ("Guardian") | Leaked-secrets scanner for your code **and Git history**: provider regex + **normalized entropy (Miller-Madow)**, baseline, **SARIF 2.1.0**, pre-commit hook; validates CPF/CNPJ check digits (Brazilian tax IDs, LGPD-relevant). Recall **13/14** on the bench corpus, **0 false positives**. `Python` | Secrets | `186` |
| `03` | **[Chaveiro](https://github.com/Paulo-Marcos-Lucio/chaveiro)** ("Locksmith") | **JWT/JWS** token auditor: `alg:none`, RS→HS confusion, HMAC secret brute-forcing, `kid`/`jku` SSRF, nested JWT, CPF in claims, claim validation + a correct-validation reference. **22/22** vectors on the corpus, **0 false positives** across 6 legitimate tokens, ~38k tokens/sec. `Python` | Authentication | `191` |
| `04` | **[Esteira](https://github.com/Paulo-Marcos-Lucio/esteira)** ("Conveyor Belt") | Security auditor for **CI/CD (GitHub Actions)**: script injection, actions not pinned by SHA, `pull_request_target`, permissions, `secrets: inherit`, unpinned images; **SARIF 2.1.0** output. **17/17** rules and **20/20** recall on the corpus, **0 false positives**. `Python` | Supply chain | `249` |
| `05` | **[Laboratório OWASP](https://github.com/Paulo-Marcos-Lucio/laboratorio-owasp)** ("OWASP Lab") | **8 vulnerabilities across 3 categories of the OWASP Top 10:2025** (A01, A04, and A05), spotlighting **A05 Injection** (SQLi with a parameterized fix, XSS, command injection) — each one paired **vulnerable → exploit → fixed**, with a JUnit test proving both sides. `Java 21` · `Spring Boot` | Remediation | `49` |

<div align="center">

**[See all repositories →](https://github.com/Paulo-Marcos-Lucio?tab=repositories)**

</div>

<sub>**And where do I lose?** I published the [honest benchmark against gitleaks, trufflehog, and zizmor](https://github.com/Paulo-Marcos-Lucio/guardiao/blob/main/BENCHMARK.md) — pinned versions and commits, reproducible, and it says where the incumbent is leaner than mine. No single scanner wins across the board; what I sell is low-false-positive calibration and the work built on top of the result.</sub>

<br/>

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/divider-scan.svg" alt="Section divider — data-scan line" width="100%"/>

<br/>

## `~/` Services

<a href="https://paulo-marcos-lucio.github.io">
  <picture>
    <source media="(prefers-reduced-motion: reduce)" srcset="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/services-pipeline-parado.svg">
    <img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/services-pipeline.svg" alt="How I work · what I deliver — a 4-step pipeline. 1) DIAGNOSIS: web vulnerability diagnosis, with a report covering severity, evidence, and prioritized remediation. 2) FIX &amp; HARDENING: CSP, HSTS, modern TLS, secure cookies, restrictive CORS. 3) RETEST: retest and follow-up, proving the risk reduction plus recurring scans per release. 4) LGPD EVIDENCE: LGPD compliance (art. 46), with dated, auditable evidence of technical measures." width="100%"/>
  </picture>
</a>

| | Service | What I deliver |
| :---: | --- | --- |
| `01` | **Web vulnerability diagnosis** | Report with severity, evidence, and prioritized remediation. |
| `02` | **Fix & hardening** | CSP, HSTS, modern TLS, secure cookies, restrictive CORS. |
| `03` | **Retest & follow-up** | Proof of risk reduction + recurring scans per release. |
| `04` | **LGPD compliance (art. 46)** | Dated, auditable evidence of technical security measures. |

<div align="center">

**[Packages and pricing on my site →](https://paulo-marcos-lucio.github.io)**

</div>

<br/>

## `~/` Stack

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/stack-bom.svg" alt="Stack bill of materials: web application security, engineering and automation, and background in regulated fintech — Spring, mTLS on ICP-Brasil, FAPI, Pix, Open Finance, OAuth2/OIDC" width="100%"/>

<br/>

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/divider-scan.svg" alt="Section divider — data-scan line" width="100%"/>

<br/>

<img src="https://raw.githubusercontent.com/Paulo-Marcos-Lucio/Paulo-Marcos-Lucio/main/assets/footer-vigilia.svg" alt="Vigil: diagnosis under authorization and defined scope — a prompt awaiting your command" width="100%"/>

<div align="center"><sub>Diagnosis always under authorization and defined scope. Security is measurable risk reduction — proven with a dated retest.</sub></div>
<!-- profile-readme -->
