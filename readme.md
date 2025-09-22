> **ForgeTelemetry is now deprecated.**
> As of **September 22, 2025**, ForgeTelemetry has been deprecated. We've collected enough samples to establish accurate resource averages for BotForge bots. A big thank you to all the developers who volunteered to provide these samples by installing ForgeTelemetry! ❤️

# ForgeTelemetry

ForgeTelemetry was an optional lightweight telemetry module for BotForge bots to report runtime stats, usage metrics, and environment details to a central monitoring API, developers were able to opt-in to help us get accurate information about the average BotForge bot, to be more specific, runtime data (e.g. RAM usage, guild counts, and other non-sensitive metrics) back to us. This data gave us a realistic picture of how the average BotForge bots performed and helped shape future services like ForgeHost.

[![@tryforge/forge.telemetry](https://img.shields.io/github/package-json/v/tryforge/ForgeTelemetry/main?label=@tryforge/forge.telemetry&color=5c16d4)](https://github.com/tryforge/ForgeDB/)
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
```
