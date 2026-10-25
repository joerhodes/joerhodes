# Joe Rhodes

Senior software developer and infrastructure engineer based in the Dallas-Fort Worth area — 30+ years designing, building and running systems, from application code down to the network layer.

By day I develop and maintain Laravel/PHP applications and lead DevOps and infrastructure efforts for a mid-size company: AWS migrations, CI/CD adoption, identity management, and network architecture. By night I run a self-hosted, local-first infrastructure lab at home — the same instincts applied at a personal scale.

## What I work on

**Professionally** — modernizing legacy applications, cloud migration and cost management, CI/CD pipelines, and segmented network design. Recently focused on integrating AI-assisted development tooling (MCP-served context docs, agent workflows) into a live development team.

**Personally** — a self-hosted infrastructure lab where I explore concepts and configurations that often end up informing how I think about the professional side: network segmentation, monitoring, and automation, but at a scale where I can experiment freely.  This currently includes:

- A home lab for infrastructure and network experiments.
- A segmented home network built on UniFi gear.
- Home Assistant for environmental and power monitoring around the property.
- A 3D printer that pulls double duty producing parts for the lab itself.

## Projects

- **[larakit](https://github.com/joerhodes/larakit):** a Bash wrapper around Laradock I built at work so a team new to Docker could run consistent local environments. Published with my employer's permission, with BATS tests and real development history.
- **[monero-income](https://github.com/joerhodes/monero-income):** a Python CLI rebuilt from scratch with spec-driven development (GitHub Spec Kit + Claude Code). The constitution, specs, plans, and session logs are all in the repo.
- **[mini-fleet-maestro](https://github.com/joerhodes/mini-fleet-maestro):** agentless Ansible provisioning for a fleet of headless Mac Minis: power settings, scoped sudo, and payloads pushed from a controller rather than pulled on each node - in progress.
- **[devmode](https://github.com/joerhodes/devmode):** a Bash script that switches a Mac between two local dev stacks (larakit's Docker containers and Laravel Herd) as one unit, coordinating Docker, dnsmasq, and supporting services through per-mode config files.

## Currently exploring

*As of October 2026*

- **Spec-driven development:** whether specs and a project constitution make AI-written code reviewable, both in my own work and as a process for a team moving to agentic coding.
- **Agent workflows built on git worktrees:** exploring Bloom, which runs coding agents in their own worktrees and hands results back as pull requests. Working through its workflow pushed me to really learn worktrees and the `gh` CLI. Running several agents in parallel is next, ideally with tooling that also works with self-hosted Forgejo, where my own work lives.
- **Design principles in AI output:** probing coding assistants for the principles they don't apply on their own, such as Separation of Concerns and Single Responsibility.
- **Supply chain security:** an occasional check-in on tooling and trust models across Python, Rust, Swift, and PHP.

## How I Work

- **Shared code, scoped variables:** Write defensively for anything that gets sourced alongside other modules — scoped variables, explicit error propagation, no unstated assumptions about caller context.<br/>
- **Tests protect contracts, not internals:** Design coverage around the guarantee a function makes to its callers, not its implementation — a suite that survives refactors instead of breaking on them.<br/>
- **Documentation reflects reality:** State actual project status, including known gaps, rather than overstating completeness — an honest "here's what's covered" beats a green checkmark that isn't quite true.<br/>
- **Traceable dependencies across files:** When related logic has to stay in sync across files, leave a discoverable trail — tagged comments, grep-able markers — rather than trusting memory to catch drift later.

## Skills

- **Languages & Frameworks:** PHP, Laravel, Python, Perl, Bash, C, Java, JavaScript<br>
- **Infrastructure:** Linux administration, Docker, AWS, DNS/DHCP, IPTables/UFW firewalls, Samba/NFS<br>
- **Databases:** PostgreSQL (incl. Foreign Data Wrappers), SQLite<br>
- **DevOps:** CI/CD (Bitbucket Pipelines, Laravel Envoyer), JumpCloud IAM, Git

## Connect

- [LinkedIn](https://www.linkedin.com/in/joerhodes-dev)

---
*This profile is a work in progress — thanks for stopping by.*
