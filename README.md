# skill-publish

Skills live under `skills/<skill-name>/SKILL.md` (YAML frontmatter + Markdown body). Push to GitHub, then install into a project:

```bash
npx skills add <owner>/<repo> --skill <skill-name>
```

Example after publishing this repo:

```bash
npx skills add <your-github-username>/skill-publish --skill no-blocking-async
```

Browse public skills at [skills.sh](https://skills.sh).
