<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" width="420" alt="coding"/>
</p>

### hey, I'm Khuswant

I build full-stack and AI products, and I spend a lot of my evenings inside Kubernetes security tooling — mostly [Kubescape](https://github.com/kubescape), where I've had 17 PRs merged across the eBPF node-agent, the Rego rule library, the operator, the Helm charts and the core CLI.

Right now I'm going deeper on distributed systems and Kubernetes internals. If you're working on something in that space, or on agentic AI that solves a real, boring business problem, I'd like to hear about it.

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

[email](mailto:khuswantrajpurohit18@gmail.com) · [linkedin](https://www.linkedin.com/in/khuswant-rajpurohit-b749ba30a/) · [x](https://x.com/KhuswantRa45688) · [youtube](https://youtube.com/@khuswantrajpurohit) · [portfolio](https://khuswant18.github.io/Portfolio/)

<br/>

### things I've fixed upstream

24 merged PRs in other people's code so far. The ones I'm proudest of:

**kubescape** — 17 merged

- `node-agent` [#926](https://github.com/kubescape/node-agent/pull/926) fixed a lifecycle race in the malware manager
- `node-agent` [#911](https://github.com/kubescape/node-agent/pull/911) context-based rule filtering in the rule manager
- `node-agent` [#914](https://github.com/kubescape/node-agent/pull/914) unit tests for the malware, health and node-profile managers
- `node-agent` [#892](https://github.com/kubescape/node-agent/pull/892) runtime alert path handling
- `kubescape` [#3802](https://github.com/kubescape/kubescape/pull/3802) made `GetScanningContext` side-effect free
- `kubescape` [#3665](https://github.com/kubescape/kubescape/pull/3665) OpenTelemetry spans now end on every exit and error path
- `kubescape` [#3126](https://github.com/kubescape/kubescape/pull/3126) validation for layers and vulnerabilities in `ScanResultReport`
- `regolibrary` [#790](https://github.com/kubescape/regolibrary/pull/790) [#792](https://github.com/kubescape/regolibrary/pull/792) new controls C-0305 and C-0307
- `regolibrary` [#768](https://github.com/kubescape/regolibrary/pull/768) [#778](https://github.com/kubescape/regolibrary/pull/778) [#787](https://github.com/kubescape/regolibrary/pull/787) Agent Sandbox rules — hardened runtime class, egress policy, resource ceilings
- `regolibrary` [#795](https://github.com/kubescape/regolibrary/pull/795) [#796](https://github.com/kubescape/regolibrary/pull/796) init/ephemeral container coverage, secrets via `envFrom`
- `operator` [#418](https://github.com/kubescape/operator/pull/418) ephemeral container support
- `helm-charts` [#907](https://github.com/kubescape/helm-charts/pull/907) Prometheus OTEL exporter for node-agent

**elsewhere**

- `harbor-next` [#955](https://github.com/container-registry/harbor-next/pull/955) goroutine leak in project `ListAll` · [#1023](https://github.com/container-registry/harbor-next/pull/1023) filter preheat scan index by tag — *in review*
- `kube-burner` [#1211](https://github.com/kube-burner/kube-burner/pull/1211) docs fix
- `Animation-Nation` six CSS/JS animations

<br/>

### what I reach for

<a href="#"><img src="https://skillicons.dev/icons?i=ts,go,py,react,nextjs,nodejs,fastapi,postgres,mongodb,redis,docker,kubernetes,linux&theme=dark" /></a>

plus LangGraph, RAG pipelines, Ollama and Groq on the AI side, and Rego, eBPF, Helm and OpenTelemetry on the cloud-native side.

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=khuswant18&theme=tokyo-night&hide_border=true&area=true&radius=10" width="100%" alt="activity graph"/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/khuswant18/khuswant18/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/khuswant18/khuswant18/output/github-contribution-grid-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/khuswant18/khuswant18/output/github-contribution-grid-snake-dark.svg" width="100%" />
</picture>

<a href="https://holopin.io/@khuswant18"><img src="https://holopin.me/khuswant18" alt="@khuswant18's Holopin badges" width="100%"/></a>
