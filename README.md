# 🧰 Toolkit

Toolkit is a template I use for tooling on new projects I spin up. It has some
basic but very useful tools that help speed up my work and ensure checks are run
before code leaves my dev machine.

## Included Tools

- **[mise](https://mise.jdx.dev)** - Runtime version manager for multiple programming languages and tools
- **[Task](https://taskfile.dev/)** - Task runner and build tool alternative to Make
- **[dprint](https://dprint.dev/)** - Code formatter that supports multiple languages including TypeScript, JSON, Markdown, YAML, and more
- **[lefthook](https://lefthook.dev)** - Fast Git hooks manager for running checks before commits and pushes
- **[committed](https://github.com/crate-ci/committed)** - Linter for conventional commit messages
- **[gitleaks](https://gitleaks.io/)** - Secret scanner to detect hardcoded secrets in Git repositories

## OpenCode Skill

This repo includes a reusable skill for bootstrapping the tooling baseline into other projects:

- Skill directory: `project-tooling-bootstrap/`
- Packaged artifact: `project-tooling-bootstrap.skill`

Install it to OpenCode with the Vercel Skills CLI:

```bash
npx skills add ./project-tooling-bootstrap -a opencode
```

Install globally instead of project-local:

```bash
npx skills add ./project-tooling-bootstrap -a opencode -g
```
