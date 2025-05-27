````md
# 🤝 Contributing to Veloce UI

Thank you for considering contributing to **Veloce UI**, a scalable and reusable UI component system built with React, Tailwind CSS, and shadcn/ui.

---

## 📦 Project Structure

This is a monorepo managed with [Turborepo](https://turbo.build/repo), containing:

- `packages/ui-kit` – The core component library
- `apps/docs` – Storybook for documentation and testing

---

## 🧪 Project Setup

```bash
git clone https://github.com/yourusername/veloce-ui.git
cd veloce-ui
pnpm install
pnpm dev
````

---

## 📚 Run Storybook

```bash
pnpm storybook
```

---

## ✅ Run Tests

```bash
pnpm test
```

---

## 🔍 Run Linter

```bash
pnpm lint
```

---

## 🧹 Code Standards

* **TypeScript** – All code must use `.ts` or `.tsx` files
* **Tailwind CSS** – Utility-first styling
* **ESLint + Prettier** – For consistent formatting
* **Husky** – Pre-commit hooks to run lint and tests
* **Changesets** – For versioning and changelogs

---

## 🧾 Commit Message Format

Follow [Conventional Commits](https://www.conventionalcommits.org/) format:

```bash
feat: add Accordion component
fix: resolve Modal z-index issue
refactor: clean up Input validation logic
chore: update dependencies
test: add RTL tests for Tabs
```

---

## ✅ Before You Submit a Pull Request

* [ ] Code builds without errors
* [ ] All tests pass
* [ ] Storybook is updated if needed
* [ ] PR title follows Conventional Commits format
* [ ] You described what and why clearly in the PR

---

## 🚀 Versioning and Publishing (Changesets)

To create a changeset:

```bash
pnpm changeset
```

To apply version bumps locally:

```bash
pnpm changeset version
```

To publish:

```bash
pnpm changeset publish
```

---

Thanks for helping make this project better 💙

```
```
