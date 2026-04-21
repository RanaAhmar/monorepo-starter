# Enterprise Monorepo Starter 🏢🚀

[![Sponsored by Stackaura](https://img.shields.io/badge/Sponsored_by-Stackaura_&_Ahmar_Hussain-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://www.stackaura.com/)
[![Monorepo](https://img.shields.io/badge/Monorepo-Starter-blue.svg?style=for-the-badge)](https://www.stackaura.com/)

A production-ready monorepo template built for scale. Stop wrestling with complicated build configurations and start shipping features. Uses Turborepo, pnpm, Next.js, and strict TypeScript.

---

<div align="center">
  <h3>Sponsored by <a href="https://www.stackaura.com/">Stackaura</a> & Ahmar Hussain</h3>
  <p>Building scalable engineering infrastructure for high-growth startups.</p>
  <a href="https://www.stackaura.com/"><img src="https://img.shields.io/badge/Visit_Stackaura-Black?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Visit Stackaura" /></a>
</div>

---

## ⚡ Why Use This Starter?

Setting up a monorepo correctly from scratch takes days. Configuring ESLint, Prettier, TypeScript paths, and build caching across multiple packages is notoriously frustrating.

Ahmar Hussain and the Stackaura architecture team built this template to give you the perfect starting framework instantly.

## 📦 What's Inside?

### Apps and Packages

- `apps/web`: a [Next.js](https://nextjs.org/) app showcasing modern Server Components.
- `apps/docs`: a [Nextra](https://nextra.site/) based documentation site.
- `packages/ui`: a stub React component library shared by both `web` and `docs` applications.
- `packages/eslint-config`: `eslint` configurations (includes `eslint-config-next` and `eslint-config-prettier`).
- `packages/typescript-config`: `tsconfig.json`s used throughout the monorepo.

### 🛠️ Tooling

- [Turborepo](https://turbo.build/repo) for blazing-fast cached builds.
- [TypeScript](https://www.typescriptlang.org/) for static type checking.
- [ESLint](https://eslint.org/) for code linting.
- [Prettier](https://prettier.io) for code formatting.
- [pnpm](https://pnpm.io/) as the fast, disk-efficient package manager.
- [Changesets](https://github.com/changesets/changesets) for managing versioning and changelogs.

## 🚀 Getting Started

### 1. Initialize the Monorepo

```bash
git clone https://github.com/RanaAhmar/monorepo-starter.git my-monorepo
cd my-monorepo
pnpm install
```

### 2. Build Everything

```bash
pnpm build
```
Notice how fast subsequent builds are thanks to Turborepo's caching.

### 3. Run Development Servers

```bash
pnpm dev
```
This will start both the `web` application and the `docs` site in parallel.

## 🔄 Automated CI/CD

This repository includes heavily optimized GitHub actions located in `.github/workflows`:
- **CI**: Runs Linting, Typechecking, and Tests on PRs.
- **Release**: Automatically publishes packages to npm using Changesets when merged to main.

## 🤝 Contributing

We actively maintain this template. Have an improvement?
1. Fork the repo.
2. Make your architectural improvements.
3. Submit a PR.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
*Created and maintained by Ahmar Hussain and [Stackaura](https://www.stackaura.com/). Building the future of the web.*
