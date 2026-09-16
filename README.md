# ai-skill-issue

Turn a rough ask into a well-formed GitHub issue, following this repo's own conventions. Use when asked to "create an issue", "open an issue", "file an issue", "raise an issue", "log a bug", "track this as an issue", "make a GitHub issue", or when describing a bug / feature / task to capture in the tracker. Interviews for gaps, researches the repo for real references and duplicates, drafts a type-aware (bug / feature / task) issue, shows it for approval, then creates it via gh. Portable across repositories — labels, areas, and attribution are read from the repo's own config or inferred, never hardcoded.

## Install

```bash
# Add marketplace (uses repo slug)
/plugin marketplace add guillempuche/ai-skill-issue

# Install plugin (plugin name is topic-only)
/plugin install issue@guillempuche-ai-skill-issue
```

## Part of AI Standards

This skill is also available in the [ai-standards](https://github.com/guillempuche/ai-standards) bundle with other skills and agents.

## License

MIT
