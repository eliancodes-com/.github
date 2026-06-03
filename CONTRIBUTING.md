# Contributing to ElianCodes

Thanks for taking the time to contribute! 🎉 This guide applies to all repositories in the
[ElianCodes organization](https://github.com/eliancodes-com) unless a repo provides its own
`CONTRIBUTING.md`.

## Code of conduct

By participating, you agree to uphold our [Code of Conduct](./CODE_OF_CONDUCT.md). Please be
kind and respectful.

## Ways to contribute

- 🐛 **Report bugs** — open an issue with clear steps to reproduce.
- 💡 **Suggest features** — open a feature request describing the problem you want solved.
- 📝 **Improve docs** — typos, clarifications, and examples are always welcome.
- 🔧 **Submit code** — fix a bug or build a feature via a pull request.

## Before you start

For anything more than a trivial fix, **open an issue first** so we can align on the approach
before you invest time. This avoids duplicated effort and surprise rewrites.

## Development workflow

1. **Fork** the repository and clone your fork.
2. **Create a branch** from `main`:
   ```bash
   git checkout -b feat/short-description
   ```
3. **Install dependencies.** Most of our projects use [pnpm](https://pnpm.io):
   ```bash
   pnpm install
   ```
4. **Make your changes.** Keep commits focused and atomic.
5. **Verify locally** before pushing:
   ```bash
   pnpm lint
   pnpm build
   pnpm test   # if the project has tests
   ```
6. **Open a pull request** against `main` and fill out the template.

## Commit messages

We follow [Conventional Commits](https://www.conventionalcommits.org/). Use a type prefix:

```
feat: add dark-mode toggle to navbar
fix: prevent layout shift on hero image
docs: clarify deploy instructions
chore: bump astro to 5.x
```

Common types: `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `test`, `chore`, `ci`.

## Pull request guidelines

- Keep PRs **small and focused** — one logical change per PR.
- Link the related issue (`Closes #123`).
- Make sure CI is green.
- Update docs and tests alongside code changes.
- A maintainer will review; please be patient and responsive to feedback.

## Code style

- **TypeScript** preferred over plain JS.
- Follow the existing **ESLint** / **Prettier** config in the repo — don't fight the formatter.
- Prioritize **accessibility** and **performance**; these are core to how we build.

## Questions?

Open a [discussion](https://github.com/orgs/eliancodes-com/discussions) or email
[hello@elian.codes](mailto:hello@elian.codes).
