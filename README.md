# skillbox

Personal collection of AI agent skills (SKILL.md format)

## Getting started

```bash
git clone <this repo>
cp -r skills/* ~/.claude/skills/
```

## Features

- Drop-in compatible with ~/.claude/skills
- Concrete instructions, output formats and examples
- YAML frontmatter: name + when-to-use description
- Versioned like code: review changes in PRs
- Each skill is a folder with a single SKILL.md

## How to use

```bash
# skills trigger automatically on matching tasks
# or invoke directly: /code-review
```

## Project structure

```text
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── bug_report.md
├── docs/
│   ├── configuration.md
│   └── development.md
├── skills/
│   ├── code-review/
│   │   └── SKILL.md
│   ├── commit-message/
│   │   └── SKILL.md
│   ├── refactor-plan/
│   │   └── SKILL.md
│   └── test-writer/
│       └── SKILL.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── Makefile
└── SECURITY.md
```

## Known issues

- none reported yet (surprisingly)

## License

MIT. Do whatever you want.
