# WeChat Mini Program Development Skill

A Codex skill for planning, building, iterating, debugging, and verifying native WeChat Mini Programs. It emphasizes repository-first work, user-controlled scope, privacy-aware data choices, and honest testing claims.

## Contents

- `SKILL.md` — core workflow and safety boundaries.
- `references/` — project interaction lessons, current-policy verification checklist, optional cloud/subscription notes, and troubleshooting.
- `assets/wx-template/` — a small native starter with an optional local/cloud data-store pattern.

## Install in Codex

1. Download this repository as a ZIP from GitHub and extract it.
2. Copy the repository folder into `~/.codex/skills/wechat-miniprogram-dev/` (or the configured `$CODEX_HOME/skills/` directory).
3. Start a new Codex session, then invoke `$wechat-miniprogram-dev` or describe a native Mini Program task.

The template is optional. For an existing app, let the skill inspect and preserve its architecture rather than copying over the project.

## Safe use

- The examples contain placeholders, not real app credentials. Never commit passwords, verification codes, private keys, access tokens, personal data, or real production configuration.
- Review `project.config.json`, `utils/config.js`, cloud permissions, privacy declarations, and pack exclusions before using or publishing a derived app.
- WeChat rules and APIs change. Verify account eligibility, privacy requirements, service categories, review steps, and API behavior in current official documentation and the developer console.
- The example's local storage stays on that app installation; it is not cross-device sync or backup. Cloud isolation depends on correctly configured access rules.

## License

MIT. See `LICENSE`.
