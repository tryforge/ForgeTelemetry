# ForgeTelemetry

Lightweight optional telemetry module for BotForge bots to report runtime stats, usage metrics, and environment details to a central monitoring API.

[![@tryforge/forge.telemetry](https://img.shields.io/github/package-json/v/tryforge/ForgeAPI/main?label=@tryforge/forge.telemetry&color=5c16d4)](https://github.com/tryforge/ForgeDB/)
[![@tryforge/forgescript](https://img.shields.io/github/package-json/v/tryforge/ForgeScript/main?label=@tryforge/forgescript&color=5c16d4)](https://github.com/tryforge/ForgeScript/)
[![Discord](https://img.shields.io/discord/739934735387721768?logo=discord)](https://discord.gg/hcJgjzPvqb)

## How to use

**Download from npm:**

```bash
npm i @tryforge/forge.telemetry
```

**in your client initialization:**

```js
const { ForgeTelemetry } = require("@tryforge/forge.telemetry")

const client = new ForgeClient({
  ...
  extensions: [new ForgeTelemetry()]
})

api.router.load("path")
```