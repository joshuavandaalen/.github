<!-- markdownlint-disable MD013 MD033 MD041 -->
<div class="wrap">
<header>
<p class="prompt mono">joshua@homelab<span class="p">:~$</span> cat joshua-van-daalen.md</p>
<h1 class="mono">Joshua Van Daalen<span class="caret" aria-hidden="true">_</span></h1>
<p class="lede">Applied-AI and platform engineer in Melbourne. Ships agentic systems end to end — discovery through production — and applies identity, access and platform discipline to the AI that gets built. Ten years turning manual work into repeatable automation across superannuation, energy and finance.</p>
<dl class="meta mono">
<div><dt>location</dt><dd>Melbourne, VIC · AU citizen</dd></div>
<div><dt>focus</dt><dd>agentic systems · MCP · IAM for AI</dd></div>
<div><dt>github</dt><dd><a href="https://github.com/joshuavandaalen">joshuavandaalen</a></dd></div>
<div><dt>linkedin</dt><dd><a href="https://linkedin.com/in/joshua-van-daalen">joshua-van-daalen</a></dd></div>
</dl>
</header>
<div class="tldr">
<p class="cap mono">tl;dr <span>for anyone skimming</span></p>
<dl>
<div><dt class="mono">now</dt><dd>Solutions Engineer at Agentics Foundation — builds multi-agent workflows, evaluation harnesses, and secure context injection for agentic systems.</dd></div>
<div><dt class="mono">strength</dt><dd>Azure, Kubernetes, IaC and PowerShell automation, carried into applied AI: MCP servers, RAG, local model hosting, agentic orchestration.</dd></div>
<div><dt class="mono">the pattern</dt><dd>Find the manual job, remove it. Build the tool nobody asked for to learn the system. Offer it, don't mandate it.</dd></div>
<div><dt class="mono">AI arc</dt><dd>First hands-on build 2016 (IBM Watson). ML study from 2018. Agentic focus from 2025. Long exposure, recent full investment.</dd></div>
</dl>
</div>
<div class="tabs" role="group" aria-label="Filter by status">
<button class="tab" data-filter="all" aria-pressed="true">All · 12</button>
<button class="tab" data-filter="decided" aria-pressed="false"><span class="dot decided"></span>Focus · 1</button>
<button class="tab" data-filter="open" aria-pressed="false"><span class="dot open"></span>Open · 1</button>
<button class="tab" data-filter="reference" aria-pressed="false"><span class="dot reference"></span>Record · 10</button>
</div>
<div class="grid">
<aside>
<nav aria-label="Entries" id="nav"></nav>
</aside>
<main id="entries" tabindex="-1">
<!-- AI-01 -->
<details class="entry" id="AI-01" data-status="decided" open>
<summary>
<span class="sum-body">
<span class="sum-head"><span class="eid mono">AI-01</span> · <span class="etitle mono">What I build now — agentic systems</span></span>
<span class="esum">The current focus: multi-agent workflows that produce decision records and escalate to a human when a finding invalidates the plan.</span>
</span>
<span class="pill decided mono"><span class="dot decided"></span>Focus</span>
</summary>
<div class="panel">
<p class="ctx">Agentic engineering with the discipline that came before it. Structured multi-phase runs (brief, discourse, execution, review) that end with a defensible recommendation, not an unreviewed dump — and stop mid-run rather than proceed on a stale assumption.</p>
<div class="opt">
<div class="opt-head"><span class="opt-label">Structured multi-phase workflows + human escalation</span> — <span class="v chosen">Chosen</span></div>
<p class="opt-detail">Each stage writes a decision record; a finding that invalidates the plan escalates instead of being silently absorbed. This has caught design faults mid-run and re-routed before build.</p>
</div>
<div class="opt">
<div class="opt-head"><span class="opt-label">MCP servers + secure context injection</span> — <span class="v chosen">Chosen</span></div>
<p class="opt-detail">Built a Model Context Protocol server for secure prompt and context management — bringing model capability inside secured environments with token budgeting and context-window limits respected.</p>
</div>
<div class="opt">
<div class="opt-head"><span class="opt-label">Multi-provider gateways &amp; local open-weight serving</span> — <span class="v conditional">Experimenting</span></div>
<p class="opt-detail">Evaluating self-hosted routing across providers with per-request cost and token tracking, and local serving via vLLM and llama.cpp. Capability under study, not a production claim.</p>
</div>
<div class="opt">
<div class="opt-head"><span class="opt-label">Autopilot agents with no review gate</span> — <span class="v ruled-out">Ruled out</span></div>
<p class="opt-detail">An agent run that ends in an unreviewed output is a liability, not a feature. The review phase and explicit success criteria are the point.</p>
</div>
<div class="tags">
<span class="tag mono">multi-agent orchestration</span> · <span class="tag mono">tool / function calling</span> · <span class="tag mono">evaluation harnesses</span> · <span class="tag mono">RAG</span> · <span class="tag mono">token budgeting</span> · <span class="tag mono">IAM for AI</span>
</div>
</div>
</details>
<!-- ROLE-01 -->
<details class="entry" id="ROLE-01" data-status="reference" open>
<summary>
<span class="sum-body">
<span class="sum-head"><span class="eid mono">ROLE-01</span> · <span class="etitle mono">Solutions Engineer — Agentics Foundation</span></span>
<span class="esum">Jan 2026 – present · remote. Turns emerging agent patterns into things other engineers and non-technical stakeholders can actually use.</span>
</span>
<span class="pill reference mono"><span class="dot reference"></span>Record</span>
</summary>
<div class="panel">
<div class="fg">
<ul>
<li>Builds <b>agentic systems and multi-agent workflows</b> — orchestration, tool and function calling, evaluation harnesses.</li>
<li>Applies <b>identity, access and platform discipline to AI</b> — secure context injection, non-human identity, guardrails.</li>
<li>Designs <b>brief/discourse/execution/review</b> workflows with written decision records and human escalation on plan-invalidating findings.</li>
<li>Runs work against explicit success criteria and a closing assessment phase.</li>
</ul>
</div>
</div>
</details>
<!-- ROLE-02 -->
<details class="entry" id="ROLE-02" data-status="reference" open>
<summary>
<span class="sum-body">
<span class="sum-head"><span class="eid mono">ROLE-02</span> · <span class="etitle mono">Applied AI Engineering — self-directed</span></span>
<span class="esum">Aug 2025 – Nov 2025. The same deep-investment pattern run before against IaC and identity, this time against generative and agentic AI.</span>
</span>
<span class="pill reference mono"><span class="dot reference"></span>Record</span>
</summary>
<div class="panel">
<div class="fg">
<ul>
<li>Built AI-assisted engineering workflows end to end: <b>LLM-driven runbooks, automated IAM audits, policy-as-code generation, identity-lifecycle review</b>.</li>
<li>Stood up <b>local model hosting and secure context injection</b>; worked through token budgeting and context-window limits against sensitive systems.</li>
<li>Ran large open-weight models locally (incl. Qwen 3 Coder-480B) for code generation and syntax learning.</li>
<li>Built <b>50+ professional GitHub Copilot modes</b> via curated prompts; analysed VS Code telemetry to iterate on instruction design.</li>
</ul>
</div>
</div>
</details>
<!-- ROLE-03 -->
<details class="entry" id="ROLE-03" data-status="reference" open>
<summary>
<span class="sum-body">
<span class="sum-head"><span class="eid mono">ROLE-03</span> · <span class="etitle mono">Identity &amp; Access Management Lead — UniSuper</span></span>
<span class="esum">Aug 2024 – Jul 2025. Senior IAM lead and principal automation engineer for a superannuation fund.</span>
</span>
<span class="pill reference mono"><span class="dot reference"></span>Record</span>
</summary>
<div class="panel">
<div class="fg">
<ul>
<li><b>SailPoint IdentityNow:</b> automated 1,900 non-production database access profiles in two days (90 in ~8 min, 1,829 in 3h 39m). Within 100 days, grew total access-profile count by 3,138 — ~75% coverage growth — with full audit evidence.</li>
<li>Generated <b>680 server roles + 680 matching access profiles</b>, every mapping validated, tracked in ServiceNow.</li>
<li><b>CyberArk:</b> automated safe provisioning and permissions; analysis uncovered hundreds of misaligned permissions and config errors.</li>
<li>Extensive PowerShell modules across IdentityNow, CyberArk, Okta and ServiceNow; dormant-account audit notifying ~30 line managers in under a minute.</li>
<li>RBAC design for Azure digital apps; team bundles for a clean vendor / smart-sourcing handover at least privilege.</li>
</ul>
</div>
<div class="tags">
<span class="tag mono">SailPoint IdentityNow</span> · <span class="tag mono">CyberArk</span> · <span class="tag mono">Okta</span> · <span class="tag mono">Entra ID</span> · <span class="tag mono">RBAC</span> · <span class="tag mono">PowerShell</span>
</div>
</div>
</details>
<!-- ROLE-04 -->
<details class="entry" id="ROLE-04" data-status="reference" open>
<summary>
<span class="sum-body">
<span class="sum-head"><span class="eid mono">ROLE-04</span> · <span class="etitle mono">Full-Stack Developer — UniSuper</span></span>
<span class="esum">Nov 2022 – Aug 2024. Integration platform (IPaaS) and the Sitecore-based web estate.</span>
</span>
<span class="pill reference mono"><span class="dot reference"></span>Record</span>
</summary>
<div class="panel">
<div class="fg">
<ul>
<li><b>.NET Core microservices on AKS</b> with protobuf/gRPC contracts to private namespaces, behind Azure API Management.</li>
<li>Contributed to a <b>Backend-for-Frontend</b> shared across web and the new mobile apps — one aggregation contract over many backend domains, including legacy datacentre data.</li>
<li>Led migration of end-of-life Sitecore XP 9.x APIs into modern microservices; Angular + Redux front ends with Azure Redis cache.</li>
<li>Non-production scheduling — scaling Sitecore dev environments down outside hours — cut cloud spend by <b>~AU$15,000 per month</b>. Built an internal monitoring portal for daily health checks.</li>
</ul>
</div>
</div>
</details>
<!-- ROLE-05 -->
<details class="entry" id="ROLE-05" data-status="reference" open>
<summary>
<span class="sum-body">
<span class="sum-head"><span class="eid mono">ROLE-05</span> · <span class="etitle mono">DevOps Engineer — UniSuper</span></span>
<span class="esum">May 2021 – Nov 2022. Brought in as the Azure specialist to fill an Azure gap on a VMware-heavy team and upskill the DevOps engineers.</span>
</span>
<span class="pill reference mono"><span class="dot reference"></span>Record</span>
</summary>
<div class="panel">
<div class="fg">
<ul>
<li>Self-initiated <b>design-review script</b>: audited live Azure config against the Sitecore design doc across dev/test and production; surfaced ~100 DNS records to change and the absence of a followed naming standard.</li>
<li>Reverse-engineered <b>Juniper firewall</b> web-portal APIs in PowerShell to export north-south/east-west rules, exposing hundreds of missed vendor rules before cutover.</li>
<li>Corrected an <b>Imperva WAF</b> health-check misconfiguration, restoring reliability on the org's first private-endpoint web app.</li>
<li>Azure plan changes and resource moves with the Sitecore team, per the reference letter, <b>saved ~AU$200,000 per year</b>.</li>
<li>Taught the IaC training programme unprompted: <b>20+ Platform Engineers</b> core, ~40 in the largest session (Operations attended), ~300 views of the recording, CTO and CPO praise. Converted his own material from Bicep/ARM to Terraform over a couple of nights.</li>
<li>DR runbook refactor cut assigned tasks from over an hour to under 15 minutes in the next test cycle.</li>
</ul>
</div>
</div>
</details>
<!-- ROLE-06 -->
<details class="entry" id="ROLE-06" data-status="reference" open>
<summary>
<span class="sum-body">
<span class="sum-head"><span class="eid mono">ROLE-06</span> · <span class="etitle mono">DevOps Consultant — Tally Group</span></span>
<span class="esum">Feb 2020 – May 2021. Multi-tenant energy-billing SaaS, built through a 10–15 to 100+ person scale-up.</span>
</span>
<span class="pill reference mono"><span class="dot reference"></span>Record</span>
</summary>
<div class="panel">
<div class="fg">
<ul>
<li>Wrote tenant-creation automation in PowerShell — cut provisioning from <b>2–4 hours to 15–30 minutes</b>; the new sandbox tenants opened a fresh income stream.</li>
<li>Azure AD B2C authentication; <b>resolved a cross-tenant access vulnerability</b> by fixing a query-string traversal bug.</li>
<li>Ran a Postman/Graph API demo for business analysts — introduced a non-technical audience to API-driven work, then shaped responses with OData.</li>
</ul>
</div>
</div>
</details>
<!-- ROLE-07 -->
<details class="entry" id="ROLE-07" data-status="reference" open>
<summary>
<span class="sum-body">
<span class="sum-head"><span class="eid mono">ROLE-07</span> · <span class="etitle mono">System Administrator — The Thomas Group</span></span>
<span class="esum">Feb 2019 – Mar 2020. Shopify, Salesforce, Sage X3 ERP, POS and Microsoft 365, plus Azure integration work.</span>
</span>
<span class="pill reference mono"><span class="dot reference"></span>Record</span>
</summary>
<div class="panel">
<div class="fg">
<ul>
<li>Used the Cloud Adoption Framework to design Azure infrastructure for API integrations; architected CI/CD pipelines.</li>
<li>Extracted and transformed data with SQL for third-party integrations; prepared cost-management proposals for the CFO and board.</li>
</ul>
</div>
</div>
</details>
<!-- ROLE-08 -->
<details class="entry" id="ROLE-08" data-status="reference" open>
<summary>
<span class="sum-body">
<span class="sum-head"><span class="eid mono">ROLE-08</span> · <span class="etitle mono">Support Consultant / SysAdmin — Posmosis</span></span>
<span class="esum">Mar 2015 – Mar 2019. Broad IT services — and where the first AI build and the automation habit both started.</span>
</span>
<span class="pill reference mono"><span class="dot reference"></span>Record</span>
</summary>
<div class="panel">
<div class="fg">
<ul>
<li>Remote support across 300+ machines via ScreenConnect; AD, Group Policy, DNS/DHCP from SBS 2000 through Server 2016; Exchange-to-O365 migrations.</li>
<li>Self-taught Office deployment automation with PowerShell and Chocolatey — the earliest instance of the pattern: find the manual job, remove it.</li>
<li><b>Stopped active ransomware</b> mid-encryption on a file server, restoring from a Veeam backup.</li>
<li><b>First hands-on AI (c. 2016–2017):</b> built an IBM Watson app identifying a car's make/model from a photo of its wheel, so a winch could be matched to the stud pattern.</li>
</ul>
</div>
</div>
</details>
<!-- SEC-01 -->
<details class="entry" id="SEC-01" data-status="open" open>
<summary>
<span class="sum-body">
<span class="sum-head"><span class="eid mono">SEC-01</span> · <span class="etitle mono">Independent security research</span></span>
<span class="esum">Ongoing, self-directed. Public information only, strict privacy-law adherence, responsible disclosure. To raise the bar, never to exploit.</span>
</span>
<span class="pill open mono"><span class="dot open"></span>Open</span>
</summary>
<div class="panel">
<p class="ctx">Defensive, disclosure-first. The value is often the disproof, not the build.</p>
<div class="fg">
<ul>
<li><b>Break-glass identity:</b> the gap most orgs fail on — MFA, credential rotation and storage on Global Admin break-glass accounts, and conditional-access exemptions signed off during audits.</li>
<li><b>Azure Communication Services OTP relay:</b> proved an automated relay is technically achievable, then concluded it's the wrong control — it puts the second factor inside the same plane the account exists to recover. Current guidance is phishing-resistant MFA. The disproof was the finding.</li>
<li>The discovery ran through the multi-phase agent process; a mid-run finding (unsigned inbound webhook) invalidated the plan, escalated, and the design pivoted to Event Grid with JWT-signed events — recorded, not silently absorbed.</li>
</ul>
</div>
</div>
</details>
<!-- COM-01 -->
<details class="entry" id="COM-01" data-status="reference" open>
<summary>
<span class="sum-body">
<span class="sum-head"><span class="eid mono">COM-01</span> · <span class="etitle mono">Community, teaching &amp; open source</span></span>
<span class="esum">Teaching adjacent audiences deliberately, and building the artefact where a claim alone would be doubted.</span>
</span>
<span class="pill reference mono"><span class="dot reference"></span>Record</span>
</summary>
<div class="panel">
<div class="fg">
<ul>
<li><b>President, Swinburne Linux Club</b> (Feb 2018 – Mar 2019).</li>
<li>In-house DevOps/infra training and brown-bags (Terraform, CI/CD, Azure), recorded for wider distribution.</li>
<li>Contributed to Microsoft Azure PowerShell and GitHub Copilot's awesome-copilot; raised a SailPoint IdentityNow API-spec issue and a VS Code bug.</li>
<li>Mentors junior engineers; pushes automation-first thinking.</li>
</ul>
</div>
</div>
</details>
<!-- SKILL-01 -->
<details class="entry" id="SKILL-01" data-status="reference" open>
<summary>
<span class="sum-body">
<span class="sum-head"><span class="eid mono">SKILL-01</span> · <span class="etitle mono">Skills &amp; tools</span></span>
<span class="esum">Grouped by where the depth actually is. Azure and PowerShell are the load-bearing ones.</span>
</span>
<span class="pill reference mono"><span class="dot reference"></span>Record</span>
</summary>
<div class="panel">
<div class="fg">
<p class="fgt mono">AI &amp; agentic</p>
<ul>
<li>Multi-agent orchestration, tool/function calling, evaluation harnesses, human escalation and decision records.</li>
<li>Model Context Protocol servers and secure context injection; RAG; prompt design and evaluation; token budgeting and context-window management.</li>
<li>Local open-weight model hosting (vLLM, llama.cpp; incl. Qwen 3 Coder-480B). Providers: OpenAI, Anthropic Claude, xAI Grok — APIs, SDKs, CLIs. GitHub Copilot with custom modes.</li>
</ul>
</div>
<div class="fg">
<p class="fgt mono">Cloud &amp; platform</p>
<ul>
<li>Microsoft Azure (PaaS/IaaS), AKS, Azure DevOps. Terraform, Bicep/ARM, Docker, CI/CD, IaC, API Management.</li>
<li>Cloud-agnostic architecture; deep Azure, working GCP familiarity.</li>
</ul>
</div>
<div class="fg">
<p class="fgt mono">Identity &amp; security</p>
<ul>
<li>SailPoint IdentityNow, CyberArk, Okta, Entra ID / Azure AD B2C. RBAC, PAM, access certification, Zero Trust, secrets and certificate management.</li>
</ul>
</div>
<div class="fg">
<p class="fgt mono">Automation &amp; development</p>
<ul>
<li>PowerShell (advanced, module development, vendor API automation, API reverse engineering). Python, .NET Core, C#, Angular, SQL. OAuth / OIDC.</li>
</ul>
</div>
</div>
</details>
</main>
</div>
<footer class="mono">joshua@homelab:~$ <span style="color:hsl(var(--text-secondary))">end of file</span> — figures are attributable career facts, not benchmarks. No third-party results presented as my own.</footer>
</div>
