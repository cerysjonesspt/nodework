# nodework

Learning TypeScript by building tiny CLIs

## What it does

- commander-based subcommands
- Ships as an ESM binary
- npm link friendly
- Strict tsconfig, no any

## How to use

```bash
npx . convert data.csv -d ';'
# or after npm link: cliparse convert data.csv
```

## Install

```bash
npm install
npm run build
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   └── index.ts
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── package.json
└── tsconfig.json
```

## Development

```bash
npm install
```

## Notes

- mostly stable, edge cases remain
