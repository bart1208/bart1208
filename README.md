## Bartolomeo Pasquale

Software engineer. Twenty years of shipped production systems — public administration, enterprise,
advertising, gaming, regulated betting. Now building the infrastructure that lets AI agents do real
engineering work.

Both halves matter, and only together. "Twenty years of delivery" describes a senior generalist in a
crowded market; "works with AI" is the most common and least verifiable claim on the internet in
2026. The uncommon part is the conjunction — someone who shipped a consular services portal for the
Italian Ministry of Foreign Affairs, led the React front end of an enterprise ordering platform at
Fujitsu, and spent six years inside regulated sports-betting data, and who now runs a self-hosted
multi-agent system with version control, encrypted secrets, scheduled integrity checks and
cross-machine deployment.

### What I work on now

**Agent infrastructure.** One instruction layer, one memory store and one tool registry, shared by
five different coding agents. MCP has no common configuration format, so the registry is the source
of truth and each agent's config is generated from it.

**Knowledge systems agents can be trusted with.** A schema'd, git-versioned vault with typed pages,
an enforced lifecycle, append-only operation logs, and a linter that runs on a timer. Agents write
it; the linter is what keeps them honest.

**Identity, credentials and secrets discipline.** git-crypt for personal data, pointer-only
credential documentation, per-machine credential activation tracked explicitly rather than assumed,
and conventions written down after each way it went wrong rather than before.

**Self-hosting.** A Hetzner VPS running the `*.fenrir.it` services on plain systemd — no Docker,
no PaaS, no managed anything.

### Public work

- **[linkedin-portability](https://github.com/bart1208/linkedin-portability)** — read your own
  LinkedIn data from the command line through the EU Digital Markets Act portability API. The README
  covers what the official documentation leaves out: API version pinning, pagination that cannot be
  trusted, and why the Snapshot endpoint is not a live read of your profile while the Changelog is.
- **[fenrir.it](https://fenrir.it)** — personal site and manifesto. Hand-written, trilingual, no
  framework and no build step. [Source](https://github.com/bart1208/fenrir.it).

### Elsewhere

Based in Sevilla. Italian native, Spanish and English at professional working proficiency.

[fenrir.it](https://fenrir.it) · [LinkedIn](https://www.linkedin.com/in/bartolomeopasquale/)
