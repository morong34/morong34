<div align="center">

# Narcis-Eusebiu Morong

**Full-stack developer · AI-agent workflows · Timișoara 🇷🇴**

<a href="https://www.linkedin.com/in/morong-narcis-eusebiu-543591200"><img src="https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<img src="https://img.shields.io/badge/open%20to-collaboration-2ea44f?style=for-the-badge" alt="Open to collaboration">

</div>

---

## 🛠️ What I work with

<div align="center">

<img src="https://skillicons.dev/icons?i=rails,ruby,postgres,redis,angular,ts,flutter,dart,py,fastapi,cloudflare,githubactions&perline=6" alt="Rails, Ruby, PostgreSQL, Redis, Angular, TypeScript, Flutter, Dart, Python, FastAPI, Cloudflare, GitHub Actions">

</div>

Backend and APIs, web and mobile apps, geospatial and satellite data, document and AI pipelines (Claude API, local models with MLX), and the platform around them: tunnels, access control, CI and deploys.

## 🤖 How I work with AI agents

I use Claude Code as a coordinator, not just an autocomplete. Every change goes through the same loop:

```mermaid
flowchart LR
    A([Me: scope the work]) --> B[Specialist agents<br/>read-only answers]
    B --> C[Worker agent<br/>own git worktree]
    C --> D[Pull request]
    D --> E{Verifier agent<br/>fresh context}
    E -- not ready --> C
    E -- ready + green CI --> F([Merge + deploy])
```

> [!IMPORTANT]
> Agents write and check the code. A human decides what ships.

<details>
<summary><b>The rules that keep it safe on production hardware</b></summary>

- Worktrees only, never edit a production checkout.
- No merge without a verifier saying ready and a green CI gate.
- No secrets in agent sandboxes.
- Production writes only after a dry run, a backup and my approval.
- Cheaper models do routine work; the strongest model is kept for design, root-cause and security questions.

</details>

## 🎯 What I care about

- **Access control and audit trails:** roles, invitations, rate limits, soft deletes with a grace period.
- **Reliable deploys:** fewer restarts, quiet retries in the client, a path to zero downtime.
- **Data honesty:** every number on a screen is real data, and its label describes it.
- **Clear hand-offs** between humans and agents.

## 🔭 Interests

Software engineering, web and mobile engineering, and building reliable systems that people outside tech depend on.

<!--
morong34/morong34 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
