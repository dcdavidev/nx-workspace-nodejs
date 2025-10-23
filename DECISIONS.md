# Decisions

With this template repository comes some dev tools already configured.
Here's a brief explanation of the reasons why I chose those tools and why I've configured them in a certain way.

## Monorepo Orchestrator

**nx** is a modern and highly customizable monorepo orchestrator.

- [nx](https://nx.dev)

## Git Hooks

I chose **lefthook** instead of **husky.js** because it is a much more powerful tool for managing git hooks.

- [lefthook](https://lefthook.dev)

## Conventional Commits

Conventional commits are a defacto standard for monorepos. I chose **commitizen** (the `cz` cli), **commitlint**, **@spellbookx/commitlint-config** commitlint config file that enhance and enrich the **cz-git** adapter for **commitizen** and **commitlint**.

- [commitizen](https://commitizen.github.io/cz-cli/)
- [cz-git](https://cz-git.qbb.sh/)
- [commitlint](https://commitlint.js.org/)
- [@spellbookx/commitlint-config](https://github.com/spellbookx/devkit)

## Spelling

**cspell** is a powerful tool that help me avoid typos.

- [cspell](https://cspell.org)

## Linting & Formatting

I chose not to use nx-configured linting and formatting tools because they are outdated.

**editorconfig**, **prettier**, and **eslint** are classics.
**@spellbookx/prettier-config**, **eslint**, and **@spellbookx/eslint-plugin** for a opinionated, clean, documented, and beautiful way of writing files.

- [editorconfig](https://editorconfig.org/)
- [prettier](https://prettier.io)
- [eslint](https://eslint.org)
- [spellbookx/devkit](https://github.com/spellbookx/devkit)

## Test Framework (Unit Tests, E2E)

I chose not to use nx-configured testing tools because they are outdated.

## Building

**webpack** (the **nx** way) and **tsdown** my way.

- [tsdown](https://tsdown.dev/)
