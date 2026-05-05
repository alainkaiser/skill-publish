# skill-publish

Agent skills shipped from this repo. Skills live under:

`skills/<skill-name>/SKILL.md`

Published skill path for **no-blocking-async**:

`skills/no-blocking-async/SKILL.md`

## Install with npx

The [`skills` CLI](https://github.com/vercel-labs/skills) (`npx skills …`) clones the skill definitions from GitHub into your Cursor (or compatible) skill directories.

**Install only this skill into the current project** (default placement is tooling-specific; Cursor typically uses `.cursor/skills/`):

```bash
npx skills add alainkaiser/skill-publish --skill no-blocking-async
```

**Install globally** (user-wide; often `~/.cursor/skills/` for Cursor):

```bash
npx skills add alainkaiser/skill-publish --skill no-blocking-async -g
```

**Target Cursor explicitly** (when the CLI supports it):

```bash
npx skills add alainkaiser/skill-publish --skill no-blocking-async -a cursor
```

Combine flags as needed, for example non-interactive:

```bash
npx skills add alainkaiser/skill-publish --skill no-blocking-async -g -a cursor -y
```

For all options, run:

```bash
npx skills add --help
```

Replace `alainkaiser/skill-publish` with your fork’s `owner/repo` if you install from a fork.

## Manual install

Copy `skills/no-blocking-async/` into your project’s `.cursor/skills/no-blocking-async/` (or your user `~/.cursor/skills/no-blocking-async/`) so that `SKILL.md` ends up at `.cursor/skills/no-blocking-async/SKILL.md`.
