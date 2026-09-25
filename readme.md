<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" width="420" alt="coding"/>
</p>

<h1 align="center">Khuswant Rajpurohit</h1>

<p align="center">
  full-stack & AI engineer &nbsp;·&nbsp; Kubescape (CNCF) contributor &nbsp;·&nbsp; Delhi, India
</p>

<p align="center">
  <a href="https://khuswant18.github.io/Portfolio/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/khuswant-rajpurohit-b749ba30a/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://x.com/KhuswantRa45688"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white"/></a>
  <a href="https://youtube.com/@khuswantrajpurohit"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/></a>
  <a href="mailto:khuswantrajpurohit18@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<br/>

I build full-stack and AI products, and I spend a lot of my evenings inside Kubernetes security tooling — mostly [Kubescape](https://github.com/kubescape), where I've had 17 PRs merged across the eBPF node-agent, the Rego rule library, the operator, the Helm charts and the core CLI.

Right now I'm going deeper on distributed systems and Kubernetes internals. If you're working on something in that space, or on agentic AI that solves a real business problem, I'd like to hear about it.

```console
khuswant@delhi ~ % whoami
────────────────────────────────────────────────────────
 name       Khuswant Rajpurohit
 based in   Delhi, India
 does       full-stack · AI agents · cloud-native OSS
 writes     TypeScript, Go, Python, Rego
 upstream   kubescape (CNCF) · harbor-next · kube-burner
 learning   distributed systems, k8s internals, eBPF
 open to    internships, collabs, open-source work
```

<br/>

## Open source

<table>
<tr>
<td align="center" width="25%">
  <a href="https://github.com/kubescape"><img src="https://github.com/kubescape.png" width="64" alt="Kubescape"/></a><br/>
  <b>Kubescape</b><br/>
  <sub>CNCF · Kubernetes security</sub><br/><br/>
  <img src="https://img.shields.io/badge/17-merged-2ea44f?style=flat-square"/>
</td>
<td align="center" width="25%">
  <a href="https://github.com/container-registry/harbor-next"><img src="https://github.com/container-registry.png" width="64" alt="Harbor Next"/></a><br/>
  <b>Harbor Next</b><br/>
  <sub>container registry</sub><br/><br/>
  <img src="https://img.shields.io/badge/2-in%20review-e3b341?style=flat-square"/>
</td>
<td align="center" width="25%">
  <a href="https://github.com/kube-burner/kube-burner"><img src="https://github.com/kube-burner.png" width="64" alt="kube-burner"/></a><br/>
  <b>kube-burner</b><br/>
  <sub>k8s perf & scale testing</sub><br/><br/>
  <img src="https://img.shields.io/badge/1-merged-2ea44f?style=flat-square"/>
</td>
<td align="center" width="25%">
  <a href="https://github.com/zero-to-mastery/Animation-Nation"><img src="https://github.com/zero-to-mastery.png" width="64" alt="Zero To Mastery"/></a><br/>
  <b>Animation-Nation</b><br/>
  <sub>CSS / JS animations</sub><br/><br/>
  <img src="https://img.shields.io/badge/6-merged-2ea44f?style=flat-square"/>
</td>
</tr>
</table>

Where the Kubescape PRs landed:

<p>
  <a href="https://github.com/kubescape/regolibrary/pulls?q=is%3Apr+author%3Akhuswant18+is%3Amerged"><img src="https://img.shields.io/badge/regolibrary-7%20merged-326CE5?style=for-the-badge&logo=openpolicyagent&logoColor=white"/></a>
  <a href="https://github.com/kubescape/node-agent/pulls?q=is%3Apr+author%3Akhuswant18+is%3Amerged"><img src="https://img.shields.io/badge/node--agent%20(eBPF)-4%20merged-326CE5?style=for-the-badge&logo=linux&logoColor=white"/></a>
  <a href="https://github.com/kubescape/kubescape/pulls?q=is%3Apr+author%3Akhuswant18+is%3Amerged"><img src="https://img.shields.io/badge/kubescape%20CLI-4%20merged-326CE5?style=for-the-badge&logo=go&logoColor=white"/></a>
  <a href="https://github.com/kubescape/operator/pulls?q=is%3Apr+author%3Akhuswant18+is%3Amerged"><img src="https://img.shields.io/badge/operator-1%20merged-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/></a>
  <a href="https://github.com/kubescape/helm-charts/pulls?q=is%3Apr+author%3Akhuswant18+is%3Amerged"><img src="https://img.shields.io/badge/helm--charts-1%20merged-326CE5?style=for-the-badge&logo=helm&logoColor=white"/></a>
</p>

<details>
<summary><b>See every PR</b></summary>
<br/>

- `node-agent` [#926](https://github.com/kubescape/node-agent/pull/926) fixed a lifecycle race in the malware manager
- `node-agent` [#911](https://github.com/kubescape/node-agent/pull/911) context-based rule filtering in the rule manager
- `node-agent` [#914](https://github.com/kubescape/node-agent/pull/914) unit tests for the malware, health and node-profile managers
- `node-agent` [#892](https://github.com/kubescape/node-agent/pull/892) runtime alert path handling
- `kubescape` [#3802](https://github.com/kubescape/kubescape/pull/3802) made `GetScanningContext` side-effect free
- `kubescape` [#3665](https://github.com/kubescape/kubescape/pull/3665) OpenTelemetry spans now end on every exit and error path
- `kubescape` [#3126](https://github.com/kubescape/kubescape/pull/3126) validation for layers and vulnerabilities in `ScanResultReport`
- `kubescape` [#2744](https://github.com/kubescape/kubescape/pull/2744) naming fixes
- `regolibrary` [#790](https://github.com/kubescape/regolibrary/pull/790) [#792](https://github.com/kubescape/regolibrary/pull/792) new controls C-0305 and C-0307
- `regolibrary` [#768](https://github.com/kubescape/regolibrary/pull/768) [#778](https://github.com/kubescape/regolibrary/pull/778) [#787](https://github.com/kubescape/regolibrary/pull/787) Agent Sandbox rules — hardened runtime class, egress policy, resource ceilings
- `regolibrary` [#795](https://github.com/kubescape/regolibrary/pull/795) [#796](https://github.com/kubescape/regolibrary/pull/796) init/ephemeral container coverage, secrets via `envFrom`
- `operator` [#418](https://github.com/kubescape/operator/pull/418) ephemeral container support
- `helm-charts` [#907](https://github.com/kubescape/helm-charts/pull/907) Prometheus OTEL exporter for node-agent
- `harbor-next` [#955](https://github.com/container-registry/harbor-next/pull/955) goroutine leak in project `ListAll` · [#1023](https://github.com/container-registry/harbor-next/pull/1023) filter preheat scan index by tag
- `kube-burner` [#1211](https://github.com/kube-burner/kube-burner/pull/1211) docs fix

</details>

<br/>

## Tech stack

<table>
<tr><td><b>Languages</b></td><td><img src="https://skillicons.dev/icons?i=ts,js,go,py,c,cpp,java,html,css&theme=dark" /></td></tr>
<tr><td><b>Frontend</b></td><td><img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,vite,redux,figma&theme=dark" /></td></tr>
<tr><td><b>Backend</b></td><td><img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,prisma,graphql&theme=dark" /></td></tr>
<tr><td><b>Databases</b></td><td><img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,mysql,supabase&theme=dark" /></td></tr>
<tr><td><b>Cloud & DevOps</b></td><td><img src="https://skillicons.dev/icons?i=docker,kubernetes,githubactions,aws,vercel,cloudflare,nginx,linux,bash&theme=dark" /></td></tr>
<tr><td><b>Tools</b></td><td><img src="https://skillicons.dev/icons?i=git,github,postman,vscode,npm,pnpm&theme=dark" /></td></tr>
<tr><td><b>AI / ML</b></td><td>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/RAG-7C3AED?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/ChromaDB-FF6B6B?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/>
  <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white"/>
  <img src="https://img.shields.io/badge/Whisper-412991?style=for-the-badge&logo=openai&logoColor=white"/>
</td></tr>
<tr><td><b>Cloud-native</b></td><td>
  <img src="https://img.shields.io/badge/Kubescape-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Rego%20%2F%20OPA-7D9199?style=for-the-badge&logo=openpolicyagent&logoColor=white"/>
  <img src="https://img.shields.io/badge/eBPF-FF6600?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/>
</td></tr>
</table>

<br/>

## Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="profile-3d-contrib/profile-night-rainbow.svg" />
  <source media="(prefers-color-scheme: light)" srcset="profile-3d-contrib/profile-green-animate.svg" />
  <img src="profile-3d-contrib/profile-night-rainbow.svg" alt="3D contribution graph" width="100%" />
</picture>

<br/>

<a href="https://holopin.io/@khuswant18"><img src="https://holopin.me/khuswant18" alt="@khuswant18's Holopin badges" width="100%"/></a>
