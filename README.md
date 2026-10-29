# Hi, I'm Narcis 👋

Software developer in Timișoara. I build full-stack products end to end and use AI agents as a normal part of how I work.

## What I work with

| Area | Stack |
|---|---|
| Backend | Ruby on Rails, PostgreSQL + PostGIS, Sidekiq, Redis, WebSockets |
| Web | Angular, TypeScript, signals, SCSS design tokens, Vitest |
| Mobile | Flutter / Dart, Riverpod |
| Services | Python, FastAPI, SQLAlchemy |
| AI | Claude API, local models with MLX, OCR and document pipelines |
| Geospatial / data | Satellite imagery, weather data, PostGIS, scrapers and data pipelines |
| Platform | Cloudflare (Tunnel, Access, Pages), launchd, GitHub Actions with a self-hosted runner |

## How I work with AI agents

I use Claude Code as a coordinator, not just an autocomplete:

- **Specialist agents** answer questions read-only and cite file and line.
- **Worker agents** implement one scoped change in their own git worktree and open a pull request. A human merges.
- **Verifier agents** re-check every pull request in a fresh context against its acceptance criteria before it merges.
- **Hard rules** keep it safe on production hardware: worktrees only, no merge without a verifier and green CI, no secrets in agent sandboxes, production writes only after a dry run, a backup and my approval.
- Cheaper models do routine work, and the strongest model is kept for design, root-cause and security questions.

## What I care about

- Access control, audit trails and safe defaults: roles, invitations, rate limits, soft deletes with a grace period.
- Reliable deploys: fewer restarts, quiet retries in the client, and a path to zero-downtime releases.
- Data honesty: every number on a screen should be real data, and its label should describe it.
- Clear hand-offs between humans and agents.

## Interests

Software engineering, web and mobile engineering, and building reliable systems that people outside tech depend on.

📫 Find me on [LinkedIn](https://www.linkedin.com/in/morong-narcis-eusebiu-543591200).

<!--
morong34/morong34 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
