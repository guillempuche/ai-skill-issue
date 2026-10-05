# ai-skill-issue

Draft and file one GitHub issue that follows the repo's conventions, after checking for duplicates. Use when asked to "create", "open", "file", or "raise" an issue, "log a bug", or "track this as an issue".

## Install

### Any agent

The [`skills`](https://github.com/vercel-labs/skills) CLI installs into Codex, OpenCode, Gemini CLI, Cursor, Copilot, Claude Code, and 70+ other agents:

```bash
npx skills add guillempuche/ai-skill-issue
```

### Claude Code

```bash
# Add marketplace (uses repo slug)
/plugin marketplace add guillempuche/ai-skill-issue

# Install plugin (plugin name is topic-only)
/plugin install issue@guillempuche-ai-skill-issue
```

### Gemini CLI

```bash
gemini skills install https://github.com/guillempuche/ai-skill-issue.git --path skills/issue
```

### Manual

Copy `skills/issue` into `.agents/skills/` (Codex, Gemini CLI, OpenCode, Mastra Code, Cursor, Copilot) or `.claude/skills/` (Claude Code).

## Part of AI Standards

This skill is also available in the [ai-standards](https://github.com/guillempuche/ai-standards) bundle with other skills and agents.

## License

MIT
