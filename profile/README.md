<p align="center">
  <img width="150" height="150" alt="spraxium-logo" src="https://github.com/user-attachments/assets/2f8e77b8-6234-41c3-98af-8046a37f9279" />
</p>

<p align="center">
  We build open-source tooling for Discord bot developers.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/typescript-5.7-3178c6?style=flat-square" alt="TypeScript" />
  <img src="https://img.shields.io/badge/discord.js-14-5865f2?style=flat-square" alt="discord.js" />
  <img src="https://img.shields.io/badge/license-Apache_2.0-green?style=flat-square" alt="License" />
</p>

---

Our main project is **[Spraxium](https://github.com/spraxium/spraxium)**, a modular TypeScript framework for building production-grade Discord bots. It brings familiar backend patterns like dependency injection, decorator-based routing, and lifecycle hooks to bot development, built on top of discord.js 14.

Each part of the framework is a standalone package. You include only what your project needs and configure everything through a single typed file.

## What we work on

- A framework core with DI, modules, and a command pipeline
- Opt-in packages for HTTP APIs, scheduling, signals, internationalization, and more
- A CLI for scaffolding projects and generating modules
- Documentation and runnable examples for every feature

## Get started

```bash
npx @spraxium/cli new my-bot
```

Documentation and guides at [spraxium.com](https://spraxium.com).

Built by [Spacelaxy](https://github.com/spacelaxy)
